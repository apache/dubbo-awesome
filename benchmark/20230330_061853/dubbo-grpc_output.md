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
# Warmup Iteration   1: 4.093 ops/ms
# Warmup Iteration   2: 8.768 ops/ms
# Warmup Iteration   3: 10.124 ops/ms
Iteration   1: 10.448 ops/ms
Iteration   2: 10.421 ops/ms
Iteration   3: 10.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.476 ±(99.9%) 1.347 ops/ms [Average]
  (min, avg, max) = (10.421, 10.476, 10.560), stdev = 0.074
  CI (99.9%): [9.129, 11.824] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.942 ops/ms
# Warmup Iteration   2: 10.420 ops/ms
# Warmup Iteration   3: 11.016 ops/ms
Iteration   1: 10.924 ops/ms
Iteration   2: 11.006 ops/ms
Iteration   3: 11.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.977 ±(99.9%) 0.836 ops/ms [Average]
  (min, avg, max) = (10.924, 10.977, 11.006), stdev = 0.046
  CI (99.9%): [10.141, 11.813] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.707 ops/ms
# Warmup Iteration   2: 10.084 ops/ms
# Warmup Iteration   3: 10.497 ops/ms
Iteration   1: 10.495 ops/ms
Iteration   2: 10.555 ops/ms
Iteration   3: 10.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.582 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (10.495, 10.582, 10.695), stdev = 0.103
  CI (99.9%): [8.703, 12.460] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.795 ops/ms
# Warmup Iteration   2: 7.426 ops/ms
# Warmup Iteration   3: 7.904 ops/ms
Iteration   1: 7.936 ops/ms
Iteration   2: 7.977 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.982 ±(99.9%) 0.889 ops/ms [Average]
  (min, avg, max) = (7.936, 7.982, 8.033), stdev = 0.049
  CI (99.9%): [7.093, 8.871] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.508 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 3.079 ±(99.9%) 0.003 ms/op
Iteration   2: 3.013 ±(99.9%) 0.002 ms/op
Iteration   3: 3.060 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.013, 3.051, 3.079), stdev = 0.034
  CI (99.9%): [2.436, 3.666] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.209 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.878 ±(99.9%) 0.002 ms/op
Iteration   1: 2.928 ±(99.9%) 0.003 ms/op
Iteration   2: 2.886 ±(99.9%) 0.002 ms/op
Iteration   3: 2.894 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.903 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (2.886, 2.903, 2.928), stdev = 0.022
  CI (99.9%): [2.501, 3.305] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.003 ms/op
Iteration   1: 3.091 ±(99.9%) 0.004 ms/op
Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
Iteration   3: 3.066 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.085 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.066, 3.085, 3.098), stdev = 0.017
  CI (99.9%): [2.776, 3.394] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.414 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.048 ms/op
Iteration   1: 4.036 ±(99.9%) 0.009 ms/op
Iteration   2: 3.951 ±(99.9%) 0.009 ms/op
Iteration   3: 3.843 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.943 ±(99.9%) 1.767 ms/op [Average]
  (min, avg, max) = (3.843, 3.943, 4.036), stdev = 0.097
  CI (99.9%): [2.176, 5.711] (assumes normal distribution)


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.516 ms/op
                 createUser·p0.9999: 35.914 ms/op
                 createUser·p1.00:   36.372 ms/op

Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.383 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  6.806 ms/op
                 createUser·p0.9999: 33.898 ms/op
                 createUser·p1.00:   34.144 ms/op

Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  10.975 ms/op
                 createUser·p0.9999: 22.511 ms/op
                 createUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316807
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20257 
    [ 2.500,  5.000) = 295408 
    [ 5.000,  7.500) = 702 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 46 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     10.430 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     36.219 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
Iteration   1: 2.901 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  7.821 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   12.878 ms/op

Iteration   2: 2.888 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.833 ms/op
                 existUser·p0.9999: 14.593 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   3: 2.862 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.322 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  8.023 ms/op
                 existUser·p0.9999: 19.052 ms/op
                 existUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332846
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1559 
    [ 1.250,  2.500) = 30414 
    [ 2.500,  3.750) = 294878 
    [ 3.750,  5.000) = 5025 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 291 
    [ 7.500,  8.750) = 116 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.248 ms/op
     p(95.0000) =      3.408 ms/op
     p(99.0000) =      4.035 ms/op
     p(99.9000) =      7.595 ms/op
     p(99.9900) =     17.194 ms/op
     p(99.9990) =     19.224 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.300 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.502 ms/op
                 getUser·p0.9999: 14.244 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.989 ms/op
                 getUser·p0.9999: 14.041 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  6.922 ms/op
                 getUser·p0.9999: 17.492 ms/op
                 getUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317130
  mean =      3.028 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 632 
    [ 1.250,  2.500) = 17796 
    [ 2.500,  3.750) = 285678 
    [ 3.750,  5.000) = 11348 
    [ 5.000,  6.250) = 1045 
    [ 6.250,  7.500) = 392 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.085 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.010 ms/op
Iteration   1: 4.044 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.334 ms/op
                 listUser·p0.999:  15.183 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 3.990 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.923 ms/op
                 listUser·p0.9999: 22.411 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 3.998 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  17.920 ms/op
                 listUser·p0.9999: 23.166 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239437
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3325 
    [ 2.500,  5.000) = 210601 
    [ 5.000,  7.500) = 23900 
    [ 7.500, 10.000) = 1097 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.108 ms/op
     p(99.9000) =     16.492 ms/op
     p(99.9900) =     22.743 ms/op
     p(99.9990) =     23.620 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.476 ± 1.347  ops/ms
ClientGrpc.existUser                       thrpt       3  10.977 ± 0.836  ops/ms
ClientGrpc.getUser                         thrpt       3  10.582 ± 1.878  ops/ms
ClientGrpc.listUser                        thrpt       3   7.982 ± 0.889  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 0.615   ms/op
ClientGrpc.existUser                        avgt       3   2.903 ± 0.402   ms/op
ClientGrpc.getUser                          avgt       3   3.085 ± 0.309   ms/op
ClientGrpc.listUser                         avgt       3   3.943 ± 1.767   ms/op
ClientGrpc.createUser                     sample  316807   3.030 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.430           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.406           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.372           ms/op
ClientGrpc.existUser                      sample  332846   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.787           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.248           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.035           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.595           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.194           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.268           ms/op
ClientGrpc.getUser                        sample  317130   3.028 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.085           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.908           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.088           ms/op
ClientGrpc.listUser                       sample  239437   4.011 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.139           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.108           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.492           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.743           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.691           ms/op
