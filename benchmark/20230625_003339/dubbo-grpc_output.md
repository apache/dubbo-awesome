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
# Warmup Iteration   1: 3.644 ops/ms
# Warmup Iteration   2: 8.679 ops/ms
# Warmup Iteration   3: 9.955 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.408 ops/ms
Iteration   3: 10.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.484 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (10.408, 10.484, 10.523), stdev = 0.065
  CI (99.9%): [9.291, 11.676] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.847 ops/ms
# Warmup Iteration   2: 10.178 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 11.191 ops/ms
Iteration   2: 10.808 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.885 ±(99.9%) 5.042 ops/ms [Average]
  (min, avg, max) = (10.655, 10.885, 11.191), stdev = 0.276
  CI (99.9%): [5.843, 15.927] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.090 ops/ms
# Warmup Iteration   2: 9.864 ops/ms
# Warmup Iteration   3: 10.236 ops/ms
Iteration   1: 10.270 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 10.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.362 ±(99.9%) 1.655 ops/ms [Average]
  (min, avg, max) = (10.270, 10.362, 10.451), stdev = 0.091
  CI (99.9%): [8.707, 12.017] (assumes normal distribution)


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
# Warmup Iteration   1: 5.285 ops/ms
# Warmup Iteration   2: 7.553 ops/ms
# Warmup Iteration   3: 7.547 ops/ms
Iteration   1: 7.691 ops/ms
Iteration   2: 7.788 ops/ms
Iteration   3: 7.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.720 ±(99.9%) 1.074 ops/ms [Average]
  (min, avg, max) = (7.681, 7.720, 7.788), stdev = 0.059
  CI (99.9%): [6.646, 8.793] (assumes normal distribution)


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
# Warmup Iteration   1: 4.579 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.002 ms/op
Iteration   1: 3.118 ±(99.9%) 0.002 ms/op
Iteration   2: 3.029 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.082 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (3.029, 3.082, 3.118), stdev = 0.047
  CI (99.9%): [2.230, 3.934] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.002 ms/op
Iteration   1: 2.961 ±(99.9%) 0.002 ms/op
Iteration   2: 2.894 ±(99.9%) 0.003 ms/op
Iteration   3: 2.845 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 1.065 ms/op [Average]
  (min, avg, max) = (2.845, 2.900, 2.961), stdev = 0.058
  CI (99.9%): [1.835, 3.965] (assumes normal distribution)


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.004 ms/op
Iteration   1: 3.103 ±(99.9%) 0.002 ms/op
Iteration   2: 3.113 ±(99.9%) 0.009 ms/op
Iteration   3: 3.073 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.097 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (3.073, 3.097, 3.113), stdev = 0.021
  CI (99.9%): [2.716, 3.477] (assumes normal distribution)


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
# Warmup Iteration   1: 6.146 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.037 ms/op
Iteration   1: 4.115 ±(99.9%) 0.019 ms/op
Iteration   2: 4.130 ±(99.9%) 0.006 ms/op
Iteration   3: 4.155 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.133 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (4.115, 4.133, 4.155), stdev = 0.020
  CI (99.9%): [3.771, 4.496] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.534 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
Iteration   1: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  9.198 ms/op
                 createUser·p0.9999: 20.730 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.072 ms/op
                 createUser·p0.9999: 14.959 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 18.459 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308742
  mean =      3.108 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17645 
    [ 2.500,  5.000) = 289162 
    [ 5.000,  7.500) = 1512 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.081 ms/op
     p(99.9900) =     20.189 ms/op
     p(99.9990) =     21.097 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.718 ms/op
                 existUser·p0.9999: 13.121 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.960 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  6.873 ms/op
                 existUser·p0.9999: 13.815 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.213 ms/op
                 existUser·p0.9999: 19.813 ms/op
                 existUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321515
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 422 
    [ 1.250,  2.500) = 24698 
    [ 2.500,  3.750) = 286345 
    [ 3.750,  5.000) = 9172 
    [ 5.000,  6.250) = 380 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      6.873 ms/op
     p(99.9900) =     18.083 ms/op
     p(99.9990) =     19.956 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  7.266 ms/op
                 getUser·p0.9999: 13.522 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  7.414 ms/op
                 getUser·p0.9999: 25.386 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.786 ms/op
                 getUser·p0.9999: 17.924 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310535
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18110 
    [ 2.500,  5.000) = 290687 
    [ 5.000,  7.500) = 1432 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.475 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     25.949 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 5.275 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.012 ms/op
Iteration   1: 4.106 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  14.190 ms/op
                 listUser·p0.9999: 15.755 ms/op
                 listUser·p1.00:   16.089 ms/op

Iteration   2: 4.096 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  15.824 ms/op
                 listUser·p0.9999: 23.060 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 4.084 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 19.863 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234370
  mean =      4.095 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1435 
    [ 2.500,  5.000) = 208480 
    [ 5.000,  7.500) = 22668 
    [ 7.500, 10.000) = 1416 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     21.547 ms/op
     p(99.9990) =     24.303 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.484 ± 1.192  ops/ms
ClientGrpc.existUser                       thrpt       3  10.885 ± 5.042  ops/ms
ClientGrpc.getUser                         thrpt       3  10.362 ± 1.655  ops/ms
ClientGrpc.listUser                        thrpt       3   7.720 ± 1.074  ops/ms
ClientGrpc.createUser                       avgt       3   3.082 ± 0.852   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 1.065   ms/op
ClientGrpc.getUser                          avgt       3   3.097 ± 0.381   ms/op
ClientGrpc.listUser                         avgt       3   4.133 ± 0.362   ms/op
ClientGrpc.createUser                     sample  308742   3.108 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.739           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.081           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.189           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.234           ms/op
ClientGrpc.existUser                      sample  321515   2.983 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.752           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.873           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.083           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.988           ms/op
ClientGrpc.getUser                        sample  310535   3.091 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.572           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.475           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.445           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.985           ms/op
ClientGrpc.listUser                       sample  234370   4.095 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.049           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.234           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.547           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.543           ms/op
