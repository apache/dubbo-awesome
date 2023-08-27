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
# Warmup Iteration   1: 3.900 ops/ms
# Warmup Iteration   2: 8.766 ops/ms
# Warmup Iteration   3: 9.762 ops/ms
Iteration   1: 10.264 ops/ms
Iteration   2: 10.457 ops/ms
Iteration   3: 10.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.333 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (10.264, 10.333, 10.457), stdev = 0.108
  CI (99.9%): [8.371, 12.295] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.236 ops/ms
# Warmup Iteration   2: 10.468 ops/ms
# Warmup Iteration   3: 10.712 ops/ms
Iteration   1: 11.035 ops/ms
Iteration   2: 10.931 ops/ms
Iteration   3: 10.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.974 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (10.931, 10.974, 11.035), stdev = 0.055
  CI (99.9%): [9.979, 11.968] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.773 ops/ms
# Warmup Iteration   2: 9.727 ops/ms
# Warmup Iteration   3: 10.290 ops/ms
Iteration   1: 10.311 ops/ms
Iteration   2: 10.364 ops/ms
Iteration   3: 10.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.354 ±(99.9%) 0.704 ops/ms [Average]
  (min, avg, max) = (10.311, 10.354, 10.386), stdev = 0.039
  CI (99.9%): [9.650, 11.058] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.097 ops/ms
# Warmup Iteration   2: 7.580 ops/ms
# Warmup Iteration   3: 7.891 ops/ms
Iteration   1: 7.771 ops/ms
Iteration   2: 7.729 ops/ms
Iteration   3: 7.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.782 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (7.729, 7.782, 7.847), stdev = 0.060
  CI (99.9%): [6.688, 8.876] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.506 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 2.997 ±(99.9%) 0.003 ms/op
Iteration   3: 3.092 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (2.997, 3.037, 3.092), stdev = 0.049
  CI (99.9%): [2.136, 3.939] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.003 ms/op
Iteration   1: 2.903 ±(99.9%) 0.002 ms/op
Iteration   2: 2.893 ±(99.9%) 0.004 ms/op
Iteration   3: 2.910 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.893, 2.902, 2.910), stdev = 0.009
  CI (99.9%): [2.743, 3.062] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.270 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.003 ms/op
Iteration   1: 3.045 ±(99.9%) 0.003 ms/op
Iteration   2: 3.006 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.037 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.006, 3.037, 3.059), stdev = 0.028
  CI (99.9%): [2.533, 3.540] (assumes normal distribution)


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
# Warmup Iteration   1: 4.955 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.012 ms/op
Iteration   1: 4.084 ±(99.9%) 0.022 ms/op
Iteration   2: 4.114 ±(99.9%) 0.012 ms/op
Iteration   3: 4.007 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.068 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (4.007, 4.068, 4.114), stdev = 0.055
  CI (99.9%): [3.065, 5.072] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.387 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.696 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  8.439 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  9.941 ms/op
                 createUser·p0.9999: 14.922 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  14.321 ms/op
                 createUser·p0.9999: 19.124 ms/op
                 createUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309460
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 494 
    [ 1.250,  2.500) = 17424 
    [ 2.500,  3.750) = 268051 
    [ 3.750,  5.000) = 21022 
    [ 5.000,  6.250) = 1125 
    [ 6.250,  7.500) = 572 
    [ 7.500,  8.750) = 359 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =     11.183 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.005 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.102 ms/op
                 existUser·p0.9999: 19.095 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  10.584 ms/op
                 existUser·p0.9999: 22.809 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.772 ms/op
                 existUser·p0.999:  10.437 ms/op
                 existUser·p0.9999: 16.830 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322605
  mean =      2.978 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23624 
    [ 2.500,  5.000) = 297053 
    [ 5.000,  7.500) = 1248 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =     10.155 ms/op
     p(99.9900) =     20.934 ms/op
     p(99.9990) =     23.028 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  9.758 ms/op
                 getUser·p0.9999: 13.856 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.334 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  8.228 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   3: 3.079 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.646 ms/op
                 getUser·p0.9999: 26.104 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310657
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17192 
    [ 2.500,  5.000) = 291122 
    [ 5.000,  7.500) = 1775 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.755 ms/op
     p(99.9900) =     25.227 ms/op
     p(99.9990) =     26.408 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 5.850 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.012 ms/op
Iteration   1: 4.112 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.497 ms/op
                 listUser·p0.999:  14.753 ms/op
                 listUser·p0.9999: 16.105 ms/op
                 listUser·p1.00:   16.466 ms/op

Iteration   2: 4.151 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.912 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  16.660 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   3: 3.913 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  18.846 ms/op
                 listUser·p0.9999: 27.263 ms/op
                 listUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236774
  mean =      4.056 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2237 
    [ 2.500,  5.000) = 209366 
    [ 5.000,  7.500) = 23174 
    [ 7.500, 10.000) = 1489 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     15.933 ms/op
     p(99.9900) =     27.208 ms/op
     p(99.9990) =     28.707 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.333 ± 1.962  ops/ms
ClientGrpc.existUser                       thrpt       3  10.974 ± 0.995  ops/ms
ClientGrpc.getUser                         thrpt       3  10.354 ± 0.704  ops/ms
ClientGrpc.listUser                        thrpt       3   7.782 ± 1.094  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.901   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 0.160   ms/op
ClientGrpc.getUser                          avgt       3   3.037 ± 0.504   ms/op
ClientGrpc.listUser                         avgt       3   4.068 ± 1.004   ms/op
ClientGrpc.createUser                     sample  309460   3.100 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.699           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.183           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.990           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.300           ms/op
ClientGrpc.existUser                      sample  322605   2.978 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.527           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.155           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.934           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.134           ms/op
ClientGrpc.getUser                        sample  310657   3.089 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.334           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.755           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.227           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.673           ms/op
ClientGrpc.listUser                       sample  236774   4.056 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.855           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.933           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.208           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.869           ms/op
