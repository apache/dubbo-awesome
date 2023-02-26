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
# Warmup Iteration   1: 1.068 ops/ms
Iteration   1: 2.333 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.333 ops/ms


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
# Warmup Iteration   1: 2.794 ops/ms
Iteration   1: 6.811 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.811 ops/ms


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
# Warmup Iteration   1: 2.064 ops/ms
Iteration   1: 4.854 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.854 ops/ms


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
# Warmup Iteration   1: 0.834 ops/ms
Iteration   1: 1.476 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.476 ops/ms


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
# Warmup Iteration   1: 14.502 ±(99.9%) 0.261 ms/op
Iteration   1: 7.382 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.382 ms/op


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
# Warmup Iteration   1: 6.373 ±(99.9%) 0.098 ms/op
Iteration   1: 4.674 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.674 ms/op


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
# Warmup Iteration   1: 10.426 ±(99.9%) 0.141 ms/op
Iteration   1: 4.615 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.615 ms/op


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
# Warmup Iteration   1: 31.330 ±(99.9%) 1.266 ms/op
Iteration   1: 18.780 ±(99.9%) 0.110 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.780 ms/op


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
# Warmup Iteration   1: 11.227 ±(99.9%) 0.398 ms/op
Iteration   1: 7.312 ±(99.9%) 0.120 ms/op
                 createUser·p0.00:   2.564 ms/op
                 createUser·p0.50:   6.865 ms/op
                 createUser·p0.90:   7.940 ms/op
                 createUser·p0.95:   12.653 ms/op
                 createUser·p0.99:   17.629 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4377
  mean =      7.312 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 233 
    [ 5.000,  7.500) = 3237 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.564 ms/op
     p(50.0000) =      6.865 ms/op
     p(90.0000) =      7.940 ms/op
     p(95.0000) =     12.653 ms/op
     p(99.0000) =     17.629 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 7.353 ±(99.9%) 0.211 ms/op
Iteration   1: 3.688 ±(99.9%) 0.061 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   13.173 ms/op
                 existUser·p0.999:  17.760 ms/op
                 existUser·p0.9999: 18.514 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8660
  mean =      3.688 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 1322 
    [ 2.500,  3.750) = 4077 
    [ 3.750,  5.000) = 2662 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =     13.173 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 12.009 ±(99.9%) 0.485 ms/op
Iteration   1: 4.824 ±(99.9%) 0.093 ms/op
                 getUser·p0.00:   0.331 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.987 ms/op
                 getUser·p0.99:   18.984 ms/op
                 getUser·p0.999:  28.503 ms/op
                 getUser·p0.9999: 28.836 ms/op
                 getUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6582
  mean =      4.824 ±(99.9%) 0.093 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 5405 
    [ 5.000,  7.500) = 1017 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.331 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.987 ms/op
     p(99.0000) =     18.984 ms/op
     p(99.9000) =     28.503 ms/op
     p(99.9900) =     28.836 ms/op
     p(99.9990) =     28.836 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 28.362 ±(99.9%) 0.967 ms/op
Iteration   1: 18.001 ±(99.9%) 0.336 ms/op
                 listUser·p0.00:   3.379 ms/op
                 listUser·p0.50:   16.564 ms/op
                 listUser·p0.90:   23.953 ms/op
                 listUser·p0.95:   24.773 ms/op
                 listUser·p0.99:   27.394 ms/op
                 listUser·p0.999:  33.833 ms/op
                 listUser·p0.9999: 36.831 ms/op
                 listUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1768
  mean =     18.001 ±(99.9%) 0.336 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 716 
    [17.500, 20.000) = 297 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 293 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.379 ms/op
     p(50.0000) =     16.564 ms/op
     p(90.0000) =     23.953 ms/op
     p(95.0000) =     24.773 ms/op
     p(99.0000) =     27.394 ms/op
     p(99.9000) =     33.833 ms/op
     p(99.9900) =     36.831 ms/op
     p(99.9990) =     36.831 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.333          ops/ms
Client.existUser                       thrpt         6.811          ops/ms
Client.getUser                         thrpt         4.854          ops/ms
Client.listUser                        thrpt         1.476          ops/ms
Client.createUser                       avgt         7.382           ms/op
Client.existUser                        avgt         4.674           ms/op
Client.getUser                          avgt         4.615           ms/op
Client.listUser                         avgt        18.780           ms/op
Client.createUser                     sample  4377   7.312 ± 0.120   ms/op
Client.createUser:createUser·p0.00    sample         2.564           ms/op
Client.createUser:createUser·p0.50    sample         6.865           ms/op
Client.createUser:createUser·p0.90    sample         7.940           ms/op
Client.createUser:createUser·p0.95    sample        12.653           ms/op
Client.createUser:createUser·p0.99    sample        17.629           ms/op
Client.createUser:createUser·p0.999   sample        20.283           ms/op
Client.createUser:createUser·p0.9999  sample        22.217           ms/op
Client.createUser:createUser·p1.00    sample        22.217           ms/op
Client.existUser                      sample  8660   3.688 ± 0.061   ms/op
Client.existUser:existUser·p0.00      sample         0.713           ms/op
Client.existUser:existUser·p0.50      sample         3.310           ms/op
Client.existUser:existUser·p0.90      sample         4.907           ms/op
Client.existUser:existUser·p0.95      sample         5.038           ms/op
Client.existUser:existUser·p0.99      sample        13.173           ms/op
Client.existUser:existUser·p0.999     sample        17.760           ms/op
Client.existUser:existUser·p0.9999    sample        18.514           ms/op
Client.existUser:existUser·p1.00      sample        18.514           ms/op
Client.getUser                        sample  6582   4.824 ± 0.093   ms/op
Client.getUser:getUser·p0.00          sample         0.331           ms/op
Client.getUser:getUser·p0.50          sample         4.497           ms/op
Client.getUser:getUser·p0.90          sample         5.448           ms/op
Client.getUser:getUser·p0.95          sample         5.987           ms/op
Client.getUser:getUser·p0.99          sample        18.984           ms/op
Client.getUser:getUser·p0.999         sample        28.503           ms/op
Client.getUser:getUser·p0.9999        sample        28.836           ms/op
Client.getUser:getUser·p1.00          sample        28.836           ms/op
Client.listUser                       sample  1768  18.001 ± 0.336   ms/op
Client.listUser:listUser·p0.00        sample         3.379           ms/op
Client.listUser:listUser·p0.50        sample        16.564           ms/op
Client.listUser:listUser·p0.90        sample        23.953           ms/op
Client.listUser:listUser·p0.95        sample        24.773           ms/op
Client.listUser:listUser·p0.99        sample        27.394           ms/op
Client.listUser:listUser·p0.999       sample        33.833           ms/op
Client.listUser:listUser·p0.9999      sample        36.831           ms/op
Client.listUser:listUser·p1.00        sample        36.831           ms/op
