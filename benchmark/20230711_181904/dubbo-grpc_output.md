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
# Warmup Iteration   1: 2.358 ops/ms
# Warmup Iteration   2: 5.106 ops/ms
# Warmup Iteration   3: 6.784 ops/ms
Iteration   1: 7.235 ops/ms
Iteration   2: 7.072 ops/ms
Iteration   3: 7.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.118 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (7.047, 7.118, 7.235), stdev = 0.102
  CI (99.9%): [5.257, 8.979] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.392 ops/ms
# Warmup Iteration   2: 6.934 ops/ms
# Warmup Iteration   3: 7.441 ops/ms
Iteration   1: 8.058 ops/ms
Iteration   2: 7.530 ops/ms
Iteration   3: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.857 ±(99.9%) 5.211 ops/ms [Average]
  (min, avg, max) = (7.530, 7.857, 8.058), stdev = 0.286
  CI (99.9%): [2.646, 13.068] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.408 ops/ms
# Warmup Iteration   2: 6.998 ops/ms
# Warmup Iteration   3: 7.505 ops/ms
Iteration   1: 7.599 ops/ms
Iteration   2: 7.428 ops/ms
Iteration   3: 7.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.485 ±(99.9%) 1.805 ops/ms [Average]
  (min, avg, max) = (7.427, 7.485, 7.599), stdev = 0.099
  CI (99.9%): [5.680, 9.289] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.742 ops/ms
# Warmup Iteration   2: 5.303 ops/ms
# Warmup Iteration   3: 5.784 ops/ms
Iteration   1: 5.961 ops/ms
Iteration   2: 5.944 ops/ms
Iteration   3: 5.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.897 ±(99.9%) 1.782 ops/ms [Average]
  (min, avg, max) = (5.784, 5.897, 5.961), stdev = 0.098
  CI (99.9%): [4.115, 7.678] (assumes normal distribution)


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
# Warmup Iteration   1: 6.467 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.269 ±(99.9%) 0.011 ms/op
Iteration   1: 4.149 ±(99.9%) 0.003 ms/op
Iteration   2: 4.153 ±(99.9%) 0.003 ms/op
Iteration   3: 4.199 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.167 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (4.149, 4.167, 4.199), stdev = 0.028
  CI (99.9%): [3.665, 4.669] (assumes normal distribution)


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
# Warmup Iteration   1: 5.622 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.004 ms/op
Iteration   1: 3.849 ±(99.9%) 0.003 ms/op
Iteration   2: 3.946 ±(99.9%) 0.005 ms/op
Iteration   3: 3.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.911 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (3.849, 3.911, 3.946), stdev = 0.054
  CI (99.9%): [2.934, 4.887] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.115 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.004 ms/op
Iteration   1: 4.079 ±(99.9%) 0.005 ms/op
Iteration   2: 4.045 ±(99.9%) 0.003 ms/op
Iteration   3: 4.070 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.065 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (4.045, 4.065, 4.079), stdev = 0.018
  CI (99.9%): [3.745, 4.384] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.130 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.578 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.698 ±(99.9%) 0.013 ms/op
Iteration   1: 5.442 ±(99.9%) 0.026 ms/op
Iteration   2: 5.398 ±(99.9%) 0.012 ms/op
Iteration   3: 5.348 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.396 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (5.348, 5.396, 5.442), stdev = 0.047
  CI (99.9%): [4.534, 6.258] (assumes normal distribution)


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
# Warmup Iteration   1: 6.728 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.470 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.427 ±(99.9%) 0.016 ms/op
Iteration   1: 3.793 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   7.255 ms/op
                 createUser·p0.999:  12.853 ms/op
                 createUser·p0.9999: 15.394 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   2: 3.834 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.223 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  15.368 ms/op
                 createUser·p0.9999: 20.032 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 3.847 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  13.546 ms/op
                 createUser·p0.9999: 17.155 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251111
  mean =      3.824 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7917 
    [ 2.500,  5.000) = 225398 
    [ 5.000,  7.500) = 15693 
    [ 7.500, 10.000) = 1397 
    [10.000, 12.500) = 375 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     19.031 ms/op
     p(99.9990) =     20.823 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.987 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.011 ms/op
Iteration   1: 3.650 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.624 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 22.192 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.547 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  9.689 ms/op
                 existUser·p0.9999: 18.643 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 3.606 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  8.327 ms/op
                 existUser·p0.9999: 18.514 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266558
  mean =      3.601 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14514 
    [ 2.500,  5.000) = 238869 
    [ 5.000,  7.500) = 12058 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     21.518 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 6.240 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.283 ±(99.9%) 0.014 ms/op
Iteration   1: 4.291 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   4.157 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  13.000 ms/op
                 getUser·p0.9999: 26.006 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   2: 4.266 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  10.781 ms/op
                 getUser·p0.9999: 28.590 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   3: 4.125 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  11.681 ms/op
                 getUser·p0.9999: 33.948 ms/op
                 getUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227114
  mean =      4.226 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7071 
    [ 2.500,  5.000) = 185223 
    [ 5.000,  7.500) = 32264 
    [ 7.500, 10.000) = 2081 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 47 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     33.419 ms/op
     p(99.9990) =     34.126 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 8.073 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.999 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.420 ±(99.9%) 0.019 ms/op
Iteration   1: 5.384 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   8.004 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  16.339 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 5.435 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.776 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  19.033 ms/op
                 listUser·p0.9999: 21.762 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 5.461 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  23.214 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176795
  mean =      5.426 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 76862 
    [ 5.000,  7.500) = 86293 
    [ 7.500, 10.000) = 11133 
    [10.000, 12.500) = 1641 
    [12.500, 15.000) = 372 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.102 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     18.134 ms/op
     p(99.9900) =     26.913 ms/op
     p(99.9990) =     28.975 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.118 ± 1.861  ops/ms
ClientGrpc.existUser                       thrpt       3   7.857 ± 5.211  ops/ms
ClientGrpc.getUser                         thrpt       3   7.485 ± 1.805  ops/ms
ClientGrpc.listUser                        thrpt       3   5.897 ± 1.782  ops/ms
ClientGrpc.createUser                       avgt       3   4.167 ± 0.502   ms/op
ClientGrpc.existUser                        avgt       3   3.911 ± 0.977   ms/op
ClientGrpc.getUser                          avgt       3   4.065 ± 0.320   ms/op
ClientGrpc.listUser                         avgt       3   5.396 ± 0.862   ms/op
ClientGrpc.createUser                     sample  251111   3.824 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.854           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.243           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.168           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.795           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.031           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.004           ms/op
ClientGrpc.existUser                      sample  266558   3.601 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.807           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.406           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.880           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.518           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.741           ms/op
ClientGrpc.getUser                        sample  227114   4.226 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.772           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.108           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.759           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.668           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.813           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.419           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.275           ms/op
ClientGrpc.listUser                       sample  176795   5.426 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.307           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.102           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.502           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.134           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.913           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.000           ms/op
