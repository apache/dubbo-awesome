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
# Warmup Iteration   1: 3.462 ops/ms
# Warmup Iteration   2: 7.279 ops/ms
# Warmup Iteration   3: 9.131 ops/ms
Iteration   1: 9.376 ops/ms
Iteration   2: 9.435 ops/ms
Iteration   3: 9.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.354 ±(99.9%) 1.730 ops/ms [Average]
  (min, avg, max) = (9.250, 9.354, 9.435), stdev = 0.095
  CI (99.9%): [7.624, 11.084] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.804 ops/ms
# Warmup Iteration   2: 9.269 ops/ms
# Warmup Iteration   3: 9.977 ops/ms
Iteration   1: 10.036 ops/ms
Iteration   2: 9.928 ops/ms
Iteration   3: 10.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.004 ±(99.9%) 1.208 ops/ms [Average]
  (min, avg, max) = (9.928, 10.004, 10.048), stdev = 0.066
  CI (99.9%): [8.795, 11.212] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.656 ops/ms
# Warmup Iteration   2: 8.755 ops/ms
# Warmup Iteration   3: 9.262 ops/ms
Iteration   1: 9.413 ops/ms
Iteration   2: 9.672 ops/ms
Iteration   3: 9.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.543 ±(99.9%) 2.359 ops/ms [Average]
  (min, avg, max) = (9.413, 9.543, 9.672), stdev = 0.129
  CI (99.9%): [7.183, 11.902] (assumes normal distribution)


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
# Warmup Iteration   1: 4.727 ops/ms
# Warmup Iteration   2: 6.828 ops/ms
# Warmup Iteration   3: 6.921 ops/ms
Iteration   1: 7.019 ops/ms
Iteration   2: 6.948 ops/ms
Iteration   3: 7.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.038 ±(99.9%) 1.845 ops/ms [Average]
  (min, avg, max) = (6.948, 7.038, 7.148), stdev = 0.101
  CI (99.9%): [5.193, 8.883] (assumes normal distribution)


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.002 ms/op
Iteration   1: 3.465 ±(99.9%) 0.003 ms/op
Iteration   2: 3.491 ±(99.9%) 0.002 ms/op
Iteration   3: 3.388 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.448 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.388, 3.448, 3.491), stdev = 0.054
  CI (99.9%): [2.464, 4.432] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.550 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.002 ms/op
Iteration   1: 3.245 ±(99.9%) 0.003 ms/op
Iteration   2: 3.240 ±(99.9%) 0.003 ms/op
Iteration   3: 3.196 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.227 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (3.196, 3.227, 3.245), stdev = 0.027
  CI (99.9%): [2.734, 3.720] (assumes normal distribution)


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.003 ms/op
Iteration   1: 3.460 ±(99.9%) 0.001 ms/op
Iteration   2: 3.389 ±(99.9%) 0.004 ms/op
Iteration   3: 3.376 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.408 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (3.376, 3.408, 3.460), stdev = 0.045
  CI (99.9%): [2.584, 4.233] (assumes normal distribution)


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
# Warmup Iteration   1: 5.766 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 5.303 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.014 ms/op
Iteration   1: 4.535 ±(99.9%) 0.010 ms/op
Iteration   2: 4.496 ±(99.9%) 0.011 ms/op
Iteration   3: 4.387 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.473 ±(99.9%) 1.395 ms/op [Average]
  (min, avg, max) = (4.387, 4.473, 4.535), stdev = 0.076
  CI (99.9%): [3.078, 5.867] (assumes normal distribution)


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
# Warmup Iteration   1: 5.092 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.008 ms/op
Iteration   1: 3.427 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  7.992 ms/op
                 createUser·p0.9999: 15.559 ms/op
                 createUser·p1.00:   16.024 ms/op

Iteration   2: 3.293 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  8.541 ms/op
                 createUser·p0.9999: 22.465 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 31.041 ms/op
                 createUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 287433
  mean =      3.339 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12939 
    [ 2.500,  5.000) = 270957 
    [ 5.000,  7.500) = 3029 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     31.130 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 4.769 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.007 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  8.712 ms/op
                 existUser·p0.9999: 20.656 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.217 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.478 ms/op
                 existUser·p0.9999: 20.318 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   3: 3.261 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  10.666 ms/op
                 existUser·p0.9999: 20.276 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 295672
  mean =      3.247 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19131 
    [ 2.500,  5.000) = 272935 
    [ 5.000,  7.500) = 3053 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =     20.330 ms/op
     p(99.9990) =     21.006 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.008 ms/op
Iteration   1: 3.426 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  10.038 ms/op
                 getUser·p0.9999: 14.631 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 3.368 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.436 ms/op
                 getUser·p0.999:  7.922 ms/op
                 getUser·p0.9999: 21.299 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   3: 3.389 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.339 ms/op
                 getUser·p0.999:  8.337 ms/op
                 getUser·p0.9999: 30.165 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 282522
  mean =      3.394 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14357 
    [ 2.500,  5.000) = 263082 
    [ 5.000,  7.500) = 4352 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     29.572 ms/op
     p(99.9990) =     30.802 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 6.192 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.582 ±(99.9%) 0.014 ms/op
Iteration   1: 4.441 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  16.089 ms/op
                 listUser·p0.9999: 17.295 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 4.467 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  18.556 ms/op
                 listUser·p0.9999: 27.257 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   3: 4.424 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.422 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  18.317 ms/op
                 listUser·p0.9999: 21.882 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 216042
  mean =      4.444 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1020 
    [ 2.500,  5.000) = 177670 
    [ 5.000,  7.500) = 33782 
    [ 7.500, 10.000) = 2967 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.744 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.354 ± 1.730  ops/ms
ClientGrpc.existUser                       thrpt       3  10.004 ± 1.208  ops/ms
ClientGrpc.getUser                         thrpt       3   9.543 ± 2.359  ops/ms
ClientGrpc.listUser                        thrpt       3   7.038 ± 1.845  ops/ms
ClientGrpc.createUser                       avgt       3   3.448 ± 0.984   ms/op
ClientGrpc.existUser                        avgt       3   3.227 ± 0.493   ms/op
ClientGrpc.getUser                          avgt       3   3.408 ± 0.825   ms/op
ClientGrpc.listUser                         avgt       3   4.473 ± 1.395   ms/op
ClientGrpc.createUser                     sample  287433   3.339 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.821           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.289           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.965           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.186           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.487           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.344           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.261           ms/op
ClientGrpc.existUser                      sample  295672   3.247 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.820           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.211           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.912           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.330           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.103           ms/op
ClientGrpc.getUser                        sample  282522   3.394 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.856           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.346           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.595           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.077           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.572           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.802           ms/op
ClientGrpc.listUser                       sample  216042   4.444 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.422           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.268           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.398           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.954           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.138           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.542           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
