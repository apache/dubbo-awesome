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
# Warmup Iteration   1: 3.924 ops/ms
# Warmup Iteration   2: 8.669 ops/ms
# Warmup Iteration   3: 9.811 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 10.101 ops/ms
Iteration   3: 10.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.205 ±(99.9%) 1.809 ops/ms [Average]
  (min, avg, max) = (10.101, 10.205, 10.298), stdev = 0.099
  CI (99.9%): [8.396, 12.014] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.331 ops/ms
# Warmup Iteration   2: 10.194 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.705 ops/ms
Iteration   2: 10.706 ops/ms
Iteration   3: 10.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.781 ±(99.9%) 2.390 ops/ms [Average]
  (min, avg, max) = (10.705, 10.781, 10.933), stdev = 0.131
  CI (99.9%): [8.391, 13.171] (assumes normal distribution)


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
# Warmup Iteration   1: 7.068 ops/ms
# Warmup Iteration   2: 9.680 ops/ms
# Warmup Iteration   3: 10.205 ops/ms
Iteration   1: 10.261 ops/ms
Iteration   2: 10.210 ops/ms
Iteration   3: 10.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.217 ±(99.9%) 0.758 ops/ms [Average]
  (min, avg, max) = (10.179, 10.217, 10.261), stdev = 0.042
  CI (99.9%): [9.459, 10.975] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.342 ops/ms
# Warmup Iteration   2: 7.905 ops/ms
# Warmup Iteration   3: 8.014 ops/ms
Iteration   1: 8.120 ops/ms
Iteration   2: 8.100 ops/ms
Iteration   3: 8.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.100 ±(99.9%) 0.363 ops/ms [Average]
  (min, avg, max) = (8.080, 8.100, 8.120), stdev = 0.020
  CI (99.9%): [7.737, 8.463] (assumes normal distribution)


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
# Warmup Iteration   1: 4.541 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.141 ±(99.9%) 0.007 ms/op
Iteration   2: 3.158 ±(99.9%) 0.003 ms/op
Iteration   3: 3.116 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.138 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.116, 3.138, 3.158), stdev = 0.021
  CI (99.9%): [2.750, 3.526] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 2.914 ±(99.9%) 0.004 ms/op
Iteration   3: 2.947 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.964 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (2.914, 2.964, 3.031), stdev = 0.060
  CI (99.9%): [1.864, 4.064] (assumes normal distribution)


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.004 ms/op
Iteration   1: 3.125 ±(99.9%) 0.004 ms/op
Iteration   2: 3.059 ±(99.9%) 0.002 ms/op
Iteration   3: 3.121 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.102 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (3.059, 3.102, 3.125), stdev = 0.037
  CI (99.9%): [2.434, 3.770] (assumes normal distribution)


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
# Warmup Iteration   1: 5.438 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.031 ms/op
Iteration   1: 3.901 ±(99.9%) 0.039 ms/op
Iteration   2: 3.925 ±(99.9%) 0.015 ms/op
Iteration   3: 3.918 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.915 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (3.901, 3.915, 3.925), stdev = 0.013
  CI (99.9%): [3.683, 4.147] (assumes normal distribution)


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.293 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.009 ms/op
Iteration   1: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  9.813 ms/op
                 createUser·p0.9999: 16.510 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  13.681 ms/op
                 createUser·p0.9999: 18.874 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   3: 3.130 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  14.333 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306028
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13749 
    [ 2.500,  5.000) = 289485 
    [ 5.000,  7.500) = 2071 
    [ 7.500, 10.000) = 281 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     19.477 ms/op
     p(99.9990) =     20.247 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
Iteration   1: 3.004 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.772 ms/op
                 existUser·p0.999:  8.290 ms/op
                 existUser·p0.9999: 20.802 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.289 ms/op
                 existUser·p0.9999: 14.089 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  10.609 ms/op
                 existUser·p0.9999: 23.330 ms/op
                 existUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323267
  mean =      2.968 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30769 
    [ 2.500,  5.000) = 290407 
    [ 5.000,  7.500) = 1615 
    [ 7.500, 10.000) = 207 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.745 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     23.684 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 4.380 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.006 ms/op
Iteration   1: 3.104 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  11.106 ms/op
                 getUser·p0.9999: 12.917 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   2: 3.157 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.590 ms/op
                 getUser·p0.9999: 15.032 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  8.138 ms/op
                 getUser·p0.9999: 35.914 ms/op
                 getUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307008
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11737 
    [ 2.500,  5.000) = 292901 
    [ 5.000,  7.500) = 1848 
    [ 7.500, 10.000) = 237 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     25.906 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 5.513 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.009 ms/op
Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 18.834 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 3.985 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.623 ms/op
                 listUser·p0.9999: 24.674 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   3: 3.921 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.373 ms/op
                 listUser·p0.9999: 20.633 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242699
  mean =      3.957 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3425 
    [ 2.500,  5.000) = 220825 
    [ 5.000,  7.500) = 17035 
    [ 7.500, 10.000) = 816 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.308 ms/op
     p(99.9900) =     20.668 ms/op
     p(99.9990) =     25.054 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.205 ± 1.809  ops/ms
ClientGrpc.existUser                       thrpt       3  10.781 ± 2.390  ops/ms
ClientGrpc.getUser                         thrpt       3  10.217 ± 0.758  ops/ms
ClientGrpc.listUser                        thrpt       3   8.100 ± 0.363  ops/ms
ClientGrpc.createUser                       avgt       3   3.138 ± 0.388   ms/op
ClientGrpc.existUser                        avgt       3   2.964 ± 1.100   ms/op
ClientGrpc.getUser                          avgt       3   3.102 ± 0.668   ms/op
ClientGrpc.listUser                         avgt       3   3.915 ± 0.232   ms/op
ClientGrpc.createUser                     sample  306028   3.137 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.684           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.353           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.477           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.343           ms/op
ClientGrpc.existUser                      sample  323267   2.968 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.691           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.745           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.430           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.052           ms/op
ClientGrpc.getUser                        sample  307008   3.126 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.530           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.535           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.906           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.766           ms/op
ClientGrpc.listUser                       sample  242699   3.957 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.823           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.308           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.668           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
