# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.978 ops/ms
# Warmup Iteration   2: 8.722 ops/ms
# Warmup Iteration   3: 9.931 ops/ms
Iteration   1: 9.784 ops/ms
Iteration   2: 10.398 ops/ms
Iteration   3: 10.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.144 ±(99.9%) 5.848 ops/ms [Average]
  (min, avg, max) = (9.784, 10.144, 10.398), stdev = 0.321
  CI (99.9%): [4.296, 15.992] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.961 ops/ms
# Warmup Iteration   2: 10.397 ops/ms
# Warmup Iteration   3: 10.688 ops/ms
Iteration   1: 10.596 ops/ms
Iteration   2: 10.639 ops/ms
Iteration   3: 10.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.675 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (10.596, 10.675, 10.790), stdev = 0.102
  CI (99.9%): [8.812, 12.538] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.960 ops/ms
# Warmup Iteration   2: 9.639 ops/ms
# Warmup Iteration   3: 10.112 ops/ms
Iteration   1: 10.181 ops/ms
Iteration   2: 9.886 ops/ms
Iteration   3: 9.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.983 ±(99.9%) 3.126 ops/ms [Average]
  (min, avg, max) = (9.882, 9.983, 10.181), stdev = 0.171
  CI (99.9%): [6.857, 13.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.673 ops/ms
# Warmup Iteration   2: 7.929 ops/ms
# Warmup Iteration   3: 8.137 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 8.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.123 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (8.062, 8.123, 8.196), stdev = 0.068
  CI (99.9%): [6.880, 9.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.002 ms/op
Iteration   1: 3.172 ±(99.9%) 0.002 ms/op
Iteration   2: 3.218 ±(99.9%) 0.001 ms/op
Iteration   3: 3.234 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.208 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (3.172, 3.208, 3.234), stdev = 0.032
  CI (99.9%): [2.616, 3.800] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.003 ms/op
Iteration   1: 3.087 ±(99.9%) 0.003 ms/op
Iteration   2: 3.213 ±(99.9%) 0.002 ms/op
Iteration   3: 3.045 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.115 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (3.045, 3.115, 3.213), stdev = 0.087
  CI (99.9%): [1.520, 4.710] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
Iteration   1: 3.140 ±(99.9%) 0.002 ms/op
Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.139 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.104, 3.139, 3.173), stdev = 0.034
  CI (99.9%): [2.514, 3.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.979 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.020 ms/op
Iteration   1: 3.823 ±(99.9%) 0.010 ms/op
Iteration   2: 3.894 ±(99.9%) 0.010 ms/op
Iteration   3: 3.890 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.869 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.823, 3.869, 3.894), stdev = 0.040
  CI (99.9%): [3.140, 4.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.227 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.006 ms/op
Iteration   1: 3.260 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.306 ms/op
                 createUser·p0.9999: 12.681 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.973 ms/op
                 createUser·p0.999:  8.839 ms/op
                 createUser·p0.9999: 18.383 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 3.177 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.526 ms/op
                 createUser·p0.999:  9.412 ms/op
                 createUser·p0.9999: 15.757 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297315
  mean =      3.227 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 344 
    [ 1.250,  2.500) = 6267 
    [ 2.500,  3.750) = 254402 
    [ 3.750,  5.000) = 34187 
    [ 5.000,  6.250) = 1239 
    [ 6.250,  7.500) = 465 
    [ 7.500,  8.750) = 129 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      8.547 ms/op
     p(99.9900) =     18.031 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.008 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  7.807 ms/op
                 existUser·p0.9999: 18.056 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   2: 2.962 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 16.109 ms/op
                 existUser·p1.00:   16.663 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  10.112 ms/op
                 existUser·p0.9999: 24.295 ms/op
                 existUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319674
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26251 
    [ 2.500,  5.000) = 291639 
    [ 5.000,  7.500) = 1283 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      9.279 ms/op
     p(99.9900) =     22.743 ms/op
     p(99.9990) =     24.471 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.006 ms/op
Iteration   1: 3.183 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 12.122 ms/op
                 getUser·p1.00:   12.599 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.413 ms/op
                 getUser·p0.9999: 14.628 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   3: 3.111 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.858 ms/op
                 getUser·p0.9999: 17.152 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306312
  mean =      3.132 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 726 
    [ 1.250,  2.500) = 15052 
    [ 2.500,  3.750) = 263877 
    [ 3.750,  5.000) = 24819 
    [ 5.000,  6.250) = 1073 
    [ 6.250,  7.500) = 467 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      7.425 ms/op
     p(99.9900) =     16.204 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.692 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
Iteration   1: 4.077 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  12.885 ms/op
                 listUser·p0.9999: 14.548 ms/op
                 listUser·p1.00:   15.466 ms/op

Iteration   2: 3.921 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 15.228 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 3.844 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.052 ms/op
                 listUser·p0.9999: 20.219 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243317
  mean =      3.945 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1760 
    [ 2.500,  5.000) = 227010 
    [ 5.000,  7.500) = 13393 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     19.694 ms/op
     p(99.9990) =     21.318 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.144 ± 5.848  ops/ms
ClientGrpc.existUser                       thrpt       3  10.675 ± 1.863  ops/ms
ClientGrpc.getUser                         thrpt       3   9.983 ± 3.126  ops/ms
ClientGrpc.listUser                        thrpt       3   8.123 ± 1.243  ops/ms
ClientGrpc.createUser                       avgt       3   3.208 ± 0.592   ms/op
ClientGrpc.existUser                        avgt       3   3.115 ± 1.595   ms/op
ClientGrpc.getUser                          avgt       3   3.139 ± 0.625   ms/op
ClientGrpc.listUser                         avgt       3   3.869 ± 0.729   ms/op
ClientGrpc.createUser                     sample  297315   3.227 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.737           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.187           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.547           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.031           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.514           ms/op
ClientGrpc.existUser                      sample  319674   3.001 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.506           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.279           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.743           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.576           ms/op
ClientGrpc.getUser                        sample  306312   3.132 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.667           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.425           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.204           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.579           ms/op
ClientGrpc.listUser                       sample  243317   3.945 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.884           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.353           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.694           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.365           ms/op
