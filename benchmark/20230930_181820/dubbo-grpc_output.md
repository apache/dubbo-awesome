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
# Warmup Iteration   1: 4.731 ops/ms
# Warmup Iteration   2: 9.343 ops/ms
# Warmup Iteration   3: 10.066 ops/ms
Iteration   1: 10.360 ops/ms
Iteration   2: 10.401 ops/ms
Iteration   3: 10.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.372 ±(99.9%) 0.466 ops/ms [Average]
  (min, avg, max) = (10.355, 10.372, 10.401), stdev = 0.026
  CI (99.9%): [9.906, 10.838] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.564 ops/ms
# Warmup Iteration   2: 10.274 ops/ms
# Warmup Iteration   3: 10.589 ops/ms
Iteration   1: 10.933 ops/ms
Iteration   2: 10.707 ops/ms
Iteration   3: 10.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.725 ±(99.9%) 3.632 ops/ms [Average]
  (min, avg, max) = (10.536, 10.725, 10.933), stdev = 0.199
  CI (99.9%): [7.093, 14.358] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.795 ops/ms
# Warmup Iteration   2: 10.019 ops/ms
# Warmup Iteration   3: 10.197 ops/ms
Iteration   1: 10.366 ops/ms
Iteration   2: 10.467 ops/ms
Iteration   3: 10.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.362 ±(99.9%) 1.942 ops/ms [Average]
  (min, avg, max) = (10.254, 10.362, 10.467), stdev = 0.106
  CI (99.9%): [8.421, 12.304] (assumes normal distribution)


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
# Warmup Iteration   1: 6.429 ops/ms
# Warmup Iteration   2: 7.949 ops/ms
# Warmup Iteration   3: 8.112 ops/ms
Iteration   1: 8.093 ops/ms
Iteration   2: 8.324 ops/ms
Iteration   3: 8.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.244 ±(99.9%) 2.378 ops/ms [Average]
  (min, avg, max) = (8.093, 8.244, 8.324), stdev = 0.130
  CI (99.9%): [5.866, 10.621] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 3.096 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 3.140 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.092 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (3.040, 3.092, 3.140), stdev = 0.050
  CI (99.9%): [2.177, 4.007] (assumes normal distribution)


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 2.934 ±(99.9%) 0.002 ms/op
Iteration   2: 2.929 ±(99.9%) 0.002 ms/op
Iteration   3: 2.927 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (2.927, 2.930, 2.934), stdev = 0.004
  CI (99.9%): [2.865, 2.995] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.011 ms/op
Iteration   1: 3.138 ±(99.9%) 0.001 ms/op
Iteration   2: 3.120 ±(99.9%) 0.002 ms/op
Iteration   3: 3.068 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.108 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (3.068, 3.108, 3.138), stdev = 0.037
  CI (99.9%): [2.440, 3.777] (assumes normal distribution)


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
# Warmup Iteration   1: 5.377 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
Iteration   1: 3.840 ±(99.9%) 0.008 ms/op
Iteration   2: 3.750 ±(99.9%) 0.032 ms/op
Iteration   3: 3.836 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.808 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (3.750, 3.808, 3.840), stdev = 0.051
  CI (99.9%): [2.882, 4.735] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.044 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  10.224 ms/op
                 createUser·p0.9999: 18.858 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  9.550 ms/op
                 createUser·p0.9999: 20.567 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  8.266 ms/op
                 createUser·p0.9999: 21.461 ms/op
                 createUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313963
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15024 
    [ 2.500,  5.000) = 296501 
    [ 5.000,  7.500) = 1831 
    [ 7.500, 10.000) = 336 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.422 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 3.761 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 2.931 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.996 ms/op
                 existUser·p0.9999: 12.666 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.989 ms/op
                 existUser·p0.9999: 13.420 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.979 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  10.103 ms/op
                 existUser·p0.9999: 14.471 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326056
  mean =      2.945 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2042 
    [ 1.250,  2.500) = 25894 
    [ 2.500,  3.750) = 288024 
    [ 3.750,  5.000) = 8344 
    [ 5.000,  6.250) = 814 
    [ 6.250,  7.500) = 538 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     13.556 ms/op
     p(99.9990) =     14.712 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
Iteration   1: 3.150 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  11.796 ms/op
                 getUser·p0.9999: 12.993 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 3.151 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  9.224 ms/op
                 getUser·p0.9999: 13.678 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   3: 3.123 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  11.683 ms/op
                 getUser·p0.9999: 20.373 ms/op
                 getUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305755
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11943 
    [ 2.500,  5.000) = 291363 
    [ 5.000,  7.500) = 1749 
    [ 7.500, 10.000) = 359 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     10.592 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     20.771 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.402 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.009 ms/op
Iteration   1: 3.902 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   6.671 ms/op
                 listUser·p0.999:  11.813 ms/op
                 listUser·p0.9999: 13.248 ms/op
                 listUser·p1.00:   14.631 ms/op

Iteration   2: 3.895 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.699 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.969 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 3.881 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.459 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246728
  mean =      3.893 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1983 
    [ 2.500,  5.000) = 233513 
    [ 5.000,  7.500) = 10209 
    [ 7.500, 10.000) = 542 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     18.066 ms/op
     p(99.9990) =     23.456 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.372 ± 0.466  ops/ms
ClientGrpc.existUser                       thrpt       3  10.725 ± 3.632  ops/ms
ClientGrpc.getUser                         thrpt       3  10.362 ± 1.942  ops/ms
ClientGrpc.listUser                        thrpt       3   8.244 ± 2.378  ops/ms
ClientGrpc.createUser                       avgt       3   3.092 ± 0.915   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.065   ms/op
ClientGrpc.getUser                          avgt       3   3.108 ± 0.668   ms/op
ClientGrpc.listUser                         avgt       3   3.808 ± 0.926   ms/op
ClientGrpc.createUser                     sample  313963   3.058 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.671           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.422           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.414           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.955           ms/op
ClientGrpc.existUser                      sample  326056   2.945 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.540           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.987           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.556           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.844           ms/op
ClientGrpc.getUser                        sample  305755   3.141 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.705           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.592           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.793           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.873           ms/op
ClientGrpc.listUser                       sample  246728   3.893 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.699           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.293           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.730           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.066           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.543           ms/op
