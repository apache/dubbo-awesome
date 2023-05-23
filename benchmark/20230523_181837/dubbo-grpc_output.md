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
# Warmup Iteration   1: 2.889 ops/ms
# Warmup Iteration   2: 6.631 ops/ms
# Warmup Iteration   3: 7.597 ops/ms
Iteration   1: 7.880 ops/ms
Iteration   2: 7.929 ops/ms
Iteration   3: 8.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.140 ±(99.9%) 7.469 ops/ms [Average]
  (min, avg, max) = (7.880, 8.140, 8.612), stdev = 0.409
  CI (99.9%): [0.671, 15.610] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.805 ops/ms
# Warmup Iteration   2: 8.413 ops/ms
# Warmup Iteration   3: 7.882 ops/ms
Iteration   1: 8.352 ops/ms
Iteration   2: 8.666 ops/ms
Iteration   3: 9.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.779 ±(99.9%) 8.991 ops/ms [Average]
  (min, avg, max) = (8.352, 8.779, 9.318), stdev = 0.493
  CI (99.9%): [≈ 0, 17.770] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.953 ops/ms
# Warmup Iteration   2: 7.968 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 8.571 ops/ms
Iteration   2: 8.524 ops/ms
Iteration   3: 8.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.642 ±(99.9%) 3.016 ops/ms [Average]
  (min, avg, max) = (8.524, 8.642, 8.831), stdev = 0.165
  CI (99.9%): [5.626, 11.658] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ops/ms
# Warmup Iteration   2: 6.504 ops/ms
# Warmup Iteration   3: 6.381 ops/ms
Iteration   1: 6.308 ops/ms
Iteration   2: 6.272 ops/ms
Iteration   3: 6.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.319 ±(99.9%) 0.969 ops/ms [Average]
  (min, avg, max) = (6.272, 6.319, 6.377), stdev = 0.053
  CI (99.9%): [5.350, 7.288] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.526 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.016 ms/op
Iteration   1: 3.760 ±(99.9%) 0.003 ms/op
Iteration   2: 3.700 ±(99.9%) 0.003 ms/op
Iteration   3: 3.829 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.763 ±(99.9%) 1.181 ms/op [Average]
  (min, avg, max) = (3.700, 3.763, 3.829), stdev = 0.065
  CI (99.9%): [2.581, 4.944] (assumes normal distribution)


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.003 ms/op
Iteration   1: 3.431 ±(99.9%) 0.004 ms/op
Iteration   2: 3.377 ±(99.9%) 0.002 ms/op
Iteration   3: 3.490 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.433 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.377, 3.433, 3.490), stdev = 0.056
  CI (99.9%): [2.406, 4.459] (assumes normal distribution)


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
# Warmup Iteration   1: 5.389 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.003 ms/op
Iteration   1: 3.885 ±(99.9%) 0.004 ms/op
Iteration   2: 3.819 ±(99.9%) 0.003 ms/op
Iteration   3: 3.691 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.799 ±(99.9%) 1.805 ms/op [Average]
  (min, avg, max) = (3.691, 3.799, 3.885), stdev = 0.099
  CI (99.9%): [1.994, 5.603] (assumes normal distribution)


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
# Warmup Iteration   1: 7.098 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.591 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.129 ±(99.9%) 0.023 ms/op
Iteration   1: 4.960 ±(99.9%) 0.025 ms/op
Iteration   2: 5.017 ±(99.9%) 0.011 ms/op
Iteration   3: 5.053 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.010 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (4.960, 5.010, 5.053), stdev = 0.047
  CI (99.9%): [4.158, 5.862] (assumes normal distribution)


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
# Warmup Iteration   1: 5.559 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.012 ms/op
Iteration   1: 3.802 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  12.320 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   18.448 ms/op

Iteration   2: 3.699 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  9.020 ms/op
                 createUser·p0.9999: 17.805 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   3: 3.764 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  15.218 ms/op
                 createUser·p0.9999: 20.758 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255747
  mean =      3.755 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9273 
    [ 2.500,  5.000) = 233090 
    [ 5.000,  7.500) = 12268 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     11.678 ms/op
     p(99.9900) =     19.380 ms/op
     p(99.9990) =     22.231 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 5.966 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.011 ms/op
Iteration   1: 3.537 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  10.099 ms/op
                 existUser·p0.9999: 16.466 ms/op
                 existUser·p1.00:   18.776 ms/op

Iteration   2: 3.375 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  11.697 ms/op
                 existUser·p0.9999: 18.514 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  11.262 ms/op
                 existUser·p0.9999: 34.789 ms/op
                 existUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276853
  mean =      3.467 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15356 
    [ 2.500,  5.000) = 254947 
    [ 5.000,  7.500) = 5706 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     11.059 ms/op
     p(99.9900) =     33.772 ms/op
     p(99.9990) =     35.142 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 5.575 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.010 ms/op
Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.114 ms/op
                 getUser·p0.999:  12.113 ms/op
                 getUser·p0.9999: 23.686 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.885 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.483 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  11.270 ms/op
                 getUser·p0.9999: 18.342 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.884 ms/op
                 getUser·p0.999:  10.297 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 245799
  mean =      3.906 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8986 
    [ 2.500,  5.000) = 217937 
    [ 5.000,  7.500) = 17223 
    [ 7.500, 10.000) = 1315 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     11.370 ms/op
     p(99.9900) =     21.280 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 6.530 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.793 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.134 ±(99.9%) 0.020 ms/op
Iteration   1: 5.008 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   2: 4.934 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.251 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 23.331 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 4.803 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  21.450 ms/op
                 listUser·p0.9999: 31.632 ms/op
                 listUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195340
  mean =      4.914 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 773 
    [ 2.500,  5.000) = 126910 
    [ 5.000,  7.500) = 60073 
    [ 7.500, 10.000) = 6284 
    [10.000, 12.500) = 858 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.349 ms/op
     p(95.0000) =      7.201 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     17.684 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     32.238 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.140 ± 7.469  ops/ms
ClientGrpc.existUser                       thrpt       3   8.779 ± 8.991  ops/ms
ClientGrpc.getUser                         thrpt       3   8.642 ± 3.016  ops/ms
ClientGrpc.listUser                        thrpt       3   6.319 ± 0.969  ops/ms
ClientGrpc.createUser                       avgt       3   3.763 ± 1.181   ms/op
ClientGrpc.existUser                        avgt       3   3.433 ± 1.026   ms/op
ClientGrpc.getUser                          avgt       3   3.799 ± 1.805   ms/op
ClientGrpc.listUser                         avgt       3   5.010 ± 0.852   ms/op
ClientGrpc.createUser                     sample  255747   3.755 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.674           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.447           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.678           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.380           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.348           ms/op
ClientGrpc.existUser                      sample  276853   3.467 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.518           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.751           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.059           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.772           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.258           ms/op
ClientGrpc.getUser                        sample  245799   3.906 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.483           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.284           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.939           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.370           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.280           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.953           ms/op
ClientGrpc.listUser                       sample  195340   4.914 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.145           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.257           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.684           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.999           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.801           ms/op
