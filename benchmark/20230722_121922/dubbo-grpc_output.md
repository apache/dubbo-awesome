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
# Warmup Iteration   1: 3.558 ops/ms
# Warmup Iteration   2: 8.309 ops/ms
# Warmup Iteration   3: 9.868 ops/ms
Iteration   1: 10.212 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.283 ±(99.9%) 1.183 ops/ms [Average]
  (min, avg, max) = (10.212, 10.283, 10.339), stdev = 0.065
  CI (99.9%): [9.101, 11.466] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.327 ops/ms
# Warmup Iteration   2: 9.788 ops/ms
# Warmup Iteration   3: 10.605 ops/ms
Iteration   1: 10.963 ops/ms
Iteration   2: 10.830 ops/ms
Iteration   3: 10.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.879 ±(99.9%) 1.337 ops/ms [Average]
  (min, avg, max) = (10.830, 10.879, 10.963), stdev = 0.073
  CI (99.9%): [9.542, 12.215] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.477 ops/ms
# Warmup Iteration   2: 9.953 ops/ms
# Warmup Iteration   3: 10.303 ops/ms
Iteration   1: 10.364 ops/ms
Iteration   2: 10.446 ops/ms
Iteration   3: 10.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.400 ±(99.9%) 0.770 ops/ms [Average]
  (min, avg, max) = (10.364, 10.400, 10.446), stdev = 0.042
  CI (99.9%): [9.630, 11.169] (assumes normal distribution)


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
# Warmup Iteration   1: 5.975 ops/ms
# Warmup Iteration   2: 7.524 ops/ms
# Warmup Iteration   3: 7.816 ops/ms
Iteration   1: 7.952 ops/ms
Iteration   2: 8.247 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.114 ±(99.9%) 2.730 ops/ms [Average]
  (min, avg, max) = (7.952, 8.114, 8.247), stdev = 0.150
  CI (99.9%): [5.384, 10.844] (assumes normal distribution)


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.005 ms/op
Iteration   1: 3.133 ±(99.9%) 0.001 ms/op
Iteration   2: 3.106 ±(99.9%) 0.002 ms/op
Iteration   3: 3.118 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.119 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (3.106, 3.119, 3.133), stdev = 0.013
  CI (99.9%): [2.877, 3.361] (assumes normal distribution)


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.002 ms/op
Iteration   1: 2.946 ±(99.9%) 0.002 ms/op
Iteration   2: 2.910 ±(99.9%) 0.003 ms/op
Iteration   3: 2.952 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (2.910, 2.936, 2.952), stdev = 0.023
  CI (99.9%): [2.518, 3.354] (assumes normal distribution)


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.003 ms/op
Iteration   1: 3.103 ±(99.9%) 0.004 ms/op
Iteration   2: 3.195 ±(99.9%) 0.002 ms/op
Iteration   3: 3.087 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.128 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (3.087, 3.128, 3.195), stdev = 0.058
  CI (99.9%): [2.067, 4.190] (assumes normal distribution)


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
# Warmup Iteration   1: 5.877 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
Iteration   1: 4.032 ±(99.9%) 0.014 ms/op
Iteration   2: 3.892 ±(99.9%) 0.008 ms/op
Iteration   3: 3.991 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.972 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (3.892, 3.972, 4.032), stdev = 0.072
  CI (99.9%): [2.662, 5.281] (assumes normal distribution)


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.735 ms/op
                 createUser·p0.9999: 12.698 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.544 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.514 ms/op
                 createUser·p0.9999: 20.544 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  15.237 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312618
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13946 
    [ 2.500,  5.000) = 296848 
    [ 5.000,  7.500) = 1343 
    [ 7.500, 10.000) = 169 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =     10.000 ms/op
     p(99.9900) =     18.636 ms/op
     p(99.9990) =     20.771 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 4.382 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.408 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.606 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.521 ms/op
                 existUser·p0.9999: 21.660 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  7.368 ms/op
                 existUser·p0.9999: 18.759 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   3: 3.000 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.467 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322668
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25906 
    [ 2.500,  5.000) = 295706 
    [ 5.000,  7.500) = 821 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.808 ms/op
     p(99.9900) =     19.685 ms/op
     p(99.9990) =     21.849 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.726 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  9.593 ms/op
                 getUser·p0.9999: 12.644 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  6.432 ms/op
                 getUser·p0.9999: 15.054 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   3: 3.169 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.370 ms/op
                 getUser·p0.999:  8.943 ms/op
                 getUser·p0.9999: 17.103 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307402
  mean =      3.124 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 447 
    [ 1.250,  2.500) = 14456 
    [ 2.500,  3.750) = 268682 
    [ 3.750,  5.000) = 21900 
    [ 5.000,  6.250) = 1248 
    [ 6.250,  7.500) = 288 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      8.448 ms/op
     p(99.9900) =     15.848 ms/op
     p(99.9990) =     18.499 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 6.168 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
Iteration   1: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.914 ms/op
                 listUser·p0.9999: 15.647 ms/op
                 listUser·p1.00:   15.958 ms/op

Iteration   2: 4.082 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  14.445 ms/op
                 listUser·p0.9999: 18.361 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.871 ms/op
                 listUser·p0.999:  14.596 ms/op
                 listUser·p0.9999: 26.083 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238327
  mean =      4.028 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2081 
    [ 2.500,  5.000) = 211232 
    [ 5.000,  7.500) = 23452 
    [ 7.500, 10.000) = 1132 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     25.313 ms/op
     p(99.9990) =     26.595 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.283 ± 1.183  ops/ms
ClientGrpc.existUser                       thrpt       3  10.879 ± 1.337  ops/ms
ClientGrpc.getUser                         thrpt       3  10.400 ± 0.770  ops/ms
ClientGrpc.listUser                        thrpt       3   8.114 ± 2.730  ops/ms
ClientGrpc.createUser                       avgt       3   3.119 ± 0.242   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.418   ms/op
ClientGrpc.getUser                          avgt       3   3.128 ± 1.062   ms/op
ClientGrpc.listUser                         avgt       3   3.972 ± 1.309   ms/op
ClientGrpc.createUser                     sample  312618   3.069 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.544           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.000           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.636           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.873           ms/op
ClientGrpc.existUser                      sample  322668   2.973 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.408           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.808           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.685           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  307402   3.124 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.670           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.448           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.848           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.514           ms/op
ClientGrpc.listUser                       sample  238327   4.028 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.997           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.313           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.706           ms/op
