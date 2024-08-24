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
# Warmup Iteration   1: 1.918 ops/ms
Iteration   1: 6.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.641 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.485 ops/ms
Iteration   1: 14.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.389 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.603 ops/ms
Iteration   1: 11.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.899 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.859 ops/ms
Iteration   1: 9.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.102 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ±(99.9%) 0.064 ms/op
Iteration   1: 1.941 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.941 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.262 ±(99.9%) 0.049 ms/op
Iteration   1: 1.898 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.898 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.499 ±(99.9%) 0.071 ms/op
Iteration   1: 1.830 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.830 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.535 ±(99.9%) 0.100 ms/op
Iteration   1: 3.162 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.162 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.341 ±(99.9%) 0.088 ms/op
Iteration   1: 2.233 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.146 ms/op
                 createUser·p0.90:   2.753 ms/op
                 createUser·p0.95:   2.970 ms/op
                 createUser·p0.99:   4.150 ms/op
                 createUser·p0.999:  15.516 ms/op
                 createUser·p0.9999: 16.748 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14439
  mean =      2.233 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 11317 
    [ 2.500,  3.750) = 2802 
    [ 3.750,  5.000) = 132 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      4.150 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     16.748 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.172 ±(99.9%) 0.074 ms/op
Iteration   1: 1.947 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.206 ms/op
                 existUser·p0.50:   1.882 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   3.837 ms/op
                 existUser·p0.999:  16.672 ms/op
                 existUser·p0.9999: 17.620 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16424
  mean =      1.947 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 807 
    [ 1.250,  2.500) = 14777 
    [ 2.500,  3.750) = 653 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.206 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.837 ms/op
     p(99.9000) =     16.672 ms/op
     p(99.9900) =     17.620 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.287 ±(99.9%) 0.081 ms/op
Iteration   1: 1.875 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   1.786 ms/op
                 getUser·p0.90:   2.265 ms/op
                 getUser·p0.95:   2.474 ms/op
                 getUser·p0.99:   3.391 ms/op
                 getUser·p0.999:  10.549 ms/op
                 getUser·p0.9999: 13.418 ms/op
                 getUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17160
  mean =      1.875 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 164 
    [ 1.250,  2.500) = 16204 
    [ 2.500,  3.750) = 670 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.391 ms/op
     p(99.9000) =     10.549 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.173 ±(99.9%) 0.103 ms/op
Iteration   1: 3.702 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.704 ms/op
                 listUser·p0.999:  27.630 ms/op
                 listUser·p0.9999: 29.098 ms/op
                 listUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8630
  mean =      3.702 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 632 
    [ 2.500,  5.000) = 7680 
    [ 5.000,  7.500) = 265 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.704 ms/op
     p(99.9000) =     27.630 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.641          ops/ms
ClientSimple.existUser                       thrpt         14.389          ops/ms
ClientSimple.getUser                         thrpt         11.899          ops/ms
ClientSimple.listUser                        thrpt          9.102          ops/ms
ClientSimple.createUser                       avgt          1.941           ms/op
ClientSimple.existUser                        avgt          1.898           ms/op
ClientSimple.getUser                          avgt          1.830           ms/op
ClientSimple.listUser                         avgt          3.162           ms/op
ClientSimple.createUser                     sample  14439   2.233 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.794           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.146           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.970           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.150           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.516           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.748           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.974           ms/op
ClientSimple.existUser                      sample  16424   1.947 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.206           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.882           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.837           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.672           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.620           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.662           ms/op
ClientSimple.getUser                        sample  17160   1.875 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.879           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.786           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.265           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.474           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.391           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.549           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.418           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.418           ms/op
ClientSimple.listUser                       sample   8630   3.702 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.818           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.641           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.704           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.630           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.098           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.098           ms/op

Benchmark result is saved to 1724458579170.json
