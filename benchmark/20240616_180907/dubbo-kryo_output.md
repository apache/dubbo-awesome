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
# Warmup Iteration   1: 2.006 ops/ms
Iteration   1: 6.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.829 ops/ms


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
# Warmup Iteration   1: 5.615 ops/ms
Iteration   1: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.776 ops/ms


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
# Warmup Iteration   1: 4.903 ops/ms
Iteration   1: 11.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.282 ops/ms


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
# Warmup Iteration   1: 5.512 ops/ms
Iteration   1: 8.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.305 ops/ms


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
# Warmup Iteration   1: 3.727 ±(99.9%) 0.060 ms/op
Iteration   1: 2.050 ±(99.9%) 0.039 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.053 ms/op
Iteration   1: 1.855 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.855 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.055 ms/op
Iteration   1: 1.924 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.924 ms/op


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
# Warmup Iteration   1: 4.489 ±(99.9%) 0.096 ms/op
Iteration   1: 3.774 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.774 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.080 ms/op
Iteration   1: 2.068 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.354 ms/op
                 createUser·p0.50:   1.726 ms/op
                 createUser·p0.90:   2.908 ms/op
                 createUser·p0.95:   3.343 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  28.224 ms/op
                 createUser·p0.9999: 31.490 ms/op
                 createUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15736
  mean =      2.068 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13076 
    [ 2.500,  5.000) = 2472 
    [ 5.000,  7.500) = 58 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.343 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     28.224 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 3.444 ±(99.9%) 0.092 ms/op
Iteration   1: 2.082 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   2.009 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 13.632 ms/op
                 existUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15486
  mean =      2.082 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 444 
    [ 1.250,  2.500) = 12574 
    [ 2.500,  3.750) = 2371 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     13.632 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.078 ms/op
Iteration   1: 1.978 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   1.894 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.626 ms/op
                 getUser·p0.99:   3.590 ms/op
                 getUser·p0.999:  15.794 ms/op
                 getUser·p0.9999: 16.255 ms/op
                 getUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16161
  mean =      1.978 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 14751 
    [ 2.500,  3.750) = 996 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.590 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     16.255 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.184 ms/op
Iteration   1: 2.898 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   2.740 ms/op
                 listUser·p0.90:   3.400 ms/op
                 listUser·p0.95:   3.801 ms/op
                 listUser·p0.99:   5.523 ms/op
                 listUser·p0.999:  14.642 ms/op
                 listUser·p0.9999: 16.034 ms/op
                 listUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 11026
  mean =      2.898 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 710 
    [ 2.500,  3.750) = 9675 
    [ 3.750,  5.000) = 515 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.523 ms/op
     p(99.9000) =     14.642 ms/op
     p(99.9900) =     16.034 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.829          ops/ms
ClientSimple.existUser                       thrpt         12.776          ops/ms
ClientSimple.getUser                         thrpt         11.282          ops/ms
ClientSimple.listUser                        thrpt          8.305          ops/ms
ClientSimple.createUser                       avgt          2.050           ms/op
ClientSimple.existUser                        avgt          1.855           ms/op
ClientSimple.getUser                          avgt          1.924           ms/op
ClientSimple.listUser                         avgt          3.774           ms/op
ClientSimple.createUser                     sample  15736   2.068 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.354           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.726           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.343           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.947           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.224           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.490           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.490           ms/op
ClientSimple.existUser                      sample  15486   2.082 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.450           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.009           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.572           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.665           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.632           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.713           ms/op
ClientSimple.getUser                        sample  16161   1.978 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.552           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.894           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.590           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.794           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.255           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.286           ms/op
ClientSimple.listUser                       sample  11026   2.898 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.303           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.740           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.400           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.801           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.523           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.642           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.034           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.073           ms/op

Benchmark result is saved to 1718561082699.json
