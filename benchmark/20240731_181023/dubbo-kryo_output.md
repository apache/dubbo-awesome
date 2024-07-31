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
# Warmup Iteration   1: 1.739 ops/ms
Iteration   1: 6.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.530 ops/ms


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
# Warmup Iteration   1: 6.980 ops/ms
Iteration   1: 13.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.967 ops/ms


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
# Warmup Iteration   1: 5.790 ops/ms
Iteration   1: 13.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.633 ops/ms


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
# Warmup Iteration   1: 5.757 ops/ms
Iteration   1: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.380 ops/ms


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.076 ms/op
Iteration   1: 2.333 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.333 ms/op


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
# Warmup Iteration   1: 3.010 ±(99.9%) 0.059 ms/op
Iteration   1: 1.899 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.899 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.062 ms/op
Iteration   1: 1.966 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.966 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.104 ms/op
Iteration   1: 3.312 ±(99.9%) 0.013 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.438 ±(99.9%) 0.093 ms/op
Iteration   1: 2.156 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   1.923 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   2.990 ms/op
                 createUser·p0.99:   7.966 ms/op
                 createUser·p0.999:  18.195 ms/op
                 createUser·p0.9999: 18.514 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14818
  mean =      2.156 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 287 
    [ 1.250,  2.500) = 12601 
    [ 2.500,  3.750) = 1407 
    [ 3.750,  5.000) = 169 
    [ 5.000,  6.250) = 160 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      7.966 ms/op
     p(99.9000) =     18.195 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 3.050 ±(99.9%) 0.073 ms/op
Iteration   1: 1.718 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   1.659 ms/op
                 existUser·p0.90:   2.032 ms/op
                 existUser·p0.95:   2.183 ms/op
                 existUser·p0.99:   2.646 ms/op
                 existUser·p0.999:  12.173 ms/op
                 existUser·p0.9999: 12.701 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18597
  mean =      1.718 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 478 
    [ 1.250,  2.500) = 17821 
    [ 2.500,  3.750) = 210 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      1.659 ms/op
     p(90.0000) =      2.032 ms/op
     p(95.0000) =      2.183 ms/op
     p(99.0000) =      2.646 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     12.701 ms/op
     p(99.9990) =     13.124 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.086 ms/op
Iteration   1: 2.142 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.521 ms/op
                 getUser·p0.50:   2.054 ms/op
                 getUser·p0.90:   2.658 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   3.636 ms/op
                 getUser·p0.999:  13.386 ms/op
                 getUser·p0.9999: 14.099 ms/op
                 getUser·p1.00:   14.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14921
  mean =      2.142 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 11874 
    [ 2.500,  3.750) = 2808 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.636 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     14.099 ms/op
     p(99.9990) =     14.156 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.139 ms/op
Iteration   1: 3.391 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.453 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  6.324 ms/op
                 listUser·p0.9999: 8.135 ms/op
                 listUser·p1.00:   8.135 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9408
  mean =      3.391 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 147 
    [2.000, 2.500) = 1008 
    [2.500, 3.000) = 1976 
    [3.000, 3.500) = 1792 
    [3.500, 4.000) = 2521 
    [4.000, 4.500) = 1419 
    [4.500, 5.000) = 296 
    [5.000, 5.500) = 107 
    [5.500, 6.000) = 84 
    [6.000, 6.500) = 30 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      6.324 ms/op
     p(99.9900) =      8.135 ms/op
     p(99.9990) =      8.135 ms/op
     p(99.9999) =      8.135 ms/op
    p(100.0000) =      8.135 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.530          ops/ms
ClientSimple.existUser                       thrpt         13.967          ops/ms
ClientSimple.getUser                         thrpt         13.633          ops/ms
ClientSimple.listUser                        thrpt          8.380          ops/ms
ClientSimple.createUser                       avgt          2.333           ms/op
ClientSimple.existUser                        avgt          1.899           ms/op
ClientSimple.getUser                          avgt          1.966           ms/op
ClientSimple.listUser                         avgt          3.312           ms/op
ClientSimple.createUser                     sample  14818   2.156 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.705           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.923           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.990           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.966           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.195           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.514           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.514           ms/op
ClientSimple.existUser                      sample  18597   1.718 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.642           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.659           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.032           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.173           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.701           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.124           ms/op
ClientSimple.getUser                        sample  14921   2.142 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.521           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.054           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.636           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.386           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.099           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.156           ms/op
ClientSimple.listUser                       sample   9408   3.391 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.087           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.453           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.644           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.324           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.135           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.135           ms/op

Benchmark result is saved to 1722449161080.json
