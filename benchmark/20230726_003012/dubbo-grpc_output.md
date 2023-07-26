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
# Warmup Iteration   1: 2.115 ops/ms
# Warmup Iteration   2: 5.156 ops/ms
# Warmup Iteration   3: 6.947 ops/ms
Iteration   1: 7.280 ops/ms
Iteration   2: 7.222 ops/ms
Iteration   3: 7.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.247 ±(99.9%) 0.547 ops/ms [Average]
  (min, avg, max) = (7.222, 7.247, 7.280), stdev = 0.030
  CI (99.9%): [6.700, 7.794] (assumes normal distribution)


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
# Warmup Iteration   1: 4.336 ops/ms
# Warmup Iteration   2: 6.904 ops/ms
# Warmup Iteration   3: 7.389 ops/ms
Iteration   1: 7.612 ops/ms
Iteration   2: 7.534 ops/ms
Iteration   3: 7.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.546 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (7.493, 7.546, 7.612), stdev = 0.060
  CI (99.9%): [6.447, 8.645] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.901 ops/ms
# Warmup Iteration   2: 6.768 ops/ms
# Warmup Iteration   3: 7.032 ops/ms
Iteration   1: 7.234 ops/ms
Iteration   2: 7.080 ops/ms
Iteration   3: 7.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.158 ±(99.9%) 1.409 ops/ms [Average]
  (min, avg, max) = (7.080, 7.158, 7.234), stdev = 0.077
  CI (99.9%): [5.749, 8.567] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.495 ops/ms
# Warmup Iteration   2: 4.650 ops/ms
# Warmup Iteration   3: 5.351 ops/ms
Iteration   1: 5.277 ops/ms
Iteration   2: 5.416 ops/ms
Iteration   3: 5.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.384 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (5.277, 5.384, 5.460), stdev = 0.096
  CI (99.9%): [3.637, 7.131] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.977 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.958 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.654 ±(99.9%) 0.004 ms/op
Iteration   1: 4.622 ±(99.9%) 0.002 ms/op
Iteration   2: 4.617 ±(99.9%) 0.004 ms/op
Iteration   3: 4.505 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.581 ±(99.9%) 1.205 ms/op [Average]
  (min, avg, max) = (4.505, 4.581, 4.622), stdev = 0.066
  CI (99.9%): [3.377, 5.786] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.427 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.004 ms/op
Iteration   1: 4.387 ±(99.9%) 0.003 ms/op
Iteration   2: 4.309 ±(99.9%) 0.002 ms/op
Iteration   3: 4.215 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.304 ±(99.9%) 1.573 ms/op [Average]
  (min, avg, max) = (4.215, 4.304, 4.387), stdev = 0.086
  CI (99.9%): [2.730, 5.877] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.186 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.347 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.725 ±(99.9%) 0.014 ms/op
Iteration   1: 4.806 ±(99.9%) 0.007 ms/op
Iteration   2: 4.786 ±(99.9%) 0.003 ms/op
Iteration   3: 4.504 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.699 ±(99.9%) 3.084 ms/op [Average]
  (min, avg, max) = (4.504, 4.699, 4.806), stdev = 0.169
  CI (99.9%): [1.614, 7.783] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.813 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 6.441 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.000 ±(99.9%) 0.013 ms/op
Iteration   1: 6.007 ±(99.9%) 0.014 ms/op
Iteration   2: 6.049 ±(99.9%) 0.016 ms/op
Iteration   3: 5.947 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.001 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (5.947, 6.001, 6.049), stdev = 0.051
  CI (99.9%): [5.069, 6.933] (assumes normal distribution)


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
# Warmup Iteration   1: 6.987 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.031 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.546 ±(99.9%) 0.013 ms/op
Iteration   1: 4.428 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  12.231 ms/op
                 createUser·p0.9999: 16.144 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   2: 4.436 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  12.155 ms/op
                 createUser·p0.9999: 17.159 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 4.371 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   7.614 ms/op
                 createUser·p0.999:  12.546 ms/op
                 createUser·p0.9999: 21.485 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217538
  mean =      4.411 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3558 
    [ 2.500,  5.000) = 170953 
    [ 5.000,  7.500) = 40915 
    [ 7.500, 10.000) = 1434 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     12.279 ms/op
     p(99.9900) =     19.505 ms/op
     p(99.9990) =     21.905 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 6.845 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.384 ±(99.9%) 0.012 ms/op
