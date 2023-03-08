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
# Warmup Iteration   1: 2.161 ops/ms
# Warmup Iteration   2: 6.065 ops/ms
# Warmup Iteration   3: 7.229 ops/ms
Iteration   1: 7.830 ops/ms
Iteration   2: 8.122 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.955 ±(99.9%) 2.740 ops/ms [Average]
  (min, avg, max) = (7.830, 7.955, 8.122), stdev = 0.150
  CI (99.9%): [5.215, 10.695] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.175 ops/ms
# Warmup Iteration   2: 7.868 ops/ms
# Warmup Iteration   3: 8.219 ops/ms
Iteration   1: 8.173 ops/ms
Iteration   2: 8.336 ops/ms
Iteration   3: 8.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.275 ±(99.9%) 1.614 ops/ms [Average]
  (min, avg, max) = (8.173, 8.275, 8.336), stdev = 0.088
  CI (99.9%): [6.660, 9.889] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.501 ops/ms
# Warmup Iteration   2: 6.852 ops/ms
# Warmup Iteration   3: 7.740 ops/ms
Iteration   1: 7.905 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 8.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.091 ±(99.9%) 3.831 ops/ms [Average]
  (min, avg, max) = (7.905, 8.091, 8.319), stdev = 0.210
  CI (99.9%): [4.260, 11.922] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.842 ops/ms
# Warmup Iteration   2: 5.855 ops/ms
# Warmup Iteration   3: 6.220 ops/ms
Iteration   1: 6.160 ops/ms
Iteration   2: 6.300 ops/ms
Iteration   3: 6.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.224 ±(99.9%) 1.297 ops/ms [Average]
  (min, avg, max) = (6.160, 6.224, 6.300), stdev = 0.071
  CI (99.9%): [4.927, 7.520] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.107 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.014 ms/op
Iteration   1: 4.026 ±(99.9%) 0.005 ms/op
Iteration   2: 3.949 ±(99.9%) 0.002 ms/op
Iteration   3: 3.977 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.984 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (3.949, 3.984, 4.026), stdev = 0.039
  CI (99.9%): [3.267, 4.701] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.632 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.003 ms/op
Iteration   1: 3.851 ±(99.9%) 0.003 ms/op
Iteration   2: 3.799 ±(99.9%) 0.003 ms/op
Iteration   3: 3.790 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.813 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.790, 3.813, 3.851), stdev = 0.033
  CI (99.9%): [3.212, 4.415] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.274 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.003 ms/op
Iteration   1: 3.969 ±(99.9%) 0.002 ms/op
Iteration   2: 3.893 ±(99.9%) 0.002 ms/op
Iteration   3: 3.883 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.915 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (3.883, 3.915, 3.969), stdev = 0.047
  CI (99.9%): [3.063, 4.767] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.492 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.369 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.016 ms/op
Iteration   1: 4.990 ±(99.9%) 0.021 ms/op
Iteration   2: 5.000 ±(99.9%) 0.011 ms/op
Iteration   3: 5.075 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.022 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (4.990, 5.022, 5.075), stdev = 0.046
  CI (99.9%): [4.182, 5.861] (assumes normal distribution)


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
# Warmup Iteration   1: 6.367 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.012 ms/op
Iteration   1: 4.075 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   5.071 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  11.565 ms/op
                 createUser·p0.9999: 16.213 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   2: 3.941 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  11.021 ms/op
                 createUser·p0.9999: 15.246 ms/op
                 createUser·p1.00:   15.614 ms/op

Iteration   3: 4.154 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  12.322 ms/op
                 createUser·p0.9999: 20.087 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 236687
  mean =      4.055 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6901 
    [ 2.500,  5.000) = 203976 
    [ 5.000,  7.500) = 23617 
    [ 7.500, 10.000) = 1656 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     11.649 ms/op
     p(99.9900) =     19.672 ms/op
     p(99.9990) =     20.903 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.929 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   6.336 ms/op
                 existUser·p0.999:  12.575 ms/op
                 existUser·p0.9999: 15.836 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   2: 3.668 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  9.432 ms/op
                 existUser·p0.9999: 14.672 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   3: 3.658 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   6.265 ms/op
                 existUser·p0.999:  10.320 ms/op
                 existUser·p0.9999: 29.163 ms/op
                 existUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 257291
  mean =      3.732 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11817 
    [ 2.500,  5.000) = 232906 
    [ 5.000,  7.500) = 11314 
    [ 7.500, 10.000) = 882 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     29.790 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 6.195 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.011 ms/op
Iteration   1: 4.020 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.212 ms/op
                 getUser·p0.999:  11.092 ms/op
                 getUser·p0.9999: 17.565 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   2: 3.965 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   6.561 ms/op
                 getUser·p0.999:  12.534 ms/op
                 getUser·p0.9999: 28.768 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  11.828 ms/op
                 getUser·p0.9999: 19.169 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241629
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8692 
    [ 2.500,  5.000) = 212478 
    [ 5.000,  7.500) = 18799 
    [ 7.500, 10.000) = 1224 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     27.575 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 7.496 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.309 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.996 ±(99.9%) 0.016 ms/op
Iteration   1: 4.967 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 20.728 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 5.131 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  18.002 ms/op
                 listUser·p0.9999: 25.624 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   3: 5.230 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   7.856 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  20.709 ms/op
                 listUser·p0.9999: 26.712 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187911
  mean =      5.107 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 376 
    [ 2.500,  5.000) = 107610 
    [ 5.000,  7.500) = 70320 
    [ 7.500, 10.000) = 8250 
    [10.000, 12.500) = 870 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.586 ms/op
     p(95.0000) =      7.528 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     25.099 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.955 ± 2.740  ops/ms
ClientGrpc.existUser                       thrpt       3   8.275 ± 1.614  ops/ms
ClientGrpc.getUser                         thrpt       3   8.091 ± 3.831  ops/ms
ClientGrpc.listUser                        thrpt       3   6.224 ± 1.297  ops/ms
ClientGrpc.createUser                       avgt       3   3.984 ± 0.717   ms/op
ClientGrpc.existUser                        avgt       3   3.813 ± 0.601   ms/op
ClientGrpc.getUser                          avgt       3   3.915 ± 0.852   ms/op
ClientGrpc.listUser                         avgt       3   5.022 ± 0.840   ms/op
ClientGrpc.createUser                     sample  236687   4.055 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.600           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.054           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.505           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.649           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.672           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.299           ms/op
ClientGrpc.existUser                      sample  257291   3.732 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.826           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.989           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.226           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.977           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.049           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.376           ms/op
ClientGrpc.getUser                        sample  241629   3.972 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.892           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.300           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.808           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.518           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.575           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.557           ms/op
ClientGrpc.listUser                       sample  187911   5.107 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.354           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.528           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.503           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.099           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
