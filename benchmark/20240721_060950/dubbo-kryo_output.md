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
# Warmup Iteration   1: 1.820 ops/ms
Iteration   1: 7.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.471 ops/ms


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
# Warmup Iteration   1: 5.066 ops/ms
Iteration   1: 12.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.416 ops/ms


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
# Warmup Iteration   1: 5.118 ops/ms
Iteration   1: 12.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.301 ops/ms


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
# Warmup Iteration   1: 5.362 ops/ms
Iteration   1: 8.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.875 ops/ms


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.069 ms/op
Iteration   1: 2.026 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.026 ms/op


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
# Warmup Iteration   1: 3.436 ±(99.9%) 0.059 ms/op
Iteration   1: 1.987 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.987 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.059 ms/op
Iteration   1: 2.472 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.472 ms/op


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.086 ms/op
Iteration   1: 3.382 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.382 ms/op


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
# Warmup Iteration   1: 3.566 ±(99.9%) 0.094 ms/op
Iteration   1: 2.273 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.034 ms/op
                 createUser·p0.90:   2.683 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   6.024 ms/op
                 createUser·p0.999:  18.905 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14065
  mean =      2.273 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 11326 
    [ 2.500,  3.750) = 2456 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      6.024 ms/op
     p(99.9000) =     18.905 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 3.256 ±(99.9%) 0.082 ms/op
Iteration   1: 2.275 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.430 ms/op
                 existUser·p0.50:   2.171 ms/op
                 existUser·p0.90:   2.810 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  18.907 ms/op
                 existUser·p0.9999: 19.372 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14048
  mean =      2.275 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 391 
    [ 1.250,  2.500) = 10261 
    [ 2.500,  3.750) = 3072 
    [ 3.750,  5.000) = 178 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     19.372 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 3.403 ±(99.9%) 0.085 ms/op
Iteration   1: 2.092 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.507 ms/op
                 getUser·p0.50:   1.952 ms/op
                 getUser·p0.90:   2.671 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   3.203 ms/op
                 getUser·p0.999:  11.534 ms/op
                 getUser·p0.9999: 12.845 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15375
  mean =      2.092 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 210 
    [ 1.250,  2.500) = 12692 
    [ 2.500,  3.750) = 2409 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      3.203 ms/op
     p(99.9000) =     11.534 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


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
# Warmup Iteration   1: 4.848 ±(99.9%) 0.150 ms/op
Iteration   1: 3.394 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.450 ms/op
                 listUser·p0.999:  26.069 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9429
  mean =      3.394 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 778 
    [ 2.500,  5.000) = 8438 
    [ 5.000,  7.500) = 146 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.450 ms/op
     p(99.9000) =     26.069 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.471          ops/ms
ClientSimple.existUser                       thrpt         12.416          ops/ms
ClientSimple.getUser                         thrpt         12.301          ops/ms
ClientSimple.listUser                        thrpt          8.875          ops/ms
ClientSimple.createUser                       avgt          2.026           ms/op
ClientSimple.existUser                        avgt          1.987           ms/op
ClientSimple.getUser                          avgt          2.472           ms/op
ClientSimple.listUser                         avgt          3.382           ms/op
ClientSimple.createUser                     sample  14065   2.273 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.909           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.034           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.024           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.905           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.169           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.169           ms/op
ClientSimple.existUser                      sample  14048   2.275 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.430           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.031           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.079           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.907           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.372           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.399           ms/op
ClientSimple.getUser                        sample  15375   2.092 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.507           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.952           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.203           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.534           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.845           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.845           ms/op
ClientSimple.listUser                       sample   9429   3.394 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.071           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.068           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.450           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.069           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.739           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.739           ms/op

Benchmark result is saved to 1721541924001.json
