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
# Warmup Iteration   1: 4.642 ops/ms
# Warmup Iteration   2: 9.557 ops/ms
# Warmup Iteration   3: 10.241 ops/ms
Iteration   1: 10.253 ops/ms
Iteration   2: 10.616 ops/ms
Iteration   3: 10.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.408 ±(99.9%) 3.418 ops/ms [Average]
  (min, avg, max) = (10.253, 10.408, 10.616), stdev = 0.187
  CI (99.9%): [6.990, 13.826] (assumes normal distribution)


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
# Warmup Iteration   1: 7.735 ops/ms
# Warmup Iteration   2: 10.779 ops/ms
# Warmup Iteration   3: 11.275 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 10.992 ops/ms
Iteration   3: 11.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.936 ±(99.9%) 2.135 ops/ms [Average]
  (min, avg, max) = (10.802, 10.936, 11.015), stdev = 0.117
  CI (99.9%): [8.801, 13.072] (assumes normal distribution)


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
# Warmup Iteration   1: 7.786 ops/ms
# Warmup Iteration   2: 9.994 ops/ms
# Warmup Iteration   3: 10.384 ops/ms
Iteration   1: 10.297 ops/ms
Iteration   2: 10.468 ops/ms
Iteration   3: 10.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.394 ±(99.9%) 1.608 ops/ms [Average]
  (min, avg, max) = (10.297, 10.394, 10.468), stdev = 0.088
  CI (99.9%): [8.786, 12.002] (assumes normal distribution)


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
# Warmup Iteration   1: 6.524 ops/ms
# Warmup Iteration   2: 7.651 ops/ms
# Warmup Iteration   3: 8.019 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.104 ops/ms
Iteration   3: 7.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.035 ±(99.9%) 3.154 ops/ms [Average]
  (min, avg, max) = (7.838, 8.035, 8.163), stdev = 0.173
  CI (99.9%): [4.881, 11.189] (assumes normal distribution)


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.010 ms/op
Iteration   1: 3.141 ±(99.9%) 0.002 ms/op
Iteration   2: 3.102 ±(99.9%) 0.004 ms/op
Iteration   3: 3.184 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.142 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.102, 3.142, 3.184), stdev = 0.041
  CI (99.9%): [2.391, 3.894] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 2.876 ±(99.9%) 0.004 ms/op
Iteration   2: 2.918 ±(99.9%) 0.002 ms/op
Iteration   3: 2.931 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.526 ms/op [Average]
  (min, avg, max) = (2.876, 2.908, 2.931), stdev = 0.029
  CI (99.9%): [2.382, 3.434] (assumes normal distribution)


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.002 ms/op
Iteration   1: 3.119 ±(99.9%) 0.002 ms/op
Iteration   2: 3.018 ±(99.9%) 0.004 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.060 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (3.018, 3.060, 3.119), stdev = 0.053
  CI (99.9%): [2.096, 4.025] (assumes normal distribution)


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
# Warmup Iteration   1: 5.293 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.032 ms/op
Iteration   1: 3.997 ±(99.9%) 0.021 ms/op
Iteration   2: 3.895 ±(99.9%) 0.008 ms/op
Iteration   3: 3.871 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.921 ±(99.9%) 1.227 ms/op [Average]
  (min, avg, max) = (3.871, 3.921, 3.997), stdev = 0.067
  CI (99.9%): [2.694, 5.148] (assumes normal distribution)


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.503 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.717 ms/op
                 createUser·p0.9999: 18.123 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.472 ms/op
                 createUser·p0.9999: 19.413 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  13.171 ms/op
                 createUser·p0.9999: 20.021 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311108
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29269 
    [ 2.500,  5.000) = 280912 
    [ 5.000,  7.500) = 569 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     20.342 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.416 ms/op
                 existUser·p0.9999: 14.049 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  10.895 ms/op
                 existUser·p0.9999: 13.124 ms/op
                 existUser·p1.00:   13.238 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  8.722 ms/op
                 existUser·p0.9999: 14.909 ms/op
                 existUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321076
  mean =      2.988 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1749 
    [ 1.250,  2.500) = 37498 
    [ 2.500,  3.750) = 264522 
    [ 3.750,  5.000) = 16427 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      8.467 ms/op
     p(99.9900) =     14.351 ms/op
     p(99.9990) =     16.600 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.819 ms/op
                 getUser·p0.9999: 11.812 ms/op
                 getUser·p1.00:   12.435 ms/op

Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  6.644 ms/op
                 getUser·p0.9999: 12.375 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.102 ms/op
                 getUser·p0.9999: 15.773 ms/op
                 getUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317524
  mean =      3.021 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1469 
    [ 1.250,  2.500) = 26071 
    [ 2.500,  3.750) = 273893 
    [ 3.750,  5.000) = 15012 
    [ 5.000,  6.250) = 598 
    [ 6.250,  7.500) = 235 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =     13.640 ms/op
     p(99.9990) =     16.162 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 4.779 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.011 ms/op
Iteration   1: 3.934 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.588 ms/op
                 listUser·p0.9999: 18.472 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 4.047 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.679 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  11.647 ms/op
                 listUser·p0.9999: 15.719 ms/op
                 listUser·p1.00:   15.991 ms/op

Iteration   3: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 16.484 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239737
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 4553 
    [ 2.500,  3.750) = 102631 
    [ 3.750,  5.000) = 100705 
    [ 5.000,  6.250) = 25610 
    [ 6.250,  7.500) = 4696 
    [ 7.500,  8.750) = 909 
    [ 8.750, 10.000) = 163 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 138 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 83 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     12.575 ms/op
     p(99.9900) =     17.762 ms/op
     p(99.9990) =     18.763 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.408 ± 3.418  ops/ms
ClientGrpc.existUser                       thrpt       3  10.936 ± 2.135  ops/ms
ClientGrpc.getUser                         thrpt       3  10.394 ± 1.608  ops/ms
ClientGrpc.listUser                        thrpt       3   8.035 ± 3.154  ops/ms
ClientGrpc.createUser                       avgt       3   3.142 ± 0.752   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.526   ms/op
ClientGrpc.getUser                          avgt       3   3.060 ± 0.964   ms/op
ClientGrpc.listUser                         avgt       3   3.921 ± 1.227   ms/op
ClientGrpc.createUser                     sample  311108   3.086 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.503           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.628           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.414           ms/op
ClientGrpc.existUser                      sample  321076   2.988 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.556           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.467           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.351           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.712           ms/op
ClientGrpc.getUser                        sample  317524   3.021 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.898           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.640           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.286           ms/op
ClientGrpc.listUser                       sample  239737   4.006 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.679           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.575           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.762           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.874           ms/op
