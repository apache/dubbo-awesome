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
# Warmup Iteration   1: 2.448 ops/ms
Iteration   1: 6.269 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.269 ops/ms


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
# Warmup Iteration   1: 5.591 ops/ms
Iteration   1: 10.689 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.689 ops/ms


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
# Warmup Iteration   1: 4.940 ops/ms
Iteration   1: 8.184 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.184 ops/ms


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
# Warmup Iteration   1: 2.146 ops/ms
Iteration   1: 3.475 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.475 ops/ms


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
# Warmup Iteration   1: 5.669 ±(99.9%) 0.098 ms/op
Iteration   1: 3.339 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.339 ms/op


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
# Warmup Iteration   1: 3.366 ±(99.9%) 0.036 ms/op
Iteration   1: 1.917 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.917 ms/op


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
# Warmup Iteration   1: 4.292 ±(99.9%) 0.052 ms/op
Iteration   1: 3.205 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.205 ms/op


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
# Warmup Iteration   1: 14.139 ±(99.9%) 0.274 ms/op
Iteration   1: 9.233 ±(99.9%) 0.122 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.233 ms/op


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.095 ms/op
Iteration   1: 2.975 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.765 ms/op
                 createUser·p0.90:   3.537 ms/op
                 createUser·p0.95:   4.201 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  16.540 ms/op
                 createUser·p0.9999: 18.183 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10723
  mean =      2.975 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 2401 
    [ 2.500,  3.750) = 7465 
    [ 3.750,  5.000) = 635 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      3.537 ms/op
     p(95.0000) =      4.201 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     16.540 ms/op
     p(99.9900) =     18.183 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.012 ±(99.9%) 0.066 ms/op
Iteration   1: 1.717 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   1.606 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.277 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  20.939 ms/op
                 existUser·p0.9999: 21.918 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18717
  mean =      1.717 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18224 
    [ 2.500,  5.000) = 333 
    [ 5.000,  7.500) = 122 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      1.606 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.277 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =     20.939 ms/op
     p(99.9900) =     21.918 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 5.081 ±(99.9%) 0.290 ms/op
Iteration   1: 3.259 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.642 ms/op
                 getUser·p0.999:  7.916 ms/op
                 getUser·p0.9999: 9.732 ms/op
                 getUser·p1.00:   9.732 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9821
  mean =      3.259 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 16 
    [ 1.500,  2.000) = 98 
    [ 2.000,  2.500) = 1233 
    [ 2.500,  3.000) = 2356 
    [ 3.000,  3.500) = 2846 
    [ 3.500,  4.000) = 2112 
    [ 4.000,  4.500) = 770 
    [ 4.500,  5.000) = 141 
    [ 5.000,  5.500) = 131 
    [ 5.500,  6.000) = 66 
    [ 6.000,  6.500) = 10 
    [ 6.500,  7.000) = 8 
    [ 7.000,  7.500) = 10 
    [ 7.500,  8.000) = 18 
    [ 8.000,  8.500) = 3 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.642 ms/op
     p(99.9000) =      7.916 ms/op
     p(99.9900) =      9.732 ms/op
     p(99.9990) =      9.732 ms/op
     p(99.9999) =      9.732 ms/op
    p(100.0000) =      9.732 ms/op


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
# Warmup Iteration   1: 11.766 ±(99.9%) 0.327 ms/op
Iteration   1: 8.236 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   3.121 ms/op
                 listUser·p0.50:   7.799 ms/op
                 listUser·p0.90:   10.453 ms/op
                 listUser·p0.95:   11.920 ms/op
                 listUser·p0.99:   20.264 ms/op
                 listUser·p0.999:  32.117 ms/op
                 listUser·p0.9999: 33.063 ms/op
                 listUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3928
  mean =      8.236 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 92 
    [ 5.000,  7.500) = 1534 
    [ 7.500, 10.000) = 1804 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.121 ms/op
     p(50.0000) =      7.799 ms/op
     p(90.0000) =     10.453 ms/op
     p(95.0000) =     11.920 ms/op
     p(99.0000) =     20.264 ms/op
     p(99.9000) =     32.117 ms/op
     p(99.9900) =     33.063 ms/op
     p(99.9990) =     33.063 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.269          ops/ms
Client.existUser                       thrpt         10.689          ops/ms
Client.getUser                         thrpt          8.184          ops/ms
Client.listUser                        thrpt          3.475          ops/ms
Client.createUser                       avgt          3.339           ms/op
Client.existUser                        avgt          1.917           ms/op
Client.getUser                          avgt          3.205           ms/op
Client.listUser                         avgt          9.233           ms/op
Client.createUser                     sample  10723   2.975 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          0.839           ms/op
Client.createUser:createUser·p0.50    sample          2.765           ms/op
Client.createUser:createUser·p0.90    sample          3.537           ms/op
Client.createUser:createUser·p0.95    sample          4.201           ms/op
Client.createUser:createUser·p0.99    sample         10.158           ms/op
Client.createUser:createUser·p0.999   sample         16.540           ms/op
Client.createUser:createUser·p0.9999  sample         18.183           ms/op
Client.createUser:createUser·p1.00    sample         18.219           ms/op
Client.existUser                      sample  18717   1.717 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.618           ms/op
Client.existUser:existUser·p0.50      sample          1.606           ms/op
Client.existUser:existUser·p0.90      sample          2.126           ms/op
Client.existUser:existUser·p0.95      sample          2.277           ms/op
Client.existUser:existUser·p0.99      sample          3.928           ms/op
Client.existUser:existUser·p0.999     sample         20.939           ms/op
Client.existUser:existUser·p0.9999    sample         21.918           ms/op
Client.existUser:existUser·p1.00      sample         22.118           ms/op
Client.getUser                        sample   9821   3.259 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.098           ms/op
Client.getUser:getUser·p0.50          sample          3.260           ms/op
Client.getUser:getUser·p0.90          sample          4.071           ms/op
Client.getUser:getUser·p0.95          sample          4.301           ms/op
Client.getUser:getUser·p0.99          sample          5.642           ms/op
Client.getUser:getUser·p0.999         sample          7.916           ms/op
Client.getUser:getUser·p0.9999        sample          9.732           ms/op
Client.getUser:getUser·p1.00          sample          9.732           ms/op
Client.listUser                       sample   3928   8.236 ± 0.137   ms/op
Client.listUser:listUser·p0.00        sample          3.121           ms/op
Client.listUser:listUser·p0.50        sample          7.799           ms/op
Client.listUser:listUser·p0.90        sample         10.453           ms/op
Client.listUser:listUser·p0.95        sample         11.920           ms/op
Client.listUser:listUser·p0.99        sample         20.264           ms/op
Client.listUser:listUser·p0.999       sample         32.117           ms/op
Client.listUser:listUser·p0.9999      sample         33.063           ms/op
Client.listUser:listUser·p1.00        sample         33.063           ms/op
