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
# Warmup Iteration   1: 4.032 ops/ms
# Warmup Iteration   2: 8.810 ops/ms
# Warmup Iteration   3: 9.714 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 10.092 ops/ms
Iteration   3: 10.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.141 ±(99.9%) 1.203 ops/ms [Average]
  (min, avg, max) = (10.092, 10.141, 10.216), stdev = 0.066
  CI (99.9%): [8.938, 11.344] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.731 ops/ms
# Warmup Iteration   2: 10.560 ops/ms
# Warmup Iteration   3: 10.892 ops/ms
Iteration   1: 10.868 ops/ms
Iteration   2: 11.267 ops/ms
Iteration   3: 11.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.154 ±(99.9%) 4.548 ops/ms [Average]
  (min, avg, max) = (10.868, 11.154, 11.327), stdev = 0.249
  CI (99.9%): [6.606, 15.702] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.639 ops/ms
# Warmup Iteration   2: 10.013 ops/ms
# Warmup Iteration   3: 10.649 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.623 ops/ms
Iteration   3: 10.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.552 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (10.469, 10.552, 10.623), stdev = 0.078
  CI (99.9%): [9.133, 11.971] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.618 ops/ms
# Warmup Iteration   2: 7.275 ops/ms
# Warmup Iteration   3: 7.804 ops/ms
Iteration   1: 8.145 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.001 ±(99.9%) 2.324 ops/ms [Average]
  (min, avg, max) = (7.903, 8.001, 8.145), stdev = 0.127
  CI (99.9%): [5.676, 10.325] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.389 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.003 ms/op
Iteration   1: 3.073 ±(99.9%) 0.002 ms/op
Iteration   2: 3.025 ±(99.9%) 0.004 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.060 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (3.025, 3.060, 3.083), stdev = 0.031
  CI (99.9%): [2.496, 3.625] (assumes normal distribution)


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.003 ms/op
Iteration   1: 2.895 ±(99.9%) 0.002 ms/op
Iteration   2: 2.883 ±(99.9%) 0.004 ms/op
Iteration   3: 2.905 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (2.883, 2.894, 2.905), stdev = 0.011
  CI (99.9%): [2.692, 3.097] (assumes normal distribution)


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.003 ms/op
Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
Iteration   3: 3.060 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.045 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (3.035, 3.045, 3.060), stdev = 0.013
  CI (99.9%): [2.802, 3.289] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.996 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.015 ms/op
Iteration   1: 3.972 ±(99.9%) 0.020 ms/op
Iteration   2: 3.927 ±(99.9%) 0.023 ms/op
Iteration   3: 3.875 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.925 ±(99.9%) 0.888 ms/op [Average]
  (min, avg, max) = (3.875, 3.925, 3.972), stdev = 0.049
  CI (99.9%): [3.037, 4.813] (assumes normal distribution)


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  11.973 ms/op
                 createUser·p0.9999: 15.189 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  7.863 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  10.744 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309915
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19708 
    [ 2.500,  5.000) = 287980 
    [ 5.000,  7.500) = 1596 
    [ 7.500, 10.000) = 237 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     11.534 ms/op
     p(99.9900) =     21.824 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
Iteration   1: 2.851 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.119 ms/op
                 existUser·p0.999:  8.322 ms/op
                 existUser·p0.9999: 12.956 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   2: 2.935 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  8.117 ms/op
                 existUser·p0.9999: 15.340 ms/op
                 existUser·p1.00:   15.909 ms/op

Iteration   3: 2.879 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  8.636 ms/op
                 existUser·p0.9999: 16.693 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332511
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2604 
    [ 1.250,  2.500) = 36632 
    [ 2.500,  3.750) = 284882 
    [ 3.750,  5.000) = 6848 
    [ 5.000,  6.250) = 677 
    [ 6.250,  7.500) = 333 
    [ 7.500,  8.750) = 306 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.311 ms/op
     p(99.9900) =     15.700 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.089 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.479 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.792 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 12.872 ms/op
                 getUser·p1.00:   13.189 ms/op

Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.595 ms/op
                 getUser·p0.999:  8.729 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  9.679 ms/op
                 getUser·p0.9999: 18.305 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312706
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 874 
    [ 1.250,  2.500) = 17942 
    [ 2.500,  3.750) = 275597 
    [ 3.750,  5.000) = 15433 
    [ 5.000,  6.250) = 1359 
    [ 6.250,  7.500) = 622 
    [ 7.500,  8.750) = 427 
    [ 8.750, 10.000) = 178 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     19.423 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 5.285 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.301 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.011 ms/op
Iteration   1: 3.949 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 16.902 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   2: 3.997 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.717 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  22.517 ms/op
                 listUser·p0.9999: 26.378 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242424
  mean =      3.958 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2293 
    [ 2.500,  5.000) = 219231 
    [ 5.000,  7.500) = 19374 
    [ 7.500, 10.000) = 999 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     16.314 ms/op
     p(99.9900) =     25.813 ms/op
     p(99.9990) =     27.811 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.141 ± 1.203  ops/ms
ClientGrpc.existUser                       thrpt       3  11.154 ± 4.548  ops/ms
ClientGrpc.getUser                         thrpt       3  10.552 ± 1.419  ops/ms
ClientGrpc.listUser                        thrpt       3   8.001 ± 2.324  ops/ms
ClientGrpc.createUser                       avgt       3   3.060 ± 0.565   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.203   ms/op
ClientGrpc.getUser                          avgt       3   3.045 ± 0.243   ms/op
ClientGrpc.listUser                         avgt       3   3.925 ± 0.888   ms/op
ClientGrpc.createUser                     sample  309915   3.099 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.583           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.534           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.824           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.101           ms/op
ClientGrpc.existUser                      sample  332511   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.701           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.311           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.700           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.007           ms/op
ClientGrpc.getUser                        sample  312706   3.068 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.479           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.781           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.629           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.595           ms/op
ClientGrpc.listUser                       sample  242424   3.958 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.717           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.314           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.813           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.984           ms/op
