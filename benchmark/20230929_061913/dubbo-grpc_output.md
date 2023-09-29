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
# Warmup Iteration   1: 2.249 ops/ms
# Warmup Iteration   2: 5.368 ops/ms
# Warmup Iteration   3: 6.805 ops/ms
Iteration   1: 7.142 ops/ms
Iteration   2: 7.328 ops/ms
Iteration   3: 7.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.234 ±(99.9%) 1.693 ops/ms [Average]
  (min, avg, max) = (7.142, 7.234, 7.328), stdev = 0.093
  CI (99.9%): [5.541, 8.928] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ops/ms
# Warmup Iteration   2: 6.654 ops/ms
# Warmup Iteration   3: 7.411 ops/ms
Iteration   1: 7.607 ops/ms
Iteration   2: 7.690 ops/ms
Iteration   3: 7.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.629 ±(99.9%) 0.963 ops/ms [Average]
  (min, avg, max) = (7.592, 7.629, 7.690), stdev = 0.053
  CI (99.9%): [6.666, 8.593] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ops/ms
# Warmup Iteration   2: 6.772 ops/ms
# Warmup Iteration   3: 7.003 ops/ms
Iteration   1: 7.083 ops/ms
Iteration   2: 7.304 ops/ms
Iteration   3: 7.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.283 ±(99.9%) 3.464 ops/ms [Average]
  (min, avg, max) = (7.083, 7.283, 7.461), stdev = 0.190
  CI (99.9%): [3.818, 10.747] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ops/ms
# Warmup Iteration   2: 4.698 ops/ms
# Warmup Iteration   3: 5.450 ops/ms
Iteration   1: 5.567 ops/ms
Iteration   2: 5.616 ops/ms
Iteration   3: 5.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.677 ±(99.9%) 2.729 ops/ms [Average]
  (min, avg, max) = (5.567, 5.677, 5.847), stdev = 0.150
  CI (99.9%): [2.948, 8.406] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.973 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.745 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.581 ±(99.9%) 0.006 ms/op
Iteration   1: 4.430 ±(99.9%) 0.002 ms/op
Iteration   2: 4.343 ±(99.9%) 0.003 ms/op
Iteration   3: 4.466 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.413 ±(99.9%) 1.150 ms/op [Average]
  (min, avg, max) = (4.343, 4.413, 4.466), stdev = 0.063
  CI (99.9%): [3.263, 5.563] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.164 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.337 ±(99.9%) 0.003 ms/op
Iteration   1: 4.072 ±(99.9%) 0.003 ms/op
Iteration   2: 4.140 ±(99.9%) 0.003 ms/op
Iteration   3: 4.190 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.134 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (4.072, 4.134, 4.190), stdev = 0.059
  CI (99.9%): [3.055, 5.213] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.409 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.004 ms/op
Iteration   1: 4.350 ±(99.9%) 0.005 ms/op
Iteration   2: 4.415 ±(99.9%) 0.003 ms/op
Iteration   3: 4.407 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.390 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (4.350, 4.390, 4.415), stdev = 0.035
  CI (99.9%): [3.744, 5.037] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 7.841 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 6.499 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.933 ±(99.9%) 0.029 ms/op
Iteration   1: 5.654 ±(99.9%) 0.018 ms/op
Iteration   2: 5.762 ±(99.9%) 0.023 ms/op
Iteration   3: 5.805 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.740 ±(99.9%) 1.415 ms/op [Average]
  (min, avg, max) = (5.654, 5.740, 5.805), stdev = 0.078
  CI (99.9%): [4.326, 7.155] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.539 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.901 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.599 ±(99.9%) 0.014 ms/op
