# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.439 ops/ms
Iteration   1: 3.858 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.858 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 3.341 ops/ms
Iteration   1: 10.355 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.355 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.123 ops/ms
Iteration   1: 6.665 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.665 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.003 ops/ms
Iteration   1: 1.395 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.395 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 10.503 ±(99.9%) 0.155 ms/op
Iteration   1: 4.140 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.140 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.462 ±(99.9%) 0.119 ms/op
Iteration   1: 2.784 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.784 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.105 ±(99.9%) 0.222 ms/op
Iteration   1: 5.833 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.833 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 28.067 ±(99.9%) 0.731 ms/op
Iteration   1: 22.313 ±(99.9%) 0.352 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  22.313 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 7.904 ±(99.9%) 0.243 ms/op
Iteration   1: 4.068 ±(99.9%) 0.105 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   9.781 ms/op
                 createUser·p0.99:   16.941 ms/op
                 createUser·p0.999:  26.241 ms/op
                 createUser·p0.9999: 26.870 ms/op
                 createUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 7863
  mean =      4.068 ±(99.9%) 0.105 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214 
    [ 2.500,  5.000) = 6397 
    [ 5.000,  7.500) = 570 
    [ 7.500, 10.000) = 310 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      9.781 ms/op
     p(99.0000) =     16.941 ms/op
     p(99.9000) =     26.241 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.489 ±(99.9%) 0.217 ms/op
Iteration   1: 2.193 ±(99.9%) 0.050 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   1.809 ms/op
                 existUser·p0.90:   2.728 ms/op
                 existUser·p0.95:   3.827 ms/op
                 existUser·p0.99:   7.368 ms/op
                 existUser·p0.999:  27.605 ms/op
                 existUser·p0.9999: 28.174 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14552
  mean =      2.193 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12720 
    [ 2.500,  5.000) = 1375 
    [ 5.000,  7.500) = 321 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      1.809 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      3.827 ms/op
     p(99.0000) =      7.368 ms/op
     p(99.9000) =     27.605 ms/op
     p(99.9900) =     28.174 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 9.220 ±(99.9%) 0.291 ms/op
Iteration   1: 4.344 ±(99.9%) 0.103 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   7.938 ms/op
                 getUser·p0.99:   14.348 ms/op
                 getUser·p0.999:  36.438 ms/op
                 getUser·p0.9999: 36.897 ms/op
                 getUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7408
  mean =      4.344 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 6372 
    [ 5.000,  7.500) = 573 
    [ 7.500, 10.000) = 175 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     14.348 ms/op
     p(99.9000) =     36.438 ms/op
     p(99.9900) =     36.897 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 27.932 ±(99.9%) 1.456 ms/op
Iteration   1: 18.443 ±(99.9%) 0.558 ms/op
                 listUser·p0.00:   5.341 ms/op
                 listUser·p0.50:   17.334 ms/op
                 listUser·p0.90:   24.216 ms/op
                 listUser·p0.95:   30.130 ms/op
                 listUser·p0.99:   49.198 ms/op
                 listUser·p0.999:  77.920 ms/op
                 listUser·p0.9999: 115.343 ms/op
                 listUser·p1.00:   115.343 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1829
  mean =     18.443 ±(99.9%) 0.558 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 228 
    [ 12.500,  25.000) = 1443 
    [ 25.000,  37.500) = 107 
    [ 37.500,  50.000) = 44 
    [ 50.000,  62.500) = 5 
    [ 62.500,  75.000) = 1 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 1 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.341 ms/op
     p(50.0000) =     17.334 ms/op
     p(90.0000) =     24.216 ms/op
     p(95.0000) =     30.130 ms/op
     p(99.0000) =     49.198 ms/op
     p(99.9000) =     77.920 ms/op
     p(99.9900) =    115.343 ms/op
     p(99.9990) =    115.343 ms/op
     p(99.9999) =    115.343 ms/op
    p(100.0000) =    115.343 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           3.858          ops/ms
Client.existUser                       thrpt          10.355          ops/ms
Client.getUser                         thrpt           6.665          ops/ms
Client.listUser                        thrpt           1.395          ops/ms
Client.createUser                       avgt           4.140           ms/op
Client.existUser                        avgt           2.784           ms/op
Client.getUser                          avgt           5.833           ms/op
Client.listUser                         avgt          22.313           ms/op
Client.createUser                     sample   7863    4.068 ± 0.105   ms/op
Client.createUser:createUser·p0.00    sample           1.407           ms/op
Client.createUser:createUser·p0.50    sample           3.043           ms/op
Client.createUser:createUser·p0.90    sample           6.988           ms/op
Client.createUser:createUser·p0.95    sample           9.781           ms/op
Client.createUser:createUser·p0.99    sample          16.941           ms/op
Client.createUser:createUser·p0.999   sample          26.241           ms/op
Client.createUser:createUser·p0.9999  sample          26.870           ms/op
Client.createUser:createUser·p1.00    sample          26.870           ms/op
Client.existUser                      sample  14552    2.193 ± 0.050   ms/op
Client.existUser:existUser·p0.00      sample           0.662           ms/op
Client.existUser:existUser·p0.50      sample           1.809           ms/op
Client.existUser:existUser·p0.90      sample           2.728           ms/op
Client.existUser:existUser·p0.95      sample           3.827           ms/op
Client.existUser:existUser·p0.99      sample           7.368           ms/op
Client.existUser:existUser·p0.999     sample          27.605           ms/op
Client.existUser:existUser·p0.9999    sample          28.174           ms/op
Client.existUser:existUser·p1.00      sample          28.279           ms/op
Client.getUser                        sample   7408    4.344 ± 0.103   ms/op
Client.getUser:getUser·p0.00          sample           1.405           ms/op
Client.getUser:getUser·p0.50          sample           3.674           ms/op
Client.getUser:getUser·p0.90          sample           5.431           ms/op
Client.getUser:getUser·p0.95          sample           7.938           ms/op
Client.getUser:getUser·p0.99          sample          14.348           ms/op
Client.getUser:getUser·p0.999         sample          36.438           ms/op
Client.getUser:getUser·p0.9999        sample          36.897           ms/op
Client.getUser:getUser·p1.00          sample          36.897           ms/op
Client.listUser                       sample   1829   18.443 ± 0.558   ms/op
Client.listUser:listUser·p0.00        sample           5.341           ms/op
Client.listUser:listUser·p0.50        sample          17.334           ms/op
Client.listUser:listUser·p0.90        sample          24.216           ms/op
Client.listUser:listUser·p0.95        sample          30.130           ms/op
Client.listUser:listUser·p0.99        sample          49.198           ms/op
Client.listUser:listUser·p0.999       sample          77.920           ms/op
Client.listUser:listUser·p0.9999      sample         115.343           ms/op
Client.listUser:listUser·p1.00        sample         115.343           ms/op
