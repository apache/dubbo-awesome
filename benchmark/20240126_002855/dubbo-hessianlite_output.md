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
# Warmup Iteration   1: 1.980 ops/ms
Iteration   1: 5.764 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.764 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.245 ops/ms
Iteration   1: 10.586 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.586 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ops/ms
Iteration   1: 8.864 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.864 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.030 ops/ms
Iteration   1: 3.154 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.154 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.293 ±(99.9%) 0.086 ms/op
Iteration   1: 3.526 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.526 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.053 ms/op
Iteration   1: 2.004 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.004 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ±(99.9%) 0.061 ms/op
Iteration   1: 3.292 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.292 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.571 ±(99.9%) 0.357 ms/op
Iteration   1: 8.482 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.482 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.494 ±(99.9%) 0.136 ms/op
Iteration   1: 3.653 ±(99.9%) 0.113 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   27.428 ms/op
                 createUser·p0.999:  38.195 ms/op
                 createUser·p0.9999: 40.501 ms/op
                 createUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8798
  mean =      3.653 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8451 
    [ 5.000, 10.000) = 251 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =     27.428 ms/op
     p(99.9000) =     38.195 ms/op
     p(99.9900) =     40.501 ms/op
     p(99.9990) =     40.501 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.402 ±(99.9%) 0.086 ms/op
Iteration   1: 2.238 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   2.224 ms/op
                 existUser·p0.90:   2.744 ms/op
                 existUser·p0.95:   2.957 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  5.526 ms/op
                 existUser·p0.9999: 7.000 ms/op
                 existUser·p1.00:   7.913 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14270
  mean =      2.238 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 40 
    [1.000, 1.500) = 515 
    [1.500, 2.000) = 4031 
    [2.000, 2.500) = 6291 
    [2.500, 3.000) = 2778 
    [3.000, 3.500) = 403 
    [3.500, 4.000) = 56 
    [4.000, 4.500) = 74 
    [4.500, 5.000) = 22 
    [5.000, 5.500) = 46 
    [5.500, 6.000) = 13 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      5.526 ms/op
     p(99.9900) =      7.000 ms/op
     p(99.9990) =      7.913 ms/op
     p(99.9999) =      7.913 ms/op
    p(100.0000) =      7.913 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.618 ±(99.9%) 0.117 ms/op
Iteration   1: 3.105 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 19.490 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10345
  mean =      3.105 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 2053 
    [ 2.500,  3.750) = 6899 
    [ 3.750,  5.000) = 1202 
    [ 5.000,  6.250) = 109 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     19.490 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.958 ±(99.9%) 0.481 ms/op
Iteration   1: 9.053 ±(99.9%) 0.163 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   8.544 ms/op
                 listUser·p0.90:   12.337 ms/op
                 listUser·p0.95:   13.524 ms/op
                 listUser·p0.99:   21.187 ms/op
                 listUser·p0.999:  28.936 ms/op
                 listUser·p0.9999: 33.620 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3570
  mean =      9.053 ±(99.9%) 0.163 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 119 
    [ 5.000,  7.500) = 942 
    [ 7.500, 10.000) = 1460 
    [10.000, 12.500) = 739 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.327 ms/op
     p(50.0000) =      8.544 ms/op
     p(90.0000) =     12.337 ms/op
     p(95.0000) =     13.524 ms/op
     p(99.0000) =     21.187 ms/op
     p(99.9000) =     28.936 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.764          ops/ms
Client.existUser                       thrpt         10.586          ops/ms
Client.getUser                         thrpt          8.864          ops/ms
Client.listUser                        thrpt          3.154          ops/ms
Client.createUser                       avgt          3.526           ms/op
Client.existUser                        avgt          2.004           ms/op
Client.getUser                          avgt          3.292           ms/op
Client.listUser                         avgt          8.482           ms/op
Client.createUser                     sample   8798   3.653 ± 0.113   ms/op
Client.createUser:createUser·p0.00    sample          0.772           ms/op
Client.createUser:createUser·p0.50    sample          3.269           ms/op
Client.createUser:createUser·p0.90    sample          4.227           ms/op
Client.createUser:createUser·p0.95    sample          4.825           ms/op
Client.createUser:createUser·p0.99    sample         27.428           ms/op
Client.createUser:createUser·p0.999   sample         38.195           ms/op
Client.createUser:createUser·p0.9999  sample         40.501           ms/op
Client.createUser:createUser·p1.00    sample         40.501           ms/op
Client.existUser                      sample  14270   2.238 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.504           ms/op
Client.existUser:existUser·p0.50      sample          2.224           ms/op
Client.existUser:existUser·p0.90      sample          2.744           ms/op
Client.existUser:existUser·p0.95      sample          2.957           ms/op
Client.existUser:existUser·p0.99      sample          4.133           ms/op
Client.existUser:existUser·p0.999     sample          5.526           ms/op
Client.existUser:existUser·p0.9999    sample          7.000           ms/op
Client.existUser:existUser·p1.00      sample          7.913           ms/op
Client.getUser                        sample  10345   3.105 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          0.658           ms/op
Client.getUser:getUser·p0.50          sample          2.966           ms/op
Client.getUser:getUser·p0.90          sample          3.871           ms/op
Client.getUser:getUser·p0.95          sample          4.235           ms/op
Client.getUser:getUser·p0.99          sample          5.972           ms/op
Client.getUser:getUser·p0.999         sample         17.302           ms/op
Client.getUser:getUser·p0.9999        sample         19.490           ms/op
Client.getUser:getUser·p1.00          sample         19.497           ms/op
Client.listUser                       sample   3570   9.053 ± 0.163   ms/op
Client.listUser:listUser·p0.00        sample          2.327           ms/op
Client.listUser:listUser·p0.50        sample          8.544           ms/op
Client.listUser:listUser·p0.90        sample         12.337           ms/op
Client.listUser:listUser·p0.95        sample         13.524           ms/op
Client.listUser:listUser·p0.99        sample         21.187           ms/op
Client.listUser:listUser·p0.999       sample         28.936           ms/op
Client.listUser:listUser·p0.9999      sample         33.620           ms/op
Client.listUser:listUser·p1.00        sample         33.620           ms/op
