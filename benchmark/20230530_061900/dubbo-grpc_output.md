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
# Warmup Iteration   1: 3.694 ops/ms
# Warmup Iteration   2: 8.312 ops/ms
# Warmup Iteration   3: 9.820 ops/ms
Iteration   1: 10.304 ops/ms
Iteration   2: 10.275 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.337 ±(99.9%) 1.516 ops/ms [Average]
  (min, avg, max) = (10.275, 10.337, 10.432), stdev = 0.083
  CI (99.9%): [8.821, 11.854] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.719 ops/ms
# Warmup Iteration   2: 10.301 ops/ms
# Warmup Iteration   3: 10.766 ops/ms
Iteration   1: 10.840 ops/ms
Iteration   2: 11.074 ops/ms
Iteration   3: 11.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.023 ±(99.9%) 2.991 ops/ms [Average]
  (min, avg, max) = (10.840, 11.023, 11.156), stdev = 0.164
  CI (99.9%): [8.032, 14.014] (assumes normal distribution)


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
# Warmup Iteration   1: 6.546 ops/ms
# Warmup Iteration   2: 9.676 ops/ms
# Warmup Iteration   3: 10.057 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.209 ops/ms
Iteration   3: 10.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.285 ±(99.9%) 2.992 ops/ms [Average]
  (min, avg, max) = (10.173, 10.285, 10.473), stdev = 0.164
  CI (99.9%): [7.294, 13.277] (assumes normal distribution)


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
# Warmup Iteration   1: 4.942 ops/ms
# Warmup Iteration   2: 7.485 ops/ms
# Warmup Iteration   3: 7.686 ops/ms
Iteration   1: 7.608 ops/ms
Iteration   2: 7.880 ops/ms
Iteration   3: 7.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.735 ±(99.9%) 2.495 ops/ms [Average]
  (min, avg, max) = (7.608, 7.735, 7.880), stdev = 0.137
  CI (99.9%): [5.240, 10.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.495 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.002 ms/op
Iteration   1: 3.167 ±(99.9%) 0.002 ms/op
Iteration   2: 3.158 ±(99.9%) 0.004 ms/op
Iteration   3: 3.025 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 1.444 ms/op [Average]
  (min, avg, max) = (3.025, 3.117, 3.167), stdev = 0.079
  CI (99.9%): [1.673, 4.561] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.310 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.003 ms/op
Iteration   1: 2.975 ±(99.9%) 0.003 ms/op
Iteration   2: 2.867 ±(99.9%) 0.003 ms/op
Iteration   3: 2.986 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.943 ±(99.9%) 1.202 ms/op [Average]
  (min, avg, max) = (2.867, 2.943, 2.986), stdev = 0.066
  CI (99.9%): [1.740, 4.145] (assumes normal distribution)


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.003 ms/op
Iteration   1: 3.112 ±(99.9%) 0.002 ms/op
Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
Iteration   3: 3.084 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.110 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (3.084, 3.110, 3.133), stdev = 0.025
  CI (99.9%): [2.660, 3.560] (assumes normal distribution)


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
# Warmup Iteration   1: 5.169 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.019 ms/op
Iteration   1: 4.085 ±(99.9%) 0.011 ms/op
Iteration   2: 4.019 ±(99.9%) 0.012 ms/op
Iteration   3: 3.888 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.997 ±(99.9%) 1.829 ms/op [Average]
  (min, avg, max) = (3.888, 3.997, 4.085), stdev = 0.100
  CI (99.9%): [2.169, 5.826] (assumes normal distribution)


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.008 ms/op
Iteration   1: 3.089 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  10.994 ms/op
                 createUser·p0.9999: 20.883 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.146 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  8.493 ms/op
                 createUser·p0.9999: 23.156 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  10.747 ms/op
                 createUser·p0.9999: 24.897 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307257
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17245 
    [ 2.500,  5.000) = 287645 
    [ 5.000,  7.500) = 1811 
    [ 7.500, 10.000) = 235 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =     10.252 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     25.416 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.376 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.172 ms/op
                 existUser·p0.9999: 12.741 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   2: 2.968 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.152 ms/op
                 existUser·p0.9999: 14.422 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  9.489 ms/op
                 existUser·p0.9999: 18.036 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322549
  mean =      2.975 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 527 
    [ 1.250,  2.500) = 26360 
    [ 2.500,  3.750) = 283893 
    [ 3.750,  5.000) = 10554 
    [ 5.000,  6.250) = 573 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.085 ms/op
     p(99.9900) =     16.797 ms/op
     p(99.9990) =     18.532 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 4.675 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  8.913 ms/op
                 getUser·p0.9999: 18.771 ms/op
                 getUser·p1.00:   18.874 ms/op

Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  9.177 ms/op
                 getUser·p0.9999: 15.516 ms/op
                 getUser·p1.00:   16.089 ms/op

Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  9.060 ms/op
                 getUser·p0.9999: 16.996 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308506
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 687 
    [ 1.250,  2.500) = 15748 
    [ 2.500,  3.750) = 268422 
    [ 3.750,  5.000) = 20810 
    [ 5.000,  6.250) = 1666 
    [ 6.250,  7.500) = 575 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =      9.036 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 5.752 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.012 ms/op
Iteration   1: 4.078 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  14.722 ms/op
                 listUser·p0.9999: 24.619 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   2: 3.929 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 18.533 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.130 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  16.737 ms/op
                 listUser·p0.9999: 25.395 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237300
  mean =      4.044 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2692 
    [ 2.500,  5.000) = 204862 
    [ 5.000,  7.500) = 27676 
    [ 7.500, 10.000) = 1584 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     16.112 ms/op
     p(99.9900) =     24.781 ms/op
     p(99.9990) =     25.776 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.337 ± 1.516  ops/ms
ClientGrpc.existUser                       thrpt       3  11.023 ± 2.991  ops/ms
ClientGrpc.getUser                         thrpt       3  10.285 ± 2.992  ops/ms
ClientGrpc.listUser                        thrpt       3   7.735 ± 2.495  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 1.444   ms/op
ClientGrpc.existUser                        avgt       3   2.943 ± 1.202   ms/op
ClientGrpc.getUser                          avgt       3   3.110 ± 0.450   ms/op
ClientGrpc.listUser                         avgt       3   3.997 ± 1.829   ms/op
ClientGrpc.createUser                     sample  307257   3.124 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.719           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.965           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.252           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.445           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.657           ms/op
ClientGrpc.existUser                      sample  322549   2.975 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.750           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.085           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.797           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.645           ms/op
ClientGrpc.getUser                        sample  308506   3.112 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.714           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.036           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.350           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.874           ms/op
ClientGrpc.listUser                       sample  237300   4.044 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.130           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.005           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.112           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.781           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.854           ms/op
