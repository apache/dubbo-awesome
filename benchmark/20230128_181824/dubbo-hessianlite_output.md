# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.267 ops/ms
Iteration   1: 2.546 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.546 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.043 ops/ms
Iteration   1: 8.253 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.253 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.217 ops/ms
Iteration   1: 4.958 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.958 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.882 ops/ms
Iteration   1: 1.363 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.363 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 16.246 ±(99.9%) 0.533 ms/op
Iteration   1: 7.556 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.556 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.598 ±(99.9%) 0.105 ms/op
Iteration   1: 4.185 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.185 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.569 ±(99.9%) 0.132 ms/op
Iteration   1: 4.773 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.773 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 29.243 ±(99.9%) 0.582 ms/op
Iteration   1: 16.590 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.599 ±(99.9%) 0.349 ms/op
Iteration   1: 5.598 ±(99.9%) 0.075 ms/op
                 createUser·p0.00:   3.543 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   7.686 ms/op
                 createUser·p0.99:   12.937 ms/op
                 createUser·p0.999:  15.546 ms/op
                 createUser·p0.9999: 39.846 ms/op
                 createUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5737
  mean =      5.598 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1550 
    [ 5.000,  7.500) = 3861 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.543 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.686 ms/op
     p(99.0000) =     12.937 ms/op
     p(99.9000) =     15.546 ms/op
     p(99.9900) =     39.846 ms/op
     p(99.9990) =     39.846 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.407 ±(99.9%) 0.185 ms/op
Iteration   1: 3.418 ±(99.9%) 0.054 ms/op
                 existUser·p0.00:   0.202 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.066 ms/op
                 existUser·p0.99:   8.864 ms/op
                 existUser·p0.999:  26.867 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9365
  mean =      3.418 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 875 
    [ 2.500,  5.000) = 8196 
    [ 5.000,  7.500) = 166 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.202 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.066 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     26.867 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 8.228 ±(99.9%) 0.306 ms/op
Iteration   1: 4.562 ±(99.9%) 0.068 ms/op
                 getUser·p0.00:   1.583 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   7.134 ms/op
                 getUser·p0.99:   14.669 ms/op
                 getUser·p0.999:  17.531 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7133
  mean =      4.562 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 32 
    [ 2.500,  3.750) = 1617 
    [ 3.750,  5.000) = 4381 
    [ 5.000,  6.250) = 670 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.583 ms/op
     p(50.0000) =      4.166 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      7.134 ms/op
     p(99.0000) =     14.669 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 22.291 ±(99.9%) 0.701 ms/op
Iteration   1: 15.742 ±(99.9%) 0.166 ms/op
                 listUser·p0.00:   6.742 ms/op
                 listUser·p0.50:   15.458 ms/op
                 listUser·p0.90:   17.203 ms/op
                 listUser·p0.95:   19.508 ms/op
                 listUser·p0.99:   25.080 ms/op
                 listUser·p0.999:  30.310 ms/op
                 listUser·p0.9999: 30.867 ms/op
                 listUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2032
  mean =     15.742 ±(99.9%) 0.166 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 335 
    [15.000, 17.500) = 1425 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      6.742 ms/op
     p(50.0000) =     15.458 ms/op
     p(90.0000) =     17.203 ms/op
     p(95.0000) =     19.508 ms/op
     p(99.0000) =     25.080 ms/op
     p(99.9000) =     30.310 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.546          ops/ms
Client.existUser                       thrpt         8.253          ops/ms
Client.getUser                         thrpt         4.958          ops/ms
Client.listUser                        thrpt         1.363          ops/ms
Client.createUser                       avgt         7.556           ms/op
Client.existUser                        avgt         4.185           ms/op
Client.getUser                          avgt         4.773           ms/op
Client.listUser                         avgt        16.590           ms/op
Client.createUser                     sample  5737   5.598 ± 0.075   ms/op
Client.createUser:createUser·p0.00    sample         3.543           ms/op
Client.createUser:createUser·p0.50    sample         5.317           ms/op
Client.createUser:createUser·p0.90    sample         6.308           ms/op
Client.createUser:createUser·p0.95    sample         7.686           ms/op
Client.createUser:createUser·p0.99    sample        12.937           ms/op
Client.createUser:createUser·p0.999   sample        15.546           ms/op
Client.createUser:createUser·p0.9999  sample        39.846           ms/op
Client.createUser:createUser·p1.00    sample        39.846           ms/op
Client.existUser                      sample  9365   3.418 ± 0.054   ms/op
Client.existUser:existUser·p0.00      sample         0.202           ms/op
Client.existUser:existUser·p0.50      sample         3.387           ms/op
Client.existUser:existUser·p0.90      sample         3.817           ms/op
Client.existUser:existUser·p0.95      sample         4.066           ms/op
Client.existUser:existUser·p0.99      sample         8.864           ms/op
Client.existUser:existUser·p0.999     sample        26.867           ms/op
Client.existUser:existUser·p0.9999    sample        27.623           ms/op
Client.existUser:existUser·p1.00      sample        27.623           ms/op
Client.getUser                        sample  7133   4.562 ± 0.068   ms/op
Client.getUser:getUser·p0.00          sample         1.583           ms/op
Client.getUser:getUser·p0.50          sample         4.166           ms/op
Client.getUser:getUser·p0.90          sample         5.349           ms/op
Client.getUser:getUser·p0.95          sample         7.134           ms/op
Client.getUser:getUser·p0.99          sample        14.669           ms/op
Client.getUser:getUser·p0.999         sample        17.531           ms/op
Client.getUser:getUser·p0.9999        sample        18.547           ms/op
Client.getUser:getUser·p1.00          sample        18.547           ms/op
Client.listUser                       sample  2032  15.742 ± 0.166   ms/op
Client.listUser:listUser·p0.00        sample         6.742           ms/op
Client.listUser:listUser·p0.50        sample        15.458           ms/op
Client.listUser:listUser·p0.90        sample        17.203           ms/op
Client.listUser:listUser·p0.95        sample        19.508           ms/op
Client.listUser:listUser·p0.99        sample        25.080           ms/op
Client.listUser:listUser·p0.999       sample        30.310           ms/op
Client.listUser:listUser·p0.9999      sample        30.867           ms/op
Client.listUser:listUser·p1.00        sample        30.867           ms/op
