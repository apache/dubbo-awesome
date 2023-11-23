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
# Warmup Iteration   1: 2.309 ops/ms
Iteration   1: 5.462 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.462 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.100 ops/ms
Iteration   1: 13.052 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.052 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.740 ops/ms
Iteration   1: 9.387 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.387 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.166 ops/ms
Iteration   1: 4.189 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.189 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.459 ±(99.9%) 0.070 ms/op
Iteration   1: 3.058 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.058 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.177 ±(99.9%) 0.045 ms/op
Iteration   1: 1.881 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.881 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.457 ±(99.9%) 0.055 ms/op
Iteration   1: 2.980 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.980 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.681 ±(99.9%) 0.162 ms/op
Iteration   1: 8.974 ±(99.9%) 0.200 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.974 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.911 ±(99.9%) 0.101 ms/op
Iteration   1: 2.967 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   2.798 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  15.709 ms/op
                 createUser·p0.9999: 16.966 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10773
  mean =      2.967 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2387 
    [ 2.500,  3.750) = 7787 
    [ 3.750,  5.000) = 322 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     15.709 ms/op
     p(99.9900) =     16.966 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.930 ±(99.9%) 0.051 ms/op
Iteration   1: 1.950 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.544 ms/op
                 existUser·p0.50:   1.794 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.549 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  34.406 ms/op
                 existUser·p0.9999: 34.739 ms/op
                 existUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16392
  mean =      1.950 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15493 
    [ 2.500,  5.000) = 723 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.549 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     34.406 ms/op
     p(99.9900) =     34.739 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.399 ±(99.9%) 0.092 ms/op
Iteration   1: 3.237 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.999 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.536 ms/op
                 getUser·p0.999:  12.453 ms/op
                 getUser·p0.9999: 12.616 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9906
  mean =      3.237 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 1346 
    [ 2.500,  3.750) = 7004 
    [ 3.750,  5.000) = 1318 
    [ 5.000,  6.250) = 113 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.999 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.536 ms/op
     p(99.9000) =     12.453 ms/op
     p(99.9900) =     12.616 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 12.634 ±(99.9%) 0.515 ms/op
Iteration   1: 8.371 ±(99.9%) 0.317 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   7.447 ms/op
                 listUser·p0.90:   10.858 ms/op
                 listUser·p0.95:   13.269 ms/op
                 listUser·p0.99:   26.798 ms/op
                 listUser·p0.999:  73.054 ms/op
                 listUser·p0.9999: 74.711 ms/op
                 listUser·p1.00:   74.711 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3822
  mean =      8.371 ±(99.9%) 0.317 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 236 
    [ 5.000, 10.000) = 3045 
    [10.000, 15.000) = 419 
    [15.000, 20.000) = 65 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 4 
    [65.000, 70.000) = 1 
    [70.000, 75.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.987 ms/op
     p(50.0000) =      7.447 ms/op
     p(90.0000) =     10.858 ms/op
     p(95.0000) =     13.269 ms/op
     p(99.0000) =     26.798 ms/op
     p(99.9000) =     73.054 ms/op
     p(99.9900) =     74.711 ms/op
     p(99.9990) =     74.711 ms/op
     p(99.9999) =     74.711 ms/op
    p(100.0000) =     74.711 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.462          ops/ms
Client.existUser                       thrpt         13.052          ops/ms
Client.getUser                         thrpt          9.387          ops/ms
Client.listUser                        thrpt          4.189          ops/ms
Client.createUser                       avgt          3.058           ms/op
Client.existUser                        avgt          1.881           ms/op
Client.getUser                          avgt          2.980           ms/op
Client.listUser                         avgt          8.974           ms/op
Client.createUser                     sample  10773   2.967 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          1.272           ms/op
Client.createUser:createUser·p0.50    sample          2.798           ms/op
Client.createUser:createUser·p0.90    sample          3.486           ms/op
Client.createUser:createUser·p0.95    sample          3.797           ms/op
Client.createUser:createUser·p0.99    sample          8.536           ms/op
Client.createUser:createUser·p0.999   sample         15.709           ms/op
Client.createUser:createUser·p0.9999  sample         16.966           ms/op
Client.createUser:createUser·p1.00    sample         16.974           ms/op
Client.existUser                      sample  16392   1.950 ± 0.044   ms/op
Client.existUser:existUser·p0.00      sample          0.544           ms/op
Client.existUser:existUser·p0.50      sample          1.794           ms/op
Client.existUser:existUser·p0.90      sample          2.302           ms/op
Client.existUser:existUser·p0.95      sample          2.549           ms/op
Client.existUser:existUser·p0.99      sample          5.226           ms/op
Client.existUser:existUser·p0.999     sample         34.406           ms/op
Client.existUser:existUser·p0.9999    sample         34.739           ms/op
Client.existUser:existUser·p1.00      sample         34.865           ms/op
Client.getUser                        sample   9906   3.237 ± 0.033   ms/op
Client.getUser:getUser·p0.00          sample          0.865           ms/op
Client.getUser:getUser·p0.50          sample          3.158           ms/op
Client.getUser:getUser·p0.90          sample          3.999           ms/op
Client.getUser:getUser·p0.95          sample          4.473           ms/op
Client.getUser:getUser·p0.99          sample          6.536           ms/op
Client.getUser:getUser·p0.999         sample         12.453           ms/op
Client.getUser:getUser·p0.9999        sample         12.616           ms/op
Client.getUser:getUser·p1.00          sample         12.616           ms/op
Client.listUser                       sample   3822   8.371 ± 0.317   ms/op
Client.listUser:listUser·p0.00        sample          1.987           ms/op
Client.listUser:listUser·p0.50        sample          7.447           ms/op
Client.listUser:listUser·p0.90        sample         10.858           ms/op
Client.listUser:listUser·p0.95        sample         13.269           ms/op
Client.listUser:listUser·p0.99        sample         26.798           ms/op
Client.listUser:listUser·p0.999       sample         73.054           ms/op
Client.listUser:listUser·p0.9999      sample         74.711           ms/op
Client.listUser:listUser·p1.00        sample         74.711           ms/op
