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
# Warmup Iteration   1: 1.660 ops/ms
# Warmup Iteration   2: 4.016 ops/ms
# Warmup Iteration   3: 6.029 ops/ms
Iteration   1: 6.159 ops/ms
Iteration   2: 6.458 ops/ms
Iteration   3: 6.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.374 ±(99.9%) 3.421 ops/ms [Average]
  (min, avg, max) = (6.159, 6.374, 6.505), stdev = 0.188
  CI (99.9%): [2.953, 9.795] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.931 ops/ms
# Warmup Iteration   2: 6.508 ops/ms
# Warmup Iteration   3: 6.982 ops/ms
Iteration   1: 7.259 ops/ms
Iteration   2: 7.318 ops/ms
Iteration   3: 7.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.236 ±(99.9%) 1.735 ops/ms [Average]
  (min, avg, max) = (7.132, 7.236, 7.318), stdev = 0.095
  CI (99.9%): [5.501, 8.971] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 5.662 ops/ms
# Warmup Iteration   3: 6.444 ops/ms
Iteration   1: 6.875 ops/ms
Iteration   2: 6.895 ops/ms
Iteration   3: 6.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.811 ±(99.9%) 2.354 ops/ms [Average]
  (min, avg, max) = (6.662, 6.811, 6.895), stdev = 0.129
  CI (99.9%): [4.457, 9.165] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.150 ops/ms
# Warmup Iteration   2: 4.524 ops/ms
# Warmup Iteration   3: 4.893 ops/ms
Iteration   1: 4.925 ops/ms
Iteration   2: 4.903 ops/ms
Iteration   3: 5.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.951 ±(99.9%) 1.182 ops/ms [Average]
  (min, avg, max) = (4.903, 4.951, 5.025), stdev = 0.065
  CI (99.9%): [3.769, 6.133] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.436 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.319 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.269 ±(99.9%) 0.024 ms/op
Iteration   1: 4.962 ±(99.9%) 0.004 ms/op
Iteration   2: 5.290 ±(99.9%) 0.005 ms/op
Iteration   3: 5.008 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.087 ±(99.9%) 3.240 ms/op [Average]
  (min, avg, max) = (4.962, 5.087, 5.290), stdev = 0.178
  CI (99.9%): [1.847, 8.327] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.046 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.084 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.624 ±(99.9%) 0.007 ms/op
Iteration   1: 4.692 ±(99.9%) 0.006 ms/op
Iteration   2: 4.730 ±(99.9%) 0.004 ms/op
Iteration   3: 4.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.649 ±(99.9%) 1.980 ms/op [Average]
  (min, avg, max) = (4.526, 4.649, 4.730), stdev = 0.109
  CI (99.9%): [2.670, 6.629] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.892 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.317 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.018 ±(99.9%) 0.009 ms/op
Iteration   1: 4.876 ±(99.9%) 0.003 ms/op
Iteration   2: 4.666 ±(99.9%) 0.005 ms/op
Iteration   3: 4.731 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.758 ±(99.9%) 1.967 ms/op [Average]
  (min, avg, max) = (4.666, 4.758, 4.876), stdev = 0.108
  CI (99.9%): [2.791, 6.724] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.461 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.687 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.309 ±(99.9%) 0.024 ms/op
Iteration   1: 6.154 ±(99.9%) 0.018 ms/op
Iteration   2: 6.436 ±(99.9%) 0.016 ms/op
Iteration   3: 6.087 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.225 ±(99.9%) 3.380 ms/op [Average]
  (min, avg, max) = (6.087, 6.225, 6.436), stdev = 0.185
  CI (99.9%): [2.845, 9.606] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.481 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 5.453 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.964 ±(99.9%) 0.020 ms/op
Iteration   1: 4.723 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   6.029 ms/op
                 createUser·p0.95:   6.717 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  13.361 ms/op
                 createUser·p0.9999: 24.271 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   2: 4.876 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   4.686 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   9.421 ms/op
                 createUser·p0.999:  12.550 ms/op
                 createUser·p0.9999: 25.748 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 5.037 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.651 ms/op
                 createUser·p0.99:   10.682 ms/op
                 createUser·p0.999:  20.588 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 196853
  mean =      4.876 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3764 
    [ 2.500,  5.000) = 120726 
    [ 5.000,  7.500) = 64805 
    [ 7.500, 10.000) = 5900 
    [10.000, 12.500) = 1256 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     14.945 ms/op
     p(99.9900) =     26.159 ms/op
     p(99.9990) =     27.955 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.802 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.325 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.017 ms/op
