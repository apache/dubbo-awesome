# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.318 ops/ms
Iteration   1: 5.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.952 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.135 ops/ms
Iteration   1: 11.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.418 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ops/ms
Iteration   1: 9.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.879 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.141 ops/ms
Iteration   1: 8.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.505 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.705 ±(99.9%) 0.094 ms/op
Iteration   1: 2.276 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.276 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.315 ±(99.9%) 0.064 ms/op
Iteration   1: 2.006 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.006 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.750 ±(99.9%) 0.069 ms/op
Iteration   1: 2.262 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.262 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.454 ±(99.9%) 0.118 ms/op
Iteration   1: 3.454 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.454 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.454 ±(99.9%) 0.115 ms/op
Iteration   1: 2.668 ±(99.9%) 0.078 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   2.241 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   13.861 ms/op
                 createUser·p0.999:  42.333 ms/op
                 createUser·p0.9999: 44.944 ms/op
                 createUser·p1.00:   45.023 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12024
  mean =      2.668 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11490 
    [ 5.000, 10.000) = 344 
    [10.000, 15.000) = 107 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 10 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      2.241 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =     13.861 ms/op
     p(99.9000) =     42.333 ms/op
     p(99.9900) =     44.944 ms/op
     p(99.9990) =     45.023 ms/op
     p(99.9999) =     45.023 ms/op
    p(100.0000) =     45.023 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.223 ±(99.9%) 0.078 ms/op
Iteration   1: 1.948 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.411 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   4.347 ms/op
                 existUser·p0.999:  23.495 ms/op
                 existUser·p0.9999: 23.846 ms/op
                 existUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16446
  mean =      1.948 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15526 
    [ 2.500,  5.000) = 762 
    [ 5.000,  7.500) = 90 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      4.347 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     23.846 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.125 ±(99.9%) 0.078 ms/op
Iteration   1: 2.034 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.388 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  16.105 ms/op
                 getUser·p0.9999: 16.456 ms/op
                 getUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15834
  mean =      2.034 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 216 
    [ 1.250,  2.500) = 14205 
    [ 2.500,  3.750) = 1192 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     16.456 ms/op
     p(99.9990) =     16.466 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ±(99.9%) 0.131 ms/op
Iteration   1: 3.570 ±(99.9%) 0.074 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.113 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   17.727 ms/op
                 listUser·p0.999:  23.037 ms/op
                 listUser·p0.9999: 23.265 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8953
  mean =      3.570 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 598 
    [ 2.500,  5.000) = 7939 
    [ 5.000,  7.500) = 190 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =     17.727 ms/op
     p(99.9000) =     23.037 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.952          ops/ms
ClientSimple.existUser                       thrpt         11.418          ops/ms
ClientSimple.getUser                         thrpt          9.879          ops/ms
ClientSimple.listUser                        thrpt          8.505          ops/ms
ClientSimple.createUser                       avgt          2.276           ms/op
ClientSimple.existUser                        avgt          2.006           ms/op
ClientSimple.getUser                          avgt          2.262           ms/op
ClientSimple.listUser                         avgt          3.454           ms/op
ClientSimple.createUser                     sample  12024   2.668 ± 0.078   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.639           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.241           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.052           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.563           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.861           ms/op
ClientSimple.createUser:createUser·p0.999   sample         42.333           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         44.944           ms/op
ClientSimple.createUser:createUser·p1.00    sample         45.023           ms/op
ClientSimple.existUser                      sample  16446   1.948 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.411           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.829           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.347           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.495           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.846           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.888           ms/op
ClientSimple.getUser                        sample  15834   2.034 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.388           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.333           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.105           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.456           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.466           ms/op
ClientSimple.listUser                       sample   8953   3.570 ± 0.074   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.987           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.113           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample         17.727           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.037           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.265           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.265           ms/op

Benchmark result is saved to 1720461932960.json
