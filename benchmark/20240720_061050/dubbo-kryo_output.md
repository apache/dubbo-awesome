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
# Warmup Iteration   1: 1.951 ops/ms
Iteration   1: 6.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.790 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.934 ops/ms
Iteration   1: 12.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.214 ops/ms


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
# Warmup Iteration   1: 5.833 ops/ms
Iteration   1: 13.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.758 ops/ms


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
# Warmup Iteration   1: 5.264 ops/ms
Iteration   1: 8.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.755 ops/ms


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.095 ms/op
Iteration   1: 2.278 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.278 ms/op


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
# Warmup Iteration   1: 2.993 ±(99.9%) 0.045 ms/op
Iteration   1: 2.018 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.018 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.306 ±(99.9%) 0.057 ms/op
Iteration   1: 1.927 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.927 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.412 ±(99.9%) 0.091 ms/op
Iteration   1: 3.100 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.100 ms/op


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.129 ms/op
Iteration   1: 2.603 ±(99.9%) 0.177 ms/op
                 createUser·p0.00:   0.330 ms/op
                 createUser·p0.50:   2.200 ms/op
                 createUser·p0.90:   2.851 ms/op
                 createUser·p0.95:   3.164 ms/op
                 createUser·p0.99:   10.800 ms/op
                 createUser·p0.999:  116.697 ms/op
                 createUser·p0.9999: 139.865 ms/op
                 createUser·p1.00:   139.985 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12289
  mean =      2.603 ±(99.9%) 0.177 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 12229 
    [ 12.500,  25.000) = 27 
    [ 25.000,  37.500) = 1 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 16 
    [112.500, 125.000) = 12 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 4 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.330 ms/op
     p(50.0000) =      2.200 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      3.164 ms/op
     p(99.0000) =     10.800 ms/op
     p(99.9000) =    116.697 ms/op
     p(99.9900) =    139.865 ms/op
     p(99.9990) =    139.985 ms/op
     p(99.9999) =    139.985 ms/op
    p(100.0000) =    139.985 ms/op


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
# Warmup Iteration   1: 3.180 ±(99.9%) 0.077 ms/op
Iteration   1: 1.900 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.245 ms/op
                 existUser·p0.95:   2.497 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  18.092 ms/op
                 existUser·p0.9999: 19.212 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16888
  mean =      1.900 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 15897 
    [ 2.500,  3.750) = 614 
    [ 3.750,  5.000) = 150 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.497 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =     18.092 ms/op
     p(99.9900) =     19.212 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.075 ms/op
Iteration   1: 1.930 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   1.759 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.736 ms/op
                 getUser·p0.99:   4.101 ms/op
                 getUser·p0.999:  10.928 ms/op
                 getUser·p0.9999: 11.694 ms/op
                 getUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16572
  mean =      1.930 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 345 
    [ 1.250,  2.500) = 14116 
    [ 2.500,  3.750) = 1903 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      4.101 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     11.694 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.131 ms/op
Iteration   1: 3.359 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.805 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  17.153 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9529
  mean =      3.359 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 919 
    [ 2.500,  3.750) = 5685 
    [ 3.750,  5.000) = 2616 
    [ 5.000,  6.250) = 240 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.805 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     17.153 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.790          ops/ms
ClientSimple.existUser                       thrpt          12.214          ops/ms
ClientSimple.getUser                         thrpt          13.758          ops/ms
ClientSimple.listUser                        thrpt           8.755          ops/ms
ClientSimple.createUser                       avgt           2.278           ms/op
ClientSimple.existUser                        avgt           2.018           ms/op
ClientSimple.getUser                          avgt           1.927           ms/op
ClientSimple.listUser                         avgt           3.100           ms/op
ClientSimple.createUser                     sample  12289    2.603 ± 0.177   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.330           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.200           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.851           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.164           ms/op
ClientSimple.createUser:createUser·p0.99    sample          10.800           ms/op
ClientSimple.createUser:createUser·p0.999   sample         116.697           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         139.865           ms/op
ClientSimple.createUser:createUser·p1.00    sample         139.985           ms/op
ClientSimple.existUser                      sample  16888    1.900 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.816           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.245           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.497           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.030           ms/op
ClientSimple.existUser:existUser·p0.999     sample          18.092           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          19.212           ms/op
ClientSimple.existUser:existUser·p1.00      sample          19.235           ms/op
ClientSimple.getUser                        sample  16572    1.930 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.584           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.759           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.736           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.101           ms/op
ClientSimple.getUser:getUser·p0.999         sample          10.928           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          11.694           ms/op
ClientSimple.getUser:getUser·p1.00          sample          11.813           ms/op
ClientSimple.listUser                       sample   9529    3.359 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.409           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.497           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.805           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.562           ms/op
ClientSimple.listUser:listUser·p0.999       sample          17.153           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          17.269           ms/op
ClientSimple.listUser:listUser·p1.00        sample          17.269           ms/op

Benchmark result is saved to 1721455585591.json
