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
# Warmup Iteration   1: 3.946 ops/ms
# Warmup Iteration   2: 9.239 ops/ms
# Warmup Iteration   3: 10.116 ops/ms
Iteration   1: 10.696 ops/ms
Iteration   2: 10.467 ops/ms
Iteration   3: 10.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.570 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (10.467, 10.570, 10.696), stdev = 0.117
  CI (99.9%): [8.442, 12.697] (assumes normal distribution)


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
# Warmup Iteration   1: 7.633 ops/ms
# Warmup Iteration   2: 10.792 ops/ms
# Warmup Iteration   3: 11.285 ops/ms
Iteration   1: 11.170 ops/ms
Iteration   2: 11.391 ops/ms
Iteration   3: 11.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.381 ±(99.9%) 3.756 ops/ms [Average]
  (min, avg, max) = (11.170, 11.381, 11.581), stdev = 0.206
  CI (99.9%): [7.625, 15.137] (assumes normal distribution)


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
# Warmup Iteration   1: 7.912 ops/ms
# Warmup Iteration   2: 10.217 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.619 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.726 ±(99.9%) 1.704 ops/ms [Average]
  (min, avg, max) = (10.619, 10.726, 10.791), stdev = 0.093
  CI (99.9%): [9.021, 12.430] (assumes normal distribution)


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
# Warmup Iteration   1: 5.813 ops/ms
# Warmup Iteration   2: 7.814 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.116 ops/ms
Iteration   2: 8.068 ops/ms
Iteration   3: 8.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.083 ±(99.9%) 0.515 ops/ms [Average]
  (min, avg, max) = (8.066, 8.083, 8.116), stdev = 0.028
  CI (99.9%): [7.569, 8.598] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.173 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.002 ms/op
Iteration   1: 3.014 ±(99.9%) 0.003 ms/op
Iteration   2: 2.967 ±(99.9%) 0.003 ms/op
Iteration   3: 2.970 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.984 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (2.967, 2.984, 3.014), stdev = 0.027
  CI (99.9%): [2.499, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.003 ms/op
Iteration   1: 2.851 ±(99.9%) 0.003 ms/op
Iteration   2: 2.923 ±(99.9%) 0.001 ms/op
Iteration   3: 2.822 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.866 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (2.822, 2.866, 2.923), stdev = 0.052
  CI (99.9%): [1.920, 3.812] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.003 ms/op
Iteration   1: 2.960 ±(99.9%) 0.002 ms/op
Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
Iteration   3: 2.997 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (2.960, 2.991, 3.016), stdev = 0.028
  CI (99.9%): [2.471, 3.510] (assumes normal distribution)


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
# Warmup Iteration   1: 5.706 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.007 ms/op
Iteration   1: 4.005 ±(99.9%) 0.021 ms/op
Iteration   2: 3.962 ±(99.9%) 0.022 ms/op
Iteration   3: 3.930 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.966 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.930, 3.966, 4.005), stdev = 0.038
  CI (99.9%): [3.281, 4.651] (assumes normal distribution)


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.408 ms/op
                 createUser·p0.9999: 20.021 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.621 ms/op
                 createUser·p0.9999: 21.720 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  9.469 ms/op
                 createUser·p0.9999: 23.144 ms/op
                 createUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318308
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30947 
    [ 2.500,  5.000) = 285804 
    [ 5.000,  7.500) = 1110 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      9.072 ms/op
     p(99.9900) =     22.850 ms/op
     p(99.9990) =     23.515 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.005 ms/op
Iteration   1: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.930 ms/op
                 existUser·p0.9999: 21.913 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.917 ms/op
                 existUser·p0.9999: 13.709 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   3: 2.890 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  8.350 ms/op
                 existUser·p0.9999: 18.020 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333300
  mean =      2.878 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50306 
    [ 2.500,  5.000) = 281716 
    [ 5.000,  7.500) = 948 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.447 ms/op
     p(99.9900) =     19.748 ms/op
     p(99.9990) =     23.877 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.619 ms/op
                 getUser·p0.9999: 16.129 ms/op
                 getUser·p1.00:   16.433 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.713 ms/op
                 getUser·p0.9999: 18.743 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  6.910 ms/op
                 getUser·p0.9999: 28.282 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315385
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23093 
    [ 2.500,  5.000) = 290668 
    [ 5.000,  7.500) = 1315 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.463 ms/op
     p(99.9900) =     27.737 ms/op
     p(99.9990) =     30.169 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 4.971 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.011 ms/op
Iteration   1: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 18.247 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 3.966 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  16.984 ms/op
                 listUser·p0.9999: 21.625 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   3: 4.010 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.410 ms/op
                 listUser·p0.9999: 16.945 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241731
  mean =      3.970 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2717 
    [ 2.500,  5.000) = 216944 
    [ 5.000,  7.500) = 20735 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     26.471 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.570 ± 2.128  ops/ms
ClientGrpc.existUser                       thrpt       3  11.381 ± 3.756  ops/ms
ClientGrpc.getUser                         thrpt       3  10.726 ± 1.704  ops/ms
ClientGrpc.listUser                        thrpt       3   8.083 ± 0.515  ops/ms
ClientGrpc.createUser                       avgt       3   2.984 ± 0.484   ms/op
ClientGrpc.existUser                        avgt       3   2.866 ± 0.946   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.520   ms/op
ClientGrpc.listUser                         avgt       3   3.966 ± 0.685   ms/op
ClientGrpc.createUser                     sample  318308   3.017 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.602           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.072           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.850           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.658           ms/op
ClientGrpc.existUser                      sample  333300   2.878 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.656           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.447           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.748           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.019           ms/op
ClientGrpc.getUser                        sample  315385   3.043 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.463           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.737           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.310           ms/op
ClientGrpc.listUser                       sample  241731   3.970 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.953           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.385           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.939           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.640           ms/op
