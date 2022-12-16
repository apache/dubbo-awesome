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
# Warmup Iteration   1: 0.703 ops/ms
Iteration   1: 1.536 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.536 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 1.750 ops/ms
Iteration   1: 3.736 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.736 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.311 ops/ms
Iteration   1: 2.883 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.883 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 0.672 ops/ms
Iteration   1: 0.911 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.911 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 26.778 ±(99.9%) 0.445 ms/op
Iteration   1: 14.607 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  14.607 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 18.845 ±(99.9%) 0.321 ms/op
Iteration   1: 8.374 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.374 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.459 ±(99.9%) 0.346 ms/op
Iteration   1: 7.620 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.620 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 38.895 ±(99.9%) 0.613 ms/op
Iteration   1: 24.770 ±(99.9%) 0.167 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  24.770 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 25.326 ±(99.9%) 1.123 ms/op
Iteration   1: 12.660 ±(99.9%) 0.337 ms/op
                 createUser·p0.00:   2.089 ms/op
                 createUser·p0.50:   12.075 ms/op
                 createUser·p0.90:   18.514 ms/op
                 createUser·p0.95:   23.101 ms/op
                 createUser·p0.99:   35.193 ms/op
                 createUser·p0.999:  36.045 ms/op
                 createUser·p0.9999: 36.045 ms/op
                 createUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2510
  mean =     12.660 ±(99.9%) 0.337 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 129 
    [ 5.000,  7.500) = 167 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 1133 
    [12.500, 15.000) = 569 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.089 ms/op
     p(50.0000) =     12.075 ms/op
     p(90.0000) =     18.514 ms/op
     p(95.0000) =     23.101 ms/op
     p(99.0000) =     35.193 ms/op
     p(99.9000) =     36.045 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 11.130 ±(99.9%) 0.454 ms/op
Iteration   1: 6.598 ±(99.9%) 0.086 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   6.504 ms/op
                 existUser·p0.90:   7.619 ms/op
                 existUser·p0.95:   8.678 ms/op
                 existUser·p0.99:   15.665 ms/op
                 existUser·p0.999:  16.432 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4786
  mean =      6.598 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 363 
    [ 5.000,  7.500) = 3859 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.372 ms/op
     p(50.0000) =      6.504 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.678 ms/op
     p(99.0000) =     15.665 ms/op
     p(99.9000) =     16.432 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 18.116 ±(99.9%) 0.580 ms/op
Iteration   1: 7.138 ±(99.9%) 0.176 ms/op
                 getUser·p0.00:   2.040 ms/op
                 getUser·p0.50:   6.398 ms/op
                 getUser·p0.90:   9.142 ms/op
                 getUser·p0.95:   12.637 ms/op
                 getUser·p0.99:   24.754 ms/op
                 getUser·p0.999:  38.011 ms/op
                 getUser·p0.9999: 38.076 ms/op
                 getUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4481
  mean =      7.138 ±(99.9%) 0.176 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 686 
    [ 5.000,  7.500) = 2720 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.040 ms/op
     p(50.0000) =      6.398 ms/op
     p(90.0000) =      9.142 ms/op
     p(95.0000) =     12.637 ms/op
     p(99.0000) =     24.754 ms/op
     p(99.9000) =     38.011 ms/op
     p(99.9900) =     38.076 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 45.476 ±(99.9%) 1.665 ms/op
Iteration   1: 24.300 ±(99.9%) 0.566 ms/op
                 listUser·p0.00:   8.454 ms/op
                 listUser·p0.50:   23.658 ms/op
                 listUser·p0.90:   31.549 ms/op
                 listUser·p0.95:   33.686 ms/op
                 listUser·p0.99:   43.183 ms/op
                 listUser·p0.999:  49.161 ms/op
                 listUser·p0.9999: 49.414 ms/op
                 listUser·p1.00:   49.414 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1321
  mean =     24.300 ±(99.9%) 0.566 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 4 
    [10.000, 15.000) = 26 
    [15.000, 20.000) = 413 
    [20.000, 25.000) = 300 
    [25.000, 30.000) = 347 
    [30.000, 35.000) = 175 
    [35.000, 40.000) = 36 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      8.454 ms/op
     p(50.0000) =     23.658 ms/op
     p(90.0000) =     31.549 ms/op
     p(95.0000) =     33.686 ms/op
     p(99.0000) =     43.183 ms/op
     p(99.9000) =     49.161 ms/op
     p(99.9900) =     49.414 ms/op
     p(99.9990) =     49.414 ms/op
     p(99.9999) =     49.414 ms/op
    p(100.0000) =     49.414 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.536          ops/ms
Client.existUser                       thrpt         3.736          ops/ms
Client.getUser                         thrpt         2.883          ops/ms
Client.listUser                        thrpt         0.911          ops/ms
Client.createUser                       avgt        14.607           ms/op
Client.existUser                        avgt         8.374           ms/op
Client.getUser                          avgt         7.620           ms/op
Client.listUser                         avgt        24.770           ms/op
Client.createUser                     sample  2510  12.660 ± 0.337   ms/op
Client.createUser:createUser·p0.00    sample         2.089           ms/op
Client.createUser:createUser·p0.50    sample        12.075           ms/op
Client.createUser:createUser·p0.90    sample        18.514           ms/op
Client.createUser:createUser·p0.95    sample        23.101           ms/op
Client.createUser:createUser·p0.99    sample        35.193           ms/op
Client.createUser:createUser·p0.999   sample        36.045           ms/op
Client.createUser:createUser·p0.9999  sample        36.045           ms/op
Client.createUser:createUser·p1.00    sample        36.045           ms/op
Client.existUser                      sample  4786   6.598 ± 0.086   ms/op
Client.existUser:existUser·p0.00      sample         2.372           ms/op
Client.existUser:existUser·p0.50      sample         6.504           ms/op
Client.existUser:existUser·p0.90      sample         7.619           ms/op
Client.existUser:existUser·p0.95      sample         8.678           ms/op
Client.existUser:existUser·p0.99      sample        15.665           ms/op
Client.existUser:existUser·p0.999     sample        16.432           ms/op
Client.existUser:existUser·p0.9999    sample        22.577           ms/op
Client.existUser:existUser·p1.00      sample        22.577           ms/op
Client.getUser                        sample  4481   7.138 ± 0.176   ms/op
Client.getUser:getUser·p0.00          sample         2.040           ms/op
Client.getUser:getUser·p0.50          sample         6.398           ms/op
Client.getUser:getUser·p0.90          sample         9.142           ms/op
Client.getUser:getUser·p0.95          sample        12.637           ms/op
Client.getUser:getUser·p0.99          sample        24.754           ms/op
Client.getUser:getUser·p0.999         sample        38.011           ms/op
Client.getUser:getUser·p0.9999        sample        38.076           ms/op
Client.getUser:getUser·p1.00          sample        38.076           ms/op
Client.listUser                       sample  1321  24.300 ± 0.566   ms/op
Client.listUser:listUser·p0.00        sample         8.454           ms/op
Client.listUser:listUser·p0.50        sample        23.658           ms/op
Client.listUser:listUser·p0.90        sample        31.549           ms/op
Client.listUser:listUser·p0.95        sample        33.686           ms/op
Client.listUser:listUser·p0.99        sample        43.183           ms/op
Client.listUser:listUser·p0.999       sample        49.161           ms/op
Client.listUser:listUser·p0.9999      sample        49.414           ms/op
Client.listUser:listUser·p1.00        sample        49.414           ms/op
