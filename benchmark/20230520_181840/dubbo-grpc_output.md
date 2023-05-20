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
# Warmup Iteration   1: 2.962 ops/ms
# Warmup Iteration   2: 6.909 ops/ms
# Warmup Iteration   3: 8.032 ops/ms
Iteration   1: 8.378 ops/ms
Iteration   2: 8.445 ops/ms
Iteration   3: 8.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.441 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (8.378, 8.441, 8.500), stdev = 0.061
  CI (99.9%): [7.335, 9.547] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.645 ops/ms
# Warmup Iteration   2: 8.468 ops/ms
# Warmup Iteration   3: 9.050 ops/ms
Iteration   1: 8.793 ops/ms
Iteration   2: 8.572 ops/ms
Iteration   3: 8.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.782 ±(99.9%) 3.715 ops/ms [Average]
  (min, avg, max) = (8.572, 8.782, 8.979), stdev = 0.204
  CI (99.9%): [5.066, 12.497] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.607 ops/ms
# Warmup Iteration   2: 7.178 ops/ms
# Warmup Iteration   3: 9.144 ops/ms
Iteration   1: 9.394 ops/ms
Iteration   2: 9.466 ops/ms
Iteration   3: 9.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.375 ±(99.9%) 1.857 ops/ms [Average]
  (min, avg, max) = (9.265, 9.375, 9.466), stdev = 0.102
  CI (99.9%): [7.518, 11.231] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.802 ops/ms
# Warmup Iteration   2: 6.379 ops/ms
# Warmup Iteration   3: 6.862 ops/ms
Iteration   1: 6.593 ops/ms
Iteration   2: 6.303 ops/ms
Iteration   3: 5.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.288 ±(99.9%) 5.693 ops/ms [Average]
  (min, avg, max) = (5.969, 6.288, 6.593), stdev = 0.312
  CI (99.9%): [0.595, 11.981] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.681 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.893 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.605 ±(99.9%) 0.005 ms/op
Iteration   1: 4.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.511 ±(99.9%) 0.003 ms/op
Iteration   3: 4.099 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.889 ±(99.9%) 5.981 ms/op [Average]
  (min, avg, max) = (3.511, 3.889, 4.099), stdev = 0.328
  CI (99.9%): [≈ 0, 9.870] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.870 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.002 ms/op
Iteration   1: 3.470 ±(99.9%) 0.002 ms/op
Iteration   2: 3.374 ±(99.9%) 0.002 ms/op
Iteration   3: 3.379 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.408 ±(99.9%) 0.983 ms/op [Average]
  (min, avg, max) = (3.374, 3.408, 3.470), stdev = 0.054
  CI (99.9%): [2.425, 4.391] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.661 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.004 ms/op
Iteration   1: 3.528 ±(99.9%) 0.004 ms/op
Iteration   2: 3.516 ±(99.9%) 0.005 ms/op
Iteration   3: 3.486 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.510 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.486, 3.510, 3.528), stdev = 0.022
  CI (99.9%): [3.117, 3.903] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.961 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.733 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.551 ±(99.9%) 0.011 ms/op
Iteration   1: 4.640 ±(99.9%) 0.020 ms/op
Iteration   2: 4.569 ±(99.9%) 0.011 ms/op
Iteration   3: 4.549 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.586 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (4.549, 4.586, 4.640), stdev = 0.048
  CI (99.9%): [3.710, 5.462] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.113 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.007 ms/op
Iteration   1: 3.445 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  11.494 ms/op
                 createUser·p0.9999: 17.905 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   2: 3.439 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  7.068 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  18.808 ms/op
                 createUser·p0.9999: 26.535 ms/op
                 createUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 278031
  mean =      3.454 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9951 
    [ 2.500,  5.000) = 265519 
    [ 5.000,  7.500) = 2097 
    [ 7.500, 10.000) = 184 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     10.043 ms/op
     p(99.9900) =     26.024 ms/op
     p(99.9990) =     26.648 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.006 ms/op
Iteration   1: 3.295 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.846 ms/op
                 existUser·p0.9999: 19.241 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   2: 3.284 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  6.705 ms/op
                 existUser·p0.9999: 16.114 ms/op
                 existUser·p1.00:   18.252 ms/op

Iteration   3: 3.318 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.776 ms/op
                 existUser·p0.9999: 18.472 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 290893
  mean =      3.299 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 427 
    [ 1.250,  2.500) = 10265 
    [ 2.500,  3.750) = 246947 
    [ 3.750,  5.000) = 31366 
    [ 5.000,  6.250) = 1359 
    [ 6.250,  7.500) = 273 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     18.249 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 5.005 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.007 ms/op
Iteration   1: 3.430 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  9.413 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 3.419 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.115 ms/op
                 getUser·p0.999:  8.039 ms/op
                 getUser·p0.9999: 16.378 ms/op
                 getUser·p1.00:   16.433 ms/op

Iteration   3: 3.432 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.177 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 18.897 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 279951
  mean =      3.427 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10191 
    [ 2.500,  5.000) = 266116 
    [ 5.000,  7.500) = 3288 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =      8.111 ms/op
     p(99.9900) =     18.121 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 6.018 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.540 ±(99.9%) 0.013 ms/op
Iteration   1: 4.469 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  15.234 ms/op
                 listUser·p0.9999: 18.148 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 4.488 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  16.872 ms/op
                 listUser·p0.9999: 22.610 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 4.352 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  18.069 ms/op
                 listUser·p0.9999: 23.067 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 216426
  mean =      4.436 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 523 
    [ 2.500,  5.000) = 186728 
    [ 5.000,  7.500) = 26257 
    [ 7.500, 10.000) = 2513 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     22.338 ms/op
     p(99.9990) =     23.670 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.441 ± 1.106  ops/ms
ClientGrpc.existUser                       thrpt       3   8.782 ± 3.715  ops/ms
ClientGrpc.getUser                         thrpt       3   9.375 ± 1.857  ops/ms
ClientGrpc.listUser                        thrpt       3   6.288 ± 5.693  ops/ms
ClientGrpc.createUser                       avgt       3   3.889 ± 5.981   ms/op
ClientGrpc.existUser                        avgt       3   3.408 ± 0.983   ms/op
ClientGrpc.getUser                          avgt       3   3.510 ± 0.393   ms/op
ClientGrpc.listUser                         avgt       3   4.586 ± 0.876   ms/op
ClientGrpc.createUser                     sample  278031   3.454 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.935           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.428           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.956           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.043           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.024           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.739           ms/op
ClientGrpc.existUser                      sample  290893   3.299 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.683           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.973           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.299           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.249           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  279951   3.427 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.738           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.396           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.018           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.210           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.111           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.121           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  216426   4.436 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.180           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.332           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.564           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.338           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.822           ms/op
