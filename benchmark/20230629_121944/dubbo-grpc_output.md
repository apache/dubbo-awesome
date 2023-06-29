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
# Warmup Iteration   1: 3.716 ops/ms
# Warmup Iteration   2: 8.858 ops/ms
# Warmup Iteration   3: 9.827 ops/ms
Iteration   1: 10.517 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.361 ±(99.9%) 2.525 ops/ms [Average]
  (min, avg, max) = (10.252, 10.361, 10.517), stdev = 0.138
  CI (99.9%): [7.836, 12.887] (assumes normal distribution)


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
# Warmup Iteration   1: 7.243 ops/ms
# Warmup Iteration   2: 10.309 ops/ms
# Warmup Iteration   3: 10.760 ops/ms
Iteration   1: 10.766 ops/ms
Iteration   2: 10.926 ops/ms
Iteration   3: 11.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.945 ±(99.9%) 3.457 ops/ms [Average]
  (min, avg, max) = (10.766, 10.945, 11.144), stdev = 0.190
  CI (99.9%): [7.488, 14.403] (assumes normal distribution)


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
# Warmup Iteration   1: 6.420 ops/ms
# Warmup Iteration   2: 9.935 ops/ms
# Warmup Iteration   3: 10.327 ops/ms
Iteration   1: 10.366 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.321 ±(99.9%) 0.759 ops/ms [Average]
  (min, avg, max) = (10.283, 10.321, 10.366), stdev = 0.042
  CI (99.9%): [9.562, 11.080] (assumes normal distribution)


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
# Warmup Iteration   1: 4.958 ops/ms
# Warmup Iteration   2: 7.492 ops/ms
# Warmup Iteration   3: 7.509 ops/ms
Iteration   1: 7.732 ops/ms
Iteration   2: 7.783 ops/ms
Iteration   3: 7.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.754 ±(99.9%) 0.475 ops/ms [Average]
  (min, avg, max) = (7.732, 7.754, 7.783), stdev = 0.026
  CI (99.9%): [7.279, 8.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.127 ±(99.9%) 0.003 ms/op
Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
Iteration   3: 3.077 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.116 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.077, 3.116, 3.145), stdev = 0.035
  CI (99.9%): [2.477, 3.756] (assumes normal distribution)


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
# Warmup Iteration   1: 4.275 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.002 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.002 ms/op
Iteration   3: 2.921 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.984 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (2.921, 2.984, 3.050), stdev = 0.065
  CI (99.9%): [1.802, 4.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.594 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.002 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.100 ±(99.9%) 0.004 ms/op
Iteration   3: 3.090 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.105 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.090, 3.105, 3.124), stdev = 0.018
  CI (99.9%): [2.783, 3.426] (assumes normal distribution)


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
# Warmup Iteration   1: 6.256 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.022 ms/op
Iteration   1: 4.098 ±(99.9%) 0.011 ms/op
Iteration   2: 4.076 ±(99.9%) 0.015 ms/op
Iteration   3: 4.111 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.095 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (4.076, 4.095, 4.111), stdev = 0.018
  CI (99.9%): [3.772, 4.418] (assumes normal distribution)


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  8.345 ms/op
                 createUser·p0.9999: 18.634 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.071 ms/op
                 createUser·p0.9999: 18.961 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 3.129 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  10.083 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309134
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17780 
    [ 2.500,  5.000) = 289632 
    [ 5.000,  7.500) = 1200 
    [ 7.500, 10.000) = 287 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.583 ms/op
     p(99.9900) =     28.347 ms/op
     p(99.9990) =     29.122 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 3.003 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.794 ms/op
                 existUser·p0.9999: 12.894 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 2.911 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.211 ms/op
                 existUser·p0.9999: 15.303 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   3: 2.925 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  10.724 ms/op
                 existUser·p0.9999: 18.219 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325813
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2404 
    [ 1.250,  2.500) = 32011 
    [ 2.500,  3.750) = 278991 
    [ 3.750,  5.000) = 11136 
    [ 5.000,  6.250) = 758 
    [ 6.250,  7.500) = 218 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.194 ms/op
     p(99.9900) =     16.911 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 4.573 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  9.138 ms/op
                 getUser·p0.9999: 20.994 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  9.611 ms/op
                 getUser·p0.9999: 21.251 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.121 ms/op
                 getUser·p0.9999: 25.395 ms/op
                 getUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306887
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12052 
    [ 2.500,  5.000) = 293473 
    [ 5.000,  7.500) = 964 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.787 ms/op
     p(99.9900) =     24.816 ms/op
     p(99.9990) =     25.688 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 5.978 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.012 ms/op
Iteration   1: 4.079 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.797 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 4.141 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.365 ms/op
                 listUser·p0.9999: 18.207 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 4.190 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  17.750 ms/op
                 listUser·p0.9999: 19.729 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232136
  mean =      4.136 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1126 
    [ 2.500,  5.000) = 204380 
    [ 5.000,  7.500) = 24788 
    [ 7.500, 10.000) = 1369 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     22.989 ms/op
     p(99.9990) =     24.667 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.361 ± 2.525  ops/ms
ClientGrpc.existUser                       thrpt       3  10.945 ± 3.457  ops/ms
ClientGrpc.getUser                         thrpt       3  10.321 ± 0.759  ops/ms
ClientGrpc.listUser                        thrpt       3   7.754 ± 0.475  ops/ms
ClientGrpc.createUser                       avgt       3   3.116 ± 0.639   ms/op
ClientGrpc.existUser                        avgt       3   2.984 ± 1.182   ms/op
ClientGrpc.getUser                          avgt       3   3.105 ± 0.322   ms/op
ClientGrpc.listUser                         avgt       3   4.095 ± 0.323   ms/op
ClientGrpc.createUser                     sample  309134   3.103 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.668           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.583           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.347           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.458           ms/op
ClientGrpc.existUser                      sample  325813   2.946 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.744           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.194           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.911           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.252           ms/op
ClientGrpc.getUser                        sample  306887   3.126 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.658           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.787           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.816           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.756           ms/op
ClientGrpc.listUser                       sample  232136   4.136 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.059           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.860           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.989           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
