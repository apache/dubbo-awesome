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
# Warmup Iteration   1: 4.490 ops/ms
# Warmup Iteration   2: 8.876 ops/ms
# Warmup Iteration   3: 9.972 ops/ms
Iteration   1: 10.599 ops/ms
Iteration   2: 10.172 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.464 ±(99.9%) 4.616 ops/ms [Average]
  (min, avg, max) = (10.172, 10.464, 10.620), stdev = 0.253
  CI (99.9%): [5.848, 15.079] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.084 ops/ms
# Warmup Iteration   2: 10.504 ops/ms
# Warmup Iteration   3: 11.071 ops/ms
Iteration   1: 11.171 ops/ms
Iteration   2: 10.925 ops/ms
Iteration   3: 10.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.009 ±(99.9%) 2.561 ops/ms [Average]
  (min, avg, max) = (10.925, 11.009, 11.171), stdev = 0.140
  CI (99.9%): [8.448, 13.569] (assumes normal distribution)


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
# Warmup Iteration   1: 7.376 ops/ms
# Warmup Iteration   2: 10.064 ops/ms
# Warmup Iteration   3: 10.268 ops/ms
Iteration   1: 10.520 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.593 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (10.520, 10.593, 10.632), stdev = 0.063
  CI (99.9%): [9.438, 11.748] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.073 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 8.290 ops/ms
Iteration   1: 8.077 ops/ms
Iteration   2: 8.082 ops/ms
Iteration   3: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.137 ±(99.9%) 1.807 ops/ms [Average]
  (min, avg, max) = (8.077, 8.137, 8.251), stdev = 0.099
  CI (99.9%): [6.330, 9.944] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.002 ms/op
Iteration   1: 3.095 ±(99.9%) 0.003 ms/op
Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
Iteration   3: 2.959 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 1.326 ms/op [Average]
  (min, avg, max) = (2.959, 3.042, 3.095), stdev = 0.073
  CI (99.9%): [1.716, 4.369] (assumes normal distribution)


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.003 ms/op
Iteration   2: 2.915 ±(99.9%) 0.004 ms/op
Iteration   3: 2.857 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (2.857, 2.894, 2.915), stdev = 0.033
  CI (99.9%): [2.298, 3.490] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.002 ms/op
Iteration   1: 3.030 ±(99.9%) 0.002 ms/op
Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.030, 3.043, 3.067), stdev = 0.021
  CI (99.9%): [2.659, 3.426] (assumes normal distribution)


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
# Warmup Iteration   1: 4.918 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.015 ms/op
Iteration   1: 3.938 ±(99.9%) 0.007 ms/op
Iteration   2: 3.855 ±(99.9%) 0.009 ms/op
Iteration   3: 3.946 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.913 ±(99.9%) 0.918 ms/op [Average]
  (min, avg, max) = (3.855, 3.913, 3.946), stdev = 0.050
  CI (99.9%): [2.995, 4.831] (assumes normal distribution)


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  10.146 ms/op
                 createUser·p0.9999: 22.333 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.485 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  12.168 ms/op
                 createUser·p0.9999: 15.593 ms/op
                 createUser·p1.00:   15.958 ms/op

Iteration   3: 3.114 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.973 ms/op
                 createUser·p0.999:  10.132 ms/op
                 createUser·p0.9999: 26.271 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309134
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21795 
    [ 2.500,  5.000) = 283168 
    [ 5.000,  7.500) = 3503 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     25.472 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.007 ms/op
Iteration   1: 2.851 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  10.467 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.375 ms/op
                 existUser·p0.9999: 14.082 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.485 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.283 ms/op
                 existUser·p0.9999: 16.351 ms/op
                 existUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330920
  mean =      2.900 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3195 
    [ 1.250,  2.500) = 37338 
    [ 2.500,  3.750) = 277912 
    [ 3.750,  5.000) = 10620 
    [ 5.000,  6.250) = 1108 
    [ 6.250,  7.500) = 385 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.079 ms/op
     p(99.9900) =     15.630 ms/op
     p(99.9990) =     16.500 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
Iteration   1: 2.937 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.537 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.372 ms/op
                 getUser·p0.9999: 15.435 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   2: 2.970 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.246 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  9.965 ms/op
                 getUser·p0.9999: 14.228 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  7.561 ms/op
                 getUser·p0.9999: 15.670 ms/op
                 getUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322444
  mean =      2.978 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5147 
    [ 1.250,  2.500) = 44992 
    [ 2.500,  3.750) = 244680 
    [ 3.750,  5.000) = 24858 
    [ 5.000,  6.250) = 1619 
    [ 6.250,  7.500) = 621 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.246 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     15.430 ms/op
     p(99.9990) =     16.431 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 5.323 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.012 ms/op
Iteration   1: 3.999 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  13.058 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   2: 3.997 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.446 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  19.428 ms/op
                 listUser·p0.9999: 24.444 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   3: 3.847 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.167 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243418
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6522 
    [ 2.500,  5.000) = 208267 
    [ 5.000,  7.500) = 26763 
    [ 7.500, 10.000) = 1261 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     23.582 ms/op
     p(99.9990) =     25.685 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.464 ± 4.616  ops/ms
ClientGrpc.existUser                       thrpt       3  11.009 ± 2.561  ops/ms
ClientGrpc.getUser                         thrpt       3  10.593 ± 1.155  ops/ms
ClientGrpc.listUser                        thrpt       3   8.137 ± 1.807  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 1.326   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.596   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.383   ms/op
ClientGrpc.listUser                         avgt       3   3.913 ± 0.918   ms/op
ClientGrpc.createUser                     sample  309134   3.105 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.485           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.567           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.472           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.542           ms/op
ClientGrpc.existUser                      sample  330920   2.900 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.485           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.079           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.630           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.744           ms/op
ClientGrpc.getUser                        sample  322444   2.978 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.246           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.471           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.430           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.793           ms/op
ClientGrpc.listUser                       sample  243418   3.947 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.446           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.155           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.582           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
