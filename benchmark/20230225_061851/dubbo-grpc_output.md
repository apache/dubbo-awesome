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
# Warmup Iteration   1: 4.086 ops/ms
# Warmup Iteration   2: 8.231 ops/ms
# Warmup Iteration   3: 9.948 ops/ms
Iteration   1: 10.213 ops/ms
Iteration   2: 10.028 ops/ms
Iteration   3: 10.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.114 ±(99.9%) 1.694 ops/ms [Average]
  (min, avg, max) = (10.028, 10.114, 10.213), stdev = 0.093
  CI (99.9%): [8.420, 11.808] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.397 ops/ms
# Warmup Iteration   2: 10.266 ops/ms
# Warmup Iteration   3: 10.518 ops/ms
Iteration   1: 10.615 ops/ms
Iteration   2: 10.607 ops/ms
Iteration   3: 10.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.571 ±(99.9%) 1.255 ops/ms [Average]
  (min, avg, max) = (10.492, 10.571, 10.615), stdev = 0.069
  CI (99.9%): [9.316, 11.827] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.739 ops/ms
# Warmup Iteration   2: 10.095 ops/ms
# Warmup Iteration   3: 10.263 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.450 ops/ms
Iteration   3: 10.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.413 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (10.302, 10.413, 10.486), stdev = 0.097
  CI (99.9%): [8.638, 12.188] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.799 ops/ms
# Warmup Iteration   2: 7.411 ops/ms
# Warmup Iteration   3: 7.672 ops/ms
Iteration   1: 7.990 ops/ms
Iteration   2: 7.771 ops/ms
Iteration   3: 7.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.881 ±(99.9%) 2.002 ops/ms [Average]
  (min, avg, max) = (7.771, 7.881, 7.990), stdev = 0.110
  CI (99.9%): [5.878, 9.883] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.324 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.003 ms/op
Iteration   1: 3.214 ±(99.9%) 0.002 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.173 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (3.135, 3.173, 3.214), stdev = 0.040
  CI (99.9%): [2.448, 3.899] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.987 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.002 ms/op
Iteration   1: 3.043 ±(99.9%) 0.002 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.031 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (2.997, 3.031, 3.054), stdev = 0.030
  CI (99.9%): [2.477, 3.585] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.403 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.005 ms/op
Iteration   1: 3.038 ±(99.9%) 0.003 ms/op
Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
Iteration   3: 3.166 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.087 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.038, 3.087, 3.166), stdev = 0.069
  CI (99.9%): [1.830, 4.344] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.451 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.024 ms/op
Iteration   1: 4.047 ±(99.9%) 0.024 ms/op
Iteration   2: 4.022 ±(99.9%) 0.010 ms/op
Iteration   3: 4.065 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.045 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (4.022, 4.045, 4.065), stdev = 0.021
  CI (99.9%): [3.653, 4.436] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.462 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.007 ms/op
Iteration   1: 3.239 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.950 ms/op
                 createUser·p0.9999: 14.922 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.294 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 23.167 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.594 ms/op
                 createUser·p0.9999: 20.341 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302545
  mean =      3.173 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25022 
    [ 2.500,  5.000) = 276261 
    [ 5.000,  7.500) = 892 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     22.765 ms/op
     p(99.9990) =     23.362 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.187 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.456 ms/op
                 existUser·p0.9999: 13.497 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  11.813 ms/op
                 existUser·p0.9999: 18.907 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.551 ms/op
                 existUser·p0.9999: 18.317 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316910
  mean =      3.029 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43373 
    [ 2.500,  5.000) = 272415 
    [ 5.000,  7.500) = 799 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.737 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.007 ms/op
Iteration   1: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.290 ms/op
                 getUser·p0.9999: 19.787 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.944 ms/op
                 getUser·p0.9999: 14.969 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.231 ms/op
                 getUser·p0.9999: 19.135 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305352
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24502 
    [ 2.500,  5.000) = 279612 
    [ 5.000,  7.500) = 957 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.386 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 5.286 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.011 ms/op
Iteration   1: 4.093 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  13.938 ms/op
                 listUser·p0.9999: 16.931 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 3.894 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   28.115 ms/op

Iteration   3: 4.055 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  18.031 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239283
  mean =      4.012 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1678 
    [ 2.500,  5.000) = 213118 
    [ 5.000,  7.500) = 23084 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     15.310 ms/op
     p(99.9900) =     26.448 ms/op
     p(99.9990) =     27.636 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.114 ± 1.694  ops/ms
ClientGrpc.existUser                       thrpt       3  10.571 ± 1.255  ops/ms
ClientGrpc.getUser                         thrpt       3  10.413 ± 1.775  ops/ms
ClientGrpc.listUser                        thrpt       3   7.881 ± 2.002  ops/ms
ClientGrpc.createUser                       avgt       3   3.173 ± 0.726   ms/op
ClientGrpc.existUser                        avgt       3   3.031 ± 0.554   ms/op
ClientGrpc.getUser                          avgt       3   3.087 ± 1.257   ms/op
ClientGrpc.listUser                         avgt       3   4.045 ± 0.391   ms/op
ClientGrpc.createUser                     sample  302545   3.173 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.294           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.067           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.520           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.765           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.495           ms/op
ClientGrpc.existUser                      sample  316910   3.029 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.757           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.737           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.350           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.447           ms/op
ClientGrpc.getUser                        sample  305352   3.142 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.671           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.386           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.300           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.709           ms/op
ClientGrpc.listUser                       sample  239283   4.012 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.310           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.448           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.115           ms/op
