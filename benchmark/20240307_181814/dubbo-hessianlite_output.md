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
# Warmup Iteration   1: 2.037 ops/ms
Iteration   1: 5.599 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.599 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.011 ops/ms
Iteration   1: 12.076 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.076 ops/ms


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
# Warmup Iteration   1: 3.908 ops/ms
Iteration   1: 7.609 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.609 ops/ms


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
# Warmup Iteration   1: 1.785 ops/ms
Iteration   1: 3.460 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.460 ops/ms


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
# Warmup Iteration   1: 5.870 ±(99.9%) 0.183 ms/op
Iteration   1: 3.084 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.084 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.030 ms/op
Iteration   1: 1.908 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.908 ms/op


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.052 ms/op
Iteration   1: 3.124 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.124 ms/op


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
# Warmup Iteration   1: 13.447 ±(99.9%) 0.287 ms/op
Iteration   1: 8.872 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.872 ms/op


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
# Warmup Iteration   1: 5.069 ±(99.9%) 0.117 ms/op
Iteration   1: 2.963 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.789 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  16.732 ms/op
                 createUser·p0.9999: 16.996 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10789
  mean =      2.963 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 3579 
    [ 2.500,  3.750) = 5974 
    [ 3.750,  5.000) = 1085 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     16.732 ms/op
     p(99.9900) =     16.996 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.080 ms/op
Iteration   1: 1.884 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   1.868 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   2.991 ms/op
                 existUser·p0.999:  10.060 ms/op
                 existUser·p0.9999: 10.163 ms/op
                 existUser·p1.00:   10.174 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17073
  mean =      1.884 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 694 
    [ 1.000,  2.000) = 9779 
    [ 2.000,  3.000) = 6431 
    [ 3.000,  4.000) = 123 
    [ 4.000,  5.000) = 11 
    [ 5.000,  6.000) = 3 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      2.991 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     10.163 ms/op
     p(99.9990) =     10.174 ms/op
     p(99.9999) =     10.174 ms/op
    p(100.0000) =     10.174 ms/op


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
# Warmup Iteration   1: 4.589 ±(99.9%) 0.111 ms/op
Iteration   1: 3.459 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.226 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  6.967 ms/op
                 getUser·p0.9999: 7.709 ms/op
                 getUser·p1.00:   7.709 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9260
  mean =      3.459 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 27 
    [1.500, 2.000) = 165 
    [2.000, 2.500) = 388 
    [2.500, 3.000) = 1466 
    [3.000, 3.500) = 2985 
    [3.500, 4.000) = 2711 
    [4.000, 4.500) = 992 
    [4.500, 5.000) = 248 
    [5.000, 5.500) = 160 
    [5.500, 6.000) = 71 
    [6.000, 6.500) = 31 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.226 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      6.967 ms/op
     p(99.9900) =      7.709 ms/op
     p(99.9990) =      7.709 ms/op
     p(99.9999) =      7.709 ms/op
    p(100.0000) =      7.709 ms/op


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
# Warmup Iteration   1: 13.136 ±(99.9%) 0.381 ms/op
Iteration   1: 8.235 ±(99.9%) 0.101 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   7.950 ms/op
                 listUser·p0.90:   10.633 ms/op
                 listUser·p0.95:   11.730 ms/op
                 listUser·p0.99:   14.454 ms/op
                 listUser·p0.999:  20.428 ms/op
                 listUser·p0.9999: 26.411 ms/op
                 listUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3880
  mean =      8.235 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 72 
    [ 5.000,  7.500) = 1330 
    [ 7.500, 10.000) = 1916 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.075 ms/op
     p(50.0000) =      7.950 ms/op
     p(90.0000) =     10.633 ms/op
     p(95.0000) =     11.730 ms/op
     p(99.0000) =     14.454 ms/op
     p(99.9000) =     20.428 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.599          ops/ms
Client.existUser                       thrpt         12.076          ops/ms
Client.getUser                         thrpt          7.609          ops/ms
Client.listUser                        thrpt          3.460          ops/ms
Client.createUser                       avgt          3.084           ms/op
Client.existUser                        avgt          1.908           ms/op
Client.getUser                          avgt          3.124           ms/op
Client.listUser                         avgt          8.872           ms/op
Client.createUser                     sample  10789   2.963 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.071           ms/op
Client.createUser:createUser·p0.50    sample          2.789           ms/op
Client.createUser:createUser·p0.90    sample          3.805           ms/op
Client.createUser:createUser·p0.95    sample          4.084           ms/op
Client.createUser:createUser·p0.99    sample          5.169           ms/op
Client.createUser:createUser·p0.999   sample         16.732           ms/op
Client.createUser:createUser·p0.9999  sample         16.996           ms/op
Client.createUser:createUser·p1.00    sample         17.007           ms/op
Client.existUser                      sample  17073   1.884 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.444           ms/op
Client.existUser:existUser·p0.50      sample          1.868           ms/op
Client.existUser:existUser·p0.90      sample          2.339           ms/op
Client.existUser:existUser·p0.95      sample          2.490           ms/op
Client.existUser:existUser·p0.99      sample          2.991           ms/op
Client.existUser:existUser·p0.999     sample         10.060           ms/op
Client.existUser:existUser·p0.9999    sample         10.163           ms/op
Client.existUser:existUser·p1.00      sample         10.174           ms/op
Client.getUser                        sample   9260   3.459 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.106           ms/op
Client.getUser:getUser·p0.50          sample          3.437           ms/op
Client.getUser:getUser·p0.90          sample          4.226           ms/op
Client.getUser:getUser·p0.95          sample          4.604           ms/op
Client.getUser:getUser·p0.99          sample          5.612           ms/op
Client.getUser:getUser·p0.999         sample          6.967           ms/op
Client.getUser:getUser·p0.9999        sample          7.709           ms/op
Client.getUser:getUser·p1.00          sample          7.709           ms/op
Client.listUser                       sample   3880   8.235 ± 0.101   ms/op
Client.listUser:listUser·p0.00        sample          2.075           ms/op
Client.listUser:listUser·p0.50        sample          7.950           ms/op
Client.listUser:listUser·p0.90        sample         10.633           ms/op
Client.listUser:listUser·p0.95        sample         11.730           ms/op
Client.listUser:listUser·p0.99        sample         14.454           ms/op
Client.listUser:listUser·p0.999       sample         20.428           ms/op
Client.listUser:listUser·p0.9999      sample         26.411           ms/op
Client.listUser:listUser·p1.00        sample         26.411           ms/op
