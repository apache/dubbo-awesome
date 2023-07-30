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
# Warmup Iteration   1: 2.617 ops/ms
# Warmup Iteration   2: 6.380 ops/ms
# Warmup Iteration   3: 8.146 ops/ms
Iteration   1: 8.429 ops/ms
Iteration   2: 8.705 ops/ms
Iteration   3: 8.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.583 ±(99.9%) 2.569 ops/ms [Average]
  (min, avg, max) = (8.429, 8.583, 8.705), stdev = 0.141
  CI (99.9%): [6.014, 11.152] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.658 ops/ms
# Warmup Iteration   2: 8.924 ops/ms
# Warmup Iteration   3: 8.727 ops/ms
Iteration   1: 9.292 ops/ms
Iteration   2: 9.176 ops/ms
Iteration   3: 9.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.249 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (9.176, 9.249, 9.292), stdev = 0.063
  CI (99.9%): [8.094, 10.405] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.491 ops/ms
# Warmup Iteration   2: 8.072 ops/ms
# Warmup Iteration   3: 8.755 ops/ms
Iteration   1: 8.919 ops/ms
Iteration   2: 8.799 ops/ms
Iteration   3: 8.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.870 ±(99.9%) 1.150 ops/ms [Average]
  (min, avg, max) = (8.799, 8.870, 8.919), stdev = 0.063
  CI (99.9%): [7.720, 10.020] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ops/ms
# Warmup Iteration   2: 6.383 ops/ms
# Warmup Iteration   3: 6.709 ops/ms
Iteration   1: 6.681 ops/ms
Iteration   2: 6.615 ops/ms
Iteration   3: 6.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.631 ±(99.9%) 0.817 ops/ms [Average]
  (min, avg, max) = (6.596, 6.631, 6.681), stdev = 0.045
  CI (99.9%): [5.814, 7.448] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.187 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.021 ms/op
Iteration   1: 3.794 ±(99.9%) 0.003 ms/op
Iteration   2: 3.928 ±(99.9%) 0.003 ms/op
Iteration   3: 3.731 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.818 ±(99.9%) 1.832 ms/op [Average]
  (min, avg, max) = (3.731, 3.818, 3.928), stdev = 0.100
  CI (99.9%): [1.985, 5.650] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.761 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.004 ms/op
Iteration   1: 3.537 ±(99.9%) 0.003 ms/op
Iteration   2: 3.367 ±(99.9%) 0.003 ms/op
Iteration   3: 3.430 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.445 ±(99.9%) 1.567 ms/op [Average]
  (min, avg, max) = (3.367, 3.445, 3.537), stdev = 0.086
  CI (99.9%): [1.878, 5.012] (assumes normal distribution)


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
# Warmup Iteration   1: 5.831 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.004 ms/op
Iteration   1: 3.879 ±(99.9%) 0.002 ms/op
Iteration   2: 3.703 ±(99.9%) 0.001 ms/op
Iteration   3: 3.568 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.717 ±(99.9%) 2.851 ms/op [Average]
  (min, avg, max) = (3.568, 3.717, 3.879), stdev = 0.156
  CI (99.9%): [0.866, 6.567] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.278 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.857 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.785 ±(99.9%) 0.027 ms/op
Iteration   1: 4.489 ±(99.9%) 0.006 ms/op
Iteration   2: 4.627 ±(99.9%) 0.024 ms/op
Iteration   3: 4.888 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.668 ±(99.9%) 3.696 ms/op [Average]
  (min, avg, max) = (4.489, 4.668, 4.888), stdev = 0.203
  CI (99.9%): [0.972, 8.365] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.479 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
Iteration   1: 3.695 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.651 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  10.552 ms/op
                 createUser·p0.9999: 15.554 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   2: 3.657 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  12.850 ms/op
                 createUser·p0.9999: 22.210 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   3: 3.627 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  9.484 ms/op
                 createUser·p0.9999: 17.451 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262161
  mean =      3.659 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8179 
    [ 2.500,  5.000) = 239450 
    [ 5.000,  7.500) = 13269 
    [ 7.500, 10.000) = 972 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     10.876 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     22.667 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.883 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.010 ms/op
Iteration   1: 3.394 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  11.262 ms/op
                 existUser·p0.9999: 17.803 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   2: 3.395 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  8.615 ms/op
                 existUser·p0.9999: 14.020 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 3.353 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.114 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 23.379 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283776
  mean =      3.381 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23862 
    [ 2.500,  5.000) = 249731 
    [ 5.000,  7.500) = 9135 
    [ 7.500, 10.000) = 784 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     22.794 ms/op
     p(99.9990) =     23.756 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 5.453 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.009 ms/op
Iteration   1: 3.760 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  12.724 ms/op
                 getUser·p0.9999: 16.007 ms/op
                 getUser·p1.00:   16.024 ms/op

Iteration   2: 3.586 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 17.239 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   3: 3.589 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  9.306 ms/op
                 getUser·p0.9999: 21.794 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263409
  mean =      3.643 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7949 
    [ 2.500,  5.000) = 239829 
    [ 5.000,  7.500) = 14391 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     19.982 ms/op
     p(99.9990) =     22.113 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 7.699 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.108 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.813 ±(99.9%) 0.019 ms/op
Iteration   1: 4.905 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   7.643 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 22.343 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 4.805 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  17.051 ms/op
                 listUser·p0.9999: 21.136 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 4.709 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   6.472 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  21.534 ms/op
                 listUser·p0.9999: 29.217 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199748
  mean =      4.805 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1606 
    [ 2.500,  5.000) = 134535 
    [ 5.000,  7.500) = 53479 
    [ 7.500, 10.000) = 8724 
    [10.000, 12.500) = 913 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.512 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     16.601 ms/op
     p(99.9900) =     26.150 ms/op
     p(99.9990) =     30.311 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.583 ± 2.569  ops/ms
ClientGrpc.existUser                       thrpt       3   9.249 ± 1.155  ops/ms
ClientGrpc.getUser                         thrpt       3   8.870 ± 1.150  ops/ms
ClientGrpc.listUser                        thrpt       3   6.631 ± 0.817  ops/ms
ClientGrpc.createUser                       avgt       3   3.818 ± 1.832   ms/op
ClientGrpc.existUser                        avgt       3   3.445 ± 1.567   ms/op
ClientGrpc.getUser                          avgt       3   3.717 ± 2.851   ms/op
ClientGrpc.listUser                         avgt       3   4.668 ± 3.696   ms/op
ClientGrpc.createUser                     sample  262161   3.659 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.811           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.529           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.876           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.562           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.790           ms/op
ClientGrpc.existUser                      sample  283776   3.381 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.819           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.447           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.355           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.794           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.740           ms/op
ClientGrpc.getUser                        sample  263409   3.643 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.815           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.562           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.289           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.982           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.315           ms/op
ClientGrpc.listUser                       sample  199748   4.805 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.075           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.512           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.519           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.601           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.150           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.507           ms/op
