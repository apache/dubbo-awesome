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
# Warmup Iteration   1: 4.661 ops/ms
# Warmup Iteration   2: 9.256 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 10.467 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.586 ±(99.9%) 2.039 ops/ms [Average]
  (min, avg, max) = (10.467, 10.586, 10.689), stdev = 0.112
  CI (99.9%): [8.546, 12.625] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.676 ops/ms
# Warmup Iteration   2: 10.365 ops/ms
# Warmup Iteration   3: 11.001 ops/ms
Iteration   1: 11.040 ops/ms
Iteration   2: 11.166 ops/ms
Iteration   3: 11.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.163 ±(99.9%) 2.201 ops/ms [Average]
  (min, avg, max) = (11.040, 11.163, 11.282), stdev = 0.121
  CI (99.9%): [8.961, 13.364] (assumes normal distribution)


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
# Warmup Iteration   1: 7.395 ops/ms
# Warmup Iteration   2: 9.970 ops/ms
# Warmup Iteration   3: 10.563 ops/ms
Iteration   1: 10.671 ops/ms
Iteration   2: 10.719 ops/ms
Iteration   3: 10.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.689 ±(99.9%) 0.480 ops/ms [Average]
  (min, avg, max) = (10.671, 10.689, 10.719), stdev = 0.026
  CI (99.9%): [10.209, 11.169] (assumes normal distribution)


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
# Warmup Iteration   1: 5.934 ops/ms
# Warmup Iteration   2: 7.960 ops/ms
# Warmup Iteration   3: 8.237 ops/ms
Iteration   1: 8.411 ops/ms
Iteration   2: 8.159 ops/ms
Iteration   3: 8.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.253 ±(99.9%) 2.505 ops/ms [Average]
  (min, avg, max) = (8.159, 8.253, 8.411), stdev = 0.137
  CI (99.9%): [5.748, 10.759] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.003 ms/op
Iteration   2: 3.021 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.023 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.005, 3.023, 3.044), stdev = 0.020
  CI (99.9%): [2.665, 3.381] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.834 ±(99.9%) 0.003 ms/op
Iteration   1: 2.852 ±(99.9%) 0.003 ms/op
Iteration   2: 2.877 ±(99.9%) 0.003 ms/op
Iteration   3: 2.843 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.858 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.843, 2.858, 2.877), stdev = 0.018
  CI (99.9%): [2.538, 3.177] (assumes normal distribution)


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.002 ms/op
Iteration   1: 3.016 ±(99.9%) 0.003 ms/op
Iteration   2: 2.989 ±(99.9%) 0.003 ms/op
Iteration   3: 2.968 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.446 ms/op [Average]
  (min, avg, max) = (2.968, 2.991, 3.016), stdev = 0.024
  CI (99.9%): [2.545, 3.437] (assumes normal distribution)


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
# Warmup Iteration   1: 5.135 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.018 ms/op
Iteration   1: 3.939 ±(99.9%) 0.032 ms/op
Iteration   2: 3.896 ±(99.9%) 0.025 ms/op
Iteration   3: 3.903 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.913 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (3.896, 3.913, 3.939), stdev = 0.023
  CI (99.9%): [3.492, 4.334] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.540 ms/op
                 createUser·p0.9999: 20.578 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.360 ms/op
                 createUser·p0.9999: 16.215 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.713 ms/op
                 createUser·p0.9999: 14.287 ms/op
                 createUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316429
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22358 
    [ 2.500,  5.000) = 292895 
    [ 5.000,  7.500) = 900 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.356 ms/op
     p(99.9000) =      7.091 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
Iteration   1: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.181 ms/op
                 existUser·p0.9999: 12.057 ms/op
                 existUser·p1.00:   12.222 ms/op

Iteration   2: 2.793 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.158 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.472 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.869 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  10.355 ms/op
                 existUser·p0.9999: 17.039 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336400
  mean =      2.853 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4135 
    [ 1.250,  2.500) = 39622 
    [ 2.500,  3.750) = 283490 
    [ 3.750,  5.000) = 8192 
    [ 5.000,  6.250) = 501 
    [ 6.250,  7.500) = 152 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.143 ms/op
     p(99.9900) =     13.971 ms/op
     p(99.9990) =     17.212 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.196 ms/op
                 getUser·p0.9999: 15.450 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   2: 2.964 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.758 ms/op
                 getUser·p0.9999: 13.052 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.410 ms/op
                 getUser·p0.9999: 17.596 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322055
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2142 
    [ 1.250,  2.500) = 20270 
    [ 2.500,  3.750) = 286700 
    [ 3.750,  5.000) = 11760 
    [ 5.000,  6.250) = 716 
    [ 6.250,  7.500) = 208 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =     16.761 ms/op
     p(99.9990) =     17.968 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 5.207 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.009 ms/op
Iteration   1: 3.945 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.189 ms/op
                 listUser·p0.9999: 19.261 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   2: 3.839 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  13.605 ms/op
                 listUser·p0.9999: 19.442 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 3.584 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   6.763 ms/op
                 listUser·p0.999:  13.784 ms/op
                 listUser·p0.9999: 17.275 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253721
  mean =      3.783 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5918 
    [ 2.500,  5.000) = 229017 
    [ 5.000,  7.500) = 17581 
    [ 7.500, 10.000) = 763 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.177 ms/op
     p(99.9900) =     19.124 ms/op
     p(99.9990) =     21.937 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.586 ± 2.039  ops/ms
ClientGrpc.existUser                       thrpt       3  11.163 ± 2.201  ops/ms
ClientGrpc.getUser                         thrpt       3  10.689 ± 0.480  ops/ms
ClientGrpc.listUser                        thrpt       3   8.253 ± 2.505  ops/ms
ClientGrpc.createUser                       avgt       3   3.023 ± 0.358   ms/op
ClientGrpc.existUser                        avgt       3   2.858 ± 0.319   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.446   ms/op
ClientGrpc.listUser                         avgt       3   3.913 ± 0.421   ms/op
ClientGrpc.createUser                     sample  316429   3.034 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.642           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.091           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.792           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.808           ms/op
ClientGrpc.existUser                      sample  336400   2.853 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.510           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.143           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.971           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.236           ms/op
ClientGrpc.getUser                        sample  322055   2.979 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.544           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.898           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.761           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  253721   3.783 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.938           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.177           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.124           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.053           ms/op
