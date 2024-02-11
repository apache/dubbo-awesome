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
# Warmup Iteration   1: 1.981 ops/ms
Iteration   1: 5.099 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.099 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.115 ops/ms
Iteration   1: 11.424 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.424 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.265 ops/ms
Iteration   1: 8.609 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.609 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.302 ops/ms
Iteration   1: 3.675 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.675 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.947 ±(99.9%) 0.061 ms/op
Iteration   1: 3.132 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.132 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.034 ms/op
Iteration   1: 2.062 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.062 ms/op


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
# Warmup Iteration   1: 4.962 ±(99.9%) 0.050 ms/op
Iteration   1: 3.334 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.334 ms/op


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
# Warmup Iteration   1: 11.556 ±(99.9%) 0.228 ms/op
Iteration   1: 8.120 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.120 ms/op


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
# Warmup Iteration   1: 6.203 ±(99.9%) 0.283 ms/op
Iteration   1: 3.195 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.159 ms/op
                 createUser·p0.999:  6.308 ms/op
                 createUser·p0.9999: 8.478 ms/op
                 createUser·p1.00:   8.487 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10219
  mean =      3.195 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 26 
    [1.500, 2.000) = 95 
    [2.000, 2.500) = 1259 
    [2.500, 3.000) = 3266 
    [3.000, 3.500) = 2635 
    [3.500, 4.000) = 1561 
    [4.000, 4.500) = 885 
    [4.500, 5.000) = 329 
    [5.000, 5.500) = 99 
    [5.500, 6.000) = 27 
    [6.000, 6.500) = 28 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.159 ms/op
     p(99.9000) =      6.308 ms/op
     p(99.9900) =      8.478 ms/op
     p(99.9990) =      8.487 ms/op
     p(99.9999) =      8.487 ms/op
    p(100.0000) =      8.487 ms/op


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
# Warmup Iteration   1: 3.418 ±(99.9%) 0.076 ms/op
Iteration   1: 2.054 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   1.939 ms/op
                 existUser·p0.90:   2.716 ms/op
                 existUser·p0.95:   2.970 ms/op
                 existUser·p0.99:   3.778 ms/op
                 existUser·p0.999:  5.443 ms/op
                 existUser·p0.9999: 6.033 ms/op
                 existUser·p1.00:   6.644 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15558
  mean =      2.054 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 37 
    [1.000, 1.500) = 1132 
    [1.500, 2.000) = 7467 
    [2.000, 2.500) = 4290 
    [2.500, 3.000) = 1894 
    [3.000, 3.500) = 486 
    [3.500, 4.000) = 129 
    [4.000, 4.500) = 26 
    [4.500, 5.000) = 28 
    [5.000, 5.500) = 62 
    [5.500, 6.000) = 6 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      3.778 ms/op
     p(99.9000) =      5.443 ms/op
     p(99.9900) =      6.033 ms/op
     p(99.9990) =      6.644 ms/op
     p(99.9999) =      6.644 ms/op
    p(100.0000) =      6.644 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.561 ±(99.9%) 0.111 ms/op
Iteration   1: 2.898 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   2.802 ms/op
                 getUser·p0.90:   3.787 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  6.421 ms/op
                 getUser·p0.9999: 8.112 ms/op
                 getUser·p1.00:   8.126 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11034
  mean =      2.898 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 14 
    [1.500, 2.000) = 518 
    [2.000, 2.500) = 3607 
    [2.500, 3.000) = 2315 
    [3.000, 3.500) = 2628 
    [3.500, 4.000) = 1277 
    [4.000, 4.500) = 370 
    [4.500, 5.000) = 146 
    [5.000, 5.500) = 56 
    [5.500, 6.000) = 64 
    [6.000, 6.500) = 31 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      2.802 ms/op
     p(90.0000) =      3.787 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      6.421 ms/op
     p(99.9900) =      8.112 ms/op
     p(99.9990) =      8.126 ms/op
     p(99.9999) =      8.126 ms/op
    p(100.0000) =      8.126 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.687 ±(99.9%) 0.440 ms/op
