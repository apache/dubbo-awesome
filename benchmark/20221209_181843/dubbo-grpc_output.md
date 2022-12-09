# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.241 ops/ms
# Warmup Iteration   2: 5.860 ops/ms
# Warmup Iteration   3: 7.128 ops/ms
Iteration   1: 7.644 ops/ms
Iteration   2: 7.570 ops/ms
Iteration   3: 7.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.687 ±(99.9%) 2.609 ops/ms [Average]
  (min, avg, max) = (7.570, 7.687, 7.846), stdev = 0.143
  CI (99.9%): [5.078, 10.296] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.344 ops/ms
# Warmup Iteration   2: 8.329 ops/ms
# Warmup Iteration   3: 8.576 ops/ms
Iteration   1: 8.590 ops/ms
Iteration   2: 8.834 ops/ms
Iteration   3: 8.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.523 ±(99.9%) 6.376 ops/ms [Average]
  (min, avg, max) = (8.144, 8.523, 8.834), stdev = 0.349
  CI (99.9%): [2.147, 14.899] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ops/ms
# Warmup Iteration   2: 6.710 ops/ms
# Warmup Iteration   3: 7.309 ops/ms
Iteration   1: 7.497 ops/ms
Iteration   2: 7.684 ops/ms
Iteration   3: 7.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.683 ±(99.9%) 3.384 ops/ms [Average]
  (min, avg, max) = (7.497, 7.683, 7.868), stdev = 0.185
  CI (99.9%): [4.300, 11.067] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.028 ops/ms
# Warmup Iteration   2: 5.672 ops/ms
# Warmup Iteration   3: 6.142 ops/ms
Iteration   1: 6.173 ops/ms
Iteration   2: 6.070 ops/ms
Iteration   3: 6.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.085 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (6.013, 6.085, 6.173), stdev = 0.081
  CI (99.9%): [4.606, 7.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.738 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.856 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.408 ±(99.9%) 0.008 ms/op
Iteration   1: 4.204 ±(99.9%) 0.003 ms/op
Iteration   2: 4.345 ±(99.9%) 0.004 ms/op
Iteration   3: 4.279 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.276 ±(99.9%) 1.286 ms/op [Average]
  (min, avg, max) = (4.204, 4.276, 4.345), stdev = 0.070
  CI (99.9%): [2.990, 5.562] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.286 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.003 ms/op
Iteration   1: 4.097 ±(99.9%) 0.003 ms/op
Iteration   2: 4.106 ±(99.9%) 0.003 ms/op
Iteration   3: 4.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.093 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (4.076, 4.093, 4.106), stdev = 0.015
  CI (99.9%): [3.814, 4.373] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.633 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.502 ±(99.9%) 0.003 ms/op
Iteration   1: 4.494 ±(99.9%) 0.002 ms/op
Iteration   2: 4.401 ±(99.9%) 0.005 ms/op
Iteration   3: 4.313 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.403 ±(99.9%) 1.647 ms/op [Average]
  (min, avg, max) = (4.313, 4.403, 4.494), stdev = 0.090
  CI (99.9%): [2.755, 6.050] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.966 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.549 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.099 ±(99.9%) 0.013 ms/op
Iteration   1: 5.197 ±(99.9%) 0.016 ms/op
Iteration   2: 5.278 ±(99.9%) 0.010 ms/op
Iteration   3: 5.313 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.263 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (5.197, 5.263, 5.313), stdev = 0.060
  CI (99.9%): [4.175, 6.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.328 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.482 ±(99.9%) 0.015 ms/op
Iteration   1: 4.472 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   8.798 ms/op
                 createUser·p0.999:  21.003 ms/op
                 createUser·p0.9999: 25.652 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   2: 4.192 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  12.302 ms/op
                 createUser·p0.9999: 38.747 ms/op
                 createUser·p1.00:   39.977 ms/op

Iteration   3: 4.168 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   4.067 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  11.461 ms/op
                 createUser·p0.9999: 26.957 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224601
  mean =      4.273 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4319 
    [ 2.500,  5.000) = 184347 
    [ 5.000,  7.500) = 32743 
    [ 7.500, 10.000) = 2445 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     13.776 ms/op
     p(99.9900) =     37.437 ms/op
     p(99.9990) =     39.830 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.529 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.011 ms/op
Iteration   1: 4.029 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   5.128 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   7.815 ms/op
                 existUser·p0.999:  11.407 ms/op
                 existUser·p0.9999: 18.948 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 4.048 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   7.062 ms/op
                 existUser·p0.999:  13.189 ms/op
                 existUser·p0.9999: 20.038 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   3: 4.024 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  12.938 ms/op
                 existUser·p0.9999: 21.238 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237992
  mean =      4.034 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10608 
    [ 2.500,  5.000) = 196655 
    [ 5.000,  7.500) = 28449 
    [ 7.500, 10.000) = 1738 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     20.559 ms/op
     p(99.9990) =     21.688 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.138 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.393 ±(99.9%) 0.013 ms/op
Iteration   1: 4.417 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.864 ms/op
                 getUser·p0.999:  14.257 ms/op
                 getUser·p0.9999: 17.294 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   2: 4.445 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  13.877 ms/op
                 getUser·p0.9999: 18.278 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   3: 4.378 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.579 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   8.225 ms/op
                 getUser·p0.999:  14.172 ms/op
                 getUser·p0.9999: 20.095 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217447
  mean =      4.413 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3848 
    [ 2.500,  5.000) = 163277 
    [ 5.000,  7.500) = 46808 
    [ 7.500, 10.000) = 2542 
    [10.000, 12.500) = 544 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.070 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     14.067 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.049 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.406 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.302 ±(99.9%) 0.020 ms/op
Iteration   1: 5.157 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.741 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  16.090 ms/op
                 listUser·p0.9999: 20.892 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 5.298 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   10.519 ms/op
                 listUser·p0.999:  16.995 ms/op
                 listUser·p0.9999: 19.790 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 5.370 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.553 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.159 ms/op
                 listUser·p0.99:   11.403 ms/op
                 listUser·p0.999:  32.719 ms/op
                 listUser·p0.9999: 40.174 ms/op
                 listUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181991
  mean =      5.273 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 95798 
    [ 5.000, 10.000) = 83768 
    [10.000, 15.000) = 2003 
    [15.000, 20.000) = 320 
    [20.000, 25.000) = 38 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 40 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      7.094 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     38.575 ms/op
     p(99.9990) =     40.436 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.687 ± 2.609  ops/ms
ClientGrpc.existUser                       thrpt       3   8.523 ± 6.376  ops/ms
ClientGrpc.getUser                         thrpt       3   7.683 ± 3.384  ops/ms
ClientGrpc.listUser                        thrpt       3   6.085 ± 1.479  ops/ms
ClientGrpc.createUser                       avgt       3   4.276 ± 1.286   ms/op
ClientGrpc.existUser                        avgt       3   4.093 ± 0.280   ms/op
ClientGrpc.getUser                          avgt       3   4.403 ± 1.647   ms/op
ClientGrpc.listUser                         avgt       3   5.263 ± 1.088   ms/op
ClientGrpc.createUser                     sample  224601   4.273 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.600           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.078           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.995           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.776           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          37.437           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.977           ms/op
ClientGrpc.existUser                      sample  237992   4.034 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.872           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.430           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.911           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.559           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.758           ms/op
ClientGrpc.getUser                        sample  217447   4.413 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.922           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.571           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.070           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.339           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.067           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.579           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.856           ms/op
ClientGrpc.listUser                       sample  181991   5.273 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.553           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.995           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.600           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.793           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          38.575           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.436           ms/op
