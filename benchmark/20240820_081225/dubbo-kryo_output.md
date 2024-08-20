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
# Warmup Iteration   1: 1.855 ops/ms
Iteration   1: 7.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.795 ops/ms


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
# Warmup Iteration   1: 5.683 ops/ms
Iteration   1: 13.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.307 ops/ms


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
# Warmup Iteration   1: 5.207 ops/ms
Iteration   1: 13.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.268 ops/ms


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
# Warmup Iteration   1: 5.754 ops/ms
Iteration   1: 8.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.514 ops/ms


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.079 ms/op
Iteration   1: 2.110 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.110 ms/op


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
# Warmup Iteration   1: 2.923 ±(99.9%) 0.043 ms/op
Iteration   1: 2.103 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.103 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.078 ms/op
Iteration   1: 2.233 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.233 ms/op


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.096 ms/op
Iteration   1: 3.232 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.232 ms/op


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.093 ms/op
Iteration   1: 2.408 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   2.216 ms/op
                 createUser·p0.90:   2.814 ms/op
                 createUser·p0.95:   3.327 ms/op
                 createUser·p0.99:   7.479 ms/op
                 createUser·p0.999:  17.698 ms/op
                 createUser·p0.9999: 19.528 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13534
  mean =      2.408 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 10254 
    [ 2.500,  3.750) = 2708 
    [ 3.750,  5.000) = 199 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.327 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     17.698 ms/op
     p(99.9900) =     19.528 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.130 ms/op
Iteration   1: 2.116 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.379 ms/op
                 existUser·p0.50:   1.903 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.818 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  20.939 ms/op
                 existUser·p0.9999: 21.543 ms/op
                 existUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15102
  mean =      2.116 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13488 
    [ 2.500,  5.000) = 1347 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     20.939 ms/op
     p(99.9900) =     21.543 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 3.138 ±(99.9%) 0.081 ms/op
Iteration   1: 1.968 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.559 ms/op
                 getUser·p0.50:   1.855 ms/op
                 getUser·p0.90:   2.552 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   3.514 ms/op
                 getUser·p0.999:  15.237 ms/op
                 getUser·p0.9999: 16.007 ms/op
                 getUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16248
  mean =      1.968 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 656 
    [ 1.250,  2.500) = 13497 
    [ 2.500,  3.750) = 1997 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     16.007 ms/op
     p(99.9990) =     16.007 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.134 ms/op
Iteration   1: 3.359 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.128 ms/op
                 listUser·p0.999:  16.365 ms/op
                 listUser·p0.9999: 16.581 ms/op
                 listUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9533
  mean =      3.359 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 442 
    [ 2.500,  3.750) = 6632 
    [ 3.750,  5.000) = 2207 
    [ 5.000,  6.250) = 160 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     16.365 ms/op
     p(99.9900) =     16.581 ms/op
     p(99.9990) =     16.581 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.795          ops/ms
ClientSimple.existUser                       thrpt         13.307          ops/ms
ClientSimple.getUser                         thrpt         13.268          ops/ms
ClientSimple.listUser                        thrpt          8.514          ops/ms
ClientSimple.createUser                       avgt          2.110           ms/op
ClientSimple.existUser                        avgt          2.103           ms/op
ClientSimple.getUser                          avgt          2.233           ms/op
ClientSimple.listUser                         avgt          3.232           ms/op
ClientSimple.createUser                     sample  13534   2.408 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.765           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.216           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.327           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.479           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.698           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.528           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.562           ms/op
ClientSimple.existUser                      sample  15102   2.116 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.379           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.903           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.818           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.619           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.939           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.543           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.660           ms/op
ClientSimple.getUser                        sample  16248   1.968 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.559           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.855           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.552           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.514           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.237           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.007           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.007           ms/op
ClientSimple.listUser                       sample   9533   3.359 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.948           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.052           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.128           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.365           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.581           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.581           ms/op

Benchmark result is saved to 1724136310863.json
