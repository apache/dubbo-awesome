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
# Warmup Iteration   1: 3.992 ops/ms
# Warmup Iteration   2: 8.754 ops/ms
# Warmup Iteration   3: 9.793 ops/ms
Iteration   1: 10.009 ops/ms
Iteration   2: 10.110 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.135 ±(99.9%) 2.535 ops/ms [Average]
  (min, avg, max) = (10.009, 10.135, 10.284), stdev = 0.139
  CI (99.9%): [7.599, 12.670] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.618 ops/ms
# Warmup Iteration   2: 9.807 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.594 ops/ms
Iteration   3: 10.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.564 ±(99.9%) 1.537 ops/ms [Average]
  (min, avg, max) = (10.469, 10.564, 10.628), stdev = 0.084
  CI (99.9%): [9.027, 12.101] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.320 ops/ms
# Warmup Iteration   2: 9.751 ops/ms
# Warmup Iteration   3: 10.213 ops/ms
Iteration   1: 10.192 ops/ms
Iteration   2: 9.957 ops/ms
Iteration   3: 10.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.084 ±(99.9%) 2.162 ops/ms [Average]
  (min, avg, max) = (9.957, 10.084, 10.192), stdev = 0.118
  CI (99.9%): [7.922, 12.245] (assumes normal distribution)


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
# Warmup Iteration   1: 5.714 ops/ms
# Warmup Iteration   2: 8.182 ops/ms
# Warmup Iteration   3: 8.352 ops/ms
Iteration   1: 8.254 ops/ms
Iteration   2: 8.390 ops/ms
Iteration   3: 8.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.315 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (8.254, 8.315, 8.390), stdev = 0.069
  CI (99.9%): [7.050, 9.579] (assumes normal distribution)


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.003 ms/op
Iteration   1: 3.154 ±(99.9%) 0.001 ms/op
Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
Iteration   3: 3.111 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.118 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (3.089, 3.118, 3.154), stdev = 0.033
  CI (99.9%): [2.514, 3.723] (assumes normal distribution)


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 3.033 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.007 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (2.958, 3.007, 3.033), stdev = 0.043
  CI (99.9%): [2.230, 3.785] (assumes normal distribution)


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.002 ms/op
Iteration   1: 3.110 ±(99.9%) 0.003 ms/op
Iteration   2: 3.152 ±(99.9%) 0.001 ms/op
Iteration   3: 3.111 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.125 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.110, 3.125, 3.152), stdev = 0.024
  CI (99.9%): [2.687, 3.563] (assumes normal distribution)


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.018 ms/op
Iteration   1: 3.960 ±(99.9%) 0.013 ms/op
Iteration   2: 3.833 ±(99.9%) 0.019 ms/op
Iteration   3: 3.833 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.875 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (3.833, 3.875, 3.960), stdev = 0.074
  CI (99.9%): [2.533, 5.218] (assumes normal distribution)


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
Iteration   1: 3.179 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  8.003 ms/op
                 createUser·p0.9999: 15.544 ms/op
                 createUser·p1.00:   16.007 ms/op

Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  8.028 ms/op
                 createUser·p0.9999: 19.544 ms/op
                 createUser·p1.00:   19.923 ms/op

Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  9.580 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303144
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18997 
    [ 2.500,  5.000) = 280772 
    [ 5.000,  7.500) = 2873 
    [ 7.500, 10.000) = 284 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     22.803 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
Iteration   1: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.350 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  7.586 ms/op
                 existUser·p0.9999: 16.934 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 18.932 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   3: 2.966 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  7.169 ms/op
                 existUser·p0.9999: 23.174 ms/op
                 existUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322465
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32714 
    [ 2.500,  5.000) = 287140 
    [ 5.000,  7.500) = 2228 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     23.677 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  7.454 ms/op
                 getUser·p0.9999: 11.629 ms/op
                 getUser·p1.00:   11.911 ms/op

Iteration   2: 3.139 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.857 ms/op
                 getUser·p0.9999: 14.022 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 3.141 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.707 ms/op
                 getUser·p0.9999: 16.053 ms/op
                 getUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305859
  mean =      3.137 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 473 
    [ 1.250,  2.500) = 9323 
    [ 2.500,  3.750) = 273168 
    [ 3.750,  5.000) = 20765 
    [ 5.000,  6.250) = 1128 
    [ 6.250,  7.500) = 664 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     16.558 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 5.478 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  13.516 ms/op
                 listUser·p0.9999: 16.614 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   2: 4.033 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.132 ms/op
                 listUser·p0.9999: 15.761 ms/op
                 listUser·p1.00:   16.024 ms/op

Iteration   3: 3.956 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.703 ms/op
                 listUser·p0.9999: 18.806 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239836
  mean =      4.001 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3120 
    [ 2.500,  5.000) = 214144 
    [ 5.000,  7.500) = 20596 
    [ 7.500, 10.000) = 1314 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     18.351 ms/op
     p(99.9990) =     18.953 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.135 ± 2.535  ops/ms
ClientGrpc.existUser                       thrpt       3  10.564 ± 1.537  ops/ms
ClientGrpc.getUser                         thrpt       3  10.084 ± 2.162  ops/ms
ClientGrpc.listUser                        thrpt       3   8.315 ± 1.264  ops/ms
ClientGrpc.createUser                       avgt       3   3.118 ± 0.604   ms/op
ClientGrpc.existUser                        avgt       3   3.007 ± 0.778   ms/op
ClientGrpc.getUser                          avgt       3   3.125 ± 0.438   ms/op
ClientGrpc.listUser                         avgt       3   3.875 ± 1.342   ms/op
ClientGrpc.createUser                     sample  303144   3.167 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.642           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.067           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.087           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.602           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.956           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.905           ms/op
ClientGrpc.existUser                      sample  322465   2.977 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.350           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.799           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.365           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.790           ms/op
ClientGrpc.getUser                        sample  305859   3.137 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.782           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.221           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.695           ms/op
ClientGrpc.listUser                       sample  239836   4.001 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.942           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.943           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.351           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.168           ms/op
