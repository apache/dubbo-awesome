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
# Warmup Iteration   1: 2.864 ops/ms
# Warmup Iteration   2: 5.941 ops/ms
# Warmup Iteration   3: 7.703 ops/ms
Iteration   1: 8.128 ops/ms
Iteration   2: 7.883 ops/ms
Iteration   3: 7.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.986 ±(99.9%) 2.314 ops/ms [Average]
  (min, avg, max) = (7.883, 7.986, 8.128), stdev = 0.127
  CI (99.9%): [5.672, 10.300] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.448 ops/ms
# Warmup Iteration   2: 8.088 ops/ms
# Warmup Iteration   3: 8.493 ops/ms
Iteration   1: 8.578 ops/ms
Iteration   2: 8.829 ops/ms
Iteration   3: 9.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.852 ±(99.9%) 5.228 ops/ms [Average]
  (min, avg, max) = (8.578, 8.852, 9.149), stdev = 0.287
  CI (99.9%): [3.624, 14.080] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.011 ops/ms
# Warmup Iteration   2: 7.605 ops/ms
# Warmup Iteration   3: 7.924 ops/ms
Iteration   1: 8.064 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 8.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.205 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (8.064, 8.205, 8.334), stdev = 0.135
  CI (99.9%): [5.736, 10.674] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ops/ms
# Warmup Iteration   2: 5.742 ops/ms
# Warmup Iteration   3: 6.108 ops/ms
Iteration   1: 6.285 ops/ms
Iteration   2: 6.346 ops/ms
Iteration   3: 6.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.389 ±(99.9%) 2.386 ops/ms [Average]
  (min, avg, max) = (6.285, 6.389, 6.536), stdev = 0.131
  CI (99.9%): [4.003, 8.775] (assumes normal distribution)


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
# Warmup Iteration   1: 5.635 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.012 ms/op
Iteration   1: 3.897 ±(99.9%) 0.004 ms/op
Iteration   2: 3.904 ±(99.9%) 0.004 ms/op
Iteration   3: 3.830 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.877 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (3.830, 3.877, 3.904), stdev = 0.041
  CI (99.9%): [3.133, 4.620] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.858 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.003 ms/op
Iteration   1: 3.733 ±(99.9%) 0.002 ms/op
Iteration   2: 3.492 ±(99.9%) 0.005 ms/op
Iteration   3: 3.663 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.629 ±(99.9%) 2.269 ms/op [Average]
  (min, avg, max) = (3.492, 3.629, 3.733), stdev = 0.124
  CI (99.9%): [1.361, 5.898] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.506 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.004 ms/op
Iteration   1: 3.790 ±(99.9%) 0.003 ms/op
Iteration   2: 3.953 ±(99.9%) 0.003 ms/op
Iteration   3: 3.906 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.883 ±(99.9%) 1.530 ms/op [Average]
  (min, avg, max) = (3.790, 3.883, 3.953), stdev = 0.084
  CI (99.9%): [2.353, 5.413] (assumes normal distribution)


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
# Warmup Iteration   1: 7.627 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.428 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.093 ±(99.9%) 0.010 ms/op
Iteration   1: 5.069 ±(99.9%) 0.013 ms/op
Iteration   2: 4.931 ±(99.9%) 0.014 ms/op
Iteration   3: 5.004 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.002 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (4.931, 5.002, 5.069), stdev = 0.069
  CI (99.9%): [3.740, 6.263] (assumes normal distribution)


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
# Warmup Iteration   1: 5.556 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
Iteration   1: 3.902 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  11.077 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.811 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  13.582 ms/op
                 createUser·p0.9999: 22.452 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 3.830 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  22.872 ms/op
                 createUser·p0.9999: 28.770 ms/op
                 createUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249482
  mean =      3.847 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5750 
    [ 2.500,  5.000) = 231103 
    [ 5.000,  7.500) = 11369 
    [ 7.500, 10.000) = 857 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     13.378 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     28.787 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 5.117 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.008 ms/op
Iteration   1: 3.706 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 18.407 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   2: 3.635 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  9.471 ms/op
                 existUser·p0.9999: 16.695 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   3: 3.620 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  11.551 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262699
  mean =      3.653 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6667 
    [ 2.500,  5.000) = 247805 
    [ 5.000,  7.500) = 7249 
    [ 7.500, 10.000) = 780 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =      9.475 ms/op
     p(99.9900) =     19.160 ms/op
     p(99.9990) =     20.996 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 5.426 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.010 ms/op
Iteration   1: 4.075 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  14.492 ms/op
                 getUser·p0.9999: 16.548 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   2: 3.901 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.347 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.507 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 17.590 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  12.086 ms/op
                 getUser·p0.9999: 19.736 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241813
  mean =      3.968 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6018 
    [ 2.500,  5.000) = 218431 
    [ 5.000,  7.500) = 15812 
    [ 7.500, 10.000) = 1051 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.012 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     20.742 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.466 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.331 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.903 ±(99.9%) 0.015 ms/op
Iteration   1: 5.016 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.397 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 5.108 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.726 ms/op
                 listUser·p0.95:   7.602 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  21.473 ms/op
                 listUser·p0.9999: 27.254 ms/op
                 listUser·p1.00:   28.934 ms/op

Iteration   3: 5.153 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   6.644 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  25.068 ms/op
                 listUser·p0.9999: 33.305 ms/op
                 listUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188615
  mean =      5.091 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 364 
    [ 2.500,  5.000) = 114535 
    [ 5.000,  7.500) = 63894 
    [ 7.500, 10.000) = 8384 
    [10.000, 12.500) = 987 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      7.545 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     31.855 ms/op
     p(99.9990) =     33.890 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.986 ± 2.314  ops/ms
ClientGrpc.existUser                       thrpt       3   8.852 ± 5.228  ops/ms
ClientGrpc.getUser                         thrpt       3   8.205 ± 2.469  ops/ms
ClientGrpc.listUser                        thrpt       3   6.389 ± 2.386  ops/ms
ClientGrpc.createUser                       avgt       3   3.877 ± 0.743   ms/op
ClientGrpc.existUser                        avgt       3   3.629 ± 2.269   ms/op
ClientGrpc.getUser                          avgt       3   3.883 ± 1.530   ms/op
ClientGrpc.listUser                         avgt       3   5.002 ± 1.261   ms/op
ClientGrpc.createUser                     sample  249482   3.847 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.980           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.390           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.378           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.558           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.803           ms/op
ClientGrpc.existUser                      sample  262699   3.653 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.876           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.931           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.475           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.160           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.103           ms/op
ClientGrpc.getUser                        sample  241813   3.968 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.347           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.218           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.668           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.012           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.416           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  188615   5.091 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.829           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.617           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.186           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.855           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.948           ms/op
