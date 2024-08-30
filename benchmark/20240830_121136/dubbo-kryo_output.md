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
# Warmup Iteration   1: 1.007 ops/ms
Iteration   1: 5.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.309 ops/ms


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
# Warmup Iteration   1: 5.466 ops/ms
Iteration   1: 10.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.207 ops/ms


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
# Warmup Iteration   1: 5.529 ops/ms
Iteration   1: 10.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.448 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ops/ms
Iteration   1: 7.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.693 ops/ms


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.071 ms/op
Iteration   1: 2.179 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.179 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.049 ms/op
Iteration   1: 1.883 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.883 ms/op


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
# Warmup Iteration   1: 3.123 ±(99.9%) 0.068 ms/op
Iteration   1: 1.757 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.757 ms/op


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
# Warmup Iteration   1: 4.625 ±(99.9%) 0.107 ms/op
Iteration   1: 3.719 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.719 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.086 ms/op
Iteration   1: 2.026 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   1.872 ms/op
                 createUser·p0.90:   2.476 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  19.141 ms/op
                 createUser·p0.9999: 20.723 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15923
  mean =      2.026 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14389 
    [ 2.500,  5.000) = 1298 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.476 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     19.141 ms/op
     p(99.9900) =     20.723 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 3.086 ±(99.9%) 0.061 ms/op
Iteration   1: 2.015 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   1.982 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   3.577 ms/op
                 existUser·p0.999:  12.241 ms/op
                 existUser·p0.9999: 12.517 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15869
  mean =      2.015 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 300 
    [ 1.250,  2.500) = 14607 
    [ 2.500,  3.750) = 840 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 2 
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
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.577 ms/op
     p(99.9000) =     12.241 ms/op
     p(99.9900) =     12.517 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.071 ms/op
Iteration   1: 2.049 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.542 ms/op
                 getUser·p0.50:   1.894 ms/op
                 getUser·p0.90:   2.494 ms/op
                 getUser·p0.95:   2.723 ms/op
                 getUser·p0.99:   3.603 ms/op
                 getUser·p0.999:  31.425 ms/op
                 getUser·p0.9999: 31.668 ms/op
                 getUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15642
  mean =      2.049 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14116 
    [ 2.500,  5.000) = 1447 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.723 ms/op
     p(99.0000) =      3.603 ms/op
     p(99.9000) =     31.425 ms/op
     p(99.9900) =     31.668 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 5.017 ±(99.9%) 0.259 ms/op
Iteration   1: 3.580 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.103 ms/op
                 listUser·p0.999:  10.453 ms/op
                 listUser·p0.9999: 10.502 ms/op
                 listUser·p1.00:   10.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8926
  mean =      3.580 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 69 
    [ 2.000,  3.000) = 1048 
    [ 3.000,  4.000) = 6443 
    [ 4.000,  5.000) = 1152 
    [ 5.000,  6.000) = 98 
    [ 6.000,  7.000) = 57 
    [ 7.000,  8.000) = 26 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     10.502 ms/op
     p(99.9990) =     10.502 ms/op
     p(99.9999) =     10.502 ms/op
    p(100.0000) =     10.502 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.309          ops/ms
ClientSimple.existUser                       thrpt         10.207          ops/ms
ClientSimple.getUser                         thrpt         10.448          ops/ms
ClientSimple.listUser                        thrpt          7.693          ops/ms
ClientSimple.createUser                       avgt          2.179           ms/op
ClientSimple.existUser                        avgt          1.883           ms/op
ClientSimple.getUser                          avgt          1.757           ms/op
ClientSimple.listUser                         avgt          3.719           ms/op
ClientSimple.createUser                     sample  15923   2.026 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.658           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.872           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.476           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.800           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.141           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.723           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.742           ms/op
ClientSimple.existUser                      sample  15869   2.015 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.591           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.982           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.577           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.241           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.517           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.517           ms/op
ClientSimple.getUser                        sample  15642   2.049 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.542           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.894           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.723           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.603           ms/op
ClientSimple.getUser:getUser·p0.999         sample         31.425           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         31.668           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.687           ms/op
ClientSimple.listUser                       sample   8926   3.580 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.278           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.103           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.453           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.502           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.502           ms/op

Benchmark result is saved to 1725019621614.json
