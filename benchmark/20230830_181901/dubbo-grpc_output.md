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
# Warmup Iteration   1: 2.826 ops/ms
# Warmup Iteration   2: 6.701 ops/ms
# Warmup Iteration   3: 7.903 ops/ms
Iteration   1: 8.344 ops/ms
Iteration   2: 8.411 ops/ms
Iteration   3: 8.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.477 ±(99.9%) 3.210 ops/ms [Average]
  (min, avg, max) = (8.344, 8.477, 8.677), stdev = 0.176
  CI (99.9%): [5.267, 11.687] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.186 ops/ms
# Warmup Iteration   2: 8.272 ops/ms
# Warmup Iteration   3: 9.405 ops/ms
Iteration   1: 9.430 ops/ms
Iteration   2: 9.539 ops/ms
Iteration   3: 9.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.437 ±(99.9%) 1.804 ops/ms [Average]
  (min, avg, max) = (9.341, 9.437, 9.539), stdev = 0.099
  CI (99.9%): [7.633, 11.241] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.120 ops/ms
# Warmup Iteration   2: 7.855 ops/ms
# Warmup Iteration   3: 8.400 ops/ms
Iteration   1: 8.411 ops/ms
Iteration   2: 8.545 ops/ms
Iteration   3: 8.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.493 ±(99.9%) 1.312 ops/ms [Average]
  (min, avg, max) = (8.411, 8.493, 8.545), stdev = 0.072
  CI (99.9%): [7.181, 9.805] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.467 ops/ms
# Warmup Iteration   2: 6.055 ops/ms
# Warmup Iteration   3: 6.528 ops/ms
Iteration   1: 6.220 ops/ms
Iteration   2: 6.466 ops/ms
Iteration   3: 6.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.353 ±(99.9%) 2.262 ops/ms [Average]
  (min, avg, max) = (6.220, 6.353, 6.466), stdev = 0.124
  CI (99.9%): [4.091, 8.616] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.993 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.013 ms/op
Iteration   1: 3.681 ±(99.9%) 0.004 ms/op
Iteration   2: 3.618 ±(99.9%) 0.003 ms/op
Iteration   3: 3.824 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.708 ±(99.9%) 1.925 ms/op [Average]
  (min, avg, max) = (3.618, 3.708, 3.824), stdev = 0.106
  CI (99.9%): [1.782, 5.633] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.346 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.004 ms/op
Iteration   1: 3.646 ±(99.9%) 0.003 ms/op
Iteration   2: 3.568 ±(99.9%) 0.003 ms/op
Iteration   3: 3.490 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.568 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (3.490, 3.568, 3.646), stdev = 0.078
  CI (99.9%): [2.143, 4.993] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.635 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.003 ms/op
Iteration   1: 3.975 ±(99.9%) 0.003 ms/op
Iteration   2: 4.085 ±(99.9%) 0.006 ms/op
Iteration   3: 3.654 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.905 ±(99.9%) 4.086 ms/op [Average]
  (min, avg, max) = (3.654, 3.905, 4.085), stdev = 0.224
  CI (99.9%): [≈ 0, 7.990] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.944 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.334 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.961 ±(99.9%) 0.021 ms/op
Iteration   1: 4.827 ±(99.9%) 0.022 ms/op
Iteration   2: 4.903 ±(99.9%) 0.015 ms/op
Iteration   3: 4.791 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.840 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (4.791, 4.840, 4.903), stdev = 0.057
  CI (99.9%): [3.800, 5.881] (assumes normal distribution)


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
# Warmup Iteration   1: 5.859 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.012 ms/op
Iteration   1: 3.635 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  11.420 ms/op
                 createUser·p0.9999: 17.406 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   2: 3.783 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  11.181 ms/op
                 createUser·p0.9999: 22.271 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   3: 3.768 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  13.976 ms/op
                 createUser·p0.9999: 24.036 ms/op
                 createUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257469
  mean =      3.728 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12322 
    [ 2.500,  5.000) = 228913 
    [ 5.000,  7.500) = 14733 
    [ 7.500, 10.000) = 1046 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     22.880 ms/op
     p(99.9990) =     24.426 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.010 ms/op
Iteration   1: 3.537 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  11.304 ms/op
                 existUser·p0.9999: 15.218 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   2: 3.490 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.671 ms/op
                 existUser·p0.999:  12.951 ms/op
                 existUser·p0.9999: 17.498 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  10.532 ms/op
                 existUser·p0.9999: 21.365 ms/op
                 existUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272269
  mean =      3.525 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11936 
    [ 2.500,  5.000) = 249294 
    [ 5.000,  7.500) = 9575 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.482 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     19.700 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 5.324 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.011 ms/op
Iteration   1: 3.787 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.719 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  10.699 ms/op
                 getUser·p0.9999: 23.433 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 3.798 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  10.371 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   3: 3.879 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  10.429 ms/op
                 getUser·p0.9999: 21.947 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251084
  mean =      3.821 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6293 
    [ 2.500,  5.000) = 226977 
    [ 5.000,  7.500) = 16238 
    [ 7.500, 10.000) = 1251 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     10.486 ms/op
     p(99.9900) =     22.963 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 6.826 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.143 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.826 ±(99.9%) 0.016 ms/op
Iteration   1: 4.832 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.562 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  20.146 ms/op
                 listUser·p0.9999: 34.104 ms/op
                 listUser·p1.00:   36.110 ms/op

Iteration   2: 4.843 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.218 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   9.437 ms/op
                 listUser·p0.999:  21.692 ms/op
                 listUser·p0.9999: 25.867 ms/op
                 listUser·p1.00:   30.769 ms/op

Iteration   3: 4.805 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  19.247 ms/op
                 listUser·p0.9999: 28.836 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198870
  mean =      4.826 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 484 
    [ 2.500,  5.000) = 137537 
    [ 5.000,  7.500) = 53142 
    [ 7.500, 10.000) = 6380 
    [10.000, 12.500) = 775 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.201 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     20.746 ms/op
     p(99.9900) =     32.943 ms/op
     p(99.9990) =     35.398 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.477 ± 3.210  ops/ms
ClientGrpc.existUser                       thrpt       3   9.437 ± 1.804  ops/ms
ClientGrpc.getUser                         thrpt       3   8.493 ± 1.312  ops/ms
ClientGrpc.listUser                        thrpt       3   6.353 ± 2.262  ops/ms
ClientGrpc.createUser                       avgt       3   3.708 ± 1.925   ms/op
ClientGrpc.existUser                        avgt       3   3.568 ± 1.425   ms/op
ClientGrpc.getUser                          avgt       3   3.905 ± 4.086   ms/op
ClientGrpc.listUser                         avgt       3   4.840 ± 1.041   ms/op
ClientGrpc.createUser                     sample  257469   3.728 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.688           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.627           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.977           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.880           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.478           ms/op
ClientGrpc.existUser                      sample  272269   3.525 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.858           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.482           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.715           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.700           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.592           ms/op
ClientGrpc.getUser                        sample  251084   3.821 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.051           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.210           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.799           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.486           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.963           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.757           ms/op
ClientGrpc.listUser                       sample  198870   4.826 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.033           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.373           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.339           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.943           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.110           ms/op
