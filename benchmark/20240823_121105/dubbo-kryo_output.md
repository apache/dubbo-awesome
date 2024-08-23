# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.757 ops/ms
Iteration   1: 7.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.417 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.141 ops/ms
Iteration   1: 11.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.614 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.989 ops/ms
Iteration   1: 11.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.227 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.628 ops/ms
Iteration   1: 8.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.186 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.067 ms/op
Iteration   1: 2.170 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.170 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.030 ±(99.9%) 0.046 ms/op
Iteration   1: 1.888 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.888 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.704 ±(99.9%) 0.059 ms/op
Iteration   1: 2.018 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.018 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.903 ±(99.9%) 0.103 ms/op
Iteration   1: 3.280 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.280 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.424 ±(99.9%) 0.082 ms/op
Iteration   1: 2.241 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   1.903 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   4.020 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  15.811 ms/op
                 createUser·p0.9999: 16.867 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14248
  mean =      2.241 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 10461 
    [ 2.500,  3.750) = 2449 
    [ 3.750,  5.000) = 1046 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.020 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     16.867 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.069 ±(99.9%) 0.066 ms/op
Iteration   1: 1.799 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   3.921 ms/op
                 existUser·p0.999:  13.533 ms/op
                 existUser·p0.9999: 14.746 ms/op
                 existUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17773
  mean =      1.799 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 338 
    [ 1.250,  2.500) = 16478 
    [ 2.500,  3.750) = 776 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.921 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     14.746 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.008 ±(99.9%) 0.086 ms/op
Iteration   1: 2.075 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.286 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  22.872 ms/op
                 getUser·p0.9999: 23.341 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15405
  mean =      2.075 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13688 
    [ 2.500,  5.000) = 1609 
    [ 5.000,  7.500) = 26 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.286 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     23.341 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.125 ms/op
Iteration   1: 3.357 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.199 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.378 ms/op
                 listUser·p0.999:  9.256 ms/op
                 listUser·p0.9999: 12.304 ms/op
                 listUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9527
  mean =      3.357 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 654 
    [ 2.500,  3.750) = 6391 
    [ 3.750,  5.000) = 2258 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.378 ms/op
     p(99.9000) =      9.256 ms/op
     p(99.9900) =     12.304 ms/op
     p(99.9990) =     12.304 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.417          ops/ms
ClientSimple.existUser                       thrpt         11.614          ops/ms
ClientSimple.getUser                         thrpt         11.227          ops/ms
ClientSimple.listUser                        thrpt          8.186          ops/ms
ClientSimple.createUser                       avgt          2.170           ms/op
ClientSimple.existUser                        avgt          1.888           ms/op
ClientSimple.getUser                          avgt          2.018           ms/op
ClientSimple.listUser                         avgt          3.280           ms/op
ClientSimple.createUser                     sample  14248   2.241 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.826           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.903           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.592           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.020           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.448           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.811           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.867           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.908           ms/op
ClientSimple.existUser                      sample  17773   1.799 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.690           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.628           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.921           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.533           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.746           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.860           ms/op
ClientSimple.getUser                        sample  15405   2.075 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.286           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.628           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.872           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.341           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.429           ms/op
ClientSimple.listUser                       sample   9527   3.357 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.016           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.199           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.378           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.256           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.304           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.304           ms/op

Benchmark result is saved to 1724414800263.json
