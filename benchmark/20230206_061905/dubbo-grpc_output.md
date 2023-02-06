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
# Warmup Iteration   1: 5.065 ops/ms
# Warmup Iteration   2: 9.653 ops/ms
# Warmup Iteration   3: 10.549 ops/ms
Iteration   1: 10.335 ops/ms
Iteration   2: 10.819 ops/ms
Iteration   3: 9.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.349 ±(99.9%) 8.451 ops/ms [Average]
  (min, avg, max) = (9.893, 10.349, 10.819), stdev = 0.463
  CI (99.9%): [1.898, 18.801] (assumes normal distribution)


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
# Warmup Iteration   1: 7.954 ops/ms
# Warmup Iteration   2: 10.798 ops/ms
# Warmup Iteration   3: 11.355 ops/ms
Iteration   1: 10.958 ops/ms
Iteration   2: 11.171 ops/ms
Iteration   3: 10.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.011 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (10.904, 11.011, 11.171), stdev = 0.142
  CI (99.9%): [8.430, 13.593] (assumes normal distribution)


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
# Warmup Iteration   1: 7.176 ops/ms
# Warmup Iteration   2: 10.587 ops/ms
# Warmup Iteration   3: 10.678 ops/ms
Iteration   1: 10.638 ops/ms
Iteration   2: 10.577 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.623 ±(99.9%) 0.743 ops/ms [Average]
  (min, avg, max) = (10.577, 10.623, 10.655), stdev = 0.041
  CI (99.9%): [9.880, 11.367] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.961 ops/ms
# Warmup Iteration   2: 7.834 ops/ms
# Warmup Iteration   3: 7.852 ops/ms
Iteration   1: 8.092 ops/ms
Iteration   2: 8.371 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.250 ±(99.9%) 2.614 ops/ms [Average]
  (min, avg, max) = (8.092, 8.250, 8.371), stdev = 0.143
  CI (99.9%): [5.636, 10.864] (assumes normal distribution)


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.002 ms/op
Iteration   1: 3.125 ±(99.9%) 0.003 ms/op
Iteration   2: 3.108 ±(99.9%) 0.001 ms/op
Iteration   3: 3.045 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.093 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.045, 3.093, 3.125), stdev = 0.042
  CI (99.9%): [2.323, 3.863] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.736 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 2.918 ±(99.9%) 0.004 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 2.950 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.960 ±(99.9%) 0.870 ms/op [Average]
  (min, avg, max) = (2.918, 2.960, 3.012), stdev = 0.048
  CI (99.9%): [2.090, 3.830] (assumes normal distribution)


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.002 ms/op
Iteration   1: 3.383 ±(99.9%) 0.003 ms/op
Iteration   2: 3.388 ±(99.9%) 0.003 ms/op
Iteration   3: 3.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.400 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.383, 3.400, 3.430), stdev = 0.026
  CI (99.9%): [2.928, 3.873] (assumes normal distribution)


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
# Warmup Iteration   1: 6.190 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.375 ±(99.9%) 0.016 ms/op
Iteration   1: 4.235 ±(99.9%) 0.011 ms/op
Iteration   2: 4.181 ±(99.9%) 0.014 ms/op
Iteration   3: 4.339 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.252 ±(99.9%) 1.470 ms/op [Average]
  (min, avg, max) = (4.181, 4.252, 4.339), stdev = 0.081
  CI (99.9%): [2.782, 5.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
Iteration   1: 3.009 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.493 ms/op
                 createUser·p0.999:  6.838 ms/op
                 createUser·p0.9999: 16.472 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  14.591 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309449
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26734 
    [ 2.500,  5.000) = 281520 
    [ 5.000,  7.500) = 795 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     10.276 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     23.950 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.422 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.045 ms/op
                 existUser·p0.9999: 14.483 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.030 ms/op
                 existUser·p0.9999: 14.425 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  6.622 ms/op
                 existUser·p0.9999: 17.105 ms/op
                 existUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323437
  mean =      2.969 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2485 
    [ 1.250,  2.500) = 35812 
    [ 2.500,  3.750) = 269203 
    [ 3.750,  5.000) = 15093 
    [ 5.000,  6.250) = 439 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     15.559 ms/op
     p(99.9990) =     17.228 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.430 ms/op
                 getUser·p0.9999: 12.709 ms/op
                 getUser·p1.00:   13.189 ms/op

Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.336 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.463 ms/op
                 getUser·p0.9999: 13.561 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.407 ms/op
                 getUser·p0.9999: 25.580 ms/op
                 getUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308246
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20516 
    [ 2.500,  5.000) = 286819 
    [ 5.000,  7.500) = 670 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.828 ms/op
     p(99.9900) =     23.435 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.011 ms/op
Iteration   1: 4.080 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  11.896 ms/op
                 listUser·p0.9999: 15.573 ms/op
                 listUser·p1.00:   15.876 ms/op

Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.170 ms/op
                 listUser·p0.9999: 18.556 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 4.018 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 30.218 ms/op
                 listUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237075
  mean =      4.048 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2496 
    [ 2.500,  5.000) = 206531 
    [ 5.000,  7.500) = 26594 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     15.219 ms/op
     p(99.9900) =     29.206 ms/op
     p(99.9990) =     32.847 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.349 ± 8.451  ops/ms
ClientGrpc.existUser                       thrpt       3  11.011 ± 2.582  ops/ms
ClientGrpc.getUser                         thrpt       3  10.623 ± 0.743  ops/ms
ClientGrpc.listUser                        thrpt       3   8.250 ± 2.614  ops/ms
ClientGrpc.createUser                       avgt       3   3.093 ± 0.770   ms/op
ClientGrpc.existUser                        avgt       3   2.960 ± 0.870   ms/op
ClientGrpc.getUser                          avgt       3   3.400 ± 0.473   ms/op
ClientGrpc.listUser                         avgt       3   4.252 ± 1.470   ms/op
ClientGrpc.createUser                     sample  309449   3.101 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.555           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.276           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.955           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  323437   2.969 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.422           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.963           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.559           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.302           ms/op
ClientGrpc.getUser                        sample  308246   3.112 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.336           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.828           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.435           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.756           ms/op
ClientGrpc.listUser                       sample  237075   4.048 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.869           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.219           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.206           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.030           ms/op
