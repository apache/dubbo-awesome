# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.274 ops/ms
Iteration   1: 2.827 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.827 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.060 ops/ms
Iteration   1: 7.837 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.837 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.968 ops/ms
Iteration   1: 3.786 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.786 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.730 ops/ms
Iteration   1: 1.346 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.346 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 22.041 ±(99.9%) 0.502 ms/op
Iteration   1: 7.642 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.642 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.402 ±(99.9%) 0.096 ms/op
Iteration   1: 4.165 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.002 ±(99.9%) 0.168 ms/op
Iteration   1: 5.636 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.636 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 28.942 ±(99.9%) 0.454 ms/op
Iteration   1: 19.116 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.116 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.177 ±(99.9%) 0.376 ms/op
Iteration   1: 7.621 ±(99.9%) 0.142 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   8.208 ms/op
                 createUser·p0.90:   9.503 ms/op
                 createUser·p0.95:   9.830 ms/op
                 createUser·p0.99:   18.285 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 20.972 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4198
  mean =      7.621 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 225 
    [ 2.500,  5.000) = 420 
    [ 5.000,  7.500) = 833 
    [ 7.500, 10.000) = 2531 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.552 ms/op
     p(50.0000) =      8.208 ms/op
     p(90.0000) =      9.503 ms/op
     p(95.0000) =      9.830 ms/op
     p(99.0000) =     18.285 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.493 ±(99.9%) 0.230 ms/op
Iteration   1: 4.033 ±(99.9%) 0.053 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   4.174 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   11.223 ms/op
                 existUser·p0.999:  17.012 ms/op
                 existUser·p0.9999: 17.269 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7945
  mean =      4.033 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 934 
    [ 2.500,  3.750) = 1451 
    [ 3.750,  5.000) = 5144 
    [ 5.000,  6.250) = 178 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     17.012 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.733 ±(99.9%) 0.353 ms/op
Iteration   1: 4.251 ±(99.9%) 0.076 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   14.786 ms/op
                 getUser·p0.999:  21.287 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7592
  mean =      4.251 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 419 
    [ 2.500,  5.000) = 6199 
    [ 5.000,  7.500) = 728 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =     14.786 ms/op
     p(99.9000) =     21.287 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 28.612 ±(99.9%) 1.348 ms/op
Iteration   1: 19.968 ±(99.9%) 0.287 ms/op
                 listUser·p0.00:   9.077 ms/op
                 listUser·p0.50:   19.366 ms/op
                 listUser·p0.90:   22.643 ms/op
                 listUser·p0.95:   25.100 ms/op
                 listUser·p0.99:   34.475 ms/op
                 listUser·p0.999:  45.302 ms/op
                 listUser·p0.9999: 47.251 ms/op
                 listUser·p1.00:   47.251 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1594
  mean =     19.968 ±(99.9%) 0.287 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 7 
    [10.000, 15.000) = 70 
    [15.000, 20.000) = 912 
    [20.000, 25.000) = 524 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      9.077 ms/op
     p(50.0000) =     19.366 ms/op
     p(90.0000) =     22.643 ms/op
     p(95.0000) =     25.100 ms/op
     p(99.0000) =     34.475 ms/op
     p(99.9000) =     45.302 ms/op
     p(99.9900) =     47.251 ms/op
     p(99.9990) =     47.251 ms/op
     p(99.9999) =     47.251 ms/op
    p(100.0000) =     47.251 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.827          ops/ms
Client.existUser                       thrpt         7.837          ops/ms
Client.getUser                         thrpt         3.786          ops/ms
Client.listUser                        thrpt         1.346          ops/ms
Client.createUser                       avgt         7.642           ms/op
Client.existUser                        avgt         4.165           ms/op
Client.getUser                          avgt         5.636           ms/op
Client.listUser                         avgt        19.116           ms/op
Client.createUser                     sample  4198   7.621 ± 0.142   ms/op
Client.createUser:createUser·p0.00    sample         1.552           ms/op
Client.createUser:createUser·p0.50    sample         8.208           ms/op
Client.createUser:createUser·p0.90    sample         9.503           ms/op
Client.createUser:createUser·p0.95    sample         9.830           ms/op
Client.createUser:createUser·p0.99    sample        18.285           ms/op
Client.createUser:createUser·p0.999   sample        20.742           ms/op
Client.createUser:createUser·p0.9999  sample        20.972           ms/op
Client.createUser:createUser·p1.00    sample        20.972           ms/op
Client.existUser                      sample  7945   4.033 ± 0.053   ms/op
Client.existUser:existUser·p0.00      sample         1.372           ms/op
Client.existUser:existUser·p0.50      sample         4.174           ms/op
Client.existUser:existUser·p0.90      sample         4.686           ms/op
Client.existUser:existUser·p0.95      sample         5.071           ms/op
Client.existUser:existUser·p0.99      sample        11.223           ms/op
Client.existUser:existUser·p0.999     sample        17.012           ms/op
Client.existUser:existUser·p0.9999    sample        17.269           ms/op
Client.existUser:existUser·p1.00      sample        17.269           ms/op
Client.getUser                        sample  7592   4.251 ± 0.076   ms/op
Client.getUser:getUser·p0.00          sample         0.941           ms/op
Client.getUser:getUser·p0.50          sample         3.965           ms/op
Client.getUser:getUser·p0.90          sample         5.226           ms/op
Client.getUser:getUser·p0.95          sample         6.185           ms/op
Client.getUser:getUser·p0.99          sample        14.786           ms/op
Client.getUser:getUser·p0.999         sample        21.287           ms/op
Client.getUser:getUser·p0.9999        sample        22.741           ms/op
Client.getUser:getUser·p1.00          sample        22.741           ms/op
Client.listUser                       sample  1594  19.968 ± 0.287   ms/op
Client.listUser:listUser·p0.00        sample         9.077           ms/op
Client.listUser:listUser·p0.50        sample        19.366           ms/op
Client.listUser:listUser·p0.90        sample        22.643           ms/op
Client.listUser:listUser·p0.95        sample        25.100           ms/op
Client.listUser:listUser·p0.99        sample        34.475           ms/op
Client.listUser:listUser·p0.999       sample        45.302           ms/op
Client.listUser:listUser·p0.9999      sample        47.251           ms/op
Client.listUser:listUser·p1.00        sample        47.251           ms/op
