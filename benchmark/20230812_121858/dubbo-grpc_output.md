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
# Warmup Iteration   1: 3.806 ops/ms
# Warmup Iteration   2: 8.463 ops/ms
# Warmup Iteration   3: 9.947 ops/ms
Iteration   1: 10.259 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.406 ±(99.9%) 2.325 ops/ms [Average]
  (min, avg, max) = (10.259, 10.406, 10.483), stdev = 0.127
  CI (99.9%): [8.081, 12.732] (assumes normal distribution)


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
# Warmup Iteration   1: 7.181 ops/ms
# Warmup Iteration   2: 10.250 ops/ms
# Warmup Iteration   3: 10.599 ops/ms
Iteration   1: 10.771 ops/ms
Iteration   2: 10.532 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.675 ±(99.9%) 2.299 ops/ms [Average]
  (min, avg, max) = (10.532, 10.675, 10.771), stdev = 0.126
  CI (99.9%): [8.376, 12.973] (assumes normal distribution)


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
# Warmup Iteration   1: 6.399 ops/ms
# Warmup Iteration   2: 9.860 ops/ms
# Warmup Iteration   3: 10.180 ops/ms
Iteration   1: 10.306 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.329 ±(99.9%) 0.803 ops/ms [Average]
  (min, avg, max) = (10.300, 10.329, 10.379), stdev = 0.044
  CI (99.9%): [9.526, 11.131] (assumes normal distribution)


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
# Warmup Iteration   1: 4.965 ops/ms
# Warmup Iteration   2: 7.307 ops/ms
# Warmup Iteration   3: 7.704 ops/ms
Iteration   1: 7.810 ops/ms
Iteration   2: 7.847 ops/ms
Iteration   3: 7.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.802 ±(99.9%) 0.910 ops/ms [Average]
  (min, avg, max) = (7.748, 7.802, 7.847), stdev = 0.050
  CI (99.9%): [6.892, 8.711] (assumes normal distribution)


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.001 ms/op
Iteration   1: 3.079 ±(99.9%) 0.003 ms/op
Iteration   2: 3.111 ±(99.9%) 0.002 ms/op
Iteration   3: 3.118 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.103 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.079, 3.103, 3.118), stdev = 0.021
  CI (99.9%): [2.717, 3.489] (assumes normal distribution)


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.003 ms/op
Iteration   1: 2.863 ±(99.9%) 0.002 ms/op
Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
Iteration   3: 2.977 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (2.863, 2.944, 2.992), stdev = 0.070
  CI (99.9%): [1.659, 4.229] (assumes normal distribution)


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.006 ms/op
Iteration   1: 3.132 ±(99.9%) 0.004 ms/op
Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
Iteration   3: 3.087 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.129 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (3.087, 3.129, 3.168), stdev = 0.041
  CI (99.9%): [2.383, 3.875] (assumes normal distribution)


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
# Warmup Iteration   1: 5.601 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.331 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.024 ms/op
Iteration   1: 4.088 ±(99.9%) 0.042 ms/op
Iteration   2: 4.114 ±(99.9%) 0.029 ms/op
Iteration   3: 4.039 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.080 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (4.039, 4.080, 4.114), stdev = 0.038
  CI (99.9%): [3.385, 4.776] (assumes normal distribution)


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
Iteration   1: 3.099 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.942 ms/op
                 createUser·p0.9999: 31.119 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.566 ms/op
                 createUser·p0.999:  7.593 ms/op
                 createUser·p0.9999: 16.960 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  10.197 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309479
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15658 
    [ 2.500,  5.000) = 291736 
    [ 5.000,  7.500) = 1576 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     30.117 ms/op
     p(99.9990) =     31.389 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.824 ms/op
                 existUser·p0.9999: 14.373 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.761 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.368 ms/op
                 existUser·p0.999:  9.156 ms/op
                 existUser·p0.9999: 15.404 ms/op
                 existUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322923
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 799 
    [ 1.250,  2.500) = 26394 
    [ 2.500,  3.750) = 284303 
    [ 3.750,  5.000) = 9722 
    [ 5.000,  6.250) = 767 
    [ 6.250,  7.500) = 472 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.307 ms/op
     p(99.9900) =     15.244 ms/op
     p(99.9990) =     15.525 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.007 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  8.320 ms/op
                 getUser·p0.9999: 18.307 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  8.131 ms/op
                 getUser·p0.9999: 15.990 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.687 ms/op
                 getUser·p0.9999: 25.805 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309992
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20597 
    [ 2.500,  5.000) = 286572 
    [ 5.000,  7.500) = 2326 
    [ 7.500, 10.000) = 308 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.889 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     26.083 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.763 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.012 ms/op
Iteration   1: 4.082 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  13.489 ms/op
                 listUser·p0.9999: 15.406 ms/op
                 listUser·p1.00:   16.089 ms/op

Iteration   2: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  16.877 ms/op
                 listUser·p0.9999: 24.071 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 4.092 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 29.860 ms/op
                 listUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234523
  mean =      4.093 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2235 
    [ 2.500,  5.000) = 208176 
    [ 5.000,  7.500) = 22176 
    [ 7.500, 10.000) = 1423 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     14.663 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     31.543 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.406 ± 2.325  ops/ms
ClientGrpc.existUser                       thrpt       3  10.675 ± 2.299  ops/ms
ClientGrpc.getUser                         thrpt       3  10.329 ± 0.803  ops/ms
ClientGrpc.listUser                        thrpt       3   7.802 ± 0.910  ops/ms
ClientGrpc.createUser                       avgt       3   3.103 ± 0.386   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 1.285   ms/op
ClientGrpc.getUser                          avgt       3   3.129 ± 0.746   ms/op
ClientGrpc.listUser                         avgt       3   4.080 ± 0.696   ms/op
ClientGrpc.createUser                     sample  309479   3.102 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.731           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.224           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.117           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.490           ms/op
ClientGrpc.existUser                      sample  322923   2.971 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.606           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.244           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.827           ms/op
ClientGrpc.getUser                        sample  309992   3.095 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.889           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.380           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.953           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.182           ms/op
ClientGrpc.listUser                       sample  234523   4.093 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.983           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.663           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.426           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.654           ms/op