Iteration   1: 4.298 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   4.149 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   8.076 ms/op
                 existUser·p0.999:  16.795 ms/op
                 existUser·p0.9999: 18.911 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 4.237 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   7.580 ms/op
                 existUser·p0.999:  13.262 ms/op
                 existUser·p0.9999: 19.412 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   3: 4.309 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   4.190 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   7.692 ms/op
                 existUser·p0.999:  12.190 ms/op
                 existUser·p0.9999: 19.862 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224382
  mean =      4.281 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5042 
    [ 2.500,  5.000) = 186077 
    [ 5.000,  7.500) = 30692 
    [ 7.500, 10.000) = 1830 
    [10.000, 12.500) = 425 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     13.308 ms/op
     p(99.9900) =     19.636 ms/op
     p(99.9990) =     20.538 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 7.267 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.849 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.609 ±(99.9%) 0.014 ms/op
Iteration   1: 4.550 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  12.065 ms/op
                 getUser·p0.9999: 17.202 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 4.667 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  13.377 ms/op
                 getUser·p0.9999: 21.332 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   3: 4.585 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.177 ms/op
                 getUser·p0.99:   8.086 ms/op
                 getUser·p0.999:  11.457 ms/op
                 getUser·p0.9999: 22.448 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 208608
  mean =      4.600 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3038 
    [ 2.500,  5.000) = 149517 
    [ 5.000,  7.500) = 53716 
    [ 7.500, 10.000) = 1892 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     12.180 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     23.057 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 8.843 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 6.627 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.889 ±(99.9%) 0.020 ms/op
Iteration   1: 5.994 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   7.864 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  17.593 ms/op
                 listUser·p0.9999: 19.615 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   2: 5.877 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.340 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  17.685 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 5.700 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   8.004 ms/op
                 listUser·p0.99:   10.174 ms/op
                 listUser·p0.999:  28.115 ms/op
                 listUser·p0.9999: 37.931 ms/op
                 listUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163949
  mean =      5.854 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 37876 
    [ 5.000,  7.500) = 110219 
    [ 7.500, 10.000) = 12922 
    [10.000, 12.500) = 2277 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      7.438 ms/op
     p(95.0000) =      8.520 ms/op
     p(99.0000) =     10.854 ms/op
     p(99.9000) =     17.927 ms/op
     p(99.9900) =     36.871 ms/op
     p(99.9990) =     38.475 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.247 ± 0.547  ops/ms
ClientGrpc.existUser                       thrpt       3   7.546 ± 1.099  ops/ms
ClientGrpc.getUser                         thrpt       3   7.158 ± 1.409  ops/ms
ClientGrpc.listUser                        thrpt       3   5.384 ± 1.747  ops/ms
ClientGrpc.createUser                       avgt       3   4.581 ± 1.205   ms/op
ClientGrpc.existUser                        avgt       3   4.304 ± 1.573   ms/op
ClientGrpc.getUser                          avgt       3   4.699 ± 3.084   ms/op
ClientGrpc.listUser                         avgt       3   6.001 ± 0.932   ms/op
ClientGrpc.createUser                     sample  217538   4.411 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.423           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.438           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.279           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.505           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.020           ms/op
ClientGrpc.existUser                      sample  224382   4.281 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.096           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.784           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.782           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.308           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.636           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  208608   4.600 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.096           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.095           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.651           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.180           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.234           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.200           ms/op
ClientGrpc.listUser                       sample  163949   5.854 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.407           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.438           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.854           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.927           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          36.871           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.601           ms/op
