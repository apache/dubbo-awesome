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
# Warmup Iteration   1: 1.356 ops/ms
Iteration   1: 6.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.038 ops/ms


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
# Warmup Iteration   1: 6.333 ops/ms
Iteration   1: 12.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.928 ops/ms


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
# Warmup Iteration   1: 5.174 ops/ms
Iteration   1: 12.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.862 ops/ms


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
# Warmup Iteration   1: 3.577 ops/ms
Iteration   1: 8.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.429 ops/ms


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.074 ms/op
Iteration   1: 2.052 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.052 ms/op


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
# Warmup Iteration   1: 2.926 ±(99.9%) 0.043 ms/op
Iteration   1: 1.807 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.807 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.068 ms/op
Iteration   1: 2.140 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.140 ms/op


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.101 ms/op
Iteration   1: 3.073 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.073 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.076 ms/op
Iteration   1: 1.928 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   1.759 ms/op
                 createUser·p0.90:   2.339 ms/op
                 createUser·p0.95:   2.503 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  21.889 ms/op
                 createUser·p0.9999: 22.104 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16903
  mean =      1.928 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16053 
    [ 2.500,  5.000) = 727 
    [ 5.000,  7.500) = 28 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     22.104 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 2.893 ±(99.9%) 0.065 ms/op
Iteration   1: 1.991 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.468 ms/op
                 existUser·p0.50:   1.978 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  18.674 ms/op
                 existUser·p0.9999: 18.945 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16099
  mean =      1.991 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1281 
    [ 1.250,  2.500) = 13152 
    [ 2.500,  3.750) = 1528 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =     18.674 ms/op
     p(99.9900) =     18.945 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.083 ms/op
Iteration   1: 2.187 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   2.167 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   3.452 ms/op
                 getUser·p0.999:  11.542 ms/op
                 getUser·p0.9999: 12.198 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14633
  mean =      2.187 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 12274 
    [ 2.500,  3.750) = 2109 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.452 ms/op
     p(99.9000) =     11.542 ms/op
     p(99.9900) =     12.198 ms/op
     p(99.9990) =     12.206 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.143 ms/op
Iteration   1: 3.037 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   2.814 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.125 ms/op
                 listUser·p0.99:   4.779 ms/op
                 listUser·p0.999:  7.188 ms/op
                 listUser·p0.9999: 7.282 ms/op
                 listUser·p1.00:   7.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10531
  mean =      3.037 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 44 
    [2.000, 2.500) = 476 
    [2.500, 3.000) = 6453 
    [3.000, 3.500) = 1367 
    [3.500, 4.000) = 1429 
    [4.000, 4.500) = 580 
    [4.500, 5.000) = 90 
    [5.000, 5.500) = 12 
    [5.500, 6.000) = 26 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 14 
    [7.000, 7.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      4.779 ms/op
     p(99.9000) =      7.188 ms/op
     p(99.9900) =      7.282 ms/op
     p(99.9990) =      7.283 ms/op
     p(99.9999) =      7.283 ms/op
    p(100.0000) =      7.283 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.038          ops/ms
ClientSimple.existUser                       thrpt         12.928          ops/ms
ClientSimple.getUser                         thrpt         12.862          ops/ms
ClientSimple.listUser                        thrpt          8.429          ops/ms
ClientSimple.createUser                       avgt          2.052           ms/op
ClientSimple.existUser                        avgt          1.807           ms/op
ClientSimple.getUser                          avgt          2.140           ms/op
ClientSimple.listUser                         avgt          3.073           ms/op
ClientSimple.createUser                     sample  16903   1.928 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.703           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.759           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.339           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.503           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.768           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.889           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.104           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.217           ms/op
ClientSimple.existUser                      sample  16099   1.991 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.468           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.978           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.621           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.674           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.945           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.005           ms/op
ClientSimple.getUser                        sample  14633   2.187 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.624           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.167           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.452           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.542           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.198           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.206           ms/op
ClientSimple.listUser                       sample  10531   3.037 ± 0.019   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.094           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.814           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.887           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.125           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.779           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.188           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.282           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.283           ms/op

Benchmark result is saved to 1725689137038.json
