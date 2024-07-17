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
# Warmup Iteration   1: 0.862 ops/ms
Iteration   1: 5.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.733 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.228 ops/ms
Iteration   1: 14.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.397 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.315 ops/ms
Iteration   1: 14.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.534 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ops/ms
Iteration   1: 7.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.366 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.942 ±(99.9%) 0.068 ms/op
Iteration   1: 2.315 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.315 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ±(99.9%) 0.070 ms/op
Iteration   1: 1.822 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.822 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.503 ±(99.9%) 0.066 ms/op
Iteration   1: 2.131 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.131 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ±(99.9%) 0.092 ms/op
Iteration   1: 3.347 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.347 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.356 ±(99.9%) 0.091 ms/op
Iteration   1: 2.145 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   1.989 ms/op
                 createUser·p0.90:   2.580 ms/op
                 createUser·p0.95:   2.929 ms/op
                 createUser·p0.99:   6.362 ms/op
                 createUser·p0.999:  21.237 ms/op
                 createUser·p0.9999: 22.365 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14891
  mean =      2.145 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12994 
    [ 2.500,  5.000) = 1657 
    [ 5.000,  7.500) = 144 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      6.362 ms/op
     p(99.9000) =     21.237 ms/op
     p(99.9900) =     22.365 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 2.983 ±(99.9%) 0.063 ms/op
Iteration   1: 1.690 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.516 ms/op
                 existUser·p0.50:   1.571 ms/op
                 existUser·p0.90:   2.003 ms/op
                 existUser·p0.95:   2.195 ms/op
                 existUser·p0.99:   2.977 ms/op
                 existUser·p0.999:  18.612 ms/op
                 existUser·p0.9999: 18.714 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18914
  mean =      1.690 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 475 
    [ 1.250,  2.500) = 18035 
    [ 2.500,  3.750) = 254 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      1.571 ms/op
     p(90.0000) =      2.003 ms/op
     p(95.0000) =      2.195 ms/op
     p(99.0000) =      2.977 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     18.714 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.075 ms/op
Iteration   1: 1.968 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.773 ms/op
                 getUser·p0.99:   3.878 ms/op
                 getUser·p0.999:  16.988 ms/op
                 getUser·p0.9999: 17.587 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16574
  mean =      1.968 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1084 
    [ 1.250,  2.500) = 12798 
    [ 2.500,  3.750) = 2521 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      3.878 ms/op
     p(99.9000) =     16.988 ms/op
     p(99.9900) =     17.587 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.252 ±(99.9%) 0.125 ms/op
Iteration   1: 3.542 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.724 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.578 ms/op
                 listUser·p0.999:  7.493 ms/op
                 listUser·p0.9999: 9.765 ms/op
                 listUser·p1.00:   9.765 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9014
  mean =      3.542 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 72 
    [ 2.000,  3.000) = 1967 
    [ 3.000,  4.000) = 5370 
    [ 4.000,  5.000) = 1364 
    [ 5.000,  6.000) = 185 
    [ 6.000,  7.000) = 43 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.578 ms/op
     p(99.9000) =      7.493 ms/op
     p(99.9900) =      9.765 ms/op
     p(99.9990) =      9.765 ms/op
     p(99.9999) =      9.765 ms/op
    p(100.0000) =      9.765 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.733          ops/ms
ClientSimple.existUser                       thrpt         14.397          ops/ms
ClientSimple.getUser                         thrpt         14.534          ops/ms
ClientSimple.listUser                        thrpt          7.366          ops/ms
ClientSimple.createUser                       avgt          2.315           ms/op
ClientSimple.existUser                        avgt          1.822           ms/op
ClientSimple.getUser                          avgt          2.131           ms/op
ClientSimple.listUser                         avgt          3.347           ms/op
ClientSimple.createUser                     sample  14891   2.145 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.769           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.989           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.580           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.362           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.237           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.365           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.381           ms/op
ClientSimple.existUser                      sample  18914   1.690 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.516           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.571           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.003           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.977           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.612           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.714           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.743           ms/op
ClientSimple.getUser                        sample  16574   1.968 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.546           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.878           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.988           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.587           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.695           ms/op
ClientSimple.listUser                       sample   9014   3.542 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.724           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.592           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.578           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.493           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.765           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.765           ms/op

Benchmark result is saved to 1721218033484.json
