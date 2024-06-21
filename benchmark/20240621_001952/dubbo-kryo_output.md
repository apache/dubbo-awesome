# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.799 ops/ms
Iteration   1: 7.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.421 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.636 ops/ms
Iteration   1: 12.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.445 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.854 ops/ms
Iteration   1: 11.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.446 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.032 ops/ms
Iteration   1: 8.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.314 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ±(99.9%) 0.101 ms/op
Iteration   1: 2.121 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.121 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.566 ±(99.9%) 0.065 ms/op
Iteration   1: 1.970 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.970 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.449 ±(99.9%) 0.063 ms/op
Iteration   1: 1.983 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.071 ±(99.9%) 0.127 ms/op
Iteration   1: 3.349 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.349 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.889 ±(99.9%) 0.113 ms/op
Iteration   1: 2.202 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   1.991 ms/op
                 createUser·p0.90:   2.540 ms/op
                 createUser·p0.95:   2.793 ms/op
                 createUser·p0.99:   10.511 ms/op
                 createUser·p0.999:  19.759 ms/op
                 createUser·p0.9999: 21.258 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14523
  mean =      2.202 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12810 
    [ 2.500,  5.000) = 1517 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =     10.511 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     21.258 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.159 ±(99.9%) 0.075 ms/op
Iteration   1: 1.874 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   1.790 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.425 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  11.436 ms/op
                 existUser·p0.9999: 11.794 ms/op
                 existUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17098
  mean =      1.874 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 632 
    [ 1.250,  2.500) = 15787 
    [ 2.500,  3.750) = 410 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 162 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.425 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     11.794 ms/op
     p(99.9990) =     11.829 ms/op
     p(99.9999) =     11.829 ms/op
    p(100.0000) =     11.829 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.478 ±(99.9%) 0.116 ms/op
Iteration   1: 1.798 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   1.667 ms/op
                 getUser·p0.90:   2.273 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   3.228 ms/op
                 getUser·p0.999:  12.894 ms/op
                 getUser·p0.9999: 12.980 ms/op
                 getUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17798
  mean =      1.798 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 16490 
    [ 2.500,  3.750) = 1078 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.228 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     12.980 ms/op
     p(99.9990) =     12.993 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.797 ±(99.9%) 0.138 ms/op
Iteration   1: 3.537 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.432 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.343 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9033
  mean =      3.537 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 790 
    [ 2.500,  3.750) = 5370 
    [ 3.750,  5.000) = 2423 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.343 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.421          ops/ms
ClientSimple.existUser                       thrpt         12.445          ops/ms
ClientSimple.getUser                         thrpt         11.446          ops/ms
ClientSimple.listUser                        thrpt          8.314          ops/ms
ClientSimple.createUser                       avgt          2.121           ms/op
ClientSimple.existUser                        avgt          1.970           ms/op
ClientSimple.getUser                          avgt          1.983           ms/op
ClientSimple.listUser                         avgt          3.349           ms/op
ClientSimple.createUser                     sample  14523   2.202 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.598           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.991           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.540           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.511           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.759           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.258           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.332           ms/op
ClientSimple.existUser                      sample  17098   1.874 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.558           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.790           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.530           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.436           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.794           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.829           ms/op
ClientSimple.getUser                        sample  17798   1.798 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.768           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.667           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.273           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.228           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.894           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.980           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.993           ms/op
ClientSimple.listUser                       sample   9033   3.537 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.202           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.432           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.343           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.712           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.777           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.777           ms/op

Benchmark result is saved to 1718928942031.json
