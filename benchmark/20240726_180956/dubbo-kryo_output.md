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
# Warmup Iteration   1: 1.861 ops/ms
Iteration   1: 6.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.691 ops/ms


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
# Warmup Iteration   1: 6.440 ops/ms
Iteration   1: 11.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.509 ops/ms


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
# Warmup Iteration   1: 5.462 ops/ms
Iteration   1: 13.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.436 ops/ms


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
# Warmup Iteration   1: 5.131 ops/ms
Iteration   1: 8.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.080 ops/ms


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.071 ms/op
Iteration   1: 2.096 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.096 ms/op


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.058 ms/op
Iteration   1: 1.937 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.937 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.054 ms/op
Iteration   1: 2.063 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.063 ms/op


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.094 ms/op
Iteration   1: 3.491 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.491 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.102 ms/op
Iteration   1: 2.251 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.322 ms/op
                 createUser·p0.50:   2.030 ms/op
                 createUser·p0.90:   2.650 ms/op
                 createUser·p0.95:   3.234 ms/op
                 createUser·p0.99:   9.075 ms/op
                 createUser·p0.999:  17.590 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14210
  mean =      2.251 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 228 
    [ 1.250,  2.500) = 11730 
    [ 2.500,  3.750) = 1771 
    [ 3.750,  5.000) = 180 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.322 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      3.234 ms/op
     p(99.0000) =      9.075 ms/op
     p(99.9000) =     17.590 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.029 ±(99.9%) 0.074 ms/op
Iteration   1: 2.100 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.023 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   4.710 ms/op
                 existUser·p0.999:  12.882 ms/op
                 existUser·p0.9999: 13.613 ms/op
                 existUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15249
  mean =      2.100 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 182 
    [ 1.250,  2.500) = 13102 
    [ 2.500,  3.750) = 1743 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =     12.882 ms/op
     p(99.9900) =     13.613 ms/op
     p(99.9990) =     13.648 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.115 ms/op
Iteration   1: 1.944 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   1.823 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.658 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 13.002 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16470
  mean =      1.944 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 15148 
    [ 2.500,  3.750) = 993 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      4.084 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     13.002 ms/op
     p(99.9990) =     13.140 ms/op
     p(99.9999) =     13.140 ms/op
    p(100.0000) =     13.140 ms/op


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
# Warmup Iteration   1: 5.221 ±(99.9%) 0.166 ms/op
Iteration   1: 3.503 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.420 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.518 ms/op
                 listUser·p0.999:  11.698 ms/op
                 listUser·p0.9999: 12.878 ms/op
                 listUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9132
  mean =      3.503 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 496 
    [ 2.500,  3.750) = 5643 
    [ 3.750,  5.000) = 2669 
    [ 5.000,  6.250) = 195 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.518 ms/op
     p(99.9000) =     11.698 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.691          ops/ms
ClientSimple.existUser                       thrpt         11.509          ops/ms
ClientSimple.getUser                         thrpt         13.436          ops/ms
ClientSimple.listUser                        thrpt          8.080          ops/ms
ClientSimple.createUser                       avgt          2.096           ms/op
ClientSimple.existUser                        avgt          1.937           ms/op
ClientSimple.getUser                          avgt          2.063           ms/op
ClientSimple.listUser                         avgt          3.491           ms/op
ClientSimple.createUser                     sample  14210   2.251 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.322           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.030           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.234           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.075           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.590           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.317           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.317           ms/op
ClientSimple.existUser                      sample  15249   2.100 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.602           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.023           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.798           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.710           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.882           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.613           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.648           ms/op
ClientSimple.getUser                        sample  16470   1.944 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.719           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.823           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.084           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.895           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.002           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.140           ms/op
ClientSimple.listUser                       sample   9132   3.503 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.210           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.420           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.518           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.698           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.878           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.878           ms/op

Benchmark result is saved to 1722017127496.json
