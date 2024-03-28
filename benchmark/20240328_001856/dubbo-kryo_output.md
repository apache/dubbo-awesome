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
# Warmup Iteration   1: 1.565 ops/ms
Iteration   1: 4.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  4.922 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.262 ops/ms
Iteration   1: 11.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.226 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ops/ms
Iteration   1: 9.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.610 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.132 ops/ms
Iteration   1: 6.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  6.425 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.598 ±(99.9%) 0.106 ms/op
Iteration   1: 2.572 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.572 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.865 ±(99.9%) 0.067 ms/op
Iteration   1: 2.083 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.083 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.082 ms/op
Iteration   1: 2.688 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.688 ms/op


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
# Warmup Iteration   1: 5.092 ±(99.9%) 0.115 ms/op
Iteration   1: 4.124 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.124 ms/op


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.114 ms/op
Iteration   1: 2.607 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.462 ms/op
                 createUser·p0.50:   2.486 ms/op
                 createUser·p0.90:   3.211 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12348
  mean =      2.607 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 6207 
    [ 2.500,  3.750) = 5571 
    [ 3.750,  5.000) = 333 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.211 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.083 ms/op
Iteration   1: 2.041 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   2.650 ms/op
                 existUser·p0.95:   2.878 ms/op
                 existUser·p0.99:   4.688 ms/op
                 existUser·p0.999:  15.041 ms/op
                 existUser·p0.9999: 15.303 ms/op
                 existUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15667
  mean =      2.041 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 13133 
    [ 2.500,  3.750) = 2068 
    [ 3.750,  5.000) = 164 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.878 ms/op
     p(99.0000) =      4.688 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     15.303 ms/op
     p(99.9990) =     15.303 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.106 ms/op
Iteration   1: 2.153 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   1.972 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.847 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  19.366 ms/op
                 getUser·p0.9999: 20.104 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14918
  mean =      2.153 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12799 
    [ 2.500,  5.000) = 1942 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     20.104 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 5.198 ±(99.9%) 0.167 ms/op
Iteration   1: 4.019 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   8.271 ms/op
                 listUser·p0.999:  15.350 ms/op
                 listUser·p0.9999: 15.450 ms/op
                 listUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8037
  mean =      4.019 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 456 
    [ 2.500,  3.750) = 2499 
    [ 3.750,  5.000) = 4295 
    [ 5.000,  6.250) = 560 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      8.271 ms/op
     p(99.9000) =     15.350 ms/op
     p(99.9900) =     15.450 ms/op
     p(99.9990) =     15.450 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          4.922          ops/ms
ClientSimple.existUser                       thrpt         11.226          ops/ms
ClientSimple.getUser                         thrpt          9.610          ops/ms
ClientSimple.listUser                        thrpt          6.425          ops/ms
ClientSimple.createUser                       avgt          2.572           ms/op
ClientSimple.existUser                        avgt          2.083           ms/op
ClientSimple.getUser                          avgt          2.688           ms/op
ClientSimple.listUser                         avgt          4.124           ms/op
ClientSimple.createUser                     sample  12348   2.607 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.462           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.486           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.211           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.551           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.398           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.810           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.039           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.039           ms/op
ClientSimple.existUser                      sample  15667   2.041 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.877           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.833           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.878           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.688           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.041           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.303           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.303           ms/op
ClientSimple.getUser                        sample  14918   2.153 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.863           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.972           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.169           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.366           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.104           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.185           ms/op
ClientSimple.listUser                       sample   8037   4.019 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.135           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.059           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.997           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.341           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.271           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.350           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.450           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.450           ms/op

Benchmark result is saved to 1711584911243.json
