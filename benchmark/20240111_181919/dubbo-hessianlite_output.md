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
# Warmup Iteration   1: 2.055 ops/ms
Iteration   1: 5.481 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.481 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.868 ops/ms
Iteration   1: 13.284 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.284 ops/ms


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
# Warmup Iteration   1: 3.950 ops/ms
Iteration   1: 7.629 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.629 ops/ms


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
# Warmup Iteration   1: 1.928 ops/ms
Iteration   1: 3.586 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.586 ops/ms


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
# Warmup Iteration   1: 5.766 ±(99.9%) 0.102 ms/op
Iteration   1: 3.277 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.277 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.036 ms/op
Iteration   1: 2.047 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.047 ms/op


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.055 ms/op
Iteration   1: 3.302 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.302 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.536 ±(99.9%) 0.229 ms/op
Iteration   1: 7.845 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.845 ms/op


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
# Warmup Iteration   1: 5.351 ±(99.9%) 0.139 ms/op
Iteration   1: 3.535 ±(99.9%) 0.075 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.036 ms/op
                 createUser·p0.999:  38.339 ms/op
                 createUser·p0.9999: 38.863 ms/op
                 createUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9017
  mean =      3.535 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 319 
    [ 2.500,  5.000) = 8445 
    [ 5.000,  7.500) = 220 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.036 ms/op
     p(99.9000) =     38.339 ms/op
     p(99.9900) =     38.863 ms/op
     p(99.9990) =     38.863 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.071 ms/op
Iteration   1: 2.108 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.034 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.920 ms/op
                 existUser·p0.99:   4.802 ms/op
                 existUser·p0.999:  9.535 ms/op
                 existUser·p0.9999: 10.534 ms/op
                 existUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15162
  mean =      2.108 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 31 
    [ 1.000,  2.000) = 7211 
    [ 2.000,  3.000) = 7269 
    [ 3.000,  4.000) = 375 
    [ 4.000,  5.000) = 133 
    [ 5.000,  6.000) = 67 
    [ 6.000,  7.000) = 39 
    [ 7.000,  8.000) = 19 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      4.802 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     10.534 ms/op
     p(99.9990) =     10.568 ms/op
     p(99.9999) =     10.568 ms/op
    p(100.0000) =     10.568 ms/op


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
# Warmup Iteration   1: 5.231 ±(99.9%) 0.165 ms/op
Iteration   1: 3.314 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.463 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.503 ms/op
                 getUser·p0.999:  20.414 ms/op
                 getUser·p0.9999: 20.611 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9804
  mean =      3.314 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1446 
    [ 2.500,  5.000) = 8061 
    [ 5.000,  7.500) = 199 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.503 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 12.256 ±(99.9%) 0.464 ms/op
Iteration   1: 11.930 ±(99.9%) 0.394 ms/op
                 listUser·p0.00:   3.310 ms/op
                 listUser·p0.50:   9.322 ms/op
                 listUser·p0.90:   21.325 ms/op
                 listUser·p0.95:   26.309 ms/op
                 listUser·p0.99:   29.426 ms/op
                 listUser·p0.999:  40.260 ms/op
                 listUser·p0.9999: 40.305 ms/op
                 listUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2681
  mean =     11.930 ±(99.9%) 0.394 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 39 
    [ 5.000, 10.000) = 1467 
    [10.000, 15.000) = 486 
    [15.000, 20.000) = 366 
    [20.000, 25.000) = 146 
    [25.000, 30.000) = 163 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      3.310 ms/op
     p(50.0000) =      9.322 ms/op
     p(90.0000) =     21.325 ms/op
     p(95.0000) =     26.309 ms/op
     p(99.0000) =     29.426 ms/op
     p(99.9000) =     40.260 ms/op
     p(99.9900) =     40.305 ms/op
     p(99.9990) =     40.305 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.481          ops/ms
Client.existUser                       thrpt         13.284          ops/ms
Client.getUser                         thrpt          7.629          ops/ms
Client.listUser                        thrpt          3.586          ops/ms
Client.createUser                       avgt          3.277           ms/op
Client.existUser                        avgt          2.047           ms/op
Client.getUser                          avgt          3.302           ms/op
Client.listUser                         avgt          7.845           ms/op
Client.createUser                     sample   9017   3.535 ± 0.075   ms/op
Client.createUser:createUser·p0.00    sample          1.397           ms/op
Client.createUser:createUser·p0.50    sample          3.322           ms/op
Client.createUser:createUser·p0.90    sample          4.252           ms/op
Client.createUser:createUser·p0.95    sample          4.547           ms/op
Client.createUser:createUser·p0.99    sample          6.036           ms/op
Client.createUser:createUser·p0.999   sample         38.339           ms/op
Client.createUser:createUser·p0.9999  sample         38.863           ms/op
Client.createUser:createUser·p1.00    sample         38.863           ms/op
Client.existUser                      sample  15162   2.108 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.666           ms/op
Client.existUser:existUser·p0.50      sample          2.034           ms/op
Client.existUser:existUser·p0.90      sample          2.601           ms/op
Client.existUser:existUser·p0.95      sample          2.920           ms/op
Client.existUser:existUser·p0.99      sample          4.802           ms/op
Client.existUser:existUser·p0.999     sample          9.535           ms/op
Client.existUser:existUser·p0.9999    sample         10.534           ms/op
Client.existUser:existUser·p1.00      sample         10.568           ms/op
Client.getUser                        sample   9804   3.314 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample          0.463           ms/op
Client.getUser:getUser·p0.50          sample          3.195           ms/op
Client.getUser:getUser·p0.90          sample          4.055           ms/op
Client.getUser:getUser·p0.95          sample          4.612           ms/op
Client.getUser:getUser·p0.99          sample          7.503           ms/op
Client.getUser:getUser·p0.999         sample         20.414           ms/op
Client.getUser:getUser·p0.9999        sample         20.611           ms/op
Client.getUser:getUser·p1.00          sample         20.611           ms/op
Client.listUser                       sample   2681  11.930 ± 0.394   ms/op
Client.listUser:listUser·p0.00        sample          3.310           ms/op
Client.listUser:listUser·p0.50        sample          9.322           ms/op
Client.listUser:listUser·p0.90        sample         21.325           ms/op
Client.listUser:listUser·p0.95        sample         26.309           ms/op
Client.listUser:listUser·p0.99        sample         29.426           ms/op
Client.listUser:listUser·p0.999       sample         40.260           ms/op
Client.listUser:listUser·p0.9999      sample         40.305           ms/op
Client.listUser:listUser·p1.00        sample         40.305           ms/op
