# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ops/ms
# Warmup Iteration   2: 9.511 ops/ms
# Warmup Iteration   3: 10.683 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.388 ops/ms
Iteration   3: 10.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.409 ±(99.9%) 2.821 ops/ms [Average]
  (min, avg, max) = (10.265, 10.409, 10.572), stdev = 0.155
  CI (99.9%): [7.588, 13.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.020 ops/ms
# Warmup Iteration   2: 10.664 ops/ms
# Warmup Iteration   3: 10.622 ops/ms
Iteration   1: 10.857 ops/ms
Iteration   2: 10.668 ops/ms
Iteration   3: 10.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.810 ±(99.9%) 2.280 ops/ms [Average]
  (min, avg, max) = (10.668, 10.810, 10.904), stdev = 0.125
  CI (99.9%): [8.529, 13.090] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.049 ops/ms
# Warmup Iteration   2: 10.274 ops/ms
# Warmup Iteration   3: 10.502 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.503 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (10.375, 10.503, 10.648), stdev = 0.137
  CI (99.9%): [7.998, 13.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.517 ops/ms
# Warmup Iteration   2: 7.755 ops/ms
# Warmup Iteration   3: 8.066 ops/ms
Iteration   1: 7.705 ops/ms
Iteration   2: 7.904 ops/ms
Iteration   3: 7.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.839 ±(99.9%) 2.119 ops/ms [Average]
  (min, avg, max) = (7.705, 7.839, 7.909), stdev = 0.116
  CI (99.9%): [5.720, 9.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.002 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.002 ms/op
Iteration   1: 3.045 ±(99.9%) 0.002 ms/op
Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
Iteration   3: 2.991 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.035 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (2.991, 3.035, 3.069), stdev = 0.040
  CI (99.9%): [2.307, 3.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.004 ms/op
Iteration   1: 2.823 ±(99.9%) 0.002 ms/op
Iteration   2: 2.940 ±(99.9%) 0.003 ms/op
Iteration   3: 2.961 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 1.361 ms/op [Average]
  (min, avg, max) = (2.823, 2.908, 2.961), stdev = 0.075
  CI (99.9%): [1.547, 4.268] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.807 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.096 ±(99.9%) 0.002 ms/op
Iteration   2: 3.167 ±(99.9%) 0.002 ms/op
Iteration   3: 3.101 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.121 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (3.096, 3.121, 3.167), stdev = 0.039
  CI (99.9%): [2.405, 3.837] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.843 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.010 ms/op
Iteration   1: 3.965 ±(99.9%) 0.009 ms/op
Iteration   2: 3.942 ±(99.9%) 0.034 ms/op
Iteration   3: 3.969 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.959 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (3.942, 3.959, 3.969), stdev = 0.015
  CI (99.9%): [3.688, 4.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.363 ms/op
                 createUser·p0.9999: 15.373 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.503 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  10.150 ms/op
                 createUser·p0.9999: 17.105 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   3: 3.178 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.095 ms/op
                 createUser·p0.9999: 17.857 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306983
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1043 
    [ 1.250,  2.500) = 23797 
    [ 2.500,  3.750) = 247451 
    [ 3.750,  5.000) = 33709 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     18.509 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.646 ms/op
                 existUser·p0.9999: 11.240 ms/op
                 existUser·p1.00:   11.649 ms/op

Iteration   2: 2.849 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  5.349 ms/op
                 existUser·p0.9999: 13.673 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.989 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.178 ms/op
                 existUser·p0.9999: 20.556 ms/op
                 existUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328961
  mean =      2.918 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51327 
    [ 2.500,  5.000) = 276871 
    [ 5.000,  7.500) = 572 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      6.276 ms/op
     p(99.9900) =     16.031 ms/op
     p(99.9990) =     20.821 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  7.351 ms/op
                 getUser·p0.9999: 11.256 ms/op
                 getUser·p1.00:   11.551 ms/op

Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.125 ms/op
                 getUser·p0.9999: 12.529 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  5.413 ms/op
                 getUser·p0.9999: 26.653 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315301
  mean =      3.044 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25717 
    [ 2.500,  5.000) = 288958 
    [ 5.000,  7.500) = 370 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.748 ms/op
     p(99.9900) =     25.935 ms/op
     p(99.9990) =     26.865 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.071 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.012 ms/op
Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  11.788 ms/op
                 listUser·p0.9999: 15.842 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   2: 3.971 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 23.817 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 4.088 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 24.958 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239858
  mean =      4.002 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4598 
    [ 2.500,  5.000) = 200849 
    [ 5.000,  7.500) = 33279 
    [ 7.500, 10.000) = 727 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.657 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     26.189 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.409 ± 2.821  ops/ms
ClientGrpc.existUser                       thrpt       3  10.810 ± 2.280  ops/ms
ClientGrpc.getUser                         thrpt       3  10.503 ± 2.506  ops/ms
ClientGrpc.listUser                        thrpt       3   7.839 ± 2.119  ops/ms
ClientGrpc.createUser                       avgt       3   3.035 ± 0.729   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 1.361   ms/op
ClientGrpc.getUser                          avgt       3   3.121 ± 0.716   ms/op
ClientGrpc.listUser                         avgt       3   3.959 ± 0.271   ms/op
ClientGrpc.createUser                     sample  306983   3.125 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.503           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.965           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.487           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.072           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.645           ms/op
ClientGrpc.existUser                      sample  328961   2.918 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.519           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.276           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.031           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.873           ms/op
ClientGrpc.getUser                        sample  315301   3.044 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.748           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.935           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.935           ms/op
ClientGrpc.listUser                       sample  239858   4.002 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.845           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.657           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.888           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.280           ms/op
