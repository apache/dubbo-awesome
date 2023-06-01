# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ops/ms
# Warmup Iteration   2: 9.308 ops/ms
# Warmup Iteration   3: 10.164 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.747 ops/ms
Iteration   3: 10.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.749 ±(99.9%) 1.989 ops/ms [Average]
  (min, avg, max) = (10.641, 10.749, 10.859), stdev = 0.109
  CI (99.9%): [8.760, 12.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.764 ops/ms
# Warmup Iteration   2: 10.872 ops/ms
# Warmup Iteration   3: 11.599 ops/ms
Iteration   1: 11.228 ops/ms
Iteration   2: 11.235 ops/ms
Iteration   3: 11.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.156 ±(99.9%) 2.393 ops/ms [Average]
  (min, avg, max) = (11.004, 11.156, 11.235), stdev = 0.131
  CI (99.9%): [8.763, 13.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.122 ops/ms
# Warmup Iteration   2: 10.370 ops/ms
# Warmup Iteration   3: 10.682 ops/ms
Iteration   1: 10.764 ops/ms
Iteration   2: 10.787 ops/ms
Iteration   3: 10.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.810 ±(99.9%) 1.108 ops/ms [Average]
  (min, avg, max) = (10.764, 10.810, 10.879), stdev = 0.061
  CI (99.9%): [9.701, 11.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.026 ops/ms
# Warmup Iteration   2: 8.124 ops/ms
# Warmup Iteration   3: 8.251 ops/ms
Iteration   1: 8.294 ops/ms
Iteration   2: 8.205 ops/ms
Iteration   3: 8.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.357 ±(99.9%) 3.509 ops/ms [Average]
  (min, avg, max) = (8.205, 8.357, 8.573), stdev = 0.192
  CI (99.9%): [4.849, 11.866] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.005 ms/op
Iteration   1: 2.911 ±(99.9%) 0.002 ms/op
Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
Iteration   3: 3.005 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.983 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (2.911, 2.983, 3.032), stdev = 0.063
  CI (99.9%): [1.825, 4.140] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.003 ms/op
Iteration   1: 2.827 ±(99.9%) 0.003 ms/op
Iteration   2: 2.937 ±(99.9%) 0.002 ms/op
Iteration   3: 2.899 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.888 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (2.827, 2.888, 2.937), stdev = 0.056
  CI (99.9%): [1.868, 3.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.335 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.004 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
Iteration   3: 2.964 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.003 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (2.964, 3.003, 3.039), stdev = 0.038
  CI (99.9%): [2.317, 3.689] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.212 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.020 ms/op
Iteration   1: 3.786 ±(99.9%) 0.009 ms/op
Iteration   2: 3.784 ±(99.9%) 0.007 ms/op
Iteration   3: 3.823 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.798 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (3.784, 3.798, 3.823), stdev = 0.022
  CI (99.9%): [3.393, 4.203] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 2.962 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.288 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.438 ms/op
                 createUser·p0.9999: 13.589 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.620 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.465 ms/op
                 createUser·p0.9999: 14.232 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  9.542 ms/op
                 createUser·p0.9999: 17.657 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321119
  mean =      2.990 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1009 
    [ 1.250,  2.500) = 27251 
    [ 2.500,  3.750) = 280423 
    [ 3.750,  5.000) = 10817 
    [ 5.000,  6.250) = 869 
    [ 6.250,  7.500) = 385 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.732 ms/op
     p(99.9900) =     16.155 ms/op
     p(99.9990) =     18.231 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.005 ms/op
Iteration   1: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  6.350 ms/op
                 existUser·p0.9999: 19.169 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 2.836 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  6.975 ms/op
                 existUser·p0.9999: 13.868 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.871 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  8.782 ms/op
                 existUser·p0.9999: 16.628 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334956
  mean =      2.865 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1508 
    [ 1.250,  2.500) = 36275 
    [ 2.500,  3.750) = 291000 
    [ 3.750,  5.000) = 5315 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 171 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.449 ms/op
     p(99.0000) =      3.981 ms/op
     p(99.9000) =      6.545 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     19.486 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.379 ms/op
                 getUser·p0.999:  7.561 ms/op
                 getUser·p0.9999: 17.087 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.497 ms/op
                 getUser·p0.9999: 18.885 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.843 ms/op
                 getUser·p0.9999: 24.520 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319315
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24397 
    [ 2.500,  5.000) = 293502 
    [ 5.000,  7.500) = 1113 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.458 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.905 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
Iteration   1: 3.839 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.856 ms/op
                 listUser·p0.9999: 20.829 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.834 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  16.476 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 3.895 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.840 ms/op
                 listUser·p0.9999: 27.445 ms/op
                 listUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249093
  mean =      3.856 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4426 
    [ 2.500,  5.000) = 226039 
    [ 5.000,  7.500) = 17668 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.012 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     15.350 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.749 ± 1.989  ops/ms
ClientGrpc.existUser                       thrpt       3  11.156 ± 2.393  ops/ms
ClientGrpc.getUser                         thrpt       3  10.810 ± 1.108  ops/ms
ClientGrpc.listUser                        thrpt       3   8.357 ± 3.509  ops/ms
ClientGrpc.createUser                       avgt       3   2.983 ± 1.157   ms/op
ClientGrpc.existUser                        avgt       3   2.888 ± 1.020   ms/op
ClientGrpc.getUser                          avgt       3   3.003 ± 0.686   ms/op
ClientGrpc.listUser                         avgt       3   3.798 ± 0.405   ms/op
ClientGrpc.createUser                     sample  321119   2.990 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.288           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.732           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.155           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.448           ms/op
ClientGrpc.existUser                      sample  334956   2.865 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.549           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.244           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.981           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.545           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.810           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.562           ms/op
ClientGrpc.getUser                        sample  319315   3.007 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.458           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.117           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  249093   3.856 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.012           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.350           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.821           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.508           ms/op
