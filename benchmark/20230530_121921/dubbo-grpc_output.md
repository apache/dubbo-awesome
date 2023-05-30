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
# Warmup Iteration   1: 5.032 ops/ms
# Warmup Iteration   2: 9.099 ops/ms
# Warmup Iteration   3: 10.037 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.553 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.520 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (10.434, 10.520, 10.575), stdev = 0.076
  CI (99.9%): [9.133, 11.908] (assumes normal distribution)


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
# Warmup Iteration   1: 7.935 ops/ms
# Warmup Iteration   2: 10.628 ops/ms
# Warmup Iteration   3: 11.033 ops/ms
Iteration   1: 11.290 ops/ms
Iteration   2: 11.181 ops/ms
Iteration   3: 10.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.132 ±(99.9%) 3.441 ops/ms [Average]
  (min, avg, max) = (10.923, 11.132, 11.290), stdev = 0.189
  CI (99.9%): [7.691, 14.572] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.687 ops/ms
# Warmup Iteration   2: 10.255 ops/ms
# Warmup Iteration   3: 10.707 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.586 ±(99.9%) 0.347 ops/ms [Average]
  (min, avg, max) = (10.573, 10.586, 10.608), stdev = 0.019
  CI (99.9%): [10.239, 10.934] (assumes normal distribution)


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
# Warmup Iteration   1: 5.509 ops/ms
# Warmup Iteration   2: 7.923 ops/ms
# Warmup Iteration   3: 8.019 ops/ms
Iteration   1: 8.123 ops/ms
Iteration   2: 8.133 ops/ms
Iteration   3: 8.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.142 ±(99.9%) 0.462 ops/ms [Average]
  (min, avg, max) = (8.123, 8.142, 8.171), stdev = 0.025
  CI (99.9%): [7.680, 8.604] (assumes normal distribution)


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.004 ms/op
Iteration   1: 2.999 ±(99.9%) 0.003 ms/op
Iteration   2: 3.002 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.014 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (2.999, 3.014, 3.041), stdev = 0.023
  CI (99.9%): [2.587, 3.441] (assumes normal distribution)


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.004 ms/op
Iteration   1: 2.932 ±(99.9%) 0.005 ms/op
Iteration   2: 2.916 ±(99.9%) 0.003 ms/op
Iteration   3: 2.916 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.916, 2.921, 2.932), stdev = 0.010
  CI (99.9%): [2.747, 3.096] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.002 ms/op
Iteration   1: 3.041 ±(99.9%) 0.003 ms/op
Iteration   2: 3.073 ±(99.9%) 0.003 ms/op
Iteration   3: 3.038 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.051 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (3.038, 3.051, 3.073), stdev = 0.019
  CI (99.9%): [2.696, 3.405] (assumes normal distribution)


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
# Warmup Iteration   1: 5.053 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.015 ms/op
Iteration   1: 3.884 ±(99.9%) 0.024 ms/op
Iteration   2: 3.857 ±(99.9%) 0.039 ms/op
Iteration   3: 3.921 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.888 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.857, 3.888, 3.921), stdev = 0.032
  CI (99.9%): [3.305, 4.470] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.009 ms/op
Iteration   1: 3.008 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  11.006 ms/op
                 createUser·p0.9999: 15.647 ms/op
                 createUser·p1.00:   15.679 ms/op

Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.498 ms/op
                 createUser·p0.99:   4.166 ms/op
                 createUser·p0.999:  7.685 ms/op
                 createUser·p0.9999: 17.709 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  9.481 ms/op
                 createUser·p0.9999: 24.510 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317718
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22728 
    [ 2.500,  5.000) = 293334 
    [ 5.000,  7.500) = 1165 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.606 ms/op
     p(99.9900) =     23.968 ms/op
     p(99.9990) =     25.056 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 3.299 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.944 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.005 ms/op
Iteration   1: 2.894 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.627 ms/op
                 existUser·p0.9999: 15.660 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  6.557 ms/op
                 existUser·p0.9999: 14.932 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.343 ms/op
                 existUser·p0.9999: 14.770 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328038
  mean =      2.928 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2133 
    [ 1.250,  2.500) = 38949 
    [ 2.500,  3.750) = 274067 
    [ 3.750,  5.000) = 11679 
    [ 5.000,  6.250) = 820 
    [ 6.250,  7.500) = 154 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      6.635 ms/op
     p(99.9900) =     15.145 ms/op
     p(99.9990) =     16.726 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.066 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.709 ms/op
                 getUser·p0.9999: 13.283 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 13.402 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.531 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.489 ms/op
                 getUser·p0.9999: 16.573 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315002
  mean =      3.046 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 957 
    [ 1.250,  2.500) = 22497 
    [ 2.500,  3.750) = 272996 
    [ 3.750,  5.000) = 17308 
    [ 5.000,  6.250) = 667 
    [ 6.250,  7.500) = 268 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     16.015 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 5.188 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.011 ms/op
Iteration   1: 3.913 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.374 ms/op
                 listUser·p0.9999: 17.448 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   2: 3.900 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 16.830 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.857 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.700 ms/op
                 listUser·p0.9999: 23.335 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246663
  mean =      3.890 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4582 
    [ 2.500,  5.000) = 221939 
    [ 5.000,  7.500) = 18826 
    [ 7.500, 10.000) = 875 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.942 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     23.776 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.520 ± 1.387  ops/ms
ClientGrpc.existUser                       thrpt       3  11.132 ± 3.441  ops/ms
ClientGrpc.getUser                         thrpt       3  10.586 ± 0.347  ops/ms
ClientGrpc.listUser                        thrpt       3   8.142 ± 0.462  ops/ms
ClientGrpc.createUser                       avgt       3   3.014 ± 0.427   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.174   ms/op
ClientGrpc.getUser                          avgt       3   3.051 ± 0.354   ms/op
ClientGrpc.listUser                         avgt       3   3.888 ± 0.582   ms/op
ClientGrpc.createUser                     sample  317718   3.020 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.528           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.606           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.968           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  328038   2.928 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.542           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.635           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.145           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.843           ms/op
ClientGrpc.getUser                        sample  315002   3.046 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.531           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.438           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.015           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.186           ms/op
ClientGrpc.listUser                       sample  246663   3.890 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.809           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.942           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.828           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.610           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.921           ms/op
