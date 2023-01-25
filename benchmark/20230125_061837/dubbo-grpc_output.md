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
# Warmup Iteration   1: 4.076 ops/ms
# Warmup Iteration   2: 9.080 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 10.041 ops/ms
Iteration   2: 10.269 ops/ms
Iteration   3: 10.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.177 ±(99.9%) 2.186 ops/ms [Average]
  (min, avg, max) = (10.041, 10.177, 10.269), stdev = 0.120
  CI (99.9%): [7.990, 12.363] (assumes normal distribution)


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
# Warmup Iteration   1: 7.352 ops/ms
# Warmup Iteration   2: 10.237 ops/ms
# Warmup Iteration   3: 10.618 ops/ms
Iteration   1: 10.560 ops/ms
Iteration   2: 10.471 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.487 ±(99.9%) 1.209 ops/ms [Average]
  (min, avg, max) = (10.430, 10.487, 10.560), stdev = 0.066
  CI (99.9%): [9.278, 11.696] (assumes normal distribution)


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
# Warmup Iteration   1: 7.386 ops/ms
# Warmup Iteration   2: 9.790 ops/ms
# Warmup Iteration   3: 10.146 ops/ms
Iteration   1: 10.027 ops/ms
Iteration   2: 10.195 ops/ms
Iteration   3: 10.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.117 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (10.027, 10.117, 10.195), stdev = 0.084
  CI (99.9%): [8.577, 11.657] (assumes normal distribution)


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
# Warmup Iteration   1: 5.910 ops/ms
# Warmup Iteration   2: 7.434 ops/ms
# Warmup Iteration   3: 7.578 ops/ms
Iteration   1: 7.876 ops/ms
Iteration   2: 7.767 ops/ms
Iteration   3: 7.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.854 ±(99.9%) 1.433 ops/ms [Average]
  (min, avg, max) = (7.767, 7.854, 7.920), stdev = 0.079
  CI (99.9%): [6.421, 9.287] (assumes normal distribution)


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.002 ms/op
Iteration   1: 3.206 ±(99.9%) 0.003 ms/op
Iteration   2: 3.109 ±(99.9%) 0.004 ms/op
Iteration   3: 3.159 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.158 ±(99.9%) 0.890 ms/op [Average]
  (min, avg, max) = (3.109, 3.158, 3.206), stdev = 0.049
  CI (99.9%): [2.268, 4.048] (assumes normal distribution)


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.002 ms/op
Iteration   1: 3.053 ±(99.9%) 0.002 ms/op
Iteration   2: 2.998 ±(99.9%) 0.002 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.036 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (2.998, 3.036, 3.058), stdev = 0.033
  CI (99.9%): [2.426, 3.647] (assumes normal distribution)


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.002 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.192 ±(99.9%) 0.002 ms/op
Iteration   3: 3.232 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.198 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.171, 3.198, 3.232), stdev = 0.031
  CI (99.9%): [2.629, 3.768] (assumes normal distribution)


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
# Warmup Iteration   1: 5.457 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.018 ms/op
Iteration   1: 4.053 ±(99.9%) 0.027 ms/op
Iteration   2: 4.004 ±(99.9%) 0.036 ms/op
Iteration   3: 4.043 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.033 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (4.004, 4.033, 4.053), stdev = 0.026
  CI (99.9%): [3.557, 4.509] (assumes normal distribution)


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
# Warmup Iteration   1: 4.344 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
Iteration   1: 3.171 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  9.420 ms/op
                 createUser·p0.9999: 21.103 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  8.851 ms/op
                 createUser·p0.9999: 17.958 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   3: 3.120 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  11.121 ms/op
                 createUser·p0.9999: 24.707 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303232
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19815 
    [ 2.500,  5.000) = 282298 
    [ 5.000,  7.500) = 640 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     10.732 ms/op
     p(99.9900) =     23.584 ms/op
     p(99.9990) =     24.903 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.386 ms/op
                 existUser·p0.9999: 12.778 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  5.207 ms/op
                 existUser·p0.9999: 24.711 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.061 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.221 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311621
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43746 
    [ 2.500,  5.000) = 267307 
    [ 5.000,  7.500) = 418 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      5.926 ms/op
     p(99.9900) =     23.774 ms/op
     p(99.9990) =     25.096 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 4.353 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.006 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  7.571 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   2: 3.172 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.963 ms/op
                 getUser·p0.9999: 16.104 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.307 ms/op
                 getUser·p0.999:  5.639 ms/op
                 getUser·p0.9999: 17.589 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304840
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 493 
    [ 1.250,  2.500) = 18505 
    [ 2.500,  3.750) = 256485 
    [ 3.750,  5.000) = 28026 
    [ 5.000,  6.250) = 833 
    [ 6.250,  7.500) = 231 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.120 ms/op
     p(99.9900) =     17.122 ms/op
     p(99.9990) =     17.757 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 5.441 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.012 ms/op
Iteration   1: 3.973 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.663 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.136 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.013 ms/op
                 listUser·p0.999:  16.225 ms/op
                 listUser·p0.9999: 25.009 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   3: 4.057 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 20.294 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238508
  mean =      4.026 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2169 
    [ 2.500,  5.000) = 212029 
    [ 5.000,  7.500) = 22934 
    [ 7.500, 10.000) = 849 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     15.507 ms/op
     p(99.9900) =     23.640 ms/op
     p(99.9990) =     26.812 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.177 ± 2.186  ops/ms
ClientGrpc.existUser                       thrpt       3  10.487 ± 1.209  ops/ms
ClientGrpc.getUser                         thrpt       3  10.117 ± 1.540  ops/ms
ClientGrpc.listUser                        thrpt       3   7.854 ± 1.433  ops/ms
ClientGrpc.createUser                       avgt       3   3.158 ± 0.890   ms/op
ClientGrpc.existUser                        avgt       3   3.036 ± 0.610   ms/op
ClientGrpc.getUser                          avgt       3   3.198 ± 0.569   ms/op
ClientGrpc.listUser                         avgt       3   4.033 ± 0.476   ms/op
ClientGrpc.createUser                     sample  303232   3.167 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.562           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.732           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.584           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.788           ms/op
ClientGrpc.existUser                      sample  311621   3.081 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.816           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.113           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.926           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.774           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.231           ms/op
ClientGrpc.getUser                        sample  304840   3.148 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.645           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.120           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.122           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.826           ms/op
ClientGrpc.listUser                       sample  238508   4.026 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.873           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.507           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.640           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.903           ms/op
