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
# Warmup Iteration   1: 2.503 ops/ms
Iteration   1: 6.092 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.092 ops/ms


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
# Warmup Iteration   1: 6.917 ops/ms
Iteration   1: 14.697 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.697 ops/ms


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
# Warmup Iteration   1: 3.927 ops/ms
Iteration   1: 8.458 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.458 ops/ms


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
# Warmup Iteration   1: 2.436 ops/ms
Iteration   1: 3.733 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.733 ops/ms


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
# Warmup Iteration   1: 5.233 ±(99.9%) 0.069 ms/op
Iteration   1: 3.076 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.076 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.035 ms/op
Iteration   1: 1.942 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.942 ms/op


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
# Warmup Iteration   1: 4.966 ±(99.9%) 0.087 ms/op
Iteration   1: 3.180 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.180 ms/op


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
# Warmup Iteration   1: 11.151 ±(99.9%) 0.175 ms/op
Iteration   1: 7.208 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.208 ms/op


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
# Warmup Iteration   1: 4.981 ±(99.9%) 0.116 ms/op
Iteration   1: 2.997 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   2.769 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   11.698 ms/op
                 createUser·p0.999:  24.834 ms/op
                 createUser·p0.9999: 26.586 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10827
  mean =      2.997 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3258 
    [ 2.500,  5.000) = 7352 
    [ 5.000,  7.500) = 84 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      2.769 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     24.834 ms/op
     p(99.9900) =     26.586 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 3.083 ±(99.9%) 0.066 ms/op
Iteration   1: 1.844 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   1.782 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   2.828 ms/op
                 existUser·p0.999:  4.258 ms/op
                 existUser·p0.9999: 6.256 ms/op
                 existUser·p1.00:   6.341 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17354
  mean =      1.844 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 12 
    [1.000, 1.500) = 864 
    [1.500, 2.000) = 12729 
    [2.000, 2.500) = 3096 
    [2.500, 3.000) = 562 
    [3.000, 3.500) = 47 
    [3.500, 4.000) = 21 
    [4.000, 4.500) = 7 
    [4.500, 5.000) = 6 
    [5.000, 5.500) = 2 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      2.828 ms/op
     p(99.9000) =      4.258 ms/op
     p(99.9900) =      6.256 ms/op
     p(99.9990) =      6.341 ms/op
     p(99.9999) =      6.341 ms/op
    p(100.0000) =      6.341 ms/op


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.130 ms/op
Iteration   1: 3.025 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   2.871 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.029 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  31.537 ms/op
                 getUser·p0.9999: 32.646 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10567
  mean =      3.025 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2425 
    [ 2.500,  5.000) = 8079 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.029 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =     31.537 ms/op
     p(99.9900) =     32.646 ms/op
     p(99.9990) =     32.670 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 11.949 ±(99.9%) 0.381 ms/op
Iteration   1: 8.158 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   7.750 ms/op
                 listUser·p0.90:   10.797 ms/op
                 listUser·p0.95:   12.065 ms/op
                 listUser·p0.99:   15.514 ms/op
                 listUser·p0.999:  19.208 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3955
  mean =      8.158 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 125 
    [ 5.000,  7.500) = 1589 
    [ 7.500, 10.000) = 1533 
    [10.000, 12.500) = 557 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.417 ms/op
     p(50.0000) =      7.750 ms/op
     p(90.0000) =     10.797 ms/op
     p(95.0000) =     12.065 ms/op
     p(99.0000) =     15.514 ms/op
     p(99.9000) =     19.208 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.092          ops/ms
Client.existUser                       thrpt         14.697          ops/ms
Client.getUser                         thrpt          8.458          ops/ms
Client.listUser                        thrpt          3.733          ops/ms
Client.createUser                       avgt          3.076           ms/op
Client.existUser                        avgt          1.942           ms/op
Client.getUser                          avgt          3.180           ms/op
Client.listUser                         avgt          7.208           ms/op
Client.createUser                     sample  10827   2.997 ± 0.051   ms/op
Client.createUser:createUser·p0.00    sample          1.042           ms/op
Client.createUser:createUser·p0.50    sample          2.769           ms/op
Client.createUser:createUser·p0.90    sample          3.682           ms/op
Client.createUser:createUser·p0.95    sample          4.145           ms/op
Client.createUser:createUser·p0.99    sample         11.698           ms/op
Client.createUser:createUser·p0.999   sample         24.834           ms/op
Client.createUser:createUser·p0.9999  sample         26.586           ms/op
Client.createUser:createUser·p1.00    sample         26.640           ms/op
Client.existUser                      sample  17354   1.844 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.792           ms/op
Client.existUser:existUser·p0.50      sample          1.782           ms/op
Client.existUser:existUser·p0.90      sample          2.212           ms/op
Client.existUser:existUser·p0.95      sample          2.417           ms/op
Client.existUser:existUser·p0.99      sample          2.828           ms/op
Client.existUser:existUser·p0.999     sample          4.258           ms/op
Client.existUser:existUser·p0.9999    sample          6.256           ms/op
Client.existUser:existUser·p1.00      sample          6.341           ms/op
Client.getUser                        sample  10567   3.025 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample          0.640           ms/op
Client.getUser:getUser·p0.50          sample          2.871           ms/op
Client.getUser:getUser·p0.90          sample          3.674           ms/op
Client.getUser:getUser·p0.95          sample          4.029           ms/op
Client.getUser:getUser·p0.99          sample          4.669           ms/op
Client.getUser:getUser·p0.999         sample         31.537           ms/op
Client.getUser:getUser·p0.9999        sample         32.646           ms/op
Client.getUser:getUser·p1.00          sample         32.670           ms/op
Client.listUser                       sample   3955   8.158 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample          2.417           ms/op
Client.listUser:listUser·p0.50        sample          7.750           ms/op
Client.listUser:listUser·p0.90        sample         10.797           ms/op
Client.listUser:listUser·p0.95        sample         12.065           ms/op
Client.listUser:listUser·p0.99        sample         15.514           ms/op
Client.listUser:listUser·p0.999       sample         19.208           ms/op
Client.listUser:listUser·p0.9999      sample         22.315           ms/op
Client.listUser:listUser·p1.00        sample         22.315           ms/op
