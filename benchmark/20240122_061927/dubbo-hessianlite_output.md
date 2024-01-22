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
# Warmup Iteration   1: 2.601 ops/ms
Iteration   1: 6.133 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.133 ops/ms


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
# Warmup Iteration   1: 6.233 ops/ms
Iteration   1: 13.562 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.562 ops/ms


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
# Warmup Iteration   1: 3.946 ops/ms
Iteration   1: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.442 ops/ms


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
# Warmup Iteration   1: 2.273 ops/ms
Iteration   1: 3.265 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.265 ops/ms


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
# Warmup Iteration   1: 5.240 ±(99.9%) 0.063 ms/op
Iteration   1: 3.172 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.172 ms/op


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
# Warmup Iteration   1: 3.016 ±(99.9%) 0.029 ms/op
Iteration   1: 1.886 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.886 ms/op


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.055 ms/op
Iteration   1: 3.334 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.334 ms/op


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
# Warmup Iteration   1: 12.547 ±(99.9%) 0.240 ms/op
Iteration   1: 8.696 ±(99.9%) 0.082 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.696 ms/op


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
# Warmup Iteration   1: 5.133 ±(99.9%) 0.109 ms/op
Iteration   1: 3.200 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.277 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 11.354 ms/op
                 createUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9986
  mean =      3.200 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 321 
    [ 2.500,  3.750) = 8318 
    [ 3.750,  5.000) = 1221 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.277 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     11.354 ms/op
     p(99.9990) =     11.354 ms/op
     p(99.9999) =     11.354 ms/op
    p(100.0000) =     11.354 ms/op


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
# Warmup Iteration   1: 2.957 ±(99.9%) 0.075 ms/op
Iteration   1: 1.566 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   1.504 ms/op
                 existUser·p0.90:   2.091 ms/op
                 existUser·p0.95:   2.265 ms/op
                 existUser·p0.99:   2.662 ms/op
                 existUser·p0.999:  5.038 ms/op
                 existUser·p0.9999: 5.365 ms/op
                 existUser·p1.00:   5.366 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 20410
  mean =      1.566 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 655 
    [1.000, 1.500) = 9482 
    [1.500, 2.000) = 7374 
    [2.000, 2.500) = 2517 
    [2.500, 3.000) = 322 
    [3.000, 3.500) = 26 
    [3.500, 4.000) = 2 
    [4.000, 4.500) = 0 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.504 ms/op
     p(90.0000) =      2.091 ms/op
     p(95.0000) =      2.265 ms/op
     p(99.0000) =      2.662 ms/op
     p(99.9000) =      5.038 ms/op
     p(99.9900) =      5.365 ms/op
     p(99.9990) =      5.366 ms/op
     p(99.9999) =      5.366 ms/op
    p(100.0000) =      5.366 ms/op


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.109 ms/op
Iteration   1: 3.226 ±(99.9%) 0.047 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   7.458 ms/op
                 getUser·p0.999:  24.117 ms/op
                 getUser·p0.9999: 24.216 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9959
  mean =      3.226 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 943 
    [ 2.500,  5.000) = 8765 
    [ 5.000,  7.500) = 156 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      7.458 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 13.478 ±(99.9%) 0.504 ms/op
Iteration   1: 9.233 ±(99.9%) 0.156 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   8.716 ms/op
                 listUser·p0.90:   12.780 ms/op
                 listUser·p0.95:   13.850 ms/op
                 listUser·p0.99:   20.087 ms/op
                 listUser·p0.999:  25.547 ms/op
                 listUser·p0.9999: 37.683 ms/op
                 listUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3532
  mean =      9.233 ±(99.9%) 0.156 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 106 
    [ 5.000,  7.500) = 768 
    [ 7.500, 10.000) = 1565 
    [10.000, 12.500) = 701 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.613 ms/op
     p(50.0000) =      8.716 ms/op
     p(90.0000) =     12.780 ms/op
     p(95.0000) =     13.850 ms/op
     p(99.0000) =     20.087 ms/op
     p(99.9000) =     25.547 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     37.683 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.133          ops/ms
Client.existUser                       thrpt         13.562          ops/ms
Client.getUser                         thrpt          8.442          ops/ms
Client.listUser                        thrpt          3.265          ops/ms
Client.createUser                       avgt          3.172           ms/op
Client.existUser                        avgt          1.886           ms/op
Client.getUser                          avgt          3.334           ms/op
Client.listUser                         avgt          8.696           ms/op
Client.createUser                     sample   9986   3.200 ± 0.020   ms/op
Client.createUser:createUser·p0.00    sample          1.167           ms/op
Client.createUser:createUser·p0.50    sample          3.052           ms/op
Client.createUser:createUser·p0.90    sample          3.891           ms/op
Client.createUser:createUser·p0.95    sample          4.243           ms/op
Client.createUser:createUser·p0.99    sample          5.277           ms/op
Client.createUser:createUser·p0.999   sample          8.389           ms/op
Client.createUser:createUser·p0.9999  sample         11.354           ms/op
Client.createUser:createUser·p1.00    sample         11.354           ms/op
Client.existUser                      sample  20410   1.566 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.569           ms/op
Client.existUser:existUser·p0.50      sample          1.504           ms/op
Client.existUser:existUser·p0.90      sample          2.091           ms/op
Client.existUser:existUser·p0.95      sample          2.265           ms/op
Client.existUser:existUser·p0.99      sample          2.662           ms/op
Client.existUser:existUser·p0.999     sample          5.038           ms/op
Client.existUser:existUser·p0.9999    sample          5.365           ms/op
Client.existUser:existUser·p1.00      sample          5.366           ms/op
Client.getUser                        sample   9959   3.226 ± 0.047   ms/op
Client.getUser:getUser·p0.00          sample          0.583           ms/op
Client.getUser:getUser·p0.50          sample          2.994           ms/op
Client.getUser:getUser·p0.90          sample          3.944           ms/op
Client.getUser:getUser·p0.95          sample          4.342           ms/op
Client.getUser:getUser·p0.99          sample          7.458           ms/op
Client.getUser:getUser·p0.999         sample         24.117           ms/op
Client.getUser:getUser·p0.9999        sample         24.216           ms/op
Client.getUser:getUser·p1.00          sample         24.216           ms/op
Client.listUser                       sample   3532   9.233 ± 0.156   ms/op
Client.listUser:listUser·p0.00        sample          2.613           ms/op
Client.listUser:listUser·p0.50        sample          8.716           ms/op
Client.listUser:listUser·p0.90        sample         12.780           ms/op
Client.listUser:listUser·p0.95        sample         13.850           ms/op
Client.listUser:listUser·p0.99        sample         20.087           ms/op
Client.listUser:listUser·p0.999       sample         25.547           ms/op
Client.listUser:listUser·p0.9999      sample         37.683           ms/op
Client.listUser:listUser·p1.00        sample         37.683           ms/op
