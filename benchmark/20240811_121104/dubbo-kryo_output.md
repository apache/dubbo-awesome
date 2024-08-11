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
# Warmup Iteration   1: 1.557 ops/ms
Iteration   1: 6.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.388 ops/ms


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
# Warmup Iteration   1: 5.980 ops/ms
Iteration   1: 14.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.051 ops/ms


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
# Warmup Iteration   1: 4.979 ops/ms
Iteration   1: 13.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.520 ops/ms


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
# Warmup Iteration   1: 5.634 ops/ms
Iteration   1: 8.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.869 ops/ms


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.071 ms/op
Iteration   1: 2.250 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.250 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.054 ms/op
Iteration   1: 1.894 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.894 ms/op


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
# Warmup Iteration   1: 3.037 ±(99.9%) 0.061 ms/op
Iteration   1: 2.069 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.069 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.070 ms/op
Iteration   1: 3.511 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.511 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.085 ms/op
Iteration   1: 2.350 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.514 ms/op
                 createUser·p0.50:   2.286 ms/op
                 createUser·p0.90:   2.907 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.914 ms/op
                 createUser·p0.999:  16.325 ms/op
                 createUser·p0.9999: 16.450 ms/op
                 createUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13602
  mean =      2.350 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 8024 
    [ 2.500,  3.750) = 5353 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      2.286 ms/op
     p(90.0000) =      2.907 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.914 ms/op
     p(99.9000) =     16.325 ms/op
     p(99.9900) =     16.450 ms/op
     p(99.9990) =     16.450 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 2.962 ±(99.9%) 0.071 ms/op
Iteration   1: 1.828 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.400 ms/op
                 existUser·p0.99:   3.467 ms/op
                 existUser·p0.999:  11.709 ms/op
                 existUser·p0.9999: 12.222 ms/op
                 existUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17659
  mean =      1.828 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 267 
    [ 1.250,  2.500) = 16793 
    [ 2.500,  3.750) = 430 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 118 
    [ 6.250,  7.500) = 1 
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
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      3.467 ms/op
     p(99.9000) =     11.709 ms/op
     p(99.9900) =     12.222 ms/op
     p(99.9990) =     12.435 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


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
# Warmup Iteration   1: 3.268 ±(99.9%) 0.081 ms/op
Iteration   1: 2.370 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.347 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.383 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  12.911 ms/op
                 getUser·p0.9999: 13.160 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13500
  mean =      2.370 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 8460 
    [ 2.500,  3.750) = 4613 
    [ 3.750,  5.000) = 163 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.347 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.383 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     13.160 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 4.545 ±(99.9%) 0.137 ms/op
Iteration   1: 2.988 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.685 ms/op
                 listUser·p0.50:   2.757 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.180 ms/op
                 listUser·p0.99:   5.337 ms/op
                 listUser·p0.999:  9.164 ms/op
                 listUser·p0.9999: 11.360 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10688
  mean =      2.988 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 2838 
    [ 2.500,  3.750) = 6254 
    [ 3.750,  5.000) = 1438 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.757 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.180 ms/op
     p(99.0000) =      5.337 ms/op
     p(99.9000) =      9.164 ms/op
     p(99.9900) =     11.360 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.388          ops/ms
ClientSimple.existUser                       thrpt         14.051          ops/ms
ClientSimple.getUser                         thrpt         13.520          ops/ms
ClientSimple.listUser                        thrpt          8.869          ops/ms
ClientSimple.createUser                       avgt          2.250           ms/op
ClientSimple.existUser                        avgt          1.894           ms/op
ClientSimple.getUser                          avgt          2.069           ms/op
ClientSimple.listUser                         avgt          3.511           ms/op
ClientSimple.createUser                     sample  13602   2.350 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.514           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.286           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.907           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.068           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.914           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.325           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.450           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.450           ms/op
ClientSimple.existUser                      sample  17659   1.828 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.767           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.204           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.467           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.709           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.222           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.435           ms/op
ClientSimple.getUser                        sample  13500   2.370 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.710           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.347           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.383           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.743           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.911           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.160           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.189           ms/op
ClientSimple.listUser                       sample  10688   2.988 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.685           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.757           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.850           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.180           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.337           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.164           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.360           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.518           ms/op

Benchmark result is saved to 1723377998898.json
