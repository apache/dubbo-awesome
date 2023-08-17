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
# Warmup Iteration   1: 1.635 ops/ms
# Warmup Iteration   2: 4.302 ops/ms
# Warmup Iteration   3: 6.082 ops/ms
Iteration   1: 6.248 ops/ms
Iteration   2: 6.377 ops/ms
Iteration   3: 6.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.330 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (6.248, 6.330, 6.377), stdev = 0.072
  CI (99.9%): [5.024, 7.637] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.791 ops/ms
# Warmup Iteration   2: 6.218 ops/ms
# Warmup Iteration   3: 6.728 ops/ms
Iteration   1: 6.705 ops/ms
Iteration   2: 6.887 ops/ms
Iteration   3: 7.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.900 ±(99.9%) 3.702 ops/ms [Average]
  (min, avg, max) = (6.705, 6.900, 7.110), stdev = 0.203
  CI (99.9%): [3.199, 10.602] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.554 ops/ms
# Warmup Iteration   2: 5.824 ops/ms
# Warmup Iteration   3: 6.126 ops/ms
Iteration   1: 6.336 ops/ms
Iteration   2: 6.288 ops/ms
Iteration   3: 6.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.329 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (6.288, 6.329, 6.364), stdev = 0.039
  CI (99.9%): [5.623, 7.035] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.104 ops/ms
# Warmup Iteration   2: 4.522 ops/ms
# Warmup Iteration   3: 4.863 ops/ms
Iteration   1: 4.878 ops/ms
Iteration   2: 4.967 ops/ms
Iteration   3: 4.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.934 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (4.878, 4.934, 4.967), stdev = 0.048
  CI (99.9%): [4.051, 5.817] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.410 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.611 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.304 ±(99.9%) 0.025 ms/op
Iteration   1: 5.096 ±(99.9%) 0.003 ms/op
Iteration   2: 5.151 ±(99.9%) 0.010 ms/op
Iteration   3: 5.038 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.095 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (5.038, 5.095, 5.151), stdev = 0.056
  CI (99.9%): [4.064, 6.126] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.634 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.105 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.827 ±(99.9%) 0.004 ms/op
Iteration   1: 4.841 ±(99.9%) 0.005 ms/op
Iteration   2: 4.752 ±(99.9%) 0.005 ms/op
Iteration   3: 4.625 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.739 ±(99.9%) 1.977 ms/op [Average]
  (min, avg, max) = (4.625, 4.739, 4.841), stdev = 0.108
  CI (99.9%): [2.762, 6.716] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.847 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.499 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.056 ±(99.9%) 0.015 ms/op
Iteration   1: 5.008 ±(99.9%) 0.005 ms/op
Iteration   2: 5.072 ±(99.9%) 0.004 ms/op
Iteration   3: 4.996 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.026 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (4.996, 5.026, 5.072), stdev = 0.041
  CI (99.9%): [4.285, 5.766] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.488 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 7.296 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 6.656 ±(99.9%) 0.019 ms/op
Iteration   1: 6.547 ±(99.9%) 0.023 ms/op
Iteration   2: 6.597 ±(99.9%) 0.026 ms/op
Iteration   3: 6.535 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.560 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (6.535, 6.560, 6.597), stdev = 0.033
  CI (99.9%): [5.963, 7.156] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 7.838 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 5.437 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.153 ±(99.9%) 0.019 ms/op
Iteration   1: 4.961 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.210 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   8.864 ms/op
                 createUser·p0.999:  16.548 ms/op
                 createUser·p0.9999: 21.827 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 5.054 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.225 ms/op
                 createUser·p0.99:   9.454 ms/op
                 createUser·p0.999:  12.644 ms/op
                 createUser·p0.9999: 23.910 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 5.023 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.472 ms/op
                 createUser·p0.95:   7.193 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  16.204 ms/op
                 createUser·p0.9999: 27.146 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 191499
  mean =      5.012 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2804 
    [ 2.500,  5.000) = 105558 
    [ 5.000,  7.500) = 76587 
    [ 7.500, 10.000) = 5228 
    [10.000, 12.500) = 927 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.086 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     26.265 ms/op
     p(99.9990) =     27.626 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 7.819 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.220 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.757 ±(99.9%) 0.016 ms/op
