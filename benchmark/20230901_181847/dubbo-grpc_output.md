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
# Warmup Iteration   1: 2.389 ops/ms
# Warmup Iteration   2: 5.685 ops/ms
# Warmup Iteration   3: 7.013 ops/ms
Iteration   1: 7.299 ops/ms
Iteration   2: 7.317 ops/ms
Iteration   3: 7.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.348 ±(99.9%) 1.278 ops/ms [Average]
  (min, avg, max) = (7.299, 7.348, 7.429), stdev = 0.070
  CI (99.9%): [6.071, 8.626] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.402 ops/ms
# Warmup Iteration   2: 7.086 ops/ms
# Warmup Iteration   3: 7.602 ops/ms
Iteration   1: 7.599 ops/ms
Iteration   2: 7.784 ops/ms
Iteration   3: 8.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.844 ±(99.9%) 5.100 ops/ms [Average]
  (min, avg, max) = (7.599, 7.844, 8.148), stdev = 0.280
  CI (99.9%): [2.743, 12.944] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.300 ops/ms
# Warmup Iteration   2: 7.073 ops/ms
# Warmup Iteration   3: 7.299 ops/ms
Iteration   1: 7.169 ops/ms
Iteration   2: 7.404 ops/ms
Iteration   3: 7.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.280 ±(99.9%) 2.154 ops/ms [Average]
  (min, avg, max) = (7.169, 7.280, 7.404), stdev = 0.118
  CI (99.9%): [5.126, 9.434] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ops/ms
# Warmup Iteration   2: 5.393 ops/ms
# Warmup Iteration   3: 5.648 ops/ms
Iteration   1: 5.863 ops/ms
Iteration   2: 5.936 ops/ms
Iteration   3: 5.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.906 ±(99.9%) 0.703 ops/ms [Average]
  (min, avg, max) = (5.863, 5.906, 5.936), stdev = 0.039
  CI (99.9%): [5.203, 6.609] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.551 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.528 ±(99.9%) 0.024 ms/op
Iteration   1: 4.311 ±(99.9%) 0.003 ms/op
Iteration   2: 4.235 ±(99.9%) 0.003 ms/op
Iteration   3: 4.201 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.249 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (4.201, 4.249, 4.311), stdev = 0.056
  CI (99.9%): [3.223, 5.275] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.940 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.011 ms/op
Iteration   1: 4.192 ±(99.9%) 0.004 ms/op
Iteration   2: 4.186 ±(99.9%) 0.004 ms/op
Iteration   3: 4.260 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.213 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (4.186, 4.213, 4.260), stdev = 0.041
  CI (99.9%): [3.457, 4.968] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.227 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.461 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.005 ms/op
Iteration   1: 4.442 ±(99.9%) 0.007 ms/op
Iteration   2: 4.432 ±(99.9%) 0.004 ms/op
Iteration   3: 4.327 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.400 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (4.327, 4.400, 4.442), stdev = 0.064
  CI (99.9%): [3.233, 5.568] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.859 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.948 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.486 ±(99.9%) 0.035 ms/op
Iteration   1: 5.482 ±(99.9%) 0.021 ms/op
Iteration   2: 5.583 ±(99.9%) 0.013 ms/op
Iteration   3: 5.611 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.559 ±(99.9%) 1.242 ms/op [Average]
  (min, avg, max) = (5.482, 5.559, 5.611), stdev = 0.068
  CI (99.9%): [4.317, 6.800] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.588 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.346 ±(99.9%) 0.014 ms/op
Iteration   1: 4.291 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   4.153 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.561 ms/op
                 createUser·p0.999:  12.742 ms/op
                 createUser·p0.9999: 17.846 ms/op
                 createUser·p1.00:   18.448 ms/op

Iteration   2: 4.203 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.084 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.743 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  13.787 ms/op
                 createUser·p0.9999: 31.365 ms/op
                 createUser·p1.00:   33.817 ms/op

