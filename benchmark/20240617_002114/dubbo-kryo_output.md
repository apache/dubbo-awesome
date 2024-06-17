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
# Warmup Iteration   1: 1.597 ops/ms
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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.709 ops/ms
Iteration   1: 9.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.750 ops/ms


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
# Warmup Iteration   1: 4.797 ops/ms
Iteration   1: 11.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.644 ops/ms


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
# Warmup Iteration   1: 3.729 ops/ms
Iteration   1: 8.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.080 ops/ms


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.066 ms/op
Iteration   1: 2.335 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.335 ms/op


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
# Warmup Iteration   1: 3.348 ±(99.9%) 0.049 ms/op
Iteration   1: 1.862 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.862 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.065 ms/op
Iteration   1: 2.119 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.119 ms/op


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.111 ms/op
Iteration   1: 3.799 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.799 ms/op


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.128 ms/op
Iteration   1: 2.166 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.406 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   8.969 ms/op
                 createUser·p0.999:  16.908 ms/op
                 createUser·p0.9999: 18.059 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14852
  mean =      2.166 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 13030 
    [ 2.500,  3.750) = 1551 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      8.969 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     18.059 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.181 ±(99.9%) 0.076 ms/op
Iteration   1: 2.030 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   1.901 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  10.405 ms/op
                 existUser·p0.9999: 13.655 ms/op
                 existUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15899
  mean =      2.030 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 249 
    [ 1.250,  2.500) = 14006 
    [ 2.500,  3.750) = 1407 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =     10.405 ms/op
     p(99.9900) =     13.655 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.134 ms/op
Iteration   1: 2.142 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   2.071 ms/op
                 getUser·p0.90:   2.830 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  11.845 ms/op
                 getUser·p0.9999: 12.075 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15062
  mean =      2.142 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 421 
    [ 1.250,  2.500) = 11478 
    [ 2.500,  3.750) = 2986 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 5 
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
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =     11.845 ms/op
     p(99.9900) =     12.075 ms/op
     p(99.9990) =     12.108 ms/op
     p(99.9999) =     12.108 ms/op
    p(100.0000) =     12.108 ms/op


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
# Warmup Iteration   1: 4.448 ±(99.9%) 0.137 ms/op
Iteration   1: 3.638 ±(99.9%) 0.063 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  29.524 ms/op
                 listUser·p0.9999: 29.786 ms/op
                 listUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8794
  mean =      3.638 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 525 
    [ 2.500,  5.000) = 7919 
    [ 5.000,  7.500) = 287 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     29.524 ms/op
     p(99.9900) =     29.786 ms/op
     p(99.9990) =     29.786 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.993          ops/ms
ClientSimple.existUser                       thrpt          9.750          ops/ms
ClientSimple.getUser                         thrpt         11.644          ops/ms
ClientSimple.listUser                        thrpt          8.080          ops/ms
ClientSimple.createUser                       avgt          2.335           ms/op
ClientSimple.existUser                        avgt          1.862           ms/op
ClientSimple.getUser                          avgt          2.119           ms/op
ClientSimple.listUser                         avgt          3.799           ms/op
ClientSimple.createUser                     sample  14852   2.166 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.406           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.969           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.908           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.059           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.186           ms/op
ClientSimple.existUser                      sample  15899   2.030 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.943           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.901           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.038           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.405           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.655           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.713           ms/op
ClientSimple.getUser                        sample  15062   2.142 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.749           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.071           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.129           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.916           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.845           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.075           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.108           ms/op
ClientSimple.listUser                       sample   8794   3.638 ± 0.063   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.311           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.502           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.907           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.234           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.524           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.786           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.786           ms/op

Benchmark result is saved to 1718583411599.json
