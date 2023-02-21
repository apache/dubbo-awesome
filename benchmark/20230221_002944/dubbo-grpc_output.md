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
# Warmup Iteration   1: 4.145 ops/ms
# Warmup Iteration   2: 8.736 ops/ms
# Warmup Iteration   3: 9.880 ops/ms
Iteration   1: 9.831 ops/ms
Iteration   2: 10.026 ops/ms
Iteration   3: 9.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.907 ±(99.9%) 1.904 ops/ms [Average]
  (min, avg, max) = (9.831, 9.907, 10.026), stdev = 0.104
  CI (99.9%): [8.004, 11.811] (assumes normal distribution)


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
# Warmup Iteration   1: 7.607 ops/ms
# Warmup Iteration   2: 10.278 ops/ms
# Warmup Iteration   3: 10.447 ops/ms
Iteration   1: 10.958 ops/ms
Iteration   2: 10.672 ops/ms
Iteration   3: 10.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.753 ±(99.9%) 3.261 ops/ms [Average]
  (min, avg, max) = (10.630, 10.753, 10.958), stdev = 0.179
  CI (99.9%): [7.493, 14.014] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.191 ops/ms
# Warmup Iteration   2: 9.736 ops/ms
# Warmup Iteration   3: 10.146 ops/ms
Iteration   1: 10.242 ops/ms
Iteration   2: 10.191 ops/ms
Iteration   3: 10.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.198 ±(99.9%) 0.744 ops/ms [Average]
  (min, avg, max) = (10.162, 10.198, 10.242), stdev = 0.041
  CI (99.9%): [9.455, 10.942] (assumes normal distribution)


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
# Warmup Iteration   1: 5.952 ops/ms
# Warmup Iteration   2: 7.340 ops/ms
# Warmup Iteration   3: 7.984 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 8.024 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.079 ±(99.9%) 1.915 ops/ms [Average]
  (min, avg, max) = (8.013, 8.079, 8.200), stdev = 0.105
  CI (99.9%): [6.164, 9.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.002 ms/op
Iteration   1: 3.147 ±(99.9%) 0.007 ms/op
Iteration   2: 3.211 ±(99.9%) 0.002 ms/op
Iteration   3: 3.158 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.172 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (3.147, 3.172, 3.211), stdev = 0.034
  CI (99.9%): [2.545, 3.799] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.003 ms/op
Iteration   1: 2.982 ±(99.9%) 0.002 ms/op
Iteration   2: 3.089 ±(99.9%) 0.001 ms/op
Iteration   3: 3.040 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.037 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (2.982, 3.037, 3.089), stdev = 0.054
  CI (99.9%): [2.057, 4.017] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.202 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.003 ms/op
Iteration   1: 3.152 ±(99.9%) 0.002 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.167 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.142 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (3.107, 3.142, 3.167), stdev = 0.031
  CI (99.9%): [2.575, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 5.059 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.024 ms/op
Iteration   1: 4.003 ±(99.9%) 0.019 ms/op
Iteration   2: 3.982 ±(99.9%) 0.005 ms/op
Iteration   3: 4.027 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.004 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (3.982, 4.004, 4.027), stdev = 0.023
  CI (99.9%): [3.589, 4.419] (assumes normal distribution)


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
Iteration   1: 3.123 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.876 ms/op
                 createUser·p0.9999: 17.973 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 3.270 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.259 ms/op
                 createUser·p0.9999: 19.661 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  9.546 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302790
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20872 
    [ 2.500,  5.000) = 280799 
    [ 5.000,  7.500) = 614 
    [ 7.500, 10.000) = 274 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     21.173 ms/op
     p(99.9990) =     22.968 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.329 ms/op
                 existUser·p0.9999: 14.549 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   2: 2.994 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  11.324 ms/op
                 existUser·p0.9999: 14.696 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 2.942 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.153 ms/op
                 existUser·p0.9999: 17.957 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321122
  mean =      2.991 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2410 
    [ 1.250,  2.500) = 47067 
    [ 2.500,  3.750) = 244223 
    [ 3.750,  5.000) = 26412 
    [ 5.000,  6.250) = 484 
    [ 6.250,  7.500) = 195 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.576 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     18.198 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
Iteration   1: 3.186 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.935 ms/op
                 getUser·p0.9999: 13.121 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.769 ms/op
                 getUser·p0.9999: 15.267 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   3: 3.143 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.607 ms/op
                 getUser·p0.9999: 20.376 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304055
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24917 
    [ 2.500,  5.000) = 278022 
    [ 5.000,  7.500) = 772 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     19.667 ms/op
     p(99.9990) =     20.641 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 5.929 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.012 ms/op
Iteration   1: 4.077 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.033 ms/op
                 listUser·p0.999:  12.805 ms/op
                 listUser·p0.9999: 15.635 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   2: 4.154 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.550 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.856 ms/op
                 listUser·p0.9999: 26.804 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 4.110 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  20.002 ms/op
                 listUser·p0.9999: 25.081 ms/op
                 listUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233453
  mean =      4.113 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2331 
    [ 2.500,  5.000) = 201196 
    [ 5.000,  7.500) = 28471 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     27.023 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.907 ± 1.904  ops/ms
ClientGrpc.existUser                       thrpt       3  10.753 ± 3.261  ops/ms
ClientGrpc.getUser                         thrpt       3  10.198 ± 0.744  ops/ms
ClientGrpc.listUser                        thrpt       3   8.079 ± 1.915  ops/ms
ClientGrpc.createUser                       avgt       3   3.172 ± 0.627   ms/op
ClientGrpc.existUser                        avgt       3   3.037 ± 0.980   ms/op
ClientGrpc.getUser                          avgt       3   3.142 ± 0.567   ms/op
ClientGrpc.listUser                         avgt       3   4.004 ± 0.415   ms/op
ClientGrpc.createUser                     sample  302790   3.171 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.703           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.913           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.173           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.101           ms/op
ClientGrpc.existUser                      sample  321122   2.991 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.714           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.576           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.465           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.317           ms/op
ClientGrpc.getUser                        sample  304055   3.155 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.714           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.030           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.667           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  233453   4.113 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.550           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.904           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
