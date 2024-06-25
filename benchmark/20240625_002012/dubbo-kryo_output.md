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
# Warmup Iteration   1: 1.963 ops/ms
Iteration   1: 7.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.077 ops/ms


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
# Warmup Iteration   1: 5.663 ops/ms
Iteration   1: 12.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.650 ops/ms


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
# Warmup Iteration   1: 6.018 ops/ms
Iteration   1: 13.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.866 ops/ms


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
# Warmup Iteration   1: 5.289 ops/ms
Iteration   1: 9.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.053 ops/ms


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
# Warmup Iteration   1: 3.471 ±(99.9%) 0.051 ms/op
Iteration   1: 1.932 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.932 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.056 ms/op
Iteration   1: 1.906 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.906 ms/op


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
# Warmup Iteration   1: 3.489 ±(99.9%) 0.068 ms/op
Iteration   1: 1.957 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.957 ms/op


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.087 ms/op
Iteration   1: 3.043 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.043 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.087 ms/op
Iteration   1: 2.001 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.537 ms/op
                 createUser·p0.50:   1.832 ms/op
                 createUser·p0.90:   2.634 ms/op
                 createUser·p0.95:   2.818 ms/op
                 createUser·p0.99:   3.679 ms/op
                 createUser·p0.999:  18.800 ms/op
                 createUser·p0.9999: 21.424 ms/op
                 createUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16254
  mean =      2.001 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13907 
    [ 2.500,  5.000) = 2244 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.832 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.679 ms/op
     p(99.9000) =     18.800 ms/op
     p(99.9900) =     21.424 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 2.814 ±(99.9%) 0.064 ms/op
Iteration   1: 2.093 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   2.023 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  14.074 ms/op
                 existUser·p0.9999: 14.602 ms/op
                 existUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15284
  mean =      2.093 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 238 
    [ 1.250,  2.500) = 13396 
    [ 2.500,  3.750) = 1538 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     14.602 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.348 ±(99.9%) 0.082 ms/op
Iteration   1: 1.998 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   1.882 ms/op
                 getUser·p0.90:   2.384 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.439 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 17.577 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16002
  mean =      1.998 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 14806 
    [ 2.500,  3.750) = 1044 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.439 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     17.577 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 5.915 ±(99.9%) 0.159 ms/op
Iteration   1: 3.402 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.142 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.565 ms/op
                 listUser·p0.99:   8.865 ms/op
                 listUser·p0.999:  15.552 ms/op
                 listUser·p0.9999: 15.729 ms/op
                 listUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9394
  mean =      3.402 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 496 
    [ 2.500,  3.750) = 6255 
    [ 3.750,  5.000) = 2366 
    [ 5.000,  6.250) = 132 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.565 ms/op
     p(99.0000) =      8.865 ms/op
     p(99.9000) =     15.552 ms/op
     p(99.9900) =     15.729 ms/op
     p(99.9990) =     15.729 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.077          ops/ms
ClientSimple.existUser                       thrpt         12.650          ops/ms
ClientSimple.getUser                         thrpt         13.866          ops/ms
ClientSimple.listUser                        thrpt          9.053          ops/ms
ClientSimple.createUser                       avgt          1.932           ms/op
ClientSimple.existUser                        avgt          1.906           ms/op
ClientSimple.getUser                          avgt          1.957           ms/op
ClientSimple.listUser                         avgt          3.043           ms/op
ClientSimple.createUser                     sample  16254   2.001 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.537           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.832           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.679           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.800           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.424           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.658           ms/op
ClientSimple.existUser                      sample  15284   2.093 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.572           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.023           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.662           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.074           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.602           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.680           ms/op
ClientSimple.getUser                        sample  16002   1.998 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.820           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.882           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.439           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.302           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.577           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.596           ms/op
ClientSimple.listUser                       sample   9394   3.402 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.202           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.142           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.565           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.865           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.552           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.729           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.729           ms/op

Benchmark result is saved to 1719274549777.json
