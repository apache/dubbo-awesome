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
# Warmup Iteration   1: 4.075 ops/ms
# Warmup Iteration   2: 9.316 ops/ms
# Warmup Iteration   3: 10.419 ops/ms
Iteration   1: 10.350 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.593 ±(99.9%) 4.072 ops/ms [Average]
  (min, avg, max) = (10.350, 10.593, 10.789), stdev = 0.223
  CI (99.9%): [6.520, 14.665] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.627 ops/ms
# Warmup Iteration   2: 10.732 ops/ms
# Warmup Iteration   3: 11.045 ops/ms
Iteration   1: 11.002 ops/ms
Iteration   2: 11.290 ops/ms
Iteration   3: 11.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.148 ±(99.9%) 2.624 ops/ms [Average]
  (min, avg, max) = (11.002, 11.148, 11.290), stdev = 0.144
  CI (99.9%): [8.523, 13.772] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.159 ops/ms
# Warmup Iteration   2: 10.211 ops/ms
# Warmup Iteration   3: 10.609 ops/ms
Iteration   1: 10.759 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.720 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (10.655, 10.720, 10.759), stdev = 0.057
  CI (99.9%): [9.679, 11.762] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.745 ops/ms
# Warmup Iteration   2: 8.176 ops/ms
# Warmup Iteration   3: 8.165 ops/ms
Iteration   1: 8.253 ops/ms
Iteration   2: 8.345 ops/ms
Iteration   3: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.264 ±(99.9%) 1.381 ops/ms [Average]
  (min, avg, max) = (8.195, 8.264, 8.345), stdev = 0.076
  CI (99.9%): [6.883, 9.645] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.144 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.003 ms/op
Iteration   2: 3.000 ±(99.9%) 0.002 ms/op
Iteration   3: 2.983 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.001 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (2.983, 3.001, 3.022), stdev = 0.019
  CI (99.9%): [2.647, 3.356] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.947 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.002 ms/op
Iteration   1: 2.892 ±(99.9%) 0.002 ms/op
Iteration   2: 2.848 ±(99.9%) 0.002 ms/op
Iteration   3: 2.864 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.868 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (2.848, 2.868, 2.892), stdev = 0.022
  CI (99.9%): [2.458, 3.278] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.003 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
Iteration   3: 2.946 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.943 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (2.939, 2.943, 2.946), stdev = 0.004
  CI (99.9%): [2.874, 3.012] (assumes normal distribution)


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
# Warmup Iteration   1: 5.133 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.016 ms/op
Iteration   1: 3.951 ±(99.9%) 0.025 ms/op
Iteration   2: 3.745 ±(99.9%) 0.009 ms/op
Iteration   3: 3.820 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.839 ±(99.9%) 1.900 ms/op [Average]
  (min, avg, max) = (3.745, 3.839, 3.951), stdev = 0.104
  CI (99.9%): [1.939, 5.738] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.219 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.947 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   2.916 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  6.668 ms/op
                 createUser·p0.9999: 16.499 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  9.054 ms/op
                 createUser·p0.9999: 18.809 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.039 ms/op
                 createUser·p0.999:  9.146 ms/op
                 createUser·p0.9999: 33.620 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320753
  mean =      2.991 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26466 
    [ 2.500,  5.000) = 293066 
    [ 5.000,  7.500) = 797 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.999 ms/op
     p(99.9900) =     32.122 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.894 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.803 ±(99.9%) 0.006 ms/op
Iteration   1: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.136 ms/op
                 existUser·p0.999:  7.002 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 2.897 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  8.445 ms/op
                 existUser·p0.9999: 13.958 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   3: 2.918 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  8.585 ms/op
                 existUser·p0.9999: 30.736 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330570
  mean =      2.903 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45872 
    [ 2.500,  5.000) = 283719 
    [ 5.000,  7.500) = 627 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.971 ms/op
     p(99.9900) =     24.867 ms/op
     p(99.9990) =     30.857 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.243 ms/op
                 getUser·p0.9999: 13.877 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  10.476 ms/op
                 getUser·p0.9999: 15.701 ms/op
                 getUser·p1.00:   16.089 ms/op

Iteration   3: 3.012 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.311 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.652 ms/op
                 getUser·p0.9999: 18.309 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318783
  mean =      3.013 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 626 
    [ 1.250,  2.500) = 24290 
    [ 2.500,  3.750) = 279104 
    [ 3.750,  5.000) = 13076 
    [ 5.000,  6.250) = 885 
    [ 6.250,  7.500) = 448 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.311 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.620 ms/op
     p(99.9900) =     15.976 ms/op
     p(99.9990) =     18.469 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 5.222 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.010 ms/op
Iteration   1: 3.784 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.673 ms/op
                 listUser·p0.9999: 15.685 ms/op
                 listUser·p1.00:   16.728 ms/op

Iteration   2: 3.816 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.228 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.945 ms/op
                 listUser·p0.9999: 16.335 ms/op
                 listUser·p1.00:   16.515 ms/op

Iteration   3: 3.858 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  14.024 ms/op
                 listUser·p0.9999: 25.975 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251358
  mean =      3.819 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2704 
    [ 2.500,  5.000) = 232568 
    [ 5.000,  7.500) = 15189 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     25.391 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.593 ± 4.072  ops/ms
ClientGrpc.existUser                       thrpt       3  11.148 ± 2.624  ops/ms
ClientGrpc.getUser                         thrpt       3  10.720 ± 1.042  ops/ms
ClientGrpc.listUser                        thrpt       3   8.264 ± 1.381  ops/ms
ClientGrpc.createUser                       avgt       3   3.001 ± 0.355   ms/op
ClientGrpc.existUser                        avgt       3   2.868 ± 0.410   ms/op
ClientGrpc.getUser                          avgt       3   2.943 ± 0.069   ms/op
ClientGrpc.listUser                         avgt       3   3.839 ± 1.900   ms/op
ClientGrpc.createUser                     sample  320753   2.991 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.797           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.999           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.122           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.948           ms/op
ClientGrpc.existUser                      sample  330570   2.903 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.501           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.971           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.867           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.867           ms/op
ClientGrpc.getUser                        sample  318783   3.013 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.311           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.620           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.976           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.579           ms/op
ClientGrpc.listUser                       sample  251358   3.819 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.155           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.599           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.391           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.214           ms/op
