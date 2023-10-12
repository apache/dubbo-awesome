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
# Warmup Iteration   1: 2.105 ops/ms
# Warmup Iteration   2: 4.308 ops/ms
# Warmup Iteration   3: 6.389 ops/ms
Iteration   1: 6.725 ops/ms
Iteration   2: 6.721 ops/ms
Iteration   3: 6.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.680 ±(99.9%) 1.347 ops/ms [Average]
  (min, avg, max) = (6.595, 6.680, 6.725), stdev = 0.074
  CI (99.9%): [5.333, 8.027] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.343 ops/ms
# Warmup Iteration   2: 6.730 ops/ms
# Warmup Iteration   3: 7.005 ops/ms
Iteration   1: 7.279 ops/ms
Iteration   2: 7.248 ops/ms
Iteration   3: 7.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.254 ±(99.9%) 0.405 ops/ms [Average]
  (min, avg, max) = (7.236, 7.254, 7.279), stdev = 0.022
  CI (99.9%): [6.850, 7.659] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.840 ops/ms
# Warmup Iteration   2: 6.315 ops/ms
# Warmup Iteration   3: 6.799 ops/ms
Iteration   1: 6.715 ops/ms
Iteration   2: 7.015 ops/ms
Iteration   3: 6.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.900 ±(99.9%) 2.948 ops/ms [Average]
  (min, avg, max) = (6.715, 6.900, 7.015), stdev = 0.162
  CI (99.9%): [3.952, 9.849] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.417 ops/ms
# Warmup Iteration   2: 4.605 ops/ms
# Warmup Iteration   3: 5.287 ops/ms
Iteration   1: 5.306 ops/ms
Iteration   2: 5.408 ops/ms
Iteration   3: 5.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.361 ±(99.9%) 0.942 ops/ms [Average]
  (min, avg, max) = (5.306, 5.361, 5.408), stdev = 0.052
  CI (99.9%): [4.419, 6.303] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.266 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.899 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.789 ±(99.9%) 0.005 ms/op
Iteration   1: 4.787 ±(99.9%) 0.005 ms/op
Iteration   2: 4.615 ±(99.9%) 0.006 ms/op
Iteration   3: 4.648 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.683 ±(99.9%) 1.661 ms/op [Average]
  (min, avg, max) = (4.615, 4.683, 4.787), stdev = 0.091
  CI (99.9%): [3.022, 6.344] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.978 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.770 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.612 ±(99.9%) 0.015 ms/op
Iteration   1: 4.415 ±(99.9%) 0.006 ms/op
Iteration   2: 4.396 ±(99.9%) 0.004 ms/op
Iteration   3: 4.367 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.393 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (4.367, 4.393, 4.415), stdev = 0.024
  CI (99.9%): [3.953, 4.832] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.755 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.026 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.782 ±(99.9%) 0.006 ms/op
Iteration   1: 4.565 ±(99.9%) 0.004 ms/op
Iteration   2: 4.679 ±(99.9%) 0.007 ms/op
Iteration   3: 4.552 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.599 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (4.552, 4.599, 4.679), stdev = 0.070
  CI (99.9%): [3.316, 5.881] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.818 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.375 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.873 ±(99.9%) 0.024 ms/op
Iteration   1: 5.809 ±(99.9%) 0.018 ms/op
Iteration   2: 5.742 ±(99.9%) 0.014 ms/op
Iteration   3: 5.790 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.781 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (5.742, 5.781, 5.809), stdev = 0.035
  CI (99.9%): [5.151, 6.410] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.366 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.042 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.684 ±(99.9%) 0.014 ms/op
Iteration   1: 4.555 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.126 ms/op
                 createUser·p0.999:  16.643 ms/op
                 createUser·p0.9999: 23.822 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 4.669 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   5.759 ms/op
                 createUser·p0.95:   6.218 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  14.696 ms/op
                 createUser·p0.9999: 24.979 ms/op
                 createUser·p1.00:   31.425 ms/op

