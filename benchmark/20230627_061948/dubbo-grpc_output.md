# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.342 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 8.950 ops/ms
Iteration   1: 9.507 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 9.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.406 ±(99.9%) 3.624 ops/ms [Average]
  (min, avg, max) = (9.177, 9.406, 9.534), stdev = 0.199
  CI (99.9%): [5.782, 13.030] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.282 ops/ms
# Warmup Iteration   2: 8.992 ops/ms
# Warmup Iteration   3: 9.771 ops/ms
Iteration   1: 9.823 ops/ms
Iteration   2: 9.921 ops/ms
Iteration   3: 9.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.874 ±(99.9%) 0.896 ops/ms [Average]
  (min, avg, max) = (9.823, 9.874, 9.921), stdev = 0.049
  CI (99.9%): [8.978, 10.770] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 5.857 ops/ms
# Warmup Iteration   2: 8.782 ops/ms
# Warmup Iteration   3: 9.022 ops/ms
Iteration   1: 9.237 ops/ms
Iteration   2: 9.444 ops/ms
Iteration   3: 9.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.369 ±(99.9%) 2.085 ops/ms [Average]
  (min, avg, max) = (9.237, 9.369, 9.444), stdev = 0.114
  CI (99.9%): [7.284, 11.454] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.611 ops/ms
# Warmup Iteration   2: 6.675 ops/ms
# Warmup Iteration   3: 6.984 ops/ms
Iteration   1: 7.081 ops/ms
Iteration   2: 7.089 ops/ms
Iteration   3: 7.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.138 ±(99.9%) 1.677 ops/ms [Average]
  (min, avg, max) = (7.081, 7.138, 7.244), stdev = 0.092
  CI (99.9%): [5.461, 8.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.148 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.011 ms/op
Iteration   1: 3.467 ±(99.9%) 0.003 ms/op
Iteration   2: 3.452 ±(99.9%) 0.003 ms/op
Iteration   3: 3.367 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.429 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.367, 3.429, 3.467), stdev = 0.054
  CI (99.9%): [2.453, 4.405] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.474 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.002 ms/op
Iteration   1: 3.253 ±(99.9%) 0.003 ms/op
Iteration   2: 3.271 ±(99.9%) 0.003 ms/op
Iteration   3: 3.222 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.249 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.222, 3.249, 3.271), stdev = 0.025
  CI (99.9%): [2.794, 3.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.087 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.003 ms/op
Iteration   1: 3.554 ±(99.9%) 0.004 ms/op
Iteration   2: 3.494 ±(99.9%) 0.002 ms/op
Iteration   3: 3.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.517 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.494, 3.517, 3.554), stdev = 0.032
  CI (99.9%): [2.932, 4.103] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.423 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.660 ±(99.9%) 0.013 ms/op
Iteration   1: 4.705 ±(99.9%) 0.019 ms/op
Iteration   2: 4.618 ±(99.9%) 0.010 ms/op
Iteration   3: 4.699 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.674 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (4.618, 4.674, 4.705), stdev = 0.049
  CI (99.9%): [3.782, 5.566] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.030 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.775 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.010 ms/op
Iteration   1: 3.532 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 20.742 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.502 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.428 ms/op
                 createUser·p0.999:  8.365 ms/op
                 createUser·p0.9999: 18.809 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   3: 3.551 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  8.799 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271949
  mean =      3.528 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7433 
    [ 2.500,  5.000) = 259494 
    [ 5.000,  7.500) = 4421 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     19.851 ms/op
     p(99.9990) =     20.948 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.665 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.009 ms/op
Iteration   1: 3.387 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  10.184 ms/op
                 existUser·p0.9999: 21.401 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   2: 3.384 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  9.445 ms/op
                 existUser·p0.9999: 23.382 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   3: 3.402 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282946
  mean =      3.391 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15004 
    [ 2.500,  5.000) = 263300 
    [ 5.000,  7.500) = 4050 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     22.043 ms/op
     p(99.9990) =     23.806 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.196 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.008 ms/op
Iteration   1: 3.555 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  9.279 ms/op
                 getUser·p0.9999: 15.565 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   2: 3.508 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  9.284 ms/op
                 getUser·p0.9999: 19.879 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   3: 3.554 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  10.830 ms/op
                 getUser·p0.9999: 20.120 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 271015
  mean =      3.539 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9955 
    [ 2.500,  5.000) = 254318 
    [ 5.000,  7.500) = 5813 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =      9.814 ms/op
     p(99.9900) =     19.559 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.486 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.516 ±(99.9%) 0.013 ms/op
Iteration   1: 4.559 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  13.317 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 4.386 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  15.500 ms/op
                 listUser·p0.9999: 22.276 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 4.380 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 216185
  mean =      4.440 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 950 
    [ 2.500,  5.000) = 178824 
    [ 5.000,  7.500) = 33101 
    [ 7.500, 10.000) = 2804 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.341 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     15.261 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     22.763 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.406 ± 3.624  ops/ms
ClientGrpc.existUser                       thrpt       3   9.874 ± 0.896  ops/ms
ClientGrpc.getUser                         thrpt       3   9.369 ± 2.085  ops/ms
ClientGrpc.listUser                        thrpt       3   7.138 ± 1.677  ops/ms
ClientGrpc.createUser                       avgt       3   3.429 ± 0.976   ms/op
ClientGrpc.existUser                        avgt       3   3.249 ± 0.455   ms/op
ClientGrpc.getUser                          avgt       3   3.517 ± 0.586   ms/op
ClientGrpc.listUser                         avgt       3   4.674 ± 0.892   ms/op
ClientGrpc.createUser                     sample  271949   3.528 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.771           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.133           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.569           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.851           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.953           ms/op
ClientGrpc.existUser                      sample  282946   3.391 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.865           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.423           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.585           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.043           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.953           ms/op
ClientGrpc.getUser                        sample  271015   3.539 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.673           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.915           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.814           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.559           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.086           ms/op
ClientGrpc.listUser                       sample  216185   4.440 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.792           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.284           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.341           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.913           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.261           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.758           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.839           ms/op
