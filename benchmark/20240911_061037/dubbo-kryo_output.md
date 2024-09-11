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
# Warmup Iteration   1: 1.882 ops/ms
Iteration   1: 8.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.328 ops/ms


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
# Warmup Iteration   1: 7.026 ops/ms
Iteration   1: 12.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.840 ops/ms


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
# Warmup Iteration   1: 5.408 ops/ms
Iteration   1: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.779 ops/ms


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
# Warmup Iteration   1: 5.461 ops/ms
Iteration   1: 8.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.613 ops/ms


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.061 ms/op
Iteration   1: 2.146 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.146 ms/op


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
# Warmup Iteration   1: 2.938 ±(99.9%) 0.047 ms/op
Iteration   1: 1.915 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.915 ms/op


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
# Warmup Iteration   1: 3.303 ±(99.9%) 0.053 ms/op
Iteration   1: 1.957 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.957 ms/op


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
# Warmup Iteration   1: 5.051 ±(99.9%) 0.103 ms/op
Iteration   1: 3.312 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.312 ms/op


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.089 ms/op
Iteration   1: 2.300 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.744 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   6.935 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 19.074 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13921
  mean =      2.300 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 10350 
    [ 2.500,  3.750) = 3165 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      6.935 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     19.074 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 2.883 ±(99.9%) 0.065 ms/op
Iteration   1: 1.737 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   1.593 ms/op
                 existUser·p0.90:   2.159 ms/op
                 existUser·p0.95:   2.318 ms/op
                 existUser·p0.99:   5.265 ms/op
                 existUser·p0.999:  14.123 ms/op
                 existUser·p0.9999: 14.718 ms/op
                 existUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18410
  mean =      1.737 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1097 
    [ 1.250,  2.500) = 16846 
    [ 2.500,  3.750) = 274 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      1.593 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.318 ms/op
     p(99.0000) =      5.265 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     14.718 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 3.235 ±(99.9%) 0.071 ms/op
Iteration   1: 1.955 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   1.786 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   3.466 ms/op
                 getUser·p0.999:  18.416 ms/op
                 getUser·p0.9999: 19.781 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16669
  mean =      1.955 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 186 
    [ 1.250,  2.500) = 14746 
    [ 2.500,  3.750) = 1610 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.466 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     19.781 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.115 ms/op
Iteration   1: 3.184 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.972 ms/op
                 listUser·p0.999:  12.254 ms/op
                 listUser·p0.9999: 12.370 ms/op
                 listUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10049
  mean =      3.184 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1717 
    [ 2.500,  3.750) = 6396 
    [ 3.750,  5.000) = 1697 
    [ 5.000,  6.250) = 155 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     12.254 ms/op
     p(99.9900) =     12.370 ms/op
     p(99.9990) =     12.370 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.328          ops/ms
ClientSimple.existUser                       thrpt         12.840          ops/ms
ClientSimple.getUser                         thrpt         12.779          ops/ms
ClientSimple.listUser                        thrpt          8.613          ops/ms
ClientSimple.createUser                       avgt          2.146           ms/op
ClientSimple.existUser                        avgt          1.915           ms/op
ClientSimple.getUser                          avgt          1.957           ms/op
ClientSimple.listUser                         avgt          3.312           ms/op
ClientSimple.createUser                     sample  13921   2.300 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.612           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.935           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.990           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.074           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.202           ms/op
ClientSimple.existUser                      sample  18410   1.737 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.522           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.593           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.159           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.265           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.123           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.718           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.746           ms/op
ClientSimple.getUser                        sample  16669   1.955 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.760           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.786           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.466           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.416           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.781           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.825           ms/op
ClientSimple.listUser                       sample  10049   3.184 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.890           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.023           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.035           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.972           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.254           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.370           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.370           ms/op

Benchmark result is saved to 1726034782797.json
