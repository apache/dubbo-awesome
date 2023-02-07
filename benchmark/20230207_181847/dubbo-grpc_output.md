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
# Warmup Iteration   1: 4.218 ops/ms
# Warmup Iteration   2: 8.623 ops/ms
# Warmup Iteration   3: 9.644 ops/ms
Iteration   1: 9.831 ops/ms
Iteration   2: 9.425 ops/ms
Iteration   3: 9.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.672 ±(99.9%) 3.951 ops/ms [Average]
  (min, avg, max) = (9.425, 9.672, 9.831), stdev = 0.217
  CI (99.9%): [5.720, 13.623] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.826 ops/ms
# Warmup Iteration   2: 9.349 ops/ms
# Warmup Iteration   3: 9.984 ops/ms
Iteration   1: 10.059 ops/ms
Iteration   2: 10.220 ops/ms
Iteration   3: 10.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.154 ±(99.9%) 1.535 ops/ms [Average]
  (min, avg, max) = (10.059, 10.154, 10.220), stdev = 0.084
  CI (99.9%): [8.619, 11.689] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.256 ops/ms
# Warmup Iteration   2: 9.772 ops/ms
# Warmup Iteration   3: 9.930 ops/ms
Iteration   1: 9.926 ops/ms
Iteration   2: 9.727 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.882 ±(99.9%) 2.533 ops/ms [Average]
  (min, avg, max) = (9.727, 9.882, 9.994), stdev = 0.139
  CI (99.9%): [7.349, 12.415] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.287 ops/ms
# Warmup Iteration   2: 6.850 ops/ms
# Warmup Iteration   3: 7.527 ops/ms
Iteration   1: 7.372 ops/ms
Iteration   2: 7.513 ops/ms
Iteration   3: 7.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.571 ±(99.9%) 4.270 ops/ms [Average]
  (min, avg, max) = (7.372, 7.571, 7.829), stdev = 0.234
  CI (99.9%): [3.301, 11.842] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.011 ms/op
Iteration   1: 3.303 ±(99.9%) 0.003 ms/op
Iteration   2: 3.303 ±(99.9%) 0.002 ms/op
Iteration   3: 3.339 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.315 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (3.303, 3.315, 3.339), stdev = 0.021
  CI (99.9%): [2.935, 3.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.002 ms/op
Iteration   1: 3.050 ±(99.9%) 0.003 ms/op
Iteration   2: 3.099 ±(99.9%) 0.001 ms/op
Iteration   3: 3.137 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.095 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.050, 3.095, 3.137), stdev = 0.044
  CI (99.9%): [2.297, 3.893] (assumes normal distribution)


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
# Warmup Iteration   1: 4.474 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.003 ms/op
Iteration   1: 3.175 ±(99.9%) 0.002 ms/op
Iteration   2: 3.205 ±(99.9%) 0.002 ms/op
Iteration   3: 3.231 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.204 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.175, 3.204, 3.231), stdev = 0.028
  CI (99.9%): [2.693, 3.714] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.040 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.011 ms/op
Iteration   1: 4.179 ±(99.9%) 0.010 ms/op
Iteration   2: 4.057 ±(99.9%) 0.006 ms/op
Iteration   3: 4.084 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.107 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (4.057, 4.107, 4.179), stdev = 0.064
  CI (99.9%): [2.943, 5.270] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.705 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.008 ms/op
Iteration   1: 3.199 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.866 ms/op
                 createUser·p0.999:  9.930 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 3.158 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.914 ms/op
                 createUser·p0.9999: 20.021 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   3: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  13.779 ms/op
                 createUser·p0.9999: 22.742 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301269
  mean =      3.189 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12491 
    [ 2.500,  5.000) = 286943 
    [ 5.000,  7.500) = 1332 
    [ 7.500, 10.000) = 209 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      9.387 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     23.035 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.441 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.006 ms/op
Iteration   1: 3.164 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  5.428 ms/op
                 existUser·p0.9999: 13.528 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.227 ms/op
                 existUser·p0.9999: 15.133 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.350 ms/op
                 existUser·p0.9999: 16.187 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308224
  mean =      3.116 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 506 
    [ 1.250,  2.500) = 26777 
    [ 2.500,  3.750) = 247434 
    [ 3.750,  5.000) = 32701 
    [ 5.000,  6.250) = 413 
    [ 6.250,  7.500) = 172 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.902 ms/op
     p(99.9900) =     15.341 ms/op
     p(99.9990) =     17.820 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
Iteration   1: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.964 ms/op
                 getUser·p0.9999: 18.406 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.069 ms/op
                 getUser·p0.9999: 19.038 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  9.831 ms/op
                 getUser·p0.9999: 21.929 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300725
  mean =      3.193 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14519 
    [ 2.500,  5.000) = 285027 
    [ 5.000,  7.500) = 765 
    [ 7.500, 10.000) = 193 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.622 ms/op
     p(99.9900) =     20.052 ms/op
     p(99.9990) =     22.478 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.768 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.362 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.012 ms/op
Iteration   1: 4.292 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  13.099 ms/op
                 listUser·p0.9999: 16.155 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   2: 4.157 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  20.485 ms/op
                 listUser·p0.9999: 26.051 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   3: 4.262 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 226530
  mean =      4.236 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1188 
    [ 2.500,  5.000) = 192631 
    [ 5.000,  7.500) = 30631 
    [ 7.500, 10.000) = 1596 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     16.416 ms/op
     p(99.9900) =     25.429 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.672 ± 3.951  ops/ms
ClientGrpc.existUser                       thrpt       3  10.154 ± 1.535  ops/ms
ClientGrpc.getUser                         thrpt       3   9.882 ± 2.533  ops/ms
ClientGrpc.listUser                        thrpt       3   7.571 ± 4.270  ops/ms
ClientGrpc.createUser                       avgt       3   3.315 ± 0.379   ms/op
ClientGrpc.existUser                        avgt       3   3.095 ± 0.798   ms/op
ClientGrpc.getUser                          avgt       3   3.204 ± 0.510   ms/op
ClientGrpc.listUser                         avgt       3   4.107 ± 1.164   ms/op
ClientGrpc.createUser                     sample  301269   3.189 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.819           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.166           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.387           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.922           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.200           ms/op
ClientGrpc.existUser                      sample  308224   3.116 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.653           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.084           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.902           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.341           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.055           ms/op
ClientGrpc.getUser                        sample  300725   3.193 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.670           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.622           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.052           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.101           ms/op
ClientGrpc.listUser                       sample  226530   4.236 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.955           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.039           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.422           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.416           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.429           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.313           ms/op
