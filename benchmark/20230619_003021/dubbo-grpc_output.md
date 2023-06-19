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
# Warmup Iteration   1: 2.107 ops/ms
# Warmup Iteration   2: 5.148 ops/ms
# Warmup Iteration   3: 6.403 ops/ms
Iteration   1: 6.773 ops/ms
Iteration   2: 6.558 ops/ms
Iteration   3: 7.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.853 ±(99.9%) 6.228 ops/ms [Average]
  (min, avg, max) = (6.558, 6.853, 7.227), stdev = 0.341
  CI (99.9%): [0.625, 13.081] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.698 ops/ms
# Warmup Iteration   2: 6.949 ops/ms
# Warmup Iteration   3: 7.244 ops/ms
Iteration   1: 7.383 ops/ms
Iteration   2: 7.287 ops/ms
Iteration   3: 7.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.238 ±(99.9%) 3.191 ops/ms [Average]
  (min, avg, max) = (7.043, 7.238, 7.383), stdev = 0.175
  CI (99.9%): [4.046, 10.429] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.702 ops/ms
# Warmup Iteration   2: 6.341 ops/ms
# Warmup Iteration   3: 7.211 ops/ms
Iteration   1: 7.371 ops/ms
Iteration   2: 7.097 ops/ms
Iteration   3: 7.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.174 ±(99.9%) 3.149 ops/ms [Average]
  (min, avg, max) = (7.053, 7.174, 7.371), stdev = 0.173
  CI (99.9%): [4.025, 10.322] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.584 ops/ms
# Warmup Iteration   2: 5.177 ops/ms
# Warmup Iteration   3: 5.532 ops/ms
Iteration   1: 5.524 ops/ms
Iteration   2: 5.586 ops/ms
Iteration   3: 5.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.604 ±(99.9%) 1.638 ops/ms [Average]
  (min, avg, max) = (5.524, 5.604, 5.701), stdev = 0.090
  CI (99.9%): [3.966, 7.241] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.211 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.881 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.749 ±(99.9%) 0.010 ms/op
Iteration   1: 4.697 ±(99.9%) 0.003 ms/op
Iteration   2: 4.627 ±(99.9%) 0.007 ms/op
Iteration   3: 4.688 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.671 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (4.627, 4.671, 4.697), stdev = 0.038
  CI (99.9%): [3.978, 5.364] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.644 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.004 ms/op
Iteration   1: 4.156 ±(99.9%) 0.002 ms/op
Iteration   2: 4.203 ±(99.9%) 0.003 ms/op
Iteration   3: 4.076 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.145 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (4.076, 4.145, 4.203), stdev = 0.064
  CI (99.9%): [2.978, 5.312] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.999 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.802 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.569 ±(99.9%) 0.011 ms/op
Iteration   1: 4.357 ±(99.9%) 0.003 ms/op
Iteration   2: 4.568 ±(99.9%) 0.003 ms/op
Iteration   3: 4.571 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.499 ±(99.9%) 2.239 ms/op [Average]
  (min, avg, max) = (4.357, 4.499, 4.571), stdev = 0.123
  CI (99.9%): [2.259, 6.738] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.487 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 6.091 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.558 ±(99.9%) 0.016 ms/op
Iteration   1: 5.463 ±(99.9%) 0.008 ms/op
Iteration   2: 5.393 ±(99.9%) 0.010 ms/op
Iteration   3: 5.672 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.509 ±(99.9%) 2.648 ms/op [Average]
  (min, avg, max) = (5.393, 5.509, 5.672), stdev = 0.145
  CI (99.9%): [2.861, 8.157] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.953 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.032 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.543 ±(99.9%) 0.013 ms/op