Iteration   1: 4.538 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   6.463 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  14.163 ms/op
                 existUser·p0.9999: 34.989 ms/op
                 existUser·p1.00:   36.700 ms/op

Iteration   2: 4.669 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.972 ms/op
                 existUser·p0.95:   6.783 ms/op
                 existUser·p0.99:   9.552 ms/op
                 existUser·p0.999:  15.197 ms/op
                 existUser·p0.9999: 21.019 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   3: 4.473 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   4.276 ms/op
                 existUser·p0.90:   5.710 ms/op
                 existUser·p0.95:   6.365 ms/op
                 existUser·p0.99:   8.978 ms/op
                 existUser·p0.999:  12.616 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 210646
  mean =      4.558 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4891 
    [ 2.500,  5.000) = 152782 
    [ 5.000,  7.500) = 47543 
    [ 7.500, 10.000) = 3875 
    [10.000, 12.500) = 1171 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.529 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     27.163 ms/op
     p(99.9990) =     35.382 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.967 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 5.453 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.849 ±(99.9%) 0.018 ms/op
Iteration   1: 4.876 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   4.678 ms/op
                 getUser·p0.90:   6.193 ms/op
                 getUser·p0.95:   6.914 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  15.506 ms/op
                 getUser·p0.9999: 21.197 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 4.813 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   6.963 ms/op
                 getUser·p0.99:   9.273 ms/op
                 getUser·p0.999:  14.084 ms/op
                 getUser·p0.9999: 20.131 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   3: 4.793 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   6.169 ms/op
                 getUser·p0.95:   6.930 ms/op
                 getUser·p0.99:   9.634 ms/op
                 getUser·p0.999:  16.857 ms/op
                 getUser·p0.9999: 36.171 ms/op
                 getUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 198754
  mean =      4.827 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3297 
    [ 2.500,  5.000) = 126019 
    [ 5.000,  7.500) = 62960 
    [ 7.500, 10.000) = 5062 
    [10.000, 12.500) = 932 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     15.225 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     38.275 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.268 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 6.991 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.415 ±(99.9%) 0.030 ms/op
Iteration   1: 6.287 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   8.815 ms/op
                 listUser·p0.95:   10.027 ms/op
                 listUser·p0.99:   13.476 ms/op
                 listUser·p0.999:  18.456 ms/op
                 listUser·p0.9999: 22.803 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 6.132 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   8.569 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   12.681 ms/op
                 listUser·p0.999:  21.135 ms/op
                 listUser·p0.9999: 26.244 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   3: 6.408 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.158 ms/op
                 listUser·p0.99:   13.500 ms/op
                 listUser·p0.999:  23.001 ms/op
                 listUser·p0.9999: 30.343 ms/op
                 listUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 153169
  mean =      6.274 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 170 
    [ 2.500,  5.000) = 37474 
    [ 5.000,  7.500) = 84676 
    [ 7.500, 10.000) = 23318 
    [10.000, 12.500) = 5379 
    [12.500, 15.000) = 1443 
    [15.000, 17.500) = 403 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.450 ms/op
     p(50.0000) =      5.767 ms/op
     p(90.0000) =      8.798 ms/op
     p(95.0000) =      9.978 ms/op
     p(99.0000) =     13.222 ms/op
     p(99.9000) =     20.409 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     31.526 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.374 ± 3.421  ops/ms
ClientGrpc.existUser                       thrpt       3   7.236 ± 1.735  ops/ms
ClientGrpc.getUser                         thrpt       3   6.811 ± 2.354  ops/ms
ClientGrpc.listUser                        thrpt       3   4.951 ± 1.182  ops/ms
ClientGrpc.createUser                       avgt       3   5.087 ± 3.240   ms/op
ClientGrpc.existUser                        avgt       3   4.649 ± 1.980   ms/op
ClientGrpc.getUser                          avgt       3   4.758 ± 1.967   ms/op
ClientGrpc.listUser                         avgt       3   6.225 ± 3.380   ms/op
ClientGrpc.createUser                     sample  196853   4.876 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.906           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.332           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.143           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.732           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.945           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.159           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.098           ms/op
ClientGrpc.existUser                      sample  210646   4.558 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.971           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.825           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.529           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.372           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.107           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.163           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.700           ms/op
ClientGrpc.getUser                        sample  198754   4.827 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.002           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.193           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.939           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.437           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.225           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.537           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          38.470           ms/op
ClientGrpc.listUser                       sample  153169   6.274 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.450           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.798           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.978           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.222           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.409           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.327           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.752           ms/op
