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
# Warmup Iteration   1: 0.894 ops/ms
Iteration   1: 6.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.493 ops/ms


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
# Warmup Iteration   1: 6.235 ops/ms
Iteration   1: 13.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.677 ops/ms


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
# Warmup Iteration   1: 5.854 ops/ms
Iteration   1: 13.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.966 ops/ms


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
# Warmup Iteration   1: 4.386 ops/ms
Iteration   1: 8.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.996 ops/ms


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.084 ms/op
Iteration   1: 2.134 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.134 ms/op


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
# Warmup Iteration   1: 2.970 ±(99.9%) 0.050 ms/op
Iteration   1: 1.864 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.864 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.056 ms/op
Iteration   1: 1.998 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.998 ms/op


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.109 ms/op
Iteration   1: 3.507 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.507 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.100 ms/op
Iteration   1: 2.235 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.044 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   6.345 ms/op
                 createUser·p0.999:  15.524 ms/op
                 createUser·p0.9999: 16.483 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14489
  mean =      2.235 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 421 
    [ 1.250,  2.500) = 10286 
    [ 2.500,  3.750) = 3210 
    [ 3.750,  5.000) = 308 
    [ 5.000,  6.250) = 113 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.044 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      6.345 ms/op
     p(99.9000) =     15.524 ms/op
     p(99.9900) =     16.483 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.079 ms/op
Iteration   1: 1.815 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   3.575 ms/op
                 existUser·p0.999:  29.991 ms/op
                 existUser·p0.9999: 30.285 ms/op
                 existUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17741
  mean =      1.815 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16511 
    [ 2.500,  5.000) = 1146 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.575 ms/op
     p(99.9000) =     29.991 ms/op
     p(99.9900) =     30.285 ms/op
     p(99.9990) =     30.310 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 3.231 ±(99.9%) 0.078 ms/op
Iteration   1: 2.072 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.695 ms/op
                 getUser·p0.95:   2.966 ms/op
                 getUser·p0.99:   4.232 ms/op
                 getUser·p0.999:  14.036 ms/op
                 getUser·p0.9999: 15.946 ms/op
                 getUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15439
  mean =      2.072 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 326 
    [ 1.250,  2.500) = 12574 
    [ 2.500,  3.750) = 2340 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      4.232 ms/op
     p(99.9000) =     14.036 ms/op
     p(99.9900) =     15.946 ms/op
     p(99.9990) =     16.400 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.138 ms/op
Iteration   1: 3.190 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   2.839 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.273 ms/op
                 listUser·p0.999:  16.203 ms/op
                 listUser·p0.9999: 16.515 ms/op
                 listUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10019
  mean =      3.190 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 631 
    [ 2.500,  3.750) = 7696 
    [ 3.750,  5.000) = 1449 
    [ 5.000,  6.250) = 138 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.273 ms/op
     p(99.9000) =     16.203 ms/op
     p(99.9900) =     16.515 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.493          ops/ms
ClientSimple.existUser                       thrpt         13.677          ops/ms
ClientSimple.getUser                         thrpt         13.966          ops/ms
ClientSimple.listUser                        thrpt          8.996          ops/ms
ClientSimple.createUser                       avgt          2.134           ms/op
ClientSimple.existUser                        avgt          1.864           ms/op
ClientSimple.getUser                          avgt          1.998           ms/op
ClientSimple.listUser                         avgt          3.507           ms/op
ClientSimple.createUser                     sample  14489   2.235 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.570           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.044           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.490           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.345           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.524           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.483           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.777           ms/op
ClientSimple.existUser                      sample  17741   1.815 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.546           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.671           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.575           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.991           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.285           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.310           ms/op
ClientSimple.getUser                        sample  15439   2.072 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.500           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.232           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.036           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.946           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.400           ms/op
ClientSimple.listUser                       sample  10019   3.190 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.475           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.839           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.273           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.203           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.515           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.515           ms/op

Benchmark result is saved to 1725927482866.json
