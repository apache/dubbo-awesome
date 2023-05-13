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
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 9.368 ops/ms
# Warmup Iteration   3: 10.374 ops/ms
Iteration   1: 10.739 ops/ms
Iteration   2: 10.883 ops/ms
Iteration   3: 10.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.826 ±(99.9%) 1.395 ops/ms [Average]
  (min, avg, max) = (10.739, 10.826, 10.883), stdev = 0.076
  CI (99.9%): [9.431, 12.222] (assumes normal distribution)


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
# Warmup Iteration   1: 7.989 ops/ms
# Warmup Iteration   2: 10.934 ops/ms
# Warmup Iteration   3: 11.217 ops/ms
Iteration   1: 11.390 ops/ms
Iteration   2: 11.416 ops/ms
Iteration   3: 11.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.315 ±(99.9%) 2.789 ops/ms [Average]
  (min, avg, max) = (11.139, 11.315, 11.416), stdev = 0.153
  CI (99.9%): [8.527, 14.104] (assumes normal distribution)


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
# Warmup Iteration   1: 7.941 ops/ms
# Warmup Iteration   2: 10.377 ops/ms
# Warmup Iteration   3: 10.381 ops/ms
Iteration   1: 10.666 ops/ms
Iteration   2: 10.639 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.588 ±(99.9%) 2.062 ops/ms [Average]
  (min, avg, max) = (10.458, 10.588, 10.666), stdev = 0.113
  CI (99.9%): [8.526, 12.650] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.714 ops/ms
# Warmup Iteration   2: 8.185 ops/ms
# Warmup Iteration   3: 8.395 ops/ms
Iteration   1: 8.215 ops/ms
Iteration   2: 8.397 ops/ms
Iteration   3: 8.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.380 ±(99.9%) 2.860 ops/ms [Average]
  (min, avg, max) = (8.215, 8.380, 8.527), stdev = 0.157
  CI (99.9%): [5.520, 11.240] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.003 ms/op
Iteration   1: 3.069 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (2.966, 3.004, 3.069), stdev = 0.057
  CI (99.9%): [1.964, 4.044] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.906 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.828 ±(99.9%) 0.007 ms/op
Iteration   1: 2.825 ±(99.9%) 0.004 ms/op
Iteration   2: 2.771 ±(99.9%) 0.003 ms/op
Iteration   3: 2.851 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.815 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (2.771, 2.815, 2.851), stdev = 0.041
  CI (99.9%): [2.075, 3.556] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.959 ±(99.9%) 0.004 ms/op
Iteration   3: 2.944 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.964 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (2.944, 2.964, 2.988), stdev = 0.023
  CI (99.9%): [2.550, 3.377] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.875 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.023 ms/op
Iteration   1: 3.810 ±(99.9%) 0.035 ms/op
Iteration   2: 3.736 ±(99.9%) 0.013 ms/op
Iteration   3: 3.817 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.788 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (3.736, 3.788, 3.817), stdev = 0.045
  CI (99.9%): [2.969, 4.607] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 2.952 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  9.654 ms/op
                 createUser·p0.9999: 14.828 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.499 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  6.721 ms/op
                 createUser·p0.9999: 25.256 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   4.063 ms/op
                 createUser·p0.999:  10.748 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323217
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21398 
    [ 2.500,  5.000) = 300712 
    [ 5.000,  7.500) = 668 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      8.975 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     25.519 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.006 ms/op
Iteration   1: 2.955 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  6.023 ms/op
                 existUser·p0.9999: 12.021 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   2: 2.930 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  9.084 ms/op
                 existUser·p0.9999: 14.339 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.873 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.498 ms/op
                 existUser·p0.9999: 14.362 ms/op
                 existUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328802
  mean =      2.919 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1560 
    [ 1.250,  2.500) = 44074 
    [ 2.500,  3.750) = 270213 
    [ 3.750,  5.000) = 11864 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.195 ms/op
     p(99.9900) =     14.076 ms/op
     p(99.9990) =     14.671 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.961 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.021 ms/op
                 getUser·p0.9999: 20.002 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.552 ms/op
                 getUser·p0.999:  6.986 ms/op
                 getUser·p0.9999: 13.309 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   3: 2.911 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.285 ms/op
                 getUser·p0.95:   3.453 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.408 ms/op
                 getUser·p0.9999: 15.024 ms/op
                 getUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324715
  mean =      2.955 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31052 
    [ 2.500,  5.000) = 292459 
    [ 5.000,  7.500) = 961 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     18.164 ms/op
     p(99.9990) =     20.267 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.010 ms/op
Iteration   1: 3.914 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.776 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 14.893 ms/op
                 listUser·p1.00:   15.286 ms/op

Iteration   2: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  16.677 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 3.666 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.192 ms/op
                 listUser·p0.9999: 21.856 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251607
  mean =      3.818 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5357 
    [ 2.500,  5.000) = 223760 
    [ 5.000,  7.500) = 21227 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.129 ms/op
     p(99.9900) =     21.261 ms/op
     p(99.9990) =     22.264 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.826 ± 1.395  ops/ms
ClientGrpc.existUser                       thrpt       3  11.315 ± 2.789  ops/ms
ClientGrpc.getUser                         thrpt       3  10.588 ± 2.062  ops/ms
ClientGrpc.listUser                        thrpt       3   8.380 ± 2.860  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 1.040   ms/op
ClientGrpc.existUser                        avgt       3   2.815 ± 0.740   ms/op
ClientGrpc.getUser                          avgt       3   2.964 ± 0.414   ms/op
ClientGrpc.listUser                         avgt       3   3.788 ± 0.819   ms/op
ClientGrpc.createUser                     sample  323217   2.970 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.499           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.387           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.133           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.975           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.970           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.592           ms/op
ClientGrpc.existUser                      sample  328802   2.919 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.710           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.195           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.076           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.828           ms/op
ClientGrpc.getUser                        sample  324715   2.955 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.734           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.164           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.382           ms/op
ClientGrpc.listUser                       sample  251607   3.818 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.776           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.129           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.261           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.708           ms/op
