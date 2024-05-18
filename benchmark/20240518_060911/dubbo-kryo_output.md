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
# Warmup Iteration   1: 1.768 ops/ms
Iteration   1: 6.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.494 ops/ms


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
# Warmup Iteration   1: 5.907 ops/ms
Iteration   1: 14.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.235 ops/ms


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
# Warmup Iteration   1: 5.779 ops/ms
Iteration   1: 13.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.228 ops/ms


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
# Warmup Iteration   1: 5.449 ops/ms
Iteration   1: 8.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.782 ops/ms


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.079 ms/op
Iteration   1: 2.297 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.297 ms/op


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
# Warmup Iteration   1: 3.050 ±(99.9%) 0.052 ms/op
Iteration   1: 1.862 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.862 ms/op


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
# Warmup Iteration   1: 3.137 ±(99.9%) 0.054 ms/op
Iteration   1: 1.995 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.995 ms/op


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
# Warmup Iteration   1: 4.693 ±(99.9%) 0.099 ms/op
Iteration   1: 3.685 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.685 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.079 ms/op
Iteration   1: 2.119 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   1.925 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   4.573 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 20.397 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15087
  mean =      2.119 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12910 
    [ 2.500,  5.000) = 2065 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      4.573 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     20.397 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.212 ms/op
Iteration   1: 2.078 ±(99.9%) 0.042 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   1.898 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   4.476 ms/op
                 existUser·p0.999:  32.604 ms/op
                 existUser·p0.9999: 33.348 ms/op
                 existUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15385
  mean =      2.078 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14302 
    [ 2.500,  5.000) = 943 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      4.476 ms/op
     p(99.9000) =     32.604 ms/op
     p(99.9900) =     33.348 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 3.066 ±(99.9%) 0.087 ms/op
Iteration   1: 1.930 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   1.782 ms/op
                 getUser·p0.90:   2.327 ms/op
                 getUser·p0.95:   2.580 ms/op
                 getUser·p0.99:   4.959 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 12.173 ms/op
                 getUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16583
  mean =      1.930 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 15465 
    [ 2.500,  3.750) = 753 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      4.959 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     12.173 ms/op
     p(99.9990) =     12.173 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


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
# Warmup Iteration   1: 5.464 ±(99.9%) 0.173 ms/op
Iteration   1: 3.290 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.244 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.607 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  18.063 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9772
  mean =      3.290 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 1853 
    [ 2.500,  3.750) = 5583 
    [ 3.750,  5.000) = 1993 
    [ 5.000,  6.250) = 201 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.607 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     18.063 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.494          ops/ms
ClientSimple.existUser                       thrpt         14.235          ops/ms
ClientSimple.getUser                         thrpt         13.228          ops/ms
ClientSimple.listUser                        thrpt          8.782          ops/ms
ClientSimple.createUser                       avgt          2.297           ms/op
ClientSimple.existUser                        avgt          1.862           ms/op
ClientSimple.getUser                          avgt          1.995           ms/op
ClientSimple.listUser                         avgt          3.685           ms/op
ClientSimple.createUser                     sample  15087   2.119 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.713           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.925           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.076           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.573           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.366           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.397           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.480           ms/op
ClientSimple.existUser                      sample  15385   2.078 ± 0.042   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.546           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.898           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.476           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.604           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.348           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.489           ms/op
ClientSimple.getUser                        sample  16583   1.930 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.857           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.782           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.959           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.091           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.173           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.173           ms/op
ClientSimple.listUser                       sample   9772   3.290 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.913           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.244           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.607           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.496           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.063           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.726           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.726           ms/op

Benchmark result is saved to 1716012290626.json
