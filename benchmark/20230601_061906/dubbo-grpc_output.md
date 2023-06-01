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
# Warmup Iteration   1: 2.162 ops/ms
# Warmup Iteration   2: 4.985 ops/ms
# Warmup Iteration   3: 7.010 ops/ms
Iteration   1: 7.114 ops/ms
Iteration   2: 7.062 ops/ms
Iteration   3: 7.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.092 ±(99.9%) 0.487 ops/ms [Average]
  (min, avg, max) = (7.062, 7.092, 7.114), stdev = 0.027
  CI (99.9%): [6.605, 7.580] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.226 ops/ms
# Warmup Iteration   2: 6.739 ops/ms
# Warmup Iteration   3: 7.665 ops/ms
Iteration   1: 7.302 ops/ms
Iteration   2: 7.086 ops/ms
Iteration   3: 7.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.311 ±(99.9%) 4.183 ops/ms [Average]
  (min, avg, max) = (7.086, 7.311, 7.544), stdev = 0.229
  CI (99.9%): [3.128, 11.494] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ops/ms
# Warmup Iteration   2: 6.257 ops/ms
# Warmup Iteration   3: 6.666 ops/ms
Iteration   1: 6.838 ops/ms
Iteration   2: 6.928 ops/ms
Iteration   3: 6.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.920 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (6.838, 6.920, 6.995), stdev = 0.079
  CI (99.9%): [5.478, 8.362] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.574 ops/ms
# Warmup Iteration   2: 4.422 ops/ms
# Warmup Iteration   3: 5.276 ops/ms
Iteration   1: 5.451 ops/ms
Iteration   2: 5.483 ops/ms
Iteration   3: 5.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.486 ±(99.9%) 0.671 ops/ms [Average]
  (min, avg, max) = (5.451, 5.486, 5.524), stdev = 0.037
  CI (99.9%): [4.815, 6.157] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.204 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.972 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.820 ±(99.9%) 0.010 ms/op
Iteration   1: 4.552 ±(99.9%) 0.006 ms/op
Iteration   2: 4.609 ±(99.9%) 0.003 ms/op
Iteration   3: 4.542 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.567 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (4.542, 4.567, 4.609), stdev = 0.036
  CI (99.9%): [3.912, 5.223] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.667 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.670 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.006 ms/op
Iteration   1: 4.264 ±(99.9%) 0.009 ms/op
Iteration   2: 4.218 ±(99.9%) 0.004 ms/op
Iteration   3: 4.306 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.263 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (4.218, 4.263, 4.306), stdev = 0.044
  CI (99.9%): [3.458, 5.068] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.103 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.022 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.667 ±(99.9%) 0.018 ms/op
Iteration   1: 4.476 ±(99.9%) 0.007 ms/op
Iteration   2: 4.549 ±(99.9%) 0.004 ms/op
Iteration   3: 4.544 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.523 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (4.476, 4.523, 4.549), stdev = 0.041
  CI (99.9%): [3.779, 5.267] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.423 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 7.089 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.269 ±(99.9%) 0.012 ms/op
Iteration   1: 5.871 ±(99.9%) 0.014 ms/op
Iteration   2: 5.877 ±(99.9%) 0.020 ms/op
Iteration   3: 5.820 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.856 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (5.820, 5.856, 5.877), stdev = 0.032
  CI (99.9%): [5.280, 6.433] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.280 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 4.905 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.549 ±(99.9%) 0.016 ms/op
Iteration   1: 4.391 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  13.045 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 4.514 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.865 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   9.045 ms/op
                 createUser·p0.999:  15.877 ms/op
                 createUser·p0.9999: 23.757 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 4.368 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   6.324 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  14.643 ms/op
                 createUser·p0.9999: 30.005 ms/op
                 createUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217108
  mean =      4.424 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6669 
    [ 2.500,  5.000) = 166413 
    [ 5.000,  7.500) = 39278 
    [ 7.500, 10.000) = 3693 
    [10.000, 12.500) = 738 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     27.497 ms/op
     p(99.9990) =     30.875 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.494 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.833 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.425 ±(99.9%) 0.014 ms/op
Iteration   1: 4.223 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.505 ms/op
                 existUser·p0.95:   6.144 ms/op
                 existUser·p0.99:   8.053 ms/op
                 existUser·p0.999:  12.059 ms/op
                 existUser·p0.9999: 22.811 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 4.215 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   6.046 ms/op
                 existUser·p0.99:   8.716 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 22.880 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   3: 4.282 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.571 ms/op
                 existUser·p0.95:   6.242 ms/op
                 existUser·p0.99:   8.749 ms/op
                 existUser·p0.999:  14.800 ms/op
                 existUser·p0.9999: 26.068 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 226263
  mean =      4.240 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10995 
    [ 2.500,  5.000) = 177451 
    [ 5.000,  7.500) = 33680 
    [ 7.500, 10.000) = 3215 
    [10.000, 12.500) = 646 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.442 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.068 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.569 ±(99.9%) 0.016 ms/op
Iteration   1: 4.497 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.324 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  11.680 ms/op
                 getUser·p0.9999: 17.353 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 4.613 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.865 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  16.411 ms/op
                 getUser·p0.9999: 25.471 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   3: 4.576 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   6.431 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 25.002 ms/op
                 getUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210470
  mean =      4.562 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4214 
    [ 2.500,  5.000) = 153597 
    [ 5.000,  7.500) = 47837 
    [ 7.500, 10.000) = 3738 
    [10.000, 12.500) = 860 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     12.583 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     25.997 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.287 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.405 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.929 ±(99.9%) 0.027 ms/op
Iteration   1: 5.733 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   7.856 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  16.964 ms/op
                 listUser·p0.9999: 19.773 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 5.830 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   11.787 ms/op
                 listUser·p0.999:  20.288 ms/op
                 listUser·p0.9999: 22.694 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   3: 6.010 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   5.595 ms/op
                 listUser·p0.90:   8.004 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  33.686 ms/op
                 listUser·p0.9999: 39.256 ms/op
                 listUser·p1.00:   39.715 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163857
  mean =      5.856 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 51378 
    [ 5.000,  7.500) = 91129 
    [ 7.500, 10.000) = 16969 
    [10.000, 12.500) = 3091 
    [12.500, 15.000) = 748 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.897 ms/op
     p(95.0000) =      8.978 ms/op
     p(99.0000) =     11.846 ms/op
     p(99.9000) =     19.797 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     39.673 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.092 ± 0.487  ops/ms
ClientGrpc.existUser                       thrpt       3   7.311 ± 4.183  ops/ms
ClientGrpc.getUser                         thrpt       3   6.920 ± 1.442  ops/ms
ClientGrpc.listUser                        thrpt       3   5.486 ± 0.671  ops/ms
ClientGrpc.createUser                       avgt       3   4.567 ± 0.656   ms/op
ClientGrpc.existUser                        avgt       3   4.263 ± 0.805   ms/op
ClientGrpc.getUser                          avgt       3   4.523 ± 0.744   ms/op
ClientGrpc.listUser                         avgt       3   5.856 ± 0.576   ms/op
ClientGrpc.createUser                     sample  217108   4.424 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.980           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.398           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.798           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.123           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.497           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.490           ms/op
ClientGrpc.existUser                      sample  226263   4.240 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.887           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.480           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.144           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.520           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.943           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.428           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.672           ms/op
ClientGrpc.getUser                        sample  210470   4.562 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.959           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.775           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.455           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.798           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.583           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.805           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.623           ms/op
ClientGrpc.listUser                       sample  163857   5.856 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.169           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.897           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.978           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.846           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.797           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.683           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.715           ms/op
