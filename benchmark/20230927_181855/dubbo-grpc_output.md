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
# Warmup Iteration   1: 3.705 ops/ms
# Warmup Iteration   2: 8.243 ops/ms
# Warmup Iteration   3: 9.570 ops/ms
Iteration   1: 9.907 ops/ms
Iteration   2: 10.064 ops/ms
Iteration   3: 10.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.048 ±(99.9%) 2.445 ops/ms [Average]
  (min, avg, max) = (9.907, 10.048, 10.174), stdev = 0.134
  CI (99.9%): [7.603, 12.493] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.695 ops/ms
# Warmup Iteration   2: 10.085 ops/ms
# Warmup Iteration   3: 10.624 ops/ms
Iteration   1: 10.373 ops/ms
Iteration   2: 10.611 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.494 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (10.373, 10.494, 10.611), stdev = 0.119
  CI (99.9%): [8.322, 12.665] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.241 ops/ms
# Warmup Iteration   2: 9.664 ops/ms
# Warmup Iteration   3: 9.977 ops/ms
Iteration   1: 9.948 ops/ms
Iteration   2: 10.066 ops/ms
Iteration   3: 9.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.987 ±(99.9%) 1.238 ops/ms [Average]
  (min, avg, max) = (9.948, 9.987, 10.066), stdev = 0.068
  CI (99.9%): [8.749, 11.226] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.913 ops/ms
# Warmup Iteration   2: 7.703 ops/ms
# Warmup Iteration   3: 7.910 ops/ms
Iteration   1: 7.829 ops/ms
Iteration   2: 7.942 ops/ms
Iteration   3: 7.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.891 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (7.829, 7.891, 7.942), stdev = 0.058
  CI (99.9%): [6.840, 8.941] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.781 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.003 ms/op
Iteration   1: 3.203 ±(99.9%) 0.009 ms/op
Iteration   2: 3.195 ±(99.9%) 0.003 ms/op
Iteration   3: 3.224 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.207 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (3.195, 3.207, 3.224), stdev = 0.015
  CI (99.9%): [2.937, 3.478] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.194 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.005 ms/op
Iteration   1: 2.874 ±(99.9%) 0.004 ms/op
Iteration   2: 3.056 ±(99.9%) 0.004 ms/op
Iteration   3: 3.022 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.984 ±(99.9%) 1.762 ms/op [Average]
  (min, avg, max) = (2.874, 2.984, 3.056), stdev = 0.097
  CI (99.9%): [1.222, 4.746] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.601 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.003 ms/op
Iteration   1: 3.191 ±(99.9%) 0.004 ms/op
Iteration   2: 3.166 ±(99.9%) 0.004 ms/op
Iteration   3: 3.134 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.164 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.134, 3.164, 3.191), stdev = 0.029
  CI (99.9%): [2.641, 3.686] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.617 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.016 ms/op
Iteration   1: 4.071 ±(99.9%) 0.022 ms/op
Iteration   2: 3.930 ±(99.9%) 0.013 ms/op
Iteration   3: 3.839 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.947 ±(99.9%) 2.136 ms/op [Average]
  (min, avg, max) = (3.839, 3.947, 4.071), stdev = 0.117
  CI (99.9%): [1.810, 6.083] (assumes normal distribution)


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
# Warmup Iteration   1: 4.333 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  11.179 ms/op
                 createUser·p0.9999: 16.572 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.154 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.534 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  7.494 ms/op
                 createUser·p0.9999: 19.694 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   3: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  15.429 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303335
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9101 
    [ 2.500,  5.000) = 292124 
    [ 5.000,  7.500) = 1611 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     21.354 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  8.909 ms/op
                 existUser·p0.9999: 15.745 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  6.908 ms/op
                 existUser·p0.9999: 16.503 ms/op
                 existUser·p1.00:   17.007 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 17.545 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317818
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 574 
    [ 1.250,  2.500) = 23752 
    [ 2.500,  3.750) = 277630 
    [ 3.750,  5.000) = 13680 
    [ 5.000,  6.250) = 1361 
    [ 6.250,  7.500) = 398 
    [ 7.500,  8.750) = 158 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 72 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.290 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     19.551 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.667 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.007 ms/op
Iteration   1: 3.183 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  13.861 ms/op
                 getUser·p0.9999: 17.561 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  9.181 ms/op
                 getUser·p0.9999: 24.247 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  10.567 ms/op
                 getUser·p0.9999: 21.299 ms/op
                 getUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301215
  mean =      3.185 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9168 
    [ 2.500,  5.000) = 289656 
    [ 5.000,  7.500) = 1669 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     11.305 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 5.965 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.011 ms/op
Iteration   1: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 31.135 ms/op
                 listUser·p1.00:   31.785 ms/op

Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.683 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 17.670 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 4.076 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.284 ms/op
                 listUser·p0.999:  18.604 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236693
  mean =      4.055 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1738 
    [ 2.500,  5.000) = 216742 
    [ 5.000,  7.500) = 15976 
    [ 7.500, 10.000) = 1380 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     16.034 ms/op
     p(99.9900) =     24.863 ms/op
     p(99.9990) =     31.651 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.048 ± 2.445  ops/ms
ClientGrpc.existUser                       thrpt       3  10.494 ± 2.171  ops/ms
ClientGrpc.getUser                         thrpt       3   9.987 ± 1.238  ops/ms
ClientGrpc.listUser                        thrpt       3   7.891 ± 1.050  ops/ms
ClientGrpc.createUser                       avgt       3   3.207 ± 0.270   ms/op
ClientGrpc.existUser                        avgt       3   2.984 ± 1.762   ms/op
ClientGrpc.getUser                          avgt       3   3.164 ± 0.523   ms/op
ClientGrpc.listUser                         avgt       3   3.947 ± 2.136   ms/op
ClientGrpc.createUser                     sample  303335   3.165 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.534           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.965           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.190           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.354           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  317818   3.018 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.835           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.290           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.007           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  301215   3.185 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.648           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.305           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.299           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.871           ms/op
ClientGrpc.listUser                       sample  236693   4.055 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.961           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.686           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.034           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.863           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.785           ms/op
