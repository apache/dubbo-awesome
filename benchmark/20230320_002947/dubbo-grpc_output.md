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
# Warmup Iteration   1: 2.990 ops/ms
# Warmup Iteration   2: 6.643 ops/ms
# Warmup Iteration   3: 7.896 ops/ms
Iteration   1: 8.293 ops/ms
Iteration   2: 8.663 ops/ms
Iteration   3: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.396 ±(99.9%) 4.253 ops/ms [Average]
  (min, avg, max) = (8.232, 8.396, 8.663), stdev = 0.233
  CI (99.9%): [4.143, 12.649] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.311 ops/ms
# Warmup Iteration   2: 8.477 ops/ms
# Warmup Iteration   3: 9.051 ops/ms
Iteration   1: 9.137 ops/ms
Iteration   2: 8.849 ops/ms
Iteration   3: 9.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.030 ±(99.9%) 2.877 ops/ms [Average]
  (min, avg, max) = (8.849, 9.030, 9.137), stdev = 0.158
  CI (99.9%): [6.153, 11.906] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.586 ops/ms
# Warmup Iteration   2: 7.647 ops/ms
# Warmup Iteration   3: 8.404 ops/ms
Iteration   1: 8.563 ops/ms
Iteration   2: 8.282 ops/ms
Iteration   3: 8.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.311 ±(99.9%) 4.337 ops/ms [Average]
  (min, avg, max) = (8.090, 8.311, 8.563), stdev = 0.238
  CI (99.9%): [3.974, 12.649] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ops/ms
# Warmup Iteration   2: 6.047 ops/ms
# Warmup Iteration   3: 6.316 ops/ms
Iteration   1: 6.384 ops/ms
Iteration   2: 6.443 ops/ms
Iteration   3: 6.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.382 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (6.319, 6.382, 6.443), stdev = 0.062
  CI (99.9%): [5.251, 7.514] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.597 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.011 ms/op
Iteration   1: 4.012 ±(99.9%) 0.003 ms/op
Iteration   2: 3.956 ±(99.9%) 0.002 ms/op
Iteration   3: 3.872 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.946 ±(99.9%) 1.284 ms/op [Average]
  (min, avg, max) = (3.872, 3.946, 4.012), stdev = 0.070
  CI (99.9%): [2.662, 5.230] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.003 ms/op
Iteration   1: 3.601 ±(99.9%) 0.003 ms/op
Iteration   2: 3.581 ±(99.9%) 0.003 ms/op
Iteration   3: 3.674 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.618 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.581, 3.618, 3.674), stdev = 0.049
  CI (99.9%): [2.722, 4.515] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.435 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.002 ms/op
Iteration   1: 3.845 ±(99.9%) 0.003 ms/op
Iteration   2: 3.893 ±(99.9%) 0.003 ms/op
Iteration   3: 3.839 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.859 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (3.839, 3.859, 3.893), stdev = 0.030
  CI (99.9%): [3.319, 4.399] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.918 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.168 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.881 ±(99.9%) 0.011 ms/op
Iteration   1: 4.974 ±(99.9%) 0.019 ms/op
Iteration   2: 5.058 ±(99.9%) 0.015 ms/op
Iteration   3: 4.991 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.008 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (4.974, 5.008, 5.058), stdev = 0.044
  CI (99.9%): [4.203, 5.812] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.745 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.012 ms/op
Iteration   1: 3.934 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  14.211 ms/op
                 createUser·p0.9999: 16.630 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 3.858 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   3: 3.854 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  13.108 ms/op
                 createUser·p0.9999: 20.634 ms/op
                 createUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 247212
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7256 
    [ 2.500,  5.000) = 219248 
    [ 5.000,  7.500) = 19146 
    [ 7.500, 10.000) = 1127 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     18.476 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.059 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.010 ms/op
Iteration   1: 3.624 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  12.521 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.511 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   5.909 ms/op
                 existUser·p0.999:  12.173 ms/op
                 existUser·p0.9999: 21.754 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 3.614 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   4.895 ms/op
                 existUser·p0.99:   6.305 ms/op
                 existUser·p0.999:  12.052 ms/op
                 existUser·p0.9999: 19.011 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267747
  mean =      3.582 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12517 
    [ 2.500,  5.000) = 244047 
    [ 5.000,  7.500) = 9830 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     12.292 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.860 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
Iteration   1: 3.976 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  11.268 ms/op
                 getUser·p0.9999: 15.942 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   2: 4.038 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  12.693 ms/op
                 getUser·p0.9999: 18.620 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   3: 4.011 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.427 ms/op
                 getUser·p0.999:  11.523 ms/op
                 getUser·p0.9999: 19.695 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 239419
  mean =      4.008 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7566 
    [ 2.500,  5.000) = 205059 
    [ 5.000,  7.500) = 24596 
    [ 7.500, 10.000) = 1719 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     12.265 ms/op
     p(99.9900) =     19.271 ms/op
     p(99.9990) =     20.270 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 7.128 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.609 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.049 ±(99.9%) 0.017 ms/op
Iteration   1: 4.907 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  16.166 ms/op
                 listUser·p0.9999: 21.900 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 5.002 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.512 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  17.038 ms/op
                 listUser·p0.9999: 24.838 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 4.781 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 31.467 ms/op
                 listUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196333
  mean =      4.895 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 558 
    [ 2.500,  5.000) = 126455 
    [ 5.000,  7.500) = 60901 
    [ 7.500, 10.000) = 6823 
    [10.000, 12.500) = 969 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.504 ms/op
     p(95.0000) =      7.324 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     18.405 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     31.855 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.396 ± 4.253  ops/ms
ClientGrpc.existUser                       thrpt       3   9.030 ± 2.877  ops/ms
ClientGrpc.getUser                         thrpt       3   8.311 ± 4.337  ops/ms
ClientGrpc.listUser                        thrpt       3   6.382 ± 1.132  ops/ms
ClientGrpc.createUser                       avgt       3   3.946 ± 1.284   ms/op
ClientGrpc.existUser                        avgt       3   3.618 ± 0.896   ms/op
ClientGrpc.getUser                          avgt       3   3.859 ± 0.540   ms/op
ClientGrpc.listUser                         avgt       3   5.008 ± 0.805   ms/op
ClientGrpc.createUser                     sample  247212   3.882 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.676           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.891           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.816           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.287           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.476           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.559           ms/op
ClientGrpc.existUser                      sample  267747   3.582 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.586           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.259           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.292           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.561           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.118           ms/op
ClientGrpc.getUser                        sample  239419   4.008 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.835           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.079           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.595           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.365           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.265           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.271           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.266           ms/op
ClientGrpc.listUser                       sample  196333   4.895 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.180           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.667           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.405           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.360           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.982           ms/op
