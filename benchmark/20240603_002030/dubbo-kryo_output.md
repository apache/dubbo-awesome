# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.719 ops/ms
Iteration   1: 6.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.500 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.823 ops/ms
Iteration   1: 11.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.283 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.569 ops/ms
Iteration   1: 13.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.327 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.007 ops/ms
Iteration   1: 8.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.778 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.073 ms/op
Iteration   1: 2.706 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.706 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.876 ±(99.9%) 0.048 ms/op
Iteration   1: 1.780 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.780 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.490 ±(99.9%) 0.061 ms/op
Iteration   1: 2.139 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ±(99.9%) 0.100 ms/op
Iteration   1: 3.460 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ±(99.9%) 0.098 ms/op
Iteration   1: 2.450 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   2.236 ms/op
                 createUser·p0.90:   2.769 ms/op
                 createUser·p0.95:   3.120 ms/op
                 createUser·p0.99:   9.071 ms/op
                 createUser·p0.999:  35.583 ms/op
                 createUser·p0.9999: 36.267 ms/op
                 createUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13045
  mean =      2.450 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9872 
    [ 2.500,  5.000) = 2878 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.236 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.120 ms/op
     p(99.0000) =      9.071 ms/op
     p(99.9000) =     35.583 ms/op
     p(99.9900) =     36.267 ms/op
     p(99.9990) =     36.307 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.908 ±(99.9%) 0.071 ms/op
Iteration   1: 1.978 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   1.872 ms/op
                 existUser·p0.90:   2.391 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   4.971 ms/op
                 existUser·p0.999:  25.388 ms/op
                 existUser·p0.9999: 26.121 ms/op
                 existUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16212
  mean =      1.978 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15155 
    [ 2.500,  5.000) = 901 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.391 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      4.971 ms/op
     p(99.9000) =     25.388 ms/op
     p(99.9900) =     26.121 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.340 ±(99.9%) 0.095 ms/op
Iteration   1: 2.068 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.675 ms/op
                 getUser·p0.99:   3.878 ms/op
                 getUser·p0.999:  16.262 ms/op
                 getUser·p0.9999: 21.105 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15456
  mean =      2.068 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13777 
    [ 2.500,  5.000) = 1592 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.878 ms/op
     p(99.9000) =     16.262 ms/op
     p(99.9900) =     21.105 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.458 ±(99.9%) 0.163 ms/op
Iteration   1: 3.461 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.672 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.583 ms/op
                 listUser·p0.999:  20.498 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9226
  mean =      3.461 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1066 
    [ 2.500,  5.000) = 7777 
    [ 5.000,  7.500) = 289 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.672 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.583 ms/op
     p(99.9000) =     20.498 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.500          ops/ms
ClientSimple.existUser                       thrpt         11.283          ops/ms
ClientSimple.getUser                         thrpt         13.327          ops/ms
ClientSimple.listUser                        thrpt          8.778          ops/ms
ClientSimple.createUser                       avgt          2.706           ms/op
ClientSimple.existUser                        avgt          1.780           ms/op
ClientSimple.getUser                          avgt          2.139           ms/op
ClientSimple.listUser                         avgt          3.460           ms/op
ClientSimple.createUser                     sample  13045   2.450 ± 0.056   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.621           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.236           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.120           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.071           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.583           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.267           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.307           ms/op
ClientSimple.existUser                      sample  16212   1.978 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.578           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.872           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.391           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.971           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.388           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.121           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.182           ms/op
ClientSimple.getUser                        sample  15456   2.068 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.676           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.878           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.262           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.105           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.266           ms/op
ClientSimple.listUser                       sample   9226   3.461 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.143           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.672           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.956           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.583           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.498           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.496           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.496           ms/op

Benchmark result is saved to 1717373774316.json
