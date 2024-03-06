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
# Warmup Iteration   1: 2.254 ops/ms
Iteration   1: 6.057 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.057 ops/ms


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
# Warmup Iteration   1: 6.423 ops/ms
Iteration   1: 12.455 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.455 ops/ms


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
# Warmup Iteration   1: 4.000 ops/ms
Iteration   1: 7.783 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.783 ops/ms


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
# Warmup Iteration   1: 2.108 ops/ms
Iteration   1: 3.576 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.576 ops/ms


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
# Warmup Iteration   1: 5.640 ±(99.9%) 0.083 ms/op
Iteration   1: 2.930 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.930 ms/op


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
# Warmup Iteration   1: 3.166 ±(99.9%) 0.031 ms/op
Iteration   1: 2.081 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.081 ms/op


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.058 ms/op
Iteration   1: 3.159 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.159 ms/op


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
# Warmup Iteration   1: 11.134 ±(99.9%) 0.166 ms/op
Iteration   1: 7.968 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.968 ms/op


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
# Warmup Iteration   1: 4.988 ±(99.9%) 0.123 ms/op
Iteration   1: 3.166 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.793 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.487 ms/op
                 createUser·p0.99:   14.905 ms/op
                 createUser·p0.999:  18.280 ms/op
                 createUser·p0.9999: 18.350 ms/op
                 createUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10124
  mean =      3.166 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2054 
    [ 2.500,  3.750) = 6818 
    [ 3.750,  5.000) = 892 
    [ 5.000,  6.250) = 126 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      2.793 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.487 ms/op
     p(99.0000) =     14.905 ms/op
     p(99.9000) =     18.280 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 2.996 ±(99.9%) 0.060 ms/op
Iteration   1: 1.788 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   1.653 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.515 ms/op
                 existUser·p0.99:   3.088 ms/op
                 existUser·p0.999:  26.874 ms/op
                 existUser·p0.9999: 27.143 ms/op
                 existUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17862
  mean =      1.788 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16933 
    [ 2.500,  5.000) = 833 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      3.088 ms/op
     p(99.9000) =     26.874 ms/op
     p(99.9900) =     27.143 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.104 ms/op
Iteration   1: 2.962 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.884 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.466 ms/op
                 getUser·p0.999:  15.480 ms/op
                 getUser·p0.9999: 17.482 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10786
  mean =      2.962 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 3034 
    [ 2.500,  3.750) = 6838 
    [ 3.750,  5.000) = 753 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.466 ms/op
     p(99.9000) =     15.480 ms/op
     p(99.9900) =     17.482 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 11.360 ±(99.9%) 0.375 ms/op
Iteration   1: 7.261 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   6.857 ms/op
                 listUser·p0.90:   9.110 ms/op
                 listUser·p0.95:   10.252 ms/op
                 listUser·p0.99:   18.267 ms/op
                 listUser·p0.999:  25.760 ms/op
                 listUser·p0.9999: 28.312 ms/op
                 listUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4404
  mean =      7.261 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 236 
    [ 5.000,  7.500) = 2752 
    [ 7.500, 10.000) = 1163 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.413 ms/op
     p(50.0000) =      6.857 ms/op
     p(90.0000) =      9.110 ms/op
     p(95.0000) =     10.252 ms/op
     p(99.0000) =     18.267 ms/op
     p(99.9000) =     25.760 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.057          ops/ms
Client.existUser                       thrpt         12.455          ops/ms
Client.getUser                         thrpt          7.783          ops/ms
Client.listUser                        thrpt          3.576          ops/ms
Client.createUser                       avgt          2.930           ms/op
Client.existUser                        avgt          2.081           ms/op
Client.getUser                          avgt          3.159           ms/op
Client.listUser                         avgt          7.968           ms/op
Client.createUser                     sample  10124   3.166 ± 0.057   ms/op
Client.createUser:createUser·p0.00    sample          1.094           ms/op
Client.createUser:createUser·p0.50    sample          2.793           ms/op
Client.createUser:createUser·p0.90    sample          3.949           ms/op
Client.createUser:createUser·p0.95    sample          4.487           ms/op
Client.createUser:createUser·p0.99    sample         14.905           ms/op
Client.createUser:createUser·p0.999   sample         18.280           ms/op
Client.createUser:createUser·p0.9999  sample         18.350           ms/op
Client.createUser:createUser·p1.00    sample         18.350           ms/op
Client.existUser                      sample  17862   1.788 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.682           ms/op
Client.existUser:existUser·p0.50      sample          1.653           ms/op
Client.existUser:existUser·p0.90      sample          2.204           ms/op
Client.existUser:existUser·p0.95      sample          2.515           ms/op
Client.existUser:existUser·p0.99      sample          3.088           ms/op
Client.existUser:existUser·p0.999     sample         26.874           ms/op
Client.existUser:existUser·p0.9999    sample         27.143           ms/op
Client.existUser:existUser·p1.00      sample         27.427           ms/op
Client.getUser                        sample  10786   2.962 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.927           ms/op
Client.getUser:getUser·p0.50          sample          2.884           ms/op
Client.getUser:getUser·p0.90          sample          3.670           ms/op
Client.getUser:getUser·p0.95          sample          3.920           ms/op
Client.getUser:getUser·p0.99          sample          5.466           ms/op
Client.getUser:getUser·p0.999         sample         15.480           ms/op
Client.getUser:getUser·p0.9999        sample         17.482           ms/op
Client.getUser:getUser·p1.00          sample         17.531           ms/op
Client.listUser                       sample   4404   7.261 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          2.413           ms/op
Client.listUser:listUser·p0.50        sample          6.857           ms/op
Client.listUser:listUser·p0.90        sample          9.110           ms/op
Client.listUser:listUser·p0.95        sample         10.252           ms/op
Client.listUser:listUser·p0.99        sample         18.267           ms/op
Client.listUser:listUser·p0.999       sample         25.760           ms/op
Client.listUser:listUser·p0.9999      sample         28.312           ms/op
Client.listUser:listUser·p1.00        sample         28.312           ms/op
