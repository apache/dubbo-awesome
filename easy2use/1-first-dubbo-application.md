随着 SpringBoot 逐渐成为 Java 应用开发的基础框架，我们不得不思考在微服务流行的当下我们服务间的交互方式该如何选择？而 Dubbo 作为一个服务治理框架又能给我带来哪些便利之处？Dubbo 与 SpringBoot 的集成方式是怎么样的？Dubbo 的使用方式又是怎样？文章篇幅有限，关于服务治理的文章会在后面发出，本章只介绍 RPC 相关部分。

按照微服务架构的设计理念，各个服务都是独立进程部署，各个服务之间通过网络调用的方式来进行通讯。但是直接在代码中嵌入太多的网络交互逻辑会导致业务模型混乱，给项目的后续迭代带来非常大的困扰。因此，引入 RPC 的概念“像调用本地方法一样来调用另外一个服务器上的服务”，RPC 将远程服务伪装成本地方法并通过这个方法的语义来描述远程服务。所以说，在微服务架构中 RPC 是必不可少的一环。

RPC 只是一种设计理念，只要能让客户端像使用本地方法一样去调用服务端，不管使用何种网络协议都可以。换句话说 RPC 是在我们常见的网络协议（HTTP、TCP）之上建立的一种封装，目的是让业务代码对进程间的网络调用零感知。

对Java开发者来说，如果要你做 RPC 框架的选型，你会选择哪个呢？毫无疑问，Dubbo 会是你参考的一个重要选项。Dubbo 作为一个服务治理框架其强大的**服务治理能力**几乎可以涵盖所有常见的服务治理场景，其**微内核**的设计理念也使得对 Dubbo 的定制非常便利。而在 **RPC** 方面，Dubbo 使用起来非常简单，和spring无缝集成且注解驱动式的编程风格非常切合当前开发环境。

接下来进入实践部分，主要讲解 Dubbo 和 spring boot 整合，以及 Dubbo 丰富的 RPC 调用方式。

