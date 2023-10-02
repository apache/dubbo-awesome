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
# Warmup Iteration   1: 4.368 ops/ms
# Warmup Iteration   2: 8.887 ops/ms
# Warmup Iteration   3: 9.716 ops/ms
Iteration   1: 10.143 ops/ms
Iteration   2: 10.838 ops/ms
Iteration   3: 10.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.378 ±(99.9%) 7.256 ops/ms [Average]
  (min, avg, max) = (10.143, 10.378, 10.838), stdev = 0.398
  CI (99.9%): [3.122, 17.634] (assumes normal distribution)


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
# Warmup Iteration   1: 9.136 ops/ms
# Warmup Iteration   2: 10.387 ops/ms
# Warmup Iteration   3: 10.638 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.728 ±(99.9%) 1.115 ops/ms [Average]
  (min, avg, max) = (10.668, 10.728, 10.791), stdev = 0.061
  CI (99.9%): [9.613, 11.842] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.076 ops/ms
# Warmup Iteration   2: 9.863 ops/ms
# Warmup Iteration   3: 10.012 ops/ms
Iteration   1: 10.231 ops/ms
Iteration   2: 10.103 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.243 ±(99.9%) 2.668 ops/ms [Average]
  (min, avg, max) = (10.103, 10.243, 10.395), stdev = 0.146
  CI (99.9%): [7.574, 12.911] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.511 ops/ms
# Warmup Iteration   2: 7.993 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.303 ops/ms
Iteration   2: 8.289 ops/ms
Iteration   3: 8.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.365 ±(99.9%) 2.165 ops/ms [Average]
  (min, avg, max) = (8.289, 8.365, 8.502), stdev = 0.119
  CI (99.9%): [6.200, 10.530] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.362 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.001 ms/op
Iteration   1: 3.142 ±(99.9%) 0.002 ms/op
Iteration   2: 3.187 ±(99.9%) 0.001 ms/op
Iteration   3: 3.177 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.169 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.142, 3.169, 3.187), stdev = 0.023
  CI (99.9%): [2.742, 3.595] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.689 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.003 ms/op
Iteration   1: 2.979 ±(99.9%) 0.002 ms/op
Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.983 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.975, 2.983, 2.996), stdev = 0.011
  CI (99.9%): [2.788, 3.179] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.127 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.003 ms/op
Iteration   1: 3.151 ±(99.9%) 0.002 ms/op
Iteration   2: 3.157 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.136 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (3.100, 3.136, 3.157), stdev = 0.032
  CI (99.9%): [2.560, 3.712] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.151 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.012 ms/op
Iteration   1: 3.833 ±(99.9%) 0.014 ms/op
Iteration   2: 3.859 ±(99.9%) 0.039 ms/op
Iteration   3: 3.823 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.838 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (3.823, 3.838, 3.859), stdev = 0.019
  CI (99.9%): [3.499, 4.177] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
Iteration   1: 3.164 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 14.988 ms/op
                 createUser·p1.00:   15.417 ms/op

Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  9.243 ms/op
                 createUser·p0.9999: 17.630 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   3: 3.084 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  12.670 ms/op
                 createUser·p0.9999: 28.988 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306633
  mean =      3.130 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13114 
    [ 2.500,  5.000) = 291803 
    [ 5.000,  7.500) = 1267 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =     10.188 ms/op
     p(99.9900) =     22.818 ms/op
     p(99.9990) =     29.194 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.834 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.005 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  6.657 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.398 ms/op
                 existUser·p0.9999: 12.432 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  6.537 ms/op
                 existUser·p0.9999: 14.506 ms/op
                 existUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321319
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2270 
    [ 1.250,  2.500) = 23229 
    [ 2.500,  3.750) = 281363 
    [ 3.750,  5.000) = 13083 
    [ 5.000,  6.250) = 948 
    [ 6.250,  7.500) = 238 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      6.510 ms/op
     p(99.9900) =     14.678 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.005 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 13.296 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 3.134 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.123 ms/op
                 getUser·p0.999:  8.877 ms/op
                 getUser·p0.9999: 12.478 ms/op
                 getUser·p1.00:   12.665 ms/op

Iteration   3: 3.157 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.737 ms/op
                 getUser·p0.999:  8.694 ms/op
                 getUser·p0.9999: 15.640 ms/op
                 getUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306934
  mean =      3.127 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 388 
    [ 1.250,  2.500) = 6138 
    [ 2.500,  3.750) = 283600 
    [ 3.750,  5.000) = 15053 
    [ 5.000,  6.250) = 762 
    [ 6.250,  7.500) = 516 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.423 ms/op
     p(99.9900) =     15.154 ms/op
     p(99.9990) =     15.778 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 4.412 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.009 ms/op
Iteration   1: 3.841 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  11.432 ms/op
                 listUser·p0.9999: 15.134 ms/op
                 listUser·p1.00:   15.958 ms/op

Iteration   2: 3.870 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.477 ms/op
                 listUser·p0.999:  13.113 ms/op
                 listUser·p0.9999: 15.124 ms/op
                 listUser·p1.00:   15.729 ms/op

Iteration   3: 3.870 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  13.800 ms/op
                 listUser·p0.9999: 16.827 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248589
  mean =      3.860 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 5330 
    [ 2.500,  3.750) = 114989 
    [ 3.750,  5.000) = 110521 
    [ 5.000,  6.250) = 12798 
    [ 6.250,  7.500) = 4039 
    [ 7.500,  8.750) = 305 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 137 
    [13.750, 15.000) = 88 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     15.958 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.378 ± 7.256  ops/ms
ClientGrpc.existUser                       thrpt       3  10.728 ± 1.115  ops/ms
ClientGrpc.getUser                         thrpt       3  10.243 ± 2.668  ops/ms
ClientGrpc.listUser                        thrpt       3   8.365 ± 2.165  ops/ms
ClientGrpc.createUser                       avgt       3   3.169 ± 0.426   ms/op
ClientGrpc.existUser                        avgt       3   2.983 ± 0.196   ms/op
ClientGrpc.getUser                          avgt       3   3.136 ± 0.576   ms/op
ClientGrpc.listUser                         avgt       3   3.838 ± 0.339   ms/op
ClientGrpc.createUser                     sample  306633   3.130 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.629           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.188           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.818           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.295           ms/op
ClientGrpc.existUser                      sample  321319   2.986 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.523           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.510           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.678           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.695           ms/op
ClientGrpc.getUser                        sample  306934   3.127 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.651           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.423           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.154           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.860           ms/op
ClientGrpc.listUser                       sample  248589   3.860 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.001           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.960           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.958           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.973           ms/op
