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
# Warmup Iteration   1: 4.833 ops/ms
# Warmup Iteration   2: 9.347 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 10.051 ops/ms
Iteration   2: 10.217 ops/ms
Iteration   3: 10.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.267 ±(99.9%) 4.465 ops/ms [Average]
  (min, avg, max) = (10.051, 10.267, 10.532), stdev = 0.245
  CI (99.9%): [5.801, 14.732] (assumes normal distribution)


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
# Warmup Iteration   1: 7.840 ops/ms
# Warmup Iteration   2: 10.899 ops/ms
# Warmup Iteration   3: 11.062 ops/ms
Iteration   1: 11.294 ops/ms
Iteration   2: 11.039 ops/ms
Iteration   3: 10.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.095 ±(99.9%) 3.234 ops/ms [Average]
  (min, avg, max) = (10.953, 11.095, 11.294), stdev = 0.177
  CI (99.9%): [7.861, 14.330] (assumes normal distribution)


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
# Warmup Iteration   1: 7.240 ops/ms
# Warmup Iteration   2: 10.165 ops/ms
# Warmup Iteration   3: 10.335 ops/ms
Iteration   1: 10.623 ops/ms
Iteration   2: 10.534 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.589 ±(99.9%) 0.870 ops/ms [Average]
  (min, avg, max) = (10.534, 10.589, 10.623), stdev = 0.048
  CI (99.9%): [9.719, 11.458] (assumes normal distribution)


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
# Warmup Iteration   1: 7.614 ops/ms
# Warmup Iteration   2: 7.610 ops/ms
# Warmup Iteration   3: 8.094 ops/ms
Iteration   1: 8.039 ops/ms
Iteration   2: 8.169 ops/ms
Iteration   3: 8.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.139 ±(99.9%) 1.617 ops/ms [Average]
  (min, avg, max) = (8.039, 8.139, 8.208), stdev = 0.089
  CI (99.9%): [6.522, 9.756] (assumes normal distribution)


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.003 ms/op
Iteration   1: 3.095 ±(99.9%) 0.004 ms/op
Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
Iteration   3: 3.009 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.038 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.009, 3.038, 3.095), stdev = 0.049
  CI (99.9%): [2.140, 3.935] (assumes normal distribution)


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.830 ±(99.9%) 0.003 ms/op
Iteration   1: 2.886 ±(99.9%) 0.004 ms/op
Iteration   2: 2.892 ±(99.9%) 0.003 ms/op
Iteration   3: 2.871 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.883 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.871, 2.883, 2.892), stdev = 0.010
  CI (99.9%): [2.693, 3.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.003 ms/op
Iteration   1: 3.061 ±(99.9%) 0.003 ms/op
Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
Iteration   3: 3.042 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.063 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.042, 3.063, 3.086), stdev = 0.022
  CI (99.9%): [2.654, 3.472] (assumes normal distribution)


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
# Warmup Iteration   1: 5.482 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.007 ms/op
Iteration   1: 4.093 ±(99.9%) 0.011 ms/op
Iteration   2: 3.896 ±(99.9%) 0.020 ms/op
Iteration   3: 3.902 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.964 ±(99.9%) 2.038 ms/op [Average]
  (min, avg, max) = (3.896, 3.964, 4.093), stdev = 0.112
  CI (99.9%): [1.925, 6.002] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.479 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  11.032 ms/op
                 createUser·p0.9999: 12.762 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  9.743 ms/op
                 createUser·p0.9999: 14.699 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   3: 2.942 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  8.844 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317772
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2178 
    [ 1.250,  2.500) = 30446 
    [ 2.500,  3.750) = 262388 
    [ 3.750,  5.000) = 19052 
    [ 5.000,  6.250) = 2045 
    [ 6.250,  7.500) = 804 
    [ 7.500,  8.750) = 356 
    [ 8.750, 10.000) = 157 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     18.332 ms/op
     p(99.9990) =     19.393 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 3.462 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.786 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  8.056 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.517 ms/op

Iteration   2: 2.935 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.808 ms/op
                 existUser·p0.9999: 15.943 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   3: 2.844 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.598 ms/op
                 existUser·p0.999:  7.590 ms/op
                 existUser·p0.9999: 16.548 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330754
  mean =      2.901 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3185 
    [ 1.250,  2.500) = 41319 
    [ 2.500,  3.750) = 272509 
    [ 3.750,  5.000) = 12075 
    [ 5.000,  6.250) = 997 
    [ 6.250,  7.500) = 342 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      7.481 ms/op
     p(99.9900) =     16.268 ms/op
     p(99.9990) =     16.845 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.008 ms/op
Iteration   1: 3.057 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.630 ms/op
                 getUser·p0.9999: 13.287 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  10.142 ms/op
                 getUser·p0.9999: 24.412 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  8.503 ms/op
                 getUser·p0.9999: 14.540 ms/op
                 getUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316509
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27613 
    [ 2.500,  5.000) = 286206 
    [ 5.000,  7.500) = 2176 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     23.096 ms/op
     p(99.9990) =     24.538 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 4.755 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.012 ms/op
Iteration   1: 3.922 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 18.172 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   2: 3.856 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.171 ms/op
                 listUser·p0.9999: 17.511 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 3.939 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  17.459 ms/op
                 listUser·p0.9999: 27.325 ms/op
                 listUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245815
  mean =      3.906 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3800 
    [ 2.500,  5.000) = 220622 
    [ 5.000,  7.500) = 19937 
    [ 7.500, 10.000) = 757 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.060 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     28.002 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.267 ± 4.465  ops/ms
ClientGrpc.existUser                       thrpt       3  11.095 ± 3.234  ops/ms
ClientGrpc.getUser                         thrpt       3  10.589 ± 0.870  ops/ms
ClientGrpc.listUser                        thrpt       3   8.139 ± 1.617  ops/ms
ClientGrpc.createUser                       avgt       3   3.038 ± 0.898   ms/op
ClientGrpc.existUser                        avgt       3   2.883 ± 0.191   ms/op
ClientGrpc.getUser                          avgt       3   3.063 ± 0.409   ms/op
ClientGrpc.listUser                         avgt       3   3.964 ± 2.038   ms/op
ClientGrpc.createUser                     sample  317772   3.021 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.479           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.177           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.551           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.332           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.595           ms/op
ClientGrpc.existUser                      sample  330754   2.901 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.552           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.481           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.268           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.433           ms/op
ClientGrpc.getUser                        sample  316509   3.031 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.670           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.765           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.096           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  245815   3.906 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.902           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.060           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.771           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.115           ms/op
