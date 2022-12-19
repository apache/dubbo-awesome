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
# Warmup Iteration   1: 3.909 ops/ms
# Warmup Iteration   2: 8.721 ops/ms
# Warmup Iteration   3: 10.201 ops/ms
Iteration   1: 9.967 ops/ms
Iteration   2: 10.107 ops/ms
Iteration   3: 10.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.122 ±(99.9%) 2.978 ops/ms [Average]
  (min, avg, max) = (9.967, 10.122, 10.292), stdev = 0.163
  CI (99.9%): [7.144, 13.100] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.786 ops/ms
# Warmup Iteration   2: 10.158 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.891 ops/ms
Iteration   2: 10.758 ops/ms
Iteration   3: 10.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.758 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (10.624, 10.758, 10.891), stdev = 0.134
  CI (99.9%): [8.319, 13.196] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.956 ops/ms
# Warmup Iteration   2: 9.877 ops/ms
# Warmup Iteration   3: 10.217 ops/ms
Iteration   1: 10.271 ops/ms
Iteration   2: 10.073 ops/ms
Iteration   3: 10.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.226 ±(99.9%) 2.488 ops/ms [Average]
  (min, avg, max) = (10.073, 10.226, 10.334), stdev = 0.136
  CI (99.9%): [7.738, 12.714] (assumes normal distribution)


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
# Warmup Iteration   1: 5.791 ops/ms
# Warmup Iteration   2: 7.513 ops/ms
# Warmup Iteration   3: 7.706 ops/ms
Iteration   1: 7.796 ops/ms
Iteration   2: 7.693 ops/ms
Iteration   3: 7.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.795 ±(99.9%) 1.845 ops/ms [Average]
  (min, avg, max) = (7.693, 7.795, 7.895), stdev = 0.101
  CI (99.9%): [5.950, 9.639] (assumes normal distribution)


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
# Warmup Iteration   1: 4.334 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.002 ms/op
Iteration   1: 3.070 ±(99.9%) 0.003 ms/op
Iteration   2: 3.145 ±(99.9%) 0.001 ms/op
Iteration   3: 3.188 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.134 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.070, 3.134, 3.188), stdev = 0.060
  CI (99.9%): [2.045, 4.222] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.002 ms/op
Iteration   1: 3.014 ±(99.9%) 0.002 ms/op
Iteration   2: 3.073 ±(99.9%) 0.002 ms/op
Iteration   3: 2.938 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.008 ±(99.9%) 1.234 ms/op [Average]
  (min, avg, max) = (2.938, 3.008, 3.073), stdev = 0.068
  CI (99.9%): [1.774, 4.243] (assumes normal distribution)


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.216 ±(99.9%) 0.004 ms/op
Iteration   2: 3.140 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.173 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (3.140, 3.173, 3.216), stdev = 0.039
  CI (99.9%): [2.464, 3.881] (assumes normal distribution)


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
# Warmup Iteration   1: 5.525 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.012 ms/op
Iteration   1: 4.035 ±(99.9%) 0.010 ms/op
Iteration   2: 4.005 ±(99.9%) 0.007 ms/op
Iteration   3: 4.018 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.019 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (4.005, 4.019, 4.035), stdev = 0.015
  CI (99.9%): [3.751, 4.288] (assumes normal distribution)


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.006 ms/op
Iteration   1: 3.185 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.539 ms/op
                 createUser·p0.9999: 13.925 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.382 ms/op
                 createUser·p0.9999: 15.172 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  9.912 ms/op
                 createUser·p0.9999: 18.309 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304022
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 748 
    [ 1.250,  2.500) = 26822 
    [ 2.500,  3.750) = 237710 
    [ 3.750,  5.000) = 37678 
    [ 5.000,  6.250) = 506 
    [ 6.250,  7.500) = 223 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.813 ms/op
     p(99.9900) =     16.895 ms/op
     p(99.9990) =     18.513 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.684 ms/op
                 existUser·p0.9999: 13.642 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.076 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  9.290 ms/op
                 existUser·p0.9999: 17.843 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315311
  mean =      3.045 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39616 
    [ 2.500,  5.000) = 274720 
    [ 5.000,  7.500) = 644 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.813 ms/op
     p(99.9900) =     24.240 ms/op
     p(99.9990) =     25.330 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.006 ms/op
Iteration   1: 3.203 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.827 ms/op
                 getUser·p0.9999: 19.629 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.185 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.221 ms/op
                 getUser·p0.9999: 16.133 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   3: 3.193 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.457 ms/op
                 getUser·p0.999:  8.092 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300565
  mean =      3.194 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 361 
    [ 1.250,  2.500) = 19355 
    [ 2.500,  3.750) = 236715 
    [ 3.750,  5.000) = 43220 
    [ 5.000,  6.250) = 388 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 116 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.496 ms/op
     p(99.9900) =     19.200 ms/op
     p(99.9990) =     19.922 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 5.533 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.013 ms/op
Iteration   1: 4.002 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.077 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 4.134 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.294 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  16.230 ms/op
                 listUser·p0.9999: 22.867 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   3: 4.150 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  17.266 ms/op
                 listUser·p0.9999: 24.487 ms/op
                 listUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234393
  mean =      4.094 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1752 
    [ 2.500,  5.000) = 203074 
    [ 5.000,  7.500) = 27884 
    [ 7.500, 10.000) = 1134 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.852 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.863 ms/op
     p(99.9900) =     23.826 ms/op
     p(99.9990) =     24.881 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.122 ± 2.978  ops/ms
ClientGrpc.existUser                       thrpt       3  10.758 ± 2.438  ops/ms
ClientGrpc.getUser                         thrpt       3  10.226 ± 2.488  ops/ms
ClientGrpc.listUser                        thrpt       3   7.795 ± 1.845  ops/ms
ClientGrpc.createUser                       avgt       3   3.134 ± 1.089   ms/op
ClientGrpc.existUser                        avgt       3   3.008 ± 1.234   ms/op
ClientGrpc.getUser                          avgt       3   3.173 ± 0.708   ms/op
ClientGrpc.listUser                         avgt       3   4.019 ± 0.269   ms/op
ClientGrpc.createUser                     sample  304022   3.156 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.637           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.813           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.895           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.776           ms/op
ClientGrpc.existUser                      sample  315311   3.045 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.768           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.912           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.813           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.240           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.362           ms/op
ClientGrpc.getUser                        sample  300565   3.194 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.867           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.496           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.200           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.956           ms/op
ClientGrpc.listUser                       sample  234393   4.094 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.040           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.852           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.863           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.826           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.853           ms/op
