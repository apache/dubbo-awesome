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
# Warmup Iteration   1: 2.405 ops/ms
Iteration   1: 6.809 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.809 ops/ms


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
# Warmup Iteration   1: 6.668 ops/ms
Iteration   1: 13.463 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.463 ops/ms


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
# Warmup Iteration   1: 3.747 ops/ms
Iteration   1: 8.696 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.696 ops/ms


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
# Warmup Iteration   1: 2.205 ops/ms
Iteration   1: 3.912 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.912 ops/ms


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
# Warmup Iteration   1: 5.108 ±(99.9%) 0.058 ms/op
Iteration   1: 3.274 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.274 ms/op


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
# Warmup Iteration   1: 3.287 ±(99.9%) 0.032 ms/op
Iteration   1: 1.843 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.843 ms/op


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.055 ms/op
Iteration   1: 2.776 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.776 ms/op


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
# Warmup Iteration   1: 11.645 ±(99.9%) 0.197 ms/op
Iteration   1: 7.524 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.524 ms/op


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.093 ms/op
Iteration   1: 2.989 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   2.703 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   9.044 ms/op
                 createUser·p0.999:  13.468 ms/op
                 createUser·p0.9999: 13.560 ms/op
                 createUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10688
  mean =      2.989 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2348 
    [ 2.500,  3.750) = 7344 
    [ 3.750,  5.000) = 641 
    [ 5.000,  6.250) = 108 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      2.703 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     13.560 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


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
# Warmup Iteration   1: 3.427 ±(99.9%) 0.117 ms/op
Iteration   1: 1.802 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   4.232 ms/op
                 existUser·p0.999:  5.259 ms/op
                 existUser·p0.9999: 6.012 ms/op
                 existUser·p1.00:   6.177 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17738
  mean =      1.802 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 221 
    [1.000, 1.500) = 2405 
    [1.500, 2.000) = 11905 
    [2.000, 2.500) = 2149 
    [2.500, 3.000) = 683 
    [3.000, 3.500) = 89 
    [3.500, 4.000) = 91 
    [4.000, 4.500) = 44 
    [4.500, 5.000) = 115 
    [5.000, 5.500) = 33 
    [5.500, 6.000) = 2 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      4.232 ms/op
     p(99.9000) =      5.259 ms/op
     p(99.9900) =      6.012 ms/op
     p(99.9990) =      6.177 ms/op
     p(99.9999) =      6.177 ms/op
    p(100.0000) =      6.177 ms/op


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.099 ms/op
Iteration   1: 2.609 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   2.372 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.988 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 19.311 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12253
  mean =      2.609 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 7478 
    [ 2.500,  3.750) = 4215 
    [ 3.750,  5.000) = 425 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      2.372 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.988 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     19.311 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 11.286 ±(99.9%) 0.331 ms/op
Iteration   1: 7.785 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   2.892 ms/op
                 listUser·p0.50:   7.414 ms/op
                 listUser·p0.90:   9.896 ms/op
                 listUser·p0.95:   11.125 ms/op
                 listUser·p0.99:   18.579 ms/op
                 listUser·p0.999:  22.961 ms/op
                 listUser·p0.9999: 25.297 ms/op
                 listUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4119
  mean =      7.785 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 196 
    [ 5.000,  7.500) = 1976 
    [ 7.500, 10.000) = 1557 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.892 ms/op
     p(50.0000) =      7.414 ms/op
     p(90.0000) =      9.896 ms/op
     p(95.0000) =     11.125 ms/op
     p(99.0000) =     18.579 ms/op
     p(99.9000) =     22.961 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.809          ops/ms
Client.existUser                       thrpt         13.463          ops/ms
Client.getUser                         thrpt          8.696          ops/ms
Client.listUser                        thrpt          3.912          ops/ms
Client.createUser                       avgt          3.274           ms/op
Client.existUser                        avgt          1.843           ms/op
Client.getUser                          avgt          2.776           ms/op
Client.listUser                         avgt          7.524           ms/op
Client.createUser                     sample  10688   2.989 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.354           ms/op
Client.createUser:createUser·p0.50    sample          2.703           ms/op
Client.createUser:createUser·p0.90    sample          3.699           ms/op
Client.createUser:createUser·p0.95    sample          4.375           ms/op
Client.createUser:createUser·p0.99    sample          9.044           ms/op
Client.createUser:createUser·p0.999   sample         13.468           ms/op
Client.createUser:createUser·p0.9999  sample         13.560           ms/op
Client.createUser:createUser·p1.00    sample         13.566           ms/op
Client.existUser                      sample  17738   1.802 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.583           ms/op
Client.existUser:existUser·p0.50      sample          1.708           ms/op
Client.existUser:existUser·p0.90      sample          2.273           ms/op
Client.existUser:existUser·p0.95      sample          2.564           ms/op
Client.existUser:existUser·p0.99      sample          4.232           ms/op
Client.existUser:existUser·p0.999     sample          5.259           ms/op
Client.existUser:existUser·p0.9999    sample          6.012           ms/op
Client.existUser:existUser·p1.00      sample          6.177           ms/op
Client.getUser                        sample  12253   2.609 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          0.982           ms/op
Client.getUser:getUser·p0.50          sample          2.372           ms/op
Client.getUser:getUser·p0.90          sample          3.375           ms/op
Client.getUser:getUser·p0.95          sample          3.715           ms/op
Client.getUser:getUser·p0.99          sample          4.988           ms/op
Client.getUser:getUser·p0.999         sample         19.202           ms/op
Client.getUser:getUser·p0.9999        sample         19.311           ms/op
Client.getUser:getUser·p1.00          sample         19.333           ms/op
Client.listUser                       sample   4119   7.785 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          2.892           ms/op
Client.listUser:listUser·p0.50        sample          7.414           ms/op
Client.listUser:listUser·p0.90        sample          9.896           ms/op
Client.listUser:listUser·p0.95        sample         11.125           ms/op
Client.listUser:listUser·p0.99        sample         18.579           ms/op
Client.listUser:listUser·p0.999       sample         22.961           ms/op
Client.listUser:listUser·p0.9999      sample         25.297           ms/op
Client.listUser:listUser·p1.00        sample         25.297           ms/op
