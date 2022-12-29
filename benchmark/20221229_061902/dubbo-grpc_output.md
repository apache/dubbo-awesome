# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.980 ops/ms
# Warmup Iteration   2: 5.013 ops/ms
# Warmup Iteration   3: 6.645 ops/ms
Iteration   1: 7.085 ops/ms
Iteration   2: 7.208 ops/ms
Iteration   3: 6.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.078 ±(99.9%) 2.442 ops/ms [Average]
  (min, avg, max) = (6.941, 7.078, 7.208), stdev = 0.134
  CI (99.9%): [4.636, 9.520] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.301 ops/ms
# Warmup Iteration   2: 6.586 ops/ms
# Warmup Iteration   3: 6.911 ops/ms
Iteration   1: 7.341 ops/ms
Iteration   2: 7.753 ops/ms
Iteration   3: 7.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.569 ±(99.9%) 3.822 ops/ms [Average]
  (min, avg, max) = (7.341, 7.569, 7.753), stdev = 0.209
  CI (99.9%): [3.748, 11.391] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.290 ops/ms
# Warmup Iteration   2: 5.977 ops/ms
# Warmup Iteration   3: 6.540 ops/ms
Iteration   1: 6.751 ops/ms
Iteration   2: 6.909 ops/ms
Iteration   3: 6.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.861 ±(99.9%) 1.741 ops/ms [Average]
  (min, avg, max) = (6.751, 6.861, 6.922), stdev = 0.095
  CI (99.9%): [5.120, 8.601] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.494 ops/ms
