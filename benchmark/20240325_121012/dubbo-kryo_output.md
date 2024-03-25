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
# Warmup Iteration   1: 1.333 ops/ms
Iteration   1: 6.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.018 ops/ms


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
# Warmup Iteration   1: 5.811 ops/ms
Iteration   1: 14.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.108 ops/ms


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
# Warmup Iteration   1: 4.936 ops/ms
Iteration   1: 13.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.107 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.948 ops/ms
Iteration   1: 8.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.590 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.942 ±(99.9%) 0.074 ms/op
Iteration   1: 2.215 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.215 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.207 ±(99.9%) 0.053 ms/op
Iteration   1: 1.869 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.869 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.183 ±(99.9%) 0.055 ms/op
Iteration   1: 2.280 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.280 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.016 ±(99.9%) 0.108 ms/op
Iteration   1: 3.778 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.778 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.443 ±(99.9%) 0.088 ms/op
Iteration   1: 2.338 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.466 ms/op
                 createUser·p0.50:   2.116 ms/op
                 createUser·p0.90:   2.912 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   11.747 ms/op
                 createUser·p0.999:  20.719 ms/op
                 createUser·p0.9999: 21.271 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13692
  mean =      2.338 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9708 
    [ 2.500,  5.000) = 3699 
    [ 5.000,  7.500) = 123 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      2.116 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.314 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     20.719 ms/op
     p(99.9900) =     21.271 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.068 ms/op
Iteration   1: 2.048 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.464 ms/op
                 existUser·p0.50:   1.987 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  12.896 ms/op
                 existUser·p0.9999: 13.269 ms/op
                 existUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15895
  mean =      2.048 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 262 
    [ 1.250,  2.500) = 14405 
    [ 2.500,  3.750) = 1064 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =     12.896 ms/op
     p(99.9900) =     13.269 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


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
# Warmup Iteration   1: 3.248 ±(99.9%) 0.081 ms/op
Iteration   1: 2.040 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   1.866 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.773 ms/op
                 getUser·p0.99:   4.048 ms/op
                 getUser·p0.999:  15.963 ms/op
                 getUser·p0.9999: 16.136 ms/op
                 getUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15676
  mean =      2.040 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 13932 
    [ 2.500,  3.750) = 1500 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      4.048 ms/op
     p(99.9000) =     15.963 ms/op
     p(99.9900) =     16.136 ms/op
     p(99.9990) =     16.155 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.109 ms/op
Iteration   1: 3.650 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.441 ms/op
                 listUser·p0.99:   8.090 ms/op
                 listUser·p0.999:  14.445 ms/op
                 listUser·p0.9999: 19.202 ms/op
                 listUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8767
  mean =      3.650 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1363 
    [ 2.500,  3.750) = 3830 
    [ 3.750,  5.000) = 2944 
    [ 5.000,  6.250) = 304 
    [ 6.250,  7.500) = 106 
    [ 7.500,  8.750) = 136 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.441 ms/op
     p(99.0000) =      8.090 ms/op
     p(99.9000) =     14.445 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.018          ops/ms
ClientSimple.existUser                       thrpt         14.108          ops/ms
ClientSimple.getUser                         thrpt         13.107          ops/ms
ClientSimple.listUser                        thrpt          8.590          ops/ms
ClientSimple.createUser                       avgt          2.215           ms/op
ClientSimple.existUser                        avgt          1.869           ms/op
ClientSimple.getUser                          avgt          2.280           ms/op
ClientSimple.listUser                         avgt          3.778           ms/op
ClientSimple.createUser                     sample  13692   2.338 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.466           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.116           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.314           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.747           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.719           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.271           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.332           ms/op
ClientSimple.existUser                      sample  15895   2.048 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.464           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.987           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.809           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.896           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.269           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.337           ms/op
ClientSimple.getUser                        sample  15676   2.040 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.688           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.866           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.048           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.963           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.136           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.155           ms/op
ClientSimple.listUser                       sample   8767   3.650 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.092           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.547           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.768           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.441           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.090           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.445           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.202           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.202           ms/op

Benchmark result is saved to 1711368364588.json
