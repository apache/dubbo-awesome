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
# Warmup Iteration   1: 1.946 ops/ms
Iteration   1: 7.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.599 ops/ms


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
# Warmup Iteration   1: 4.808 ops/ms
Iteration   1: 12.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.150 ops/ms


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
# Warmup Iteration   1: 5.028 ops/ms
Iteration   1: 11.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.467 ops/ms


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
# Warmup Iteration   1: 4.314 ops/ms
Iteration   1: 8.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.894 ops/ms


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.089 ms/op
Iteration   1: 2.107 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.107 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.053 ms/op
Iteration   1: 2.066 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.066 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.048 ms/op
Iteration   1: 2.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.037 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.101 ms/op
Iteration   1: 3.125 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.125 ms/op


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
# Warmup Iteration   1: 3.665 ±(99.9%) 0.102 ms/op
Iteration   1: 2.075 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   1.862 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.757 ms/op
                 createUser·p0.99:   5.332 ms/op
                 createUser·p0.999:  31.673 ms/op
                 createUser·p0.9999: 34.210 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15412
  mean =      2.075 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13657 
    [ 2.500,  5.000) = 1563 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      5.332 ms/op
     p(99.9000) =     31.673 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 3.287 ±(99.9%) 0.090 ms/op
Iteration   1: 2.086 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   1.939 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.884 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  12.659 ms/op
                 existUser·p0.9999: 14.279 ms/op
                 existUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15358
  mean =      2.086 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 227 
    [ 1.250,  2.500) = 13463 
    [ 2.500,  3.750) = 1304 
    [ 3.750,  5.000) = 152 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     12.659 ms/op
     p(99.9900) =     14.279 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.081 ms/op
Iteration   1: 1.825 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   1.731 ms/op
                 getUser·p0.90:   2.171 ms/op
                 getUser·p0.95:   2.359 ms/op
                 getUser·p0.99:   2.888 ms/op
                 getUser·p0.999:  16.351 ms/op
                 getUser·p0.9999: 16.732 ms/op
                 getUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17534
  mean =      1.825 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 16946 
    [ 2.500,  3.750) = 432 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      2.888 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     16.732 ms/op
     p(99.9990) =     16.744 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.151 ms/op
Iteration   1: 3.356 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.412 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.717 ms/op
                 listUser·p0.999:  16.715 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9708
  mean =      3.356 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 1781 
    [ 2.500,  3.750) = 4694 
    [ 3.750,  5.000) = 3026 
    [ 5.000,  6.250) = 130 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.717 ms/op
     p(99.9000) =     16.715 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.599          ops/ms
ClientSimple.existUser                       thrpt         12.150          ops/ms
ClientSimple.getUser                         thrpt         11.467          ops/ms
ClientSimple.listUser                        thrpt          8.894          ops/ms
ClientSimple.createUser                       avgt          2.107           ms/op
ClientSimple.existUser                        avgt          2.066           ms/op
ClientSimple.getUser                          avgt          2.037           ms/op
ClientSimple.listUser                         avgt          3.125           ms/op
ClientSimple.createUser                     sample  15412   2.075 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.732           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.862           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.332           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.673           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.210           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.210           ms/op
ClientSimple.existUser                      sample  15358   2.086 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.718           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.939           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.884           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.997           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.659           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.279           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.008           ms/op
ClientSimple.getUser                        sample  17534   1.825 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.729           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.731           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.171           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.359           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.351           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.732           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.744           ms/op
ClientSimple.listUser                       sample   9708   3.356 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.961           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.412           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.717           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.715           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.988           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.988           ms/op

Benchmark result is saved to 1714176892521.json
