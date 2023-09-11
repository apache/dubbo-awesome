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
# Warmup Iteration   1: 4.319 ops/ms
# Warmup Iteration   2: 8.573 ops/ms
# Warmup Iteration   3: 9.931 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.716 ops/ms
Iteration   3: 10.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.577 ±(99.9%) 3.596 ops/ms [Average]
  (min, avg, max) = (10.352, 10.577, 10.716), stdev = 0.197
  CI (99.9%): [6.982, 14.173] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.456 ops/ms
# Warmup Iteration   2: 10.892 ops/ms
# Warmup Iteration   3: 11.048 ops/ms
Iteration   1: 11.009 ops/ms
Iteration   2: 11.393 ops/ms
Iteration   3: 11.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.229 ±(99.9%) 3.613 ops/ms [Average]
  (min, avg, max) = (11.009, 11.229, 11.393), stdev = 0.198
  CI (99.9%): [7.616, 14.842] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.138 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 10.837 ops/ms
Iteration   2: 10.872 ops/ms
Iteration   3: 10.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.874 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (10.837, 10.874, 10.913), stdev = 0.038
  CI (99.9%): [10.182, 11.566] (assumes normal distribution)


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
# Warmup Iteration   1: 6.038 ops/ms
# Warmup Iteration   2: 7.868 ops/ms
# Warmup Iteration   3: 8.260 ops/ms
Iteration   1: 8.036 ops/ms
Iteration   2: 8.158 ops/ms
Iteration   3: 8.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.124 ±(99.9%) 1.404 ops/ms [Average]
  (min, avg, max) = (8.036, 8.124, 8.178), stdev = 0.077
  CI (99.9%): [6.720, 9.528] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 3.017 ±(99.9%) 0.017 ms/op
Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
Iteration   3: 3.070 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.054 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.017, 3.054, 3.075), stdev = 0.032
  CI (99.9%): [2.464, 3.644] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.003 ms/op
Iteration   1: 2.964 ±(99.9%) 0.003 ms/op
Iteration   2: 2.877 ±(99.9%) 0.003 ms/op
Iteration   3: 2.867 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.903 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (2.867, 2.903, 2.964), stdev = 0.053
  CI (99.9%): [1.933, 3.873] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.002 ms/op
Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.045 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.020, 3.045, 3.072), stdev = 0.026
  CI (99.9%): [2.575, 3.515] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.662 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.024 ms/op
Iteration   1: 3.963 ±(99.9%) 0.021 ms/op
Iteration   2: 3.876 ±(99.9%) 0.022 ms/op
Iteration   3: 3.912 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.917 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (3.876, 3.917, 3.963), stdev = 0.043
  CI (99.9%): [3.124, 4.711] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
Iteration   1: 3.056 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  10.565 ms/op
                 createUser·p0.9999: 18.448 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.494 ms/op
                 createUser·p0.999:  9.697 ms/op
                 createUser·p0.9999: 16.089 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.558 ms/op
                 createUser·p0.999:  9.287 ms/op
                 createUser·p0.9999: 15.722 ms/op
                 createUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313983
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1075 
    [ 1.250,  2.500) = 22968 
    [ 2.500,  3.750) = 269225 
    [ 3.750,  5.000) = 18593 
    [ 5.000,  6.250) = 1001 
    [ 6.250,  7.500) = 447 
    [ 7.500,  8.750) = 171 
    [ 8.750, 10.000) = 203 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 65 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     17.747 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.899 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.007 ms/op
Iteration   1: 2.861 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.070 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   2: 2.867 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.957 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.925 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.508 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  13.320 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332741
  mean =      2.884 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53101 
    [ 2.500,  5.000) = 277121 
    [ 5.000,  7.500) = 1641 
    [ 7.500, 10.000) = 435 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.516 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 12.803 ms/op
                 getUser·p1.00:   13.091 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.893 ms/op
                 getUser·p0.9999: 12.818 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.749 ms/op
                 getUser·p0.9999: 14.582 ms/op
                 getUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319639
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1430 
    [ 1.250,  2.500) = 28231 
    [ 2.500,  3.750) = 271861 
    [ 3.750,  5.000) = 16434 
    [ 5.000,  6.250) = 824 
    [ 6.250,  7.500) = 399 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.476 ms/op
     p(99.9900) =     14.222 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.994 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 3.914 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 18.137 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   2: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.797 ms/op
                 listUser·p0.999:  13.323 ms/op
                 listUser·p0.9999: 15.632 ms/op
                 listUser·p1.00:   16.515 ms/op

Iteration   3: 3.950 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 19.395 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244514
  mean =      3.927 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3911 
    [ 2.500,  5.000) = 217975 
    [ 5.000,  7.500) = 21025 
    [ 7.500, 10.000) = 1030 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     18.750 ms/op
     p(99.9990) =     19.679 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.577 ± 3.596  ops/ms
ClientGrpc.existUser                       thrpt       3  11.229 ± 3.613  ops/ms
ClientGrpc.getUser                         thrpt       3  10.874 ± 0.692  ops/ms
ClientGrpc.listUser                        thrpt       3   8.124 ± 1.404  ops/ms
ClientGrpc.createUser                       avgt       3   3.054 ± 0.590   ms/op
ClientGrpc.existUser                        avgt       3   2.903 ± 0.970   ms/op
ClientGrpc.getUser                          avgt       3   3.045 ± 0.470   ms/op
ClientGrpc.listUser                         avgt       3   3.917 ± 0.794   ms/op
ClientGrpc.createUser                     sample  313983   3.059 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.678           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.880           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.747           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.940           ms/op
ClientGrpc.existUser                      sample  332741   2.884 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.508           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.735           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.469           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.235           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  319639   3.002 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.516           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.476           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.222           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.827           ms/op
ClientGrpc.listUser                       sample  244514   3.927 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.802           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.750           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.349           ms/op
