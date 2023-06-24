# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ops/ms
# Warmup Iteration   2: 8.669 ops/ms
# Warmup Iteration   3: 9.901 ops/ms
Iteration   1: 10.385 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.449 ±(99.9%) 1.672 ops/ms [Average]
  (min, avg, max) = (10.385, 10.449, 10.554), stdev = 0.092
  CI (99.9%): [8.777, 12.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.271 ops/ms
# Warmup Iteration   2: 10.503 ops/ms
# Warmup Iteration   3: 11.022 ops/ms
Iteration   1: 11.490 ops/ms
Iteration   2: 10.877 ops/ms
Iteration   3: 10.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.078 ±(99.9%) 6.508 ops/ms [Average]
  (min, avg, max) = (10.868, 11.078, 11.490), stdev = 0.357
  CI (99.9%): [4.570, 17.586] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.841 ops/ms
# Warmup Iteration   2: 10.097 ops/ms
# Warmup Iteration   3: 10.582 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.690 ops/ms
Iteration   3: 10.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.590 ±(99.9%) 1.813 ops/ms [Average]
  (min, avg, max) = (10.491, 10.590, 10.690), stdev = 0.099
  CI (99.9%): [8.777, 12.403] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.626 ops/ms
# Warmup Iteration   2: 7.477 ops/ms
# Warmup Iteration   3: 7.753 ops/ms
Iteration   1: 7.724 ops/ms
Iteration   2: 7.807 ops/ms
Iteration   3: 7.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.781 ±(99.9%) 0.890 ops/ms [Average]
  (min, avg, max) = (7.724, 7.781, 7.811), stdev = 0.049
  CI (99.9%): [6.890, 8.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.564 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.002 ms/op
Iteration   1: 3.053 ±(99.9%) 0.004 ms/op
Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
Iteration   3: 3.034 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (3.034, 3.042, 3.053), stdev = 0.010
  CI (99.9%): [2.867, 3.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.068 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 2.927 ±(99.9%) 0.003 ms/op
Iteration   2: 2.885 ±(99.9%) 0.003 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.939 ±(99.9%) 1.102 ms/op [Average]
  (min, avg, max) = (2.885, 2.939, 3.004), stdev = 0.060
  CI (99.9%): [1.837, 4.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.002 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.031 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.002, 3.031, 3.061), stdev = 0.029
  CI (99.9%): [2.495, 3.568] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.367 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.008 ms/op
Iteration   1: 4.076 ±(99.9%) 0.010 ms/op
Iteration   2: 4.112 ±(99.9%) 0.006 ms/op
Iteration   3: 4.088 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.092 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (4.076, 4.092, 4.112), stdev = 0.019
  CI (99.9%): [3.752, 4.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.167 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.005 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  10.872 ms/op
                 createUser·p0.9999: 14.296 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.447 ms/op
                 createUser·p0.999:  7.949 ms/op
                 createUser·p0.9999: 13.973 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.478 ms/op
                 createUser·p0.999:  10.931 ms/op
                 createUser·p0.9999: 18.176 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311480
  mean =      3.081 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 471 
    [ 1.250,  2.500) = 16396 
    [ 2.500,  3.750) = 276050 
    [ 3.750,  5.000) = 16882 
    [ 5.000,  6.250) = 893 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =     10.569 ms/op
     p(99.9900) =     16.709 ms/op
     p(99.9990) =     18.532 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  7.433 ms/op
                 existUser·p0.9999: 13.226 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  11.705 ms/op
                 existUser·p0.9999: 22.554 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.739 ms/op
                 existUser·p0.9999: 21.391 ms/op
                 existUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323577
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31823 
    [ 2.500,  5.000) = 290738 
    [ 5.000,  7.500) = 651 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.761 ms/op
     p(99.9900) =     21.713 ms/op
     p(99.9990) =     23.094 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.757 ms/op
                 getUser·p0.9999: 19.503 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.184 ms/op
                 getUser·p0.9999: 15.372 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 15.581 ms/op
                 getUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312259
  mean =      3.072 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 651 
    [ 1.250,  2.500) = 17458 
    [ 2.500,  3.750) = 274154 
    [ 3.750,  5.000) = 18718 
    [ 5.000,  6.250) = 777 
    [ 6.250,  7.500) = 316 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =     18.572 ms/op
     p(99.9990) =     19.874 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.061 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.011 ms/op
Iteration   1: 4.119 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 19.996 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 4.039 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 4.046 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 28.652 ms/op
                 listUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236001
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2600 
    [ 2.500,  5.000) = 210012 
    [ 5.000,  7.500) = 21790 
    [ 7.500, 10.000) = 1149 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     27.178 ms/op
     p(99.9990) =     29.304 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.449 ± 1.672  ops/ms
ClientGrpc.existUser                       thrpt       3  11.078 ± 6.508  ops/ms
ClientGrpc.getUser                         thrpt       3  10.590 ± 1.813  ops/ms
ClientGrpc.listUser                        thrpt       3   7.781 ± 0.890  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 0.175   ms/op
ClientGrpc.existUser                        avgt       3   2.939 ± 1.102   ms/op
ClientGrpc.getUser                          avgt       3   3.031 ± 0.537   ms/op
ClientGrpc.listUser                         avgt       3   4.092 ± 0.340   ms/op
ClientGrpc.createUser                     sample  311480   3.081 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.716           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.569           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.709           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.711           ms/op
ClientGrpc.existUser                      sample  323577   2.967 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.739           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.761           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.713           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.560           ms/op
ClientGrpc.getUser                        sample  312259   3.072 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.837           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.898           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.572           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.988           ms/op
ClientGrpc.listUser                       sample  236001   4.068 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.994           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.680           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.178           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.393           ms/op
