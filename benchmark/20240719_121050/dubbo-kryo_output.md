# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.823 ops/ms
Iteration   1: 7.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.011 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.405 ops/ms
Iteration   1: 13.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.718 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.083 ops/ms
Iteration   1: 13.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.499 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.733 ops/ms
Iteration   1: 8.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.579 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.657 ±(99.9%) 0.095 ms/op
Iteration   1: 2.489 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.489 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.043 ±(99.9%) 0.047 ms/op
Iteration   1: 1.573 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.573 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.078 ±(99.9%) 0.054 ms/op
Iteration   1: 1.932 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.932 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.420 ±(99.9%) 0.112 ms/op
Iteration   1: 3.328 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.328 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.571 ±(99.9%) 0.106 ms/op
Iteration   1: 2.063 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   1.978 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.662 ms/op
                 createUser·p0.99:   3.432 ms/op
                 createUser·p0.999:  18.416 ms/op
                 createUser·p0.9999: 19.662 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15498
  mean =      2.063 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 13826 
    [ 2.500,  3.750) = 1236 
    [ 3.750,  5.000) = 13 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.432 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     19.662 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.027 ±(99.9%) 0.064 ms/op
Iteration   1: 2.004 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.261 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.503 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  26.313 ms/op
                 existUser·p0.9999: 26.956 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15941
  mean =      2.004 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14316 
    [ 2.500,  5.000) = 1503 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.261 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =     26.313 ms/op
     p(99.9900) =     26.956 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ±(99.9%) 0.087 ms/op
Iteration   1: 2.064 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.442 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.597 ms/op
                 getUser·p0.95:   2.761 ms/op
                 getUser·p0.99:   4.330 ms/op
                 getUser·p0.999:  10.837 ms/op
                 getUser·p0.9999: 11.350 ms/op
                 getUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15570
  mean =      2.064 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 13216 
    [ 2.500,  3.750) = 2025 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      4.330 ms/op
     p(99.9000) =     10.837 ms/op
     p(99.9900) =     11.350 ms/op
     p(99.9990) =     11.551 ms/op
     p(99.9999) =     11.551 ms/op
    p(100.0000) =     11.551 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.130 ms/op
Iteration   1: 3.518 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.391 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  21.555 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9089
  mean =      3.518 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 819 
    [ 2.500,  5.000) = 7866 
    [ 5.000,  7.500) = 305 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     21.555 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.011          ops/ms
ClientSimple.existUser                       thrpt         13.718          ops/ms
ClientSimple.getUser                         thrpt         13.499          ops/ms
ClientSimple.listUser                        thrpt          8.579          ops/ms
ClientSimple.createUser                       avgt          2.489           ms/op
ClientSimple.existUser                        avgt          1.573           ms/op
ClientSimple.getUser                          avgt          1.932           ms/op
ClientSimple.listUser                         avgt          3.328           ms/op
ClientSimple.createUser                     sample  15498   2.063 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.659           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.978           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.432           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.416           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.662           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.825           ms/op
ClientSimple.existUser                      sample  15941   2.004 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.261           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.153           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.313           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.956           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.034           ms/op
ClientSimple.getUser                        sample  15570   2.064 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.442           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.330           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.837           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.350           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.551           ms/op
ClientSimple.listUser                       sample   9089   3.518 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.391           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.421           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.555           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.381           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.381           ms/op

Benchmark result is saved to 1721390792380.json
