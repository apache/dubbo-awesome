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
# Warmup Iteration   1: 4.523 ops/ms
# Warmup Iteration   2: 9.117 ops/ms
# Warmup Iteration   3: 10.219 ops/ms
Iteration   1: 10.265 ops/ms
Iteration   2: 10.614 ops/ms
Iteration   3: 10.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.473 ±(99.9%) 3.353 ops/ms [Average]
  (min, avg, max) = (10.265, 10.473, 10.614), stdev = 0.184
  CI (99.9%): [7.120, 13.826] (assumes normal distribution)


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
# Warmup Iteration   1: 7.590 ops/ms
# Warmup Iteration   2: 10.771 ops/ms
# Warmup Iteration   3: 11.019 ops/ms
Iteration   1: 10.933 ops/ms
Iteration   2: 10.864 ops/ms
Iteration   3: 10.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.887 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (10.863, 10.887, 10.933), stdev = 0.040
  CI (99.9%): [10.159, 11.615] (assumes normal distribution)


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
# Warmup Iteration   1: 7.497 ops/ms
# Warmup Iteration   2: 10.338 ops/ms
# Warmup Iteration   3: 10.582 ops/ms
Iteration   1: 10.650 ops/ms
Iteration   2: 10.481 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.548 ±(99.9%) 1.642 ops/ms [Average]
  (min, avg, max) = (10.481, 10.548, 10.650), stdev = 0.090
  CI (99.9%): [8.906, 12.190] (assumes normal distribution)


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
# Warmup Iteration   1: 7.067 ops/ms
# Warmup Iteration   2: 8.175 ops/ms
# Warmup Iteration   3: 8.110 ops/ms
Iteration   1: 8.360 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.239 ±(99.9%) 1.983 ops/ms [Average]
  (min, avg, max) = (8.149, 8.239, 8.360), stdev = 0.109
  CI (99.9%): [6.256, 10.223] (assumes normal distribution)


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
Iteration   1: 3.030 ±(99.9%) 0.002 ms/op
Iteration   2: 3.085 ±(99.9%) 0.002 ms/op
Iteration   3: 3.019 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.045 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (3.019, 3.045, 3.085), stdev = 0.036
  CI (99.9%): [2.394, 3.696] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.004 ms/op
Iteration   1: 2.933 ±(99.9%) 0.005 ms/op
Iteration   2: 2.886 ±(99.9%) 0.005 ms/op
Iteration   3: 2.892 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.904 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (2.886, 2.904, 2.933), stdev = 0.026
  CI (99.9%): [2.435, 3.373] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
Iteration   3: 2.985 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.530 ms/op [Average]
  (min, avg, max) = (2.966, 2.991, 3.023), stdev = 0.029
  CI (99.9%): [2.461, 3.521] (assumes normal distribution)


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.012 ms/op
Iteration   1: 3.852 ±(99.9%) 0.025 ms/op
Iteration   2: 3.886 ±(99.9%) 0.036 ms/op
Iteration   3: 3.871 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.870 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (3.852, 3.870, 3.886), stdev = 0.017
  CI (99.9%): [3.556, 4.183] (assumes normal distribution)


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.491 ms/op
                 createUser·p0.999:  6.390 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   2: 3.020 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  10.813 ms/op
                 createUser·p0.9999: 20.362 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 16.707 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316983
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22846 
    [ 2.500,  5.000) = 292466 
    [ 5.000,  7.500) = 1233 
    [ 7.500, 10.000) = 175 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     20.031 ms/op
     p(99.9990) =     20.573 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.958 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.912 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  6.230 ms/op
                 existUser·p0.9999: 19.858 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 2.869 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  6.301 ms/op
                 existUser·p0.9999: 18.345 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 2.942 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.194 ms/op
                 existUser·p0.9999: 14.436 ms/op
                 existUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330046
  mean =      2.907 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43626 
    [ 2.500,  5.000) = 285252 
    [ 5.000,  7.500) = 973 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      6.266 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  6.882 ms/op
                 getUser·p0.9999: 19.196 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   2: 3.069 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.614 ms/op
                 getUser·p0.9999: 13.905 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.350 ms/op
                 getUser·p0.9999: 18.297 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316465
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18267 
    [ 2.500,  5.000) = 297237 
    [ 5.000,  7.500) = 697 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.046 ms/op
     p(99.9900) =     18.526 ms/op
     p(99.9990) =     19.716 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 5.207 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.010 ms/op
Iteration   1: 3.909 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  12.337 ms/op
                 listUser·p0.9999: 14.300 ms/op
                 listUser·p1.00:   15.270 ms/op

Iteration   2: 3.922 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.207 ms/op
                 listUser·p0.9999: 18.858 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 3.903 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.500 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245508
  mean =      3.911 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7183 
    [ 2.500,  5.000) = 213785 
    [ 5.000,  7.500) = 23459 
    [ 7.500, 10.000) = 646 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.705 ms/op
     p(99.9900) =     21.558 ms/op
     p(99.9990) =     22.434 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.473 ± 3.353  ops/ms
ClientGrpc.existUser                       thrpt       3  10.887 ± 0.728  ops/ms
ClientGrpc.getUser                         thrpt       3  10.548 ± 1.642  ops/ms
ClientGrpc.listUser                        thrpt       3   8.239 ± 1.983  ops/ms
ClientGrpc.createUser                       avgt       3   3.045 ± 0.651   ms/op
ClientGrpc.existUser                        avgt       3   2.904 ± 0.469   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.530   ms/op
ClientGrpc.listUser                         avgt       3   3.870 ± 0.314   ms/op
ClientGrpc.createUser                     sample  316983   3.027 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.563           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.405           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.031           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.644           ms/op
ClientGrpc.existUser                      sample  330046   2.907 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.593           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.711           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.332           ms/op
ClientGrpc.getUser                        sample  316465   3.032 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.695           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.046           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.526           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.021           ms/op
ClientGrpc.listUser                       sample  245508   3.911 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.903           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.705           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.558           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.544           ms/op
