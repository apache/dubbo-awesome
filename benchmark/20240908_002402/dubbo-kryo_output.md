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
# Warmup Iteration   1: 1.209 ops/ms
Iteration   1: 5.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.857 ops/ms


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
# Warmup Iteration   1: 5.911 ops/ms
Iteration   1: 12.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.219 ops/ms


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
# Warmup Iteration   1: 5.796 ops/ms
Iteration   1: 12.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.680 ops/ms


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
# Warmup Iteration   1: 5.395 ops/ms
Iteration   1: 7.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.855 ops/ms


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.089 ms/op
Iteration   1: 2.060 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.060 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.044 ms/op
Iteration   1: 1.974 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.496 ±(99.9%) 0.069 ms/op
Iteration   1: 2.022 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.022 ms/op


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.105 ms/op
Iteration   1: 3.259 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.259 ms/op


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
# Warmup Iteration   1: 3.590 ±(99.9%) 0.099 ms/op
Iteration   1: 2.216 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.114 ms/op
                 createUser·p0.90:   2.617 ms/op
                 createUser·p0.95:   2.859 ms/op
                 createUser·p0.99:   5.614 ms/op
                 createUser·p0.999:  15.745 ms/op
                 createUser·p0.9999: 17.251 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14438
  mean =      2.216 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 12254 
    [ 2.500,  3.750) = 1902 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      5.614 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     17.251 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 2.861 ±(99.9%) 0.074 ms/op
Iteration   1: 1.929 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  15.784 ms/op
                 existUser·p0.9999: 16.067 ms/op
                 existUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16591
  mean =      1.929 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 356 
    [ 1.250,  2.500) = 15259 
    [ 2.500,  3.750) = 654 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     15.784 ms/op
     p(99.9900) =     16.067 ms/op
     p(99.9990) =     16.089 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.071 ms/op
Iteration   1: 2.169 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.516 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.635 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   3.749 ms/op
                 getUser·p0.999:  16.548 ms/op
                 getUser·p0.9999: 16.863 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14737
  mean =      2.169 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 12327 
    [ 2.500,  3.750) = 2107 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.635 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      3.749 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     16.863 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.144 ms/op
Iteration   1: 3.583 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.315 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   6.118 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8922
  mean =      3.583 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 785 
    [ 2.500,  3.750) = 4917 
    [ 3.750,  5.000) = 2957 
    [ 5.000,  6.250) = 186 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.315 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.118 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     17.138 ms/op
     p(99.9990) =     17.138 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.857          ops/ms
ClientSimple.existUser                       thrpt         12.219          ops/ms
ClientSimple.getUser                         thrpt         12.680          ops/ms
ClientSimple.listUser                        thrpt          7.855          ops/ms
ClientSimple.createUser                       avgt          2.060           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.022           ms/op
ClientSimple.listUser                         avgt          3.259           ms/op
ClientSimple.createUser                     sample  14438   2.216 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.954           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.114           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.859           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.614           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.745           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.251           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.367           ms/op
ClientSimple.existUser                      sample  16591   1.929 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.741           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.786           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.079           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.784           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.067           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.089           ms/op
ClientSimple.getUser                        sample  14737   2.169 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.516           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.635           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.749           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.548           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.863           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.941           ms/op
ClientSimple.listUser                       sample   8922   3.583 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.006           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.315           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.118           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.974           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.138           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.138           ms/op

Benchmark result is saved to 1725754781522.json
