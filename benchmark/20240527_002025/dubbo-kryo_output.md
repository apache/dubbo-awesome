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
# Warmup Iteration   1: 1.657 ops/ms
Iteration   1: 6.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.326 ops/ms


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
# Warmup Iteration   1: 5.813 ops/ms
Iteration   1: 11.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.688 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.293 ops/ms
Iteration   1: 12.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.534 ops/ms


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
# Warmup Iteration   1: 4.811 ops/ms
Iteration   1: 8.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.558 ops/ms


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.068 ms/op
Iteration   1: 2.011 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.011 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.054 ms/op
Iteration   1: 1.753 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.753 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.062 ms/op
Iteration   1: 2.206 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.206 ms/op


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.101 ms/op
Iteration   1: 3.720 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.720 ms/op


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.088 ms/op
Iteration   1: 2.175 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   1.987 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.802 ms/op
                 createUser·p0.99:   9.810 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 21.941 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14726
  mean =      2.175 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12807 
    [ 2.500,  5.000) = 1610 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      9.810 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     21.941 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 2.959 ±(99.9%) 0.067 ms/op
Iteration   1: 1.727 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   1.569 ms/op
                 existUser·p0.90:   2.228 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   3.360 ms/op
                 existUser·p0.999:  27.162 ms/op
                 existUser·p0.9999: 28.031 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18533
  mean =      1.727 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17666 
    [ 2.500,  5.000) = 783 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      1.569 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      3.360 ms/op
     p(99.9000) =     27.162 ms/op
     p(99.9900) =     28.031 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.074 ms/op
Iteration   1: 1.995 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.650 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   3.292 ms/op
                 getUser·p0.999:  11.977 ms/op
                 getUser·p0.9999: 12.619 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16030
  mean =      1.995 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 13144 
    [ 2.500,  3.750) = 2693 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.292 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     12.619 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.142 ms/op
Iteration   1: 3.469 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  12.791 ms/op
                 listUser·p0.9999: 13.173 ms/op
                 listUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9309
  mean =      3.469 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 1357 
    [ 2.500,  3.750) = 4580 
    [ 3.750,  5.000) = 2914 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     12.791 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.326          ops/ms
ClientSimple.existUser                       thrpt         11.688          ops/ms
ClientSimple.getUser                         thrpt         12.534          ops/ms
ClientSimple.listUser                        thrpt          8.558          ops/ms
ClientSimple.createUser                       avgt          2.011           ms/op
ClientSimple.existUser                        avgt          1.753           ms/op
ClientSimple.getUser                          avgt          2.206           ms/op
ClientSimple.listUser                         avgt          3.720           ms/op
ClientSimple.createUser                     sample  14726   2.175 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.552           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.987           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.810           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.299           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.941           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.282           ms/op
ClientSimple.existUser                      sample  18533   1.727 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.800           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.569           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.360           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.162           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.031           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.115           ms/op
ClientSimple.getUser                        sample  16030   1.995 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.515           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.292           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.977           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.619           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.698           ms/op
ClientSimple.listUser                       sample   9309   3.469 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.898           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.531           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.463           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.791           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.173           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.173           ms/op

Benchmark result is saved to 1716768968481.json
