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
# Warmup Iteration   1: 2.283 ops/ms
Iteration   1: 5.620 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.620 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.325 ops/ms
Iteration   1: 14.644 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.644 ops/ms


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
# Warmup Iteration   1: 4.418 ops/ms
Iteration   1: 10.009 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.009 ops/ms


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
# Warmup Iteration   1: 2.183 ops/ms
Iteration   1: 3.728 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.728 ops/ms


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.067 ms/op
Iteration   1: 3.146 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.146 ms/op


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
# Warmup Iteration   1: 3.050 ±(99.9%) 0.029 ms/op
Iteration   1: 1.699 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.699 ms/op


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
# Warmup Iteration   1: 4.596 ±(99.9%) 0.055 ms/op
Iteration   1: 3.136 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.136 ms/op


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
# Warmup Iteration   1: 12.262 ±(99.9%) 0.260 ms/op
Iteration   1: 8.265 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.265 ms/op


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
# Warmup Iteration   1: 5.116 ±(99.9%) 0.113 ms/op
Iteration   1: 3.281 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   9.593 ms/op
                 createUser·p0.999:  13.000 ms/op
                 createUser·p0.9999: 15.106 ms/op
                 createUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9816
  mean =      3.281 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1414 
    [ 2.500,  3.750) = 7063 
    [ 3.750,  5.000) = 826 
    [ 5.000,  6.250) = 171 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      9.593 ms/op
     p(99.9000) =     13.000 ms/op
     p(99.9900) =     15.106 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.128 ms/op
Iteration   1: 1.947 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   1.929 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   3.301 ms/op
                 existUser·p0.999:  8.282 ms/op
                 existUser·p0.9999: 8.797 ms/op
                 existUser·p1.00:   8.831 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16998
  mean =      1.947 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 120 
    [1.000, 1.500) = 2767 
    [1.500, 2.000) = 6654 
    [2.000, 2.500) = 6403 
    [2.500, 3.000) = 798 
    [3.000, 3.500) = 106 
    [3.500, 4.000) = 26 
    [4.000, 4.500) = 5 
    [4.500, 5.000) = 24 
    [5.000, 5.500) = 14 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 11 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 8 
    [8.000, 8.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.301 ms/op
     p(99.9000) =      8.282 ms/op
     p(99.9900) =      8.797 ms/op
     p(99.9990) =      8.831 ms/op
     p(99.9999) =      8.831 ms/op
    p(100.0000) =      8.831 ms/op


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
# Warmup Iteration   1: 4.660 ±(99.9%) 0.128 ms/op
Iteration   1: 2.857 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.650 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  11.056 ms/op
                 getUser·p0.9999: 11.865 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11192
  mean =      2.857 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 4299 
    [ 2.500,  3.750) = 5976 
    [ 3.750,  5.000) = 735 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     11.056 ms/op
     p(99.9900) =     11.865 ms/op
     p(99.9990) =     11.928 ms/op
     p(99.9999) =     11.928 ms/op
    p(100.0000) =     11.928 ms/op


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
# Warmup Iteration   1: 12.566 ±(99.9%) 0.440 ms/op
Iteration   1: 7.553 ±(99.9%) 0.111 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   7.266 ms/op
                 listUser·p0.90:   9.552 ms/op
                 listUser·p0.95:   10.486 ms/op
                 listUser·p0.99:   15.544 ms/op
                 listUser·p0.999:  25.722 ms/op
                 listUser·p0.9999: 27.656 ms/op
                 listUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4236
  mean =      7.553 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 166 
    [ 5.000,  7.500) = 2200 
    [ 7.500, 10.000) = 1559 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.429 ms/op
     p(50.0000) =      7.266 ms/op
     p(90.0000) =      9.552 ms/op
     p(95.0000) =     10.486 ms/op
     p(99.0000) =     15.544 ms/op
     p(99.9000) =     25.722 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.620          ops/ms
Client.existUser                       thrpt         14.644          ops/ms
Client.getUser                         thrpt         10.009          ops/ms
Client.listUser                        thrpt          3.728          ops/ms
Client.createUser                       avgt          3.146           ms/op
Client.existUser                        avgt          1.699           ms/op
Client.getUser                          avgt          3.136           ms/op
Client.listUser                         avgt          8.265           ms/op
Client.createUser                     sample   9816   3.281 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.174           ms/op
Client.createUser:createUser·p0.50    sample          3.060           ms/op
Client.createUser:createUser·p0.90    sample          3.990           ms/op
Client.createUser:createUser·p0.95    sample          5.104           ms/op
Client.createUser:createUser·p0.99    sample          9.593           ms/op
Client.createUser:createUser·p0.999   sample         13.000           ms/op
Client.createUser:createUser·p0.9999  sample         15.106           ms/op
Client.createUser:createUser·p1.00    sample         15.106           ms/op
Client.existUser                      sample  16998   1.947 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.511           ms/op
Client.existUser:existUser·p0.50      sample          1.929           ms/op
Client.existUser:existUser·p0.90      sample          2.417           ms/op
Client.existUser:existUser·p0.95      sample          2.564           ms/op
Client.existUser:existUser·p0.99      sample          3.301           ms/op
Client.existUser:existUser·p0.999     sample          8.282           ms/op
Client.existUser:existUser·p0.9999    sample          8.797           ms/op
Client.existUser:existUser·p1.00      sample          8.831           ms/op
Client.getUser                        sample  11192   2.857 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.826           ms/op
Client.getUser:getUser·p0.50          sample          2.650           ms/op
Client.getUser:getUser·p0.90          sample          3.678           ms/op
Client.getUser:getUser·p0.95          sample          3.977           ms/op
Client.getUser:getUser·p0.99          sample          5.775           ms/op
Client.getUser:getUser·p0.999         sample         11.056           ms/op
Client.getUser:getUser·p0.9999        sample         11.865           ms/op
Client.getUser:getUser·p1.00          sample         11.928           ms/op
Client.listUser                       sample   4236   7.553 ± 0.111   ms/op
Client.listUser:listUser·p0.00        sample          2.429           ms/op
Client.listUser:listUser·p0.50        sample          7.266           ms/op
Client.listUser:listUser·p0.90        sample          9.552           ms/op
Client.listUser:listUser·p0.95        sample         10.486           ms/op
Client.listUser:listUser·p0.99        sample         15.544           ms/op
Client.listUser:listUser·p0.999       sample         25.722           ms/op
Client.listUser:listUser·p0.9999      sample         27.656           ms/op
Client.listUser:listUser·p1.00        sample         27.656           ms/op
