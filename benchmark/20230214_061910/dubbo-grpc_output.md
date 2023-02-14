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
# Warmup Iteration   1: 4.024 ops/ms
# Warmup Iteration   2: 8.674 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 10.208 ops/ms
Iteration   2: 10.043 ops/ms
Iteration   3: 9.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.000 ±(99.9%) 4.259 ops/ms [Average]
  (min, avg, max) = (9.748, 10.000, 10.208), stdev = 0.233
  CI (99.9%): [5.741, 14.259] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.762 ops/ms
# Warmup Iteration   2: 9.991 ops/ms
# Warmup Iteration   3: 10.560 ops/ms
Iteration   1: 10.331 ops/ms
Iteration   2: 10.888 ops/ms
Iteration   3: 10.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.621 ±(99.9%) 5.093 ops/ms [Average]
  (min, avg, max) = (10.331, 10.621, 10.888), stdev = 0.279
  CI (99.9%): [5.528, 15.714] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.434 ops/ms
# Warmup Iteration   2: 9.887 ops/ms
# Warmup Iteration   3: 10.108 ops/ms
Iteration   1: 10.091 ops/ms
Iteration   2: 10.173 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.182 ±(99.9%) 1.760 ops/ms [Average]
  (min, avg, max) = (10.091, 10.182, 10.283), stdev = 0.096
  CI (99.9%): [8.423, 11.942] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.522 ops/ms
# Warmup Iteration   2: 7.416 ops/ms
# Warmup Iteration   3: 7.945 ops/ms
Iteration   1: 7.710 ops/ms
Iteration   2: 7.813 ops/ms
Iteration   3: 7.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.790 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (7.710, 7.790, 7.847), stdev = 0.072
  CI (99.9%): [6.482, 9.097] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.177 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.003 ms/op
Iteration   1: 3.189 ±(99.9%) 0.012 ms/op
Iteration   2: 3.189 ±(99.9%) 0.002 ms/op
Iteration   3: 3.226 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.201 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.189, 3.201, 3.226), stdev = 0.022
  CI (99.9%): [2.808, 3.594] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.711 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.005 ms/op
Iteration   1: 3.027 ±(99.9%) 0.002 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.992 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (2.940, 2.992, 3.027), stdev = 0.046
  CI (99.9%): [2.159, 3.824] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.004 ms/op
Iteration   1: 3.175 ±(99.9%) 0.002 ms/op
Iteration   2: 3.209 ±(99.9%) 0.002 ms/op
Iteration   3: 3.204 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.196 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.175, 3.196, 3.209), stdev = 0.019
  CI (99.9%): [2.856, 3.536] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.591 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.028 ms/op
Iteration   1: 4.051 ±(99.9%) 0.026 ms/op
Iteration   2: 4.003 ±(99.9%) 0.010 ms/op
Iteration   3: 4.046 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.033 ±(99.9%) 0.486 ms/op [Average]
  (min, avg, max) = (4.003, 4.033, 4.051), stdev = 0.027
  CI (99.9%): [3.547, 4.520] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
Iteration   1: 3.170 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.385 ms/op
                 createUser·p0.999:  7.822 ms/op
                 createUser·p0.9999: 12.923 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  6.883 ms/op
                 createUser·p0.9999: 15.462 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   3: 3.243 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  12.468 ms/op
                 createUser·p0.9999: 18.289 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302476
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22898 
    [ 2.500,  5.000) = 278709 
    [ 5.000,  7.500) = 530 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.857 ms/op
     p(99.9900) =     17.228 ms/op
     p(99.9990) =     18.676 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.775 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.414 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.456 ms/op
                 existUser·p0.9999: 13.960 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 3.036 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.461 ms/op
                 existUser·p0.9999: 25.214 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  12.075 ms/op
                 existUser·p0.9999: 19.150 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320994
  mean =      2.988 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49952 
    [ 2.500,  5.000) = 270022 
    [ 5.000,  7.500) = 625 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     10.601 ms/op
     p(99.9900) =     23.490 ms/op
     p(99.9990) =     25.473 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.059 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.389 ms/op
                 getUser·p0.9999: 13.690 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 3.174 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.338 ms/op
                 getUser·p0.9999: 18.872 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  10.214 ms/op
                 getUser·p0.9999: 20.281 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303440
  mean =      3.162 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23964 
    [ 2.500,  5.000) = 278328 
    [ 5.000,  7.500) = 869 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.410 ms/op
     p(99.9900) =     19.224 ms/op
     p(99.9990) =     20.674 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 5.393 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.011 ms/op
Iteration   1: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.794 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 4.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.226 ms/op
                 listUser·p0.9999: 17.502 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 4.063 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  17.370 ms/op
                 listUser·p0.9999: 28.361 ms/op
                 listUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237637
  mean =      4.041 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2650 
    [ 2.500,  5.000) = 207753 
    [ 5.000,  7.500) = 25938 
    [ 7.500, 10.000) = 840 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.719 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     28.942 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.000 ± 4.259  ops/ms
ClientGrpc.existUser                       thrpt       3  10.621 ± 5.093  ops/ms
ClientGrpc.getUser                         thrpt       3  10.182 ± 1.760  ops/ms
ClientGrpc.listUser                        thrpt       3   7.790 ± 1.307  ops/ms
ClientGrpc.createUser                       avgt       3   3.201 ± 0.393   ms/op
ClientGrpc.existUser                        avgt       3   2.992 ± 0.833   ms/op
ClientGrpc.getUser                          avgt       3   3.196 ± 0.340   ms/op
ClientGrpc.listUser                         avgt       3   4.033 ± 0.486   ms/op
ClientGrpc.createUser                     sample  302476   3.176 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.648           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.857           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.228           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.510           ms/op
ClientGrpc.existUser                      sample  320994   2.988 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.414           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.601           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.490           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.592           ms/op
ClientGrpc.getUser                        sample  303440   3.162 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.506           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.410           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.224           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.808           ms/op
ClientGrpc.listUser                       sample  237637   4.041 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.180           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.719           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.706           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.065           ms/op
