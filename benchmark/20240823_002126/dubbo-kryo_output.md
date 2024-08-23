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
# Warmup Iteration   1: 1.035 ops/ms
Iteration   1: 6.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.456 ops/ms


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
# Warmup Iteration   1: 5.428 ops/ms
Iteration   1: 12.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.063 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.725 ops/ms
Iteration   1: 12.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.459 ops/ms


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
# Warmup Iteration   1: 4.753 ops/ms
Iteration   1: 8.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.479 ops/ms


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.071 ms/op
Iteration   1: 2.213 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.213 ms/op


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
# Warmup Iteration   1: 3.410 ±(99.9%) 0.055 ms/op
Iteration   1: 1.980 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.980 ms/op


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
# Warmup Iteration   1: 3.309 ±(99.9%) 0.061 ms/op
Iteration   1: 1.946 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.946 ms/op


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
# Warmup Iteration   1: 5.008 ±(99.9%) 0.108 ms/op
Iteration   1: 3.656 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.656 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.094 ms/op
Iteration   1: 2.146 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   1.911 ms/op
                 createUser·p0.90:   2.454 ms/op
                 createUser·p0.95:   2.837 ms/op
                 createUser·p0.99:   8.192 ms/op
                 createUser·p0.999:  18.547 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14906
  mean =      2.146 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 241 
    [ 1.250,  2.500) = 13359 
    [ 2.500,  3.750) = 880 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.837 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.076 ms/op
Iteration   1: 1.789 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.062 ms/op
                 existUser·p0.95:   2.212 ms/op
                 existUser·p0.99:   2.798 ms/op
                 existUser·p0.999:  13.959 ms/op
                 existUser·p0.9999: 15.493 ms/op
                 existUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17898
  mean =      1.789 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 17455 
    [ 2.500,  3.750) = 195 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.062 ms/op
     p(95.0000) =      2.212 ms/op
     p(99.0000) =      2.798 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     15.493 ms/op
     p(99.9990) =     15.532 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 3.280 ±(99.9%) 0.084 ms/op
Iteration   1: 1.764 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   1.610 ms/op
                 getUser·p0.90:   2.134 ms/op
                 getUser·p0.95:   2.507 ms/op
                 getUser·p0.99:   3.330 ms/op
                 getUser·p0.999:  22.081 ms/op
                 getUser·p0.9999: 22.825 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18146
  mean =      1.764 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17235 
    [ 2.500,  5.000) = 814 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      1.610 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.330 ms/op
     p(99.9000) =     22.081 ms/op
     p(99.9900) =     22.825 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 4.787 ±(99.9%) 0.167 ms/op
Iteration   1: 3.364 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   0.553 ms/op
                 listUser·p0.50:   3.224 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.540 ms/op
                 listUser·p0.999:  27.754 ms/op
                 listUser·p0.9999: 28.508 ms/op
                 listUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9573
  mean =      3.364 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 991 
    [ 2.500,  5.000) = 8407 
    [ 5.000,  7.500) = 110 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.540 ms/op
     p(99.9000) =     27.754 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.456          ops/ms
ClientSimple.existUser                       thrpt         12.063          ops/ms
ClientSimple.getUser                         thrpt         12.459          ops/ms
ClientSimple.listUser                        thrpt          8.479          ops/ms
ClientSimple.createUser                       avgt          2.213           ms/op
ClientSimple.existUser                        avgt          1.980           ms/op
ClientSimple.getUser                          avgt          1.946           ms/op
ClientSimple.listUser                         avgt          3.656           ms/op
ClientSimple.createUser                     sample  14906   2.146 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.582           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.911           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.837           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.192           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.547           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.562           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.562           ms/op
ClientSimple.existUser                      sample  17898   1.789 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.534           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.062           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.798           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.959           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.493           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.532           ms/op
ClientSimple.getUser                        sample  18146   1.764 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.659           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.610           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.134           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.330           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.081           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.825           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.905           ms/op
ClientSimple.listUser                       sample   9573   3.364 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.553           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.224           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.076           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.540           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.754           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.508           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.508           ms/op

Benchmark result is saved to 1724372217966.json
