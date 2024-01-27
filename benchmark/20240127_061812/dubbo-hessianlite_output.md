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
# Warmup Iteration   1: 2.145 ops/ms
Iteration   1: 6.561 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.561 ops/ms


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
# Warmup Iteration   1: 6.037 ops/ms
Iteration   1: 13.472 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.472 ops/ms


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
# Warmup Iteration   1: 4.148 ops/ms
Iteration   1: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.984 ops/ms


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
# Warmup Iteration   1: 1.784 ops/ms
Iteration   1: 3.372 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.372 ops/ms


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
# Warmup Iteration   1: 5.744 ±(99.9%) 0.092 ms/op
Iteration   1: 3.033 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.033 ms/op


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
# Warmup Iteration   1: 3.069 ±(99.9%) 0.038 ms/op
Iteration   1: 1.855 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.855 ms/op


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
# Warmup Iteration   1: 4.589 ±(99.9%) 0.057 ms/op
Iteration   1: 3.234 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.234 ms/op


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
# Warmup Iteration   1: 12.088 ±(99.9%) 0.243 ms/op
Iteration   1: 8.668 ±(99.9%) 0.124 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.668 ms/op


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
# Warmup Iteration   1: 4.881 ±(99.9%) 0.100 ms/op
Iteration   1: 3.175 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  16.024 ms/op
                 createUser·p0.9999: 16.138 ms/op
                 createUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10335
  mean =      3.175 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1810 
    [ 2.500,  3.750) = 6943 
    [ 3.750,  5.000) = 1397 
    [ 5.000,  6.250) = 115 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     16.138 ms/op
     p(99.9990) =     16.138 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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
# Warmup Iteration   1: 3.090 ±(99.9%) 0.065 ms/op
Iteration   1: 1.969 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   1.827 ms/op
                 existUser·p0.90:   2.548 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  21.292 ms/op
                 existUser·p0.9999: 21.607 ms/op
                 existUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16229
  mean =      1.969 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14363 
    [ 2.500,  5.000) = 1793 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =     21.292 ms/op
     p(99.9900) =     21.607 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.693 ±(99.9%) 0.113 ms/op
Iteration   1: 2.997 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.173 ms/op
                 getUser·p0.99:   5.981 ms/op
                 getUser·p0.999:  7.435 ms/op
                 getUser·p0.9999: 8.797 ms/op
                 getUser·p1.00:   8.798 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10683
  mean =      2.997 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 67 
    [1.500, 2.000) = 758 
    [2.000, 2.500) = 1977 
    [2.500, 3.000) = 2821 
    [3.000, 3.500) = 2838 
    [3.500, 4.000) = 1418 
    [4.000, 4.500) = 442 
    [4.500, 5.000) = 104 
    [5.000, 5.500) = 120 
    [5.500, 6.000) = 29 
    [6.000, 6.500) = 59 
    [6.500, 7.000) = 25 
    [7.000, 7.500) = 13 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.173 ms/op
     p(99.0000) =      5.981 ms/op
     p(99.9000) =      7.435 ms/op
     p(99.9900) =      8.797 ms/op
     p(99.9990) =      8.798 ms/op
     p(99.9999) =      8.798 ms/op
    p(100.0000) =      8.798 ms/op


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
# Warmup Iteration   1: 13.556 ±(99.9%) 0.489 ms/op
Iteration   1: 8.135 ±(99.9%) 0.124 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   7.733 ms/op
                 listUser·p0.90:   10.666 ms/op
                 listUser·p0.95:   12.494 ms/op
                 listUser·p0.99:   17.817 ms/op
                 listUser·p0.999:  21.927 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3927
  mean =      8.135 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 107 
    [ 5.000,  7.500) = 1620 
    [ 7.500, 10.000) = 1645 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.310 ms/op
     p(50.0000) =      7.733 ms/op
     p(90.0000) =     10.666 ms/op
     p(95.0000) =     12.494 ms/op
     p(99.0000) =     17.817 ms/op
     p(99.9000) =     21.927 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.561          ops/ms
Client.existUser                       thrpt         13.472          ops/ms
Client.getUser                         thrpt          7.984          ops/ms
Client.listUser                        thrpt          3.372          ops/ms
Client.createUser                       avgt          3.033           ms/op
Client.existUser                        avgt          1.855           ms/op
Client.getUser                          avgt          3.234           ms/op
Client.listUser                         avgt          8.668           ms/op
Client.createUser                     sample  10335   3.175 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.094           ms/op
Client.createUser:createUser·p0.50    sample          3.097           ms/op
Client.createUser:createUser·p0.90    sample          3.891           ms/op
Client.createUser:createUser·p0.95    sample          4.219           ms/op
Client.createUser:createUser·p0.99    sample          5.612           ms/op
Client.createUser:createUser·p0.999   sample         16.024           ms/op
Client.createUser:createUser·p0.9999  sample         16.138           ms/op
Client.createUser:createUser·p1.00    sample         16.138           ms/op
Client.existUser                      sample  16229   1.969 ± 0.025   ms/op
Client.existUser:existUser·p0.00      sample          0.749           ms/op
Client.existUser:existUser·p0.50      sample          1.827           ms/op
Client.existUser:existUser·p0.90      sample          2.548           ms/op
Client.existUser:existUser·p0.95      sample          2.777           ms/op
Client.existUser:existUser·p0.99      sample          3.539           ms/op
Client.existUser:existUser·p0.999     sample         21.292           ms/op
Client.existUser:existUser·p0.9999    sample         21.607           ms/op
Client.existUser:existUser·p1.00      sample         21.791           ms/op
Client.getUser                        sample  10683   2.997 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.861           ms/op
Client.getUser:getUser·p0.50          sample          2.945           ms/op
Client.getUser:getUser·p0.90          sample          3.850           ms/op
Client.getUser:getUser·p0.95          sample          4.173           ms/op
Client.getUser:getUser·p0.99          sample          5.981           ms/op
Client.getUser:getUser·p0.999         sample          7.435           ms/op
Client.getUser:getUser·p0.9999        sample          8.797           ms/op
Client.getUser:getUser·p1.00          sample          8.798           ms/op
Client.listUser                       sample   3927   8.135 ± 0.124   ms/op
Client.listUser:listUser·p0.00        sample          2.310           ms/op
Client.listUser:listUser·p0.50        sample          7.733           ms/op
Client.listUser:listUser·p0.90        sample         10.666           ms/op
Client.listUser:listUser·p0.95        sample         12.494           ms/op
Client.listUser:listUser·p0.99        sample         17.817           ms/op
Client.listUser:listUser·p0.999       sample         21.927           ms/op
Client.listUser:listUser·p0.9999      sample         26.018           ms/op
Client.listUser:listUser·p1.00        sample         26.018           ms/op
