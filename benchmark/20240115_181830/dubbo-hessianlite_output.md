# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.747 ops/ms
Iteration   1: 6.144 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.144 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.092 ops/ms
Iteration   1: 13.902 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.902 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.165 ops/ms
Iteration   1: 9.168 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.168 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.137 ops/ms
Iteration   1: 4.073 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.073 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ±(99.9%) 0.064 ms/op
Iteration   1: 3.035 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.035 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.989 ±(99.9%) 0.023 ms/op
Iteration   1: 1.783 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.955 ±(99.9%) 0.061 ms/op
Iteration   1: 3.127 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.127 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.777 ±(99.9%) 0.207 ms/op
Iteration   1: 8.954 ±(99.9%) 0.113 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.954 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.696 ±(99.9%) 0.094 ms/op
Iteration   1: 2.766 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   6.032 ms/op
                 createUser·p0.999:  15.374 ms/op
                 createUser·p0.9999: 15.903 ms/op
                 createUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11672
  mean =      2.766 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 4714 
    [ 2.500,  3.750) = 6113 
    [ 3.750,  5.000) = 628 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      6.032 ms/op
     p(99.9000) =     15.374 ms/op
     p(99.9900) =     15.903 ms/op
     p(99.9990) =     15.942 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.027 ±(99.9%) 0.063 ms/op
Iteration   1: 1.747 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.458 ms/op
                 existUser·p0.999:  13.386 ms/op
                 existUser·p0.9999: 14.604 ms/op
                 existUser·p1.00:   14.631 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18287
  mean =      1.747 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1538 
    [ 1.250,  2.500) = 15898 
    [ 2.500,  3.750) = 702 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.458 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     14.604 ms/op
     p(99.9990) =     14.631 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 5.222 ±(99.9%) 0.139 ms/op
Iteration   1: 3.006 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.798 ms/op
                 getUser·p0.90:   3.931 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  8.458 ms/op
                 getUser·p0.9999: 9.470 ms/op
                 getUser·p1.00:   9.470 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10762
  mean =      3.006 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 5 
    [ 1.000,  2.000) = 211 
    [ 2.000,  3.000) = 5942 
    [ 3.000,  4.000) = 3687 
    [ 4.000,  5.000) = 748 
    [ 5.000,  6.000) = 87 
    [ 6.000,  7.000) = 38 
    [ 7.000,  8.000) = 33 
    [ 8.000,  9.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.931 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =      8.458 ms/op
     p(99.9900) =      9.470 ms/op
     p(99.9990) =      9.470 ms/op
     p(99.9999) =      9.470 ms/op
    p(100.0000) =      9.470 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.211 ±(99.9%) 0.595 ms/op
Iteration   1: 8.666 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   2.875 ms/op
                 listUser·p0.50:   8.421 ms/op
                 listUser·p0.90:   11.600 ms/op
                 listUser·p0.95:   12.403 ms/op
                 listUser·p0.99:   14.485 ms/op
                 listUser·p0.999:  21.010 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3694
  mean =      8.666 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 83 
    [ 5.000,  7.500) = 1139 
    [ 7.500, 10.000) = 1545 
    [10.000, 12.500) = 748 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.875 ms/op
     p(50.0000) =      8.421 ms/op
     p(90.0000) =     11.600 ms/op
     p(95.0000) =     12.403 ms/op
     p(99.0000) =     14.485 ms/op
     p(99.9000) =     21.010 ms/op
     p(99.9900) =     27.427 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.144          ops/ms
Client.existUser                       thrpt         13.902          ops/ms
Client.getUser                         thrpt          9.168          ops/ms
Client.listUser                        thrpt          4.073          ops/ms
Client.createUser                       avgt          3.035           ms/op
Client.existUser                        avgt          1.783           ms/op
Client.getUser                          avgt          3.127           ms/op
Client.listUser                         avgt          8.954           ms/op
Client.createUser                     sample  11672   2.766 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          1.282           ms/op
Client.createUser:createUser·p0.50    sample          2.593           ms/op
Client.createUser:createUser·p0.90    sample          3.510           ms/op
Client.createUser:createUser·p0.95    sample          3.985           ms/op
Client.createUser:createUser·p0.99    sample          6.032           ms/op
Client.createUser:createUser·p0.999   sample         15.374           ms/op
Client.createUser:createUser·p0.9999  sample         15.903           ms/op
Client.createUser:createUser·p1.00    sample         15.942           ms/op
Client.existUser                      sample  18287   1.747 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.571           ms/op
Client.existUser:existUser·p0.50      sample          1.661           ms/op
Client.existUser:existUser·p0.90      sample          2.183           ms/op
Client.existUser:existUser·p0.95      sample          2.478           ms/op
Client.existUser:existUser·p0.99      sample          3.458           ms/op
Client.existUser:existUser·p0.999     sample         13.386           ms/op
Client.existUser:existUser·p0.9999    sample         14.604           ms/op
Client.existUser:existUser·p1.00      sample         14.631           ms/op
Client.getUser                        sample  10762   3.006 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.784           ms/op
Client.getUser:getUser·p0.50          sample          2.798           ms/op
Client.getUser:getUser·p0.90          sample          3.931           ms/op
Client.getUser:getUser·p0.95          sample          4.219           ms/op
Client.getUser:getUser·p0.99          sample          5.825           ms/op
Client.getUser:getUser·p0.999         sample          8.458           ms/op
Client.getUser:getUser·p0.9999        sample          9.470           ms/op
Client.getUser:getUser·p1.00          sample          9.470           ms/op
Client.listUser                       sample   3694   8.666 ± 0.119   ms/op
Client.listUser:listUser·p0.00        sample          2.875           ms/op
Client.listUser:listUser·p0.50        sample          8.421           ms/op
Client.listUser:listUser·p0.90        sample         11.600           ms/op
Client.listUser:listUser·p0.95        sample         12.403           ms/op
Client.listUser:listUser·p0.99        sample         14.485           ms/op
Client.listUser:listUser·p0.999       sample         21.010           ms/op
Client.listUser:listUser·p0.9999      sample         27.427           ms/op
Client.listUser:listUser·p1.00        sample         27.427           ms/op
