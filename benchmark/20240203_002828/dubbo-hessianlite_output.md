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
# Warmup Iteration   1: 2.197 ops/ms
Iteration   1: 5.388 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.388 ops/ms


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
# Warmup Iteration   1: 5.850 ops/ms
Iteration   1: 13.116 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.116 ops/ms


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
# Warmup Iteration   1: 4.005 ops/ms
Iteration   1: 8.474 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.474 ops/ms


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
# Warmup Iteration   1: 1.914 ops/ms
Iteration   1: 3.324 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.324 ops/ms


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
# Warmup Iteration   1: 5.349 ±(99.9%) 0.078 ms/op
Iteration   1: 3.045 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.045 ms/op


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
# Warmup Iteration   1: 3.160 ±(99.9%) 0.032 ms/op
Iteration   1: 1.973 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.973 ms/op


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.090 ms/op
Iteration   1: 3.316 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.316 ms/op


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
# Warmup Iteration   1: 14.109 ±(99.9%) 0.303 ms/op
Iteration   1: 8.325 ±(99.9%) 0.084 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.325 ms/op


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.114 ms/op
Iteration   1: 3.009 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   2.740 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   11.059 ms/op
                 createUser·p0.999:  16.318 ms/op
                 createUser·p0.9999: 17.643 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10703
  mean =      3.009 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 2896 
    [ 2.500,  3.750) = 6723 
    [ 3.750,  5.000) = 798 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     17.643 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.083 ms/op
Iteration   1: 1.685 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   1.612 ms/op
                 existUser·p0.90:   1.964 ms/op
                 existUser·p0.95:   2.159 ms/op
                 existUser·p0.99:   3.072 ms/op
                 existUser·p0.999:  18.022 ms/op
                 existUser·p0.9999: 18.331 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18988
  mean =      1.685 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1134 
    [ 1.250,  2.500) = 17477 
    [ 2.500,  3.750) = 232 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      1.612 ms/op
     p(90.0000) =      1.964 ms/op
     p(95.0000) =      2.159 ms/op
     p(99.0000) =      3.072 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     18.331 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.103 ms/op
Iteration   1: 3.159 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.393 ms/op
                 getUser·p0.999:  6.963 ms/op
                 getUser·p0.9999: 10.358 ms/op
                 getUser·p1.00:   10.404 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10134
  mean =      3.159 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 4 
    [ 1.000,  2.000) = 104 
    [ 2.000,  3.000) = 4890 
    [ 3.000,  4.000) = 4275 
    [ 4.000,  5.000) = 686 
    [ 5.000,  6.000) = 115 
    [ 6.000,  7.000) = 56 
    [ 7.000,  8.000) = 3 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.393 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     10.358 ms/op
     p(99.9990) =     10.404 ms/op
     p(99.9999) =     10.404 ms/op
    p(100.0000) =     10.404 ms/op


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
# Warmup Iteration   1: 12.836 ±(99.9%) 0.441 ms/op
Iteration   1: 8.893 ±(99.9%) 0.142 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   8.471 ms/op
                 listUser·p0.90:   11.965 ms/op
                 listUser·p0.95:   13.255 ms/op
                 listUser·p0.99:   18.056 ms/op
                 listUser·p0.999:  24.644 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3596
  mean =      8.893 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 71 
    [ 5.000,  7.500) = 1067 
    [ 7.500, 10.000) = 1479 
    [10.000, 12.500) = 679 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.552 ms/op
     p(50.0000) =      8.471 ms/op
     p(90.0000) =     11.965 ms/op
     p(95.0000) =     13.255 ms/op
     p(99.0000) =     18.056 ms/op
     p(99.9000) =     24.644 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.388          ops/ms
Client.existUser                       thrpt         13.116          ops/ms
Client.getUser                         thrpt          8.474          ops/ms
Client.listUser                        thrpt          3.324          ops/ms
Client.createUser                       avgt          3.045           ms/op
Client.existUser                        avgt          1.973           ms/op
Client.getUser                          avgt          3.316           ms/op
Client.listUser                         avgt          8.325           ms/op
Client.createUser                     sample  10703   3.009 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.096           ms/op
Client.createUser:createUser·p0.50    sample          2.740           ms/op
Client.createUser:createUser·p0.90    sample          3.752           ms/op
Client.createUser:createUser·p0.95    sample          4.260           ms/op
Client.createUser:createUser·p0.99    sample         11.059           ms/op
Client.createUser:createUser·p0.999   sample         16.318           ms/op
Client.createUser:createUser·p0.9999  sample         17.643           ms/op
Client.createUser:createUser·p1.00    sample         17.727           ms/op
Client.existUser                      sample  18988   1.685 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.580           ms/op
Client.existUser:existUser·p0.50      sample          1.612           ms/op
Client.existUser:existUser·p0.90      sample          1.964           ms/op
Client.existUser:existUser·p0.95      sample          2.159           ms/op
Client.existUser:existUser·p0.99      sample          3.072           ms/op
Client.existUser:existUser·p0.999     sample         18.022           ms/op
Client.existUser:existUser·p0.9999    sample         18.331           ms/op
Client.existUser:existUser·p1.00      sample         18.448           ms/op
Client.getUser                        sample  10134   3.159 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.751           ms/op
Client.getUser:getUser·p0.50          sample          3.015           ms/op
Client.getUser:getUser·p0.90          sample          3.936           ms/op
Client.getUser:getUser·p0.95          sample          4.252           ms/op
Client.getUser:getUser·p0.99          sample          5.393           ms/op
Client.getUser:getUser·p0.999         sample          6.963           ms/op
Client.getUser:getUser·p0.9999        sample         10.358           ms/op
Client.getUser:getUser·p1.00          sample         10.404           ms/op
Client.listUser                       sample   3596   8.893 ± 0.142   ms/op
Client.listUser:listUser·p0.00        sample          2.552           ms/op
Client.listUser:listUser·p0.50        sample          8.471           ms/op
Client.listUser:listUser·p0.90        sample         11.965           ms/op
Client.listUser:listUser·p0.95        sample         13.255           ms/op
Client.listUser:listUser·p0.99        sample         18.056           ms/op
Client.listUser:listUser·p0.999       sample         24.644           ms/op
Client.listUser:listUser·p0.9999      sample         25.919           ms/op
Client.listUser:listUser·p1.00        sample         25.919           ms/op
