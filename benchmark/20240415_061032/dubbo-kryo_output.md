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
# Warmup Iteration   1: 1.988 ops/ms
Iteration   1: 7.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.697 ops/ms


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
# Warmup Iteration   1: 5.965 ops/ms
Iteration   1: 11.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.412 ops/ms


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
# Warmup Iteration   1: 5.819 ops/ms
Iteration   1: 12.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.701 ops/ms


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
# Warmup Iteration   1: 5.701 ops/ms
Iteration   1: 8.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.516 ops/ms


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.072 ms/op
Iteration   1: 2.080 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.080 ms/op


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.090 ms/op
Iteration   1: 1.905 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.905 ms/op


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.071 ms/op
Iteration   1: 1.889 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.889 ms/op


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.131 ms/op
Iteration   1: 3.187 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.187 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.079 ms/op
Iteration   1: 2.240 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   1.890 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   12.665 ms/op
                 createUser·p0.999:  32.047 ms/op
                 createUser·p0.9999: 32.464 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14265
  mean =      2.240 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11329 
    [ 2.500,  5.000) = 2602 
    [ 5.000,  7.500) = 127 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =     12.665 ms/op
     p(99.9000) =     32.047 ms/op
     p(99.9900) =     32.464 ms/op
     p(99.9990) =     32.506 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 3.015 ±(99.9%) 0.074 ms/op
Iteration   1: 2.109 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   2.007 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   4.865 ms/op
                 existUser·p0.999:  19.978 ms/op
                 existUser·p0.9999: 20.723 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15307
  mean =      2.109 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13918 
    [ 2.500,  5.000) = 1241 
    [ 5.000,  7.500) = 71 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      4.865 ms/op
     p(99.9000) =     19.978 ms/op
     p(99.9900) =     20.723 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.083 ms/op
Iteration   1: 1.951 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.527 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  15.788 ms/op
                 getUser·p0.9999: 15.940 ms/op
                 getUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16375
  mean =      1.951 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 187 
    [ 1.250,  2.500) = 15243 
    [ 2.500,  3.750) = 780 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =     15.788 ms/op
     p(99.9900) =     15.940 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.141 ms/op
Iteration   1: 3.246 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.210 ms/op
                 listUser·p0.999:  7.038 ms/op
                 listUser·p0.9999: 7.692 ms/op
                 listUser·p1.00:   7.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9849
  mean =      3.246 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 36 
    [2.000, 2.500) = 804 
    [2.500, 3.000) = 4572 
    [3.000, 3.500) = 1222 
    [3.500, 4.000) = 1302 
    [4.000, 4.500) = 1350 
    [4.500, 5.000) = 245 
    [5.000, 5.500) = 82 
    [5.500, 6.000) = 105 
    [6.000, 6.500) = 67 
    [6.500, 7.000) = 46 
    [7.000, 7.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =      7.038 ms/op
     p(99.9900) =      7.692 ms/op
     p(99.9990) =      7.692 ms/op
     p(99.9999) =      7.692 ms/op
    p(100.0000) =      7.692 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.697          ops/ms
ClientSimple.existUser                       thrpt         11.412          ops/ms
ClientSimple.getUser                         thrpt         12.701          ops/ms
ClientSimple.listUser                        thrpt          8.516          ops/ms
ClientSimple.createUser                       avgt          2.080           ms/op
ClientSimple.existUser                        avgt          1.905           ms/op
ClientSimple.getUser                          avgt          1.889           ms/op
ClientSimple.listUser                         avgt          3.187           ms/op
ClientSimple.createUser                     sample  14265   2.240 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.575           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.890           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.665           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.047           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.464           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.506           ms/op
ClientSimple.existUser                      sample  15307   2.109 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.483           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.007           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.865           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.978           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.723           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.775           ms/op
ClientSimple.getUser                        sample  16375   1.951 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.891           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.752           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.788           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.940           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.024           ms/op
ClientSimple.listUser                       sample   9849   3.246 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.169           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.892           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.210           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.038           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.692           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.692           ms/op

Benchmark result is saved to 1713161172897.json
