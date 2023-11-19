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
# Warmup Iteration   1: 1.991 ops/ms
Iteration   1: 5.873 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.873 ops/ms


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
# Warmup Iteration   1: 6.699 ops/ms
Iteration   1: 13.558 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.558 ops/ms


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
# Warmup Iteration   1: 4.461 ops/ms
Iteration   1: 8.706 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.706 ops/ms


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
# Warmup Iteration   1: 2.085 ops/ms
Iteration   1: 3.644 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.644 ops/ms


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
# Warmup Iteration   1: 5.012 ±(99.9%) 0.064 ms/op
Iteration   1: 3.238 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.238 ms/op


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
# Warmup Iteration   1: 3.369 ±(99.9%) 0.052 ms/op
Iteration   1: 1.758 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.758 ms/op


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.051 ms/op
Iteration   1: 3.173 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.173 ms/op


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
# Warmup Iteration   1: 9.884 ±(99.9%) 0.142 ms/op
Iteration   1: 8.323 ±(99.9%) 0.109 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.323 ms/op


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.108 ms/op
Iteration   1: 2.914 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   11.420 ms/op
                 createUser·p0.999:  16.138 ms/op
                 createUser·p0.9999: 18.969 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11161
  mean =      2.914 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2797 
    [ 2.500,  3.750) = 7656 
    [ 3.750,  5.000) = 405 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      2.662 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =     11.420 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     18.969 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 3.278 ±(99.9%) 0.073 ms/op
Iteration   1: 1.916 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   1.794 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  14.156 ms/op
                 existUser·p0.9999: 15.830 ms/op
                 existUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16708
  mean =      1.916 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 346 
    [ 1.250,  2.500) = 15569 
    [ 2.500,  3.750) = 585 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     15.830 ms/op
     p(99.9990) =     16.171 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.089 ms/op
Iteration   1: 2.983 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  7.601 ms/op
                 getUser·p0.9999: 7.776 ms/op
                 getUser·p1.00:   7.782 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10703
  mean =      2.983 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 18 
    [1.500, 2.000) = 409 
    [2.000, 2.500) = 2485 
    [2.500, 3.000) = 2618 
    [3.000, 3.500) = 3057 
    [3.500, 4.000) = 1542 
    [4.000, 4.500) = 338 
    [4.500, 5.000) = 91 
    [5.000, 5.500) = 60 
    [5.500, 6.000) = 7 
    [6.000, 6.500) = 39 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      7.601 ms/op
     p(99.9900) =      7.776 ms/op
     p(99.9990) =      7.782 ms/op
     p(99.9999) =      7.782 ms/op
    p(100.0000) =      7.782 ms/op


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
# Warmup Iteration   1: 13.774 ±(99.9%) 0.585 ms/op
Iteration   1: 8.151 ±(99.9%) 0.132 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   7.676 ms/op
                 listUser·p0.90:   10.797 ms/op
                 listUser·p0.95:   11.949 ms/op
                 listUser·p0.99:   16.596 ms/op
                 listUser·p0.999:  28.349 ms/op
                 listUser·p0.9999: 28.803 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3933
  mean =      8.151 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 140 
    [ 5.000,  7.500) = 1685 
    [ 7.500, 10.000) = 1480 
    [10.000, 12.500) = 476 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.679 ms/op
     p(50.0000) =      7.676 ms/op
     p(90.0000) =     10.797 ms/op
     p(95.0000) =     11.949 ms/op
     p(99.0000) =     16.596 ms/op
     p(99.9000) =     28.349 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.873          ops/ms
Client.existUser                       thrpt         13.558          ops/ms
Client.getUser                         thrpt          8.706          ops/ms
Client.listUser                        thrpt          3.644          ops/ms
Client.createUser                       avgt          3.238           ms/op
Client.existUser                        avgt          1.758           ms/op
Client.getUser                          avgt          3.173           ms/op
Client.listUser                         avgt          8.323           ms/op
Client.createUser                     sample  11161   2.914 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.059           ms/op
Client.createUser:createUser·p0.50    sample          2.662           ms/op
Client.createUser:createUser·p0.90    sample          3.404           ms/op
Client.createUser:createUser·p0.95    sample          3.924           ms/op
Client.createUser:createUser·p0.99    sample         11.420           ms/op
Client.createUser:createUser·p0.999   sample         16.138           ms/op
Client.createUser:createUser·p0.9999  sample         18.969           ms/op
Client.createUser:createUser·p1.00    sample         18.973           ms/op
Client.existUser                      sample  16708   1.916 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.539           ms/op
Client.existUser:existUser·p0.50      sample          1.794           ms/op
Client.existUser:existUser·p0.90      sample          2.257           ms/op
Client.existUser:existUser·p0.95      sample          2.482           ms/op
Client.existUser:existUser·p0.99      sample          4.522           ms/op
Client.existUser:existUser·p0.999     sample         14.156           ms/op
Client.existUser:existUser·p0.9999    sample         15.830           ms/op
Client.existUser:existUser·p1.00      sample         16.171           ms/op
Client.getUser                        sample  10703   2.983 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.862           ms/op
Client.getUser:getUser·p0.50          sample          2.970           ms/op
Client.getUser:getUser·p0.90          sample          3.736           ms/op
Client.getUser:getUser·p0.95          sample          4.018           ms/op
Client.getUser:getUser·p0.99          sample          5.341           ms/op
Client.getUser:getUser·p0.999         sample          7.601           ms/op
Client.getUser:getUser·p0.9999        sample          7.776           ms/op
Client.getUser:getUser·p1.00          sample          7.782           ms/op
Client.listUser                       sample   3933   8.151 ± 0.132   ms/op
Client.listUser:listUser·p0.00        sample          2.679           ms/op
Client.listUser:listUser·p0.50        sample          7.676           ms/op
Client.listUser:listUser·p0.90        sample         10.797           ms/op
Client.listUser:listUser·p0.95        sample         11.949           ms/op
Client.listUser:listUser·p0.99        sample         16.596           ms/op
Client.listUser:listUser·p0.999       sample         28.349           ms/op
Client.listUser:listUser·p0.9999      sample         28.803           ms/op
Client.listUser:listUser·p1.00        sample         28.803           ms/op
