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
# Warmup Iteration   1: 2.240 ops/ms
Iteration   1: 7.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.364 ops/ms


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
# Warmup Iteration   1: 5.843 ops/ms
Iteration   1: 11.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.470 ops/ms


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
# Warmup Iteration   1: 6.044 ops/ms
Iteration   1: 13.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.643 ops/ms


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
# Warmup Iteration   1: 5.576 ops/ms
Iteration   1: 8.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.694 ops/ms


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
# Warmup Iteration   1: 3.625 ±(99.9%) 0.061 ms/op
Iteration   1: 2.342 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.342 ms/op


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
# Warmup Iteration   1: 3.030 ±(99.9%) 0.057 ms/op
Iteration   1: 1.991 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.991 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.051 ms/op
Iteration   1: 2.032 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.032 ms/op


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.082 ms/op
Iteration   1: 3.107 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.107 ms/op


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
# Warmup Iteration   1: 3.650 ±(99.9%) 0.109 ms/op
Iteration   1: 2.080 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.385 ms/op
                 createUser·p0.50:   1.886 ms/op
                 createUser·p0.90:   2.454 ms/op
                 createUser·p0.95:   2.687 ms/op
                 createUser·p0.99:   8.703 ms/op
                 createUser·p0.999:  34.931 ms/op
                 createUser·p0.9999: 39.086 ms/op
                 createUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15913
  mean =      2.080 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14583 
    [ 2.500,  5.000) = 1015 
    [ 5.000,  7.500) = 118 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      8.703 ms/op
     p(99.9000) =     34.931 ms/op
     p(99.9900) =     39.086 ms/op
     p(99.9990) =     39.125 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


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
# Warmup Iteration   1: 3.009 ±(99.9%) 0.061 ms/op
Iteration   1: 1.771 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   1.665 ms/op
                 existUser·p0.90:   2.171 ms/op
                 existUser·p0.95:   2.384 ms/op
                 existUser·p0.99:   3.467 ms/op
                 existUser·p0.999:  24.183 ms/op
                 existUser·p0.9999: 24.615 ms/op
                 existUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18040
  mean =      1.771 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17448 
    [ 2.500,  5.000) = 514 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.384 ms/op
     p(99.0000) =      3.467 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     24.615 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.231 ms/op
Iteration   1: 2.010 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.332 ms/op
                 getUser·p0.50:   1.802 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.523 ms/op
                 getUser·p0.999:  14.107 ms/op
                 getUser·p0.9999: 14.359 ms/op
                 getUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15996
  mean =      2.010 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 13575 
    [ 2.500,  3.750) = 2129 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.332 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.523 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     14.359 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 4.393 ±(99.9%) 0.117 ms/op
Iteration   1: 3.503 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.598 ms/op
                 listUser·p0.999:  23.032 ms/op
                 listUser·p0.9999: 25.690 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9128
  mean =      3.503 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1013 
    [ 2.500,  5.000) = 7889 
    [ 5.000,  7.500) = 187 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.598 ms/op
     p(99.9000) =     23.032 ms/op
     p(99.9900) =     25.690 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.364          ops/ms
ClientSimple.existUser                       thrpt         11.470          ops/ms
ClientSimple.getUser                         thrpt         13.643          ops/ms
ClientSimple.listUser                        thrpt          8.694          ops/ms
ClientSimple.createUser                       avgt          2.342           ms/op
ClientSimple.existUser                        avgt          1.991           ms/op
ClientSimple.getUser                          avgt          2.032           ms/op
ClientSimple.listUser                         avgt          3.107           ms/op
ClientSimple.createUser                     sample  15913   2.080 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.385           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.886           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.703           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.931           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.086           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.125           ms/op
ClientSimple.existUser                      sample  18040   1.771 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.551           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.665           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.467           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.183           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.615           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.642           ms/op
ClientSimple.getUser                        sample  15996   2.010 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.332           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.802           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.215           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.523           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.107           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.359           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.369           ms/op
ClientSimple.listUser                       sample   9128   3.503 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.827           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.518           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.497           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.598           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.032           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.690           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.690           ms/op

Benchmark result is saved to 1715623494074.json
