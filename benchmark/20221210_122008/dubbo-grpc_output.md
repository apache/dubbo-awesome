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
# Warmup Iteration   1: 4.565 ops/ms
# Warmup Iteration   2: 9.463 ops/ms
# Warmup Iteration   3: 10.007 ops/ms
Iteration   1: 10.318 ops/ms
Iteration   2: 10.075 ops/ms
Iteration   3: 9.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.073 ±(99.9%) 4.502 ops/ms [Average]
  (min, avg, max) = (9.825, 10.073, 10.318), stdev = 0.247
  CI (99.9%): [5.571, 14.575] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.855 ops/ms
# Warmup Iteration   2: 10.246 ops/ms
# Warmup Iteration   3: 10.285 ops/ms
Iteration   1: 10.775 ops/ms
Iteration   2: 10.541 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.605 ±(99.9%) 2.717 ops/ms [Average]
  (min, avg, max) = (10.498, 10.605, 10.775), stdev = 0.149
  CI (99.9%): [7.887, 13.322] (assumes normal distribution)


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
# Warmup Iteration   1: 7.369 ops/ms
# Warmup Iteration   2: 10.363 ops/ms
# Warmup Iteration   3: 10.216 ops/ms
Iteration   1: 10.157 ops/ms
Iteration   2: 10.099 ops/ms
Iteration   3: 10.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.212 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (10.099, 10.212, 10.380), stdev = 0.148
  CI (99.9%): [7.508, 12.916] (assumes normal distribution)


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
# Warmup Iteration   1: 6.756 ops/ms
# Warmup Iteration   2: 7.189 ops/ms
# Warmup Iteration   3: 7.611 ops/ms
Iteration   1: 7.943 ops/ms
Iteration   2: 7.810 ops/ms
Iteration   3: 7.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.859 ±(99.9%) 1.330 ops/ms [Average]
  (min, avg, max) = (7.810, 7.859, 7.943), stdev = 0.073
  CI (99.9%): [6.529, 9.188] (assumes normal distribution)


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.002 ms/op
Iteration   1: 3.156 ±(99.9%) 0.004 ms/op
Iteration   2: 3.226 ±(99.9%) 0.002 ms/op
Iteration   3: 3.187 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.190 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (3.156, 3.190, 3.226), stdev = 0.035
  CI (99.9%): [2.544, 3.835] (assumes normal distribution)


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.003 ms/op
Iteration   1: 3.032 ±(99.9%) 0.004 ms/op
Iteration   2: 2.959 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.030 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (2.959, 3.030, 3.100), stdev = 0.071
  CI (99.9%): [1.738, 4.322] (assumes normal distribution)


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.003 ms/op
Iteration   1: 3.173 ±(99.9%) 0.003 ms/op
Iteration   2: 3.175 ±(99.9%) 0.002 ms/op
Iteration   3: 3.170 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.172 ±(99.9%) 0.044 ms/op [Average]
  (min, avg, max) = (3.170, 3.172, 3.175), stdev = 0.002
  CI (99.9%): [3.129, 3.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.020 ms/op
Iteration   1: 4.111 ±(99.9%) 0.006 ms/op
Iteration   2: 4.196 ±(99.9%) 0.030 ms/op
Iteration   3: 4.134 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.147 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (4.111, 4.147, 4.196), stdev = 0.044
  CI (99.9%): [3.340, 4.953] (assumes normal distribution)


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
Iteration   1: 3.151 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.360 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  9.721 ms/op
                 createUser·p0.9999: 20.010 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  7.676 ms/op
                 createUser·p0.9999: 20.868 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   3: 3.166 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  7.632 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305534
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21750 
    [ 2.500,  5.000) = 281392 
    [ 5.000,  7.500) = 1960 
    [ 7.500, 10.000) = 189 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      8.911 ms/op
     p(99.9900) =     20.953 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.007 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.472 ms/op
                 existUser·p0.9999: 12.202 ms/op
                 existUser·p1.00:   12.435 ms/op

Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  7.849 ms/op
                 existUser·p0.9999: 15.548 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   3: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  8.675 ms/op
                 existUser·p0.9999: 15.867 ms/op
                 existUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316612
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2288 
    [ 1.250,  2.500) = 34655 
    [ 2.500,  3.750) = 255267 
    [ 3.750,  5.000) = 22743 
    [ 5.000,  6.250) = 1037 
    [ 6.250,  7.500) = 299 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 73 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.537 ms/op
     p(99.9900) =     15.647 ms/op
     p(99.9990) =     15.999 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.006 ms/op
Iteration   1: 3.226 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  8.756 ms/op
                 getUser·p0.9999: 16.535 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   2: 3.267 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.651 ms/op
                 getUser·p0.9999: 14.005 ms/op
                 getUser·p1.00:   15.761 ms/op

Iteration   3: 3.161 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.041 ms/op
                 getUser·p0.9999: 14.393 ms/op
                 getUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298622
  mean =      3.218 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1020 
    [ 1.250,  2.500) = 16297 
    [ 2.500,  3.750) = 234216 
    [ 3.750,  5.000) = 44977 
    [ 5.000,  6.250) = 1347 
    [ 6.250,  7.500) = 396 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      8.010 ms/op
     p(99.9900) =     14.603 ms/op
     p(99.9990) =     16.942 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 5.152 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.011 ms/op
Iteration   1: 4.236 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  13.819 ms/op
                 listUser·p0.9999: 16.209 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 4.316 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  16.361 ms/op
                 listUser·p0.9999: 24.045 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   3: 4.258 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.579 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  20.185 ms/op
                 listUser·p0.9999: 24.280 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 224723
  mean =      4.270 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4177 
    [ 2.500,  5.000) = 173275 
    [ 5.000,  7.500) = 44450 
    [ 7.500, 10.000) = 2160 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     26.845 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.073 ± 4.502  ops/ms
ClientGrpc.existUser                       thrpt       3  10.605 ± 2.717  ops/ms
ClientGrpc.getUser                         thrpt       3  10.212 ± 2.704  ops/ms
ClientGrpc.listUser                        thrpt       3   7.859 ± 1.330  ops/ms
ClientGrpc.createUser                       avgt       3   3.190 ± 0.645   ms/op
ClientGrpc.existUser                        avgt       3   3.030 ± 1.292   ms/op
ClientGrpc.getUser                          avgt       3   3.172 ± 0.044   ms/op
ClientGrpc.listUser                         avgt       3   4.147 ± 0.807   ms/op
ClientGrpc.createUser                     sample  305534   3.145 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.360           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.911           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.953           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  316612   3.033 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.629           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.537           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.647           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.024           ms/op
ClientGrpc.getUser                        sample  298622   3.218 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.722           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.187           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.112           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.010           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.603           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.072           ms/op
ClientGrpc.listUser                       sample  224723   4.270 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.579           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.022           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.185           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.953           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.165           ms/op
