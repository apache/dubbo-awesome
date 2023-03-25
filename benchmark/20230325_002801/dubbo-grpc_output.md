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
# Warmup Iteration   1: 4.057 ops/ms
# Warmup Iteration   2: 8.951 ops/ms
# Warmup Iteration   3: 10.155 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.370 ops/ms
Iteration   3: 10.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.545 ±(99.9%) 2.803 ops/ms [Average]
  (min, avg, max) = (10.370, 10.545, 10.658), stdev = 0.154
  CI (99.9%): [7.742, 13.348] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.335 ops/ms
# Warmup Iteration   2: 10.465 ops/ms
# Warmup Iteration   3: 10.744 ops/ms
Iteration   1: 11.029 ops/ms
Iteration   2: 11.085 ops/ms
Iteration   3: 11.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.063 ±(99.9%) 0.544 ops/ms [Average]
  (min, avg, max) = (11.029, 11.063, 11.085), stdev = 0.030
  CI (99.9%): [10.519, 11.607] (assumes normal distribution)


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
# Warmup Iteration   1: 7.006 ops/ms
# Warmup Iteration   2: 9.531 ops/ms
# Warmup Iteration   3: 10.152 ops/ms
Iteration   1: 10.372 ops/ms
Iteration   2: 10.240 ops/ms
Iteration   3: 10.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.282 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (10.235, 10.282, 10.372), stdev = 0.078
  CI (99.9%): [8.864, 11.701] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 5.731 ops/ms
# Warmup Iteration   2: 7.297 ops/ms
# Warmup Iteration   3: 7.696 ops/ms
Iteration   1: 7.830 ops/ms
Iteration   2: 7.872 ops/ms
Iteration   3: 7.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.847 ±(99.9%) 0.407 ops/ms [Average]
  (min, avg, max) = (7.830, 7.847, 7.872), stdev = 0.022
  CI (99.9%): [7.440, 8.254] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 4.314 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.003 ms/op
Iteration   2: 3.104 ±(99.9%) 0.002 ms/op
Iteration   3: 3.064 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.080 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (3.064, 3.080, 3.104), stdev = 0.022
  CI (99.9%): [2.683, 3.476] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.930 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.002 ms/op
Iteration   1: 2.935 ±(99.9%) 0.002 ms/op
Iteration   2: 2.933 ±(99.9%) 0.002 ms/op
Iteration   3: 2.832 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 1.070 ms/op [Average]
  (min, avg, max) = (2.832, 2.900, 2.935), stdev = 0.059
  CI (99.9%): [1.830, 3.970] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.161 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.002 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 3.015 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.021 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.008, 3.021, 3.041), stdev = 0.018
  CI (99.9%): [2.699, 3.343] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.119 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.010 ms/op
Iteration   1: 4.180 ±(99.9%) 0.022 ms/op
Iteration   2: 4.041 ±(99.9%) 0.016 ms/op
Iteration   3: 3.953 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.058 ±(99.9%) 2.087 ms/op [Average]
  (min, avg, max) = (3.953, 4.058, 4.180), stdev = 0.114
  CI (99.9%): [1.970, 6.145] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.384 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.018 ms/op
Iteration   1: 3.089 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   7.494 ms/op
                 createUser·p0.999:  11.006 ms/op
                 createUser·p0.9999: 19.638 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.032 ms/op
                 createUser·p0.999:  10.569 ms/op
                 createUser·p0.9999: 18.339 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.787 ms/op
                 createUser·p0.9999: 22.263 ms/op
                 createUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312731
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25439 
    [ 2.500,  5.000) = 283544 
    [ 5.000,  7.500) = 2336 
    [ 7.500, 10.000) = 1126 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.322 ms/op
     p(99.9000) =      9.364 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     22.696 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.068 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.927 ±(99.9%) 0.007 ms/op
Iteration   1: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.251 ms/op
                 existUser·p0.9999: 15.205 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.525 ms/op
                 existUser·p0.9999: 15.010 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   3: 2.998 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  10.170 ms/op
                 existUser·p0.9999: 17.553 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325495
  mean =      2.949 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1826 
    [ 1.250,  2.500) = 41111 
    [ 2.500,  3.750) = 267643 
    [ 3.750,  5.000) = 10921 
    [ 5.000,  6.250) = 1387 
    [ 6.250,  7.500) = 1299 
    [ 7.500,  8.750) = 933 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.151 ms/op
     p(99.9900) =     16.256 ms/op
     p(99.9990) =     19.037 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.340 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  13.095 ms/op
                 getUser·p0.9999: 18.850 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  9.733 ms/op
                 getUser·p0.9999: 17.293 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  7.854 ms/op
                 getUser·p0.9999: 25.873 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310778
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16810 
    [ 2.500,  5.000) = 290241 
    [ 5.000,  7.500) = 2658 
    [ 7.500, 10.000) = 725 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     10.329 ms/op
     p(99.9900) =     25.420 ms/op
     p(99.9990) =     26.113 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 5.805 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.015 ms/op
Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  15.490 ms/op
                 listUser·p0.9999: 22.788 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 4.172 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.575 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.215 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  18.390 ms/op
                 listUser·p0.9999: 26.920 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   3: 3.956 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236345
  mean =      4.066 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1972 
    [ 2.500,  5.000) = 206012 
    [ 5.000,  7.500) = 25273 
    [ 7.500, 10.000) = 2031 
    [10.000, 12.500) = 498 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     25.342 ms/op
     p(99.9990) =     27.841 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.545 ± 2.803  ops/ms
ClientGrpc.existUser                       thrpt       3  11.063 ± 0.544  ops/ms
ClientGrpc.getUser                         thrpt       3  10.282 ± 1.418  ops/ms
ClientGrpc.listUser                        thrpt       3   7.847 ± 0.407  ops/ms
ClientGrpc.createUser                       avgt       3   3.080 ± 0.396   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 1.070   ms/op
ClientGrpc.getUser                          avgt       3   3.021 ± 0.322   ms/op
ClientGrpc.listUser                         avgt       3   4.058 ± 2.087   ms/op
ClientGrpc.createUser                     sample  312731   3.068 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.636           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.322           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.364           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.349           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.921           ms/op
ClientGrpc.existUser                      sample  325495   2.949 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.480           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.151           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.256           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  310778   3.090 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.743           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.329           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.420           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.182           ms/op
ClientGrpc.listUser                       sample  236345   4.066 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.575           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.954           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.629           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.342           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.853           ms/op
