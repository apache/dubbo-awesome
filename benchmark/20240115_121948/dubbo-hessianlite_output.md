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
# Warmup Iteration   1: 2.143 ops/ms
Iteration   1: 6.098 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.098 ops/ms


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
# Warmup Iteration   1: 5.814 ops/ms
Iteration   1: 13.594 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.594 ops/ms


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
# Warmup Iteration   1: 3.790 ops/ms
Iteration   1: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.984 ops/ms


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
# Warmup Iteration   1: 2.030 ops/ms
Iteration   1: 3.830 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.830 ops/ms


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
# Warmup Iteration   1: 5.320 ±(99.9%) 0.074 ms/op
Iteration   1: 3.070 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.070 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.052 ms/op
Iteration   1: 1.866 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.866 ms/op


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
# Warmup Iteration   1: 4.997 ±(99.9%) 0.067 ms/op
Iteration   1: 2.844 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.844 ms/op


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
# Warmup Iteration   1: 11.414 ±(99.9%) 0.197 ms/op
Iteration   1: 8.301 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.301 ms/op


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
# Warmup Iteration   1: 5.107 ±(99.9%) 0.109 ms/op
Iteration   1: 3.410 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.504 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  20.349 ms/op
                 createUser·p0.9999: 22.413 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9383
  mean =      3.410 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 714 
    [ 2.500,  5.000) = 8477 
    [ 5.000,  7.500) = 154 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.504 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 2.915 ±(99.9%) 0.070 ms/op
Iteration   1: 1.599 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.481 ms/op
                 existUser·p0.50:   1.524 ms/op
                 existUser·p0.90:   2.036 ms/op
                 existUser·p0.95:   2.200 ms/op
                 existUser·p0.99:   2.695 ms/op
                 existUser·p0.999:  4.301 ms/op
                 existUser·p0.9999: 4.768 ms/op
                 existUser·p1.00:   6.111 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 20001
  mean =      1.599 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 2 
    [0.500, 1.000) = 193 
    [1.000, 1.500) = 8998 
    [1.500, 2.000) = 8433 
    [2.000, 2.500) = 1977 
    [2.500, 3.000) = 302 
    [3.000, 3.500) = 41 
    [3.500, 4.000) = 29 
    [4.000, 4.500) = 12 
    [4.500, 5.000) = 13 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      1.524 ms/op
     p(90.0000) =      2.036 ms/op
     p(95.0000) =      2.200 ms/op
     p(99.0000) =      2.695 ms/op
     p(99.9000) =      4.301 ms/op
     p(99.9900) =      4.768 ms/op
     p(99.9990) =      6.111 ms/op
     p(99.9999) =      6.111 ms/op
    p(100.0000) =      6.111 ms/op


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.094 ms/op
Iteration   1: 2.812 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   2.671 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  18.502 ms/op
                 getUser·p0.9999: 18.903 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11367
  mean =      2.812 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 4206 
    [ 2.500,  3.750) = 6195 
    [ 3.750,  5.000) = 851 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =     18.502 ms/op
     p(99.9900) =     18.903 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 12.007 ±(99.9%) 0.422 ms/op
Iteration   1: 9.186 ±(99.9%) 0.131 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   9.134 ms/op
                 listUser·p0.90:   12.198 ms/op
                 listUser·p0.95:   13.169 ms/op
                 listUser·p0.99:   15.291 ms/op
                 listUser·p0.999:  21.033 ms/op
                 listUser·p0.9999: 25.788 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3484
  mean =      9.186 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 77 
    [ 5.000,  7.500) = 759 
    [ 7.500, 10.000) = 1428 
    [10.000, 12.500) = 936 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.290 ms/op
     p(50.0000) =      9.134 ms/op
     p(90.0000) =     12.198 ms/op
     p(95.0000) =     13.169 ms/op
     p(99.0000) =     15.291 ms/op
     p(99.9000) =     21.033 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.098          ops/ms
Client.existUser                       thrpt         13.594          ops/ms
Client.getUser                         thrpt          7.984          ops/ms
Client.listUser                        thrpt          3.830          ops/ms
Client.createUser                       avgt          3.070           ms/op
Client.existUser                        avgt          1.866           ms/op
Client.getUser                          avgt          2.844           ms/op
Client.listUser                         avgt          8.301           ms/op
Client.createUser                     sample   9383   3.410 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          1.163           ms/op
Client.createUser:createUser·p0.50    sample          3.269           ms/op
Client.createUser:createUser·p0.90    sample          4.243           ms/op
Client.createUser:createUser·p0.95    sample          4.504           ms/op
Client.createUser:createUser·p0.99    sample          6.357           ms/op
Client.createUser:createUser·p0.999   sample         20.349           ms/op
Client.createUser:createUser·p0.9999  sample         22.413           ms/op
Client.createUser:createUser·p1.00    sample         22.413           ms/op
Client.existUser                      sample  20001   1.599 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.481           ms/op
Client.existUser:existUser·p0.50      sample          1.524           ms/op
Client.existUser:existUser·p0.90      sample          2.036           ms/op
Client.existUser:existUser·p0.95      sample          2.200           ms/op
Client.existUser:existUser·p0.99      sample          2.695           ms/op
Client.existUser:existUser·p0.999     sample          4.301           ms/op
Client.existUser:existUser·p0.9999    sample          4.768           ms/op
Client.existUser:existUser·p1.00      sample          6.111           ms/op
Client.getUser                        sample  11367   2.812 ± 0.033   ms/op
Client.getUser:getUser·p0.00          sample          0.721           ms/op
Client.getUser:getUser·p0.50          sample          2.671           ms/op
Client.getUser:getUser·p0.90          sample          3.670           ms/op
Client.getUser:getUser·p0.95          sample          3.895           ms/op
Client.getUser:getUser·p0.99          sample          4.514           ms/op
Client.getUser:getUser·p0.999         sample         18.502           ms/op
Client.getUser:getUser·p0.9999        sample         18.903           ms/op
Client.getUser:getUser·p1.00          sample         18.907           ms/op
Client.listUser                       sample   3484   9.186 ± 0.131   ms/op
Client.listUser:listUser·p0.00        sample          2.290           ms/op
Client.listUser:listUser·p0.50        sample          9.134           ms/op
Client.listUser:listUser·p0.90        sample         12.198           ms/op
Client.listUser:listUser·p0.95        sample         13.169           ms/op
Client.listUser:listUser·p0.99        sample         15.291           ms/op
Client.listUser:listUser·p0.999       sample         21.033           ms/op
Client.listUser:listUser·p0.9999      sample         25.788           ms/op
Client.listUser:listUser·p1.00        sample         25.788           ms/op
