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
# Warmup Iteration   1: 1.912 ops/ms
Iteration   1: 7.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.631 ops/ms


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
# Warmup Iteration   1: 6.106 ops/ms
Iteration   1: 14.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.077 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.597 ops/ms
Iteration   1: 14.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.048 ops/ms


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
# Warmup Iteration   1: 5.212 ops/ms
Iteration   1: 9.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.127 ops/ms


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.069 ms/op
Iteration   1: 2.189 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.189 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.094 ms/op
Iteration   1: 1.978 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.978 ms/op


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.078 ms/op
Iteration   1: 1.990 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.990 ms/op


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.096 ms/op
Iteration   1: 3.570 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.570 ms/op


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
# Warmup Iteration   1: 3.276 ±(99.9%) 0.080 ms/op
Iteration   1: 2.465 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.314 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  19.073 ms/op
                 createUser·p0.9999: 19.589 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12942
  mean =      2.465 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 8263 
    [ 2.500,  3.750) = 4267 
    [ 3.750,  5.000) = 184 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      2.314 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     19.073 ms/op
     p(99.9900) =     19.589 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 3.007 ±(99.9%) 0.072 ms/op
Iteration   1: 1.918 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   1.825 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   4.433 ms/op
                 existUser·p0.999:  13.965 ms/op
                 existUser·p0.9999: 14.347 ms/op
                 existUser·p1.00:   14.434 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16670
  mean =      1.918 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 645 
    [ 1.250,  2.500) = 15004 
    [ 2.500,  3.750) = 836 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      4.433 ms/op
     p(99.9000) =     13.965 ms/op
     p(99.9900) =     14.347 ms/op
     p(99.9990) =     14.434 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.761 ±(99.9%) 0.098 ms/op
Iteration   1: 2.003 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  22.970 ms/op
                 getUser·p0.9999: 23.331 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15963
  mean =      2.003 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14477 
    [ 2.500,  5.000) = 1323 
    [ 5.000,  7.500) = 67 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.104 ms/op
Iteration   1: 3.696 ±(99.9%) 0.077 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   10.503 ms/op
                 listUser·p0.999:  32.447 ms/op
                 listUser·p0.9999: 37.814 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8792
  mean =      3.696 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 633 
    [ 2.500,  5.000) = 7861 
    [ 5.000,  7.500) = 197 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =     10.503 ms/op
     p(99.9000) =     32.447 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.631          ops/ms
ClientSimple.existUser                       thrpt         14.077          ops/ms
ClientSimple.getUser                         thrpt         14.048          ops/ms
ClientSimple.listUser                        thrpt          9.127          ops/ms
ClientSimple.createUser                       avgt          2.189           ms/op
ClientSimple.existUser                        avgt          1.978           ms/op
ClientSimple.getUser                          avgt          1.990           ms/op
ClientSimple.listUser                         avgt          3.570           ms/op
ClientSimple.createUser                     sample  12942   2.465 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.977           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.314           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.265           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.193           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.073           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.589           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.628           ms/op
ClientSimple.existUser                      sample  16670   1.918 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.572           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.825           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.433           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.965           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.347           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.434           ms/op
ClientSimple.getUser                        sample  15963   2.003 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.564           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.464           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.970           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.331           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.331           ms/op
ClientSimple.listUser                       sample   8792   3.696 ± 0.077   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.006           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.490           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.503           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.447           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         37.814           ms/op
ClientSimple.listUser:listUser·p1.00        sample         37.814           ms/op

Benchmark result is saved to 1722212242396.json