Iteration   1: 4.475 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   6.218 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  15.803 ms/op
                 createUser·p0.9999: 19.853 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 4.599 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.710 ms/op
                 createUser·p0.95:   6.226 ms/op
                 createUser·p0.99:   8.552 ms/op
                 createUser·p0.999:  14.306 ms/op
                 createUser·p0.9999: 20.387 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 4.505 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.562 ms/op
                 createUser·p0.95:   6.095 ms/op
                 createUser·p0.99:   8.356 ms/op
                 createUser·p0.999:  19.399 ms/op
                 createUser·p0.9999: 21.361 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 211908
  mean =      4.526 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3414 
    [ 2.500,  5.000) = 157552 
    [ 5.000,  7.500) = 47469 
    [ 7.500, 10.000) = 2501 
    [10.000, 12.500) = 541 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.181 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     15.828 ms/op
     p(99.9900) =     20.670 ms/op
     p(99.9990) =     21.484 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.592 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.360 ±(99.9%) 0.013 ms/op
Iteration   1: 4.263 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   4.133 ms/op
                 existUser·p0.90:   5.472 ms/op
                 existUser·p0.95:   6.201 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  13.466 ms/op
                 existUser·p0.9999: 17.514 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 4.298 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   4.178 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.702 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  10.615 ms/op
                 existUser·p0.9999: 20.283 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   3: 4.395 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   4.243 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   7.632 ms/op
                 existUser·p0.999:  13.585 ms/op
                 existUser·p0.9999: 23.317 ms/op
                 existUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222441
  mean =      4.318 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5704 
    [ 2.500,  5.000) = 177168 
    [ 5.000,  7.500) = 36703 
    [ 7.500, 10.000) = 2226 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      4.186 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     13.231 ms/op
     p(99.9900) =     22.127 ms/op
     p(99.9990) =     26.374 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.358 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.511 ±(99.9%) 0.013 ms/op
Iteration   1: 4.484 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   7.847 ms/op
                 getUser·p0.999:  13.856 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   2: 4.583 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   7.807 ms/op
                 getUser·p0.999:  11.915 ms/op
                 getUser·p0.9999: 19.007 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   3: 4.421 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   7.602 ms/op
                 getUser·p0.999:  11.367 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213497
  mean =      4.495 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3641 
    [ 2.500,  5.000) = 160595 
    [ 5.000,  7.500) = 46710 
    [ 7.500, 10.000) = 1925 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.695 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.381 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.172 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.638 ±(99.9%) 0.022 ms/op
Iteration   1: 5.816 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.724 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  17.329 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 5.641 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.534 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 22.914 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 5.741 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  20.948 ms/op
                 listUser·p0.9999: 23.640 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167573
  mean =      5.732 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 56265 
    [ 5.000,  7.500) = 92734 
    [ 7.500, 10.000) = 14479 
    [10.000, 12.500) = 2890 
    [12.500, 15.000) = 710 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.660 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     19.085 ms/op
     p(99.9900) =     23.109 ms/op
     p(99.9990) =     23.898 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.234 ± 1.693  ops/ms
ClientGrpc.existUser                       thrpt       3   7.629 ± 0.963  ops/ms
ClientGrpc.getUser                         thrpt       3   7.283 ± 3.464  ops/ms
ClientGrpc.listUser                        thrpt       3   5.677 ± 2.729  ops/ms
ClientGrpc.createUser                       avgt       3   4.413 ± 1.150   ms/op
ClientGrpc.existUser                        avgt       3   4.134 ± 1.079   ms/op
ClientGrpc.getUser                          avgt       3   4.390 ± 0.646   ms/op
ClientGrpc.listUser                         avgt       3   5.740 ± 1.415   ms/op
ClientGrpc.createUser                     sample  211908   4.526 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.010           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.636           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.181           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.438           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.828           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.670           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.787           ms/op
ClientGrpc.existUser                      sample  222441   4.318 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.902           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.390           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.882           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.922           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.231           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.127           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.477           ms/op
ClientGrpc.getUser                        sample  213497   4.495 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.846           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.587           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.078           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.750           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.059           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.151           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  167573   5.732 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.266           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.765           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.567           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.085           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.109           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.921           ms/op
