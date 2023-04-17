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
# Warmup Iteration   1: 4.222 ops/ms
# Warmup Iteration   2: 8.957 ops/ms
# Warmup Iteration   3: 9.833 ops/ms
Iteration   1: 10.314 ops/ms
Iteration   2: 10.388 ops/ms
Iteration   3: 11.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.579 ±(99.9%) 7.256 ops/ms [Average]
  (min, avg, max) = (10.314, 10.579, 11.037), stdev = 0.398
  CI (99.9%): [3.323, 17.836] (assumes normal distribution)


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
# Warmup Iteration   1: 7.824 ops/ms
# Warmup Iteration   2: 11.278 ops/ms
# Warmup Iteration   3: 11.366 ops/ms
Iteration   1: 11.724 ops/ms
Iteration   2: 11.404 ops/ms
Iteration   3: 11.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.610 ±(99.9%) 3.262 ops/ms [Average]
  (min, avg, max) = (11.404, 11.610, 11.724), stdev = 0.179
  CI (99.9%): [8.348, 14.872] (assumes normal distribution)


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
# Warmup Iteration   1: 7.375 ops/ms
# Warmup Iteration   2: 10.731 ops/ms
# Warmup Iteration   3: 10.991 ops/ms
Iteration   1: 11.021 ops/ms
Iteration   2: 10.576 ops/ms
Iteration   3: 10.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.826 ±(99.9%) 4.143 ops/ms [Average]
  (min, avg, max) = (10.576, 10.826, 11.021), stdev = 0.227
  CI (99.9%): [6.682, 14.969] (assumes normal distribution)


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
# Warmup Iteration   1: 5.302 ops/ms
# Warmup Iteration   2: 7.695 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 7.988 ops/ms
Iteration   2: 8.058 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.035 ±(99.9%) 0.741 ops/ms [Average]
  (min, avg, max) = (7.988, 8.035, 8.060), stdev = 0.041
  CI (99.9%): [7.294, 8.777] (assumes normal distribution)


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.010 ms/op
Iteration   1: 3.066 ±(99.9%) 0.003 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 2.998 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (2.998, 3.037, 3.066), stdev = 0.035
  CI (99.9%): [2.393, 3.681] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.003 ms/op
Iteration   1: 2.924 ±(99.9%) 0.002 ms/op
Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
Iteration   3: 2.877 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (2.877, 2.914, 2.939), stdev = 0.032
  CI (99.9%): [2.324, 3.503] (assumes normal distribution)


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
# Warmup Iteration   1: 4.588 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.003 ms/op
Iteration   1: 3.157 ±(99.9%) 0.003 ms/op
Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.107 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.041, 3.107, 3.157), stdev = 0.060
  CI (99.9%): [2.018, 4.197] (assumes normal distribution)


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
# Warmup Iteration   1: 5.657 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.036 ms/op
Iteration   1: 3.958 ±(99.9%) 0.014 ms/op
Iteration   2: 3.931 ±(99.9%) 0.027 ms/op
Iteration   3: 3.887 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.926 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (3.887, 3.926, 3.958), stdev = 0.036
  CI (99.9%): [3.271, 4.580] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.472 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  9.715 ms/op
                 createUser·p0.9999: 13.222 ms/op
                 createUser·p1.00:   13.468 ms/op

Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.813 ms/op
                 createUser·p0.9999: 14.628 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.119 ms/op
                 createUser·p0.9999: 17.877 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316283
  mean =      3.036 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 21938 
    [ 2.500,  3.750) = 277901 
    [ 3.750,  5.000) = 14817 
    [ 5.000,  6.250) = 569 
    [ 6.250,  7.500) = 192 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     16.663 ms/op
     p(99.9990) =     18.176 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.934 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.007 ms/op
Iteration   1: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  9.062 ms/op
                 existUser·p0.9999: 14.223 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.902 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.779 ms/op
                 existUser·p0.9999: 14.729 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.948 ms/op
                 existUser·p0.9999: 17.565 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329023
  mean =      2.919 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1673 
    [ 1.250,  2.500) = 34603 
    [ 2.500,  3.750) = 280542 
    [ 3.750,  5.000) = 11012 
    [ 5.000,  6.250) = 640 
    [ 6.250,  7.500) = 245 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.086 ms/op
     p(99.9900) =     16.846 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.567 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.077 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.341 ms/op
                 getUser·p0.9999: 16.610 ms/op
                 getUser·p1.00:   17.891 ms/op

Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.987 ms/op
                 getUser·p0.9999: 14.713 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 19.202 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316185
  mean =      3.036 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 663 
    [ 1.250,  2.500) = 17542 
    [ 2.500,  3.750) = 279485 
    [ 3.750,  5.000) = 17194 
    [ 5.000,  6.250) = 739 
    [ 6.250,  7.500) = 266 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.356 ms/op
     p(99.9900) =     17.929 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 5.338 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.011 ms/op
Iteration   1: 4.077 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 16.719 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.778 ms/op
                 listUser·p0.9999: 22.349 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   3: 4.135 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.305 ms/op
                 listUser·p0.999:  15.773 ms/op
                 listUser·p0.9999: 22.249 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235677
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2750 
    [ 2.500,  5.000) = 203543 
    [ 5.000,  7.500) = 27587 
    [ 7.500, 10.000) = 1365 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     23.034 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.579 ± 7.256  ops/ms
ClientGrpc.existUser                       thrpt       3  11.610 ± 3.262  ops/ms
ClientGrpc.getUser                         thrpt       3  10.826 ± 4.143  ops/ms
ClientGrpc.listUser                        thrpt       3   8.035 ± 0.741  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.644   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 0.589   ms/op
ClientGrpc.getUser                          avgt       3   3.107 ± 1.089   ms/op
ClientGrpc.listUser                         avgt       3   3.926 ± 0.655   ms/op
ClientGrpc.createUser                     sample  316283   3.036 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.705           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.077           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.663           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.317           ms/op
ClientGrpc.existUser                      sample  329023   2.919 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.782           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.086           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.846           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.957           ms/op
ClientGrpc.getUser                        sample  316185   3.036 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.731           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.356           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.929           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.235           ms/op
ClientGrpc.listUser                       sample  235677   4.071 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.868           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.319           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.103           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
