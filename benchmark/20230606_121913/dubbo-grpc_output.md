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
# Warmup Iteration   1: 4.235 ops/ms
# Warmup Iteration   2: 8.914 ops/ms
# Warmup Iteration   3: 9.853 ops/ms
Iteration   1: 10.486 ops/ms
Iteration   2: 10.493 ops/ms
Iteration   3: 10.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.456 ±(99.9%) 1.056 ops/ms [Average]
  (min, avg, max) = (10.390, 10.456, 10.493), stdev = 0.058
  CI (99.9%): [9.400, 11.512] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.314 ops/ms
# Warmup Iteration   2: 10.609 ops/ms
# Warmup Iteration   3: 10.977 ops/ms
Iteration   1: 11.092 ops/ms
Iteration   2: 11.026 ops/ms
Iteration   3: 10.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.980 ±(99.9%) 2.563 ops/ms [Average]
  (min, avg, max) = (10.822, 10.980, 11.092), stdev = 0.140
  CI (99.9%): [8.417, 13.543] (assumes normal distribution)


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
# Warmup Iteration   1: 6.705 ops/ms
# Warmup Iteration   2: 9.941 ops/ms
# Warmup Iteration   3: 10.460 ops/ms
Iteration   1: 10.416 ops/ms
Iteration   2: 10.683 ops/ms
Iteration   3: 10.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.598 ±(99.9%) 2.880 ops/ms [Average]
  (min, avg, max) = (10.416, 10.598, 10.696), stdev = 0.158
  CI (99.9%): [7.718, 13.479] (assumes normal distribution)


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
# Warmup Iteration   1: 5.597 ops/ms
# Warmup Iteration   2: 7.638 ops/ms
# Warmup Iteration   3: 8.085 ops/ms
Iteration   1: 7.921 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.027 ±(99.9%) 1.704 ops/ms [Average]
  (min, avg, max) = (7.921, 8.027, 8.098), stdev = 0.093
  CI (99.9%): [6.323, 9.732] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.238 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.002 ms/op
Iteration   1: 3.035 ±(99.9%) 0.003 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.011 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (2.984, 3.011, 3.035), stdev = 0.025
  CI (99.9%): [2.549, 3.474] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.002 ms/op
Iteration   1: 2.852 ±(99.9%) 0.003 ms/op
Iteration   2: 2.851 ±(99.9%) 0.002 ms/op
Iteration   3: 2.875 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.859 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.851, 2.859, 2.875), stdev = 0.014
  CI (99.9%): [2.613, 3.106] (assumes normal distribution)


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.002 ms/op
Iteration   1: 3.042 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.046 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (3.042, 3.046, 3.051), stdev = 0.005
  CI (99.9%): [2.958, 3.133] (assumes normal distribution)


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
# Warmup Iteration   1: 5.497 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.013 ms/op
Iteration   1: 4.024 ±(99.9%) 0.032 ms/op
Iteration   2: 4.036 ±(99.9%) 0.018 ms/op
Iteration   3: 4.033 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.031 ±(99.9%) 0.117 ms/op [Average]
  (min, avg, max) = (4.024, 4.031, 4.036), stdev = 0.006
  CI (99.9%): [3.914, 4.148] (assumes normal distribution)


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  7.348 ms/op
                 createUser·p0.9999: 15.844 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.136 ms/op
                 createUser·p0.9999: 18.907 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.045 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.380 ms/op
                 createUser·p0.9999: 34.046 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316538
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25672 
    [ 2.500,  5.000) = 289000 
    [ 5.000,  7.500) = 1556 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.471 ms/op
     p(99.9900) =     33.238 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.005 ms/op
Iteration   1: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  7.852 ms/op
                 existUser·p0.9999: 11.920 ms/op
                 existUser·p1.00:   12.304 ms/op

Iteration   2: 2.920 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.884 ms/op
                 existUser·p0.9999: 13.977 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.570 ms/op
                 existUser·p0.999:  7.952 ms/op
                 existUser·p0.9999: 16.644 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327993
  mean =      2.926 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 729 
    [ 1.250,  2.500) = 34826 
    [ 2.500,  3.750) = 283299 
    [ 3.750,  5.000) = 7730 
    [ 5.000,  6.250) = 713 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     14.723 ms/op
     p(99.9990) =     16.997 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.290 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.107 ms/op
                 getUser·p0.9999: 13.846 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.785 ms/op
                 getUser·p0.9999: 14.774 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.460 ms/op
                 getUser·p0.999:  8.581 ms/op
                 getUser·p0.9999: 17.920 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312540
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 989 
    [ 1.250,  2.500) = 20629 
    [ 2.500,  3.750) = 265434 
    [ 3.750,  5.000) = 23817 
    [ 5.000,  6.250) = 1001 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     16.585 ms/op
     p(99.9990) =     19.026 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 5.375 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.011 ms/op
Iteration   1: 3.984 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  13.309 ms/op
                 listUser·p0.9999: 16.596 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   2: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.787 ms/op
                 listUser·p0.9999: 22.614 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 3.975 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  16.730 ms/op
                 listUser·p0.9999: 22.314 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239295
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2857 
    [ 2.500,  5.000) = 212316 
    [ 5.000,  7.500) = 22532 
    [ 7.500, 10.000) = 1114 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     14.638 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.456 ± 1.056  ops/ms
ClientGrpc.existUser                       thrpt       3  10.980 ± 2.563  ops/ms
ClientGrpc.getUser                         thrpt       3  10.598 ± 2.880  ops/ms
ClientGrpc.listUser                        thrpt       3   8.027 ± 1.704  ops/ms
ClientGrpc.createUser                       avgt       3   3.011 ± 0.462   ms/op
ClientGrpc.existUser                        avgt       3   2.859 ± 0.246   ms/op
ClientGrpc.getUser                          avgt       3   3.046 ± 0.087   ms/op
ClientGrpc.listUser                         avgt       3   4.031 ± 0.117   ms/op
ClientGrpc.createUser                     sample  316538   3.031 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.471           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.238           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.472           ms/op
ClientGrpc.existUser                      sample  327993   2.926 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.702           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.897           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.723           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.007           ms/op
ClientGrpc.getUser                        sample  312540   3.071 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.585           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.733           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.585           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.137           ms/op
ClientGrpc.listUser                       sample  239295   4.009 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.918           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.638           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.381           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
