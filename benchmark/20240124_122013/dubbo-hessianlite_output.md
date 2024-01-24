# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.225 ops/ms
Iteration   1: 6.443 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.443 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.014 ops/ms
Iteration   1: 13.327 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.327 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.241 ops/ms
Iteration   1: 9.063 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.063 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.533 ops/ms
Iteration   1: 3.799 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.799 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.133 ±(99.9%) 0.084 ms/op
Iteration   1: 3.267 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.267 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.422 ±(99.9%) 0.038 ms/op
Iteration   1: 1.794 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.794 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.494 ±(99.9%) 0.074 ms/op
Iteration   1: 3.332 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.332 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.303 ±(99.9%) 0.189 ms/op
Iteration   1: 8.120 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.120 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.125 ±(99.9%) 0.111 ms/op
Iteration   1: 2.957 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.769 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  26.727 ms/op
                 createUser·p0.9999: 27.124 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10795
  mean =      2.957 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1425 
    [ 2.500,  5.000) = 9259 
    [ 5.000,  7.500) = 79 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.769 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     26.727 ms/op
     p(99.9900) =     27.124 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.859 ±(99.9%) 0.058 ms/op
Iteration   1: 1.712 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   2.118 ms/op
                 existUser·p0.95:   2.327 ms/op
                 existUser·p0.99:   3.146 ms/op
                 existUser·p0.999:  4.907 ms/op
                 existUser·p0.9999: 7.050 ms/op
                 existUser·p1.00:   7.242 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18657
  mean =      1.712 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 18 
    [1.000, 1.500) = 3879 
    [1.500, 2.000) = 12270 
    [2.000, 2.500) = 1982 
    [2.500, 3.000) = 276 
    [3.000, 3.500) = 96 
    [3.500, 4.000) = 91 
    [4.000, 4.500) = 6 
    [4.500, 5.000) = 22 
    [5.000, 5.500) = 3 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.327 ms/op
     p(99.0000) =      3.146 ms/op
     p(99.9000) =      4.907 ms/op
     p(99.9900) =      7.050 ms/op
     p(99.9990) =      7.242 ms/op
     p(99.9999) =      7.242 ms/op
    p(100.0000) =      7.242 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.708 ±(99.9%) 0.112 ms/op
Iteration   1: 3.355 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  19.578 ms/op
                 getUser·p0.9999: 21.332 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9518
  mean =      3.355 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1213 
    [ 2.500,  5.000) = 8086 
    [ 5.000,  7.500) = 183 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     19.578 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.714 ±(99.9%) 0.474 ms/op
Iteration   1: 8.689 ±(99.9%) 0.136 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   8.471 ms/op
                 listUser·p0.90:   11.606 ms/op
                 listUser·p0.95:   12.861 ms/op
                 listUser·p0.99:   18.587 ms/op
                 listUser·p0.999:  21.843 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3675
  mean =      8.689 ±(99.9%) 0.136 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 123 
    [ 5.000,  7.500) = 1133 
    [ 7.500, 10.000) = 1482 
    [10.000, 12.500) = 714 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.769 ms/op
     p(50.0000) =      8.471 ms/op
     p(90.0000) =     11.606 ms/op
     p(95.0000) =     12.861 ms/op
     p(99.0000) =     18.587 ms/op
     p(99.9000) =     21.843 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.443          ops/ms
Client.existUser                       thrpt         13.327          ops/ms
Client.getUser                         thrpt          9.063          ops/ms
Client.listUser                        thrpt          3.799          ops/ms
Client.createUser                       avgt          3.267           ms/op
Client.existUser                        avgt          1.794           ms/op
Client.getUser                          avgt          3.332           ms/op
Client.listUser                         avgt          8.120           ms/op
Client.createUser                     sample  10795   2.957 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          0.900           ms/op
Client.createUser:createUser·p0.50    sample          2.769           ms/op
Client.createUser:createUser·p0.90    sample          3.465           ms/op
Client.createUser:createUser·p0.95    sample          3.850           ms/op
Client.createUser:createUser·p0.99    sample          5.030           ms/op
Client.createUser:createUser·p0.999   sample         26.727           ms/op
Client.createUser:createUser·p0.9999  sample         27.124           ms/op
Client.createUser:createUser·p1.00    sample         27.132           ms/op
Client.existUser                      sample  18657   1.712 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.673           ms/op
Client.existUser:existUser·p0.50      sample          1.620           ms/op
Client.existUser:existUser·p0.90      sample          2.118           ms/op
Client.existUser:existUser·p0.95      sample          2.327           ms/op
Client.existUser:existUser·p0.99      sample          3.146           ms/op
Client.existUser:existUser·p0.999     sample          4.907           ms/op
Client.existUser:existUser·p0.9999    sample          7.050           ms/op
Client.existUser:existUser·p1.00      sample          7.242           ms/op
Client.getUser                        sample   9518   3.355 ± 0.040   ms/op
Client.getUser:getUser·p0.00          sample          1.237           ms/op
Client.getUser:getUser·p0.50          sample          3.297           ms/op
Client.getUser:getUser·p0.90          sample          4.104           ms/op
Client.getUser:getUser·p0.95          sample          4.489           ms/op
Client.getUser:getUser·p0.99          sample          5.857           ms/op
Client.getUser:getUser·p0.999         sample         19.578           ms/op
Client.getUser:getUser·p0.9999        sample         21.332           ms/op
Client.getUser:getUser·p1.00          sample         21.332           ms/op
Client.listUser                       sample   3675   8.689 ± 0.136   ms/op
Client.listUser:listUser·p0.00        sample          2.769           ms/op
Client.listUser:listUser·p0.50        sample          8.471           ms/op
Client.listUser:listUser·p0.90        sample         11.606           ms/op
Client.listUser:listUser·p0.95        sample         12.861           ms/op
Client.listUser:listUser·p0.99        sample         18.587           ms/op
Client.listUser:listUser·p0.999       sample         21.843           ms/op
Client.listUser:listUser·p0.9999      sample         26.018           ms/op
Client.listUser:listUser·p1.00        sample         26.018           ms/op
