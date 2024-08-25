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
# Warmup Iteration   1: 1.815 ops/ms
Iteration   1: 6.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.539 ops/ms


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
# Warmup Iteration   1: 5.615 ops/ms
Iteration   1: 12.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.113 ops/ms


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
# Warmup Iteration   1: 4.389 ops/ms
Iteration   1: 11.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.849 ops/ms


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
# Warmup Iteration   1: 5.290 ops/ms
Iteration   1: 8.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.977 ops/ms


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.084 ms/op
Iteration   1: 2.163 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.163 ms/op


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
# Warmup Iteration   1: 2.996 ±(99.9%) 0.046 ms/op
Iteration   1: 1.859 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.859 ms/op


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
# Warmup Iteration   1: 3.452 ±(99.9%) 0.061 ms/op
Iteration   1: 2.236 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.236 ms/op


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.113 ms/op
Iteration   1: 3.262 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.262 ms/op


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.178 ms/op
Iteration   1: 2.288 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.863 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  47.645 ms/op
                 createUser·p0.9999: 48.379 ms/op
                 createUser·p1.00:   48.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13959
  mean =      2.288 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13711 
    [ 5.000, 10.000) = 152 
    [10.000, 15.000) = 28 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     47.645 ms/op
     p(99.9900) =     48.379 ms/op
     p(99.9990) =     48.431 ms/op
     p(99.9999) =     48.431 ms/op
    p(100.0000) =     48.431 ms/op


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.182 ms/op
Iteration   1: 1.821 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   1.663 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   4.115 ms/op
                 existUser·p0.999:  17.826 ms/op
                 existUser·p0.9999: 18.161 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17563
  mean =      1.821 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1142 
    [ 1.250,  2.500) = 15421 
    [ 2.500,  3.750) = 762 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      4.115 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     18.161 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.102 ms/op
Iteration   1: 2.069 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   1.920 ms/op
                 getUser·p0.90:   2.552 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  11.878 ms/op
                 getUser·p0.9999: 12.246 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15708
  mean =      2.069 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 13881 
    [ 2.500,  3.750) = 1565 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.920 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     12.246 ms/op
     p(99.9990) =     12.255 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


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
# Warmup Iteration   1: 4.630 ±(99.9%) 0.143 ms/op
Iteration   1: 3.365 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.715 ms/op
                 listUser·p0.50:   3.297 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  11.608 ms/op
                 listUser·p0.9999: 12.108 ms/op
                 listUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9509
  mean =      3.365 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2561 
    [ 2.500,  3.750) = 3711 
    [ 3.750,  5.000) = 2768 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     11.608 ms/op
     p(99.9900) =     12.108 ms/op
     p(99.9990) =     12.108 ms/op
     p(99.9999) =     12.108 ms/op
    p(100.0000) =     12.108 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.539          ops/ms
ClientSimple.existUser                       thrpt         12.113          ops/ms
ClientSimple.getUser                         thrpt         11.849          ops/ms
ClientSimple.listUser                        thrpt          8.977          ops/ms
ClientSimple.createUser                       avgt          2.163           ms/op
ClientSimple.existUser                        avgt          1.859           ms/op
ClientSimple.getUser                          avgt          2.236           ms/op
ClientSimple.listUser                         avgt          3.262           ms/op
ClientSimple.createUser                     sample  13959   2.288 ± 0.068   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.680           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.269           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.037           ms/op
ClientSimple.createUser:createUser·p0.999   sample         47.645           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         48.379           ms/op
ClientSimple.createUser:createUser·p1.00    sample         48.431           ms/op
ClientSimple.existUser                      sample  17563   1.821 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.543           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.663           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.115           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.826           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.161           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.186           ms/op
ClientSimple.getUser                        sample  15708   2.069 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.564           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.920           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.552           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.669           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.878           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.246           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.255           ms/op
ClientSimple.listUser                       sample   9509   3.365 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.715           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.297           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.973           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.791           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.608           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.108           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.108           ms/op

Benchmark result is saved to 1724587573794.json
