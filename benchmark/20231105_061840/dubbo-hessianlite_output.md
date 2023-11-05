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
# Warmup Iteration   1: 2.345 ops/ms
Iteration   1: 6.255 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.255 ops/ms


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
# Warmup Iteration   1: 6.436 ops/ms
Iteration   1: 13.144 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.144 ops/ms


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
# Warmup Iteration   1: 5.212 ops/ms
Iteration   1: 8.518 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.518 ops/ms


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
# Warmup Iteration   1: 2.261 ops/ms
Iteration   1: 3.981 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.981 ops/ms


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
# Warmup Iteration   1: 5.314 ±(99.9%) 0.069 ms/op
Iteration   1: 3.093 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.093 ms/op


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
# Warmup Iteration   1: 2.903 ±(99.9%) 0.031 ms/op
Iteration   1: 2.033 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.033 ms/op


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.058 ms/op
Iteration   1: 2.809 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.809 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.405 ±(99.9%) 0.273 ms/op
Iteration   1: 8.344 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.344 ms/op


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
# Warmup Iteration   1: 5.318 ±(99.9%) 0.086 ms/op
Iteration   1: 3.444 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.525 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  16.721 ms/op
                 createUser·p0.9999: 17.924 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9431
  mean =      3.444 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 653 
    [ 2.500,  3.750) = 6649 
    [ 3.750,  5.000) = 1803 
    [ 5.000,  6.250) = 189 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.525 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     16.721 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 2.860 ±(99.9%) 0.051 ms/op
Iteration   1: 2.288 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.366 ms/op
                 existUser·p0.50:   2.273 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  22.433 ms/op
                 existUser·p0.9999: 23.009 ms/op
                 existUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14129
  mean =      2.288 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9770 
    [ 2.500,  5.000) = 4293 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      2.273 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =     22.433 ms/op
     p(99.9900) =     23.009 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 4.660 ±(99.9%) 0.107 ms/op
Iteration   1: 3.134 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   2.851 ms/op
                 getUser·p0.90:   4.041 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   10.359 ms/op
                 getUser·p0.999:  15.779 ms/op
                 getUser·p0.9999: 19.421 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10273
  mean =      3.134 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 3263 
    [ 2.500,  3.750) = 5332 
    [ 3.750,  5.000) = 1236 
    [ 5.000,  6.250) = 139 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      4.041 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =     10.359 ms/op
     p(99.9000) =     15.779 ms/op
     p(99.9900) =     19.421 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 12.453 ±(99.9%) 0.438 ms/op
Iteration   1: 7.927 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   3.047 ms/op
                 listUser·p0.50:   7.553 ms/op
                 listUser·p0.90:   10.420 ms/op
                 listUser·p0.95:   11.469 ms/op
                 listUser·p0.99:   14.905 ms/op
                 listUser·p0.999:  23.952 ms/op
                 listUser·p0.9999: 27.623 ms/op
                 listUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4042
  mean =      7.927 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 99 
    [ 5.000,  7.500) = 1842 
    [ 7.500, 10.000) = 1595 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.047 ms/op
     p(50.0000) =      7.553 ms/op
     p(90.0000) =     10.420 ms/op
     p(95.0000) =     11.469 ms/op
     p(99.0000) =     14.905 ms/op
     p(99.9000) =     23.952 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.255          ops/ms
Client.existUser                       thrpt         13.144          ops/ms
Client.getUser                         thrpt          8.518          ops/ms
Client.listUser                        thrpt          3.981          ops/ms
Client.createUser                       avgt          3.093           ms/op
Client.existUser                        avgt          2.033           ms/op
Client.getUser                          avgt          2.809           ms/op
Client.listUser                         avgt          8.344           ms/op
Client.createUser                     sample   9431   3.444 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          0.724           ms/op
Client.createUser:createUser·p0.50    sample          3.355           ms/op
Client.createUser:createUser·p0.90    sample          4.092           ms/op
Client.createUser:createUser·p0.95    sample          4.525           ms/op
Client.createUser:createUser·p0.99    sample          6.808           ms/op
Client.createUser:createUser·p0.999   sample         16.721           ms/op
Client.createUser:createUser·p0.9999  sample         17.924           ms/op
Client.createUser:createUser·p1.00    sample         17.924           ms/op
Client.existUser                      sample  14129   2.288 ± 0.033   ms/op
Client.existUser:existUser·p0.00      sample          0.366           ms/op
Client.existUser:existUser·p0.50      sample          2.273           ms/op
Client.existUser:existUser·p0.90      sample          2.892           ms/op
Client.existUser:existUser·p0.95      sample          3.109           ms/op
Client.existUser:existUser·p0.99      sample          3.662           ms/op
Client.existUser:existUser·p0.999     sample         22.433           ms/op
Client.existUser:existUser·p0.9999    sample         23.009           ms/op
Client.existUser:existUser·p1.00      sample         23.036           ms/op
Client.getUser                        sample  10273   3.134 ± 0.045   ms/op
Client.getUser:getUser·p0.00          sample          1.016           ms/op
Client.getUser:getUser·p0.50          sample          2.851           ms/op
Client.getUser:getUser·p0.90          sample          4.041           ms/op
Client.getUser:getUser·p0.95          sample          4.727           ms/op
Client.getUser:getUser·p0.99          sample         10.359           ms/op
Client.getUser:getUser·p0.999         sample         15.779           ms/op
Client.getUser:getUser·p0.9999        sample         19.421           ms/op
Client.getUser:getUser·p1.00          sample         19.464           ms/op
Client.listUser                       sample   4042   7.927 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample          3.047           ms/op
Client.listUser:listUser·p0.50        sample          7.553           ms/op
Client.listUser:listUser·p0.90        sample         10.420           ms/op
Client.listUser:listUser·p0.95        sample         11.469           ms/op
Client.listUser:listUser·p0.99        sample         14.905           ms/op
Client.listUser:listUser·p0.999       sample         23.952           ms/op
Client.listUser:listUser·p0.9999      sample         27.623           ms/op
Client.listUser:listUser·p1.00        sample         27.623           ms/op
