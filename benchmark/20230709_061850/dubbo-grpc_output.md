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
# Warmup Iteration   1: 4.358 ops/ms
# Warmup Iteration   2: 9.570 ops/ms
# Warmup Iteration   3: 9.946 ops/ms
Iteration   1: 10.390 ops/ms
Iteration   2: 10.552 ops/ms
Iteration   3: 10.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.469 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (10.390, 10.469, 10.552), stdev = 0.081
  CI (99.9%): [8.989, 11.949] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.923 ops/ms
# Warmup Iteration   2: 10.711 ops/ms
# Warmup Iteration   3: 11.170 ops/ms
Iteration   1: 10.989 ops/ms
Iteration   2: 11.188 ops/ms
Iteration   3: 11.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.159 ±(99.9%) 2.873 ops/ms [Average]
  (min, avg, max) = (10.989, 11.159, 11.301), stdev = 0.157
  CI (99.9%): [8.286, 14.032] (assumes normal distribution)


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
# Warmup Iteration   1: 7.347 ops/ms
# Warmup Iteration   2: 10.278 ops/ms
# Warmup Iteration   3: 10.633 ops/ms
Iteration   1: 10.720 ops/ms
Iteration   2: 10.647 ops/ms
Iteration   3: 10.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.698 ±(99.9%) 0.809 ops/ms [Average]
  (min, avg, max) = (10.647, 10.698, 10.726), stdev = 0.044
  CI (99.9%): [9.889, 11.507] (assumes normal distribution)


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
# Warmup Iteration   1: 6.113 ops/ms
# Warmup Iteration   2: 7.725 ops/ms
# Warmup Iteration   3: 7.971 ops/ms
Iteration   1: 8.176 ops/ms
Iteration   2: 8.206 ops/ms
Iteration   3: 8.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.169 ±(99.9%) 0.739 ops/ms [Average]
  (min, avg, max) = (8.126, 8.169, 8.206), stdev = 0.041
  CI (99.9%): [7.430, 8.909] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.003 ms/op
Iteration   1: 3.048 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 3.067 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.047 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.026, 3.047, 3.067), stdev = 0.021
  CI (99.9%): [2.672, 3.422] (assumes normal distribution)


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.004 ms/op
Iteration   1: 2.949 ±(99.9%) 0.003 ms/op
Iteration   2: 2.936 ±(99.9%) 0.002 ms/op
Iteration   3: 2.969 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.951 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.936, 2.951, 2.969), stdev = 0.017
  CI (99.9%): [2.645, 3.257] (assumes normal distribution)


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.003 ms/op
Iteration   2: 3.042 ±(99.9%) 0.005 ms/op
Iteration   3: 2.936 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (2.936, 3.008, 3.044), stdev = 0.062
  CI (99.9%): [1.881, 4.135] (assumes normal distribution)


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.014 ms/op
Iteration   1: 3.956 ±(99.9%) 0.013 ms/op
Iteration   2: 3.883 ±(99.9%) 0.015 ms/op
Iteration   3: 3.928 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (3.883, 3.922, 3.956), stdev = 0.037
  CI (99.9%): [3.253, 4.592] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.169 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 17.452 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.254 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  11.514 ms/op
                 createUser·p0.9999: 12.651 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  10.253 ms/op
                 createUser·p0.9999: 20.677 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312973
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19478 
    [ 2.500,  5.000) = 291564 
    [ 5.000,  7.500) = 1386 
    [ 7.500, 10.000) = 232 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =     10.012 ms/op
     p(99.9900) =     19.725 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.005 ms/op
Iteration   1: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.418 ms/op
                 existUser·p0.9999: 17.269 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.312 ms/op
                 existUser·p0.9999: 20.420 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  10.224 ms/op
                 existUser·p0.9999: 16.451 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325432
  mean =      2.948 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31621 
    [ 2.500,  5.000) = 292523 
    [ 5.000,  7.500) = 990 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.313 ms/op
     p(99.9900) =     18.489 ms/op
     p(99.9990) =     20.725 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.798 ms/op
                 getUser·p0.9999: 13.124 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 16.253 ms/op
                 getUser·p1.00:   16.466 ms/op

Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.375 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.580 ms/op
                 getUser·p0.9999: 18.039 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314048
  mean =      3.055 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1495 
    [ 1.250,  2.500) = 17478 
    [ 2.500,  3.750) = 278188 
    [ 3.750,  5.000) = 15215 
    [ 5.000,  6.250) = 955 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.036 ms/op
     p(99.9900) =     17.681 ms/op
     p(99.9990) =     18.247 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 5.175 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
Iteration   1: 3.887 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.349 ms/op
                 listUser·p0.9999: 16.008 ms/op
                 listUser·p1.00:   16.204 ms/op

Iteration   2: 3.827 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.931 ms/op
                 listUser·p0.999:  13.081 ms/op
                 listUser·p0.9999: 14.057 ms/op
                 listUser·p1.00:   16.024 ms/op

Iteration   3: 3.807 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 15.222 ms/op
                 listUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250193
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 4108 
    [ 2.500,  3.750) = 127429 
    [ 3.750,  5.000) = 100683 
    [ 5.000,  6.250) = 12969 
    [ 6.250,  7.500) = 3772 
    [ 7.500,  8.750) = 581 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 174 
    [13.750, 15.000) = 104 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     15.139 ms/op
     p(99.9990) =     16.196 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.469 ± 1.480  ops/ms
ClientGrpc.existUser                       thrpt       3  11.159 ± 2.873  ops/ms
ClientGrpc.getUser                         thrpt       3  10.698 ± 0.809  ops/ms
ClientGrpc.listUser                        thrpt       3   8.169 ± 0.739  ops/ms
ClientGrpc.createUser                       avgt       3   3.047 ± 0.375   ms/op
ClientGrpc.existUser                        avgt       3   2.951 ± 0.306   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 1.127   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 0.669   ms/op
ClientGrpc.createUser                     sample  312973   3.067 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.254           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.012           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.725           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.135           ms/op
ClientGrpc.existUser                      sample  325432   2.948 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.546           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.313           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.489           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.168           ms/op
ClientGrpc.getUser                        sample  314048   3.055 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.375           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.036           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.681           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.547           ms/op
ClientGrpc.listUser                       sample  250193   3.840 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.863           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.993           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.139           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          16.204           ms/op