Iteration   3: 4.577 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  20.253 ms/op
                 createUser·p0.9999: 28.706 ms/op
                 createUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 208634
  mean =      4.600 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1851 
    [ 2.500,  5.000) = 150210 
    [ 5.000,  7.500) = 54439 
    [ 7.500, 10.000) = 1520 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     16.204 ms/op
     p(99.9900) =     25.039 ms/op
     p(99.9990) =     31.154 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.447 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.687 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.510 ±(99.9%) 0.013 ms/op
Iteration   1: 4.500 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   4.366 ms/op
                 existUser·p0.90:   5.612 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   7.717 ms/op
                 existUser·p0.999:  15.366 ms/op
                 existUser·p0.9999: 17.519 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   2: 4.291 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.300 ms/op
                 existUser·p0.95:   5.693 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  10.391 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   3: 4.287 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  11.011 ms/op
                 existUser·p0.9999: 36.836 ms/op
                 existUser·p1.00:   42.861 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220396
  mean =      4.357 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 179232 
    [ 5.000, 10.000) = 40778 
    [10.000, 15.000) = 235 
    [15.000, 20.000) = 118 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     12.816 ms/op
     p(99.9900) =     36.173 ms/op
     p(99.9990) =     37.263 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.141 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.988 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.709 ±(99.9%) 0.013 ms/op
Iteration   1: 4.535 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  14.729 ms/op
                 getUser·p0.9999: 18.507 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   2: 4.697 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   6.210 ms/op
                 getUser·p0.99:   7.712 ms/op
                 getUser·p0.999:  13.532 ms/op
                 getUser·p0.9999: 23.272 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 4.560 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  14.988 ms/op
                 getUser·p0.9999: 25.821 ms/op
                 getUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 208800
  mean =      4.596 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2611 
    [ 2.500,  5.000) = 149739 
    [ 5.000,  7.500) = 54151 
    [ 7.500, 10.000) = 1767 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     14.247 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.859 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 6.313 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 6.087 ±(99.9%) 0.025 ms/op
Iteration   1: 6.066 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   8.167 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   12.550 ms/op
                 listUser·p0.999:  20.194 ms/op
                 listUser·p0.9999: 29.557 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   2: 5.944 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.575 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   12.313 ms/op
                 listUser·p0.999:  21.506 ms/op
                 listUser·p0.9999: 34.290 ms/op
                 listUser·p1.00:   34.865 ms/op

Iteration   3: 5.984 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.600 ms/op
                 listUser·p0.999:  23.596 ms/op
                 listUser·p0.9999: 30.394 ms/op
                 listUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160020
  mean =      5.998 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 144 
    [ 2.500,  5.000) = 39226 
    [ 5.000,  7.500) = 99853 
    [ 7.500, 10.000) = 15952 
    [10.000, 12.500) = 3427 
    [12.500, 15.000) = 740 
    [15.000, 17.500) = 258 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      5.636 ms/op
     p(90.0000) =      7.979 ms/op
     p(95.0000) =      9.175 ms/op
     p(99.0000) =     12.157 ms/op
     p(99.9000) =     22.216 ms/op
     p(99.9900) =     32.932 ms/op
     p(99.9990) =     34.747 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.680 ± 1.347  ops/ms
ClientGrpc.existUser                       thrpt       3   7.254 ± 0.405  ops/ms
ClientGrpc.getUser                         thrpt       3   6.900 ± 2.948  ops/ms
ClientGrpc.listUser                        thrpt       3   5.361 ± 0.942  ops/ms
ClientGrpc.createUser                       avgt       3   4.683 ± 1.661   ms/op
ClientGrpc.existUser                        avgt       3   4.393 ± 0.440   ms/op
ClientGrpc.getUser                          avgt       3   4.599 ± 1.282   ms/op
ClientGrpc.listUser                         avgt       3   5.781 ± 0.630   ms/op
ClientGrpc.createUser                     sample  208634   4.600 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.811           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.062           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.528           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.204           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.039           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.425           ms/op
ClientGrpc.existUser                      sample  220396   4.357 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.705           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.415           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.849           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.266           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.816           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          36.173           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          42.861           ms/op
ClientGrpc.getUser                        sample  208800   4.596 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.824           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.111           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.627           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.247           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.265           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.214           ms/op
ClientGrpc.listUser                       sample  160020   5.998 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.575           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.979           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.175           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.157           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.216           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.932           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.865           ms/op
