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
# Warmup Iteration   1: 1.634 ops/ms
Iteration   1: 6.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.642 ops/ms


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
# Warmup Iteration   1: 5.172 ops/ms
Iteration   1: 12.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.815 ops/ms


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
# Warmup Iteration   1: 6.095 ops/ms
Iteration   1: 13.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.305 ops/ms


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
# Warmup Iteration   1: 5.804 ops/ms
Iteration   1: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.179 ops/ms


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.061 ms/op
Iteration   1: 2.006 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.006 ms/op


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
# Warmup Iteration   1: 2.995 ±(99.9%) 0.047 ms/op
Iteration   1: 1.878 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.878 ms/op


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
# Warmup Iteration   1: 3.438 ±(99.9%) 0.059 ms/op
Iteration   1: 1.790 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.790 ms/op


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
# Warmup Iteration   1: 4.970 ±(99.9%) 0.111 ms/op
Iteration   1: 3.495 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.495 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.083 ms/op
Iteration   1: 2.350 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.284 ms/op
                 createUser·p0.50:   2.281 ms/op
                 createUser·p0.90:   2.781 ms/op
                 createUser·p0.95:   3.039 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 19.599 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13759
  mean =      2.350 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 9712 
    [ 2.500,  3.750) = 3762 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.284 ms/op
     p(50.0000) =      2.281 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     19.599 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.048 ±(99.9%) 0.071 ms/op
Iteration   1: 1.743 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   1.640 ms/op
                 existUser·p0.90:   2.075 ms/op
                 existUser·p0.95:   2.216 ms/op
                 existUser·p0.99:   2.846 ms/op
                 existUser·p0.999:  22.195 ms/op
                 existUser·p0.9999: 23.314 ms/op
                 existUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18328
  mean =      1.743 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18006 
    [ 2.500,  5.000) = 251 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.640 ms/op
     p(90.0000) =      2.075 ms/op
     p(95.0000) =      2.216 ms/op
     p(99.0000) =      2.846 ms/op
     p(99.9000) =     22.195 ms/op
     p(99.9900) =     23.314 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 3.271 ±(99.9%) 0.070 ms/op
Iteration   1: 2.012 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   1.907 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.736 ms/op
                 getUser·p0.99:   3.962 ms/op
                 getUser·p0.999:  29.066 ms/op
                 getUser·p0.9999: 29.885 ms/op
                 getUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15981
  mean =      2.012 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13859 
    [ 2.500,  5.000) = 2037 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      3.962 ms/op
     p(99.9000) =     29.066 ms/op
     p(99.9900) =     29.885 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.145 ms/op
Iteration   1: 3.509 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   3.219 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  12.106 ms/op
                 listUser·p0.9999: 12.354 ms/op
                 listUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9116
  mean =      3.509 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 173 
    [ 2.500,  3.750) = 6056 
    [ 3.750,  5.000) = 2469 
    [ 5.000,  6.250) = 222 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     12.106 ms/op
     p(99.9900) =     12.354 ms/op
     p(99.9990) =     12.354 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.642          ops/ms
ClientSimple.existUser                       thrpt         12.815          ops/ms
ClientSimple.getUser                         thrpt         13.305          ops/ms
ClientSimple.listUser                        thrpt          8.179          ops/ms
ClientSimple.createUser                       avgt          2.006           ms/op
ClientSimple.existUser                        avgt          1.878           ms/op
ClientSimple.getUser                          avgt          1.790           ms/op
ClientSimple.listUser                         avgt          3.495           ms/op
ClientSimple.createUser                     sample  13759   2.350 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.284           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.281           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.039           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.317           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.743           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.599           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.759           ms/op
ClientSimple.existUser                      sample  18328   1.743 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.593           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.640           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.075           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.216           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.846           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.195           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.314           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.396           ms/op
ClientSimple.getUser                        sample  15981   2.012 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.775           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.907           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.962           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.066           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.885           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.179           ms/op
ClientSimple.listUser                       sample   9116   3.509 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.998           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.219           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.249           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.106           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.354           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.354           ms/op

Benchmark result is saved to 1712037922993.json
