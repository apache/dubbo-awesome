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
# Warmup Iteration   1: 1.829 ops/ms
Iteration   1: 6.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.904 ops/ms


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
# Warmup Iteration   1: 5.505 ops/ms
Iteration   1: 13.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.033 ops/ms


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
# Warmup Iteration   1: 6.353 ops/ms
Iteration   1: 13.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.788 ops/ms


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
# Warmup Iteration   1: 5.277 ops/ms
Iteration   1: 8.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.508 ops/ms


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.086 ms/op
Iteration   1: 2.171 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.171 ms/op


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
# Warmup Iteration   1: 3.037 ±(99.9%) 0.043 ms/op
Iteration   1: 1.940 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.940 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.060 ms/op
Iteration   1: 1.879 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.879 ms/op


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
# Warmup Iteration   1: 4.452 ±(99.9%) 0.084 ms/op
Iteration   1: 3.340 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.340 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.088 ms/op
Iteration   1: 2.194 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.537 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.592 ms/op
                 createUser·p0.95:   2.836 ms/op
                 createUser·p0.99:   4.373 ms/op
                 createUser·p0.999:  39.649 ms/op
                 createUser·p0.9999: 40.870 ms/op
                 createUser·p1.00:   40.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14570
  mean =      2.194 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14455 
    [ 5.000, 10.000) = 19 
    [10.000, 15.000) = 64 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.592 ms/op
     p(95.0000) =      2.836 ms/op
     p(99.0000) =      4.373 ms/op
     p(99.9000) =     39.649 ms/op
     p(99.9900) =     40.870 ms/op
     p(99.9990) =     40.960 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


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
# Warmup Iteration   1: 3.142 ±(99.9%) 0.081 ms/op
Iteration   1: 1.884 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.691 ms/op
                 existUser·p0.99:   3.960 ms/op
                 existUser·p0.999:  17.695 ms/op
                 existUser·p0.9999: 17.898 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17008
  mean =      1.884 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 644 
    [ 1.250,  2.500) = 14770 
    [ 2.500,  3.750) = 1368 
    [ 3.750,  5.000) = 185 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      3.960 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     17.898 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.083 ms/op
Iteration   1: 2.122 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.021 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  14.811 ms/op
                 getUser·p0.9999: 14.983 ms/op
                 getUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15278
  mean =      2.122 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 13415 
    [ 2.500,  3.750) = 1483 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     14.983 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.128 ms/op
Iteration   1: 3.256 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  10.568 ms/op
                 listUser·p0.9999: 11.076 ms/op
                 listUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9799
  mean =      3.256 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 39 
    [ 2.000,  3.000) = 4638 
    [ 3.000,  4.000) = 3579 
    [ 4.000,  5.000) = 1338 
    [ 5.000,  6.000) = 118 
    [ 6.000,  7.000) = 22 
    [ 7.000,  8.000) = 31 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 9 
    [10.000, 11.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     10.568 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     11.076 ms/op
     p(99.9999) =     11.076 ms/op
    p(100.0000) =     11.076 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.904          ops/ms
ClientSimple.existUser                       thrpt         13.033          ops/ms
ClientSimple.getUser                         thrpt         13.788          ops/ms
ClientSimple.listUser                        thrpt          8.508          ops/ms
ClientSimple.createUser                       avgt          2.171           ms/op
ClientSimple.existUser                        avgt          1.940           ms/op
ClientSimple.getUser                          avgt          1.879           ms/op
ClientSimple.listUser                         avgt          3.340           ms/op
ClientSimple.createUser                     sample  14570   2.194 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.537           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.592           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.836           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.373           ms/op
ClientSimple.createUser:createUser·p0.999   sample         39.649           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         40.870           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.960           ms/op
ClientSimple.existUser                      sample  17008   1.884 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.504           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.691           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.960           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.695           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.898           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.990           ms/op
ClientSimple.getUser                        sample  15278   2.122 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.826           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.021           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.940           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.811           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.983           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.991           ms/op
ClientSimple.listUser                       sample   9799   3.256 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.235           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.064           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.865           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.568           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.076           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.076           ms/op

Benchmark result is saved to 1714478753845.json