Iteration   1: 9.030 ±(99.9%) 0.154 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   8.684 ms/op
                 listUser·p0.90:   11.796 ms/op
                 listUser·p0.95:   13.435 ms/op
                 listUser·p0.99:   16.446 ms/op
                 listUser·p0.999:  33.755 ms/op
                 listUser·p0.9999: 36.241 ms/op
                 listUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3539
  mean =      9.030 ±(99.9%) 0.154 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 77 
    [ 5.000,  7.500) = 918 
    [ 7.500, 10.000) = 1491 
    [10.000, 12.500) = 798 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      8.684 ms/op
     p(90.0000) =     11.796 ms/op
     p(95.0000) =     13.435 ms/op
     p(99.0000) =     16.446 ms/op
     p(99.9000) =     33.755 ms/op
     p(99.9900) =     36.241 ms/op
     p(99.9990) =     36.241 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.099          ops/ms
Client.existUser                       thrpt         11.424          ops/ms
Client.getUser                         thrpt          8.609          ops/ms
Client.listUser                        thrpt          3.675          ops/ms
Client.createUser                       avgt          3.132           ms/op
Client.existUser                        avgt          2.062           ms/op
Client.getUser                          avgt          3.334           ms/op
Client.listUser                         avgt          8.120           ms/op
Client.createUser                     sample  10219   3.195 ± 0.023   ms/op
Client.createUser:createUser·p0.00    sample          0.779           ms/op
Client.createUser:createUser·p0.50    sample          3.064           ms/op
Client.createUser:createUser·p0.90    sample          4.211           ms/op
Client.createUser:createUser·p0.95    sample          4.489           ms/op
Client.createUser:createUser·p0.99    sample          5.159           ms/op
Client.createUser:createUser·p0.999   sample          6.308           ms/op
Client.createUser:createUser·p0.9999  sample          8.478           ms/op
Client.createUser:createUser·p1.00    sample          8.487           ms/op
Client.existUser                      sample  15558   2.054 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.623           ms/op
Client.existUser:existUser·p0.50      sample          1.939           ms/op
Client.existUser:existUser·p0.90      sample          2.716           ms/op
Client.existUser:existUser·p0.95      sample          2.970           ms/op
Client.existUser:existUser·p0.99      sample          3.778           ms/op
Client.existUser:existUser·p0.999     sample          5.443           ms/op
Client.existUser:existUser·p0.9999    sample          6.033           ms/op
Client.existUser:existUser·p1.00      sample          6.644           ms/op
Client.getUser                        sample  11034   2.898 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          1.031           ms/op
Client.getUser:getUser·p0.50          sample          2.802           ms/op
Client.getUser:getUser·p0.90          sample          3.787           ms/op
Client.getUser:getUser·p0.95          sample          4.145           ms/op
Client.getUser:getUser·p0.99          sample          5.431           ms/op
Client.getUser:getUser·p0.999         sample          6.421           ms/op
Client.getUser:getUser·p0.9999        sample          8.112           ms/op
Client.getUser:getUser·p1.00          sample          8.126           ms/op
Client.listUser                       sample   3539   9.030 ± 0.154   ms/op
Client.listUser:listUser·p0.00        sample          1.386           ms/op
Client.listUser:listUser·p0.50        sample          8.684           ms/op
Client.listUser:listUser·p0.90        sample         11.796           ms/op
Client.listUser:listUser·p0.95        sample         13.435           ms/op
Client.listUser:listUser·p0.99        sample         16.446           ms/op
Client.listUser:listUser·p0.999       sample         33.755           ms/op
Client.listUser:listUser·p0.9999      sample         36.241           ms/op
Client.listUser:listUser·p1.00        sample         36.241           ms/op
