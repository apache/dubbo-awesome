# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.331 ops/ms
Iteration   1: 7.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.459 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.573 ops/ms
Iteration   1: 13.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.662 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.256 ops/ms
Iteration   1: 13.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.053 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.953 ops/ms
Iteration   1: 9.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.324 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.069 ms/op
Iteration   1: 2.139 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ±(99.9%) 0.048 ms/op
Iteration   1: 1.704 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.704 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.315 ±(99.9%) 0.062 ms/op
Iteration   1: 1.852 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.852 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.095 ms/op
Iteration   1: 3.324 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.593 ±(99.9%) 0.114 ms/op
Iteration   1: 2.198 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.543 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   2.830 ms/op
                 createUser·p0.99:   7.092 ms/op
                 createUser·p0.999:  16.843 ms/op
                 createUser·p0.9999: 17.072 ms/op
                 createUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14727
  mean =      2.198 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 247 
    [ 1.250,  2.500) = 12255 
    [ 2.500,  3.750) = 1897 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      7.092 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.768 ±(99.9%) 0.059 ms/op
Iteration   1: 1.950 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.474 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   3.154 ms/op
                 existUser·p0.999:  23.953 ms/op
                 existUser·p0.9999: 24.554 ms/op
                 existUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16683
  mean =      1.950 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15983 
    [ 2.500,  5.000) = 604 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.154 ms/op
     p(99.9000) =     23.953 ms/op
     p(99.9900) =     24.554 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.322 ±(99.9%) 0.082 ms/op
Iteration   1: 2.180 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.495 ms/op
                 getUser·p0.50:   2.171 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   3.911 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 12.690 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14904
  mean =      2.180 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 12496 
    [ 2.500,  3.750) = 2106 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.911 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     12.690 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.648 ±(99.9%) 0.142 ms/op
Iteration   1: 2.905 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.675 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.063 ms/op
                 listUser·p0.99:   4.473 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 16.312 ms/op
                 listUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 11004
  mean =      2.905 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 2930 
    [ 2.500,  3.750) = 6773 
    [ 3.750,  5.000) = 1235 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.675 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     16.312 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.459          ops/ms
ClientSimple.existUser                       thrpt         13.662          ops/ms
ClientSimple.getUser                         thrpt         13.053          ops/ms
ClientSimple.listUser                        thrpt          9.324          ops/ms
ClientSimple.createUser                       avgt          2.139           ms/op
ClientSimple.existUser                        avgt          1.704           ms/op
ClientSimple.getUser                          avgt          1.852           ms/op
ClientSimple.listUser                         avgt          3.324           ms/op
ClientSimple.createUser                     sample  14727   2.198 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.543           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.092           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.843           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.072           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.072           ms/op
ClientSimple.existUser                      sample  16683   1.950 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.474           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.884           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.154           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.953           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.554           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.642           ms/op
ClientSimple.getUser                        sample  14904   2.180 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.495           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.171           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.911           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.911           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.690           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.698           ms/op
ClientSimple.listUser                       sample  11004   2.905 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.871           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.675           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.834           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.063           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.942           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.312           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.318           ms/op

Benchmark result is saved to 1712449025246.json
