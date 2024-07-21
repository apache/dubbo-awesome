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
# Warmup Iteration   1: 1.678 ops/ms
Iteration   1: 5.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.717 ops/ms


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
# Warmup Iteration   1: 5.247 ops/ms
Iteration   1: 11.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.050 ops/ms


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
# Warmup Iteration   1: 5.452 ops/ms
Iteration   1: 12.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.620 ops/ms


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
# Warmup Iteration   1: 4.621 ops/ms
Iteration   1: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.179 ops/ms


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.077 ms/op
Iteration   1: 2.323 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.323 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.061 ms/op
Iteration   1: 1.974 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.055 ms/op
Iteration   1: 2.288 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.288 ms/op


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
# Warmup Iteration   1: 4.432 ±(99.9%) 0.079 ms/op
Iteration   1: 3.433 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.433 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.077 ms/op
Iteration   1: 2.278 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.358 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.896 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   11.600 ms/op
                 createUser·p0.999:  24.052 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14031
  mean =      2.278 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10895 
    [ 2.500,  5.000) = 2833 
    [ 5.000,  7.500) = 141 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.351 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 3.054 ±(99.9%) 0.074 ms/op
Iteration   1: 1.713 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   1.495 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  12.162 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18670
  mean =      1.713 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1007 
    [ 1.250,  2.500) = 16632 
    [ 2.500,  3.750) = 844 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      1.495 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =     12.162 ms/op
     p(99.9900) =     12.386 ms/op
     p(99.9990) =     12.386 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.083 ms/op
Iteration   1: 2.021 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   1.903 ms/op
                 getUser·p0.90:   2.367 ms/op
                 getUser·p0.95:   2.621 ms/op
                 getUser·p0.99:   4.103 ms/op
                 getUser·p0.999:  21.928 ms/op
                 getUser·p0.9999: 23.353 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15815
  mean =      2.021 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14733 
    [ 2.500,  5.000) = 981 
    [ 5.000,  7.500) = 26 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      4.103 ms/op
     p(99.9000) =     21.928 ms/op
     p(99.9900) =     23.353 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 4.930 ±(99.9%) 0.136 ms/op
Iteration   1: 3.509 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.396 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   5.980 ms/op
                 listUser·p0.999:  7.566 ms/op
                 listUser·p0.9999: 8.503 ms/op
                 listUser·p1.00:   8.503 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9119
  mean =      3.509 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 80 
    [2.000, 2.500) = 170 
    [2.500, 3.000) = 2756 
    [3.000, 3.500) = 1883 
    [3.500, 4.000) = 1945 
    [4.000, 4.500) = 1562 
    [4.500, 5.000) = 412 
    [5.000, 5.500) = 139 
    [5.500, 6.000) = 81 
    [6.000, 6.500) = 46 
    [6.500, 7.000) = 13 
    [7.000, 7.500) = 14 
    [7.500, 8.000) = 7 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =      7.566 ms/op
     p(99.9900) =      8.503 ms/op
     p(99.9990) =      8.503 ms/op
     p(99.9999) =      8.503 ms/op
    p(100.0000) =      8.503 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.717          ops/ms
ClientSimple.existUser                       thrpt         11.050          ops/ms
ClientSimple.getUser                         thrpt         12.620          ops/ms
ClientSimple.listUser                        thrpt          8.179          ops/ms
ClientSimple.createUser                       avgt          2.323           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.288           ms/op
ClientSimple.listUser                         avgt          3.433           ms/op
ClientSimple.createUser                     sample  14031   2.278 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.358           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.351           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.600           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.052           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.183           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.183           ms/op
ClientSimple.existUser                      sample  18670   1.713 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.929           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.495           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.756           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.162           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.386           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.386           ms/op
ClientSimple.getUser                        sample  15815   2.021 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.538           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.903           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.367           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.103           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.928           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.353           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.429           ms/op
ClientSimple.listUser                       sample   9119   3.509 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.092           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.396           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.980           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.566           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.503           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.503           ms/op

Benchmark result is saved to 1721563615567.json
