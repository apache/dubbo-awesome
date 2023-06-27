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
# Warmup Iteration   1: 2.032 ops/ms
# Warmup Iteration   2: 4.797 ops/ms
# Warmup Iteration   3: 6.404 ops/ms
Iteration   1: 6.596 ops/ms
Iteration   2: 6.915 ops/ms
Iteration   3: 6.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.828 ±(99.9%) 3.700 ops/ms [Average]
  (min, avg, max) = (6.596, 6.828, 6.973), stdev = 0.203
  CI (99.9%): [3.128, 10.528] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ops/ms
# Warmup Iteration   2: 6.774 ops/ms
# Warmup Iteration   3: 7.377 ops/ms
Iteration   1: 7.462 ops/ms
Iteration   2: 7.413 ops/ms
Iteration   3: 7.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.462 ±(99.9%) 0.881 ops/ms [Average]
  (min, avg, max) = (7.413, 7.462, 7.510), stdev = 0.048
  CI (99.9%): [6.581, 8.342] (assumes normal distribution)


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
# Warmup Iteration   1: 3.983 ops/ms
# Warmup Iteration   2: 6.576 ops/ms
# Warmup Iteration   3: 7.016 ops/ms
Iteration   1: 7.270 ops/ms
Iteration   2: 7.276 ops/ms
Iteration   3: 7.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.280 ±(99.9%) 0.232 ops/ms [Average]
  (min, avg, max) = (7.270, 7.280, 7.294), stdev = 0.013
  CI (99.9%): [7.047, 7.512] (assumes normal distribution)


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
# Warmup Iteration   1: 3.494 ops/ms
# Warmup Iteration   2: 4.338 ops/ms
# Warmup Iteration   3: 5.391 ops/ms
Iteration   1: 5.614 ops/ms
Iteration   2: 5.582 ops/ms
Iteration   3: 5.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.560 ±(99.9%) 1.231 ops/ms [Average]
  (min, avg, max) = (5.484, 5.560, 5.614), stdev = 0.067
  CI (99.9%): [4.329, 6.791] (assumes normal distribution)


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
# Warmup Iteration   1: 6.687 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.905 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.612 ±(99.9%) 0.005 ms/op
Iteration   1: 4.493 ±(99.9%) 0.003 ms/op
Iteration   2: 4.620 ±(99.9%) 0.004 ms/op
Iteration   3: 4.597 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.570 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (4.493, 4.570, 4.620), stdev = 0.068
  CI (99.9%): [3.334, 5.806] (assumes normal distribution)


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
# Warmup Iteration   1: 6.006 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.359 ±(99.9%) 0.002 ms/op
Iteration   1: 4.320 ±(99.9%) 0.002 ms/op
Iteration   2: 4.317 ±(99.9%) 0.002 ms/op
Iteration   3: 4.216 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.285 ±(99.9%) 1.084 ms/op [Average]
  (min, avg, max) = (4.216, 4.285, 4.320), stdev = 0.059
  CI (99.9%): [3.201, 5.368] (assumes normal distribution)


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
# Warmup Iteration   1: 7.126 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.589 ±(99.9%) 0.009 ms/op
Iteration   1: 4.482 ±(99.9%) 0.004 ms/op
Iteration   2: 4.510 ±(99.9%) 0.004 ms/op
Iteration   3: 4.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.488 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (4.474, 4.488, 4.510), stdev = 0.019
  CI (99.9%): [4.136, 4.841] (assumes normal distribution)


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
# Warmup Iteration   1: 8.926 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.347 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.818 ±(99.9%) 0.026 ms/op
Iteration   1: 5.767 ±(99.9%) 0.025 ms/op
Iteration   2: 5.866 ±(99.9%) 0.031 ms/op
Iteration   3: 5.875 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.836 ±(99.9%) 1.093 ms/op [Average]
  (min, avg, max) = (5.767, 5.836, 5.875), stdev = 0.060
  CI (99.9%): [4.743, 6.929] (assumes normal distribution)


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
# Warmup Iteration   1: 7.074 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.726 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.556 ±(99.9%) 0.015 ms/op
Iteration   1: 4.424 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.725 ms/op
                 createUser·p0.999:  15.186 ms/op
                 createUser·p0.9999: 27.378 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 4.465 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   7.971 ms/op
                 createUser·p0.999:  13.058 ms/op
                 createUser·p0.9999: 33.156 ms/op
                 createUser·p1.00:   33.522 ms/op

