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
# Warmup Iteration   1: 0.523 ops/ms
Iteration   1: 1.235 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.235 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:27
# Fork: 1 of 1
# Warmup Iteration   1: 1.541 ops/ms
Iteration   1: 3.373 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.373 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.181 ops/ms
Iteration   1: 2.481 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.481 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 0.603 ops/ms
Iteration   1: 0.878 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.878 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 27.292 ±(99.9%) 0.481 ms/op
Iteration   1: 16.739 ±(99.9%) 0.117 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.739 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 22.420 ±(99.9%) 0.419 ms/op
Iteration   1: 9.464 ±(99.9%) 0.115 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.464 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:46
# Fork: 1 of 1
# Warmup Iteration   1: 20.090 ±(99.9%) 0.274 ms/op
Iteration   1: 8.235 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.235 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 41.700 ±(99.9%) 0.846 ms/op
Iteration   1: 26.342 ±(99.9%) 0.213 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  26.342 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.586 ±(99.9%) 0.842 ms/op
Iteration   1: 14.239 ±(99.9%) 0.460 ms/op
                 createUser·p0.00:   4.948 ms/op
                 createUser·p0.50:   12.206 ms/op
                 createUser·p0.90:   22.171 ms/op
                 createUser·p0.95:   28.046 ms/op
                 createUser·p0.99:   46.818 ms/op
                 createUser·p0.999:  49.136 ms/op
                 createUser·p0.9999: 49.152 ms/op
                 createUser·p1.00:   49.152 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2241
  mean =     14.239 ±(99.9%) 0.460 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3 
    [ 5.000, 10.000) = 97 
    [10.000, 15.000) = 1689 
    [15.000, 20.000) = 223 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 95 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      4.948 ms/op
     p(50.0000) =     12.206 ms/op
     p(90.0000) =     22.171 ms/op
     p(95.0000) =     28.046 ms/op
     p(99.0000) =     46.818 ms/op
     p(99.9000) =     49.136 ms/op
     p(99.9900) =     49.152 ms/op
     p(99.9990) =     49.152 ms/op
     p(99.9999) =     49.152 ms/op
    p(100.0000) =     49.152 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 15.494 ±(99.9%) 0.434 ms/op
Iteration   1: 6.887 ±(99.9%) 0.149 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   6.291 ms/op
                 existUser·p0.90:   9.114 ms/op
                 existUser·p0.95:   10.535 ms/op
                 existUser·p0.99:   24.544 ms/op
                 existUser·p0.999:  27.132 ms/op
                 existUser·p0.9999: 36.897 ms/op
                 existUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4656
  mean =      6.887 ±(99.9%) 0.149 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 897 
    [ 5.000,  7.500) = 2194 
    [ 7.500, 10.000) = 1218 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      6.291 ms/op
     p(90.0000) =      9.114 ms/op
     p(95.0000) =     10.535 ms/op
     p(99.0000) =     24.544 ms/op
     p(99.9000) =     27.132 ms/op
     p(99.9900) =     36.897 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 17.555 ±(99.9%) 0.632 ms/op
