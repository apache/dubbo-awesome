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
# Warmup Iteration   1: 1.420 ops/ms
Iteration   1: 6.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.819 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.796 ops/ms
Iteration   1: 13.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.578 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.526 ops/ms
Iteration   1: 11.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.777 ops/ms


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
# Warmup Iteration   1: 5.038 ops/ms
Iteration   1: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.350 ops/ms


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.063 ms/op
Iteration   1: 2.164 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.164 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.070 ms/op
Iteration   1: 2.162 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.162 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.057 ms/op
Iteration   1: 1.840 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.840 ms/op


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
# Warmup Iteration   1: 5.268 ±(99.9%) 0.121 ms/op
Iteration   1: 3.537 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.537 ms/op


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.231 ms/op
Iteration   1: 2.085 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.396 ms/op
                 createUser·p0.50:   1.815 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.903 ms/op
                 createUser·p0.99:   7.118 ms/op
                 createUser·p0.999:  24.412 ms/op
                 createUser·p0.9999: 24.591 ms/op
                 createUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15505
  mean =      2.085 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13646 
    [ 2.500,  5.000) = 1576 
    [ 5.000,  7.500) = 145 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.903 ms/op
     p(99.0000) =      7.118 ms/op
     p(99.9000) =     24.412 ms/op
     p(99.9900) =     24.591 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 2.990 ±(99.9%) 0.086 ms/op
Iteration   1: 1.974 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.328 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   3.224 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 19.422 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16215
  mean =      1.974 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 416 
    [ 1.250,  2.500) = 14421 
    [ 2.500,  3.750) = 1295 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.328 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.224 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     19.422 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.076 ms/op
Iteration   1: 2.414 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   2.306 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   6.359 ms/op
                 getUser·p0.999:  15.162 ms/op
                 getUser·p0.9999: 15.499 ms/op
                 getUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13289
  mean =      2.414 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 242 
    [ 1.250,  2.500) = 8222 
    [ 2.500,  3.750) = 4511 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.306 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      6.359 ms/op
     p(99.9000) =     15.162 ms/op
     p(99.9900) =     15.499 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 5.126 ±(99.9%) 0.167 ms/op
Iteration   1: 3.906 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.512 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8182
  mean =      3.906 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 231 
    [ 2.500,  3.750) = 3667 
    [ 3.750,  5.000) = 3633 
    [ 5.000,  6.250) = 362 
    [ 6.250,  7.500) = 158 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.512 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     15.958 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.819          ops/ms
ClientSimple.existUser                       thrpt         13.578          ops/ms
ClientSimple.getUser                         thrpt         11.777          ops/ms
ClientSimple.listUser                        thrpt          8.350          ops/ms
ClientSimple.createUser                       avgt          2.164           ms/op
ClientSimple.existUser                        avgt          2.162           ms/op
ClientSimple.getUser                          avgt          1.840           ms/op
ClientSimple.listUser                         avgt          3.537           ms/op
ClientSimple.createUser                     sample  15505   2.085 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.396           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.815           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.903           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.118           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.412           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.591           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.609           ms/op
ClientSimple.existUser                      sample  16215   1.974 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.328           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.909           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.224           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.367           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.422           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.890           ms/op
ClientSimple.getUser                        sample  13289   2.414 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.572           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.306           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.974           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.252           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.359           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.162           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.499           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.516           ms/op
ClientSimple.listUser                       sample   8182   3.906 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.227           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.785           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.512           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.913           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.124           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.958           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.958           ms/op

Benchmark result is saved to 1719317195624.json