Iteration   3: 4.323 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   4.186 ms/op
                 createUser·p0.90:   5.562 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   8.028 ms/op
                 createUser·p0.999:  12.704 ms/op
                 createUser·p0.9999: 20.210 ms/op
                 createUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224829
  mean =      4.272 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5664 
    [ 2.500,  5.000) = 179295 
    [ 5.000,  7.500) = 37238 
    [ 7.500, 10.000) = 2041 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      4.141 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     13.135 ms/op
     p(99.9900) =     30.363 ms/op
     p(99.9990) =     32.343 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.468 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.462 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.013 ms/op
Iteration   1: 4.040 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   7.365 ms/op
                 existUser·p0.999:  10.596 ms/op
                 existUser·p0.9999: 17.107 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 3.951 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  13.915 ms/op
                 existUser·p0.9999: 21.657 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 4.018 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   7.716 ms/op
                 existUser·p0.999:  13.926 ms/op
                 existUser·p0.9999: 23.693 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 239768
  mean =      4.003 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9238 
    [ 2.500,  5.000) = 202086 
    [ 5.000,  7.500) = 26077 
    [ 7.500, 10.000) = 1643 
    [10.000, 12.500) = 383 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     23.102 ms/op
     p(99.9990) =     24.092 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.290 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.460 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.463 ±(99.9%) 0.015 ms/op
Iteration   1: 4.488 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.429 ms/op
                 getUser·p0.50:   4.329 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   8.429 ms/op
                 getUser·p0.999:  13.754 ms/op
                 getUser·p0.9999: 15.399 ms/op
                 getUser·p1.00:   15.860 ms/op

Iteration   2: 4.412 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   7.778 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 19.620 ms/op
                 getUser·p1.00:   19.923 ms/op

Iteration   3: 4.273 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   7.463 ms/op
                 getUser·p0.999:  10.994 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218618
  mean =      4.389 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4218 
    [ 2.500,  5.000) = 169578 
    [ 5.000,  7.500) = 42069 
    [ 7.500, 10.000) = 2132 
    [10.000, 12.500) = 435 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     12.038 ms/op
     p(99.9900) =     19.973 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 7.754 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.126 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 6.071 ±(99.9%) 0.026 ms/op
Iteration   1: 5.797 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   11.174 ms/op
                 listUser·p0.999:  16.838 ms/op
                 listUser·p0.9999: 21.216 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 5.722 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  21.365 ms/op
                 listUser·p0.9999: 25.461 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   3: 5.781 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.925 ms/op
                 listUser·p0.999:  24.369 ms/op
                 listUser·p0.9999: 29.030 ms/op
                 listUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166384
  mean =      5.767 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 53384 
    [ 5.000,  7.500) = 94472 
    [ 7.500, 10.000) = 14889 
    [10.000, 12.500) = 2667 
    [12.500, 15.000) = 452 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.660 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     20.495 ms/op
     p(99.9900) =     27.582 ms/op
     p(99.9990) =     29.481 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.348 ± 1.278  ops/ms
ClientGrpc.existUser                       thrpt       3   7.844 ± 5.100  ops/ms
ClientGrpc.getUser                         thrpt       3   7.280 ± 2.154  ops/ms
ClientGrpc.listUser                        thrpt       3   5.906 ± 0.703  ops/ms
ClientGrpc.createUser                       avgt       3   4.249 ± 1.026   ms/op
ClientGrpc.existUser                        avgt       3   4.213 ± 0.755   ms/op
ClientGrpc.getUser                          avgt       3   4.400 ± 1.167   ms/op
ClientGrpc.listUser                         avgt       3   5.559 ± 1.242   ms/op
ClientGrpc.createUser                     sample  224829   4.272 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.133           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.439           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.972           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.717           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.135           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.363           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.817           ms/op
ClientGrpc.existUser                      sample  239768   4.003 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.671           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.652           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.479           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.550           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.102           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.904           ms/op
ClientGrpc.getUser                        sample  218618   4.389 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.429           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.046           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.832           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.038           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.973           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.692           ms/op
ClientGrpc.listUser                       sample  166384   5.767 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.153           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.321           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.495           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.582           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.590           ms/op
