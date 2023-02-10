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
# Warmup Iteration   1: 4.501 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 10.465 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.693 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.598 ±(99.9%) 2.313 ops/ms [Average]
  (min, avg, max) = (10.454, 10.598, 10.693), stdev = 0.127
  CI (99.9%): [8.285, 12.911] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.304 ops/ms
# Warmup Iteration   2: 10.984 ops/ms
# Warmup Iteration   3: 10.914 ops/ms
Iteration   1: 10.727 ops/ms
Iteration   2: 10.737 ops/ms
Iteration   3: 10.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.752 ±(99.9%) 0.637 ops/ms [Average]
  (min, avg, max) = (10.727, 10.752, 10.792), stdev = 0.035
  CI (99.9%): [10.115, 11.389] (assumes normal distribution)


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
# Warmup Iteration   1: 8.206 ops/ms
# Warmup Iteration   2: 10.385 ops/ms
# Warmup Iteration   3: 10.379 ops/ms
Iteration   1: 10.441 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.452 ±(99.9%) 2.598 ops/ms [Average]
  (min, avg, max) = (10.315, 10.452, 10.599), stdev = 0.142
  CI (99.9%): [7.853, 13.050] (assumes normal distribution)


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
# Warmup Iteration   1: 6.651 ops/ms
# Warmup Iteration   2: 7.760 ops/ms
# Warmup Iteration   3: 7.773 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 8.262 ops/ms
Iteration   3: 7.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.077 ±(99.9%) 2.978 ops/ms [Average]
  (min, avg, max) = (7.955, 8.077, 8.262), stdev = 0.163
  CI (99.9%): [5.099, 11.054] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.002 ms/op
Iteration   1: 3.044 ±(99.9%) 0.008 ms/op
Iteration   2: 3.149 ±(99.9%) 0.002 ms/op
Iteration   3: 3.144 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.112 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (3.044, 3.112, 3.149), stdev = 0.059
  CI (99.9%): [2.030, 4.195] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.003 ms/op
Iteration   1: 2.963 ±(99.9%) 0.002 ms/op
Iteration   2: 2.987 ±(99.9%) 0.004 ms/op
Iteration   3: 2.876 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.942 ±(99.9%) 1.067 ms/op [Average]
  (min, avg, max) = (2.876, 2.942, 2.987), stdev = 0.059
  CI (99.9%): [1.875, 4.009] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 3.100 ±(99.9%) 0.004 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.044, 3.071, 3.100), stdev = 0.028
  CI (99.9%): [2.551, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 5.310 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.043 ms/op
Iteration   1: 4.011 ±(99.9%) 0.107 ms/op
Iteration   2: 4.006 ±(99.9%) 0.018 ms/op
Iteration   3: 3.953 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.990 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (3.953, 3.990, 4.011), stdev = 0.032
  CI (99.9%): [3.401, 4.579] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  5.891 ms/op
                 createUser·p0.9999: 12.500 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.322 ms/op
                 createUser·p0.9999: 12.265 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  12.200 ms/op
                 createUser·p0.9999: 14.598 ms/op
                 createUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311060
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1401 
    [ 1.250,  2.500) = 26998 
    [ 2.500,  3.750) = 252406 
    [ 3.750,  5.000) = 29354 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 164 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      9.207 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     15.000 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.748 ms/op
                 existUser·p0.9999: 11.911 ms/op
                 existUser·p1.00:   12.190 ms/op

Iteration   2: 2.913 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  5.809 ms/op
                 existUser·p0.9999: 12.714 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.930 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327769
  mean =      2.929 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52322 
    [ 2.500,  5.000) = 274788 
    [ 5.000,  7.500) = 404 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      6.688 ms/op
     p(99.9900) =     22.486 ms/op
     p(99.9990) =     23.182 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.076 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  11.420 ms/op
                 getUser·p0.9999: 13.062 ms/op
                 getUser·p1.00:   13.435 ms/op

Iteration   2: 3.076 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.020 ms/op
                 getUser·p0.9999: 15.480 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.363 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.051 ms/op
                 getUser·p0.9999: 25.905 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312276
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25973 
    [ 2.500,  5.000) = 285215 
    [ 5.000,  7.500) = 769 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.363 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.634 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     26.239 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 5.360 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.012 ms/op
Iteration   1: 4.174 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.093 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  14.151 ms/op
                 listUser·p0.9999: 18.382 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 4.071 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  17.111 ms/op
                 listUser·p0.9999: 23.396 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 17.081 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234635
  mean =      4.096 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4930 
    [ 2.500,  5.000) = 194676 
    [ 5.000,  7.500) = 33391 
    [ 7.500, 10.000) = 1095 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     22.857 ms/op
     p(99.9990) =     23.636 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.598 ± 2.313  ops/ms
ClientGrpc.existUser                       thrpt       3  10.752 ± 0.637  ops/ms
ClientGrpc.getUser                         thrpt       3  10.452 ± 2.598  ops/ms
ClientGrpc.listUser                        thrpt       3   8.077 ± 2.978  ops/ms
ClientGrpc.createUser                       avgt       3   3.112 ± 1.083   ms/op
ClientGrpc.existUser                        avgt       3   2.942 ± 1.067   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 0.519   ms/op
ClientGrpc.listUser                         avgt       3   3.990 ± 0.589   ms/op
ClientGrpc.createUser                     sample  311060   3.087 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.686           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.207           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          13.550           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.892           ms/op
ClientGrpc.existUser                      sample  327769   2.929 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.636           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.688           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.486           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.265           ms/op
ClientGrpc.getUser                        sample  312276   3.073 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.363           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.634           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.166           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.345           ms/op
ClientGrpc.listUser                       sample  234635   4.096 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.732           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.582           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.857           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.757           ms/op
