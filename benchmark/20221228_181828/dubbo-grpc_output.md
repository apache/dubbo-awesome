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
# Warmup Iteration   1: 4.138 ops/ms
# Warmup Iteration   2: 9.206 ops/ms
# Warmup Iteration   3: 10.063 ops/ms
Iteration   1: 10.278 ops/ms
Iteration   2: 9.999 ops/ms
Iteration   3: 10.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.127 ±(99.9%) 2.573 ops/ms [Average]
  (min, avg, max) = (9.999, 10.127, 10.278), stdev = 0.141
  CI (99.9%): [7.554, 12.700] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.901 ops/ms
# Warmup Iteration   2: 10.498 ops/ms
# Warmup Iteration   3: 10.922 ops/ms
Iteration   1: 10.759 ops/ms
Iteration   2: 10.775 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.744 ±(99.9%) 0.739 ops/ms [Average]
  (min, avg, max) = (10.698, 10.744, 10.775), stdev = 0.040
  CI (99.9%): [10.005, 11.482] (assumes normal distribution)


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
# Warmup Iteration   1: 6.999 ops/ms
# Warmup Iteration   2: 9.968 ops/ms
# Warmup Iteration   3: 10.322 ops/ms
Iteration   1: 10.044 ops/ms
Iteration   2: 10.212 ops/ms
Iteration   3: 10.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.111 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (10.044, 10.111, 10.212), stdev = 0.089
  CI (99.9%): [8.486, 11.736] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.045 ops/ms
# Warmup Iteration   2: 7.655 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 7.908 ops/ms
Iteration   2: 8.046 ops/ms
Iteration   3: 7.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.974 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (7.908, 7.974, 8.046), stdev = 0.069
  CI (99.9%): [6.716, 9.232] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.160 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.003 ms/op
Iteration   1: 3.161 ±(99.9%) 0.003 ms/op
Iteration   2: 3.131 ±(99.9%) 0.001 ms/op
Iteration   3: 3.243 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.178 ±(99.9%) 1.059 ms/op [Average]
  (min, avg, max) = (3.131, 3.178, 3.243), stdev = 0.058
  CI (99.9%): [2.119, 4.237] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.002 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 3.012 ±(99.9%) 0.001 ms/op
Iteration   3: 3.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.032 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.012, 3.032, 3.050), stdev = 0.019
  CI (99.9%): [2.687, 3.377] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.003 ms/op
Iteration   1: 3.159 ±(99.9%) 0.002 ms/op
Iteration   2: 3.170 ±(99.9%) 0.001 ms/op
Iteration   3: 3.122 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.151 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.122, 3.151, 3.170), stdev = 0.025
  CI (99.9%): [2.691, 3.611] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.412 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.017 ms/op
Iteration   1: 4.122 ±(99.9%) 0.024 ms/op
Iteration   2: 3.964 ±(99.9%) 0.005 ms/op
Iteration   3: 4.049 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.045 ±(99.9%) 1.444 ms/op [Average]
  (min, avg, max) = (3.964, 4.045, 4.122), stdev = 0.079
  CI (99.9%): [2.601, 5.489] (assumes normal distribution)


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.092 ms/op
                 createUser·p0.9999: 22.239 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.789 ms/op
                 createUser·p0.9999: 22.849 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  11.461 ms/op
                 createUser·p0.9999: 26.411 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303335
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26356 
    [ 2.500,  5.000) = 275890 
    [ 5.000,  7.500) = 680 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.031 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
Iteration   1: 3.014 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.477 ms/op
                 existUser·p0.9999: 15.021 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 2.997 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.161 ms/op
                 existUser·p0.9999: 16.886 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 19.758 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318085
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45658 
    [ 2.500,  5.000) = 271466 
    [ 5.000,  7.500) = 673 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.266 ms/op
     p(99.9900) =     19.208 ms/op
     p(99.9990) =     20.140 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 12.763 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.643 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 3.183 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.606 ms/op
                 getUser·p0.9999: 16.908 ms/op
                 getUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303835
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 431 
    [ 1.250,  2.500) = 20673 
    [ 2.500,  3.750) = 246020 
    [ 3.750,  5.000) = 35535 
    [ 5.000,  6.250) = 435 
    [ 6.250,  7.500) = 298 
    [ 7.500,  8.750) = 202 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 66 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.349 ms/op
     p(99.9900) =     16.928 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 5.377 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.012 ms/op
Iteration   1: 4.115 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.557 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  17.509 ms/op
                 listUser·p0.9999: 23.214 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 3.772 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  17.145 ms/op
                 listUser·p0.9999: 25.085 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   3: 4.040 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  18.018 ms/op
                 listUser·p0.9999: 22.956 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241738
  mean =      3.970 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3737 
    [ 2.500,  5.000) = 211951 
    [ 5.000,  7.500) = 24585 
    [ 7.500, 10.000) = 958 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     24.177 ms/op
     p(99.9990) =     25.575 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.127 ± 2.573  ops/ms
ClientGrpc.existUser                       thrpt       3  10.744 ± 0.739  ops/ms
ClientGrpc.getUser                         thrpt       3  10.111 ± 1.625  ops/ms
ClientGrpc.listUser                        thrpt       3   7.974 ± 1.258  ops/ms
ClientGrpc.createUser                       avgt       3   3.178 ± 1.059   ms/op
ClientGrpc.existUser                        avgt       3   3.032 ± 0.345   ms/op
ClientGrpc.getUser                          avgt       3   3.151 ± 0.460   ms/op
ClientGrpc.listUser                         avgt       3   4.045 ± 1.444   ms/op
ClientGrpc.createUser                     sample  303335   3.166 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.654           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.249           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.428           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  318085   3.017 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.727           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.850           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.208           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.251           ms/op
ClientGrpc.getUser                        sample  303835   3.158 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.783           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.349           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.928           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.531           ms/op
ClientGrpc.listUser                       sample  241738   3.970 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.557           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.269           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.177           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.756           ms/op
