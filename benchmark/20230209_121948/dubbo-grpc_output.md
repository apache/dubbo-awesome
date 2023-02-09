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
# Warmup Iteration   1: 4.892 ops/ms
# Warmup Iteration   2: 9.803 ops/ms
# Warmup Iteration   3: 10.156 ops/ms
Iteration   1: 10.464 ops/ms
Iteration   2: 10.534 ops/ms
Iteration   3: 10.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.422 ±(99.9%) 2.514 ops/ms [Average]
  (min, avg, max) = (10.268, 10.422, 10.534), stdev = 0.138
  CI (99.9%): [7.908, 12.936] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.981 ops/ms
# Warmup Iteration   2: 10.581 ops/ms
# Warmup Iteration   3: 11.055 ops/ms
Iteration   1: 10.810 ops/ms
Iteration   2: 10.856 ops/ms
Iteration   3: 10.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.885 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (10.810, 10.885, 10.989), stdev = 0.093
  CI (99.9%): [9.185, 12.585] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.830 ops/ms
# Warmup Iteration   2: 10.331 ops/ms
# Warmup Iteration   3: 10.722 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.381 ops/ms
Iteration   3: 10.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.447 ±(99.9%) 4.603 ops/ms [Average]
  (min, avg, max) = (10.234, 10.447, 10.725), stdev = 0.252
  CI (99.9%): [5.843, 15.050] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.071 ops/ms
# Warmup Iteration   2: 7.813 ops/ms
# Warmup Iteration   3: 8.390 ops/ms
Iteration   1: 8.040 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.095 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (8.024, 8.095, 8.221), stdev = 0.109
  CI (99.9%): [6.101, 10.089] (assumes normal distribution)


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.003 ms/op
Iteration   1: 3.099 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.069 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.007, 3.069, 3.100), stdev = 0.053
  CI (99.9%): [2.093, 4.044] (assumes normal distribution)


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
# Warmup Iteration   1: 3.837 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.003 ms/op
Iteration   1: 2.942 ±(99.9%) 0.002 ms/op
Iteration   2: 2.923 ±(99.9%) 0.001 ms/op
Iteration   3: 2.928 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (2.923, 2.931, 2.942), stdev = 0.010
  CI (99.9%): [2.754, 3.108] (assumes normal distribution)


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
# Warmup Iteration   1: 3.563 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.002 ms/op
Iteration   1: 3.015 ±(99.9%) 0.002 ms/op
Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
Iteration   3: 3.026 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.010 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.990, 3.010, 3.026), stdev = 0.019
  CI (99.9%): [2.670, 3.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.035 ms/op
Iteration   1: 4.064 ±(99.9%) 0.014 ms/op
Iteration   2: 3.889 ±(99.9%) 0.015 ms/op
Iteration   3: 4.038 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.997 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (3.889, 3.997, 4.064), stdev = 0.094
  CI (99.9%): [2.276, 5.717] (assumes normal distribution)


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
# Warmup Iteration   1: 3.496 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.376 ms/op
                 createUser·p0.9999: 12.091 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.751 ms/op
                 createUser·p0.9999: 13.931 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.441 ms/op
                 createUser·p0.9999: 15.891 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310458
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1632 
    [ 1.250,  2.500) = 27314 
    [ 2.500,  3.750) = 250035 
    [ 3.750,  5.000) = 30570 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 153 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     15.123 ms/op
     p(99.9990) =     17.983 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.005 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.125 ms/op
                 existUser·p0.9999: 11.116 ms/op
                 existUser·p1.00:   11.551 ms/op

Iteration   2: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.336 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.319 ms/op
                 existUser·p0.9999: 13.650 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  8.569 ms/op
                 existUser·p0.9999: 15.239 ms/op
                 existUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323868
  mean =      2.963 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2299 
    [ 1.250,  2.500) = 46390 
    [ 2.500,  3.750) = 251860 
    [ 3.750,  5.000) = 22142 
    [ 5.000,  6.250) = 538 
    [ 6.250,  7.500) = 327 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.455 ms/op
     p(99.9900) =     13.963 ms/op
     p(99.9990) =     15.635 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.277 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  9.679 ms/op
                 getUser·p0.9999: 11.977 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  5.882 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   3: 2.959 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  5.894 ms/op
                 getUser·p0.9999: 17.280 ms/op
                 getUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322047
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3762 
    [ 1.250,  2.500) = 25194 
    [ 2.500,  3.750) = 280142 
    [ 3.750,  5.000) = 12112 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.277 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.849 ms/op
     p(99.9900) =     17.033 ms/op
     p(99.9990) =     17.771 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.011 ms/op
Iteration   1: 3.909 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.941 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  12.130 ms/op
                 listUser·p0.9999: 16.184 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   2: 3.876 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  14.790 ms/op
                 listUser·p0.9999: 24.419 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   3: 3.962 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.708 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 20.773 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245196
  mean =      3.915 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3652 
    [ 2.500,  5.000) = 215811 
    [ 5.000,  7.500) = 24747 
    [ 7.500, 10.000) = 579 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     24.579 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.422 ± 2.514  ops/ms
ClientGrpc.existUser                       thrpt       3  10.885 ± 1.700  ops/ms
ClientGrpc.getUser                         thrpt       3  10.447 ± 4.603  ops/ms
ClientGrpc.listUser                        thrpt       3   8.095 ± 1.994  ops/ms
ClientGrpc.createUser                       avgt       3   3.069 ± 0.976   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 0.177   ms/op
ClientGrpc.getUser                          avgt       3   3.010 ± 0.340   ms/op
ClientGrpc.listUser                         avgt       3   3.997 ± 1.721   ms/op
ClientGrpc.createUser                     sample  310458   3.092 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.634           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.053           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.123           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.121           ms/op
ClientGrpc.existUser                      sample  323868   2.963 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.336           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.850           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.455           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.963           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.778           ms/op
ClientGrpc.getUser                        sample  322047   2.980 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.277           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.178           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.849           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.033           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.793           ms/op
ClientGrpc.listUser                       sample  245196   3.915 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.762           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.681           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.429           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.199           ms/op
