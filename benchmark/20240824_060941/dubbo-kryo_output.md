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
# Warmup Iteration   1: 1.683 ops/ms
Iteration   1: 6.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.507 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.130 ops/ms
Iteration   1: 14.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.054 ops/ms


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
# Warmup Iteration   1: 5.109 ops/ms
Iteration   1: 11.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.527 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.931 ops/ms
Iteration   1: 8.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.311 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.244 ±(99.9%) 0.095 ms/op
Iteration   1: 1.992 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.992 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.069 ms/op
Iteration   1: 1.992 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.992 ms/op


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.071 ms/op
Iteration   1: 2.419 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.419 ms/op


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
# Warmup Iteration   1: 5.812 ±(99.9%) 0.115 ms/op
Iteration   1: 4.099 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.099 ms/op


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.109 ms/op
Iteration   1: 2.223 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   7.872 ms/op
                 createUser·p0.999:  37.906 ms/op
                 createUser·p0.9999: 39.892 ms/op
                 createUser·p1.00:   40.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14601
  mean =      2.223 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14289 
    [ 5.000, 10.000) = 236 
    [10.000, 15.000) = 7 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 38 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      7.872 ms/op
     p(99.9000) =     37.906 ms/op
     p(99.9900) =     39.892 ms/op
     p(99.9990) =     40.042 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


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
# Warmup Iteration   1: 3.558 ±(99.9%) 0.084 ms/op
Iteration   1: 1.972 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   1.896 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 12.693 ms/op
                 existUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16281
  mean =      1.972 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 502 
    [ 1.250,  2.500) = 14512 
    [ 2.500,  3.750) = 1050 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     12.693 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.107 ms/op
Iteration   1: 2.035 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   1.804 ms/op
                 getUser·p0.90:   2.814 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.742 ms/op
                 getUser·p0.999:  12.321 ms/op
                 getUser·p0.9999: 13.151 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15810
  mean =      2.035 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 13327 
    [ 2.500,  3.750) = 2024 
    [ 3.750,  5.000) = 212 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.742 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     13.151 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.130 ms/op
Iteration   1: 3.374 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.642 ms/op
                 listUser·p0.99:   6.653 ms/op
                 listUser·p0.999:  19.252 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9487
  mean =      3.374 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 739 
    [ 2.500,  3.750) = 5825 
    [ 3.750,  5.000) = 2602 
    [ 5.000,  6.250) = 151 
    [ 6.250,  7.500) = 127 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.642 ms/op
     p(99.0000) =      6.653 ms/op
     p(99.9000) =     19.252 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.507          ops/ms
ClientSimple.existUser                       thrpt         14.054          ops/ms
ClientSimple.getUser                         thrpt         11.527          ops/ms
ClientSimple.listUser                        thrpt          8.311          ops/ms
ClientSimple.createUser                       avgt          1.992           ms/op
ClientSimple.existUser                        avgt          1.992           ms/op
ClientSimple.getUser                          avgt          2.419           ms/op
ClientSimple.listUser                         avgt          4.099           ms/op
ClientSimple.createUser                     sample  14601   2.223 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.613           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.084           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.872           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.906           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.892           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.042           ms/op
ClientSimple.existUser                      sample  16281   1.972 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.566           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.896           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.211           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.517           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.693           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.714           ms/op
ClientSimple.getUser                        sample  15810   2.035 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.702           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.804           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.183           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.742           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.321           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.151           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.189           ms/op
ClientSimple.listUser                       sample   9487   3.374 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.956           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.002           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.642           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.653           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.252           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.595           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.595           ms/op

Benchmark result is saved to 1724479527852.json
