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
# Warmup Iteration   1: 2.220 ops/ms
Iteration   1: 5.725 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.725 ops/ms


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
# Warmup Iteration   1: 6.197 ops/ms
Iteration   1: 13.335 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.335 ops/ms


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
# Warmup Iteration   1: 4.033 ops/ms
Iteration   1: 8.501 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.501 ops/ms


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
# Warmup Iteration   1: 1.981 ops/ms
Iteration   1: 3.615 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.615 ops/ms


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
# Warmup Iteration   1: 5.840 ±(99.9%) 0.075 ms/op
Iteration   1: 3.379 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.379 ms/op


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
# Warmup Iteration   1: 3.065 ±(99.9%) 0.033 ms/op
Iteration   1: 2.002 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.002 ms/op


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
# Warmup Iteration   1: 4.903 ±(99.9%) 0.051 ms/op
Iteration   1: 3.286 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.286 ms/op


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
# Warmup Iteration   1: 11.176 ±(99.9%) 0.159 ms/op
Iteration   1: 8.444 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.444 ms/op


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
# Warmup Iteration   1: 5.104 ±(99.9%) 0.113 ms/op
Iteration   1: 2.958 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   2.896 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.558 ms/op
                 createUser·p0.999:  10.174 ms/op
                 createUser·p0.9999: 11.193 ms/op
                 createUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10951
  mean =      2.958 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 476 
    [ 2.000,  3.000) = 5903 
    [ 3.000,  4.000) = 3849 
    [ 4.000,  5.000) = 557 
    [ 5.000,  6.000) = 84 
    [ 6.000,  7.000) = 34 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 15 
    [ 9.000, 10.000) = 14 
    [10.000, 11.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.558 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     11.193 ms/op
     p(99.9990) =     11.239 ms/op
     p(99.9999) =     11.239 ms/op
    p(100.0000) =     11.239 ms/op


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
# Warmup Iteration   1: 3.001 ±(99.9%) 0.070 ms/op
Iteration   1: 1.541 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   1.540 ms/op
                 existUser·p0.90:   1.880 ms/op
                 existUser·p0.95:   2.054 ms/op
                 existUser·p0.99:   2.897 ms/op
                 existUser·p0.999:  10.060 ms/op
                 existUser·p0.9999: 10.270 ms/op
                 existUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 20768
  mean =      1.541 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4517 
    [ 1.250,  2.500) = 15943 
    [ 2.500,  3.750) = 166 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      1.540 ms/op
     p(90.0000) =      1.880 ms/op
     p(95.0000) =      2.054 ms/op
     p(99.0000) =      2.897 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     10.270 ms/op
     p(99.9990) =     11.092 ms/op
     p(99.9999) =     11.092 ms/op
    p(100.0000) =     11.092 ms/op


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.107 ms/op
Iteration   1: 3.079 ±(99.9%) 0.059 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   2.867 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.302 ms/op
                 getUser·p0.999:  35.193 ms/op
                 getUser·p0.9999: 36.304 ms/op
                 getUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10381
  mean =      3.079 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1247 
    [ 2.500,  5.000) = 9004 
    [ 5.000,  7.500) = 88 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.302 ms/op
     p(99.9000) =     35.193 ms/op
     p(99.9900) =     36.304 ms/op
     p(99.9990) =     36.307 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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
# Warmup Iteration   1: 11.101 ±(99.9%) 0.406 ms/op
Iteration   1: 8.130 ±(99.9%) 0.125 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   7.746 ms/op
                 listUser·p0.90:   10.502 ms/op
                 listUser·p0.95:   11.611 ms/op
                 listUser·p0.99:   19.562 ms/op
                 listUser·p0.999:  20.746 ms/op
                 listUser·p0.9999: 20.972 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3946
  mean =      8.130 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 150 
    [ 5.000,  7.500) = 1576 
    [ 7.500, 10.000) = 1654 
    [10.000, 12.500) = 433 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      7.746 ms/op
     p(90.0000) =     10.502 ms/op
     p(95.0000) =     11.611 ms/op
     p(99.0000) =     19.562 ms/op
     p(99.9000) =     20.746 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.725          ops/ms
Client.existUser                       thrpt         13.335          ops/ms
Client.getUser                         thrpt          8.501          ops/ms
Client.listUser                        thrpt          3.615          ops/ms
Client.createUser                       avgt          3.379           ms/op
Client.existUser                        avgt          2.002           ms/op
Client.getUser                          avgt          3.286           ms/op
Client.listUser                         avgt          8.444           ms/op
Client.createUser                     sample  10951   2.958 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.315           ms/op
Client.createUser:createUser·p0.50    sample          2.896           ms/op
Client.createUser:createUser·p0.90    sample          3.715           ms/op
Client.createUser:createUser·p0.95    sample          4.166           ms/op
Client.createUser:createUser·p0.99    sample          5.558           ms/op
Client.createUser:createUser·p0.999   sample         10.174           ms/op
Client.createUser:createUser·p0.9999  sample         11.193           ms/op
Client.createUser:createUser·p1.00    sample         11.239           ms/op
Client.existUser                      sample  20768   1.541 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.707           ms/op
Client.existUser:existUser·p0.50      sample          1.540           ms/op
Client.existUser:existUser·p0.90      sample          1.880           ms/op
Client.existUser:existUser·p0.95      sample          2.054           ms/op
Client.existUser:existUser·p0.99      sample          2.897           ms/op
Client.existUser:existUser·p0.999     sample         10.060           ms/op
Client.existUser:existUser·p0.9999    sample         10.270           ms/op
Client.existUser:existUser·p1.00      sample         11.092           ms/op
Client.getUser                        sample  10381   3.079 ± 0.059   ms/op
Client.getUser:getUser·p0.00          sample          0.781           ms/op
Client.getUser:getUser·p0.50          sample          2.867           ms/op
Client.getUser:getUser·p0.90          sample          3.637           ms/op
Client.getUser:getUser·p0.95          sample          4.030           ms/op
Client.getUser:getUser·p0.99          sample          5.302           ms/op
Client.getUser:getUser·p0.999         sample         35.193           ms/op
Client.getUser:getUser·p0.9999        sample         36.304           ms/op
Client.getUser:getUser·p1.00          sample         36.307           ms/op
Client.listUser                       sample   3946   8.130 ± 0.125   ms/op
Client.listUser:listUser·p0.00        sample          1.241           ms/op
Client.listUser:listUser·p0.50        sample          7.746           ms/op
Client.listUser:listUser·p0.90        sample         10.502           ms/op
Client.listUser:listUser·p0.95        sample         11.611           ms/op
Client.listUser:listUser·p0.99        sample         19.562           ms/op
Client.listUser:listUser·p0.999       sample         20.746           ms/op
Client.listUser:listUser·p0.9999      sample         20.972           ms/op
Client.listUser:listUser·p1.00        sample         20.972           ms/op
