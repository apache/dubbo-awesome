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
# Warmup Iteration   1: 2.058 ops/ms
Iteration   1: 5.243 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.243 ops/ms


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
# Warmup Iteration   1: 5.693 ops/ms
Iteration   1: 13.719 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.719 ops/ms


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
# Warmup Iteration   1: 3.198 ops/ms
Iteration   1: 7.399 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.399 ops/ms


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
# Warmup Iteration   1: 1.831 ops/ms
Iteration   1: 3.241 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.241 ops/ms


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
# Warmup Iteration   1: 6.473 ±(99.9%) 0.150 ms/op
Iteration   1: 3.195 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.195 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.027 ms/op
Iteration   1: 1.869 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.869 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.687 ±(99.9%) 0.061 ms/op
Iteration   1: 3.237 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.237 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.992 ±(99.9%) 0.229 ms/op
Iteration   1: 8.980 ±(99.9%) 0.107 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.980 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.140 ±(99.9%) 0.112 ms/op
Iteration   1: 3.111 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   2.851 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   8.287 ms/op
                 createUser·p0.999:  14.708 ms/op
                 createUser·p0.9999: 15.417 ms/op
                 createUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10266
  mean =      3.111 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2187 
    [ 2.500,  3.750) = 6523 
    [ 3.750,  5.000) = 1316 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      8.287 ms/op
     p(99.9000) =     14.708 ms/op
     p(99.9900) =     15.417 ms/op
     p(99.9990) =     15.417 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.244 ±(99.9%) 0.110 ms/op
Iteration   1: 2.030 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.666 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   3.351 ms/op
                 existUser·p0.999:  15.548 ms/op
                 existUser·p0.9999: 15.857 ms/op
                 existUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15850
  mean =      2.030 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 205 
    [ 1.250,  2.500) = 13242 
    [ 2.500,  3.750) = 2302 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      3.351 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     15.857 ms/op
     p(99.9990) =     15.876 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.970 ±(99.9%) 0.118 ms/op
Iteration   1: 3.338 ±(99.9%) 0.064 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.599 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  32.885 ms/op
                 getUser·p0.9999: 36.110 ms/op
                 getUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9572
  mean =      3.338 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1267 
    [ 2.500,  5.000) = 8000 
    [ 5.000,  7.500) = 232 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.599 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     32.885 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     36.110 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.632 ±(99.9%) 0.472 ms/op
Iteration   1: 8.877 ±(99.9%) 0.321 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   8.045 ms/op
                 listUser·p0.90:   11.010 ms/op
                 listUser·p0.95:   12.541 ms/op
                 listUser·p0.99:   30.982 ms/op
                 listUser·p0.999:  72.360 ms/op
                 listUser·p0.9999: 74.973 ms/op
                 listUser·p1.00:   74.973 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3616
  mean =      8.877 ±(99.9%) 0.321 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 85 
    [ 5.000, 10.000) = 2932 
    [10.000, 15.000) = 501 
    [15.000, 20.000) = 53 
    [20.000, 25.000) = 9 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 14 
    [70.000, 75.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.470 ms/op
     p(50.0000) =      8.045 ms/op
     p(90.0000) =     11.010 ms/op
     p(95.0000) =     12.541 ms/op
     p(99.0000) =     30.982 ms/op
     p(99.9000) =     72.360 ms/op
     p(99.9900) =     74.973 ms/op
     p(99.9990) =     74.973 ms/op
     p(99.9999) =     74.973 ms/op
    p(100.0000) =     74.973 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.243          ops/ms
Client.existUser                       thrpt         13.719          ops/ms
Client.getUser                         thrpt          7.399          ops/ms
Client.listUser                        thrpt          3.241          ops/ms
Client.createUser                       avgt          3.195           ms/op
Client.existUser                        avgt          1.869           ms/op
Client.getUser                          avgt          3.237           ms/op
Client.listUser                         avgt          8.980           ms/op
Client.createUser                     sample  10266   3.111 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.077           ms/op
Client.createUser:createUser·p0.50    sample          2.851           ms/op
Client.createUser:createUser·p0.90    sample          3.936           ms/op
Client.createUser:createUser·p0.95    sample          4.202           ms/op
Client.createUser:createUser·p0.99    sample          8.287           ms/op
Client.createUser:createUser·p0.999   sample         14.708           ms/op
Client.createUser:createUser·p0.9999  sample         15.417           ms/op
Client.createUser:createUser·p1.00    sample         15.417           ms/op
Client.existUser                      sample  15850   2.030 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.641           ms/op
Client.existUser:existUser·p0.50      sample          1.880           ms/op
Client.existUser:existUser·p0.90      sample          2.666           ms/op
Client.existUser:existUser·p0.95      sample          2.855           ms/op
Client.existUser:existUser·p0.99      sample          3.351           ms/op
Client.existUser:existUser·p0.999     sample         15.548           ms/op
Client.existUser:existUser·p0.9999    sample         15.857           ms/op
Client.existUser:existUser·p1.00      sample         15.876           ms/op
Client.getUser                        sample   9572   3.338 ± 0.064   ms/op
Client.getUser:getUser·p0.00          sample          0.595           ms/op
Client.getUser:getUser·p0.50          sample          3.183           ms/op
Client.getUser:getUser·p0.90          sample          4.071           ms/op
Client.getUser:getUser·p0.95          sample          4.599           ms/op
Client.getUser:getUser·p0.99          sample          6.332           ms/op
Client.getUser:getUser·p0.999         sample         32.885           ms/op
Client.getUser:getUser·p0.9999        sample         36.110           ms/op
Client.getUser:getUser·p1.00          sample         36.110           ms/op
Client.listUser                       sample   3616   8.877 ± 0.321   ms/op
Client.listUser:listUser·p0.00        sample          2.470           ms/op
Client.listUser:listUser·p0.50        sample          8.045           ms/op
Client.listUser:listUser·p0.90        sample         11.010           ms/op
Client.listUser:listUser·p0.95        sample         12.541           ms/op
Client.listUser:listUser·p0.99        sample         30.982           ms/op
Client.listUser:listUser·p0.999       sample         72.360           ms/op
Client.listUser:listUser·p0.9999      sample         74.973           ms/op
Client.listUser:listUser·p1.00        sample         74.973           ms/op
