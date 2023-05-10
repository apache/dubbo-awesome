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
# Warmup Iteration   1: 4.128 ops/ms
# Warmup Iteration   2: 9.115 ops/ms
# Warmup Iteration   3: 10.039 ops/ms
Iteration   1: 10.325 ops/ms
Iteration   2: 10.347 ops/ms
Iteration   3: 10.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.348 ±(99.9%) 0.437 ops/ms [Average]
  (min, avg, max) = (10.325, 10.348, 10.373), stdev = 0.024
  CI (99.9%): [9.912, 10.785] (assumes normal distribution)


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
# Warmup Iteration   1: 7.772 ops/ms
# Warmup Iteration   2: 10.629 ops/ms
# Warmup Iteration   3: 10.973 ops/ms
Iteration   1: 10.905 ops/ms
Iteration   2: 11.161 ops/ms
Iteration   3: 11.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.061 ±(99.9%) 2.495 ops/ms [Average]
  (min, avg, max) = (10.905, 11.061, 11.161), stdev = 0.137
  CI (99.9%): [8.567, 13.556] (assumes normal distribution)


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
# Warmup Iteration   1: 6.983 ops/ms
# Warmup Iteration   2: 9.930 ops/ms
# Warmup Iteration   3: 10.452 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.502 ±(99.9%) 1.365 ops/ms [Average]
  (min, avg, max) = (10.434, 10.502, 10.582), stdev = 0.075
  CI (99.9%): [9.137, 11.867] (assumes normal distribution)


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
# Warmup Iteration   1: 5.115 ops/ms
# Warmup Iteration   2: 7.747 ops/ms
# Warmup Iteration   3: 8.018 ops/ms
Iteration   1: 8.011 ops/ms
Iteration   2: 8.141 ops/ms
Iteration   3: 8.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.157 ±(99.9%) 2.811 ops/ms [Average]
  (min, avg, max) = (8.011, 8.157, 8.318), stdev = 0.154
  CI (99.9%): [5.346, 10.967] (assumes normal distribution)


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.002 ms/op
Iteration   1: 3.073 ±(99.9%) 0.002 ms/op
Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (3.006, 3.042, 3.073), stdev = 0.034
  CI (99.9%): [2.424, 3.660] (assumes normal distribution)


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.002 ms/op
Iteration   1: 2.932 ±(99.9%) 0.003 ms/op
Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
Iteration   3: 2.951 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.932, 2.946, 2.954), stdev = 0.012
  CI (99.9%): [2.723, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.063 ±(99.9%) 0.004 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.105 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.073 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.051, 3.073, 3.105), stdev = 0.028
  CI (99.9%): [2.560, 3.586] (assumes normal distribution)


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
# Warmup Iteration   1: 5.410 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
Iteration   1: 3.946 ±(99.9%) 0.009 ms/op
Iteration   2: 3.998 ±(99.9%) 0.024 ms/op
Iteration   3: 3.912 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.952 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.912, 3.952, 3.998), stdev = 0.043
  CI (99.9%): [3.160, 4.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.006 ms/op
Iteration   1: 3.170 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  8.077 ms/op
                 createUser·p0.9999: 13.794 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.308 ms/op
                 createUser·p0.9999: 16.613 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  11.119 ms/op
                 createUser·p0.9999: 18.106 ms/op
                 createUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305910
  mean =      3.139 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 477 
    [ 1.250,  2.500) = 14455 
    [ 2.500,  3.750) = 264864 
    [ 3.750,  5.000) = 24488 
    [ 5.000,  6.250) = 977 
    [ 6.250,  7.500) = 267 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.636 ms/op
     p(99.9900) =     16.709 ms/op
     p(99.9990) =     18.283 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.007 ms/op
Iteration   1: 2.968 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  7.186 ms/op
                 existUser·p0.9999: 12.226 ms/op
                 existUser·p1.00:   12.550 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 17.906 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   3: 2.981 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  10.302 ms/op
                 existUser·p0.9999: 26.101 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321501
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19151 
    [ 2.500,  5.000) = 301045 
    [ 5.000,  7.500) = 889 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     23.880 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 4.412 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.848 ms/op
                 getUser·p0.9999: 13.124 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.418 ms/op
                 getUser·p0.999:  7.997 ms/op
                 getUser·p0.9999: 13.692 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.542 ms/op
                 getUser·p0.9999: 17.617 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311324
  mean =      3.081 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 599 
    [ 1.250,  2.500) = 17059 
    [ 2.500,  3.750) = 272175 
    [ 3.750,  5.000) = 20115 
    [ 5.000,  6.250) = 738 
    [ 6.250,  7.500) = 281 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.867 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     17.822 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.398 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.011 ms/op
Iteration   1: 3.908 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.354 ms/op
                 listUser·p0.9999: 21.085 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 3.973 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.770 ms/op
                 listUser·p0.9999: 16.547 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 3.882 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 29.067 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244685
  mean =      3.920 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1762 
    [ 2.500,  5.000) = 224949 
    [ 5.000,  7.500) = 16665 
    [ 7.500, 10.000) = 829 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     27.837 ms/op
     p(99.9990) =     29.724 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.348 ± 0.437  ops/ms
ClientGrpc.existUser                       thrpt       3  11.061 ± 2.495  ops/ms
ClientGrpc.getUser                         thrpt       3  10.502 ± 1.365  ops/ms
ClientGrpc.listUser                        thrpt       3   8.157 ± 2.811  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 0.618   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 0.222   ms/op
ClientGrpc.getUser                          avgt       3   3.073 ± 0.513   ms/op
ClientGrpc.listUser                         avgt       3   3.952 ± 0.793   ms/op
ClientGrpc.createUser                     sample  305910   3.139 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.736           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.636           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.709           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.285           ms/op
ClientGrpc.existUser                      sample  321501   2.985 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.794           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.028           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.880           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.378           ms/op
ClientGrpc.getUser                        sample  311324   3.081 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.762           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.867           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.072           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  244685   3.920 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.938           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.837           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.310           ms/op
