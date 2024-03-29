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
# Warmup Iteration   1: 2.097 ops/ms
Iteration   1: 7.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.753 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.928 ops/ms
Iteration   1: 12.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.091 ops/ms


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
# Warmup Iteration   1: 7.604 ops/ms
Iteration   1: 15.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.304 ops/ms


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
# Warmup Iteration   1: 5.278 ops/ms
Iteration   1: 8.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.456 ops/ms


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.076 ms/op
Iteration   1: 2.250 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.250 ms/op


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.045 ms/op
Iteration   1: 1.823 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.823 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.068 ms/op
Iteration   1: 1.984 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.984 ms/op


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.119 ms/op
Iteration   1: 3.214 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.214 ms/op


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.088 ms/op
Iteration   1: 2.201 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   2.085 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   2.968 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  14.123 ms/op
                 createUser·p0.9999: 14.461 ms/op
                 createUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14528
  mean =      2.201 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 11939 
    [ 2.500,  3.750) = 2204 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.968 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     14.461 ms/op
     p(99.9990) =     14.713 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 2.907 ±(99.9%) 0.068 ms/op
Iteration   1: 1.859 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   1.739 ms/op
                 existUser·p0.90:   2.220 ms/op
                 existUser·p0.95:   2.359 ms/op
                 existUser·p0.99:   2.950 ms/op
                 existUser·p0.999:  16.476 ms/op
                 existUser·p0.9999: 17.517 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17390
  mean =      1.859 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 452 
    [ 1.250,  2.500) = 16430 
    [ 2.500,  3.750) = 385 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      2.950 ms/op
     p(99.9000) =     16.476 ms/op
     p(99.9900) =     17.517 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 2.960 ±(99.9%) 0.075 ms/op
Iteration   1: 1.928 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   1.886 ms/op
                 getUser·p0.90:   2.384 ms/op
                 getUser·p0.95:   2.654 ms/op
                 getUser·p0.99:   3.490 ms/op
                 getUser·p0.999:  11.747 ms/op
                 getUser·p0.9999: 11.857 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16570
  mean =      1.928 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 462 
    [ 1.250,  2.500) = 14893 
    [ 2.500,  3.750) = 1134 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.490 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     11.857 ms/op
     p(99.9990) =     11.878 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.136 ms/op
Iteration   1: 3.506 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.457 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  7.921 ms/op
                 listUser·p0.9999: 8.765 ms/op
                 listUser·p1.00:   8.765 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9124
  mean =      3.506 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 112 
    [2.000, 2.500) = 712 
    [2.500, 3.000) = 1739 
    [3.000, 3.500) = 2137 
    [3.500, 4.000) = 1927 
    [4.000, 4.500) = 1665 
    [4.500, 5.000) = 619 
    [5.000, 5.500) = 101 
    [5.500, 6.000) = 57 
    [6.000, 6.500) = 5 
    [6.500, 7.000) = 14 
    [7.000, 7.500) = 16 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      7.921 ms/op
     p(99.9900) =      8.765 ms/op
     p(99.9990) =      8.765 ms/op
     p(99.9999) =      8.765 ms/op
    p(100.0000) =      8.765 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.753          ops/ms
ClientSimple.existUser                       thrpt         12.091          ops/ms
ClientSimple.getUser                         thrpt         15.304          ops/ms
ClientSimple.listUser                        thrpt          8.456          ops/ms
ClientSimple.createUser                       avgt          2.250           ms/op
ClientSimple.existUser                        avgt          1.823           ms/op
ClientSimple.getUser                          avgt          1.984           ms/op
ClientSimple.listUser                         avgt          3.214           ms/op
ClientSimple.createUser                     sample  14528   2.201 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.593           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.085           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.968           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.906           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.123           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.461           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.713           ms/op
ClientSimple.existUser                      sample  17390   1.859 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.594           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.739           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.950           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.476           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.517           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.662           ms/op
ClientSimple.getUser                        sample  16570   1.928 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.810           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.886           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.654           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.490           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.747           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.857           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.878           ms/op
ClientSimple.listUser                       sample   9124   3.506 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.243           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.457           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.743           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.921           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.765           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.765           ms/op

Benchmark result is saved to 1711671297172.json