# Warmup Iteration   2: 5.066 ops/ms
# Warmup Iteration   3: 5.779 ops/ms
Iteration   1: 5.610 ops/ms
Iteration   2: 5.498 ops/ms
Iteration   3: 5.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.607 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (5.498, 5.607, 5.712), stdev = 0.107
  CI (99.9%): [3.662, 7.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.831 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.676 ±(99.9%) 0.003 ms/op
Iteration   1: 4.491 ±(99.9%) 0.009 ms/op
Iteration   2: 4.396 ±(99.9%) 0.003 ms/op
Iteration   3: 4.418 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.435 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (4.396, 4.435, 4.491), stdev = 0.050
  CI (99.9%): [3.531, 5.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.903 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.680 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.003 ms/op
Iteration   1: 4.348 ±(99.9%) 0.003 ms/op
Iteration   2: 4.148 ±(99.9%) 0.002 ms/op
Iteration   3: 4.295 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.263 ±(99.9%) 1.889 ms/op [Average]
  (min, avg, max) = (4.148, 4.263, 4.348), stdev = 0.104
  CI (99.9%): [2.375, 6.152] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.431 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.838 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.793 ±(99.9%) 0.005 ms/op
Iteration   1: 4.524 ±(99.9%) 0.004 ms/op
Iteration   2: 4.684 ±(99.9%) 0.003 ms/op
Iteration   3: 4.600 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.603 ±(99.9%) 1.454 ms/op [Average]
  (min, avg, max) = (4.524, 4.603, 4.684), stdev = 0.080
  CI (99.9%): [3.149, 6.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.980 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 6.767 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.840 ±(99.9%) 0.012 ms/op
Iteration   1: 5.753 ±(99.9%) 0.012 ms/op
Iteration   2: 5.778 ±(99.9%) 0.017 ms/op
Iteration   3: 5.679 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.737 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (5.679, 5.737, 5.778), stdev = 0.051
  CI (99.9%): [4.801, 6.673] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.985 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.719 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.015 ms/op
Iteration   1: 4.495 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   4.366 ms/op
                 createUser·p0.90:   5.751 ms/op
                 createUser·p0.95:   6.193 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  9.440 ms/op
                 createUser·p0.9999: 21.596 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 4.660 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   5.915 ms/op
                 createUser·p0.95:   6.324 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  13.552 ms/op
                 createUser·p0.9999: 22.440 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 4.509 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  25.292 ms/op
                 createUser·p0.9999: 35.389 ms/op
                 createUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 210840
  mean =      4.553 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2414 
    [ 2.500,  5.000) = 146498 
    [ 5.000,  7.500) = 60022 
    [ 7.500, 10.000) = 1496 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.800 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     14.191 ms/op
     p(99.9900) =     35.122 ms/op
     p(99.9990) =     35.579 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.383 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.013 ms/op
Iteration   1: 4.535 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   4.456 ms/op
                 existUser·p0.90:   5.751 ms/op
                 existUser·p0.95:   6.128 ms/op
                 existUser·p0.99:   7.381 ms/op
                 existUser·p0.999:  10.895 ms/op
                 existUser·p0.9999: 19.263 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   2: 4.334 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   5.546 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  9.636 ms/op
                 existUser·p0.9999: 22.048 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   3: 4.479 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   5.857 ms/op
                 existUser·p0.95:   6.193 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  13.697 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 215771
  mean =      4.448 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5209 
    [ 2.500,  5.000) = 151237 
    [ 5.000,  7.500) = 57902 
    [ 7.500, 10.000) = 1066 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     12.947 ms/op
     p(99.9900) =     22.375 ms/op
     p(99.9990) =     23.129 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.762 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.005 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.685 ±(99.9%) 0.013 ms/op
Iteration   1: 4.683 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   7.376 ms/op
                 getUser·p0.999:  9.988 ms/op
                 getUser·p0.9999: 18.830 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   2: 4.744 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   4.678 ms/op
                 getUser·p0.90:   6.070 ms/op
                 getUser·p0.95:   6.463 ms/op
                 getUser·p0.99:   7.455 ms/op
                 getUser·p0.999:  14.324 ms/op
                 getUser·p0.9999: 20.375 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   3: 4.705 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   6.029 ms/op
                 getUser·p0.95:   6.463 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  12.155 ms/op
                 getUser·p0.9999: 22.301 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 203859
  mean =      4.711 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2236 
    [ 2.500,  5.000) = 128717 
    [ 5.000,  7.500) = 70901 
    [ 7.500, 10.000) = 1634 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     12.028 ms/op
     p(99.9900) =     20.487 ms/op
     p(99.9990) =     22.737 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.662 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.375 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.955 ±(99.9%) 0.026 ms/op
Iteration   1: 5.789 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.897 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  18.900 ms/op
                 listUser·p0.9999: 26.506 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 6.052 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   8.315 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   11.518 ms/op
                 listUser·p0.999:  18.047 ms/op
                 listUser·p0.9999: 22.601 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 5.872 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   8.159 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  22.872 ms/op
                 listUser·p0.9999: 27.776 ms/op
                 listUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 162529
  mean =      5.902 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 145 
    [ 2.500,  5.000) = 56973 
    [ 5.000,  7.500) = 79029 
    [ 7.500, 10.000) = 21954 
    [10.000, 12.500) = 3715 
    [12.500, 15.000) = 394 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      8.135 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     11.284 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     30.204 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.078 ± 2.442  ops/ms
ClientGrpc.existUser                       thrpt       3   7.569 ± 3.822  ops/ms
ClientGrpc.getUser                         thrpt       3   6.861 ± 1.741  ops/ms
ClientGrpc.listUser                        thrpt       3   5.607 ± 1.945  ops/ms
ClientGrpc.createUser                       avgt       3   4.435 ± 0.904   ms/op
ClientGrpc.existUser                        avgt       3   4.263 ± 1.889   ms/op
ClientGrpc.getUser                          avgt       3   4.603 ± 1.454   ms/op
ClientGrpc.listUser                         avgt       3   5.737 ± 0.936   ms/op
ClientGrpc.createUser                     sample  210840   4.553 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.781           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.800           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.226           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.406           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.191           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.122           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.586           ms/op
ClientGrpc.existUser                      sample  215771   4.448 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.974           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.726           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.103           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.021           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.947           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.375           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.200           ms/op
ClientGrpc.getUser                        sample  203859   4.711 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.821           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.013           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.431           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.487           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.028           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.487           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.839           ms/op
ClientGrpc.listUser                       sample  162529   5.902 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.593           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.135           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.110           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.284           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.628           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.771           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.245           ms/op
