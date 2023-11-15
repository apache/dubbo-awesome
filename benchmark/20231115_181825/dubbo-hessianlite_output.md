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
# Warmup Iteration   1: 2.638 ops/ms
Iteration   1: 6.302 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.302 ops/ms


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
# Warmup Iteration   1: 6.517 ops/ms
Iteration   1: 13.327 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.327 ops/ms


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
# Warmup Iteration   1: 4.300 ops/ms
Iteration   1: 9.279 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.279 ops/ms


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
# Warmup Iteration   1: 2.305 ops/ms
Iteration   1: 3.502 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.502 ops/ms


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
# Warmup Iteration   1: 5.635 ±(99.9%) 0.086 ms/op
Iteration   1: 3.088 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.088 ms/op


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
# Warmup Iteration   1: 2.720 ±(99.9%) 0.032 ms/op
Iteration   1: 2.030 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.030 ms/op


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.058 ms/op
Iteration   1: 3.038 ±(99.9%) 0.013 ms/op


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
# Warmup Iteration   1: 13.310 ±(99.9%) 0.351 ms/op
Iteration   1: 8.205 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.205 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.881 ±(99.9%) 0.091 ms/op
Iteration   1: 3.240 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.670 ms/op
                 createUser·p0.999:  12.765 ms/op
                 createUser·p0.9999: 13.746 ms/op
                 createUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9915
  mean =      3.240 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 1391 
    [ 2.500,  3.750) = 7120 
    [ 3.750,  5.000) = 1106 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.670 ms/op
     p(99.9000) =     12.765 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 3.023 ±(99.9%) 0.071 ms/op
Iteration   1: 1.796 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.253 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  17.020 ms/op
                 existUser·p0.9999: 17.272 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17802
  mean =      1.796 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1222 
    [ 1.250,  2.500) = 15636 
    [ 2.500,  3.750) = 720 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.253 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =     17.020 ms/op
     p(99.9900) =     17.272 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.088 ms/op
Iteration   1: 2.657 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.435 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 11.793 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12026
  mean =      2.657 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 6702 
    [ 2.500,  3.750) = 4619 
    [ 3.750,  5.000) = 522 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.435 ms/op
     p(99.9000) =     11.698 ms/op
     p(99.9900) =     11.793 ms/op
     p(99.9990) =     11.796 ms/op
     p(99.9999) =     11.796 ms/op
    p(100.0000) =     11.796 ms/op


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
# Warmup Iteration   1: 11.640 ±(99.9%) 0.415 ms/op
Iteration   1: 8.084 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   7.614 ms/op
                 listUser·p0.90:   11.212 ms/op
                 listUser·p0.95:   13.134 ms/op
                 listUser·p0.99:   17.110 ms/op
                 listUser·p0.999:  21.565 ms/op
                 listUser·p0.9999: 24.478 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3986
  mean =      8.084 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 204 
    [ 5.000,  7.500) = 1697 
    [ 7.500, 10.000) = 1371 
    [10.000, 12.500) = 431 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      7.614 ms/op
     p(90.0000) =     11.212 ms/op
     p(95.0000) =     13.134 ms/op
     p(99.0000) =     17.110 ms/op
     p(99.9000) =     21.565 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.302          ops/ms
Client.existUser                       thrpt         13.327          ops/ms
Client.getUser                         thrpt          9.279          ops/ms
Client.listUser                        thrpt          3.502          ops/ms
Client.createUser                       avgt          3.088           ms/op
Client.existUser                        avgt          2.030           ms/op
Client.getUser                          avgt          3.038           ms/op
Client.listUser                         avgt          8.205           ms/op
Client.createUser                     sample   9915   3.240 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          0.756           ms/op
Client.createUser:createUser·p0.50    sample          3.166           ms/op
Client.createUser:createUser·p0.90    sample          4.022           ms/op
Client.createUser:createUser·p0.95    sample          4.555           ms/op
Client.createUser:createUser·p0.99    sample          6.670           ms/op
Client.createUser:createUser·p0.999   sample         12.765           ms/op
Client.createUser:createUser·p0.9999  sample         13.746           ms/op
Client.createUser:createUser·p1.00    sample         13.746           ms/op
Client.existUser                      sample  17802   1.796 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.699           ms/op
Client.existUser:existUser·p0.50      sample          1.667           ms/op
Client.existUser:existUser·p0.90      sample          2.253           ms/op
Client.existUser:existUser·p0.95      sample          2.523           ms/op
Client.existUser:existUser·p0.99      sample          4.194           ms/op
Client.existUser:existUser·p0.999     sample         17.020           ms/op
Client.existUser:existUser·p0.9999    sample         17.272           ms/op
Client.existUser:existUser·p1.00      sample         17.400           ms/op
Client.getUser                        sample  12026   2.657 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.916           ms/op
Client.getUser:getUser·p0.50          sample          2.449           ms/op
Client.getUser:getUser·p0.90          sample          3.351           ms/op
Client.getUser:getUser·p0.95          sample          3.842           ms/op
Client.getUser:getUser·p0.99          sample          5.435           ms/op
Client.getUser:getUser·p0.999         sample         11.698           ms/op
Client.getUser:getUser·p0.9999        sample         11.793           ms/op
Client.getUser:getUser·p1.00          sample         11.796           ms/op
Client.listUser                       sample   3986   8.084 ± 0.137   ms/op
Client.listUser:listUser·p0.00        sample          1.491           ms/op
Client.listUser:listUser·p0.50        sample          7.614           ms/op
Client.listUser:listUser·p0.90        sample         11.212           ms/op
Client.listUser:listUser·p0.95        sample         13.134           ms/op
Client.listUser:listUser·p0.99        sample         17.110           ms/op
Client.listUser:listUser·p0.999       sample         21.565           ms/op
Client.listUser:listUser·p0.9999      sample         24.478           ms/op
Client.listUser:listUser·p1.00        sample         24.478           ms/op
