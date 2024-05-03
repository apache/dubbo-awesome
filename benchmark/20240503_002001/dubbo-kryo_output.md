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
# Warmup Iteration   1: 1.890 ops/ms
Iteration   1: 7.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.752 ops/ms


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
# Warmup Iteration   1: 6.659 ops/ms
Iteration   1: 12.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.887 ops/ms


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
# Warmup Iteration   1: 6.535 ops/ms
Iteration   1: 14.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.504 ops/ms


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
# Warmup Iteration   1: 5.003 ops/ms
Iteration   1: 8.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.430 ops/ms


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
# Warmup Iteration   1: 3.653 ±(99.9%) 0.057 ms/op
Iteration   1: 2.122 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.122 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.052 ms/op
Iteration   1: 1.880 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.880 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.070 ms/op
Iteration   1: 2.031 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.031 ms/op


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
# Warmup Iteration   1: 4.552 ±(99.9%) 0.079 ms/op
Iteration   1: 3.268 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.268 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.138 ms/op
Iteration   1: 2.083 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   1.935 ms/op
                 createUser·p0.90:   2.454 ms/op
                 createUser·p0.95:   2.679 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  19.517 ms/op
                 createUser·p0.9999: 20.020 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15396
  mean =      2.083 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14112 
    [ 2.500,  5.000) = 1136 
    [ 5.000,  7.500) = 70 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     19.517 ms/op
     p(99.9900) =     20.020 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 2.712 ±(99.9%) 0.069 ms/op
Iteration   1: 1.795 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.333 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   2.617 ms/op
                 existUser·p0.999:  12.059 ms/op
                 existUser·p0.9999: 12.324 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17827
  mean =      1.795 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 644 
    [ 1.250,  2.500) = 16834 
    [ 2.500,  3.750) = 272 
    [ 3.750,  5.000) = 3 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      2.617 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     12.324 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


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
# Warmup Iteration   1: 3.318 ±(99.9%) 0.080 ms/op
Iteration   1: 2.057 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   1.882 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   5.252 ms/op
                 getUser·p0.999:  16.073 ms/op
                 getUser·p0.9999: 16.839 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15543
  mean =      2.057 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 13495 
    [ 2.500,  3.750) = 1687 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      5.252 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     16.839 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.104 ms/op
Iteration   1: 3.119 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   4.932 ms/op
                 listUser·p0.999:  6.415 ms/op
                 listUser·p0.9999: 9.970 ms/op
                 listUser·p1.00:   9.994 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10275
  mean =      3.119 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 6 
    [ 1.500,  2.000) = 105 
    [ 2.000,  2.500) = 485 
    [ 2.500,  3.000) = 5361 
    [ 3.000,  3.500) = 2178 
    [ 3.500,  4.000) = 1126 
    [ 4.000,  4.500) = 752 
    [ 4.500,  5.000) = 184 
    [ 5.000,  5.500) = 62 
    [ 5.500,  6.000) = 3 
    [ 6.000,  6.500) = 6 
    [ 6.500,  7.000) = 1 
    [ 7.000,  7.500) = 0 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 4 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =      6.415 ms/op
     p(99.9900) =      9.970 ms/op
     p(99.9990) =      9.994 ms/op
     p(99.9999) =      9.994 ms/op
    p(100.0000) =      9.994 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.752          ops/ms
ClientSimple.existUser                       thrpt         12.887          ops/ms
ClientSimple.getUser                         thrpt         14.504          ops/ms
ClientSimple.listUser                        thrpt          8.430          ops/ms
ClientSimple.createUser                       avgt          2.122           ms/op
ClientSimple.existUser                        avgt          1.880           ms/op
ClientSimple.getUser                          avgt          2.031           ms/op
ClientSimple.listUser                         avgt          3.268           ms/op
ClientSimple.createUser                     sample  15396   2.083 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.745           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.935           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.768           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.517           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.020           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.480           ms/op
ClientSimple.existUser                      sample  17827   1.795 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.333           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.059           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.324           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.632           ms/op
ClientSimple.getUser                        sample  15543   2.057 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.529           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.882           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.252           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.073           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.839           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.876           ms/op
ClientSimple.listUser                       sample  10275   3.119 ± 0.019   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.229           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.937           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.415           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.970           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.994           ms/op

Benchmark result is saved to 1714695314960.json
