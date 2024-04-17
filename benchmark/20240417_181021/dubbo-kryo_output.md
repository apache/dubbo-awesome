# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.784 ops/ms
Iteration   1: 6.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.813 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.875 ops/ms
Iteration   1: 14.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.062 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.635 ops/ms
Iteration   1: 13.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.445 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.402 ops/ms
Iteration   1: 9.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.162 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.832 ±(99.9%) 0.072 ms/op
Iteration   1: 1.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.969 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.038 ±(99.9%) 0.052 ms/op
Iteration   1: 2.081 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.123 ±(99.9%) 0.051 ms/op
Iteration   1: 2.112 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.112 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.105 ms/op
Iteration   1: 3.132 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ±(99.9%) 0.120 ms/op
Iteration   1: 2.131 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   1.901 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   2.949 ms/op
                 createUser·p0.99:   5.463 ms/op
                 createUser·p0.999:  18.841 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15007
  mean =      2.131 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 12602 
    [ 2.500,  3.750) = 2131 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      5.463 ms/op
     p(99.9000) =     18.841 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.022 ±(99.9%) 0.075 ms/op
Iteration   1: 1.692 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   1.618 ms/op
                 existUser·p0.90:   1.862 ms/op
                 existUser·p0.95:   2.093 ms/op
                 existUser·p0.99:   2.626 ms/op
                 existUser·p0.999:  16.762 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18903
  mean =      1.692 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 301 
    [ 1.250,  2.500) = 18349 
    [ 2.500,  3.750) = 172 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      1.618 ms/op
     p(90.0000) =      1.862 ms/op
     p(95.0000) =      2.093 ms/op
     p(99.0000) =      2.626 ms/op
     p(99.9000) =     16.762 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     16.810 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.111 ±(99.9%) 0.079 ms/op
Iteration   1: 1.972 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.331 ms/op
                 getUser·p0.95:   2.507 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  12.710 ms/op
                 getUser·p0.9999: 12.835 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16212
  mean =      1.972 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 15296 
    [ 2.500,  3.750) = 652 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =     12.710 ms/op
     p(99.9900) =     12.835 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.509 ±(99.9%) 0.129 ms/op
Iteration   1: 3.936 ±(99.9%) 0.184 ms/op
                 listUser·p0.00:   0.659 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   9.902 ms/op
                 listUser·p0.999:  86.097 ms/op
                 listUser·p0.9999: 90.440 ms/op
                 listUser·p1.00:   90.440 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8132
  mean =      3.936 ±(99.9%) 0.184 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 8053 
    [ 10.000,  20.000) = 9 
    [ 20.000,  30.000) = 37 
    [ 30.000,  40.000) = 1 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 0 
    [ 60.000,  70.000) = 8 
    [ 70.000,  80.000) = 5 
    [ 80.000,  90.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      9.902 ms/op
     p(99.9000) =     86.097 ms/op
     p(99.9900) =     90.440 ms/op
     p(99.9990) =     90.440 ms/op
     p(99.9999) =     90.440 ms/op
    p(100.0000) =     90.440 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.813          ops/ms
ClientSimple.existUser                       thrpt         14.062          ops/ms
ClientSimple.getUser                         thrpt         13.445          ops/ms
ClientSimple.listUser                        thrpt          9.162          ops/ms
ClientSimple.createUser                       avgt          1.969           ms/op
ClientSimple.existUser                        avgt          2.081           ms/op
ClientSimple.getUser                          avgt          2.112           ms/op
ClientSimple.listUser                         avgt          3.132           ms/op
ClientSimple.createUser                     sample  15007   2.131 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.911           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.901           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.949           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.463           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.841           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.956           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.956           ms/op
ClientSimple.existUser                      sample  18903   1.692 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.559           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.618           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.862           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.093           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.762           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.810           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.810           ms/op
ClientSimple.getUser                        sample  16212   1.972 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.730           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.331           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.252           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.710           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.835           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.845           ms/op
ClientSimple.listUser                       sample   8132   3.936 ± 0.184   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.659           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.902           ms/op
ClientSimple.listUser:listUser·p0.999       sample         86.097           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         90.440           ms/op
ClientSimple.listUser:listUser·p1.00        sample         90.440           ms/op

Benchmark result is saved to 1713377153102.json
