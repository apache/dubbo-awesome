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
# Warmup Iteration   1: 1.668 ops/ms
Iteration   1: 6.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.029 ops/ms


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
# Warmup Iteration   1: 5.669 ops/ms
Iteration   1: 12.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.063 ops/ms


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
# Warmup Iteration   1: 4.999 ops/ms
Iteration   1: 12.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.433 ops/ms


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
# Warmup Iteration   1: 4.559 ops/ms
Iteration   1: 7.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.749 ops/ms


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.077 ms/op
Iteration   1: 1.983 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.983 ms/op


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
# Warmup Iteration   1: 3.456 ±(99.9%) 0.051 ms/op
Iteration   1: 2.003 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.003 ms/op


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
# Warmup Iteration   1: 3.540 ±(99.9%) 0.058 ms/op
Iteration   1: 2.229 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.229 ms/op


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
# Warmup Iteration   1: 5.038 ±(99.9%) 0.141 ms/op
Iteration   1: 3.422 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.422 ms/op


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.149 ms/op
Iteration   1: 2.386 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.892 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   4.454 ms/op
                 createUser·p0.999:  28.397 ms/op
                 createUser·p0.9999: 28.967 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13386
  mean =      2.386 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9114 
    [ 2.500,  5.000) = 4141 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      4.454 ms/op
     p(99.9000) =     28.397 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 3.018 ±(99.9%) 0.063 ms/op
Iteration   1: 2.032 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.451 ms/op
                 existUser·p0.50:   1.665 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  15.794 ms/op
                 existUser·p0.9999: 15.958 ms/op
                 existUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15895
  mean =      2.032 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 610 
    [ 1.250,  2.500) = 10983 
    [ 2.500,  3.750) = 3926 
    [ 3.750,  5.000) = 285 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     15.958 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.078 ms/op
Iteration   1: 2.115 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.814 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  25.359 ms/op
                 getUser·p0.9999: 25.870 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15115
  mean =      2.115 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11731 
    [ 2.500,  5.000) = 3261 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     25.359 ms/op
     p(99.9900) =     25.870 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.119 ms/op
Iteration   1: 3.934 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  8.552 ms/op
                 listUser·p0.9999: 11.223 ms/op
                 listUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8128
  mean =      3.934 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 38 
    [ 2.000,  3.000) = 588 
    [ 3.000,  4.000) = 4374 
    [ 4.000,  5.000) = 2570 
    [ 5.000,  6.000) = 272 
    [ 6.000,  7.000) = 187 
    [ 7.000,  8.000) = 62 
    [ 8.000,  9.000) = 34 
    [ 9.000, 10.000) = 0 
    [10.000, 11.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     11.223 ms/op
     p(99.9990) =     11.223 ms/op
     p(99.9999) =     11.223 ms/op
    p(100.0000) =     11.223 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.029          ops/ms
ClientSimple.existUser                       thrpt         12.063          ops/ms
ClientSimple.getUser                         thrpt         12.433          ops/ms
ClientSimple.listUser                        thrpt          7.749          ops/ms
ClientSimple.createUser                       avgt          1.983           ms/op
ClientSimple.existUser                        avgt          2.003           ms/op
ClientSimple.getUser                          avgt          2.229           ms/op
ClientSimple.listUser                         avgt          3.422           ms/op
ClientSimple.createUser                     sample  13386   2.386 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.842           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.892           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.052           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.454           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.397           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.967           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.967           ms/op
ClientSimple.existUser                      sample  15895   2.032 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.451           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.665           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.892           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.224           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.211           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.794           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.958           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.958           ms/op
ClientSimple.getUser                        sample  15115   2.115 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.656           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.072           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.440           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.359           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.870           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.887           ms/op
ClientSimple.listUser                       sample   8128   3.934 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.423           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.842           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.374           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.315           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.552           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.223           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.223           ms/op

Benchmark result is saved to 1723874719754.json
