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
# Warmup Iteration   1: 1.089 ops/ms
Iteration   1: 2.631 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.631 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 2.774 ops/ms
Iteration   1: 6.936 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.936 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.383 ops/ms
Iteration   1: 5.305 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.305 ops/ms


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
# Warmup Iteration   1: 0.869 ops/ms
Iteration   1: 1.436 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.436 ops/ms


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
# Warmup Iteration   1: 16.765 ±(99.9%) 0.254 ms/op
Iteration   1: 7.256 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.256 ms/op


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
# Warmup Iteration   1: 6.640 ±(99.9%) 0.083 ms/op
Iteration   1: 3.784 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.784 ms/op


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
# Warmup Iteration   1: 8.006 ±(99.9%) 0.152 ms/op
Iteration   1: 4.423 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.423 ms/op


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
# Warmup Iteration   1: 27.426 ±(99.9%) 0.382 ms/op
Iteration   1: 16.274 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.274 ms/op


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
# Warmup Iteration   1: 10.903 ±(99.9%) 0.320 ms/op
Iteration   1: 5.588 ±(99.9%) 0.111 ms/op
                 createUser·p0.00:   2.286 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   5.947 ms/op
                 createUser·p0.95:   9.952 ms/op
                 createUser·p0.99:   18.988 ms/op
                 createUser·p0.999:  30.482 ms/op
                 createUser·p0.9999: 31.818 ms/op
                 createUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5750
  mean =      5.588 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 2728 
    [ 5.000,  7.500) = 2565 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.286 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      9.952 ms/op
     p(99.0000) =     18.988 ms/op
     p(99.9000) =     30.482 ms/op
     p(99.9900) =     31.818 ms/op
     p(99.9990) =     31.818 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


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
# Warmup Iteration   1: 5.148 ±(99.9%) 0.168 ms/op
Iteration   1: 3.579 ±(99.9%) 0.042 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  12.879 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8936
  mean =      3.579 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 240 
    [ 2.500,  3.750) = 6450 
    [ 3.750,  5.000) = 1929 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     12.879 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     12.960 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


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
# Warmup Iteration   1: 7.427 ±(99.9%) 0.281 ms/op
Iteration   1: 4.556 ±(99.9%) 0.075 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   6.334 ms/op
                 getUser·p0.99:   10.716 ms/op
                 getUser·p0.999:  26.477 ms/op
                 getUser·p0.9999: 27.066 ms/op
                 getUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7027
  mean =      4.556 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 5558 
    [ 5.000,  7.500) = 1228 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.334 ms/op
     p(99.0000) =     10.716 ms/op
     p(99.9000) =     26.477 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 26.359 ±(99.9%) 0.728 ms/op
Iteration   1: 15.892 ±(99.9%) 0.191 ms/op
                 listUser·p0.00:   4.825 ms/op
                 listUser·p0.50:   16.400 ms/op
                 listUser·p0.90:   17.826 ms/op
                 listUser·p0.95:   18.614 ms/op
                 listUser·p0.99:   26.608 ms/op
                 listUser·p0.999:  27.064 ms/op
                 listUser·p0.9999: 28.115 ms/op
                 listUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2038
  mean =     15.892 ±(99.9%) 0.191 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 485 
    [15.000, 17.500) = 1127 
    [17.500, 20.000) = 247 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      4.825 ms/op
     p(50.0000) =     16.400 ms/op
     p(90.0000) =     17.826 ms/op
     p(95.0000) =     18.614 ms/op
     p(99.0000) =     26.608 ms/op
     p(99.9000) =     27.064 ms/op
     p(99.9900) =     28.115 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.631          ops/ms
Client.existUser                       thrpt         6.936          ops/ms
Client.getUser                         thrpt         5.305          ops/ms
Client.listUser                        thrpt         1.436          ops/ms
Client.createUser                       avgt         7.256           ms/op
Client.existUser                        avgt         3.784           ms/op
Client.getUser                          avgt         4.423           ms/op
Client.listUser                         avgt        16.274           ms/op
Client.createUser                     sample  5750   5.588 ± 0.111   ms/op
Client.createUser:createUser·p0.00    sample         2.286           ms/op
Client.createUser:createUser·p0.50    sample         5.022           ms/op
Client.createUser:createUser·p0.90    sample         5.947           ms/op
Client.createUser:createUser·p0.95    sample         9.952           ms/op
Client.createUser:createUser·p0.99    sample        18.988           ms/op
Client.createUser:createUser·p0.999   sample        30.482           ms/op
Client.createUser:createUser·p0.9999  sample        31.818           ms/op
Client.createUser:createUser·p1.00    sample        31.818           ms/op
Client.existUser                      sample  8936   3.579 ± 0.042   ms/op
Client.existUser:existUser·p0.00      sample         0.708           ms/op
Client.existUser:existUser·p0.50      sample         3.518           ms/op
Client.existUser:existUser·p0.90      sample         4.121           ms/op
Client.existUser:existUser·p0.95      sample         4.514           ms/op
Client.existUser:existUser·p0.99      sample        10.142           ms/op
Client.existUser:existUser·p0.999     sample        12.879           ms/op
Client.existUser:existUser·p0.9999    sample        12.960           ms/op
Client.existUser:existUser·p1.00      sample        12.960           ms/op
Client.getUser                        sample  7027   4.556 ± 0.075   ms/op
Client.getUser:getUser·p0.00          sample         1.362           ms/op
Client.getUser:getUser·p0.50          sample         4.260           ms/op
Client.getUser:getUser·p0.90          sample         5.464           ms/op
Client.getUser:getUser·p0.95          sample         6.334           ms/op
Client.getUser:getUser·p0.99          sample        10.716           ms/op
Client.getUser:getUser·p0.999         sample        26.477           ms/op
Client.getUser:getUser·p0.9999        sample        27.066           ms/op
Client.getUser:getUser·p1.00          sample        27.066           ms/op
Client.listUser                       sample  2038  15.892 ± 0.191   ms/op
Client.listUser:listUser·p0.00        sample         4.825           ms/op
Client.listUser:listUser·p0.50        sample        16.400           ms/op
Client.listUser:listUser·p0.90        sample        17.826           ms/op
Client.listUser:listUser·p0.95        sample        18.614           ms/op
Client.listUser:listUser·p0.99        sample        26.608           ms/op
Client.listUser:listUser·p0.999       sample        27.064           ms/op
Client.listUser:listUser·p0.9999      sample        28.115           ms/op
Client.listUser:listUser·p1.00        sample        28.115           ms/op
