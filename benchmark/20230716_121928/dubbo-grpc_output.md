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
# Warmup Iteration   1: 4.068 ops/ms
# Warmup Iteration   2: 8.740 ops/ms
# Warmup Iteration   3: 9.938 ops/ms
Iteration   1: 10.127 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 10.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.169 ±(99.9%) 1.940 ops/ms [Average]
  (min, avg, max) = (10.090, 10.169, 10.290), stdev = 0.106
  CI (99.9%): [8.229, 12.109] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.573 ops/ms
# Warmup Iteration   2: 10.334 ops/ms
# Warmup Iteration   3: 10.668 ops/ms
Iteration   1: 10.806 ops/ms
Iteration   2: 10.766 ops/ms
Iteration   3: 10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.738 ±(99.9%) 1.554 ops/ms [Average]
  (min, avg, max) = (10.643, 10.738, 10.806), stdev = 0.085
  CI (99.9%): [9.185, 12.292] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.532 ops/ms
# Warmup Iteration   2: 9.832 ops/ms
# Warmup Iteration   3: 10.226 ops/ms
Iteration   1: 10.328 ops/ms
Iteration   2: 10.378 ops/ms
Iteration   3: 10.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.316 ±(99.9%) 1.270 ops/ms [Average]
  (min, avg, max) = (10.241, 10.316, 10.378), stdev = 0.070
  CI (99.9%): [9.046, 11.586] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.081 ops/ms
# Warmup Iteration   2: 7.569 ops/ms
# Warmup Iteration   3: 8.105 ops/ms
Iteration   1: 7.792 ops/ms
Iteration   2: 7.636 ops/ms
Iteration   3: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.746 ±(99.9%) 1.744 ops/ms [Average]
  (min, avg, max) = (7.636, 7.746, 7.810), stdev = 0.096
  CI (99.9%): [6.002, 9.490] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.609 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.110 ±(99.9%) 0.003 ms/op
Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
Iteration   3: 3.152 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.121 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (3.101, 3.121, 3.152), stdev = 0.027
  CI (99.9%): [2.628, 3.615] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.003 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.163 ±(99.9%) 0.003 ms/op
Iteration   3: 3.057 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.079 ±(99.9%) 1.374 ms/op [Average]
  (min, avg, max) = (3.017, 3.079, 3.163), stdev = 0.075
  CI (99.9%): [1.705, 4.453] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.004 ms/op
Iteration   1: 3.111 ±(99.9%) 0.005 ms/op
Iteration   2: 3.144 ±(99.9%) 0.005 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.119 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (3.102, 3.119, 3.144), stdev = 0.022
  CI (99.9%): [2.720, 3.519] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.928 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.013 ms/op
Iteration   1: 4.103 ±(99.9%) 0.010 ms/op
Iteration   2: 4.181 ±(99.9%) 0.028 ms/op
Iteration   3: 4.130 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.138 ±(99.9%) 0.724 ms/op [Average]
  (min, avg, max) = (4.103, 4.138, 4.181), stdev = 0.040
  CI (99.9%): [3.414, 4.861] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  8.394 ms/op
                 createUser·p0.9999: 13.737 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 3.077 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.183 ms/op
                 createUser·p0.9999: 16.076 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  10.486 ms/op
                 createUser·p0.9999: 18.537 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309639
  mean =      3.101 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12961 
    [ 2.500,  5.000) = 294748 
    [ 5.000,  7.500) = 1575 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     19.945 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.412 ms/op
                 existUser·p0.9999: 16.376 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 2.990 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.357 ms/op
                 existUser·p0.9999: 15.668 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 17.499 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319186
  mean =      3.008 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1084 
    [ 1.250,  2.500) = 19107 
    [ 2.500,  3.750) = 283642 
    [ 3.750,  5.000) = 13502 
    [ 5.000,  6.250) = 1037 
    [ 6.250,  7.500) = 444 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.266 ms/op
     p(99.9900) =     16.272 ms/op
     p(99.9990) =     17.846 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.558 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 14.809 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   2: 3.172 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  8.070 ms/op
                 getUser·p0.9999: 14.990 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  10.937 ms/op
                 getUser·p0.9999: 20.021 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302832
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12095 
    [ 2.500,  5.000) = 288287 
    [ 5.000,  7.500) = 1985 
    [ 7.500, 10.000) = 218 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     19.183 ms/op
     p(99.9990) =     20.347 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.193 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.012 ms/op
Iteration   1: 4.179 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.864 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  13.501 ms/op
                 listUser·p0.9999: 16.095 ms/op
                 listUser·p1.00:   16.351 ms/op

Iteration   2: 4.217 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 26.845 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   3: 4.218 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  18.323 ms/op
                 listUser·p0.9999: 23.890 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228338
  mean =      4.204 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1780 
    [ 2.500,  5.000) = 195544 
    [ 5.000,  7.500) = 29239 
    [ 7.500, 10.000) = 1324 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.330 ms/op
     p(99.9900) =     25.838 ms/op
     p(99.9990) =     27.728 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.169 ± 1.940  ops/ms
ClientGrpc.existUser                       thrpt       3  10.738 ± 1.554  ops/ms
ClientGrpc.getUser                         thrpt       3  10.316 ± 1.270  ops/ms
ClientGrpc.listUser                        thrpt       3   7.746 ± 1.744  ops/ms
ClientGrpc.createUser                       avgt       3   3.121 ± 0.494   ms/op
ClientGrpc.existUser                        avgt       3   3.079 ± 1.374   ms/op
ClientGrpc.getUser                          avgt       3   3.119 ± 0.399   ms/op
ClientGrpc.listUser                         avgt       3   4.138 ± 0.724   ms/op
ClientGrpc.createUser                     sample  309639   3.101 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.560           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.298           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.908           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.120           ms/op
ClientGrpc.existUser                      sample  319186   3.008 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.272           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  302832   3.169 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.696           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.208           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.183           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.513           ms/op
ClientGrpc.listUser                       sample  228338   4.204 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.026           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.330           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.838           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.049           ms/op
