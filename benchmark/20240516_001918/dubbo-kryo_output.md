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
# Warmup Iteration   1: 2.247 ops/ms
Iteration   1: 6.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.837 ops/ms


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
# Warmup Iteration   1: 6.528 ops/ms
Iteration   1: 14.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.520 ops/ms


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
# Warmup Iteration   1: 5.676 ops/ms
Iteration   1: 12.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.048 ops/ms


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
# Warmup Iteration   1: 4.580 ops/ms
Iteration   1: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.110 ops/ms


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
# Warmup Iteration   1: 3.790 ±(99.9%) 0.064 ms/op
Iteration   1: 2.063 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.063 ms/op


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
# Warmup Iteration   1: 3.365 ±(99.9%) 0.058 ms/op
Iteration   1: 1.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.055 ms/op
Iteration   1: 2.218 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.218 ms/op


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
# Warmup Iteration   1: 3.948 ±(99.9%) 0.067 ms/op
Iteration   1: 3.725 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.725 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.089 ms/op
Iteration   1: 2.564 ±(99.9%) 0.062 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   2.372 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  42.926 ms/op
                 createUser·p0.9999: 44.250 ms/op
                 createUser·p1.00:   44.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12651
  mean =      2.564 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12479 
    [ 5.000, 10.000) = 140 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.372 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     42.926 ms/op
     p(99.9900) =     44.250 ms/op
     p(99.9990) =     44.302 ms/op
     p(99.9999) =     44.302 ms/op
    p(100.0000) =     44.302 ms/op


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
# Warmup Iteration   1: 3.134 ±(99.9%) 0.084 ms/op
Iteration   1: 2.237 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.216 ms/op
                 existUser·p0.90:   2.810 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  15.925 ms/op
                 existUser·p0.9999: 16.049 ms/op
                 existUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14306
  mean =      2.237 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 187 
    [ 1.250,  2.500) = 9889 
    [ 2.500,  3.750) = 4121 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     16.049 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 3.043 ±(99.9%) 0.073 ms/op
Iteration   1: 2.000 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.537 ms/op
                 getUser·p0.50:   1.798 ms/op
                 getUser·p0.90:   2.486 ms/op
                 getUser·p0.95:   2.666 ms/op
                 getUser·p0.99:   3.582 ms/op
                 getUser·p0.999:  31.688 ms/op
                 getUser·p0.9999: 32.519 ms/op
                 getUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15972
  mean =      2.000 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14453 
    [ 2.500,  5.000) = 1450 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      3.582 ms/op
     p(99.9000) =     31.688 ms/op
     p(99.9900) =     32.519 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 4.334 ±(99.9%) 0.139 ms/op
Iteration   1: 3.130 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.305 ms/op
                 listUser·p0.999:  12.665 ms/op
                 listUser·p0.9999: 14.834 ms/op
                 listUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10208
  mean =      3.130 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2890 
    [ 2.500,  3.750) = 5403 
    [ 3.750,  5.000) = 1750 
    [ 5.000,  6.250) = 121 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.305 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     14.834 ms/op
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
ClientSimple.createUser                      thrpt          6.837          ops/ms
ClientSimple.existUser                       thrpt         14.520          ops/ms
ClientSimple.getUser                         thrpt         12.048          ops/ms
ClientSimple.listUser                        thrpt          8.110          ops/ms
ClientSimple.createUser                       avgt          2.063           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.218           ms/op
ClientSimple.listUser                         avgt          3.725           ms/op
ClientSimple.createUser                     sample  12651   2.564 ± 0.062   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.607           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.372           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.154           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.841           ms/op
ClientSimple.createUser:createUser·p0.999   sample         42.926           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         44.250           ms/op
ClientSimple.createUser:createUser·p1.00    sample         44.302           ms/op
ClientSimple.existUser                      sample  14306   2.237 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.585           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.216           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.978           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.633           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.925           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.049           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.056           ms/op
ClientSimple.getUser                        sample  15972   2.000 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.537           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.798           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.486           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.582           ms/op
ClientSimple.getUser:getUser·p0.999         sample         31.688           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         32.519           ms/op
ClientSimple.getUser:getUser·p1.00          sample         32.539           ms/op
ClientSimple.listUser                       sample  10208   3.130 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.536           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.031           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.047           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.305           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.665           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.834           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.860           ms/op

Benchmark result is saved to 1715818500368.json
