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
# Warmup Iteration   1: 2.052 ops/ms
Iteration   1: 5.911 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.911 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.911 ops/ms
Iteration   1: 11.599 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.599 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.527 ops/ms
Iteration   1: 7.758 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.758 ops/ms


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
# Warmup Iteration   1: 2.128 ops/ms
Iteration   1: 3.572 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.572 ops/ms


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
# Warmup Iteration   1: 5.799 ±(99.9%) 0.091 ms/op
Iteration   1: 3.430 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.430 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.039 ms/op
Iteration   1: 2.163 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.163 ms/op


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
# Warmup Iteration   1: 5.480 ±(99.9%) 0.084 ms/op
Iteration   1: 3.093 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.093 ms/op


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
# Warmup Iteration   1: 13.974 ±(99.9%) 0.260 ms/op
Iteration   1: 8.464 ±(99.9%) 0.105 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.464 ms/op


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
# Warmup Iteration   1: 5.298 ±(99.9%) 0.141 ms/op
Iteration   1: 3.470 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   10.240 ms/op
                 createUser·p0.999:  22.538 ms/op
                 createUser·p0.9999: 27.132 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9193
  mean =      3.470 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 688 
    [ 2.500,  5.000) = 8154 
    [ 5.000,  7.500) = 216 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     22.538 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.086 ms/op
Iteration   1: 1.959 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   3.644 ms/op
                 existUser·p0.999:  8.618 ms/op
                 existUser·p0.9999: 8.788 ms/op
                 existUser·p1.00:   8.798 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16339
  mean =      1.959 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 19 
    [1.000, 1.500) = 1132 
    [1.500, 2.000) = 8949 
    [2.000, 2.500) = 5147 
    [2.500, 3.000) = 751 
    [3.000, 3.500) = 152 
    [3.500, 4.000) = 50 
    [4.000, 4.500) = 17 
    [4.500, 5.000) = 53 
    [5.000, 5.500) = 15 
    [5.500, 6.000) = 19 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.644 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =      8.788 ms/op
     p(99.9990) =      8.798 ms/op
     p(99.9999) =      8.798 ms/op
    p(100.0000) =      8.798 ms/op


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
# Warmup Iteration   1: 4.985 ±(99.9%) 0.134 ms/op
Iteration   1: 3.073 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  6.929 ms/op
                 getUser·p0.9999: 12.919 ms/op
                 getUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10398
  mean =      3.073 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2683 
    [ 2.500,  3.750) = 5889 
    [ 3.750,  5.000) = 1667 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      6.929 ms/op
     p(99.9900) =     12.919 ms/op
     p(99.9990) =     13.042 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


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
# Warmup Iteration   1: 13.072 ±(99.9%) 0.458 ms/op
Iteration   1: 9.461 ±(99.9%) 0.174 ms/op
                 listUser·p0.00:   3.002 ms/op
                 listUser·p0.50:   8.798 ms/op
                 listUser·p0.90:   12.616 ms/op
                 listUser·p0.95:   13.910 ms/op
                 listUser·p0.99:   22.044 ms/op
                 listUser·p0.999:  28.889 ms/op
                 listUser·p0.9999: 36.635 ms/op
                 listUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3381
  mean =      9.461 ±(99.9%) 0.174 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 29 
    [ 5.000,  7.500) = 749 
    [ 7.500, 10.000) = 1513 
    [10.000, 12.500) = 729 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.002 ms/op
     p(50.0000) =      8.798 ms/op
     p(90.0000) =     12.616 ms/op
     p(95.0000) =     13.910 ms/op
     p(99.0000) =     22.044 ms/op
     p(99.9000) =     28.889 ms/op
     p(99.9900) =     36.635 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.911          ops/ms
Client.existUser                       thrpt         11.599          ops/ms
Client.getUser                         thrpt          7.758          ops/ms
Client.listUser                        thrpt          3.572          ops/ms
Client.createUser                       avgt          3.430           ms/op
Client.existUser                        avgt          2.163           ms/op
Client.getUser                          avgt          3.093           ms/op
Client.listUser                         avgt          8.464           ms/op
Client.createUser                     sample   9193   3.470 ± 0.057   ms/op
Client.createUser:createUser·p0.00    sample          1.374           ms/op
Client.createUser:createUser·p0.50    sample          3.097           ms/op
Client.createUser:createUser·p0.90    sample          4.530           ms/op
Client.createUser:createUser·p0.95    sample          4.817           ms/op
Client.createUser:createUser·p0.99    sample         10.240           ms/op
Client.createUser:createUser·p0.999   sample         22.538           ms/op
Client.createUser:createUser·p0.9999  sample         27.132           ms/op
Client.createUser:createUser·p1.00    sample         27.132           ms/op
Client.existUser                      sample  16339   1.959 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.772           ms/op
Client.existUser:existUser·p0.50      sample          1.860           ms/op
Client.existUser:existUser·p0.90      sample          2.396           ms/op
Client.existUser:existUser·p0.95      sample          2.580           ms/op
Client.existUser:existUser·p0.99      sample          3.644           ms/op
Client.existUser:existUser·p0.999     sample          8.618           ms/op
Client.existUser:existUser·p0.9999    sample          8.788           ms/op
Client.existUser:existUser·p1.00      sample          8.798           ms/op
Client.getUser                        sample  10398   3.073 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.270           ms/op
Client.getUser:getUser·p0.50          sample          2.949           ms/op
Client.getUser:getUser·p0.90          sample          4.080           ms/op
Client.getUser:getUser·p0.95          sample          4.284           ms/op
Client.getUser:getUser·p0.99          sample          5.423           ms/op
Client.getUser:getUser·p0.999         sample          6.929           ms/op
Client.getUser:getUser·p0.9999        sample         12.919           ms/op
Client.getUser:getUser·p1.00          sample         13.042           ms/op
Client.listUser                       sample   3381   9.461 ± 0.174   ms/op
Client.listUser:listUser·p0.00        sample          3.002           ms/op
Client.listUser:listUser·p0.50        sample          8.798           ms/op
Client.listUser:listUser·p0.90        sample         12.616           ms/op
Client.listUser:listUser·p0.95        sample         13.910           ms/op
Client.listUser:listUser·p0.99        sample         22.044           ms/op
Client.listUser:listUser·p0.999       sample         28.889           ms/op
Client.listUser:listUser·p0.9999      sample         36.635           ms/op
Client.listUser:listUser·p1.00        sample         36.635           ms/op
