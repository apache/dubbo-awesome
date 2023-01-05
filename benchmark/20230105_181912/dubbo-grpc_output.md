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
# Warmup Iteration   1: 2.330 ops/ms
# Warmup Iteration   2: 5.807 ops/ms
# Warmup Iteration   3: 7.482 ops/ms
Iteration   1: 7.603 ops/ms
Iteration   2: 7.660 ops/ms
Iteration   3: 7.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.613 ±(99.9%) 0.787 ops/ms [Average]
  (min, avg, max) = (7.576, 7.613, 7.660), stdev = 0.043
  CI (99.9%): [6.826, 8.399] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.014 ops/ms
# Warmup Iteration   2: 7.460 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 7.783 ops/ms
Iteration   3: 7.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.883 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (7.783, 7.883, 8.044), stdev = 0.141
  CI (99.9%): [5.312, 10.453] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.563 ops/ms
# Warmup Iteration   2: 7.126 ops/ms
# Warmup Iteration   3: 7.498 ops/ms
Iteration   1: 7.437 ops/ms
Iteration   2: 7.286 ops/ms
Iteration   3: 7.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.385 ±(99.9%) 1.562 ops/ms [Average]
  (min, avg, max) = (7.286, 7.385, 7.437), stdev = 0.086
  CI (99.9%): [5.823, 8.947] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.486 ops/ms
# Warmup Iteration   2: 5.415 ops/ms
# Warmup Iteration   3: 5.791 ops/ms
Iteration   1: 5.627 ops/ms
Iteration   2: 5.863 ops/ms
Iteration   3: 5.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.746 ±(99.9%) 2.150 ops/ms [Average]
  (min, avg, max) = (5.627, 5.746, 5.863), stdev = 0.118
  CI (99.9%): [3.596, 7.896] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.435 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.003 ms/op
Iteration   1: 4.438 ±(99.9%) 0.004 ms/op
Iteration   2: 4.470 ±(99.9%) 0.004 ms/op
Iteration   3: 4.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.444 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (4.424, 4.444, 4.470), stdev = 0.024
  CI (99.9%): [4.009, 4.878] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.877 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.003 ms/op
Iteration   1: 4.068 ±(99.9%) 0.005 ms/op
Iteration   2: 4.132 ±(99.9%) 0.017 ms/op
Iteration   3: 4.189 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.129 ±(99.9%) 1.104 ms/op [Average]
  (min, avg, max) = (4.068, 4.129, 4.189), stdev = 0.061
  CI (99.9%): [3.026, 5.233] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.581 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.415 ±(99.9%) 0.003 ms/op
Iteration   1: 4.444 ±(99.9%) 0.003 ms/op
Iteration   2: 4.215 ±(99.9%) 0.003 ms/op
Iteration   3: 4.225 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.295 ±(99.9%) 2.357 ms/op [Average]
  (min, avg, max) = (4.215, 4.295, 4.444), stdev = 0.129
  CI (99.9%): [1.937, 6.652] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.347 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.953 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.411 ±(99.9%) 0.021 ms/op
Iteration   1: 5.584 ±(99.9%) 0.023 ms/op
Iteration   2: 5.450 ±(99.9%) 0.018 ms/op
Iteration   3: 5.510 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.515 ±(99.9%) 1.226 ms/op [Average]
  (min, avg, max) = (5.450, 5.515, 5.584), stdev = 0.067
  CI (99.9%): [4.288, 6.741] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.284 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.014 ms/op
Iteration   1: 4.180 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   5.308 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   7.905 ms/op
                 createUser·p0.999:  11.819 ms/op
                 createUser·p0.9999: 22.173 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 4.165 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.882 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  14.536 ms/op
                 createUser·p0.9999: 24.564 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   3: 4.137 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.284 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.676 ms/op
                 createUser·p0.999:  13.323 ms/op
                 createUser·p0.9999: 27.665 ms/op
                 createUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 230716
  mean =      4.161 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8211 
    [ 2.500,  5.000) = 189098 
    [ 5.000,  7.500) = 30755 
    [ 7.500, 10.000) = 1844 
    [10.000, 12.500) = 507 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     13.126 ms/op
     p(99.9900) =     25.369 ms/op
     p(99.9990) =     27.777 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.123 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.013 ms/op
