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
# Warmup Iteration   1: 1.578 ops/ms
Iteration   1: 6.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.576 ops/ms


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
# Warmup Iteration   1: 5.905 ops/ms
Iteration   1: 13.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.385 ops/ms


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
# Warmup Iteration   1: 4.974 ops/ms
Iteration   1: 11.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.521 ops/ms


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
# Warmup Iteration   1: 5.253 ops/ms
Iteration   1: 9.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.646 ops/ms


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.059 ms/op
Iteration   1: 2.215 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.215 ms/op


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
# Warmup Iteration   1: 2.989 ±(99.9%) 0.046 ms/op
Iteration   1: 1.856 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.856 ms/op


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
# Warmup Iteration   1: 3.475 ±(99.9%) 0.059 ms/op
Iteration   1: 1.992 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.992 ms/op


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.107 ms/op
Iteration   1: 3.137 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.137 ms/op


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
# Warmup Iteration   1: 3.214 ±(99.9%) 0.089 ms/op
Iteration   1: 2.137 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.383 ms/op
                 createUser·p0.50:   1.968 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.896 ms/op
                 createUser·p0.99:   8.045 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 19.513 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15198
  mean =      2.137 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 13206 
    [ 2.500,  3.750) = 964 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 111 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     19.513 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 2.963 ±(99.9%) 0.068 ms/op
Iteration   1: 1.950 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.447 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   4.795 ms/op
                 existUser·p0.999:  20.480 ms/op
                 existUser·p0.9999: 20.843 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16585
  mean =      1.950 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15806 
    [ 2.500,  5.000) = 627 
    [ 5.000,  7.500) = 79 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      4.795 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     20.843 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 3.507 ±(99.9%) 0.090 ms/op
Iteration   1: 1.874 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.608 ms/op
                 getUser·p0.50:   1.743 ms/op
                 getUser·p0.90:   2.458 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  11.221 ms/op
                 getUser·p0.9999: 12.054 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17129
  mean =      1.874 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 15241 
    [ 2.500,  3.750) = 1335 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =     11.221 ms/op
     p(99.9900) =     12.054 ms/op
     p(99.9990) =     12.206 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.145 ms/op
Iteration   1: 3.336 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.561 ms/op
                 listUser·p0.50:   3.283 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.676 ms/op
                 listUser·p0.99:   7.161 ms/op
                 listUser·p0.999:  9.804 ms/op
                 listUser·p0.9999: 10.027 ms/op
                 listUser·p1.00:   10.027 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9584
  mean =      3.336 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 66 
    [ 2.000,  3.000) = 4093 
    [ 3.000,  4.000) = 3839 
    [ 4.000,  5.000) = 1249 
    [ 5.000,  6.000) = 105 
    [ 6.000,  7.000) = 124 
    [ 7.000,  8.000) = 40 
    [ 8.000,  9.000) = 44 
    [ 9.000, 10.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.283 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.676 ms/op
     p(99.0000) =      7.161 ms/op
     p(99.9000) =      9.804 ms/op
     p(99.9900) =     10.027 ms/op
     p(99.9990) =     10.027 ms/op
     p(99.9999) =     10.027 ms/op
    p(100.0000) =     10.027 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.576          ops/ms
ClientSimple.existUser                       thrpt         13.385          ops/ms
ClientSimple.getUser                         thrpt         11.521          ops/ms
ClientSimple.listUser                        thrpt          9.646          ops/ms
ClientSimple.createUser                       avgt          2.215           ms/op
ClientSimple.existUser                        avgt          1.856           ms/op
ClientSimple.getUser                          avgt          1.992           ms/op
ClientSimple.listUser                         avgt          3.137           ms/op
ClientSimple.createUser                     sample  15198   2.137 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.383           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.968           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.045           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.383           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.513           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.530           ms/op
ClientSimple.existUser                      sample  16585   1.950 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.447           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.815           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.795           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.480           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.843           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.037           ms/op
ClientSimple.getUser                        sample  17129   1.874 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.608           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.743           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.871           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.221           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.054           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.206           ms/op
ClientSimple.listUser                       sample   9584   3.336 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.561           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.283           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.676           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.161           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.804           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.027           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.027           ms/op

Benchmark result is saved to 1715882693860.json
