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
# Warmup Iteration   1: 4.031 ops/ms
# Warmup Iteration   2: 9.144 ops/ms
# Warmup Iteration   3: 10.018 ops/ms
Iteration   1: 10.415 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.543 ±(99.9%) 2.213 ops/ms [Average]
  (min, avg, max) = (10.415, 10.543, 10.657), stdev = 0.121
  CI (99.9%): [8.330, 12.756] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.070 ops/ms
# Warmup Iteration   2: 10.300 ops/ms
# Warmup Iteration   3: 10.918 ops/ms
Iteration   1: 10.684 ops/ms
Iteration   2: 10.868 ops/ms
Iteration   3: 10.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.832 ±(99.9%) 2.436 ops/ms [Average]
  (min, avg, max) = (10.684, 10.832, 10.944), stdev = 0.134
  CI (99.9%): [8.396, 13.268] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.708 ops/ms
# Warmup Iteration   2: 9.998 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.390 ops/ms
Iteration   2: 10.407 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.392 ±(99.9%) 0.268 ops/ms [Average]
  (min, avg, max) = (10.378, 10.392, 10.407), stdev = 0.015
  CI (99.9%): [10.124, 10.660] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.234 ops/ms
# Warmup Iteration   2: 7.239 ops/ms
# Warmup Iteration   3: 7.695 ops/ms
Iteration   1: 7.781 ops/ms
Iteration   2: 7.739 ops/ms
Iteration   3: 7.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.765 ±(99.9%) 0.415 ops/ms [Average]
  (min, avg, max) = (7.739, 7.765, 7.781), stdev = 0.023
  CI (99.9%): [7.349, 8.180] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.437 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.080 ±(99.9%) 0.003 ms/op
Iteration   3: 3.018 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.058 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (3.018, 3.058, 3.080), stdev = 0.035
  CI (99.9%): [2.426, 3.690] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.003 ms/op
Iteration   1: 2.926 ±(99.9%) 0.003 ms/op
Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
Iteration   3: 2.858 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.890 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (2.858, 2.890, 2.926), stdev = 0.034
  CI (99.9%): [2.266, 3.514] (assumes normal distribution)


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.004 ms/op
Iteration   1: 3.131 ±(99.9%) 0.005 ms/op
Iteration   2: 3.026 ±(99.9%) 0.004 ms/op
Iteration   3: 3.105 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.087 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (3.026, 3.087, 3.131), stdev = 0.054
  CI (99.9%): [2.093, 4.081] (assumes normal distribution)


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
# Warmup Iteration   1: 5.492 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.012 ms/op
Iteration   1: 4.148 ±(99.9%) 0.026 ms/op
Iteration   2: 4.136 ±(99.9%) 0.015 ms/op
Iteration   3: 4.113 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.132 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (4.113, 4.132, 4.148), stdev = 0.018
  CI (99.9%): [3.811, 4.453] (assumes normal distribution)


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.442 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  9.870 ms/op
                 createUser·p0.9999: 16.880 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  9.375 ms/op
                 createUser·p0.9999: 19.518 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  9.355 ms/op
                 createUser·p0.9999: 22.853 ms/op
                 createUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311801
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21123 
    [ 2.500,  5.000) = 288287 
    [ 5.000,  7.500) = 1572 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      9.440 ms/op
     p(99.9900) =     21.535 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   2: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.126 ms/op
                 existUser·p0.9999: 14.240 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.935 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.372 ms/op
                 existUser·p0.9999: 17.170 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324637
  mean =      2.958 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1321 
    [ 1.250,  2.500) = 26482 
    [ 2.500,  3.750) = 286720 
    [ 3.750,  5.000) = 8214 
    [ 5.000,  6.250) = 898 
    [ 6.250,  7.500) = 480 
    [ 7.500,  8.750) = 261 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.378 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     17.351 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  8.912 ms/op
                 getUser·p0.9999: 13.141 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  11.977 ms/op
                 getUser·p0.9999: 15.303 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.666 ms/op
                 getUser·p0.9999: 17.615 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311281
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 534 
    [ 1.250,  2.500) = 17616 
    [ 2.500,  3.750) = 272892 
    [ 3.750,  5.000) = 18063 
    [ 5.000,  6.250) = 958 
    [ 6.250,  7.500) = 612 
    [ 7.500,  8.750) = 214 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      9.990 ms/op
     p(99.9900) =     16.467 ms/op
     p(99.9990) =     17.949 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 6.033 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.012 ms/op
Iteration   1: 4.126 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.556 ms/op
                 listUser·p0.9999: 19.898 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   2: 4.101 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  16.690 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.140 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  19.652 ms/op
                 listUser·p0.9999: 25.750 ms/op
                 listUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232767
  mean =      4.122 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2340 
    [ 2.500,  5.000) = 203806 
    [ 5.000,  7.500) = 24798 
    [ 7.500, 10.000) = 1333 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     15.651 ms/op
     p(99.9900) =     24.206 ms/op
     p(99.9990) =     26.149 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.543 ± 2.213  ops/ms
ClientGrpc.existUser                       thrpt       3  10.832 ± 2.436  ops/ms
ClientGrpc.getUser                         thrpt       3  10.392 ± 0.268  ops/ms
ClientGrpc.listUser                        thrpt       3   7.765 ± 0.415  ops/ms
ClientGrpc.createUser                       avgt       3   3.058 ± 0.632   ms/op
ClientGrpc.existUser                        avgt       3   2.890 ± 0.624   ms/op
ClientGrpc.getUser                          avgt       3   3.087 ± 0.994   ms/op
ClientGrpc.listUser                         avgt       3   4.132 ± 0.321   ms/op
ClientGrpc.createUser                     sample  311801   3.076 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.442           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.440           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.535           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.790           ms/op
ClientGrpc.existUser                      sample  324637   2.958 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.641           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.378           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.777           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.498           ms/op
ClientGrpc.getUser                        sample  311281   3.083 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.755           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.990           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.467           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.055           ms/op
ClientGrpc.listUser                       sample  232767   4.122 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.290           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.949           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.651           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.206           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.182           ms/op
