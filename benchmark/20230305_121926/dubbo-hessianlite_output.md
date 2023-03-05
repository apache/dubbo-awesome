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
# Warmup Iteration   1: 1.184 ops/ms
Iteration   1: 2.152 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.152 ops/ms


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
# Warmup Iteration   1: 3.251 ops/ms
Iteration   1: 8.810 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.810 ops/ms


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
# Warmup Iteration   1: 1.755 ops/ms
Iteration   1: 4.528 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.528 ops/ms


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
# Warmup Iteration   1: 0.876 ops/ms
Iteration   1: 1.242 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.242 ops/ms


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
# Warmup Iteration   1: 19.483 ±(99.9%) 0.253 ms/op
Iteration   1: 8.840 ±(99.9%) 0.056 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.840 ms/op


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
# Warmup Iteration   1: 8.775 ±(99.9%) 0.109 ms/op
Iteration   1: 4.863 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.863 ms/op


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
# Warmup Iteration   1: 9.319 ±(99.9%) 0.105 ms/op
Iteration   1: 5.708 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.708 ms/op


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
# Warmup Iteration   1: 27.474 ±(99.9%) 0.258 ms/op
Iteration   1: 20.222 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.222 ms/op


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
# Warmup Iteration   1: 13.074 ±(99.9%) 0.397 ms/op
Iteration   1: 7.253 ±(99.9%) 0.113 ms/op
                 createUser·p0.00:   1.978 ms/op
                 createUser·p0.50:   6.988 ms/op
                 createUser·p0.90:   8.995 ms/op
                 createUser·p0.95:   9.421 ms/op
                 createUser·p0.99:   16.318 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 17.105 ms/op
                 createUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4403
  mean =      7.253 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 72 
    [ 2.500,  3.750) = 279 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 1174 
    [ 6.250,  7.500) = 656 
    [ 7.500,  8.750) = 1296 
    [ 8.750, 10.000) = 670 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 66 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      6.988 ms/op
     p(90.0000) =      8.995 ms/op
     p(95.0000) =      9.421 ms/op
     p(99.0000) =     16.318 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 7.383 ±(99.9%) 0.234 ms/op
Iteration   1: 3.854 ±(99.9%) 0.094 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.318 ms/op
                 existUser·p0.99:   12.665 ms/op
                 existUser·p0.999:  39.040 ms/op
                 existUser·p0.9999: 39.780 ms/op
                 existUser·p1.00:   39.780 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8296
  mean =      3.854 ±(99.9%) 0.094 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1207 
    [ 2.500,  5.000) = 6413 
    [ 5.000,  7.500) = 421 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.318 ms/op
     p(99.0000) =     12.665 ms/op
     p(99.9000) =     39.040 ms/op
     p(99.9900) =     39.780 ms/op
     p(99.9990) =     39.780 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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
# Warmup Iteration   1: 9.018 ±(99.9%) 0.389 ms/op
Iteration   1: 4.658 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   10.488 ms/op
                 getUser·p0.999:  15.063 ms/op
                 getUser·p0.9999: 15.286 ms/op
                 getUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6865
  mean =      4.658 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 16 
    [ 2.500,  3.750) = 209 
    [ 3.750,  5.000) = 5564 
    [ 5.000,  6.250) = 844 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =     10.488 ms/op
     p(99.9000) =     15.063 ms/op
     p(99.9900) =     15.286 ms/op
     p(99.9990) =     15.286 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 32.706 ±(99.9%) 1.297 ms/op
Iteration   1: 18.378 ±(99.9%) 0.446 ms/op
                 listUser·p0.00:   6.398 ms/op
                 listUser·p0.50:   15.466 ms/op
                 listUser·p0.90:   26.477 ms/op
                 listUser·p0.95:   30.717 ms/op
                 listUser·p0.99:   38.168 ms/op
                 listUser·p0.999:  45.107 ms/op
                 listUser·p0.9999: 45.351 ms/op
                 listUser·p1.00:   45.351 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1743
  mean =     18.378 ±(99.9%) 0.446 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 7 
    [10.000, 15.000) = 532 
    [15.000, 20.000) = 696 
    [20.000, 25.000) = 298 
    [25.000, 30.000) = 120 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 39 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      6.398 ms/op
     p(50.0000) =     15.466 ms/op
     p(90.0000) =     26.477 ms/op
     p(95.0000) =     30.717 ms/op
     p(99.0000) =     38.168 ms/op
     p(99.9000) =     45.107 ms/op
     p(99.9900) =     45.351 ms/op
     p(99.9990) =     45.351 ms/op
     p(99.9999) =     45.351 ms/op
    p(100.0000) =     45.351 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.152          ops/ms
Client.existUser                       thrpt         8.810          ops/ms
Client.getUser                         thrpt         4.528          ops/ms
Client.listUser                        thrpt         1.242          ops/ms
Client.createUser                       avgt         8.840           ms/op
Client.existUser                        avgt         4.863           ms/op
Client.getUser                          avgt         5.708           ms/op
Client.listUser                         avgt        20.222           ms/op
Client.createUser                     sample  4403   7.253 ± 0.113   ms/op
Client.createUser:createUser·p0.00    sample         1.978           ms/op
Client.createUser:createUser·p0.50    sample         6.988           ms/op
Client.createUser:createUser·p0.90    sample         8.995           ms/op
Client.createUser:createUser·p0.95    sample         9.421           ms/op
Client.createUser:createUser·p0.99    sample        16.318           ms/op
Client.createUser:createUser·p0.999   sample        17.105           ms/op
Client.createUser:createUser·p0.9999  sample        17.105           ms/op
Client.createUser:createUser·p1.00    sample        17.105           ms/op
Client.existUser                      sample  8296   3.854 ± 0.094   ms/op
Client.existUser:existUser·p0.00      sample         0.816           ms/op
Client.existUser:existUser·p0.50      sample         3.625           ms/op
Client.existUser:existUser·p0.90      sample         4.858           ms/op
Client.existUser:existUser·p0.95      sample         5.318           ms/op
Client.existUser:existUser·p0.99      sample        12.665           ms/op
Client.existUser:existUser·p0.999     sample        39.040           ms/op
Client.existUser:existUser·p0.9999    sample        39.780           ms/op
Client.existUser:existUser·p1.00      sample        39.780           ms/op
Client.getUser                        sample  6865   4.658 ± 0.045   ms/op
Client.getUser:getUser·p0.00          sample         1.622           ms/op
Client.getUser:getUser·p0.50          sample         4.465           ms/op
Client.getUser:getUser·p0.90          sample         5.267           ms/op
Client.getUser:getUser·p0.95          sample         5.915           ms/op
Client.getUser:getUser·p0.99          sample        10.488           ms/op
Client.getUser:getUser·p0.999         sample        15.063           ms/op
Client.getUser:getUser·p0.9999        sample        15.286           ms/op
Client.getUser:getUser·p1.00          sample        15.286           ms/op
Client.listUser                       sample  1743  18.378 ± 0.446   ms/op
Client.listUser:listUser·p0.00        sample         6.398           ms/op
Client.listUser:listUser·p0.50        sample        15.466           ms/op
Client.listUser:listUser·p0.90        sample        26.477           ms/op
Client.listUser:listUser·p0.95        sample        30.717           ms/op
Client.listUser:listUser·p0.99        sample        38.168           ms/op
Client.listUser:listUser·p0.999       sample        45.107           ms/op
Client.listUser:listUser·p0.9999      sample        45.351           ms/op
Client.listUser:listUser·p1.00        sample        45.351           ms/op
