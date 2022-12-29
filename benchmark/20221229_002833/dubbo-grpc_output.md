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
# Warmup Iteration   1: 2.221 ops/ms
# Warmup Iteration   2: 4.825 ops/ms
# Warmup Iteration   3: 6.396 ops/ms
Iteration   1: 6.398 ops/ms
Iteration   2: 6.397 ops/ms
Iteration   3: 6.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.490 ±(99.9%) 2.905 ops/ms [Average]
  (min, avg, max) = (6.397, 6.490, 6.674), stdev = 0.159
  CI (99.9%): [3.585, 9.395] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.350 ops/ms
# Warmup Iteration   2: 6.196 ops/ms
# Warmup Iteration   3: 6.714 ops/ms
Iteration   1: 6.814 ops/ms
Iteration   2: 6.618 ops/ms
Iteration   3: 7.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.828 ±(99.9%) 3.979 ops/ms [Average]
  (min, avg, max) = (6.618, 6.828, 7.053), stdev = 0.218
  CI (99.9%): [2.849, 10.807] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ops/ms
# Warmup Iteration   2: 5.932 ops/ms
# Warmup Iteration   3: 6.205 ops/ms
Iteration   1: 6.352 ops/ms
Iteration   2: 6.340 ops/ms
Iteration   3: 6.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.491 ±(99.9%) 4.599 ops/ms [Average]
  (min, avg, max) = (6.340, 6.491, 6.783), stdev = 0.252
  CI (99.9%): [1.892, 11.091] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ops/ms
# Warmup Iteration   2: 4.503 ops/ms
# Warmup Iteration   3: 4.778 ops/ms
Iteration   1: 4.945 ops/ms
Iteration   2: 5.239 ops/ms
Iteration   3: 5.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.072 ±(99.9%) 2.747 ops/ms [Average]
  (min, avg, max) = (4.945, 5.072, 5.239), stdev = 0.151
  CI (99.9%): [2.325, 7.820] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.809 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.279 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.193 ±(99.9%) 0.005 ms/op
Iteration   1: 4.894 ±(99.9%) 0.005 ms/op
Iteration   2: 4.994 ±(99.9%) 0.004 ms/op
Iteration   3: 5.258 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.048 ±(99.9%) 3.434 ms/op [Average]
  (min, avg, max) = (4.894, 5.048, 5.258), stdev = 0.188
  CI (99.9%): [1.614, 8.483] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.647 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.002 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.917 ±(99.9%) 0.004 ms/op
Iteration   1: 4.785 ±(99.9%) 0.004 ms/op
Iteration   2: 4.856 ±(99.9%) 0.004 ms/op
Iteration   3: 4.860 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.833 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (4.785, 4.833, 4.860), stdev = 0.042
  CI (99.9%): [4.061, 5.606] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.911 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.610 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.226 ±(99.9%) 0.007 ms/op
Iteration   1: 5.142 ±(99.9%) 0.004 ms/op
Iteration   2: 5.272 ±(99.9%) 0.004 ms/op
Iteration   3: 4.966 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.126 ±(99.9%) 2.799 ms/op [Average]
  (min, avg, max) = (4.966, 5.126, 5.272), stdev = 0.153
  CI (99.9%): [2.328, 7.925] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.285 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.146 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.299 ±(99.9%) 0.019 ms/op
Iteration   1: 6.142 ±(99.9%) 0.018 ms/op
Iteration   2: 6.335 ±(99.9%) 0.012 ms/op
Iteration   3: 6.237 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.238 ±(99.9%) 1.757 ms/op [Average]
  (min, avg, max) = (6.142, 6.238, 6.335), stdev = 0.096
  CI (99.9%): [4.481, 7.995] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.266 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.251 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.282 ±(99.9%) 0.019 ms/op
Iteration   1: 5.059 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.521 ms/op
                 createUser·p0.95:   7.160 ms/op
                 createUser·p0.99:   9.404 ms/op
                 createUser·p0.999:  13.776 ms/op
                 createUser·p0.9999: 30.333 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   2: 5.011 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   6.906 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  13.536 ms/op
                 createUser·p0.9999: 18.469 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   3: 5.087 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.004 ms/op
                 createUser·p0.99:   9.372 ms/op
                 createUser·p0.999:  13.255 ms/op
                 createUser·p0.9999: 21.424 ms/op
                 createUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 189964
  mean =      5.052 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1580 
    [ 2.500,  5.000) = 100794 
    [ 5.000,  7.500) = 81648 
    [ 7.500, 10.000) = 4687 
    [10.000, 12.500) = 940 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     28.870 ms/op
     p(99.9990) =     30.576 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.965 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.104 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.894 ±(99.9%) 0.018 ms/op
