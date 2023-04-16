# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ops/ms
# Warmup Iteration   2: 7.465 ops/ms
# Warmup Iteration   3: 8.511 ops/ms
Iteration   1: 9.101 ops/ms
Iteration   2: 9.120 ops/ms
Iteration   3: 9.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.143 ±(99.9%) 1.043 ops/ms [Average]
  (min, avg, max) = (9.101, 9.143, 9.208), stdev = 0.057
  CI (99.9%): [8.100, 10.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.148 ops/ms
# Warmup Iteration   2: 8.985 ops/ms
# Warmup Iteration   3: 9.455 ops/ms
Iteration   1: 9.518 ops/ms
Iteration   2: 9.730 ops/ms
Iteration   3: 9.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.730 ±(99.9%) 3.881 ops/ms [Average]
  (min, avg, max) = (9.518, 9.730, 9.943), stdev = 0.213
  CI (99.9%): [5.849, 13.611] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.454 ops/ms
# Warmup Iteration   2: 8.525 ops/ms
# Warmup Iteration   3: 8.938 ops/ms
Iteration   1: 9.028 ops/ms
Iteration   2: 9.249 ops/ms
Iteration   3: 9.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.193 ±(99.9%) 2.664 ops/ms [Average]
  (min, avg, max) = (9.028, 9.193, 9.303), stdev = 0.146
  CI (99.9%): [6.530, 11.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ops/ms
# Warmup Iteration   2: 6.665 ops/ms
# Warmup Iteration   3: 7.005 ops/ms
Iteration   1: 7.092 ops/ms
Iteration   2: 7.208 ops/ms
Iteration   3: 7.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.165 ±(99.9%) 1.160 ops/ms [Average]
  (min, avg, max) = (7.092, 7.165, 7.208), stdev = 0.064
  CI (99.9%): [6.005, 8.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.347 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.008 ms/op
Iteration   1: 3.541 ±(99.9%) 0.003 ms/op
Iteration   2: 3.569 ±(99.9%) 0.001 ms/op
Iteration   3: 3.542 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.551 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (3.541, 3.551, 3.569), stdev = 0.016
  CI (99.9%): [3.262, 3.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.679 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.003 ms/op
Iteration   1: 3.325 ±(99.9%) 0.003 ms/op
Iteration   2: 3.375 ±(99.9%) 0.003 ms/op
Iteration   3: 3.348 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.349 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (3.325, 3.349, 3.375), stdev = 0.025
  CI (99.9%): [2.897, 3.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.180 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.003 ms/op
Iteration   1: 3.473 ±(99.9%) 0.004 ms/op
Iteration   2: 3.518 ±(99.9%) 0.004 ms/op
Iteration   3: 3.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.486 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.466, 3.486, 3.518), stdev = 0.028
  CI (99.9%): [2.972, 3.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.505 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.754 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 4.572 ±(99.9%) 0.033 ms/op
Iteration   1: 4.509 ±(99.9%) 0.016 ms/op
Iteration   2: 4.557 ±(99.9%) 0.017 ms/op
Iteration   3: 4.451 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.506 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (4.451, 4.506, 4.557), stdev = 0.053
  CI (99.9%): [3.540, 5.472] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.846 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.008 ms/op
Iteration   1: 3.575 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 23.134 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.474 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  12.407 ms/op
                 createUser·p0.9999: 20.499 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   3: 3.535 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  10.870 ms/op
                 createUser·p0.9999: 19.462 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 272302
  mean =      3.528 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9973 
    [ 2.500,  5.000) = 257663 
    [ 5.000,  7.500) = 4075 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     10.694 ms/op
     p(99.9900) =     22.733 ms/op
     p(99.9990) =     23.316 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.786 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.008 ms/op
Iteration   1: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  8.769 ms/op
                 existUser·p0.9999: 21.017 ms/op
                 existUser·p1.00:   21.365 ms/op

Iteration   2: 3.338 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  11.964 ms/op
                 existUser·p0.9999: 15.168 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   3: 3.328 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  9.893 ms/op
                 existUser·p0.9999: 26.345 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 288305
  mean =      3.331 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12078 
    [ 2.500,  5.000) = 273228 
    [ 5.000,  7.500) = 2429 
    [ 7.500, 10.000) = 258 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     10.268 ms/op
     p(99.9900) =     24.956 ms/op
     p(99.9990) =     26.717 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.255 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.008 ms/op
Iteration   1: 3.460 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  8.263 ms/op
                 getUser·p0.9999: 16.380 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   2: 3.490 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  7.733 ms/op
                 getUser·p0.9999: 22.297 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.447 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  7.127 ms/op
                 getUser·p0.9999: 17.138 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 276963
  mean =      3.466 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9748 
    [ 2.500,  5.000) = 263185 
    [ 5.000,  7.500) = 3739 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     21.329 ms/op
     p(99.9990) =     23.273 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.410 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.820 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.579 ±(99.9%) 0.013 ms/op
Iteration   1: 4.630 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  15.870 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 4.555 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 19.363 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 4.559 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  18.969 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209513
  mean =      4.581 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 603 
    [ 2.500,  5.000) = 168481 
    [ 5.000,  7.500) = 36864 
    [ 7.500, 10.000) = 2958 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     20.678 ms/op
     p(99.9990) =     21.195 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.143 ± 1.043  ops/ms
ClientGrpc.existUser                       thrpt       3   9.730 ± 3.881  ops/ms
ClientGrpc.getUser                         thrpt       3   9.193 ± 2.664  ops/ms
ClientGrpc.listUser                        thrpt       3   7.165 ± 1.160  ops/ms
ClientGrpc.createUser                       avgt       3   3.551 ± 0.288   ms/op
ClientGrpc.existUser                        avgt       3   3.349 ± 0.453   ms/op
ClientGrpc.getUser                          avgt       3   3.486 ± 0.514   ms/op
ClientGrpc.listUser                         avgt       3   4.506 ± 0.966   ms/op
ClientGrpc.createUser                     sample  272302   3.528 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.697           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.694           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.733           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.396           ms/op
ClientGrpc.existUser                      sample  288305   3.331 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.818           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.850           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.268           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.956           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.804           ms/op
ClientGrpc.getUser                        sample  276963   3.466 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.735           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.035           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.329           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.593           ms/op
ClientGrpc.listUser                       sample  209513   4.581 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.044           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.391           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.744           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.678           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.266           ms/op
