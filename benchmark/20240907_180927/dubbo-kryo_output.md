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
# Warmup Iteration   1: 1.710 ops/ms
Iteration   1: 6.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.749 ops/ms


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
# Warmup Iteration   1: 6.749 ops/ms
Iteration   1: 12.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.916 ops/ms


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
# Warmup Iteration   1: 5.257 ops/ms
Iteration   1: 11.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.657 ops/ms


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
# Warmup Iteration   1: 4.035 ops/ms
Iteration   1: 9.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.257 ops/ms


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.066 ms/op
Iteration   1: 2.241 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.241 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.057 ms/op
Iteration   1: 1.777 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.777 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.053 ms/op
Iteration   1: 2.365 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.365 ms/op


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.088 ms/op
Iteration   1: 3.263 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.263 ms/op


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.106 ms/op
Iteration   1: 2.281 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.473 ms/op
                 createUser·p0.50:   2.126 ms/op
                 createUser·p0.90:   2.871 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   5.402 ms/op
                 createUser·p0.999:  16.499 ms/op
                 createUser·p0.9999: 16.843 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13997
  mean =      2.281 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 204 
    [ 1.250,  2.500) = 10235 
    [ 2.500,  3.750) = 3377 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      5.402 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 3.018 ±(99.9%) 0.059 ms/op
Iteration   1: 1.802 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.445 ms/op
                 existUser·p0.50:   1.714 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.501 ms/op
                 existUser·p0.99:   3.031 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 10.669 ms/op
                 existUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17865
  mean =      1.802 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 902 
    [ 1.250,  2.500) = 16070 
    [ 2.500,  3.750) = 815 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.501 ms/op
     p(99.0000) =      3.031 ms/op
     p(99.9000) =     10.125 ms/op
     p(99.9900) =     10.669 ms/op
     p(99.9990) =     10.863 ms/op
     p(99.9999) =     10.863 ms/op
    p(100.0000) =     10.863 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.478 ±(99.9%) 0.093 ms/op
Iteration   1: 1.985 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   1.849 ms/op
                 getUser·p0.90:   2.486 ms/op
                 getUser·p0.95:   2.795 ms/op
                 getUser·p0.99:   3.750 ms/op
                 getUser·p0.999:  13.912 ms/op
                 getUser·p0.9999: 14.813 ms/op
                 getUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16433
  mean =      1.985 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 14696 
    [ 2.500,  3.750) = 1436 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.795 ms/op
     p(99.0000) =      3.750 ms/op
     p(99.9000) =     13.912 ms/op
     p(99.9900) =     14.813 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.961 ±(99.9%) 0.179 ms/op
Iteration   1: 3.593 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8898
  mean =      3.593 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1056 
    [ 2.500,  3.750) = 4597 
    [ 3.750,  5.000) = 2836 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.749          ops/ms
ClientSimple.existUser                       thrpt         12.916          ops/ms
ClientSimple.getUser                         thrpt         11.657          ops/ms
ClientSimple.listUser                        thrpt          9.257          ops/ms
ClientSimple.createUser                       avgt          2.241           ms/op
ClientSimple.existUser                        avgt          1.777           ms/op
ClientSimple.getUser                          avgt          2.365           ms/op
ClientSimple.listUser                         avgt          3.263           ms/op
ClientSimple.createUser                     sample  13997   2.281 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.473           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.126           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.402           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.499           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.843           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.007           ms/op
ClientSimple.existUser                      sample  17865   1.802 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.445           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.714           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.501           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.031           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.125           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.669           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.863           ms/op
ClientSimple.getUser                        sample  16433   1.985 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.465           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.849           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.486           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.795           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.750           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.912           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.813           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.877           ms/op
ClientSimple.listUser                       sample   8898   3.593 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.253           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.539           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.682           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.219           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.448           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.448           ms/op

Benchmark result is saved to 1725732300625.json
