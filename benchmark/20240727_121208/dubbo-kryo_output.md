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
# Warmup Iteration   1: 1.863 ops/ms
Iteration   1: 7.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.051 ops/ms


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
# Warmup Iteration   1: 5.847 ops/ms
Iteration   1: 12.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.704 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.977 ops/ms
Iteration   1: 11.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.998 ops/ms


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
# Warmup Iteration   1: 5.247 ops/ms
Iteration   1: 8.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.560 ops/ms


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.057 ms/op
Iteration   1: 2.138 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.138 ms/op


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
# Warmup Iteration   1: 3.160 ±(99.9%) 0.051 ms/op
Iteration   1: 1.824 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.824 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.057 ms/op
Iteration   1: 2.006 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.006 ms/op


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.086 ms/op
Iteration   1: 3.625 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.625 ms/op


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.118 ms/op
Iteration   1: 2.616 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   2.449 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   10.617 ms/op
                 createUser·p0.999:  29.229 ms/op
                 createUser·p0.9999: 29.884 ms/op
                 createUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12132
  mean =      2.616 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6662 
    [ 2.500,  5.000) = 5106 
    [ 5.000,  7.500) = 149 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     29.229 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     29.884 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.084 ms/op
Iteration   1: 2.044 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.492 ms/op
                 existUser·p0.50:   2.013 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  12.419 ms/op
                 existUser·p0.9999: 12.530 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15639
  mean =      2.044 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 629 
    [ 1.250,  2.500) = 12940 
    [ 2.500,  3.750) = 1928 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     12.530 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.074 ms/op
Iteration   1: 1.988 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.212 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.514 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   3.166 ms/op
                 getUser·p0.999:  4.366 ms/op
                 getUser·p0.9999: 4.569 ms/op
                 getUser·p1.00:   4.653 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16061
  mean =      1.988 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 9 
    [0.500, 1.000) = 53 
    [1.000, 1.500) = 1598 
    [1.500, 2.000) = 6850 
    [2.000, 2.500) = 5860 
    [2.500, 3.000) = 1446 
    [3.000, 3.500) = 154 
    [3.500, 4.000) = 56 
    [4.000, 4.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.212 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.514 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.166 ms/op
     p(99.9000) =      4.366 ms/op
     p(99.9900) =      4.569 ms/op
     p(99.9990) =      4.653 ms/op
     p(99.9999) =      4.653 ms/op
    p(100.0000) =      4.653 ms/op


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.108 ms/op
Iteration   1: 3.358 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.314 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 13.631 ms/op
                 listUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9559
  mean =      3.358 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1583 
    [ 2.500,  3.750) = 4618 
    [ 3.750,  5.000) = 3084 
    [ 5.000,  6.250) = 201 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     13.631 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.051          ops/ms
ClientSimple.existUser                       thrpt         12.704          ops/ms
ClientSimple.getUser                         thrpt         11.998          ops/ms
ClientSimple.listUser                        thrpt          8.560          ops/ms
ClientSimple.createUser                       avgt          2.138           ms/op
ClientSimple.existUser                        avgt          1.824           ms/op
ClientSimple.getUser                          avgt          2.006           ms/op
ClientSimple.listUser                         avgt          3.625           ms/op
ClientSimple.createUser                     sample  12132   2.616 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.782           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.974           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.490           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.617           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.229           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.884           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.884           ms/op
ClientSimple.existUser                      sample  15639   2.044 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.492           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.013           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.580           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.419           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.530           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.567           ms/op
ClientSimple.getUser                        sample  16061   1.988 ± 0.011   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.212           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.514           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.166           ms/op
ClientSimple.getUser:getUser·p0.999         sample          4.366           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          4.569           ms/op
ClientSimple.getUser:getUser·p1.00          sample          4.653           ms/op
ClientSimple.listUser                       sample   9559   3.358 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.087           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.314           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.743           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.500           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.631           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.631           ms/op

Benchmark result is saved to 1722082070504.json
