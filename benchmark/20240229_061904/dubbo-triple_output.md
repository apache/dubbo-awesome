# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.554 ops/ms
# Warmup Iteration   2: 12.149 ops/ms
# Warmup Iteration   3: 12.591 ops/ms
Iteration   1: 12.706 ops/ms
Iteration   2: 12.865 ops/ms
Iteration   3: 12.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.802 ±(99.9%) 1.551 ops/ms [Average]
  (min, avg, max) = (12.706, 12.802, 12.865), stdev = 0.085
  CI (99.9%): [11.251, 14.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ops/ms
# Warmup Iteration   2: 13.180 ops/ms
# Warmup Iteration   3: 13.337 ops/ms
Iteration   1: 13.324 ops/ms
Iteration   2: 13.209 ops/ms
Iteration   3: 13.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.242 ±(99.9%) 1.299 ops/ms [Average]
  (min, avg, max) = (13.194, 13.242, 13.324), stdev = 0.071
  CI (99.9%): [11.943, 14.542] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.916 ops/ms
# Warmup Iteration   2: 12.796 ops/ms
# Warmup Iteration   3: 13.033 ops/ms
Iteration   1: 13.101 ops/ms
Iteration   2: 13.282 ops/ms
Iteration   3: 13.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.155 ±(99.9%) 2.015 ops/ms [Average]
  (min, avg, max) = (13.081, 13.155, 13.282), stdev = 0.110
  CI (99.9%): [11.140, 15.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.877 ops/ms
# Warmup Iteration   2: 10.458 ops/ms
# Warmup Iteration   3: 10.739 ops/ms
Iteration   1: 10.823 ops/ms
Iteration   2: 10.860 ops/ms
Iteration   3: 10.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.816 ±(99.9%) 0.878 ops/ms [Average]
  (min, avg, max) = (10.765, 10.816, 10.860), stdev = 0.048
  CI (99.9%): [9.938, 11.694] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.301 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.003 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.484 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.479, 2.484, 2.495), stdev = 0.009
  CI (99.9%): [2.318, 2.650] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.681 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.004 ms/op
Iteration   1: 2.359 ±(99.9%) 0.004 ms/op
Iteration   2: 2.357 ±(99.9%) 0.004 ms/op
Iteration   3: 2.366 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.361 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.357, 2.361, 2.366), stdev = 0.005
  CI (99.9%): [2.275, 2.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.831 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.465 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (2.459, 2.465, 2.471), stdev = 0.006
  CI (99.9%): [2.353, 2.576] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.573 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.005 ms/op
Iteration   1: 2.973 ±(99.9%) 0.005 ms/op
Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
Iteration   3: 2.959 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.958 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.941, 2.958, 2.973), stdev = 0.016
  CI (99.9%): [2.672, 3.243] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  11.068 ms/op
                 createUser·p0.9999: 12.960 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  6.735 ms/op
                 createUser·p0.9999: 12.207 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  8.374 ms/op
                 createUser·p0.9999: 11.308 ms/op
                 createUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386249
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 186296 
    [ 2.500,  3.750) = 195462 
    [ 3.750,  5.000) = 3536 
    [ 5.000,  6.250) = 429 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 143 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.356 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     13.306 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.402 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.396 ±(99.9%) 0.005 ms/op
Iteration   1: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  5.542 ms/op
                 existUser·p0.9999: 13.451 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  5.980 ms/op
                 existUser·p0.9999: 12.463 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.880 ms/op
                 existUser·p0.9999: 11.447 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399915
  mean =      2.398 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 205509 
    [ 2.500,  3.750) = 191750 
    [ 3.750,  5.000) = 1982 
    [ 5.000,  6.250) = 209 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      6.520 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  6.548 ms/op
                 getUser·p0.9999: 13.632 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.898 ms/op
                 getUser·p0.9999: 12.419 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  5.382 ms/op
                 getUser·p0.9999: 11.028 ms/op
                 getUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386750
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 192340 
    [ 2.500,  3.750) = 189256 
    [ 3.750,  5.000) = 4033 
    [ 5.000,  6.250) = 646 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      6.111 ms/op
     p(99.9900) =     13.101 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.739 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.009 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.351 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   2: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.438 ms/op
                 listUser·p0.9999: 11.033 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 12.132 ms/op
                 listUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316645
  mean =      3.029 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 88415 
    [ 2.500,  3.750) = 186828 
    [ 3.750,  5.000) = 33302 
    [ 5.000,  6.250) = 6642 
    [ 6.250,  7.500) = 658 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.780 ms/op
     p(99.9990) =     12.558 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.802 ± 1.551  ops/ms
ClientPb.existUser                       thrpt       3  13.242 ± 1.299  ops/ms
ClientPb.getUser                         thrpt       3  13.155 ± 2.015  ops/ms
ClientPb.listUser                        thrpt       3  10.816 ± 0.878  ops/ms
ClientPb.createUser                       avgt       3   2.484 ± 0.166   ms/op
ClientPb.existUser                        avgt       3   2.361 ± 0.086   ms/op
ClientPb.getUser                          avgt       3   2.465 ± 0.112   ms/op
ClientPb.listUser                         avgt       3   2.958 ± 0.285   ms/op
ClientPb.createUser                     sample  386249   2.483 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.805           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.356           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.747           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.353           ms/op
ClientPb.existUser                      sample  399915   2.398 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.520           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.796           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.730           ms/op
ClientPb.getUser                        sample  386750   2.480 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.592           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.111           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.101           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.812           ms/op
ClientPb.listUser                       sample  316645   3.029 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.780           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.911           ms/op
