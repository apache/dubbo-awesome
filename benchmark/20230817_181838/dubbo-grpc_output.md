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
# Warmup Iteration   1: 2.986 ops/ms
# Warmup Iteration   2: 6.449 ops/ms
# Warmup Iteration   3: 7.737 ops/ms
Iteration   1: 8.242 ops/ms
Iteration   2: 8.300 ops/ms
Iteration   3: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.265 ±(99.9%) 0.556 ops/ms [Average]
  (min, avg, max) = (8.242, 8.265, 8.300), stdev = 0.030
  CI (99.9%): [7.710, 8.821] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.856 ops/ms
# Warmup Iteration   2: 8.072 ops/ms
# Warmup Iteration   3: 8.654 ops/ms
Iteration   1: 9.100 ops/ms
Iteration   2: 9.171 ops/ms
Iteration   3: 9.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.187 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (9.100, 9.187, 9.291), stdev = 0.097
  CI (99.9%): [7.424, 10.950] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 4.967 ops/ms
# Warmup Iteration   2: 7.542 ops/ms
# Warmup Iteration   3: 8.202 ops/ms
Iteration   1: 8.066 ops/ms
Iteration   2: 8.525 ops/ms
Iteration   3: 8.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.264 ±(99.9%) 4.299 ops/ms [Average]
  (min, avg, max) = (8.066, 8.264, 8.525), stdev = 0.236
  CI (99.9%): [3.965, 12.563] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ops/ms
# Warmup Iteration   2: 5.859 ops/ms
# Warmup Iteration   3: 6.217 ops/ms
Iteration   1: 6.270 ops/ms
Iteration   2: 6.174 ops/ms
Iteration   3: 6.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.271 ±(99.9%) 1.769 ops/ms [Average]
  (min, avg, max) = (6.174, 6.271, 6.368), stdev = 0.097
  CI (99.9%): [4.501, 8.040] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.904 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.005 ms/op
Iteration   1: 3.802 ±(99.9%) 0.003 ms/op
Iteration   2: 3.805 ±(99.9%) 0.002 ms/op
Iteration   3: 3.760 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.789 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (3.760, 3.789, 3.805), stdev = 0.025
  CI (99.9%): [3.326, 4.252] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.347 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.002 ms/op
Iteration   1: 3.446 ±(99.9%) 0.003 ms/op
Iteration   2: 3.536 ±(99.9%) 0.002 ms/op
Iteration   3: 3.684 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.555 ±(99.9%) 2.193 ms/op [Average]
  (min, avg, max) = (3.446, 3.555, 3.684), stdev = 0.120
  CI (99.9%): [1.363, 5.748] (assumes normal distribution)


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
# Warmup Iteration   1: 5.864 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.854 ±(99.9%) 0.003 ms/op
Iteration   2: 3.865 ±(99.9%) 0.003 ms/op
Iteration   3: 3.871 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.863 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (3.854, 3.863, 3.871), stdev = 0.009
  CI (99.9%): [3.703, 4.024] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.371 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.587 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.154 ±(99.9%) 0.014 ms/op
Iteration   1: 5.119 ±(99.9%) 0.015 ms/op
Iteration   2: 5.099 ±(99.9%) 0.013 ms/op
Iteration   3: 5.083 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.100 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (5.083, 5.100, 5.119), stdev = 0.018
  CI (99.9%): [4.773, 5.427] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.796 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.013 ms/op
Iteration   1: 4.033 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  12.112 ms/op
                 createUser·p0.9999: 23.729 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   2: 3.980 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  10.212 ms/op
                 createUser·p0.9999: 28.371 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 4.007 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  12.141 ms/op
                 createUser·p0.9999: 27.756 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239442
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4602 
    [ 2.500,  5.000) = 209859 
    [ 5.000,  7.500) = 23630 
    [ 7.500, 10.000) = 842 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.665 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     27.754 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 5.071 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.010 ms/op
Iteration   1: 3.536 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.019 ms/op
                 existUser·p0.999:  9.168 ms/op
                 existUser·p0.9999: 17.235 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 3.561 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   3: 3.732 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 18.495 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265943
  mean =      3.607 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12502 
    [ 2.500,  5.000) = 241899 
    [ 5.000,  7.500) = 10052 
    [ 7.500, 10.000) = 1026 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.866 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.010 ms/op
Iteration   1: 4.042 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   6.503 ms/op
                 getUser·p0.999:  9.057 ms/op
                 getUser·p0.9999: 15.895 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   2: 3.940 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  9.224 ms/op
                 getUser·p0.9999: 18.597 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 3.908 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   7.336 ms/op
                 getUser·p0.999:  13.652 ms/op
                 getUser·p0.9999: 20.414 ms/op
                 getUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 242210
  mean =      3.962 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9509 
    [ 2.500,  5.000) = 209515 
    [ 5.000,  7.500) = 21736 
    [ 7.500, 10.000) = 1067 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     11.482 ms/op
     p(99.9900) =     18.583 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 7.633 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.504 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.169 ±(99.9%) 0.018 ms/op
Iteration   1: 5.133 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.784 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   9.437 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 22.471 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 5.038 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.504 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  17.140 ms/op
                 listUser·p0.9999: 20.741 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 5.235 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 26.961 ms/op
                 listUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186936
  mean =      5.134 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 146 
    [ 2.500,  5.000) = 100698 
    [ 5.000,  7.500) = 77896 
    [ 7.500, 10.000) = 6669 
    [10.000, 12.500) = 927 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     22.358 ms/op
     p(99.9990) =     27.706 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.265 ± 0.556  ops/ms
ClientGrpc.existUser                       thrpt       3   9.187 ± 1.763  ops/ms
ClientGrpc.getUser                         thrpt       3   8.264 ± 4.299  ops/ms
ClientGrpc.listUser                        thrpt       3   6.271 ± 1.769  ops/ms
ClientGrpc.createUser                       avgt       3   3.789 ± 0.463   ms/op
ClientGrpc.existUser                        avgt       3   3.555 ± 2.193   ms/op
ClientGrpc.getUser                          avgt       3   3.863 ± 0.160   ms/op
ClientGrpc.listUser                         avgt       3   5.100 ± 0.327   ms/op
ClientGrpc.createUser                     sample  239442   4.006 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.793           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.030           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.665           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.436           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.754           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.606           ms/op
ClientGrpc.existUser                      sample  265943   3.607 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.596           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.332           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.190           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.711           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.283           ms/op
ClientGrpc.getUser                        sample  242210   3.962 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.761           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.973           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.399           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.758           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.482           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.583           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.644           ms/op
ClientGrpc.listUser                       sample  186936   5.134 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.200           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.480           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.634           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.629           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.358           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.820           ms/op
