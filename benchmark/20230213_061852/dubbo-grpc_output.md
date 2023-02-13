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
# Warmup Iteration   1: 4.250 ops/ms
# Warmup Iteration   2: 9.229 ops/ms
# Warmup Iteration   3: 9.868 ops/ms
Iteration   1: 9.929 ops/ms
Iteration   2: 10.216 ops/ms
Iteration   3: 10.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.095 ±(99.9%) 2.719 ops/ms [Average]
  (min, avg, max) = (9.929, 10.095, 10.216), stdev = 0.149
  CI (99.9%): [7.376, 12.814] (assumes normal distribution)


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
# Warmup Iteration   1: 7.320 ops/ms
# Warmup Iteration   2: 10.096 ops/ms
# Warmup Iteration   3: 10.368 ops/ms
Iteration   1: 10.560 ops/ms
Iteration   2: 10.371 ops/ms
Iteration   3: 10.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.455 ±(99.9%) 1.754 ops/ms [Average]
  (min, avg, max) = (10.371, 10.455, 10.560), stdev = 0.096
  CI (99.9%): [8.701, 12.209] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.849 ops/ms
# Warmup Iteration   2: 9.946 ops/ms
# Warmup Iteration   3: 10.110 ops/ms
Iteration   1: 10.144 ops/ms
Iteration   2: 9.923 ops/ms
Iteration   3: 10.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.046 ±(99.9%) 2.054 ops/ms [Average]
  (min, avg, max) = (9.923, 10.046, 10.144), stdev = 0.113
  CI (99.9%): [7.992, 12.100] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.241 ops/ms
# Warmup Iteration   2: 7.569 ops/ms
# Warmup Iteration   3: 7.532 ops/ms
Iteration   1: 7.890 ops/ms
Iteration   2: 7.944 ops/ms
Iteration   3: 7.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.896 ±(99.9%) 0.831 ops/ms [Average]
  (min, avg, max) = (7.853, 7.896, 7.944), stdev = 0.046
  CI (99.9%): [7.065, 8.727] (assumes normal distribution)


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
# Warmup Iteration   1: 4.941 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.003 ms/op
Iteration   1: 3.221 ±(99.9%) 0.011 ms/op
Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
Iteration   3: 3.295 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.225 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (3.159, 3.225, 3.295), stdev = 0.068
  CI (99.9%): [1.988, 4.462] (assumes normal distribution)


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.002 ms/op
Iteration   1: 3.087 ±(99.9%) 0.002 ms/op
Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
Iteration   3: 3.062 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.082 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (3.062, 3.082, 3.096), stdev = 0.017
  CI (99.9%): [2.765, 3.398] (assumes normal distribution)


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.003 ms/op
Iteration   1: 3.272 ±(99.9%) 0.002 ms/op
Iteration   2: 3.250 ±(99.9%) 0.002 ms/op
Iteration   3: 3.215 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.246 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (3.215, 3.246, 3.272), stdev = 0.029
  CI (99.9%): [2.722, 3.769] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.030 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.022 ms/op
Iteration   1: 4.120 ±(99.9%) 0.006 ms/op
Iteration   2: 4.072 ±(99.9%) 0.007 ms/op
Iteration   3: 4.092 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.095 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (4.072, 4.095, 4.120), stdev = 0.024
  CI (99.9%): [3.661, 4.528] (assumes normal distribution)


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.579 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  10.486 ms/op
                 createUser·p0.9999: 13.028 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 16.414 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   3: 3.238 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  9.634 ms/op
                 createUser·p0.9999: 16.945 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302418
  mean =      3.173 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 526 
    [ 1.250,  2.500) = 20471 
    [ 2.500,  3.750) = 243942 
    [ 3.750,  5.000) = 35768 
    [ 5.000,  6.250) = 756 
    [ 6.250,  7.500) = 453 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =     11.265 ms/op
     p(99.9900) =     16.531 ms/op
     p(99.9990) =     17.752 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.075 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.947 ms/op
                 existUser·p0.9999: 13.628 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.295 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.092 ms/op
                 existUser·p0.9999: 21.758 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  9.291 ms/op
                 existUser·p0.9999: 17.616 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313061
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33640 
    [ 2.500,  5.000) = 278542 
    [ 5.000,  7.500) = 631 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.295 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     21.093 ms/op
     p(99.9990) =     21.913 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 4.381 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
Iteration   1: 3.186 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.896 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.074 ms/op
                 getUser·p0.9999: 13.255 ms/op
                 getUser·p1.00:   13.533 ms/op

Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.608 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.446 ms/op
                 getUser·p0.9999: 14.564 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 3.161 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 17.854 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302631
  mean =      3.173 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 574 
    [ 1.250,  2.500) = 19370 
    [ 2.500,  3.750) = 242814 
    [ 3.750,  5.000) = 38660 
    [ 5.000,  6.250) = 660 
    [ 6.250,  7.500) = 300 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.269 ms/op
     p(99.9900) =     16.351 ms/op
     p(99.9990) =     18.381 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 6.040 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.011 ms/op
Iteration   1: 4.064 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 17.868 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   2: 4.056 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  19.337 ms/op
                 listUser·p0.9999: 21.765 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   3: 4.115 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  16.480 ms/op
                 listUser·p0.9999: 21.359 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235416
  mean =      4.078 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2272 
    [ 2.500,  5.000) = 205625 
    [ 5.000,  7.500) = 25907 
    [ 7.500, 10.000) = 1156 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.853 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.602 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.095 ± 2.719  ops/ms
ClientGrpc.existUser                       thrpt       3  10.455 ± 1.754  ops/ms
ClientGrpc.getUser                         thrpt       3  10.046 ± 2.054  ops/ms
ClientGrpc.listUser                        thrpt       3   7.896 ± 0.831  ops/ms
ClientGrpc.createUser                       avgt       3   3.225 ± 1.237   ms/op
ClientGrpc.existUser                        avgt       3   3.082 ± 0.317   ms/op
ClientGrpc.getUser                          avgt       3   3.246 ± 0.524   ms/op
ClientGrpc.listUser                         avgt       3   4.095 ± 0.433   ms/op
ClientGrpc.createUser                     sample  302418   3.173 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.579           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.265           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.531           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.924           ms/op
ClientGrpc.existUser                      sample  313061   3.067 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.295           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.944           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.930           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.093           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.053           ms/op
ClientGrpc.getUser                        sample  302631   3.173 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.608           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.150           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.063           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.269           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.351           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.711           ms/op
ClientGrpc.listUser                       sample  235416   4.078 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.964           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.853           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.332           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.741           ms/op
