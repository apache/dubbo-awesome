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
# Warmup Iteration   1: 1.872 ops/ms
Iteration   1: 7.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.062 ops/ms


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
# Warmup Iteration   1: 5.596 ops/ms
Iteration   1: 12.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.665 ops/ms


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
# Warmup Iteration   1: 5.629 ops/ms
Iteration   1: 11.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.684 ops/ms


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
# Warmup Iteration   1: 4.764 ops/ms
Iteration   1: 10.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  10.091 ops/ms


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
# Warmup Iteration   1: 3.655 ±(99.9%) 0.081 ms/op
Iteration   1: 2.113 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.113 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.988 ±(99.9%) 0.051 ms/op
Iteration   1: 1.781 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.781 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.349 ±(99.9%) 0.056 ms/op
Iteration   1: 2.020 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.020 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.530 ±(99.9%) 0.099 ms/op
Iteration   1: 3.707 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.707 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.581 ±(99.9%) 0.112 ms/op
Iteration   1: 1.876 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   1.663 ms/op
                 createUser·p0.90:   2.418 ms/op
                 createUser·p0.95:   2.671 ms/op
                 createUser·p0.99:   4.938 ms/op
                 createUser·p0.999:  16.433 ms/op
                 createUser·p0.9999: 16.984 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17026
  mean =      1.876 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 395 
    [ 1.250,  2.500) = 15325 
    [ 2.500,  3.750) = 1068 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.418 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      4.938 ms/op
     p(99.9000) =     16.433 ms/op
     p(99.9900) =     16.984 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.976 ±(99.9%) 0.064 ms/op
Iteration   1: 1.994 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   1.915 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.728 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 13.828 ms/op
                 existUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16128
  mean =      1.994 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 296 
    [ 1.250,  2.500) = 14234 
    [ 2.500,  3.750) = 1492 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      3.383 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.078 ms/op
Iteration   1: 1.896 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   1.688 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   3.980 ms/op
                 getUser·p0.999:  16.421 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16884
  mean =      1.896 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 15439 
    [ 2.500,  3.750) = 1177 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.980 ms/op
     p(99.9000) =     16.421 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.115 ms/op
Iteration   1: 3.092 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   2.789 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.266 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 19.261 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10325
  mean =      3.092 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1934 
    [ 2.500,  3.750) = 7119 
    [ 3.750,  5.000) = 993 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.266 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.261 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.062          ops/ms
ClientSimple.existUser                       thrpt         12.665          ops/ms
ClientSimple.getUser                         thrpt         11.684          ops/ms
ClientSimple.listUser                        thrpt         10.091          ops/ms
ClientSimple.createUser                       avgt          2.113           ms/op
ClientSimple.existUser                        avgt          1.781           ms/op
ClientSimple.getUser                          avgt          2.020           ms/op
ClientSimple.listUser                         avgt          3.707           ms/op
ClientSimple.createUser                     sample  17026   1.876 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.793           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.663           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.418           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.938           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.433           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.984           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.007           ms/op
ClientSimple.existUser                      sample  16128   1.994 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.598           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.915           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.383           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.174           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.828           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.828           ms/op
ClientSimple.getUser                        sample  16884   1.896 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.782           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.688           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.980           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.421           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.941           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.941           ms/op
ClientSimple.listUser                       sample  10325   3.092 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.126           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.789           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.834           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.266           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.529           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.940           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.261           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.268           ms/op

Benchmark result is saved to 1714025128467.json
