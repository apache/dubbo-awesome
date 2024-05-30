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
# Warmup Iteration   1: 2.107 ops/ms
Iteration   1: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.042 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.913 ops/ms
Iteration   1: 14.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.246 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.868 ops/ms
Iteration   1: 13.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.805 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.564 ops/ms
Iteration   1: 10.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  10.186 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.575 ±(99.9%) 0.061 ms/op
Iteration   1: 2.333 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.333 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.791 ±(99.9%) 0.046 ms/op
Iteration   1: 1.552 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.552 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.434 ±(99.9%) 0.053 ms/op
Iteration   1: 1.802 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.802 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.067 ms/op
Iteration   1: 3.377 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.377 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.096 ±(99.9%) 0.072 ms/op
Iteration   1: 1.786 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.594 ms/op
                 createUser·p0.50:   1.638 ms/op
                 createUser·p0.90:   2.204 ms/op
                 createUser·p0.95:   2.429 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  12.960 ms/op
                 createUser·p0.9999: 13.180 ms/op
                 createUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17917
  mean =      1.786 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 476 
    [ 1.250,  2.500) = 16668 
    [ 2.500,  3.750) = 597 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     13.180 ms/op
     p(99.9990) =     13.206 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ±(99.9%) 0.105 ms/op
Iteration   1: 1.822 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   2.815 ms/op
                 existUser·p0.999:  9.608 ms/op
                 existUser·p0.9999: 10.658 ms/op
                 existUser·p1.00:   10.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17579
  mean =      1.822 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 48 
    [ 1.000,  2.000) = 13634 
    [ 2.000,  3.000) = 3755 
    [ 3.000,  4.000) = 50 
    [ 4.000,  5.000) = 25 
    [ 5.000,  6.000) = 33 
    [ 6.000,  7.000) = 2 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      2.815 ms/op
     p(99.9000) =      9.608 ms/op
     p(99.9900) =     10.658 ms/op
     p(99.9990) =     10.682 ms/op
     p(99.9999) =     10.682 ms/op
    p(100.0000) =     10.682 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.856 ±(99.9%) 0.065 ms/op
Iteration   1: 1.910 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.543 ms/op
                 getUser·p0.50:   1.724 ms/op
                 getUser·p0.90:   2.875 ms/op
                 getUser·p0.95:   3.035 ms/op
                 getUser·p0.99:   3.396 ms/op
                 getUser·p0.999:  15.090 ms/op
                 getUser·p0.9999: 16.570 ms/op
                 getUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16720
  mean =      1.910 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1007 
    [ 1.250,  2.500) = 12772 
    [ 2.500,  3.750) = 2887 
    [ 3.750,  5.000) = 23 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      1.724 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.396 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     16.570 ms/op
     p(99.9990) =     16.581 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.657 ±(99.9%) 0.106 ms/op
Iteration   1: 3.088 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.543 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  16.606 ms/op
                 listUser·p0.9999: 17.005 ms/op
                 listUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10422
  mean =      3.088 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 2003 
    [ 2.500,  3.750) = 6859 
    [ 3.750,  5.000) = 1308 
    [ 5.000,  6.250) = 120 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     16.606 ms/op
     p(99.9900) =     17.005 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.042          ops/ms
ClientSimple.existUser                       thrpt         14.246          ops/ms
ClientSimple.getUser                         thrpt         13.805          ops/ms
ClientSimple.listUser                        thrpt         10.186          ops/ms
ClientSimple.createUser                       avgt          2.333           ms/op
ClientSimple.existUser                        avgt          1.552           ms/op
ClientSimple.getUser                          avgt          1.802           ms/op
ClientSimple.listUser                         avgt          3.377           ms/op
ClientSimple.createUser                     sample  17917   1.786 ± 0.021   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.594           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.638           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.429           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.654           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.960           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.180           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.206           ms/op
ClientSimple.existUser                      sample  17579   1.822 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.780           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.815           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.608           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.658           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.682           ms/op
ClientSimple.getUser                        sample  16720   1.910 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.543           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.724           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.035           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.396           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.090           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.570           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.581           ms/op
ClientSimple.listUser                       sample  10422   3.088 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.543           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.933           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.936           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.792           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.606           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.005           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.007           ms/op

Benchmark result is saved to 1717092358888.json
