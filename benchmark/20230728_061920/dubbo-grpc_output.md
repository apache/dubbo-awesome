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
# Warmup Iteration   1: 2.126 ops/ms
# Warmup Iteration   2: 5.208 ops/ms
# Warmup Iteration   3: 6.520 ops/ms
Iteration   1: 6.770 ops/ms
Iteration   2: 7.046 ops/ms
Iteration   3: 7.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.011 ±(99.9%) 4.110 ops/ms [Average]
  (min, avg, max) = (6.770, 7.011, 7.216), stdev = 0.225
  CI (99.9%): [2.900, 11.121] (assumes normal distribution)


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
# Warmup Iteration   1: 4.626 ops/ms
# Warmup Iteration   2: 7.421 ops/ms
# Warmup Iteration   3: 8.134 ops/ms
Iteration   1: 8.357 ops/ms
Iteration   2: 8.458 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.418 ±(99.9%) 0.984 ops/ms [Average]
  (min, avg, max) = (8.357, 8.418, 8.458), stdev = 0.054
  CI (99.9%): [7.434, 9.402] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.413 ops/ms
# Warmup Iteration   2: 7.194 ops/ms
# Warmup Iteration   3: 7.403 ops/ms
Iteration   1: 7.131 ops/ms
Iteration   2: 7.521 ops/ms
Iteration   3: 7.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.391 ±(99.9%) 4.104 ops/ms [Average]
  (min, avg, max) = (7.131, 7.391, 7.522), stdev = 0.225
  CI (99.9%): [3.287, 11.495] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ops/ms
# Warmup Iteration   2: 5.139 ops/ms
# Warmup Iteration   3: 5.542 ops/ms
Iteration   1: 5.778 ops/ms
Iteration   2: 5.680 ops/ms
Iteration   3: 6.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.823 ±(99.9%) 3.101 ops/ms [Average]
  (min, avg, max) = (5.680, 5.823, 6.011), stdev = 0.170
  CI (99.9%): [2.722, 8.925] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.260 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.506 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.003 ms/op
Iteration   1: 4.248 ±(99.9%) 0.003 ms/op
Iteration   2: 4.219 ±(99.9%) 0.001 ms/op
Iteration   3: 4.142 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.203 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (4.142, 4.203, 4.248), stdev = 0.055
  CI (99.9%): [3.207, 5.199] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.762 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.004 ms/op
Iteration   1: 4.315 ±(99.9%) 0.002 ms/op
Iteration   2: 4.416 ±(99.9%) 0.002 ms/op
Iteration   3: 4.356 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.362 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (4.315, 4.362, 4.416), stdev = 0.051
  CI (99.9%): [3.436, 5.288] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.784 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.880 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.636 ±(99.9%) 0.004 ms/op
Iteration   1: 4.324 ±(99.9%) 0.002 ms/op
Iteration   2: 4.138 ±(99.9%) 0.004 ms/op
Iteration   3: 4.185 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.216 ±(99.9%) 1.771 ms/op [Average]
  (min, avg, max) = (4.138, 4.216, 4.324), stdev = 0.097
  CI (99.9%): [2.444, 5.987] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.327 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.982 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.779 ±(99.9%) 0.022 ms/op
Iteration   1: 5.566 ±(99.9%) 0.015 ms/op
Iteration   2: 5.167 ±(99.9%) 0.008 ms/op
Iteration   3: 5.257 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.330 ±(99.9%) 3.817 ms/op [Average]
  (min, avg, max) = (5.167, 5.330, 5.566), stdev = 0.209
  CI (99.9%): [1.513, 9.147] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.540 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.011 ms/op
Iteration   1: 3.975 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  9.244 ms/op
                 createUser·p0.9999: 15.679 ms/op
                 createUser·p1.00:   16.220 ms/op

Iteration   2: 4.091 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   7.015 ms/op
                 createUser·p0.999:  14.751 ms/op
                 createUser·p0.9999: 19.011 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  15.042 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 238270
  mean =      4.026 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4300 
    [ 2.500,  5.000) = 211096 
    [ 5.000,  7.500) = 21679 
    [ 7.500, 10.000) = 792 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     12.455 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 6.167 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.012 ms/op
Iteration   1: 3.974 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   4.850 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   6.366 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 17.524 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   2: 3.980 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   4.850 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  10.051 ms/op
                 existUser·p0.9999: 18.021 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   3: 3.920 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  13.004 ms/op
                 existUser·p0.9999: 32.533 ms/op
                 existUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242426
  mean =      3.958 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3369 
    [ 2.500,  5.000) = 220724 
    [ 5.000,  7.500) = 17238 
    [ 7.500, 10.000) = 731 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     12.117 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     32.904 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 6.460 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.540 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.012 ms/op
Iteration   1: 4.079 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  11.210 ms/op
                 getUser·p0.9999: 25.564 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   2: 4.035 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  11.661 ms/op
                 getUser·p0.9999: 21.337 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   3: 4.020 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  13.098 ms/op
                 getUser·p0.9999: 23.171 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237217
  mean =      4.044 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3969 
    [ 2.500,  5.000) = 207420 
    [ 5.000,  7.500) = 24347 
    [ 7.500, 10.000) = 968 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     24.683 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 8.305 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.916 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.367 ±(99.9%) 0.020 ms/op
Iteration   1: 5.384 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   7.938 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  18.708 ms/op
                 listUser·p0.9999: 27.384 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   2: 5.426 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   8.156 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 22.701 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 5.513 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.339 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  21.364 ms/op
                 listUser·p0.9999: 26.876 ms/op
                 listUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176556
  mean =      5.440 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183 
    [ 2.500,  5.000) = 76080 
    [ 5.000,  7.500) = 86204 
    [ 7.500, 10.000) = 11693 
    [10.000, 12.500) = 1775 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     19.872 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     29.408 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.011 ± 4.110  ops/ms
ClientGrpc.existUser                       thrpt       3   8.418 ± 0.984  ops/ms
ClientGrpc.getUser                         thrpt       3   7.391 ± 4.104  ops/ms
ClientGrpc.listUser                        thrpt       3   5.823 ± 3.101  ops/ms
ClientGrpc.createUser                       avgt       3   4.203 ± 0.996   ms/op
ClientGrpc.existUser                        avgt       3   4.362 ± 0.926   ms/op
ClientGrpc.getUser                          avgt       3   4.216 ± 1.771   ms/op
ClientGrpc.listUser                         avgt       3   5.330 ± 3.817   ms/op
ClientGrpc.createUser                     sample  238270   4.026 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.949           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.981           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.439           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.455           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.873           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.298           ms/op
ClientGrpc.existUser                      sample  242426   3.958 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.754           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.858           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.210           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.324           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.117           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.113           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.932           ms/op
ClientGrpc.getUser                        sample  237217   4.044 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.836           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.054           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.767           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.878           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.683           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.919           ms/op
ClientGrpc.listUser                       sample  176556   5.440 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.630           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.159           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.437           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.872           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.706           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.064           ms/op
