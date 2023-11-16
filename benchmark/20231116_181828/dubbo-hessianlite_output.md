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
# Warmup Iteration   1: 2.447 ops/ms
Iteration   1: 5.999 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.999 ops/ms


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
# Warmup Iteration   1: 6.844 ops/ms
Iteration   1: 13.666 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.666 ops/ms


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
# Warmup Iteration   1: 3.978 ops/ms
Iteration   1: 9.411 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.411 ops/ms


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
# Warmup Iteration   1: 2.139 ops/ms
Iteration   1: 3.515 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.515 ops/ms


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
# Warmup Iteration   1: 5.362 ±(99.9%) 0.087 ms/op
Iteration   1: 2.931 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.931 ms/op


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
# Warmup Iteration   1: 2.979 ±(99.9%) 0.033 ms/op
Iteration   1: 1.797 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.797 ms/op


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.070 ms/op
Iteration   1: 2.985 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.985 ms/op


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
# Warmup Iteration   1: 12.990 ±(99.9%) 0.623 ms/op
Iteration   1: 7.955 ±(99.9%) 0.071 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.955 ms/op


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
# Warmup Iteration   1: 4.556 ±(99.9%) 0.095 ms/op
Iteration   1: 3.089 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   2.834 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   9.232 ms/op
                 createUser·p0.999:  14.172 ms/op
                 createUser·p0.9999: 15.711 ms/op
                 createUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10352
  mean =      3.089 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1769 
    [ 2.500,  3.750) = 7435 
    [ 3.750,  5.000) = 760 
    [ 5.000,  6.250) = 161 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      9.232 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     15.711 ms/op
     p(99.9990) =     15.712 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 2.912 ±(99.9%) 0.058 ms/op
Iteration   1: 2.180 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.042 ms/op
                 existUser·p0.90:   2.679 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  26.673 ms/op
                 existUser·p0.9999: 27.363 ms/op
                 existUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14900
  mean =      2.180 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12502 
    [ 2.500,  5.000) = 2186 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     26.673 ms/op
     p(99.9900) =     27.363 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 4.341 ±(99.9%) 0.093 ms/op
Iteration   1: 2.951 ±(99.9%) 0.054 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.652 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.146 ms/op
                 getUser·p0.99:   6.247 ms/op
                 getUser·p0.999:  28.514 ms/op
                 getUser·p0.9999: 30.327 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10836
  mean =      2.951 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4374 
    [ 2.500,  5.000) = 6241 
    [ 5.000,  7.500) = 123 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.652 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.146 ms/op
     p(99.0000) =      6.247 ms/op
     p(99.9000) =     28.514 ms/op
     p(99.9900) =     30.327 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 11.796 ±(99.9%) 0.336 ms/op
Iteration   1: 7.147 ±(99.9%) 0.086 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   6.849 ms/op
                 listUser·p0.90:   9.257 ms/op
                 listUser·p0.95:   10.256 ms/op
                 listUser·p0.99:   13.222 ms/op
                 listUser·p0.999:  16.257 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4462
  mean =      7.147 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3 
    [ 2.500,  3.750) = 19 
    [ 3.750,  5.000) = 251 
    [ 5.000,  6.250) = 1108 
    [ 6.250,  7.500) = 1539 
    [ 7.500,  8.750) = 925 
    [ 8.750, 10.000) = 356 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.200 ms/op
     p(50.0000) =      6.849 ms/op
     p(90.0000) =      9.257 ms/op
     p(95.0000) =     10.256 ms/op
     p(99.0000) =     13.222 ms/op
     p(99.9000) =     16.257 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.999          ops/ms
Client.existUser                       thrpt         13.666          ops/ms
Client.getUser                         thrpt          9.411          ops/ms
Client.listUser                        thrpt          3.515          ops/ms
Client.createUser                       avgt          2.931           ms/op
Client.existUser                        avgt          1.797           ms/op
Client.getUser                          avgt          2.985           ms/op
Client.listUser                         avgt          7.955           ms/op
Client.createUser                     sample  10352   3.089 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.048           ms/op
Client.createUser:createUser·p0.50    sample          2.834           ms/op
Client.createUser:createUser·p0.90    sample          3.842           ms/op
Client.createUser:createUser·p0.95    sample          4.383           ms/op
Client.createUser:createUser·p0.99    sample          9.232           ms/op
Client.createUser:createUser·p0.999   sample         14.172           ms/op
Client.createUser:createUser·p0.9999  sample         15.711           ms/op
Client.createUser:createUser·p1.00    sample         15.712           ms/op
Client.existUser                      sample  14900   2.180 ± 0.037   ms/op
Client.existUser:existUser·p0.00      sample          0.594           ms/op
Client.existUser:existUser·p0.50      sample          2.042           ms/op
Client.existUser:existUser·p0.90      sample          2.679           ms/op
Client.existUser:existUser·p0.95      sample          3.043           ms/op
Client.existUser:existUser·p0.99      sample          6.783           ms/op
Client.existUser:existUser·p0.999     sample         26.673           ms/op
Client.existUser:existUser·p0.9999    sample         27.363           ms/op
Client.existUser:existUser·p1.00      sample         27.427           ms/op
Client.getUser                        sample  10836   2.951 ± 0.054   ms/op
Client.getUser:getUser·p0.00          sample          0.682           ms/op
Client.getUser:getUser·p0.50          sample          2.652           ms/op
Client.getUser:getUser·p0.90          sample          3.764           ms/op
Client.getUser:getUser·p0.95          sample          4.146           ms/op
Client.getUser:getUser·p0.99          sample          6.247           ms/op
Client.getUser:getUser·p0.999         sample         28.514           ms/op
Client.getUser:getUser·p0.9999        sample         30.327           ms/op
Client.getUser:getUser·p1.00          sample         30.343           ms/op
Client.listUser                       sample   4462   7.147 ± 0.086   ms/op
Client.listUser:listUser·p0.00        sample          2.200           ms/op
Client.listUser:listUser·p0.50        sample          6.849           ms/op
Client.listUser:listUser·p0.90        sample          9.257           ms/op
Client.listUser:listUser·p0.95        sample         10.256           ms/op
Client.listUser:listUser·p0.99        sample         13.222           ms/op
Client.listUser:listUser·p0.999       sample         16.257           ms/op
Client.listUser:listUser·p0.9999      sample         17.760           ms/op
Client.listUser:listUser·p1.00        sample         17.760           ms/op
