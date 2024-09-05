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
# Warmup Iteration   1: 1.434 ops/ms
Iteration   1: 5.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.986 ops/ms


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
# Warmup Iteration   1: 6.225 ops/ms
Iteration   1: 11.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.835 ops/ms


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
# Warmup Iteration   1: 5.271 ops/ms
Iteration   1: 12.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.688 ops/ms


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
# Warmup Iteration   1: 5.313 ops/ms
Iteration   1: 9.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.320 ops/ms


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.082 ms/op
Iteration   1: 2.299 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.299 ms/op


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
# Warmup Iteration   1: 2.897 ±(99.9%) 0.085 ms/op
Iteration   1: 1.849 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.849 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.062 ms/op
Iteration   1: 2.067 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.067 ms/op


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.081 ms/op
Iteration   1: 3.204 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.204 ms/op


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
# Warmup Iteration   1: 3.511 ±(99.9%) 0.080 ms/op
Iteration   1: 2.095 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   1.853 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.847 ms/op
                 createUser·p0.99:   5.761 ms/op
                 createUser·p0.999:  24.571 ms/op
                 createUser·p0.9999: 27.315 ms/op
                 createUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15569
  mean =      2.095 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14120 
    [ 2.500,  5.000) = 1203 
    [ 5.000,  7.500) = 109 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      5.761 ms/op
     p(99.9000) =     24.571 ms/op
     p(99.9900) =     27.315 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 3.027 ±(99.9%) 0.069 ms/op
Iteration   1: 2.037 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   1.966 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 11.794 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15701
  mean =      2.037 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 265 
    [ 1.250,  2.500) = 13909 
    [ 2.500,  3.750) = 1306 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     11.794 ms/op
     p(99.9990) =     11.878 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


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
# Warmup Iteration   1: 3.295 ±(99.9%) 0.098 ms/op
Iteration   1: 1.945 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   1.833 ms/op
                 getUser·p0.90:   2.441 ms/op
                 getUser·p0.95:   2.630 ms/op
                 getUser·p0.99:   3.355 ms/op
                 getUser·p0.999:  16.179 ms/op
                 getUser·p0.9999: 16.789 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16493
  mean =      1.945 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 271 
    [ 1.250,  2.500) = 14883 
    [ 2.500,  3.750) = 1228 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.355 ms/op
     p(99.9000) =     16.179 ms/op
     p(99.9900) =     16.789 ms/op
     p(99.9990) =     16.810 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.621 ±(99.9%) 0.148 ms/op
Iteration   1: 3.876 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   6.738 ms/op
                 listUser·p0.999:  13.414 ms/op
                 listUser·p0.9999: 13.730 ms/op
                 listUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8248
  mean =      3.876 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 553 
    [ 2.500,  3.750) = 2636 
    [ 3.750,  5.000) = 4688 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.738 ms/op
     p(99.9000) =     13.414 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.986          ops/ms
ClientSimple.existUser                       thrpt         11.835          ops/ms
ClientSimple.getUser                         thrpt         12.688          ops/ms
ClientSimple.listUser                        thrpt          9.320          ops/ms
ClientSimple.createUser                       avgt          2.299           ms/op
ClientSimple.existUser                        avgt          1.849           ms/op
ClientSimple.getUser                          avgt          2.067           ms/op
ClientSimple.listUser                         avgt          3.204           ms/op
ClientSimple.createUser                     sample  15569   2.095 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.746           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.853           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.761           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.571           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.315           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.410           ms/op
ClientSimple.existUser                      sample  15701   2.037 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.571           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.966           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.448           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.289           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.794           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.878           ms/op
ClientSimple.getUser                        sample  16493   1.945 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.824           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.833           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.441           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.355           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.179           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.789           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.810           ms/op
ClientSimple.listUser                       sample   8248   3.876 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.126           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.920           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.738           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.414           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.730           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.730           ms/op

Benchmark result is saved to 1725538042896.json
