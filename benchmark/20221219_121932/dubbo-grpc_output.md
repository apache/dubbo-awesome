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
# Warmup Iteration   1: 4.530 ops/ms
# Warmup Iteration   2: 9.195 ops/ms
# Warmup Iteration   3: 9.953 ops/ms
Iteration   1: 10.211 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.312 ±(99.9%) 2.821 ops/ms [Average]
  (min, avg, max) = (10.211, 10.312, 10.490), stdev = 0.155
  CI (99.9%): [7.491, 13.132] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.652 ops/ms
# Warmup Iteration   2: 10.452 ops/ms
# Warmup Iteration   3: 10.621 ops/ms
Iteration   1: 10.468 ops/ms
Iteration   2: 10.608 ops/ms
Iteration   3: 10.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.588 ±(99.9%) 2.031 ops/ms [Average]
  (min, avg, max) = (10.468, 10.588, 10.689), stdev = 0.111
  CI (99.9%): [8.557, 12.620] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.596 ops/ms
# Warmup Iteration   2: 10.198 ops/ms
# Warmup Iteration   3: 10.291 ops/ms
Iteration   1: 10.177 ops/ms
Iteration   2: 10.331 ops/ms
Iteration   3: 10.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.196 ±(99.9%) 2.315 ops/ms [Average]
  (min, avg, max) = (10.080, 10.196, 10.331), stdev = 0.127
  CI (99.9%): [7.881, 12.511] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.891 ops/ms
# Warmup Iteration   2: 7.895 ops/ms
# Warmup Iteration   3: 7.952 ops/ms
Iteration   1: 8.455 ops/ms
Iteration   2: 8.181 ops/ms
Iteration   3: 8.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.327 ±(99.9%) 2.512 ops/ms [Average]
  (min, avg, max) = (8.181, 8.327, 8.455), stdev = 0.138
  CI (99.9%): [5.816, 10.839] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.418 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.003 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
Iteration   3: 3.174 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.119 ±(99.9%) 0.868 ms/op [Average]
  (min, avg, max) = (3.087, 3.119, 3.174), stdev = 0.048
  CI (99.9%): [2.251, 3.988] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.003 ms/op
Iteration   1: 2.939 ±(99.9%) 0.002 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 2.854 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.918 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (2.854, 2.918, 2.960), stdev = 0.056
  CI (99.9%): [1.888, 3.947] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.002 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
Iteration   3: 3.060 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.073 ±(99.9%) 0.830 ms/op [Average]
  (min, avg, max) = (3.035, 3.073, 3.124), stdev = 0.045
  CI (99.9%): [2.243, 3.903] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.017 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.014 ms/op
Iteration   1: 3.873 ±(99.9%) 0.011 ms/op
Iteration   2: 3.851 ±(99.9%) 0.036 ms/op
Iteration   3: 3.865 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.863 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (3.851, 3.863, 3.873), stdev = 0.011
  CI (99.9%): [3.658, 4.068] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.167 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.008 ms/op
Iteration   1: 3.026 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  6.998 ms/op
                 createUser·p0.9999: 12.119 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.317 ms/op
                 createUser·p0.9999: 14.057 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.647 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310470
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 685 
    [ 1.250,  2.500) = 28319 
    [ 2.500,  3.750) = 250836 
    [ 3.750,  5.000) = 29824 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     19.201 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.421 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.676 ms/op
                 existUser·p0.9999: 12.698 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   2: 3.039 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  8.753 ms/op
                 existUser·p0.9999: 17.087 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  9.997 ms/op
                 existUser·p0.9999: 18.481 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319798
  mean =      3.003 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1899 
    [ 1.250,  2.500) = 50236 
    [ 2.500,  3.750) = 239311 
    [ 3.750,  5.000) = 27429 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 249 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.959 ms/op
     p(99.9900) =     18.153 ms/op
     p(99.9990) =     18.861 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.368 ms/op
                 getUser·p0.9999: 16.847 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.914 ms/op
                 getUser·p0.9999: 17.387 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.548 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.720 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310143
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25330 
    [ 2.500,  5.000) = 283534 
    [ 5.000,  7.500) = 967 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.512 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     21.555 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.010 ms/op
Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.176 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 3.835 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.215 ms/op
                 listUser·p0.9999: 19.879 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 3.939 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.953 ms/op
                 listUser·p0.9999: 24.867 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245494
  mean =      3.910 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3471 
    [ 2.500,  5.000) = 218229 
    [ 5.000,  7.500) = 22719 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     23.739 ms/op
     p(99.9990) =     25.318 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.312 ± 2.821  ops/ms
ClientGrpc.existUser                       thrpt       3  10.588 ± 2.031  ops/ms
ClientGrpc.getUser                         thrpt       3  10.196 ± 2.315  ops/ms
ClientGrpc.listUser                        thrpt       3   8.327 ± 2.512  ops/ms
ClientGrpc.createUser                       avgt       3   3.119 ± 0.868   ms/op
ClientGrpc.existUser                        avgt       3   2.918 ± 1.029   ms/op
ClientGrpc.getUser                          avgt       3   3.073 ± 0.830   ms/op
ClientGrpc.listUser                         avgt       3   3.863 ± 0.205   ms/op
ClientGrpc.createUser                     sample  310470   3.092 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.558           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.963           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.201           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.857           ms/op
ClientGrpc.existUser                      sample  319798   3.003 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.591           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.959           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.153           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.940           ms/op
ClientGrpc.getUser                        sample  310143   3.096 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.548           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.512           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.906           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.987           ms/op
ClientGrpc.listUser                       sample  245494   3.910 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.761           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.303           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.739           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.214           ms/op
