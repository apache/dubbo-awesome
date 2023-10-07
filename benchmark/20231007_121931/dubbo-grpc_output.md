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
# Warmup Iteration   1: 1.943 ops/ms
# Warmup Iteration   2: 4.970 ops/ms
# Warmup Iteration   3: 6.510 ops/ms
Iteration   1: 6.689 ops/ms
Iteration   2: 6.781 ops/ms
Iteration   3: 6.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.785 ±(99.9%) 1.787 ops/ms [Average]
  (min, avg, max) = (6.689, 6.785, 6.885), stdev = 0.098
  CI (99.9%): [4.998, 8.573] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ops/ms
# Warmup Iteration   2: 6.413 ops/ms
# Warmup Iteration   3: 7.084 ops/ms
Iteration   1: 6.958 ops/ms
Iteration   2: 7.364 ops/ms
Iteration   3: 7.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.253 ±(99.9%) 4.721 ops/ms [Average]
  (min, avg, max) = (6.958, 7.253, 7.438), stdev = 0.259
  CI (99.9%): [2.533, 11.974] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.655 ops/ms
# Warmup Iteration   2: 6.183 ops/ms
# Warmup Iteration   3: 6.768 ops/ms
Iteration   1: 6.782 ops/ms
Iteration   2: 6.870 ops/ms
Iteration   3: 6.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.860 ±(99.9%) 1.341 ops/ms [Average]
  (min, avg, max) = (6.782, 6.860, 6.928), stdev = 0.073
  CI (99.9%): [5.519, 8.200] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.448 ops/ms
# Warmup Iteration   2: 4.914 ops/ms
# Warmup Iteration   3: 5.305 ops/ms
Iteration   1: 5.499 ops/ms
Iteration   2: 5.511 ops/ms
Iteration   3: 5.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.443 ±(99.9%) 1.957 ops/ms [Average]
  (min, avg, max) = (5.319, 5.443, 5.511), stdev = 0.107
  CI (99.9%): [3.486, 7.400] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.342 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.999 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.974 ±(99.9%) 0.007 ms/op
Iteration   1: 4.668 ±(99.9%) 0.005 ms/op
Iteration   2: 4.700 ±(99.9%) 0.005 ms/op
Iteration   3: 4.799 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.722 ±(99.9%) 1.244 ms/op [Average]
  (min, avg, max) = (4.668, 4.722, 4.799), stdev = 0.068
  CI (99.9%): [3.478, 5.966] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.458 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.775 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.463 ±(99.9%) 0.003 ms/op
Iteration   1: 4.340 ±(99.9%) 0.003 ms/op
Iteration   2: 4.471 ±(99.9%) 0.005 ms/op
Iteration   3: 4.539 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.450 ±(99.9%) 1.846 ms/op [Average]
  (min, avg, max) = (4.340, 4.450, 4.539), stdev = 0.101
  CI (99.9%): [2.603, 6.296] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.557 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.206 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.005 ms/op
Iteration   1: 4.675 ±(99.9%) 0.005 ms/op
Iteration   2: 4.611 ±(99.9%) 0.004 ms/op
Iteration   3: 4.644 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.643 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (4.611, 4.643, 4.675), stdev = 0.032
  CI (99.9%): [4.066, 5.221] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.577 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 6.289 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.919 ±(99.9%) 0.017 ms/op
Iteration   1: 6.075 ±(99.9%) 0.021 ms/op
Iteration   2: 6.083 ±(99.9%) 0.011 ms/op
Iteration   3: 6.009 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.056 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (6.009, 6.056, 6.083), stdev = 0.040
  CI (99.9%): [5.317, 6.794] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.621 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.115 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.652 ±(99.9%) 0.015 ms/op
Iteration   1: 4.663 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.882 ms/op
                 createUser·p0.95:   6.562 ms/op
                 createUser·p0.99:   8.880 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 17.474 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 4.694 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   8.700 ms/op
                 createUser·p0.999:  14.830 ms/op
                 createUser·p0.9999: 20.087 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   3: 4.729 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   6.078 ms/op
                 createUser·p0.95:   6.778 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  12.851 ms/op
                 createUser·p0.9999: 20.414 ms/op
                 createUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 204388
  mean =      4.695 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2518 
    [ 2.500,  5.000) = 137717 
    [ 5.000,  7.500) = 58957 
    [ 7.500, 10.000) = 3998 
    [10.000, 12.500) = 891 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.652 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     13.576 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     21.519 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.617 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.686 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.452 ±(99.9%) 0.016 ms/op
