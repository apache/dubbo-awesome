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
# Warmup Iteration   1: 4.003 ops/ms
# Warmup Iteration   2: 8.545 ops/ms
# Warmup Iteration   3: 9.754 ops/ms
Iteration   1: 10.271 ops/ms
Iteration   2: 10.182 ops/ms
Iteration   3: 10.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.258 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (10.182, 10.258, 10.321), stdev = 0.070
  CI (99.9%): [8.977, 11.539] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.997 ops/ms
# Warmup Iteration   2: 9.996 ops/ms
# Warmup Iteration   3: 10.298 ops/ms
Iteration   1: 10.837 ops/ms
Iteration   2: 10.728 ops/ms
Iteration   3: 11.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.855 ±(99.9%) 2.495 ops/ms [Average]
  (min, avg, max) = (10.728, 10.855, 11.000), stdev = 0.137
  CI (99.9%): [8.360, 13.350] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.479 ops/ms
# Warmup Iteration   2: 9.678 ops/ms
# Warmup Iteration   3: 10.301 ops/ms
Iteration   1: 10.392 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 10.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.183 ±(99.9%) 3.313 ops/ms [Average]
  (min, avg, max) = (10.061, 10.183, 10.392), stdev = 0.182
  CI (99.9%): [6.870, 13.496] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ops/ms
# Warmup Iteration   2: 7.569 ops/ms
# Warmup Iteration   3: 7.518 ops/ms
Iteration   1: 7.839 ops/ms
Iteration   2: 7.765 ops/ms
Iteration   3: 7.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.787 ±(99.9%) 0.825 ops/ms [Average]
  (min, avg, max) = (7.758, 7.787, 7.839), stdev = 0.045
  CI (99.9%): [6.962, 8.612] (assumes normal distribution)


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.003 ms/op
Iteration   1: 3.286 ±(99.9%) 0.001 ms/op
Iteration   2: 3.172 ±(99.9%) 0.002 ms/op
Iteration   3: 3.196 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.218 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (3.172, 3.218, 3.286), stdev = 0.060
  CI (99.9%): [2.118, 4.318] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.396 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.002 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.020 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.054 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.020, 3.054, 3.107), stdev = 0.047
  CI (99.9%): [2.201, 3.907] (assumes normal distribution)


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.003 ms/op
Iteration   1: 3.102 ±(99.9%) 0.003 ms/op
Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.112 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.100, 3.112, 3.133), stdev = 0.019
  CI (99.9%): [2.773, 3.450] (assumes normal distribution)


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
# Warmup Iteration   1: 5.170 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.012 ms/op
Iteration   1: 4.190 ±(99.9%) 0.031 ms/op
Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
Iteration   3: 4.089 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.102 ±(99.9%) 1.502 ms/op [Average]
  (min, avg, max) = (4.026, 4.102, 4.190), stdev = 0.082
  CI (99.9%): [2.599, 5.604] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.496 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.007 ms/op
Iteration   1: 3.169 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  11.369 ms/op
                 createUser·p0.9999: 20.834 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  7.848 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   3: 3.132 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  15.000 ms/op
                 createUser·p0.9999: 30.491 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304291
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24612 
    [ 2.500,  5.000) = 277524 
    [ 5.000,  7.500) = 1597 
    [ 7.500, 10.000) = 239 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     10.170 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     30.829 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.321 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.562 ms/op
                 existUser·p0.9999: 13.196 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.445 ms/op
                 existUser·p0.9999: 13.932 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   3: 2.967 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.332 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 17.079 ms/op
                 existUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322092
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 927 
    [ 1.250,  2.500) = 39044 
    [ 2.500,  3.750) = 267395 
    [ 3.750,  5.000) = 13421 
    [ 5.000,  6.250) = 785 
    [ 6.250,  7.500) = 206 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.321 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.347 ms/op
     p(99.9900) =     16.652 ms/op
     p(99.9990) =     18.027 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.172 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.418 ms/op
                 getUser·p0.9999: 14.874 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   2: 3.188 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.448 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.447 ms/op
                 getUser·p0.9999: 14.057 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   3: 3.228 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  6.824 ms/op
                 getUser·p0.9999: 32.152 ms/op
                 getUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300384
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20113 
    [ 2.500,  5.000) = 278361 
    [ 5.000,  7.500) = 1641 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      7.381 ms/op
     p(99.9900) =     31.324 ms/op
     p(99.9990) =     32.669 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 6.014 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.011 ms/op
Iteration   1: 4.183 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.639 ms/op
                 listUser·p0.999:  15.131 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   2: 4.150 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.643 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 30.091 ms/op
                 listUser·p1.00:   30.441 ms/op

Iteration   3: 4.152 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 30.517 ms/op
                 listUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230559
  mean =      4.162 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2350 
    [ 2.500,  5.000) = 200201 
    [ 5.000,  7.500) = 25913 
    [ 7.500, 10.000) = 1534 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     16.391 ms/op
     p(99.9900) =     30.081 ms/op
     p(99.9990) =     30.792 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.258 ± 1.281  ops/ms
ClientGrpc.existUser                       thrpt       3  10.855 ± 2.495  ops/ms
ClientGrpc.getUser                         thrpt       3  10.183 ± 3.313  ops/ms
ClientGrpc.listUser                        thrpt       3   7.787 ± 0.825  ops/ms
ClientGrpc.createUser                       avgt       3   3.218 ± 1.100   ms/op
ClientGrpc.existUser                        avgt       3   3.054 ± 0.853   ms/op
ClientGrpc.getUser                          avgt       3   3.112 ± 0.338   ms/op
ClientGrpc.listUser                         avgt       3   4.102 ± 1.502   ms/op
ClientGrpc.createUser                     sample  304291   3.158 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.551           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.170           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.884           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.835           ms/op
ClientGrpc.existUser                      sample  322092   2.980 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.321           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.347           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.652           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.579           ms/op
ClientGrpc.getUser                        sample  300384   3.196 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.448           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.166           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.324           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.801           ms/op
ClientGrpc.listUser                       sample  230559   4.162 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.643           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.990           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.391           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.081           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.835           ms/op