Iteration   1: 8.311 ±(99.9%) 0.194 ms/op
                 getUser·p0.00:   1.616 ms/op
                 getUser·p0.50:   7.471 ms/op
                 getUser·p0.90:   11.665 ms/op
                 getUser·p0.95:   13.156 ms/op
                 getUser·p0.99:   18.317 ms/op
                 getUser·p0.999:  40.042 ms/op
                 getUser·p0.9999: 40.042 ms/op
                 getUser·p1.00:   40.042 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3898
  mean =      8.311 ±(99.9%) 0.194 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 249 
    [ 5.000, 10.000) = 2972 
    [10.000, 15.000) = 560 
    [15.000, 20.000) = 83 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      7.471 ms/op
     p(90.0000) =     11.665 ms/op
     p(95.0000) =     13.156 ms/op
     p(99.0000) =     18.317 ms/op
     p(99.9000) =     40.042 ms/op
     p(99.9900) =     40.042 ms/op
     p(99.9990) =     40.042 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


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
# Warmup Iteration   1: 44.977 ±(99.9%) 1.912 ms/op
Iteration   1: 30.641 ±(99.9%) 1.026 ms/op
                 listUser·p0.00:   10.289 ms/op
                 listUser·p0.50:   27.132 ms/op
                 listUser·p0.90:   42.480 ms/op
                 listUser·p0.95:   54.709 ms/op
                 listUser·p0.99:   70.008 ms/op
                 listUser·p0.999:  74.272 ms/op
                 listUser·p0.9999: 74.318 ms/op
                 listUser·p1.00:   74.318 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1043
  mean =     30.641 ±(99.9%) 1.026 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 1 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 207 
    [25.000, 30.000) = 480 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 125 
    [40.000, 45.000) = 36 
    [45.000, 50.000) = 23 
    [50.000, 55.000) = 16 
    [55.000, 60.000) = 22 
    [60.000, 65.000) = 4 
    [65.000, 70.000) = 14 
    [70.000, 75.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =     10.289 ms/op
     p(50.0000) =     27.132 ms/op
     p(90.0000) =     42.480 ms/op
     p(95.0000) =     54.709 ms/op
     p(99.0000) =     70.008 ms/op
     p(99.9000) =     74.272 ms/op
     p(99.9900) =     74.318 ms/op
     p(99.9990) =     74.318 ms/op
     p(99.9999) =     74.318 ms/op
    p(100.0000) =     74.318 ms/op


# Run complete. Total time: 00:01:33

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.235          ops/ms
Client.existUser                       thrpt         3.373          ops/ms
Client.getUser                         thrpt         2.481          ops/ms
Client.listUser                        thrpt         0.878          ops/ms
Client.createUser                       avgt        16.739           ms/op
Client.existUser                        avgt         9.464           ms/op
Client.getUser                          avgt         8.235           ms/op
Client.listUser                         avgt        26.342           ms/op
Client.createUser                     sample  2241  14.239 ± 0.460   ms/op
Client.createUser:createUser·p0.00    sample         4.948           ms/op
Client.createUser:createUser·p0.50    sample        12.206           ms/op
Client.createUser:createUser·p0.90    sample        22.171           ms/op
Client.createUser:createUser·p0.95    sample        28.046           ms/op
Client.createUser:createUser·p0.99    sample        46.818           ms/op
Client.createUser:createUser·p0.999   sample        49.136           ms/op
Client.createUser:createUser·p0.9999  sample        49.152           ms/op
Client.createUser:createUser·p1.00    sample        49.152           ms/op
Client.existUser                      sample  4656   6.887 ± 0.149   ms/op
Client.existUser:existUser·p0.00      sample         0.904           ms/op
Client.existUser:existUser·p0.50      sample         6.291           ms/op
Client.existUser:existUser·p0.90      sample         9.114           ms/op
Client.existUser:existUser·p0.95      sample        10.535           ms/op
Client.existUser:existUser·p0.99      sample        24.544           ms/op
Client.existUser:existUser·p0.999     sample        27.132           ms/op
Client.existUser:existUser·p0.9999    sample        36.897           ms/op
Client.existUser:existUser·p1.00      sample        36.897           ms/op
Client.getUser                        sample  3898   8.311 ± 0.194   ms/op
Client.getUser:getUser·p0.00          sample         1.616           ms/op
Client.getUser:getUser·p0.50          sample         7.471           ms/op
Client.getUser:getUser·p0.90          sample        11.665           ms/op
Client.getUser:getUser·p0.95          sample        13.156           ms/op
Client.getUser:getUser·p0.99          sample        18.317           ms/op
Client.getUser:getUser·p0.999         sample        40.042           ms/op
Client.getUser:getUser·p0.9999        sample        40.042           ms/op
Client.getUser:getUser·p1.00          sample        40.042           ms/op
Client.listUser                       sample  1043  30.641 ± 1.026   ms/op
Client.listUser:listUser·p0.00        sample        10.289           ms/op
Client.listUser:listUser·p0.50        sample        27.132           ms/op
Client.listUser:listUser·p0.90        sample        42.480           ms/op
Client.listUser:listUser·p0.95        sample        54.709           ms/op
Client.listUser:listUser·p0.99        sample        70.008           ms/op
Client.listUser:listUser·p0.999       sample        74.272           ms/op
Client.listUser:listUser·p0.9999      sample        74.318           ms/op
Client.listUser:listUser·p1.00        sample        74.318           ms/op
