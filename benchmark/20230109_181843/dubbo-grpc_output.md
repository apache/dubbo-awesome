# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.742 ops/ms
# Warmup Iteration   2: 9.707 ops/ms
# Warmup Iteration   3: 10.259 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.676 ops/ms
Iteration   3: 10.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.595 ±(99.9%) 1.466 ops/ms [Average]
  (min, avg, max) = (10.515, 10.595, 10.676), stdev = 0.080
  CI (99.9%): [9.129, 12.062] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.877 ops/ms
# Warmup Iteration   2: 10.697 ops/ms
# Warmup Iteration   3: 11.015 ops/ms
Iteration   1: 10.782 ops/ms
Iteration   2: 11.077 ops/ms
Iteration   3: 11.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.979 ±(99.9%) 3.126 ops/ms [Average]
  (min, avg, max) = (10.782, 10.979, 11.080), stdev = 0.171
  CI (99.9%): [7.853, 14.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.506 ops/ms
# Warmup Iteration   2: 10.242 ops/ms
# Warmup Iteration   3: 10.609 ops/ms
Iteration   1: 10.160 ops/ms
Iteration   2: 10.356 ops/ms
Iteration   3: 10.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.273 ±(99.9%) 1.844 ops/ms [Average]
  (min, avg, max) = (10.160, 10.273, 10.356), stdev = 0.101
  CI (99.9%): [8.429, 12.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.101 ops/ms
# Warmup Iteration   2: 7.852 ops/ms
# Warmup Iteration   3: 7.964 ops/ms
Iteration   1: 8.112 ops/ms
Iteration   2: 8.123 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.174 ±(99.9%) 1.803 ops/ms [Average]
  (min, avg, max) = (8.112, 8.174, 8.288), stdev = 0.099
  CI (99.9%): [6.371, 9.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.090 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.005 ms/op
Iteration   1: 3.079 ±(99.9%) 0.003 ms/op
Iteration   2: 3.154 ±(99.9%) 0.002 ms/op
Iteration   3: 3.055 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.096 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.055, 3.096, 3.154), stdev = 0.052
  CI (99.9%): [2.155, 4.037] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.002 ms/op
Iteration   1: 2.979 ±(99.9%) 0.004 ms/op
Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
Iteration   3: 2.928 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.983 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (2.928, 2.983, 3.042), stdev = 0.057
  CI (99.9%): [1.947, 4.020] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.894 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.002 ms/op
Iteration   1: 3.088 ±(99.9%) 0.002 ms/op
Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
Iteration   3: 3.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.086 ±(99.9%) 0.963 ms/op [Average]
  (min, avg, max) = (3.032, 3.086, 3.138), stdev = 0.053
  CI (99.9%): [2.123, 4.048] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.705 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.033 ms/op
Iteration   1: 3.933 ±(99.9%) 0.022 ms/op
Iteration   2: 4.035 ±(99.9%) 0.025 ms/op
Iteration   3: 3.953 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.973 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (3.933, 3.973, 4.035), stdev = 0.054
  CI (99.9%): [2.987, 4.960] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.889 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.750 ms/op
                 createUser·p0.9999: 18.405 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  9.551 ms/op
                 createUser·p0.9999: 16.859 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 21.413 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308448
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27511 
    [ 2.500,  5.000) = 279778 
    [ 5.000,  7.500) = 736 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     18.814 ms/op
     p(99.9990) =     21.722 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.608 ms/op
                 existUser·p0.9999: 12.206 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  5.784 ms/op
                 existUser·p0.9999: 18.560 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.489 ms/op
                 existUser·p0.9999: 14.296 ms/op
                 existUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318368
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1951 
    [ 1.250,  2.500) = 37118 
    [ 2.500,  3.750) = 253660 
    [ 3.750,  5.000) = 24794 
    [ 5.000,  6.250) = 388 
    [ 6.250,  7.500) = 215 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.045 ms/op
     p(99.9900) =     17.547 ms/op
     p(99.9990) =     18.895 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.006 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.473 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 16.330 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.383 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.352 ms/op
                 getUser·p0.999:  6.996 ms/op
                 getUser·p0.9999: 27.925 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.303 ms/op
                 getUser·p0.9999: 17.227 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316575
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28670 
    [ 2.500,  5.000) = 287019 
    [ 5.000,  7.500) = 637 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.073 ms/op
     p(99.9900) =     26.171 ms/op
     p(99.9990) =     28.563 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.201 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.012 ms/op
Iteration   1: 4.012 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.873 ms/op
                 listUser·p0.9999: 16.632 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 4.100 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.923 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 31.064 ms/op
                 listUser·p1.00:   31.359 ms/op

Iteration   3: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.717 ms/op
                 listUser·p0.9999: 18.482 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237619
  mean =      4.040 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3391 
    [ 2.500,  5.000) = 205212 
    [ 5.000,  7.500) = 27590 
    [ 7.500, 10.000) = 894 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     30.441 ms/op
     p(99.9990) =     31.281 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.595 ± 1.466  ops/ms
ClientGrpc.existUser                       thrpt       3  10.979 ± 3.126  ops/ms
ClientGrpc.getUser                         thrpt       3  10.273 ± 1.844  ops/ms
ClientGrpc.listUser                        thrpt       3   8.174 ± 1.803  ops/ms
ClientGrpc.createUser                       avgt       3   3.096 ± 0.941   ms/op
ClientGrpc.existUser                        avgt       3   2.983 ± 1.037   ms/op
ClientGrpc.getUser                          avgt       3   3.086 ± 0.963   ms/op
ClientGrpc.listUser                         avgt       3   3.973 ± 0.987   ms/op
ClientGrpc.createUser                     sample  308448   3.110 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.642           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.044           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.814           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  318368   3.015 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.647           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.045           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.547           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.071           ms/op
ClientGrpc.getUser                        sample  316575   3.033 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.383           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.073           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.171           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.738           ms/op
ClientGrpc.listUser                       sample  237619   4.040 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.896           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.441           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.359           ms/op
