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
# Warmup Iteration   1: 3.925 ops/ms
# Warmup Iteration   2: 8.519 ops/ms
# Warmup Iteration   3: 9.873 ops/ms
Iteration   1: 10.107 ops/ms
Iteration   2: 10.317 ops/ms
Iteration   3: 10.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.273 ±(99.9%) 2.706 ops/ms [Average]
  (min, avg, max) = (10.107, 10.273, 10.393), stdev = 0.148
  CI (99.9%): [7.567, 12.979] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.520 ops/ms
# Warmup Iteration   2: 10.087 ops/ms
# Warmup Iteration   3: 10.651 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.618 ±(99.9%) 0.813 ops/ms [Average]
  (min, avg, max) = (10.585, 10.618, 10.669), stdev = 0.045
  CI (99.9%): [9.805, 11.431] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.109 ops/ms
# Warmup Iteration   2: 9.775 ops/ms
# Warmup Iteration   3: 10.089 ops/ms
Iteration   1: 10.071 ops/ms
Iteration   2: 10.039 ops/ms
Iteration   3: 9.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.000 ±(99.9%) 1.745 ops/ms [Average]
  (min, avg, max) = (9.891, 10.000, 10.071), stdev = 0.096
  CI (99.9%): [8.255, 11.745] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.561 ops/ms
# Warmup Iteration   2: 7.452 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 7.864 ops/ms
Iteration   2: 8.247 ops/ms
Iteration   3: 8.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.155 ±(99.9%) 4.708 ops/ms [Average]
  (min, avg, max) = (7.864, 8.155, 8.355), stdev = 0.258
  CI (99.9%): [3.448, 12.863] (assumes normal distribution)


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.002 ms/op
Iteration   1: 3.143 ±(99.9%) 0.003 ms/op
Iteration   2: 3.182 ±(99.9%) 0.020 ms/op
Iteration   3: 3.154 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.160 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.143, 3.160, 3.182), stdev = 0.020
  CI (99.9%): [2.793, 3.527] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.002 ms/op
Iteration   1: 2.974 ±(99.9%) 0.002 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 2.973 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.978 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.973, 2.978, 2.985), stdev = 0.007
  CI (99.9%): [2.856, 3.099] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.603 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.003 ms/op
Iteration   1: 3.102 ±(99.9%) 0.004 ms/op
Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
Iteration   3: 3.105 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.130 ±(99.9%) 0.838 ms/op [Average]
  (min, avg, max) = (3.102, 3.130, 3.183), stdev = 0.046
  CI (99.9%): [2.291, 3.968] (assumes normal distribution)


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
# Warmup Iteration   1: 5.483 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.009 ms/op
Iteration   1: 3.907 ±(99.9%) 0.034 ms/op
Iteration   2: 3.975 ±(99.9%) 0.033 ms/op
Iteration   3: 3.908 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.907, 3.930, 3.975), stdev = 0.039
  CI (99.9%): [3.217, 4.643] (assumes normal distribution)


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.006 ms/op
Iteration   1: 3.141 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 12.377 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  9.535 ms/op
                 createUser·p0.9999: 14.491 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  9.039 ms/op
                 createUser·p0.9999: 16.744 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306152
  mean =      3.135 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 348 
    [ 1.250,  2.500) = 8980 
    [ 2.500,  3.750) = 274304 
    [ 3.750,  5.000) = 20261 
    [ 5.000,  6.250) = 1388 
    [ 6.250,  7.500) = 428 
    [ 7.500,  8.750) = 118 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     16.216 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.005 ms/op
Iteration   1: 3.136 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.119 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  12.272 ms/op
                 existUser·p0.9999: 18.077 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.458 ms/op
                 existUser·p0.9999: 17.423 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307991
  mean =      3.116 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 388 
    [ 1.250,  2.500) = 12186 
    [ 2.500,  3.750) = 269150 
    [ 3.750,  5.000) = 24858 
    [ 5.000,  6.250) = 562 
    [ 6.250,  7.500) = 374 
    [ 7.500,  8.750) = 120 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      9.618 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.293 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.397 ms/op
                 getUser·p0.9999: 16.447 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  10.408 ms/op
                 getUser·p0.9999: 17.523 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.280 ms/op
                 getUser·p0.999:  7.084 ms/op
                 getUser·p0.9999: 29.065 ms/op
                 getUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303728
  mean =      3.161 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4630 
    [ 2.500,  5.000) = 297154 
    [ 5.000,  7.500) = 1561 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.352 ms/op
     p(99.9900) =     28.791 ms/op
     p(99.9990) =     31.527 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 5.064 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.010 ms/op
Iteration   1: 4.011 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.888 ms/op
                 listUser·p0.9999: 14.877 ms/op
                 listUser·p1.00:   15.909 ms/op

Iteration   2: 3.909 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.059 ms/op
                 listUser·p0.9999: 17.780 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.428 ms/op
                 listUser·p0.9999: 18.346 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243165
  mean =      3.950 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1837 
    [ 2.500,  5.000) = 227835 
    [ 5.000,  7.500) = 12558 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     17.608 ms/op
     p(99.9990) =     19.667 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.273 ± 2.706  ops/ms
ClientGrpc.existUser                       thrpt       3  10.618 ± 0.813  ops/ms
ClientGrpc.getUser                         thrpt       3  10.000 ± 1.745  ops/ms
ClientGrpc.listUser                        thrpt       3   8.155 ± 4.708  ops/ms
ClientGrpc.createUser                       avgt       3   3.160 ± 0.367   ms/op
ClientGrpc.existUser                        avgt       3   2.978 ± 0.121   ms/op
ClientGrpc.getUser                          avgt       3   3.130 ± 0.838   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 0.713   ms/op
ClientGrpc.createUser                     sample  306152   3.135 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.725           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.962           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.216           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.908           ms/op
ClientGrpc.existUser                      sample  307991   3.116 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.823           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.064           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.618           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.400           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.071           ms/op
ClientGrpc.getUser                        sample  303728   3.161 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.777           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.352           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.791           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.621           ms/op
ClientGrpc.listUser                       sample  243165   3.950 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.000           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.107           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.608           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.283           ms/op
