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
# Warmup Iteration   1: 2.156 ops/ms
Iteration   1: 5.753 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.753 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.976 ops/ms
Iteration   1: 13.997 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.997 ops/ms


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
# Warmup Iteration   1: 4.303 ops/ms
Iteration   1: 8.824 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.824 ops/ms


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
# Warmup Iteration   1: 2.082 ops/ms
Iteration   1: 3.824 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.824 ops/ms


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
# Warmup Iteration   1: 5.498 ±(99.9%) 0.075 ms/op
Iteration   1: 3.331 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.331 ms/op


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
# Warmup Iteration   1: 3.429 ±(99.9%) 0.033 ms/op
Iteration   1: 1.943 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.943 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.049 ms/op
Iteration   1: 3.110 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.110 ms/op


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
# Warmup Iteration   1: 13.576 ±(99.9%) 0.268 ms/op
Iteration   1: 9.218 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.218 ms/op


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
# Warmup Iteration   1: 4.978 ±(99.9%) 0.110 ms/op
Iteration   1: 2.933 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   2.777 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  7.087 ms/op
                 createUser·p0.9999: 8.290 ms/op
                 createUser·p1.00:   8.290 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10895
  mean =      2.933 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 13 
    [1.000, 1.500) = 95 
    [1.500, 2.000) = 661 
    [2.000, 2.500) = 2666 
    [2.500, 3.000) = 3234 
    [3.000, 3.500) = 2164 
    [3.500, 4.000) = 955 
    [4.000, 4.500) = 716 
    [4.500, 5.000) = 119 
    [5.000, 5.500) = 114 
    [5.500, 6.000) = 113 
    [6.000, 6.500) = 22 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 16 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      7.087 ms/op
     p(99.9900) =      8.290 ms/op
     p(99.9990) =      8.290 ms/op
     p(99.9999) =      8.290 ms/op
    p(100.0000) =      8.290 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.064 ms/op
Iteration   1: 1.786 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   1.655 ms/op
                 existUser·p0.90:   2.245 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.105 ms/op
                 existUser·p0.999:  22.151 ms/op
                 existUser·p0.9999: 22.794 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17897
  mean =      1.786 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17177 
    [ 2.500,  5.000) = 676 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      1.655 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.105 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     22.794 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.109 ms/op
Iteration   1: 3.001 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   2.818 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.163 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  6.603 ms/op
                 getUser·p0.9999: 8.214 ms/op
                 getUser·p1.00:   8.249 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10653
  mean =      3.001 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 15 
    [1.000, 1.500) = 59 
    [1.500, 2.000) = 341 
    [2.000, 2.500) = 3022 
    [2.500, 3.000) = 2445 
    [3.000, 3.500) = 1832 
    [3.500, 4.000) = 2072 
    [4.000, 4.500) = 588 
    [4.500, 5.000) = 157 
    [5.000, 5.500) = 69 
    [5.500, 6.000) = 15 
    [6.000, 6.500) = 16 
    [6.500, 7.000) = 20 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.163 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =      6.603 ms/op
     p(99.9900) =      8.214 ms/op
     p(99.9990) =      8.249 ms/op
     p(99.9999) =      8.249 ms/op
    p(100.0000) =      8.249 ms/op


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
# Warmup Iteration   1: 12.997 ±(99.9%) 0.541 ms/op
Iteration   1: 8.171 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   7.791 ms/op
                 listUser·p0.90:   10.486 ms/op
                 listUser·p0.95:   11.663 ms/op
                 listUser·p0.99:   16.841 ms/op
                 listUser·p0.999:  20.260 ms/op
                 listUser·p0.9999: 24.871 ms/op
                 listUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3902
  mean =      8.171 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 82 
    [ 5.000,  7.500) = 1575 
    [ 7.500, 10.000) = 1714 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.339 ms/op
     p(50.0000) =      7.791 ms/op
     p(90.0000) =     10.486 ms/op
     p(95.0000) =     11.663 ms/op
     p(99.0000) =     16.841 ms/op
     p(99.9000) =     20.260 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.753          ops/ms
Client.existUser                       thrpt         13.997          ops/ms
Client.getUser                         thrpt          8.824          ops/ms
Client.listUser                        thrpt          3.824          ops/ms
Client.createUser                       avgt          3.331           ms/op
Client.existUser                        avgt          1.943           ms/op
Client.getUser                          avgt          3.110           ms/op
Client.listUser                         avgt          9.218           ms/op
Client.createUser                     sample  10895   2.933 ± 0.026   ms/op
Client.createUser:createUser·p0.00    sample          0.618           ms/op
Client.createUser:createUser·p0.50    sample          2.777           ms/op
Client.createUser:createUser·p0.90    sample          4.014           ms/op
Client.createUser:createUser·p0.95    sample          4.350           ms/op
Client.createUser:createUser·p0.99    sample          5.734           ms/op
Client.createUser:createUser·p0.999   sample          7.087           ms/op
Client.createUser:createUser·p0.9999  sample          8.290           ms/op
Client.createUser:createUser·p1.00    sample          8.290           ms/op
Client.existUser                      sample  17897   1.786 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.724           ms/op
Client.existUser:existUser·p0.50      sample          1.655           ms/op
Client.existUser:existUser·p0.90      sample          2.245           ms/op
Client.existUser:existUser·p0.95      sample          2.433           ms/op
Client.existUser:existUser·p0.99      sample          3.105           ms/op
Client.existUser:existUser·p0.999     sample         22.151           ms/op
Client.existUser:existUser·p0.9999    sample         22.794           ms/op
Client.existUser:existUser·p1.00      sample         22.872           ms/op
Client.getUser                        sample  10653   3.001 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.727           ms/op
Client.getUser:getUser·p0.50          sample          2.818           ms/op
Client.getUser:getUser·p0.90          sample          3.944           ms/op
Client.getUser:getUser·p0.95          sample          4.163           ms/op
Client.getUser:getUser·p0.99          sample          5.071           ms/op
Client.getUser:getUser·p0.999         sample          6.603           ms/op
Client.getUser:getUser·p0.9999        sample          8.214           ms/op
Client.getUser:getUser·p1.00          sample          8.249           ms/op
Client.listUser                       sample   3902   8.171 ± 0.112   ms/op
Client.listUser:listUser·p0.00        sample          2.339           ms/op
Client.listUser:listUser·p0.50        sample          7.791           ms/op
Client.listUser:listUser·p0.90        sample         10.486           ms/op
Client.listUser:listUser·p0.95        sample         11.663           ms/op
Client.listUser:listUser·p0.99        sample         16.841           ms/op
Client.listUser:listUser·p0.999       sample         20.260           ms/op
Client.listUser:listUser·p0.9999      sample         24.871           ms/op
Client.listUser:listUser·p1.00        sample         24.871           ms/op
