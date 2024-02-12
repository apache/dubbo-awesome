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
# Warmup Iteration   1: 2.603 ops/ms
Iteration   1: 6.619 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.619 ops/ms


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
# Warmup Iteration   1: 5.846 ops/ms
Iteration   1: 13.211 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.211 ops/ms


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
# Warmup Iteration   1: 4.510 ops/ms
Iteration   1: 9.511 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.511 ops/ms


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
# Warmup Iteration   1: 2.006 ops/ms
Iteration   1: 3.864 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.864 ops/ms


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
# Warmup Iteration   1: 5.435 ±(99.9%) 0.067 ms/op
Iteration   1: 3.243 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.243 ms/op


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
# Warmup Iteration   1: 3.401 ±(99.9%) 0.038 ms/op
Iteration   1: 1.816 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.816 ms/op


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
# Warmup Iteration   1: 6.289 ±(99.9%) 0.077 ms/op
Iteration   1: 3.315 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.315 ms/op


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
# Warmup Iteration   1: 11.951 ±(99.9%) 0.256 ms/op
Iteration   1: 7.991 ±(99.9%) 0.152 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.991 ms/op


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
# Warmup Iteration   1: 5.148 ±(99.9%) 0.102 ms/op
Iteration   1: 3.146 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   2.732 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   8.798 ms/op
                 createUser·p0.999:  19.485 ms/op
                 createUser·p0.9999: 19.890 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10135
  mean =      3.146 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 2987 
    [ 2.500,  3.750) = 5022 
    [ 3.750,  5.000) = 1837 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      2.732 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     19.485 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.084 ms/op
Iteration   1: 1.904 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.383 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.540 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   3.419 ms/op
                 existUser·p0.999:  8.736 ms/op
                 existUser·p0.9999: 8.809 ms/op
                 existUser·p1.00:   8.831 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16819
  mean =      1.904 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 4 
    [0.500, 1.000) = 116 
    [1.000, 1.500) = 3369 
    [1.500, 2.000) = 7195 
    [2.000, 2.500) = 4289 
    [2.500, 3.000) = 1311 
    [3.000, 3.500) = 422 
    [3.500, 4.000) = 48 
    [4.000, 4.500) = 23 
    [4.500, 5.000) = 10 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.419 ms/op
     p(99.9000) =      8.736 ms/op
     p(99.9900) =      8.809 ms/op
     p(99.9990) =      8.831 ms/op
     p(99.9999) =      8.831 ms/op
    p(100.0000) =      8.831 ms/op


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.107 ms/op
Iteration   1: 2.889 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.863 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.074 ms/op
                 getUser·p0.99:   4.648 ms/op
                 getUser·p0.999:  5.347 ms/op
                 getUser·p0.9999: 6.132 ms/op
                 getUser·p1.00:   6.136 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11065
  mean =      2.889 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 89 
    [1.500, 2.000) = 972 
    [2.000, 2.500) = 2501 
    [2.500, 3.000) = 2782 
    [3.000, 3.500) = 2654 
    [3.500, 4.000) = 1381 
    [4.000, 4.500) = 506 
    [4.500, 5.000) = 148 
    [5.000, 5.500) = 25 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.074 ms/op
     p(99.0000) =      4.648 ms/op
     p(99.9000) =      5.347 ms/op
     p(99.9900) =      6.132 ms/op
     p(99.9990) =      6.136 ms/op
     p(99.9999) =      6.136 ms/op
    p(100.0000) =      6.136 ms/op


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
# Warmup Iteration   1: 12.764 ±(99.9%) 0.508 ms/op
Iteration   1: 7.232 ±(99.9%) 0.110 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   6.926 ms/op
                 listUser·p0.90:   9.144 ms/op
                 listUser·p0.95:   10.044 ms/op
                 listUser·p0.99:   19.572 ms/op
                 listUser·p0.999:  23.205 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4418
  mean =      7.232 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 297 
    [ 5.000,  7.500) = 2597 
    [ 7.500, 10.000) = 1292 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.445 ms/op
     p(50.0000) =      6.926 ms/op
     p(90.0000) =      9.144 ms/op
     p(95.0000) =     10.044 ms/op
     p(99.0000) =     19.572 ms/op
     p(99.9000) =     23.205 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.619          ops/ms
Client.existUser                       thrpt         13.211          ops/ms
Client.getUser                         thrpt          9.511          ops/ms
Client.listUser                        thrpt          3.864          ops/ms
Client.createUser                       avgt          3.243           ms/op
Client.existUser                        avgt          1.816           ms/op
Client.getUser                          avgt          3.315           ms/op
Client.listUser                         avgt          7.991           ms/op
Client.createUser                     sample  10135   3.146 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.087           ms/op
Client.createUser:createUser·p0.50    sample          2.732           ms/op
Client.createUser:createUser·p0.90    sample          4.219           ms/op
Client.createUser:createUser·p0.95    sample          4.579           ms/op
Client.createUser:createUser·p0.99    sample          8.798           ms/op
Client.createUser:createUser·p0.999   sample         19.485           ms/op
Client.createUser:createUser·p0.9999  sample         19.890           ms/op
Client.createUser:createUser·p1.00    sample         19.890           ms/op
Client.existUser                      sample  16819   1.904 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.383           ms/op
Client.existUser:existUser·p0.50      sample          1.798           ms/op
Client.existUser:existUser·p0.90      sample          2.540           ms/op
Client.existUser:existUser·p0.95      sample          2.822           ms/op
Client.existUser:existUser·p0.99      sample          3.419           ms/op
Client.existUser:existUser·p0.999     sample          8.736           ms/op
Client.existUser:existUser·p0.9999    sample          8.809           ms/op
Client.existUser:existUser·p1.00      sample          8.831           ms/op
Client.getUser                        sample  11065   2.889 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          1.059           ms/op
Client.getUser:getUser·p0.50          sample          2.863           ms/op
Client.getUser:getUser·p0.90          sample          3.797           ms/op
Client.getUser:getUser·p0.95          sample          4.074           ms/op
Client.getUser:getUser·p0.99          sample          4.648           ms/op
Client.getUser:getUser·p0.999         sample          5.347           ms/op
Client.getUser:getUser·p0.9999        sample          6.132           ms/op
Client.getUser:getUser·p1.00          sample          6.136           ms/op
Client.listUser                       sample   4418   7.232 ± 0.110   ms/op
Client.listUser:listUser·p0.00        sample          2.445           ms/op
Client.listUser:listUser·p0.50        sample          6.926           ms/op
Client.listUser:listUser·p0.90        sample          9.144           ms/op
Client.listUser:listUser·p0.95        sample         10.044           ms/op
Client.listUser:listUser·p0.99        sample         19.572           ms/op
Client.listUser:listUser·p0.999       sample         23.205           ms/op
Client.listUser:listUser·p0.9999      sample         23.822           ms/op
Client.listUser:listUser·p1.00        sample         23.822           ms/op
