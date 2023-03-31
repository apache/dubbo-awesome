# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.561 ops/ms
# Warmup Iteration   2: 6.600 ops/ms
# Warmup Iteration   3: 7.719 ops/ms
Iteration   1: 8.246 ops/ms
Iteration   2: 8.737 ops/ms
Iteration   3: 8.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.597 ±(99.9%) 5.579 ops/ms [Average]
  (min, avg, max) = (8.246, 8.597, 8.807), stdev = 0.306
  CI (99.9%): [3.018, 14.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.423 ops/ms
# Warmup Iteration   2: 7.946 ops/ms
# Warmup Iteration   3: 8.688 ops/ms
Iteration   1: 8.666 ops/ms
Iteration   2: 8.574 ops/ms
Iteration   3: 9.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.872 ±(99.9%) 8.016 ops/ms [Average]
  (min, avg, max) = (8.574, 8.872, 9.377), stdev = 0.439
  CI (99.9%): [0.857, 16.888] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.375 ops/ms
# Warmup Iteration   2: 7.528 ops/ms
# Warmup Iteration   3: 8.151 ops/ms
Iteration   1: 8.225 ops/ms
Iteration   2: 8.277 ops/ms
Iteration   3: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.294 ±(99.9%) 1.440 ops/ms [Average]
  (min, avg, max) = (8.225, 8.294, 8.380), stdev = 0.079
  CI (99.9%): [6.854, 9.734] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.548 ops/ms
# Warmup Iteration   2: 5.629 ops/ms
# Warmup Iteration   3: 6.229 ops/ms
Iteration   1: 6.435 ops/ms
Iteration   2: 6.480 ops/ms
Iteration   3: 6.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.349 ±(99.9%) 3.452 ops/ms [Average]
  (min, avg, max) = (6.132, 6.349, 6.480), stdev = 0.189
  CI (99.9%): [2.897, 9.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.865 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.762 ±(99.9%) 0.003 ms/op
Iteration   2: 3.810 ±(99.9%) 0.003 ms/op
Iteration   3: 3.887 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.820 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (3.762, 3.820, 3.887), stdev = 0.063
  CI (99.9%): [2.672, 4.968] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.404 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.005 ms/op
Iteration   1: 3.516 ±(99.9%) 0.002 ms/op
Iteration   2: 3.580 ±(99.9%) 0.003 ms/op
Iteration   3: 3.607 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.568 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (3.516, 3.568, 3.607), stdev = 0.047
  CI (99.9%): [2.716, 4.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.043 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.004 ms/op
Iteration   1: 3.868 ±(99.9%) 0.003 ms/op
Iteration   2: 3.828 ±(99.9%) 0.006 ms/op
Iteration   3: 3.862 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.853 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (3.828, 3.853, 3.868), stdev = 0.022
  CI (99.9%): [3.458, 4.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.068 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.247 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.958 ±(99.9%) 0.019 ms/op
Iteration   1: 5.115 ±(99.9%) 0.021 ms/op
Iteration   2: 4.955 ±(99.9%) 0.016 ms/op
Iteration   3: 4.971 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.014 ±(99.9%) 1.613 ms/op [Average]
  (min, avg, max) = (4.955, 5.014, 5.115), stdev = 0.088
  CI (99.9%): [3.401, 6.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.907 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.009 ms/op
Iteration   1: 3.871 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 18.866 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   2: 3.930 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  11.801 ms/op
                 createUser·p0.9999: 17.133 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   3: 3.774 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  10.095 ms/op
                 createUser·p0.9999: 18.367 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248877
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 5325 
    [ 2.500,  3.750) = 116176 
    [ 3.750,  5.000) = 111136 
    [ 5.000,  6.250) = 13157 
    [ 6.250,  7.500) = 1860 
    [ 7.500,  8.750) = 664 
    [ 8.750, 10.000) = 206 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     10.211 ms/op
     p(99.9900) =     18.354 ms/op
     p(99.9990) =     19.285 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.323 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.010 ms/op
Iteration   1: 3.626 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  11.443 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   2: 3.600 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 19.667 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   3: 3.489 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  10.317 ms/op
                 existUser·p0.9999: 20.895 ms/op
                 existUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268783
  mean =      3.571 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9899 
    [ 2.500,  5.000) = 250368 
    [ 5.000,  7.500) = 7542 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     20.124 ms/op
     p(99.9990) =     21.144 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.717 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.009 ms/op
Iteration   1: 3.871 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 19.873 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   2: 3.897 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  11.578 ms/op
                 getUser·p0.9999: 17.189 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 3.862 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  10.453 ms/op
                 getUser·p0.9999: 19.969 ms/op
                 getUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247719
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5364 
    [ 2.500,  5.000) = 225980 
    [ 5.000,  7.500) = 15081 
    [ 7.500, 10.000) = 925 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     20.383 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.947 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.263 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.991 ±(99.9%) 0.015 ms/op
Iteration   1: 4.946 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.382 ms/op
                 listUser·p0.95:   7.274 ms/op
                 listUser·p0.99:   9.437 ms/op
                 listUser·p0.999:  16.414 ms/op
                 listUser·p0.9999: 19.125 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 4.890 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  15.443 ms/op
                 listUser·p0.9999: 20.180 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 4.994 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.644 ms/op
                 listUser·p0.95:   7.512 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  24.120 ms/op
                 listUser·p0.9999: 26.712 ms/op
                 listUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194149
  mean =      4.943 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 667 
    [ 2.500,  5.000) = 122261 
    [ 5.000,  7.500) = 62862 
    [ 7.500, 10.000) = 7144 
    [10.000, 12.500) = 773 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.324 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     16.838 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     30.225 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.597 ± 5.579  ops/ms
ClientGrpc.existUser                       thrpt       3   8.872 ± 8.016  ops/ms
ClientGrpc.getUser                         thrpt       3   8.294 ± 1.440  ops/ms
ClientGrpc.listUser                        thrpt       3   6.349 ± 3.452  ops/ms
ClientGrpc.createUser                       avgt       3   3.820 ± 1.148   ms/op
ClientGrpc.existUser                        avgt       3   3.568 ± 0.851   ms/op
ClientGrpc.getUser                          avgt       3   3.853 ± 0.395   ms/op
ClientGrpc.listUser                         avgt       3   5.014 ± 1.613   ms/op
ClientGrpc.createUser                     sample  248877   3.857 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.810           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.153           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.463           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.211           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.354           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.431           ms/op
ClientGrpc.existUser                      sample  268783   3.571 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.823           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.988           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.551           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.124           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.053           ms/op
ClientGrpc.getUser                        sample  247719   3.877 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.973           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.169           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.521           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.092           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.857           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.480           ms/op
ClientGrpc.listUser                       sample  194149   4.943 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.033           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.480           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.404           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.838           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.018           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.966           ms/op
