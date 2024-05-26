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
# Warmup Iteration   1: 2.054 ops/ms
Iteration   1: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.259 ops/ms


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
# Warmup Iteration   1: 5.727 ops/ms
Iteration   1: 15.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.949 ops/ms


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
# Warmup Iteration   1: 5.558 ops/ms
Iteration   1: 12.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.951 ops/ms


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
# Warmup Iteration   1: 4.608 ops/ms
Iteration   1: 8.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.621 ops/ms


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.053 ms/op
Iteration   1: 2.172 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.172 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.050 ms/op
Iteration   1: 1.967 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.967 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.052 ms/op
Iteration   1: 2.018 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.018 ms/op


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.106 ms/op
Iteration   1: 3.888 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.888 ms/op


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.101 ms/op
Iteration   1: 2.168 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.370 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.859 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   7.676 ms/op
                 createUser·p0.999:  14.598 ms/op
                 createUser·p0.9999: 14.771 ms/op
                 createUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14750
  mean =      2.168 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 752 
    [ 1.250,  2.500) = 10289 
    [ 2.500,  3.750) = 3306 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.859 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     14.771 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 3.040 ±(99.9%) 0.070 ms/op
Iteration   1: 2.031 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   1.939 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  18.792 ms/op
                 existUser·p0.9999: 19.661 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15758
  mean =      2.031 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 296 
    [ 1.250,  2.500) = 13937 
    [ 2.500,  3.750) = 1426 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.367 ms/op
     p(99.9000) =     18.792 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.079 ms/op
Iteration   1: 1.964 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.526 ms/op
                 getUser·p0.50:   1.720 ms/op
                 getUser·p0.90:   2.691 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   3.170 ms/op
                 getUser·p0.999:  12.871 ms/op
                 getUser·p0.9999: 13.496 ms/op
                 getUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16270
  mean =      1.964 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 13512 
    [ 2.500,  3.750) = 2613 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.720 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      3.170 ms/op
     p(99.9000) =     12.871 ms/op
     p(99.9900) =     13.496 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


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
# Warmup Iteration   1: 4.369 ±(99.9%) 0.131 ms/op
Iteration   1: 3.353 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   3.334 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.388 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  20.644 ms/op
                 listUser·p0.9999: 23.560 ms/op
                 listUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9525
  mean =      3.353 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1552 
    [ 2.500,  5.000) = 7660 
    [ 5.000,  7.500) = 243 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.388 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.259          ops/ms
ClientSimple.existUser                       thrpt         15.949          ops/ms
ClientSimple.getUser                         thrpt         12.951          ops/ms
ClientSimple.listUser                        thrpt          8.621          ops/ms
ClientSimple.createUser                       avgt          2.172           ms/op
ClientSimple.existUser                        avgt          1.967           ms/op
ClientSimple.getUser                          avgt          2.018           ms/op
ClientSimple.listUser                         avgt          3.888           ms/op
ClientSimple.createUser                     sample  14750   2.168 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.370           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.859           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.676           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.598           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.771           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.778           ms/op
ClientSimple.existUser                      sample  15758   2.031 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.513           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.939           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.367           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.792           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.661           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.661           ms/op
ClientSimple.getUser                        sample  16270   1.964 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.526           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.720           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.170           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.871           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.496           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.599           ms/op
ClientSimple.listUser                       sample   9525   3.353 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.836           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.334           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.121           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.388           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.472           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.644           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.560           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.560           ms/op

Benchmark result is saved to 1716746685255.json
