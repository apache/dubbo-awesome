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
# Warmup Iteration   1: 0.662 ops/ms
Iteration   1: 1.510 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.510 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 1.803 ops/ms
Iteration   1: 4.373 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.373 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.295 ops/ms
Iteration   1: 3.338 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.338 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 0.720 ops/ms
Iteration   1: 1.015 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.015 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 23.844 ±(99.9%) 0.424 ms/op
Iteration   1: 12.139 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  12.139 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.017 ±(99.9%) 0.223 ms/op
Iteration   1: 6.004 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.004 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.853 ±(99.9%) 0.200 ms/op
Iteration   1: 6.155 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.155 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 36.764 ±(99.9%) 0.793 ms/op
Iteration   1: 22.260 ±(99.9%) 0.131 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  22.260 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 17.282 ±(99.9%) 0.483 ms/op
Iteration   1: 9.008 ±(99.9%) 0.149 ms/op
                 createUser·p0.00:   4.047 ms/op
                 createUser·p0.50:   7.619 ms/op
                 createUser·p0.90:   11.141 ms/op
                 createUser·p0.95:   11.960 ms/op
                 createUser·p0.99:   20.231 ms/op
                 createUser·p0.999:  26.492 ms/op
                 createUser·p0.9999: 26.575 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3539
  mean =      9.008 ±(99.9%) 0.149 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 30 
    [ 5.000,  7.500) = 1610 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 1256 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      4.047 ms/op
     p(50.0000) =      7.619 ms/op
     p(90.0000) =     11.141 ms/op
     p(95.0000) =     11.960 ms/op
     p(99.0000) =     20.231 ms/op
     p(99.9000) =     26.492 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     26.575 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.710 ±(99.9%) 0.318 ms/op
Iteration   1: 5.097 ±(99.9%) 0.126 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   5.759 ms/op
                 existUser·p0.95:   11.724 ms/op
                 existUser·p0.99:   17.244 ms/op
                 existUser·p0.999:  33.373 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6273
  mean =      5.097 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 4929 
    [ 5.000,  7.500) = 800 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =     11.724 ms/op
     p(99.0000) =     17.244 ms/op
     p(99.9000) =     33.373 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 14.524 ±(99.9%) 0.484 ms/op
Iteration   1: 6.611 ±(99.9%) 0.146 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   6.222 ms/op
                 getUser·p0.90:   9.331 ms/op
                 getUser·p0.95:   10.592 ms/op
                 getUser·p0.99:   21.964 ms/op
                 getUser·p0.999:  29.164 ms/op
                 getUser·p0.9999: 30.540 ms/op
                 getUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4884
  mean =      6.611 ±(99.9%) 0.146 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 1368 
    [ 5.000,  7.500) = 2528 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      6.222 ms/op
     p(90.0000) =      9.331 ms/op
     p(95.0000) =     10.592 ms/op
     p(99.0000) =     21.964 ms/op
     p(99.9000) =     29.164 ms/op
     p(99.9900) =     30.540 ms/op
     p(99.9990) =     30.540 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 37.362 ±(99.9%) 1.212 ms/op
Iteration   1: 25.041 ±(99.9%) 0.508 ms/op
                 listUser·p0.00:   6.300 ms/op
                 listUser·p0.50:   26.280 ms/op
                 listUser·p0.90:   29.917 ms/op
                 listUser·p0.95:   34.341 ms/op
                 listUser·p0.99:   37.755 ms/op
                 listUser·p0.999:  40.011 ms/op
                 listUser·p0.9999: 40.239 ms/op
                 listUser·p1.00:   40.239 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1289
  mean =     25.041 ±(99.9%) 0.508 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 19 
    [10.000, 15.000) = 37 
    [15.000, 20.000) = 194 
    [20.000, 25.000) = 158 
    [25.000, 30.000) = 761 
    [30.000, 35.000) = 62 
    [35.000, 40.000) = 57 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      6.300 ms/op
     p(50.0000) =     26.280 ms/op
     p(90.0000) =     29.917 ms/op
     p(95.0000) =     34.341 ms/op
     p(99.0000) =     37.755 ms/op
     p(99.9000) =     40.011 ms/op
     p(99.9900) =     40.239 ms/op
     p(99.9990) =     40.239 ms/op
     p(99.9999) =     40.239 ms/op
    p(100.0000) =     40.239 ms/op


# Run complete. Total time: 00:01:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.510          ops/ms
Client.existUser                       thrpt         4.373          ops/ms
Client.getUser                         thrpt         3.338          ops/ms
Client.listUser                        thrpt         1.015          ops/ms
Client.createUser                       avgt        12.139           ms/op
Client.existUser                        avgt         6.004           ms/op
Client.getUser                          avgt         6.155           ms/op
Client.listUser                         avgt        22.260           ms/op
Client.createUser                     sample  3539   9.008 ± 0.149   ms/op
Client.createUser:createUser·p0.00    sample         4.047           ms/op
Client.createUser:createUser·p0.50    sample         7.619           ms/op
Client.createUser:createUser·p0.90    sample        11.141           ms/op
Client.createUser:createUser·p0.95    sample        11.960           ms/op
Client.createUser:createUser·p0.99    sample        20.231           ms/op
Client.createUser:createUser·p0.999   sample        26.492           ms/op
Client.createUser:createUser·p0.9999  sample        26.575           ms/op
Client.createUser:createUser·p1.00    sample        26.575           ms/op
Client.existUser                      sample  6273   5.097 ± 0.126   ms/op
Client.existUser:existUser·p0.00      sample         1.368           ms/op
Client.existUser:existUser·p0.50      sample         4.645           ms/op
Client.existUser:existUser·p0.90      sample         5.759           ms/op
Client.existUser:existUser·p0.95      sample        11.724           ms/op
Client.existUser:existUser·p0.99      sample        17.244           ms/op
Client.existUser:existUser·p0.999     sample        33.373           ms/op
Client.existUser:existUser·p0.9999    sample        33.948           ms/op
Client.existUser:existUser·p1.00      sample        33.948           ms/op
Client.getUser                        sample  4884   6.611 ± 0.146   ms/op
Client.getUser:getUser·p0.00          sample         0.633           ms/op
Client.getUser:getUser·p0.50          sample         6.222           ms/op
Client.getUser:getUser·p0.90          sample         9.331           ms/op
Client.getUser:getUser·p0.95          sample        10.592           ms/op
Client.getUser:getUser·p0.99          sample        21.964           ms/op
Client.getUser:getUser·p0.999         sample        29.164           ms/op
Client.getUser:getUser·p0.9999        sample        30.540           ms/op
Client.getUser:getUser·p1.00          sample        30.540           ms/op
Client.listUser                       sample  1289  25.041 ± 0.508   ms/op
Client.listUser:listUser·p0.00        sample         6.300           ms/op
Client.listUser:listUser·p0.50        sample        26.280           ms/op
Client.listUser:listUser·p0.90        sample        29.917           ms/op
Client.listUser:listUser·p0.95        sample        34.341           ms/op
Client.listUser:listUser·p0.99        sample        37.755           ms/op
Client.listUser:listUser·p0.999       sample        40.011           ms/op
Client.listUser:listUser·p0.9999      sample        40.239           ms/op
Client.listUser:listUser·p1.00        sample        40.239           ms/op
