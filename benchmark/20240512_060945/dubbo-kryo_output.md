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
# Warmup Iteration   1: 1.400 ops/ms
Iteration   1: 6.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.666 ops/ms


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
# Warmup Iteration   1: 6.726 ops/ms
Iteration   1: 12.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.578 ops/ms


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
# Warmup Iteration   1: 5.050 ops/ms
Iteration   1: 14.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.397 ops/ms


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
# Warmup Iteration   1: 5.223 ops/ms
Iteration   1: 8.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.882 ops/ms


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.071 ms/op
Iteration   1: 2.069 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.069 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.058 ms/op
Iteration   1: 1.887 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.887 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.058 ms/op
Iteration   1: 2.218 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.218 ms/op


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
# Warmup Iteration   1: 4.389 ±(99.9%) 0.102 ms/op
Iteration   1: 3.226 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.226 ms/op


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.082 ms/op
Iteration   1: 2.189 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.802 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 18.483 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14776
  mean =      2.189 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 11185 
    [ 2.500,  3.750) = 3227 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     18.483 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.078 ms/op
Iteration   1: 1.899 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   3.138 ms/op
                 existUser·p0.999:  11.452 ms/op
                 existUser·p0.9999: 11.816 ms/op
                 existUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16847
  mean =      1.899 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 235 
    [ 1.250,  2.500) = 15452 
    [ 2.500,  3.750) = 1091 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.138 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     11.816 ms/op
     p(99.9990) =     11.895 ms/op
     p(99.9999) =     11.895 ms/op
    p(100.0000) =     11.895 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.076 ms/op
Iteration   1: 1.839 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.407 ms/op
                 getUser·p0.50:   1.688 ms/op
                 getUser·p0.90:   2.294 ms/op
                 getUser·p0.95:   2.544 ms/op
                 getUser·p0.99:   3.536 ms/op
                 getUser·p0.999:  13.517 ms/op
                 getUser·p0.9999: 13.747 ms/op
                 getUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17382
  mean =      1.839 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 282 
    [ 1.250,  2.500) = 16138 
    [ 2.500,  3.750) = 812 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      3.536 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     13.747 ms/op
     p(99.9990) =     13.795 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.113 ms/op
Iteration   1: 3.130 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.165 ms/op
                 listUser·p0.99:   6.259 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10262
  mean =      3.130 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 1425 
    [ 2.500,  3.750) = 7061 
    [ 3.750,  5.000) = 1593 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.165 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.666          ops/ms
ClientSimple.existUser                       thrpt         12.578          ops/ms
ClientSimple.getUser                         thrpt         14.397          ops/ms
ClientSimple.listUser                        thrpt          8.882          ops/ms
ClientSimple.createUser                       avgt          2.069           ms/op
ClientSimple.existUser                        avgt          1.887           ms/op
ClientSimple.getUser                          avgt          2.218           ms/op
ClientSimple.listUser                         avgt          3.226           ms/op
ClientSimple.createUser                     sample  14776   2.189 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.651           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.145           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.383           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.483           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.514           ms/op
ClientSimple.existUser                      sample  16847   1.899 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.665           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.138           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.452           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.816           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.895           ms/op
ClientSimple.getUser                        sample  17382   1.839 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.407           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.688           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.294           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.544           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.536           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.517           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.747           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.795           ms/op
ClientSimple.listUser                       sample  10262   3.130 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.933           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.855           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.165           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.259           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.744           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.843           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.843           ms/op

Benchmark result is saved to 1715493911517.json
