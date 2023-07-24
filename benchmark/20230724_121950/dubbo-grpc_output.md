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
# Warmup Iteration   1: 4.297 ops/ms
# Warmup Iteration   2: 9.118 ops/ms
# Warmup Iteration   3: 9.992 ops/ms
Iteration   1: 10.248 ops/ms
Iteration   2: 10.378 ops/ms
Iteration   3: 10.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.414 ±(99.9%) 3.402 ops/ms [Average]
  (min, avg, max) = (10.248, 10.414, 10.616), stdev = 0.186
  CI (99.9%): [7.012, 13.816] (assumes normal distribution)


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
# Warmup Iteration   1: 7.790 ops/ms
# Warmup Iteration   2: 10.575 ops/ms
# Warmup Iteration   3: 11.076 ops/ms
Iteration   1: 11.090 ops/ms
Iteration   2: 11.085 ops/ms
Iteration   3: 11.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.134 ±(99.9%) 1.482 ops/ms [Average]
  (min, avg, max) = (11.085, 11.134, 11.228), stdev = 0.081
  CI (99.9%): [9.653, 12.616] (assumes normal distribution)


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
# Warmup Iteration   1: 7.286 ops/ms
# Warmup Iteration   2: 10.069 ops/ms
# Warmup Iteration   3: 10.592 ops/ms
Iteration   1: 10.750 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.684 ±(99.9%) 1.172 ops/ms [Average]
  (min, avg, max) = (10.622, 10.684, 10.750), stdev = 0.064
  CI (99.9%): [9.511, 11.856] (assumes normal distribution)


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
# Warmup Iteration   1: 5.761 ops/ms
# Warmup Iteration   2: 7.930 ops/ms
# Warmup Iteration   3: 8.254 ops/ms
Iteration   1: 8.333 ops/ms
Iteration   2: 8.300 ops/ms
Iteration   3: 8.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.304 ±(99.9%) 0.490 ops/ms [Average]
  (min, avg, max) = (8.279, 8.304, 8.333), stdev = 0.027
  CI (99.9%): [7.814, 8.794] (assumes normal distribution)


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.003 ms/op
Iteration   1: 3.035 ±(99.9%) 0.002 ms/op
Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.048 ±(99.9%) 0.373 ms/op [Average]
  (min, avg, max) = (3.035, 3.048, 3.072), stdev = 0.020
  CI (99.9%): [2.675, 3.421] (assumes normal distribution)


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.004 ms/op
Iteration   1: 2.918 ±(99.9%) 0.002 ms/op
Iteration   2: 2.897 ±(99.9%) 0.003 ms/op
Iteration   3: 2.889 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.901 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (2.889, 2.901, 2.918), stdev = 0.015
  CI (99.9%): [2.622, 3.180] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.003 ms/op
Iteration   1: 3.039 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.003 ms/op
Iteration   3: 3.025 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.030 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (3.025, 3.030, 3.039), stdev = 0.008
  CI (99.9%): [2.888, 3.172] (assumes normal distribution)


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
# Warmup Iteration   1: 5.107 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.017 ms/op
Iteration   1: 3.921 ±(99.9%) 0.022 ms/op
Iteration   2: 3.827 ±(99.9%) 0.004 ms/op
Iteration   3: 3.937 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.895 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (3.827, 3.895, 3.937), stdev = 0.060
  CI (99.9%): [2.808, 4.981] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  6.887 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.579 ms/op
                 createUser·p0.9999: 19.871 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   3: 2.986 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.518 ms/op
                 createUser·p0.99:   4.121 ms/op
                 createUser·p0.999:  7.600 ms/op
                 createUser·p0.9999: 15.761 ms/op
                 createUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320051
  mean =      2.997 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20922 
    [ 2.500,  5.000) = 297782 
    [ 5.000,  7.500) = 1035 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.479 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.005 ms/op
Iteration   1: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.850 ms/op
                 existUser·p0.9999: 11.372 ms/op
                 existUser·p1.00:   11.600 ms/op

Iteration   2: 2.902 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  5.833 ms/op
                 existUser·p0.9999: 14.843 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.349 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 14.927 ms/op
                 existUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329636
  mean =      2.914 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1492 
    [ 1.250,  2.500) = 34734 
    [ 2.500,  3.750) = 282610 
    [ 3.750,  5.000) = 9376 
    [ 5.000,  6.250) = 944 
    [ 6.250,  7.500) = 247 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      6.843 ms/op
     p(99.9900) =     14.763 ms/op
     p(99.9990) =     15.215 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  9.921 ms/op
                 getUser·p0.9999: 19.252 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.947 ms/op
                 getUser·p0.9999: 20.203 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.122 ms/op
                 getUser·p0.9999: 21.688 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314906
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18757 
    [ 2.500,  5.000) = 294493 
    [ 5.000,  7.500) = 1342 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.496 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     22.048 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 5.006 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.011 ms/op
Iteration   1: 3.915 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  12.678 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   2: 3.906 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.732 ms/op
                 listUser·p0.9999: 17.513 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 3.914 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.501 ms/op
                 listUser·p0.9999: 24.559 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245368
  mean =      3.912 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3216 
    [ 2.500,  5.000) = 218881 
    [ 5.000,  7.500) = 22088 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.609 ms/op
     p(99.9900) =     22.625 ms/op
     p(99.9990) =     24.957 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.414 ± 3.402  ops/ms
ClientGrpc.existUser                       thrpt       3  11.134 ± 1.482  ops/ms
ClientGrpc.getUser                         thrpt       3  10.684 ± 1.172  ops/ms
ClientGrpc.listUser                        thrpt       3   8.304 ± 0.490  ops/ms
ClientGrpc.createUser                       avgt       3   3.048 ± 0.373   ms/op
ClientGrpc.existUser                        avgt       3   2.901 ± 0.279   ms/op
ClientGrpc.getUser                          avgt       3   3.030 ± 0.142   ms/op
ClientGrpc.listUser                         avgt       3   3.895 ± 1.087   ms/op
ClientGrpc.createUser                     sample  320051   2.997 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.584           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.428           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.479           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.759           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.644           ms/op
ClientGrpc.existUser                      sample  329636   2.914 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.635           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.843           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.763           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.532           ms/op
ClientGrpc.getUser                        sample  314906   3.047 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.652           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.496           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.004           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.184           ms/op
ClientGrpc.listUser                       sample  245368   3.912 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.031           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.609           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.625           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
