# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.480 ops/ms
Iteration   1: 7.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.139 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.208 ops/ms
Iteration   1: 12.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.034 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.974 ops/ms
Iteration   1: 11.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.972 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.289 ops/ms
Iteration   1: 8.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.985 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.103 ms/op
Iteration   1: 2.128 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.128 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.350 ±(99.9%) 0.059 ms/op
Iteration   1: 2.030 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.030 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.866 ±(99.9%) 0.079 ms/op
Iteration   1: 2.091 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.091 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.559 ±(99.9%) 0.090 ms/op
Iteration   1: 3.605 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.605 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.482 ±(99.9%) 0.086 ms/op
Iteration   1: 2.335 ±(99.9%) 0.071 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  48.562 ms/op
                 createUser·p0.9999: 61.116 ms/op
                 createUser·p1.00:   68.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13689
  mean =      2.335 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13464 
    [ 5.000, 10.000) = 124 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 46 
    [20.000, 25.000) = 16 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 27 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     48.562 ms/op
     p(99.9900) =     61.116 ms/op
     p(99.9990) =     68.420 ms/op
     p(99.9999) =     68.420 ms/op
    p(100.0000) =     68.420 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.862 ±(99.9%) 0.078 ms/op
Iteration   1: 1.923 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   4.551 ms/op
                 existUser·p0.999:  13.603 ms/op
                 existUser·p0.9999: 13.844 ms/op
                 existUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16715
  mean =      1.923 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 308 
    [ 1.250,  2.500) = 15405 
    [ 2.500,  3.750) = 750 
    [ 3.750,  5.000) = 152 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      4.551 ms/op
     p(99.9000) =     13.603 ms/op
     p(99.9900) =     13.844 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ±(99.9%) 0.198 ms/op
Iteration   1: 2.010 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   1.833 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   5.042 ms/op
                 getUser·p0.999:  16.384 ms/op
                 getUser·p0.9999: 17.412 ms/op
                 getUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16157
  mean =      2.010 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 14941 
    [ 2.500,  3.750) = 906 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      5.042 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     17.412 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.446 ±(99.9%) 0.148 ms/op
Iteration   1: 3.653 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.884 ms/op
                 listUser·p0.999:  21.808 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8873
  mean =      3.653 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 375 
    [ 2.500,  5.000) = 8296 
    [ 5.000,  7.500) = 157 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.884 ms/op
     p(99.9000) =     21.808 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.139          ops/ms
ClientSimple.existUser                       thrpt         12.034          ops/ms
ClientSimple.getUser                         thrpt         11.972          ops/ms
ClientSimple.listUser                        thrpt          8.985          ops/ms
ClientSimple.createUser                       avgt          2.128           ms/op
ClientSimple.existUser                        avgt          2.030           ms/op
ClientSimple.getUser                          avgt          2.091           ms/op
ClientSimple.listUser                         avgt          3.605           ms/op
ClientSimple.createUser                     sample  13689   2.335 ± 0.071   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.591           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.210           ms/op
ClientSimple.createUser:createUser·p0.999   sample         48.562           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         61.116           ms/op
ClientSimple.createUser:createUser·p1.00    sample         68.420           ms/op
ClientSimple.existUser                      sample  16715   1.923 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.504           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.551           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.603           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.844           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.844           ms/op
ClientSimple.getUser                        sample  16157   2.010 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.544           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.833           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.042           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.384           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.412           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.433           ms/op
ClientSimple.listUser                       sample   8873   3.653 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.898           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.666           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.884           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.808           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.675           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.675           ms/op

Benchmark result is saved to 1722794696087.json
