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
# Warmup Iteration   1: 3.647 ops/ms
# Warmup Iteration   2: 8.447 ops/ms
# Warmup Iteration   3: 9.988 ops/ms
Iteration   1: 10.226 ops/ms
Iteration   2: 10.367 ops/ms
Iteration   3: 10.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.329 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (10.226, 10.329, 10.393), stdev = 0.090
  CI (99.9%): [8.695, 11.962] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.460 ops/ms
# Warmup Iteration   2: 10.213 ops/ms
# Warmup Iteration   3: 10.828 ops/ms
Iteration   1: 11.008 ops/ms
Iteration   2: 10.939 ops/ms
Iteration   3: 10.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.935 ±(99.9%) 1.384 ops/ms [Average]
  (min, avg, max) = (10.857, 10.935, 11.008), stdev = 0.076
  CI (99.9%): [9.550, 12.319] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.698 ops/ms
# Warmup Iteration   2: 9.748 ops/ms
# Warmup Iteration   3: 10.290 ops/ms
Iteration   1: 10.319 ops/ms
Iteration   2: 10.521 ops/ms
Iteration   3: 10.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.385 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (10.316, 10.385, 10.521), stdev = 0.117
  CI (99.9%): [8.245, 12.525] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.378 ops/ms
# Warmup Iteration   2: 7.723 ops/ms
# Warmup Iteration   3: 7.921 ops/ms
Iteration   1: 7.857 ops/ms
Iteration   2: 7.872 ops/ms
Iteration   3: 8.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.973 ±(99.9%) 3.429 ops/ms [Average]
  (min, avg, max) = (7.857, 7.973, 8.190), stdev = 0.188
  CI (99.9%): [4.544, 11.401] (assumes normal distribution)


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
# Warmup Iteration   1: 4.651 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.002 ms/op
Iteration   1: 3.084 ±(99.9%) 0.004 ms/op
Iteration   2: 3.102 ±(99.9%) 0.002 ms/op
Iteration   3: 3.079 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.088 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.079, 3.088, 3.102), stdev = 0.012
  CI (99.9%): [2.865, 3.311] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 2.963 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.963, 2.974, 2.984), stdev = 0.010
  CI (99.9%): [2.783, 3.165] (assumes normal distribution)


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.003 ms/op
Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
Iteration   3: 3.045 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.063 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (3.045, 3.063, 3.091), stdev = 0.024
  CI (99.9%): [2.621, 3.506] (assumes normal distribution)


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
# Warmup Iteration   1: 5.942 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.019 ms/op
Iteration   1: 4.006 ±(99.9%) 0.024 ms/op
Iteration   2: 4.015 ±(99.9%) 0.013 ms/op
Iteration   3: 3.981 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.001 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (3.981, 4.001, 4.015), stdev = 0.017
  CI (99.9%): [3.682, 4.320] (assumes normal distribution)


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
# Warmup Iteration   1: 4.571 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
Iteration   1: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.406 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.643 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.117 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  12.978 ms/op
                 createUser·p0.9999: 32.257 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311717
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15293 
    [ 2.500,  5.000) = 294960 
    [ 5.000,  7.500) = 1076 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.994 ms/op
     p(99.9900) =     30.660 ms/op
     p(99.9990) =     32.728 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.606 ms/op
                 existUser·p0.9999: 15.436 ms/op
                 existUser·p1.00:   15.909 ms/op

Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  7.021 ms/op
                 existUser·p0.9999: 15.221 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  8.877 ms/op
                 existUser·p0.9999: 16.630 ms/op
                 existUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322909
  mean =      2.972 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 942 
    [ 1.250,  2.500) = 27032 
    [ 2.500,  3.750) = 284277 
    [ 3.750,  5.000) = 9466 
    [ 5.000,  6.250) = 733 
    [ 6.250,  7.500) = 134 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 87 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      7.520 ms/op
     p(99.9900) =     15.974 ms/op
     p(99.9990) =     16.791 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 4.460 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.633 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 13.463 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.112 ms/op
                 getUser·p0.9999: 14.550 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.372 ms/op
                 getUser·p0.9999: 29.803 ms/op
                 getUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312499
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15936 
    [ 2.500,  5.000) = 294914 
    [ 5.000,  7.500) = 1225 
    [ 7.500, 10.000) = 218 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     28.475 ms/op
     p(99.9990) =     30.208 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 5.224 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.011 ms/op
Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  14.543 ms/op
                 listUser·p0.9999: 21.042 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   2: 4.011 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 25.953 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   3: 4.057 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 22.260 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238173
  mean =      4.031 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2686 
    [ 2.500,  5.000) = 211712 
    [ 5.000,  7.500) = 22117 
    [ 7.500, 10.000) = 1159 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     24.573 ms/op
     p(99.9990) =     26.373 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.329 ± 1.633  ops/ms
ClientGrpc.existUser                       thrpt       3  10.935 ± 1.384  ops/ms
ClientGrpc.getUser                         thrpt       3  10.385 ± 2.140  ops/ms
ClientGrpc.listUser                        thrpt       3   7.973 ± 3.429  ops/ms
ClientGrpc.createUser                       avgt       3   3.088 ± 0.223   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.191   ms/op
ClientGrpc.getUser                          avgt       3   3.063 ± 0.443   ms/op
ClientGrpc.listUser                         avgt       3   4.001 ± 0.319   ms/op
ClientGrpc.createUser                     sample  311717   3.081 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.854           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.994           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.660           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.882           ms/op
ClientGrpc.existUser                      sample  322909   2.972 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.498           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.520           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.974           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.596           ms/op
ClientGrpc.getUser                        sample  312499   3.074 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.611           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.475           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.212           ms/op
ClientGrpc.listUser                       sample  238173   4.031 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.894           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.596           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.573           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.509           ms/op
