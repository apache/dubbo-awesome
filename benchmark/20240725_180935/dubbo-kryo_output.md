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
# Warmup Iteration   1: 1.770 ops/ms
Iteration   1: 7.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.736 ops/ms


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
# Warmup Iteration   1: 5.061 ops/ms
Iteration   1: 11.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.100 ops/ms


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
# Warmup Iteration   1: 5.662 ops/ms
Iteration   1: 12.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.426 ops/ms


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
# Warmup Iteration   1: 4.444 ops/ms
Iteration   1: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.189 ops/ms


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.106 ms/op
Iteration   1: 2.157 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.157 ms/op


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
# Warmup Iteration   1: 2.989 ±(99.9%) 0.052 ms/op
Iteration   1: 1.787 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.787 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.054 ms/op
Iteration   1: 2.035 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.035 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.102 ms/op
Iteration   1: 3.311 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.311 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.092 ms/op
Iteration   1: 2.460 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   2.306 ms/op
                 createUser·p0.90:   2.916 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  18.057 ms/op
                 createUser·p0.9999: 19.556 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12983
  mean =      2.460 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 8304 
    [ 2.500,  3.750) = 4272 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.306 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     18.057 ms/op
     p(99.9900) =     19.556 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 3.408 ±(99.9%) 0.085 ms/op
Iteration   1: 2.162 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   2.075 ms/op
                 existUser·p0.90:   2.527 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  24.878 ms/op
                 existUser·p0.9999: 25.626 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14797
  mean =      2.162 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13160 
    [ 2.500,  5.000) = 1504 
    [ 5.000,  7.500) = 67 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     24.878 ms/op
     p(99.9900) =     25.626 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 3.248 ±(99.9%) 0.081 ms/op
Iteration   1: 2.067 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   1.987 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   3.478 ms/op
                 getUser·p0.999:  13.279 ms/op
                 getUser·p0.9999: 13.628 ms/op
                 getUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15486
  mean =      2.067 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 13508 
    [ 2.500,  3.750) = 1738 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 87 
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
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.478 ms/op
     p(99.9000) =     13.279 ms/op
     p(99.9900) =     13.628 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.135 ms/op
Iteration   1: 3.750 ±(99.9%) 0.094 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.066 ms/op
                 listUser·p0.999:  46.989 ms/op
                 listUser·p0.9999: 49.283 ms/op
                 listUser·p1.00:   49.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8524
  mean =      3.750 ±(99.9%) 0.094 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8291 
    [ 5.000, 10.000) = 194 
    [10.000, 15.000) = 4 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.066 ms/op
     p(99.9000) =     46.989 ms/op
     p(99.9900) =     49.283 ms/op
     p(99.9990) =     49.283 ms/op
     p(99.9999) =     49.283 ms/op
    p(100.0000) =     49.283 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.736          ops/ms
ClientSimple.existUser                       thrpt         11.100          ops/ms
ClientSimple.getUser                         thrpt         12.426          ops/ms
ClientSimple.listUser                        thrpt          8.189          ops/ms
ClientSimple.createUser                       avgt          2.157           ms/op
ClientSimple.existUser                        avgt          1.787           ms/op
ClientSimple.getUser                          avgt          2.035           ms/op
ClientSimple.listUser                         avgt          3.311           ms/op
ClientSimple.createUser                     sample  12983   2.460 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.596           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.306           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.142           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.765           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.057           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.556           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.595           ms/op
ClientSimple.existUser                      sample  14797   2.162 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.561           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.075           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.798           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.293           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.878           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.626           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.657           ms/op
ClientSimple.getUser                        sample  15486   2.067 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.743           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.987           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.478           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.279           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.628           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.664           ms/op
ClientSimple.listUser                       sample   8524   3.750 ± 0.094   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.124           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.641           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.066           ms/op
ClientSimple.listUser:listUser·p0.999       sample         46.989           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         49.283           ms/op
ClientSimple.listUser:listUser·p1.00        sample         49.283           ms/op

Benchmark result is saved to 1721930716135.json
