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
# Warmup Iteration   1: 1.127 ops/ms
Iteration   1: 2.232 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.232 ops/ms


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
# Warmup Iteration   1: 3.555 ops/ms
Iteration   1: 8.175 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.175 ops/ms


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
# Warmup Iteration   1: 1.825 ops/ms
Iteration   1: 4.730 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.730 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.792 ops/ms
Iteration   1: 1.245 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.245 ops/ms


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
# Warmup Iteration   1: 14.728 ±(99.9%) 0.307 ms/op
Iteration   1: 6.643 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.643 ms/op


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
# Warmup Iteration   1: 6.461 ±(99.9%) 0.099 ms/op
Iteration   1: 3.506 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.506 ms/op


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
# Warmup Iteration   1: 7.485 ±(99.9%) 0.122 ms/op
Iteration   1: 4.639 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.639 ms/op


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
# Warmup Iteration   1: 26.501 ±(99.9%) 0.502 ms/op
Iteration   1: 18.296 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.296 ms/op


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
# Warmup Iteration   1: 11.360 ±(99.9%) 0.322 ms/op
Iteration   1: 6.540 ±(99.9%) 0.073 ms/op
                 createUser·p0.00:   3.289 ms/op
                 createUser·p0.50:   6.504 ms/op
                 createUser·p0.90:   7.274 ms/op
                 createUser·p0.95:   7.782 ms/op
                 createUser·p0.99:   14.304 ms/op
                 createUser·p0.999:  15.960 ms/op
                 createUser·p0.9999: 16.220 ms/op
                 createUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4897
  mean =      6.540 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 16 
    [ 3.750,  5.000) = 250 
    [ 5.000,  6.250) = 1320 
    [ 6.250,  7.500) = 3006 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.289 ms/op
     p(50.0000) =      6.504 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      7.782 ms/op
     p(99.0000) =     14.304 ms/op
     p(99.9000) =     15.960 ms/op
     p(99.9900) =     16.220 ms/op
     p(99.9990) =     16.220 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


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
# Warmup Iteration   1: 6.232 ±(99.9%) 0.236 ms/op
Iteration   1: 3.719 ±(99.9%) 0.051 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   8.571 ms/op
                 existUser·p0.999:  23.134 ms/op
                 existUser·p0.9999: 23.200 ms/op
                 existUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8670
  mean =      3.719 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 449 
    [ 2.500,  5.000) = 7893 
    [ 5.000,  7.500) = 187 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      8.571 ms/op
     p(99.9000) =     23.134 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 7.564 ±(99.9%) 0.261 ms/op
Iteration   1: 4.139 ±(99.9%) 0.054 ms/op
                 getUser·p0.00:   0.349 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   10.991 ms/op
                 getUser·p0.999:  17.269 ms/op
                 getUser·p0.9999: 17.465 ms/op
                 getUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7813
  mean =      4.139 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 110 
    [ 2.500,  3.750) = 3263 
    [ 3.750,  5.000) = 3572 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =     10.991 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 31.294 ±(99.9%) 1.331 ms/op
Iteration   1: 27.791 ±(99.9%) 0.933 ms/op
                 listUser·p0.00:   9.306 ms/op
                 listUser·p0.50:   27.591 ms/op
                 listUser·p0.90:   41.445 ms/op
                 listUser·p0.95:   44.761 ms/op
                 listUser·p0.99:   52.720 ms/op
                 listUser·p0.999:  58.290 ms/op
                 listUser·p0.9999: 58.393 ms/op
                 listUser·p1.00:   58.393 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1155
  mean =     27.791 ±(99.9%) 0.933 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 4 
    [10.000, 15.000) = 55 
    [15.000, 20.000) = 277 
    [20.000, 25.000) = 167 
    [25.000, 30.000) = 202 
    [30.000, 35.000) = 168 
    [35.000, 40.000) = 139 
    [40.000, 45.000) = 93 
    [45.000, 50.000) = 33 
    [50.000, 55.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      9.306 ms/op
     p(50.0000) =     27.591 ms/op
     p(90.0000) =     41.445 ms/op
     p(95.0000) =     44.761 ms/op
     p(99.0000) =     52.720 ms/op
     p(99.9000) =     58.290 ms/op
     p(99.9900) =     58.393 ms/op
     p(99.9990) =     58.393 ms/op
     p(99.9999) =     58.393 ms/op
    p(100.0000) =     58.393 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.232          ops/ms
Client.existUser                       thrpt         8.175          ops/ms
Client.getUser                         thrpt         4.730          ops/ms
Client.listUser                        thrpt         1.245          ops/ms
Client.createUser                       avgt         6.643           ms/op
Client.existUser                        avgt         3.506           ms/op
Client.getUser                          avgt         4.639           ms/op
Client.listUser                         avgt        18.296           ms/op
Client.createUser                     sample  4897   6.540 ± 0.073   ms/op
Client.createUser:createUser·p0.00    sample         3.289           ms/op
Client.createUser:createUser·p0.50    sample         6.504           ms/op
Client.createUser:createUser·p0.90    sample         7.274           ms/op
Client.createUser:createUser·p0.95    sample         7.782           ms/op
Client.createUser:createUser·p0.99    sample        14.304           ms/op
Client.createUser:createUser·p0.999   sample        15.960           ms/op
Client.createUser:createUser·p0.9999  sample        16.220           ms/op
Client.createUser:createUser·p1.00    sample        16.220           ms/op
Client.existUser                      sample  8670   3.719 ± 0.051   ms/op
Client.existUser:existUser·p0.00      sample         0.892           ms/op
Client.existUser:existUser·p0.50      sample         3.633           ms/op
Client.existUser:existUser·p0.90      sample         4.030           ms/op
Client.existUser:existUser·p0.95      sample         4.620           ms/op
Client.existUser:existUser·p0.99      sample         8.571           ms/op
Client.existUser:existUser·p0.999     sample        23.134           ms/op
Client.existUser:existUser·p0.9999    sample        23.200           ms/op
Client.existUser:existUser·p1.00      sample        23.200           ms/op
Client.getUser                        sample  7813   4.139 ± 0.054   ms/op
Client.getUser:getUser·p0.00          sample         0.349           ms/op
Client.getUser:getUser·p0.50          sample         3.891           ms/op
Client.getUser:getUser·p0.90          sample         5.046           ms/op
Client.getUser:getUser·p0.95          sample         5.906           ms/op
Client.getUser:getUser·p0.99          sample        10.991           ms/op
Client.getUser:getUser·p0.999         sample        17.269           ms/op
Client.getUser:getUser·p0.9999        sample        17.465           ms/op
Client.getUser:getUser·p1.00          sample        17.465           ms/op
Client.listUser                       sample  1155  27.791 ± 0.933   ms/op
Client.listUser:listUser·p0.00        sample         9.306           ms/op
Client.listUser:listUser·p0.50        sample        27.591           ms/op
Client.listUser:listUser·p0.90        sample        41.445           ms/op
Client.listUser:listUser·p0.95        sample        44.761           ms/op
Client.listUser:listUser·p0.99        sample        52.720           ms/op
Client.listUser:listUser·p0.999       sample        58.290           ms/op
Client.listUser:listUser·p0.9999      sample        58.393           ms/op
Client.listUser:listUser·p1.00        sample        58.393           ms/op
