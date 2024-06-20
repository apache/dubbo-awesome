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
# Warmup Iteration   1: 1.588 ops/ms
Iteration   1: 7.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.224 ops/ms


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
# Warmup Iteration   1: 6.296 ops/ms
Iteration   1: 12.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.853 ops/ms


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
# Warmup Iteration   1: 5.277 ops/ms
Iteration   1: 13.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.629 ops/ms


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
# Warmup Iteration   1: 5.328 ops/ms
Iteration   1: 8.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.249 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.070 ms/op
Iteration   1: 2.425 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.425 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.240 ±(99.9%) 0.047 ms/op
Iteration   1: 1.946 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.946 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.111 ±(99.9%) 0.058 ms/op
Iteration   1: 2.059 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.059 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.338 ±(99.9%) 0.080 ms/op
Iteration   1: 3.060 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.060 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.548 ±(99.9%) 0.086 ms/op
Iteration   1: 2.180 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.048 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.728 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  14.746 ms/op
                 createUser·p0.9999: 14.885 ms/op
                 createUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14652
  mean =      2.180 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 12712 
    [ 2.500,  3.750) = 1623 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     14.885 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.183 ±(99.9%) 0.076 ms/op
Iteration   1: 1.954 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   1.903 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.485 ms/op
                 existUser·p0.99:   3.611 ms/op
                 existUser·p0.999:  12.173 ms/op
                 existUser·p0.9999: 12.284 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16364
  mean =      1.954 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 15426 
    [ 2.500,  3.750) = 624 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.485 ms/op
     p(99.0000) =      3.611 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     12.284 ms/op
     p(99.9990) =     12.304 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


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
# Warmup Iteration   1: 3.248 ±(99.9%) 0.077 ms/op
Iteration   1: 1.899 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.359 ms/op
                 getUser·p0.50:   1.761 ms/op
                 getUser·p0.90:   2.318 ms/op
                 getUser·p0.95:   2.494 ms/op
                 getUser·p0.99:   3.129 ms/op
                 getUser·p0.999:  24.805 ms/op
                 getUser·p0.9999: 25.395 ms/op
                 getUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16918
  mean =      1.899 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16088 
    [ 2.500,  5.000) = 762 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.129 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.128 ms/op
Iteration   1: 3.455 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.690 ms/op
                 listUser·p0.50:   3.510 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 9.437 ms/op
                 listUser·p1.00:   9.437 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9261
  mean =      3.455 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 91 
    [ 2.000,  3.000) = 3329 
    [ 3.000,  4.000) = 3423 
    [ 4.000,  5.000) = 2182 
    [ 5.000,  6.000) = 113 
    [ 6.000,  7.000) = 78 
    [ 7.000,  8.000) = 7 
    [ 8.000,  9.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =      9.437 ms/op
     p(99.9990) =      9.437 ms/op
     p(99.9999) =      9.437 ms/op
    p(100.0000) =      9.437 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.224          ops/ms
ClientSimple.existUser                       thrpt         12.853          ops/ms
ClientSimple.getUser                         thrpt         13.629          ops/ms
ClientSimple.listUser                        thrpt          8.249          ops/ms
ClientSimple.createUser                       avgt          2.425           ms/op
ClientSimple.existUser                        avgt          1.946           ms/op
ClientSimple.getUser                          avgt          2.059           ms/op
ClientSimple.listUser                         avgt          3.060           ms/op
ClientSimple.createUser                     sample  14652   2.180 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.569           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.048           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.210           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.746           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.885           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.893           ms/op
ClientSimple.existUser                      sample  16364   1.954 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.604           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.903           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.485           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.611           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.173           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.284           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.304           ms/op
ClientSimple.getUser                        sample  16918   1.899 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.359           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.761           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.318           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.129           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.805           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.395           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.395           ms/op
ClientSimple.listUser                       sample   9261   3.455 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.690           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.510           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.398           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.028           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.437           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.437           ms/op

Benchmark result is saved to 1718842546674.json
