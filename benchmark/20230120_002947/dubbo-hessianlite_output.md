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
# Warmup Iteration   1: 1.159 ops/ms
Iteration   1: 3.142 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.142 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.159 ops/ms
Iteration   1: 6.675 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.675 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.734 ops/ms
Iteration   1: 4.671 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.671 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 0.982 ops/ms
Iteration   1: 1.356 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.356 ops/ms


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
# Warmup Iteration   1: 17.275 ±(99.9%) 0.265 ms/op
Iteration   1: 6.773 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.773 ms/op


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
# Warmup Iteration   1: 6.125 ±(99.9%) 0.068 ms/op
Iteration   1: 2.861 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.861 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.965 ±(99.9%) 0.101 ms/op
Iteration   1: 4.559 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.559 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 25.995 ±(99.9%) 0.400 ms/op
Iteration   1: 17.112 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.112 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.585 ±(99.9%) 0.369 ms/op
Iteration   1: 5.762 ±(99.9%) 0.115 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   6.029 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   11.176 ms/op
                 createUser·p0.99:   17.760 ms/op
                 createUser·p0.999:  22.217 ms/op
                 createUser·p0.9999: 23.691 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5616
  mean =      5.762 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 348 
    [ 2.500,  5.000) = 1686 
    [ 5.000,  7.500) = 3127 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      6.029 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =     11.176 ms/op
     p(99.0000) =     17.760 ms/op
     p(99.9000) =     22.217 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.872 ±(99.9%) 0.168 ms/op
Iteration   1: 3.452 ±(99.9%) 0.046 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   11.764 ms/op
                 existUser·p0.999:  15.166 ms/op
                 existUser·p0.9999: 16.286 ms/op
                 existUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9346
  mean =      3.452 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 871 
    [ 2.500,  3.750) = 7619 
    [ 3.750,  5.000) = 445 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 145 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =     11.764 ms/op
     p(99.9000) =     15.166 ms/op
     p(99.9900) =     16.286 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 8.394 ±(99.9%) 0.381 ms/op
Iteration   1: 4.380 ±(99.9%) 0.062 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   8.192 ms/op
                 getUser·p0.999:  24.598 ms/op
                 getUser·p0.9999: 25.690 ms/op
                 getUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7337
  mean =      4.380 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 166 
    [ 2.500,  5.000) = 6022 
    [ 5.000,  7.500) = 1024 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     24.598 ms/op
     p(99.9900) =     25.690 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 25.660 ±(99.9%) 0.682 ms/op
Iteration   1: 16.970 ±(99.9%) 0.294 ms/op
                 listUser·p0.00:   5.456 ms/op
                 listUser·p0.50:   15.172 ms/op
                 listUser·p0.90:   22.774 ms/op
                 listUser·p0.95:   23.298 ms/op
                 listUser·p0.99:   28.230 ms/op
                 listUser·p0.999:  33.528 ms/op
                 listUser·p0.9999: 34.603 ms/op
                 listUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1886
  mean =     16.970 ±(99.9%) 0.294 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 648 
    [15.000, 17.500) = 488 
    [17.500, 20.000) = 187 
    [20.000, 22.500) = 215 
    [22.500, 25.000) = 201 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.456 ms/op
     p(50.0000) =     15.172 ms/op
     p(90.0000) =     22.774 ms/op
     p(95.0000) =     23.298 ms/op
     p(99.0000) =     28.230 ms/op
     p(99.9000) =     33.528 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.142          ops/ms
Client.existUser                       thrpt         6.675          ops/ms
Client.getUser                         thrpt         4.671          ops/ms
Client.listUser                        thrpt         1.356          ops/ms
Client.createUser                       avgt         6.773           ms/op
Client.existUser                        avgt         2.861           ms/op
Client.getUser                          avgt         4.559           ms/op
Client.listUser                         avgt        17.112           ms/op
Client.createUser                     sample  5616   5.762 ± 0.115   ms/op
Client.createUser:createUser·p0.00    sample         1.004           ms/op
Client.createUser:createUser·p0.50    sample         6.029           ms/op
Client.createUser:createUser·p0.90    sample         6.947           ms/op
Client.createUser:createUser·p0.95    sample        11.176           ms/op
Client.createUser:createUser·p0.99    sample        17.760           ms/op
Client.createUser:createUser·p0.999   sample        22.217           ms/op
Client.createUser:createUser·p0.9999  sample        23.691           ms/op
Client.createUser:createUser·p1.00    sample        23.691           ms/op
Client.existUser                      sample  9346   3.452 ± 0.046   ms/op
Client.existUser:existUser·p0.00      sample         1.100           ms/op
Client.existUser:existUser·p0.50      sample         3.478           ms/op
Client.existUser:existUser·p0.90      sample         3.731           ms/op
Client.existUser:existUser·p0.95      sample         4.317           ms/op
Client.existUser:existUser·p0.99      sample        11.764           ms/op
Client.existUser:existUser·p0.999     sample        15.166           ms/op
Client.existUser:existUser·p0.9999    sample        16.286           ms/op
Client.existUser:existUser·p1.00      sample        16.286           ms/op
Client.getUser                        sample  7337   4.380 ± 0.062   ms/op
Client.getUser:getUser·p0.00          sample         1.272           ms/op
Client.getUser:getUser·p0.50          sample         4.219           ms/op
Client.getUser:getUser·p0.90          sample         5.308           ms/op
Client.getUser:getUser·p0.95          sample         5.800           ms/op
Client.getUser:getUser·p0.99          sample         8.192           ms/op
Client.getUser:getUser·p0.999         sample        24.598           ms/op
Client.getUser:getUser·p0.9999        sample        25.690           ms/op
Client.getUser:getUser·p1.00          sample        25.690           ms/op
Client.listUser                       sample  1886  16.970 ± 0.294   ms/op
Client.listUser:listUser·p0.00        sample         5.456           ms/op
Client.listUser:listUser·p0.50        sample        15.172           ms/op
Client.listUser:listUser·p0.90        sample        22.774           ms/op
Client.listUser:listUser·p0.95        sample        23.298           ms/op
Client.listUser:listUser·p0.99        sample        28.230           ms/op
Client.listUser:listUser·p0.999       sample        33.528           ms/op
Client.listUser:listUser·p0.9999      sample        34.603           ms/op
Client.listUser:listUser·p1.00        sample        34.603           ms/op
