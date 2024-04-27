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
# Warmup Iteration   1: 1.852 ops/ms
Iteration   1: 5.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.939 ops/ms


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
# Warmup Iteration   1: 5.937 ops/ms
Iteration   1: 12.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.368 ops/ms


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
# Warmup Iteration   1: 5.821 ops/ms
Iteration   1: 13.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.020 ops/ms


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
# Warmup Iteration   1: 4.834 ops/ms
Iteration   1: 9.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.121 ops/ms


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.104 ms/op
Iteration   1: 2.186 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.186 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.056 ms/op
Iteration   1: 2.122 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.122 ms/op


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
# Warmup Iteration   1: 3.582 ±(99.9%) 0.067 ms/op
Iteration   1: 2.085 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.085 ms/op


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
# Warmup Iteration   1: 4.668 ±(99.9%) 0.110 ms/op
Iteration   1: 3.563 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.563 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.105 ms/op
Iteration   1: 2.417 ±(99.9%) 0.133 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   1.995 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   8.851 ms/op
                 createUser·p0.999:  94.233 ms/op
                 createUser·p0.9999: 111.065 ms/op
                 createUser·p1.00:   111.280 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13277
  mean =      2.417 ±(99.9%) 0.133 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 13186 
    [ 12.500,  25.000) = 47 
    [ 25.000,  37.500) = 5 
    [ 37.500,  50.000) = 6 
    [ 50.000,  62.500) = 2 
    [ 62.500,  75.000) = 7 
    [ 75.000,  87.500) = 5 
    [ 87.500, 100.000) = 12 
    [100.000, 112.500) = 7 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      8.851 ms/op
     p(99.9000) =     94.233 ms/op
     p(99.9900) =    111.065 ms/op
     p(99.9990) =    111.280 ms/op
     p(99.9999) =    111.280 ms/op
    p(100.0000) =    111.280 ms/op


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
# Warmup Iteration   1: 3.131 ±(99.9%) 0.074 ms/op
Iteration   1: 1.971 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.826 ms/op
                 existUser·p0.99:   3.537 ms/op
                 existUser·p0.999:  18.121 ms/op
                 existUser·p0.9999: 18.231 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16237
  mean =      1.971 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 446 
    [ 1.250,  2.500) = 14168 
    [ 2.500,  3.750) = 1507 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      3.537 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     18.231 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.077 ±(99.9%) 0.089 ms/op
Iteration   1: 2.131 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.030 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.783 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  12.878 ms/op
                 getUser·p0.9999: 12.927 ms/op
                 getUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15151
  mean =      2.131 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 13432 
    [ 2.500,  3.750) = 1390 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.783 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     12.927 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.127 ms/op
Iteration   1: 3.270 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.076 ms/op
                 listUser·p0.90:   3.851 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.253 ms/op
                 listUser·p0.999:  20.351 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9936
  mean =      3.270 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 119 
    [ 2.500,  5.000) = 9706 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.851 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.253 ms/op
     p(99.9000) =     20.351 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           5.939          ops/ms
ClientSimple.existUser                       thrpt          12.368          ops/ms
ClientSimple.getUser                         thrpt          13.020          ops/ms
ClientSimple.listUser                        thrpt           9.121          ops/ms
ClientSimple.createUser                       avgt           2.186           ms/op
ClientSimple.existUser                        avgt           2.122           ms/op
ClientSimple.getUser                          avgt           2.085           ms/op
ClientSimple.listUser                         avgt           3.563           ms/op
ClientSimple.createUser                     sample  13277    2.417 ± 0.133   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.558           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.995           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.215           ms/op
ClientSimple.createUser:createUser·p0.99    sample           8.851           ms/op
ClientSimple.createUser:createUser·p0.999   sample          94.233           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         111.065           ms/op
ClientSimple.createUser:createUser·p1.00    sample         111.280           ms/op
ClientSimple.existUser                      sample  16237    1.971 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.501           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.829           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.826           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.537           ms/op
ClientSimple.existUser:existUser·p0.999     sample          18.121           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          18.231           ms/op
ClientSimple.existUser:existUser·p1.00      sample          18.252           ms/op
ClientSimple.getUser                        sample  15151    2.131 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.807           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.030           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.783           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.342           ms/op
ClientSimple.getUser:getUser·p0.999         sample          12.878           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          12.927           ms/op
ClientSimple.getUser:getUser·p1.00          sample          12.927           ms/op
ClientSimple.listUser                       sample   9936    3.270 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.294           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.076           ms/op
ClientSimple.listUser:listUser·p0.90        sample           3.851           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.243           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.253           ms/op
ClientSimple.listUser:listUser·p0.999       sample          20.351           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          21.332           ms/op
ClientSimple.listUser:listUser·p1.00        sample          21.332           ms/op

Benchmark result is saved to 1714219542916.json
