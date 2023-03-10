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
# Warmup Iteration   1: 3.954 ops/ms
# Warmup Iteration   2: 8.793 ops/ms
# Warmup Iteration   3: 9.854 ops/ms
Iteration   1: 10.445 ops/ms
Iteration   2: 10.395 ops/ms
Iteration   3: 10.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.416 ±(99.9%) 0.478 ops/ms [Average]
  (min, avg, max) = (10.395, 10.416, 10.445), stdev = 0.026
  CI (99.9%): [9.938, 10.894] (assumes normal distribution)


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
# Warmup Iteration   1: 7.269 ops/ms
# Warmup Iteration   2: 10.202 ops/ms
# Warmup Iteration   3: 10.965 ops/ms
Iteration   1: 11.108 ops/ms
Iteration   2: 11.012 ops/ms
Iteration   3: 10.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.996 ±(99.9%) 2.215 ops/ms [Average]
  (min, avg, max) = (10.867, 10.996, 11.108), stdev = 0.121
  CI (99.9%): [8.781, 13.211] (assumes normal distribution)


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
# Warmup Iteration   1: 6.380 ops/ms
# Warmup Iteration   2: 10.134 ops/ms
# Warmup Iteration   3: 10.389 ops/ms
Iteration   1: 10.262 ops/ms
Iteration   2: 10.353 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.406 ±(99.9%) 3.238 ops/ms [Average]
  (min, avg, max) = (10.262, 10.406, 10.604), stdev = 0.177
  CI (99.9%): [7.168, 13.645] (assumes normal distribution)


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
# Warmup Iteration   1: 5.314 ops/ms
# Warmup Iteration   2: 7.356 ops/ms
# Warmup Iteration   3: 7.735 ops/ms
Iteration   1: 8.219 ops/ms
Iteration   2: 7.923 ops/ms
Iteration   3: 7.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.035 ±(99.9%) 2.928 ops/ms [Average]
  (min, avg, max) = (7.923, 8.035, 8.219), stdev = 0.161
  CI (99.9%): [5.107, 10.963] (assumes normal distribution)


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.001 ms/op
Iteration   1: 3.081 ±(99.9%) 0.002 ms/op
Iteration   2: 3.103 ±(99.9%) 0.002 ms/op
Iteration   3: 3.126 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.103 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.081, 3.103, 3.126), stdev = 0.022
  CI (99.9%): [2.694, 3.512] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.181 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.004 ms/op
Iteration   1: 2.897 ±(99.9%) 0.003 ms/op
Iteration   2: 2.947 ±(99.9%) 0.004 ms/op
Iteration   3: 2.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (2.878, 2.907, 2.947), stdev = 0.035
  CI (99.9%): [2.260, 3.555] (assumes normal distribution)


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.002 ms/op
Iteration   1: 3.088 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.081 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.078 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (3.064, 3.078, 3.088), stdev = 0.012
  CI (99.9%): [2.850, 3.305] (assumes normal distribution)


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
# Warmup Iteration   1: 5.991 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.024 ms/op
Iteration   1: 4.036 ±(99.9%) 0.009 ms/op
Iteration   2: 4.000 ±(99.9%) 0.009 ms/op
Iteration   3: 3.983 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.006 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.983, 4.006, 4.036), stdev = 0.027
  CI (99.9%): [3.517, 4.496] (assumes normal distribution)


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  9.982 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  10.604 ms/op
                 createUser·p0.9999: 14.434 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.943 ms/op
                 createUser·p0.999:  11.733 ms/op
                 createUser·p0.9999: 16.571 ms/op
                 createUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306889
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17052 
    [ 2.500,  5.000) = 286797 
    [ 5.000,  7.500) = 2423 
    [ 7.500, 10.000) = 261 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.990 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     18.950 ms/op
     p(99.9990) =     20.181 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  8.307 ms/op
                 existUser·p0.9999: 13.800 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  7.700 ms/op
                 existUser·p0.9999: 14.589 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.201 ms/op
                 existUser·p0.999:  8.004 ms/op
                 existUser·p0.9999: 24.500 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319291
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26784 
    [ 2.500,  5.000) = 289694 
    [ 5.000,  7.500) = 2279 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      8.059 ms/op
     p(99.9900) =     23.300 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 4.623 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.007 ms/op
Iteration   1: 3.184 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  10.233 ms/op
                 getUser·p0.9999: 17.824 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  10.100 ms/op
                 getUser·p0.9999: 19.431 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  10.485 ms/op
                 getUser·p0.9999: 20.511 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302722
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15275 
    [ 2.500,  5.000) = 283348 
    [ 5.000,  7.500) = 3256 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     10.179 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.709 ms/op
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
# Warmup Iteration   1: 5.256 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.013 ms/op
Iteration   1: 4.276 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.300 ms/op
                 listUser·p0.99:   7.645 ms/op
                 listUser·p0.999:  15.536 ms/op
                 listUser·p0.9999: 17.027 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 4.180 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  16.258 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 4.173 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  17.018 ms/op
                 listUser·p0.9999: 20.917 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228024
  mean =      4.209 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1600 
    [ 2.500,  5.000) = 191716 
    [ 5.000,  7.500) = 32123 
    [ 7.500, 10.000) = 2137 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     20.257 ms/op
     p(99.9990) =     21.084 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.416 ± 0.478  ops/ms
ClientGrpc.existUser                       thrpt       3  10.996 ± 2.215  ops/ms
ClientGrpc.getUser                         thrpt       3  10.406 ± 3.238  ops/ms
ClientGrpc.listUser                        thrpt       3   8.035 ± 2.928  ops/ms
ClientGrpc.createUser                       avgt       3   3.103 ± 0.409   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.647   ms/op
ClientGrpc.getUser                          avgt       3   3.078 ± 0.227   ms/op
ClientGrpc.listUser                         avgt       3   4.006 ± 0.489   ms/op
ClientGrpc.createUser                     sample  306889   3.128 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.591           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.990           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.950           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.135           ms/op
ClientGrpc.existUser                      sample  319291   3.006 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.729           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.059           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.300           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.904           ms/op
ClientGrpc.getUser                        sample  302722   3.169 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.666           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.116           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.308           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.179           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.152           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  228024   4.209 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.955           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.985           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.177           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.627           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.155           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.257           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.234           ms/op
