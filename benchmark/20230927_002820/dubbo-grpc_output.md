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
# Warmup Iteration   1: 4.782 ops/ms
# Warmup Iteration   2: 8.944 ops/ms
# Warmup Iteration   3: 10.115 ops/ms
Iteration   1: 10.283 ops/ms
Iteration   2: 10.288 ops/ms
Iteration   3: 10.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.301 ±(99.9%) 0.471 ops/ms [Average]
  (min, avg, max) = (10.283, 10.301, 10.330), stdev = 0.026
  CI (99.9%): [9.829, 10.772] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.572 ops/ms
# Warmup Iteration   2: 10.640 ops/ms
# Warmup Iteration   3: 10.811 ops/ms
Iteration   1: 10.909 ops/ms
Iteration   2: 11.109 ops/ms
Iteration   3: 10.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.950 ±(99.9%) 2.596 ops/ms [Average]
  (min, avg, max) = (10.833, 10.950, 11.109), stdev = 0.142
  CI (99.9%): [8.354, 13.547] (assumes normal distribution)


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
# Warmup Iteration   1: 7.305 ops/ms
# Warmup Iteration   2: 10.017 ops/ms
# Warmup Iteration   3: 10.441 ops/ms
Iteration   1: 10.367 ops/ms
Iteration   2: 10.280 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.415 ±(99.9%) 2.990 ops/ms [Average]
  (min, avg, max) = (10.280, 10.415, 10.597), stdev = 0.164
  CI (99.9%): [7.425, 13.404] (assumes normal distribution)


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
# Warmup Iteration   1: 5.787 ops/ms
# Warmup Iteration   2: 8.044 ops/ms
# Warmup Iteration   3: 8.234 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 9.003 ops/ms
Iteration   3: 8.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.528 ±(99.9%) 7.502 ops/ms [Average]
  (min, avg, max) = (8.287, 8.528, 9.003), stdev = 0.411
  CI (99.9%): [1.025, 16.030] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.002 ms/op
Iteration   1: 3.156 ±(99.9%) 0.002 ms/op
Iteration   2: 3.204 ±(99.9%) 0.001 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.165 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (3.135, 3.165, 3.204), stdev = 0.036
  CI (99.9%): [2.513, 3.817] (assumes normal distribution)


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.001 ms/op
Iteration   1: 2.932 ±(99.9%) 0.003 ms/op
Iteration   2: 2.922 ±(99.9%) 0.002 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.942 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (2.922, 2.942, 2.974), stdev = 0.028
  CI (99.9%): [2.438, 3.446] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.003 ms/op
Iteration   1: 3.095 ±(99.9%) 0.003 ms/op
Iteration   2: 3.068 ±(99.9%) 0.001 ms/op
Iteration   3: 3.079 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.080 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (3.068, 3.080, 3.095), stdev = 0.013
  CI (99.9%): [2.835, 3.326] (assumes normal distribution)


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
# Warmup Iteration   1: 5.217 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.034 ms/op
Iteration   1: 3.877 ±(99.9%) 0.025 ms/op
Iteration   2: 3.867 ±(99.9%) 0.021 ms/op
Iteration   3: 3.871 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.872 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (3.867, 3.872, 3.877), stdev = 0.005
  CI (99.9%): [3.783, 3.960] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.005 ms/op
Iteration   1: 3.102 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.221 ms/op
                 createUser·p0.9999: 10.988 ms/op
                 createUser·p1.00:   13.058 ms/op

Iteration   2: 3.146 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.355 ms/op
                 createUser·p0.999:  8.371 ms/op
                 createUser·p0.9999: 12.525 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  10.551 ms/op
                 createUser·p0.9999: 15.677 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307391
  mean =      3.124 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 354 
    [ 1.250,  2.500) = 9436 
    [ 2.500,  3.750) = 275098 
    [ 3.750,  5.000) = 20736 
    [ 5.000,  6.250) = 982 
    [ 6.250,  7.500) = 315 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.457 ms/op
     p(99.9000) =      8.812 ms/op
     p(99.9900) =     14.902 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.005 ms/op
Iteration   1: 3.011 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  7.981 ms/op
                 existUser·p0.9999: 11.110 ms/op
                 existUser·p1.00:   11.469 ms/op

Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  9.235 ms/op
                 existUser·p0.9999: 14.513 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.973 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.168 ms/op
                 existUser·p0.999:  6.345 ms/op
                 existUser·p0.9999: 12.468 ms/op
                 existUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320191
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 734 
    [ 1.250,  2.500) = 17164 
    [ 2.500,  3.750) = 291792 
    [ 3.750,  5.000) = 9029 
    [ 5.000,  6.250) = 816 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.879 ms/op
     p(99.9900) =     13.967 ms/op
     p(99.9990) =     14.710 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.686 ms/op
                 getUser·p0.9999: 15.595 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 16.658 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.967 ms/op
                 getUser·p0.9999: 18.973 ms/op
                 getUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309224
  mean =      3.103 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 635 
    [ 1.250,  2.500) = 9091 
    [ 2.500,  3.750) = 279963 
    [ 3.750,  5.000) = 18049 
    [ 5.000,  6.250) = 833 
    [ 6.250,  7.500) = 306 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.928 ms/op
     p(99.9900) =     17.697 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.009 ms/op
Iteration   1: 3.812 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.482 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  12.665 ms/op
                 listUser·p0.9999: 15.660 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 3.871 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  12.177 ms/op
                 listUser·p0.9999: 14.386 ms/op
                 listUser·p1.00:   14.991 ms/op

Iteration   3: 3.796 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  14.233 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251085
  mean =      3.826 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1812 
    [ 2.500,  5.000) = 238074 
    [ 5.000,  7.500) = 10249 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     12.808 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     21.412 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.301 ± 0.471  ops/ms
ClientGrpc.existUser                       thrpt       3  10.950 ± 2.596  ops/ms
ClientGrpc.getUser                         thrpt       3  10.415 ± 2.990  ops/ms
ClientGrpc.listUser                        thrpt       3   8.528 ± 7.502  ops/ms
ClientGrpc.createUser                       avgt       3   3.165 ± 0.652   ms/op
ClientGrpc.existUser                        avgt       3   2.942 ± 0.504   ms/op
ClientGrpc.getUser                          avgt       3   3.080 ± 0.246   ms/op
ClientGrpc.listUser                         avgt       3   3.872 ± 0.088   ms/op
ClientGrpc.createUser                     sample  307391   3.124 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.815           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.457           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.902           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.974           ms/op
ClientGrpc.existUser                      sample  320191   2.999 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.717           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.879           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.967           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.746           ms/op
ClientGrpc.getUser                        sample  309224   3.103 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.690           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.928           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.697           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.694           ms/op
ClientGrpc.listUser                       sample  251085   3.826 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.482           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.808           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.203           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.020           ms/op
