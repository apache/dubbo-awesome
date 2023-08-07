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
# Warmup Iteration   1: 2.904 ops/ms
# Warmup Iteration   2: 7.043 ops/ms
# Warmup Iteration   3: 8.160 ops/ms
Iteration   1: 8.637 ops/ms
Iteration   2: 9.348 ops/ms
Iteration   3: 8.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.890 ±(99.9%) 7.248 ops/ms [Average]
  (min, avg, max) = (8.637, 8.890, 9.348), stdev = 0.397
  CI (99.9%): [1.642, 16.137] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.753 ops/ms
# Warmup Iteration   2: 7.913 ops/ms
# Warmup Iteration   3: 8.728 ops/ms
Iteration   1: 8.993 ops/ms
Iteration   2: 9.744 ops/ms
Iteration   3: 9.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.379 ±(99.9%) 6.852 ops/ms [Average]
  (min, avg, max) = (8.993, 9.379, 9.744), stdev = 0.376
  CI (99.9%): [2.526, 16.231] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.592 ops/ms
# Warmup Iteration   2: 7.993 ops/ms
# Warmup Iteration   3: 8.266 ops/ms
Iteration   1: 8.749 ops/ms
Iteration   2: 8.451 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.408 ±(99.9%) 6.650 ops/ms [Average]
  (min, avg, max) = (8.024, 8.408, 8.749), stdev = 0.365
  CI (99.9%): [1.757, 15.058] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.351 ops/ms
# Warmup Iteration   2: 6.243 ops/ms
# Warmup Iteration   3: 6.295 ops/ms
Iteration   1: 6.416 ops/ms
Iteration   2: 6.479 ops/ms
Iteration   3: 6.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.387 ±(99.9%) 2.000 ops/ms [Average]
  (min, avg, max) = (6.265, 6.387, 6.479), stdev = 0.110
  CI (99.9%): [4.386, 8.387] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.717 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.016 ms/op
Iteration   1: 3.935 ±(99.9%) 0.004 ms/op
Iteration   2: 3.763 ±(99.9%) 0.003 ms/op
Iteration   3: 3.780 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.826 ±(99.9%) 1.732 ms/op [Average]
  (min, avg, max) = (3.763, 3.826, 3.935), stdev = 0.095
  CI (99.9%): [2.094, 5.558] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.126 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.003 ms/op
Iteration   1: 3.729 ±(99.9%) 0.003 ms/op
Iteration   2: 3.629 ±(99.9%) 0.003 ms/op
Iteration   3: 3.671 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.677 ±(99.9%) 0.918 ms/op [Average]
  (min, avg, max) = (3.629, 3.677, 3.729), stdev = 0.050
  CI (99.9%): [2.759, 4.594] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.167 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.003 ms/op
Iteration   1: 3.843 ±(99.9%) 0.004 ms/op
Iteration   2: 3.807 ±(99.9%) 0.004 ms/op
Iteration   3: 3.693 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.781 ±(99.9%) 1.428 ms/op [Average]
  (min, avg, max) = (3.693, 3.781, 3.843), stdev = 0.078
  CI (99.9%): [2.353, 5.208] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.169 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.147 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.905 ±(99.9%) 0.010 ms/op
Iteration   1: 4.925 ±(99.9%) 0.015 ms/op
Iteration   2: 4.827 ±(99.9%) 0.015 ms/op
Iteration   3: 4.826 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.859 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (4.826, 4.859, 4.925), stdev = 0.057
  CI (99.9%): [3.817, 5.902] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.700 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.012 ms/op
Iteration   1: 3.823 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.742 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  12.222 ms/op
                 createUser·p0.9999: 27.817 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   3: 3.859 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  17.002 ms/op
                 createUser·p0.9999: 27.820 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252302
  mean =      3.807 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6166 
    [ 2.500,  5.000) = 234608 
    [ 5.000,  7.500) = 10113 
    [ 7.500, 10.000) = 969 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     11.995 ms/op
     p(99.9900) =     27.747 ms/op
     p(99.9990) =     28.098 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.399 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.008 ms/op
Iteration   1: 3.421 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.334 ms/op
                 existUser·p0.999:  13.173 ms/op
                 existUser·p0.9999: 14.974 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   2: 3.422 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  11.462 ms/op
                 existUser·p0.9999: 16.808 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   3: 3.461 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 21.185 ms/op
                 existUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279335
  mean =      3.435 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11871 
    [ 2.500,  5.000) = 261019 
    [ 5.000,  7.500) = 5287 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     20.255 ms/op
     p(99.9990) =     22.480 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.361 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.010 ms/op
Iteration   1: 3.601 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  11.995 ms/op
                 getUser·p0.9999: 15.111 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 3.484 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  9.997 ms/op
                 getUser·p0.9999: 16.237 ms/op
                 getUser·p1.00:   16.302 ms/op

Iteration   3: 3.620 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  11.523 ms/op
                 getUser·p0.9999: 19.999 ms/op
                 getUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 269108
  mean =      3.568 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8529 
    [ 2.500,  5.000) = 253671 
    [ 5.000,  7.500) = 5746 
    [ 7.500, 10.000) = 779 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     11.025 ms/op
     p(99.9900) =     19.014 ms/op
     p(99.9990) =     20.369 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 7.258 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.263 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.840 ±(99.9%) 0.016 ms/op
Iteration   1: 4.813 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  15.876 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 4.786 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   9.193 ms/op
                 listUser·p0.999:  16.699 ms/op
                 listUser·p0.9999: 20.261 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.746 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   6.152 ms/op
                 listUser·p0.95:   7.043 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 35.062 ms/op
                 listUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200626
  mean =      4.782 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 479 
    [ 2.500,  5.000) = 146503 
    [ 5.000,  7.500) = 46530 
    [ 7.500, 10.000) = 5761 
    [10.000, 12.500) = 807 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      7.094 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.890 ± 7.248  ops/ms
ClientGrpc.existUser                       thrpt       3   9.379 ± 6.852  ops/ms
ClientGrpc.getUser                         thrpt       3   8.408 ± 6.650  ops/ms
ClientGrpc.listUser                        thrpt       3   6.387 ± 2.000  ops/ms
ClientGrpc.createUser                       avgt       3   3.826 ± 1.732   ms/op
ClientGrpc.existUser                        avgt       3   3.677 ± 0.918   ms/op
ClientGrpc.getUser                          avgt       3   3.781 ± 1.428   ms/op
ClientGrpc.listUser                         avgt       3   4.859 ± 1.042   ms/op
ClientGrpc.createUser                     sample  252302   3.807 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.659           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.956           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.439           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.995           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.747           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.213           ms/op
ClientGrpc.existUser                      sample  279335   3.435 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.812           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.857           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.878           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.255           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.560           ms/op
ClientGrpc.getUser                        sample  269108   3.568 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.732           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.054           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.025           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.014           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.644           ms/op
ClientGrpc.listUser                       sample  200626   4.782 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.116           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.144           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.210           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.258           ms/op
