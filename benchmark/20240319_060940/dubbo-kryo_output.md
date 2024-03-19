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
# Warmup Iteration   1: 2.040 ops/ms
Iteration   1: 6.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.957 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.833 ops/ms
Iteration   1: 13.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.077 ops/ms


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
# Warmup Iteration   1: 6.000 ops/ms
Iteration   1: 13.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.965 ops/ms


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
# Warmup Iteration   1: 5.494 ops/ms
Iteration   1: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.371 ops/ms


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.072 ms/op
Iteration   1: 2.292 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.292 ms/op


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
# Warmup Iteration   1: 3.101 ±(99.9%) 0.057 ms/op
Iteration   1: 1.915 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.915 ms/op


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
# Warmup Iteration   1: 3.478 ±(99.9%) 0.057 ms/op
Iteration   1: 2.197 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.197 ms/op


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.105 ms/op
Iteration   1: 3.547 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.547 ms/op


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.094 ms/op
Iteration   1: 2.262 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   2.699 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   5.886 ms/op
                 createUser·p0.999:  20.185 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14173
  mean =      2.262 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11353 
    [ 2.500,  5.000) = 2586 
    [ 5.000,  7.500) = 102 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      5.886 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 2.993 ±(99.9%) 0.065 ms/op
Iteration   1: 1.787 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.223 ms/op
                 existUser·p0.50:   1.649 ms/op
                 existUser·p0.90:   1.962 ms/op
                 existUser·p0.95:   2.154 ms/op
                 existUser·p0.99:   3.023 ms/op
                 existUser·p0.999:  34.214 ms/op
                 existUser·p0.9999: 35.206 ms/op
                 existUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17941
  mean =      1.787 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17631 
    [ 2.500,  5.000) = 237 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.223 ms/op
     p(50.0000) =      1.649 ms/op
     p(90.0000) =      1.962 ms/op
     p(95.0000) =      2.154 ms/op
     p(99.0000) =      3.023 ms/op
     p(99.9000) =     34.214 ms/op
     p(99.9900) =     35.206 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 3.266 ±(99.9%) 0.095 ms/op
Iteration   1: 2.027 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.542 ms/op
                 getUser·p0.50:   1.925 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.691 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  15.351 ms/op
                 getUser·p0.9999: 15.669 ms/op
                 getUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16038
  mean =      2.027 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 231 
    [ 1.250,  2.500) = 14356 
    [ 2.500,  3.750) = 1229 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      4.948 ms/op
     p(99.9000) =     15.351 ms/op
     p(99.9900) =     15.669 ms/op
     p(99.9990) =     15.827 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.341 ±(99.9%) 0.124 ms/op
Iteration   1: 4.024 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.723 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7946
  mean =      4.024 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 213 
    [ 2.500,  3.750) = 2553 
    [ 3.750,  5.000) = 4498 
    [ 5.000,  6.250) = 547 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.957          ops/ms
ClientSimple.existUser                       thrpt         13.077          ops/ms
ClientSimple.getUser                         thrpt         13.965          ops/ms
ClientSimple.listUser                        thrpt          9.371          ops/ms
ClientSimple.createUser                       avgt          2.292           ms/op
ClientSimple.existUser                        avgt          1.915           ms/op
ClientSimple.getUser                          avgt          2.197           ms/op
ClientSimple.listUser                         avgt          3.547           ms/op
ClientSimple.createUser                     sample  14173   2.262 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.924           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.195           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.886           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.185           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.660           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.660           ms/op
ClientSimple.existUser                      sample  17941   1.787 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.223           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.649           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.962           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.154           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.023           ms/op
ClientSimple.existUser:existUser·p0.999     sample         34.214           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         35.206           ms/op
ClientSimple.existUser:existUser·p1.00      sample         35.258           ms/op
ClientSimple.getUser                        sample  16038   2.027 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.542           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.925           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.948           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.351           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.669           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.827           ms/op
ClientSimple.listUser                       sample   7946   4.024 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.723           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.018           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.218           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.988           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.088           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.874           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.874           ms/op

Benchmark result is saved to 1710828320239.json
