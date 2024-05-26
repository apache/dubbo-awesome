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
# Warmup Iteration   1: 1.450 ops/ms
Iteration   1: 6.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.761 ops/ms


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
# Warmup Iteration   1: 6.272 ops/ms
Iteration   1: 12.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.036 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.520 ops/ms
Iteration   1: 12.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.684 ops/ms


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
# Warmup Iteration   1: 4.939 ops/ms
Iteration   1: 8.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.426 ops/ms


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.081 ms/op
Iteration   1: 2.186 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.186 ms/op


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.068 ms/op
Iteration   1: 2.114 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.114 ms/op


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
# Warmup Iteration   1: 3.214 ±(99.9%) 0.049 ms/op
Iteration   1: 2.044 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.044 ms/op


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
# Warmup Iteration   1: 4.489 ±(99.9%) 0.088 ms/op
Iteration   1: 3.184 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.184 ms/op


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
# Warmup Iteration   1: 3.542 ±(99.9%) 0.096 ms/op
Iteration   1: 2.209 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.482 ms/op
                 createUser·p0.50:   1.914 ms/op
                 createUser·p0.90:   2.814 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   7.530 ms/op
                 createUser·p0.999:  30.727 ms/op
                 createUser·p0.9999: 34.373 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14474
  mean =      2.209 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11451 
    [ 2.500,  5.000) = 2723 
    [ 5.000,  7.500) = 153 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      1.914 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      7.530 ms/op
     p(99.9000) =     30.727 ms/op
     p(99.9900) =     34.373 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 3.156 ±(99.9%) 0.074 ms/op
Iteration   1: 1.785 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   1.927 ms/op
                 existUser·p0.95:   2.077 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  16.155 ms/op
                 existUser·p0.9999: 16.220 ms/op
                 existUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17892
  mean =      1.785 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 204 
    [ 1.250,  2.500) = 17349 
    [ 2.500,  3.750) = 141 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      1.927 ms/op
     p(95.0000) =      2.077 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     16.220 ms/op
     p(99.9990) =     16.220 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


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
# Warmup Iteration   1: 3.205 ±(99.9%) 0.080 ms/op
Iteration   1: 2.257 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   2.154 ms/op
                 getUser·p0.90:   2.818 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  12.943 ms/op
                 getUser·p0.9999: 13.613 ms/op
                 getUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14208
  mean =      2.257 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 195 
    [ 1.250,  2.500) = 10641 
    [ 2.500,  3.750) = 3208 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     13.613 ms/op
     p(99.9990) =     13.648 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


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
# Warmup Iteration   1: 4.506 ±(99.9%) 0.132 ms/op
Iteration   1: 3.367 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  20.483 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9486
  mean =      3.367 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1144 
    [ 2.500,  5.000) = 7981 
    [ 5.000,  7.500) = 234 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     20.483 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.761          ops/ms
ClientSimple.existUser                       thrpt         12.036          ops/ms
ClientSimple.getUser                         thrpt         12.684          ops/ms
ClientSimple.listUser                        thrpt          8.426          ops/ms
ClientSimple.createUser                       avgt          2.186           ms/op
ClientSimple.existUser                        avgt          2.114           ms/op
ClientSimple.getUser                          avgt          2.044           ms/op
ClientSimple.listUser                         avgt          3.184           ms/op
ClientSimple.createUser                     sample  14474   2.209 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.482           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.914           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.240           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.530           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.727           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.373           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.931           ms/op
ClientSimple.existUser                      sample  17892   1.785 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.520           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.679           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.927           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.077           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.506           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.155           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.220           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.220           ms/op
ClientSimple.getUser                        sample  14208   2.257 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.580           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.154           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.944           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.943           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.613           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.648           ms/op
ClientSimple.listUser                       sample   9486   3.367 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.841           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.052           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.791           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.483           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.708           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.708           ms/op

Benchmark result is saved to 1716725172868.json
