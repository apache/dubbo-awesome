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
# Warmup Iteration   1: 1.502 ops/ms
Iteration   1: 5.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.993 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.321 ops/ms
Iteration   1: 12.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.441 ops/ms


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
# Warmup Iteration   1: 4.721 ops/ms
Iteration   1: 12.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.137 ops/ms


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
# Warmup Iteration   1: 4.273 ops/ms
Iteration   1: 8.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.836 ops/ms


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.074 ms/op
Iteration   1: 1.949 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.949 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.050 ms/op
Iteration   1: 2.060 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.060 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.065 ms/op
Iteration   1: 2.130 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.130 ms/op


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
# Warmup Iteration   1: 5.623 ±(99.9%) 0.117 ms/op
Iteration   1: 3.472 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.472 ms/op


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.332 ms/op
Iteration   1: 2.096 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.464 ms/op
                 createUser·p0.50:   1.942 ms/op
                 createUser·p0.90:   2.851 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.115 ms/op
                 createUser·p0.999:  20.013 ms/op
                 createUser·p0.9999: 21.160 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15257
  mean =      2.096 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12492 
    [ 2.500,  5.000) = 2657 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.115 ms/op
     p(99.9000) =     20.013 ms/op
     p(99.9900) =     21.160 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 3.250 ±(99.9%) 0.077 ms/op
Iteration   1: 1.852 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.320 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   3.892 ms/op
                 existUser·p0.999:  19.497 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17279
  mean =      1.852 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16386 
    [ 2.500,  5.000) = 768 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.320 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.892 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 3.380 ±(99.9%) 0.077 ms/op
Iteration   1: 2.020 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   1.954 ms/op
                 getUser·p0.90:   2.699 ms/op
                 getUser·p0.95:   2.859 ms/op
                 getUser·p0.99:   3.348 ms/op
                 getUser·p0.999:  11.879 ms/op
                 getUser·p0.9999: 12.003 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15968
  mean =      2.020 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 696 
    [ 1.250,  2.500) = 12134 
    [ 2.500,  3.750) = 3058 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      3.348 ms/op
     p(99.9000) =     11.879 ms/op
     p(99.9900) =     12.003 ms/op
     p(99.9990) =     12.042 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.155 ms/op
Iteration   1: 3.148 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  16.065 ms/op
                 listUser·p0.9999: 17.592 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10224
  mean =      3.148 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 947 
    [ 2.500,  3.750) = 7868 
    [ 3.750,  5.000) = 1158 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     16.065 ms/op
     p(99.9900) =     17.592 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.993          ops/ms
ClientSimple.existUser                       thrpt         12.441          ops/ms
ClientSimple.getUser                         thrpt         12.137          ops/ms
ClientSimple.listUser                        thrpt          8.836          ops/ms
ClientSimple.createUser                       avgt          1.949           ms/op
ClientSimple.existUser                        avgt          2.060           ms/op
ClientSimple.getUser                          avgt          2.130           ms/op
ClientSimple.listUser                         avgt          3.472           ms/op
ClientSimple.createUser                     sample  15257   2.096 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.464           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.942           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.207           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.115           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.013           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.160           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.332           ms/op
ClientSimple.existUser                      sample  17279   1.852 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.320           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.747           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.892           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.497           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.120           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.120           ms/op
ClientSimple.getUser                        sample  15968   2.020 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.506           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.954           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.348           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.879           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.003           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.042           ms/op
ClientSimple.listUser                       sample  10224   3.148 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.962           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.916           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.652           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.065           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.592           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.596           ms/op

Benchmark result is saved to 1717416414680.json
