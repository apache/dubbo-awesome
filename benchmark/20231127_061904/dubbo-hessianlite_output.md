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
# Warmup Iteration   1: 2.063 ops/ms
Iteration   1: 5.424 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.424 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.619 ops/ms
Iteration   1: 12.041 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.041 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ops/ms
Iteration   1: 8.028 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.028 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.312 ops/ms
Iteration   1: 3.506 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.506 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.512 ±(99.9%) 0.083 ms/op
Iteration   1: 3.456 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.456 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.039 ms/op
Iteration   1: 2.033 ±(99.9%) 0.011 ms/op


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.061 ms/op
Iteration   1: 2.933 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.933 ms/op


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
# Warmup Iteration   1: 11.370 ±(99.9%) 0.206 ms/op
Iteration   1: 9.224 ±(99.9%) 0.113 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.224 ms/op


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
# Warmup Iteration   1: 4.969 ±(99.9%) 0.117 ms/op
Iteration   1: 3.248 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  14.906 ms/op
                 createUser·p0.9999: 16.217 ms/op
                 createUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10053
  mean =      3.248 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2288 
    [ 2.500,  3.750) = 5142 
    [ 3.750,  5.000) = 2239 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     14.906 ms/op
     p(99.9900) =     16.217 ms/op
     p(99.9990) =     16.220 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.053 ms/op
Iteration   1: 1.751 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   1.632 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   4.053 ms/op
                 existUser·p0.999:  14.561 ms/op
                 existUser·p0.9999: 14.825 ms/op
                 existUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18250
  mean =      1.751 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1642 
    [ 1.250,  2.500) = 15763 
    [ 2.500,  3.750) = 612 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      4.053 ms/op
     p(99.9000) =     14.561 ms/op
     p(99.9900) =     14.825 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.106 ms/op
Iteration   1: 2.953 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   2.793 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.905 ms/op
                 getUser·p0.999:  18.383 ms/op
                 getUser·p0.9999: 18.894 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10831
  mean =      2.953 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 3176 
    [ 2.500,  3.750) = 6550 
    [ 3.750,  5.000) = 879 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.793 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.905 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     18.894 ms/op
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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.708 ±(99.9%) 0.419 ms/op
Iteration   1: 7.313 ±(99.9%) 0.092 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   7.053 ms/op
                 listUser·p0.90:   9.565 ms/op
                 listUser·p0.95:   10.748 ms/op
                 listUser·p0.99:   13.863 ms/op
                 listUser·p0.999:  16.173 ms/op
                 listUser·p0.9999: 23.265 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4371
  mean =      7.313 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 254 
    [ 5.000,  7.500) = 2449 
    [ 7.500, 10.000) = 1329 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      7.053 ms/op
     p(90.0000) =      9.565 ms/op
     p(95.0000) =     10.748 ms/op
     p(99.0000) =     13.863 ms/op
     p(99.9000) =     16.173 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.424          ops/ms
Client.existUser                       thrpt         12.041          ops/ms
Client.getUser                         thrpt          8.028          ops/ms
Client.listUser                        thrpt          3.506          ops/ms
Client.createUser                       avgt          3.456           ms/op
Client.existUser                        avgt          2.033           ms/op
Client.getUser                          avgt          2.933           ms/op
Client.listUser                         avgt          9.224           ms/op
Client.createUser                     sample  10053   3.248 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.311           ms/op
Client.createUser:createUser·p0.50    sample          2.986           ms/op
Client.createUser:createUser·p0.90    sample          4.358           ms/op
Client.createUser:createUser·p0.95    sample          4.760           ms/op
Client.createUser:createUser·p0.99    sample          7.348           ms/op
Client.createUser:createUser·p0.999   sample         14.906           ms/op
Client.createUser:createUser·p0.9999  sample         16.217           ms/op
Client.createUser:createUser·p1.00    sample         16.220           ms/op
Client.existUser                      sample  18250   1.751 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.653           ms/op
Client.existUser:existUser·p0.50      sample          1.632           ms/op
Client.existUser:existUser·p0.90      sample          2.232           ms/op
Client.existUser:existUser·p0.95      sample          2.474           ms/op
Client.existUser:existUser·p0.99      sample          4.053           ms/op
Client.existUser:existUser·p0.999     sample         14.561           ms/op
Client.existUser:existUser·p0.9999    sample         14.825           ms/op
Client.existUser:existUser·p1.00      sample         14.893           ms/op
Client.getUser                        sample  10831   2.953 ± 0.038   ms/op
Client.getUser:getUser·p0.00          sample          0.877           ms/op
Client.getUser:getUser·p0.50          sample          2.793           ms/op
Client.getUser:getUser·p0.90          sample          3.748           ms/op
Client.getUser:getUser·p0.95          sample          4.174           ms/op
Client.getUser:getUser·p0.99          sample          5.905           ms/op
Client.getUser:getUser·p0.999         sample         18.383           ms/op
Client.getUser:getUser·p0.9999        sample         18.894           ms/op
Client.getUser:getUser·p1.00          sample         18.907           ms/op
Client.listUser                       sample   4371   7.313 ± 0.092   ms/op
Client.listUser:listUser·p0.00        sample          1.327           ms/op
Client.listUser:listUser·p0.50        sample          7.053           ms/op
Client.listUser:listUser·p0.90        sample          9.565           ms/op
Client.listUser:listUser·p0.95        sample         10.748           ms/op
Client.listUser:listUser·p0.99        sample         13.863           ms/op
Client.listUser:listUser·p0.999       sample         16.173           ms/op
Client.listUser:listUser·p0.9999      sample         23.265           ms/op
Client.listUser:listUser·p1.00        sample         23.265           ms/op
