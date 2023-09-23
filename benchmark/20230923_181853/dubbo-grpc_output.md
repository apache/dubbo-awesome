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
# Warmup Iteration   1: 3.364 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 8.693 ops/ms
Iteration   1: 8.867 ops/ms
Iteration   2: 9.137 ops/ms
Iteration   3: 9.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.077 ±(99.9%) 3.417 ops/ms [Average]
  (min, avg, max) = (8.867, 9.077, 9.228), stdev = 0.187
  CI (99.9%): [5.660, 12.495] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.698 ops/ms
# Warmup Iteration   2: 9.677 ops/ms
# Warmup Iteration   3: 9.893 ops/ms
Iteration   1: 10.092 ops/ms
Iteration   2: 10.188 ops/ms
Iteration   3: 9.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.969 ±(99.9%) 5.483 ops/ms [Average]
  (min, avg, max) = (9.626, 9.969, 10.188), stdev = 0.301
  CI (99.9%): [4.485, 15.452] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.087 ops/ms
# Warmup Iteration   2: 8.757 ops/ms
# Warmup Iteration   3: 9.086 ops/ms
Iteration   1: 9.109 ops/ms
Iteration   2: 9.223 ops/ms
Iteration   3: 9.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.236 ±(99.9%) 2.447 ops/ms [Average]
  (min, avg, max) = (9.109, 9.236, 9.376), stdev = 0.134
  CI (99.9%): [6.790, 11.683] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.630 ops/ms
# Warmup Iteration   2: 6.717 ops/ms
# Warmup Iteration   3: 6.811 ops/ms
Iteration   1: 7.030 ops/ms
Iteration   2: 6.793 ops/ms
Iteration   3: 7.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.947 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (6.793, 6.947, 7.030), stdev = 0.134
  CI (99.9%): [4.509, 9.385] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.304 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.004 ms/op
Iteration   1: 3.457 ±(99.9%) 0.002 ms/op
Iteration   2: 3.430 ±(99.9%) 0.003 ms/op
Iteration   3: 3.425 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.437 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (3.425, 3.437, 3.457), stdev = 0.017
  CI (99.9%): [3.125, 3.749] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.844 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.002 ms/op
Iteration   1: 3.297 ±(99.9%) 0.001 ms/op
Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
Iteration   3: 3.210 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.222 ±(99.9%) 1.259 ms/op [Average]
  (min, avg, max) = (3.160, 3.222, 3.297), stdev = 0.069
  CI (99.9%): [1.963, 4.482] (assumes normal distribution)


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
# Warmup Iteration   1: 4.813 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.003 ms/op
Iteration   1: 3.529 ±(99.9%) 0.002 ms/op
Iteration   2: 3.468 ±(99.9%) 0.003 ms/op
Iteration   3: 3.675 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.557 ±(99.9%) 1.940 ms/op [Average]
  (min, avg, max) = (3.468, 3.557, 3.675), stdev = 0.106
  CI (99.9%): [1.617, 5.497] (assumes normal distribution)


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
# Warmup Iteration   1: 6.316 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.852 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.677 ±(99.9%) 0.013 ms/op
Iteration   1: 4.683 ±(99.9%) 0.013 ms/op
Iteration   2: 4.423 ±(99.9%) 0.010 ms/op
Iteration   3: 4.545 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.550 ±(99.9%) 2.366 ms/op [Average]
  (min, avg, max) = (4.423, 4.550, 4.683), stdev = 0.130
  CI (99.9%): [2.184, 6.917] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.927 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.010 ms/op
Iteration   1: 3.425 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  9.628 ms/op
                 createUser·p0.9999: 16.832 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 3.445 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  12.273 ms/op
                 createUser·p0.9999: 19.619 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   3: 3.573 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  13.751 ms/op
                 createUser·p0.9999: 21.469 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 275802
  mean =      3.480 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11112 
    [ 2.500,  5.000) = 256889 
    [ 5.000,  7.500) = 6631 
    [ 7.500, 10.000) = 787 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     11.672 ms/op
     p(99.9900) =     21.182 ms/op
     p(99.9990) =     24.756 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.751 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.485 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
Iteration   1: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  9.307 ms/op
                 existUser·p0.9999: 17.269 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  10.138 ms/op
                 existUser·p0.9999: 20.013 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   3: 3.279 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  10.469 ms/op
                 existUser·p0.9999: 24.683 ms/op
                 existUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 291143
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19863 
    [ 2.500,  5.000) = 265475 
    [ 5.000,  7.500) = 4610 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     21.914 ms/op
     p(99.9990) =     24.972 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 5.155 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.009 ms/op
Iteration   1: 3.549 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.864 ms/op
                 getUser·p0.999:  10.812 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 3.476 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 19.320 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   3: 3.519 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  10.111 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 272984
  mean =      3.515 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9545 
    [ 2.500,  5.000) = 253891 
    [ 5.000,  7.500) = 7951 
    [ 7.500, 10.000) = 1260 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     19.585 ms/op
     p(99.9990) =     22.005 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 6.852 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.839 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.595 ±(99.9%) 0.016 ms/op
Iteration   1: 4.727 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  14.285 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   2: 4.767 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 32.263 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   3: 4.724 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 21.279 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202518
  mean =      4.739 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 409 
    [ 2.500,  5.000) = 146149 
    [ 5.000,  7.500) = 49308 
    [ 7.500, 10.000) = 5588 
    [10.000, 12.500) = 608 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     17.121 ms/op
     p(99.9900) =     29.622 ms/op
     p(99.9990) =     32.765 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.077 ± 3.417  ops/ms
ClientGrpc.existUser                       thrpt       3   9.969 ± 5.483  ops/ms
ClientGrpc.getUser                         thrpt       3   9.236 ± 2.447  ops/ms
ClientGrpc.listUser                        thrpt       3   6.947 ± 2.438  ops/ms
ClientGrpc.createUser                       avgt       3   3.437 ± 0.312   ms/op
ClientGrpc.existUser                        avgt       3   3.222 ± 1.259   ms/op
ClientGrpc.getUser                          avgt       3   3.557 ± 1.940   ms/op
ClientGrpc.listUser                         avgt       3   4.550 ± 2.366   ms/op
ClientGrpc.createUser                     sample  275802   3.480 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.345           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.005           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.672           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.182           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.904           ms/op
ClientGrpc.existUser                      sample  291143   3.297 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.650           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.211           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.051           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.207           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.914           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.166           ms/op
ClientGrpc.getUser                        sample  272984   3.515 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.764           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.408           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.463           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.273           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.585           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.577           ms/op
ClientGrpc.listUser                       sample  202518   4.739 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.194           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.103           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.093           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.121           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.622           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.554           ms/op