Iteration   1: 4.347 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.456 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  10.289 ms/op
                 createUser·p0.9999: 17.355 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   2: 4.411 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.782 ms/op
                 createUser·p0.999:  12.748 ms/op
                 createUser·p0.9999: 28.500 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 4.511 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.930 ms/op
                 createUser·p0.999:  10.863 ms/op
                 createUser·p0.9999: 21.135 ms/op
                 createUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217248
  mean =      4.422 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4021 
    [ 2.500,  5.000) = 168623 
    [ 5.000,  7.500) = 42387 
    [ 7.500, 10.000) = 1734 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     27.501 ms/op
     p(99.9990) =     29.212 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.222 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.597 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.012 ms/op
Iteration   1: 4.186 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.644 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  10.021 ms/op
                 existUser·p0.9999: 17.784 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 4.072 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.981 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   7.278 ms/op
                 existUser·p0.999:  10.411 ms/op
                 existUser·p0.9999: 19.198 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 4.011 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  12.403 ms/op
                 existUser·p0.9999: 31.263 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 234641
  mean =      4.089 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7112 
    [ 2.500,  5.000) = 202243 
    [ 5.000,  7.500) = 23619 
    [ 7.500, 10.000) = 1241 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     11.835 ms/op
     p(99.9900) =     30.560 ms/op
     p(99.9990) =     31.685 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.767 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.719 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.497 ±(99.9%) 0.013 ms/op
Iteration   1: 4.345 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  13.133 ms/op
                 getUser·p0.9999: 28.615 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   2: 4.479 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  14.008 ms/op
                 getUser·p0.9999: 34.800 ms/op
                 getUser·p1.00:   34.865 ms/op

Iteration   3: 4.510 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.644 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  12.629 ms/op
                 getUser·p0.9999: 34.007 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216019
  mean =      4.443 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4636 
    [ 2.500,  5.000) = 168538 
    [ 5.000,  7.500) = 39886 
    [ 7.500, 10.000) = 2196 
    [10.000, 12.500) = 466 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 52 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     34.629 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 8.701 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 6.364 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.817 ±(99.9%) 0.022 ms/op
Iteration   1: 5.825 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  19.177 ms/op
                 listUser·p0.9999: 23.512 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 5.784 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  19.651 ms/op
                 listUser·p0.9999: 28.364 ms/op
                 listUser·p1.00:   29.393 ms/op

Iteration   3: 5.654 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.266 ms/op
                 listUser·p0.99:   10.666 ms/op
                 listUser·p0.999:  27.028 ms/op
                 listUser·p0.9999: 38.470 ms/op
                 listUser·p1.00:   38.666 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166773
  mean =      5.754 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 46044 
    [ 5.000,  7.500) = 104729 
    [ 7.500, 10.000) = 13313 
    [10.000, 12.500) = 1960 
    [12.500, 15.000) = 342 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.438 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     20.706 ms/op
     p(99.9900) =     37.421 ms/op
     p(99.9990) =     38.666 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.853 ± 6.228  ops/ms
ClientGrpc.existUser                       thrpt       3   7.238 ± 3.191  ops/ms
ClientGrpc.getUser                         thrpt       3   7.174 ± 3.149  ops/ms
ClientGrpc.listUser                        thrpt       3   5.604 ± 1.638  ops/ms
ClientGrpc.createUser                       avgt       3   4.671 ± 0.693   ms/op
ClientGrpc.existUser                        avgt       3   4.145 ± 1.167   ms/op
ClientGrpc.getUser                          avgt       3   4.499 ± 2.239   ms/op
ClientGrpc.listUser                         avgt       3   5.509 ± 2.648   ms/op
ClientGrpc.createUser                     sample  217248   4.422 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.057           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.480           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.528           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.256           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.501           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.327           ms/op
ClientGrpc.existUser                      sample  234641   4.089 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.733           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.054           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.513           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.963           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.835           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.560           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.818           ms/op
ClientGrpc.getUser                        sample  216019   4.443 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.013           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.062           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.020           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.353           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.629           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.865           ms/op
ClientGrpc.listUser                       sample  166773   5.754 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.475           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.438           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.421           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.748           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.706           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.421           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.666           ms/op
