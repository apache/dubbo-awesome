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
# Warmup Iteration   1: 2.057 ops/ms
# Warmup Iteration   2: 4.915 ops/ms
# Warmup Iteration   3: 6.584 ops/ms
Iteration   1: 6.845 ops/ms
Iteration   2: 6.961 ops/ms
Iteration   3: 6.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.873 ±(99.9%) 1.427 ops/ms [Average]
  (min, avg, max) = (6.812, 6.873, 6.961), stdev = 0.078
  CI (99.9%): [5.446, 8.299] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ops/ms
# Warmup Iteration   2: 6.749 ops/ms
# Warmup Iteration   3: 6.934 ops/ms
Iteration   1: 6.977 ops/ms
Iteration   2: 7.191 ops/ms
Iteration   3: 7.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.063 ±(99.9%) 2.068 ops/ms [Average]
  (min, avg, max) = (6.977, 7.063, 7.191), stdev = 0.113
  CI (99.9%): [4.994, 9.131] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 6.187 ops/ms
# Warmup Iteration   3: 6.294 ops/ms
Iteration   1: 6.760 ops/ms
Iteration   2: 6.506 ops/ms
Iteration   3: 6.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.619 ±(99.9%) 2.351 ops/ms [Average]
  (min, avg, max) = (6.506, 6.619, 6.760), stdev = 0.129
  CI (99.9%): [4.268, 8.970] (assumes normal distribution)


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
# Warmup Iteration   1: 3.455 ops/ms
# Warmup Iteration   2: 4.506 ops/ms
# Warmup Iteration   3: 5.066 ops/ms
Iteration   1: 5.182 ops/ms
Iteration   2: 5.138 ops/ms
Iteration   3: 5.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.213 ±(99.9%) 1.725 ops/ms [Average]
  (min, avg, max) = (5.138, 5.213, 5.319), stdev = 0.095
  CI (99.9%): [3.488, 6.938] (assumes normal distribution)


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
# Warmup Iteration   1: 7.714 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.011 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.895 ±(99.9%) 0.005 ms/op
Iteration   1: 4.921 ±(99.9%) 0.004 ms/op
Iteration   2: 4.798 ±(99.9%) 0.003 ms/op
Iteration   3: 4.921 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.880 ±(99.9%) 1.295 ms/op [Average]
  (min, avg, max) = (4.798, 4.880, 4.921), stdev = 0.071
  CI (99.9%): [3.585, 6.174] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.822 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.940 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.631 ±(99.9%) 0.004 ms/op
Iteration   1: 4.645 ±(99.9%) 0.003 ms/op
Iteration   2: 4.543 ±(99.9%) 0.003 ms/op
Iteration   3: 4.567 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.585 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (4.543, 4.585, 4.645), stdev = 0.054
  CI (99.9%): [3.605, 5.564] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.451 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.198 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.173 ±(99.9%) 0.004 ms/op
Iteration   1: 4.905 ±(99.9%) 0.006 ms/op
Iteration   2: 4.852 ±(99.9%) 0.005 ms/op
Iteration   3: 4.989 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.916 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (4.852, 4.916, 4.989), stdev = 0.069
  CI (99.9%): [3.654, 6.177] (assumes normal distribution)


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
# Warmup Iteration   1: 9.558 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.470 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.933 ±(99.9%) 0.008 ms/op
Iteration   1: 5.956 ±(99.9%) 0.018 ms/op
Iteration   2: 6.112 ±(99.9%) 0.020 ms/op
Iteration   3: 5.915 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.994 ±(99.9%) 1.894 ms/op [Average]
  (min, avg, max) = (5.915, 5.994, 6.112), stdev = 0.104
  CI (99.9%): [4.101, 7.888] (assumes normal distribution)


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
# Warmup Iteration   1: 7.452 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.019 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.982 ±(99.9%) 0.015 ms/op
Iteration   1: 4.813 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   4.694 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   8.694 ms/op
                 createUser·p0.999:  15.387 ms/op
                 createUser·p0.9999: 17.905 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 4.831 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   4.710 ms/op
                 createUser·p0.90:   6.128 ms/op
                 createUser·p0.95:   6.619 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  11.857 ms/op
                 createUser·p0.9999: 25.092 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 4.909 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   4.792 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   8.338 ms/op
                 createUser·p0.999:  19.249 ms/op
                 createUser·p0.9999: 22.510 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 197952
  mean =      4.851 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2445 
    [ 2.500,  5.000) = 117121 
    [ 5.000,  7.500) = 74613 
    [ 7.500, 10.000) = 2871 
    [10.000, 12.500) = 551 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.603 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     23.338 ms/op
     p(99.9990) =     26.020 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 7.216 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.909 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.016 ms/op
