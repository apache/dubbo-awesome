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
# Warmup Iteration   1: 1.656 ops/ms
Iteration   1: 8.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.209 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.167 ops/ms
Iteration   1: 11.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.384 ops/ms


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
# Warmup Iteration   1: 5.296 ops/ms
Iteration   1: 11.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.998 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.441 ops/ms
Iteration   1: 7.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.454 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.069 ms/op
Iteration   1: 2.079 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.079 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.419 ±(99.9%) 0.048 ms/op
Iteration   1: 1.758 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.758 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ±(99.9%) 0.055 ms/op
Iteration   1: 2.014 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.014 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.430 ±(99.9%) 0.090 ms/op
Iteration   1: 3.249 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.249 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ±(99.9%) 0.087 ms/op
Iteration   1: 2.268 ±(99.9%) 0.069 ms/op
                 createUser·p0.00:   0.471 ms/op
                 createUser·p0.50:   2.032 ms/op
                 createUser·p0.90:   2.650 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  48.431 ms/op
                 createUser·p0.9999: 49.283 ms/op
                 createUser·p1.00:   49.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14397
  mean =      2.268 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14225 
    [ 5.000, 10.000) = 76 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 33 
    [20.000, 25.000) = 31 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     48.431 ms/op
     p(99.9900) =     49.283 ms/op
     p(99.9990) =     49.283 ms/op
     p(99.9999) =     49.283 ms/op
    p(100.0000) =     49.283 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.254 ±(99.9%) 0.080 ms/op
Iteration   1: 1.971 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  22.315 ms/op
                 existUser·p0.9999: 24.560 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16246
  mean =      1.971 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15460 
    [ 2.500,  5.000) = 653 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =     22.315 ms/op
     p(99.9900) =     24.560 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 3.362 ±(99.9%) 0.089 ms/op
Iteration   1: 2.157 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.101 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  13.402 ms/op
                 getUser·p0.9999: 13.574 ms/op
                 getUser·p1.00:   13.582 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14903
  mean =      2.157 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 262 
    [ 1.250,  2.500) = 11860 
    [ 2.500,  3.750) = 2560 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     13.574 ms/op
     p(99.9990) =     13.582 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.123 ms/op
Iteration   1: 3.186 ±(99.9%) 0.063 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   2.814 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.335 ms/op
                 listUser·p0.999:  30.407 ms/op
                 listUser·p0.9999: 31.064 ms/op
                 listUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10055
  mean =      3.186 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2670 
    [ 2.500,  5.000) = 7129 
    [ 5.000,  7.500) = 174 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.335 ms/op
     p(99.9000) =     30.407 ms/op
     p(99.9900) =     31.064 ms/op
     p(99.9990) =     31.064 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.209          ops/ms
ClientSimple.existUser                       thrpt         11.384          ops/ms
ClientSimple.getUser                         thrpt         11.998          ops/ms
ClientSimple.listUser                        thrpt          7.454          ops/ms
ClientSimple.createUser                       avgt          2.079           ms/op
ClientSimple.existUser                        avgt          1.758           ms/op
ClientSimple.getUser                          avgt          2.014           ms/op
ClientSimple.listUser                         avgt          3.249           ms/op
ClientSimple.createUser                     sample  14397   2.268 ± 0.069   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.471           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.032           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.333           ms/op
ClientSimple.createUser:createUser·p0.999   sample         48.431           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         49.283           ms/op
ClientSimple.createUser:createUser·p1.00    sample         49.283           ms/op
ClientSimple.existUser                      sample  16246   1.971 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.705           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.751           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.315           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.560           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.625           ms/op
ClientSimple.getUser                        sample  14903   2.157 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.845           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.101           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.063           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.402           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.574           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.582           ms/op
ClientSimple.listUser                       sample  10055   3.186 ± 0.063   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.020           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.814           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.961           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.335           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.407           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.064           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.064           ms/op

Benchmark result is saved to 1721693815382.json
