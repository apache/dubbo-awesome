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
# Warmup Iteration   1: 4.559 ops/ms
# Warmup Iteration   2: 9.132 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.929 ops/ms
Iteration   2: 10.751 ops/ms
Iteration   3: 10.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.757 ±(99.9%) 3.089 ops/ms [Average]
  (min, avg, max) = (10.590, 10.757, 10.929), stdev = 0.169
  CI (99.9%): [7.668, 13.845] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ops/ms
# Warmup Iteration   2: 11.053 ops/ms
# Warmup Iteration   3: 11.318 ops/ms
Iteration   1: 11.262 ops/ms
Iteration   2: 11.400 ops/ms
Iteration   3: 11.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.279 ±(99.9%) 2.072 ops/ms [Average]
  (min, avg, max) = (11.175, 11.279, 11.400), stdev = 0.114
  CI (99.9%): [9.207, 13.350] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.057 ops/ms
# Warmup Iteration   2: 10.250 ops/ms
# Warmup Iteration   3: 10.530 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.736 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.685 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (10.530, 10.685, 10.789), stdev = 0.137
  CI (99.9%): [8.183, 13.187] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.704 ops/ms
# Warmup Iteration   2: 8.527 ops/ms
# Warmup Iteration   3: 8.151 ops/ms
Iteration   1: 7.950 ops/ms
Iteration   2: 8.236 ops/ms
Iteration   3: 8.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.071 ±(99.9%) 2.695 ops/ms [Average]
  (min, avg, max) = (7.950, 8.071, 8.236), stdev = 0.148
  CI (99.9%): [5.377, 10.766] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.002 ms/op
Iteration   1: 3.035 ±(99.9%) 0.003 ms/op
Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
Iteration   3: 3.077 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (3.035, 3.094, 3.172), stdev = 0.070
  CI (99.9%): [1.815, 4.374] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.648 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 2.989 ±(99.9%) 0.002 ms/op
Iteration   2: 2.934 ±(99.9%) 0.003 ms/op
Iteration   3: 2.934 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.952 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (2.934, 2.952, 2.989), stdev = 0.032
  CI (99.9%): [2.372, 3.533] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.391 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.003 ms/op
Iteration   1: 3.221 ±(99.9%) 0.002 ms/op
Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
Iteration   3: 3.167 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.195 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (3.167, 3.195, 3.221), stdev = 0.027
  CI (99.9%): [2.704, 3.686] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 6.304 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.388 ±(99.9%) 0.015 ms/op
Iteration   1: 4.257 ±(99.9%) 0.009 ms/op
Iteration   2: 4.112 ±(99.9%) 0.009 ms/op
Iteration   3: 4.165 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.178 ±(99.9%) 1.338 ms/op [Average]
  (min, avg, max) = (4.112, 4.178, 4.257), stdev = 0.073
  CI (99.9%): [2.840, 5.516] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.636 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
Iteration   1: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.242 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  8.019 ms/op
                 createUser·p0.9999: 16.572 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  8.179 ms/op
                 createUser·p0.9999: 18.050 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   3: 3.254 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  8.339 ms/op
                 createUser·p0.9999: 22.714 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301011
  mean =      3.189 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18814 
    [ 2.500,  5.000) = 279979 
    [ 5.000,  7.500) = 1803 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.242 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      8.159 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     23.297 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.496 ms/op
                 existUser·p0.9999: 21.543 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 13.491 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   3: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.550 ms/op
                 existUser·p0.9999: 16.007 ms/op
                 existUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321889
  mean =      2.982 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25963 
    [ 2.500,  5.000) = 294533 
    [ 5.000,  7.500) = 1052 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.636 ms/op
     p(99.9900) =     19.915 ms/op
     p(99.9990) =     21.718 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.252 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
Iteration   1: 3.037 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  9.559 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  6.731 ms/op
                 getUser·p0.9999: 20.089 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   3: 3.038 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  6.781 ms/op
                 getUser·p0.9999: 35.979 ms/op
                 getUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317820
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26764 
    [ 2.500,  5.000) = 289098 
    [ 5.000,  7.500) = 1655 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      7.356 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     36.927 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.539 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.321 ±(99.9%) 0.012 ms/op
Iteration   1: 4.203 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  13.432 ms/op
                 listUser·p0.9999: 18.002 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   2: 4.238 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 20.641 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 4.188 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  18.633 ms/op
                 listUser·p0.9999: 27.918 ms/op
                 listUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 227921
  mean =      4.210 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1965 
    [ 2.500,  5.000) = 189546 
    [ 5.000,  7.500) = 34176 
    [ 7.500, 10.000) = 1758 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     25.894 ms/op
     p(99.9990) =     28.111 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.757 ± 3.089  ops/ms
ClientGrpc.existUser                       thrpt       3  11.279 ± 2.072  ops/ms
ClientGrpc.getUser                         thrpt       3  10.685 ± 2.502  ops/ms
ClientGrpc.listUser                        thrpt       3   8.071 ± 2.695  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 1.279   ms/op
ClientGrpc.existUser                        avgt       3   2.952 ± 0.580   ms/op
ClientGrpc.getUser                          avgt       3   3.195 ± 0.491   ms/op
ClientGrpc.listUser                         avgt       3   4.178 ± 1.338   ms/op
ClientGrpc.createUser                     sample  301011   3.189 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.242           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.159           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.840           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  321889   2.982 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.750           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.636           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.915           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.791           ms/op
ClientGrpc.getUser                        sample  317820   3.020 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.500           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.356           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.521           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.683           ms/op
ClientGrpc.listUser                       sample  227921   4.210 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.065           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.985           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.479           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.894           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.148           ms/op
