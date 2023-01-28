# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.143 ops/ms
Iteration   1: 2.441 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.441 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ops/ms
Iteration   1: 8.167 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.167 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.760 ops/ms
Iteration   1: 6.013 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.013 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.865 ops/ms
Iteration   1: 1.302 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.302 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 17.621 ±(99.9%) 0.267 ms/op
Iteration   1: 6.781 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.781 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.372 ±(99.9%) 0.075 ms/op
Iteration   1: 2.944 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.944 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.265 ±(99.9%) 0.099 ms/op
Iteration   1: 4.386 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.386 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 26.388 ±(99.9%) 0.574 ms/op
Iteration   1: 17.735 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.735 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.081 ±(99.9%) 0.509 ms/op
Iteration   1: 6.120 ±(99.9%) 0.113 ms/op
                 createUser·p0.00:   0.347 ms/op
                 createUser·p0.50:   6.119 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   9.228 ms/op
                 createUser·p0.99:   16.777 ms/op
                 createUser·p0.999:  26.436 ms/op
                 createUser·p0.9999: 26.640 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5234
  mean =      6.120 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 1311 
    [ 5.000,  7.500) = 3612 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      6.119 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      9.228 ms/op
     p(99.0000) =     16.777 ms/op
     p(99.9000) =     26.436 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.766 ±(99.9%) 0.180 ms/op
Iteration   1: 2.933 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   10.584 ms/op
                 existUser·p0.999:  11.782 ms/op
                 existUser·p0.9999: 11.813 ms/op
                 existUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10899
  mean =      2.933 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 4127 
    [ 2.500,  3.750) = 6211 
    [ 3.750,  5.000) = 201 
    [ 5.000,  6.250) = 130 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     11.782 ms/op
     p(99.9900) =     11.813 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.048 ±(99.9%) 0.433 ms/op
Iteration   1: 4.462 ±(99.9%) 0.090 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   7.102 ms/op
                 getUser·p0.99:   16.176 ms/op
                 getUser·p0.999:  26.722 ms/op
                 getUser·p0.9999: 27.296 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7167
  mean =      4.462 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 319 
    [ 2.500,  5.000) = 5486 
    [ 5.000,  7.500) = 1100 
    [ 7.500, 10.000) = 143 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      7.102 ms/op
     p(99.0000) =     16.176 ms/op
     p(99.9000) =     26.722 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 23.388 ±(99.9%) 0.588 ms/op
Iteration   1: 23.847 ±(99.9%) 1.006 ms/op
                 listUser·p0.00:   4.235 ms/op
                 listUser·p0.50:   20.087 ms/op
                 listUser·p0.90:   40.436 ms/op
                 listUser·p0.95:   47.448 ms/op
                 listUser·p0.99:   55.273 ms/op
                 listUser·p0.999:  75.136 ms/op
                 listUser·p0.9999: 75.760 ms/op
                 listUser·p1.00:   75.760 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1339
  mean =     23.847 ±(99.9%) 1.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3 
    [ 5.000, 10.000) = 22 
    [10.000, 15.000) = 196 
    [15.000, 20.000) = 446 
    [20.000, 25.000) = 153 
    [25.000, 30.000) = 228 
    [30.000, 35.000) = 94 
    [35.000, 40.000) = 60 
    [40.000, 45.000) = 39 
    [45.000, 50.000) = 59 
    [50.000, 55.000) = 25 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 8 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      4.235 ms/op
     p(50.0000) =     20.087 ms/op
     p(90.0000) =     40.436 ms/op
     p(95.0000) =     47.448 ms/op
     p(99.0000) =     55.273 ms/op
     p(99.9000) =     75.136 ms/op
     p(99.9900) =     75.760 ms/op
     p(99.9990) =     75.760 ms/op
     p(99.9999) =     75.760 ms/op
    p(100.0000) =     75.760 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.441          ops/ms
Client.existUser                       thrpt          8.167          ops/ms
Client.getUser                         thrpt          6.013          ops/ms
Client.listUser                        thrpt          1.302          ops/ms
Client.createUser                       avgt          6.781           ms/op
Client.existUser                        avgt          2.944           ms/op
Client.getUser                          avgt          4.386           ms/op
Client.listUser                         avgt         17.735           ms/op
Client.createUser                     sample   5234   6.120 ± 0.113   ms/op
Client.createUser:createUser·p0.00    sample          0.347           ms/op
Client.createUser:createUser·p0.50    sample          6.119           ms/op
Client.createUser:createUser·p0.90    sample          6.636           ms/op
Client.createUser:createUser·p0.95    sample          9.228           ms/op
Client.createUser:createUser·p0.99    sample         16.777           ms/op
Client.createUser:createUser·p0.999   sample         26.436           ms/op
Client.createUser:createUser·p0.9999  sample         26.640           ms/op
Client.createUser:createUser·p1.00    sample         26.640           ms/op
Client.existUser                      sample  10899   2.933 ± 0.035   ms/op
Client.existUser:existUser·p0.00      sample          0.569           ms/op
Client.existUser:existUser·p0.50      sample          2.621           ms/op
Client.existUser:existUser·p0.90      sample          3.355           ms/op
Client.existUser:existUser·p0.95      sample          3.711           ms/op
Client.existUser:existUser·p0.99      sample         10.584           ms/op
Client.existUser:existUser·p0.999     sample         11.782           ms/op
Client.existUser:existUser·p0.9999    sample         11.813           ms/op
Client.existUser:existUser·p1.00      sample         11.813           ms/op
Client.getUser                        sample   7167   4.462 ± 0.090   ms/op
Client.getUser:getUser·p0.00          sample          1.286           ms/op
Client.getUser:getUser·p0.50          sample          4.334           ms/op
Client.getUser:getUser·p0.90          sample          5.620           ms/op
Client.getUser:getUser·p0.95          sample          7.102           ms/op
Client.getUser:getUser·p0.99          sample         16.176           ms/op
Client.getUser:getUser·p0.999         sample         26.722           ms/op
Client.getUser:getUser·p0.9999        sample         27.296           ms/op
Client.getUser:getUser·p1.00          sample         27.296           ms/op
Client.listUser                       sample   1339  23.847 ± 1.006   ms/op
Client.listUser:listUser·p0.00        sample          4.235           ms/op
Client.listUser:listUser·p0.50        sample         20.087           ms/op
Client.listUser:listUser·p0.90        sample         40.436           ms/op
Client.listUser:listUser·p0.95        sample         47.448           ms/op
Client.listUser:listUser·p0.99        sample         55.273           ms/op
Client.listUser:listUser·p0.999       sample         75.136           ms/op
Client.listUser:listUser·p0.9999      sample         75.760           ms/op
Client.listUser:listUser·p1.00        sample         75.760           ms/op
