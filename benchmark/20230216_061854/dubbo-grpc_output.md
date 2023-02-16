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
# Warmup Iteration   1: 2.685 ops/ms
# Warmup Iteration   2: 6.195 ops/ms
# Warmup Iteration   3: 7.814 ops/ms
Iteration   1: 7.956 ops/ms
Iteration   2: 8.346 ops/ms
Iteration   3: 8.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.120 ±(99.9%) 3.691 ops/ms [Average]
  (min, avg, max) = (7.956, 8.120, 8.346), stdev = 0.202
  CI (99.9%): [4.430, 11.811] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.386 ops/ms
# Warmup Iteration   2: 7.967 ops/ms
# Warmup Iteration   3: 8.427 ops/ms
Iteration   1: 8.544 ops/ms
Iteration   2: 8.459 ops/ms
Iteration   3: 8.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.473 ±(99.9%) 1.173 ops/ms [Average]
  (min, avg, max) = (8.417, 8.473, 8.544), stdev = 0.064
  CI (99.9%): [7.301, 9.646] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.917 ops/ms
# Warmup Iteration   2: 7.721 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 7.899 ops/ms
Iteration   2: 8.127 ops/ms
Iteration   3: 8.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.021 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (7.899, 8.021, 8.127), stdev = 0.115
  CI (99.9%): [5.925, 10.117] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.552 ops/ms
# Warmup Iteration   2: 5.550 ops/ms
# Warmup Iteration   3: 6.017 ops/ms
Iteration   1: 5.978 ops/ms
Iteration   2: 6.022 ops/ms
Iteration   3: 6.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.102 ±(99.9%) 3.262 ops/ms [Average]
  (min, avg, max) = (5.978, 6.102, 6.307), stdev = 0.179
  CI (99.9%): [2.840, 9.364] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.814 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.003 ms/op
Iteration   1: 4.101 ±(99.9%) 0.003 ms/op
Iteration   2: 4.114 ±(99.9%) 0.002 ms/op
Iteration   3: 3.924 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.046 ±(99.9%) 1.937 ms/op [Average]
  (min, avg, max) = (3.924, 4.046, 4.114), stdev = 0.106
  CI (99.9%): [2.109, 5.983] (assumes normal distribution)


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
# Warmup Iteration   1: 5.449 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.004 ms/op
Iteration   1: 3.780 ±(99.9%) 0.004 ms/op
Iteration   2: 3.827 ±(99.9%) 0.003 ms/op
Iteration   3: 3.916 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.841 ±(99.9%) 1.259 ms/op [Average]
  (min, avg, max) = (3.780, 3.841, 3.916), stdev = 0.069
  CI (99.9%): [2.582, 5.100] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.453 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.008 ms/op
Iteration   1: 3.867 ±(99.9%) 0.005 ms/op
Iteration   2: 3.901 ±(99.9%) 0.004 ms/op
Iteration   3: 3.885 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.884 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (3.867, 3.884, 3.901), stdev = 0.017
  CI (99.9%): [3.572, 4.197] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.371 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.460 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.341 ±(99.9%) 0.020 ms/op
Iteration   1: 5.381 ±(99.9%) 0.034 ms/op
Iteration   2: 5.201 ±(99.9%) 0.021 ms/op
Iteration   3: 5.211 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.264 ±(99.9%) 1.847 ms/op [Average]
  (min, avg, max) = (5.201, 5.264, 5.381), stdev = 0.101
  CI (99.9%): [3.417, 7.111] (assumes normal distribution)


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
# Warmup Iteration   1: 5.722 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.013 ms/op
Iteration   1: 4.004 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  17.500 ms/op
                 createUser·p0.9999: 22.874 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.921 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   7.495 ms/op
                 createUser·p0.999:  18.696 ms/op
                 createUser·p0.9999: 31.746 ms/op
                 createUser·p1.00:   32.113 ms/op

Iteration   3: 3.885 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  16.630 ms/op
                 createUser·p0.9999: 20.603 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244076
  mean =      3.936 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11574 
    [ 2.500,  5.000) = 213667 
    [ 5.000,  7.500) = 16436 
    [ 7.500, 10.000) = 1023 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 424 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     17.627 ms/op
     p(99.9900) =     28.956 ms/op
     p(99.9990) =     32.033 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.085 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.014 ms/op
Iteration   1: 3.832 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  14.969 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   2: 3.697 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  13.213 ms/op
                 existUser·p0.9999: 18.722 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   3: 3.711 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   7.963 ms/op
                 existUser·p0.999:  23.084 ms/op
                 existUser·p0.9999: 29.950 ms/op
                 existUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 256199
  mean =      3.746 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17843 
    [ 2.500,  5.000) = 224335 
    [ 5.000,  7.500) = 11654 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 463 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     28.291 ms/op
     p(99.9990) =     30.503 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 5.564 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.013 ms/op
Iteration   1: 3.917 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   8.028 ms/op
                 getUser·p0.999:  15.341 ms/op
                 getUser·p0.9999: 19.857 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.879 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   7.303 ms/op
                 getUser·p0.999:  13.255 ms/op
                 getUser·p0.9999: 35.373 ms/op
                 getUser·p1.00:   39.453 ms/op

Iteration   3: 3.912 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   7.946 ms/op
                 getUser·p0.999:  16.843 ms/op
                 getUser·p0.9999: 24.853 ms/op
                 getUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 245926
  mean =      3.903 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8709 
    [ 2.500,  5.000) = 220861 
    [ 5.000,  7.500) = 13551 
    [ 7.500, 10.000) = 1811 
    [10.000, 12.500) = 475 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     15.208 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     37.817 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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
# Warmup Iteration   1: 7.422 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.531 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.312 ±(99.9%) 0.021 ms/op
Iteration   1: 5.145 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.742 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  15.626 ms/op
                 listUser·p0.9999: 20.473 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 5.195 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.453 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.725 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  21.957 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 5.196 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   10.891 ms/op
                 listUser·p0.999:  24.362 ms/op
                 listUser·p0.9999: 32.962 ms/op
                 listUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 185302
  mean =      5.179 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 564 
    [ 2.500,  5.000) = 105849 
    [ 5.000,  7.500) = 68367 
    [ 7.500, 10.000) = 8220 
    [10.000, 12.500) = 1289 
    [12.500, 15.000) = 409 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 197 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     20.382 ms/op
     p(99.9900) =     28.450 ms/op
     p(99.9990) =     34.034 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.120 ± 3.691  ops/ms
ClientGrpc.existUser                       thrpt       3   8.473 ± 1.173  ops/ms
ClientGrpc.getUser                         thrpt       3   8.021 ± 2.096  ops/ms
ClientGrpc.listUser                        thrpt       3   6.102 ± 3.262  ops/ms
ClientGrpc.createUser                       avgt       3   4.046 ± 1.937   ms/op
ClientGrpc.existUser                        avgt       3   3.841 ± 1.259   ms/op
ClientGrpc.getUser                          avgt       3   3.884 ± 0.313   ms/op
ClientGrpc.listUser                         avgt       3   5.264 ± 1.847   ms/op
ClientGrpc.createUser                     sample  244076   3.936 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.779           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.251           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.447           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.627           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.956           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.113           ms/op
ClientGrpc.existUser                      sample  256199   3.746 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.710           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.054           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.299           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          16.040           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.291           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.605           ms/op
ClientGrpc.getUser                        sample  245926   3.903 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.735           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.832           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.208           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.013           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          39.453           ms/op
ClientGrpc.listUser                       sample  185302   5.179 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.453           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.643           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.519           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.382           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.450           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.537           ms/op
