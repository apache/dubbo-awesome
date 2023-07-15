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
# Warmup Iteration   1: 2.065 ops/ms
# Warmup Iteration   2: 4.383 ops/ms
# Warmup Iteration   3: 6.584 ops/ms
Iteration   1: 6.978 ops/ms
Iteration   2: 7.074 ops/ms
Iteration   3: 7.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.076 ±(99.9%) 1.810 ops/ms [Average]
  (min, avg, max) = (6.978, 7.076, 7.177), stdev = 0.099
  CI (99.9%): [5.267, 8.886] (assumes normal distribution)


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
# Warmup Iteration   1: 4.549 ops/ms
# Warmup Iteration   2: 7.267 ops/ms
# Warmup Iteration   3: 7.734 ops/ms
Iteration   1: 8.003 ops/ms
Iteration   2: 7.953 ops/ms
Iteration   3: 8.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.024 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (7.953, 8.024, 8.115), stdev = 0.083
  CI (99.9%): [6.513, 9.534] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ops/ms
# Warmup Iteration   2: 6.451 ops/ms
# Warmup Iteration   3: 7.062 ops/ms
Iteration   1: 7.187 ops/ms
Iteration   2: 7.383 ops/ms
Iteration   3: 7.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.270 ±(99.9%) 1.847 ops/ms [Average]
  (min, avg, max) = (7.187, 7.270, 7.383), stdev = 0.101
  CI (99.9%): [5.424, 9.117] (assumes normal distribution)


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
# Warmup Iteration   1: 3.415 ops/ms
# Warmup Iteration   2: 4.861 ops/ms
# Warmup Iteration   3: 5.279 ops/ms
Iteration   1: 5.522 ops/ms
Iteration   2: 5.564 ops/ms
Iteration   3: 5.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.555 ±(99.9%) 0.550 ops/ms [Average]
  (min, avg, max) = (5.522, 5.555, 5.580), stdev = 0.030
  CI (99.9%): [5.005, 6.105] (assumes normal distribution)


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
# Warmup Iteration   1: 7.212 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.826 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.005 ms/op
Iteration   1: 4.385 ±(99.9%) 0.003 ms/op
Iteration   2: 4.427 ±(99.9%) 0.004 ms/op
Iteration   3: 4.486 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.433 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (4.385, 4.433, 4.486), stdev = 0.051
  CI (99.9%): [3.500, 5.365] (assumes normal distribution)


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
# Warmup Iteration   1: 6.547 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.004 ms/op
Iteration   1: 4.125 ±(99.9%) 0.006 ms/op
Iteration   2: 4.104 ±(99.9%) 0.004 ms/op
Iteration   3: 4.039 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.089 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (4.039, 4.089, 4.125), stdev = 0.045
  CI (99.9%): [3.265, 4.914] (assumes normal distribution)


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
# Warmup Iteration   1: 6.842 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.539 ±(99.9%) 0.015 ms/op
Iteration   1: 4.436 ±(99.9%) 0.004 ms/op
Iteration   2: 4.320 ±(99.9%) 0.003 ms/op
Iteration   3: 4.327 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.361 ±(99.9%) 1.183 ms/op [Average]
  (min, avg, max) = (4.320, 4.361, 4.436), stdev = 0.065
  CI (99.9%): [3.178, 5.544] (assumes normal distribution)


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
# Warmup Iteration   1: 9.148 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 6.239 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.930 ±(99.9%) 0.020 ms/op
Iteration   1: 6.035 ±(99.9%) 0.017 ms/op
Iteration   2: 5.852 ±(99.9%) 0.017 ms/op
Iteration   3: 5.656 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.848 ±(99.9%) 3.458 ms/op [Average]
  (min, avg, max) = (5.656, 5.848, 6.035), stdev = 0.190
  CI (99.9%): [2.390, 9.306] (assumes normal distribution)


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
# Warmup Iteration   1: 7.354 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.855 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.554 ±(99.9%) 0.014 ms/op
Iteration   1: 4.481 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  13.303 ms/op
                 createUser·p0.9999: 16.036 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   2: 4.425 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 18.736 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 4.447 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   9.237 ms/op
                 createUser·p0.999:  17.438 ms/op
                 createUser·p0.9999: 24.531 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215547
  mean =      4.451 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3489 
    [ 2.500,  5.000) = 169699 
    [ 5.000,  7.500) = 38573 
    [ 7.500, 10.000) = 2588 
    [10.000, 12.500) = 783 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     14.474 ms/op
     p(99.9900) =     22.606 ms/op
     p(99.9990) =     24.818 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 6.116 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.666 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.013 ms/op