Iteration   1: 4.621 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   4.473 ms/op
                 existUser·p0.90:   5.816 ms/op
                 existUser·p0.95:   6.349 ms/op
                 existUser·p0.99:   8.453 ms/op
                 existUser·p0.999:  12.904 ms/op
                 existUser·p0.9999: 20.367 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 4.625 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   6.406 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  16.658 ms/op
                 existUser·p0.9999: 21.433 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   3: 4.527 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.070 ms/op
                 existUser·p0.99:   7.424 ms/op
                 existUser·p0.999:  15.424 ms/op
                 existUser·p0.9999: 21.365 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 208915
  mean =      4.591 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4641 
    [ 2.500,  5.000) = 143548 
    [ 5.000,  7.500) = 57468 
    [ 7.500, 10.000) = 2375 
    [10.000, 12.500) = 455 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.800 ms/op
     p(95.0000) =      6.275 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     15.026 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.919 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 7.201 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.201 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.659 ±(99.9%) 0.015 ms/op
Iteration   1: 4.733 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   4.645 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   8.235 ms/op
                 getUser·p0.999:  11.151 ms/op
                 getUser·p0.9999: 17.448 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   2: 4.625 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.792 ms/op
                 getUser·p0.95:   6.275 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  15.380 ms/op
                 getUser·p0.9999: 21.930 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   3: 4.532 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   4.448 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.561 ms/op
                 getUser·p0.999:  13.025 ms/op
                 getUser·p0.9999: 20.476 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 207327
  mean =      4.628 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4060 
    [ 2.500,  5.000) = 145398 
    [ 5.000,  7.500) = 54950 
    [ 7.500, 10.000) = 2142 
    [10.000, 12.500) = 479 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.234 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     20.891 ms/op
     p(99.9990) =     22.497 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 9.213 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.621 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.389 ±(99.9%) 0.029 ms/op
Iteration   1: 6.223 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   8.307 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   11.862 ms/op
                 listUser·p0.999:  24.680 ms/op
                 listUser·p0.9999: 33.437 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   2: 5.821 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.026 ms/op
                 listUser·p0.999:  25.760 ms/op
                 listUser·p0.9999: 28.577 ms/op
                 listUser·p1.00:   29.393 ms/op

Iteration   3: 6.175 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  30.776 ms/op
                 listUser·p0.9999: 37.725 ms/op
                 listUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 158209
  mean =      6.068 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 35372 
    [ 5.000,  7.500) = 100653 
    [ 7.500, 10.000) = 18201 
    [10.000, 12.500) = 2984 
    [12.500, 15.000) = 465 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      5.759 ms/op
     p(90.0000) =      8.028 ms/op
     p(95.0000) =      9.044 ms/op
     p(99.0000) =     11.502 ms/op
     p(99.9000) =     27.675 ms/op
     p(99.9900) =     35.794 ms/op
     p(99.9990) =     38.328 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.873 ± 1.427  ops/ms
ClientGrpc.existUser                       thrpt       3   7.063 ± 2.068  ops/ms
ClientGrpc.getUser                         thrpt       3   6.619 ± 2.351  ops/ms
ClientGrpc.listUser                        thrpt       3   5.213 ± 1.725  ops/ms
ClientGrpc.createUser                       avgt       3   4.880 ± 1.295   ms/op
ClientGrpc.existUser                        avgt       3   4.585 ± 0.980   ms/op
ClientGrpc.getUser                          avgt       3   4.916 ± 1.261   ms/op
ClientGrpc.listUser                         avgt       3   5.994 ± 1.894   ms/op
ClientGrpc.createUser                     sample  197952   4.851 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.083           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.128           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.603           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.520           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.172           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.338           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.149           ms/op
ClientGrpc.existUser                      sample  208915   4.591 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.061           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.800           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.275           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.217           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.026           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.332           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.708           ms/op
ClientGrpc.getUser                        sample  207327   4.628 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.009           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.759           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.234           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.118           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.926           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.891           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.610           ms/op
ClientGrpc.listUser                       sample  158209   6.068 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.411           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.502           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          27.675           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.794           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.404           ms/op
