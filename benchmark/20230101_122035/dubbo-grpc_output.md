# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
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
# Warmup Iteration   2: 9.553 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.261 ops/ms
Iteration   3: 10.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.236 ±(99.9%) 3.011 ops/ms [Average]
  (min, avg, max) = (10.060, 10.236, 10.387), stdev = 0.165
  CI (99.9%): [7.225, 13.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.057 ops/ms
# Warmup Iteration   2: 10.389 ops/ms
# Warmup Iteration   3: 11.162 ops/ms
Iteration   1: 11.108 ops/ms
Iteration   2: 11.288 ops/ms
Iteration   3: 10.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.119 ±(99.9%) 3.003 ops/ms [Average]
  (min, avg, max) = (10.960, 11.119, 11.288), stdev = 0.165
  CI (99.9%): [8.116, 14.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.583 ops/ms
# Warmup Iteration   2: 10.496 ops/ms
# Warmup Iteration   3: 10.869 ops/ms
Iteration   1: 10.494 ops/ms
Iteration   2: 10.718 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.637 ±(99.9%) 2.263 ops/ms [Average]
  (min, avg, max) = (10.494, 10.637, 10.718), stdev = 0.124
  CI (99.9%): [8.374, 12.900] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.306 ops/ms
# Warmup Iteration   2: 7.786 ops/ms
# Warmup Iteration   3: 8.133 ops/ms
Iteration   1: 7.852 ops/ms
Iteration   2: 7.788 ops/ms
Iteration   3: 7.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.872 ±(99.9%) 1.726 ops/ms [Average]
  (min, avg, max) = (7.788, 7.872, 7.974), stdev = 0.095
  CI (99.9%): [6.145, 9.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
Iteration   3: 3.130 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 1.300 ms/op [Average]
  (min, avg, max) = (2.991, 3.051, 3.130), stdev = 0.071
  CI (99.9%): [1.751, 4.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.003 ms/op
Iteration   1: 2.906 ±(99.9%) 0.003 ms/op
Iteration   2: 2.944 ±(99.9%) 0.002 ms/op
Iteration   3: 2.795 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.881 ±(99.9%) 1.412 ms/op [Average]
  (min, avg, max) = (2.795, 2.881, 2.944), stdev = 0.077
  CI (99.9%): [1.470, 4.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.502 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.003 ms/op
Iteration   1: 3.019 ±(99.9%) 0.003 ms/op
Iteration   2: 3.066 ±(99.9%) 0.002 ms/op
Iteration   3: 3.094 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.060 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.019, 3.060, 3.094), stdev = 0.038
  CI (99.9%): [2.371, 3.749] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.828 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.013 ms/op
Iteration   1: 4.002 ±(99.9%) 0.023 ms/op
Iteration   2: 3.897 ±(99.9%) 0.047 ms/op
Iteration   3: 3.862 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.921 ±(99.9%) 1.328 ms/op [Average]
  (min, avg, max) = (3.862, 3.921, 4.002), stdev = 0.073
  CI (99.9%): [2.592, 5.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.052 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.153 ms/op
                 createUser·p0.9999: 12.264 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.758 ms/op
                 createUser·p0.9999: 12.939 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  13.058 ms/op
                 createUser·p0.9999: 19.214 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312514
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 987 
    [ 1.250,  2.500) = 29718 
    [ 2.500,  3.750) = 252771 
    [ 3.750,  5.000) = 28200 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 132 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.951 ms/op
     p(99.9900) =     18.227 ms/op
     p(99.9990) =     19.681 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 2.879 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  5.929 ms/op
                 existUser·p0.9999: 17.330 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   2: 2.982 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  7.036 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  6.210 ms/op
                 existUser·p0.9999: 25.157 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324745
  mean =      2.956 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48237 
    [ 2.500,  5.000) = 275592 
    [ 5.000,  7.500) = 721 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.390 ms/op
     p(99.9900) =     22.464 ms/op
     p(99.9990) =     25.518 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.548 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.831 ms/op
                 getUser·p0.9999: 13.880 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  7.291 ms/op
                 getUser·p0.9999: 14.898 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.547 ms/op
                 getUser·p0.9999: 17.727 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319909
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2205 
    [ 1.250,  2.500) = 32125 
    [ 2.500,  3.750) = 269178 
    [ 3.750,  5.000) = 15487 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 216 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 76 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.843 ms/op
     p(99.9900) =     15.974 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.928 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.012 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  12.603 ms/op
                 listUser·p0.9999: 17.336 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   2: 3.923 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.276 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 3.953 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.912 ms/op
                 listUser·p0.999:  16.881 ms/op
                 listUser·p0.9999: 24.475 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241732
  mean =      3.968 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3759 
    [ 2.500,  5.000) = 211491 
    [ 5.000,  7.500) = 25331 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     24.674 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.236 ± 3.011  ops/ms
ClientGrpc.existUser                       thrpt       3  11.119 ± 3.003  ops/ms
ClientGrpc.getUser                         thrpt       3  10.637 ± 2.263  ops/ms
ClientGrpc.listUser                        thrpt       3   7.872 ± 1.726  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 1.300   ms/op
ClientGrpc.existUser                        avgt       3   2.881 ± 1.412   ms/op
ClientGrpc.getUser                          avgt       3   3.060 ± 0.689   ms/op
ClientGrpc.listUser                         avgt       3   3.921 ± 1.328   ms/op
ClientGrpc.createUser                     sample  312514   3.074 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.563           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.951           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.227           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.726           ms/op
ClientGrpc.existUser                      sample  324745   2.956 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.520           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.390           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.464           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.625           ms/op
ClientGrpc.getUser                        sample  319909   2.999 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.548           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.843           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  241732   3.968 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.938           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.921           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