# SpringBoot 整合 Dubbo
## 项目创建
需要创建 api、consumer、provider 这三个工程，同时 consumer 和 provider 需要依赖 api 工程。具体的代码可以参考 [dubbo-samples-spring-boot](https://github.com/apache/dubbo-samples/tree/master/dubbo-samples-spring-boot) 。（依赖相关问题可以参考该工程）
## 项目启动

1. 运行ProviderApplication的main方法。
2. 运行ConsumerApplication的main方法。

# Dubbo 丰富的调用方式
在我们日常开发过程中很多情况下是同步调用，即要等到方法返回结果再继续执行后续逻辑。可以说同步调用的方式能解决日常开发中80%的问题，但在下面这些场景下同步调用却没法解决问题。

1. 服务提供者的处理事件比较长，导致消费者很多逻辑“卡”住了。
2. 网关服务需要在没有服务契约（即网关服务不依赖提供者的api）的情况下直接调用提供者。
3. 很多场景下我们需要服务端主动推送的功能，比如：消息推送、视频推流等。

问题一，在 Dubbo 中给出的解决方案是**异步调用**。和 JUC 的 Future 功能一样，该方式能让消费者端和提供者端并发的处理。（若是提供者端的处理时间超时则会报错，而且若是提供者端的时间太长使用该方式最终也会导致消费者端“卡”住）。

问题二，在 Dubbo 中给出的解决方案是**泛化调用**。目前已经很多开源网关项目使用该方式来集成，比如：apache/shenyu、apache/apisix等。

问题三，在 Dubbo 中给出的解决方案是**流式调用**。目前流式调用仅3.0以上版本支持，若要使用需要先确认版本是否支持。

## 异步调用示例
异步调用方式有多种，下面只展示其中一种，具体的可以参考[这里](https://dubbo.apache.org/zh/docs3-v2/java-sdk/advanced-features-and-usage/service/async-call/) 。

### 接口定义
```java
import java.util.concurrent.CompletableFuture;

public interface HelloService {

    CompletableFuture<String> asyncHello(String str);
}
```
### 服务端实现
```java
import org.apache.dubbo.config.annotation.DubboService;

import java.util.Date;
import java.util.concurrent.CompletableFuture;


@DubboService
public class HelloServiceImpl implements HelloService{

    @Override
    public CompletableFuture<String> asyncHello(String str) {
        return CompletableFuture.supplyAsync(() -> "Hello " + str + " " + new Date());
    }
}
```
### 客户端调用
```java
@RestController
@RequestMapping("/test")
public class TestController {

    @DubboReference
    private HelloService helloService;

    /**
     * async dubbo invoke
     * TODO continue
     * @return
     */
    @GetMapping("/async")
    public String async(@RequestParam("name") String name) {
        CompletableFuture<String> future = helloService.asyncHello(name);
        try {
            return future.get();
        } catch (Exception e) {
            return "async failed";
        }
    }

}
```
## 泛化调用示例
### 接口定义
```java
public interface HelloService {

    String hello(String str);
}
```
### 服务端实现
```java
import org.apache.dubbo.config.annotation.DubboService;

import java.util.Date;


@DubboService
public class HelloServiceImpl implements HelloService{
    
    @Override
    public String hello(String str) {
        return "Hello " + str + " " + new Date();
    }
}
```
### 客户端调用
```java
@RestController
@RequestMapping("/test")
public class TestController {

    @DubboReference(interfaceClass = HelloService.class)
    private GenericService genericService;

    /**
     * generic dubbo invoke
     * TODO continue
     * @return
     */
    @GetMapping("/generic")
    public String generic() {
        String method = "hello";
        String[] paramTypes = {"java.lang.String"};
        Object[] params = {"Paul"};
        Object o = genericService.$invoke(method, paramTypes, params);
        return o.toString();
    }

}
```

## 流式调用示例
流式调用时需要在api模块依赖protobuf相关的maven插件，可以参考[官方示例](https://github.com/apache/dubbo-samples/tree/master/dubbo-samples-triple) 。
### maven插件
下面部分代码仅做参考。
```xml
<properties>
    <compiler.version>0.0.4.1</compiler.version>
    <source.level>1.8</source.level>
    <target.level>1.8</target.level>
    <maven-compiler-plugin.version>3.10.1</maven-compiler-plugin.version>
    <protoc.version>3.19.4</protoc.version>
    <grpc.version>1.44.1</grpc.version>
</properties>

<build>
    <extensions>
      <extension>
        <groupId>kr.motd.maven</groupId>
        <artifactId>os-maven-plugin</artifactId>
        <version>1.6.1</version>
      </extension>
    </extensions>
    <plugins>
      <plugin>
        <groupId>org.xolstice.maven.plugins</groupId>
        <artifactId>protobuf-maven-plugin</artifactId>
        <version>0.6.1</version>
        <configuration>
          <protocArtifact>com.google.protobuf:protoc:${protoc.version}:exe:${os.detected.classifier}
          </protocArtifact>
          <pluginId>grpc-java</pluginId>
          <pluginArtifact>io.grpc:protoc-gen-grpc-java:${grpc.version}:exe:${os.detected.classifier}
          </pluginArtifact>
          <protocPlugins>
            <protocPlugin>
              <id>dubbo</id>
              <groupId>org.apache.dubbo</groupId>
              <artifactId>dubbo-compiler</artifactId>
              <version>${compiler.version}</version>
              <mainClass>org.apache.dubbo.gen.tri.Dubbo3TripleGenerator</mainClass>
            </protocPlugin>
          </protocPlugins>
        </configuration>
        <executions>
          <execution>
            <goals>
              <goal>compile</goal>
              <goal>test-compile</goal>
              <goal>compile-custom</goal>
              <goal>test-compile-custom</goal>
            </goals>
          </execution>
        </executions>
      </plugin>
      <plugin>
        <groupId>org.apache.maven.plugins</groupId>
        <artifactId>maven-compiler-plugin</artifactId>
        <version>${maven-compiler-plugin.version}</version>
        <configuration>
          <source>${source.level}</source>
          <target>${target.level}</target>
        </configuration>
      </plugin>
    </plugins>
  </build>
```
### proto定义
```protobuf
syntax = "proto3";

option java_multiple_files = true;

package org.apache.dubbo.sample.tri;


// The request message containing the user's name.
message GreeterRequest {
string name = 1;
}

// The response message containing the greetings
message GreeterReply {
string message = 1;
}

service Greeter{

// serverStream
rpc greetServerStream(GreeterRequest) returns (stream GreeterReply);

}

```
### 服务端实现
`GreeterImplBase`是使用maven插件生成的。
```java

import org.apache.dubbo.common.stream.StreamObserver;
import org.apache.dubbo.config.annotation.DubboService;
import org.apache.dubbo.rpc.RpcContext;
import org.apache.dubbo.rpc.protocol.tri.ServerStreamObserver;
import org.apache.dubbo.sample.tri.DubboGreeterTriple.GreeterImplBase;
import org.apache.dubbo.sample.tri.GreeterReply;
import org.apache.dubbo.sample.tri.GreeterRequest;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;

import java.util.HashMap;
import java.util.Map;

@DubboService
public class GreeterImpl extends GreeterImplBase {
    private static final Logger LOGGER = LoggerFactory.getLogger(GreeterImpl.class);

    private final String serverName;
    public static final Map<String, Boolean> cancelResultMap = new HashMap<>();

    public GreeterImpl() {
        this.serverName = "default-server";
    }

    public GreeterImpl(String serverName) {
        this.serverName = serverName;
    }

   
    @Override
    public void greetServerStream(GreeterRequest request,
                                  StreamObserver<GreeterReply> replyStream) {
        for (int i = 0; i < 10; i++) {
            replyStream.onNext(GreeterReply.newBuilder()
                    .setMessage(request.getName() + "--" + i)
                    .build());
        }
        replyStream.onCompleted();
    }
}
```
### 客户端调用
客户端需要新增两个类`GrpcStreamObserverAdapter`和`StdoutStreamObserver`
```java
@RestController
@RequestMapping("/test")
public class TestController {

    @DubboReference
    private Greeter greeter;

        /**
     * stream dubbo invoke
     * TODO continue
     * @return
     */
    @GetMapping("/stream")
    public String stream(HttpServletResponse httpServletResponse) {
        greeter.greetServerStream(GreeterRequest.newBuilder()
                .setName("request")
                .build(), new StdoutStreamObserver<>("stdoutStreamObserver"));
        return "success";
    }
}
```
```java

import org.apache.dubbo.common.stream.StreamObserver;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;

/**
 * @author earthchen
 * @date 2021/9/6
 **/
public class StdoutStreamObserver<T> implements StreamObserver<T>, io.grpc.stub.StreamObserver<T> {

    private static final Logger LOGGER = LoggerFactory.getLogger(StdoutStreamObserver.class);

    private final String name;

    public StdoutStreamObserver(String name) {
        this.name = name;
    }

    @Override
    public void onNext(T data) {
        LOGGER.info("{} stream <- reply:{}", name, data);
    }

    @Override
    public void onError(Throwable throwable) {
        LOGGER.error("{} stream onError", name, throwable);
        throwable.printStackTrace();
    }

    @Override
    public void onCompleted() {
        LOGGER.info("{} stream completed", name);
    }

    public io.grpc.stub.StreamObserver<T> asGrpcObserver() {
        return new GrpcStreamObserverAdapter<>(this);
    }
}
```
```java        
import io.grpc.stub.StreamObserver;

public class GrpcStreamObserverAdapter<T> implements StreamObserver<T> {

    private final org.apache.dubbo.common.stream.StreamObserver<T> delegate;

    public GrpcStreamObserverAdapter(org.apache.dubbo.common.stream.StreamObserver<T> delegate) {
        this.delegate = delegate;
    }

    @Override
    public void onNext(T data) {
        delegate.onNext(data);
    }

    @Override
    public void onError(Throwable throwable) {
        delegate.onError(throwable);
    }

    @Override
    public void onCompleted() {
        delegate.onCompleted();
    }
}
```