Iteration   3: 4.543 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.913 ms/op
                 createUser·p0.999:  17.682 ms/op
                 createUser·p0.9999: 35.584 ms/op
                 createUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214414
  mean =      4.477 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2777 
    [ 2.500,  5.000) = 165218 
    [ 5.000,  7.500) = 43724 
    [ 7.500, 10.000) = 2082 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     33.693 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 6.746 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.014 ms/op
Iteration   1: 4.350 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.456 ms/op
                 existUser·p0.95:   5.964 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  12.292 ms/op
                 existUser·p0.9999: 17.081 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 4.246 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   7.356 ms/op
                 existUser·p0.999:  12.012 ms/op
                 existUser·p0.9999: 17.839 ms/op
                 existUser·p1.00:   18.252 ms/op

Iteration   3: 4.199 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   4.080 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.693 ms/op
                 existUser·p0.99:   7.602 ms/op
                 existUser·p0.999:  11.362 ms/op
                 existUser·p0.9999: 19.751 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 225161
  mean =      4.264 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3934 
    [ 2.500,  5.000) = 185915 
    [ 5.000,  7.500) = 33038 
    [ 7.500, 10.000) = 1808 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     11.597 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     20.554 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 6.988 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.079 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.573 ±(99.9%) 0.016 ms/op
Iteration   1: 4.539 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.013 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 4.553 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.718 ms/op
                 getUser·p0.95:   6.234 ms/op
                 getUser·p0.99:   8.212 ms/op
                 getUser·p0.999:  11.953 ms/op
                 getUser·p0.9999: 29.424 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 4.605 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.759 ms/op
                 getUser·p0.95:   6.259 ms/op
                 getUser·p0.99:   8.233 ms/op
                 getUser·p0.999:  12.345 ms/op
                 getUser·p0.9999: 29.006 ms/op
                 getUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210190
  mean =      4.566 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2883 
    [ 2.500,  5.000) = 151863 
    [ 5.000,  7.500) = 52419 
    [ 7.500, 10.000) = 2494 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.169 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     11.616 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     29.985 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 7.870 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.555 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.684 ±(99.9%) 0.021 ms/op
Iteration   1: 5.600 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.603 ms/op
                 listUser·p0.999:  18.836 ms/op
                 listUser·p0.9999: 27.010 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 5.833 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  18.942 ms/op
                 listUser·p0.9999: 24.068 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   3: 5.696 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  20.901 ms/op
                 listUser·p0.9999: 29.864 ms/op
                 listUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168149
  mean =      5.708 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 54075 
    [ 5.000,  7.500) = 96671 
    [ 7.500, 10.000) = 14491 
    [10.000, 12.500) = 2098 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     10.674 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     28.420 ms/op
     p(99.9990) =     30.352 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.828 ± 3.700  ops/ms
ClientGrpc.existUser                       thrpt       3   7.462 ± 0.881  ops/ms
ClientGrpc.getUser                         thrpt       3   7.280 ± 0.232  ops/ms
ClientGrpc.listUser                        thrpt       3   5.560 ± 1.231  ops/ms
ClientGrpc.createUser                       avgt       3   4.570 ± 1.236   ms/op
ClientGrpc.existUser                        avgt       3   4.285 ± 1.084   ms/op
ClientGrpc.getUser                          avgt       3   4.488 ± 0.352   ms/op
ClientGrpc.listUser                         avgt       3   5.836 ± 1.093   ms/op
ClientGrpc.createUser                     sample  214414   4.477 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.009           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.480           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.956           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.889           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.877           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.693           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.176           ms/op
ClientGrpc.existUser                      sample  225161   4.264 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.897           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.767           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.512           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.597           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.055           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  210190   4.566 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.809           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.685           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.169           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.004           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.616           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.000           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.079           ms/op
ClientGrpc.listUser                       sample  168149   5.708 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.323           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.674           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.825           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.420           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.441           ms/op
