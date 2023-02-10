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
# Warmup Iteration   1: 5.074 ops/ms
# Warmup Iteration   2: 8.962 ops/ms
# Warmup Iteration   3: 10.302 ops/ms
Iteration   1: 10.328 ops/ms
Iteration   2: 10.355 ops/ms
Iteration   3: 10.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.373 ±(99.9%) 1.015 ops/ms [Average]
  (min, avg, max) = (10.328, 10.373, 10.435), stdev = 0.056
  CI (99.9%): [9.358, 11.388] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.370 ops/ms
# Warmup Iteration   2: 10.944 ops/ms
# Warmup Iteration   3: 10.730 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.743 ops/ms
Iteration   3: 10.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.821 ±(99.9%) 2.129 ops/ms [Average]
  (min, avg, max) = (10.743, 10.821, 10.955), stdev = 0.117
  CI (99.9%): [8.692, 12.950] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.679 ops/ms
# Warmup Iteration   2: 10.448 ops/ms
# Warmup Iteration   3: 10.620 ops/ms
Iteration   1: 10.467 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.577 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (10.467, 10.577, 10.639), stdev = 0.096
  CI (99.9%): [8.824, 12.331] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.052 ops/ms
# Warmup Iteration   2: 7.717 ops/ms
# Warmup Iteration   3: 7.839 ops/ms
Iteration   1: 8.127 ops/ms
Iteration   2: 8.199 ops/ms
Iteration   3: 7.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.010 ±(99.9%) 4.861 ops/ms [Average]
  (min, avg, max) = (7.705, 8.010, 8.199), stdev = 0.266
  CI (99.9%): [3.149, 12.871] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.004 ms/op
Iteration   2: 3.187 ±(99.9%) 0.001 ms/op
Iteration   3: 3.145 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.120 ±(99.9%) 1.510 ms/op [Average]
  (min, avg, max) = (3.028, 3.120, 3.187), stdev = 0.083
  CI (99.9%): [1.610, 4.630] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 2.899 ±(99.9%) 0.003 ms/op
Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 1.205 ms/op [Average]
  (min, avg, max) = (2.886, 2.931, 3.006), stdev = 0.066
  CI (99.9%): [1.726, 4.136] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.003 ms/op
Iteration   1: 3.079 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 2.967 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.041 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (2.967, 3.041, 3.079), stdev = 0.064
  CI (99.9%): [1.868, 4.214] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.849 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.020 ms/op
Iteration   1: 3.854 ±(99.9%) 0.004 ms/op
Iteration   2: 3.989 ±(99.9%) 0.022 ms/op
Iteration   3: 3.732 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.858 ±(99.9%) 2.341 ms/op [Average]
  (min, avg, max) = (3.732, 3.858, 3.989), stdev = 0.128
  CI (99.9%): [1.518, 6.199] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.069 ms/op
                 createUser·p0.9999: 14.609 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.372 ms/op
                 createUser·p0.9999: 15.219 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.354 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.592 ms/op
                 createUser·p0.9999: 20.006 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311154
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26894 
    [ 2.500,  5.000) = 283158 
    [ 5.000,  7.500) = 703 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.709 ms/op
     p(99.9900) =     18.900 ms/op
     p(99.9990) =     20.476 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.007 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  5.517 ms/op
                 existUser·p0.9999: 10.962 ms/op
                 existUser·p1.00:   11.387 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  9.466 ms/op
                 existUser·p0.9999: 14.828 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.294 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321956
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42721 
    [ 2.500,  5.000) = 278486 
    [ 5.000,  7.500) = 469 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.259 ms/op
     p(99.9900) =     22.773 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.709 ms/op
                 getUser·p0.9999: 11.605 ms/op
                 getUser·p1.00:   12.190 ms/op

Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.426 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  5.972 ms/op
                 getUser·p0.9999: 21.489 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  6.242 ms/op
                 getUser·p0.9999: 14.101 ms/op
                 getUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313796
  mean =      3.059 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25246 
    [ 2.500,  5.000) = 287782 
    [ 5.000,  7.500) = 545 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.400 ms/op
     p(99.9900) =     20.529 ms/op
     p(99.9990) =     21.847 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 5.348 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.010 ms/op
Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  12.370 ms/op
                 listUser·p0.9999: 18.021 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   2: 3.947 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.071 ms/op
                 listUser·p0.9999: 18.297 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 4.060 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.378 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  14.327 ms/op
                 listUser·p0.9999: 17.801 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240181
  mean =      3.996 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 4502 
    [ 2.500,  3.750) = 105006 
    [ 3.750,  5.000) = 99612 
    [ 5.000,  6.250) = 25404 
    [ 6.250,  7.500) = 4400 
    [ 7.500,  8.750) = 595 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 97 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 58 
    [17.500, 18.750) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     18.703 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.373 ± 1.015  ops/ms
ClientGrpc.existUser                       thrpt       3  10.821 ± 2.129  ops/ms
ClientGrpc.getUser                         thrpt       3  10.577 ± 1.753  ops/ms
ClientGrpc.listUser                        thrpt       3   8.010 ± 4.861  ops/ms
ClientGrpc.createUser                       avgt       3   3.120 ± 1.510   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 1.205   ms/op
ClientGrpc.getUser                          avgt       3   3.041 ± 1.173   ms/op
ClientGrpc.listUser                         avgt       3   3.858 ± 2.341   ms/op
ClientGrpc.createUser                     sample  311154   3.084 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.354           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.709           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.900           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.692           ms/op
ClientGrpc.existUser                      sample  321956   2.983 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.597           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.259           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.773           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.329           ms/op
ClientGrpc.getUser                        sample  313796   3.059 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.426           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.400           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.529           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.889           ms/op
ClientGrpc.listUser                       sample  240181   3.996 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.378           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.730           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.990           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.940           ms/op
