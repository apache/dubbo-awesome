# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.584 ops/ms
Iteration   1: 6.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.958 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.850 ops/ms
Iteration   1: 11.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.802 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.773 ops/ms
Iteration   1: 11.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.906 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.723 ops/ms
Iteration   1: 8.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.523 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.985 ±(99.9%) 0.068 ms/op
Iteration   1: 2.138 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.138 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.627 ±(99.9%) 0.069 ms/op
Iteration   1: 1.915 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.915 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 2.990 ±(99.9%) 0.053 ms/op
Iteration   1: 2.149 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.149 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.324 ±(99.9%) 0.097 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.073 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.640 ±(99.9%) 0.112 ms/op
Iteration   1: 1.967 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.479 ms/op
                 createUser·p0.50:   1.767 ms/op
                 createUser·p0.90:   2.314 ms/op
                 createUser·p0.95:   2.601 ms/op
                 createUser·p0.99:   6.122 ms/op
                 createUser·p0.999:  25.494 ms/op
                 createUser·p0.9999: 26.222 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16254
  mean =      1.967 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15241 
    [ 2.500,  5.000) = 817 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      6.122 ms/op
     p(99.9000) =     25.494 ms/op
     p(99.9900) =     26.222 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.161 ±(99.9%) 0.083 ms/op
Iteration   1: 1.879 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.906 ms/op
                 existUser·p0.999:  12.272 ms/op
                 existUser·p0.9999: 12.571 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17026
  mean =      1.879 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 15807 
    [ 2.500,  3.750) = 902 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.906 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     12.571 ms/op
     p(99.9990) =     12.583 ms/op
     p(99.9999) =     12.583 ms/op
    p(100.0000) =     12.583 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.349 ±(99.9%) 0.088 ms/op
Iteration   1: 2.129 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.509 ms/op
                 getUser·p0.50:   2.056 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   3.396 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 11.660 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15306
  mean =      2.129 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 181 
    [ 1.250,  2.500) = 12295 
    [ 2.500,  3.750) = 2721 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.396 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     11.660 ms/op
     p(99.9990) =     11.747 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.637 ±(99.9%) 0.152 ms/op
Iteration   1: 3.494 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   6.666 ms/op
                 listUser·p0.999:  11.813 ms/op
                 listUser·p0.9999: 11.878 ms/op
                 listUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9163
  mean =      3.494 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 858 
    [ 2.500,  3.750) = 5234 
    [ 3.750,  5.000) = 2653 
    [ 5.000,  6.250) = 268 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.666 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     11.878 ms/op
     p(99.9990) =     11.878 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.958          ops/ms
ClientSimple.existUser                       thrpt         11.802          ops/ms
ClientSimple.getUser                         thrpt         11.906          ops/ms
ClientSimple.listUser                        thrpt          8.523          ops/ms
ClientSimple.createUser                       avgt          2.138           ms/op
ClientSimple.existUser                        avgt          1.915           ms/op
ClientSimple.getUser                          avgt          2.149           ms/op
ClientSimple.listUser                         avgt          3.073           ms/op
ClientSimple.createUser                     sample  16254   1.967 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.479           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.767           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.314           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.122           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.494           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.222           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.345           ms/op
ClientSimple.existUser                      sample  17026   1.879 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.614           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.747           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.906           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.272           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.571           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.583           ms/op
ClientSimple.getUser                        sample  15306   2.129 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.509           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.056           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.396           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.715           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.660           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.747           ms/op
ClientSimple.listUser                       sample   9163   3.494 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.908           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.502           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.666           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.813           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.878           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.878           ms/op

Benchmark result is saved to 1711066479434.json
