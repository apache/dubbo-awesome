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
# Warmup Iteration   1: 4.183 ops/ms
# Warmup Iteration   2: 8.561 ops/ms
# Warmup Iteration   3: 9.689 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.384 ±(99.9%) 1.869 ops/ms [Average]
  (min, avg, max) = (10.299, 10.384, 10.498), stdev = 0.102
  CI (99.9%): [8.515, 12.253] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.054 ops/ms
# Warmup Iteration   2: 10.282 ops/ms
# Warmup Iteration   3: 11.008 ops/ms
Iteration   1: 11.213 ops/ms
Iteration   2: 10.837 ops/ms
Iteration   3: 11.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.118 ±(99.9%) 4.531 ops/ms [Average]
  (min, avg, max) = (10.837, 11.118, 11.306), stdev = 0.248
  CI (99.9%): [6.588, 15.649] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.903 ops/ms
# Warmup Iteration   2: 9.727 ops/ms
# Warmup Iteration   3: 10.305 ops/ms
Iteration   1: 10.340 ops/ms
Iteration   2: 10.399 ops/ms
Iteration   3: 10.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.411 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (10.340, 10.411, 10.494), stdev = 0.078
  CI (99.9%): [8.993, 11.829] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.496 ops/ms
# Warmup Iteration   2: 7.523 ops/ms
# Warmup Iteration   3: 7.767 ops/ms
Iteration   1: 7.697 ops/ms
Iteration   2: 7.856 ops/ms
Iteration   3: 7.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.725 ±(99.9%) 2.189 ops/ms [Average]
  (min, avg, max) = (7.621, 7.725, 7.856), stdev = 0.120
  CI (99.9%): [5.535, 9.914] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.802 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.003 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
Iteration   3: 3.198 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.162 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.097, 3.162, 3.198), stdev = 0.057
  CI (99.9%): [2.127, 4.198] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.264 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 2.963 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 2.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.969 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (2.949, 2.969, 2.994), stdev = 0.023
  CI (99.9%): [2.550, 3.387] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.329 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.002 ms/op
Iteration   1: 3.027 ±(99.9%) 0.004 ms/op
Iteration   2: 3.033 ±(99.9%) 0.004 ms/op
Iteration   3: 3.065 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.042 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.027, 3.042, 3.065), stdev = 0.020
  CI (99.9%): [2.675, 3.409] (assumes normal distribution)


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
# Warmup Iteration   1: 5.853 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.022 ms/op
Iteration   1: 4.067 ±(99.9%) 0.018 ms/op
Iteration   2: 4.036 ±(99.9%) 0.016 ms/op
Iteration   3: 4.065 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.056 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (4.036, 4.056, 4.067), stdev = 0.017
  CI (99.9%): [3.740, 4.371] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.348 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 13.316 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  8.223 ms/op
                 createUser·p0.9999: 18.697 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  8.433 ms/op
                 createUser·p0.9999: 16.283 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308815
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19789 
    [ 2.500,  5.000) = 285918 
    [ 5.000,  7.500) = 2482 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      8.408 ms/op
     p(99.9900) =     17.994 ms/op
     p(99.9990) =     21.804 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.197 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.077 ms/op
                 existUser·p0.9999: 12.908 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  8.042 ms/op
                 existUser·p0.9999: 14.696 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.778 ms/op
                 existUser·p0.9999: 28.092 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320637
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21836 
    [ 2.500,  5.000) = 296862 
    [ 5.000,  7.500) = 1448 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.012 ms/op
     p(99.9900) =     26.746 ms/op
     p(99.9990) =     28.396 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
Iteration   1: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  9.041 ms/op
                 getUser·p0.9999: 17.138 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.287 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  8.239 ms/op
                 getUser·p0.9999: 19.126 ms/op
                 getUser·p1.00:   20.054 ms/op

Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  9.839 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297471
  mean =      3.229 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14337 
    [ 2.500,  5.000) = 278749 
    [ 5.000,  7.500) = 3625 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.287 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     18.489 ms/op
     p(99.9990) =     19.925 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 6.487 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
Iteration   1: 4.015 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  19.395 ms/op
                 listUser·p0.9999: 25.200 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 4.083 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 22.161 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.189 ms/op
                 listUser·p0.9999: 28.672 ms/op
                 listUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236059
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2111 
    [ 2.500,  5.000) = 209674 
    [ 5.000,  7.500) = 22293 
    [ 7.500, 10.000) = 1429 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     27.800 ms/op
     p(99.9990) =     29.018 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.384 ± 1.869  ops/ms
ClientGrpc.existUser                       thrpt       3  11.118 ± 4.531  ops/ms
ClientGrpc.getUser                         thrpt       3  10.411 ± 1.418  ops/ms
ClientGrpc.listUser                        thrpt       3   7.725 ± 2.189  ops/ms
ClientGrpc.createUser                       avgt       3   3.162 ± 1.035   ms/op
ClientGrpc.existUser                        avgt       3   2.969 ± 0.418   ms/op
ClientGrpc.getUser                          avgt       3   3.042 ± 0.367   ms/op
ClientGrpc.listUser                         avgt       3   4.056 ± 0.315   ms/op
ClientGrpc.createUser                     sample  308815   3.107 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.864           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.005           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.408           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.994           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  320637   2.994 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.691           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.012           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.746           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.508           ms/op
ClientGrpc.getUser                        sample  297471   3.229 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.287           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.308           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.175           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.489           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.054           ms/op
ClientGrpc.listUser                       sample  236059   4.068 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.200           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.800           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.098           ms/op
