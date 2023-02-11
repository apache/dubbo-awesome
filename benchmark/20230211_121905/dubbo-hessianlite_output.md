# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.359 ops/ms
Iteration   1: 2.823 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.823 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.265 ops/ms
Iteration   1: 9.652 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.652 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.271 ops/ms
Iteration   1: 5.880 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.880 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.830 ops/ms
Iteration   1: 1.549 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.549 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 14.202 ±(99.9%) 0.194 ms/op
Iteration   1: 6.637 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.637 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.136 ±(99.9%) 0.102 ms/op
Iteration   1: 4.021 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.021 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.701 ±(99.9%) 0.091 ms/op
Iteration   1: 4.456 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.456 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 26.585 ±(99.9%) 0.341 ms/op
Iteration   1: 18.044 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.044 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.150 ±(99.9%) 0.370 ms/op
Iteration   1: 5.606 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   2.613 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   15.221 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 19.202 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5741
  mean =      5.606 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 13 
    [ 3.750,  5.000) = 401 
    [ 5.000,  6.250) = 4985 
    [ 6.250,  7.500) = 150 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.613 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.373 ms/op
     p(99.0000) =     15.221 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.401 ±(99.9%) 0.220 ms/op
Iteration   1: 3.598 ±(99.9%) 0.061 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   6.783 ms/op
                 existUser·p0.99:   12.370 ms/op
                 existUser·p0.999:  14.074 ms/op
                 existUser·p0.9999: 14.434 ms/op
                 existUser·p1.00:   14.434 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9001
  mean =      3.598 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 1765 
    [ 2.500,  3.750) = 3588 
    [ 3.750,  5.000) = 2944 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 136 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =     12.370 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     14.434 ms/op
     p(99.9990) =     14.434 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.301 ±(99.9%) 0.347 ms/op
Iteration   1: 4.458 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   8.554 ms/op
                 getUser·p0.999:  14.374 ms/op
                 getUser·p0.9999: 15.761 ms/op
                 getUser·p1.00:   15.761 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7287
  mean =      4.458 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 136 
    [ 2.500,  3.750) = 827 
    [ 3.750,  5.000) = 5422 
    [ 5.000,  6.250) = 603 
    [ 6.250,  7.500) = 190 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.554 ms/op
     p(99.9000) =     14.374 ms/op
     p(99.9900) =     15.761 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.684 ±(99.9%) 0.754 ms/op
Iteration   1: 16.494 ±(99.9%) 0.375 ms/op
                 listUser·p0.00:   5.349 ms/op
                 listUser·p0.50:   17.695 ms/op
                 listUser·p0.90:   20.873 ms/op
                 listUser·p0.95:   24.379 ms/op
                 listUser·p0.99:   32.405 ms/op
                 listUser·p0.999:  37.630 ms/op
                 listUser·p0.9999: 38.011 ms/op
                 listUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1967
  mean =     16.494 ±(99.9%) 0.375 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 21 
    [ 7.500, 10.000) = 200 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 699 
    [20.000, 22.500) = 168 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      5.349 ms/op
     p(50.0000) =     17.695 ms/op
     p(90.0000) =     20.873 ms/op
     p(95.0000) =     24.379 ms/op
     p(99.0000) =     32.405 ms/op
     p(99.9000) =     37.630 ms/op
     p(99.9900) =     38.011 ms/op
     p(99.9990) =     38.011 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.823          ops/ms
Client.existUser                       thrpt         9.652          ops/ms
Client.getUser                         thrpt         5.880          ops/ms
Client.listUser                        thrpt         1.549          ops/ms
Client.createUser                       avgt         6.637           ms/op
Client.existUser                        avgt         4.021           ms/op
Client.getUser                          avgt         4.456           ms/op
Client.listUser                         avgt        18.044           ms/op
Client.createUser                     sample  5741   5.606 ± 0.068   ms/op
Client.createUser:createUser·p0.00    sample         2.613           ms/op
Client.createUser:createUser·p0.50    sample         5.308           ms/op
Client.createUser:createUser·p0.90    sample         5.849           ms/op
Client.createUser:createUser·p0.95    sample         6.373           ms/op
Client.createUser:createUser·p0.99    sample        15.221           ms/op
Client.createUser:createUser·p0.999   sample        19.137           ms/op
Client.createUser:createUser·p0.9999  sample        19.202           ms/op
Client.createUser:createUser·p1.00    sample        19.202           ms/op
Client.existUser                      sample  9001   3.598 ± 0.061   ms/op
Client.existUser:existUser·p0.00      sample         0.601           ms/op
Client.existUser:existUser·p0.50      sample         3.592           ms/op
Client.existUser:existUser·p0.90      sample         4.227           ms/op
Client.existUser:existUser·p0.95      sample         6.783           ms/op
Client.existUser:existUser·p0.99      sample        12.370           ms/op
Client.existUser:existUser·p0.999     sample        14.074           ms/op
Client.existUser:existUser·p0.9999    sample        14.434           ms/op
Client.existUser:existUser·p1.00      sample        14.434           ms/op
Client.getUser                        sample  7287   4.458 ± 0.042   ms/op
Client.getUser:getUser·p0.00          sample         0.818           ms/op
Client.getUser:getUser·p0.50          sample         4.383           ms/op
Client.getUser:getUser·p0.90          sample         5.112           ms/op
Client.getUser:getUser·p0.95          sample         5.792           ms/op
Client.getUser:getUser·p0.99          sample         8.554           ms/op
Client.getUser:getUser·p0.999         sample        14.374           ms/op
Client.getUser:getUser·p0.9999        sample        15.761           ms/op
Client.getUser:getUser·p1.00          sample        15.761           ms/op
Client.listUser                       sample  1967  16.494 ± 0.375   ms/op
Client.listUser:listUser·p0.00        sample         5.349           ms/op
Client.listUser:listUser·p0.50        sample        17.695           ms/op
Client.listUser:listUser·p0.90        sample        20.873           ms/op
Client.listUser:listUser·p0.95        sample        24.379           ms/op
Client.listUser:listUser·p0.99        sample        32.405           ms/op
Client.listUser:listUser·p0.999       sample        37.630           ms/op
Client.listUser:listUser·p0.9999      sample        38.011           ms/op
Client.listUser:listUser·p1.00        sample        38.011           ms/op
