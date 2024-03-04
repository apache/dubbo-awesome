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
# Warmup Iteration   1: 2.191 ops/ms
Iteration   1: 5.672 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.672 ops/ms


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
# Warmup Iteration   1: 6.592 ops/ms
Iteration   1: 13.321 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.321 ops/ms


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
# Warmup Iteration   1: 3.763 ops/ms
Iteration   1: 8.977 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.977 ops/ms


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
# Warmup Iteration   1: 2.217 ops/ms
Iteration   1: 3.773 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.773 ops/ms


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
# Warmup Iteration   1: 6.324 ±(99.9%) 0.100 ms/op
Iteration   1: 3.028 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.028 ms/op


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
# Warmup Iteration   1: 3.502 ±(99.9%) 0.033 ms/op
Iteration   1: 2.446 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.446 ms/op


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
# Warmup Iteration   1: 5.577 ±(99.9%) 0.068 ms/op
Iteration   1: 3.338 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.338 ms/op


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
# Warmup Iteration   1: 12.797 ±(99.9%) 0.244 ms/op
Iteration   1: 9.024 ±(99.9%) 0.121 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.024 ms/op


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
# Warmup Iteration   1: 4.936 ±(99.9%) 0.110 ms/op
Iteration   1: 2.942 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   2.720 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   9.139 ms/op
                 createUser·p0.999:  12.091 ms/op
                 createUser·p0.9999: 13.894 ms/op
                 createUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10858
  mean =      2.942 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 2095 
    [ 2.500,  3.750) = 7971 
    [ 3.750,  5.000) = 550 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      2.720 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      9.139 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 3.247 ±(99.9%) 0.082 ms/op
Iteration   1: 1.771 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.253 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  25.885 ms/op
                 existUser·p0.9999: 26.221 ms/op
                 existUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18054
  mean =      1.771 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17064 
    [ 2.500,  5.000) = 926 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.253 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.371 ms/op
     p(99.9000) =     25.885 ms/op
     p(99.9900) =     26.221 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.107 ms/op
Iteration   1: 3.399 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.659 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  8.253 ms/op
                 getUser·p0.9999: 10.551 ms/op
                 getUser·p1.00:   10.551 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9425
  mean =      3.399 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 9 
    [ 1.000,  2.000) = 101 
    [ 2.000,  3.000) = 3338 
    [ 3.000,  4.000) = 4445 
    [ 4.000,  5.000) = 1272 
    [ 5.000,  6.000) = 147 
    [ 6.000,  7.000) = 83 
    [ 7.000,  8.000) = 18 
    [ 8.000,  9.000) = 9 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.659 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =      8.253 ms/op
     p(99.9900) =     10.551 ms/op
     p(99.9990) =     10.551 ms/op
     p(99.9999) =     10.551 ms/op
    p(100.0000) =     10.551 ms/op


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
# Warmup Iteration   1: 15.709 ±(99.9%) 0.470 ms/op
Iteration   1: 9.401 ±(99.9%) 0.131 ms/op
                 listUser·p0.00:   1.675 ms/op
                 listUser·p0.50:   9.175 ms/op
                 listUser·p0.90:   12.234 ms/op
                 listUser·p0.95:   13.451 ms/op
                 listUser·p0.99:   16.612 ms/op
                 listUser·p0.999:  21.428 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3402
  mean =      9.401 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 47 
    [ 5.000,  7.500) = 575 
    [ 7.500, 10.000) = 1607 
    [10.000, 12.500) = 880 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.675 ms/op
     p(50.0000) =      9.175 ms/op
     p(90.0000) =     12.234 ms/op
     p(95.0000) =     13.451 ms/op
     p(99.0000) =     16.612 ms/op
     p(99.9000) =     21.428 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     23.593 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.672          ops/ms
Client.existUser                       thrpt         13.321          ops/ms
Client.getUser                         thrpt          8.977          ops/ms
Client.listUser                        thrpt          3.773          ops/ms
Client.createUser                       avgt          3.028           ms/op
Client.existUser                        avgt          2.446           ms/op
Client.getUser                          avgt          3.338           ms/op
Client.listUser                         avgt          9.024           ms/op
Client.createUser                     sample  10858   2.942 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.139           ms/op
Client.createUser:createUser·p0.50    sample          2.720           ms/op
Client.createUser:createUser·p0.90    sample          3.531           ms/op
Client.createUser:createUser·p0.95    sample          4.084           ms/op
Client.createUser:createUser·p0.99    sample          9.139           ms/op
Client.createUser:createUser·p0.999   sample         12.091           ms/op
Client.createUser:createUser·p0.9999  sample         13.894           ms/op
Client.createUser:createUser·p1.00    sample         13.894           ms/op
Client.existUser                      sample  18054   1.771 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.514           ms/op
Client.existUser:existUser·p0.50      sample          1.634           ms/op
Client.existUser:existUser·p0.90      sample          2.253           ms/op
Client.existUser:existUser·p0.95      sample          2.540           ms/op
Client.existUser:existUser·p0.99      sample          3.371           ms/op
Client.existUser:existUser·p0.999     sample         25.885           ms/op
Client.existUser:existUser·p0.9999    sample         26.221           ms/op
Client.existUser:existUser·p1.00      sample         26.247           ms/op
Client.getUser                        sample   9425   3.399 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.811           ms/op
Client.getUser:getUser·p0.50          sample          3.277           ms/op
Client.getUser:getUser·p0.90          sample          4.301           ms/op
Client.getUser:getUser·p0.95          sample          4.659           ms/op
Client.getUser:getUser·p0.99          sample          6.210           ms/op
Client.getUser:getUser·p0.999         sample          8.253           ms/op
Client.getUser:getUser·p0.9999        sample         10.551           ms/op
Client.getUser:getUser·p1.00          sample         10.551           ms/op
Client.listUser                       sample   3402   9.401 ± 0.131   ms/op
Client.listUser:listUser·p0.00        sample          1.675           ms/op
Client.listUser:listUser·p0.50        sample          9.175           ms/op
Client.listUser:listUser·p0.90        sample         12.234           ms/op
Client.listUser:listUser·p0.95        sample         13.451           ms/op
Client.listUser:listUser·p0.99        sample         16.612           ms/op
Client.listUser:listUser·p0.999       sample         21.428           ms/op
Client.listUser:listUser·p0.9999      sample         23.593           ms/op
Client.listUser:listUser·p1.00        sample         23.593           ms/op
