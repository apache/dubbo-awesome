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
# Warmup Iteration   1: 4.850 ops/ms
# Warmup Iteration   2: 9.423 ops/ms
# Warmup Iteration   3: 10.451 ops/ms
Iteration   1: 10.390 ops/ms
Iteration   2: 10.853 ops/ms
Iteration   3: 10.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.455 ±(99.9%) 6.736 ops/ms [Average]
  (min, avg, max) = (10.123, 10.455, 10.853), stdev = 0.369
  CI (99.9%): [3.720, 17.191] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.370 ops/ms
# Warmup Iteration   2: 10.141 ops/ms
# Warmup Iteration   3: 10.499 ops/ms
Iteration   1: 10.385 ops/ms
Iteration   2: 10.589 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.509 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (10.385, 10.509, 10.589), stdev = 0.109
  CI (99.9%): [8.523, 12.494] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.381 ops/ms
# Warmup Iteration   2: 10.290 ops/ms
# Warmup Iteration   3: 10.399 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.279 ops/ms
Iteration   3: 10.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.432 ±(99.9%) 2.422 ops/ms [Average]
  (min, avg, max) = (10.279, 10.432, 10.516), stdev = 0.133
  CI (99.9%): [8.010, 12.855] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.981 ops/ms
# Warmup Iteration   2: 7.518 ops/ms
# Warmup Iteration   3: 7.519 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 7.576 ops/ms
Iteration   3: 7.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.742 ±(99.9%) 4.215 ops/ms [Average]
  (min, avg, max) = (7.576, 7.742, 8.006), stdev = 0.231
  CI (99.9%): [3.527, 11.957] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.002 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.089 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (3.071, 3.089, 3.124), stdev = 0.031
  CI (99.9%): [2.532, 3.646] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 2.925 ±(99.9%) 0.004 ms/op
Iteration   3: 3.079 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.983 ±(99.9%) 1.538 ms/op [Average]
  (min, avg, max) = (2.925, 2.983, 3.079), stdev = 0.084
  CI (99.9%): [1.445, 4.520] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.004 ms/op
Iteration   1: 3.065 ±(99.9%) 0.003 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.139 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.090 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.064, 3.090, 3.139), stdev = 0.043
  CI (99.9%): [2.304, 3.876] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.334 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.025 ms/op
Iteration   1: 4.015 ±(99.9%) 0.015 ms/op
Iteration   2: 4.112 ±(99.9%) 0.017 ms/op
Iteration   3: 4.126 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.084 ±(99.9%) 1.101 ms/op [Average]
  (min, avg, max) = (4.015, 4.084, 4.126), stdev = 0.060
  CI (99.9%): [2.984, 5.185] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 3.136 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.315 ms/op
                 createUser·p0.9999: 11.102 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.733 ms/op
                 createUser·p0.9999: 12.596 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 3.141 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  6.668 ms/op
                 createUser·p0.9999: 16.695 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305798
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 863 
    [ 1.250,  2.500) = 20563 
    [ 2.500,  3.750) = 249208 
    [ 3.750,  5.000) = 34082 
    [ 5.000,  6.250) = 564 
    [ 6.250,  7.500) = 206 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.653 ms/op
     p(99.9900) =     16.171 ms/op
     p(99.9990) =     17.068 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 3.003 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.968 ms/op
                 existUser·p0.9999: 11.583 ms/op
                 existUser·p1.00:   11.813 ms/op

Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.209 ms/op
                 existUser·p0.999:  6.389 ms/op
                 existUser·p0.9999: 15.958 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.598 ms/op
                 existUser·p0.9999: 24.992 ms/op
                 existUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319132
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42353 
    [ 2.500,  5.000) = 275941 
    [ 5.000,  7.500) = 624 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.529 ms/op
     p(99.9900) =     22.616 ms/op
     p(99.9990) =     25.239 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 3.873 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.219 ms/op
                 getUser·p0.9999: 12.183 ms/op
                 getUser·p1.00:   12.337 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.182 ms/op
                 getUser·p0.9999: 13.480 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.897 ms/op
                 getUser·p0.9999: 13.912 ms/op
                 getUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317268
  mean =      3.027 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1726 
    [ 1.250,  2.500) = 28066 
    [ 2.500,  3.750) = 266881 
    [ 3.750,  5.000) = 19723 
    [ 5.000,  6.250) = 361 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.133 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.156 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.011 ms/op
Iteration   1: 4.057 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  12.642 ms/op
                 listUser·p0.9999: 19.507 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   2: 4.070 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.701 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 4.012 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 22.579 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237264
  mean =      4.046 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3435 
    [ 2.500,  5.000) = 203512 
    [ 5.000,  7.500) = 29170 
    [ 7.500, 10.000) = 690 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     15.278 ms/op
     p(99.9900) =     22.062 ms/op
     p(99.9990) =     23.505 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.455 ± 6.736  ops/ms
ClientGrpc.existUser                       thrpt       3  10.509 ± 1.986  ops/ms
ClientGrpc.getUser                         thrpt       3  10.432 ± 2.422  ops/ms
ClientGrpc.listUser                        thrpt       3   7.742 ± 4.215  ops/ms
ClientGrpc.createUser                       avgt       3   3.089 ± 0.557   ms/op
ClientGrpc.existUser                        avgt       3   2.983 ± 1.538   ms/op
ClientGrpc.getUser                          avgt       3   3.090 ± 0.786   ms/op
ClientGrpc.listUser                         avgt       3   4.084 ± 1.101   ms/op
ClientGrpc.createUser                     sample  305798   3.140 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.693           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.002           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.653           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.171           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.236           ms/op
ClientGrpc.existUser                      sample  319132   3.005 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.570           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.529           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.616           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.297           ms/op
ClientGrpc.getUser                        sample  317268   3.027 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.133           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.517           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.303           ms/op
ClientGrpc.listUser                       sample  237264   4.046 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.983           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.278           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.062           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
