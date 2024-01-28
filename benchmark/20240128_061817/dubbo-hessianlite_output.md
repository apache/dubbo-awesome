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
# Warmup Iteration   1: 2.272 ops/ms
Iteration   1: 5.356 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.356 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.708 ops/ms
Iteration   1: 12.422 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.422 ops/ms


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
# Warmup Iteration   1: 3.834 ops/ms
Iteration   1: 7.211 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.211 ops/ms


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
# Warmup Iteration   1: 1.863 ops/ms
Iteration   1: 3.400 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.400 ops/ms


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
# Warmup Iteration   1: 6.273 ±(99.9%) 0.107 ms/op
Iteration   1: 3.137 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.137 ms/op


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
# Warmup Iteration   1: 3.488 ±(99.9%) 0.036 ms/op
Iteration   1: 1.905 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.905 ms/op


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
# Warmup Iteration   1: 5.128 ±(99.9%) 0.074 ms/op
Iteration   1: 3.225 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.225 ms/op


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
# Warmup Iteration   1: 13.304 ±(99.9%) 0.243 ms/op
Iteration   1: 8.209 ±(99.9%) 0.077 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.209 ms/op


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
# Warmup Iteration   1: 5.316 ±(99.9%) 0.119 ms/op
Iteration   1: 2.955 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   2.748 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.600 ms/op
                 createUser·p0.999:  16.122 ms/op
                 createUser·p0.9999: 16.251 ms/op
                 createUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10933
  mean =      2.955 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 3270 
    [ 2.500,  3.750) = 6554 
    [ 3.750,  5.000) = 816 
    [ 5.000,  6.250) = 168 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.600 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     16.251 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 3.065 ±(99.9%) 0.073 ms/op
Iteration   1: 1.787 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.317 ms/op
                 existUser·p0.50:   1.651 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   3.511 ms/op
                 existUser·p0.999:  27.329 ms/op
                 existUser·p0.9999: 27.499 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17886
  mean =      1.787 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17143 
    [ 2.500,  5.000) = 676 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.317 ms/op
     p(50.0000) =      1.651 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      3.511 ms/op
     p(99.9000) =     27.329 ms/op
     p(99.9900) =     27.499 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.123 ms/op
Iteration   1: 3.234 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   4.171 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.311 ms/op
                 getUser·p0.999:  7.604 ms/op
                 getUser·p0.9999: 8.667 ms/op
                 getUser·p1.00:   8.667 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9885
  mean =      3.234 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 73 
    [2.000, 2.500) = 1055 
    [2.500, 3.000) = 3604 
    [3.000, 3.500) = 1845 
    [3.500, 4.000) = 1804 
    [4.000, 4.500) = 1103 
    [4.500, 5.000) = 246 
    [5.000, 5.500) = 64 
    [5.500, 6.000) = 33 
    [6.000, 6.500) = 15 
    [6.500, 7.000) = 14 
    [7.000, 7.500) = 13 
    [7.500, 8.000) = 6 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.171 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.311 ms/op
     p(99.9000) =      7.604 ms/op
     p(99.9900) =      8.667 ms/op
     p(99.9990) =      8.667 ms/op
     p(99.9999) =      8.667 ms/op
    p(100.0000) =      8.667 ms/op


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
# Warmup Iteration   1: 13.198 ±(99.9%) 0.527 ms/op
Iteration   1: 9.205 ±(99.9%) 0.150 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   8.815 ms/op
                 listUser·p0.90:   12.829 ms/op
                 listUser·p0.95:   13.817 ms/op
                 listUser·p0.99:   17.874 ms/op
                 listUser·p0.999:  22.530 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3476
  mean =      9.205 ±(99.9%) 0.150 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 90 
    [ 5.000,  7.500) = 842 
    [ 7.500, 10.000) = 1429 
    [10.000, 12.500) = 714 
    [12.500, 15.000) = 320 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.757 ms/op
     p(50.0000) =      8.815 ms/op
     p(90.0000) =     12.829 ms/op
     p(95.0000) =     13.817 ms/op
     p(99.0000) =     17.874 ms/op
     p(99.9000) =     22.530 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.356          ops/ms
Client.existUser                       thrpt         12.422          ops/ms
Client.getUser                         thrpt          7.211          ops/ms
Client.listUser                        thrpt          3.400          ops/ms
Client.createUser                       avgt          3.137           ms/op
Client.existUser                        avgt          1.905           ms/op
Client.getUser                          avgt          3.225           ms/op
Client.listUser                         avgt          8.209           ms/op
Client.createUser                     sample  10933   2.955 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.133           ms/op
Client.createUser:createUser·p0.50    sample          2.748           ms/op
Client.createUser:createUser·p0.90    sample          3.756           ms/op
Client.createUser:createUser·p0.95    sample          4.391           ms/op
Client.createUser:createUser·p0.99    sample          6.600           ms/op
Client.createUser:createUser·p0.999   sample         16.122           ms/op
Client.createUser:createUser·p0.9999  sample         16.251           ms/op
Client.createUser:createUser·p1.00    sample         16.253           ms/op
Client.existUser                      sample  17886   1.787 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.317           ms/op
Client.existUser:existUser·p0.50      sample          1.651           ms/op
Client.existUser:existUser·p0.90      sample          2.167           ms/op
Client.existUser:existUser·p0.95      sample          2.396           ms/op
Client.existUser:existUser·p0.99      sample          3.511           ms/op
Client.existUser:existUser·p0.999     sample         27.329           ms/op
Client.existUser:existUser·p0.9999    sample         27.499           ms/op
Client.existUser:existUser·p1.00      sample         27.525           ms/op
Client.getUser                        sample   9885   3.234 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.260           ms/op
Client.getUser:getUser·p0.50          sample          3.039           ms/op
Client.getUser:getUser·p0.90          sample          4.171           ms/op
Client.getUser:getUser·p0.95          sample          4.432           ms/op
Client.getUser:getUser·p0.99          sample          5.311           ms/op
Client.getUser:getUser·p0.999         sample          7.604           ms/op
Client.getUser:getUser·p0.9999        sample          8.667           ms/op
Client.getUser:getUser·p1.00          sample          8.667           ms/op
Client.listUser                       sample   3476   9.205 ± 0.150   ms/op
Client.listUser:listUser·p0.00        sample          1.757           ms/op
Client.listUser:listUser·p0.50        sample          8.815           ms/op
Client.listUser:listUser·p0.90        sample         12.829           ms/op
Client.listUser:listUser·p0.95        sample         13.817           ms/op
Client.listUser:listUser·p0.99        sample         17.874           ms/op
Client.listUser:listUser·p0.999       sample         22.530           ms/op
Client.listUser:listUser·p0.9999      sample         23.658           ms/op
Client.listUser:listUser·p1.00        sample         23.658           ms/op