Iteration   1: 4.348 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   4.157 ms/op
                 existUser·p0.90:   5.677 ms/op
                 existUser·p0.95:   6.341 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  14.367 ms/op
                 existUser·p0.9999: 18.959 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   2: 4.495 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   4.293 ms/op
                 existUser·p0.90:   5.767 ms/op
                 existUser·p0.95:   6.595 ms/op
                 existUser·p0.99:   9.077 ms/op
                 existUser·p0.999:  12.514 ms/op
                 existUser·p0.9999: 20.247 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   3: 4.437 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.332 ms/op
                 existUser·p0.99:   8.749 ms/op
                 existUser·p0.999:  14.791 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 216857
  mean =      4.426 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4871 
    [ 2.500,  5.000) = 163693 
    [ 5.000,  7.500) = 43272 
    [ 7.500, 10.000) = 3971 
    [10.000, 12.500) = 734 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     13.912 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.299 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.301 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.855 ±(99.9%) 0.016 ms/op
Iteration   1: 4.854 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   4.645 ms/op
                 getUser·p0.90:   6.291 ms/op
                 getUser·p0.95:   7.045 ms/op
                 getUser·p0.99:   9.433 ms/op
                 getUser·p0.999:  13.783 ms/op
                 getUser·p0.9999: 26.424 ms/op
                 getUser·p1.00:   38.666 ms/op

Iteration   2: 4.829 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   4.645 ms/op
                 getUser·p0.90:   6.185 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.290 ms/op
                 getUser·p0.999:  15.270 ms/op
                 getUser·p0.9999: 22.626 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   3: 4.745 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   6.111 ms/op
                 getUser·p0.95:   6.906 ms/op
                 getUser·p0.99:   9.404 ms/op
                 getUser·p0.999:  12.460 ms/op
                 getUser·p0.9999: 20.325 ms/op
                 getUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 199588
  mean =      4.809 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2189 
    [ 2.500,  5.000) = 126914 
    [ 5.000,  7.500) = 64079 
    [ 7.500, 10.000) = 5103 
    [10.000, 12.500) = 991 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     14.163 ms/op
     p(99.9900) =     26.281 ms/op
     p(99.9990) =     36.317 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.567 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 6.438 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.850 ±(99.9%) 0.023 ms/op
Iteration   1: 5.829 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.910 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   11.753 ms/op
                 listUser·p0.999:  18.418 ms/op
                 listUser·p0.9999: 24.315 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   2: 5.784 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   11.915 ms/op
                 listUser·p0.999:  20.414 ms/op
                 listUser·p0.9999: 38.858 ms/op
                 listUser·p1.00:   39.911 ms/op

Iteration   3: 5.890 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   12.747 ms/op
                 listUser·p0.999:  22.610 ms/op
                 listUser·p0.9999: 24.529 ms/op
                 listUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164654
  mean =      5.834 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 131 
    [ 2.500,  5.000) = 53513 
    [ 5.000,  7.500) = 90395 
    [ 7.500, 10.000) = 15862 
    [10.000, 12.500) = 3364 
    [12.500, 15.000) = 837 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      7.873 ms/op
     p(95.0000) =      9.011 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     21.638 ms/op
     p(99.9900) =     38.273 ms/op
     p(99.9990) =     39.869 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.785 ± 1.787  ops/ms
ClientGrpc.existUser                       thrpt       3   7.253 ± 4.721  ops/ms
ClientGrpc.getUser                         thrpt       3   6.860 ± 1.341  ops/ms
ClientGrpc.listUser                        thrpt       3   5.443 ± 1.957  ops/ms
ClientGrpc.createUser                       avgt       3   4.722 ± 1.244   ms/op
ClientGrpc.existUser                        avgt       3   4.450 ± 1.846   ms/op
ClientGrpc.getUser                          avgt       3   4.643 ± 0.577   ms/op
ClientGrpc.listUser                         avgt       3   6.056 ± 0.738   ms/op
ClientGrpc.createUser                     sample  204388   4.695 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.092           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.972           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.652           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.995           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.576           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.956           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.561           ms/op
ClientGrpc.existUser                      sample  216857   4.426 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.835           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.693           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.414           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.913           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.912           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.296           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.591           ms/op
ClientGrpc.getUser                        sample  199588   4.809 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.953           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.193           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.930           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.388           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.163           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.281           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          38.666           ms/op
ClientGrpc.listUser                       sample  164654   5.834 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.843           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.873           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.011           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.075           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.638           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          38.273           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.911           ms/op