Iteration   1: 4.148 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.856 ms/op
                 existUser·p0.999:  11.450 ms/op
                 existUser·p0.9999: 18.926 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 4.171 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.578 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 29.524 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   3: 4.103 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  13.893 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231986
  mean =      4.141 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8283 
    [ 2.500,  5.000) = 196822 
    [ 5.000,  7.500) = 24110 
    [ 7.500, 10.000) = 2172 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      7.840 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     27.375 ms/op
     p(99.9990) =     29.819 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 7.123 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.818 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.485 ±(99.9%) 0.014 ms/op
Iteration   1: 4.481 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   9.044 ms/op
                 getUser·p0.999:  15.548 ms/op
                 getUser·p0.9999: 17.849 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   2: 4.438 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  12.857 ms/op
                 getUser·p0.9999: 29.045 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   3: 4.549 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.077 ms/op
                 getUser·p0.999:  12.811 ms/op
                 getUser·p0.9999: 20.217 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213855
  mean =      4.489 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5459 
    [ 2.500,  5.000) = 157389 
    [ 5.000,  7.500) = 47265 
    [ 7.500, 10.000) = 2793 
    [10.000, 12.500) = 658 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     13.912 ms/op
     p(99.9900) =     21.753 ms/op
     p(99.9990) =     29.417 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 9.447 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 6.452 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.898 ±(99.9%) 0.023 ms/op
Iteration   1: 5.956 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  18.392 ms/op
                 listUser·p0.9999: 27.999 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 6.006 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   5.628 ms/op
                 listUser·p0.90:   8.200 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  18.656 ms/op
                 listUser·p0.9999: 34.406 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   3: 6.085 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   8.348 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  31.043 ms/op
                 listUser·p0.9999: 39.680 ms/op
                 listUser·p1.00:   39.977 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 159692
  mean =      6.015 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 154 
    [ 2.500,  5.000) = 42581 
    [ 5.000,  7.500) = 93023 
    [ 7.500, 10.000) = 19050 
    [10.000, 12.500) = 3810 
    [12.500, 15.000) = 675 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      5.620 ms/op
     p(90.0000) =      8.126 ms/op
     p(95.0000) =      9.208 ms/op
     p(99.0000) =     11.715 ms/op
     p(99.9000) =     20.359 ms/op
     p(99.9900) =     39.324 ms/op
     p(99.9990) =     39.899 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.076 ± 1.810  ops/ms
ClientGrpc.existUser                       thrpt       3   8.024 ± 1.510  ops/ms
ClientGrpc.getUser                         thrpt       3   7.270 ± 1.847  ops/ms
ClientGrpc.listUser                        thrpt       3   5.555 ± 0.550  ops/ms
ClientGrpc.createUser                       avgt       3   4.433 ± 0.932   ms/op
ClientGrpc.existUser                        avgt       3   4.089 ± 0.824   ms/op
ClientGrpc.getUser                          avgt       3   4.361 ± 1.183   ms/op
ClientGrpc.listUser                         avgt       3   5.848 ± 3.458   ms/op
ClientGrpc.createUser                     sample  215547   4.451 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.057           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.472           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.972           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.815           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.474           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.606           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.723           ms/op
ClientGrpc.existUser                      sample  231986   4.141 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.665           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.095           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.571           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.840           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.895           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.375           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.950           ms/op
ClientGrpc.getUser                        sample  213855   4.489 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.017           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.585           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.912           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.753           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.458           ms/op
ClientGrpc.listUser                       sample  159692   6.015 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.262           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.208           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.715           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.359           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          39.324           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.977           ms/op
