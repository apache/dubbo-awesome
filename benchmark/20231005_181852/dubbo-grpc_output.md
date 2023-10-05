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
# Warmup Iteration   1: 3.706 ops/ms
# Warmup Iteration   2: 8.258 ops/ms
# Warmup Iteration   3: 9.765 ops/ms
Iteration   1: 9.870 ops/ms
Iteration   2: 9.973 ops/ms
Iteration   3: 10.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.073 ±(99.9%) 4.865 ops/ms [Average]
  (min, avg, max) = (9.870, 10.073, 10.375), stdev = 0.267
  CI (99.9%): [5.208, 14.937] (assumes normal distribution)


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
# Warmup Iteration   1: 6.949 ops/ms
# Warmup Iteration   2: 10.293 ops/ms
# Warmup Iteration   3: 10.675 ops/ms
Iteration   1: 10.774 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 10.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.811 ±(99.9%) 3.072 ops/ms [Average]
  (min, avg, max) = (10.664, 10.811, 10.995), stdev = 0.168
  CI (99.9%): [7.739, 13.883] (assumes normal distribution)


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
# Warmup Iteration   1: 6.685 ops/ms
# Warmup Iteration   2: 9.924 ops/ms
# Warmup Iteration   3: 9.995 ops/ms
Iteration   1: 10.300 ops/ms
Iteration   2: 10.192 ops/ms
Iteration   3: 10.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.236 ±(99.9%) 1.038 ops/ms [Average]
  (min, avg, max) = (10.192, 10.236, 10.300), stdev = 0.057
  CI (99.9%): [9.197, 11.274] (assumes normal distribution)


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
# Warmup Iteration   1: 6.144 ops/ms
# Warmup Iteration   2: 7.593 ops/ms
# Warmup Iteration   3: 7.927 ops/ms
Iteration   1: 8.093 ops/ms
Iteration   2: 8.044 ops/ms
Iteration   3: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.023 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (7.931, 8.023, 8.093), stdev = 0.083
  CI (99.9%): [6.503, 9.543] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.003 ms/op
Iteration   2: 3.195 ±(99.9%) 0.004 ms/op
Iteration   3: 3.129 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.137 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.088, 3.137, 3.195), stdev = 0.054
  CI (99.9%): [2.149, 4.125] (assumes normal distribution)


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 2.948 ±(99.9%) 0.003 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 2.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.982 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (2.948, 2.982, 3.033), stdev = 0.045
  CI (99.9%): [2.163, 3.802] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.004 ms/op
Iteration   1: 3.119 ±(99.9%) 0.004 ms/op
Iteration   2: 3.094 ±(99.9%) 0.003 ms/op
Iteration   3: 3.156 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.123 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (3.094, 3.123, 3.156), stdev = 0.031
  CI (99.9%): [2.556, 3.690] (assumes normal distribution)


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
# Warmup Iteration   1: 5.113 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.024 ms/op
Iteration   1: 3.903 ±(99.9%) 0.015 ms/op
Iteration   2: 3.973 ±(99.9%) 0.023 ms/op
Iteration   3: 4.045 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 1.300 ms/op [Average]
  (min, avg, max) = (3.903, 3.974, 4.045), stdev = 0.071
  CI (99.9%): [2.674, 5.273] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.006 ms/op
Iteration   1: 3.093 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.699 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.730 ms/op
                 createUser·p0.999:  12.686 ms/op
                 createUser·p0.9999: 15.840 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  13.449 ms/op
                 createUser·p0.9999: 20.401 ms/op
                 createUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307260
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12436 
    [ 2.500,  5.000) = 292819 
    [ 5.000,  7.500) = 1474 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     12.141 ms/op
     p(99.9900) =     19.834 ms/op
     p(99.9990) =     20.773 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  12.612 ms/op
                 existUser·p0.9999: 27.181 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  8.155 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  9.997 ms/op
                 existUser·p0.9999: 20.131 ms/op
                 existUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317718
  mean =      3.022 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26346 
    [ 2.500,  5.000) = 289603 
    [ 5.000,  7.500) = 1118 
    [ 7.500, 10.000) = 269 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     11.150 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     27.677 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  12.447 ms/op
                 getUser·p0.9999: 30.573 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.673 ms/op
                 getUser·p0.9999: 19.045 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 22.774 ms/op
                 getUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308386
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10684 
    [ 2.500,  5.000) = 295786 
    [ 5.000,  7.500) = 1379 
    [ 7.500, 10.000) = 176 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     22.746 ms/op
     p(99.9990) =     31.905 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 5.281 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.010 ms/op
Iteration   1: 4.016 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  13.799 ms/op
                 listUser·p0.9999: 23.109 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 3.964 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 19.031 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   3: 4.077 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 21.566 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238936
  mean =      4.019 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1915 
    [ 2.500,  5.000) = 219655 
    [ 5.000,  7.500) = 16076 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 320 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     21.079 ms/op
     p(99.9990) =     23.711 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.073 ± 4.865  ops/ms
ClientGrpc.existUser                       thrpt       3  10.811 ± 3.072  ops/ms
ClientGrpc.getUser                         thrpt       3  10.236 ± 1.038  ops/ms
ClientGrpc.listUser                        thrpt       3   8.023 ± 1.520  ops/ms
ClientGrpc.createUser                       avgt       3   3.137 ± 0.988   ms/op
ClientGrpc.existUser                        avgt       3   2.982 ± 0.819   ms/op
ClientGrpc.getUser                          avgt       3   3.123 ± 0.567   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 1.300   ms/op
ClientGrpc.createUser                     sample  307260   3.123 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.685           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.141           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.834           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.873           ms/op
ClientGrpc.existUser                      sample  317718   3.022 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.719           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.150           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.594           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.820           ms/op
ClientGrpc.getUser                        sample  308386   3.113 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.853           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.878           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.746           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.145           ms/op
ClientGrpc.listUser                       sample  238936   4.019 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.943           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.079           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.838           ms/op