Iteration   1: 4.727 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   4.612 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   6.636 ms/op
                 existUser·p0.99:   8.628 ms/op
                 existUser·p0.999:  12.297 ms/op
                 existUser·p0.9999: 22.691 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 4.643 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.988 ms/op
                 existUser·p0.95:   6.431 ms/op
                 existUser·p0.99:   7.847 ms/op
                 existUser·p0.999:  11.798 ms/op
                 existUser·p0.9999: 24.059 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 4.681 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   6.562 ms/op
                 existUser·p0.99:   8.169 ms/op
                 existUser·p0.999:  14.055 ms/op
                 existUser·p0.9999: 22.353 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 204933
  mean =      4.684 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4773 
    [ 2.500,  5.000) = 128445 
    [ 5.000,  7.500) = 68171 
    [ 7.500, 10.000) = 2913 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     12.604 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     24.278 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.002 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 5.357 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.095 ±(99.9%) 0.016 ms/op
Iteration   1: 5.111 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.463 ms/op
                 getUser·p0.95:   7.000 ms/op
                 getUser·p0.99:   8.634 ms/op
                 getUser·p0.999:  12.173 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   2: 4.915 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   6.144 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   8.177 ms/op
                 getUser·p0.999:  13.122 ms/op
                 getUser·p0.9999: 19.381 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   3: 5.071 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.472 ms/op
                 getUser·p0.95:   7.021 ms/op
                 getUser·p0.99:   9.404 ms/op
                 getUser·p0.999:  12.545 ms/op
                 getUser·p0.9999: 23.870 ms/op
                 getUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 190782
  mean =      5.031 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1605 
    [ 2.500,  5.000) = 100683 
    [ 5.000,  7.500) = 83713 
    [ 7.500, 10.000) = 3791 
    [10.000, 12.500) = 801 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      6.881 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     19.855 ms/op
     p(99.9990) =     24.356 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.494 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.834 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.230 ±(99.9%) 0.024 ms/op
Iteration   1: 6.141 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   8.159 ms/op
                 listUser·p0.95:   9.322 ms/op
                 listUser·p0.99:   11.684 ms/op
                 listUser·p0.999:  22.476 ms/op
                 listUser·p0.9999: 34.248 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   2: 6.243 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   8.126 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  17.851 ms/op
                 listUser·p0.9999: 19.952 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 6.290 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.851 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   8.217 ms/op
                 listUser·p0.95:   9.241 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  24.674 ms/op
                 listUser·p0.9999: 36.694 ms/op
                 listUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154231
  mean =      6.224 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 28071 
    [ 5.000,  7.500) = 102336 
    [ 7.500, 10.000) = 19310 
    [10.000, 12.500) = 3561 
    [12.500, 15.000) = 579 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      5.923 ms/op
     p(90.0000) =      8.167 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     21.758 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     37.088 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.490 ± 2.905  ops/ms
ClientGrpc.existUser                       thrpt       3   6.828 ± 3.979  ops/ms
ClientGrpc.getUser                         thrpt       3   6.491 ± 4.599  ops/ms
ClientGrpc.listUser                        thrpt       3   5.072 ± 2.747  ops/ms
ClientGrpc.createUser                       avgt       3   5.048 ± 3.434   ms/op
ClientGrpc.existUser                        avgt       3   4.833 ± 0.773   ms/op
ClientGrpc.getUser                          avgt       3   5.126 ± 2.799   ms/op
ClientGrpc.listUser                         avgt       3   6.238 ± 1.757   ms/op
ClientGrpc.createUser                     sample  189964   5.052 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.961           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.431           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.029           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.241           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.517           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.870           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.605           ms/op
ClientGrpc.existUser                      sample  204933   4.684 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.047           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.070           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.537           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.282           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.604           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.708           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.379           ms/op
ClientGrpc.getUser                        sample  190782   5.031 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.118           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.365           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.881           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.733           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.485           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.855           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.445           ms/op
ClientGrpc.listUser                       sample  154231   6.224 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.649           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.167           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.191           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.600           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.758           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.603           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.159           ms/op
