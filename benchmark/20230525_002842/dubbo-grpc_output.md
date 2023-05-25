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
# Warmup Iteration   1: 2.548 ops/ms
# Warmup Iteration   2: 5.646 ops/ms
# Warmup Iteration   3: 6.906 ops/ms
Iteration   1: 7.294 ops/ms
Iteration   2: 7.405 ops/ms
Iteration   3: 7.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.351 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (7.294, 7.351, 7.405), stdev = 0.056
  CI (99.9%): [6.337, 8.364] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.896 ops/ms
# Warmup Iteration   2: 7.316 ops/ms
# Warmup Iteration   3: 7.584 ops/ms
Iteration   1: 8.272 ops/ms
Iteration   2: 7.960 ops/ms
Iteration   3: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.045 ±(99.9%) 3.625 ops/ms [Average]
  (min, avg, max) = (7.903, 8.045, 8.272), stdev = 0.199
  CI (99.9%): [4.421, 11.670] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.172 ops/ms
# Warmup Iteration   2: 6.891 ops/ms
# Warmup Iteration   3: 7.478 ops/ms
Iteration   1: 7.713 ops/ms
Iteration   2: 7.616 ops/ms
Iteration   3: 7.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.666 ±(99.9%) 0.882 ops/ms [Average]
  (min, avg, max) = (7.616, 7.666, 7.713), stdev = 0.048
  CI (99.9%): [6.783, 8.548] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ops/ms
# Warmup Iteration   2: 4.953 ops/ms
# Warmup Iteration   3: 5.601 ops/ms
Iteration   1: 5.711 ops/ms
Iteration   2: 5.788 ops/ms
Iteration   3: 5.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.717 ±(99.9%) 1.246 ops/ms [Average]
  (min, avg, max) = (5.651, 5.717, 5.788), stdev = 0.068
  CI (99.9%): [4.471, 6.962] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.674 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.533 ±(99.9%) 0.009 ms/op
Iteration   1: 4.451 ±(99.9%) 0.004 ms/op
Iteration   2: 4.287 ±(99.9%) 0.002 ms/op
Iteration   3: 4.382 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.373 ±(99.9%) 1.504 ms/op [Average]
  (min, avg, max) = (4.287, 4.373, 4.451), stdev = 0.082
  CI (99.9%): [2.869, 5.877] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.120 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.002 ms/op
Iteration   1: 4.113 ±(99.9%) 0.004 ms/op
Iteration   2: 3.982 ±(99.9%) 0.002 ms/op
Iteration   3: 4.145 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.080 ±(99.9%) 1.574 ms/op [Average]
  (min, avg, max) = (3.982, 4.080, 4.145), stdev = 0.086
  CI (99.9%): [2.506, 5.654] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.511 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.446 ±(99.9%) 0.003 ms/op
Iteration   1: 4.295 ±(99.9%) 0.003 ms/op
Iteration   2: 4.262 ±(99.9%) 0.003 ms/op
Iteration   3: 4.198 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.252 ±(99.9%) 0.906 ms/op [Average]
  (min, avg, max) = (4.198, 4.252, 4.295), stdev = 0.050
  CI (99.9%): [3.346, 5.158] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.654 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.968 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.807 ±(99.9%) 0.017 ms/op
Iteration   1: 5.558 ±(99.9%) 0.014 ms/op
Iteration   2: 5.582 ±(99.9%) 0.016 ms/op
Iteration   3: 5.417 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.519 ±(99.9%) 1.624 ms/op [Average]
  (min, avg, max) = (5.417, 5.519, 5.582), stdev = 0.089
  CI (99.9%): [3.895, 7.143] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.547 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.795 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.337 ±(99.9%) 0.012 ms/op
Iteration   1: 4.295 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   4.190 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   5.693 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  12.521 ms/op
                 createUser·p0.9999: 16.876 ms/op
                 createUser·p1.00:   17.400 ms/op

