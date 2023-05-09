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
# Warmup Iteration   1: 2.122 ops/ms
# Warmup Iteration   2: 4.872 ops/ms
# Warmup Iteration   3: 6.570 ops/ms
Iteration   1: 6.834 ops/ms
Iteration   2: 6.976 ops/ms
Iteration   3: 7.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.957 ±(99.9%) 2.088 ops/ms [Average]
  (min, avg, max) = (6.834, 6.957, 7.061), stdev = 0.114
  CI (99.9%): [4.869, 9.045] (assumes normal distribution)


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
# Warmup Iteration   1: 4.640 ops/ms
# Warmup Iteration   2: 7.220 ops/ms
# Warmup Iteration   3: 7.700 ops/ms
Iteration   1: 7.707 ops/ms
Iteration   2: 7.727 ops/ms
Iteration   3: 7.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.735 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (7.707, 7.735, 7.771), stdev = 0.033
  CI (99.9%): [7.132, 8.337] (assumes normal distribution)


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
# Warmup Iteration   1: 3.716 ops/ms
# Warmup Iteration   2: 6.577 ops/ms
# Warmup Iteration   3: 7.088 ops/ms
Iteration   1: 7.295 ops/ms
Iteration   2: 7.175 ops/ms
Iteration   3: 7.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.186 ±(99.9%) 1.901 ops/ms [Average]
  (min, avg, max) = (7.087, 7.186, 7.295), stdev = 0.104
  CI (99.9%): [5.284, 9.087] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ops/ms
# Warmup Iteration   2: 4.819 ops/ms
# Warmup Iteration   3: 5.338 ops/ms
Iteration   1: 5.501 ops/ms
Iteration   2: 5.476 ops/ms
Iteration   3: 5.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.574 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (5.476, 5.574, 5.745), stdev = 0.148
  CI (99.9%): [2.870, 8.278] (assumes normal distribution)


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
# Warmup Iteration   1: 6.839 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.841 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.550 ±(99.9%) 0.008 ms/op
Iteration   1: 4.429 ±(99.9%) 0.004 ms/op
Iteration   2: 4.328 ±(99.9%) 0.003 ms/op
Iteration   3: 4.402 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.386 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (4.328, 4.386, 4.429), stdev = 0.052
  CI (99.9%): [3.429, 5.344] (assumes normal distribution)


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
# Warmup Iteration   1: 6.460 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.422 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.228 ±(99.9%) 0.004 ms/op
Iteration   1: 4.038 ±(99.9%) 0.004 ms/op
Iteration   2: 4.092 ±(99.9%) 0.003 ms/op
Iteration   3: 4.184 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.105 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (4.038, 4.105, 4.184), stdev = 0.074
  CI (99.9%): [2.758, 5.451] (assumes normal distribution)


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
# Warmup Iteration   1: 7.221 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.830 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.698 ±(99.9%) 0.003 ms/op
Iteration   1: 4.523 ±(99.9%) 0.004 ms/op
Iteration   2: 4.544 ±(99.9%) 0.007 ms/op
Iteration   3: 4.508 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.525 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (4.508, 4.525, 4.544), stdev = 0.018
  CI (99.9%): [4.202, 4.848] (assumes normal distribution)


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
# Warmup Iteration   1: 7.905 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 6.505 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.908 ±(99.9%) 0.019 ms/op
Iteration   1: 5.906 ±(99.9%) 0.023 ms/op
Iteration   2: 5.812 ±(99.9%) 0.016 ms/op
Iteration   3: 5.918 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.879 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (5.812, 5.879, 5.918), stdev = 0.058
  CI (99.9%): [4.824, 6.934] (assumes normal distribution)


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
# Warmup Iteration   1: 6.806 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.943 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.659 ±(99.9%) 0.014 ms/op
Iteration   1: 4.534 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   7.345 ms/op
                 createUser·p0.999:  13.189 ms/op
                 createUser·p0.9999: 20.445 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 4.397 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.882 ms/op
                 createUser·p0.99:   7.561 ms/op
                 createUser·p0.999:  17.410 ms/op
                 createUser·p0.9999: 29.777 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   3: 4.478 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  19.155 ms/op
                 createUser·p0.9999: 28.433 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214794
  mean =      4.469 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5130 
    [ 2.500,  5.000) = 162924 
    [ 5.000,  7.500) = 44580 
    [ 7.500, 10.000) = 1512 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     16.460 ms/op
     p(99.9900) =     29.246 ms/op
     p(99.9990) =     30.225 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 6.497 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.011 ms/op
Iteration   1: 4.220 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  11.063 ms/op
                 existUser·p0.9999: 21.791 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   2: 4.291 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.333 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  11.198 ms/op
                 existUser·p0.9999: 18.630 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   3: 4.223 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  12.708 ms/op
                 existUser·p0.9999: 22.086 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 225972
  mean =      4.244 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5646 
    [ 2.500,  5.000) = 186574 
    [ 5.000,  7.500) = 32204 
    [ 7.500, 10.000) = 1139 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      4.141 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     11.471 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     22.306 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 7.108 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.030 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.596 ±(99.9%) 0.012 ms/op
Iteration   1: 4.515 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  12.281 ms/op
                 getUser·p0.9999: 16.690 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 4.659 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   7.881 ms/op
                 getUser·p0.999:  10.485 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   3: 4.544 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  9.929 ms/op
                 getUser·p0.9999: 21.128 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 209883
  mean =      4.572 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3311 
    [ 2.500,  5.000) = 152306 
    [ 5.000,  7.500) = 52192 
    [ 7.500, 10.000) = 1695 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     21.712 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 8.518 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.233 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.769 ±(99.9%) 0.022 ms/op
Iteration   1: 5.708 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.339 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  27.754 ms/op
                 listUser·p0.9999: 30.952 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   2: 5.719 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   7.053 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  28.671 ms/op
                 listUser·p0.9999: 34.079 ms/op
                 listUser·p1.00:   34.406 ms/op

Iteration   3: 5.768 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  26.968 ms/op
                 listUser·p0.9999: 32.158 ms/op
                 listUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167366
  mean =      5.732 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 50082 
    [ 5.000,  7.500) = 100913 
    [ 7.500, 10.000) = 13503 
    [10.000, 12.500) = 2136 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.455 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     27.698 ms/op
     p(99.9900) =     33.146 ms/op
     p(99.9990) =     34.274 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.957 ± 2.088  ops/ms
ClientGrpc.existUser                       thrpt       3   7.735 ± 0.602  ops/ms
ClientGrpc.getUser                         thrpt       3   7.186 ± 1.901  ops/ms
ClientGrpc.listUser                        thrpt       3   5.574 ± 2.704  ops/ms
ClientGrpc.createUser                       avgt       3   4.386 ± 0.957   ms/op
ClientGrpc.existUser                        avgt       3   4.105 ± 1.346   ms/op
ClientGrpc.getUser                          avgt       3   4.525 ± 0.323   ms/op
ClientGrpc.listUser                         avgt       3   5.879 ± 1.055   ms/op
ClientGrpc.createUser                     sample  214794   4.469 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.807           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.513           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.947           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.512           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.460           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.246           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.278           ms/op
ClientGrpc.existUser                      sample  225972   4.244 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.024           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.267           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.012           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.660           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.315           ms/op
ClientGrpc.getUser                        sample  209883   4.572 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.210           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.062           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.479           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.190           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.366           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.823           ms/op
ClientGrpc.listUser                       sample  167366   5.732 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.153           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.455           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.487           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.715           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          27.698           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.146           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.406           ms/op
