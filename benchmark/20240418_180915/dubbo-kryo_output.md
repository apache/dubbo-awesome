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
# Warmup Iteration   1: 1.833 ops/ms
Iteration   1: 6.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.587 ops/ms


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
# Warmup Iteration   1: 6.330 ops/ms
Iteration   1: 12.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.969 ops/ms


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
# Warmup Iteration   1: 5.811 ops/ms
Iteration   1: 12.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.298 ops/ms


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
# Warmup Iteration   1: 5.343 ops/ms
Iteration   1: 8.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.853 ops/ms


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.100 ms/op
Iteration   1: 2.282 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.282 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.054 ms/op
Iteration   1: 1.808 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.808 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.062 ms/op
Iteration   1: 1.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.911 ms/op


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.100 ms/op
Iteration   1: 3.414 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.414 ms/op


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.163 ms/op
Iteration   1: 2.497 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   2.195 ms/op
                 createUser·p0.90:   3.252 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  14.074 ms/op
                 createUser·p0.9999: 17.019 ms/op
                 createUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12707
  mean =      2.497 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 8237 
    [ 2.500,  3.750) = 3552 
    [ 3.750,  5.000) = 458 
    [ 5.000,  6.250) = 144 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     17.019 ms/op
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
# Warmup Iteration   1: 3.367 ±(99.9%) 0.084 ms/op
Iteration   1: 2.184 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.463 ms/op
                 existUser·p0.50:   2.017 ms/op
                 existUser·p0.90:   2.761 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  21.192 ms/op
                 existUser·p0.9999: 21.861 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14637
  mean =      2.184 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12038 
    [ 2.500,  5.000) = 2465 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =     21.192 ms/op
     p(99.9900) =     21.861 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.083 ms/op
Iteration   1: 1.960 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   1.804 ms/op
                 getUser·p0.90:   2.359 ms/op
                 getUser·p0.95:   2.580 ms/op
                 getUser·p0.99:   3.946 ms/op
                 getUser·p0.999:  14.509 ms/op
                 getUser·p0.9999: 29.023 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16439
  mean =      1.960 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15383 
    [ 2.500,  5.000) = 913 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.946 ms/op
     p(99.9000) =     14.509 ms/op
     p(99.9900) =     29.023 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.185 ms/op
Iteration   1: 3.523 ±(99.9%) 0.066 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   3.428 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.349 ms/op
                 listUser·p0.99:   12.546 ms/op
                 listUser·p0.999:  25.023 ms/op
                 listUser·p0.9999: 31.130 ms/op
                 listUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9122
  mean =      3.523 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 944 
    [ 2.500,  5.000) = 7858 
    [ 5.000,  7.500) = 188 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.349 ms/op
     p(99.0000) =     12.546 ms/op
     p(99.9000) =     25.023 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     31.130 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.587          ops/ms
ClientSimple.existUser                       thrpt         12.969          ops/ms
ClientSimple.getUser                         thrpt         12.298          ops/ms
ClientSimple.listUser                        thrpt          8.853          ops/ms
ClientSimple.createUser                       avgt          2.282           ms/op
ClientSimple.existUser                        avgt          1.808           ms/op
ClientSimple.getUser                          avgt          1.911           ms/op
ClientSimple.listUser                         avgt          3.414           ms/op
ClientSimple.createUser                     sample  12707   2.497 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.633           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.195           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.252           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.219           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.389           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.074           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.019           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.072           ms/op
ClientSimple.existUser                      sample  14637   2.184 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.463           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.017           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.761           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.011           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.571           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.192           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.861           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.922           ms/op
ClientSimple.getUser                        sample  16439   1.960 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.570           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.804           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.359           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.946           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.509           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.023           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.065           ms/op
ClientSimple.listUser                       sample   9122   3.523 ± 0.066   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.842           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.428           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.014           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.349           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.546           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.023           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.130           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.130           ms/op

Benchmark result is saved to 1713463508113.json
