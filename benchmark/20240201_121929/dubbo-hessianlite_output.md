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
# Warmup Iteration   1: 2.843 ops/ms
Iteration   1: 6.087 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.087 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 6.528 ops/ms
Iteration   1: 13.536 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.536 ops/ms


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
# Warmup Iteration   1: 5.116 ops/ms
Iteration   1: 8.876 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.876 ops/ms


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
# Warmup Iteration   1: 2.177 ops/ms
Iteration   1: 3.377 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.377 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.176 ±(99.9%) 0.063 ms/op
Iteration   1: 3.108 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.108 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.829 ±(99.9%) 0.029 ms/op
Iteration   1: 1.706 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.706 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.040 ±(99.9%) 0.047 ms/op
Iteration   1: 3.072 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.072 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:33
# Fork: 1 of 1
# Warmup Iteration   1: 11.944 ±(99.9%) 0.227 ms/op
Iteration   1: 8.677 ±(99.9%) 0.144 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.677 ms/op


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
# Warmup Iteration   1: 4.491 ±(99.9%) 0.092 ms/op
Iteration   1: 2.722 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.155 ms/op
                 createUser·p0.999:  7.539 ms/op
                 createUser·p0.9999: 8.552 ms/op
                 createUser·p1.00:   8.552 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11737
  mean =      2.722 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 6 
    [1.000, 1.500) = 86 
    [1.500, 2.000) = 769 
    [2.000, 2.500) = 4146 
    [2.500, 3.000) = 3896 
    [3.000, 3.500) = 1687 
    [3.500, 4.000) = 697 
    [4.000, 4.500) = 187 
    [4.500, 5.000) = 122 
    [5.000, 5.500) = 41 
    [5.500, 6.000) = 7 
    [6.000, 6.500) = 25 
    [6.500, 7.000) = 19 
    [7.000, 7.500) = 32 
    [7.500, 8.000) = 11 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.155 ms/op
     p(99.9000) =      7.539 ms/op
     p(99.9900) =      8.552 ms/op
     p(99.9990) =      8.552 ms/op
     p(99.9999) =      8.552 ms/op
    p(100.0000) =      8.552 ms/op


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
# Warmup Iteration   1: 3.108 ±(99.9%) 0.067 ms/op
Iteration   1: 1.985 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.539 ms/op
                 existUser·p0.95:   2.732 ms/op
                 existUser·p0.99:   3.909 ms/op
                 existUser·p0.999:  26.997 ms/op
                 existUser·p0.9999: 27.886 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16121
  mean =      1.985 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14249 
    [ 2.500,  5.000) = 1737 
    [ 5.000,  7.500) = 71 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.539 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.909 ms/op
     p(99.9000) =     26.997 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.092 ms/op
Iteration   1: 2.937 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.692 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  6.704 ms/op
                 getUser·p0.9999: 9.074 ms/op
                 getUser·p1.00:   9.257 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10895
  mean =      2.937 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 27 
    [ 1.500,  2.000) = 685 
    [ 2.000,  2.500) = 2339 
    [ 2.500,  3.000) = 2873 
    [ 3.000,  3.500) = 3220 
    [ 3.500,  4.000) = 1136 
    [ 4.000,  4.500) = 327 
    [ 4.500,  5.000) = 134 
    [ 5.000,  5.500) = 61 
    [ 5.500,  6.000) = 31 
    [ 6.000,  6.500) = 40 
    [ 6.500,  7.000) = 19 
    [ 7.000,  7.500) = 2 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.692 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =      6.704 ms/op
     p(99.9900) =      9.074 ms/op
     p(99.9990) =      9.257 ms/op
     p(99.9999) =      9.257 ms/op
    p(100.0000) =      9.257 ms/op


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
# Warmup Iteration   1: 12.494 ±(99.9%) 0.408 ms/op
Iteration   1: 8.237 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   7.823 ms/op
                 listUser·p0.90:   10.943 ms/op
                 listUser·p0.95:   12.468 ms/op
                 listUser·p0.99:   17.658 ms/op
                 listUser·p0.999:  23.449 ms/op
                 listUser·p0.9999: 25.297 ms/op
                 listUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3910
  mean =      8.237 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 156 
    [ 5.000,  7.500) = 1455 
    [ 7.500, 10.000) = 1640 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      7.823 ms/op
     p(90.0000) =     10.943 ms/op
     p(95.0000) =     12.468 ms/op
     p(99.0000) =     17.658 ms/op
     p(99.9000) =     23.449 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.087          ops/ms
Client.existUser                       thrpt         13.536          ops/ms
Client.getUser                         thrpt          8.876          ops/ms
Client.listUser                        thrpt          3.377          ops/ms
Client.createUser                       avgt          3.108           ms/op
Client.existUser                        avgt          1.706           ms/op
Client.getUser                          avgt          3.072           ms/op
Client.listUser                         avgt          8.677           ms/op
Client.createUser                     sample  11737   2.722 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          0.912           ms/op
Client.createUser:createUser·p0.50    sample          2.564           ms/op
Client.createUser:createUser·p0.90    sample          3.490           ms/op
Client.createUser:createUser·p0.95    sample          3.867           ms/op
Client.createUser:createUser·p0.99    sample          5.155           ms/op
Client.createUser:createUser·p0.999   sample          7.539           ms/op
Client.createUser:createUser·p0.9999  sample          8.552           ms/op
Client.createUser:createUser·p1.00    sample          8.552           ms/op
Client.existUser                      sample  16121   1.985 ± 0.033   ms/op
Client.existUser:existUser·p0.00      sample          0.524           ms/op
Client.existUser:existUser·p0.50      sample          1.806           ms/op
Client.existUser:existUser·p0.90      sample          2.539           ms/op
Client.existUser:existUser·p0.95      sample          2.732           ms/op
Client.existUser:existUser·p0.99      sample          3.909           ms/op
Client.existUser:existUser·p0.999     sample         26.997           ms/op
Client.existUser:existUser·p0.9999    sample         27.886           ms/op
Client.existUser:existUser·p1.00      sample         27.886           ms/op
Client.getUser                        sample  10895   2.937 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          1.176           ms/op
Client.getUser:getUser·p0.50          sample          2.933           ms/op
Client.getUser:getUser·p0.90          sample          3.692           ms/op
Client.getUser:getUser·p0.95          sample          4.047           ms/op
Client.getUser:getUser·p0.99          sample          5.194           ms/op
Client.getUser:getUser·p0.999         sample          6.704           ms/op
Client.getUser:getUser·p0.9999        sample          9.074           ms/op
Client.getUser:getUser·p1.00          sample          9.257           ms/op
Client.listUser                       sample   3910   8.237 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          1.473           ms/op
Client.listUser:listUser·p0.50        sample          7.823           ms/op
Client.listUser:listUser·p0.90        sample         10.943           ms/op
Client.listUser:listUser·p0.95        sample         12.468           ms/op
Client.listUser:listUser·p0.99        sample         17.658           ms/op
Client.listUser:listUser·p0.999       sample         23.449           ms/op
Client.listUser:listUser·p0.9999      sample         25.297           ms/op
Client.listUser:listUser·p1.00        sample         25.297           ms/op
