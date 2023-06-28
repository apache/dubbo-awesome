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
# Warmup Iteration   1: 4.345 ops/ms
# Warmup Iteration   2: 8.897 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.325 ops/ms
Iteration   3: 10.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.359 ±(99.9%) 1.013 ops/ms [Average]
  (min, avg, max) = (10.325, 10.359, 10.423), stdev = 0.056
  CI (99.9%): [9.347, 11.372] (assumes normal distribution)


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
# Warmup Iteration   1: 7.714 ops/ms
# Warmup Iteration   2: 10.467 ops/ms
# Warmup Iteration   3: 11.123 ops/ms
Iteration   1: 11.211 ops/ms
Iteration   2: 10.973 ops/ms
Iteration   3: 10.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.019 ±(99.9%) 3.154 ops/ms [Average]
  (min, avg, max) = (10.875, 11.019, 11.211), stdev = 0.173
  CI (99.9%): [7.865, 14.174] (assumes normal distribution)


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
# Warmup Iteration   1: 7.943 ops/ms
# Warmup Iteration   2: 10.074 ops/ms
# Warmup Iteration   3: 10.533 ops/ms
Iteration   1: 10.618 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.637 ±(99.9%) 0.386 ops/ms [Average]
  (min, avg, max) = (10.618, 10.637, 10.660), stdev = 0.021
  CI (99.9%): [10.252, 11.023] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.962 ops/ms
# Warmup Iteration   2: 7.976 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.280 ops/ms
Iteration   2: 8.172 ops/ms
Iteration   3: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.155 ±(99.9%) 2.462 ops/ms [Average]
  (min, avg, max) = (8.012, 8.155, 8.280), stdev = 0.135
  CI (99.9%): [5.692, 10.617] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.005 ms/op
Iteration   1: 3.045 ±(99.9%) 0.005 ms/op
Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
Iteration   3: 2.958 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.017 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (2.958, 3.017, 3.048), stdev = 0.051
  CI (99.9%): [2.088, 3.947] (assumes normal distribution)


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.004 ms/op
Iteration   1: 2.846 ±(99.9%) 0.004 ms/op
Iteration   2: 2.895 ±(99.9%) 0.003 ms/op
Iteration   3: 2.876 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.873 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.846, 2.873, 2.895), stdev = 0.025
  CI (99.9%): [2.419, 3.326] (assumes normal distribution)


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.004 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 3.039 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.016 ±(99.9%) 0.563 ms/op [Average]
  (min, avg, max) = (2.981, 3.016, 3.039), stdev = 0.031
  CI (99.9%): [2.452, 3.579] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.151 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.007 ms/op
Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
Iteration   2: 3.830 ±(99.9%) 0.067 ms/op
Iteration   3: 3.824 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.845 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.824, 3.845, 3.880), stdev = 0.031
  CI (99.9%): [3.284, 4.406] (assumes normal distribution)


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 13.566 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  9.660 ms/op
                 createUser·p0.9999: 12.665 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 25.518 ms/op
                 createUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315199
  mean =      3.045 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20191 
    [ 2.500,  5.000) = 293148 
    [ 5.000,  7.500) = 1335 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.516 ms/op
     p(99.9900) =     24.967 ms/op
     p(99.9990) =     25.778 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 2.931 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.417 ms/op
                 existUser·p0.9999: 12.797 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   2: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  5.698 ms/op
                 existUser·p0.9999: 12.155 ms/op
                 existUser·p1.00:   12.386 ms/op

Iteration   3: 2.884 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 23.069 ms/op
                 existUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330530
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37907 
    [ 2.500,  5.000) = 291463 
    [ 5.000,  7.500) = 879 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.864 ms/op
     p(99.9900) =     22.641 ms/op
     p(99.9990) =     23.770 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  6.128 ms/op
                 getUser·p0.9999: 17.903 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 3.017 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.687 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.250 ms/op
                 getUser·p0.9999: 22.514 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317324
  mean =      3.026 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23284 
    [ 2.500,  5.000) = 292507 
    [ 5.000,  7.500) = 1272 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.182 ms/op
     p(99.9900) =     21.489 ms/op
     p(99.9990) =     22.828 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 5.093 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.011 ms/op
Iteration   1: 3.853 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  12.632 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 3.783 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.362 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 17.772 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249858
  mean =      3.839 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 3934 
    [ 2.500,  3.750) = 130490 
    [ 3.750,  5.000) = 95611 
    [ 5.000,  6.250) = 14939 
    [ 6.250,  7.500) = 3858 
    [ 7.500,  8.750) = 488 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 136 
    [13.750, 15.000) = 116 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.503 ms/op
     p(99.9900) =     19.334 ms/op
     p(99.9990) =     19.874 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.359 ± 1.013  ops/ms
ClientGrpc.existUser                       thrpt       3  11.019 ± 3.154  ops/ms
ClientGrpc.getUser                         thrpt       3  10.637 ± 0.386  ops/ms
ClientGrpc.listUser                        thrpt       3   8.155 ± 2.462  ops/ms
ClientGrpc.createUser                       avgt       3   3.017 ± 0.930   ms/op
ClientGrpc.existUser                        avgt       3   2.873 ± 0.454   ms/op
ClientGrpc.getUser                          avgt       3   3.016 ± 0.563   ms/op
ClientGrpc.listUser                         avgt       3   3.845 ± 0.561   ms/op
ClientGrpc.createUser                     sample  315199   3.045 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.632           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.516           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.967           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.887           ms/op
ClientGrpc.existUser                      sample  330530   2.904 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.595           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.864           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.641           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.428           ms/op
ClientGrpc.getUser                        sample  317324   3.026 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.587           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.182           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.489           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.036           ms/op
ClientGrpc.listUser                       sample  249858   3.839 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.011           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.707           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.503           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.334           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.890           ms/op
