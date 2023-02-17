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
# Warmup Iteration   1: 4.578 ops/ms
# Warmup Iteration   2: 9.062 ops/ms
# Warmup Iteration   3: 10.041 ops/ms
Iteration   1: 10.122 ops/ms
Iteration   2: 10.098 ops/ms
Iteration   3: 10.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.146 ±(99.9%) 1.159 ops/ms [Average]
  (min, avg, max) = (10.098, 10.146, 10.218), stdev = 0.064
  CI (99.9%): [8.987, 11.305] (assumes normal distribution)


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
# Warmup Iteration   1: 7.885 ops/ms
# Warmup Iteration   2: 10.484 ops/ms
# Warmup Iteration   3: 10.512 ops/ms
Iteration   1: 10.761 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.741 ±(99.9%) 0.381 ops/ms [Average]
  (min, avg, max) = (10.719, 10.741, 10.761), stdev = 0.021
  CI (99.9%): [10.359, 11.122] (assumes normal distribution)


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
# Warmup Iteration   1: 8.612 ops/ms
# Warmup Iteration   2: 9.737 ops/ms
# Warmup Iteration   3: 10.443 ops/ms
Iteration   1: 10.372 ops/ms
Iteration   2: 10.237 ops/ms
Iteration   3: 10.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.250 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (10.143, 10.250, 10.372), stdev = 0.115
  CI (99.9%): [8.150, 12.350] (assumes normal distribution)


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
# Warmup Iteration   1: 6.600 ops/ms
# Warmup Iteration   2: 7.437 ops/ms
# Warmup Iteration   3: 7.628 ops/ms
Iteration   1: 7.878 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 7.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.876 ±(99.9%) 0.613 ops/ms [Average]
  (min, avg, max) = (7.842, 7.876, 7.909), stdev = 0.034
  CI (99.9%): [7.263, 8.489] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.160 ±(99.9%) 0.004 ms/op
Iteration   2: 3.181 ±(99.9%) 0.001 ms/op
Iteration   3: 3.193 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.178 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (3.160, 3.178, 3.193), stdev = 0.017
  CI (99.9%): [2.874, 3.481] (assumes normal distribution)


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
# Warmup Iteration   1: 3.556 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 2.996 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.992 ±(99.9%) 0.075 ms/op [Average]
  (min, avg, max) = (2.988, 2.992, 2.996), stdev = 0.004
  CI (99.9%): [2.917, 3.067] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.002 ms/op
Iteration   1: 3.145 ±(99.9%) 0.002 ms/op
Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
Iteration   3: 3.091 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.112 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (3.091, 3.112, 3.145), stdev = 0.029
  CI (99.9%): [2.583, 3.641] (assumes normal distribution)


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.023 ms/op
Iteration   1: 3.988 ±(99.9%) 0.013 ms/op
Iteration   2: 4.153 ±(99.9%) 0.037 ms/op
Iteration   3: 4.035 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.059 ±(99.9%) 1.549 ms/op [Average]
  (min, avg, max) = (3.988, 4.059, 4.153), stdev = 0.085
  CI (99.9%): [2.510, 5.608] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
Iteration   1: 3.186 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.632 ms/op
                 createUser·p0.9999: 11.026 ms/op
                 createUser·p1.00:   11.289 ms/op

Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.947 ms/op
                 createUser·p0.9999: 13.124 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   3: 3.185 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.329 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.971 ms/op
                 createUser·p0.9999: 16.086 ms/op
                 createUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301177
  mean =      3.189 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1116 
    [ 1.250,  2.500) = 20175 
    [ 2.500,  3.750) = 233184 
    [ 3.750,  5.000) = 45650 
    [ 5.000,  6.250) = 465 
    [ 6.250,  7.500) = 262 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.748 ms/op
     p(99.9900) =     15.135 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.124 ms/op
                 existUser·p0.9999: 12.277 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.306 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.569 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  11.670 ms/op
                 existUser·p0.9999: 17.217 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320998
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2908 
    [ 1.250,  2.500) = 38025 
    [ 2.500,  3.750) = 258567 
    [ 3.750,  5.000) = 20515 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 169 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.306 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.939 ms/op
     p(99.9900) =     15.827 ms/op
     p(99.9990) =     17.543 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.627 ms/op
                 getUser·p0.9999: 11.822 ms/op
                 getUser·p1.00:   12.059 ms/op

Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.494 ms/op
                 getUser·p0.9999: 12.507 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.359 ms/op
                 getUser·p0.9999: 14.860 ms/op
                 getUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309519
  mean =      3.100 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1313 
    [ 1.250,  2.500) = 19900 
    [ 2.500,  3.750) = 263610 
    [ 3.750,  5.000) = 23563 
    [ 5.000,  6.250) = 530 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 115 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.508 ms/op
     p(99.9900) =     14.125 ms/op
     p(99.9990) =     15.655 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.011 ms/op
Iteration   1: 4.244 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.563 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  12.502 ms/op
                 listUser·p0.9999: 15.120 ms/op
                 listUser·p1.00:   16.646 ms/op

Iteration   2: 4.044 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.834 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 15.420 ms/op
                 listUser·p1.00:   15.729 ms/op

Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.091 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232361
  mean =      4.132 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3182 
    [ 2.500,  5.000) = 195156 
    [ 5.000,  7.500) = 32413 
    [ 7.500, 10.000) = 1116 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     22.565 ms/op
     p(99.9990) =     26.729 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.146 ± 1.159  ops/ms
ClientGrpc.existUser                       thrpt       3  10.741 ± 0.381  ops/ms
ClientGrpc.getUser                         thrpt       3  10.250 ± 2.100  ops/ms
ClientGrpc.listUser                        thrpt       3   7.876 ± 0.613  ops/ms
ClientGrpc.createUser                       avgt       3   3.178 ± 0.304   ms/op
ClientGrpc.existUser                        avgt       3   2.992 ± 0.075   ms/op
ClientGrpc.getUser                          avgt       3   3.112 ± 0.529   ms/op
ClientGrpc.listUser                         avgt       3   4.059 ± 1.549   ms/op
ClientGrpc.createUser                     sample  301177   3.189 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.329           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.166           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.112           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.748           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.135           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.597           ms/op
ClientGrpc.existUser                      sample  320998   2.992 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.306           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.939           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.827           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.629           ms/op
ClientGrpc.getUser                        sample  309519   3.100 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.605           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.508           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.125           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.794           ms/op
ClientGrpc.listUser                       sample  232361   4.132 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.563           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.944           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.517           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.565           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.804           ms/op
