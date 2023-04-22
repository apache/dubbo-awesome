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
# Warmup Iteration   1: 3.572 ops/ms
# Warmup Iteration   2: 8.213 ops/ms
# Warmup Iteration   3: 9.696 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.358 ops/ms
Iteration   3: 10.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.301 ±(99.9%) 1.762 ops/ms [Average]
  (min, avg, max) = (10.190, 10.301, 10.358), stdev = 0.097
  CI (99.9%): [8.540, 12.063] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.990 ops/ms
# Warmup Iteration   2: 10.388 ops/ms
# Warmup Iteration   3: 11.098 ops/ms
Iteration   1: 11.088 ops/ms
Iteration   2: 11.039 ops/ms
Iteration   3: 10.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.031 ±(99.9%) 1.128 ops/ms [Average]
  (min, avg, max) = (10.965, 11.031, 11.088), stdev = 0.062
  CI (99.9%): [9.903, 12.158] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.530 ops/ms
# Warmup Iteration   2: 10.001 ops/ms
# Warmup Iteration   3: 10.467 ops/ms
Iteration   1: 10.238 ops/ms
Iteration   2: 10.675 ops/ms
Iteration   3: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.446 ±(99.9%) 3.994 ops/ms [Average]
  (min, avg, max) = (10.238, 10.446, 10.675), stdev = 0.219
  CI (99.9%): [6.453, 14.440] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.691 ops/ms
# Warmup Iteration   2: 7.332 ops/ms
# Warmup Iteration   3: 7.940 ops/ms
Iteration   1: 7.965 ops/ms
Iteration   2: 7.915 ops/ms
Iteration   3: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.930 ±(99.9%) 0.552 ops/ms [Average]
  (min, avg, max) = (7.910, 7.930, 7.965), stdev = 0.030
  CI (99.9%): [7.378, 8.482] (assumes normal distribution)


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.005 ms/op
Iteration   1: 3.114 ±(99.9%) 0.003 ms/op
Iteration   2: 3.062 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.064 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (3.016, 3.064, 3.114), stdev = 0.049
  CI (99.9%): [2.169, 3.959] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.002 ms/op
Iteration   1: 2.964 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 2.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.962, 2.972, 2.989), stdev = 0.015
  CI (99.9%): [2.700, 3.243] (assumes normal distribution)


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.004 ms/op
Iteration   1: 3.083 ±(99.9%) 0.001 ms/op
Iteration   2: 3.067 ±(99.9%) 0.004 ms/op
Iteration   3: 3.057 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (3.057, 3.069, 3.083), stdev = 0.013
  CI (99.9%): [2.831, 3.307] (assumes normal distribution)


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
# Warmup Iteration   1: 5.619 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.013 ms/op
Iteration   1: 3.982 ±(99.9%) 0.007 ms/op
Iteration   2: 3.971 ±(99.9%) 0.019 ms/op
Iteration   3: 3.986 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.980 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (3.971, 3.980, 3.986), stdev = 0.008
  CI (99.9%): [3.833, 4.126] (assumes normal distribution)


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
# Warmup Iteration   1: 4.991 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  7.463 ms/op
                 createUser·p0.9999: 14.969 ms/op
                 createUser·p1.00:   15.221 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.478 ms/op
                 createUser·p0.9999: 15.790 ms/op
                 createUser·p1.00:   16.073 ms/op

Iteration   3: 3.146 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  8.865 ms/op
                 createUser·p0.9999: 33.116 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308249
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18984 
    [ 2.500,  5.000) = 287261 
    [ 5.000,  7.500) = 1639 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      7.965 ms/op
     p(99.9900) =     31.955 ms/op
     p(99.9990) =     33.746 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.298 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.005 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.338 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.035 ms/op
                 existUser·p0.999:  5.863 ms/op
                 existUser·p0.9999: 14.731 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   2: 2.886 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   3: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.498 ms/op
                 existUser·p0.9999: 18.416 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330218
  mean =      2.906 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37126 
    [ 2.500,  5.000) = 291965 
    [ 5.000,  7.500) = 833 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.338 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      7.314 ms/op
     p(99.9900) =     19.481 ms/op
     p(99.9990) =     25.123 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.279 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
Iteration   1: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.434 ms/op
                 getUser·p0.9999: 14.909 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.581 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.733 ms/op
                 getUser·p0.9999: 15.009 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.176 ms/op
                 getUser·p0.9999: 19.855 ms/op
                 getUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311738
  mean =      3.079 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15763 
    [ 2.500,  5.000) = 294429 
    [ 5.000,  7.500) = 1207 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     18.994 ms/op
     p(99.9990) =     20.407 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 4.959 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.012 ms/op
Iteration   1: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.286 ms/op
                 listUser·p0.9999: 21.548 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 4.086 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  16.980 ms/op
                 listUser·p0.9999: 30.933 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   3: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   7.050 ms/op
                 listUser·p0.999:  17.103 ms/op
                 listUser·p0.9999: 26.388 ms/op
                 listUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235336
  mean =      4.080 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2351 
    [ 2.500,  5.000) = 206485 
    [ 5.000,  7.500) = 24681 
    [ 7.500, 10.000) = 1318 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.247 ms/op
     p(99.9000) =     15.707 ms/op
     p(99.9900) =     29.356 ms/op
     p(99.9990) =     31.051 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.301 ± 1.762  ops/ms
ClientGrpc.existUser                       thrpt       3  11.031 ± 1.128  ops/ms
ClientGrpc.getUser                         thrpt       3  10.446 ± 3.994  ops/ms
ClientGrpc.listUser                        thrpt       3   7.930 ± 0.552  ops/ms
ClientGrpc.createUser                       avgt       3   3.064 ± 0.895   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 0.272   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.238   ms/op
ClientGrpc.listUser                         avgt       3   3.980 ± 0.146   ms/op
ClientGrpc.createUser                     sample  308249   3.115 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.965           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.955           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.817           ms/op
ClientGrpc.existUser                      sample  330218   2.906 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.338           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.314           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.481           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.199           ms/op
ClientGrpc.getUser                        sample  311738   3.079 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.581           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.668           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.994           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.906           ms/op
ClientGrpc.listUser                       sample  235336   4.080 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.015           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.247           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.707           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.356           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.687           ms/op
