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
# Warmup Iteration   1: 1.505 ops/ms
Iteration   1: 7.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.188 ops/ms


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
# Warmup Iteration   1: 6.176 ops/ms
Iteration   1: 13.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.002 ops/ms


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
# Warmup Iteration   1: 7.492 ops/ms
Iteration   1: 14.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.009 ops/ms


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
# Warmup Iteration   1: 4.386 ops/ms
Iteration   1: 8.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.764 ops/ms


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.078 ms/op
Iteration   1: 2.201 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.201 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.061 ms/op
Iteration   1: 2.005 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.005 ms/op


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
# Warmup Iteration   1: 3.486 ±(99.9%) 0.066 ms/op
Iteration   1: 2.176 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.176 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.085 ms/op
Iteration   1: 3.418 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.418 ms/op


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
# Warmup Iteration   1: 3.559 ±(99.9%) 0.086 ms/op
Iteration   1: 2.138 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   1.831 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   10.117 ms/op
                 createUser·p0.999:  27.429 ms/op
                 createUser·p0.9999: 28.362 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14947
  mean =      2.138 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13377 
    [ 2.500,  5.000) = 1315 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =     10.117 ms/op
     p(99.9000) =     27.429 ms/op
     p(99.9900) =     28.362 ms/op
     p(99.9990) =     28.475 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.089 ms/op
Iteration   1: 1.963 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   1.907 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.215 ms/op
                 existUser·p0.999:  13.582 ms/op
                 existUser·p0.9999: 13.928 ms/op
                 existUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16385
  mean =      1.963 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 14578 
    [ 2.500,  3.750) = 1482 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.215 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     13.928 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.510 ±(99.9%) 0.101 ms/op
Iteration   1: 1.854 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   1.761 ms/op
                 getUser·p0.90:   2.065 ms/op
                 getUser·p0.95:   2.290 ms/op
                 getUser·p0.99:   3.002 ms/op
                 getUser·p0.999:  14.451 ms/op
                 getUser·p0.9999: 14.828 ms/op
                 getUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17378
  mean =      1.854 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 16806 
    [ 2.500,  3.750) = 411 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.065 ms/op
     p(95.0000) =      2.290 ms/op
     p(99.0000) =      3.002 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     14.828 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.122 ms/op
Iteration   1: 3.395 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.183 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.234 ms/op
                 listUser·p0.999:  26.804 ms/op
                 listUser·p0.9999: 27.394 ms/op
                 listUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9417
  mean =      3.395 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 806 
    [ 2.500,  5.000) = 8308 
    [ 5.000,  7.500) = 232 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.188          ops/ms
ClientSimple.existUser                       thrpt         13.002          ops/ms
ClientSimple.getUser                         thrpt         14.009          ops/ms
ClientSimple.listUser                        thrpt          8.764          ops/ms
ClientSimple.createUser                       avgt          2.201           ms/op
ClientSimple.existUser                        avgt          2.005           ms/op
ClientSimple.getUser                          avgt          2.176           ms/op
ClientSimple.listUser                         avgt          3.418           ms/op
ClientSimple.createUser                     sample  14947   2.138 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.758           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.831           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.117           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.429           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.362           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.475           ms/op
ClientSimple.existUser                      sample  16385   1.963 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.598           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.907           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.215           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.582           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.928           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.959           ms/op
ClientSimple.getUser                        sample  17378   1.854 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.935           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.761           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.065           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.290           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.002           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.451           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.828           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.877           ms/op
ClientSimple.listUser                       sample   9417   3.395 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.462           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.183           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.234           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.804           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.394           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.394           ms/op

Benchmark result is saved to 1723637236089.json
