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
# Warmup Iteration   1: 2.143 ops/ms
Iteration   1: 5.865 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.865 ops/ms


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
# Warmup Iteration   1: 6.553 ops/ms
Iteration   1: 14.176 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.176 ops/ms


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
# Warmup Iteration   1: 3.971 ops/ms
Iteration   1: 8.020 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.020 ops/ms


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
# Warmup Iteration   1: 1.982 ops/ms
Iteration   1: 3.436 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.436 ops/ms


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
# Warmup Iteration   1: 5.837 ±(99.9%) 0.082 ms/op
Iteration   1: 3.399 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.399 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.031 ms/op
Iteration   1: 2.045 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.045 ms/op


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.055 ms/op
Iteration   1: 2.987 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.987 ms/op


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
# Warmup Iteration   1: 12.530 ±(99.9%) 0.273 ms/op
Iteration   1: 7.999 ±(99.9%) 0.109 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.999 ms/op


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
# Warmup Iteration   1: 5.314 ±(99.9%) 0.117 ms/op
Iteration   1: 2.950 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.765 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   7.905 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10832
  mean =      2.950 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2949 
    [ 2.500,  3.750) = 6896 
    [ 3.750,  5.000) = 724 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 2.946 ±(99.9%) 0.060 ms/op
Iteration   1: 1.814 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   2.943 ms/op
                 existUser·p0.999:  5.716 ms/op
                 existUser·p0.9999: 7.168 ms/op
                 existUser·p1.00:   7.193 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17619
  mean =      1.814 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 33 
    [1.000, 1.500) = 3354 
    [1.500, 2.000) = 9990 
    [2.000, 2.500) = 3445 
    [2.500, 3.000) = 632 
    [3.000, 3.500) = 45 
    [3.500, 4.000) = 13 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 19 
    [5.000, 5.500) = 57 
    [5.500, 6.000) = 14 
    [6.000, 6.500) = 11 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      2.943 ms/op
     p(99.9000) =      5.716 ms/op
     p(99.9900) =      7.168 ms/op
     p(99.9990) =      7.193 ms/op
     p(99.9999) =      7.193 ms/op
    p(100.0000) =      7.193 ms/op


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.103 ms/op
Iteration   1: 3.030 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   4.921 ms/op
                 getUser·p0.999:  19.323 ms/op
                 getUser·p0.9999: 19.781 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10577
  mean =      3.030 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 3010 
    [ 2.500,  3.750) = 5833 
    [ 3.750,  5.000) = 1612 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      4.921 ms/op
     p(99.9000) =     19.323 ms/op
     p(99.9900) =     19.781 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 12.632 ±(99.9%) 0.386 ms/op
Iteration   1: 8.168 ±(99.9%) 0.146 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   7.684 ms/op
                 listUser·p0.90:   10.846 ms/op
                 listUser·p0.95:   12.239 ms/op
                 listUser·p0.99:   19.500 ms/op
                 listUser·p0.999:  31.447 ms/op
                 listUser·p0.9999: 37.356 ms/op
                 listUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3890
  mean =      8.168 ±(99.9%) 0.146 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 129 
    [ 5.000,  7.500) = 1659 
    [ 7.500, 10.000) = 1507 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      7.684 ms/op
     p(90.0000) =     10.846 ms/op
     p(95.0000) =     12.239 ms/op
     p(99.0000) =     19.500 ms/op
     p(99.9000) =     31.447 ms/op
     p(99.9900) =     37.356 ms/op
     p(99.9990) =     37.356 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.865          ops/ms
Client.existUser                       thrpt         14.176          ops/ms
Client.getUser                         thrpt          8.020          ops/ms
Client.listUser                        thrpt          3.436          ops/ms
Client.createUser                       avgt          3.399           ms/op
Client.existUser                        avgt          2.045           ms/op
Client.getUser                          avgt          2.987           ms/op
Client.listUser                         avgt          7.999           ms/op
Client.createUser                     sample  10832   2.950 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          0.850           ms/op
Client.createUser:createUser·p0.50    sample          2.765           ms/op
Client.createUser:createUser·p0.90    sample          3.670           ms/op
Client.createUser:createUser·p0.95    sample          4.063           ms/op
Client.createUser:createUser·p0.99    sample          7.905           ms/op
Client.createUser:createUser·p0.999   sample         18.481           ms/op
Client.createUser:createUser·p0.9999  sample         19.169           ms/op
Client.createUser:createUser·p1.00    sample         19.169           ms/op
Client.existUser                      sample  17619   1.814 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.729           ms/op
Client.existUser:existUser·p0.50      sample          1.759           ms/op
Client.existUser:existUser·p0.90      sample          2.290           ms/op
Client.existUser:existUser·p0.95      sample          2.478           ms/op
Client.existUser:existUser·p0.99      sample          2.943           ms/op
Client.existUser:existUser·p0.999     sample          5.716           ms/op
Client.existUser:existUser·p0.9999    sample          7.168           ms/op
Client.existUser:existUser·p1.00      sample          7.193           ms/op
Client.getUser                        sample  10577   3.030 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample          0.990           ms/op
Client.getUser:getUser·p0.50          sample          2.929           ms/op
Client.getUser:getUser·p0.90          sample          3.936           ms/op
Client.getUser:getUser·p0.95          sample          4.202           ms/op
Client.getUser:getUser·p0.99          sample          4.921           ms/op
Client.getUser:getUser·p0.999         sample         19.323           ms/op
Client.getUser:getUser·p0.9999        sample         19.781           ms/op
Client.getUser:getUser·p1.00          sample         19.792           ms/op
Client.listUser                       sample   3890   8.168 ± 0.146   ms/op
Client.listUser:listUser·p0.00        sample          2.154           ms/op
Client.listUser:listUser·p0.50        sample          7.684           ms/op
Client.listUser:listUser·p0.90        sample         10.846           ms/op
Client.listUser:listUser·p0.95        sample         12.239           ms/op
Client.listUser:listUser·p0.99        sample         19.500           ms/op
Client.listUser:listUser·p0.999       sample         31.447           ms/op
Client.listUser:listUser·p0.9999      sample         37.356           ms/op
Client.listUser:listUser·p1.00        sample         37.356           ms/op
