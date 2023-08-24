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
# Warmup Iteration   1: 4.042 ops/ms
# Warmup Iteration   2: 9.033 ops/ms
# Warmup Iteration   3: 10.087 ops/ms
Iteration   1: 10.339 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.371 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (10.332, 10.371, 10.443), stdev = 0.062
  CI (99.9%): [9.240, 11.503] (assumes normal distribution)


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
# Warmup Iteration   1: 7.592 ops/ms
# Warmup Iteration   2: 10.431 ops/ms
# Warmup Iteration   3: 10.855 ops/ms
Iteration   1: 10.830 ops/ms
Iteration   2: 11.107 ops/ms
Iteration   3: 11.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.169 ±(99.9%) 6.820 ops/ms [Average]
  (min, avg, max) = (10.830, 11.169, 11.570), stdev = 0.374
  CI (99.9%): [4.348, 17.989] (assumes normal distribution)


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
# Warmup Iteration   1: 6.733 ops/ms
# Warmup Iteration   2: 10.080 ops/ms
# Warmup Iteration   3: 10.372 ops/ms
Iteration   1: 10.257 ops/ms
Iteration   2: 10.451 ops/ms
Iteration   3: 10.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.329 ±(99.9%) 1.938 ops/ms [Average]
  (min, avg, max) = (10.257, 10.329, 10.451), stdev = 0.106
  CI (99.9%): [8.391, 12.268] (assumes normal distribution)


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
# Warmup Iteration   1: 5.744 ops/ms
# Warmup Iteration   2: 7.682 ops/ms
# Warmup Iteration   3: 7.881 ops/ms
Iteration   1: 7.868 ops/ms
Iteration   2: 7.814 ops/ms
Iteration   3: 7.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.815 ±(99.9%) 0.968 ops/ms [Average]
  (min, avg, max) = (7.762, 7.815, 7.868), stdev = 0.053
  CI (99.9%): [6.847, 8.782] (assumes normal distribution)


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.004 ms/op
Iteration   1: 2.999 ±(99.9%) 0.003 ms/op
Iteration   2: 3.068 ±(99.9%) 0.003 ms/op
Iteration   3: 3.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.044 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (2.999, 3.044, 3.068), stdev = 0.039
  CI (99.9%): [2.333, 3.756] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.003 ms/op
Iteration   1: 2.913 ±(99.9%) 0.002 ms/op
Iteration   2: 2.944 ±(99.9%) 0.002 ms/op
Iteration   3: 2.865 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (2.865, 2.907, 2.944), stdev = 0.040
  CI (99.9%): [2.181, 3.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.239 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.004 ms/op
Iteration   1: 3.094 ±(99.9%) 0.002 ms/op
Iteration   2: 3.080 ±(99.9%) 0.003 ms/op
Iteration   3: 3.018 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.018, 3.064, 3.094), stdev = 0.041
  CI (99.9%): [2.324, 3.804] (assumes normal distribution)


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
# Warmup Iteration   1: 5.279 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.013 ms/op
Iteration   1: 4.018 ±(99.9%) 0.014 ms/op
Iteration   2: 3.936 ±(99.9%) 0.014 ms/op
Iteration   3: 4.072 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.008 ±(99.9%) 1.254 ms/op [Average]
  (min, avg, max) = (3.936, 4.008, 4.072), stdev = 0.069
  CI (99.9%): [2.754, 5.263] (assumes normal distribution)


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
# Warmup Iteration   1: 4.275 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  8.358 ms/op
                 createUser·p0.9999: 19.157 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.622 ms/op
                 createUser·p0.9999: 14.674 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  11.360 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311443
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15210 
    [ 2.500,  5.000) = 293769 
    [ 5.000,  7.500) = 1839 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.102 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     20.276 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.638 ms/op
                 existUser·p0.9999: 23.728 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  10.423 ms/op
                 existUser·p0.9999: 16.073 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  10.247 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323077
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30828 
    [ 2.500,  5.000) = 289801 
    [ 5.000,  7.500) = 1787 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      8.764 ms/op
     p(99.9900) =     21.861 ms/op
     p(99.9990) =     23.971 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.922 ms/op
                 getUser·p0.9999: 22.793 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.927 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 22.856 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313554
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13896 
    [ 2.500,  5.000) = 297170 
    [ 5.000,  7.500) = 2037 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 5.226 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.012 ms/op
Iteration   1: 4.027 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  14.165 ms/op
                 listUser·p0.9999: 15.977 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 4.117 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.325 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 29.499 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   3: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.229 ms/op
                 listUser·p0.999:  15.835 ms/op
                 listUser·p0.9999: 18.647 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236453
  mean =      4.058 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2196 
    [ 2.500,  5.000) = 209116 
    [ 5.000,  7.500) = 23231 
    [ 7.500, 10.000) = 1387 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     28.782 ms/op
     p(99.9990) =     29.774 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.371 ± 1.132  ops/ms
ClientGrpc.existUser                       thrpt       3  11.169 ± 6.820  ops/ms
ClientGrpc.getUser                         thrpt       3  10.329 ± 1.938  ops/ms
ClientGrpc.listUser                        thrpt       3   7.815 ± 0.968  ops/ms
ClientGrpc.createUser                       avgt       3   3.044 ± 0.711   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.727   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 0.740   ms/op
ClientGrpc.listUser                         avgt       3   4.008 ± 1.254   ms/op
ClientGrpc.createUser                     sample  311443   3.085 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.802           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.102           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.383           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.447           ms/op
ClientGrpc.existUser                      sample  323077   2.972 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.590           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.764           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.861           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.052           ms/op
ClientGrpc.getUser                        sample  313554   3.060 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.625           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.897           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.986           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.788           ms/op
ClientGrpc.listUser                       sample  236453   4.058 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.434           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.782           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.917           ms/op
