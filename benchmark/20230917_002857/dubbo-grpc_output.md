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
# Warmup Iteration   1: 4.083 ops/ms
# Warmup Iteration   2: 8.948 ops/ms
# Warmup Iteration   3: 9.714 ops/ms
Iteration   1: 10.056 ops/ms
Iteration   2: 10.157 ops/ms
Iteration   3: 10.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.108 ±(99.9%) 0.925 ops/ms [Average]
  (min, avg, max) = (10.056, 10.108, 10.157), stdev = 0.051
  CI (99.9%): [9.183, 11.033] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.723 ops/ms
# Warmup Iteration   2: 10.366 ops/ms
# Warmup Iteration   3: 10.450 ops/ms
Iteration   1: 10.603 ops/ms
Iteration   2: 10.824 ops/ms
Iteration   3: 10.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.751 ±(99.9%) 2.339 ops/ms [Average]
  (min, avg, max) = (10.603, 10.751, 10.826), stdev = 0.128
  CI (99.9%): [8.412, 13.090] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.546 ops/ms
# Warmup Iteration   2: 9.980 ops/ms
# Warmup Iteration   3: 10.210 ops/ms
Iteration   1: 9.968 ops/ms
Iteration   2: 10.261 ops/ms
Iteration   3: 10.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.184 ±(99.9%) 3.453 ops/ms [Average]
  (min, avg, max) = (9.968, 10.184, 10.322), stdev = 0.189
  CI (99.9%): [6.730, 13.637] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.891 ops/ms
# Warmup Iteration   2: 7.938 ops/ms
# Warmup Iteration   3: 8.156 ops/ms
Iteration   1: 8.059 ops/ms
Iteration   2: 8.165 ops/ms
Iteration   3: 8.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.125 ±(99.9%) 1.053 ops/ms [Average]
  (min, avg, max) = (8.059, 8.125, 8.165), stdev = 0.058
  CI (99.9%): [7.072, 9.178] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.923 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.001 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
Iteration   3: 3.137 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.109 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (3.091, 3.109, 3.137), stdev = 0.024
  CI (99.9%): [2.667, 3.552] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.004 ms/op
Iteration   1: 2.975 ±(99.9%) 0.003 ms/op
Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
Iteration   3: 2.954 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.981 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (2.954, 2.981, 3.016), stdev = 0.031
  CI (99.9%): [2.410, 3.553] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.168 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.002 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
Iteration   3: 3.135 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.132 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (3.114, 3.132, 3.147), stdev = 0.016
  CI (99.9%): [2.834, 3.430] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.010 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.016 ms/op
Iteration   1: 3.910 ±(99.9%) 0.015 ms/op
Iteration   2: 3.876 ±(99.9%) 0.021 ms/op
Iteration   3: 3.915 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.900 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.876, 3.900, 3.915), stdev = 0.021
  CI (99.9%): [3.514, 4.287] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.221 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.008 ms/op
Iteration   1: 3.099 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.605 ms/op
                 createUser·p0.9999: 12.927 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   2: 3.081 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.243 ms/op
                 createUser·p0.9999: 13.176 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 3.109 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.233 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310190
  mean =      3.096 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 258 
    [ 1.250,  2.500) = 7469 
    [ 2.500,  3.750) = 284124 
    [ 3.750,  5.000) = 16649 
    [ 5.000,  6.250) = 1040 
    [ 6.250,  7.500) = 277 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.912 ms/op
     p(99.9900) =     15.536 ms/op
     p(99.9990) =     17.134 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.107 ms/op
                 existUser·p0.999:  6.914 ms/op
                 existUser·p0.9999: 15.765 ms/op
                 existUser·p1.00:   16.122 ms/op

Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  6.302 ms/op
                 existUser·p0.9999: 13.049 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.491 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316777
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 920 
    [ 1.250,  2.500) = 15357 
    [ 2.500,  3.750) = 287525 
    [ 3.750,  5.000) = 11890 
    [ 5.000,  6.250) = 644 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      7.001 ms/op
     p(99.9900) =     14.250 ms/op
     p(99.9990) =     16.034 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.006 ms/op
Iteration   1: 3.153 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.047 ms/op
                 getUser·p0.9999: 11.431 ms/op
                 getUser·p1.00:   12.255 ms/op

Iteration   2: 3.132 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  8.667 ms/op
                 getUser·p0.9999: 12.842 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   3: 3.104 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  6.636 ms/op
                 getUser·p0.9999: 15.462 ms/op
                 getUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306626
  mean =      3.130 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 434 
    [ 1.250,  2.500) = 6939 
    [ 2.500,  3.750) = 279405 
    [ 3.750,  5.000) = 18468 
    [ 5.000,  6.250) = 741 
    [ 6.250,  7.500) = 328 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.562 ms/op
     p(99.9900) =     14.931 ms/op
     p(99.9990) =     15.645 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.009 ms/op
Iteration   1: 3.937 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.448 ms/op
                 listUser·p0.9999: 15.719 ms/op
                 listUser·p1.00:   16.187 ms/op

Iteration   2: 3.951 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  12.893 ms/op
                 listUser·p0.9999: 14.300 ms/op
                 listUser·p1.00:   15.565 ms/op

Iteration   3: 3.927 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.525 ms/op
                 listUser·p0.9999: 18.313 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243752
  mean =      3.938 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3219 
    [ 2.500,  5.000) = 224978 
    [ 5.000,  7.500) = 14462 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     12.882 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     20.142 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.108 ± 0.925  ops/ms
ClientGrpc.existUser                       thrpt       3  10.751 ± 2.339  ops/ms
ClientGrpc.getUser                         thrpt       3  10.184 ± 3.453  ops/ms
ClientGrpc.listUser                        thrpt       3   8.125 ± 1.053  ops/ms
ClientGrpc.createUser                       avgt       3   3.109 ± 0.442   ms/op
ClientGrpc.existUser                        avgt       3   2.981 ± 0.572   ms/op
ClientGrpc.getUser                          avgt       3   3.132 ± 0.298   ms/op
ClientGrpc.listUser                         avgt       3   3.900 ± 0.386   ms/op
ClientGrpc.createUser                     sample  310190   3.096 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.736           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.912           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.536           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.302           ms/op
ClientGrpc.existUser                      sample  316777   3.029 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.001           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.250           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.122           ms/op
ClientGrpc.getUser                        sample  306626   3.130 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.837           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.562           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.931           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.745           ms/op
ClientGrpc.listUser                       sample  243752   3.938 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.798           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.882           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.465           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.251           ms/op
