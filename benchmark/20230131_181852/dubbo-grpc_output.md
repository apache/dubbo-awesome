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
# Warmup Iteration   1: 4.508 ops/ms
# Warmup Iteration   2: 9.415 ops/ms
# Warmup Iteration   3: 10.308 ops/ms
Iteration   1: 10.585 ops/ms
Iteration   2: 10.739 ops/ms
Iteration   3: 10.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.608 ±(99.9%) 2.200 ops/ms [Average]
  (min, avg, max) = (10.501, 10.608, 10.739), stdev = 0.121
  CI (99.9%): [8.408, 12.808] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.882 ops/ms
# Warmup Iteration   2: 10.634 ops/ms
# Warmup Iteration   3: 10.690 ops/ms
Iteration   1: 10.553 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.716 ±(99.9%) 2.649 ops/ms [Average]
  (min, avg, max) = (10.553, 10.716, 10.829), stdev = 0.145
  CI (99.9%): [8.067, 13.365] (assumes normal distribution)


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
# Warmup Iteration   1: 7.184 ops/ms
# Warmup Iteration   2: 10.179 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.574 ops/ms
Iteration   2: 10.537 ops/ms
Iteration   3: 10.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.509 ±(99.9%) 1.507 ops/ms [Average]
  (min, avg, max) = (10.416, 10.509, 10.574), stdev = 0.083
  CI (99.9%): [9.002, 12.015] (assumes normal distribution)


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
# Warmup Iteration   1: 6.243 ops/ms
# Warmup Iteration   2: 7.807 ops/ms
# Warmup Iteration   3: 7.854 ops/ms
Iteration   1: 7.914 ops/ms
Iteration   2: 7.989 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.987 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (7.914, 7.987, 8.060), stdev = 0.073
  CI (99.9%): [6.658, 9.317] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.003 ms/op
Iteration   1: 3.116 ±(99.9%) 0.002 ms/op
Iteration   2: 3.092 ±(99.9%) 0.002 ms/op
Iteration   3: 3.191 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.133 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (3.092, 3.133, 3.191), stdev = 0.051
  CI (99.9%): [2.195, 4.071] (assumes normal distribution)


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.004 ms/op
Iteration   1: 2.903 ±(99.9%) 0.003 ms/op
Iteration   2: 2.905 ±(99.9%) 0.003 ms/op
Iteration   3: 2.939 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.916 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (2.903, 2.916, 2.939), stdev = 0.020
  CI (99.9%): [2.550, 3.281] (assumes normal distribution)


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.002 ms/op
Iteration   1: 3.131 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 2.981 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 1.400 ms/op [Average]
  (min, avg, max) = (2.981, 3.064, 3.131), stdev = 0.077
  CI (99.9%): [1.665, 4.464] (assumes normal distribution)


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
# Warmup Iteration   1: 5.109 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.022 ms/op
Iteration   1: 4.078 ±(99.9%) 0.014 ms/op
Iteration   2: 3.856 ±(99.9%) 0.092 ms/op
Iteration   3: 3.964 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.966 ±(99.9%) 2.019 ms/op [Average]
  (min, avg, max) = (3.856, 3.966, 4.078), stdev = 0.111
  CI (99.9%): [1.946, 5.985] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
Iteration   1: 3.150 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 14.776 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   2: 3.134 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.487 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.869 ms/op
                 createUser·p0.9999: 16.831 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 22.012 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304973
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20427 
    [ 2.500,  5.000) = 283484 
    [ 5.000,  7.500) = 584 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =     10.421 ms/op
     p(99.9900) =     19.333 ms/op
     p(99.9990) =     22.444 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.927 ms/op
                 existUser·p0.9999: 11.534 ms/op
                 existUser·p1.00:   11.780 ms/op

Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   3.992 ms/op
                 existUser·p0.999:  5.071 ms/op
                 existUser·p0.9999: 12.468 ms/op
                 existUser·p1.00:   12.681 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  9.863 ms/op
                 existUser·p0.9999: 15.401 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326878
  mean =      2.939 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1702 
    [ 1.250,  2.500) = 40909 
    [ 2.500,  3.750) = 272763 
    [ 3.750,  5.000) = 10701 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      7.065 ms/op
     p(99.9900) =     14.647 ms/op
     p(99.9990) =     15.626 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.576 ms/op
                 getUser·p0.9999: 16.191 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.332 ms/op
                 getUser·p0.9999: 13.555 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.381 ms/op
                 getUser·p0.9999: 17.351 ms/op
                 getUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307404
  mean =      3.124 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1102 
    [ 1.250,  2.500) = 19031 
    [ 2.500,  3.750) = 255342 
    [ 3.750,  5.000) = 31204 
    [ 5.000,  6.250) = 329 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.690 ms/op
     p(99.9900) =     16.011 ms/op
     p(99.9990) =     17.725 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.012 ms/op
Iteration   1: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  12.082 ms/op
                 listUser·p0.9999: 15.217 ms/op
                 listUser·p1.00:   16.466 ms/op

Iteration   2: 3.883 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.549 ms/op
                 listUser·p0.9999: 16.708 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 4.047 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 18.484 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242123
  mean =      3.966 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 4725 
    [ 2.500,  3.750) = 100300 
    [ 3.750,  5.000) = 111957 
    [ 5.000,  6.250) = 19329 
    [ 6.250,  7.500) = 4648 
    [ 7.500,  8.750) = 594 
    [ 8.750, 10.000) = 126 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 88 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     13.285 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     19.040 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.608 ± 2.200  ops/ms
ClientGrpc.existUser                       thrpt       3  10.716 ± 2.649  ops/ms
ClientGrpc.getUser                         thrpt       3  10.509 ± 1.507  ops/ms
ClientGrpc.listUser                        thrpt       3   7.987 ± 1.329  ops/ms
ClientGrpc.createUser                       avgt       3   3.133 ± 0.938   ms/op
ClientGrpc.existUser                        avgt       3   2.916 ± 0.365   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 1.400   ms/op
ClientGrpc.listUser                         avgt       3   3.966 ± 2.019   ms/op
ClientGrpc.createUser                     sample  304973   3.149 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.487           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.333           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.544           ms/op
ClientGrpc.existUser                      sample  326878   2.939 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.688           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.065           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.647           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  307404   3.124 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.465           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.690           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.011           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.826           ms/op
ClientGrpc.listUser                       sample  242123   3.966 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.940           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.285           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.777           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.235           ms/op
