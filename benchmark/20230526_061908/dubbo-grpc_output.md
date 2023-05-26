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
# Warmup Iteration   1: 2.257 ops/ms
# Warmup Iteration   2: 5.168 ops/ms
# Warmup Iteration   3: 6.548 ops/ms
Iteration   1: 7.204 ops/ms
Iteration   2: 7.166 ops/ms
Iteration   3: 7.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.226 ±(99.9%) 1.348 ops/ms [Average]
  (min, avg, max) = (7.166, 7.226, 7.309), stdev = 0.074
  CI (99.9%): [5.878, 8.575] (assumes normal distribution)


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
# Warmup Iteration   1: 4.643 ops/ms
# Warmup Iteration   2: 7.225 ops/ms
# Warmup Iteration   3: 7.591 ops/ms
Iteration   1: 7.551 ops/ms
Iteration   2: 7.642 ops/ms
Iteration   3: 7.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.643 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (7.551, 7.643, 7.734), stdev = 0.092
  CI (99.9%): [5.972, 9.313] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ops/ms
# Warmup Iteration   2: 6.485 ops/ms
# Warmup Iteration   3: 7.066 ops/ms
Iteration   1: 7.521 ops/ms
Iteration   2: 7.382 ops/ms
Iteration   3: 7.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.467 ±(99.9%) 1.359 ops/ms [Average]
  (min, avg, max) = (7.382, 7.467, 7.521), stdev = 0.075
  CI (99.9%): [6.108, 8.826] (assumes normal distribution)


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
# Warmup Iteration   1: 3.879 ops/ms
# Warmup Iteration   2: 5.160 ops/ms
# Warmup Iteration   3: 5.576 ops/ms
Iteration   1: 5.864 ops/ms
Iteration   2: 5.737 ops/ms
Iteration   3: 5.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.762 ±(99.9%) 1.679 ops/ms [Average]
  (min, avg, max) = (5.686, 5.762, 5.864), stdev = 0.092
  CI (99.9%): [4.083, 7.441] (assumes normal distribution)


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
# Warmup Iteration   1: 6.318 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.343 ±(99.9%) 0.007 ms/op
Iteration   1: 4.516 ±(99.9%) 0.002 ms/op
Iteration   2: 4.563 ±(99.9%) 0.004 ms/op
Iteration   3: 4.467 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.515 ±(99.9%) 0.874 ms/op [Average]
  (min, avg, max) = (4.467, 4.515, 4.563), stdev = 0.048
  CI (99.9%): [3.642, 5.389] (assumes normal distribution)


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
# Warmup Iteration   1: 6.145 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.004 ms/op
Iteration   1: 4.112 ±(99.9%) 0.004 ms/op
Iteration   2: 4.069 ±(99.9%) 0.003 ms/op
Iteration   3: 3.880 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.020 ±(99.9%) 2.252 ms/op [Average]
  (min, avg, max) = (3.880, 4.020, 4.112), stdev = 0.123
  CI (99.9%): [1.769, 6.272] (assumes normal distribution)


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
# Warmup Iteration   1: 6.209 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.359 ±(99.9%) 0.005 ms/op
Iteration   1: 4.252 ±(99.9%) 0.008 ms/op
Iteration   2: 4.311 ±(99.9%) 0.004 ms/op
Iteration   3: 4.214 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.259 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (4.214, 4.259, 4.311), stdev = 0.049
  CI (99.9%): [3.363, 5.155] (assumes normal distribution)


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
# Warmup Iteration   1: 8.265 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 6.379 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.600 ±(99.9%) 0.020 ms/op
Iteration   1: 5.683 ±(99.9%) 0.018 ms/op
Iteration   2: 5.614 ±(99.9%) 0.022 ms/op
Iteration   3: 5.695 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.664 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (5.614, 5.664, 5.695), stdev = 0.044
  CI (99.9%): [4.864, 6.464] (assumes normal distribution)


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
# Warmup Iteration   1: 6.805 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.605 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.442 ±(99.9%) 0.016 ms/op
Iteration   1: 4.322 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   8.102 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 16.967 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 4.239 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.374 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  13.976 ms/op
                 createUser·p0.9999: 21.231 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   3: 4.388 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  14.649 ms/op
                 createUser·p0.9999: 23.442 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222406
  mean =      4.315 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5482 
    [ 2.500,  5.000) = 176238 
    [ 5.000,  7.500) = 37880 
    [ 7.500, 10.000) = 2206 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.840 ms/op
     p(99.9000) =     14.002 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     24.237 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 6.018 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.169 ±(99.9%) 0.013 ms/op
