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
# Warmup Iteration   1: 3.340 ops/ms
# Warmup Iteration   2: 6.736 ops/ms
# Warmup Iteration   3: 8.133 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 8.772 ops/ms
Iteration   3: 8.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.613 ±(99.9%) 5.141 ops/ms [Average]
  (min, avg, max) = (8.287, 8.613, 8.779), stdev = 0.282
  CI (99.9%): [3.471, 13.754] (assumes normal distribution)


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
# Warmup Iteration   1: 5.755 ops/ms
# Warmup Iteration   2: 8.437 ops/ms
# Warmup Iteration   3: 9.136 ops/ms
Iteration   1: 9.354 ops/ms
Iteration   2: 9.332 ops/ms
Iteration   3: 9.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.312 ±(99.9%) 0.978 ops/ms [Average]
  (min, avg, max) = (9.252, 9.312, 9.354), stdev = 0.054
  CI (99.9%): [8.335, 10.290] (assumes normal distribution)


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
# Warmup Iteration   1: 5.281 ops/ms
# Warmup Iteration   2: 8.211 ops/ms
# Warmup Iteration   3: 8.558 ops/ms
Iteration   1: 8.734 ops/ms
Iteration   2: 8.612 ops/ms
Iteration   3: 8.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.749 ±(99.9%) 2.643 ops/ms [Average]
  (min, avg, max) = (8.612, 8.749, 8.900), stdev = 0.145
  CI (99.9%): [6.106, 11.391] (assumes normal distribution)


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
# Warmup Iteration   1: 4.652 ops/ms
# Warmup Iteration   2: 6.162 ops/ms
# Warmup Iteration   3: 6.484 ops/ms
Iteration   1: 6.538 ops/ms
Iteration   2: 6.587 ops/ms
Iteration   3: 6.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.612 ±(99.9%) 1.646 ops/ms [Average]
  (min, avg, max) = (6.538, 6.612, 6.713), stdev = 0.090
  CI (99.9%): [4.967, 8.258] (assumes normal distribution)


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
# Warmup Iteration   1: 5.229 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.005 ms/op
Iteration   1: 3.750 ±(99.9%) 0.004 ms/op
Iteration   2: 3.590 ±(99.9%) 0.005 ms/op
Iteration   3: 3.601 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.647 ±(99.9%) 1.629 ms/op [Average]
  (min, avg, max) = (3.590, 3.647, 3.750), stdev = 0.089
  CI (99.9%): [2.017, 5.276] (assumes normal distribution)


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
# Warmup Iteration   1: 5.064 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.002 ms/op
Iteration   1: 3.398 ±(99.9%) 0.003 ms/op
Iteration   2: 3.381 ±(99.9%) 0.004 ms/op
Iteration   3: 3.354 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.378 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (3.354, 3.378, 3.398), stdev = 0.022
  CI (99.9%): [2.973, 3.783] (assumes normal distribution)


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
# Warmup Iteration   1: 4.938 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.003 ms/op
Iteration   1: 3.503 ±(99.9%) 0.005 ms/op
Iteration   2: 3.495 ±(99.9%) 0.005 ms/op
Iteration   3: 3.550 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.516 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.495, 3.516, 3.550), stdev = 0.030
  CI (99.9%): [2.977, 4.055] (assumes normal distribution)


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
# Warmup Iteration   1: 6.707 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.765 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.595 ±(99.9%) 0.015 ms/op
Iteration   1: 4.666 ±(99.9%) 0.025 ms/op
Iteration   2: 4.651 ±(99.9%) 0.022 ms/op
Iteration   3: 4.567 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.628 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (4.567, 4.628, 4.666), stdev = 0.053
  CI (99.9%): [3.660, 5.596] (assumes normal distribution)


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
# Warmup Iteration   1: 5.544 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.011 ms/op
Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  11.054 ms/op
                 createUser·p0.9999: 19.886 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   2: 3.852 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.389 ms/op
                 createUser·p0.999:  13.565 ms/op
                 createUser·p0.9999: 22.099 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   3: 3.680 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  13.517 ms/op
                 createUser·p0.9999: 26.132 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255312
  mean =      3.760 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5851 
    [ 2.500,  5.000) = 239042 
    [ 5.000,  7.500) = 8651 
    [ 7.500, 10.000) = 1280 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     24.493 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 5.049 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.009 ms/op
Iteration   1: 3.491 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.338 ms/op
                 existUser·p0.999:  12.542 ms/op
                 existUser·p0.9999: 19.033 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 3.346 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  9.033 ms/op
                 existUser·p0.9999: 14.957 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  13.143 ms/op
                 existUser·p0.9999: 35.324 ms/op
                 existUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280229
  mean =      3.427 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9096 
    [ 2.500,  5.000) = 267494 
    [ 5.000,  7.500) = 2794 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     11.711 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     35.599 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 5.161 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.008 ms/op
Iteration   1: 3.519 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  8.487 ms/op
                 getUser·p0.9999: 13.498 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   2: 3.551 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  8.683 ms/op
                 getUser·p0.9999: 15.663 ms/op
                 getUser·p1.00:   16.269 ms/op

Iteration   3: 3.619 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  10.377 ms/op
                 getUser·p0.9999: 29.048 ms/op
                 getUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 269310
  mean =      3.563 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8059 
    [ 2.500,  5.000) = 256405 
    [ 5.000,  7.500) = 4127 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     28.039 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 7.176 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.060 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.014 ms/op
Iteration   1: 4.722 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.767 ms/op
                 listUser·p0.95:   6.805 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 4.740 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.814 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 4.825 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  18.012 ms/op
                 listUser·p0.9999: 34.889 ms/op
                 listUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201452
  mean =      4.762 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 495 
    [ 2.500,  5.000) = 154437 
    [ 5.000,  7.500) = 40801 
    [ 7.500, 10.000) = 4838 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.841 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     16.467 ms/op
     p(99.9900) =     33.732 ms/op
     p(99.9990) =     35.322 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.613 ± 5.141  ops/ms
ClientGrpc.existUser                       thrpt       3   9.312 ± 0.978  ops/ms
ClientGrpc.getUser                         thrpt       3   8.749 ± 2.643  ops/ms
ClientGrpc.listUser                        thrpt       3   6.612 ± 1.646  ops/ms
ClientGrpc.createUser                       avgt       3   3.647 ± 1.629   ms/op
ClientGrpc.existUser                        avgt       3   3.378 ± 0.405   ms/op
ClientGrpc.getUser                          avgt       3   3.516 ± 0.539   ms/op
ClientGrpc.listUser                         avgt       3   4.628 ± 0.968   ms/op
ClientGrpc.createUser                     sample  255312   3.760 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.816           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.726           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.960           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.493           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.296           ms/op
ClientGrpc.existUser                      sample  280229   3.427 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.903           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.965           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.251           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.711           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.260           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.652           ms/op
ClientGrpc.getUser                        sample  269310   3.563 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.858           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.273           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.039           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.393           ms/op
ClientGrpc.listUser                       sample  201452   4.762 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.762           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.467           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.732           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.324           ms/op
