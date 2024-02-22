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
# Warmup Iteration   1: 2.112 ops/ms
Iteration   1: 5.770 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.770 ops/ms


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
# Warmup Iteration   1: 5.592 ops/ms
Iteration   1: 12.013 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.013 ops/ms


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
# Warmup Iteration   1: 3.688 ops/ms
Iteration   1: 8.125 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.125 ops/ms


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
# Warmup Iteration   1: 2.189 ops/ms
Iteration   1: 3.988 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.988 ops/ms


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
# Warmup Iteration   1: 5.476 ±(99.9%) 0.079 ms/op
Iteration   1: 3.331 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.331 ms/op


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
# Warmup Iteration   1: 3.623 ±(99.9%) 0.038 ms/op
Iteration   1: 2.059 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.059 ms/op


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
# Warmup Iteration   1: 5.263 ±(99.9%) 0.071 ms/op
Iteration   1: 3.167 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.167 ms/op


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
# Warmup Iteration   1: 12.883 ±(99.9%) 0.247 ms/op
Iteration   1: 8.571 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.571 ms/op


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
# Warmup Iteration   1: 6.038 ±(99.9%) 0.157 ms/op
Iteration   1: 3.225 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   8.123 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9981
  mean =      3.225 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1065 
    [ 2.500,  3.750) = 7504 
    [ 3.750,  5.000) = 1150 
    [ 5.000,  6.250) = 155 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      8.123 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


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
# Warmup Iteration   1: 3.239 ±(99.9%) 0.077 ms/op
Iteration   1: 1.890 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   1.823 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   3.919 ms/op
                 existUser·p0.999:  6.227 ms/op
                 existUser·p0.9999: 6.667 ms/op
                 existUser·p1.00:   6.701 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16913
  mean =      1.890 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 8 
    [1.000, 1.500) = 3696 
    [1.500, 2.000) = 7222 
    [2.000, 2.500) = 4553 
    [2.500, 3.000) = 1070 
    [3.000, 3.500) = 182 
    [3.500, 4.000) = 21 
    [4.000, 4.500) = 62 
    [4.500, 5.000) = 14 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 42 
    [6.000, 6.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.919 ms/op
     p(99.9000) =      6.227 ms/op
     p(99.9900) =      6.667 ms/op
     p(99.9990) =      6.701 ms/op
     p(99.9999) =      6.701 ms/op
    p(100.0000) =      6.701 ms/op


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
# Warmup Iteration   1: 4.708 ±(99.9%) 0.111 ms/op
Iteration   1: 3.017 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.461 ms/op
                 getUser·p0.999:  8.057 ms/op
                 getUser·p0.9999: 9.148 ms/op
                 getUser·p1.00:   9.175 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10621
  mean =      3.017 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 7 
    [ 1.000,  2.000) = 526 
    [ 2.000,  3.000) = 4781 
    [ 3.000,  4.000) = 4402 
    [ 4.000,  5.000) = 747 
    [ 5.000,  6.000) = 86 
    [ 6.000,  7.000) = 31 
    [ 7.000,  8.000) = 29 
    [ 8.000,  9.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.461 ms/op
     p(99.9000) =      8.057 ms/op
     p(99.9900) =      9.148 ms/op
     p(99.9990) =      9.175 ms/op
     p(99.9999) =      9.175 ms/op
    p(100.0000) =      9.175 ms/op


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
# Warmup Iteration   1: 13.053 ±(99.9%) 0.444 ms/op
Iteration   1: 8.029 ±(99.9%) 0.093 ms/op
                 listUser·p0.00:   2.810 ms/op
                 listUser·p0.50:   7.815 ms/op
                 listUser·p0.90:   10.355 ms/op
                 listUser·p0.95:   11.234 ms/op
                 listUser·p0.99:   13.436 ms/op
                 listUser·p0.999:  16.440 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4046
  mean =      8.029 ±(99.9%) 0.093 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 95 
    [ 5.000,  7.500) = 1577 
    [ 7.500, 10.000) = 1858 
    [10.000, 12.500) = 442 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.810 ms/op
     p(50.0000) =      7.815 ms/op
     p(90.0000) =     10.355 ms/op
     p(95.0000) =     11.234 ms/op
     p(99.0000) =     13.436 ms/op
     p(99.9000) =     16.440 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.770          ops/ms
Client.existUser                       thrpt         12.013          ops/ms
Client.getUser                         thrpt          8.125          ops/ms
Client.listUser                        thrpt          3.988          ops/ms
Client.createUser                       avgt          3.331           ms/op
Client.existUser                        avgt          2.059           ms/op
Client.getUser                          avgt          3.167           ms/op
Client.listUser                         avgt          8.571           ms/op
Client.createUser                     sample   9981   3.225 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.282           ms/op
Client.createUser:createUser·p0.50    sample          3.035           ms/op
Client.createUser:createUser·p0.90    sample          3.957           ms/op
Client.createUser:createUser·p0.95    sample          4.309           ms/op
Client.createUser:createUser·p0.99    sample          8.123           ms/op
Client.createUser:createUser·p0.999   sample         11.878           ms/op
Client.createUser:createUser·p0.9999  sample         13.468           ms/op
Client.createUser:createUser·p1.00    sample         13.468           ms/op
Client.existUser                      sample  16913   1.890 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.967           ms/op
Client.existUser:existUser·p0.50      sample          1.823           ms/op
Client.existUser:existUser·p0.90      sample          2.445           ms/op
Client.existUser:existUser·p0.95      sample          2.687           ms/op
Client.existUser:existUser·p0.99      sample          3.919           ms/op
Client.existUser:existUser·p0.999     sample          6.227           ms/op
Client.existUser:existUser·p0.9999    sample          6.667           ms/op
Client.existUser:existUser·p1.00      sample          6.701           ms/op
Client.getUser                        sample  10621   3.017 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.845           ms/op
Client.getUser:getUser·p0.50          sample          2.998           ms/op
Client.getUser:getUser·p0.90          sample          3.908           ms/op
Client.getUser:getUser·p0.95          sample          4.227           ms/op
Client.getUser:getUser·p0.99          sample          5.461           ms/op
Client.getUser:getUser·p0.999         sample          8.057           ms/op
Client.getUser:getUser·p0.9999        sample          9.148           ms/op
Client.getUser:getUser·p1.00          sample          9.175           ms/op
Client.listUser                       sample   4046   8.029 ± 0.093   ms/op
Client.listUser:listUser·p0.00        sample          2.810           ms/op
Client.listUser:listUser·p0.50        sample          7.815           ms/op
Client.listUser:listUser·p0.90        sample         10.355           ms/op
Client.listUser:listUser·p0.95        sample         11.234           ms/op
Client.listUser:listUser·p0.99        sample         13.436           ms/op
Client.listUser:listUser·p0.999       sample         16.440           ms/op
Client.listUser:listUser·p0.9999      sample         21.496           ms/op
Client.listUser:listUser·p1.00        sample         21.496           ms/op
