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
# Warmup Iteration   1: 4.150 ops/ms
# Warmup Iteration   2: 8.967 ops/ms
# Warmup Iteration   3: 10.016 ops/ms
Iteration   1: 10.282 ops/ms
Iteration   2: 10.279 ops/ms
Iteration   3: 10.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.317 ±(99.9%) 1.144 ops/ms [Average]
  (min, avg, max) = (10.279, 10.317, 10.389), stdev = 0.063
  CI (99.9%): [9.173, 11.461] (assumes normal distribution)


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
# Warmup Iteration   1: 7.540 ops/ms
# Warmup Iteration   2: 10.276 ops/ms
# Warmup Iteration   3: 10.743 ops/ms
Iteration   1: 10.743 ops/ms
Iteration   2: 10.867 ops/ms
Iteration   3: 10.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.727 ±(99.9%) 2.711 ops/ms [Average]
  (min, avg, max) = (10.571, 10.727, 10.867), stdev = 0.149
  CI (99.9%): [8.016, 13.438] (assumes normal distribution)


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
# Warmup Iteration   1: 6.872 ops/ms
# Warmup Iteration   2: 10.018 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 9.958 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 9.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.909 ±(99.9%) 0.810 ops/ms [Average]
  (min, avg, max) = (9.871, 9.909, 9.958), stdev = 0.044
  CI (99.9%): [9.099, 10.718] (assumes normal distribution)


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
# Warmup Iteration   1: 6.718 ops/ms
# Warmup Iteration   2: 7.683 ops/ms
# Warmup Iteration   3: 8.134 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.178 ops/ms
Iteration   3: 8.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.134 ±(99.9%) 2.120 ops/ms [Average]
  (min, avg, max) = (8.003, 8.134, 8.222), stdev = 0.116
  CI (99.9%): [6.014, 10.254] (assumes normal distribution)


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.002 ms/op
Iteration   1: 3.177 ±(99.9%) 0.010 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.172 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.152 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (3.107, 3.152, 3.177), stdev = 0.039
  CI (99.9%): [2.438, 3.867] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.001 ms/op
Iteration   2: 3.089 ±(99.9%) 0.001 ms/op
Iteration   3: 3.042 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.051 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.022, 3.051, 3.089), stdev = 0.034
  CI (99.9%): [2.426, 3.676] (assumes normal distribution)


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.002 ms/op
Iteration   2: 3.137 ±(99.9%) 0.002 ms/op
Iteration   3: 3.116 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.121 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (3.109, 3.121, 3.137), stdev = 0.014
  CI (99.9%): [2.860, 3.382] (assumes normal distribution)


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.031 ms/op
Iteration   1: 3.911 ±(99.9%) 0.009 ms/op
Iteration   2: 3.886 ±(99.9%) 0.020 ms/op
Iteration   3: 3.893 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.896 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.886, 3.896, 3.911), stdev = 0.013
  CI (99.9%): [3.661, 4.132] (assumes normal distribution)


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
Iteration   1: 3.146 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.140 ms/op
                 createUser·p0.9999: 11.401 ms/op
                 createUser·p1.00:   11.534 ms/op

Iteration   2: 3.137 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.536 ms/op
                 createUser·p0.999:  11.825 ms/op
                 createUser·p0.9999: 16.122 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   3: 3.170 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.285 ms/op
                 createUser·p0.999:  9.971 ms/op
                 createUser·p0.9999: 18.514 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304590
  mean =      3.151 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6373 
    [ 2.500,  5.000) = 296704 
    [ 5.000,  7.500) = 1083 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =     10.043 ms/op
     p(99.9900) =     18.025 ms/op
     p(99.9990) =     18.675 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.844 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 2.972 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  8.366 ms/op
                 existUser·p0.9999: 13.144 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  10.995 ms/op
                 existUser·p0.9999: 13.012 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  9.191 ms/op
                 existUser·p0.9999: 14.594 ms/op
                 existUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317783
  mean =      3.020 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1515 
    [ 1.250,  2.500) = 17697 
    [ 2.500,  3.750) = 280710 
    [ 3.750,  5.000) = 16071 
    [ 5.000,  6.250) = 714 
    [ 6.250,  7.500) = 487 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     15.255 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.746 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.006 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  7.832 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.021 ms/op
                 getUser·p0.9999: 19.395 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.722 ms/op
                 getUser·p0.9999: 20.803 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304629
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9949 
    [ 2.500,  5.000) = 292787 
    [ 5.000,  7.500) = 1629 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.196 ms/op
     p(99.9900) =     20.563 ms/op
     p(99.9990) =     20.937 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.716 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.009 ms/op
Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.957 ms/op
                 listUser·p0.9999: 16.164 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   2: 3.945 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 15.751 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   3: 3.921 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.561 ms/op
                 listUser·p0.9999: 16.693 ms/op
                 listUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245803
  mean =      3.903 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 2747 
    [ 2.500,  3.750) = 103072 
    [ 3.750,  5.000) = 125684 
    [ 5.000,  6.250) = 8588 
    [ 6.250,  7.500) = 4650 
    [ 7.500,  8.750) = 303 
    [ 8.750, 10.000) = 188 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 156 
    [13.750, 15.000) = 108 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     16.454 ms/op
     p(99.9990) =     17.060 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.317 ± 1.144  ops/ms
ClientGrpc.existUser                       thrpt       3  10.727 ± 2.711  ops/ms
ClientGrpc.getUser                         thrpt       3   9.909 ± 0.810  ops/ms
ClientGrpc.listUser                        thrpt       3   8.134 ± 2.120  ops/ms
ClientGrpc.createUser                       avgt       3   3.152 ± 0.715   ms/op
ClientGrpc.existUser                        avgt       3   3.051 ± 0.625   ms/op
ClientGrpc.getUser                          avgt       3   3.121 ± 0.261   ms/op
ClientGrpc.listUser                         avgt       3   3.896 ± 0.235   ms/op
ClientGrpc.createUser                     sample  304590   3.151 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.780           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.043           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.025           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.054           ms/op
ClientGrpc.existUser                      sample  317783   3.020 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.540           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.470           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.255           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.352           ms/op
ClientGrpc.getUser                        sample  304629   3.149 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.678           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.196           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.563           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  245803   3.903 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.848           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.358           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.484           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.454           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.105           ms/op
