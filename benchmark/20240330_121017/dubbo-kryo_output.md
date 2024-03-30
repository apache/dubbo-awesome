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
# Warmup Iteration   1: 1.710 ops/ms
Iteration   1: 6.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.843 ops/ms


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
# Warmup Iteration   1: 6.413 ops/ms
Iteration   1: 12.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.308 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.567 ops/ms
Iteration   1: 14.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.186 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.464 ops/ms
Iteration   1: 8.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.536 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.668 ±(99.9%) 0.080 ms/op
Iteration   1: 2.198 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.198 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.133 ±(99.9%) 0.055 ms/op
Iteration   1: 1.860 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ±(99.9%) 0.072 ms/op
Iteration   1: 1.934 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.934 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.943 ±(99.9%) 0.075 ms/op
Iteration   1: 3.769 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.769 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.493 ±(99.9%) 0.091 ms/op
Iteration   1: 2.116 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   1.966 ms/op
                 createUser·p0.90:   2.654 ms/op
                 createUser·p0.95:   2.970 ms/op
                 createUser·p0.99:   5.547 ms/op
                 createUser·p0.999:  16.056 ms/op
                 createUser·p0.9999: 16.826 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15082
  mean =      2.116 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 12617 
    [ 2.500,  3.750) = 1993 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      5.547 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     16.826 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.135 ms/op
Iteration   1: 1.699 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   1.589 ms/op
                 existUser·p0.90:   1.952 ms/op
                 existUser·p0.95:   2.154 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 16.244 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18881
  mean =      1.699 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 835 
    [ 1.250,  2.500) = 17552 
    [ 2.500,  3.750) = 237 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 120 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      1.589 ms/op
     p(90.0000) =      1.952 ms/op
     p(95.0000) =      2.154 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     16.244 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.091 ms/op
Iteration   1: 1.996 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   1.921 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   3.177 ms/op
                 getUser·p0.999:  14.025 ms/op
                 getUser·p0.9999: 14.306 ms/op
                 getUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16012
  mean =      1.996 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 183 
    [ 1.250,  2.500) = 13949 
    [ 2.500,  3.750) = 1786 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.177 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     14.306 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.132 ms/op
Iteration   1: 2.970 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.322 ms/op
                 listUser·p0.95:   3.629 ms/op
                 listUser·p0.99:   4.512 ms/op
                 listUser·p0.999:  10.699 ms/op
                 listUser·p0.9999: 10.812 ms/op
                 listUser·p1.00:   10.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10812
  mean =      2.970 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 38 
    [ 2.000,  3.000) = 7499 
    [ 3.000,  4.000) = 3032 
    [ 4.000,  5.000) = 173 
    [ 5.000,  6.000) = 8 
    [ 6.000,  7.000) = 9 
    [ 7.000,  8.000) = 27 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.512 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     10.812 ms/op
     p(99.9990) =     10.813 ms/op
     p(99.9999) =     10.813 ms/op
    p(100.0000) =     10.813 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.843          ops/ms
ClientSimple.existUser                       thrpt         12.308          ops/ms
ClientSimple.getUser                         thrpt         14.186          ops/ms
ClientSimple.listUser                        thrpt          8.536          ops/ms
ClientSimple.createUser                       avgt          2.198           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          1.934           ms/op
ClientSimple.listUser                         avgt          3.769           ms/op
ClientSimple.createUser                     sample  15082   2.116 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.565           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.966           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.970           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.547           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.056           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.826           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.843           ms/op
ClientSimple.existUser                      sample  18881   1.699 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.828           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.589           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.154           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.317           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.631           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.244           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.302           ms/op
ClientSimple.getUser                        sample  16012   1.996 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.645           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.921           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.177           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.025           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.306           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.533           ms/op
ClientSimple.listUser                       sample  10812   2.970 ± 0.018   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.067           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.863           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.322           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.629           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.512           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.699           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.812           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.813           ms/op

Benchmark result is saved to 1711800337342.json
