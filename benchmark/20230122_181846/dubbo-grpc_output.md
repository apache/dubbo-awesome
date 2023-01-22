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
# Warmup Iteration   1: 3.224 ops/ms
# Warmup Iteration   2: 6.782 ops/ms
# Warmup Iteration   3: 7.889 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.464 ops/ms
Iteration   3: 8.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.360 ±(99.9%) 1.685 ops/ms [Average]
  (min, avg, max) = (8.288, 8.360, 8.464), stdev = 0.092
  CI (99.9%): [6.675, 10.046] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.743 ops/ms
# Warmup Iteration   2: 8.007 ops/ms
# Warmup Iteration   3: 8.536 ops/ms
Iteration   1: 8.589 ops/ms
Iteration   2: 8.647 ops/ms
Iteration   3: 8.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.638 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (8.589, 8.638, 8.679), stdev = 0.045
  CI (99.9%): [7.810, 9.466] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.717 ops/ms
# Warmup Iteration   2: 8.111 ops/ms
# Warmup Iteration   3: 8.020 ops/ms
Iteration   1: 8.289 ops/ms
Iteration   2: 8.483 ops/ms
Iteration   3: 8.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.494 ±(99.9%) 3.846 ops/ms [Average]
  (min, avg, max) = (8.289, 8.494, 8.710), stdev = 0.211
  CI (99.9%): [4.648, 12.340] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.223 ops/ms
# Warmup Iteration   2: 6.023 ops/ms
# Warmup Iteration   3: 6.177 ops/ms
Iteration   1: 6.358 ops/ms
Iteration   2: 6.303 ops/ms
Iteration   3: 6.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.380 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (6.303, 6.380, 6.480), stdev = 0.091
  CI (99.9%): [4.728, 8.032] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.680 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.003 ms/op
Iteration   1: 3.949 ±(99.9%) 0.004 ms/op
Iteration   2: 3.962 ±(99.9%) 0.002 ms/op
Iteration   3: 3.929 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.947 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (3.929, 3.947, 3.962), stdev = 0.017
  CI (99.9%): [3.644, 4.249] (assumes normal distribution)


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
# Warmup Iteration   1: 4.980 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.004 ms/op
Iteration   1: 3.701 ±(99.9%) 0.003 ms/op
Iteration   2: 3.616 ±(99.9%) 0.003 ms/op
Iteration   3: 3.658 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.658 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.616, 3.658, 3.701), stdev = 0.042
  CI (99.9%): [2.888, 4.428] (assumes normal distribution)


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
# Warmup Iteration   1: 5.661 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.004 ms/op
Iteration   1: 3.951 ±(99.9%) 0.004 ms/op
Iteration   2: 3.872 ±(99.9%) 0.003 ms/op
Iteration   3: 3.897 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.907 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.872, 3.907, 3.951), stdev = 0.040
  CI (99.9%): [3.169, 4.644] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.915 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.238 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.052 ±(99.9%) 0.019 ms/op
Iteration   1: 4.872 ±(99.9%) 0.011 ms/op
Iteration   2: 4.943 ±(99.9%) 0.014 ms/op
Iteration   3: 4.885 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.900 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (4.872, 4.900, 4.943), stdev = 0.038
  CI (99.9%): [4.211, 5.589] (assumes normal distribution)


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
# Warmup Iteration   1: 5.350 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.012 ms/op
Iteration   1: 3.895 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  11.711 ms/op
                 createUser·p0.9999: 25.021 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   2: 3.761 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.535 ms/op
                 createUser·p0.999:  10.355 ms/op
                 createUser·p0.9999: 22.938 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.941 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.324 ms/op
                 createUser·p0.999:  12.510 ms/op
                 createUser·p0.9999: 24.794 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248280
  mean =      3.864 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6858 
    [ 2.500,  5.000) = 225207 
    [ 5.000,  7.500) = 14211 
    [ 7.500, 10.000) = 1550 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     11.710 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.416 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.010 ms/op
Iteration   1: 3.683 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  10.371 ms/op
                 existUser·p0.9999: 16.449 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 3.600 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  14.260 ms/op
                 existUser·p0.9999: 22.778 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 3.744 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  11.292 ms/op
                 existUser·p0.9999: 17.677 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261034
  mean =      3.675 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15939 
    [ 2.500,  5.000) = 233736 
    [ 5.000,  7.500) = 10319 
    [ 7.500, 10.000) = 668 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     11.860 ms/op
     p(99.9900) =     21.492 ms/op
     p(99.9990) =     23.049 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 5.350 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.719 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  14.582 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.870 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.401 ms/op
                 getUser·p0.999:  11.360 ms/op
                 getUser·p0.9999: 35.258 ms/op
                 getUser·p1.00:   35.717 ms/op

Iteration   3: 3.925 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  9.730 ms/op
                 getUser·p0.9999: 24.173 ms/op
                 getUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247094
  mean =      3.884 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5515 
    [ 2.500,  5.000) = 226676 
    [ 5.000,  7.500) = 13670 
    [ 7.500, 10.000) = 869 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     34.267 ms/op
     p(99.9990) =     35.590 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 6.489 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.401 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.076 ±(99.9%) 0.017 ms/op
Iteration   1: 4.759 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.193 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  16.262 ms/op
                 listUser·p0.9999: 25.202 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   2: 4.792 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  20.644 ms/op
                 listUser·p0.9999: 26.399 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   3: 4.917 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.447 ms/op
                 listUser·p0.95:   7.242 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  21.332 ms/op
                 listUser·p0.9999: 27.000 ms/op
                 listUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199000
  mean =      4.822 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 505 
    [ 2.500,  5.000) = 141915 
    [ 5.000,  7.500) = 49306 
    [ 7.500, 10.000) = 5930 
    [10.000, 12.500) = 815 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.360 ± 1.685  ops/ms
ClientGrpc.existUser                       thrpt       3   8.638 ± 0.828  ops/ms
ClientGrpc.getUser                         thrpt       3   8.494 ± 3.846  ops/ms
ClientGrpc.listUser                        thrpt       3   6.380 ± 1.652  ops/ms
ClientGrpc.createUser                       avgt       3   3.947 ± 0.302   ms/op
ClientGrpc.existUser                        avgt       3   3.658 ± 0.770   ms/op
ClientGrpc.getUser                          avgt       3   3.907 ± 0.738   ms/op
ClientGrpc.listUser                         avgt       3   4.900 ± 0.689   ms/op
ClientGrpc.createUser                     sample  248280   3.864 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.762           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.102           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.710           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.707           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.018           ms/op
ClientGrpc.existUser                      sample  261034   3.675 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.864           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.250           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.860           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.492           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.134           ms/op
ClientGrpc.getUser                        sample  247094   3.884 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.803           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.104           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.488           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.267           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.717           ms/op
ClientGrpc.listUser                       sample  199000   4.822 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.951           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.275           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.726           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.214           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.394           ms/op
