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
# Warmup Iteration   1: 3.942 ops/ms
# Warmup Iteration   2: 8.749 ops/ms
# Warmup Iteration   3: 9.920 ops/ms
Iteration   1: 10.705 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.616 ±(99.9%) 2.043 ops/ms [Average]
  (min, avg, max) = (10.490, 10.616, 10.705), stdev = 0.112
  CI (99.9%): [8.574, 12.659] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.151 ops/ms
# Warmup Iteration   2: 10.856 ops/ms
# Warmup Iteration   3: 11.167 ops/ms
Iteration   1: 11.090 ops/ms
Iteration   2: 11.670 ops/ms
Iteration   3: 11.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.344 ±(99.9%) 5.414 ops/ms [Average]
  (min, avg, max) = (11.090, 11.344, 11.670), stdev = 0.297
  CI (99.9%): [5.930, 16.758] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.531 ops/ms
# Warmup Iteration   2: 10.204 ops/ms
# Warmup Iteration   3: 10.537 ops/ms
Iteration   1: 10.408 ops/ms
Iteration   2: 10.476 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.518 ±(99.9%) 2.468 ops/ms [Average]
  (min, avg, max) = (10.408, 10.518, 10.669), stdev = 0.135
  CI (99.9%): [8.050, 12.985] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.878 ops/ms
# Warmup Iteration   2: 7.846 ops/ms
# Warmup Iteration   3: 8.083 ops/ms
Iteration   1: 8.108 ops/ms
Iteration   2: 8.123 ops/ms
Iteration   3: 8.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.185 ±(99.9%) 2.202 ops/ms [Average]
  (min, avg, max) = (8.108, 8.185, 8.324), stdev = 0.121
  CI (99.9%): [5.983, 10.387] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.441 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.009 ms/op
Iteration   2: 3.032 ±(99.9%) 0.002 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.018 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.995, 3.018, 3.032), stdev = 0.020
  CI (99.9%): [2.657, 3.379] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.195 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.003 ms/op
Iteration   1: 2.883 ±(99.9%) 0.002 ms/op
Iteration   2: 2.934 ±(99.9%) 0.001 ms/op
Iteration   3: 2.959 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.925 ±(99.9%) 0.710 ms/op [Average]
  (min, avg, max) = (2.883, 2.925, 2.959), stdev = 0.039
  CI (99.9%): [2.215, 3.635] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.389 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.038 ms/op
Iteration   1: 3.029 ±(99.9%) 0.003 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.021 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (2.994, 3.021, 3.040), stdev = 0.024
  CI (99.9%): [2.588, 3.455] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.666 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.014 ms/op
Iteration   1: 3.952 ±(99.9%) 0.034 ms/op
Iteration   2: 3.830 ±(99.9%) 0.009 ms/op
Iteration   3: 3.923 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.902 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (3.830, 3.902, 3.952), stdev = 0.064
  CI (99.9%): [2.737, 5.067] (assumes normal distribution)


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
# Warmup Iteration   1: 4.393 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
Iteration   1: 3.118 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.393 ms/op
                 createUser·p0.9999: 13.208 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.219 ms/op
                 createUser·p0.9999: 19.452 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   3: 3.019 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  11.257 ms/op
                 createUser·p0.9999: 20.919 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312302
  mean =      3.075 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16028 
    [ 2.500,  5.000) = 294766 
    [ 5.000,  7.500) = 1169 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     20.210 ms/op
     p(99.9990) =     22.012 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.278 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.006 ms/op
Iteration   1: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.437 ms/op
                 existUser·p0.9999: 20.086 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 2.946 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  5.953 ms/op
                 existUser·p0.9999: 17.928 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  7.625 ms/op
                 existUser·p0.9999: 20.388 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327075
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34700 
    [ 2.500,  5.000) = 291566 
    [ 5.000,  7.500) = 585 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      6.405 ms/op
     p(99.9900) =     20.064 ms/op
     p(99.9990) =     21.550 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.523 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 12.703 ms/op
                 getUser·p1.00:   13.222 ms/op

Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.563 ms/op
                 getUser·p0.9999: 14.490 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.514 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.520 ms/op
                 getUser·p0.9999: 23.350 ms/op
                 getUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316850
  mean =      3.028 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22825 
    [ 2.500,  5.000) = 292755 
    [ 5.000,  7.500) = 910 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.841 ms/op
     p(99.9900) =     21.961 ms/op
     p(99.9990) =     23.647 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 5.160 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.012 ms/op
Iteration   1: 3.961 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  16.978 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 3.954 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 26.065 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   3: 3.939 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.527 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.167 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 23.589 ms/op
                 listUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242992
  mean =      3.952 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3508 
    [ 2.500,  5.000) = 215319 
    [ 5.000,  7.500) = 22570 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     24.874 ms/op
     p(99.9990) =     26.925 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.616 ± 2.043  ops/ms
ClientGrpc.existUser                       thrpt       3  11.344 ± 5.414  ops/ms
ClientGrpc.getUser                         thrpt       3  10.518 ± 2.468  ops/ms
ClientGrpc.listUser                        thrpt       3   8.185 ± 2.202  ops/ms
ClientGrpc.createUser                       avgt       3   3.018 ± 0.361   ms/op
ClientGrpc.existUser                        avgt       3   2.925 ± 0.710   ms/op
ClientGrpc.getUser                          avgt       3   3.021 ± 0.434   ms/op
ClientGrpc.listUser                         avgt       3   3.902 ± 1.165   ms/op
ClientGrpc.createUser                     sample  312302   3.075 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.758           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.210           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  327075   2.934 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.631           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.405           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.064           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  316850   3.028 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.514           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.841           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.961           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.347           ms/op
ClientGrpc.listUser                       sample  242992   3.952 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.527           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.874           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.099           ms/op
