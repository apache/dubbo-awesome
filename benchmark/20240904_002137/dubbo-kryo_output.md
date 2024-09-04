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
# Warmup Iteration   1: 1.431 ops/ms
Iteration   1: 7.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.133 ops/ms


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
# Warmup Iteration   1: 6.043 ops/ms
Iteration   1: 12.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.125 ops/ms


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
# Warmup Iteration   1: 6.060 ops/ms
Iteration   1: 12.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.492 ops/ms


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
# Warmup Iteration   1: 3.898 ops/ms
Iteration   1: 8.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.048 ops/ms


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.087 ms/op
Iteration   1: 2.221 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.221 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.056 ms/op
Iteration   1: 1.911 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.911 ms/op


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
# Warmup Iteration   1: 3.392 ±(99.9%) 0.092 ms/op
Iteration   1: 2.121 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.121 ms/op


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.093 ms/op
Iteration   1: 3.629 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.629 ms/op


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.262 ms/op
Iteration   1: 2.027 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   1.868 ms/op
                 createUser·p0.90:   2.318 ms/op
                 createUser·p0.95:   2.675 ms/op
                 createUser·p0.99:   6.458 ms/op
                 createUser·p0.999:  18.325 ms/op
                 createUser·p0.9999: 19.253 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15763
  mean =      2.027 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 14554 
    [ 2.500,  3.750) = 819 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      6.458 ms/op
     p(99.9000) =     18.325 ms/op
     p(99.9900) =     19.253 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 2.920 ±(99.9%) 0.072 ms/op
Iteration   1: 1.972 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   3.677 ms/op
                 existUser·p0.999:  13.402 ms/op
                 existUser·p0.9999: 14.300 ms/op
                 existUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16212
  mean =      1.972 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 14533 
    [ 2.500,  3.750) = 1353 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.677 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     14.300 ms/op
     p(99.9990) =     14.483 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.091 ms/op
Iteration   1: 1.974 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.532 ms/op
                 getUser·p0.50:   1.812 ms/op
                 getUser·p0.90:   2.376 ms/op
                 getUser·p0.95:   2.783 ms/op
                 getUser·p0.99:   5.383 ms/op
                 getUser·p0.999:  25.100 ms/op
                 getUser·p0.9999: 25.559 ms/op
                 getUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16188
  mean =      1.974 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14897 
    [ 2.500,  5.000) = 1096 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.783 ms/op
     p(99.0000) =      5.383 ms/op
     p(99.9000) =     25.100 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 5.089 ±(99.9%) 0.189 ms/op
Iteration   1: 3.524 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.375 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   6.160 ms/op
                 listUser·p0.999:  14.924 ms/op
                 listUser·p0.9999: 15.221 ms/op
                 listUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9103
  mean =      3.524 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 935 
    [ 2.500,  3.750) = 4655 
    [ 3.750,  5.000) = 3118 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     14.924 ms/op
     p(99.9900) =     15.221 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.133          ops/ms
ClientSimple.existUser                       thrpt         12.125          ops/ms
ClientSimple.getUser                         thrpt         12.492          ops/ms
ClientSimple.listUser                        thrpt          8.048          ops/ms
ClientSimple.createUser                       avgt          2.221           ms/op
ClientSimple.existUser                        avgt          1.911           ms/op
ClientSimple.getUser                          avgt          2.121           ms/op
ClientSimple.listUser                         avgt          3.629           ms/op
ClientSimple.createUser                     sample  15763   2.027 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.010           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.868           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.318           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.675           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.458           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.325           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.253           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.366           ms/op
ClientSimple.existUser                      sample  16212   1.972 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.575           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.858           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.677           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.402           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.300           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.483           ms/op
ClientSimple.getUser                        sample  16188   1.974 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.532           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.812           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.783           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.383           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.100           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.559           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.559           ms/op
ClientSimple.listUser                       sample   9103   3.524 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.959           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.375           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.160           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.924           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.221           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.221           ms/op

Benchmark result is saved to 1725409046934.json
