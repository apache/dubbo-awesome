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
# Warmup Iteration   1: 5.164 ops/ms
# Warmup Iteration   2: 9.013 ops/ms
# Warmup Iteration   3: 10.005 ops/ms
Iteration   1: 10.072 ops/ms
Iteration   2: 10.273 ops/ms
Iteration   3: 10.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.353 ±(99.9%) 5.995 ops/ms [Average]
  (min, avg, max) = (10.072, 10.353, 10.714), stdev = 0.329
  CI (99.9%): [4.358, 16.348] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.052 ops/ms
# Warmup Iteration   2: 10.877 ops/ms
# Warmup Iteration   3: 11.230 ops/ms
Iteration   1: 11.260 ops/ms
Iteration   2: 11.340 ops/ms
Iteration   3: 11.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.231 ±(99.9%) 2.295 ops/ms [Average]
  (min, avg, max) = (11.093, 11.231, 11.340), stdev = 0.126
  CI (99.9%): [8.936, 13.526] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.714 ops/ms
# Warmup Iteration   2: 10.199 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.568 ops/ms
Iteration   2: 11.140 ops/ms
Iteration   3: 10.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.858 ±(99.9%) 5.220 ops/ms [Average]
  (min, avg, max) = (10.568, 10.858, 11.140), stdev = 0.286
  CI (99.9%): [5.638, 16.078] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.820 ops/ms
# Warmup Iteration   2: 8.038 ops/ms
# Warmup Iteration   3: 8.251 ops/ms
Iteration   1: 8.331 ops/ms
Iteration   2: 8.003 ops/ms
Iteration   3: 8.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.156 ±(99.9%) 3.009 ops/ms [Average]
  (min, avg, max) = (8.003, 8.156, 8.331), stdev = 0.165
  CI (99.9%): [5.147, 11.165] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.138 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 2.959 ±(99.9%) 0.002 ms/op
Iteration   2: 2.936 ±(99.9%) 0.003 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.960 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (2.936, 2.960, 2.987), stdev = 0.025
  CI (99.9%): [2.495, 3.425] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.003 ms/op
Iteration   1: 2.910 ±(99.9%) 0.003 ms/op
Iteration   2: 2.901 ±(99.9%) 0.002 ms/op
Iteration   3: 2.832 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.881 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (2.832, 2.881, 2.910), stdev = 0.043
  CI (99.9%): [2.100, 3.662] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.002 ms/op
Iteration   1: 2.940 ±(99.9%) 0.003 ms/op
Iteration   2: 2.864 ±(99.9%) 0.002 ms/op
Iteration   3: 2.964 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.923 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (2.864, 2.923, 2.964), stdev = 0.052
  CI (99.9%): [1.965, 3.880] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.013 ms/op
Iteration   1: 3.880 ±(99.9%) 0.016 ms/op
Iteration   2: 3.826 ±(99.9%) 0.018 ms/op
Iteration   3: 3.804 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.837 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (3.804, 3.837, 3.880), stdev = 0.039
  CI (99.9%): [3.129, 4.544] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.540 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.603 ms/op
                 createUser·p0.9999: 11.731 ms/op
                 createUser·p1.00:   12.042 ms/op

Iteration   2: 2.978 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.824 ms/op
                 createUser·p0.9999: 16.991 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.510 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.513 ms/op
                 createUser·p0.9999: 25.812 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322216
  mean =      2.980 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33120 
    [ 2.500,  5.000) = 287520 
    [ 5.000,  7.500) = 1284 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.066 ms/op
     p(99.9900) =     23.280 ms/op
     p(99.9990) =     26.233 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.894 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
Iteration   1: 2.824 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.521 ms/op
                 existUser·p0.9999: 16.887 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   2: 2.864 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.685 ms/op
                 existUser·p0.9999: 15.557 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   3: 2.743 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.229 ms/op
                 existUser·p0.9999: 13.834 ms/op
                 existUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 341468
  mean =      2.809 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5971 
    [ 1.250,  2.500) = 52210 
    [ 2.500,  3.750) = 274606 
    [ 3.750,  5.000) = 7691 
    [ 5.000,  6.250) = 648 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.259 ms/op
     p(99.9900) =     16.328 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
Iteration   1: 2.928 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.957 ms/op
                 getUser·p0.9999: 14.189 ms/op
                 getUser·p1.00:   16.220 ms/op

Iteration   2: 2.940 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 16.535 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   3: 2.974 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.312 ms/op
                 getUser·p0.9999: 22.626 ms/op
                 getUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325516
  mean =      2.947 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34961 
    [ 2.500,  5.000) = 289412 
    [ 5.000,  7.500) = 823 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.455 ms/op
     p(99.9900) =     19.894 ms/op
     p(99.9990) =     22.896 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 4.684 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
Iteration   1: 3.844 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.821 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.205 ms/op
                 listUser·p0.9999: 26.964 ms/op
                 listUser·p1.00:   27.427 ms/op

Iteration   3: 3.796 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  15.567 ms/op
                 listUser·p0.9999: 23.854 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251387
  mean =      3.820 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6771 
    [ 2.500,  5.000) = 225474 
    [ 5.000,  7.500) = 18169 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     23.097 ms/op
     p(99.9990) =     27.328 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.353 ± 5.995  ops/ms
ClientGrpc.existUser                       thrpt       3  11.231 ± 2.295  ops/ms
ClientGrpc.getUser                         thrpt       3  10.858 ± 5.220  ops/ms
ClientGrpc.listUser                        thrpt       3   8.156 ± 3.009  ops/ms
ClientGrpc.createUser                       avgt       3   2.960 ± 0.465   ms/op
ClientGrpc.existUser                        avgt       3   2.881 ± 0.781   ms/op
ClientGrpc.getUser                          avgt       3   2.923 ± 0.958   ms/op
ClientGrpc.listUser                         avgt       3   3.837 ± 0.708   ms/op
ClientGrpc.createUser                     sample  322216   2.980 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.510           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.066           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.280           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.345           ms/op
ClientGrpc.existUser                      sample  341468   2.809 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.537           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.818           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.259           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.328           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.170           ms/op
ClientGrpc.getUser                        sample  325516   2.947 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.455           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.894           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.233           ms/op
ClientGrpc.listUser                       sample  251387   3.820 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.903           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.097           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.427           ms/op
