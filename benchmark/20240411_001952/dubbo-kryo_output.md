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
# Warmup Iteration   1: 2.006 ops/ms
Iteration   1: 7.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.756 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.553 ops/ms
Iteration   1: 14.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.069 ops/ms


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
# Warmup Iteration   1: 6.162 ops/ms
Iteration   1: 13.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.971 ops/ms


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
# Warmup Iteration   1: 5.025 ops/ms
Iteration   1: 9.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.464 ops/ms


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.052 ms/op
Iteration   1: 1.874 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.874 ms/op


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
# Warmup Iteration   1: 2.791 ±(99.9%) 0.053 ms/op
Iteration   1: 1.730 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.730 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.058 ms/op
Iteration   1: 2.022 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.022 ms/op


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.098 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.147 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.111 ms/op
Iteration   1: 2.159 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   1.921 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.802 ms/op
                 createUser·p0.99:   8.126 ms/op
                 createUser·p0.999:  36.909 ms/op
                 createUser·p0.9999: 38.994 ms/op
                 createUser·p1.00:   38.994 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14813
  mean =      2.159 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12877 
    [ 2.500,  5.000) = 1668 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     36.909 ms/op
     p(99.9900) =     38.994 ms/op
     p(99.9990) =     38.994 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.814 ±(99.9%) 0.060 ms/op
Iteration   1: 1.807 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.171 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   3.162 ms/op
                 existUser·p0.999:  14.685 ms/op
                 existUser·p0.9999: 15.158 ms/op
                 existUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17697
  mean =      1.807 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 873 
    [ 1.250,  2.500) = 16229 
    [ 2.500,  3.750) = 471 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      3.162 ms/op
     p(99.9000) =     14.685 ms/op
     p(99.9900) =     15.158 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.406 ±(99.9%) 0.079 ms/op
Iteration   1: 1.809 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.511 ms/op
                 getUser·p0.50:   1.628 ms/op
                 getUser·p0.90:   2.134 ms/op
                 getUser·p0.95:   2.367 ms/op
                 getUser·p0.99:   2.843 ms/op
                 getUser·p0.999:  46.399 ms/op
                 getUser·p0.9999: 47.659 ms/op
                 getUser·p1.00:   48.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17657
  mean =      1.809 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 17580 
    [ 5.000, 10.000) = 5 
    [10.000, 15.000) = 39 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.367 ms/op
     p(99.0000) =      2.843 ms/op
     p(99.9000) =     46.399 ms/op
     p(99.9900) =     47.659 ms/op
     p(99.9990) =     48.562 ms/op
     p(99.9999) =     48.562 ms/op
    p(100.0000) =     48.562 ms/op


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.145 ms/op
Iteration   1: 3.074 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.377 ms/op
                 listUser·p0.999:  10.094 ms/op
                 listUser·p0.9999: 10.236 ms/op
                 listUser·p1.00:   10.240 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10462
  mean =      3.074 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 78 
    [ 2.000,  3.000) = 5531 
    [ 3.000,  4.000) = 4051 
    [ 4.000,  5.000) = 622 
    [ 5.000,  6.000) = 108 
    [ 6.000,  7.000) = 29 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.377 ms/op
     p(99.9000) =     10.094 ms/op
     p(99.9900) =     10.236 ms/op
     p(99.9990) =     10.240 ms/op
     p(99.9999) =     10.240 ms/op
    p(100.0000) =     10.240 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.756          ops/ms
ClientSimple.existUser                       thrpt         14.069          ops/ms
ClientSimple.getUser                         thrpt         13.971          ops/ms
ClientSimple.listUser                        thrpt          9.464          ops/ms
ClientSimple.createUser                       avgt          1.874           ms/op
ClientSimple.existUser                        avgt          1.730           ms/op
ClientSimple.getUser                          avgt          2.022           ms/op
ClientSimple.listUser                         avgt          3.147           ms/op
ClientSimple.createUser                     sample  14813   2.159 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.812           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.921           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.126           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.909           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.994           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.994           ms/op
ClientSimple.existUser                      sample  17697   1.807 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.579           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.729           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.162           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.685           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.158           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.221           ms/op
ClientSimple.getUser                        sample  17657   1.809 ± 0.046   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.511           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.628           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.134           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.367           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.843           ms/op
ClientSimple.getUser:getUser·p0.999         sample         46.399           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         47.659           ms/op
ClientSimple.getUser:getUser·p1.00          sample         48.562           ms/op
ClientSimple.listUser                       sample  10462   3.074 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.976           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.884           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.842           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.377           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.094           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.236           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.240           ms/op

Benchmark result is saved to 1712794526570.json
