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
# Warmup Iteration   1: 4.911 ops/ms
# Warmup Iteration   2: 9.497 ops/ms
# Warmup Iteration   3: 10.369 ops/ms
Iteration   1: 10.181 ops/ms
Iteration   2: 10.439 ops/ms
Iteration   3: 10.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.260 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (10.160, 10.260, 10.439), stdev = 0.155
  CI (99.9%): [7.423, 13.097] (assumes normal distribution)


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
# Warmup Iteration   1: 7.882 ops/ms
# Warmup Iteration   2: 10.552 ops/ms
# Warmup Iteration   3: 10.844 ops/ms
Iteration   1: 10.927 ops/ms
Iteration   2: 11.048 ops/ms
Iteration   3: 11.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.072 ±(99.9%) 2.900 ops/ms [Average]
  (min, avg, max) = (10.927, 11.072, 11.242), stdev = 0.159
  CI (99.9%): [8.172, 13.973] (assumes normal distribution)


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
# Warmup Iteration   1: 7.877 ops/ms
# Warmup Iteration   2: 10.347 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.402 ops/ms
Iteration   2: 10.441 ops/ms
Iteration   3: 10.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.448 ±(99.9%) 0.900 ops/ms [Average]
  (min, avg, max) = (10.402, 10.448, 10.500), stdev = 0.049
  CI (99.9%): [9.548, 11.348] (assumes normal distribution)


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
# Warmup Iteration   1: 5.819 ops/ms
# Warmup Iteration   2: 7.685 ops/ms
# Warmup Iteration   3: 7.842 ops/ms
Iteration   1: 8.016 ops/ms
Iteration   2: 8.510 ops/ms
Iteration   3: 8.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.196 ±(99.9%) 4.973 ops/ms [Average]
  (min, avg, max) = (8.016, 8.196, 8.510), stdev = 0.273
  CI (99.9%): [3.223, 13.169] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.008 ms/op
Iteration   2: 3.098 ±(99.9%) 0.001 ms/op
Iteration   3: 3.175 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.111 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (3.059, 3.111, 3.175), stdev = 0.059
  CI (99.9%): [2.030, 4.192] (assumes normal distribution)


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 2.948 ±(99.9%) 0.002 ms/op
Iteration   3: 2.973 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.971 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (2.948, 2.971, 2.991), stdev = 0.022
  CI (99.9%): [2.577, 3.364] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.003 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.044 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (3.002, 3.044, 3.074), stdev = 0.037
  CI (99.9%): [2.366, 3.722] (assumes normal distribution)


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
# Warmup Iteration   1: 5.258 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.055 ms/op
Iteration   1: 3.876 ±(99.9%) 0.008 ms/op
Iteration   2: 3.824 ±(99.9%) 0.005 ms/op
Iteration   3: 3.923 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.874 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (3.824, 3.874, 3.923), stdev = 0.050
  CI (99.9%): [2.970, 4.778] (assumes normal distribution)


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.354 ms/op
                 createUser·p0.9999: 12.170 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.469 ms/op
                 createUser·p0.9999: 12.738 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  14.411 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309808
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25328 
    [ 2.500,  5.000) = 283090 
    [ 5.000,  7.500) = 911 
    [ 7.500, 10.000) = 186 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     22.087 ms/op
     p(99.9990) =     22.279 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.863 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.275 ms/op
                 existUser·p0.9999: 17.736 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.151 ms/op
                 existUser·p0.999:  5.399 ms/op
                 existUser·p0.9999: 14.864 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  5.784 ms/op
                 existUser·p0.9999: 16.298 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323666
  mean =      2.964 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1909 
    [ 1.250,  2.500) = 45334 
    [ 2.500,  3.750) = 257691 
    [ 3.750,  5.000) = 18034 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      5.669 ms/op
     p(99.9900) =     17.143 ms/op
     p(99.9990) =     17.884 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.007 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.300 ms/op
                 getUser·p0.9999: 23.167 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.482 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.229 ms/op
                 getUser·p0.999:  7.954 ms/op
                 getUser·p0.9999: 18.055 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   3: 3.051 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.971 ms/op
                 getUser·p0.9999: 30.359 ms/op
                 getUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315448
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26542 
    [ 2.500,  5.000) = 287913 
    [ 5.000,  7.500) = 669 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.771 ms/op
     p(99.9900) =     29.816 ms/op
     p(99.9990) =     30.600 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.010 ms/op
Iteration   1: 4.087 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.428 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  11.428 ms/op
                 listUser·p0.9999: 18.624 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 16.812 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.893 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.607 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.876 ms/op
                 listUser·p0.9999: 25.340 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240268
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3577 
    [ 2.500,  5.000) = 206928 
    [ 5.000,  7.500) = 28526 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     23.461 ms/op
     p(99.9990) =     26.272 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.260 ± 2.837  ops/ms
ClientGrpc.existUser                       thrpt       3  11.072 ± 2.900  ops/ms
ClientGrpc.getUser                         thrpt       3  10.448 ± 0.900  ops/ms
ClientGrpc.listUser                        thrpt       3   8.196 ± 4.973  ops/ms
ClientGrpc.createUser                       avgt       3   3.111 ± 1.081   ms/op
ClientGrpc.existUser                        avgt       3   2.971 ± 0.394   ms/op
ClientGrpc.getUser                          avgt       3   3.044 ± 0.678   ms/op
ClientGrpc.listUser                         avgt       3   3.874 ± 0.904   ms/op
ClientGrpc.createUser                     sample  309808   3.097 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.550           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.732           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.087           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.348           ms/op
ClientGrpc.existUser                      sample  323666   2.964 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.535           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.143           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.891           ms/op
ClientGrpc.getUser                        sample  315448   3.044 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.482           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.771           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.816           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.671           ms/op
ClientGrpc.listUser                       sample  240268   3.995 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.428           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.156           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.461           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
