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
# Warmup Iteration   1: 1.854 ops/ms
Iteration   1: 6.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.303 ops/ms


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
# Warmup Iteration   1: 6.224 ops/ms
Iteration   1: 12.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.488 ops/ms


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
# Warmup Iteration   1: 5.943 ops/ms
Iteration   1: 12.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.512 ops/ms


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
# Warmup Iteration   1: 5.303 ops/ms
Iteration   1: 8.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.237 ops/ms


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
# Warmup Iteration   1: 4.853 ±(99.9%) 0.118 ms/op
Iteration   1: 2.327 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.327 ms/op


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
# Warmup Iteration   1: 3.218 ±(99.9%) 0.050 ms/op
Iteration   1: 2.148 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.148 ms/op


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
# Warmup Iteration   1: 3.086 ±(99.9%) 0.064 ms/op
Iteration   1: 2.298 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.298 ms/op


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.098 ms/op
Iteration   1: 3.284 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.284 ms/op


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.136 ms/op
Iteration   1: 2.251 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   2.023 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   3.063 ms/op
                 createUser·p0.99:   9.240 ms/op
                 createUser·p0.999:  22.544 ms/op
                 createUser·p0.9999: 26.383 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14201
  mean =      2.251 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12486 
    [ 2.500,  5.000) = 1375 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      3.063 ms/op
     p(99.0000) =      9.240 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     26.383 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.080 ms/op
Iteration   1: 2.056 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.290 ms/op
                 existUser·p0.50:   1.974 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.879 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  14.309 ms/op
                 existUser·p0.9999: 15.402 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15540
  mean =      2.056 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 674 
    [ 1.250,  2.500) = 12904 
    [ 2.500,  3.750) = 1609 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.290 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     14.309 ms/op
     p(99.9900) =     15.402 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.197 ms/op
Iteration   1: 2.331 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.253 ms/op
                 getUser·p0.90:   2.798 ms/op
                 getUser·p0.95:   2.961 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  13.112 ms/op
                 getUser·p0.9999: 13.324 ms/op
                 getUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13718
  mean =      2.331 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 9823 
    [ 2.500,  3.750) = 3672 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =     13.112 ms/op
     p(99.9900) =     13.324 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


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
# Warmup Iteration   1: 4.389 ±(99.9%) 0.118 ms/op
Iteration   1: 3.202 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.678 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.112 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9992
  mean =      3.202 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 1719 
    [ 2.500,  3.750) = 5983 
    [ 3.750,  5.000) = 2088 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.112 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.303          ops/ms
ClientSimple.existUser                       thrpt         12.488          ops/ms
ClientSimple.getUser                         thrpt         12.512          ops/ms
ClientSimple.listUser                        thrpt          8.237          ops/ms
ClientSimple.createUser                       avgt          2.327           ms/op
ClientSimple.existUser                        avgt          2.148           ms/op
ClientSimple.getUser                          avgt          2.298           ms/op
ClientSimple.listUser                         avgt          3.284           ms/op
ClientSimple.createUser                     sample  14201   2.251 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.552           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.023           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.063           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.240           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.544           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.383           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.411           ms/op
ClientSimple.existUser                      sample  15540   2.056 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.290           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.974           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.879           ms/op
ClientSimple.existUser:existUser·p0.99      sample          7.545           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.309           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.402           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.892           ms/op
ClientSimple.getUser                        sample  13718   2.331 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.822           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.253           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.961           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.186           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.112           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.324           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.337           ms/op
ClientSimple.listUser                       sample   9992   3.202 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.678           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.112           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.448           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.562           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.562           ms/op

Benchmark result is saved to 1716573947227.json
