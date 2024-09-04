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
# Warmup Iteration   1: 1.901 ops/ms
Iteration   1: 7.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.000 ops/ms


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
# Warmup Iteration   1: 7.111 ops/ms
Iteration   1: 14.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.053 ops/ms


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
# Warmup Iteration   1: 5.979 ops/ms
Iteration   1: 12.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.902 ops/ms


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
# Warmup Iteration   1: 4.967 ops/ms
Iteration   1: 8.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.566 ops/ms


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
# Warmup Iteration   1: 3.517 ±(99.9%) 0.074 ms/op
Iteration   1: 2.072 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.072 ms/op


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.065 ms/op
Iteration   1: 1.936 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.936 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.055 ms/op
Iteration   1: 2.118 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.118 ms/op


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.079 ms/op
Iteration   1: 3.774 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.774 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.121 ms/op
Iteration   1: 2.270 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.415 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.425 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   10.104 ms/op
                 createUser·p0.999:  16.073 ms/op
                 createUser·p0.9999: 16.239 ms/op
                 createUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14065
  mean =      2.270 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 12741 
    [ 2.500,  3.750) = 700 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =     10.104 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     16.239 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 3.078 ±(99.9%) 0.071 ms/op
Iteration   1: 1.751 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   1.637 ms/op
                 existUser·p0.90:   2.175 ms/op
                 existUser·p0.95:   2.413 ms/op
                 existUser·p0.99:   3.036 ms/op
                 existUser·p0.999:  13.564 ms/op
                 existUser·p0.9999: 13.961 ms/op
                 existUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18368
  mean =      1.751 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 622 
    [ 1.250,  2.500) = 17038 
    [ 2.500,  3.750) = 571 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      1.637 ms/op
     p(90.0000) =      2.175 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      3.036 ms/op
     p(99.9000) =     13.564 ms/op
     p(99.9900) =     13.961 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.095 ms/op
Iteration   1: 2.468 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.473 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.648 ms/op
                 getUser·p0.999:  12.862 ms/op
                 getUser·p0.9999: 13.101 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12955
  mean =      2.468 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 203 
    [ 1.250,  2.500) = 6381 
    [ 2.500,  3.750) = 6073 
    [ 3.750,  5.000) = 185 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.301 ms/op
     p(99.0000) =      4.648 ms/op
     p(99.9000) =     12.862 ms/op
     p(99.9900) =     13.101 ms/op
     p(99.9990) =     13.140 ms/op
     p(99.9999) =     13.140 ms/op
    p(100.0000) =     13.140 ms/op


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.135 ms/op
Iteration   1: 3.554 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   5.988 ms/op
                 listUser·p0.999:  7.953 ms/op
                 listUser·p0.9999: 15.876 ms/op
                 listUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9001
  mean =      3.554 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1064 
    [ 2.500,  3.750) = 4398 
    [ 3.750,  5.000) = 3217 
    [ 5.000,  6.250) = 240 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =      7.953 ms/op
     p(99.9900) =     15.876 ms/op
     p(99.9990) =     15.876 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.000          ops/ms
ClientSimple.existUser                       thrpt         14.053          ops/ms
ClientSimple.getUser                         thrpt         12.902          ops/ms
ClientSimple.listUser                        thrpt          8.566          ops/ms
ClientSimple.createUser                       avgt          2.072           ms/op
ClientSimple.existUser                        avgt          1.936           ms/op
ClientSimple.getUser                          avgt          2.118           ms/op
ClientSimple.listUser                         avgt          3.774           ms/op
ClientSimple.createUser                     sample  14065   2.270 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.415           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.425           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.104           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.073           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.239           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.318           ms/op
ClientSimple.existUser                      sample  18368   1.751 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.629           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.637           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.175           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.036           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.564           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.961           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.057           ms/op
ClientSimple.getUser                        sample  12955   2.468 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.473           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.043           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.301           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.648           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.862           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.101           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.140           ms/op
ClientSimple.listUser                       sample   9001   3.554 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.282           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.988           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.953           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.876           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.876           ms/op

Benchmark result is saved to 1725451686299.json
