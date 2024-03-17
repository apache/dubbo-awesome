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
# Warmup Iteration   1: 1.554 ops/ms
Iteration   1: 7.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.908 ops/ms


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
# Warmup Iteration   1: 6.971 ops/ms
Iteration   1: 13.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.984 ops/ms


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
# Warmup Iteration   1: 5.691 ops/ms
Iteration   1: 14.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.201 ops/ms


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
# Warmup Iteration   1: 5.486 ops/ms
Iteration   1: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.581 ops/ms


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.102 ms/op
Iteration   1: 2.253 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.253 ms/op


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
# Warmup Iteration   1: 3.215 ±(99.9%) 0.048 ms/op
Iteration   1: 1.655 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.655 ms/op


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
# Warmup Iteration   1: 3.159 ±(99.9%) 0.051 ms/op
Iteration   1: 1.793 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.793 ms/op


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.077 ms/op
Iteration   1: 3.055 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.055 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.076 ms/op
Iteration   1: 2.036 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   1.880 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   2.888 ms/op
                 createUser·p0.99:   4.093 ms/op
                 createUser·p0.999:  15.811 ms/op
                 createUser·p0.9999: 16.722 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15531
  mean =      2.036 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 13569 
    [ 2.500,  3.750) = 1692 
    [ 3.750,  5.000) = 112 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      4.093 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     16.722 ms/op
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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.762 ±(99.9%) 0.058 ms/op
Iteration   1: 1.838 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   3.485 ms/op
                 existUser·p0.999:  17.269 ms/op
                 existUser·p0.9999: 17.532 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17380
  mean =      1.838 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1229 
    [ 1.250,  2.500) = 15496 
    [ 2.500,  3.750) = 490 
    [ 3.750,  5.000) = 23 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.485 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     17.532 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.075 ms/op
Iteration   1: 2.060 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   1.995 ms/op
                 getUser·p0.90:   2.624 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   3.469 ms/op
                 getUser·p0.999:  10.820 ms/op
                 getUser·p0.9999: 11.432 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15533
  mean =      2.060 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 13066 
    [ 2.500,  3.750) = 2192 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.624 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.469 ms/op
     p(99.9000) =     10.820 ms/op
     p(99.9900) =     11.432 ms/op
     p(99.9990) =     11.731 ms/op
     p(99.9999) =     11.731 ms/op
    p(100.0000) =     11.731 ms/op


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
# Warmup Iteration   1: 4.706 ±(99.9%) 0.140 ms/op
Iteration   1: 3.651 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.643 ms/op
                 listUser·p0.99:   6.456 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8744
  mean =      3.651 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 406 
    [ 2.500,  3.750) = 4727 
    [ 3.750,  5.000) = 3352 
    [ 5.000,  6.250) = 153 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.643 ms/op
     p(99.0000) =      6.456 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.908          ops/ms
ClientSimple.existUser                       thrpt         13.984          ops/ms
ClientSimple.getUser                         thrpt         14.201          ops/ms
ClientSimple.listUser                        thrpt          8.581          ops/ms
ClientSimple.createUser                       avgt          2.253           ms/op
ClientSimple.existUser                        avgt          1.655           ms/op
ClientSimple.getUser                          avgt          1.793           ms/op
ClientSimple.listUser                         avgt          3.055           ms/op
ClientSimple.createUser                     sample  15531   2.036 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.722           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.880           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.093           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.811           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.722           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.039           ms/op
ClientSimple.existUser                      sample  17380   1.838 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.513           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.191           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.485           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.269           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.532           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.629           ms/op
ClientSimple.getUser                        sample  15533   2.060 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.629           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.995           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.624           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.469           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.820           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.432           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.731           ms/op
ClientSimple.listUser                       sample   8744   3.651 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.643           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.456           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.448           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.514           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.514           ms/op

Benchmark result is saved to 1710634565139.json
