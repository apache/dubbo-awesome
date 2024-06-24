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
# Warmup Iteration   1: 1.596 ops/ms
Iteration   1: 6.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.702 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.313 ops/ms
Iteration   1: 12.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.887 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.302 ops/ms
Iteration   1: 13.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.587 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.499 ops/ms
Iteration   1: 8.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.413 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.079 ms/op
Iteration   1: 2.216 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.216 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.354 ±(99.9%) 0.059 ms/op
Iteration   1: 1.841 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.841 ms/op


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
# Warmup Iteration   1: 3.661 ±(99.9%) 0.061 ms/op
Iteration   1: 2.142 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.142 ms/op


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
# Warmup Iteration   1: 4.997 ±(99.9%) 0.107 ms/op
Iteration   1: 3.571 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.571 ms/op


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.116 ms/op
Iteration   1: 2.331 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   2.216 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   4.365 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 23.622 ms/op
                 createUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13710
  mean =      2.331 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9498 
    [ 2.500,  5.000) = 4095 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.365 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     23.622 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 2.966 ±(99.9%) 0.075 ms/op
Iteration   1: 2.016 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   1.905 ms/op
                 existUser·p0.90:   2.447 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   5.450 ms/op
                 existUser·p0.999:  14.825 ms/op
                 existUser·p0.9999: 16.337 ms/op
                 existUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16156
  mean =      2.016 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 401 
    [ 1.250,  2.500) = 14399 
    [ 2.500,  3.750) = 1054 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.447 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      5.450 ms/op
     p(99.9000) =     14.825 ms/op
     p(99.9900) =     16.337 ms/op
     p(99.9990) =     16.368 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.103 ms/op
Iteration   1: 2.154 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   2.077 ms/op
                 getUser·p0.90:   2.851 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.023 ms/op
                 getUser·p0.999:  16.140 ms/op
                 getUser·p0.9999: 16.702 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15090
  mean =      2.154 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 338 
    [ 1.250,  2.500) = 10936 
    [ 2.500,  3.750) = 3621 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.023 ms/op
     p(99.9000) =     16.140 ms/op
     p(99.9900) =     16.702 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.123 ms/op
Iteration   1: 3.878 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.610 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.282 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8251
  mean =      3.878 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 265 
    [ 2.500,  3.750) = 3523 
    [ 3.750,  5.000) = 4019 
    [ 5.000,  6.250) = 285 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.610 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.282 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.702          ops/ms
ClientSimple.existUser                       thrpt         12.887          ops/ms
ClientSimple.getUser                         thrpt         13.587          ops/ms
ClientSimple.listUser                        thrpt          8.413          ops/ms
ClientSimple.createUser                       avgt          2.216           ms/op
ClientSimple.existUser                        avgt          1.841           ms/op
ClientSimple.getUser                          avgt          2.142           ms/op
ClientSimple.listUser                         avgt          3.571           ms/op
ClientSimple.createUser                     sample  13710   2.331 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.825           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.216           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.974           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.195           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.365           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.431           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.622           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.658           ms/op
ClientSimple.existUser                      sample  16156   2.016 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.627           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.905           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.447           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.450           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.825           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.337           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.368           ms/op
ClientSimple.getUser                        sample  15090   2.154 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.622           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.077           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.207           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.023           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.140           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.702           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.777           ms/op
ClientSimple.listUser                       sample   8251   3.878 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.202           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.809           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.610           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.071           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.282           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.105           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.269           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.269           ms/op

Benchmark result is saved to 1719230806627.json
