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
# Warmup Iteration   1: 1.941 ops/ms
Iteration   1: 7.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.306 ops/ms


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
# Warmup Iteration   1: 5.753 ops/ms
Iteration   1: 13.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.635 ops/ms


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
# Warmup Iteration   1: 6.035 ops/ms
Iteration   1: 13.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.680 ops/ms


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
# Warmup Iteration   1: 5.895 ops/ms
Iteration   1: 8.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.859 ops/ms


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
# Warmup Iteration   1: 3.658 ±(99.9%) 0.061 ms/op
Iteration   1: 2.174 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.174 ms/op


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
# Warmup Iteration   1: 3.292 ±(99.9%) 0.052 ms/op
Iteration   1: 1.875 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.875 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.065 ms/op
Iteration   1: 2.014 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.014 ms/op


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.079 ms/op
Iteration   1: 3.039 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.039 ms/op


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
# Warmup Iteration   1: 3.556 ±(99.9%) 0.102 ms/op
Iteration   1: 2.122 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.472 ms/op
                 createUser·p0.50:   1.837 ms/op
                 createUser·p0.90:   2.650 ms/op
                 createUser·p0.95:   2.925 ms/op
                 createUser·p0.99:   6.663 ms/op
                 createUser·p0.999:  36.697 ms/op
                 createUser·p0.9999: 38.172 ms/op
                 createUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15051
  mean =      2.122 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12767 
    [ 2.500,  5.000) = 2083 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      6.663 ms/op
     p(99.9000) =     36.697 ms/op
     p(99.9900) =     38.172 ms/op
     p(99.9990) =     38.404 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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
# Warmup Iteration   1: 2.800 ±(99.9%) 0.062 ms/op
Iteration   1: 1.947 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.367 ms/op
                 existUser·p0.50:   1.903 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.228 ms/op
                 existUser·p0.999:  13.156 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16418
  mean =      1.947 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 475 
    [ 1.250,  2.500) = 15030 
    [ 2.500,  3.750) = 794 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.367 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.228 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.090 ms/op
Iteration   1: 2.049 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   1.935 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   2.953 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  14.555 ms/op
                 getUser·p0.9999: 14.739 ms/op
                 getUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15631
  mean =      2.049 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 534 
    [ 1.250,  2.500) = 12355 
    [ 2.500,  3.750) = 2510 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =     14.555 ms/op
     p(99.9900) =     14.739 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.140 ms/op
Iteration   1: 3.276 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.358 ms/op
                 listUser·p0.999:  15.274 ms/op
                 listUser·p0.9999: 15.696 ms/op
                 listUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9772
  mean =      3.276 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 865 
    [ 2.500,  3.750) = 6901 
    [ 3.750,  5.000) = 1764 
    [ 5.000,  6.250) = 120 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.591 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.358 ms/op
     p(99.9000) =     15.274 ms/op
     p(99.9900) =     15.696 ms/op
     p(99.9990) =     15.696 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.306          ops/ms
ClientSimple.existUser                       thrpt         13.635          ops/ms
ClientSimple.getUser                         thrpt         13.680          ops/ms
ClientSimple.listUser                        thrpt          8.859          ops/ms
ClientSimple.createUser                       avgt          2.174           ms/op
ClientSimple.existUser                        avgt          1.875           ms/op
ClientSimple.getUser                          avgt          2.014           ms/op
ClientSimple.listUser                         avgt          3.039           ms/op
ClientSimple.createUser                     sample  15051   2.122 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.472           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.837           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.663           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.697           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.172           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.404           ms/op
ClientSimple.existUser                      sample  16418   1.947 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.367           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.903           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.228           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.156           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.812           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.812           ms/op
ClientSimple.getUser                        sample  15631   2.049 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.506           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.935           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.953           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.710           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.555           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.739           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.795           ms/op
ClientSimple.listUser                       sample   9772   3.276 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.591           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.990           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.014           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.358           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.274           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.696           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.696           ms/op

Benchmark result is saved to 1720094797603.json
