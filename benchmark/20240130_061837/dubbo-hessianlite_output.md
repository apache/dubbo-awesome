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
# Warmup Iteration   1: 2.044 ops/ms
Iteration   1: 5.673 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.673 ops/ms


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
# Warmup Iteration   1: 5.557 ops/ms
Iteration   1: 13.277 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.277 ops/ms


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
# Warmup Iteration   1: 4.544 ops/ms
Iteration   1: 9.441 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.441 ops/ms


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
# Warmup Iteration   1: 1.825 ops/ms
Iteration   1: 3.246 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.246 ops/ms


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
# Warmup Iteration   1: 5.749 ±(99.9%) 0.085 ms/op
Iteration   1: 3.025 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.025 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.034 ms/op
Iteration   1: 1.986 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.986 ms/op


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
# Warmup Iteration   1: 5.249 ±(99.9%) 0.057 ms/op
Iteration   1: 3.255 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.255 ms/op


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
# Warmup Iteration   1: 14.393 ±(99.9%) 0.282 ms/op
Iteration   1: 10.271 ±(99.9%) 0.155 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.271 ms/op


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
# Warmup Iteration   1: 5.508 ±(99.9%) 0.139 ms/op
Iteration   1: 3.336 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.818 ms/op
                 createUser·p0.99:   12.059 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 21.332 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9597
  mean =      3.336 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 770 
    [ 2.500,  5.000) = 8415 
    [ 5.000,  7.500) = 232 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.818 ms/op
     p(99.0000) =     12.059 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.072 ms/op
Iteration   1: 1.787 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.410 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   2.892 ms/op
                 existUser·p0.999:  6.262 ms/op
                 existUser·p0.9999: 7.906 ms/op
                 existUser·p1.00:   7.938 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17893
  mean =      1.787 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 11 
    [0.500, 1.000) = 466 
    [1.000, 1.500) = 2324 
    [1.500, 2.000) = 11902 
    [2.000, 2.500) = 2595 
    [2.500, 3.000) = 458 
    [3.000, 3.500) = 36 
    [3.500, 4.000) = 17 
    [4.000, 4.500) = 15 
    [4.500, 5.000) = 34 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 25 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      2.892 ms/op
     p(99.9000) =      6.262 ms/op
     p(99.9900) =      7.906 ms/op
     p(99.9990) =      7.938 ms/op
     p(99.9999) =      7.938 ms/op
    p(100.0000) =      7.938 ms/op


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
# Warmup Iteration   1: 5.048 ±(99.9%) 0.119 ms/op
Iteration   1: 3.002 ±(99.9%) 0.050 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   2.716 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.373 ms/op
                 getUser·p0.999:  27.853 ms/op
                 getUser·p0.9999: 28.567 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10705
  mean =      3.002 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3945 
    [ 2.500,  5.000) = 6606 
    [ 5.000,  7.500) = 120 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.373 ms/op
     p(99.9000) =     27.853 ms/op
     p(99.9900) =     28.567 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 13.126 ±(99.9%) 0.446 ms/op
Iteration   1: 9.964 ±(99.9%) 0.167 ms/op
                 listUser·p0.00:   3.211 ms/op
                 listUser·p0.50:   9.535 ms/op
                 listUser·p0.90:   13.761 ms/op
                 listUser·p0.95:   15.427 ms/op
                 listUser·p0.99:   18.902 ms/op
                 listUser·p0.999:  23.358 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3216
  mean =      9.964 ±(99.9%) 0.167 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 56 
    [ 5.000,  7.500) = 481 
    [ 7.500, 10.000) = 1361 
    [10.000, 12.500) = 792 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.211 ms/op
     p(50.0000) =      9.535 ms/op
     p(90.0000) =     13.761 ms/op
     p(95.0000) =     15.427 ms/op
     p(99.0000) =     18.902 ms/op
     p(99.9000) =     23.358 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.673          ops/ms
Client.existUser                       thrpt         13.277          ops/ms
Client.getUser                         thrpt          9.441          ops/ms
Client.listUser                        thrpt          3.246          ops/ms
Client.createUser                       avgt          3.025           ms/op
Client.existUser                        avgt          1.986           ms/op
Client.getUser                          avgt          3.255           ms/op
Client.listUser                         avgt         10.271           ms/op
Client.createUser                     sample   9597   3.336 ± 0.053   ms/op
Client.createUser:createUser·p0.00    sample          0.674           ms/op
Client.createUser:createUser·p0.50    sample          3.043           ms/op
Client.createUser:createUser·p0.90    sample          3.920           ms/op
Client.createUser:createUser·p0.95    sample          4.818           ms/op
Client.createUser:createUser·p0.99    sample         12.059           ms/op
Client.createUser:createUser·p0.999   sample         19.202           ms/op
Client.createUser:createUser·p0.9999  sample         21.332           ms/op
Client.createUser:createUser·p1.00    sample         21.332           ms/op
Client.existUser                      sample  17893   1.787 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.410           ms/op
Client.existUser:existUser·p0.50      sample          1.780           ms/op
Client.existUser:existUser·p0.90      sample          2.126           ms/op
Client.existUser:existUser·p0.95      sample          2.347           ms/op
Client.existUser:existUser·p0.99      sample          2.892           ms/op
Client.existUser:existUser·p0.999     sample          6.262           ms/op
Client.existUser:existUser·p0.9999    sample          7.906           ms/op
Client.existUser:existUser·p1.00      sample          7.938           ms/op
Client.getUser                        sample  10705   3.002 ± 0.050   ms/op
Client.getUser:getUser·p0.00          sample          0.680           ms/op
Client.getUser:getUser·p0.50          sample          2.716           ms/op
Client.getUser:getUser·p0.90          sample          4.026           ms/op
Client.getUser:getUser·p0.95          sample          4.235           ms/op
Client.getUser:getUser·p0.99          sample          5.373           ms/op
Client.getUser:getUser·p0.999         sample         27.853           ms/op
Client.getUser:getUser·p0.9999        sample         28.567           ms/op
Client.getUser:getUser·p1.00          sample         28.574           ms/op
Client.listUser                       sample   3216   9.964 ± 0.167   ms/op
Client.listUser:listUser·p0.00        sample          3.211           ms/op
Client.listUser:listUser·p0.50        sample          9.535           ms/op
Client.listUser:listUser·p0.90        sample         13.761           ms/op
Client.listUser:listUser·p0.95        sample         15.427           ms/op
Client.listUser:listUser·p0.99        sample         18.902           ms/op
Client.listUser:listUser·p0.999       sample         23.358           ms/op
Client.listUser:listUser·p0.9999      sample         23.757           ms/op
Client.listUser:listUser·p1.00        sample         23.757           ms/op
