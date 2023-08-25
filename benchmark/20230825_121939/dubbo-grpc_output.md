# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 6.044 ops/ms
# Warmup Iteration   3: 7.817 ops/ms
Iteration   1: 8.094 ops/ms
Iteration   2: 8.432 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.222 ±(99.9%) 3.354 ops/ms [Average]
  (min, avg, max) = (8.094, 8.222, 8.432), stdev = 0.184
  CI (99.9%): [4.868, 11.576] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.772 ops/ms
# Warmup Iteration   2: 8.469 ops/ms
# Warmup Iteration   3: 9.145 ops/ms
Iteration   1: 9.336 ops/ms
Iteration   2: 9.122 ops/ms
Iteration   3: 9.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.254 ±(99.9%) 2.108 ops/ms [Average]
  (min, avg, max) = (9.122, 9.254, 9.336), stdev = 0.116
  CI (99.9%): [7.146, 11.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.356 ops/ms
# Warmup Iteration   2: 8.292 ops/ms
# Warmup Iteration   3: 8.711 ops/ms
Iteration   1: 8.756 ops/ms
Iteration   2: 8.806 ops/ms
Iteration   3: 8.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.701 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (8.541, 8.701, 8.806), stdev = 0.141
  CI (99.9%): [6.131, 11.271] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.144 ops/ms
# Warmup Iteration   2: 5.908 ops/ms
# Warmup Iteration   3: 6.505 ops/ms
Iteration   1: 6.510 ops/ms
Iteration   2: 6.635 ops/ms
Iteration   3: 6.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.526 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (6.432, 6.526, 6.635), stdev = 0.102
  CI (99.9%): [4.661, 8.391] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.061 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.012 ms/op
Iteration   1: 3.885 ±(99.9%) 0.004 ms/op
Iteration   2: 3.807 ±(99.9%) 0.004 ms/op
Iteration   3: 3.715 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.802 ±(99.9%) 1.557 ms/op [Average]
  (min, avg, max) = (3.715, 3.802, 3.885), stdev = 0.085
  CI (99.9%): [2.245, 5.360] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.160 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.010 ms/op
Iteration   1: 3.362 ±(99.9%) 0.004 ms/op
Iteration   2: 3.312 ±(99.9%) 0.004 ms/op
Iteration   3: 3.418 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.364 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.312, 3.364, 3.418), stdev = 0.053
  CI (99.9%): [2.392, 4.336] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.002 ms/op
Iteration   1: 3.674 ±(99.9%) 0.003 ms/op
Iteration   2: 3.752 ±(99.9%) 0.004 ms/op
Iteration   3: 3.803 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.743 ±(99.9%) 1.179 ms/op [Average]
  (min, avg, max) = (3.674, 3.743, 3.803), stdev = 0.065
  CI (99.9%): [2.564, 4.922] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.170 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.763 ±(99.9%) 0.011 ms/op
Iteration   1: 4.873 ±(99.9%) 0.012 ms/op
Iteration   2: 4.785 ±(99.9%) 0.015 ms/op
Iteration   3: 4.675 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.778 ±(99.9%) 1.817 ms/op [Average]
  (min, avg, max) = (4.675, 4.778, 4.873), stdev = 0.100
  CI (99.9%): [2.961, 6.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.466 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.009 ms/op
Iteration   1: 3.755 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  10.203 ms/op
                 createUser·p0.9999: 24.248 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.619 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  9.379 ms/op
                 createUser·p0.9999: 26.023 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.695 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  24.347 ms/op
                 createUser·p0.9999: 30.774 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260357
  mean =      3.689 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6046 
    [ 2.500,  5.000) = 247483 
    [ 5.000,  7.500) = 6016 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     11.069 ms/op
     p(99.9900) =     29.359 ms/op
     p(99.9990) =     31.470 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.073 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.008 ms/op
Iteration   1: 3.553 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  9.684 ms/op
                 existUser·p0.9999: 17.990 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   2: 3.442 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 14.631 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   3: 3.629 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  11.125 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271087
  mean =      3.540 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13320 
    [ 2.500,  5.000) = 252561 
    [ 5.000,  7.500) = 4419 
    [ 7.500, 10.000) = 491 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     10.502 ms/op
     p(99.9900) =     17.986 ms/op
     p(99.9990) =     20.570 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.885 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.010 ms/op
Iteration   1: 3.785 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  8.167 ms/op
                 getUser·p0.9999: 23.859 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   2: 3.814 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  10.111 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   3: 3.866 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  13.112 ms/op
                 getUser·p0.9999: 27.141 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251083
  mean =      3.821 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6089 
    [ 2.500,  5.000) = 234486 
    [ 5.000,  7.500) = 9406 
    [ 7.500, 10.000) = 751 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     10.812 ms/op
     p(99.9900) =     24.638 ms/op
     p(99.9990) =     27.836 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.151 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.432 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.681 ±(99.9%) 0.014 ms/op
Iteration   1: 4.657 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 16.856 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 4.829 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.119 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 29.045 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   3: 4.856 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  21.597 ms/op
                 listUser·p0.9999: 32.002 ms/op
                 listUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200823
  mean =      4.779 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 279 
    [ 2.500,  5.000) = 151533 
    [ 5.000,  7.500) = 43503 
    [ 7.500, 10.000) = 4646 
    [10.000, 12.500) = 453 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     15.994 ms/op
     p(99.9900) =     31.523 ms/op
     p(99.9990) =     33.024 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.222 ± 3.354  ops/ms
ClientGrpc.existUser                       thrpt       3   9.254 ± 2.108  ops/ms
ClientGrpc.getUser                         thrpt       3   8.701 ± 2.570  ops/ms
ClientGrpc.listUser                        thrpt       3   6.526 ± 1.865  ops/ms
ClientGrpc.createUser                       avgt       3   3.802 ± 1.557   ms/op
ClientGrpc.existUser                        avgt       3   3.364 ± 0.972   ms/op
ClientGrpc.getUser                          avgt       3   3.743 ± 1.179   ms/op
ClientGrpc.listUser                         avgt       3   4.778 ± 1.817   ms/op
ClientGrpc.createUser                     sample  260357   3.689 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.776           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.677           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.069           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.359           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.523           ms/op
ClientGrpc.existUser                      sample  271087   3.540 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.631           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.513           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.502           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.986           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.775           ms/op
ClientGrpc.getUser                        sample  251083   3.821 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.910           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.160           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.812           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.638           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.886           ms/op
ClientGrpc.listUser                       sample  200823   4.779 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.925           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.994           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.523           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.800           ms/op
