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
# Warmup Iteration   1: 1.873 ops/ms
Iteration   1: 7.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.064 ops/ms


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
# Warmup Iteration   1: 5.667 ops/ms
Iteration   1: 11.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.888 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.293 ops/ms
Iteration   1: 12.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.907 ops/ms


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
# Warmup Iteration   1: 4.311 ops/ms
Iteration   1: 8.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.409 ops/ms


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.067 ms/op
Iteration   1: 2.024 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.024 ms/op


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
# Warmup Iteration   1: 3.337 ±(99.9%) 0.062 ms/op
Iteration   1: 2.149 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.149 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.070 ms/op
Iteration   1: 2.069 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.069 ms/op


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
# Warmup Iteration   1: 5.762 ±(99.9%) 0.136 ms/op
Iteration   1: 3.094 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.094 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.098 ms/op
Iteration   1: 2.476 ±(99.9%) 0.065 ms/op
                 createUser·p0.00:   0.518 ms/op
                 createUser·p0.50:   2.257 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   7.888 ms/op
                 createUser·p0.999:  39.415 ms/op
                 createUser·p0.9999: 39.977 ms/op
                 createUser·p1.00:   39.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12913
  mean =      2.476 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9568 
    [ 2.500,  5.000) = 3002 
    [ 5.000,  7.500) = 188 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      2.257 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      7.888 ms/op
     p(99.9000) =     39.415 ms/op
     p(99.9900) =     39.977 ms/op
     p(99.9990) =     39.977 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


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
# Warmup Iteration   1: 2.903 ±(99.9%) 0.082 ms/op
Iteration   1: 1.891 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  15.846 ms/op
                 existUser·p0.9999: 17.668 ms/op
                 existUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16939
  mean =      1.891 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 311 
    [ 1.250,  2.500) = 15604 
    [ 2.500,  3.750) = 788 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     15.846 ms/op
     p(99.9900) =     17.668 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 3.186 ±(99.9%) 0.084 ms/op
Iteration   1: 2.230 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.900 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  16.237 ms/op
                 getUser·p0.9999: 16.311 ms/op
                 getUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14351
  mean =      2.230 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 11172 
    [ 2.500,  3.750) = 2813 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      4.948 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     16.311 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 4.949 ±(99.9%) 0.137 ms/op
Iteration   1: 3.817 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   6.071 ms/op
                 listUser·p0.999:  21.483 ms/op
                 listUser·p0.9999: 21.955 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8388
  mean =      3.817 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 287 
    [ 2.500,  5.000) = 7747 
    [ 5.000,  7.500) = 319 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.071 ms/op
     p(99.9000) =     21.483 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.064          ops/ms
ClientSimple.existUser                       thrpt         11.888          ops/ms
ClientSimple.getUser                         thrpt         12.907          ops/ms
ClientSimple.listUser                        thrpt          8.409          ops/ms
ClientSimple.createUser                       avgt          2.024           ms/op
ClientSimple.existUser                        avgt          2.149           ms/op
ClientSimple.getUser                          avgt          2.069           ms/op
ClientSimple.listUser                         avgt          3.094           ms/op
ClientSimple.createUser                     sample  12913   2.476 ± 0.065   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.518           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.257           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.183           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.888           ms/op
ClientSimple.createUser:createUser·p0.999   sample         39.415           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.977           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.977           ms/op
ClientSimple.existUser                      sample  16939   1.891 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.561           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.579           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.846           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.668           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.169           ms/op
ClientSimple.getUser                        sample  14351   2.230 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.676           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.948           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.237           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.311           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.318           ms/op
ClientSimple.listUser                       sample   8388   3.817 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.241           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.731           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.071           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.483           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.955           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.955           ms/op

Benchmark result is saved to 1713636336636.json
