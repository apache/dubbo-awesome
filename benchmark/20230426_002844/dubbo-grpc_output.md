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
# Warmup Iteration   1: 4.310 ops/ms
# Warmup Iteration   2: 8.993 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.654 ±(99.9%) 1.224 ops/ms [Average]
  (min, avg, max) = (10.576, 10.654, 10.694), stdev = 0.067
  CI (99.9%): [9.430, 11.877] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.481 ops/ms
# Warmup Iteration   2: 10.707 ops/ms
# Warmup Iteration   3: 11.052 ops/ms
Iteration   1: 11.079 ops/ms
Iteration   2: 11.306 ops/ms
Iteration   3: 11.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.191 ±(99.9%) 2.077 ops/ms [Average]
  (min, avg, max) = (11.079, 11.191, 11.306), stdev = 0.114
  CI (99.9%): [9.114, 13.268] (assumes normal distribution)


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
# Warmup Iteration   1: 7.274 ops/ms
# Warmup Iteration   2: 10.214 ops/ms
# Warmup Iteration   3: 10.419 ops/ms
Iteration   1: 10.587 ops/ms
Iteration   2: 10.512 ops/ms
Iteration   3: 10.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.589 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (10.512, 10.589, 10.670), stdev = 0.079
  CI (99.9%): [9.147, 12.031] (assumes normal distribution)


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
# Warmup Iteration   1: 5.429 ops/ms
# Warmup Iteration   2: 7.909 ops/ms
# Warmup Iteration   3: 7.968 ops/ms
Iteration   1: 8.126 ops/ms
Iteration   2: 8.112 ops/ms
Iteration   3: 8.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.083 ±(99.9%) 1.144 ops/ms [Average]
  (min, avg, max) = (8.011, 8.083, 8.126), stdev = 0.063
  CI (99.9%): [6.939, 9.227] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 3.046 ±(99.9%) 0.004 ms/op
Iteration   3: 3.033 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.050 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (3.033, 3.050, 3.070), stdev = 0.019
  CI (99.9%): [2.702, 3.397] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.003 ms/op
Iteration   1: 2.885 ±(99.9%) 0.002 ms/op
Iteration   2: 2.808 ±(99.9%) 0.003 ms/op
Iteration   3: 2.834 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.842 ±(99.9%) 0.719 ms/op [Average]
  (min, avg, max) = (2.808, 2.842, 2.885), stdev = 0.039
  CI (99.9%): [2.123, 3.562] (assumes normal distribution)


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.004 ms/op
Iteration   1: 3.012 ±(99.9%) 0.003 ms/op
Iteration   2: 2.987 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.987, 2.996, 3.012), stdev = 0.015
  CI (99.9%): [2.730, 3.261] (assumes normal distribution)


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
# Warmup Iteration   1: 5.240 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.017 ms/op
Iteration   1: 3.863 ±(99.9%) 0.020 ms/op
Iteration   2: 3.944 ±(99.9%) 0.038 ms/op
Iteration   3: 3.790 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.866 ±(99.9%) 1.401 ms/op [Average]
  (min, avg, max) = (3.790, 3.866, 3.944), stdev = 0.077
  CI (99.9%): [2.465, 5.266] (assumes normal distribution)


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.130 ms/op
                 createUser·p0.9999: 18.383 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 3.057 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 15.451 ms/op
                 createUser·p1.00:   15.892 ms/op

Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  10.376 ms/op
                 createUser·p0.9999: 18.874 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311708
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 509 
    [ 1.250,  2.500) = 18207 
    [ 2.500,  3.750) = 274824 
    [ 3.750,  5.000) = 16443 
    [ 5.000,  6.250) = 915 
    [ 6.250,  7.500) = 322 
    [ 7.500,  8.750) = 115 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 65 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      9.540 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 3.377 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.005 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.491 ms/op
                 existUser·p0.9999: 12.699 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   2: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.611 ms/op
                 existUser·p0.9999: 14.143 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.767 ms/op
                 existUser·p0.9999: 18.892 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326658
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36616 
    [ 2.500,  5.000) = 288827 
    [ 5.000,  7.500) = 908 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.217 ms/op
     p(99.9900) =     16.909 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  6.679 ms/op
                 getUser·p0.9999: 12.805 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.589 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.821 ms/op
                 getUser·p0.9999: 13.713 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.108 ms/op
                 getUser·p0.9999: 17.866 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317708
  mean =      3.022 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 424 
    [ 1.250,  2.500) = 22468 
    [ 2.500,  3.750) = 279281 
    [ 3.750,  5.000) = 13876 
    [ 5.000,  6.250) = 1166 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      6.821 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     18.606 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 5.132 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.011 ms/op
Iteration   1: 3.939 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  13.087 ms/op
                 listUser·p0.9999: 15.526 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 3.908 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  16.272 ms/op
                 listUser·p0.9999: 19.163 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 3.970 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.588 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243641
  mean =      3.939 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3497 
    [ 2.500,  5.000) = 218213 
    [ 5.000,  7.500) = 20577 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     14.407 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.218 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.654 ± 1.224  ops/ms
ClientGrpc.existUser                       thrpt       3  11.191 ± 2.077  ops/ms
ClientGrpc.getUser                         thrpt       3  10.589 ± 1.442  ops/ms
ClientGrpc.listUser                        thrpt       3   8.083 ± 1.144  ops/ms
ClientGrpc.createUser                       avgt       3   3.050 ± 0.348   ms/op
ClientGrpc.existUser                        avgt       3   2.842 ± 0.719   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.265   ms/op
ClientGrpc.listUser                         avgt       3   3.866 ± 1.401   ms/op
ClientGrpc.createUser                     sample  311708   3.080 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.651           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.540           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.416           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.907           ms/op
ClientGrpc.existUser                      sample  326658   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.535           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.217           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.909           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.578           ms/op
ClientGrpc.getUser                        sample  317708   3.022 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.613           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.821           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.466           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.678           ms/op
ClientGrpc.listUser                       sample  243641   3.939 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.915           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.407           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.741           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.462           ms/op
