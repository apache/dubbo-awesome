# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.946 ops/ms
Iteration   1: 6.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.007 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.521 ops/ms
Iteration   1: 11.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.618 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.487 ops/ms
Iteration   1: 12.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.509 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.294 ops/ms
Iteration   1: 8.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.751 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.787 ±(99.9%) 0.059 ms/op
Iteration   1: 1.980 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.980 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.233 ±(99.9%) 0.046 ms/op
Iteration   1: 2.014 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.014 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.232 ±(99.9%) 0.065 ms/op
Iteration   1: 1.911 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.911 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.582 ±(99.9%) 0.092 ms/op
Iteration   1: 3.403 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.403 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.390 ±(99.9%) 0.075 ms/op
Iteration   1: 2.424 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   2.146 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  30.545 ms/op
                 createUser·p0.9999: 32.421 ms/op
                 createUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13165
  mean =      2.424 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9533 
    [ 2.500,  5.000) = 3495 
    [ 5.000,  7.500) = 102 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =     30.545 ms/op
     p(99.9900) =     32.421 ms/op
     p(99.9990) =     32.473 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.872 ±(99.9%) 0.065 ms/op
Iteration   1: 1.978 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.328 ms/op
                 existUser·p0.50:   1.862 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   3.771 ms/op
                 existUser·p0.999:  25.002 ms/op
                 existUser·p0.9999: 27.007 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16013
  mean =      1.978 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15082 
    [ 2.500,  5.000) = 782 
    [ 5.000,  7.500) = 97 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.328 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.771 ms/op
     p(99.9000) =     25.002 ms/op
     p(99.9900) =     27.007 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.646 ±(99.9%) 0.099 ms/op
Iteration   1: 2.177 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   2.062 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   4.585 ms/op
                 getUser·p0.999:  14.374 ms/op
                 getUser·p0.9999: 15.778 ms/op
                 getUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14705
  mean =      2.177 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 11914 
    [ 2.500,  3.750) = 2442 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      4.585 ms/op
     p(99.9000) =     14.374 ms/op
     p(99.9900) =     15.778 ms/op
     p(99.9990) =     15.778 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.464 ±(99.9%) 0.142 ms/op
Iteration   1: 3.320 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   3.355 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.649 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 16.531 ms/op
                 listUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9636
  mean =      3.320 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 1786 
    [ 2.500,  3.750) = 5290 
    [ 3.750,  5.000) = 2344 
    [ 5.000,  6.250) = 121 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.649 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     16.531 ms/op
     p(99.9990) =     16.531 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.007          ops/ms
ClientSimple.existUser                       thrpt         11.618          ops/ms
ClientSimple.getUser                         thrpt         12.509          ops/ms
ClientSimple.listUser                        thrpt          8.751          ops/ms
ClientSimple.createUser                       avgt          1.980           ms/op
ClientSimple.existUser                        avgt          2.014           ms/op
ClientSimple.getUser                          avgt          1.911           ms/op
ClientSimple.listUser                         avgt          3.403           ms/op
ClientSimple.createUser                     sample  13165   2.424 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.760           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.146           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.228           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.211           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.087           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.545           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.421           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.473           ms/op
ClientSimple.existUser                      sample  16013   1.978 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.328           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.862           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.771           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.002           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.007           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.165           ms/op
ClientSimple.getUser                        sample  14705   2.177 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.589           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.062           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.585           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.374           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.778           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.778           ms/op
ClientSimple.listUser                       sample   9636   3.320 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.792           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.355           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.137           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.649           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.663           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.531           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.531           ms/op

Benchmark result is saved to 1713269168566.json
