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
# Warmup Iteration   1: 2.410 ops/ms
Iteration   1: 6.606 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.606 ops/ms


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
# Warmup Iteration   1: 5.719 ops/ms
Iteration   1: 13.543 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.543 ops/ms


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
# Warmup Iteration   1: 4.917 ops/ms
Iteration   1: 8.911 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.911 ops/ms


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
# Warmup Iteration   1: 2.253 ops/ms
Iteration   1: 3.338 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.338 ops/ms


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
# Warmup Iteration   1: 5.643 ±(99.9%) 0.135 ms/op
Iteration   1: 3.170 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.170 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.031 ms/op
Iteration   1: 2.063 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.063 ms/op


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
# Warmup Iteration   1: 4.432 ±(99.9%) 0.048 ms/op
Iteration   1: 3.197 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.197 ms/op


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
# Warmup Iteration   1: 13.737 ±(99.9%) 0.289 ms/op
Iteration   1: 9.054 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.054 ms/op


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
# Warmup Iteration   1: 5.477 ±(99.9%) 0.166 ms/op
Iteration   1: 3.043 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.855 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   6.202 ms/op
                 createUser·p0.999:  25.100 ms/op
                 createUser·p0.9999: 25.197 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10492
  mean =      3.043 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1196 
    [ 2.500,  5.000) = 9111 
    [ 5.000,  7.500) = 116 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      6.202 ms/op
     p(99.9000) =     25.100 ms/op
     p(99.9900) =     25.197 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.083 ms/op
Iteration   1: 2.060 ±(99.9%) 0.049 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   1.894 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   4.618 ms/op
                 existUser·p0.999:  42.795 ms/op
                 existUser·p0.9999: 44.390 ms/op
                 existUser·p1.00:   44.499 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15526
  mean =      2.060 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15393 
    [ 5.000, 10.000) = 95 
    [10.000, 15.000) = 1 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      4.618 ms/op
     p(99.9000) =     42.795 ms/op
     p(99.9900) =     44.390 ms/op
     p(99.9990) =     44.499 ms/op
     p(99.9999) =     44.499 ms/op
    p(100.0000) =     44.499 ms/op


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
# Warmup Iteration   1: 5.023 ±(99.9%) 0.133 ms/op
Iteration   1: 3.266 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.534 ms/op
                 getUser·p0.99:   6.082 ms/op
                 getUser·p0.999:  10.764 ms/op
                 getUser·p0.9999: 11.174 ms/op
                 getUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9789
  mean =      3.266 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1505 
    [ 2.500,  3.750) = 6148 
    [ 3.750,  5.000) = 1826 
    [ 5.000,  6.250) = 231 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.534 ms/op
     p(99.0000) =      6.082 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     11.174 ms/op
     p(99.9990) =     11.174 ms/op
     p(99.9999) =     11.174 ms/op
    p(100.0000) =     11.174 ms/op


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
# Warmup Iteration   1: 11.968 ±(99.9%) 0.401 ms/op
Iteration   1: 9.149 ±(99.9%) 0.138 ms/op
                 listUser·p0.00:   3.174 ms/op
                 listUser·p0.50:   8.880 ms/op
                 listUser·p0.90:   11.944 ms/op
                 listUser·p0.95:   13.713 ms/op
                 listUser·p0.99:   18.143 ms/op
                 listUser·p0.999:  19.381 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3532
  mean =      9.149 ±(99.9%) 0.138 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 52 
    [ 5.000,  7.500) = 820 
    [ 7.500, 10.000) = 1610 
    [10.000, 12.500) = 769 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.174 ms/op
     p(50.0000) =      8.880 ms/op
     p(90.0000) =     11.944 ms/op
     p(95.0000) =     13.713 ms/op
     p(99.0000) =     18.143 ms/op
     p(99.9000) =     19.381 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.606          ops/ms
Client.existUser                       thrpt         13.543          ops/ms
Client.getUser                         thrpt          8.911          ops/ms
Client.listUser                        thrpt          3.338          ops/ms
Client.createUser                       avgt          3.170           ms/op
Client.existUser                        avgt          2.063           ms/op
Client.getUser                          avgt          3.197           ms/op
Client.listUser                         avgt          9.054           ms/op
Client.createUser                     sample  10492   3.043 ± 0.048   ms/op
Client.createUser:createUser·p0.00    sample          0.768           ms/op
Client.createUser:createUser·p0.50    sample          2.855           ms/op
Client.createUser:createUser·p0.90    sample          3.424           ms/op
Client.createUser:createUser·p0.95    sample          3.850           ms/op
Client.createUser:createUser·p0.99    sample          6.202           ms/op
Client.createUser:createUser·p0.999   sample         25.100           ms/op
Client.createUser:createUser·p0.9999  sample         25.197           ms/op
Client.createUser:createUser·p1.00    sample         25.199           ms/op
Client.existUser                      sample  15526   2.060 ± 0.049   ms/op
Client.existUser:existUser·p0.00      sample          0.667           ms/op
Client.existUser:existUser·p0.50      sample          1.894           ms/op
Client.existUser:existUser·p0.90      sample          2.470           ms/op
Client.existUser:existUser·p0.95      sample          2.740           ms/op
Client.existUser:existUser·p0.99      sample          4.618           ms/op
Client.existUser:existUser·p0.999     sample         42.795           ms/op
Client.existUser:existUser·p0.9999    sample         44.390           ms/op
Client.existUser:existUser·p1.00      sample         44.499           ms/op
Client.getUser                        sample   9789   3.266 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.882           ms/op
Client.getUser:getUser·p0.50          sample          3.199           ms/op
Client.getUser:getUser·p0.90          sample          4.096           ms/op
Client.getUser:getUser·p0.95          sample          4.534           ms/op
Client.getUser:getUser·p0.99          sample          6.082           ms/op
Client.getUser:getUser·p0.999         sample         10.764           ms/op
Client.getUser:getUser·p0.9999        sample         11.174           ms/op
Client.getUser:getUser·p1.00          sample         11.174           ms/op
Client.listUser                       sample   3532   9.149 ± 0.138   ms/op
Client.listUser:listUser·p0.00        sample          3.174           ms/op
Client.listUser:listUser·p0.50        sample          8.880           ms/op
Client.listUser:listUser·p0.90        sample         11.944           ms/op
Client.listUser:listUser·p0.95        sample         13.713           ms/op
Client.listUser:listUser·p0.99        sample         18.143           ms/op
Client.listUser:listUser·p0.999       sample         19.381           ms/op
Client.listUser:listUser·p0.9999      sample         20.578           ms/op
Client.listUser:listUser·p1.00        sample         20.578           ms/op
