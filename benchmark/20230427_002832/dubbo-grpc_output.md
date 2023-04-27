# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.651 ops/ms
# Warmup Iteration   2: 8.305 ops/ms
# Warmup Iteration   3: 10.143 ops/ms
Iteration   1: 10.635 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 10.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.681 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (10.635, 10.681, 10.771), stdev = 0.078
  CI (99.9%): [9.263, 12.100] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.596 ops/ms
# Warmup Iteration   2: 10.602 ops/ms
# Warmup Iteration   3: 11.071 ops/ms
Iteration   1: 10.953 ops/ms
Iteration   2: 11.314 ops/ms
Iteration   3: 11.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.095 ±(99.9%) 3.513 ops/ms [Average]
  (min, avg, max) = (10.953, 11.095, 11.314), stdev = 0.193
  CI (99.9%): [7.582, 14.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.917 ops/ms
# Warmup Iteration   2: 10.264 ops/ms
# Warmup Iteration   3: 10.711 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.846 ops/ms
Iteration   3: 10.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.713 ±(99.9%) 2.191 ops/ms [Average]
  (min, avg, max) = (10.614, 10.713, 10.846), stdev = 0.120
  CI (99.9%): [8.522, 12.903] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.730 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 8.120 ops/ms
Iteration   1: 8.048 ops/ms
Iteration   2: 8.200 ops/ms
Iteration   3: 8.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.128 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (8.048, 8.128, 8.200), stdev = 0.076
  CI (99.9%): [6.741, 9.515] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.308 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.003 ms/op
Iteration   1: 3.050 ±(99.9%) 0.005 ms/op
Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (3.028, 3.037, 3.050), stdev = 0.012
  CI (99.9%): [2.823, 3.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.003 ms/op
Iteration   1: 2.842 ±(99.9%) 0.002 ms/op
Iteration   2: 2.844 ±(99.9%) 0.003 ms/op
Iteration   3: 2.927 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.871 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (2.842, 2.871, 2.927), stdev = 0.048
  CI (99.9%): [1.993, 3.749] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.004 ms/op
Iteration   1: 2.987 ±(99.9%) 0.003 ms/op
Iteration   2: 2.982 ±(99.9%) 0.004 ms/op
Iteration   3: 3.014 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.994 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.982, 2.994, 3.014), stdev = 0.017
  CI (99.9%): [2.681, 3.308] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.542 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.016 ms/op
Iteration   1: 3.895 ±(99.9%) 0.010 ms/op
Iteration   2: 3.920 ±(99.9%) 0.012 ms/op
Iteration   3: 3.955 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.923 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.895, 3.923, 3.955), stdev = 0.030
  CI (99.9%): [3.378, 4.469] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.168 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.904 ms/op
                 createUser·p0.9999: 12.767 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  9.560 ms/op
                 createUser·p0.9999: 15.590 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.589 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  11.045 ms/op
                 createUser·p0.9999: 17.005 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318894
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 540 
    [ 1.250,  2.500) = 29353 
    [ 2.500,  3.750) = 273672 
    [ 3.750,  5.000) = 13916 
    [ 5.000,  6.250) = 698 
    [ 6.250,  7.500) = 285 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 69 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.849 ms/op
     p(99.9900) =     16.371 ms/op
     p(99.9990) =     18.059 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.005 ms/op
Iteration   1: 2.883 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  6.840 ms/op
                 existUser·p0.9999: 12.989 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.780 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.511 ms/op
                 existUser·p0.9999: 16.957 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   3: 2.915 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.998 ms/op
                 existUser·p0.9999: 17.794 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335776
  mean =      2.858 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2289 
    [ 1.250,  2.500) = 46561 
    [ 2.500,  3.750) = 280136 
    [ 3.750,  5.000) = 5876 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 258 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 52 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      6.752 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     18.043 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.600 ms/op
                 getUser·p0.9999: 18.399 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   2: 3.030 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.012 ms/op
                 getUser·p0.9999: 12.780 ms/op
                 getUser·p1.00:   13.369 ms/op

Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.568 ms/op
                 getUser·p0.9999: 17.653 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315022
  mean =      3.047 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 19310 
    [ 2.500,  3.750) = 277113 
    [ 3.750,  5.000) = 17063 
    [ 5.000,  6.250) = 508 
    [ 6.250,  7.500) = 220 
    [ 7.500,  8.750) = 172 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.339 ms/op
     p(99.9900) =     18.006 ms/op
     p(99.9990) =     18.607 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.430 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.010 ms/op
Iteration   1: 3.885 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 22.249 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 3.973 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.719 ms/op
                 listUser·p0.9999: 19.037 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 24.666 ms/op
                 listUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244177
  mean =      3.930 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2307 
    [ 2.500,  5.000) = 219815 
    [ 5.000,  7.500) = 20671 
    [ 7.500, 10.000) = 945 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.914 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.907 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.681 ± 1.418  ops/ms
ClientGrpc.existUser                       thrpt       3  11.095 ± 3.513  ops/ms
ClientGrpc.getUser                         thrpt       3  10.713 ± 2.191  ops/ms
ClientGrpc.listUser                        thrpt       3   8.128 ± 1.387  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.214   ms/op
ClientGrpc.existUser                        avgt       3   2.871 ± 0.878   ms/op
ClientGrpc.getUser                          avgt       3   2.994 ± 0.314   ms/op
ClientGrpc.listUser                         avgt       3   3.923 ± 0.545   ms/op
ClientGrpc.createUser                     sample  318894   3.011 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.589           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.849           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.371           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.252           ms/op
ClientGrpc.existUser                      sample  335776   2.858 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.510           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.314           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.752           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.072           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  315022   3.047 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.688           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.339           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.006           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.071           ms/op
ClientGrpc.listUser                       sample  244177   3.930 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.061           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.914           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.364           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.969           ms/op
