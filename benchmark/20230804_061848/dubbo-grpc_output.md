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
# Warmup Iteration   1: 4.788 ops/ms
# Warmup Iteration   2: 9.149 ops/ms
# Warmup Iteration   3: 10.573 ops/ms
Iteration   1: 10.806 ops/ms
Iteration   2: 10.673 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.740 ±(99.9%) 1.209 ops/ms [Average]
  (min, avg, max) = (10.673, 10.740, 10.806), stdev = 0.066
  CI (99.9%): [9.530, 11.949] (assumes normal distribution)


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
# Warmup Iteration   1: 8.005 ops/ms
# Warmup Iteration   2: 10.965 ops/ms
# Warmup Iteration   3: 11.218 ops/ms
Iteration   1: 11.630 ops/ms
Iteration   2: 11.391 ops/ms
Iteration   3: 11.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.459 ±(99.9%) 2.722 ops/ms [Average]
  (min, avg, max) = (11.355, 11.459, 11.630), stdev = 0.149
  CI (99.9%): [8.736, 14.181] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.198 ops/ms
# Warmup Iteration   2: 10.559 ops/ms
# Warmup Iteration   3: 10.657 ops/ms
Iteration   1: 10.848 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.796 ±(99.9%) 1.489 ops/ms [Average]
  (min, avg, max) = (10.702, 10.796, 10.848), stdev = 0.082
  CI (99.9%): [9.307, 12.284] (assumes normal distribution)


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
# Warmup Iteration   1: 5.868 ops/ms
# Warmup Iteration   2: 7.988 ops/ms
# Warmup Iteration   3: 8.245 ops/ms
Iteration   1: 8.307 ops/ms
Iteration   2: 8.310 ops/ms
Iteration   3: 8.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.279 ±(99.9%) 0.941 ops/ms [Average]
  (min, avg, max) = (8.219, 8.279, 8.310), stdev = 0.052
  CI (99.9%): [7.338, 9.219] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.192 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.002 ms/op
Iteration   1: 2.976 ±(99.9%) 0.019 ms/op
Iteration   2: 2.920 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.954 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (2.920, 2.954, 2.976), stdev = 0.030
  CI (99.9%): [2.414, 3.494] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.872 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.003 ms/op
Iteration   1: 2.872 ±(99.9%) 0.004 ms/op
Iteration   2: 2.827 ±(99.9%) 0.003 ms/op
Iteration   3: 2.832 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.844 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (2.827, 2.844, 2.872), stdev = 0.024
  CI (99.9%): [2.398, 3.289] (assumes normal distribution)


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.016 ms/op
Iteration   1: 2.938 ±(99.9%) 0.004 ms/op
Iteration   2: 2.943 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.948 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.938, 2.948, 2.963), stdev = 0.013
  CI (99.9%): [2.707, 3.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.935 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.020 ms/op
Iteration   1: 3.863 ±(99.9%) 0.005 ms/op
Iteration   2: 3.892 ±(99.9%) 0.019 ms/op
Iteration   3: 3.851 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.869 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.851, 3.869, 3.892), stdev = 0.021
  CI (99.9%): [3.482, 4.255] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  7.758 ms/op
                 createUser·p0.9999: 12.326 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   2: 2.981 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.324 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  13.042 ms/op
                 createUser·p0.9999: 15.131 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  11.780 ms/op
                 createUser·p0.9999: 16.777 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321026
  mean =      2.989 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1776 
    [ 1.250,  2.500) = 25677 
    [ 2.500,  3.750) = 279027 
    [ 3.750,  5.000) = 12239 
    [ 5.000,  6.250) = 1144 
    [ 6.250,  7.500) = 606 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.324 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     16.048 ms/op
     p(99.9990) =     17.189 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.921 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.006 ms/op
Iteration   1: 2.800 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.825 ms/op
                 existUser·p0.9999: 13.295 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.825 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  10.532 ms/op
                 existUser·p0.9999: 12.747 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   3: 2.836 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.881 ms/op
                 existUser·p0.9999: 16.773 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340134
  mean =      2.820 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4445 
    [ 1.250,  2.500) = 56053 
    [ 2.500,  3.750) = 269086 
    [ 3.750,  5.000) = 8659 
    [ 5.000,  6.250) = 849 
    [ 6.250,  7.500) = 525 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     14.285 ms/op
     p(99.9990) =     16.895 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  8.623 ms/op
                 getUser·p0.9999: 11.792 ms/op
                 getUser·p1.00:   12.222 ms/op

Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.913 ms/op
                 getUser·p0.9999: 12.800 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   3: 2.978 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.311 ms/op
                 getUser·p0.9999: 13.523 ms/op
                 getUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321371
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1705 
    [ 1.250,  2.500) = 24813 
    [ 2.500,  3.750) = 280045 
    [ 3.750,  5.000) = 12789 
    [ 5.000,  6.250) = 1051 
    [ 6.250,  7.500) = 541 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.873 ms/op
     p(99.9900) =     12.857 ms/op
     p(99.9990) =     14.901 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 4.979 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.010 ms/op
Iteration   1: 3.877 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.788 ms/op
                 listUser·p0.999:  11.852 ms/op
                 listUser·p0.9999: 14.094 ms/op
                 listUser·p1.00:   14.483 ms/op

Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 22.059 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   3: 3.879 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.539 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.689 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246364
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4009 
    [ 2.500,  5.000) = 221073 
    [ 5.000,  7.500) = 19850 
    [ 7.500, 10.000) = 898 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.259 ms/op
     p(99.9900) =     21.311 ms/op
     p(99.9990) =     22.501 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.740 ± 1.209  ops/ms
ClientGrpc.existUser                       thrpt       3  11.459 ± 2.722  ops/ms
ClientGrpc.getUser                         thrpt       3  10.796 ± 1.489  ops/ms
ClientGrpc.listUser                        thrpt       3   8.279 ± 0.941  ops/ms
ClientGrpc.createUser                       avgt       3   2.954 ± 0.540   ms/op
ClientGrpc.existUser                        avgt       3   2.844 ± 0.445   ms/op
ClientGrpc.getUser                          avgt       3   2.948 ± 0.241   ms/op
ClientGrpc.listUser                         avgt       3   3.869 ± 0.386   ms/op
ClientGrpc.createUser                     sample  321026   2.989 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.324           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.191           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.048           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.334           ms/op
ClientGrpc.existUser                      sample  340134   2.820 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.501           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.818           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.277           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.126           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.285           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  321371   2.985 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.541           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.873           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          12.857           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.073           ms/op
ClientGrpc.listUser                       sample  246364   3.898 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.539           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.259           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.311           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.643           ms/op
