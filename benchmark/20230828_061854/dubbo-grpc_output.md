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
# Warmup Iteration   1: 3.675 ops/ms
# Warmup Iteration   2: 7.794 ops/ms
# Warmup Iteration   3: 9.482 ops/ms
Iteration   1: 9.871 ops/ms
Iteration   2: 10.103 ops/ms
Iteration   3: 10.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.022 ±(99.9%) 2.390 ops/ms [Average]
  (min, avg, max) = (9.871, 10.022, 10.103), stdev = 0.131
  CI (99.9%): [7.631, 12.412] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.408 ops/ms
# Warmup Iteration   2: 10.141 ops/ms
# Warmup Iteration   3: 10.595 ops/ms
Iteration   1: 10.846 ops/ms
Iteration   2: 10.783 ops/ms
Iteration   3: 10.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.811 ±(99.9%) 0.584 ops/ms [Average]
  (min, avg, max) = (10.783, 10.811, 10.846), stdev = 0.032
  CI (99.9%): [10.227, 11.395] (assumes normal distribution)


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
# Warmup Iteration   1: 6.191 ops/ms
# Warmup Iteration   2: 9.679 ops/ms
# Warmup Iteration   3: 9.712 ops/ms
Iteration   1: 10.245 ops/ms
Iteration   2: 10.150 ops/ms
Iteration   3: 10.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.205 ±(99.9%) 0.906 ops/ms [Average]
  (min, avg, max) = (10.150, 10.205, 10.245), stdev = 0.050
  CI (99.9%): [9.299, 11.111] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.659 ops/ms
# Warmup Iteration   2: 7.330 ops/ms
# Warmup Iteration   3: 7.748 ops/ms
Iteration   1: 7.811 ops/ms
Iteration   2: 7.778 ops/ms
Iteration   3: 7.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.762 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (7.698, 7.762, 7.811), stdev = 0.058
  CI (99.9%): [6.699, 8.826] (assumes normal distribution)


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.003 ms/op
Iteration   1: 3.110 ±(99.9%) 0.004 ms/op
Iteration   2: 3.090 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.059, 3.086, 3.110), stdev = 0.026
  CI (99.9%): [2.611, 3.561] (assumes normal distribution)


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.003 ms/op
Iteration   1: 2.950 ±(99.9%) 0.003 ms/op
Iteration   2: 2.884 ±(99.9%) 0.003 ms/op
Iteration   3: 2.908 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (2.884, 2.914, 2.950), stdev = 0.033
  CI (99.9%): [2.312, 3.516] (assumes normal distribution)


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
# Warmup Iteration   1: 4.302 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.056 ±(99.9%) 0.003 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.073 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.049, 3.073, 3.115), stdev = 0.036
  CI (99.9%): [2.412, 3.734] (assumes normal distribution)


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
# Warmup Iteration   1: 5.590 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.023 ms/op
Iteration   1: 4.034 ±(99.9%) 0.025 ms/op
Iteration   2: 4.042 ±(99.9%) 0.030 ms/op
Iteration   3: 4.092 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.056 ±(99.9%) 0.573 ms/op [Average]
  (min, avg, max) = (4.034, 4.056, 4.092), stdev = 0.031
  CI (99.9%): [3.483, 4.630] (assumes normal distribution)


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.008 ms/op
Iteration   1: 3.143 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 18.737 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   2: 3.142 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  10.224 ms/op
                 createUser·p0.9999: 25.389 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.176 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  12.075 ms/op
                 createUser·p0.9999: 26.706 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304608
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13737 
    [ 2.500,  5.000) = 288802 
    [ 5.000,  7.500) = 1300 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =     10.623 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  10.879 ms/op
                 existUser·p0.9999: 14.530 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.733 ms/op
                 existUser·p0.9999: 14.880 ms/op
                 existUser·p1.00:   15.466 ms/op

Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  10.603 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320379
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1029 
    [ 1.250,  2.500) = 28265 
    [ 2.500,  3.750) = 276711 
    [ 3.750,  5.000) = 12305 
    [ 5.000,  6.250) = 992 
    [ 6.250,  7.500) = 275 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 171 
    [10.000, 11.250) = 185 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     18.428 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.509 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.105 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 14.256 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  7.781 ms/op
                 getUser·p0.9999: 16.293 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.805 ms/op
                 getUser·p0.9999: 19.377 ms/op
                 getUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312137
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 732 
    [ 1.250,  2.500) = 21726 
    [ 2.500,  3.750) = 266307 
    [ 3.750,  5.000) = 20926 
    [ 5.000,  6.250) = 1479 
    [ 6.250,  7.500) = 442 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 139 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =      8.730 ms/op
     p(99.9900) =     18.060 ms/op
     p(99.9990) =     19.920 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 6.046 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.012 ms/op
Iteration   1: 4.049 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.405 ms/op
                 listUser·p0.999:  15.203 ms/op
                 listUser·p0.9999: 16.911 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 4.061 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 18.805 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 4.067 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  17.350 ms/op
                 listUser·p0.9999: 26.088 ms/op
                 listUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236454
  mean =      4.059 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2080 
    [ 2.500,  5.000) = 209487 
    [ 5.000,  7.500) = 22985 
    [ 7.500, 10.000) = 1340 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.295 ms/op
     p(99.9900) =     25.451 ms/op
     p(99.9990) =     26.399 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.022 ± 2.390  ops/ms
ClientGrpc.existUser                       thrpt       3  10.811 ± 0.584  ops/ms
ClientGrpc.getUser                         thrpt       3  10.205 ± 0.906  ops/ms
ClientGrpc.listUser                        thrpt       3   7.762 ± 1.064  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 0.475   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 0.602   ms/op
ClientGrpc.getUser                          avgt       3   3.073 ± 0.661   ms/op
ClientGrpc.listUser                         avgt       3   4.056 ± 0.573   ms/op
ClientGrpc.createUser                     sample  304608   3.154 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.656           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.623           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.411           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.099           ms/op
ClientGrpc.existUser                      sample  320379   2.995 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.635           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.273           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.810           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  312137   3.074 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.578           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.730           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.060           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.988           ms/op
ClientGrpc.listUser                       sample  236454   4.059 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.051           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.295           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.451           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.411           ms/op
