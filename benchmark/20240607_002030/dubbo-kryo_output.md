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
# Warmup Iteration   1: 2.011 ops/ms
Iteration   1: 6.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.982 ops/ms


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
# Warmup Iteration   1: 6.858 ops/ms
Iteration   1: 14.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.439 ops/ms


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
# Warmup Iteration   1: 7.350 ops/ms
Iteration   1: 14.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.834 ops/ms


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
# Warmup Iteration   1: 4.086 ops/ms
Iteration   1: 8.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.217 ops/ms


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.103 ms/op
Iteration   1: 2.011 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.011 ms/op


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
# Warmup Iteration   1: 2.777 ±(99.9%) 0.051 ms/op
Iteration   1: 1.747 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.747 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.074 ms/op
Iteration   1: 2.010 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.010 ms/op


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
# Warmup Iteration   1: 4.982 ±(99.9%) 0.102 ms/op
Iteration   1: 3.374 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.374 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.102 ms/op
Iteration   1: 2.212 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   1.997 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   9.545 ms/op
                 createUser·p0.999:  34.669 ms/op
                 createUser·p0.9999: 37.195 ms/op
                 createUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14443
  mean =      2.212 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12880 
    [ 2.500,  5.000) = 1300 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      9.545 ms/op
     p(99.9000) =     34.669 ms/op
     p(99.9900) =     37.195 ms/op
     p(99.9990) =     37.224 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.086 ms/op
Iteration   1: 1.597 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   1.462 ms/op
                 existUser·p0.90:   1.982 ms/op
                 existUser·p0.95:   2.130 ms/op
                 existUser·p0.99:   2.743 ms/op
                 existUser·p0.999:  12.681 ms/op
                 existUser·p0.9999: 13.058 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 20070
  mean =      1.597 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1939 
    [ 1.250,  2.500) = 17797 
    [ 2.500,  3.750) = 247 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      1.462 ms/op
     p(90.0000) =      1.982 ms/op
     p(95.0000) =      2.130 ms/op
     p(99.0000) =      2.743 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.074 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


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
# Warmup Iteration   1: 3.027 ±(99.9%) 0.064 ms/op
Iteration   1: 2.212 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.167 ms/op
                 getUser·p0.90:   2.683 ms/op
                 getUser·p0.95:   2.961 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  12.780 ms/op
                 getUser·p0.9999: 14.289 ms/op
                 getUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14458
  mean =      2.212 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 11951 
    [ 2.500,  3.750) = 2311 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 1 
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
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     14.289 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.146 ms/op
Iteration   1: 3.680 ±(99.9%) 0.074 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.912 ms/op
                 listUser·p0.999:  36.516 ms/op
                 listUser·p0.9999: 37.945 ms/op
                 listUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8703
  mean =      3.680 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 599 
    [ 2.500,  5.000) = 7821 
    [ 5.000,  7.500) = 202 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.912 ms/op
     p(99.9000) =     36.516 ms/op
     p(99.9900) =     37.945 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.982          ops/ms
ClientSimple.existUser                       thrpt         14.439          ops/ms
ClientSimple.getUser                         thrpt         14.834          ops/ms
ClientSimple.listUser                        thrpt          8.217          ops/ms
ClientSimple.createUser                       avgt          2.011           ms/op
ClientSimple.existUser                        avgt          1.747           ms/op
ClientSimple.getUser                          avgt          2.010           ms/op
ClientSimple.listUser                         avgt          3.374           ms/op
ClientSimple.createUser                     sample  14443   2.212 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.889           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.997           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.545           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.669           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.195           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.224           ms/op
ClientSimple.existUser                      sample  20070   1.597 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.828           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.462           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.982           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.743           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.681           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.058           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.074           ms/op
ClientSimple.getUser                        sample  14458   2.212 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.709           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.167           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.961           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.621           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.780           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.289           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.303           ms/op
ClientSimple.listUser                       sample   8703   3.680 ± 0.074   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.184           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.912           ms/op
ClientSimple.listUser:listUser·p0.999       sample         36.516           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         37.945           ms/op
ClientSimple.listUser:listUser·p1.00        sample         37.945           ms/op

Benchmark result is saved to 1717719364206.json
