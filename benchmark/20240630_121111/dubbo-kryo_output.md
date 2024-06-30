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
# Warmup Iteration   1: 2.039 ops/ms
Iteration   1: 7.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.138 ops/ms


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
# Warmup Iteration   1: 5.983 ops/ms
Iteration   1: 11.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.831 ops/ms


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
# Warmup Iteration   1: 4.693 ops/ms
Iteration   1: 12.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.735 ops/ms


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
# Warmup Iteration   1: 5.737 ops/ms
Iteration   1: 9.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.234 ops/ms


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.072 ms/op
Iteration   1: 2.036 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.036 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.050 ms/op
Iteration   1: 1.719 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.719 ms/op


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
# Warmup Iteration   1: 3.484 ±(99.9%) 0.068 ms/op
Iteration   1: 2.042 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.562 ±(99.9%) 0.083 ms/op
Iteration   1: 3.485 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.485 ms/op


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
# Warmup Iteration   1: 3.417 ±(99.9%) 0.082 ms/op
Iteration   1: 2.274 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.095 ms/op
                 createUser·p0.90:   2.748 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   9.100 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 14.336 ms/op
                 createUser·p1.00:   14.336 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14060
  mean =      2.274 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 11434 
    [ 2.500,  3.750) = 2231 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      2.095 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      9.100 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.075 ms/op
Iteration   1: 1.647 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.435 ms/op
                 existUser·p0.50:   1.491 ms/op
                 existUser·p0.90:   2.105 ms/op
                 existUser·p0.95:   2.301 ms/op
                 existUser·p0.99:   2.920 ms/op
                 existUser·p0.999:  18.448 ms/op
                 existUser·p0.9999: 20.683 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19482
  mean =      1.647 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19054 
    [ 2.500,  5.000) = 362 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      1.491 ms/op
     p(90.0000) =      2.105 ms/op
     p(95.0000) =      2.301 ms/op
     p(99.0000) =      2.920 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     20.683 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 3.215 ±(99.9%) 0.075 ms/op
Iteration   1: 1.920 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   1.765 ms/op
                 getUser·p0.90:   2.339 ms/op
                 getUser·p0.95:   2.552 ms/op
                 getUser·p0.99:   3.560 ms/op
                 getUser·p0.999:  18.907 ms/op
                 getUser·p0.9999: 18.994 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16688
  mean =      1.920 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 15585 
    [ 2.500,  3.750) = 816 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.552 ms/op
     p(99.0000) =      3.560 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     18.994 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.137 ms/op
Iteration   1: 3.025 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   2.839 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.087 ms/op
                 listUser·p0.99:   4.694 ms/op
                 listUser·p0.999:  5.895 ms/op
                 listUser·p0.9999: 6.715 ms/op
                 listUser·p1.00:   6.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10583
  mean =      3.025 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 16 
    [1.500, 2.000) = 103 
    [2.000, 2.500) = 1646 
    [2.500, 3.000) = 4566 
    [3.000, 3.500) = 1718 
    [3.500, 4.000) = 1789 
    [4.000, 4.500) = 560 
    [4.500, 5.000) = 123 
    [5.000, 5.500) = 39 
    [5.500, 6.000) = 16 
    [6.000, 6.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.087 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      5.895 ms/op
     p(99.9900) =      6.715 ms/op
     p(99.9990) =      6.742 ms/op
     p(99.9999) =      6.742 ms/op
    p(100.0000) =      6.742 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.138          ops/ms
ClientSimple.existUser                       thrpt         11.831          ops/ms
ClientSimple.getUser                         thrpt         12.735          ops/ms
ClientSimple.listUser                        thrpt          9.234          ops/ms
ClientSimple.createUser                       avgt          2.036           ms/op
ClientSimple.existUser                        avgt          1.719           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.485           ms/op
ClientSimple.createUser                     sample  14060   2.274 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.057           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.095           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.100           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.254           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.336           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.336           ms/op
ClientSimple.existUser                      sample  19482   1.647 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.435           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.491           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.105           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.301           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.920           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.448           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.683           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.808           ms/op
ClientSimple.getUser                        sample  16688   1.920 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.654           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.765           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.552           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.560           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.907           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.994           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.038           ms/op
ClientSimple.listUser                       sample  10583   3.025 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.122           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.839           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.899           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.087           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.999       sample          5.895           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.715           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.742           ms/op

Benchmark result is saved to 1719749214666.json
