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
# Warmup Iteration   1: 1.799 ops/ms
Iteration   1: 6.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.607 ops/ms


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
# Warmup Iteration   1: 6.300 ops/ms
Iteration   1: 12.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.841 ops/ms


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
# Warmup Iteration   1: 5.533 ops/ms
Iteration   1: 11.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.559 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.261 ops/ms
Iteration   1: 8.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.531 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.075 ms/op
Iteration   1: 2.049 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.049 ms/op


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
# Warmup Iteration   1: 3.016 ±(99.9%) 0.047 ms/op
Iteration   1: 2.044 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.044 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.061 ms/op
Iteration   1: 2.101 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.101 ms/op


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.092 ms/op
Iteration   1: 3.543 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.543 ms/op


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
# Warmup Iteration   1: 3.405 ±(99.9%) 0.084 ms/op
Iteration   1: 2.244 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.488 ms/op
                 createUser·p0.50:   2.083 ms/op
                 createUser·p0.90:   2.904 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 20.631 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14245
  mean =      2.244 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11084 
    [ 2.500,  5.000) = 2995 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     20.631 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.901 ±(99.9%) 0.067 ms/op
Iteration   1: 1.739 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   1.665 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.327 ms/op
                 existUser·p0.99:   2.791 ms/op
                 existUser·p0.999:  10.349 ms/op
                 existUser·p0.9999: 10.868 ms/op
                 existUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18369
  mean =      1.739 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 913 
    [ 1.250,  2.500) = 17065 
    [ 2.500,  3.750) = 329 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.327 ms/op
     p(99.0000) =      2.791 ms/op
     p(99.9000) =     10.349 ms/op
     p(99.9900) =     10.868 ms/op
     p(99.9990) =     10.977 ms/op
     p(99.9999) =     10.977 ms/op
    p(100.0000) =     10.977 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.152 ±(99.9%) 0.110 ms/op
Iteration   1: 2.362 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.298 ms/op
                 getUser·p0.90:   2.839 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  15.773 ms/op
                 getUser·p0.9999: 16.622 ms/op
                 getUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13551
  mean =      2.362 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 9120 
    [ 2.500,  3.750) = 4018 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.298 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     15.773 ms/op
     p(99.9900) =     16.622 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.130 ms/op
Iteration   1: 3.075 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   4.826 ms/op
                 listUser·p0.999:  7.484 ms/op
                 listUser·p0.9999: 8.126 ms/op
                 listUser·p1.00:   8.143 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10394
  mean =      3.075 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 135 
    [1.500, 2.000) = 278 
    [2.000, 2.500) = 1097 
    [2.500, 3.000) = 4002 
    [3.000, 3.500) = 2437 
    [3.500, 4.000) = 1430 
    [4.000, 4.500) = 850 
    [4.500, 5.000) = 91 
    [5.000, 5.500) = 35 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 15 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 9 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      4.826 ms/op
     p(99.9000) =      7.484 ms/op
     p(99.9900) =      8.126 ms/op
     p(99.9990) =      8.143 ms/op
     p(99.9999) =      8.143 ms/op
    p(100.0000) =      8.143 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.607          ops/ms
ClientSimple.existUser                       thrpt         12.841          ops/ms
ClientSimple.getUser                         thrpt         11.559          ops/ms
ClientSimple.listUser                        thrpt          8.531          ops/ms
ClientSimple.createUser                       avgt          2.049           ms/op
ClientSimple.existUser                        avgt          2.044           ms/op
ClientSimple.getUser                          avgt          2.101           ms/op
ClientSimple.listUser                         avgt          3.543           ms/op
ClientSimple.createUser                     sample  14245   2.244 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.488           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.083           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.203           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.202           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.694           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.631           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.742           ms/op
ClientSimple.existUser                      sample  18369   1.739 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.684           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.665           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.191           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.791           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.349           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.868           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.977           ms/op
ClientSimple.getUser                        sample  13551   2.362 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.800           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.298           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.080           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.120           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.773           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.622           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.663           ms/op
ClientSimple.listUser                       sample  10394   3.075 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.159           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.966           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.994           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.826           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.484           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.126           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.143           ms/op

Benchmark result is saved to 1724825170725.json
