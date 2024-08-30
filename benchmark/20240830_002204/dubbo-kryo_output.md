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
# Warmup Iteration   1: 1.754 ops/ms
Iteration   1: 6.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.641 ops/ms


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
# Warmup Iteration   1: 6.346 ops/ms
Iteration   1: 12.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.299 ops/ms


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
# Warmup Iteration   1: 5.868 ops/ms
Iteration   1: 12.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.734 ops/ms


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
# Warmup Iteration   1: 4.977 ops/ms
Iteration   1: 8.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.133 ops/ms


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.078 ms/op
Iteration   1: 2.157 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.157 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ±(99.9%) 0.066 ms/op
Iteration   1: 1.737 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.737 ms/op


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
# Warmup Iteration   1: 3.118 ±(99.9%) 0.055 ms/op
Iteration   1: 2.177 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.177 ms/op


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
# Warmup Iteration   1: 4.409 ±(99.9%) 0.089 ms/op
Iteration   1: 3.735 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.735 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.197 ±(99.9%) 0.079 ms/op
Iteration   1: 2.170 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.032 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.634 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  28.681 ms/op
                 createUser·p0.9999: 28.990 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14727
  mean =      2.170 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13482 
    [ 2.500,  5.000) = 1125 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     28.681 ms/op
     p(99.9900) =     28.990 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.071 ms/op
Iteration   1: 2.003 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   1.864 ms/op
                 existUser·p0.90:   2.740 ms/op
                 existUser·p0.95:   2.916 ms/op
                 existUser·p0.99:   3.581 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 13.134 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15972
  mean =      2.003 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 413 
    [ 1.250,  2.500) = 12889 
    [ 2.500,  3.750) = 2519 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      3.581 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     13.134 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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
# Warmup Iteration   1: 3.240 ±(99.9%) 0.090 ms/op
Iteration   1: 1.955 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   1.778 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   3.390 ms/op
                 getUser·p0.999:  35.717 ms/op
                 getUser·p0.9999: 36.641 ms/op
                 getUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16339
  mean =      1.955 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15181 
    [ 2.500,  5.000) = 1052 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.390 ms/op
     p(99.9000) =     35.717 ms/op
     p(99.9900) =     36.641 ms/op
     p(99.9990) =     36.766 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.116 ms/op
Iteration   1: 3.291 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.146 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.632 ms/op
                 listUser·p0.999:  22.938 ms/op
                 listUser·p0.9999: 23.167 ms/op
                 listUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9716
  mean =      3.291 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1326 
    [ 2.500,  5.000) = 8260 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.632 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.641          ops/ms
ClientSimple.existUser                       thrpt         12.299          ops/ms
ClientSimple.getUser                         thrpt         12.734          ops/ms
ClientSimple.listUser                        thrpt          8.133          ops/ms
ClientSimple.createUser                       avgt          2.157           ms/op
ClientSimple.existUser                        avgt          1.737           ms/op
ClientSimple.getUser                          avgt          2.177           ms/op
ClientSimple.listUser                         avgt          3.735           ms/op
ClientSimple.createUser                     sample  14727   2.170 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.796           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.032           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.276           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.681           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.990           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.098           ms/op
ClientSimple.existUser                      sample  15972   2.003 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.648           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.864           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.916           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.581           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.321           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.134           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.222           ms/op
ClientSimple.getUser                        sample  16339   1.955 ± 0.042   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.713           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.778           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.390           ms/op
ClientSimple.getUser:getUser·p0.999         sample         35.717           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         36.641           ms/op
ClientSimple.getUser:getUser·p1.00          sample         36.766           ms/op
ClientSimple.listUser                       sample   9716   3.291 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.057           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.146           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.632           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.938           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.167           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.167           ms/op

Benchmark result is saved to 1724977061441.json