Iteration   2: 4.374 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.877 ms/op
                 createUser·p0.999:  13.121 ms/op
                 createUser·p0.9999: 17.684 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   3: 4.431 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.423 ms/op
                 createUser·p0.95:   5.882 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  15.218 ms/op
                 createUser·p0.9999: 28.140 ms/op
                 createUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219840
  mean =      4.366 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3417 
    [ 2.500,  5.000) = 177024 
    [ 5.000,  7.500) = 36947 
    [ 7.500, 10.000) = 1861 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     13.208 ms/op
     p(99.9900) =     27.723 ms/op
     p(99.9990) =     28.489 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.379 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.009 ms/op
Iteration   1: 4.136 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  9.874 ms/op
                 existUser·p0.9999: 16.741 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 4.156 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   4.022 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   8.061 ms/op
                 existUser·p0.999:  12.142 ms/op
                 existUser·p0.9999: 15.450 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   3: 4.118 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   7.373 ms/op
                 existUser·p0.999:  12.231 ms/op
                 existUser·p0.9999: 19.570 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 232011
  mean =      4.136 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5615 
    [ 2.500,  5.000) = 198661 
    [ 5.000,  7.500) = 25498 
    [ 7.500, 10.000) = 1720 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     18.802 ms/op
     p(99.9990) =     19.891 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 6.564 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.783 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.369 ±(99.9%) 0.013 ms/op
Iteration   1: 4.343 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  13.562 ms/op
                 getUser·p0.9999: 26.313 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 4.399 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.489 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   8.054 ms/op
                 getUser·p0.999:  13.517 ms/op
                 getUser·p0.9999: 23.969 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 4.272 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   4.157 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  12.197 ms/op
                 getUser·p0.9999: 27.050 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221145
  mean =      4.337 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2716 
    [ 2.500,  5.000) = 183312 
    [ 5.000,  7.500) = 32894 
    [ 7.500, 10.000) = 1750 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     26.637 ms/op
     p(99.9990) =     27.453 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.780 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 5.769 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.453 ±(99.9%) 0.019 ms/op
Iteration   1: 5.468 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  25.508 ms/op
                 listUser·p0.9999: 33.554 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   2: 5.302 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   6.742 ms/op
                 listUser·p0.95:   7.766 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  22.076 ms/op
                 listUser·p0.9999: 28.704 ms/op
                 listUser·p1.00:   29.393 ms/op

Iteration   3: 5.358 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  22.314 ms/op
                 listUser·p0.9999: 25.496 ms/op
                 listUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178533
  mean =      5.375 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 146 
    [ 2.500,  5.000) = 78366 
    [ 5.000,  7.500) = 88178 
    [ 7.500, 10.000) = 10019 
    [10.000, 12.500) = 1243 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      7.881 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     22.608 ms/op
     p(99.9900) =     32.778 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.351 ± 1.014  ops/ms
ClientGrpc.existUser                       thrpt       3   8.045 ± 3.625  ops/ms
ClientGrpc.getUser                         thrpt       3   7.666 ± 0.882  ops/ms
ClientGrpc.listUser                        thrpt       3   5.717 ± 1.246  ops/ms
ClientGrpc.createUser                       avgt       3   4.373 ± 1.504   ms/op
ClientGrpc.existUser                        avgt       3   4.080 ± 1.574   ms/op
ClientGrpc.getUser                          avgt       3   4.252 ± 0.906   ms/op
ClientGrpc.listUser                         avgt       3   5.519 ± 1.624   ms/op
ClientGrpc.createUser                     sample  219840   4.366 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.106           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.349           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.792           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.676           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.208           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.723           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.574           ms/op
ClientGrpc.existUser                      sample  232011   4.136 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.106           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.018           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.112           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.562           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.438           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.715           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.802           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.021           ms/op
ClientGrpc.getUser                        sample  221145   4.337 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.949           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.775           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.512           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.124           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.637           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.787           ms/op
ClientGrpc.listUser                       sample  178533   5.375 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.303           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.881           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.027           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.608           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.778           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.079           ms/op
