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
# Warmup Iteration   1: 2.391 ops/ms
Iteration   1: 6.491 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.491 ops/ms


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
# Warmup Iteration   1: 6.546 ops/ms
Iteration   1: 12.092 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.092 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.201 ops/ms
Iteration   1: 9.313 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.313 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.327 ops/ms
Iteration   1: 3.978 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.978 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.313 ±(99.9%) 0.110 ms/op
Iteration   1: 3.062 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.062 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.942 ±(99.9%) 0.031 ms/op
Iteration   1: 1.817 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.817 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.560 ±(99.9%) 0.070 ms/op
Iteration   1: 3.030 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.030 ms/op


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
# Warmup Iteration   1: 12.399 ±(99.9%) 0.295 ms/op
Iteration   1: 8.253 ±(99.9%) 0.090 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.253 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.374 ±(99.9%) 0.135 ms/op
Iteration   1: 3.426 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   9.982 ms/op
                 createUser·p0.999:  18.107 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9418
  mean =      3.426 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1257 
    [ 2.500,  3.750) = 5573 
    [ 3.750,  5.000) = 2275 
    [ 5.000,  6.250) = 155 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      9.982 ms/op
     p(99.9000) =     18.107 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.006 ±(99.9%) 0.086 ms/op
Iteration   1: 1.849 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.481 ms/op
                 existUser·p0.50:   1.724 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  7.178 ms/op
                 existUser·p0.9999: 8.610 ms/op
                 existUser·p1.00:   9.191 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17394
  mean =      1.849 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 180 
    [ 1.000,  2.000) = 11503 
    [ 2.000,  3.000) = 5209 
    [ 3.000,  4.000) = 419 
    [ 4.000,  5.000) = 24 
    [ 5.000,  6.000) = 3 
    [ 6.000,  7.000) = 36 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      1.724 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.457 ms/op
     p(99.9000) =      7.178 ms/op
     p(99.9900) =      8.610 ms/op
     p(99.9990) =      9.191 ms/op
     p(99.9999) =      9.191 ms/op
    p(100.0000) =      9.191 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.881 ±(99.9%) 0.135 ms/op
Iteration   1: 2.919 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.765 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  18.153 ms/op
                 getUser·p0.9999: 19.883 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11090
  mean =      2.919 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 3330 
    [ 2.500,  3.750) = 6969 
    [ 3.750,  5.000) = 650 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     19.883 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.861 ±(99.9%) 0.459 ms/op
Iteration   1: 7.635 ±(99.9%) 0.123 ms/op
                 listUser·p0.00:   3.150 ms/op
                 listUser·p0.50:   7.234 ms/op
                 listUser·p0.90:   10.043 ms/op
                 listUser·p0.95:   10.994 ms/op
                 listUser·p0.99:   17.528 ms/op
                 listUser·p0.999:  25.467 ms/op
                 listUser·p0.9999: 36.831 ms/op
                 listUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4208
  mean =      7.635 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 212 
    [ 5.000,  7.500) = 2156 
    [ 7.500, 10.000) = 1404 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.150 ms/op
     p(50.0000) =      7.234 ms/op
     p(90.0000) =     10.043 ms/op
     p(95.0000) =     10.994 ms/op
     p(99.0000) =     17.528 ms/op
     p(99.9000) =     25.467 ms/op
     p(99.9900) =     36.831 ms/op
     p(99.9990) =     36.831 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.491          ops/ms
Client.existUser                       thrpt         12.092          ops/ms
Client.getUser                         thrpt          9.313          ops/ms
Client.listUser                        thrpt          3.978          ops/ms
Client.createUser                       avgt          3.062           ms/op
Client.existUser                        avgt          1.817           ms/op
Client.getUser                          avgt          3.030           ms/op
Client.listUser                         avgt          8.253           ms/op
Client.createUser                     sample   9418   3.426 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          0.820           ms/op
Client.createUser:createUser·p0.50    sample          3.359           ms/op
Client.createUser:createUser·p0.90    sample          4.092           ms/op
Client.createUser:createUser·p0.95    sample          4.383           ms/op
Client.createUser:createUser·p0.99    sample          9.982           ms/op
Client.createUser:createUser·p0.999   sample         18.107           ms/op
Client.createUser:createUser·p0.9999  sample         18.252           ms/op
Client.createUser:createUser·p1.00    sample         18.252           ms/op
Client.existUser                      sample  17394   1.849 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.481           ms/op
Client.existUser:existUser·p0.50      sample          1.724           ms/op
Client.existUser:existUser·p0.90      sample          2.531           ms/op
Client.existUser:existUser·p0.95      sample          2.777           ms/op
Client.existUser:existUser·p0.99      sample          3.457           ms/op
Client.existUser:existUser·p0.999     sample          7.178           ms/op
Client.existUser:existUser·p0.9999    sample          8.610           ms/op
Client.existUser:existUser·p1.00      sample          9.191           ms/op
Client.getUser                        sample  11090   2.919 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          0.978           ms/op
Client.getUser:getUser·p0.50          sample          2.765           ms/op
Client.getUser:getUser·p0.90          sample          3.637           ms/op
Client.getUser:getUser·p0.95          sample          3.879           ms/op
Client.getUser:getUser·p0.99          sample          5.087           ms/op
Client.getUser:getUser·p0.999         sample         18.153           ms/op
Client.getUser:getUser·p0.9999        sample         19.883           ms/op
Client.getUser:getUser·p1.00          sample         19.890           ms/op
Client.listUser                       sample   4208   7.635 ± 0.123   ms/op
Client.listUser:listUser·p0.00        sample          3.150           ms/op
Client.listUser:listUser·p0.50        sample          7.234           ms/op
Client.listUser:listUser·p0.90        sample         10.043           ms/op
Client.listUser:listUser·p0.95        sample         10.994           ms/op
Client.listUser:listUser·p0.99        sample         17.528           ms/op
Client.listUser:listUser·p0.999       sample         25.467           ms/op
Client.listUser:listUser·p0.9999      sample         36.831           ms/op
Client.listUser:listUser·p1.00        sample         36.831           ms/op
