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
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 6.492 ops/ms
# Warmup Iteration   3: 7.704 ops/ms
Iteration   1: 8.234 ops/ms
Iteration   2: 8.392 ops/ms
Iteration   3: 8.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.356 ±(99.9%) 1.989 ops/ms [Average]
  (min, avg, max) = (8.234, 8.356, 8.443), stdev = 0.109
  CI (99.9%): [6.367, 10.345] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.017 ops/ms
# Warmup Iteration   2: 8.413 ops/ms
# Warmup Iteration   3: 8.696 ops/ms
Iteration   1: 9.279 ops/ms
Iteration   2: 8.819 ops/ms
Iteration   3: 9.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.097 ±(99.9%) 4.463 ops/ms [Average]
  (min, avg, max) = (8.819, 9.097, 9.279), stdev = 0.245
  CI (99.9%): [4.633, 13.560] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.478 ops/ms
# Warmup Iteration   2: 7.925 ops/ms
# Warmup Iteration   3: 8.374 ops/ms
Iteration   1: 8.495 ops/ms
Iteration   2: 8.581 ops/ms
Iteration   3: 8.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.547 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (8.495, 8.547, 8.581), stdev = 0.046
  CI (99.9%): [7.711, 9.384] (assumes normal distribution)


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
# Warmup Iteration   1: 4.262 ops/ms
# Warmup Iteration   2: 6.346 ops/ms
# Warmup Iteration   3: 6.491 ops/ms
Iteration   1: 6.622 ops/ms
Iteration   2: 6.696 ops/ms
Iteration   3: 6.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.593 ±(99.9%) 2.208 ops/ms [Average]
  (min, avg, max) = (6.460, 6.593, 6.696), stdev = 0.121
  CI (99.9%): [4.385, 8.800] (assumes normal distribution)


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
# Warmup Iteration   1: 5.337 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.045 ms/op
Iteration   1: 3.787 ±(99.9%) 0.003 ms/op
Iteration   2: 3.847 ±(99.9%) 0.004 ms/op
Iteration   3: 3.824 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.819 ±(99.9%) 0.558 ms/op [Average]
  (min, avg, max) = (3.787, 3.819, 3.847), stdev = 0.031
  CI (99.9%): [3.261, 4.377] (assumes normal distribution)


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
# Warmup Iteration   1: 4.812 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.004 ms/op
Iteration   1: 3.574 ±(99.9%) 0.003 ms/op
Iteration   2: 3.527 ±(99.9%) 0.003 ms/op
Iteration   3: 3.606 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.569 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (3.527, 3.569, 3.606), stdev = 0.040
  CI (99.9%): [2.847, 4.291] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.363 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.003 ms/op
Iteration   1: 3.849 ±(99.9%) 0.002 ms/op
Iteration   2: 3.765 ±(99.9%) 0.003 ms/op
Iteration   3: 3.709 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.774 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (3.709, 3.774, 3.849), stdev = 0.070
  CI (99.9%): [2.492, 5.057] (assumes normal distribution)


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
# Warmup Iteration   1: 5.789 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 5.271 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.018 ms/op
Iteration   1: 4.904 ±(99.9%) 0.018 ms/op
Iteration   2: 4.827 ±(99.9%) 0.015 ms/op
Iteration   3: 4.829 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.854 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (4.827, 4.854, 4.904), stdev = 0.044
  CI (99.9%): [4.052, 5.655] (assumes normal distribution)


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
# Warmup Iteration   1: 5.411 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.011 ms/op
Iteration   1: 3.751 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.490 ms/op
                 createUser·p0.999:  14.426 ms/op
                 createUser·p0.9999: 24.821 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   2: 3.796 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  14.178 ms/op
                 createUser·p0.9999: 26.186 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   3: 3.803 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  14.431 ms/op
                 createUser·p0.9999: 27.268 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253821
  mean =      3.784 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7386 
    [ 2.500,  5.000) = 233037 
    [ 5.000,  7.500) = 11440 
    [ 7.500, 10.000) = 1171 
    [10.000, 12.500) = 433 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     26.583 ms/op
     p(99.9990) =     27.671 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 5.191 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.009 ms/op
Iteration   1: 3.620 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 14.942 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   2: 3.651 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.466 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  10.739 ms/op
                 existUser·p0.9999: 18.750 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 3.750 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  11.382 ms/op
                 existUser·p0.9999: 20.314 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261300
  mean =      3.673 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6459 
    [ 2.500,  5.000) = 245189 
    [ 5.000,  7.500) = 8421 
    [ 7.500, 10.000) = 864 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     18.018 ms/op
     p(99.9990) =     20.657 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.011 ms/op
Iteration   1: 3.722 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   7.257 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 16.089 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.359 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  9.946 ms/op
                 getUser·p0.9999: 19.349 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 3.736 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  11.193 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256761
  mean =      3.738 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11558 
    [ 2.500,  5.000) = 232622 
    [ 5.000,  7.500) = 10993 
    [ 7.500, 10.000) = 1211 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     10.994 ms/op
     p(99.9900) =     23.178 ms/op
     p(99.9990) =     24.389 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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
# Warmup Iteration   1: 6.428 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.210 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.871 ±(99.9%) 0.017 ms/op
Iteration   1: 4.791 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.373 ms/op
                 listUser·p0.95:   7.258 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  16.437 ms/op
                 listUser·p0.9999: 20.884 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 4.845 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   7.086 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  16.629 ms/op
                 listUser·p0.9999: 24.917 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   3: 4.795 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.275 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  23.862 ms/op
                 listUser·p0.9999: 29.731 ms/op
                 listUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199586
  mean =      4.810 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 414 
    [ 2.500,  5.000) = 145760 
    [ 5.000,  7.500) = 45894 
    [ 7.500, 10.000) = 6114 
    [10.000, 12.500) = 842 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     18.738 ms/op
     p(99.9900) =     26.677 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.356 ± 1.989  ops/ms
ClientGrpc.existUser                       thrpt       3   9.097 ± 4.463  ops/ms
ClientGrpc.getUser                         thrpt       3   8.547 ± 0.837  ops/ms
ClientGrpc.listUser                        thrpt       3   6.593 ± 2.208  ops/ms
ClientGrpc.createUser                       avgt       3   3.819 ± 0.558   ms/op
ClientGrpc.existUser                        avgt       3   3.569 ± 0.722   ms/op
ClientGrpc.getUser                          avgt       3   3.774 ± 1.282   ms/op
ClientGrpc.listUser                         avgt       3   4.854 ± 0.801   ms/op
ClientGrpc.createUser                     sample  253821   3.784 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.038           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.988           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.369           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.583           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.689           ms/op
ClientGrpc.existUser                      sample  261300   3.673 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.904           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.373           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.764           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.018           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.742           ms/op
ClientGrpc.getUser                        sample  256761   3.738 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.359           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.989           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.521           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.994           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.178           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.674           ms/op
ClientGrpc.listUser                       sample  199586   4.810 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.251           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.339           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.738           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.677           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.983           ms/op
