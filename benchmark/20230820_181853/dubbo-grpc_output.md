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
# Warmup Iteration   1: 4.300 ops/ms
# Warmup Iteration   2: 9.010 ops/ms
# Warmup Iteration   3: 9.970 ops/ms
Iteration   1: 10.313 ops/ms
Iteration   2: 10.253 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.332 ±(99.9%) 1.638 ops/ms [Average]
  (min, avg, max) = (10.253, 10.332, 10.430), stdev = 0.090
  CI (99.9%): [8.694, 11.969] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.874 ops/ms
# Warmup Iteration   2: 10.601 ops/ms
# Warmup Iteration   3: 10.789 ops/ms
Iteration   1: 10.901 ops/ms
Iteration   2: 11.021 ops/ms
Iteration   3: 11.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.087 ±(99.9%) 4.126 ops/ms [Average]
  (min, avg, max) = (10.901, 11.087, 11.338), stdev = 0.226
  CI (99.9%): [6.961, 15.213] (assumes normal distribution)


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
# Warmup Iteration   1: 6.920 ops/ms
# Warmup Iteration   2: 10.055 ops/ms
# Warmup Iteration   3: 10.224 ops/ms
Iteration   1: 10.363 ops/ms
Iteration   2: 10.257 ops/ms
Iteration   3: 10.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.353 ±(99.9%) 1.670 ops/ms [Average]
  (min, avg, max) = (10.257, 10.353, 10.440), stdev = 0.092
  CI (99.9%): [8.683, 12.024] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.893 ops/ms
# Warmup Iteration   2: 7.735 ops/ms
# Warmup Iteration   3: 7.772 ops/ms
Iteration   1: 7.976 ops/ms
Iteration   2: 8.027 ops/ms
Iteration   3: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.961 ±(99.9%) 1.374 ops/ms [Average]
  (min, avg, max) = (7.879, 7.961, 8.027), stdev = 0.075
  CI (99.9%): [6.587, 9.335] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.417 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.002 ms/op
Iteration   1: 3.155 ±(99.9%) 0.019 ms/op
Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
Iteration   3: 3.048 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.103 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.048, 3.103, 3.155), stdev = 0.053
  CI (99.9%): [2.131, 4.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.923 ±(99.9%) 0.003 ms/op
Iteration   3: 2.959 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.942 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (2.923, 2.942, 2.959), stdev = 0.018
  CI (99.9%): [2.617, 3.266] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.002 ms/op
Iteration   2: 3.100 ±(99.9%) 0.003 ms/op
Iteration   3: 3.132 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.118 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.100, 3.118, 3.132), stdev = 0.016
  CI (99.9%): [2.817, 3.418] (assumes normal distribution)


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
# Warmup Iteration   1: 5.494 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.016 ms/op
Iteration   1: 4.041 ±(99.9%) 0.029 ms/op
Iteration   2: 4.025 ±(99.9%) 0.032 ms/op
Iteration   3: 3.985 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.017 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (3.985, 4.017, 4.041), stdev = 0.029
  CI (99.9%): [3.490, 4.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.506 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.770 ms/op
                 createUser·p0.999:  9.341 ms/op
                 createUser·p0.9999: 18.434 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.925 ms/op
                 createUser·p0.999:  9.727 ms/op
                 createUser·p0.9999: 21.247 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.429 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.836 ms/op
                 createUser·p0.999:  9.510 ms/op
                 createUser·p0.9999: 26.903 ms/op
                 createUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313807
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20942 
    [ 2.500,  5.000) = 290161 
    [ 5.000,  7.500) = 2148 
    [ 7.500, 10.000) = 312 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     26.964 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  7.199 ms/op
                 existUser·p0.9999: 17.760 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.288 ms/op
                 existUser·p0.9999: 13.423 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  10.679 ms/op
                 existUser·p0.9999: 16.290 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322790
  mean =      2.974 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 640 
    [ 1.250,  2.500) = 23135 
    [ 2.500,  3.750) = 290791 
    [ 3.750,  5.000) = 6641 
    [ 5.000,  6.250) = 691 
    [ 6.250,  7.500) = 440 
    [ 7.500,  8.750) = 145 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.474 ms/op
     p(99.9900) =     17.194 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.006 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.503 ms/op
                 getUser·p0.9999: 15.079 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 3.134 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.036 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309097
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 567 
    [ 1.250,  2.500) = 17044 
    [ 2.500,  3.750) = 269874 
    [ 3.750,  5.000) = 18971 
    [ 5.000,  6.250) = 1659 
    [ 6.250,  7.500) = 484 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     19.032 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 5.529 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
Iteration   1: 3.955 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 16.489 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   2: 4.005 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.683 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.285 ms/op
                 listUser·p0.999:  17.827 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   3: 4.024 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  20.891 ms/op
                 listUser·p0.9999: 26.284 ms/op
                 listUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240429
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3372 
    [ 2.500,  5.000) = 208650 
    [ 5.000,  7.500) = 26603 
    [ 7.500, 10.000) = 1288 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     16.250 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     26.699 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.332 ± 1.638  ops/ms
ClientGrpc.existUser                       thrpt       3  11.087 ± 4.126  ops/ms
ClientGrpc.getUser                         thrpt       3  10.353 ± 1.670  ops/ms
ClientGrpc.listUser                        thrpt       3   7.961 ± 1.374  ops/ms
ClientGrpc.createUser                       avgt       3   3.103 ± 0.971   ms/op
ClientGrpc.existUser                        avgt       3   2.942 ± 0.325   ms/op
ClientGrpc.getUser                          avgt       3   3.118 ± 0.301   ms/op
ClientGrpc.listUser                         avgt       3   4.017 ± 0.527   ms/op
ClientGrpc.createUser                     sample  313807   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.429           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.535           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.362           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.066           ms/op
ClientGrpc.existUser                      sample  322790   2.974 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.474           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.194           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.121           ms/op
ClientGrpc.getUser                        sample  309097   3.104 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.650           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.503           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.810           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.169           ms/op
ClientGrpc.listUser                       sample  240429   3.995 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.683           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.250           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.642           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.837           ms/op