Iteration   1: 4.824 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   6.685 ms/op
                 existUser·p0.99:   8.569 ms/op
                 existUser·p0.999:  14.166 ms/op
                 existUser·p0.9999: 19.783 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   2: 4.650 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.529 ms/op
                 existUser·p0.99:   9.077 ms/op
                 existUser·p0.999:  17.487 ms/op
                 existUser·p0.9999: 22.248 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 4.685 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.396 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.915 ms/op
                 existUser·p0.95:   6.488 ms/op
                 existUser·p0.99:   8.311 ms/op
                 existUser·p0.999:  12.867 ms/op
                 existUser·p0.9999: 30.889 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 203516
  mean =      4.718 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3252 
    [ 2.500,  5.000) = 138804 
    [ 5.000,  7.500) = 57078 
    [ 7.500, 10.000) = 3392 
    [10.000, 12.500) = 590 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.563 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     28.923 ms/op
     p(99.9990) =     31.779 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.582 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.649 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.105 ±(99.9%) 0.016 ms/op
Iteration   1: 4.991 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   7.057 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  13.875 ms/op
                 getUser·p0.9999: 18.618 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   2: 5.118 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.029 ms/op
                 getUser·p0.99:   9.257 ms/op
                 getUser·p0.999:  16.945 ms/op
                 getUser·p0.9999: 23.610 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   3: 5.019 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.234 ms/op
                 getUser·p0.95:   6.849 ms/op
                 getUser·p0.99:   9.486 ms/op
                 getUser·p0.999:  15.372 ms/op
                 getUser·p0.9999: 23.393 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 190235
  mean =      5.042 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1700 
    [ 2.500,  5.000) = 104433 
    [ 5.000,  7.500) = 77809 
    [ 7.500, 10.000) = 5147 
    [10.000, 12.500) = 678 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      6.988 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     14.734 ms/op
     p(99.9900) =     23.363 ms/op
     p(99.9990) =     26.004 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.613 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 7.219 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 6.535 ±(99.9%) 0.030 ms/op
Iteration   1: 6.724 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   9.159 ms/op
                 listUser·p0.95:   10.535 ms/op
                 listUser·p0.99:   13.582 ms/op
                 listUser·p0.999:  22.687 ms/op
                 listUser·p0.9999: 24.764 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   2: 6.620 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   9.945 ms/op
                 listUser·p0.99:   12.613 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 25.532 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   3: 6.670 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   9.077 ms/op
                 listUser·p0.95:   10.256 ms/op
                 listUser·p0.99:   13.124 ms/op
                 listUser·p0.999:  24.378 ms/op
                 listUser·p0.9999: 38.246 ms/op
                 listUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 144007
  mean =      6.671 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 17546 
    [ 5.000,  7.500) = 93316 
    [ 7.500, 10.000) = 24882 
    [10.000, 12.500) = 6214 
    [12.500, 15.000) = 1368 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      6.234 ms/op
     p(90.0000) =      9.028 ms/op
     p(95.0000) =     10.240 ms/op
     p(99.0000) =     13.107 ms/op
     p(99.9000) =     22.642 ms/op
     p(99.9900) =     37.356 ms/op
     p(99.9990) =     39.151 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.330 ± 1.306  ops/ms
ClientGrpc.existUser                       thrpt       3   6.900 ± 3.702  ops/ms
ClientGrpc.getUser                         thrpt       3   6.329 ± 0.706  ops/ms
ClientGrpc.listUser                        thrpt       3   4.934 ± 0.883  ops/ms
ClientGrpc.createUser                       avgt       3   5.095 ± 1.031   ms/op
ClientGrpc.existUser                        avgt       3   4.739 ± 1.977   ms/op
ClientGrpc.getUser                          avgt       3   5.026 ± 0.740   ms/op
ClientGrpc.listUser                         avgt       3   6.560 ± 0.597   ms/op
ClientGrpc.createUser                     sample  191499   5.012 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.116           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.423           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.086           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.322           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.909           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.265           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.656           ms/op
ClientGrpc.existUser                      sample  203516   4.718 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.396           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.947           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.563           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.684           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.466           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.923           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.916           ms/op
ClientGrpc.getUser                        sample  190235   5.042 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.184           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.324           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.988           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.191           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.734           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.363           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.182           ms/op
ClientGrpc.listUser                       sample  144007   6.671 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.489           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           6.234           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           9.028           ms/op
ClientGrpc.listUser:listUser·p0.95        sample          10.240           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.107           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.642           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.356           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.584           ms/op
