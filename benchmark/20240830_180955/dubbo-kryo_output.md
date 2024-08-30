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
# Warmup Iteration   1: 1.810 ops/ms
Iteration   1: 6.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.065 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.745 ops/ms
Iteration   1: 12.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.364 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.217 ops/ms
Iteration   1: 11.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.856 ops/ms


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
# Warmup Iteration   1: 4.974 ops/ms
Iteration   1: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.029 ops/ms


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.085 ms/op
Iteration   1: 2.006 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.006 ms/op


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
# Warmup Iteration   1: 3.173 ±(99.9%) 0.062 ms/op
Iteration   1: 1.761 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.761 ms/op


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
# Warmup Iteration   1: 3.380 ±(99.9%) 0.061 ms/op
Iteration   1: 2.328 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.328 ms/op


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.087 ms/op
Iteration   1: 3.487 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.487 ms/op


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
# Warmup Iteration   1: 3.440 ±(99.9%) 0.085 ms/op
Iteration   1: 2.028 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.497 ms/op
                 createUser·p0.50:   1.907 ms/op
                 createUser·p0.90:   2.417 ms/op
                 createUser·p0.95:   2.638 ms/op
                 createUser·p0.99:   6.556 ms/op
                 createUser·p0.999:  17.939 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15766
  mean =      2.028 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14613 
    [ 2.500,  5.000) = 938 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      6.556 ms/op
     p(99.9000) =     17.939 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 2.957 ±(99.9%) 0.071 ms/op
Iteration   1: 1.880 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   3.660 ms/op
                 existUser·p0.999:  17.677 ms/op
                 existUser·p0.9999: 18.196 ms/op
                 existUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17091
  mean =      1.880 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 304 
    [ 1.250,  2.500) = 15797 
    [ 2.500,  3.750) = 823 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      3.660 ms/op
     p(99.9000) =     17.677 ms/op
     p(99.9900) =     18.196 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.335 ±(99.9%) 0.108 ms/op
Iteration   1: 1.984 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.572 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  11.842 ms/op
                 getUser·p0.9999: 12.316 ms/op
                 getUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16105
  mean =      1.984 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 14915 
    [ 2.500,  3.750) = 824 
    [ 3.750,  5.000) = 195 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =     11.842 ms/op
     p(99.9900) =     12.316 ms/op
     p(99.9990) =     12.386 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.133 ms/op
Iteration   1: 3.114 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.138 ms/op
                 listUser·p0.999:  6.255 ms/op
                 listUser·p0.9999: 7.714 ms/op
                 listUser·p1.00:   7.717 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10389
  mean =      3.114 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 175 
    [2.000, 2.500) = 1545 
    [2.500, 3.000) = 3716 
    [3.000, 3.500) = 2062 
    [3.500, 4.000) = 1625 
    [4.000, 4.500) = 948 
    [4.500, 5.000) = 180 
    [5.000, 5.500) = 61 
    [5.500, 6.000) = 48 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.138 ms/op
     p(99.9000) =      6.255 ms/op
     p(99.9900) =      7.714 ms/op
     p(99.9990) =      7.717 ms/op
     p(99.9999) =      7.717 ms/op
    p(100.0000) =      7.717 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.065          ops/ms
ClientSimple.existUser                       thrpt         12.364          ops/ms
ClientSimple.getUser                         thrpt         11.856          ops/ms
ClientSimple.listUser                        thrpt          8.029          ops/ms
ClientSimple.createUser                       avgt          2.006           ms/op
ClientSimple.existUser                        avgt          1.761           ms/op
ClientSimple.getUser                          avgt          2.328           ms/op
ClientSimple.listUser                         avgt          3.487           ms/op
ClientSimple.createUser                     sample  15766   2.028 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.497           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.907           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.556           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.939           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.463           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.463           ms/op
ClientSimple.existUser                      sample  17091   1.880 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.715           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.660           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.677           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.196           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.219           ms/op
ClientSimple.getUser                        sample  16105   1.984 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.862           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.399           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.842           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.316           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.386           ms/op
ClientSimple.listUser                       sample  10389   3.114 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.998           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.953           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.138           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.255           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.714           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.717           ms/op

Benchmark result is saved to 1725041139472.json
