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
# Warmup Iteration   1: 1.759 ops/ms
Iteration   1: 7.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.712 ops/ms


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
# Warmup Iteration   1: 5.903 ops/ms
Iteration   1: 12.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.998 ops/ms


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
# Warmup Iteration   1: 5.041 ops/ms
Iteration   1: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.047 ops/ms


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
# Warmup Iteration   1: 4.637 ops/ms
Iteration   1: 8.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.708 ops/ms


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.075 ms/op
Iteration   1: 2.114 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.114 ms/op


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
# Warmup Iteration   1: 3.109 ±(99.9%) 0.047 ms/op
Iteration   1: 2.028 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.028 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.054 ms/op
Iteration   1: 1.910 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.910 ms/op


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
# Warmup Iteration   1: 5.090 ±(99.9%) 0.124 ms/op
Iteration   1: 3.304 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.304 ms/op


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
# Warmup Iteration   1: 3.486 ±(99.9%) 0.077 ms/op
Iteration   1: 2.145 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.566 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.470 ms/op
                 createUser·p0.95:   2.821 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  15.632 ms/op
                 createUser·p0.9999: 15.920 ms/op
                 createUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14904
  mean =      2.145 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 449 
    [ 1.250,  2.500) = 13041 
    [ 2.500,  3.750) = 1003 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.821 ms/op
     p(99.0000) =     11.108 ms/op
     p(99.9000) =     15.632 ms/op
     p(99.9900) =     15.920 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 3.176 ±(99.9%) 0.084 ms/op
Iteration   1: 1.852 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  16.755 ms/op
                 existUser·p0.9999: 17.179 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17341
  mean =      1.852 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 846 
    [ 1.250,  2.500) = 15747 
    [ 2.500,  3.750) = 609 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =     16.755 ms/op
     p(99.9900) =     17.179 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 3.139 ±(99.9%) 0.072 ms/op
Iteration   1: 2.022 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.526 ms/op
                 getUser·p0.50:   1.864 ms/op
                 getUser·p0.90:   2.839 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.748 ms/op
                 getUser·p0.9999: 11.560 ms/op
                 getUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15812
  mean =      2.022 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 468 
    [ 1.250,  2.500) = 12652 
    [ 2.500,  3.750) = 2509 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     11.560 ms/op
     p(99.9990) =     13.369 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.158 ms/op
Iteration   1: 3.117 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   4.727 ms/op
                 listUser·p0.999:  7.633 ms/op
                 listUser·p0.9999: 8.864 ms/op
                 listUser·p1.00:   8.880 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10266
  mean =      3.117 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 17 
    [1.500, 2.000) = 150 
    [2.000, 2.500) = 1118 
    [2.500, 3.000) = 4178 
    [3.000, 3.500) = 1893 
    [3.500, 4.000) = 1943 
    [4.000, 4.500) = 769 
    [4.500, 5.000) = 123 
    [5.000, 5.500) = 15 
    [5.500, 6.000) = 14 
    [6.000, 6.500) = 8 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 5 
    [7.500, 8.000) = 25 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      7.633 ms/op
     p(99.9900) =      8.864 ms/op
     p(99.9990) =      8.880 ms/op
     p(99.9999) =      8.880 ms/op
    p(100.0000) =      8.880 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.712          ops/ms
ClientSimple.existUser                       thrpt         12.998          ops/ms
ClientSimple.getUser                         thrpt         13.047          ops/ms
ClientSimple.listUser                        thrpt          8.708          ops/ms
ClientSimple.createUser                       avgt          2.114           ms/op
ClientSimple.existUser                        avgt          2.028           ms/op
ClientSimple.getUser                          avgt          1.910           ms/op
ClientSimple.listUser                         avgt          3.304           ms/op
ClientSimple.createUser                     sample  14904   2.145 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.566           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.470           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.821           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.108           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.632           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.920           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.056           ms/op
ClientSimple.existUser                      sample  17341   1.852 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.615           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.482           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.755           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.179           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.203           ms/op
ClientSimple.getUser                        sample  15812   2.022 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.526           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.864           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.097           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.522           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.748           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.560           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.369           ms/op
ClientSimple.listUser                       sample  10266   3.117 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.090           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.949           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.977           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.633           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.864           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.880           ms/op

Benchmark result is saved to 1715105130830.json
