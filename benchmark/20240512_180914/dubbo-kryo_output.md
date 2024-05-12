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
# Warmup Iteration   1: 1.859 ops/ms
Iteration   1: 7.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.354 ops/ms


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
# Warmup Iteration   1: 6.248 ops/ms
Iteration   1: 12.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.088 ops/ms


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
# Warmup Iteration   1: 6.051 ops/ms
Iteration   1: 14.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.110 ops/ms


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
# Warmup Iteration   1: 4.810 ops/ms
Iteration   1: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.467 ops/ms


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.073 ms/op
Iteration   1: 1.963 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.963 ms/op


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
# Warmup Iteration   1: 3.047 ±(99.9%) 0.046 ms/op
Iteration   1: 1.979 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.979 ms/op


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
# Warmup Iteration   1: 3.249 ±(99.9%) 0.053 ms/op
Iteration   1: 2.295 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.295 ms/op


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
# Warmup Iteration   1: 4.404 ±(99.9%) 0.098 ms/op
Iteration   1: 3.235 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.235 ms/op


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.114 ms/op
Iteration   1: 2.740 ±(99.9%) 0.064 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   2.462 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   16.220 ms/op
                 createUser·p0.999:  23.101 ms/op
                 createUser·p0.9999: 23.796 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11605
  mean =      2.740 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6105 
    [ 2.500,  5.000) = 5093 
    [ 5.000,  7.500) = 177 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =     16.220 ms/op
     p(99.9000) =     23.101 ms/op
     p(99.9900) =     23.796 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 2.946 ±(99.9%) 0.070 ms/op
Iteration   1: 1.954 ±(99.9%) 0.043 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   1.776 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   3.297 ms/op
                 existUser·p0.999:  36.110 ms/op
                 existUser·p0.9999: 36.747 ms/op
                 existUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16404
  mean =      1.954 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15041 
    [ 2.500,  5.000) = 1234 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.297 ms/op
     p(99.9000) =     36.110 ms/op
     p(99.9900) =     36.747 ms/op
     p(99.9990) =     36.831 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.095 ms/op
Iteration   1: 2.078 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.472 ms/op
                 getUser·p0.50:   1.933 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 20.709 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15604
  mean =      2.078 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13747 
    [ 2.500,  5.000) = 1677 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.126 ms/op
Iteration   1: 3.183 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.292 ms/op
                 listUser·p0.99:   5.371 ms/op
                 listUser·p0.999:  7.569 ms/op
                 listUser·p0.9999: 7.946 ms/op
                 listUser·p1.00:   7.946 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10040
  mean =      3.183 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 7 
    [1.500, 2.000) = 69 
    [2.000, 2.500) = 688 
    [2.500, 3.000) = 4305 
    [3.000, 3.500) = 2358 
    [3.500, 4.000) = 1444 
    [4.000, 4.500) = 882 
    [4.500, 5.000) = 127 
    [5.000, 5.500) = 97 
    [5.500, 6.000) = 11 
    [6.000, 6.500) = 11 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.292 ms/op
     p(99.0000) =      5.371 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =      7.946 ms/op
     p(99.9990) =      7.946 ms/op
     p(99.9999) =      7.946 ms/op
    p(100.0000) =      7.946 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.354          ops/ms
ClientSimple.existUser                       thrpt         12.088          ops/ms
ClientSimple.getUser                         thrpt         14.110          ops/ms
ClientSimple.listUser                        thrpt          8.467          ops/ms
ClientSimple.createUser                       avgt          1.963           ms/op
ClientSimple.existUser                        avgt          1.979           ms/op
ClientSimple.getUser                          avgt          2.295           ms/op
ClientSimple.listUser                         avgt          3.235           ms/op
ClientSimple.createUser                     sample  11605   2.740 ± 0.064   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.602           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.285           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.211           ms/op
ClientSimple.createUser:createUser·p0.99    sample         16.220           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.101           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.796           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.822           ms/op
ClientSimple.existUser                      sample  16404   1.954 ± 0.043   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.591           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.776           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.297           ms/op
ClientSimple.existUser:existUser·p0.999     sample         36.110           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         36.747           ms/op
ClientSimple.existUser:existUser·p1.00      sample         36.831           ms/op
ClientSimple.getUser                        sample  15604   2.078 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.472           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.933           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.743           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.152           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.709           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.709           ms/op
ClientSimple.listUser                       sample  10040   3.183 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.245           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.994           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.292           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.371           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.569           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.946           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.946           ms/op

Benchmark result is saved to 1715537096549.json
