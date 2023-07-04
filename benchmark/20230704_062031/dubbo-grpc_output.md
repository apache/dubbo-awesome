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
# Warmup Iteration   1: 4.773 ops/ms
# Warmup Iteration   2: 9.390 ops/ms
# Warmup Iteration   3: 10.109 ops/ms
Iteration   1: 10.831 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 11.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.817 ±(99.9%) 3.618 ops/ms [Average]
  (min, avg, max) = (10.612, 10.817, 11.008), stdev = 0.198
  CI (99.9%): [7.199, 14.435] (assumes normal distribution)


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
# Warmup Iteration   1: 8.208 ops/ms
# Warmup Iteration   2: 11.326 ops/ms
# Warmup Iteration   3: 11.295 ops/ms
Iteration   1: 11.535 ops/ms
Iteration   2: 11.262 ops/ms
Iteration   3: 11.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.485 ±(99.9%) 3.705 ops/ms [Average]
  (min, avg, max) = (11.262, 11.485, 11.659), stdev = 0.203
  CI (99.9%): [7.780, 15.191] (assumes normal distribution)


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
# Warmup Iteration   1: 7.544 ops/ms
# Warmup Iteration   2: 10.491 ops/ms
# Warmup Iteration   3: 10.559 ops/ms
Iteration   1: 10.789 ops/ms
Iteration   2: 10.547 ops/ms
Iteration   3: 10.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.689 ±(99.9%) 2.301 ops/ms [Average]
  (min, avg, max) = (10.547, 10.689, 10.789), stdev = 0.126
  CI (99.9%): [8.388, 12.989] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.182 ops/ms
# Warmup Iteration   2: 7.704 ops/ms
# Warmup Iteration   3: 8.065 ops/ms
Iteration   1: 8.007 ops/ms
Iteration   2: 8.131 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.062 ±(99.9%) 1.153 ops/ms [Average]
  (min, avg, max) = (8.007, 8.062, 8.131), stdev = 0.063
  CI (99.9%): [6.910, 9.215] (assumes normal distribution)


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
# Warmup Iteration   1: 3.686 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.004 ms/op
Iteration   1: 2.993 ±(99.9%) 0.002 ms/op
Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.973 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.952, 2.973, 2.993), stdev = 0.021
  CI (99.9%): [2.599, 3.347] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.808 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.004 ms/op
Iteration   1: 2.819 ±(99.9%) 0.003 ms/op
Iteration   2: 2.843 ±(99.9%) 0.004 ms/op
Iteration   3: 2.880 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.847 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (2.819, 2.847, 2.880), stdev = 0.030
  CI (99.9%): [2.294, 3.400] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
Iteration   1: 3.008 ±(99.9%) 0.003 ms/op
Iteration   2: 2.972 ±(99.9%) 0.002 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.989 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.972, 2.989, 3.008), stdev = 0.018
  CI (99.9%): [2.654, 3.323] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.043 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.012 ms/op
Iteration   1: 3.944 ±(99.9%) 0.020 ms/op
Iteration   2: 3.881 ±(99.9%) 0.014 ms/op
Iteration   3: 3.861 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.895 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.861, 3.895, 3.944), stdev = 0.043
  CI (99.9%): [3.102, 4.688] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  10.293 ms/op
                 createUser·p0.9999: 16.792 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.187 ms/op
                 createUser·p0.9999: 12.751 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.825 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.786 ms/op
                 createUser·p0.9999: 17.001 ms/op
                 createUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318839
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1231 
    [ 1.250,  2.500) = 22655 
    [ 2.500,  3.750) = 278637 
    [ 3.750,  5.000) = 15149 
    [ 5.000,  6.250) = 547 
    [ 6.250,  7.500) = 186 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      9.210 ms/op
     p(99.9900) =     16.568 ms/op
     p(99.9990) =     17.387 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.814 ±(99.9%) 0.006 ms/op
Iteration   1: 2.863 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   3.957 ms/op
                 existUser·p0.999:  5.463 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   11.960 ms/op

Iteration   2: 2.843 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 15.348 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   3: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  11.133 ms/op
                 existUser·p0.9999: 16.196 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335342
  mean =      2.861 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3333 
    [ 1.250,  2.500) = 36720 
    [ 2.500,  3.750) = 287192 
    [ 3.750,  5.000) = 7148 
    [ 5.000,  6.250) = 487 
    [ 6.250,  7.500) = 155 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 67 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.461 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.018 ms/op
     p(99.9900) =     15.720 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.005 ms/op
Iteration   1: 3.026 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  5.753 ms/op
                 getUser·p0.9999: 11.172 ms/op
                 getUser·p1.00:   11.469 ms/op

Iteration   2: 2.992 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  11.848 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  9.289 ms/op
                 getUser·p0.9999: 13.800 ms/op
                 getUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319577
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27275 
    [ 2.500,  5.000) = 290925 
    [ 5.000,  7.500) = 953 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     10.057 ms/op
     p(99.9900) =     21.368 ms/op
     p(99.9990) =     22.564 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.010 ms/op
Iteration   1: 3.922 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 20.239 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   2: 3.967 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 18.741 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 3.877 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  15.163 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244796
  mean =      3.921 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4748 
    [ 2.500,  5.000) = 219737 
    [ 5.000,  7.500) = 19031 
    [ 7.500, 10.000) = 779 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     15.126 ms/op
     p(99.9900) =     20.892 ms/op
     p(99.9990) =     23.531 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.817 ± 3.618  ops/ms
ClientGrpc.existUser                       thrpt       3  11.485 ± 3.705  ops/ms
ClientGrpc.getUser                         thrpt       3  10.689 ± 2.301  ops/ms
ClientGrpc.listUser                        thrpt       3   8.062 ± 1.153  ops/ms
ClientGrpc.createUser                       avgt       3   2.973 ± 0.374   ms/op
ClientGrpc.existUser                        avgt       3   2.847 ± 0.553   ms/op
ClientGrpc.getUser                          avgt       3   2.989 ± 0.335   ms/op
ClientGrpc.listUser                         avgt       3   3.895 ± 0.793   ms/op
ClientGrpc.createUser                     sample  318839   3.011 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.210           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.568           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.498           ms/op
ClientGrpc.existUser                      sample  335342   2.861 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.513           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.277           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.018           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.720           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.810           ms/op
ClientGrpc.getUser                        sample  319577   3.001 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.579           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.057           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.368           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  244796   3.921 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.863           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.126           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.892           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.626           ms/op
