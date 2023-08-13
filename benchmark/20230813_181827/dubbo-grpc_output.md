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
# Warmup Iteration   1: 4.481 ops/ms
# Warmup Iteration   2: 9.176 ops/ms
# Warmup Iteration   3: 10.056 ops/ms
Iteration   1: 10.573 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.709 ±(99.9%) 2.156 ops/ms [Average]
  (min, avg, max) = (10.573, 10.709, 10.789), stdev = 0.118
  CI (99.9%): [8.553, 12.865] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.200 ops/ms
# Warmup Iteration   2: 10.824 ops/ms
# Warmup Iteration   3: 11.059 ops/ms
Iteration   1: 11.344 ops/ms
Iteration   2: 11.220 ops/ms
Iteration   3: 11.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.282 ±(99.9%) 1.128 ops/ms [Average]
  (min, avg, max) = (11.220, 11.282, 11.344), stdev = 0.062
  CI (99.9%): [10.154, 12.411] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.681 ops/ms
# Warmup Iteration   2: 10.334 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.679 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.691 ±(99.9%) 0.378 ops/ms [Average]
  (min, avg, max) = (10.679, 10.691, 10.715), stdev = 0.021
  CI (99.9%): [10.313, 11.070] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.879 ops/ms
# Warmup Iteration   2: 7.680 ops/ms
# Warmup Iteration   3: 7.926 ops/ms
Iteration   1: 8.127 ops/ms
Iteration   2: 8.089 ops/ms
Iteration   3: 8.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.155 ±(99.9%) 1.516 ops/ms [Average]
  (min, avg, max) = (8.089, 8.155, 8.248), stdev = 0.083
  CI (99.9%): [6.639, 9.670] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.015 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.019 ±(99.9%) 0.002 ms/op
Iteration   3: 3.003 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (3.003, 3.013, 3.019), stdev = 0.009
  CI (99.9%): [2.855, 3.172] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.815 ±(99.9%) 0.003 ms/op
Iteration   1: 2.877 ±(99.9%) 0.003 ms/op
Iteration   2: 2.864 ±(99.9%) 0.002 ms/op
Iteration   3: 2.865 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.869 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (2.864, 2.869, 2.877), stdev = 0.007
  CI (99.9%): [2.735, 3.002] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 3.021 ±(99.9%) 0.002 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.005 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.996, 3.005, 3.021), stdev = 0.014
  CI (99.9%): [2.752, 3.257] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.141 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.047 ms/op
Iteration   1: 3.878 ±(99.9%) 0.021 ms/op
Iteration   2: 3.972 ±(99.9%) 0.013 ms/op
Iteration   3: 3.904 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.918 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (3.878, 3.918, 3.972), stdev = 0.048
  CI (99.9%): [3.041, 4.796] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.140 ms/op
                 createUser·p0.9999: 11.693 ms/op
                 createUser·p1.00:   11.944 ms/op

Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.271 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  9.228 ms/op
                 createUser·p0.9999: 16.083 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.677 ms/op
                 createUser·p0.9999: 22.165 ms/op
                 createUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319001
  mean =      3.009 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21894 
    [ 2.500,  5.000) = 295527 
    [ 5.000,  7.500) = 1116 
    [ 7.500, 10.000) = 232 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.271 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     21.470 ms/op
     p(99.9990) =     22.368 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.876 ±(99.9%) 0.006 ms/op
Iteration   1: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.758 ms/op
                 existUser·p0.9999: 13.765 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.390 ms/op
                 existUser·p0.999:  7.093 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 2.895 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.676 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.858 ms/op
                 existUser·p0.9999: 26.444 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329816
  mean =      2.908 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40850 
    [ 2.500,  5.000) = 286784 
    [ 5.000,  7.500) = 1761 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.989 ms/op
     p(99.9900) =     16.959 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
Iteration   1: 2.993 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  8.048 ms/op
                 getUser·p0.9999: 24.935 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   2: 2.976 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.481 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.586 ms/op
                 getUser·p0.9999: 21.970 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.062 ms/op
                 getUser·p0.9999: 22.905 ms/op
                 getUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320922
  mean =      2.991 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29593 
    [ 2.500,  5.000) = 289278 
    [ 5.000,  7.500) = 1706 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     23.283 ms/op
     p(99.9990) =     25.342 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 5.309 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.010 ms/op
Iteration   1: 3.937 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  12.955 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 3.914 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.783 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 3.927 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.294 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.014 ms/op
                 listUser·p0.999:  14.343 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244558
  mean =      3.926 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4019 
    [ 2.500,  5.000) = 218999 
    [ 5.000,  7.500) = 20202 
    [ 7.500, 10.000) = 806 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.844 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     19.416 ms/op
     p(99.9990) =     21.925 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.709 ± 2.156  ops/ms
ClientGrpc.existUser                       thrpt       3  11.282 ± 1.128  ops/ms
ClientGrpc.getUser                         thrpt       3  10.691 ± 0.378  ops/ms
ClientGrpc.listUser                        thrpt       3   8.155 ± 1.516  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.158   ms/op
ClientGrpc.existUser                        avgt       3   2.869 ± 0.133   ms/op
ClientGrpc.getUser                          avgt       3   3.005 ± 0.252   ms/op
ClientGrpc.listUser                         avgt       3   3.918 ± 0.878   ms/op
ClientGrpc.createUser                     sample  319001   3.009 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.271           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.618           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.470           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.117           ms/op
ClientGrpc.existUser                      sample  329816   2.908 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.670           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.989           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.959           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.001           ms/op
ClientGrpc.getUser                        sample  320922   2.991 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.481           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.283           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  244558   3.926 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.294           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.844           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.369           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.416           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.839           ms/op
