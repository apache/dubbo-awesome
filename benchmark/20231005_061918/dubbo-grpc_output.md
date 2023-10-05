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
# Warmup Iteration   1: 3.879 ops/ms
# Warmup Iteration   2: 8.664 ops/ms
# Warmup Iteration   3: 9.582 ops/ms
Iteration   1: 9.841 ops/ms
Iteration   2: 10.021 ops/ms
Iteration   3: 10.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.060 ±(99.9%) 4.392 ops/ms [Average]
  (min, avg, max) = (9.841, 10.060, 10.318), stdev = 0.241
  CI (99.9%): [5.668, 14.452] (assumes normal distribution)


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
# Warmup Iteration   1: 7.416 ops/ms
# Warmup Iteration   2: 10.090 ops/ms
# Warmup Iteration   3: 10.519 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.692 ops/ms
Iteration   3: 10.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.576 ±(99.9%) 3.010 ops/ms [Average]
  (min, avg, max) = (10.387, 10.576, 10.692), stdev = 0.165
  CI (99.9%): [7.567, 13.586] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.245 ops/ms
# Warmup Iteration   2: 9.627 ops/ms
# Warmup Iteration   3: 10.021 ops/ms
Iteration   1: 10.090 ops/ms
Iteration   2: 10.232 ops/ms
Iteration   3: 10.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.177 ±(99.9%) 1.391 ops/ms [Average]
  (min, avg, max) = (10.090, 10.177, 10.232), stdev = 0.076
  CI (99.9%): [8.785, 11.568] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.983 ops/ms
# Warmup Iteration   2: 7.448 ops/ms
# Warmup Iteration   3: 7.733 ops/ms
Iteration   1: 7.789 ops/ms
Iteration   2: 7.815 ops/ms
Iteration   3: 7.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.820 ±(99.9%) 0.611 ops/ms [Average]
  (min, avg, max) = (7.789, 7.820, 7.856), stdev = 0.034
  CI (99.9%): [7.209, 8.432] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.481 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.002 ms/op
Iteration   1: 3.209 ±(99.9%) 0.005 ms/op
Iteration   2: 3.129 ±(99.9%) 0.004 ms/op
Iteration   3: 3.212 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.183 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (3.129, 3.183, 3.212), stdev = 0.047
  CI (99.9%): [2.318, 4.048] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.163 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.003 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.001 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (2.983, 3.001, 3.012), stdev = 0.016
  CI (99.9%): [2.717, 3.284] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.589 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.003 ms/op
Iteration   1: 3.155 ±(99.9%) 0.003 ms/op
Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
Iteration   3: 3.179 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.159 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (3.143, 3.159, 3.179), stdev = 0.018
  CI (99.9%): [2.822, 3.496] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.462 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.012 ms/op
Iteration   1: 4.035 ±(99.9%) 0.012 ms/op
Iteration   2: 4.126 ±(99.9%) 0.019 ms/op
Iteration   3: 4.083 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.081 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (4.035, 4.081, 4.126), stdev = 0.045
  CI (99.9%): [3.252, 4.910] (assumes normal distribution)


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
# Warmup Iteration   1: 4.548 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
Iteration   1: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  11.141 ms/op
                 createUser·p0.9999: 22.853 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.750 ms/op
                 createUser·p0.999:  8.788 ms/op
                 createUser·p0.9999: 22.938 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.951 ms/op
                 createUser·p0.999:  16.261 ms/op
                 createUser·p0.9999: 22.345 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305313
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10245 
    [ 2.500,  5.000) = 292472 
    [ 5.000,  7.500) = 1973 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =     12.090 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     24.279 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 4.357 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  10.457 ms/op
                 existUser·p0.9999: 16.392 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  11.637 ms/op
                 existUser·p0.9999: 15.460 ms/op
                 existUser·p1.00:   16.531 ms/op

Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  8.593 ms/op
                 existUser·p0.9999: 16.105 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315506
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 944 
    [ 1.250,  2.500) = 21797 
    [ 2.500,  3.750) = 274634 
    [ 3.750,  5.000) = 15922 
    [ 5.000,  6.250) = 1009 
    [ 6.250,  7.500) = 577 
    [ 7.500,  8.750) = 156 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 77 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =     10.486 ms/op
     p(99.9900) =     16.073 ms/op
     p(99.9990) =     16.739 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.467 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.006 ms/op
Iteration   1: 3.173 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.733 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.724 ms/op
                 getUser·p0.999:  7.041 ms/op
                 getUser·p0.9999: 12.763 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.323 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   5.054 ms/op
                 getUser·p0.999:  8.140 ms/op
                 getUser·p0.9999: 13.987 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 16.963 ms/op
                 getUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305561
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 582 
    [ 1.250,  2.500) = 15609 
    [ 2.500,  3.750) = 261294 
    [ 3.750,  5.000) = 24951 
    [ 5.000,  6.250) = 2122 
    [ 6.250,  7.500) = 588 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.323 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =      8.237 ms/op
     p(99.9900) =     15.292 ms/op
     p(99.9990) =     17.099 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 5.921 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.012 ms/op
Iteration   1: 4.128 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.769 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  14.918 ms/op
                 listUser·p0.9999: 18.326 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 4.109 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.764 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  15.206 ms/op
                 listUser·p0.9999: 20.684 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   3: 4.131 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.321 ms/op
                 listUser·p0.999:  16.078 ms/op
                 listUser·p0.9999: 19.166 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232893
  mean =      4.123 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1768 
    [ 2.500,  5.000) = 207742 
    [ 5.000,  7.500) = 21163 
    [ 7.500, 10.000) = 1653 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     19.586 ms/op
     p(99.9990) =     26.281 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.060 ± 4.392  ops/ms
ClientGrpc.existUser                       thrpt       3  10.576 ± 3.010  ops/ms
ClientGrpc.getUser                         thrpt       3  10.177 ± 1.391  ops/ms
ClientGrpc.listUser                        thrpt       3   7.820 ± 0.611  ops/ms
ClientGrpc.createUser                       avgt       3   3.183 ± 0.865   ms/op
ClientGrpc.existUser                        avgt       3   3.001 ± 0.283   ms/op
ClientGrpc.getUser                          avgt       3   3.159 ± 0.337   ms/op
ClientGrpc.listUser                         avgt       3   4.081 ± 0.829   ms/op
ClientGrpc.createUser                     sample  305313   3.143 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.764           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.090           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.675           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.231           ms/op
ClientGrpc.existUser                      sample  315506   3.043 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.592           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.486           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.073           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.908           ms/op
ClientGrpc.getUser                        sample  305561   3.142 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.323           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.014           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.237           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.292           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.269           ms/op
ClientGrpc.listUser                       sample  232893   4.123 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.769           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.961           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.455           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.385           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.586           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.608           ms/op
