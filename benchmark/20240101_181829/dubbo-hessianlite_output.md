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
# Warmup Iteration   1: 1.989 ops/ms
Iteration   1: 5.222 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.222 ops/ms


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
# Warmup Iteration   1: 5.000 ops/ms
Iteration   1: 12.075 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.075 ops/ms


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
# Warmup Iteration   1: 4.050 ops/ms
Iteration   1: 9.372 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.372 ops/ms


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
# Warmup Iteration   1: 2.020 ops/ms
Iteration   1: 3.121 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.121 ops/ms


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
# Warmup Iteration   1: 5.762 ±(99.9%) 0.094 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.979 ms/op


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
# Warmup Iteration   1: 3.044 ±(99.9%) 0.031 ms/op
Iteration   1: 2.085 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.085 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.189 ±(99.9%) 0.079 ms/op
Iteration   1: 2.965 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.965 ms/op


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
# Warmup Iteration   1: 11.819 ±(99.9%) 0.169 ms/op
Iteration   1: 8.560 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.560 ms/op


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
# Warmup Iteration   1: 5.393 ±(99.9%) 0.139 ms/op
Iteration   1: 3.190 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.340 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  11.469 ms/op
                 createUser·p0.9999: 11.944 ms/op
                 createUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10024
  mean =      3.190 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1036 
    [ 2.500,  3.750) = 7789 
    [ 3.750,  5.000) = 895 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.340 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     11.944 ms/op
     p(99.9990) =     11.944 ms/op
     p(99.9999) =     11.944 ms/op
    p(100.0000) =     11.944 ms/op


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
# Warmup Iteration   1: 3.082 ±(99.9%) 0.082 ms/op
Iteration   1: 2.011 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   1.933 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   5.421 ms/op
                 existUser·p0.999:  16.566 ms/op
                 existUser·p0.9999: 17.114 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15904
  mean =      2.011 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 429 
    [ 1.250,  2.500) = 14401 
    [ 2.500,  3.750) = 797 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      5.421 ms/op
     p(99.9000) =     16.566 ms/op
     p(99.9900) =     17.114 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.099 ms/op
Iteration   1: 2.762 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.691 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   5.198 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 11.288 ms/op
                 getUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11571
  mean =      2.762 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 4317 
    [ 2.500,  3.750) = 6565 
    [ 3.750,  5.000) = 547 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.691 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.198 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     11.288 ms/op
     p(99.9990) =     11.452 ms/op
     p(99.9999) =     11.452 ms/op
    p(100.0000) =     11.452 ms/op


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
# Warmup Iteration   1: 12.088 ±(99.9%) 0.471 ms/op
Iteration   1: 7.649 ±(99.9%) 0.109 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   7.283 ms/op
                 listUser·p0.90:   10.060 ms/op
                 listUser·p0.95:   11.567 ms/op
                 listUser·p0.99:   15.902 ms/op
                 listUser·p0.999:  19.459 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4179
  mean =      7.649 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 183 
    [ 5.000,  7.500) = 2146 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      7.283 ms/op
     p(90.0000) =     10.060 ms/op
     p(95.0000) =     11.567 ms/op
     p(99.0000) =     15.902 ms/op
     p(99.9000) =     19.459 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.222          ops/ms
Client.existUser                       thrpt         12.075          ops/ms
Client.getUser                         thrpt          9.372          ops/ms
Client.listUser                        thrpt          3.121          ops/ms
Client.createUser                       avgt          2.979           ms/op
Client.existUser                        avgt          2.085           ms/op
Client.getUser                          avgt          2.965           ms/op
Client.listUser                         avgt          8.560           ms/op
Client.createUser                     sample  10024   3.190 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.219           ms/op
Client.createUser:createUser·p0.50    sample          3.015           ms/op
Client.createUser:createUser·p0.90    sample          3.834           ms/op
Client.createUser:createUser·p0.95    sample          4.340           ms/op
Client.createUser:createUser·p0.99    sample          7.700           ms/op
Client.createUser:createUser·p0.999   sample         11.469           ms/op
Client.createUser:createUser·p0.9999  sample         11.944           ms/op
Client.createUser:createUser·p1.00    sample         11.944           ms/op
Client.existUser                      sample  15904   2.011 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.549           ms/op
Client.existUser:existUser·p0.50      sample          1.933           ms/op
Client.existUser:existUser·p0.90      sample          2.413           ms/op
Client.existUser:existUser·p0.95      sample          2.597           ms/op
Client.existUser:existUser·p0.99      sample          5.421           ms/op
Client.existUser:existUser·p0.999     sample         16.566           ms/op
Client.existUser:existUser·p0.9999    sample         17.114           ms/op
Client.existUser:existUser·p1.00      sample         17.269           ms/op
Client.getUser                        sample  11571   2.762 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.701           ms/op
Client.getUser:getUser·p0.50          sample          2.691           ms/op
Client.getUser:getUser·p0.90          sample          3.457           ms/op
Client.getUser:getUser·p0.95          sample          3.817           ms/op
Client.getUser:getUser·p0.99          sample          5.198           ms/op
Client.getUser:getUser·p0.999         sample         10.273           ms/op
Client.getUser:getUser·p0.9999        sample         11.288           ms/op
Client.getUser:getUser·p1.00          sample         11.452           ms/op
Client.listUser                       sample   4179   7.649 ± 0.109   ms/op
Client.listUser:listUser·p0.00        sample          2.179           ms/op
Client.listUser:listUser·p0.50        sample          7.283           ms/op
Client.listUser:listUser·p0.90        sample         10.060           ms/op
Client.listUser:listUser·p0.95        sample         11.567           ms/op
Client.listUser:listUser·p0.99        sample         15.902           ms/op
Client.listUser:listUser·p0.999       sample         19.459           ms/op
Client.listUser:listUser·p0.9999      sample         22.348           ms/op
Client.listUser:listUser·p1.00        sample         22.348           ms/op
