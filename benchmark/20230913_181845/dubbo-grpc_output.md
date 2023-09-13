# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.688 ops/ms
# Warmup Iteration   2: 9.261 ops/ms
# Warmup Iteration   3: 10.251 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 10.644 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.742 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (10.644, 10.742, 10.839), stdev = 0.097
  CI (99.9%): [8.966, 12.517] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.150 ops/ms
# Warmup Iteration   2: 10.746 ops/ms
# Warmup Iteration   3: 11.174 ops/ms
Iteration   1: 11.348 ops/ms
Iteration   2: 11.351 ops/ms
Iteration   3: 11.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.323 ±(99.9%) 0.832 ops/ms [Average]
  (min, avg, max) = (11.270, 11.323, 11.351), stdev = 0.046
  CI (99.9%): [10.491, 12.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.602 ops/ms
# Warmup Iteration   2: 10.163 ops/ms
# Warmup Iteration   3: 10.711 ops/ms
Iteration   1: 10.814 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.754 ±(99.9%) 1.519 ops/ms [Average]
  (min, avg, max) = (10.659, 10.754, 10.814), stdev = 0.083
  CI (99.9%): [9.235, 12.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.635 ops/ms
# Warmup Iteration   2: 7.799 ops/ms
# Warmup Iteration   3: 8.221 ops/ms
Iteration   1: 8.356 ops/ms
Iteration   2: 8.204 ops/ms
Iteration   3: 8.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.282 ±(99.9%) 1.382 ops/ms [Average]
  (min, avg, max) = (8.204, 8.282, 8.356), stdev = 0.076
  CI (99.9%): [6.900, 9.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.007 ms/op
Iteration   1: 2.929 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 2.982 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.957 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (2.929, 2.957, 2.982), stdev = 0.026
  CI (99.9%): [2.476, 3.437] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.592 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.941 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.004 ms/op
Iteration   1: 2.898 ±(99.9%) 0.004 ms/op
Iteration   2: 2.785 ±(99.9%) 0.004 ms/op
Iteration   3: 2.902 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.862 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (2.785, 2.862, 2.902), stdev = 0.066
  CI (99.9%): [1.650, 4.073] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.929 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 3.002 ±(99.9%) 0.003 ms/op
Iteration   2: 2.928 ±(99.9%) 0.002 ms/op
Iteration   3: 2.949 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.960 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (2.928, 2.960, 3.002), stdev = 0.038
  CI (99.9%): [2.268, 3.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.242 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.038 ms/op
Iteration   1: 3.833 ±(99.9%) 0.034 ms/op
Iteration   2: 3.815 ±(99.9%) 0.010 ms/op
Iteration   3: 3.755 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.801 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.755, 3.801, 3.833), stdev = 0.041
  CI (99.9%): [3.051, 4.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.992 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.649 ms/op
                 createUser·p0.999:  8.889 ms/op
                 createUser·p0.9999: 13.297 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.559 ms/op
                 createUser·p0.9999: 13.411 ms/op
                 createUser·p1.00:   13.763 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  12.354 ms/op
                 createUser·p0.9999: 20.429 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317352
  mean =      3.029 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31615 
    [ 2.500,  5.000) = 283608 
    [ 5.000,  7.500) = 1404 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     19.776 ms/op
     p(99.9990) =     20.638 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.618 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.813 ±(99.9%) 0.007 ms/op
Iteration   1: 2.883 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  7.488 ms/op
                 existUser·p0.9999: 15.297 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   2: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.961 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 2.832 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  8.258 ms/op
                 existUser·p0.9999: 25.016 ms/op
                 existUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333992
  mean =      2.873 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52477 
    [ 2.500,  5.000) = 279797 
    [ 5.000,  7.500) = 1264 
    [ 7.500, 10.000) = 261 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      7.840 ms/op
     p(99.9900) =     22.715 ms/op
     p(99.9990) =     25.406 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.854 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.175 ms/op
                 getUser·p0.9999: 18.035 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.059 ms/op
                 getUser·p0.9999: 18.594 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.259 ms/op
                 getUser·p0.9999: 14.831 ms/op
                 getUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323805
  mean =      2.963 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1395 
    [ 1.250,  2.500) = 29340 
    [ 2.500,  3.750) = 279871 
    [ 3.750,  5.000) = 11667 
    [ 5.000,  6.250) = 763 
    [ 6.250,  7.500) = 397 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.800 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     19.096 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.317 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.010 ms/op
Iteration   1: 3.862 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.386 ms/op
                 listUser·p0.9999: 17.128 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   2: 3.792 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 16.428 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 3.890 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.989 ms/op
                 listUser·p0.999:  16.566 ms/op
                 listUser·p0.9999: 24.084 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249533
  mean =      3.848 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4400 
    [ 2.500,  5.000) = 225565 
    [ 5.000,  7.500) = 18218 
    [ 7.500, 10.000) = 897 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     13.967 ms/op
     p(99.9900) =     23.693 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.742 ± 1.775  ops/ms
ClientGrpc.existUser                       thrpt       3  11.323 ± 0.832  ops/ms
ClientGrpc.getUser                         thrpt       3  10.754 ± 1.519  ops/ms
ClientGrpc.listUser                        thrpt       3   8.282 ± 1.382  ops/ms
ClientGrpc.createUser                       avgt       3   2.957 ± 0.481   ms/op
ClientGrpc.existUser                        avgt       3   2.862 ± 1.212   ms/op
ClientGrpc.getUser                          avgt       3   2.960 ± 0.692   ms/op
ClientGrpc.listUser                         avgt       3   3.801 ± 0.750   ms/op
ClientGrpc.createUser                     sample  317352   3.029 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.669           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.011           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.776           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  333992   2.873 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.484           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.840           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.715           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.526           ms/op
ClientGrpc.getUser                        sample  323805   2.963 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.580           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.800           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.022           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.169           ms/op
ClientGrpc.listUser                       sample  249533   3.848 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.913           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.707           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.967           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.693           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.445           ms/op
