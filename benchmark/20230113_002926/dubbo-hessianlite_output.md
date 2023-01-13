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
# Warmup Iteration   1: 1.044 ops/ms
Iteration   1: 2.674 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.674 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.727 ops/ms
Iteration   1: 8.583 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.583 ops/ms


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
# Warmup Iteration   1: 2.509 ops/ms
Iteration   1: 4.260 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.260 ops/ms


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
# Warmup Iteration   1: 0.990 ops/ms
Iteration   1: 1.365 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.365 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 15.492 ±(99.9%) 0.624 ms/op
Iteration   1: 7.562 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.562 ms/op


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
# Warmup Iteration   1: 7.013 ±(99.9%) 0.067 ms/op
Iteration   1: 3.320 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.320 ms/op


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
# Warmup Iteration   1: 9.906 ±(99.9%) 0.138 ms/op
Iteration   1: 4.461 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.461 ms/op


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
# Warmup Iteration   1: 29.178 ±(99.9%) 0.322 ms/op
Iteration   1: 17.639 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.639 ms/op


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
# Warmup Iteration   1: 11.555 ±(99.9%) 0.528 ms/op
Iteration   1: 5.558 ±(99.9%) 0.113 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.676 ms/op
                 createUser·p0.95:   10.568 ms/op
                 createUser·p0.99:   17.826 ms/op
                 createUser·p0.999:  24.068 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5748
  mean =      5.558 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 285 
    [ 2.500,  5.000) = 1554 
    [ 5.000,  7.500) = 3414 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =     10.568 ms/op
     p(99.0000) =     17.826 ms/op
     p(99.9000) =     24.068 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 5.889 ±(99.9%) 0.170 ms/op
Iteration   1: 3.549 ±(99.9%) 0.075 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   10.674 ms/op
                 existUser·p0.999:  31.423 ms/op
                 existUser·p0.9999: 32.211 ms/op
                 existUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9052
  mean =      3.549 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1221 
    [ 2.500,  5.000) = 7439 
    [ 5.000,  7.500) = 137 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =     10.674 ms/op
     p(99.9000) =     31.423 ms/op
     p(99.9900) =     32.211 ms/op
     p(99.9990) =     32.211 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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
# Warmup Iteration   1: 7.313 ±(99.9%) 0.277 ms/op
Iteration   1: 4.117 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   4.002 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   9.044 ms/op
                 getUser·p0.999:  15.857 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7768
  mean =      4.117 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 129 
    [ 2.500,  3.750) = 2620 
    [ 3.750,  5.000) = 4170 
    [ 5.000,  6.250) = 721 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     15.857 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 26.509 ±(99.9%) 0.932 ms/op
Iteration   1: 16.371 ±(99.9%) 0.264 ms/op
                 listUser·p0.00:   6.062 ms/op
                 listUser·p0.50:   16.695 ms/op
                 listUser·p0.90:   19.792 ms/op
                 listUser·p0.95:   22.217 ms/op
                 listUser·p0.99:   28.485 ms/op
                 listUser·p0.999:  36.460 ms/op
                 listUser·p0.9999: 37.290 ms/op
                 listUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1973
  mean =     16.371 ±(99.9%) 0.264 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 533 
    [15.000, 17.500) = 643 
    [17.500, 20.000) = 398 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      6.062 ms/op
     p(50.0000) =     16.695 ms/op
     p(90.0000) =     19.792 ms/op
     p(95.0000) =     22.217 ms/op
     p(99.0000) =     28.485 ms/op
     p(99.9000) =     36.460 ms/op
     p(99.9900) =     37.290 ms/op
     p(99.9990) =     37.290 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.674          ops/ms
Client.existUser                       thrpt         8.583          ops/ms
Client.getUser                         thrpt         4.260          ops/ms
Client.listUser                        thrpt         1.365          ops/ms
Client.createUser                       avgt         7.562           ms/op
Client.existUser                        avgt         3.320           ms/op
Client.getUser                          avgt         4.461           ms/op
Client.listUser                         avgt        17.639           ms/op
Client.createUser                     sample  5748   5.558 ± 0.113   ms/op
Client.createUser:createUser·p0.00    sample         1.524           ms/op
Client.createUser:createUser·p0.50    sample         5.284           ms/op
Client.createUser:createUser·p0.90    sample         6.676           ms/op
Client.createUser:createUser·p0.95    sample        10.568           ms/op
Client.createUser:createUser·p0.99    sample        17.826           ms/op
Client.createUser:createUser·p0.999   sample        24.068           ms/op
Client.createUser:createUser·p0.9999  sample        24.281           ms/op
Client.createUser:createUser·p1.00    sample        24.281           ms/op
Client.existUser                      sample  9052   3.549 ± 0.075   ms/op
Client.existUser:existUser·p0.00      sample         0.633           ms/op
Client.existUser:existUser·p0.50      sample         3.453           ms/op
Client.existUser:existUser·p0.90      sample         3.666           ms/op
Client.existUser:existUser·p0.95      sample         4.227           ms/op
Client.existUser:existUser·p0.99      sample        10.674           ms/op
Client.existUser:existUser·p0.999     sample        31.423           ms/op
Client.existUser:existUser·p0.9999    sample        32.211           ms/op
Client.existUser:existUser·p1.00      sample        32.211           ms/op
Client.getUser                        sample  7768   4.117 ± 0.042   ms/op
Client.getUser:getUser·p0.00          sample         1.556           ms/op
Client.getUser:getUser·p0.50          sample         4.002           ms/op
Client.getUser:getUser·p0.90          sample         5.038           ms/op
Client.getUser:getUser·p0.95          sample         5.390           ms/op
Client.getUser:getUser·p0.99          sample         9.044           ms/op
Client.getUser:getUser·p0.999         sample        15.857           ms/op
Client.getUser:getUser·p0.9999        sample        16.974           ms/op
Client.getUser:getUser·p1.00          sample        16.974           ms/op
Client.listUser                       sample  1973  16.371 ± 0.264   ms/op
Client.listUser:listUser·p0.00        sample         6.062           ms/op
Client.listUser:listUser·p0.50        sample        16.695           ms/op
Client.listUser:listUser·p0.90        sample        19.792           ms/op
Client.listUser:listUser·p0.95        sample        22.217           ms/op
Client.listUser:listUser·p0.99        sample        28.485           ms/op
Client.listUser:listUser·p0.999       sample        36.460           ms/op
Client.listUser:listUser·p0.9999      sample        37.290           ms/op
Client.listUser:listUser·p1.00        sample        37.290           ms/op
