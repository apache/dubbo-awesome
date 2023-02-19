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
# Warmup Iteration   1: 0.643 ops/ms
Iteration   1: 1.729 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.729 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.188 ops/ms
Iteration   1: 6.036 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.036 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.028 ops/ms
Iteration   1: 3.745 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.745 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.721 ops/ms
Iteration   1: 1.248 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.248 ops/ms


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
# Warmup Iteration   1: 20.622 ±(99.9%) 0.423 ms/op
Iteration   1: 11.995 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  11.995 ms/op


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
# Warmup Iteration   1: 11.152 ±(99.9%) 0.184 ms/op
Iteration   1: 5.421 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.421 ms/op


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
# Warmup Iteration   1: 10.505 ±(99.9%) 0.151 ms/op
Iteration   1: 5.030 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.030 ms/op


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
# Warmup Iteration   1: 31.669 ±(99.9%) 0.514 ms/op
Iteration   1: 19.235 ±(99.9%) 0.144 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.235 ms/op


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
# Warmup Iteration   1: 13.380 ±(99.9%) 0.527 ms/op
Iteration   1: 7.041 ±(99.9%) 0.145 ms/op
                 createUser·p0.00:   2.114 ms/op
                 createUser·p0.50:   6.185 ms/op
                 createUser·p0.90:   9.191 ms/op
                 createUser·p0.95:   11.878 ms/op
                 createUser·p0.99:   22.428 ms/op
                 createUser·p0.999:  28.020 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4627
  mean =      7.041 ±(99.9%) 0.145 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 172 
    [ 5.000,  7.500) = 3744 
    [ 7.500, 10.000) = 291 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      6.185 ms/op
     p(90.0000) =      9.191 ms/op
     p(95.0000) =     11.878 ms/op
     p(99.0000) =     22.428 ms/op
     p(99.9000) =     28.020 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 7.286 ±(99.9%) 0.232 ms/op
Iteration   1: 3.860 ±(99.9%) 0.097 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   8.503 ms/op
                 existUser·p0.99:   14.796 ms/op
                 existUser·p0.999:  26.935 ms/op
                 existUser·p0.9999: 30.638 ms/op
                 existUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8364
  mean =      3.860 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2348 
    [ 2.500,  5.000) = 5055 
    [ 5.000,  7.500) = 434 
    [ 7.500, 10.000) = 231 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     14.796 ms/op
     p(99.9000) =     26.935 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     30.638 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 12.913 ±(99.9%) 0.428 ms/op
Iteration   1: 4.981 ±(99.9%) 0.090 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   6.010 ms/op
                 getUser·p0.95:   6.947 ms/op
                 getUser·p0.99:   19.528 ms/op
                 getUser·p0.999:  25.362 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6552
  mean =      4.981 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 4329 
    [ 5.000,  7.500) = 1956 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      6.010 ms/op
     p(95.0000) =      6.947 ms/op
     p(99.0000) =     19.528 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 33.107 ±(99.9%) 1.405 ms/op
Iteration   1: 19.538 ±(99.9%) 0.254 ms/op
                 listUser·p0.00:   8.471 ms/op
                 listUser·p0.50:   18.874 ms/op
                 listUser·p0.90:   22.466 ms/op
                 listUser·p0.95:   26.070 ms/op
                 listUser·p0.99:   30.724 ms/op
                 listUser·p0.999:  35.030 ms/op
                 listUser·p0.9999: 37.814 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1633
  mean =     19.538 ±(99.9%) 0.254 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 783 
    [20.000, 22.500) = 467 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      8.471 ms/op
     p(50.0000) =     18.874 ms/op
     p(90.0000) =     22.466 ms/op
     p(95.0000) =     26.070 ms/op
     p(99.0000) =     30.724 ms/op
     p(99.9000) =     35.030 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.729          ops/ms
Client.existUser                       thrpt         6.036          ops/ms
Client.getUser                         thrpt         3.745          ops/ms
Client.listUser                        thrpt         1.248          ops/ms
Client.createUser                       avgt        11.995           ms/op
Client.existUser                        avgt         5.421           ms/op
Client.getUser                          avgt         5.030           ms/op
Client.listUser                         avgt        19.235           ms/op
Client.createUser                     sample  4627   7.041 ± 0.145   ms/op
Client.createUser:createUser·p0.00    sample         2.114           ms/op
Client.createUser:createUser·p0.50    sample         6.185           ms/op
Client.createUser:createUser·p0.90    sample         9.191           ms/op
Client.createUser:createUser·p0.95    sample        11.878           ms/op
Client.createUser:createUser·p0.99    sample        22.428           ms/op
Client.createUser:createUser·p0.999   sample        28.020           ms/op
Client.createUser:createUser·p0.9999  sample        28.312           ms/op
Client.createUser:createUser·p1.00    sample        28.312           ms/op
Client.existUser                      sample  8364   3.860 ± 0.097   ms/op
Client.existUser:existUser·p0.00      sample         0.852           ms/op
Client.existUser:existUser·p0.50      sample         3.129           ms/op
Client.existUser:existUser·p0.90      sample         5.317           ms/op
Client.existUser:existUser·p0.95      sample         8.503           ms/op
Client.existUser:existUser·p0.99      sample        14.796           ms/op
Client.existUser:existUser·p0.999     sample        26.935           ms/op
Client.existUser:existUser·p0.9999    sample        30.638           ms/op
Client.existUser:existUser·p1.00      sample        30.638           ms/op
Client.getUser                        sample  6552   4.981 ± 0.090   ms/op
Client.getUser:getUser·p0.00          sample         1.217           ms/op
Client.getUser:getUser·p0.50          sample         4.727           ms/op
Client.getUser:getUser·p0.90          sample         6.010           ms/op
Client.getUser:getUser·p0.95          sample         6.947           ms/op
Client.getUser:getUser·p0.99          sample        19.528           ms/op
Client.getUser:getUser·p0.999         sample        25.362           ms/op
Client.getUser:getUser·p0.9999        sample        26.083           ms/op
Client.getUser:getUser·p1.00          sample        26.083           ms/op
Client.listUser                       sample  1633  19.538 ± 0.254   ms/op
Client.listUser:listUser·p0.00        sample         8.471           ms/op
Client.listUser:listUser·p0.50        sample        18.874           ms/op
Client.listUser:listUser·p0.90        sample        22.466           ms/op
Client.listUser:listUser·p0.95        sample        26.070           ms/op
Client.listUser:listUser·p0.99        sample        30.724           ms/op
Client.listUser:listUser·p0.999       sample        35.030           ms/op
Client.listUser:listUser·p0.9999      sample        37.814           ms/op
Client.listUser:listUser·p1.00        sample        37.814           ms/op
