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
# Warmup Iteration   1: 3.633 ops/ms
# Warmup Iteration   2: 8.385 ops/ms
# Warmup Iteration   3: 10.132 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.278 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.489 ±(99.9%) 3.487 ops/ms [Average]
  (min, avg, max) = (10.278, 10.489, 10.651), stdev = 0.191
  CI (99.9%): [7.002, 13.976] (assumes normal distribution)


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
# Warmup Iteration   1: 7.186 ops/ms
# Warmup Iteration   2: 10.889 ops/ms
# Warmup Iteration   3: 11.117 ops/ms
Iteration   1: 11.337 ops/ms
Iteration   2: 11.543 ops/ms
Iteration   3: 11.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.439 ±(99.9%) 1.888 ops/ms [Average]
  (min, avg, max) = (11.337, 11.439, 11.543), stdev = 0.103
  CI (99.9%): [9.551, 13.327] (assumes normal distribution)


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
# Warmup Iteration   1: 6.261 ops/ms
# Warmup Iteration   2: 10.183 ops/ms
# Warmup Iteration   3: 10.430 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.747 ops/ms
Iteration   3: 10.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.624 ±(99.9%) 2.006 ops/ms [Average]
  (min, avg, max) = (10.535, 10.624, 10.747), stdev = 0.110
  CI (99.9%): [8.618, 12.630] (assumes normal distribution)


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
# Warmup Iteration   1: 5.738 ops/ms
# Warmup Iteration   2: 7.726 ops/ms
# Warmup Iteration   3: 7.931 ops/ms
Iteration   1: 7.978 ops/ms
Iteration   2: 7.967 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.010 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (7.967, 8.010, 8.086), stdev = 0.066
  CI (99.9%): [6.808, 9.213] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 2.915 ±(99.9%) 0.002 ms/op
Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
Iteration   3: 2.990 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.971 ±(99.9%) 0.888 ms/op [Average]
  (min, avg, max) = (2.915, 2.971, 3.007), stdev = 0.049
  CI (99.9%): [2.083, 3.858] (assumes normal distribution)


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.899 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.759 ±(99.9%) 0.003 ms/op
Iteration   1: 2.821 ±(99.9%) 0.002 ms/op
Iteration   2: 2.828 ±(99.9%) 0.002 ms/op
Iteration   3: 2.779 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.809 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (2.779, 2.809, 2.828), stdev = 0.027
  CI (99.9%): [2.320, 3.299] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.003 ms/op
Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.006 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (3.000, 3.006, 3.014), stdev = 0.007
  CI (99.9%): [2.879, 3.133] (assumes normal distribution)


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.020 ms/op
Iteration   1: 3.843 ±(99.9%) 0.019 ms/op
Iteration   2: 3.616 ±(99.9%) 0.027 ms/op
Iteration   3: 3.622 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.694 ±(99.9%) 2.360 ms/op [Average]
  (min, avg, max) = (3.616, 3.694, 3.843), stdev = 0.129
  CI (99.9%): [1.334, 6.054] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.625 ms/op
                 createUser·p0.999:  7.791 ms/op
                 createUser·p0.9999: 14.385 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.759 ms/op
                 createUser·p0.9999: 15.459 ms/op
                 createUser·p1.00:   15.712 ms/op

Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  15.598 ms/op
                 createUser·p0.9999: 17.061 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315102
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 474 
    [ 1.250,  2.500) = 22943 
    [ 2.500,  3.750) = 273666 
    [ 3.750,  5.000) = 15866 
    [ 5.000,  6.250) = 923 
    [ 6.250,  7.500) = 439 
    [ 7.500,  8.750) = 330 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 111 
    [15.000, 16.250) = 96 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     11.646 ms/op
     p(99.9900) =     16.736 ms/op
     p(99.9990) =     17.428 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.781 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.783 ±(99.9%) 0.005 ms/op
Iteration   1: 2.720 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   2.699 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  7.436 ms/op
                 existUser·p0.9999: 12.263 ms/op
                 existUser·p1.00:   12.517 ms/op

Iteration   2: 2.860 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.308 ms/op
                 existUser·p0.9999: 14.713 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   3: 2.896 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  9.570 ms/op
                 existUser·p0.9999: 17.759 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340002
  mean =      2.823 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2418 
    [ 1.250,  2.500) = 68455 
    [ 2.500,  3.750) = 257551 
    [ 3.750,  5.000) = 9477 
    [ 5.000,  6.250) = 1033 
    [ 6.250,  7.500) = 566 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     15.532 ms/op
     p(99.9990) =     17.878 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.007 ms/op
Iteration   1: 2.866 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   2.834 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  11.069 ms/op
                 getUser·p0.9999: 19.940 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  10.285 ms/op
                 getUser·p0.9999: 18.104 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  6.944 ms/op
                 getUser·p0.9999: 21.201 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322049
  mean =      2.980 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39659 
    [ 2.500,  5.000) = 279481 
    [ 5.000,  7.500) = 2211 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =     10.108 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 5.074 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.012 ms/op
Iteration   1: 3.944 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.069 ms/op
                 listUser·p0.9999: 19.654 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.864 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 17.832 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.878 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.378 ms/op
                 listUser·p0.9999: 22.078 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246245
  mean =      3.895 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4127 
    [ 2.500,  5.000) = 219233 
    [ 5.000,  7.500) = 21383 
    [ 7.500, 10.000) = 1062 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     21.508 ms/op
     p(99.9990) =     22.333 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.489 ± 3.487  ops/ms
ClientGrpc.existUser                       thrpt       3  11.439 ± 1.888  ops/ms
ClientGrpc.getUser                         thrpt       3  10.624 ± 2.006  ops/ms
ClientGrpc.listUser                        thrpt       3   8.010 ± 1.202  ops/ms
ClientGrpc.createUser                       avgt       3   2.971 ± 0.888   ms/op
ClientGrpc.existUser                        avgt       3   2.809 ± 0.489   ms/op
ClientGrpc.getUser                          avgt       3   3.006 ± 0.127   ms/op
ClientGrpc.listUser                         avgt       3   3.694 ± 2.360   ms/op
ClientGrpc.createUser                     sample  315102   3.047 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.749           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.646           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.736           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.317           ms/op
ClientGrpc.existUser                      sample  340002   2.823 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.557           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.777           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.532           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  322049   2.980 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.561           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.108           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.578           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.446           ms/op
ClientGrpc.listUser                       sample  246245   3.895 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.996           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.270           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.508           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
