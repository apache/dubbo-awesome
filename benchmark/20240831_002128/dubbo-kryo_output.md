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
# Warmup Iteration   1: 1.685 ops/ms
Iteration   1: 7.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.482 ops/ms


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
# Warmup Iteration   1: 5.692 ops/ms
Iteration   1: 11.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.790 ops/ms


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
# Warmup Iteration   1: 6.075 ops/ms
Iteration   1: 13.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.471 ops/ms


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
# Warmup Iteration   1: 5.387 ops/ms
Iteration   1: 8.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.246 ops/ms


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.087 ms/op
Iteration   1: 2.271 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.271 ms/op


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
# Warmup Iteration   1: 3.086 ±(99.9%) 0.056 ms/op
Iteration   1: 1.783 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.783 ms/op


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
# Warmup Iteration   1: 3.406 ±(99.9%) 0.053 ms/op
Iteration   1: 2.036 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.036 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.849 ±(99.9%) 0.092 ms/op
Iteration   1: 3.562 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.562 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.076 ms/op
Iteration   1: 2.088 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.411 ms/op
                 createUser·p0.50:   1.870 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.871 ms/op
                 createUser·p0.99:   5.527 ms/op
                 createUser·p0.999:  23.799 ms/op
                 createUser·p0.9999: 24.671 ms/op
                 createUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15760
  mean =      2.088 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13370 
    [ 2.500,  5.000) = 2191 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      5.527 ms/op
     p(99.9000) =     23.799 ms/op
     p(99.9900) =     24.671 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 2.819 ±(99.9%) 0.067 ms/op
Iteration   1: 1.897 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.794 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.552 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  19.300 ms/op
                 existUser·p0.9999: 19.462 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16920
  mean =      1.897 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 442 
    [ 1.250,  2.500) = 15437 
    [ 2.500,  3.750) = 805 
    [ 3.750,  5.000) = 141 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.552 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     19.462 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.593 ±(99.9%) 0.127 ms/op
Iteration   1: 2.408 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.452 ms/op
                 getUser·p0.50:   2.253 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  22.060 ms/op
                 getUser·p0.9999: 23.058 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13259
  mean =      2.408 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8876 
    [ 2.500,  5.000) = 4188 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     22.060 ms/op
     p(99.9900) =     23.058 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.103 ms/op
Iteration   1: 3.086 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   2.781 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  8.298 ms/op
                 listUser·p0.9999: 8.404 ms/op
                 listUser·p1.00:   8.405 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10359
  mean =      3.086 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 93 
    [2.000, 2.500) = 2015 
    [2.500, 3.000) = 3895 
    [3.000, 3.500) = 1432 
    [3.500, 4.000) = 1665 
    [4.000, 4.500) = 892 
    [4.500, 5.000) = 161 
    [5.000, 5.500) = 79 
    [5.500, 6.000) = 36 
    [6.000, 6.500) = 35 
    [6.500, 7.000) = 23 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =      8.404 ms/op
     p(99.9990) =      8.405 ms/op
     p(99.9999) =      8.405 ms/op
    p(100.0000) =      8.405 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.482          ops/ms
ClientSimple.existUser                       thrpt         11.790          ops/ms
ClientSimple.getUser                         thrpt         13.471          ops/ms
ClientSimple.listUser                        thrpt          8.246          ops/ms
ClientSimple.createUser                       avgt          2.271           ms/op
ClientSimple.existUser                        avgt          1.783           ms/op
ClientSimple.getUser                          avgt          2.036           ms/op
ClientSimple.listUser                         avgt          3.562           ms/op
ClientSimple.createUser                     sample  15760   2.088 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.411           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.870           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.527           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.799           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.671           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.068           ms/op
ClientSimple.existUser                      sample  16920   1.897 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.560           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.794           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.552           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.776           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.300           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.462           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.530           ms/op
ClientSimple.getUser                        sample  13259   2.408 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.452           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.253           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.138           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.759           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.060           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.058           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.069           ms/op
ClientSimple.listUser                       sample  10359   3.086 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.264           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.781           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.825           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.298           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.404           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.405           ms/op

Benchmark result is saved to 1725063443548.json
