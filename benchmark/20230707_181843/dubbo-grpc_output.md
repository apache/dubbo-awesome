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
# Warmup Iteration   1: 3.421 ops/ms
# Warmup Iteration   2: 7.876 ops/ms
# Warmup Iteration   3: 9.334 ops/ms
Iteration   1: 9.994 ops/ms
Iteration   2: 9.168 ops/ms
Iteration   3: 8.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.370 ±(99.9%) 10.050 ops/ms [Average]
  (min, avg, max) = (8.949, 9.370, 9.994), stdev = 0.551
  CI (99.9%): [≈ 0, 19.420] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.526 ops/ms
# Warmup Iteration   2: 9.089 ops/ms
# Warmup Iteration   3: 10.222 ops/ms
Iteration   1: 9.156 ops/ms
Iteration   2: 9.754 ops/ms
Iteration   3: 9.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.555 ±(99.9%) 6.313 ops/ms [Average]
  (min, avg, max) = (9.156, 9.555, 9.755), stdev = 0.346
  CI (99.9%): [3.242, 15.868] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.559 ops/ms
# Warmup Iteration   2: 9.103 ops/ms
# Warmup Iteration   3: 9.734 ops/ms
Iteration   1: 9.955 ops/ms
Iteration   2: 9.780 ops/ms
Iteration   3: 9.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.808 ±(99.9%) 2.474 ops/ms [Average]
  (min, avg, max) = (9.688, 9.808, 9.955), stdev = 0.136
  CI (99.9%): [7.334, 12.282] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ops/ms
# Warmup Iteration   2: 6.978 ops/ms
# Warmup Iteration   3: 7.608 ops/ms
Iteration   1: 7.249 ops/ms
Iteration   2: 7.101 ops/ms
Iteration   3: 6.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.082 ±(99.9%) 3.228 ops/ms [Average]
  (min, avg, max) = (6.897, 7.082, 7.249), stdev = 0.177
  CI (99.9%): [3.854, 10.310] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.559 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.438 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.012 ms/op
Iteration   1: 3.125 ±(99.9%) 0.002 ms/op
Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.129 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (3.110, 3.129, 3.151), stdev = 0.021
  CI (99.9%): [2.748, 3.509] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.155 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 3.069 ±(99.9%) 0.003 ms/op
Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
Iteration   3: 3.077 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.077 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (3.069, 3.077, 3.084), stdev = 0.007
  CI (99.9%): [2.941, 3.213] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.411 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.002 ms/op
Iteration   1: 3.316 ±(99.9%) 0.003 ms/op
Iteration   2: 3.214 ±(99.9%) 0.004 ms/op
Iteration   3: 3.217 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.249 ±(99.9%) 1.059 ms/op [Average]
  (min, avg, max) = (3.214, 3.249, 3.316), stdev = 0.058
  CI (99.9%): [2.190, 4.309] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.477 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.418 ±(99.9%) 0.031 ms/op
Iteration   1: 4.337 ±(99.9%) 0.012 ms/op
Iteration   2: 4.242 ±(99.9%) 0.022 ms/op
Iteration   3: 4.306 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.295 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (4.242, 4.295, 4.337), stdev = 0.048
  CI (99.9%): [3.411, 5.179] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.864 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
Iteration   1: 3.328 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.318 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.995 ms/op
                 createUser·p0.999:  11.780 ms/op
                 createUser·p0.9999: 20.087 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  10.563 ms/op
                 createUser·p0.9999: 15.942 ms/op
                 createUser·p1.00:   16.155 ms/op

Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.101 ms/op
                 createUser·p0.999:  12.882 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294099
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13797 
    [ 2.500,  5.000) = 275255 
    [ 5.000,  7.500) = 3668 
    [ 7.500, 10.000) = 954 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     12.170 ms/op
     p(99.9900) =     19.746 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 2.946 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  6.887 ms/op
                 existUser·p0.9999: 13.224 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  8.456 ms/op
                 existUser·p0.9999: 14.668 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   3: 3.069 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  11.239 ms/op
                 existUser·p0.9999: 28.672 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321522
  mean =      2.987 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26737 
    [ 2.500,  5.000) = 290192 
    [ 5.000,  7.500) = 3511 
    [ 7.500, 10.000) = 776 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =      9.805 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.276 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.013 ms/op
Iteration   1: 3.229 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  12.107 ms/op
                 getUser·p0.9999: 15.683 ms/op
                 getUser·p1.00:   16.253 ms/op

Iteration   2: 3.393 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  15.809 ms/op
                 getUser·p0.9999: 27.722 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 3.408 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   8.202 ms/op
                 getUser·p0.999:  11.010 ms/op
                 getUser·p0.9999: 28.594 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 287215
  mean =      3.341 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13484 
    [ 2.500,  5.000) = 257301 
    [ 5.000,  7.500) = 12026 
    [ 7.500, 10.000) = 3828 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     28.091 ms/op
     p(99.9990) =     28.906 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 6.896 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.587 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.014 ms/op
Iteration   1: 4.311 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  14.723 ms/op
                 listUser·p0.9999: 18.295 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 4.307 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  17.334 ms/op
                 listUser·p0.9999: 19.633 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 4.437 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   5.960 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  20.455 ms/op
                 listUser·p0.9999: 36.766 ms/op
                 listUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 220586
  mean =      4.351 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1356 
    [ 2.500,  5.000) = 181722 
    [ 5.000,  7.500) = 33763 
    [ 7.500, 10.000) = 2929 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 162 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     17.675 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     37.302 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3   9.370 ± 10.050  ops/ms
ClientGrpc.existUser                       thrpt       3   9.555 ±  6.313  ops/ms
ClientGrpc.getUser                         thrpt       3   9.808 ±  2.474  ops/ms
ClientGrpc.listUser                        thrpt       3   7.082 ±  3.228  ops/ms
ClientGrpc.createUser                       avgt       3   3.129 ±  0.381   ms/op
ClientGrpc.existUser                        avgt       3   3.077 ±  0.136   ms/op
ClientGrpc.getUser                          avgt       3   3.249 ±  1.059   ms/op
ClientGrpc.listUser                         avgt       3   4.295 ±  0.884   ms/op
ClientGrpc.createUser                     sample  294099   3.263 ±  0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.318            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.174            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.940            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.268            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.874            ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.170            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.746            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.349            ms/op
ClientGrpc.existUser                      sample  321522   2.987 ±  0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.631            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.882            ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.805            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.640            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.934            ms/op
ClientGrpc.getUser                        sample  287215   3.341 ±  0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.561            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.998            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.366            ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.979            ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.009            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.091            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.065            ms/op
ClientGrpc.listUser                       sample  220586   4.351 ±  0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.802            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.092            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.644            ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.398            ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.118            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.675            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.931            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.356            ms/op
