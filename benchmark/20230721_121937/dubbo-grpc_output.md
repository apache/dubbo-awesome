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
# Warmup Iteration   1: 2.420 ops/ms
# Warmup Iteration   2: 5.696 ops/ms
# Warmup Iteration   3: 7.147 ops/ms
Iteration   1: 7.335 ops/ms
Iteration   2: 7.475 ops/ms
Iteration   3: 7.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.455 ±(99.9%) 2.025 ops/ms [Average]
  (min, avg, max) = (7.335, 7.455, 7.554), stdev = 0.111
  CI (99.9%): [5.430, 9.480] (assumes normal distribution)


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
# Warmup Iteration   1: 4.675 ops/ms
# Warmup Iteration   2: 7.402 ops/ms
# Warmup Iteration   3: 7.891 ops/ms
Iteration   1: 8.061 ops/ms
Iteration   2: 8.074 ops/ms
Iteration   3: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.080 ±(99.9%) 0.411 ops/ms [Average]
  (min, avg, max) = (8.061, 8.080, 8.105), stdev = 0.023
  CI (99.9%): [7.669, 8.491] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.357 ops/ms
# Warmup Iteration   2: 6.936 ops/ms
# Warmup Iteration   3: 7.165 ops/ms
Iteration   1: 7.443 ops/ms
Iteration   2: 7.430 ops/ms
Iteration   3: 7.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.449 ±(99.9%) 0.429 ops/ms [Average]
  (min, avg, max) = (7.430, 7.449, 7.476), stdev = 0.024
  CI (99.9%): [7.020, 7.879] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ops/ms
# Warmup Iteration   2: 5.342 ops/ms
# Warmup Iteration   3: 5.790 ops/ms
Iteration   1: 5.942 ops/ms
Iteration   2: 5.986 ops/ms
Iteration   3: 6.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.001 ±(99.9%) 1.240 ops/ms [Average]
  (min, avg, max) = (5.942, 6.001, 6.076), stdev = 0.068
  CI (99.9%): [4.761, 7.242] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.092 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.404 ±(99.9%) 0.027 ms/op
Iteration   1: 4.208 ±(99.9%) 0.003 ms/op
Iteration   2: 4.178 ±(99.9%) 0.004 ms/op
Iteration   3: 4.126 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.171 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (4.126, 4.171, 4.208), stdev = 0.041
  CI (99.9%): [3.415, 4.927] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.275 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.004 ms/op
Iteration   1: 4.060 ±(99.9%) 0.003 ms/op
Iteration   2: 4.152 ±(99.9%) 0.004 ms/op
Iteration   3: 3.953 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.055 ±(99.9%) 1.824 ms/op [Average]
  (min, avg, max) = (3.953, 4.055, 4.152), stdev = 0.100
  CI (99.9%): [2.231, 5.879] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.092 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.006 ms/op
Iteration   1: 4.200 ±(99.9%) 0.003 ms/op
Iteration   2: 4.237 ±(99.9%) 0.004 ms/op
Iteration   3: 4.188 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.208 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (4.188, 4.208, 4.237), stdev = 0.026
  CI (99.9%): [3.739, 4.678] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.112 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.849 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.483 ±(99.9%) 0.024 ms/op
Iteration   1: 5.390 ±(99.9%) 0.017 ms/op
Iteration   2: 5.490 ±(99.9%) 0.013 ms/op
Iteration   3: 5.514 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.464 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (5.390, 5.464, 5.514), stdev = 0.066
  CI (99.9%): [4.267, 6.662] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.689 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.333 ±(99.9%) 0.014 ms/op
Iteration   1: 4.276 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   4.125 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.923 ms/op
                 createUser·p0.99:   7.627 ms/op
                 createUser·p0.999:  12.904 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   21.627 ms/op

Iteration   2: 4.193 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  10.961 ms/op
                 createUser·p0.9999: 20.197 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 4.263 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.121 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  17.889 ms/op
                 createUser·p0.9999: 25.149 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 226081
  mean =      4.244 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3771 
    [ 2.500,  5.000) = 187588 
    [ 5.000,  7.500) = 32422 
    [ 7.500, 10.000) = 1791 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     12.713 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     25.804 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.342 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.011 ms/op
Iteration   1: 3.947 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 22.246 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 19.854 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   3: 4.118 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   7.201 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236959
  mean =      4.049 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4399 
    [ 2.500,  5.000) = 205430 
    [ 5.000,  7.500) = 25384 
    [ 7.500, 10.000) = 1351 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     24.137 ms/op
     p(99.9990) =     24.781 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 6.701 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.012 ms/op
Iteration   1: 4.231 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   4.092 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   7.758 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 15.548 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   2: 4.142 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  12.020 ms/op
                 getUser·p0.9999: 19.745 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   3: 4.074 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  11.819 ms/op
                 getUser·p0.9999: 21.046 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231357
  mean =      4.148 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7500 
    [ 2.500,  5.000) = 193014 
    [ 5.000,  7.500) = 28723 
    [ 7.500, 10.000) = 1610 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     11.987 ms/op
     p(99.9900) =     20.115 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 8.560 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.709 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.559 ±(99.9%) 0.021 ms/op
Iteration   1: 5.465 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  16.751 ms/op
                 listUser·p0.9999: 18.355 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 5.267 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.815 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 5.333 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   5.087 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  21.135 ms/op
                 listUser·p0.9999: 27.263 ms/op
                 listUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179367
  mean =      5.354 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 82450 
    [ 5.000,  7.500) = 84639 
    [ 7.500, 10.000) = 9830 
    [10.000, 12.500) = 1783 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     10.425 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     24.644 ms/op
     p(99.9990) =     27.670 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.455 ± 2.025  ops/ms
ClientGrpc.existUser                       thrpt       3   8.080 ± 0.411  ops/ms
ClientGrpc.getUser                         thrpt       3   7.449 ± 0.429  ops/ms
ClientGrpc.listUser                        thrpt       3   6.001 ± 1.240  ops/ms
ClientGrpc.createUser                       avgt       3   4.171 ± 0.756   ms/op
ClientGrpc.existUser                        avgt       3   4.055 ± 1.824   ms/op
ClientGrpc.getUser                          avgt       3   4.208 ± 0.470   ms/op
ClientGrpc.listUser                         avgt       3   5.464 ± 1.198   ms/op
ClientGrpc.createUser                     sample  226081   4.244 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.027           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.112           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.300           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.528           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.713           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.740           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.018           ms/op
ClientGrpc.existUser                      sample  236959   4.049 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.859           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.095           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.222           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.137           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.838           ms/op
ClientGrpc.getUser                        sample  231357   4.148 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.902           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.210           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.726           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.987           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.115           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.332           ms/op
ClientGrpc.listUser                       sample  179367   5.354 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.309           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.922           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.425           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.644           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.722           ms/op
