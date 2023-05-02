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
# Warmup Iteration   1: 4.122 ops/ms
# Warmup Iteration   2: 9.124 ops/ms
# Warmup Iteration   3: 10.466 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.633 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (10.576, 10.633, 10.735), stdev = 0.088
  CI (99.9%): [9.020, 12.246] (assumes normal distribution)


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
# Warmup Iteration   1: 7.292 ops/ms
# Warmup Iteration   2: 10.863 ops/ms
# Warmup Iteration   3: 11.042 ops/ms
Iteration   1: 11.188 ops/ms
Iteration   2: 11.231 ops/ms
Iteration   3: 11.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.330 ±(99.9%) 3.830 ops/ms [Average]
  (min, avg, max) = (11.188, 11.330, 11.571), stdev = 0.210
  CI (99.9%): [7.500, 15.160] (assumes normal distribution)


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
# Warmup Iteration   1: 7.359 ops/ms
# Warmup Iteration   2: 10.332 ops/ms
# Warmup Iteration   3: 10.581 ops/ms
Iteration   1: 10.692 ops/ms
Iteration   2: 10.738 ops/ms
Iteration   3: 10.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.732 ±(99.9%) 0.673 ops/ms [Average]
  (min, avg, max) = (10.692, 10.732, 10.765), stdev = 0.037
  CI (99.9%): [10.059, 11.405] (assumes normal distribution)


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
# Warmup Iteration   1: 6.379 ops/ms
# Warmup Iteration   2: 7.747 ops/ms
# Warmup Iteration   3: 8.059 ops/ms
Iteration   1: 8.063 ops/ms
Iteration   2: 8.118 ops/ms
Iteration   3: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.064 ±(99.9%) 0.969 ops/ms [Average]
  (min, avg, max) = (8.012, 8.064, 8.118), stdev = 0.053
  CI (99.9%): [7.096, 9.033] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.003 ms/op
Iteration   1: 2.993 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.985 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.962, 2.985, 3.001), stdev = 0.020
  CI (99.9%): [2.614, 3.357] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.914 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.004 ms/op
Iteration   1: 2.897 ±(99.9%) 0.003 ms/op
Iteration   2: 2.938 ±(99.9%) 0.003 ms/op
Iteration   3: 2.935 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.923 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (2.897, 2.923, 2.938), stdev = 0.023
  CI (99.9%): [2.507, 3.339] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 2.959 ±(99.9%) 0.002 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.000 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (2.959, 3.000, 3.036), stdev = 0.039
  CI (99.9%): [2.295, 3.704] (assumes normal distribution)


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
# Warmup Iteration   1: 5.135 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.023 ms/op
Iteration   1: 3.932 ±(99.9%) 0.049 ms/op
Iteration   2: 3.896 ±(99.9%) 0.009 ms/op
Iteration   3: 3.986 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.896, 3.938, 3.986), stdev = 0.045
  CI (99.9%): [3.110, 4.766] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.594 ms/op
                 createUser·p0.999:  9.248 ms/op
                 createUser·p0.9999: 13.572 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.027 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  9.122 ms/op
                 createUser·p0.9999: 35.258 ms/op
                 createUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319195
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27907 
    [ 2.500,  5.000) = 289535 
    [ 5.000,  7.500) = 1273 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     34.608 ms/op
     p(99.9990) =     35.508 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  8.186 ms/op
                 existUser·p0.9999: 11.977 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 2.952 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.095 ms/op
                 existUser·p0.9999: 13.539 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 2.844 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.166 ms/op
                 existUser·p0.9999: 15.217 ms/op
                 existUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330527
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2348 
    [ 1.250,  2.500) = 38024 
    [ 2.500,  3.750) = 278085 
    [ 3.750,  5.000) = 11076 
    [ 5.000,  6.250) = 603 
    [ 6.250,  7.500) = 138 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.598 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     15.484 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.298 ms/op
                 getUser·p0.9999: 17.933 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  6.943 ms/op
                 getUser·p0.9999: 15.917 ms/op
                 getUser·p1.00:   16.466 ms/op

Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.450 ms/op
                 getUser·p0.999:  7.111 ms/op
                 getUser·p0.9999: 15.542 ms/op
                 getUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314521
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2062 
    [ 1.250,  2.500) = 20320 
    [ 2.500,  3.750) = 268602 
    [ 3.750,  5.000) = 22061 
    [ 5.000,  6.250) = 907 
    [ 6.250,  7.500) = 253 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.520 ms/op
     p(99.9900) =     17.319 ms/op
     p(99.9990) =     18.116 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 5.935 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.010 ms/op
Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  11.959 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   2: 3.925 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.379 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.328 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   3: 3.912 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  16.925 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244365
  mean =      3.929 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3006 
    [ 2.500,  5.000) = 220868 
    [ 5.000,  7.500) = 19432 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.613 ms/op
     p(99.9900) =     22.123 ms/op
     p(99.9990) =     23.171 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.633 ± 1.613  ops/ms
ClientGrpc.existUser                       thrpt       3  11.330 ± 3.830  ops/ms
ClientGrpc.getUser                         thrpt       3  10.732 ± 0.673  ops/ms
ClientGrpc.listUser                        thrpt       3   8.064 ± 0.969  ops/ms
ClientGrpc.createUser                       avgt       3   2.985 ± 0.372   ms/op
ClientGrpc.existUser                        avgt       3   2.923 ± 0.416   ms/op
ClientGrpc.getUser                          avgt       3   3.000 ± 0.704   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 0.828   ms/op
ClientGrpc.createUser                     sample  319195   3.009 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.658           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.929           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.608           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.586           ms/op
ClientGrpc.existUser                      sample  330527   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.598           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.566           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.811           ms/op
ClientGrpc.getUser                        sample  314521   3.055 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.609           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.520           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.319           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.252           ms/op
ClientGrpc.listUser                       sample  244365   3.929 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.959           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.613           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.123           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.298           ms/op
