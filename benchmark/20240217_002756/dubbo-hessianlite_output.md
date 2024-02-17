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
# Warmup Iteration   1: 2.252 ops/ms
Iteration   1: 5.638 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.638 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.504 ops/ms
Iteration   1: 11.443 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.443 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.264 ops/ms
Iteration   1: 7.680 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.680 ops/ms


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
# Warmup Iteration   1: 2.065 ops/ms
Iteration   1: 3.932 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.932 ops/ms


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
# Warmup Iteration   1: 5.554 ±(99.9%) 0.061 ms/op
Iteration   1: 3.310 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.310 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.039 ms/op
Iteration   1: 1.723 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.723 ms/op


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
# Warmup Iteration   1: 4.999 ±(99.9%) 0.047 ms/op
Iteration   1: 2.984 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.984 ms/op


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
# Warmup Iteration   1: 11.678 ±(99.9%) 0.158 ms/op
Iteration   1: 8.036 ±(99.9%) 0.124 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.036 ms/op


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
# Warmup Iteration   1: 5.234 ±(99.9%) 0.124 ms/op
Iteration   1: 3.019 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   2.888 ms/op
                 createUser·p0.90:   3.788 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  11.647 ms/op
                 createUser·p0.9999: 13.450 ms/op
                 createUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10582
  mean =      3.019 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2035 
    [ 2.500,  3.750) = 7425 
    [ 3.750,  5.000) = 972 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.788 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     11.647 ms/op
     p(99.9900) =     13.450 ms/op
     p(99.9990) =     13.451 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


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
# Warmup Iteration   1: 3.532 ±(99.9%) 0.081 ms/op
Iteration   1: 2.135 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   1.987 ms/op
                 existUser·p0.90:   2.830 ms/op
                 existUser·p0.95:   2.957 ms/op
                 existUser·p0.99:   3.293 ms/op
                 existUser·p0.999:  27.034 ms/op
                 existUser·p0.9999: 27.378 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14972
  mean =      2.135 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12109 
    [ 2.500,  5.000) = 2800 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      3.293 ms/op
     p(99.9000) =     27.034 ms/op
     p(99.9900) =     27.378 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.632 ±(99.9%) 0.110 ms/op
Iteration   1: 2.847 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   2.740 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.256 ms/op
                 getUser·p0.999:  6.537 ms/op
                 getUser·p0.9999: 9.066 ms/op
                 getUser·p1.00:   9.077 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11337
  mean =      2.847 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 15 
    [ 1.000,  2.000) = 247 
    [ 2.000,  3.000) = 7447 
    [ 3.000,  4.000) = 3170 
    [ 4.000,  5.000) = 329 
    [ 5.000,  6.000) = 96 
    [ 6.000,  7.000) = 25 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.256 ms/op
     p(99.9000) =      6.537 ms/op
     p(99.9900) =      9.066 ms/op
     p(99.9990) =      9.077 ms/op
     p(99.9999) =      9.077 ms/op
    p(100.0000) =      9.077 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.960 ±(99.9%) 0.491 ms/op
Iteration   1: 8.440 ±(99.9%) 0.283 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   7.733 ms/op
                 listUser·p0.90:   10.715 ms/op
                 listUser·p0.95:   11.947 ms/op
                 listUser·p0.99:   30.115 ms/op
                 listUser·p0.999:  68.157 ms/op
                 listUser·p0.9999: 69.861 ms/op
                 listUser·p1.00:   69.861 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3795
  mean =      8.440 ±(99.9%) 0.283 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 135 
    [ 5.000, 10.000) = 3124 
    [10.000, 15.000) = 467 
    [15.000, 20.000) = 26 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 7 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.220 ms/op
     p(50.0000) =      7.733 ms/op
     p(90.0000) =     10.715 ms/op
     p(95.0000) =     11.947 ms/op
     p(99.0000) =     30.115 ms/op
     p(99.9000) =     68.157 ms/op
     p(99.9900) =     69.861 ms/op
     p(99.9990) =     69.861 ms/op
     p(99.9999) =     69.861 ms/op
    p(100.0000) =     69.861 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.638          ops/ms
Client.existUser                       thrpt         11.443          ops/ms
Client.getUser                         thrpt          7.680          ops/ms
Client.listUser                        thrpt          3.932          ops/ms
Client.createUser                       avgt          3.310           ms/op
Client.existUser                        avgt          1.723           ms/op
Client.getUser                          avgt          2.984           ms/op
Client.listUser                         avgt          8.036           ms/op
Client.createUser                     sample  10582   3.019 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.176           ms/op
Client.createUser:createUser·p0.50    sample          2.888           ms/op
Client.createUser:createUser·p0.90    sample          3.788           ms/op
Client.createUser:createUser·p0.95    sample          4.096           ms/op
Client.createUser:createUser·p0.99    sample          5.947           ms/op
Client.createUser:createUser·p0.999   sample         11.647           ms/op
Client.createUser:createUser·p0.9999  sample         13.450           ms/op
Client.createUser:createUser·p1.00    sample         13.451           ms/op
Client.existUser                      sample  14972   2.135 ± 0.034   ms/op
Client.existUser:existUser·p0.00      sample          0.571           ms/op
Client.existUser:existUser·p0.50      sample          1.987           ms/op
Client.existUser:existUser·p0.90      sample          2.830           ms/op
Client.existUser:existUser·p0.95      sample          2.957           ms/op
Client.existUser:existUser·p0.99      sample          3.293           ms/op
Client.existUser:existUser·p0.999     sample         27.034           ms/op
Client.existUser:existUser·p0.9999    sample         27.378           ms/op
Client.existUser:existUser·p1.00      sample         27.525           ms/op
Client.getUser                        sample  11337   2.847 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          0.599           ms/op
Client.getUser:getUser·p0.50          sample          2.740           ms/op
Client.getUser:getUser·p0.90          sample          3.559           ms/op
Client.getUser:getUser·p0.95          sample          3.867           ms/op
Client.getUser:getUser·p0.99          sample          5.256           ms/op
Client.getUser:getUser·p0.999         sample          6.537           ms/op
Client.getUser:getUser·p0.9999        sample          9.066           ms/op
Client.getUser:getUser·p1.00          sample          9.077           ms/op
Client.listUser                       sample   3795   8.440 ± 0.283   ms/op
Client.listUser:listUser·p0.00        sample          2.220           ms/op
Client.listUser:listUser·p0.50        sample          7.733           ms/op
Client.listUser:listUser·p0.90        sample         10.715           ms/op
Client.listUser:listUser·p0.95        sample         11.947           ms/op
Client.listUser:listUser·p0.99        sample         30.115           ms/op
Client.listUser:listUser·p0.999       sample         68.157           ms/op
Client.listUser:listUser·p0.9999      sample         69.861           ms/op
Client.listUser:listUser·p1.00        sample         69.861           ms/op
