# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.084 ops/ms
Iteration   1: 2.386 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.386 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 2.146 ops/ms
Iteration   1: 6.648 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.648 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.710 ops/ms
Iteration   1: 5.502 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.502 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.822 ops/ms
Iteration   1: 1.369 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.369 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 16.535 ±(99.9%) 0.306 ms/op
Iteration   1: 7.334 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.334 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.479 ±(99.9%) 0.068 ms/op
Iteration   1: 3.664 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.856 ±(99.9%) 0.182 ms/op
Iteration   1: 4.667 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.667 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 27.674 ±(99.9%) 0.435 ms/op
Iteration   1: 15.354 ±(99.9%) 0.144 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.354 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.467 ±(99.9%) 0.409 ms/op
Iteration   1: 5.588 ±(99.9%) 0.079 ms/op
                 createUser·p0.00:   2.154 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.185 ms/op
                 createUser·p0.95:   8.520 ms/op
                 createUser·p0.99:   15.525 ms/op
                 createUser·p0.999:  16.869 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5734
  mean =      5.588 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3 
    [ 2.500,  3.750) = 54 
    [ 3.750,  5.000) = 1645 
    [ 5.000,  6.250) = 3509 
    [ 6.250,  7.500) = 189 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      8.520 ms/op
     p(99.0000) =     15.525 ms/op
     p(99.9000) =     16.869 ms/op
     p(99.9900) =     18.186 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.384 ±(99.9%) 0.156 ms/op
Iteration   1: 3.133 ±(99.9%) 0.053 ms/op
                 existUser·p0.00:   0.322 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.594 ms/op
                 existUser·p0.99:   10.387 ms/op
                 existUser·p0.999:  21.889 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10248
  mean =      3.133 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 981 
    [ 2.500,  5.000) = 8953 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.322 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.594 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 12.341 ±(99.9%) 0.326 ms/op
Iteration   1: 4.241 ±(99.9%) 0.074 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   12.075 ms/op
                 getUser·p0.999:  26.950 ms/op
                 getUser·p0.9999: 27.263 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7539
  mean =      4.241 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 6903 
    [ 5.000,  7.500) = 409 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     26.950 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.377 ±(99.9%) 0.719 ms/op
Iteration   1: 15.665 ±(99.9%) 0.174 ms/op
                 listUser·p0.00:   11.878 ms/op
                 listUser·p0.50:   14.942 ms/op
                 listUser·p0.90:   17.131 ms/op
                 listUser·p0.95:   21.027 ms/op
                 listUser·p0.99:   26.435 ms/op
                 listUser·p0.999:  32.824 ms/op
                 listUser·p0.9999: 33.194 ms/op
                 listUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2041
  mean =     15.665 ±(99.9%) 0.174 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 1126 
    [15.000, 17.500) = 731 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =     11.878 ms/op
     p(50.0000) =     14.942 ms/op
     p(90.0000) =     17.131 ms/op
     p(95.0000) =     21.027 ms/op
     p(99.0000) =     26.435 ms/op
     p(99.9000) =     32.824 ms/op
     p(99.9900) =     33.194 ms/op
     p(99.9990) =     33.194 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.386          ops/ms
Client.existUser                       thrpt          6.648          ops/ms
Client.getUser                         thrpt          5.502          ops/ms
Client.listUser                        thrpt          1.369          ops/ms
Client.createUser                       avgt          7.334           ms/op
Client.existUser                        avgt          3.664           ms/op
Client.getUser                          avgt          4.667           ms/op
Client.listUser                         avgt         15.354           ms/op
Client.createUser                     sample   5734   5.588 ± 0.079   ms/op
Client.createUser:createUser·p0.00    sample          2.154           ms/op
Client.createUser:createUser·p0.50    sample          5.243           ms/op
Client.createUser:createUser·p0.90    sample          6.185           ms/op
Client.createUser:createUser·p0.95    sample          8.520           ms/op
Client.createUser:createUser·p0.99    sample         15.525           ms/op
Client.createUser:createUser·p0.999   sample         16.869           ms/op
Client.createUser:createUser·p0.9999  sample         18.186           ms/op
Client.createUser:createUser·p1.00    sample         18.186           ms/op
Client.existUser                      sample  10248   3.133 ± 0.053   ms/op
Client.existUser:existUser·p0.00      sample          0.322           ms/op
Client.existUser:existUser·p0.50      sample          2.974           ms/op
Client.existUser:existUser·p0.90      sample          3.305           ms/op
Client.existUser:existUser·p0.95      sample          3.594           ms/op
Client.existUser:existUser·p0.99      sample         10.387           ms/op
Client.existUser:existUser·p0.999     sample         21.889           ms/op
Client.existUser:existUser·p0.9999    sample         21.987           ms/op
Client.existUser:existUser·p1.00      sample         21.987           ms/op
Client.getUser                        sample   7539   4.241 ± 0.074   ms/op
Client.getUser:getUser·p0.00          sample          1.085           ms/op
Client.getUser:getUser·p0.50          sample          3.908           ms/op
Client.getUser:getUser·p0.90          sample          4.866           ms/op
Client.getUser:getUser·p0.95          sample          5.579           ms/op
Client.getUser:getUser·p0.99          sample         12.075           ms/op
Client.getUser:getUser·p0.999         sample         26.950           ms/op
Client.getUser:getUser·p0.9999        sample         27.263           ms/op
Client.getUser:getUser·p1.00          sample         27.263           ms/op
Client.listUser                       sample   2041  15.665 ± 0.174   ms/op
Client.listUser:listUser·p0.00        sample         11.878           ms/op
Client.listUser:listUser·p0.50        sample         14.942           ms/op
Client.listUser:listUser·p0.90        sample         17.131           ms/op
Client.listUser:listUser·p0.95        sample         21.027           ms/op
Client.listUser:listUser·p0.99        sample         26.435           ms/op
Client.listUser:listUser·p0.999       sample         32.824           ms/op
Client.listUser:listUser·p0.9999      sample         33.194           ms/op
Client.listUser:listUser·p1.00        sample         33.194           ms/op
