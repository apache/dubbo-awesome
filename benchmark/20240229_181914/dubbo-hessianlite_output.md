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
# Warmup Iteration   1: 1.969 ops/ms
Iteration   1: 5.180 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.180 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.571 ops/ms
Iteration   1: 11.073 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.073 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.034 ops/ms
Iteration   1: 7.029 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.029 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.701 ops/ms
Iteration   1: 3.054 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.054 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.873 ±(99.9%) 0.098 ms/op
Iteration   1: 3.636 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.636 ms/op


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
# Warmup Iteration   1: 3.589 ±(99.9%) 0.038 ms/op
Iteration   1: 2.220 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.220 ms/op


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
# Warmup Iteration   1: 5.490 ±(99.9%) 0.071 ms/op
Iteration   1: 3.488 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.488 ms/op


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
# Warmup Iteration   1: 15.659 ±(99.9%) 0.306 ms/op
Iteration   1: 9.134 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.134 ms/op


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
# Warmup Iteration   1: 5.953 ±(99.9%) 0.175 ms/op
Iteration   1: 3.736 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.599 ms/op
                 createUser·p0.95:   5.448 ms/op
                 createUser·p0.99:   11.034 ms/op
                 createUser·p0.999:  28.213 ms/op
                 createUser·p0.9999: 28.508 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8565
  mean =      3.736 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 298 
    [ 2.500,  5.000) = 7739 
    [ 5.000,  7.500) = 333 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.599 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =     11.034 ms/op
     p(99.9000) =     28.213 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.096 ms/op
Iteration   1: 2.220 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.079 ms/op
                 existUser·p0.90:   2.724 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   4.180 ms/op
                 existUser·p0.999:  15.794 ms/op
                 existUser·p0.9999: 17.373 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14522
  mean =      2.220 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 11746 
    [ 2.500,  3.750) = 2543 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      4.180 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     17.373 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.901 ±(99.9%) 0.135 ms/op
Iteration   1: 3.842 ±(99.9%) 0.203 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.848 ms/op
                 getUser·p0.99:   19.411 ms/op
                 getUser·p0.999:  94.845 ms/op
                 getUser·p0.9999: 114.819 ms/op
                 getUser·p1.00:   114.819 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8462
  mean =      3.842 ±(99.9%) 0.203 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 8338 
    [ 12.500,  25.000) = 78 
    [ 25.000,  37.500) = 14 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 17 
    [ 87.500, 100.000) = 11 
    [100.000, 112.500) = 2 
    [112.500, 125.000) = 2 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.848 ms/op
     p(99.0000) =     19.411 ms/op
     p(99.9000) =     94.845 ms/op
     p(99.9900) =    114.819 ms/op
     p(99.9990) =    114.819 ms/op
     p(99.9999) =    114.819 ms/op
    p(100.0000) =    114.819 ms/op


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
# Warmup Iteration   1: 13.648 ±(99.9%) 0.501 ms/op
Iteration   1: 10.464 ±(99.9%) 0.184 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   10.043 ms/op
                 listUser·p0.90:   13.976 ms/op
                 listUser·p0.95:   15.466 ms/op
                 listUser·p0.99:   24.672 ms/op
                 listUser·p0.999:  27.367 ms/op
                 listUser·p0.9999: 29.458 ms/op
                 listUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3207
  mean =     10.464 ±(99.9%) 0.184 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 33 
    [ 5.000,  7.500) = 390 
    [ 7.500, 10.000) = 1157 
    [10.000, 12.500) = 939 
    [12.500, 15.000) = 488 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =     10.043 ms/op
     p(90.0000) =     13.976 ms/op
     p(95.0000) =     15.466 ms/op
     p(99.0000) =     24.672 ms/op
     p(99.9000) =     27.367 ms/op
     p(99.9900) =     29.458 ms/op
     p(99.9990) =     29.458 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           5.180          ops/ms
Client.existUser                       thrpt          11.073          ops/ms
Client.getUser                         thrpt           7.029          ops/ms
Client.listUser                        thrpt           3.054          ops/ms
Client.createUser                       avgt           3.636           ms/op
Client.existUser                        avgt           2.220           ms/op
Client.getUser                          avgt           3.488           ms/op
Client.listUser                         avgt           9.134           ms/op
Client.createUser                     sample   8565    3.736 ± 0.068   ms/op
Client.createUser:createUser·p0.00    sample           1.210           ms/op
Client.createUser:createUser·p0.50    sample           3.355           ms/op
Client.createUser:createUser·p0.90    sample           4.599           ms/op
Client.createUser:createUser·p0.95    sample           5.448           ms/op
Client.createUser:createUser·p0.99    sample          11.034           ms/op
Client.createUser:createUser·p0.999   sample          28.213           ms/op
Client.createUser:createUser·p0.9999  sample          28.508           ms/op
Client.createUser:createUser·p1.00    sample          28.508           ms/op
Client.existUser                      sample  14522    2.220 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample           0.716           ms/op
Client.existUser:existUser·p0.50      sample           2.079           ms/op
Client.existUser:existUser·p0.90      sample           2.724           ms/op
Client.existUser:existUser·p0.95      sample           2.990           ms/op
Client.existUser:existUser·p0.99      sample           4.180           ms/op
Client.existUser:existUser·p0.999     sample          15.794           ms/op
Client.existUser:existUser·p0.9999    sample          17.373           ms/op
Client.existUser:existUser·p1.00      sample          18.285           ms/op
Client.getUser                        sample   8462    3.842 ± 0.203   ms/op
Client.getUser:getUser·p0.00          sample           0.815           ms/op
Client.getUser:getUser·p0.50          sample           3.285           ms/op
Client.getUser:getUser·p0.90          sample           4.219           ms/op
Client.getUser:getUser·p0.95          sample           4.848           ms/op
Client.getUser:getUser·p0.99          sample          19.411           ms/op
Client.getUser:getUser·p0.999         sample          94.845           ms/op
Client.getUser:getUser·p0.9999        sample         114.819           ms/op
Client.getUser:getUser·p1.00          sample         114.819           ms/op
Client.listUser                       sample   3207   10.464 ± 0.184   ms/op
Client.listUser:listUser·p0.00        sample           1.690           ms/op
Client.listUser:listUser·p0.50        sample          10.043           ms/op
Client.listUser:listUser·p0.90        sample          13.976           ms/op
Client.listUser:listUser·p0.95        sample          15.466           ms/op
Client.listUser:listUser·p0.99        sample          24.672           ms/op
Client.listUser:listUser·p0.999       sample          27.367           ms/op
Client.listUser:listUser·p0.9999      sample          29.458           ms/op
Client.listUser:listUser·p1.00        sample          29.458           ms/op
