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
# Warmup Iteration   1: 2.471 ops/ms
Iteration   1: 6.338 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.338 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.518 ops/ms
Iteration   1: 16.107 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  16.107 ops/ms


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
# Warmup Iteration   1: 4.717 ops/ms
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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.142 ops/ms
Iteration   1: 3.167 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.167 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.095 ±(99.9%) 0.043 ms/op
Iteration   1: 3.063 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.063 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.105 ±(99.9%) 0.035 ms/op
Iteration   1: 1.828 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.828 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.091 ms/op
Iteration   1: 3.726 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.726 ms/op


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
# Warmup Iteration   1: 11.801 ±(99.9%) 0.252 ms/op
Iteration   1: 8.948 ±(99.9%) 0.124 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.948 ms/op


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
# Warmup Iteration   1: 4.928 ±(99.9%) 0.089 ms/op
Iteration   1: 3.112 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.822 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   8.778 ms/op
                 createUser·p0.999:  22.020 ms/op
                 createUser·p0.9999: 22.117 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10324
  mean =      3.112 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2716 
    [ 2.500,  5.000) = 7195 
    [ 5.000,  7.500) = 264 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      8.778 ms/op
     p(99.9000) =     22.020 ms/op
     p(99.9900) =     22.117 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.179 ±(99.9%) 0.059 ms/op
Iteration   1: 2.127 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.389 ms/op
                 existUser·p0.50:   2.085 ms/op
                 existUser·p0.90:   2.617 ms/op
                 existUser·p0.95:   2.816 ms/op
                 existUser·p0.99:   3.934 ms/op
                 existUser·p0.999:  15.056 ms/op
                 existUser·p0.9999: 15.171 ms/op
                 existUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15068
  mean =      2.127 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 12511 
    [ 2.500,  3.750) = 2029 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.816 ms/op
     p(99.0000) =      3.934 ms/op
     p(99.9000) =     15.056 ms/op
     p(99.9900) =     15.171 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 4.503 ±(99.9%) 0.107 ms/op
Iteration   1: 3.138 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.163 ms/op
                 getUser·p0.999:  15.565 ms/op
                 getUser·p0.9999: 16.284 ms/op
                 getUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10236
  mean =      3.138 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 1980 
    [ 2.500,  3.750) = 6534 
    [ 3.750,  5.000) = 1491 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.163 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     16.284 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 12.197 ±(99.9%) 0.364 ms/op
Iteration   1: 9.198 ±(99.9%) 0.143 ms/op
                 listUser·p0.00:   3.346 ms/op
                 listUser·p0.50:   8.995 ms/op
                 listUser·p0.90:   12.263 ms/op
                 listUser·p0.95:   13.746 ms/op
                 listUser·p0.99:   17.498 ms/op
                 listUser·p0.999:  20.016 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3474
  mean =      9.198 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 82 
    [ 5.000,  7.500) = 871 
    [ 7.500, 10.000) = 1303 
    [10.000, 12.500) = 922 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.346 ms/op
     p(50.0000) =      8.995 ms/op
     p(90.0000) =     12.263 ms/op
     p(95.0000) =     13.746 ms/op
     p(99.0000) =     17.498 ms/op
     p(99.9000) =     20.016 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.338          ops/ms
Client.existUser                       thrpt         16.107          ops/ms
Client.getUser                         thrpt          9.405          ops/ms
Client.listUser                        thrpt          3.167          ops/ms
Client.createUser                       avgt          3.063           ms/op
Client.existUser                        avgt          1.828           ms/op
Client.getUser                          avgt          3.726           ms/op
Client.listUser                         avgt          8.948           ms/op
Client.createUser                     sample  10324   3.112 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          1.044           ms/op
Client.createUser:createUser·p0.50    sample          2.822           ms/op
Client.createUser:createUser·p0.90    sample          3.801           ms/op
Client.createUser:createUser·p0.95    sample          4.530           ms/op
Client.createUser:createUser·p0.99    sample          8.778           ms/op
Client.createUser:createUser·p0.999   sample         22.020           ms/op
Client.createUser:createUser·p0.9999  sample         22.117           ms/op
Client.createUser:createUser·p1.00    sample         22.118           ms/op
Client.existUser                      sample  15068   2.127 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.389           ms/op
Client.existUser:existUser·p0.50      sample          2.085           ms/op
Client.existUser:existUser·p0.90      sample          2.617           ms/op
Client.existUser:existUser·p0.95      sample          2.816           ms/op
Client.existUser:existUser·p0.99      sample          3.934           ms/op
Client.existUser:existUser·p0.999     sample         15.056           ms/op
Client.existUser:existUser·p0.9999    sample         15.171           ms/op
Client.existUser:existUser·p1.00      sample         15.188           ms/op
Client.getUser                        sample  10236   3.138 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          0.896           ms/op
Client.getUser:getUser·p0.50          sample          3.056           ms/op
Client.getUser:getUser·p0.90          sample          3.957           ms/op
Client.getUser:getUser·p0.95          sample          4.293           ms/op
Client.getUser:getUser·p0.99          sample          6.163           ms/op
Client.getUser:getUser·p0.999         sample         15.565           ms/op
Client.getUser:getUser·p0.9999        sample         16.284           ms/op
Client.getUser:getUser·p1.00          sample         16.286           ms/op
Client.listUser                       sample   3474   9.198 ± 0.143   ms/op
Client.listUser:listUser·p0.00        sample          3.346           ms/op
Client.listUser:listUser·p0.50        sample          8.995           ms/op
Client.listUser:listUser·p0.90        sample         12.263           ms/op
Client.listUser:listUser·p0.95        sample         13.746           ms/op
Client.listUser:listUser·p0.99        sample         17.498           ms/op
Client.listUser:listUser·p0.999       sample         20.016           ms/op
Client.listUser:listUser·p0.9999      sample         20.611           ms/op
Client.listUser:listUser·p1.00        sample         20.611           ms/op
