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
# Warmup Iteration   1: 3.835 ops/ms
# Warmup Iteration   2: 8.913 ops/ms
# Warmup Iteration   3: 9.662 ops/ms
Iteration   1: 10.541 ops/ms
Iteration   2: 10.337 ops/ms
Iteration   3: 10.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.431 ±(99.9%) 1.877 ops/ms [Average]
  (min, avg, max) = (10.337, 10.431, 10.541), stdev = 0.103
  CI (99.9%): [8.554, 12.309] (assumes normal distribution)


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
# Warmup Iteration   1: 7.381 ops/ms
# Warmup Iteration   2: 10.258 ops/ms
# Warmup Iteration   3: 11.079 ops/ms
Iteration   1: 11.028 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 11.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.900 ±(99.9%) 4.790 ops/ms [Average]
  (min, avg, max) = (10.598, 10.900, 11.074), stdev = 0.263
  CI (99.9%): [6.109, 15.690] (assumes normal distribution)


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
# Warmup Iteration   1: 6.697 ops/ms
# Warmup Iteration   2: 9.764 ops/ms
# Warmup Iteration   3: 10.354 ops/ms
Iteration   1: 10.386 ops/ms
Iteration   2: 10.346 ops/ms
Iteration   3: 10.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.385 ±(99.9%) 0.707 ops/ms [Average]
  (min, avg, max) = (10.346, 10.385, 10.423), stdev = 0.039
  CI (99.9%): [9.678, 11.092] (assumes normal distribution)


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
# Warmup Iteration   1: 5.467 ops/ms
# Warmup Iteration   2: 7.585 ops/ms
# Warmup Iteration   3: 8.030 ops/ms
Iteration   1: 8.108 ops/ms
Iteration   2: 7.954 ops/ms
Iteration   3: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.050 ±(99.9%) 1.530 ops/ms [Average]
  (min, avg, max) = (7.954, 8.050, 8.108), stdev = 0.084
  CI (99.9%): [6.520, 9.580] (assumes normal distribution)


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
# Warmup Iteration   1: 4.257 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.002 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 3.073 ±(99.9%) 0.002 ms/op
Iteration   3: 3.046 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.059 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (3.046, 3.059, 3.073), stdev = 0.014
  CI (99.9%): [2.806, 3.313] (assumes normal distribution)


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.003 ms/op
Iteration   1: 2.902 ±(99.9%) 0.004 ms/op
Iteration   2: 2.818 ±(99.9%) 0.002 ms/op
Iteration   3: 2.914 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.878 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (2.818, 2.878, 2.914), stdev = 0.052
  CI (99.9%): [1.925, 3.831] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.004 ms/op
Iteration   1: 3.052 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.002 ms/op
Iteration   3: 3.103 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.078 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.052, 3.078, 3.103), stdev = 0.026
  CI (99.9%): [2.606, 3.550] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.698 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.023 ms/op
Iteration   1: 4.003 ±(99.9%) 0.010 ms/op
Iteration   2: 3.950 ±(99.9%) 0.022 ms/op
Iteration   3: 3.963 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.972 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.950, 3.972, 4.003), stdev = 0.028
  CI (99.9%): [3.468, 4.476] (assumes normal distribution)


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
# Warmup Iteration   1: 4.440 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.108 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.184 ms/op
                 createUser·p0.9999: 14.507 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.185 ms/op
                 createUser·p0.9999: 16.915 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  6.554 ms/op
                 createUser·p0.9999: 24.805 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309939
  mean =      3.098 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16071 
    [ 2.500,  5.000) = 292031 
    [ 5.000,  7.500) = 1610 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     24.118 ms/op
     p(99.9990) =     26.504 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.005 ms/op
Iteration   1: 2.941 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  7.545 ms/op
                 existUser·p0.9999: 13.062 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   2: 2.950 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  6.750 ms/op
                 existUser·p0.9999: 14.303 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   3: 2.820 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  11.811 ms/op
                 existUser·p0.9999: 14.898 ms/op
                 existUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330701
  mean =      2.902 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 667 
    [ 1.250,  2.500) = 42873 
    [ 2.500,  3.750) = 279137 
    [ 3.750,  5.000) = 7114 
    [ 5.000,  6.250) = 286 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      7.768 ms/op
     p(99.9900) =     14.500 ms/op
     p(99.9990) =     15.380 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  10.010 ms/op
                 getUser·p0.9999: 14.489 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.810 ms/op
                 getUser·p0.9999: 15.033 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 3.054 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.052 ms/op
                 getUser·p0.9999: 21.251 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314934
  mean =      3.046 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15724 
    [ 2.500,  5.000) = 298082 
    [ 5.000,  7.500) = 815 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.496 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     21.425 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 5.153 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.012 ms/op
Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.898 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 3.984 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  17.130 ms/op
                 listUser·p0.9999: 26.410 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   3: 3.962 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  17.279 ms/op
                 listUser·p0.9999: 23.656 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243839
  mean =      3.934 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3622 
    [ 2.500,  5.000) = 218238 
    [ 5.000,  7.500) = 20476 
    [ 7.500, 10.000) = 1030 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     16.567 ms/op
     p(99.9900) =     25.456 ms/op
     p(99.9990) =     26.806 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.431 ± 1.877  ops/ms
ClientGrpc.existUser                       thrpt       3  10.900 ± 4.790  ops/ms
ClientGrpc.getUser                         thrpt       3  10.385 ± 0.707  ops/ms
ClientGrpc.listUser                        thrpt       3   8.050 ± 1.530  ops/ms
ClientGrpc.createUser                       avgt       3   3.059 ± 0.254   ms/op
ClientGrpc.existUser                        avgt       3   2.878 ± 0.953   ms/op
ClientGrpc.getUser                          avgt       3   3.078 ± 0.472   ms/op
ClientGrpc.listUser                         avgt       3   3.972 ± 0.504   ms/op
ClientGrpc.createUser                     sample  309939   3.098 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.862           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.102           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.118           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.706           ms/op
ClientGrpc.existUser                      sample  330701   2.902 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.750           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.768           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.500           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.401           ms/op
ClientGrpc.getUser                        sample  314934   3.046 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.544           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.496           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.480           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.594           ms/op
ClientGrpc.listUser                       sample  243839   3.934 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.094           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.567           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.456           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
