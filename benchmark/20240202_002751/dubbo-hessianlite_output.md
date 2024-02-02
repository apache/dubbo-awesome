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
# Warmup Iteration   1: 2.456 ops/ms
Iteration   1: 5.810 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.810 ops/ms


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
# Warmup Iteration   1: 5.903 ops/ms
Iteration   1: 13.666 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.666 ops/ms


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
# Warmup Iteration   1: 3.860 ops/ms
Iteration   1: 7.846 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.846 ops/ms


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
# Warmup Iteration   1: 2.214 ops/ms
Iteration   1: 2.992 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.992 ops/ms


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
# Warmup Iteration   1: 5.389 ±(99.9%) 0.074 ms/op
Iteration   1: 3.004 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.004 ms/op


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
# Warmup Iteration   1: 3.040 ±(99.9%) 0.033 ms/op
Iteration   1: 1.924 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.924 ms/op


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
# Warmup Iteration   1: 4.991 ±(99.9%) 0.071 ms/op
Iteration   1: 3.064 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.064 ms/op


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
# Warmup Iteration   1: 10.658 ±(99.9%) 0.191 ms/op
Iteration   1: 7.980 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.980 ms/op


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
# Warmup Iteration   1: 5.057 ±(99.9%) 0.107 ms/op
Iteration   1: 2.914 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.705 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   7.692 ms/op
                 createUser·p0.999:  15.483 ms/op
                 createUser·p0.9999: 15.514 ms/op
                 createUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10913
  mean =      2.914 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 4125 
    [ 2.500,  3.750) = 5731 
    [ 3.750,  5.000) = 717 
    [ 5.000,  6.250) = 157 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      2.662 ms/op
     p(90.0000) =      3.705 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     15.514 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.070 ms/op
Iteration   1: 1.964 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.874 ms/op
                 existUser·p0.90:   2.490 ms/op
                 existUser·p0.95:   2.671 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  5.190 ms/op
                 existUser·p0.9999: 6.489 ms/op
                 existUser·p1.00:   6.504 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16297
  mean =      1.964 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 43 
    [1.000, 1.500) = 1380 
    [1.500, 2.000) = 8863 
    [2.000, 2.500) = 4420 
    [2.500, 3.000) = 1253 
    [3.000, 3.500) = 179 
    [3.500, 4.000) = 61 
    [4.000, 4.500) = 33 
    [4.500, 5.000) = 33 
    [5.000, 5.500) = 22 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      5.190 ms/op
     p(99.9900) =      6.489 ms/op
     p(99.9990) =      6.504 ms/op
     p(99.9999) =      6.504 ms/op
    p(100.0000) =      6.504 ms/op


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.112 ms/op
Iteration   1: 3.194 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.256 ms/op
                 getUser·p0.999:  20.644 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10008
  mean =      3.194 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1287 
    [ 2.500,  5.000) = 8591 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.256 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 12.760 ±(99.9%) 0.475 ms/op
Iteration   1: 9.182 ±(99.9%) 0.147 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   8.765 ms/op
                 listUser·p0.90:   12.386 ms/op
                 listUser·p0.95:   13.356 ms/op
                 listUser·p0.99:   19.076 ms/op
                 listUser·p0.999:  23.748 ms/op
                 listUser·p0.9999: 24.904 ms/op
                 listUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3477
  mean =      9.182 ±(99.9%) 0.147 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 52 
    [ 5.000,  7.500) = 846 
    [ 7.500, 10.000) = 1510 
    [10.000, 12.500) = 754 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.609 ms/op
     p(50.0000) =      8.765 ms/op
     p(90.0000) =     12.386 ms/op
     p(95.0000) =     13.356 ms/op
     p(99.0000) =     19.076 ms/op
     p(99.9000) =     23.748 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.810          ops/ms
Client.existUser                       thrpt         13.666          ops/ms
Client.getUser                         thrpt          7.846          ops/ms
Client.listUser                        thrpt          2.992          ops/ms
Client.createUser                       avgt          3.004           ms/op
Client.existUser                        avgt          1.924           ms/op
Client.getUser                          avgt          3.064           ms/op
Client.listUser                         avgt          7.980           ms/op
Client.createUser                     sample  10913   2.914 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          0.956           ms/op
Client.createUser:createUser·p0.50    sample          2.662           ms/op
Client.createUser:createUser·p0.90    sample          3.705           ms/op
Client.createUser:createUser·p0.95    sample          4.252           ms/op
Client.createUser:createUser·p0.99    sample          7.692           ms/op
Client.createUser:createUser·p0.999   sample         15.483           ms/op
Client.createUser:createUser·p0.9999  sample         15.514           ms/op
Client.createUser:createUser·p1.00    sample         15.516           ms/op
Client.existUser                      sample  16297   1.964 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.560           ms/op
Client.existUser:existUser·p0.50      sample          1.874           ms/op
Client.existUser:existUser·p0.90      sample          2.490           ms/op
Client.existUser:existUser·p0.95      sample          2.671           ms/op
Client.existUser:existUser·p0.99      sample          3.453           ms/op
Client.existUser:existUser·p0.999     sample          5.190           ms/op
Client.existUser:existUser·p0.9999    sample          6.489           ms/op
Client.existUser:existUser·p1.00      sample          6.504           ms/op
Client.getUser                        sample  10008   3.194 ± 0.039   ms/op
Client.getUser:getUser·p0.00          sample          0.664           ms/op
Client.getUser:getUser·p0.50          sample          3.072           ms/op
Client.getUser:getUser·p0.90          sample          3.977           ms/op
Client.getUser:getUser·p0.95          sample          4.252           ms/op
Client.getUser:getUser·p0.99          sample          5.256           ms/op
Client.getUser:getUser·p0.999         sample         20.644           ms/op
Client.getUser:getUser·p0.9999        sample         20.808           ms/op
Client.getUser:getUser·p1.00          sample         20.808           ms/op
Client.listUser                       sample   3477   9.182 ± 0.147   ms/op
Client.listUser:listUser·p0.00        sample          2.609           ms/op
Client.listUser:listUser·p0.50        sample          8.765           ms/op
Client.listUser:listUser·p0.90        sample         12.386           ms/op
Client.listUser:listUser·p0.95        sample         13.356           ms/op
Client.listUser:listUser·p0.99        sample         19.076           ms/op
Client.listUser:listUser·p0.999       sample         23.748           ms/op
Client.listUser:listUser·p0.9999      sample         24.904           ms/op
Client.listUser:listUser·p1.00        sample         24.904           ms/op
