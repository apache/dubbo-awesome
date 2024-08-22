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
# Warmup Iteration   1: 1.126 ops/ms
Iteration   1: 6.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.300 ops/ms


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
# Warmup Iteration   1: 6.531 ops/ms
Iteration   1: 13.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.241 ops/ms


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
# Warmup Iteration   1: 5.326 ops/ms
Iteration   1: 12.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.756 ops/ms


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
# Warmup Iteration   1: 4.657 ops/ms
Iteration   1: 8.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.917 ops/ms


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.069 ms/op
Iteration   1: 2.194 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.194 ms/op


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
# Warmup Iteration   1: 3.578 ±(99.9%) 0.054 ms/op
Iteration   1: 2.116 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.116 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.111 ms/op
Iteration   1: 2.187 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.187 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.101 ms/op
Iteration   1: 3.692 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.692 ms/op


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
# Warmup Iteration   1: 3.821 ±(99.9%) 0.108 ms/op
Iteration   1: 2.189 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   1.968 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   2.863 ms/op
                 createUser·p0.99:   7.512 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 17.385 ms/op
                 createUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14636
  mean =      2.189 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 12226 
    [ 2.500,  3.750) = 2003 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     17.385 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.080 ms/op
Iteration   1: 1.880 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  11.485 ms/op
                 existUser·p0.9999: 12.702 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17037
  mean =      1.880 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 211 
    [ 1.250,  2.500) = 16255 
    [ 2.500,  3.750) = 351 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 167 
    [ 6.250,  7.500) = 9 
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
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     12.702 ms/op
     p(99.9990) =     12.829 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.087 ms/op
Iteration   1: 2.016 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   1.905 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  21.500 ms/op
                 getUser·p0.9999: 21.785 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15877
  mean =      2.016 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14593 
    [ 2.500,  5.000) = 1196 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =     21.500 ms/op
     p(99.9900) =     21.785 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 4.748 ±(99.9%) 0.137 ms/op
Iteration   1: 3.474 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   3.453 ms/op
                 listUser·p0.90:   4.184 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.642 ms/op
                 listUser·p0.999:  11.252 ms/op
                 listUser·p0.9999: 11.485 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9204
  mean =      3.474 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 753 
    [ 2.500,  3.750) = 5832 
    [ 3.750,  5.000) = 2315 
    [ 5.000,  6.250) = 137 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.184 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.642 ms/op
     p(99.9000) =     11.252 ms/op
     p(99.9900) =     11.485 ms/op
     p(99.9990) =     11.485 ms/op
     p(99.9999) =     11.485 ms/op
    p(100.0000) =     11.485 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.300          ops/ms
ClientSimple.existUser                       thrpt         13.241          ops/ms
ClientSimple.getUser                         thrpt         12.756          ops/ms
ClientSimple.listUser                        thrpt          8.917          ops/ms
ClientSimple.createUser                       avgt          2.194           ms/op
ClientSimple.existUser                        avgt          2.116           ms/op
ClientSimple.getUser                          avgt          2.187           ms/op
ClientSimple.listUser                         avgt          3.692           ms/op
ClientSimple.createUser                     sample  14636   2.189 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.631           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.968           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.512           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.385           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.400           ms/op
ClientSimple.existUser                      sample  17037   1.880 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.870           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.784           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.349           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.485           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.702           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.829           ms/op
ClientSimple.getUser                        sample  15877   2.016 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.688           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.905           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.658           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.500           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.785           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.823           ms/op
ClientSimple.listUser                       sample   9204   3.474 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.030           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.453           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.184           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.642           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.252           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.485           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.485           ms/op

Benchmark result is saved to 1724328407827.json
