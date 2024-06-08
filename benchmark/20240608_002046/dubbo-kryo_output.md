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
# Warmup Iteration   1: 1.798 ops/ms
Iteration   1: 7.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.909 ops/ms


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
# Warmup Iteration   1: 5.303 ops/ms
Iteration   1: 12.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.777 ops/ms


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
# Warmup Iteration   1: 5.077 ops/ms
Iteration   1: 12.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.404 ops/ms


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
# Warmup Iteration   1: 4.881 ops/ms
Iteration   1: 9.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.461 ops/ms


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.068 ms/op
Iteration   1: 2.085 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.085 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.051 ms/op
Iteration   1: 1.761 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.761 ms/op


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
# Warmup Iteration   1: 3.188 ±(99.9%) 0.060 ms/op
Iteration   1: 1.922 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.922 ms/op


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.080 ms/op
Iteration   1: 3.151 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.151 ms/op


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
# Warmup Iteration   1: 3.194 ±(99.9%) 0.077 ms/op
Iteration   1: 1.943 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.415 ms/op
                 createUser·p0.50:   1.733 ms/op
                 createUser·p0.90:   2.228 ms/op
                 createUser·p0.95:   2.408 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  21.692 ms/op
                 createUser·p0.9999: 23.499 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16439
  mean =      1.943 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15735 
    [ 2.500,  5.000) = 389 
    [ 5.000,  7.500) = 101 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     23.499 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.999 ±(99.9%) 0.074 ms/op
Iteration   1: 2.012 ±(99.9%) 0.049 ms/op
                 existUser·p0.00:   0.261 ms/op
                 existUser·p0.50:   1.790 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   5.493 ms/op
                 existUser·p0.999:  37.224 ms/op
                 existUser·p0.9999: 39.074 ms/op
                 existUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15949
  mean =      2.012 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15260 
    [ 2.500,  5.000) = 527 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.261 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      5.493 ms/op
     p(99.9000) =     37.224 ms/op
     p(99.9900) =     39.074 ms/op
     p(99.9990) =     39.191 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ±(99.9%) 0.076 ms/op
Iteration   1: 1.950 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.497 ms/op
                 getUser·p0.50:   1.849 ms/op
                 getUser·p0.90:   2.397 ms/op
                 getUser·p0.95:   2.568 ms/op
                 getUser·p0.99:   3.543 ms/op
                 getUser·p0.999:  15.198 ms/op
                 getUser·p0.9999: 16.394 ms/op
                 getUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16388
  mean =      1.950 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 388 
    [ 1.250,  2.500) = 14942 
    [ 2.500,  3.750) = 907 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.397 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =     15.198 ms/op
     p(99.9900) =     16.394 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.561 ±(99.9%) 0.136 ms/op
Iteration   1: 3.046 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   2.806 ms/op
                 listUser·p0.90:   3.806 ms/op
                 listUser·p0.95:   4.052 ms/op
                 listUser·p0.99:   5.199 ms/op
                 listUser·p0.999:  6.586 ms/op
                 listUser·p0.9999: 14.859 ms/op
                 listUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10536
  mean =      3.046 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 729 
    [ 2.500,  3.750) = 8567 
    [ 3.750,  5.000) = 1088 
    [ 5.000,  6.250) = 116 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.806 ms/op
     p(95.0000) =      4.052 ms/op
     p(99.0000) =      5.199 ms/op
     p(99.9000) =      6.586 ms/op
     p(99.9900) =     14.859 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.909          ops/ms
ClientSimple.existUser                       thrpt         12.777          ops/ms
ClientSimple.getUser                         thrpt         12.404          ops/ms
ClientSimple.listUser                        thrpt          9.461          ops/ms
ClientSimple.createUser                       avgt          2.085           ms/op
ClientSimple.existUser                        avgt          1.761           ms/op
ClientSimple.getUser                          avgt          1.922           ms/op
ClientSimple.listUser                         avgt          3.151           ms/op
ClientSimple.createUser                     sample  16439   1.943 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.415           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.733           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.228           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.408           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.716           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.692           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.499           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.626           ms/op
ClientSimple.existUser                      sample  15949   2.012 ± 0.049   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.261           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.790           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.493           ms/op
ClientSimple.existUser:existUser·p0.999     sample         37.224           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         39.074           ms/op
ClientSimple.existUser:existUser·p1.00      sample         39.191           ms/op
ClientSimple.getUser                        sample  16388   1.950 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.497           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.849           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.397           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.543           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.198           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.394           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.613           ms/op
ClientSimple.listUser                       sample  10536   3.046 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.499           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.806           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.806           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.052           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.199           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.586           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.859           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.860           ms/op

Benchmark result is saved to 1717805785002.json
