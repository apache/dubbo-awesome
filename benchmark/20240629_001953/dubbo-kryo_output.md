# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.765 ops/ms
Iteration   1: 7.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.039 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.010 ops/ms
Iteration   1: 11.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.726 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.778 ops/ms
Iteration   1: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.497 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.592 ops/ms
Iteration   1: 8.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.063 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ±(99.9%) 0.061 ms/op
Iteration   1: 2.171 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.171 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.526 ±(99.9%) 0.051 ms/op
Iteration   1: 1.798 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.798 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.254 ±(99.9%) 0.060 ms/op
Iteration   1: 1.905 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.905 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.794 ±(99.9%) 0.105 ms/op
Iteration   1: 3.358 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.358 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.345 ±(99.9%) 0.085 ms/op
Iteration   1: 2.348 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   2.191 ms/op
                 createUser·p0.90:   2.691 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   4.861 ms/op
                 createUser·p0.999:  27.046 ms/op
                 createUser·p0.9999: 27.979 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13611
  mean =      2.348 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10747 
    [ 2.500,  5.000) = 2732 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      4.861 ms/op
     p(99.9000) =     27.046 ms/op
     p(99.9900) =     27.979 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.371 ±(99.9%) 0.084 ms/op
Iteration   1: 1.926 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   3.857 ms/op
                 existUser·p0.999:  15.630 ms/op
                 existUser·p0.9999: 16.504 ms/op
                 existUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16618
  mean =      1.926 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 445 
    [ 1.250,  2.500) = 14346 
    [ 2.500,  3.750) = 1652 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.857 ms/op
     p(99.9000) =     15.630 ms/op
     p(99.9900) =     16.504 ms/op
     p(99.9990) =     16.548 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.308 ±(99.9%) 0.075 ms/op
Iteration   1: 2.022 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.513 ms/op
                 getUser·p0.50:   1.786 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.679 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 25.934 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15809
  mean =      2.022 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14395 
    [ 2.500,  5.000) = 1244 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     25.934 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.374 ±(99.9%) 0.128 ms/op
Iteration   1: 3.196 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.111 ms/op
                 listUser·p0.999:  24.183 ms/op
                 listUser·p0.9999: 24.902 ms/op
                 listUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10067
  mean =      3.196 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1282 
    [ 2.500,  5.000) = 8534 
    [ 5.000,  7.500) = 210 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     24.902 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.039          ops/ms
ClientSimple.existUser                       thrpt         11.726          ops/ms
ClientSimple.getUser                         thrpt         12.497          ops/ms
ClientSimple.listUser                        thrpt          8.063          ops/ms
ClientSimple.createUser                       avgt          2.171           ms/op
ClientSimple.existUser                        avgt          1.798           ms/op
ClientSimple.getUser                          avgt          1.905           ms/op
ClientSimple.listUser                         avgt          3.358           ms/op
ClientSimple.createUser                     sample  13611   2.348 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.450           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.191           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.861           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.046           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.979           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.180           ms/op
ClientSimple.existUser                      sample  16618   1.926 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.801           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.784           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.798           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.857           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.630           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.504           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.548           ms/op
ClientSimple.getUser                        sample  15809   2.022 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.513           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.786           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.226           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.069           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.934           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.590           ms/op
ClientSimple.listUser                       sample  10067   3.196 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.949           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.945           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.111           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.183           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.902           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.904           ms/op

Benchmark result is saved to 1719620139661.json
