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
# Warmup Iteration   1: 1.429 ops/ms
Iteration   1: 6.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.356 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.394 ops/ms
Iteration   1: 12.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.027 ops/ms


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
# Warmup Iteration   1: 6.131 ops/ms
Iteration   1: 13.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.085 ops/ms


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
# Warmup Iteration   1: 4.136 ops/ms
Iteration   1: 8.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.222 ops/ms


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.089 ms/op
Iteration   1: 2.151 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.151 ms/op


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
# Warmup Iteration   1: 3.324 ±(99.9%) 0.056 ms/op
Iteration   1: 1.797 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.797 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.051 ms/op
Iteration   1: 2.162 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.162 ms/op


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
# Warmup Iteration   1: 5.237 ±(99.9%) 0.121 ms/op
Iteration   1: 3.181 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.181 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.527 ±(99.9%) 0.096 ms/op
Iteration   1: 2.305 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   2.042 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   13.050 ms/op
                 createUser·p0.999:  29.594 ms/op
                 createUser·p0.9999: 30.570 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13851
  mean =      2.305 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11714 
    [ 2.500,  5.000) = 1878 
    [ 5.000,  7.500) = 67 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =     13.050 ms/op
     p(99.9000) =     29.594 ms/op
     p(99.9900) =     30.570 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 2.762 ±(99.9%) 0.066 ms/op
Iteration   1: 1.696 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   1.624 ms/op
                 existUser·p0.90:   1.907 ms/op
                 existUser·p0.95:   2.134 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  12.305 ms/op
                 existUser·p0.9999: 13.602 ms/op
                 existUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18937
  mean =      1.696 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 181 
    [ 1.250,  2.500) = 18383 
    [ 2.500,  3.750) = 231 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.624 ms/op
     p(90.0000) =      1.907 ms/op
     p(95.0000) =      2.134 ms/op
     p(99.0000) =      3.383 ms/op
     p(99.9000) =     12.305 ms/op
     p(99.9900) =     13.602 ms/op
     p(99.9990) =     13.631 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.094 ms/op
Iteration   1: 2.196 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.442 ms/op
                 getUser·p0.50:   2.114 ms/op
                 getUser·p0.90:   2.753 ms/op
                 getUser·p0.95:   2.863 ms/op
                 getUser·p0.99:   3.217 ms/op
                 getUser·p0.999:  12.984 ms/op
                 getUser·p0.9999: 13.083 ms/op
                 getUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14771
  mean =      2.196 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 11177 
    [ 2.500,  3.750) = 3370 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      3.217 ms/op
     p(99.9000) =     12.984 ms/op
     p(99.9900) =     13.083 ms/op
     p(99.9990) =     13.091 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.130 ms/op
Iteration   1: 3.266 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   3.113 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9797
  mean =      3.266 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2141 
    [ 2.500,  3.750) = 5116 
    [ 3.750,  5.000) = 2186 
    [ 5.000,  6.250) = 224 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.356          ops/ms
ClientSimple.existUser                       thrpt         12.027          ops/ms
ClientSimple.getUser                         thrpt         13.085          ops/ms
ClientSimple.listUser                        thrpt          8.222          ops/ms
ClientSimple.createUser                       avgt          2.151           ms/op
ClientSimple.existUser                        avgt          1.797           ms/op
ClientSimple.getUser                          avgt          2.162           ms/op
ClientSimple.listUser                         avgt          3.181           ms/op
ClientSimple.createUser                     sample  13851   2.305 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.765           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.042           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.050           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.594           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.570           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.671           ms/op
ClientSimple.existUser                      sample  18937   1.696 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.540           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.624           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.907           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.134           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.383           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.305           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.602           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.631           ms/op
ClientSimple.getUser                        sample  14771   2.196 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.442           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.114           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.217           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.984           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.083           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.091           ms/op
ClientSimple.listUser                       sample   9797   3.266 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.452           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.113           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.129           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.382           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.498           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.596           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.596           ms/op

Benchmark result is saved to 1715040919632.json
