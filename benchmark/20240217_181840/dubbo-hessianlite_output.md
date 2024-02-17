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
# Warmup Iteration   1: 2.434 ops/ms
Iteration   1: 5.694 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.694 ops/ms


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
# Warmup Iteration   1: 6.551 ops/ms
Iteration   1: 13.281 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.281 ops/ms


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
# Warmup Iteration   1: 3.953 ops/ms
Iteration   1: 8.236 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.236 ops/ms


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
# Warmup Iteration   1: 2.093 ops/ms
Iteration   1: 3.535 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.535 ops/ms


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
# Warmup Iteration   1: 5.228 ±(99.9%) 0.102 ms/op
Iteration   1: 3.231 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.231 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.048 ms/op
Iteration   1: 2.092 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.092 ms/op


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
# Warmup Iteration   1: 4.956 ±(99.9%) 0.066 ms/op
Iteration   1: 3.540 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.540 ms/op


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
# Warmup Iteration   1: 12.048 ±(99.9%) 0.165 ms/op
Iteration   1: 8.634 ±(99.9%) 0.110 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.634 ms/op


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
# Warmup Iteration   1: 5.419 ±(99.9%) 0.144 ms/op
Iteration   1: 3.236 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   7.387 ms/op
                 createUser·p0.999:  10.682 ms/op
                 createUser·p0.9999: 11.403 ms/op
                 createUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10030
  mean =      3.236 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1341 
    [ 2.500,  3.750) = 6284 
    [ 3.750,  5.000) = 2203 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.387 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     11.403 ms/op
     p(99.9990) =     11.403 ms/op
     p(99.9999) =     11.403 ms/op
    p(100.0000) =     11.403 ms/op


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
# Warmup Iteration   1: 3.325 ±(99.9%) 0.085 ms/op
Iteration   1: 1.634 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   1.577 ms/op
                 existUser·p0.90:   1.927 ms/op
                 existUser·p0.95:   2.095 ms/op
                 existUser·p0.99:   2.586 ms/op
                 existUser·p0.999:  5.283 ms/op
                 existUser·p0.9999: 7.087 ms/op
                 existUser·p1.00:   7.127 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19673
  mean =      1.634 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 100 
    [1.000, 1.500) = 5916 
    [1.500, 2.000) = 12125 
    [2.000, 2.500) = 1306 
    [2.500, 3.000) = 94 
    [3.000, 3.500) = 21 
    [3.500, 4.000) = 20 
    [4.000, 4.500) = 47 
    [4.500, 5.000) = 21 
    [5.000, 5.500) = 6 
    [5.500, 6.000) = 2 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      1.577 ms/op
     p(90.0000) =      1.927 ms/op
     p(95.0000) =      2.095 ms/op
     p(99.0000) =      2.586 ms/op
     p(99.9000) =      5.283 ms/op
     p(99.9900) =      7.087 ms/op
     p(99.9990) =      7.127 ms/op
     p(99.9999) =      7.127 ms/op
    p(100.0000) =      7.127 ms/op


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.108 ms/op
Iteration   1: 2.833 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   2.642 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  6.486 ms/op
                 getUser·p0.9999: 6.641 ms/op
                 getUser·p1.00:   6.644 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11288
  mean =      2.833 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 44 
    [1.500, 2.000) = 492 
    [2.000, 2.500) = 3820 
    [2.500, 3.000) = 3031 
    [3.000, 3.500) = 2135 
    [3.500, 4.000) = 1098 
    [4.000, 4.500) = 447 
    [4.500, 5.000) = 79 
    [5.000, 5.500) = 64 
    [5.500, 6.000) = 40 
    [6.000, 6.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =      6.486 ms/op
     p(99.9900) =      6.641 ms/op
     p(99.9990) =      6.644 ms/op
     p(99.9999) =      6.644 ms/op
    p(100.0000) =      6.644 ms/op


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
# Warmup Iteration   1: 12.073 ±(99.9%) 0.409 ms/op
Iteration   1: 7.898 ±(99.9%) 0.131 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   7.455 ms/op
                 listUser·p0.90:   10.486 ms/op
                 listUser·p0.95:   11.839 ms/op
                 listUser·p0.99:   20.186 ms/op
                 listUser·p0.999:  22.998 ms/op
                 listUser·p0.9999: 29.262 ms/op
                 listUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4047
  mean =      7.898 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 220 
    [ 5.000,  7.500) = 1838 
    [ 7.500, 10.000) = 1471 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.429 ms/op
     p(50.0000) =      7.455 ms/op
     p(90.0000) =     10.486 ms/op
     p(95.0000) =     11.839 ms/op
     p(99.0000) =     20.186 ms/op
     p(99.9000) =     22.998 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.694          ops/ms
Client.existUser                       thrpt         13.281          ops/ms
Client.getUser                         thrpt          8.236          ops/ms
Client.listUser                        thrpt          3.535          ops/ms
Client.createUser                       avgt          3.231           ms/op
Client.existUser                        avgt          2.092           ms/op
Client.getUser                          avgt          3.540           ms/op
Client.listUser                         avgt          8.634           ms/op
Client.createUser                     sample  10030   3.236 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.266           ms/op
Client.createUser:createUser·p0.50    sample          2.986           ms/op
Client.createUser:createUser·p0.90    sample          4.202           ms/op
Client.createUser:createUser·p0.95    sample          4.465           ms/op
Client.createUser:createUser·p0.99    sample          7.387           ms/op
Client.createUser:createUser·p0.999   sample         10.682           ms/op
Client.createUser:createUser·p0.9999  sample         11.403           ms/op
Client.createUser:createUser·p1.00    sample         11.403           ms/op
Client.existUser                      sample  19673   1.634 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.506           ms/op
Client.existUser:existUser·p0.50      sample          1.577           ms/op
Client.existUser:existUser·p0.90      sample          1.927           ms/op
Client.existUser:existUser·p0.95      sample          2.095           ms/op
Client.existUser:existUser·p0.99      sample          2.586           ms/op
Client.existUser:existUser·p0.999     sample          5.283           ms/op
Client.existUser:existUser·p0.9999    sample          7.087           ms/op
Client.existUser:existUser·p1.00      sample          7.127           ms/op
Client.getUser                        sample  11288   2.833 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.973           ms/op
Client.getUser:getUser·p0.50          sample          2.642           ms/op
Client.getUser:getUser·p0.90          sample          3.731           ms/op
Client.getUser:getUser·p0.95          sample          4.104           ms/op
Client.getUser:getUser·p0.99          sample          5.120           ms/op
Client.getUser:getUser·p0.999         sample          6.486           ms/op
Client.getUser:getUser·p0.9999        sample          6.641           ms/op
Client.getUser:getUser·p1.00          sample          6.644           ms/op
Client.listUser                       sample   4047   7.898 ± 0.131   ms/op
Client.listUser:listUser·p0.00        sample          2.429           ms/op
Client.listUser:listUser·p0.50        sample          7.455           ms/op
Client.listUser:listUser·p0.90        sample         10.486           ms/op
Client.listUser:listUser·p0.95        sample         11.839           ms/op
Client.listUser:listUser·p0.99        sample         20.186           ms/op
Client.listUser:listUser·p0.999       sample         22.998           ms/op
Client.listUser:listUser·p0.9999      sample         29.262           ms/op
Client.listUser:listUser·p1.00        sample         29.262           ms/op
