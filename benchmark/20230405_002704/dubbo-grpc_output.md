# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
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
# Warmup Iteration   2: 5.504 ops/ms
# Warmup Iteration   3: 6.719 ops/ms
Iteration   1: 7.104 ops/ms
Iteration   2: 7.185 ops/ms
Iteration   3: 7.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.208 ±(99.9%) 2.144 ops/ms [Average]
  (min, avg, max) = (7.104, 7.208, 7.335), stdev = 0.118
  CI (99.9%): [5.064, 9.352] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.609 ops/ms
# Warmup Iteration   2: 6.968 ops/ms
# Warmup Iteration   3: 7.347 ops/ms
Iteration   1: 7.773 ops/ms
Iteration   2: 7.727 ops/ms
Iteration   3: 7.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.753 ±(99.9%) 0.435 ops/ms [Average]
  (min, avg, max) = (7.727, 7.753, 7.773), stdev = 0.024
  CI (99.9%): [7.318, 8.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.997 ops/ms
# Warmup Iteration   2: 6.772 ops/ms
# Warmup Iteration   3: 7.035 ops/ms
Iteration   1: 7.196 ops/ms
Iteration   2: 7.582 ops/ms
Iteration   3: 7.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.378 ±(99.9%) 3.541 ops/ms [Average]
  (min, avg, max) = (7.196, 7.378, 7.582), stdev = 0.194
  CI (99.9%): [3.837, 10.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.503 ops/ms
# Warmup Iteration   2: 5.311 ops/ms
# Warmup Iteration   3: 5.750 ops/ms
Iteration   1: 5.767 ops/ms
Iteration   2: 5.787 ops/ms
Iteration   3: 5.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.735 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (5.650, 5.735, 5.787), stdev = 0.074
  CI (99.9%): [4.384, 7.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.105 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.694 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.557 ±(99.9%) 0.007 ms/op
Iteration   1: 4.453 ±(99.9%) 0.003 ms/op
Iteration   2: 4.514 ±(99.9%) 0.004 ms/op
Iteration   3: 4.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.478 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (4.453, 4.478, 4.514), stdev = 0.032
  CI (99.9%): [3.888, 5.067] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.442 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.003 ms/op
Iteration   1: 4.156 ±(99.9%) 0.003 ms/op
Iteration   2: 4.133 ±(99.9%) 0.003 ms/op
Iteration   3: 4.190 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.160 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (4.133, 4.160, 4.190), stdev = 0.029
  CI (99.9%): [3.635, 4.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.595 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.427 ±(99.9%) 0.006 ms/op
Iteration   1: 4.467 ±(99.9%) 0.003 ms/op
Iteration   2: 4.504 ±(99.9%) 0.005 ms/op
Iteration   3: 4.327 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.433 ±(99.9%) 1.697 ms/op [Average]
  (min, avg, max) = (4.327, 4.433, 4.504), stdev = 0.093
  CI (99.9%): [2.736, 6.130] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.940 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.242 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.022 ±(99.9%) 0.017 ms/op
Iteration   1: 5.890 ±(99.9%) 0.026 ms/op
Iteration   2: 5.728 ±(99.9%) 0.022 ms/op
Iteration   3: 5.886 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.835 ±(99.9%) 1.681 ms/op [Average]
  (min, avg, max) = (5.728, 5.835, 5.890), stdev = 0.092
  CI (99.9%): [4.154, 7.515] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.003 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.835 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.488 ±(99.9%) 0.013 ms/op
Iteration   1: 4.489 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  12.940 ms/op
                 createUser·p0.9999: 28.979 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   2: 4.480 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   5.972 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  21.135 ms/op
                 createUser·p0.9999: 22.867 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 4.474 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   7.651 ms/op
                 createUser·p0.999:  15.435 ms/op
                 createUser·p0.9999: 27.258 ms/op
                 createUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214110
  mean =      4.481 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3049 
    [ 2.500,  5.000) = 162203 
    [ 5.000,  7.500) = 46606 
    [ 7.500, 10.000) = 1696 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     29.379 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.478 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.012 ms/op
Iteration   1: 4.109 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   4.010 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.250 ms/op
                 existUser·p0.999:  13.140 ms/op
                 existUser·p0.9999: 19.143 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 4.130 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.546 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  11.295 ms/op
                 existUser·p0.9999: 17.577 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   3: 4.114 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  10.519 ms/op
                 existUser·p0.9999: 30.254 ms/op
                 existUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 233194
  mean =      4.118 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5875 
    [ 2.500,  5.000) = 202914 
    [ 5.000,  7.500) = 22759 
    [ 7.500, 10.000) = 1246 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     12.177 ms/op
     p(99.9900) =     29.622 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.507 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.803 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.405 ±(99.9%) 0.013 ms/op
Iteration   1: 4.450 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 16.299 ms/op
                 getUser·p1.00:   16.515 ms/op

Iteration   2: 4.422 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  14.238 ms/op
                 getUser·p0.9999: 17.500 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   3: 4.484 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   4.391 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   7.186 ms/op
                 getUser·p0.999:  15.118 ms/op
                 getUser·p0.9999: 18.567 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215698
  mean =      4.452 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2644 
    [ 2.500,  3.750) = 41013 
    [ 3.750,  5.000) = 124815 
    [ 5.000,  6.250) = 40633 
    [ 6.250,  7.500) = 4369 
    [ 7.500,  8.750) = 1122 
    [ 8.750, 10.000) = 483 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 89 
    [15.000, 16.250) = 86 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     14.292 ms/op
     p(99.9900) =     17.774 ms/op
     p(99.9990) =     18.869 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.222 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 5.957 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.565 ±(99.9%) 0.021 ms/op
Iteration   1: 5.635 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.332 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  26.640 ms/op
                 listUser·p0.9999: 29.688 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   2: 5.555 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  29.866 ms/op
                 listUser·p0.9999: 33.489 ms/op
                 listUser·p1.00:   34.144 ms/op

Iteration   3: 5.704 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.723 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   7.586 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   10.657 ms/op
                 listUser·p0.999:  34.265 ms/op
                 listUser·p0.9999: 50.553 ms/op
                 listUser·p1.00:   50.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 170458
  mean =      5.631 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 60197 
    [ 5.000, 10.000) = 107852 
    [10.000, 15.000) = 2117 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 134 
    [30.000, 35.000) = 82 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 19 
    [50.000, 55.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     27.951 ms/op
     p(99.9900) =     49.739 ms/op
     p(99.9990) =     50.671 ms/op
     p(99.9999) =     50.856 ms/op
    p(100.0000) =     50.856 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.208 ± 2.144  ops/ms
ClientGrpc.existUser                       thrpt       3   7.753 ± 0.435  ops/ms
ClientGrpc.getUser                         thrpt       3   7.378 ± 3.541  ops/ms
ClientGrpc.listUser                        thrpt       3   5.735 ± 1.351  ops/ms
ClientGrpc.createUser                       avgt       3   4.478 ± 0.590   ms/op
ClientGrpc.existUser                        avgt       3   4.160 ± 0.524   ms/op
ClientGrpc.getUser                          avgt       3   4.433 ± 1.697   ms/op
ClientGrpc.listUser                         avgt       3   5.835 ± 1.681   ms/op
ClientGrpc.createUser                     sample  214110   4.481 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.926           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.546           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.988           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.569           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.073           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.066           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.524           ms/op
ClientGrpc.existUser                      sample  233194   4.118 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.882           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.022           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.423           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.980           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.177           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.622           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.702           ms/op
ClientGrpc.getUser                        sample  215698   4.452 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.067           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.292           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.774           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.661           ms/op
ClientGrpc.listUser                       sample  170458   5.631 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.723           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.339           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.469           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          27.951           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          49.739           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          50.856           ms/op