Iteration   1: 4.055 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.272 ms/op
                 existUser·p0.999:  11.242 ms/op
                 existUser·p0.9999: 15.396 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   2: 4.012 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.310 ms/op
                 existUser·p0.999:  14.434 ms/op
                 existUser·p0.9999: 22.054 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.299 ms/op
                 existUser·p0.999:  12.932 ms/op
                 existUser·p0.9999: 21.739 ms/op
                 existUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236434
  mean =      4.058 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8686 
    [ 2.500,  5.000) = 197367 
    [ 5.000,  7.500) = 28289 
    [ 7.500, 10.000) = 1521 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     12.183 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     22.291 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.821 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.014 ms/op
Iteration   1: 4.404 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   8.110 ms/op
                 getUser·p0.999:  12.065 ms/op
                 getUser·p0.9999: 17.431 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 4.277 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  11.633 ms/op
                 getUser·p0.9999: 30.147 ms/op
                 getUser·p1.00:   33.194 ms/op

Iteration   3: 4.297 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   4.149 ms/op
                 getUser·p0.90:   5.644 ms/op
                 getUser·p0.95:   6.210 ms/op
                 getUser·p0.99:   7.913 ms/op
                 getUser·p0.999:  10.462 ms/op
                 getUser·p0.9999: 24.285 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 222002
  mean =      4.325 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7282 
    [ 2.500,  5.000) = 169031 
    [ 5.000,  7.500) = 42677 
    [ 7.500, 10.000) = 2492 
    [10.000, 12.500) = 375 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      4.186 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     11.403 ms/op
     p(99.9900) =     29.190 ms/op
     p(99.9990) =     33.107 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 8.629 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 5.894 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.671 ±(99.9%) 0.023 ms/op
Iteration   1: 5.540 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.241 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  15.650 ms/op
                 listUser·p0.9999: 19.552 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 5.526 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   5.153 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  19.276 ms/op
                 listUser·p0.9999: 23.595 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 5.467 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.863 ms/op
                 listUser·p0.999:  20.826 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174414
  mean =      5.511 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 421 
    [ 2.500,  5.000) = 74596 
    [ 5.000,  7.500) = 82744 
    [ 7.500, 10.000) = 13909 
    [10.000, 12.500) = 1988 
    [12.500, 15.000) = 390 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.438 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     18.539 ms/op
     p(99.9900) =     23.742 ms/op
     p(99.9990) =     25.174 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.613 ± 0.787  ops/ms
ClientGrpc.existUser                       thrpt       3   7.883 ± 2.570  ops/ms
ClientGrpc.getUser                         thrpt       3   7.385 ± 1.562  ops/ms
ClientGrpc.listUser                        thrpt       3   5.746 ± 2.150  ops/ms
ClientGrpc.createUser                       avgt       3   4.444 ± 0.434   ms/op
ClientGrpc.existUser                        avgt       3   4.129 ± 1.104   ms/op
ClientGrpc.getUser                          avgt       3   4.295 ± 2.357   ms/op
ClientGrpc.listUser                         avgt       3   5.515 ± 1.226   ms/op
ClientGrpc.createUser                     sample  230716   4.161 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.599           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.300           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.849           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.733           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.126           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.369           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.279           ms/op
ClientGrpc.existUser                      sample  236434   4.058 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.687           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.603           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.291           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.183           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.725           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.381           ms/op
ClientGrpc.getUser                        sample  222002   4.325 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.997           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.186           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.562           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.087           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.913           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.403           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.190           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.194           ms/op
ClientGrpc.listUser                       sample  174414   5.511 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.438           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.339           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.682           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.539           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.742           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.199           ms/op
