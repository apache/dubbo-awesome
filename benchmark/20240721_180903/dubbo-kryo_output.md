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
# Warmup Iteration   1: 1.823 ops/ms
Iteration   1: 6.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.243 ops/ms


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
# Warmup Iteration   1: 5.184 ops/ms
Iteration   1: 11.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.265 ops/ms


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
# Warmup Iteration   1: 5.782 ops/ms
Iteration   1: 12.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.472 ops/ms


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
# Warmup Iteration   1: 5.652 ops/ms
Iteration   1: 8.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.223 ops/ms


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.087 ms/op
Iteration   1: 2.488 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.488 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.054 ms/op
Iteration   1: 2.070 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.070 ms/op


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
# Warmup Iteration   1: 3.214 ±(99.9%) 0.052 ms/op
Iteration   1: 2.215 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.215 ms/op


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.083 ms/op
Iteration   1: 3.492 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.492 ms/op


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.109 ms/op
Iteration   1: 2.195 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   1.991 ms/op
                 createUser·p0.90:   2.798 ms/op
                 createUser·p0.95:   2.998 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  21.474 ms/op
                 createUser·p0.9999: 21.791 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14650
  mean =      2.195 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11765 
    [ 2.500,  5.000) = 2663 
    [ 5.000,  7.500) = 70 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     21.474 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 3.024 ±(99.9%) 0.072 ms/op
Iteration   1: 2.062 ±(99.9%) 0.043 ms/op
                 existUser·p0.00:   0.502 ms/op
                 existUser·p0.50:   1.933 ms/op
                 existUser·p0.90:   2.462 ms/op
                 existUser·p0.95:   2.666 ms/op
                 existUser·p0.99:   3.595 ms/op
                 existUser·p0.999:  29.590 ms/op
                 existUser·p0.9999: 30.008 ms/op
                 existUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15536
  mean =      2.062 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14194 
    [ 2.500,  5.000) = 1252 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      3.595 ms/op
     p(99.9000) =     29.590 ms/op
     p(99.9900) =     30.008 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.081 ms/op
Iteration   1: 2.047 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   1.833 ms/op
                 getUser·p0.90:   2.666 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   3.612 ms/op
                 getUser·p0.999:  21.004 ms/op
                 getUser·p0.9999: 21.127 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15604
  mean =      2.047 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13080 
    [ 2.500,  5.000) = 2470 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      3.612 ms/op
     p(99.9000) =     21.004 ms/op
     p(99.9900) =     21.127 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.135 ms/op
Iteration   1: 3.355 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.158 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.510 ms/op
                 listUser·p0.999:  18.759 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9531
  mean =      3.355 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 770 
    [ 2.500,  3.750) = 6604 
    [ 3.750,  5.000) = 1970 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.510 ms/op
     p(99.9000) =     18.759 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.243          ops/ms
ClientSimple.existUser                       thrpt         11.265          ops/ms
ClientSimple.getUser                         thrpt         12.472          ops/ms
ClientSimple.listUser                        thrpt          8.223          ops/ms
ClientSimple.createUser                       avgt          2.488           ms/op
ClientSimple.existUser                        avgt          2.070           ms/op
ClientSimple.getUser                          avgt          2.215           ms/op
ClientSimple.listUser                         avgt          3.492           ms/op
ClientSimple.createUser                     sample  14650   2.195 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.677           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.991           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.998           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.553           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.474           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.791           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.791           ms/op
ClientSimple.existUser                      sample  15536   2.062 ± 0.043   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.502           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.933           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.666           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.595           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.590           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.008           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.081           ms/op
ClientSimple.getUser                        sample  15604   2.047 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.833           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.612           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.004           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.127           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.201           ms/op
ClientSimple.listUser                       sample   9531   3.355 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.116           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.158           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.178           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.510           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.759           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.300           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.300           ms/op

Benchmark result is saved to 1721585086546.json
