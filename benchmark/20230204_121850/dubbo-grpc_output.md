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
# Warmup Iteration   1: 4.088 ops/ms
# Warmup Iteration   2: 9.017 ops/ms
# Warmup Iteration   3: 10.237 ops/ms
Iteration   1: 9.929 ops/ms
Iteration   2: 9.985 ops/ms
Iteration   3: 10.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.017 ±(99.9%) 1.976 ops/ms [Average]
  (min, avg, max) = (9.929, 10.017, 10.138), stdev = 0.108
  CI (99.9%): [8.041, 11.993] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.418 ops/ms
# Warmup Iteration   2: 10.271 ops/ms
# Warmup Iteration   3: 10.934 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.654 ops/ms
Iteration   3: 11.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.746 ±(99.9%) 5.569 ops/ms [Average]
  (min, avg, max) = (10.498, 10.746, 11.087), stdev = 0.305
  CI (99.9%): [5.177, 16.316] (assumes normal distribution)


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
# Warmup Iteration   1: 7.075 ops/ms
# Warmup Iteration   2: 9.819 ops/ms
# Warmup Iteration   3: 10.193 ops/ms
Iteration   1: 10.143 ops/ms
Iteration   2: 10.309 ops/ms
Iteration   3: 10.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.172 ±(99.9%) 2.290 ops/ms [Average]
  (min, avg, max) = (10.063, 10.172, 10.309), stdev = 0.126
  CI (99.9%): [7.882, 12.461] (assumes normal distribution)


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
# Warmup Iteration   1: 5.536 ops/ms
# Warmup Iteration   2: 7.702 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 7.964 ops/ms
Iteration   2: 8.029 ops/ms
Iteration   3: 7.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.981 ±(99.9%) 0.763 ops/ms [Average]
  (min, avg, max) = (7.951, 7.981, 8.029), stdev = 0.042
  CI (99.9%): [7.218, 8.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.003 ms/op
Iteration   1: 3.138 ±(99.9%) 0.003 ms/op
Iteration   2: 3.170 ±(99.9%) 0.002 ms/op
Iteration   3: 3.105 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.138 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (3.105, 3.138, 3.170), stdev = 0.032
  CI (99.9%): [2.545, 3.730] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.004 ms/op
Iteration   1: 3.078 ±(99.9%) 0.005 ms/op
Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
Iteration   3: 3.070 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.048 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (2.995, 3.048, 3.078), stdev = 0.046
  CI (99.9%): [2.208, 3.887] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.443 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.002 ms/op
Iteration   1: 3.147 ±(99.9%) 0.003 ms/op
Iteration   2: 3.209 ±(99.9%) 0.002 ms/op
Iteration   3: 3.171 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.176 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.147, 3.176, 3.209), stdev = 0.031
  CI (99.9%): [2.606, 3.745] (assumes normal distribution)


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
# Warmup Iteration   1: 5.418 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.013 ms/op
Iteration   1: 3.955 ±(99.9%) 0.010 ms/op
Iteration   2: 4.035 ±(99.9%) 0.022 ms/op
Iteration   3: 3.919 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.970 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (3.919, 3.970, 4.035), stdev = 0.060
  CI (99.9%): [2.883, 5.057] (assumes normal distribution)


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
Iteration   1: 3.158 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.799 ms/op
                 createUser·p0.9999: 15.300 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 3.152 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.873 ms/op
                 createUser·p0.9999: 16.777 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   3: 3.305 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  6.988 ms/op
                 createUser·p0.9999: 21.550 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299662
  mean =      3.204 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18097 
    [ 2.500,  5.000) = 280483 
    [ 5.000,  7.500) = 823 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.171 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.273 ms/op
                 existUser·p0.999:  8.959 ms/op
                 existUser·p0.9999: 12.711 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   2: 2.953 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.136 ms/op
                 existUser·p0.9999: 14.397 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   3: 2.964 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.012 ms/op
                 existUser·p0.9999: 28.803 ms/op
                 existUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321908
  mean =      2.981 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52576 
    [ 2.500,  5.000) = 268333 
    [ 5.000,  7.500) = 627 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.089 ms/op
     p(99.9900) =     26.161 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.006 ms/op
Iteration   1: 3.172 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  9.948 ms/op
                 getUser·p0.9999: 13.681 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 3.140 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.363 ms/op
                 getUser·p0.999:  6.768 ms/op
                 getUser·p0.9999: 14.180 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.459 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302134
  mean =      3.175 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 519 
    [ 1.250,  2.500) = 19872 
    [ 2.500,  3.750) = 241088 
    [ 3.750,  5.000) = 39389 
    [ 5.000,  6.250) = 668 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.560 ms/op
     p(99.9900) =     17.812 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 5.703 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
Iteration   1: 4.057 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.586 ms/op
                 listUser·p0.9999: 20.028 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 4.059 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 16.230 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 4.080 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  16.841 ms/op
                 listUser·p0.9999: 24.909 ms/op
                 listUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236292
  mean =      4.065 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2221 
    [ 2.500,  5.000) = 205834 
    [ 5.000,  7.500) = 26731 
    [ 7.500, 10.000) = 1053 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     14.823 ms/op
     p(99.9900) =     23.540 ms/op
     p(99.9990) =     25.175 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.017 ± 1.976  ops/ms
ClientGrpc.existUser                       thrpt       3  10.746 ± 5.569  ops/ms
ClientGrpc.getUser                         thrpt       3  10.172 ± 2.290  ops/ms
ClientGrpc.listUser                        thrpt       3   7.981 ± 0.763  ops/ms
ClientGrpc.createUser                       avgt       3   3.138 ± 0.593   ms/op
ClientGrpc.existUser                        avgt       3   3.048 ± 0.839   ms/op
ClientGrpc.getUser                          avgt       3   3.176 ± 0.569   ms/op
ClientGrpc.listUser                         avgt       3   3.970 ± 1.087   ms/op
ClientGrpc.createUser                     sample  299662   3.204 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.655           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.174           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.171           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.677           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.086           ms/op
ClientGrpc.existUser                      sample  321908   2.981 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.698           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.875           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.089           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.161           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.000           ms/op
ClientGrpc.getUser                        sample  302134   3.175 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.755           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.146           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.026           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.560           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.812           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.268           ms/op
ClientGrpc.listUser                       sample  236292   4.065 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.081           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.823           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.540           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.461           ms/op
