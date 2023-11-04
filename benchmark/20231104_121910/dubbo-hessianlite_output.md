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
# Warmup Iteration   1: 2.252 ops/ms
Iteration   1: 6.315 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.315 ops/ms


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
# Warmup Iteration   1: 6.764 ops/ms
Iteration   1: 13.148 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.148 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.822 ops/ms
Iteration   1: 9.405 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.405 ops/ms


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
# Warmup Iteration   1: 2.039 ops/ms
Iteration   1: 3.544 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.544 ops/ms


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
# Warmup Iteration   1: 5.141 ±(99.9%) 0.049 ms/op
Iteration   1: 3.039 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.039 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.042 ms/op
Iteration   1: 2.068 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.068 ms/op


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
# Warmup Iteration   1: 4.863 ±(99.9%) 0.079 ms/op
Iteration   1: 3.297 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.297 ms/op


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
# Warmup Iteration   1: 13.598 ±(99.9%) 0.278 ms/op
Iteration   1: 7.942 ±(99.9%) 0.105 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.942 ms/op


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.102 ms/op
Iteration   1: 2.929 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   2.720 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   9.421 ms/op
                 createUser·p0.999:  20.319 ms/op
                 createUser·p0.9999: 22.023 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10909
  mean =      2.929 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3478 
    [ 2.500,  5.000) = 7167 
    [ 5.000,  7.500) = 104 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      2.720 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     20.319 ms/op
     p(99.9900) =     22.023 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 2.929 ±(99.9%) 0.051 ms/op
Iteration   1: 1.793 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.380 ms/op
                 existUser·p0.99:   3.403 ms/op
                 existUser·p0.999:  15.945 ms/op
                 existUser·p0.9999: 16.222 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17821
  mean =      1.793 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 764 
    [ 1.250,  2.500) = 16366 
    [ 2.500,  3.750) = 534 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.380 ms/op
     p(99.0000) =      3.403 ms/op
     p(99.9000) =     15.945 ms/op
     p(99.9900) =     16.222 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.159 ±(99.9%) 0.090 ms/op
Iteration   1: 3.095 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.059 ms/op
                 getUser·p0.999:  6.256 ms/op
                 getUser·p0.9999: 8.131 ms/op
                 getUser·p1.00:   8.167 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10340
  mean =      3.095 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 153 
    [2.000, 2.500) = 1663 
    [2.500, 3.000) = 3139 
    [3.000, 3.500) = 3120 
    [3.500, 4.000) = 1336 
    [4.000, 4.500) = 569 
    [4.500, 5.000) = 214 
    [5.000, 5.500) = 68 
    [5.500, 6.000) = 42 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.059 ms/op
     p(99.9000) =      6.256 ms/op
     p(99.9900) =      8.131 ms/op
     p(99.9990) =      8.167 ms/op
     p(99.9999) =      8.167 ms/op
    p(100.0000) =      8.167 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 10.745 ±(99.9%) 0.339 ms/op
Iteration   1: 7.825 ±(99.9%) 0.104 ms/op
                 listUser·p0.00:   2.834 ms/op
                 listUser·p0.50:   7.569 ms/op
                 listUser·p0.90:   10.420 ms/op
                 listUser·p0.95:   11.444 ms/op
                 listUser·p0.99:   14.141 ms/op
                 listUser·p0.999:  18.683 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4094
  mean =      7.825 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 18 
    [ 3.750,  5.000) = 165 
    [ 5.000,  6.250) = 633 
    [ 6.250,  7.500) = 1187 
    [ 7.500,  8.750) = 1016 
    [ 8.750, 10.000) = 549 
    [10.000, 11.250) = 307 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.834 ms/op
     p(50.0000) =      7.569 ms/op
     p(90.0000) =     10.420 ms/op
     p(95.0000) =     11.444 ms/op
     p(99.0000) =     14.141 ms/op
     p(99.9000) =     18.683 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.315          ops/ms
Client.existUser                       thrpt         13.148          ops/ms
Client.getUser                         thrpt          9.405          ops/ms
Client.listUser                        thrpt          3.544          ops/ms
Client.createUser                       avgt          3.039           ms/op
Client.existUser                        avgt          2.068           ms/op
Client.getUser                          avgt          3.297           ms/op
Client.listUser                         avgt          7.942           ms/op
Client.createUser                     sample  10909   2.929 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.137           ms/op
Client.createUser:createUser·p0.50    sample          2.720           ms/op
Client.createUser:createUser·p0.90    sample          3.478           ms/op
Client.createUser:createUser·p0.95    sample          3.944           ms/op
Client.createUser:createUser·p0.99    sample          9.421           ms/op
Client.createUser:createUser·p0.999   sample         20.319           ms/op
Client.createUser:createUser·p0.9999  sample         22.023           ms/op
Client.createUser:createUser·p1.00    sample         22.053           ms/op
Client.existUser                      sample  17821   1.793 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.627           ms/op
Client.existUser:existUser·p0.50      sample          1.681           ms/op
Client.existUser:existUser·p0.90      sample          2.216           ms/op
Client.existUser:existUser·p0.95      sample          2.380           ms/op
Client.existUser:existUser·p0.99      sample          3.403           ms/op
Client.existUser:existUser·p0.999     sample         15.945           ms/op
Client.existUser:existUser·p0.9999    sample         16.222           ms/op
Client.existUser:existUser·p1.00      sample         16.876           ms/op
Client.getUser                        sample  10340   3.095 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.946           ms/op
Client.getUser:getUser·p0.50          sample          3.027           ms/op
Client.getUser:getUser·p0.90          sample          3.920           ms/op
Client.getUser:getUser·p0.95          sample          4.309           ms/op
Client.getUser:getUser·p0.99          sample          5.059           ms/op
Client.getUser:getUser·p0.999         sample          6.256           ms/op
Client.getUser:getUser·p0.9999        sample          8.131           ms/op
Client.getUser:getUser·p1.00          sample          8.167           ms/op
Client.listUser                       sample   4094   7.825 ± 0.104   ms/op
Client.listUser:listUser·p0.00        sample          2.834           ms/op
Client.listUser:listUser·p0.50        sample          7.569           ms/op
Client.listUser:listUser·p0.90        sample         10.420           ms/op
Client.listUser:listUser·p0.95        sample         11.444           ms/op
Client.listUser:listUser·p0.99        sample         14.141           ms/op
Client.listUser:listUser·p0.999       sample         18.683           ms/op
Client.listUser:listUser·p0.9999      sample         19.595           ms/op
Client.listUser:listUser·p1.00        sample         19.595           ms/op
