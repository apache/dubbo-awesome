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
# Warmup Iteration   1: 3.851 ops/ms
# Warmup Iteration   2: 8.723 ops/ms
# Warmup Iteration   3: 10.011 ops/ms
Iteration   1: 10.129 ops/ms
Iteration   2: 9.924 ops/ms
Iteration   3: 9.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.015 ±(99.9%) 1.906 ops/ms [Average]
  (min, avg, max) = (9.924, 10.015, 10.129), stdev = 0.104
  CI (99.9%): [8.109, 11.920] (assumes normal distribution)


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
# Warmup Iteration   1: 7.654 ops/ms
# Warmup Iteration   2: 10.220 ops/ms
# Warmup Iteration   3: 10.547 ops/ms
Iteration   1: 10.438 ops/ms
Iteration   2: 10.411 ops/ms
Iteration   3: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.503 ±(99.9%) 2.501 ops/ms [Average]
  (min, avg, max) = (10.411, 10.503, 10.660), stdev = 0.137
  CI (99.9%): [8.002, 13.004] (assumes normal distribution)


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
# Warmup Iteration   1: 6.943 ops/ms
# Warmup Iteration   2: 9.742 ops/ms
# Warmup Iteration   3: 10.126 ops/ms
Iteration   1: 10.105 ops/ms
Iteration   2: 10.257 ops/ms
Iteration   3: 10.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.195 ±(99.9%) 1.452 ops/ms [Average]
  (min, avg, max) = (10.105, 10.195, 10.257), stdev = 0.080
  CI (99.9%): [8.743, 11.647] (assumes normal distribution)


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
# Warmup Iteration   1: 5.322 ops/ms
# Warmup Iteration   2: 7.495 ops/ms
# Warmup Iteration   3: 7.740 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.716 ops/ms
Iteration   3: 7.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.676 ±(99.9%) 1.363 ops/ms [Average]
  (min, avg, max) = (7.590, 7.676, 7.723), stdev = 0.075
  CI (99.9%): [6.313, 9.040] (assumes normal distribution)


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.003 ms/op
Iteration   1: 3.152 ±(99.9%) 0.004 ms/op
Iteration   2: 3.203 ±(99.9%) 0.002 ms/op
Iteration   3: 3.197 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.184 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.152, 3.184, 3.203), stdev = 0.028
  CI (99.9%): [2.680, 3.688] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 2.927 ±(99.9%) 0.002 ms/op
Iteration   3: 3.094 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.026 ±(99.9%) 1.594 ms/op [Average]
  (min, avg, max) = (2.927, 3.026, 3.094), stdev = 0.087
  CI (99.9%): [1.432, 4.620] (assumes normal distribution)


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.004 ms/op
Iteration   1: 3.217 ±(99.9%) 0.002 ms/op
Iteration   2: 3.247 ±(99.9%) 0.001 ms/op
Iteration   3: 3.202 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.222 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (3.202, 3.222, 3.247), stdev = 0.023
  CI (99.9%): [2.808, 3.637] (assumes normal distribution)


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
# Warmup Iteration   1: 5.770 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.021 ms/op
Iteration   1: 4.045 ±(99.9%) 0.016 ms/op
Iteration   2: 4.134 ±(99.9%) 0.015 ms/op
Iteration   3: 4.150 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.110 ±(99.9%) 1.027 ms/op [Average]
  (min, avg, max) = (4.045, 4.110, 4.150), stdev = 0.056
  CI (99.9%): [3.083, 5.136] (assumes normal distribution)


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
Iteration   1: 3.230 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 15.175 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 3.285 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   4.607 ms/op
                 createUser·p0.999:  8.965 ms/op
                 createUser·p0.9999: 19.154 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   3: 3.211 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 21.268 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295977
  mean =      3.242 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17323 
    [ 2.500,  5.000) = 276430 
    [ 5.000,  7.500) = 1609 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.127 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     21.470 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.873 ms/op
                 existUser·p0.9999: 13.149 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.146 ms/op
                 existUser·p0.9999: 19.205 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  8.086 ms/op
                 existUser·p0.9999: 15.855 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315520
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44860 
    [ 2.500,  5.000) = 268772 
    [ 5.000,  7.500) = 1472 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     18.135 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
Iteration   1: 3.167 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.025 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  8.348 ms/op
                 getUser·p0.9999: 21.493 ms/op
                 getUser·p1.00:   21.758 ms/op

Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.758 ms/op
                 getUser·p0.9999: 17.695 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   3: 3.216 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.521 ms/op
                 getUser·p0.999:  11.006 ms/op
                 getUser·p0.9999: 23.202 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298847
  mean =      3.210 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17872 
    [ 2.500,  5.000) = 279413 
    [ 5.000,  7.500) = 1139 
    [ 7.500, 10.000) = 183 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.888 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.275 ms/op
     p(99.9900) =     22.646 ms/op
     p(99.9990) =     23.430 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 5.202 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.013 ms/op
Iteration   1: 4.225 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  14.239 ms/op
                 listUser·p0.9999: 15.981 ms/op
                 listUser·p1.00:   16.187 ms/op

Iteration   2: 4.092 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.426 ms/op
                 listUser·p0.9999: 18.264 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 4.162 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  17.148 ms/op
                 listUser·p0.9999: 20.009 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230724
  mean =      4.159 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2101 
    [ 2.500,  5.000) = 197714 
    [ 5.000,  7.500) = 28827 
    [ 7.500, 10.000) = 1502 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     19.490 ms/op
     p(99.9990) =     20.863 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.015 ± 1.906  ops/ms
ClientGrpc.existUser                       thrpt       3  10.503 ± 2.501  ops/ms
ClientGrpc.getUser                         thrpt       3  10.195 ± 1.452  ops/ms
ClientGrpc.listUser                        thrpt       3   7.676 ± 1.363  ops/ms
ClientGrpc.createUser                       avgt       3   3.184 ± 0.504   ms/op
ClientGrpc.existUser                        avgt       3   3.026 ± 1.594   ms/op
ClientGrpc.getUser                          avgt       3   3.222 ± 0.414   ms/op
ClientGrpc.listUser                         avgt       3   4.110 ± 1.027   ms/op
ClientGrpc.createUser                     sample  295977   3.242 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.819           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.195           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.157           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.127           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.414           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.692           ms/op
ClientGrpc.existUser                      sample  315520   3.041 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.736           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.936           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.864           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.135           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.775           ms/op
ClientGrpc.getUser                        sample  298847   3.210 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.888           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.275           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.646           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.593           ms/op
ClientGrpc.listUser                       sample  230724   4.159 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.959           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.892           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.490           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.906           ms/op
