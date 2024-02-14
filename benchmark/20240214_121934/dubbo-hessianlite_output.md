# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.201 ops/ms
Iteration   1: 5.892 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.892 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.617 ops/ms
Iteration   1: 14.544 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.544 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.519 ops/ms
Iteration   1: 8.597 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.597 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.978 ops/ms
Iteration   1: 3.471 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.471 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.700 ±(99.9%) 0.080 ms/op
Iteration   1: 3.196 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.196 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.098 ±(99.9%) 0.037 ms/op
Iteration   1: 1.820 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.820 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ±(99.9%) 0.060 ms/op
Iteration   1: 3.093 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.473 ±(99.9%) 0.235 ms/op
Iteration   1: 10.004 ±(99.9%) 0.107 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.004 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.256 ±(99.9%) 0.113 ms/op
Iteration   1: 2.930 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   8.319 ms/op
                 createUser·p0.999:  11.984 ms/op
                 createUser·p0.9999: 14.098 ms/op
                 createUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10910
  mean =      2.930 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 3407 
    [ 2.500,  3.750) = 6374 
    [ 3.750,  5.000) = 819 
    [ 5.000,  6.250) = 126 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      2.683 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      8.319 ms/op
     p(99.9000) =     11.984 ms/op
     p(99.9900) =     14.098 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.948 ±(99.9%) 0.073 ms/op
Iteration   1: 1.635 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   1.491 ms/op
                 existUser·p0.90:   2.154 ms/op
                 existUser·p0.95:   2.400 ms/op
                 existUser·p0.99:   2.949 ms/op
                 existUser·p0.999:  17.072 ms/op
                 existUser·p0.9999: 17.371 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19598
  mean =      1.635 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2042 
    [ 1.250,  2.500) = 16835 
    [ 2.500,  3.750) = 676 
    [ 3.750,  5.000) = 13 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      1.491 ms/op
     p(90.0000) =      2.154 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      2.949 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     17.371 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.837 ±(99.9%) 0.137 ms/op
Iteration   1: 3.079 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  6.611 ms/op
                 getUser·p0.9999: 7.771 ms/op
                 getUser·p1.00:   7.782 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10394
  mean =      3.079 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 29 
    [1.500, 2.000) = 203 
    [2.000, 2.500) = 1493 
    [2.500, 3.000) = 3164 
    [3.000, 3.500) = 3493 
    [3.500, 4.000) = 1368 
    [4.000, 4.500) = 368 
    [4.500, 5.000) = 108 
    [5.000, 5.500) = 82 
    [5.500, 6.000) = 43 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 28 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      6.611 ms/op
     p(99.9900) =      7.771 ms/op
     p(99.9990) =      7.782 ms/op
     p(99.9999) =      7.782 ms/op
    p(100.0000) =      7.782 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.884 ±(99.9%) 0.478 ms/op
Iteration   1: 8.530 ±(99.9%) 0.146 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   8.200 ms/op
                 listUser·p0.90:   11.665 ms/op
                 listUser·p0.95:   13.025 ms/op
                 listUser·p0.99:   16.685 ms/op
                 listUser·p0.999:  28.885 ms/op
                 listUser·p0.9999: 32.080 ms/op
                 listUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3746
  mean =      8.530 ±(99.9%) 0.146 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 216 
    [ 5.000,  7.500) = 1171 
    [ 7.500, 10.000) = 1467 
    [10.000, 12.500) = 646 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      8.200 ms/op
     p(90.0000) =     11.665 ms/op
     p(95.0000) =     13.025 ms/op
     p(99.0000) =     16.685 ms/op
     p(99.9000) =     28.885 ms/op
     p(99.9900) =     32.080 ms/op
     p(99.9990) =     32.080 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.892          ops/ms
Client.existUser                       thrpt         14.544          ops/ms
Client.getUser                         thrpt          8.597          ops/ms
Client.listUser                        thrpt          3.471          ops/ms
Client.createUser                       avgt          3.196           ms/op
Client.existUser                        avgt          1.820           ms/op
Client.getUser                          avgt          3.093           ms/op
Client.listUser                         avgt         10.004           ms/op
Client.createUser                     sample  10910   2.930 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          0.984           ms/op
Client.createUser:createUser·p0.50    sample          2.683           ms/op
Client.createUser:createUser·p0.90    sample          3.760           ms/op
Client.createUser:createUser·p0.95    sample          4.227           ms/op
Client.createUser:createUser·p0.99    sample          8.319           ms/op
Client.createUser:createUser·p0.999   sample         11.984           ms/op
Client.createUser:createUser·p0.9999  sample         14.098           ms/op
Client.createUser:createUser·p1.00    sample         14.107           ms/op
Client.existUser                      sample  19598   1.635 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.669           ms/op
Client.existUser:existUser·p0.50      sample          1.491           ms/op
Client.existUser:existUser·p0.90      sample          2.154           ms/op
Client.existUser:existUser·p0.95      sample          2.400           ms/op
Client.existUser:existUser·p0.99      sample          2.949           ms/op
Client.existUser:existUser·p0.999     sample         17.072           ms/op
Client.existUser:existUser·p0.9999    sample         17.371           ms/op
Client.existUser:existUser·p1.00      sample         17.465           ms/op
Client.getUser                        sample  10394   3.079 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.969           ms/op
Client.getUser:getUser·p0.50          sample          3.052           ms/op
Client.getUser:getUser·p0.90          sample          3.822           ms/op
Client.getUser:getUser·p0.95          sample          4.108           ms/op
Client.getUser:getUser·p0.99          sample          5.341           ms/op
Client.getUser:getUser·p0.999         sample          6.611           ms/op
Client.getUser:getUser·p0.9999        sample          7.771           ms/op
Client.getUser:getUser·p1.00          sample          7.782           ms/op
Client.listUser                       sample   3746   8.530 ± 0.146   ms/op
Client.listUser:listUser·p0.00        sample          1.868           ms/op
Client.listUser:listUser·p0.50        sample          8.200           ms/op
Client.listUser:listUser·p0.90        sample         11.665           ms/op
Client.listUser:listUser·p0.95        sample         13.025           ms/op
Client.listUser:listUser·p0.99        sample         16.685           ms/op
Client.listUser:listUser·p0.999       sample         28.885           ms/op
Client.listUser:listUser·p0.9999      sample         32.080           ms/op
Client.listUser:listUser·p1.00        sample         32.080           ms/op
