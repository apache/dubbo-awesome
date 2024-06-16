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
# Warmup Iteration   1: 1.892 ops/ms
Iteration   1: 6.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.996 ops/ms


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
# Warmup Iteration   1: 5.970 ops/ms
Iteration   1: 12.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.474 ops/ms


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
# Warmup Iteration   1: 5.277 ops/ms
Iteration   1: 12.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.606 ops/ms


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
# Warmup Iteration   1: 3.910 ops/ms
Iteration   1: 8.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.162 ops/ms


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.098 ms/op
Iteration   1: 2.050 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.050 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.055 ms/op
Iteration   1: 2.162 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.162 ms/op


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
# Warmup Iteration   1: 3.555 ±(99.9%) 0.070 ms/op
Iteration   1: 2.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.046 ms/op


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
# Warmup Iteration   1: 4.334 ±(99.9%) 0.137 ms/op
Iteration   1: 3.019 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.019 ms/op


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.171 ms/op
Iteration   1: 2.114 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   2.001 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   8.104 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 18.628 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15067
  mean =      2.114 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 13118 
    [ 2.500,  3.750) = 1512 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      8.104 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     18.628 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.067 ms/op
Iteration   1: 1.904 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.434 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  13.402 ms/op
                 existUser·p0.9999: 13.670 ms/op
                 existUser·p1.00:   14.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16892
  mean =      1.904 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1042 
    [ 1.250,  2.500) = 15009 
    [ 2.500,  3.750) = 699 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     13.670 ms/op
     p(99.9990) =     14.156 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.430 ±(99.9%) 0.086 ms/op
Iteration   1: 2.077 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   1.999 ms/op
                 getUser·p0.90:   2.634 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   4.146 ms/op
                 getUser·p0.999:  11.420 ms/op
                 getUser·p0.9999: 12.206 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15387
  mean =      2.077 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 239 
    [ 1.250,  2.500) = 12621 
    [ 2.500,  3.750) = 2305 
    [ 3.750,  5.000) = 171 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      4.146 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     12.206 ms/op
     p(99.9990) =     12.206 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.127 ms/op
Iteration   1: 3.872 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   7.752 ms/op
                 listUser·p0.999:  8.274 ms/op
                 listUser·p0.9999: 12.419 ms/op
                 listUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8267
  mean =      3.872 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 300 
    [ 2.500,  3.750) = 3398 
    [ 3.750,  5.000) = 3740 
    [ 5.000,  6.250) = 661 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.752 ms/op
     p(99.9000) =      8.274 ms/op
     p(99.9900) =     12.419 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.996          ops/ms
ClientSimple.existUser                       thrpt         12.474          ops/ms
ClientSimple.getUser                         thrpt         12.606          ops/ms
ClientSimple.listUser                        thrpt          8.162          ops/ms
ClientSimple.createUser                       avgt          2.050           ms/op
ClientSimple.existUser                        avgt          2.162           ms/op
ClientSimple.getUser                          avgt          2.046           ms/op
ClientSimple.listUser                         avgt          3.019           ms/op
ClientSimple.createUser                     sample  15067   2.114 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.871           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.001           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.104           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.383           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.628           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.645           ms/op
ClientSimple.existUser                      sample  16892   1.904 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.434           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.510           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.402           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.670           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.156           ms/op
ClientSimple.getUser                        sample  15387   2.077 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.720           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.999           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.146           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.420           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.206           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.206           ms/op
ClientSimple.listUser                       sample   8267   3.872 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.063           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.850           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.300           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.752           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.274           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.419           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.419           ms/op

Benchmark result is saved to 1718539577438.json
