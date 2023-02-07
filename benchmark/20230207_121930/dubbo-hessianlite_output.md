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
# Warmup Iteration   1: 0.991 ops/ms
Iteration   1: 2.080 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.080 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.256 ops/ms
Iteration   1: 6.072 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.072 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.037 ops/ms
Iteration   1: 3.857 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.857 ops/ms


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
# Warmup Iteration   1: 0.831 ops/ms
Iteration   1: 1.286 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.286 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 22.762 ±(99.9%) 0.379 ms/op
Iteration   1: 8.752 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.752 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 6.914 ±(99.9%) 0.090 ms/op
Iteration   1: 3.834 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.834 ms/op


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
# Warmup Iteration   1: 9.743 ±(99.9%) 0.117 ms/op
Iteration   1: 4.920 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.920 ms/op


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
# Warmup Iteration   1: 29.465 ±(99.9%) 0.892 ms/op
Iteration   1: 18.470 ±(99.9%) 0.116 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.470 ms/op


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
# Warmup Iteration   1: 13.523 ±(99.9%) 0.344 ms/op
Iteration   1: 7.259 ±(99.9%) 0.118 ms/op
                 createUser·p0.00:   2.527 ms/op
                 createUser·p0.50:   6.832 ms/op
                 createUser·p0.90:   7.995 ms/op
                 createUser·p0.95:   9.319 ms/op
                 createUser·p0.99:   18.612 ms/op
                 createUser·p0.999:  26.502 ms/op
                 createUser·p0.9999: 26.870 ms/op
                 createUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4403
  mean =      7.259 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 45 
    [ 5.000,  7.500) = 3634 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.527 ms/op
     p(50.0000) =      6.832 ms/op
     p(90.0000) =      7.995 ms/op
     p(95.0000) =      9.319 ms/op
     p(99.0000) =     18.612 ms/op
     p(99.9000) =     26.502 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 8.547 ±(99.9%) 0.282 ms/op
Iteration   1: 4.681 ±(99.9%) 0.070 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   4.506 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   8.118 ms/op
                 existUser·p0.99:   12.787 ms/op
                 existUser·p0.999:  14.811 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6830
  mean =      4.681 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 326 
    [ 2.500,  3.750) = 981 
    [ 3.750,  5.000) = 4578 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 177 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      8.118 ms/op
     p(99.0000) =     12.787 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 12.159 ±(99.9%) 0.441 ms/op
Iteration   1: 4.947 ±(99.9%) 0.069 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   4.776 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   6.824 ms/op
                 getUser·p0.99:   12.179 ms/op
                 getUser·p0.999:  19.104 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6465
  mean =      4.947 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 112 
    [ 2.500,  3.750) = 723 
    [ 3.750,  5.000) = 3009 
    [ 5.000,  6.250) = 1986 
    [ 6.250,  7.500) = 466 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =     12.179 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 25.477 ±(99.9%) 0.798 ms/op
Iteration   1: 17.669 ±(99.9%) 0.342 ms/op
                 listUser·p0.00:   5.718 ms/op
                 listUser·p0.50:   18.416 ms/op
                 listUser·p0.90:   22.417 ms/op
                 listUser·p0.95:   24.319 ms/op
                 listUser·p0.99:   31.772 ms/op
                 listUser·p0.999:  39.188 ms/op
                 listUser·p0.9999: 39.518 ms/op
                 listUser·p1.00:   39.518 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1838
  mean =     17.669 ±(99.9%) 0.342 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 400 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 484 
    [20.000, 22.500) = 381 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      5.718 ms/op
     p(50.0000) =     18.416 ms/op
     p(90.0000) =     22.417 ms/op
     p(95.0000) =     24.319 ms/op
     p(99.0000) =     31.772 ms/op
     p(99.9000) =     39.188 ms/op
     p(99.9900) =     39.518 ms/op
     p(99.9990) =     39.518 ms/op
     p(99.9999) =     39.518 ms/op
    p(100.0000) =     39.518 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.080          ops/ms
Client.existUser                       thrpt         6.072          ops/ms
Client.getUser                         thrpt         3.857          ops/ms
Client.listUser                        thrpt         1.286          ops/ms
Client.createUser                       avgt         8.752           ms/op
Client.existUser                        avgt         3.834           ms/op
Client.getUser                          avgt         4.920           ms/op
Client.listUser                         avgt        18.470           ms/op
Client.createUser                     sample  4403   7.259 ± 0.118   ms/op
Client.createUser:createUser·p0.00    sample         2.527           ms/op
Client.createUser:createUser·p0.50    sample         6.832           ms/op
Client.createUser:createUser·p0.90    sample         7.995           ms/op
Client.createUser:createUser·p0.95    sample         9.319           ms/op
Client.createUser:createUser·p0.99    sample        18.612           ms/op
Client.createUser:createUser·p0.999   sample        26.502           ms/op
Client.createUser:createUser·p0.9999  sample        26.870           ms/op
Client.createUser:createUser·p1.00    sample        26.870           ms/op
Client.existUser                      sample  6830   4.681 ± 0.070   ms/op
Client.existUser:existUser·p0.00      sample         0.791           ms/op
Client.existUser:existUser·p0.50      sample         4.506           ms/op
Client.existUser:existUser·p0.90      sample         5.226           ms/op
Client.existUser:existUser·p0.95      sample         8.118           ms/op
Client.existUser:existUser·p0.99      sample        12.787           ms/op
Client.existUser:existUser·p0.999     sample        14.811           ms/op
Client.existUser:existUser·p0.9999    sample        17.727           ms/op
Client.existUser:existUser·p1.00      sample        17.727           ms/op
Client.getUser                        sample  6465   4.947 ± 0.069   ms/op
Client.getUser:getUser·p0.00          sample         1.317           ms/op
Client.getUser:getUser·p0.50          sample         4.776           ms/op
Client.getUser:getUser·p0.90          sample         6.218           ms/op
Client.getUser:getUser·p0.95          sample         6.824           ms/op
Client.getUser:getUser·p0.99          sample        12.179           ms/op
Client.getUser:getUser·p0.999         sample        19.104           ms/op
Client.getUser:getUser·p0.9999        sample        19.137           ms/op
Client.getUser:getUser·p1.00          sample        19.137           ms/op
Client.listUser                       sample  1838  17.669 ± 0.342   ms/op
Client.listUser:listUser·p0.00        sample         5.718           ms/op
Client.listUser:listUser·p0.50        sample        18.416           ms/op
Client.listUser:listUser·p0.90        sample        22.417           ms/op
Client.listUser:listUser·p0.95        sample        24.319           ms/op
Client.listUser:listUser·p0.99        sample        31.772           ms/op
Client.listUser:listUser·p0.999       sample        39.188           ms/op
Client.listUser:listUser·p0.9999      sample        39.518           ms/op
Client.listUser:listUser·p1.00        sample        39.518           ms/op
