# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.929 ops/ms
# Warmup Iteration   2: 8.637 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.364 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 9.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.250 ±(99.9%) 4.734 ops/ms [Average]
  (min, avg, max) = (9.953, 10.250, 10.434), stdev = 0.259
  CI (99.9%): [5.516, 14.984] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.851 ops/ms
# Warmup Iteration   2: 10.463 ops/ms
# Warmup Iteration   3: 10.846 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.524 ops/ms
Iteration   3: 10.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.618 ±(99.9%) 1.502 ops/ms [Average]
  (min, avg, max) = (10.524, 10.618, 10.677), stdev = 0.082
  CI (99.9%): [9.116, 12.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.997 ops/ms
# Warmup Iteration   2: 10.210 ops/ms
# Warmup Iteration   3: 10.232 ops/ms
Iteration   1: 10.290 ops/ms
Iteration   2: 10.195 ops/ms
Iteration   3: 10.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.250 ±(99.9%) 0.897 ops/ms [Average]
  (min, avg, max) = (10.195, 10.250, 10.290), stdev = 0.049
  CI (99.9%): [9.353, 11.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.528 ops/ms
# Warmup Iteration   2: 7.438 ops/ms
# Warmup Iteration   3: 7.846 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 7.784 ops/ms
Iteration   3: 7.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.851 ±(99.9%) 1.131 ops/ms [Average]
  (min, avg, max) = (7.784, 7.851, 7.907), stdev = 0.062
  CI (99.9%): [6.719, 8.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.330 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.002 ms/op
Iteration   1: 3.175 ±(99.9%) 0.004 ms/op
Iteration   2: 3.202 ±(99.9%) 0.002 ms/op
Iteration   3: 3.272 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.216 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (3.175, 3.216, 3.272), stdev = 0.050
  CI (99.9%): [2.301, 4.131] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.002 ms/op
Iteration   1: 2.921 ±(99.9%) 0.004 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 2.968 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (2.921, 2.962, 2.997), stdev = 0.038
  CI (99.9%): [2.261, 3.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.003 ms/op
Iteration   1: 3.131 ±(99.9%) 0.002 ms/op
Iteration   2: 3.168 ±(99.9%) 0.001 ms/op
Iteration   3: 3.118 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.139 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.118, 3.139, 3.168), stdev = 0.026
  CI (99.9%): [2.668, 3.610] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.183 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.014 ms/op
Iteration   1: 4.009 ±(99.9%) 0.009 ms/op
Iteration   2: 4.057 ±(99.9%) 0.022 ms/op
Iteration   3: 4.004 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.023 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (4.004, 4.023, 4.057), stdev = 0.030
  CI (99.9%): [3.481, 4.565] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  6.391 ms/op
                 createUser·p0.9999: 19.059 ms/op
                 createUser·p1.00:   19.595 ms/op

Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.998 ms/op
                 createUser·p0.9999: 19.257 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  11.553 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304372
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25917 
    [ 2.500,  5.000) = 277080 
    [ 5.000,  7.500) = 933 
    [ 7.500, 10.000) = 173 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     20.793 ms/op
     p(99.9990) =     22.051 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.130 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  9.510 ms/op
                 existUser·p0.9999: 15.363 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.725 ms/op
                 existUser·p0.9999: 14.789 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.179 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318793
  mean =      3.011 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49459 
    [ 2.500,  5.000) = 268111 
    [ 5.000,  7.500) = 831 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.009 ms/op
     p(99.9900) =     23.204 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
Iteration   1: 3.194 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  10.232 ms/op
                 getUser·p0.9999: 20.316 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.177 ms/op
                 getUser·p0.9999: 23.036 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.071 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.779 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304241
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22528 
    [ 2.500,  5.000) = 280375 
    [ 5.000,  7.500) = 984 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.254 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     25.588 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.792 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
Iteration   1: 4.068 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.343 ms/op
                 listUser·p0.9999: 17.252 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 4.036 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.639 ms/op
                 listUser·p0.9999: 17.075 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 4.112 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.566 ms/op
                 listUser·p0.9999: 22.061 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235913
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3362 
    [ 2.500,  5.000) = 201292 
    [ 5.000,  7.500) = 29668 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.517 ms/op
     p(99.9900) =     17.290 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.250 ± 4.734  ops/ms
ClientGrpc.existUser                       thrpt       3  10.618 ± 1.502  ops/ms
ClientGrpc.getUser                         thrpt       3  10.250 ± 0.897  ops/ms
ClientGrpc.listUser                        thrpt       3   7.851 ± 1.131  ops/ms
ClientGrpc.createUser                       avgt       3   3.216 ± 0.915   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.701   ms/op
ClientGrpc.getUser                          avgt       3   3.139 ± 0.471   ms/op
ClientGrpc.listUser                         avgt       3   4.023 ± 0.542   ms/op
ClientGrpc.createUser                     sample  304372   3.156 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.599           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.454           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.793           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.184           ms/op
ClientGrpc.existUser                      sample  318793   3.011 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.615           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.903           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.009           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.204           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.231           ms/op
ClientGrpc.getUser                        sample  304241   3.155 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.254           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.478           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.919           ms/op
ClientGrpc.listUser                       sample  235913   4.071 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.887           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.517           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.290           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.774           ms/op
