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
# Warmup Iteration   1: 2.619 ops/ms
Iteration   1: 6.496 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.496 ops/ms


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
# Warmup Iteration   1: 6.576 ops/ms
Iteration   1: 14.371 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.371 ops/ms


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
# Warmup Iteration   1: 4.874 ops/ms
Iteration   1: 9.167 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.167 ops/ms


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
# Warmup Iteration   1: 2.069 ops/ms
Iteration   1: 3.186 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.186 ops/ms


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
# Warmup Iteration   1: 6.637 ±(99.9%) 0.129 ms/op
Iteration   1: 3.141 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.141 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.032 ms/op
Iteration   1: 2.107 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.107 ms/op


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.043 ms/op
Iteration   1: 3.075 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.075 ms/op


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
# Warmup Iteration   1: 11.943 ±(99.9%) 0.194 ms/op
Iteration   1: 8.331 ±(99.9%) 0.154 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.331 ms/op


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
# Warmup Iteration   1: 5.408 ±(99.9%) 0.118 ms/op
Iteration   1: 3.079 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   6.677 ms/op
                 createUser·p0.999:  13.235 ms/op
                 createUser·p0.9999: 13.336 ms/op
                 createUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10397
  mean =      3.079 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 2188 
    [ 2.500,  3.750) = 7208 
    [ 3.750,  5.000) = 806 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      6.677 ms/op
     p(99.9000) =     13.235 ms/op
     p(99.9900) =     13.336 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


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
# Warmup Iteration   1: 2.980 ±(99.9%) 0.063 ms/op
Iteration   1: 1.861 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.354 ms/op
                 existUser·p0.50:   1.827 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  20.840 ms/op
                 existUser·p0.9999: 21.392 ms/op
                 existUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17183
  mean =      1.861 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16419 
    [ 2.500,  5.000) = 668 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     21.392 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.099 ms/op
Iteration   1: 3.484 ±(99.9%) 0.149 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.505 ms/op
                 getUser·p0.99:   7.425 ms/op
                 getUser·p0.999:  80.549 ms/op
                 getUser·p0.9999: 91.226 ms/op
                 getUser·p1.00:   91.226 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9161
  mean =      3.484 ±(99.9%) 0.149 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 9091 
    [ 10.000,  20.000) = 21 
    [ 20.000,  30.000) = 7 
    [ 30.000,  40.000) = 6 
    [ 40.000,  50.000) = 6 
    [ 50.000,  60.000) = 7 
    [ 60.000,  70.000) = 8 
    [ 70.000,  80.000) = 6 
    [ 80.000,  90.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.505 ms/op
     p(99.0000) =      7.425 ms/op
     p(99.9000) =     80.549 ms/op
     p(99.9900) =     91.226 ms/op
     p(99.9990) =     91.226 ms/op
     p(99.9999) =     91.226 ms/op
    p(100.0000) =     91.226 ms/op


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
# Warmup Iteration   1: 12.430 ±(99.9%) 0.420 ms/op
Iteration   1: 8.646 ±(99.9%) 0.126 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   8.266 ms/op
                 listUser·p0.90:   11.606 ms/op
                 listUser·p0.95:   12.796 ms/op
                 listUser·p0.99:   16.142 ms/op
                 listUser·p0.999:  21.242 ms/op
                 listUser·p0.9999: 22.249 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3675
  mean =      8.646 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 69 
    [ 5.000,  7.500) = 1176 
    [ 7.500, 10.000) = 1550 
    [10.000, 12.500) = 655 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      8.266 ms/op
     p(90.0000) =     11.606 ms/op
     p(95.0000) =     12.796 ms/op
     p(99.0000) =     16.142 ms/op
     p(99.9000) =     21.242 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.496          ops/ms
Client.existUser                       thrpt         14.371          ops/ms
Client.getUser                         thrpt          9.167          ops/ms
Client.listUser                        thrpt          3.186          ops/ms
Client.createUser                       avgt          3.141           ms/op
Client.existUser                        avgt          2.107           ms/op
Client.getUser                          avgt          3.075           ms/op
Client.listUser                         avgt          8.331           ms/op
Client.createUser                     sample  10397   3.079 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          1.163           ms/op
Client.createUser:createUser·p0.50    sample          3.056           ms/op
Client.createUser:createUser·p0.90    sample          3.723           ms/op
Client.createUser:createUser·p0.95    sample          4.067           ms/op
Client.createUser:createUser·p0.99    sample          6.677           ms/op
Client.createUser:createUser·p0.999   sample         13.235           ms/op
Client.createUser:createUser·p0.9999  sample         13.336           ms/op
Client.createUser:createUser·p1.00    sample         13.337           ms/op
Client.existUser                      sample  17183   1.861 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.354           ms/op
Client.existUser:existUser·p0.50      sample          1.827           ms/op
Client.existUser:existUser·p0.90      sample          2.265           ms/op
Client.existUser:existUser·p0.95      sample          2.462           ms/op
Client.existUser:existUser·p0.99      sample          3.875           ms/op
Client.existUser:existUser·p0.999     sample         20.840           ms/op
Client.existUser:existUser·p0.9999    sample         21.392           ms/op
Client.existUser:existUser·p1.00      sample         21.463           ms/op
Client.getUser                        sample   9161   3.484 ± 0.149   ms/op
Client.getUser:getUser·p0.00          sample          0.770           ms/op
Client.getUser:getUser·p0.50          sample          3.162           ms/op
Client.getUser:getUser·p0.90          sample          4.071           ms/op
Client.getUser:getUser·p0.95          sample          4.505           ms/op
Client.getUser:getUser·p0.99          sample          7.425           ms/op
Client.getUser:getUser·p0.999         sample         80.549           ms/op
Client.getUser:getUser·p0.9999        sample         91.226           ms/op
Client.getUser:getUser·p1.00          sample         91.226           ms/op
Client.listUser                       sample   3675   8.646 ± 0.126   ms/op
Client.listUser:listUser·p0.00        sample          1.497           ms/op
Client.listUser:listUser·p0.50        sample          8.266           ms/op
Client.listUser:listUser·p0.90        sample         11.606           ms/op
Client.listUser:listUser·p0.95        sample         12.796           ms/op
Client.listUser:listUser·p0.99        sample         16.142           ms/op
Client.listUser:listUser·p0.999       sample         21.242           ms/op
Client.listUser:listUser·p0.9999      sample         22.249           ms/op
Client.listUser:listUser·p1.00        sample         22.249           ms/op
