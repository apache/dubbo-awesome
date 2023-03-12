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
# Warmup Iteration   1: 3.175 ops/ms
# Warmup Iteration   2: 7.164 ops/ms
# Warmup Iteration   3: 8.224 ops/ms
Iteration   1: 8.613 ops/ms
Iteration   2: 8.872 ops/ms
Iteration   3: 8.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.795 ±(99.9%) 2.889 ops/ms [Average]
  (min, avg, max) = (8.613, 8.795, 8.900), stdev = 0.158
  CI (99.9%): [5.906, 11.684] (assumes normal distribution)


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
# Warmup Iteration   1: 6.046 ops/ms
# Warmup Iteration   2: 8.858 ops/ms
# Warmup Iteration   3: 9.255 ops/ms
Iteration   1: 9.248 ops/ms
Iteration   2: 9.396 ops/ms
Iteration   3: 9.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.442 ±(99.9%) 4.035 ops/ms [Average]
  (min, avg, max) = (9.248, 9.442, 9.683), stdev = 0.221
  CI (99.9%): [5.408, 13.477] (assumes normal distribution)


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
# Warmup Iteration   1: 5.487 ops/ms
# Warmup Iteration   2: 8.434 ops/ms
# Warmup Iteration   3: 8.743 ops/ms
Iteration   1: 8.821 ops/ms
Iteration   2: 8.891 ops/ms
Iteration   3: 8.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.857 ±(99.9%) 0.636 ops/ms [Average]
  (min, avg, max) = (8.821, 8.857, 8.891), stdev = 0.035
  CI (99.9%): [8.220, 9.493] (assumes normal distribution)


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
# Warmup Iteration   1: 4.526 ops/ms
# Warmup Iteration   2: 6.576 ops/ms
# Warmup Iteration   3: 6.592 ops/ms
Iteration   1: 6.805 ops/ms
Iteration   2: 6.858 ops/ms
Iteration   3: 6.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.869 ±(99.9%) 1.284 ops/ms [Average]
  (min, avg, max) = (6.805, 6.869, 6.945), stdev = 0.070
  CI (99.9%): [5.585, 8.153] (assumes normal distribution)


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
# Warmup Iteration   1: 5.252 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.022 ms/op
Iteration   1: 3.607 ±(99.9%) 0.004 ms/op
Iteration   2: 3.540 ±(99.9%) 0.006 ms/op
Iteration   3: 3.558 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.568 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.540, 3.568, 3.607), stdev = 0.035
  CI (99.9%): [2.938, 4.199] (assumes normal distribution)


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
# Warmup Iteration   1: 5.004 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.003 ms/op
Iteration   1: 3.410 ±(99.9%) 0.003 ms/op
Iteration   2: 3.382 ±(99.9%) 0.004 ms/op
Iteration   3: 3.460 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.417 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.382, 3.417, 3.460), stdev = 0.040
  CI (99.9%): [2.696, 4.139] (assumes normal distribution)


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
# Warmup Iteration   1: 5.116 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.004 ms/op
Iteration   1: 3.621 ±(99.9%) 0.005 ms/op
Iteration   2: 3.601 ±(99.9%) 0.004 ms/op
Iteration   3: 3.612 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.611 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (3.601, 3.611, 3.621), stdev = 0.010
  CI (99.9%): [3.430, 3.793] (assumes normal distribution)


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
# Warmup Iteration   1: 6.850 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.875 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.777 ±(99.9%) 0.016 ms/op
Iteration   1: 4.715 ±(99.9%) 0.020 ms/op
Iteration   2: 4.711 ±(99.9%) 0.013 ms/op
Iteration   3: 4.672 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.699 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (4.672, 4.699, 4.715), stdev = 0.023
  CI (99.9%): [4.271, 5.127] (assumes normal distribution)


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
# Warmup Iteration   1: 5.603 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.008 ms/op
Iteration   1: 3.682 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  13.025 ms/op
                 createUser·p0.9999: 15.463 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.554 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.492 ms/op
                 createUser·p0.999:  11.431 ms/op
                 createUser·p0.9999: 15.499 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   3: 3.683 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.878 ms/op
                 createUser·p0.999:  16.353 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263919
  mean =      3.639 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7325 
    [ 2.500,  5.000) = 250836 
    [ 5.000,  7.500) = 4989 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.896 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     29.118 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 4.968 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.007 ms/op
Iteration   1: 3.422 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  13.320 ms/op
                 existUser·p0.9999: 15.285 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   2: 3.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  7.449 ms/op
                 existUser·p0.9999: 15.052 ms/op
                 existUser·p1.00:   16.663 ms/op

Iteration   3: 3.424 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 19.005 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279915
  mean =      3.429 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5417 
    [ 2.500,  5.000) = 271911 
    [ 5.000,  7.500) = 2231 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     20.264 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 5.258 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.008 ms/op
Iteration   1: 3.624 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  13.611 ms/op
                 getUser·p0.9999: 30.578 ms/op
                 getUser·p1.00:   31.130 ms/op

Iteration   2: 3.643 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  9.473 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   3: 3.623 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  8.016 ms/op
                 getUser·p0.9999: 24.325 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264288
  mean =      3.630 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7726 
    [ 2.500,  5.000) = 250617 
    [ 5.000,  7.500) = 5344 
    [ 7.500, 10.000) = 336 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     10.022 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     30.816 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 6.714 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.880 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.013 ms/op
Iteration   1: 4.682 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.841 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  15.623 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 4.688 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  16.265 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 4.701 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.741 ms/op
                 listUser·p0.95:   6.382 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  18.641 ms/op
                 listUser·p0.9999: 21.830 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204589
  mean =      4.690 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 493 
    [ 2.500,  5.000) = 161060 
    [ 5.000,  7.500) = 38695 
    [ 7.500, 10.000) = 3755 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.562 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     16.653 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     23.883 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.795 ± 2.889  ops/ms
ClientGrpc.existUser                       thrpt       3   9.442 ± 4.035  ops/ms
ClientGrpc.getUser                         thrpt       3   8.857 ± 0.636  ops/ms
ClientGrpc.listUser                        thrpt       3   6.869 ± 1.284  ops/ms
ClientGrpc.createUser                       avgt       3   3.568 ± 0.630   ms/op
ClientGrpc.existUser                        avgt       3   3.417 ± 0.721   ms/op
ClientGrpc.getUser                          avgt       3   3.611 ± 0.182   ms/op
ClientGrpc.listUser                         avgt       3   4.699 ± 0.428   ms/op
ClientGrpc.createUser                     sample  263919   3.639 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.850           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.896           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.100           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.327           ms/op
ClientGrpc.existUser                      sample  279915   3.429 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.667           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.932           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.086           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.695           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.382           ms/op
ClientGrpc.getUser                        sample  264288   3.630 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.809           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.022           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.541           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.130           ms/op
ClientGrpc.listUser                       sample  204589   4.690 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.257           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.653           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.807           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.986           ms/op
