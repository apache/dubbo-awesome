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
# Warmup Iteration   1: 1.855 ops/ms
Iteration   1: 6.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.460 ops/ms


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
# Warmup Iteration   1: 6.730 ops/ms
Iteration   1: 13.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.053 ops/ms


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
# Warmup Iteration   1: 5.409 ops/ms
Iteration   1: 11.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.500 ops/ms


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
# Warmup Iteration   1: 5.784 ops/ms
Iteration   1: 8.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.996 ops/ms


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.067 ms/op
Iteration   1: 2.215 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.215 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.047 ms/op
Iteration   1: 1.765 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.765 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.049 ms/op
Iteration   1: 1.769 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.769 ms/op


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
# Warmup Iteration   1: 4.782 ±(99.9%) 0.087 ms/op
Iteration   1: 3.717 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.717 ms/op


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.100 ms/op
Iteration   1: 2.038 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.518 ms/op
                 createUser·p0.50:   1.901 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.892 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  15.696 ms/op
                 createUser·p0.9999: 17.115 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15664
  mean =      2.038 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 313 
    [ 1.250,  2.500) = 13902 
    [ 2.500,  3.750) = 971 
    [ 3.750,  5.000) = 259 
    [ 5.000,  6.250) = 110 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     17.115 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.210 ±(99.9%) 0.075 ms/op
Iteration   1: 1.960 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   6.299 ms/op
                 existUser·p0.999:  18.874 ms/op
                 existUser·p0.9999: 25.562 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16306
  mean =      1.960 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14919 
    [ 2.500,  5.000) = 1215 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      6.299 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     25.562 ms/op
     p(99.9990) =     26.575 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 3.353 ±(99.9%) 0.138 ms/op
Iteration   1: 2.040 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.230 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.830 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   3.355 ms/op
                 getUser·p0.999:  14.942 ms/op
                 getUser·p0.9999: 16.106 ms/op
                 getUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15694
  mean =      2.040 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 401 
    [ 1.250,  2.500) = 12435 
    [ 2.500,  3.750) = 2775 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.230 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.355 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     16.106 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.128 ms/op
Iteration   1: 3.400 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.414 ms/op
                 listUser·p0.999:  14.798 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9412
  mean =      3.400 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 943 
    [ 2.500,  3.750) = 5864 
    [ 3.750,  5.000) = 2458 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.414 ms/op
     p(99.9000) =     14.798 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.460          ops/ms
ClientSimple.existUser                       thrpt         13.053          ops/ms
ClientSimple.getUser                         thrpt         11.500          ops/ms
ClientSimple.listUser                        thrpt          8.996          ops/ms
ClientSimple.createUser                       avgt          2.215           ms/op
ClientSimple.existUser                        avgt          1.765           ms/op
ClientSimple.getUser                          avgt          1.769           ms/op
ClientSimple.listUser                         avgt          3.717           ms/op
ClientSimple.createUser                     sample  15664   2.038 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.518           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.901           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.892           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.726           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.696           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.115           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.170           ms/op
ClientSimple.existUser                      sample  16306   1.960 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.700           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.299           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.874           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.562           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.575           ms/op
ClientSimple.getUser                        sample  15694   2.040 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.230           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.355           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.942           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.106           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.237           ms/op
ClientSimple.listUser                       sample   9412   3.400 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.053           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.129           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.414           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.798           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.039           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.039           ms/op

Benchmark result is saved to 1724565955963.json
