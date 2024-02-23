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
# Warmup Iteration   1: 2.680 ops/ms
Iteration   1: 6.560 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.560 ops/ms


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
# Warmup Iteration   1: 6.407 ops/ms
Iteration   1: 12.580 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.580 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ops/ms
Iteration   1: 9.289 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.289 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.500 ops/ms
Iteration   1: 3.382 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.382 ops/ms


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
# Warmup Iteration   1: 5.333 ±(99.9%) 0.076 ms/op
Iteration   1: 3.283 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.283 ms/op


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
# Warmup Iteration   1: 2.914 ±(99.9%) 0.026 ms/op
Iteration   1: 1.766 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.766 ms/op


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
# Warmup Iteration   1: 4.841 ±(99.9%) 0.053 ms/op
Iteration   1: 2.877 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.877 ms/op


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
# Warmup Iteration   1: 11.546 ±(99.9%) 0.226 ms/op
Iteration   1: 8.860 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.860 ms/op


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.110 ms/op
Iteration   1: 2.892 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   2.785 ms/op
                 createUser·p0.90:   3.766 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  11.289 ms/op
                 createUser·p0.9999: 11.319 ms/op
                 createUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11314
  mean =      2.892 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 4023 
    [ 2.500,  3.750) = 6126 
    [ 3.750,  5.000) = 986 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.766 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     11.319 ms/op
     p(99.9990) =     11.321 ms/op
     p(99.9999) =     11.321 ms/op
    p(100.0000) =     11.321 ms/op


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
# Warmup Iteration   1: 3.108 ±(99.9%) 0.072 ms/op
Iteration   1: 1.908 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.437 ms/op
                 existUser·p0.50:   1.843 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.084 ms/op
                 existUser·p0.999:  13.222 ms/op
                 existUser·p0.9999: 13.303 ms/op
                 existUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16787
  mean =      1.908 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 401 
    [ 1.250,  2.500) = 15185 
    [ 2.500,  3.750) = 1104 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.084 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     13.303 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.480 ±(99.9%) 0.098 ms/op
Iteration   1: 3.158 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  8.199 ms/op
                 getUser·p0.9999: 8.217 ms/op
                 getUser·p1.00:   8.217 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10130
  mean =      3.158 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 219 
    [2.000, 2.500) = 2219 
    [2.500, 3.000) = 2647 
    [3.000, 3.500) = 1559 
    [3.500, 4.000) = 1846 
    [4.000, 4.500) = 1148 
    [4.500, 5.000) = 267 
    [5.000, 5.500) = 72 
    [5.500, 6.000) = 72 
    [6.000, 6.500) = 27 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 7 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      8.199 ms/op
     p(99.9900) =      8.217 ms/op
     p(99.9990) =      8.217 ms/op
     p(99.9999) =      8.217 ms/op
    p(100.0000) =      8.217 ms/op


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
# Warmup Iteration   1: 13.008 ±(99.9%) 0.401 ms/op
Iteration   1: 9.397 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   4.157 ms/op
                 listUser·p0.50:   8.913 ms/op
                 listUser·p0.90:   12.517 ms/op
                 listUser·p0.95:   13.926 ms/op
                 listUser·p0.99:   18.340 ms/op
                 listUser·p0.999:  23.601 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3409
  mean =      9.397 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 22 
    [ 5.000,  7.500) = 620 
    [ 7.500, 10.000) = 1721 
    [10.000, 12.500) = 704 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      4.157 ms/op
     p(50.0000) =      8.913 ms/op
     p(90.0000) =     12.517 ms/op
     p(95.0000) =     13.926 ms/op
     p(99.0000) =     18.340 ms/op
     p(99.9000) =     23.601 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.560          ops/ms
Client.existUser                       thrpt         12.580          ops/ms
Client.getUser                         thrpt          9.289          ops/ms
Client.listUser                        thrpt          3.382          ops/ms
Client.createUser                       avgt          3.283           ms/op
Client.existUser                        avgt          1.766           ms/op
Client.getUser                          avgt          2.877           ms/op
Client.listUser                         avgt          8.860           ms/op
Client.createUser                     sample  11314   2.892 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          0.966           ms/op
Client.createUser:createUser·p0.50    sample          2.785           ms/op
Client.createUser:createUser·p0.90    sample          3.766           ms/op
Client.createUser:createUser·p0.95    sample          4.055           ms/op
Client.createUser:createUser·p0.99    sample          5.710           ms/op
Client.createUser:createUser·p0.999   sample         11.289           ms/op
Client.createUser:createUser·p0.9999  sample         11.319           ms/op
Client.createUser:createUser·p1.00    sample         11.321           ms/op
Client.existUser                      sample  16787   1.908 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.437           ms/op
Client.existUser:existUser·p0.50      sample          1.843           ms/op
Client.existUser:existUser·p0.90      sample          2.367           ms/op
Client.existUser:existUser·p0.95      sample          2.585           ms/op
Client.existUser:existUser·p0.99      sample          3.084           ms/op
Client.existUser:existUser·p0.999     sample         13.222           ms/op
Client.existUser:existUser·p0.9999    sample         13.303           ms/op
Client.existUser:existUser·p1.00      sample         13.337           ms/op
Client.getUser                        sample  10130   3.158 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.606           ms/op
Client.getUser:getUser·p0.50          sample          2.986           ms/op
Client.getUser:getUser·p0.90          sample          4.235           ms/op
Client.getUser:getUser·p0.95          sample          4.481           ms/op
Client.getUser:getUser·p0.99          sample          5.702           ms/op
Client.getUser:getUser·p0.999         sample          8.199           ms/op
Client.getUser:getUser·p0.9999        sample          8.217           ms/op
Client.getUser:getUser·p1.00          sample          8.217           ms/op
Client.listUser                       sample   3409   9.397 ± 0.137   ms/op
Client.listUser:listUser·p0.00        sample          4.157           ms/op
Client.listUser:listUser·p0.50        sample          8.913           ms/op
Client.listUser:listUser·p0.90        sample         12.517           ms/op
Client.listUser:listUser·p0.95        sample         13.926           ms/op
Client.listUser:listUser·p0.99        sample         18.340           ms/op
Client.listUser:listUser·p0.999       sample         23.601           ms/op
Client.listUser:listUser·p0.9999      sample         25.494           ms/op
Client.listUser:listUser·p1.00        sample         25.494           ms/op
