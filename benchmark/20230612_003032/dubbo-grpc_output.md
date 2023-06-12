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
# Warmup Iteration   1: 3.826 ops/ms
# Warmup Iteration   2: 9.126 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.366 ops/ms
Iteration   2: 10.243 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.369 ±(99.9%) 2.324 ops/ms [Average]
  (min, avg, max) = (10.243, 10.369, 10.498), stdev = 0.127
  CI (99.9%): [8.045, 12.693] (assumes normal distribution)


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
# Warmup Iteration   1: 7.161 ops/ms
# Warmup Iteration   2: 10.506 ops/ms
# Warmup Iteration   3: 10.719 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 11.007 ops/ms
Iteration   3: 11.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.973 ±(99.9%) 2.871 ops/ms [Average]
  (min, avg, max) = (10.802, 10.973, 11.111), stdev = 0.157
  CI (99.9%): [8.102, 13.844] (assumes normal distribution)


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
# Warmup Iteration   1: 6.715 ops/ms
# Warmup Iteration   2: 9.878 ops/ms
# Warmup Iteration   3: 10.194 ops/ms
Iteration   1: 10.415 ops/ms
Iteration   2: 10.517 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.446 ±(99.9%) 1.118 ops/ms [Average]
  (min, avg, max) = (10.406, 10.446, 10.517), stdev = 0.061
  CI (99.9%): [9.328, 11.564] (assumes normal distribution)


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
# Warmup Iteration   1: 4.943 ops/ms
# Warmup Iteration   2: 7.672 ops/ms
# Warmup Iteration   3: 7.657 ops/ms
Iteration   1: 7.958 ops/ms
Iteration   2: 7.840 ops/ms
Iteration   3: 8.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.952 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (7.840, 7.952, 8.059), stdev = 0.109
  CI (99.9%): [5.959, 9.946] (assumes normal distribution)


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.002 ms/op
Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
Iteration   3: 3.074 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.008, 3.051, 3.074), stdev = 0.037
  CI (99.9%): [2.384, 3.717] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.003 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.987 ±(99.9%) 0.002 ms/op
Iteration   3: 2.909 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.935 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (2.909, 2.935, 2.987), stdev = 0.045
  CI (99.9%): [2.119, 3.751] (assumes normal distribution)


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.059 ±(99.9%) 0.003 ms/op
Iteration   3: 3.084 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.079 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (3.059, 3.079, 3.093), stdev = 0.018
  CI (99.9%): [2.757, 3.400] (assumes normal distribution)


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
# Warmup Iteration   1: 6.123 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.032 ms/op
Iteration   1: 4.045 ±(99.9%) 0.012 ms/op
Iteration   2: 4.029 ±(99.9%) 0.009 ms/op
Iteration   3: 4.137 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.070 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (4.029, 4.070, 4.137), stdev = 0.058
  CI (99.9%): [3.008, 5.133] (assumes normal distribution)


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
# Warmup Iteration   1: 4.286 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.008 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.110 ms/op
                 createUser·p0.9999: 13.526 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   2: 3.064 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  9.183 ms/op
                 createUser·p0.9999: 15.942 ms/op
                 createUser·p1.00:   16.269 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 28.443 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308331
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11857 
    [ 2.500,  5.000) = 294952 
    [ 5.000,  7.500) = 1117 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     28.800 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.005 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.942 ms/op
                 existUser·p0.9999: 22.435 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 2.944 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  7.209 ms/op
                 existUser·p0.9999: 13.357 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.671 ms/op
                 existUser·p0.9999: 14.227 ms/op
                 existUser·p1.00:   14.434 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323576
  mean =      2.966 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21411 
    [ 2.500,  5.000) = 301388 
    [ 5.000,  7.500) = 566 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      6.852 ms/op
     p(99.9900) =     19.117 ms/op
     p(99.9990) =     22.766 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  8.989 ms/op
                 getUser·p0.9999: 12.560 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 3.064 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.324 ms/op
                 getUser·p0.9999: 13.502 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.313 ms/op
                 getUser·p0.9999: 17.957 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314004
  mean =      3.057 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 799 
    [ 1.250,  2.500) = 20569 
    [ 2.500,  3.750) = 273435 
    [ 3.750,  5.000) = 17231 
    [ 5.000,  6.250) = 1245 
    [ 6.250,  7.500) = 347 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     16.099 ms/op
     p(99.9990) =     18.341 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 5.080 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.011 ms/op
Iteration   1: 4.037 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  12.894 ms/op
                 listUser·p0.9999: 14.369 ms/op
                 listUser·p1.00:   15.204 ms/op

Iteration   2: 4.047 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.563 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 3.968 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 23.422 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239189
  mean =      4.017 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3068 
    [ 2.500,  5.000) = 208894 
    [ 5.000,  7.500) = 25897 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     22.061 ms/op
     p(99.9990) =     23.862 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.369 ± 2.324  ops/ms
ClientGrpc.existUser                       thrpt       3  10.973 ± 2.871  ops/ms
ClientGrpc.getUser                         thrpt       3  10.446 ± 1.118  ops/ms
ClientGrpc.listUser                        thrpt       3   7.952 ± 1.993  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 0.667   ms/op
ClientGrpc.existUser                        avgt       3   2.935 ± 0.816   ms/op
ClientGrpc.getUser                          avgt       3   3.079 ± 0.321   ms/op
ClientGrpc.listUser                         avgt       3   4.070 ± 1.063   ms/op
ClientGrpc.createUser                     sample  308331   3.111 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.530           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.536           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.280           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.967           ms/op
ClientGrpc.existUser                      sample  323576   2.966 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.055           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.852           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.117           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.905           ms/op
ClientGrpc.getUser                        sample  314004   3.057 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.824           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.799           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.099           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.481           ms/op
ClientGrpc.listUser                       sample  239189   4.017 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.194           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.090           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.061           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.986           ms/op
