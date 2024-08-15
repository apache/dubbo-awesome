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
# Warmup Iteration   1: 1.595 ops/ms
Iteration   1: 6.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.734 ops/ms


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
# Warmup Iteration   1: 6.338 ops/ms
Iteration   1: 11.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.667 ops/ms


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
# Warmup Iteration   1: 6.255 ops/ms
Iteration   1: 13.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.856 ops/ms


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
# Warmup Iteration   1: 4.434 ops/ms
Iteration   1: 8.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.177 ops/ms


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.071 ms/op
Iteration   1: 2.208 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.208 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.063 ms/op
Iteration   1: 1.850 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.850 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.081 ms/op
Iteration   1: 2.460 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.460 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.089 ms/op
Iteration   1: 3.839 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.839 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.077 ms/op
Iteration   1: 2.138 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.021 ms/op
                 createUser·p0.90:   2.691 ms/op
                 createUser·p0.95:   2.945 ms/op
                 createUser·p0.99:   4.482 ms/op
                 createUser·p0.999:  14.354 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14946
  mean =      2.138 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 11834 
    [ 2.500,  3.750) = 2734 
    [ 3.750,  5.000) = 175 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      4.482 ms/op
     p(99.9000) =     14.354 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 2.949 ±(99.9%) 0.066 ms/op
Iteration   1: 2.105 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.420 ms/op
                 existUser·p0.50:   2.001 ms/op
                 existUser·p0.90:   2.736 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  18.088 ms/op
                 existUser·p0.9999: 18.726 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15189
  mean =      2.105 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 836 
    [ 1.250,  2.500) = 10922 
    [ 2.500,  3.750) = 3237 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     18.726 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.082 ms/op
Iteration   1: 2.223 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.691 ms/op
                 getUser·p0.95:   2.871 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  13.631 ms/op
                 getUser·p0.9999: 16.926 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14386
  mean =      2.223 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 11529 
    [ 2.500,  3.750) = 2624 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     16.926 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.785 ±(99.9%) 0.145 ms/op
Iteration   1: 3.837 ±(99.9%) 0.071 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.077 ms/op
                 listUser·p0.999:  33.838 ms/op
                 listUser·p0.9999: 34.603 ms/op
                 listUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8338
  mean =      3.837 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 343 
    [ 2.500,  5.000) = 7663 
    [ 5.000,  7.500) = 264 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.077 ms/op
     p(99.9000) =     33.838 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.734          ops/ms
ClientSimple.existUser                       thrpt         11.667          ops/ms
ClientSimple.getUser                         thrpt         13.856          ops/ms
ClientSimple.listUser                        thrpt          8.177          ops/ms
ClientSimple.createUser                       avgt          2.208           ms/op
ClientSimple.existUser                        avgt          1.850           ms/op
ClientSimple.getUser                          avgt          2.460           ms/op
ClientSimple.listUser                         avgt          3.839           ms/op
ClientSimple.createUser                     sample  14946   2.138 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.561           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.021           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.482           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.354           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.169           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.169           ms/op
ClientSimple.existUser                      sample  15189   2.105 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.420           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.001           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.736           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.006           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.055           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.088           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.726           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.743           ms/op
ClientSimple.getUser                        sample  14386   2.223 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.771           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.932           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.631           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.926           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.170           ms/op
ClientSimple.listUser                       sample   8338   3.837 ± 0.071   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.932           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.715           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.077           ms/op
ClientSimple.listUser:listUser·p0.999       sample         33.838           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         34.603           ms/op
ClientSimple.listUser:listUser·p1.00        sample         34.603           ms/op

Benchmark result is saved to 1723745169696.json
