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
# Warmup Iteration   1: 4.633 ops/ms
# Warmup Iteration   2: 9.293 ops/ms
# Warmup Iteration   3: 10.508 ops/ms
Iteration   1: 10.676 ops/ms
Iteration   2: 10.796 ops/ms
Iteration   3: 10.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.671 ±(99.9%) 2.338 ops/ms [Average]
  (min, avg, max) = (10.540, 10.671, 10.796), stdev = 0.128
  CI (99.9%): [8.333, 13.008] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.904 ops/ms
# Warmup Iteration   2: 10.966 ops/ms
# Warmup Iteration   3: 11.350 ops/ms
Iteration   1: 11.384 ops/ms
Iteration   2: 11.444 ops/ms
Iteration   3: 11.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.422 ±(99.9%) 0.601 ops/ms [Average]
  (min, avg, max) = (11.384, 11.422, 11.444), stdev = 0.033
  CI (99.9%): [10.821, 12.023] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.854 ops/ms
# Warmup Iteration   2: 10.239 ops/ms
# Warmup Iteration   3: 10.626 ops/ms
Iteration   1: 10.737 ops/ms
Iteration   2: 10.255 ops/ms
Iteration   3: 10.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.488 ±(99.9%) 4.405 ops/ms [Average]
  (min, avg, max) = (10.255, 10.488, 10.737), stdev = 0.241
  CI (99.9%): [6.083, 14.892] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.767 ops/ms
# Warmup Iteration   2: 8.145 ops/ms
# Warmup Iteration   3: 8.216 ops/ms
Iteration   1: 8.278 ops/ms
Iteration   2: 8.305 ops/ms
Iteration   3: 8.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.317 ±(99.9%) 0.853 ops/ms [Average]
  (min, avg, max) = (8.278, 8.317, 8.369), stdev = 0.047
  CI (99.9%): [7.464, 9.170] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.002 ms/op
Iteration   1: 2.966 ±(99.9%) 0.002 ms/op
Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.990 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.966, 2.990, 3.003), stdev = 0.021
  CI (99.9%): [2.615, 3.365] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.854 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.881 ±(99.9%) 0.003 ms/op
Iteration   1: 2.896 ±(99.9%) 0.003 ms/op
Iteration   2: 2.804 ±(99.9%) 0.004 ms/op
Iteration   3: 2.902 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (2.804, 2.867, 2.902), stdev = 0.055
  CI (99.9%): [1.860, 3.874] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 2.955 ±(99.9%) 0.003 ms/op
Iteration   2: 2.998 ±(99.9%) 0.002 ms/op
Iteration   3: 3.020 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (2.955, 2.991, 3.020), stdev = 0.033
  CI (99.9%): [2.394, 3.588] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.229 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.013 ms/op
Iteration   1: 3.811 ±(99.9%) 0.022 ms/op
Iteration   2: 3.775 ±(99.9%) 0.031 ms/op
Iteration   3: 3.851 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.812 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.775, 3.812, 3.851), stdev = 0.038
  CI (99.9%): [3.114, 4.511] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.682 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  5.741 ms/op
                 createUser·p0.9999: 11.609 ms/op
                 createUser·p1.00:   12.009 ms/op

Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.897 ms/op
                 createUser·p0.9999: 13.038 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 3.010 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  18.948 ms/op
                 createUser·p0.9999: 26.804 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319564
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26946 
    [ 2.500,  5.000) = 291411 
    [ 5.000,  7.500) = 854 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.915 ms/op
     p(99.9900) =     25.891 ms/op
     p(99.9990) =     27.119 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.006 ms/op
Iteration   1: 2.856 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  6.300 ms/op
                 existUser·p0.9999: 11.777 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.895 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.844 ms/op
                 existUser·p0.9999: 15.612 ms/op
                 existUser·p1.00:   15.925 ms/op

Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.360 ms/op
                 existUser·p0.9999: 15.204 ms/op
                 existUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333109
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1859 
    [ 1.250,  2.500) = 40283 
    [ 2.500,  3.750) = 281287 
    [ 3.750,  5.000) = 8458 
    [ 5.000,  6.250) = 712 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.749 ms/op
     p(99.9900) =     15.161 ms/op
     p(99.9990) =     15.805 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.674 ms/op
                 getUser·p0.9999: 21.574 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.225 ms/op
                 getUser·p0.9999: 16.337 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  8.693 ms/op
                 getUser·p0.9999: 19.628 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322361
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28451 
    [ 2.500,  5.000) = 292496 
    [ 5.000,  7.500) = 1047 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.012 ms/op
     p(99.9900) =     20.522 ms/op
     p(99.9990) =     22.562 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 4.972 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.010 ms/op
Iteration   1: 3.894 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.015 ms/op
                 listUser·p0.999:  11.448 ms/op
                 listUser·p0.9999: 19.326 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.812 ms/op
                 listUser·p0.9999: 14.697 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 3.879 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.799 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.135 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 29.950 ms/op
                 listUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247988
  mean =      3.874 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3579 
    [ 2.500,  5.000) = 225581 
    [ 5.000,  7.500) = 17538 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.671 ± 2.338  ops/ms
ClientGrpc.existUser                       thrpt       3  11.422 ± 0.601  ops/ms
ClientGrpc.getUser                         thrpt       3  10.488 ± 4.405  ops/ms
ClientGrpc.listUser                        thrpt       3   8.317 ± 0.853  ops/ms
ClientGrpc.createUser                       avgt       3   2.990 ± 0.375   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 1.007   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.597   ms/op
ClientGrpc.listUser                         avgt       3   3.812 ± 0.699   ms/op
ClientGrpc.createUser                     sample  319564   3.002 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.605           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.915           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.891           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.263           ms/op
ClientGrpc.existUser                      sample  333109   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.582           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.749           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.161           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.925           ms/op
ClientGrpc.getUser                        sample  322361   2.977 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.683           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.012           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.522           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  247988   3.874 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.799           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.960           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.214           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.212           ms/op
