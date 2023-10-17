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
# Warmup Iteration   1: 3.828 ops/ms
# Warmup Iteration   2: 8.719 ops/ms
# Warmup Iteration   3: 9.794 ops/ms
Iteration   1: 10.160 ops/ms
Iteration   2: 10.217 ops/ms
Iteration   3: 10.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.282 ±(99.9%) 2.995 ops/ms [Average]
  (min, avg, max) = (10.160, 10.282, 10.469), stdev = 0.164
  CI (99.9%): [7.286, 13.277] (assumes normal distribution)


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
# Warmup Iteration   1: 7.027 ops/ms
# Warmup Iteration   2: 10.261 ops/ms
# Warmup Iteration   3: 10.746 ops/ms
Iteration   1: 10.819 ops/ms
Iteration   2: 10.696 ops/ms
Iteration   3: 10.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.780 ±(99.9%) 1.331 ops/ms [Average]
  (min, avg, max) = (10.696, 10.780, 10.826), stdev = 0.073
  CI (99.9%): [9.450, 12.111] (assumes normal distribution)


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
# Warmup Iteration   1: 6.600 ops/ms
# Warmup Iteration   2: 9.950 ops/ms
# Warmup Iteration   3: 9.903 ops/ms
Iteration   1: 10.117 ops/ms
Iteration   2: 10.214 ops/ms
Iteration   3: 10.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.254 ±(99.9%) 2.935 ops/ms [Average]
  (min, avg, max) = (10.117, 10.254, 10.431), stdev = 0.161
  CI (99.9%): [7.320, 13.189] (assumes normal distribution)


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
# Warmup Iteration   1: 5.509 ops/ms
# Warmup Iteration   2: 7.972 ops/ms
# Warmup Iteration   3: 8.098 ops/ms
Iteration   1: 8.039 ops/ms
Iteration   2: 7.985 ops/ms
Iteration   3: 8.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.053 ±(99.9%) 1.393 ops/ms [Average]
  (min, avg, max) = (7.985, 8.053, 8.136), stdev = 0.076
  CI (99.9%): [6.661, 9.446] (assumes normal distribution)


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
# Warmup Iteration   1: 4.249 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.002 ms/op
Iteration   2: 3.085 ±(99.9%) 0.005 ms/op
Iteration   3: 3.152 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.099 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (3.059, 3.099, 3.152), stdev = 0.048
  CI (99.9%): [2.227, 3.970] (assumes normal distribution)


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.004 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
Iteration   2: 2.903 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.955 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (2.903, 2.955, 2.996), stdev = 0.047
  CI (99.9%): [2.090, 3.820] (assumes normal distribution)


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.003 ms/op
Iteration   1: 3.113 ±(99.9%) 0.002 ms/op
Iteration   2: 3.112 ±(99.9%) 0.003 ms/op
Iteration   3: 3.145 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.123 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (3.112, 3.123, 3.145), stdev = 0.019
  CI (99.9%): [2.782, 3.465] (assumes normal distribution)


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
# Warmup Iteration   1: 5.885 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.036 ms/op
Iteration   1: 3.992 ±(99.9%) 0.026 ms/op
Iteration   2: 3.887 ±(99.9%) 0.017 ms/op
Iteration   3: 3.964 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.948 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (3.887, 3.948, 3.992), stdev = 0.054
  CI (99.9%): [2.958, 4.938] (assumes normal distribution)


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.008 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  7.647 ms/op
                 createUser·p0.9999: 16.488 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   2: 3.119 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.543 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  15.352 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  15.875 ms/op
                 createUser·p0.9999: 20.997 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308462
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15085 
    [ 2.500,  5.000) = 291275 
    [ 5.000,  7.500) = 1424 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.283 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  7.143 ms/op
                 existUser·p0.9999: 13.906 ms/op
                 existUser·p1.00:   16.777 ms/op

Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  12.435 ms/op
                 existUser·p0.9999: 31.699 ms/op
                 existUser·p1.00:   31.982 ms/op

Iteration   3: 2.963 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 21.011 ms/op
                 existUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322372
  mean =      2.979 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30185 
    [ 2.500,  5.000) = 290691 
    [ 5.000,  7.500) = 928 
    [ 7.500, 10.000) = 195 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.283 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     10.267 ms/op
     p(99.9900) =     23.086 ms/op
     p(99.9990) =     31.843 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  9.574 ms/op
                 getUser·p0.9999: 16.672 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   2: 3.157 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  10.207 ms/op
                 getUser·p0.9999: 18.411 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  14.517 ms/op
                 getUser·p0.9999: 22.108 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306815
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12373 
    [ 2.500,  5.000) = 292075 
    [ 5.000,  7.500) = 1881 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     10.590 ms/op
     p(99.9900) =     19.016 ms/op
     p(99.9990) =     22.308 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 5.824 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.011 ms/op
Iteration   1: 3.917 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 21.682 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.502 ms/op
                 listUser·p0.9999: 18.410 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 3.876 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.776 ms/op
                 listUser·p0.999:  14.770 ms/op
                 listUser·p0.9999: 17.949 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244957
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2214 
    [ 2.500,  5.000) = 228641 
    [ 5.000,  7.500) = 12542 
    [ 7.500, 10.000) = 860 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     23.113 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.282 ± 2.995  ops/ms
ClientGrpc.existUser                       thrpt       3  10.780 ± 1.331  ops/ms
ClientGrpc.getUser                         thrpt       3  10.254 ± 2.935  ops/ms
ClientGrpc.listUser                        thrpt       3   8.053 ± 1.393  ops/ms
ClientGrpc.createUser                       avgt       3   3.099 ± 0.872   ms/op
ClientGrpc.existUser                        avgt       3   2.955 ± 0.865   ms/op
ClientGrpc.getUser                          avgt       3   3.123 ± 0.342   ms/op
ClientGrpc.listUser                         avgt       3   3.948 ± 0.990   ms/op
ClientGrpc.createUser                     sample  308462   3.112 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.543           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.369           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.956           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.266           ms/op
ClientGrpc.existUser                      sample  322372   2.979 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.283           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.267           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.086           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.982           ms/op
ClientGrpc.getUser                        sample  306815   3.129 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.510           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.590           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.016           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  244957   3.916 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.079           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.407           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.335           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.956           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.757           ms/op