Iteration   1: 3.998 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  9.618 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 4.047 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   3.883 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   7.332 ms/op
                 existUser·p0.999:  13.205 ms/op
                 existUser·p0.9999: 29.668 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   3: 4.008 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.736 ms/op
                 existUser·p0.999:  12.161 ms/op
                 existUser·p0.9999: 22.152 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238755
  mean =      4.018 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7253 
    [ 2.500,  5.000) = 204468 
    [ 5.000,  7.500) = 24875 
    [ 7.500, 10.000) = 1516 
    [10.000, 12.500) = 456 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     12.046 ms/op
     p(99.9900) =     28.156 ms/op
     p(99.9990) =     30.285 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 6.524 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.889 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.573 ±(99.9%) 0.015 ms/op
Iteration   1: 4.438 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.579 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  11.795 ms/op
                 getUser·p0.9999: 14.942 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   2: 4.601 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.923 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   9.074 ms/op
                 getUser·p0.999:  15.564 ms/op
                 getUser·p0.9999: 22.026 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 4.636 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   6.709 ms/op
                 getUser·p0.99:   9.142 ms/op
                 getUser·p0.999:  14.889 ms/op
                 getUser·p0.9999: 27.335 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210644
  mean =      4.557 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4915 
    [ 2.500,  5.000) = 150049 
    [ 5.000,  7.500) = 51146 
    [ 7.500, 10.000) = 3550 
    [10.000, 12.500) = 716 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.488 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     13.971 ms/op
     p(99.9900) =     23.345 ms/op
     p(99.9990) =     27.744 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 9.327 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 6.513 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.789 ±(99.9%) 0.023 ms/op
Iteration   1: 5.649 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.578 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.125 ms/op
                 listUser·p0.999:  16.656 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 5.792 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   8.020 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  19.662 ms/op
                 listUser·p0.9999: 28.196 ms/op
                 listUser·p1.00:   35.979 ms/op

Iteration   3: 5.956 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   8.036 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  23.968 ms/op
                 listUser·p0.9999: 29.986 ms/op
                 listUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165639
  mean =      5.796 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 255 
    [ 2.500,  5.000) = 54458 
    [ 5.000,  7.500) = 89872 
    [ 7.500, 10.000) = 17019 
    [10.000, 12.500) = 2985 
    [12.500, 15.000) = 603 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.889 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     20.733 ms/op
     p(99.9900) =     28.096 ms/op
     p(99.9990) =     35.893 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.226 ± 1.348  ops/ms
ClientGrpc.existUser                       thrpt       3   7.643 ± 1.671  ops/ms
ClientGrpc.getUser                         thrpt       3   7.467 ± 1.359  ops/ms
ClientGrpc.listUser                        thrpt       3   5.762 ± 1.679  ops/ms
ClientGrpc.createUser                       avgt       3   4.515 ± 0.874   ms/op
ClientGrpc.existUser                        avgt       3   4.020 ± 2.252   ms/op
ClientGrpc.getUser                          avgt       3   4.259 ± 0.896   ms/op
ClientGrpc.listUser                         avgt       3   5.664 ± 0.800   ms/op
ClientGrpc.createUser                     sample  222406   4.315 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.966           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.947           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.840           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.002           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.807           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.347           ms/op
ClientGrpc.existUser                      sample  238755   4.018 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.732           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.095           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.628           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.348           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.046           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.156           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.343           ms/op
ClientGrpc.getUser                        sample  210644   4.557 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.206           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.488           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.684           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.971           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.345           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.886           ms/op
ClientGrpc.listUser                       sample  165639   5.796 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.317           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.889           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.897           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.534           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.733           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.096           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.979           ms/op
