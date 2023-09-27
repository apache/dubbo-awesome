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
# Warmup Iteration   1: 4.838 ops/ms
# Warmup Iteration   2: 8.973 ops/ms
# Warmup Iteration   3: 9.889 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 10.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.192 ±(99.9%) 2.561 ops/ms [Average]
  (min, avg, max) = (10.090, 10.192, 10.352), stdev = 0.140
  CI (99.9%): [7.630, 12.753] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.453 ops/ms
# Warmup Iteration   2: 10.263 ops/ms
# Warmup Iteration   3: 10.875 ops/ms
Iteration   1: 10.727 ops/ms
Iteration   2: 10.695 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.722 ±(99.9%) 0.465 ops/ms [Average]
  (min, avg, max) = (10.695, 10.722, 10.745), stdev = 0.025
  CI (99.9%): [10.257, 11.187] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.509 ops/ms
# Warmup Iteration   2: 9.778 ops/ms
# Warmup Iteration   3: 10.183 ops/ms
Iteration   1: 10.370 ops/ms
Iteration   2: 10.335 ops/ms
Iteration   3: 10.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.340 ±(99.9%) 0.516 ops/ms [Average]
  (min, avg, max) = (10.314, 10.340, 10.370), stdev = 0.028
  CI (99.9%): [9.824, 10.856] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.943 ops/ms
# Warmup Iteration   2: 8.032 ops/ms
# Warmup Iteration   3: 8.065 ops/ms
Iteration   1: 8.108 ops/ms
Iteration   2: 8.160 ops/ms
Iteration   3: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.144 ±(99.9%) 0.565 ops/ms [Average]
  (min, avg, max) = (8.108, 8.144, 8.164), stdev = 0.031
  CI (99.9%): [7.579, 8.709] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.004 ms/op
Iteration   1: 3.131 ±(99.9%) 0.003 ms/op
Iteration   2: 3.167 ±(99.9%) 0.002 ms/op
Iteration   3: 3.067 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.121 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (3.067, 3.121, 3.167), stdev = 0.050
  CI (99.9%): [2.204, 4.039] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.362 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.002 ms/op
Iteration   1: 3.015 ±(99.9%) 0.003 ms/op
Iteration   2: 2.925 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.973 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (2.925, 2.973, 3.015), stdev = 0.046
  CI (99.9%): [2.138, 3.808] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.002 ms/op
Iteration   1: 3.110 ±(99.9%) 0.002 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.118 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.114 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (3.110, 3.114, 3.118), stdev = 0.004
  CI (99.9%): [3.036, 3.192] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.027 ms/op
Iteration   1: 3.939 ±(99.9%) 0.036 ms/op
Iteration   2: 3.852 ±(99.9%) 0.029 ms/op
Iteration   3: 3.873 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.888 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (3.852, 3.888, 3.939), stdev = 0.046
  CI (99.9%): [3.055, 4.720] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.005 ms/op
Iteration   1: 3.108 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.666 ms/op
                 createUser·p0.9999: 11.393 ms/op
                 createUser·p1.00:   11.518 ms/op

Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.221 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  9.912 ms/op
                 createUser·p0.9999: 12.908 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  11.013 ms/op
                 createUser·p0.9999: 17.489 ms/op
                 createUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308915
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 795 
    [ 1.250,  2.500) = 12939 
    [ 2.500,  3.750) = 270330 
    [ 3.750,  5.000) = 22936 
    [ 5.000,  6.250) = 893 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 207 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.221 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.897 ms/op
     p(99.9900) =     15.223 ms/op
     p(99.9990) =     17.787 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
Iteration   1: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.463 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.995 ms/op
                 existUser·p0.9999: 11.570 ms/op
                 existUser·p1.00:   11.944 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  11.472 ms/op
                 existUser·p0.9999: 13.262 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 15.077 ms/op
                 existUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324361
  mean =      2.958 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1800 
    [ 1.250,  2.500) = 19614 
    [ 2.500,  3.750) = 290971 
    [ 3.750,  5.000) = 10427 
    [ 5.000,  6.250) = 831 
    [ 6.250,  7.500) = 291 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      9.366 ms/op
     p(99.9900) =     14.722 ms/op
     p(99.9990) =     15.254 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.005 ms/op
Iteration   1: 3.169 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.978 ms/op
                 getUser·p0.9999: 13.185 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.461 ms/op
                 getUser·p0.999:  7.725 ms/op
                 getUser·p0.9999: 12.683 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   3: 3.163 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  8.264 ms/op
                 getUser·p0.9999: 16.155 ms/op
                 getUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305367
  mean =      3.145 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 383 
    [ 1.250,  2.500) = 6253 
    [ 2.500,  3.750) = 275812 
    [ 3.750,  5.000) = 20891 
    [ 5.000,  6.250) = 1025 
    [ 6.250,  7.500) = 522 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 126 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     15.909 ms/op
     p(99.9990) =     16.299 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 4.997 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.010 ms/op
Iteration   1: 3.805 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  14.630 ms/op
                 listUser·p0.9999: 17.321 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 3.897 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.466 ms/op
                 listUser·p0.9999: 14.876 ms/op
                 listUser·p1.00:   15.254 ms/op

Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.732 ms/op
                 listUser·p0.999:  12.789 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247600
  mean =      3.877 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2961 
    [ 2.500,  5.000) = 231286 
    [ 5.000,  7.500) = 12469 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     17.932 ms/op
     p(99.9990) =     19.943 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.192 ± 2.561  ops/ms
ClientGrpc.existUser                       thrpt       3  10.722 ± 0.465  ops/ms
ClientGrpc.getUser                         thrpt       3  10.340 ± 0.516  ops/ms
ClientGrpc.listUser                        thrpt       3   8.144 ± 0.565  ops/ms
ClientGrpc.createUser                       avgt       3   3.121 ± 0.917   ms/op
ClientGrpc.existUser                        avgt       3   2.973 ± 0.835   ms/op
ClientGrpc.getUser                          avgt       3   3.114 ± 0.078   ms/op
ClientGrpc.listUser                         avgt       3   3.888 ± 0.832   ms/op
ClientGrpc.createUser                     sample  308915   3.111 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.221           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.897           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.223           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.891           ms/op
ClientGrpc.existUser                      sample  324361   2.958 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.463           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.366           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.722           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.385           ms/op
ClientGrpc.getUser                        sample  305367   3.145 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.803           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.831           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.909           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.400           ms/op
ClientGrpc.listUser                       sample  247600   3.877 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.051           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.350           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.124           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.932           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.054           ms/op
