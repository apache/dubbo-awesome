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
# Warmup Iteration   1: 2.412 ops/ms
Iteration   1: 6.637 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.637 ops/ms


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
# Warmup Iteration   1: 6.011 ops/ms
Iteration   1: 14.480 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.480 ops/ms


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
# Warmup Iteration   1: 4.823 ops/ms
Iteration   1: 8.997 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.997 ops/ms


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
# Warmup Iteration   1: 2.459 ops/ms
Iteration   1: 3.692 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.692 ops/ms


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
# Warmup Iteration   1: 5.218 ±(99.9%) 0.057 ms/op
Iteration   1: 3.190 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.190 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.037 ms/op
Iteration   1: 2.079 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.079 ms/op


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
# Warmup Iteration   1: 4.947 ±(99.9%) 0.072 ms/op
Iteration   1: 3.038 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.038 ms/op


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
# Warmup Iteration   1: 11.879 ±(99.9%) 0.256 ms/op
Iteration   1: 7.786 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.786 ms/op


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
# Warmup Iteration   1: 5.387 ±(99.9%) 0.150 ms/op
Iteration   1: 2.996 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   2.703 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   7.791 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10656
  mean =      2.996 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 3151 
    [ 2.500,  3.750) = 6366 
    [ 3.750,  5.000) = 836 
    [ 5.000,  6.250) = 118 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      2.703 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 3.390 ±(99.9%) 0.093 ms/op
Iteration   1: 1.883 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.359 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.511 ms/op
                 existUser·p0.99:   3.006 ms/op
                 existUser·p0.999:  4.801 ms/op
                 existUser·p0.9999: 5.408 ms/op
                 existUser·p1.00:   5.489 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16999
  mean =      1.883 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 3 
    [0.500, 1.000) = 54 
    [1.000, 1.500) = 1759 
    [1.500, 2.000) = 9726 
    [2.000, 2.500) = 4570 
    [2.500, 3.000) = 713 
    [3.000, 3.500) = 66 
    [3.500, 4.000) = 57 
    [4.000, 4.500) = 8 
    [4.500, 5.000) = 38 
    [5.000, 5.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      3.006 ms/op
     p(99.9000) =      4.801 ms/op
     p(99.9900) =      5.408 ms/op
     p(99.9990) =      5.489 ms/op
     p(99.9999) =      5.489 ms/op
    p(100.0000) =      5.489 ms/op


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.103 ms/op
Iteration   1: 3.513 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.470 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 15.270 ms/op
                 getUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9040
  mean =      3.513 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 819 
    [ 2.500,  3.750) = 5559 
    [ 3.750,  5.000) = 2271 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.470 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     15.270 ms/op
     p(99.9990) =     15.270 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 11.573 ±(99.9%) 0.399 ms/op
Iteration   1: 8.115 ±(99.9%) 0.125 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   7.635 ms/op
                 listUser·p0.90:   10.781 ms/op
                 listUser·p0.95:   12.091 ms/op
                 listUser·p0.99:   17.319 ms/op
                 listUser·p0.999:  24.947 ms/op
                 listUser·p0.9999: 27.263 ms/op
                 listUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3946
  mean =      8.115 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 81 
    [ 5.000,  7.500) = 1788 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 493 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.523 ms/op
     p(50.0000) =      7.635 ms/op
     p(90.0000) =     10.781 ms/op
     p(95.0000) =     12.091 ms/op
     p(99.0000) =     17.319 ms/op
     p(99.9000) =     24.947 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.637          ops/ms
Client.existUser                       thrpt         14.480          ops/ms
Client.getUser                         thrpt          8.997          ops/ms
Client.listUser                        thrpt          3.692          ops/ms
Client.createUser                       avgt          3.190           ms/op
Client.existUser                        avgt          2.079           ms/op
Client.getUser                          avgt          3.038           ms/op
Client.listUser                         avgt          7.786           ms/op
Client.createUser                     sample  10656   2.996 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.114           ms/op
Client.createUser:createUser·p0.50    sample          2.703           ms/op
Client.createUser:createUser·p0.90    sample          3.891           ms/op
Client.createUser:createUser·p0.95    sample          4.538           ms/op
Client.createUser:createUser·p0.99    sample          7.791           ms/op
Client.createUser:createUser·p0.999   sample         18.481           ms/op
Client.createUser:createUser·p0.9999  sample         18.579           ms/op
Client.createUser:createUser·p1.00    sample         18.579           ms/op
Client.existUser                      sample  16999   1.883 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.359           ms/op
Client.existUser:existUser·p0.50      sample          1.829           ms/op
Client.existUser:existUser·p0.90      sample          2.310           ms/op
Client.existUser:existUser·p0.95      sample          2.511           ms/op
Client.existUser:existUser·p0.99      sample          3.006           ms/op
Client.existUser:existUser·p0.999     sample          4.801           ms/op
Client.existUser:existUser·p0.9999    sample          5.408           ms/op
Client.existUser:existUser·p1.00      sample          5.489           ms/op
Client.getUser                        sample   9040   3.513 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          1.028           ms/op
Client.getUser:getUser·p0.50          sample          3.449           ms/op
Client.getUser:getUser·p0.90          sample          4.383           ms/op
Client.getUser:getUser·p0.95          sample          4.915           ms/op
Client.getUser:getUser·p0.99          sample          6.470           ms/op
Client.getUser:getUser·p0.999         sample         11.076           ms/op
Client.getUser:getUser·p0.9999        sample         15.270           ms/op
Client.getUser:getUser·p1.00          sample         15.270           ms/op
Client.listUser                       sample   3946   8.115 ± 0.125   ms/op
Client.listUser:listUser·p0.00        sample          2.523           ms/op
Client.listUser:listUser·p0.50        sample          7.635           ms/op
Client.listUser:listUser·p0.90        sample         10.781           ms/op
Client.listUser:listUser·p0.95        sample         12.091           ms/op
Client.listUser:listUser·p0.99        sample         17.319           ms/op
Client.listUser:listUser·p0.999       sample         24.947           ms/op
Client.listUser:listUser·p0.9999      sample         27.263           ms/op
Client.listUser:listUser·p1.00        sample         27.263           ms/op
