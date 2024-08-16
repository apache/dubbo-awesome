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
# Warmup Iteration   1: 1.805 ops/ms
Iteration   1: 7.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.046 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.624 ops/ms
Iteration   1: 13.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.546 ops/ms


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
# Warmup Iteration   1: 5.263 ops/ms
Iteration   1: 13.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.128 ops/ms


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
# Warmup Iteration   1: 5.661 ops/ms
Iteration   1: 8.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.620 ops/ms


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
# Warmup Iteration   1: 4.807 ±(99.9%) 0.105 ms/op
Iteration   1: 2.064 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.064 ms/op


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
# Warmup Iteration   1: 3.127 ±(99.9%) 0.043 ms/op
Iteration   1: 2.106 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.106 ms/op


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
# Warmup Iteration   1: 3.527 ±(99.9%) 0.066 ms/op
Iteration   1: 1.976 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.976 ms/op


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.115 ms/op
Iteration   1: 3.599 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.599 ms/op


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.107 ms/op
Iteration   1: 2.280 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   2.163 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  17.793 ms/op
                 createUser·p0.9999: 18.291 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14010
  mean =      2.280 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 10985 
    [ 2.500,  3.750) = 2515 
    [ 3.750,  5.000) = 256 
    [ 5.000,  6.250) = 109 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.163 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     18.291 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.273 ±(99.9%) 0.096 ms/op
Iteration   1: 1.991 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.593 ms/op
                 existUser·p0.95:   2.830 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  31.552 ms/op
                 existUser·p0.9999: 31.876 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16102
  mean =      1.991 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14078 
    [ 2.500,  5.000) = 1916 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =     31.552 ms/op
     p(99.9900) =     31.876 ms/op
     p(99.9990) =     31.916 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 3.074 ±(99.9%) 0.077 ms/op
Iteration   1: 2.125 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.781 ms/op
                 getUser·p0.99:   3.382 ms/op
                 getUser·p0.999:  15.646 ms/op
                 getUser·p0.9999: 16.179 ms/op
                 getUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15038
  mean =      2.125 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 12842 
    [ 2.500,  3.750) = 2079 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      3.382 ms/op
     p(99.9000) =     15.646 ms/op
     p(99.9900) =     16.179 ms/op
     p(99.9990) =     16.204 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 5.378 ±(99.9%) 0.225 ms/op
Iteration   1: 3.192 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  7.216 ms/op
                 listUser·p0.9999: 7.422 ms/op
                 listUser·p1.00:   7.422 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10025
  mean =      3.192 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 12 
    [1.500, 2.000) = 108 
    [2.000, 2.500) = 700 
    [2.500, 3.000) = 4067 
    [3.000, 3.500) = 2401 
    [3.500, 4.000) = 1529 
    [4.000, 4.500) = 893 
    [4.500, 5.000) = 189 
    [5.000, 5.500) = 36 
    [5.500, 6.000) = 23 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 36 
    [7.000, 7.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      7.216 ms/op
     p(99.9900) =      7.422 ms/op
     p(99.9990) =      7.422 ms/op
     p(99.9999) =      7.422 ms/op
    p(100.0000) =      7.422 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.046          ops/ms
ClientSimple.existUser                       thrpt         13.546          ops/ms
ClientSimple.getUser                         thrpt         13.128          ops/ms
ClientSimple.listUser                        thrpt          8.620          ops/ms
ClientSimple.createUser                       avgt          2.064           ms/op
ClientSimple.existUser                        avgt          2.106           ms/op
ClientSimple.getUser                          avgt          1.976           ms/op
ClientSimple.listUser                         avgt          3.599           ms/op
ClientSimple.createUser                     sample  14010   2.280 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.696           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.163           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.277           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.169           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.793           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.291           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.317           ms/op
ClientSimple.existUser                      sample  16102   1.991 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.473           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.830           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.555           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.552           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.876           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.916           ms/op
ClientSimple.getUser                        sample  15038   2.125 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.895           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.382           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.646           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.179           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.204           ms/op
ClientSimple.listUser                       sample  10025   3.192 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.094           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.019           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.366           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.216           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.422           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.422           ms/op

Benchmark result is saved to 1723767399236.json
