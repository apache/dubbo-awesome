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
# Warmup Iteration   1: 4.063 ops/ms
# Warmup Iteration   2: 8.821 ops/ms
# Warmup Iteration   3: 10.127 ops/ms
Iteration   1: 10.476 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.613 ±(99.9%) 2.873 ops/ms [Average]
  (min, avg, max) = (10.476, 10.613, 10.785), stdev = 0.157
  CI (99.9%): [7.740, 13.486] (assumes normal distribution)


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
# Warmup Iteration   1: 7.652 ops/ms
# Warmup Iteration   2: 10.774 ops/ms
# Warmup Iteration   3: 11.182 ops/ms
Iteration   1: 11.061 ops/ms
Iteration   2: 11.031 ops/ms
Iteration   3: 11.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.079 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (11.031, 11.079, 11.145), stdev = 0.059
  CI (99.9%): [9.997, 12.161] (assumes normal distribution)


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
# Warmup Iteration   1: 7.191 ops/ms
# Warmup Iteration   2: 10.004 ops/ms
# Warmup Iteration   3: 10.506 ops/ms
Iteration   1: 10.636 ops/ms
Iteration   2: 10.505 ops/ms
Iteration   3: 10.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.561 ±(99.9%) 1.238 ops/ms [Average]
  (min, avg, max) = (10.505, 10.561, 10.636), stdev = 0.068
  CI (99.9%): [9.322, 11.799] (assumes normal distribution)


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
# Warmup Iteration   1: 5.450 ops/ms
# Warmup Iteration   2: 7.864 ops/ms
# Warmup Iteration   3: 8.006 ops/ms
Iteration   1: 8.238 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.169 ±(99.9%) 1.090 ops/ms [Average]
  (min, avg, max) = (8.131, 8.169, 8.238), stdev = 0.060
  CI (99.9%): [7.080, 9.259] (assumes normal distribution)


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.003 ms/op
Iteration   1: 3.009 ±(99.9%) 0.004 ms/op
Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
Iteration   3: 3.075 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.047 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.009, 3.047, 3.075), stdev = 0.034
  CI (99.9%): [2.432, 3.662] (assumes normal distribution)


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.002 ms/op
Iteration   1: 2.921 ±(99.9%) 0.003 ms/op
Iteration   2: 2.883 ±(99.9%) 0.002 ms/op
Iteration   3: 2.917 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.883, 2.907, 2.921), stdev = 0.021
  CI (99.9%): [2.524, 3.290] (assumes normal distribution)


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.042 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (3.032, 3.042, 3.047), stdev = 0.009
  CI (99.9%): [2.887, 3.197] (assumes normal distribution)


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
# Warmup Iteration   1: 5.529 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.028 ms/op
Iteration   1: 3.876 ±(99.9%) 0.021 ms/op
Iteration   2: 3.925 ±(99.9%) 0.027 ms/op
Iteration   3: 3.990 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.876, 3.930, 3.990), stdev = 0.058
  CI (99.9%): [2.879, 4.982] (assumes normal distribution)


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  9.560 ms/op
                 createUser·p0.9999: 21.678 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.224 ms/op
                 createUser·p0.9999: 21.469 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   3: 3.022 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.516 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316513
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21382 
    [ 2.500,  5.000) = 293742 
    [ 5.000,  7.500) = 1021 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.724 ms/op
     p(99.9900) =     27.712 ms/op
     p(99.9990) =     29.644 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  8.074 ms/op
                 existUser·p0.9999: 13.454 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  5.921 ms/op
                 existUser·p0.9999: 17.435 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   3: 2.920 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.427 ms/op
                 existUser·p0.9999: 17.695 ms/op
                 existUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327021
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 558 
    [ 1.250,  2.500) = 32327 
    [ 2.500,  3.750) = 286197 
    [ 3.750,  5.000) = 6789 
    [ 5.000,  6.250) = 752 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      6.488 ms/op
     p(99.9900) =     17.377 ms/op
     p(99.9990) =     18.014 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.115 ms/op
                 getUser·p0.9999: 13.409 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 15.143 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  11.029 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315756
  mean =      3.040 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20771 
    [ 2.500,  5.000) = 293392 
    [ 5.000,  7.500) = 1284 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.473 ms/op
     p(99.9900) =     21.575 ms/op
     p(99.9990) =     24.135 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 5.624 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.011 ms/op
Iteration   1: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.248 ms/op
                 listUser·p0.9999: 15.098 ms/op
                 listUser·p1.00:   16.630 ms/op

Iteration   2: 3.880 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.124 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.992 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 24.935 ms/op
                 listUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244264
  mean =      3.929 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2433 
    [ 2.500,  5.000) = 220088 
    [ 5.000,  7.500) = 20587 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     23.270 ms/op
     p(99.9990) =     25.468 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.613 ± 2.873  ops/ms
ClientGrpc.existUser                       thrpt       3  11.079 ± 1.082  ops/ms
ClientGrpc.getUser                         thrpt       3  10.561 ± 1.238  ops/ms
ClientGrpc.listUser                        thrpt       3   8.169 ± 1.090  ops/ms
ClientGrpc.createUser                       avgt       3   3.047 ± 0.615   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.383   ms/op
ClientGrpc.getUser                          avgt       3   3.042 ± 0.155   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 1.051   ms/op
ClientGrpc.createUser                     sample  316513   3.034 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.597           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.724           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.712           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.753           ms/op
ClientGrpc.existUser                      sample  327021   2.934 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.770           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.488           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.377           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.153           ms/op
ClientGrpc.getUser                        sample  315756   3.040 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.735           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.473           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.575           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.183           ms/op
ClientGrpc.listUser                       sample  244264   3.929 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.951           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.713           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.270           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.559           ms/op
