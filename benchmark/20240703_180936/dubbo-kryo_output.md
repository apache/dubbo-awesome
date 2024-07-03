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
# Warmup Iteration   1: 0.781 ops/ms
Iteration   1: 6.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.237 ops/ms


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
# Warmup Iteration   1: 6.065 ops/ms
Iteration   1: 12.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.281 ops/ms


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
# Warmup Iteration   1: 5.615 ops/ms
Iteration   1: 12.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.664 ops/ms


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
Iteration   1: 8.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.170 ops/ms


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.090 ms/op
Iteration   1: 2.142 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.142 ms/op


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
# Warmup Iteration   1: 3.079 ±(99.9%) 0.056 ms/op
Iteration   1: 2.092 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.092 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.060 ms/op
Iteration   1: 1.944 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.944 ms/op


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.080 ms/op
Iteration   1: 3.211 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.211 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.078 ms/op
Iteration   1: 1.894 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   1.726 ms/op
                 createUser·p0.90:   2.054 ms/op
                 createUser·p0.95:   2.286 ms/op
                 createUser·p0.99:   4.516 ms/op
                 createUser·p0.999:  34.873 ms/op
                 createUser·p0.9999: 37.356 ms/op
                 createUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16884
  mean =      1.894 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16352 
    [ 2.500,  5.000) = 385 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.054 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      4.516 ms/op
     p(99.9000) =     34.873 ms/op
     p(99.9900) =     37.356 ms/op
     p(99.9990) =     37.356 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 2.907 ±(99.9%) 0.077 ms/op
Iteration   1: 1.942 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.858 ms/op
                 existUser·p0.999:  14.836 ms/op
                 existUser·p0.9999: 16.507 ms/op
                 existUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16470
  mean =      1.942 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 15281 
    [ 2.500,  3.750) = 901 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =     14.836 ms/op
     p(99.9900) =     16.507 ms/op
     p(99.9990) =     16.613 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


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
# Warmup Iteration   1: 3.264 ±(99.9%) 0.077 ms/op
Iteration   1: 1.786 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   1.708 ms/op
                 getUser·p0.90:   1.997 ms/op
                 getUser·p0.95:   2.146 ms/op
                 getUser·p0.99:   2.790 ms/op
                 getUser·p0.999:  26.673 ms/op
                 getUser·p0.9999: 26.968 ms/op
                 getUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17893
  mean =      1.786 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17620 
    [ 2.500,  5.000) = 209 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      1.997 ms/op
     p(95.0000) =      2.146 ms/op
     p(99.0000) =      2.790 ms/op
     p(99.9000) =     26.673 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.137 ms/op
Iteration   1: 3.196 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   4.993 ms/op
                 listUser·p0.999:  6.054 ms/op
                 listUser·p0.9999: 6.578 ms/op
                 listUser·p1.00:   6.578 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10044
  mean =      3.196 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 7 
    [1.500, 2.000) = 40 
    [2.000, 2.500) = 639 
    [2.500, 3.000) = 4090 
    [3.000, 3.500) = 2286 
    [3.500, 4.000) = 1880 
    [4.000, 4.500) = 853 
    [4.500, 5.000) = 154 
    [5.000, 5.500) = 66 
    [5.500, 6.000) = 15 
    [6.000, 6.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      4.993 ms/op
     p(99.9000) =      6.054 ms/op
     p(99.9900) =      6.578 ms/op
     p(99.9990) =      6.578 ms/op
     p(99.9999) =      6.578 ms/op
    p(100.0000) =      6.578 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.237          ops/ms
ClientSimple.existUser                       thrpt         12.281          ops/ms
ClientSimple.getUser                         thrpt         12.664          ops/ms
ClientSimple.listUser                        thrpt          8.170          ops/ms
ClientSimple.createUser                       avgt          2.142           ms/op
ClientSimple.existUser                        avgt          2.092           ms/op
ClientSimple.getUser                          avgt          1.944           ms/op
ClientSimple.listUser                         avgt          3.211           ms/op
ClientSimple.createUser                     sample  16884   1.894 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.521           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.726           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.054           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.286           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.516           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.873           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.356           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.356           ms/op
ClientSimple.existUser                      sample  16470   1.942 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.866           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.806           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.858           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.836           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.507           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.613           ms/op
ClientSimple.getUser                        sample  17893   1.786 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.655           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.708           ms/op
ClientSimple.getUser:getUser·p0.90          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.146           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.790           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.673           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.968           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.968           ms/op
ClientSimple.listUser                       sample  10044   3.196 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.116           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.047           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.035           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.993           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.054           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.578           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.578           ms/op

Benchmark result is saved to 1720029913882.json
