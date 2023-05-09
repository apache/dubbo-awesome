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
# Warmup Iteration   1: 4.552 ops/ms
# Warmup Iteration   2: 9.236 ops/ms
# Warmup Iteration   3: 10.538 ops/ms
Iteration   1: 10.781 ops/ms
Iteration   2: 10.611 ops/ms
Iteration   3: 10.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.709 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (10.611, 10.709, 10.781), stdev = 0.088
  CI (99.9%): [9.103, 12.315] (assumes normal distribution)


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
# Warmup Iteration   1: 7.931 ops/ms
# Warmup Iteration   2: 11.146 ops/ms
# Warmup Iteration   3: 11.536 ops/ms
Iteration   1: 11.335 ops/ms
Iteration   2: 11.341 ops/ms
Iteration   3: 11.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.394 ±(99.9%) 1.782 ops/ms [Average]
  (min, avg, max) = (11.335, 11.394, 11.507), stdev = 0.098
  CI (99.9%): [9.613, 13.176] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.824 ops/ms
# Warmup Iteration   2: 10.525 ops/ms
# Warmup Iteration   3: 10.855 ops/ms
Iteration   1: 10.807 ops/ms
Iteration   2: 10.854 ops/ms
Iteration   3: 10.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.840 ±(99.9%) 0.534 ops/ms [Average]
  (min, avg, max) = (10.807, 10.840, 10.861), stdev = 0.029
  CI (99.9%): [10.306, 11.374] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.902 ops/ms
# Warmup Iteration   2: 8.662 ops/ms
# Warmup Iteration   3: 8.235 ops/ms
Iteration   1: 8.320 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.316 ±(99.9%) 0.281 ops/ms [Average]
  (min, avg, max) = (8.299, 8.316, 8.329), stdev = 0.015
  CI (99.9%): [8.034, 8.597] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.003 ms/op
Iteration   1: 2.967 ±(99.9%) 0.002 ms/op
Iteration   2: 2.931 ±(99.9%) 0.002 ms/op
Iteration   3: 2.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.937 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (2.913, 2.937, 2.967), stdev = 0.027
  CI (99.9%): [2.437, 3.438] (assumes normal distribution)


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.881 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.774 ±(99.9%) 0.004 ms/op
Iteration   1: 2.852 ±(99.9%) 0.002 ms/op
Iteration   2: 2.811 ±(99.9%) 0.003 ms/op
Iteration   3: 2.786 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.816 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (2.786, 2.816, 2.852), stdev = 0.033
  CI (99.9%): [2.211, 3.421] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.002 ms/op
Iteration   1: 2.931 ±(99.9%) 0.002 ms/op
Iteration   2: 2.910 ±(99.9%) 0.003 ms/op
Iteration   3: 2.956 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.932 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (2.910, 2.932, 2.956), stdev = 0.023
  CI (99.9%): [2.511, 3.354] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.487 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.013 ms/op
Iteration   1: 3.835 ±(99.9%) 0.006 ms/op
Iteration   2: 3.833 ±(99.9%) 0.033 ms/op
Iteration   3: 3.834 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.834 ±(99.9%) 0.020 ms/op [Average]
  (min, avg, max) = (3.833, 3.834, 3.835), stdev = 0.001
  CI (99.9%): [3.814, 3.854] (assumes normal distribution)


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.260 ms/op
                 createUser·p0.95:   3.449 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  6.201 ms/op
                 createUser·p0.9999: 22.024 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   2: 2.937 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  6.054 ms/op
                 createUser·p0.9999: 12.587 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.461 ms/op
                 createUser·p0.99:   4.049 ms/op
                 createUser·p0.999:  7.184 ms/op
                 createUser·p0.9999: 24.938 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 327361
  mean =      2.932 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23741 
    [ 2.500,  5.000) = 302576 
    [ 5.000,  7.500) = 783 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.486 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      6.294 ms/op
     p(99.9900) =     22.509 ms/op
     p(99.9990) =     25.190 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 2.899 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.833 ±(99.9%) 0.006 ms/op
Iteration   1: 2.828 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.265 ms/op
                 existUser·p0.9999: 11.060 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   2: 2.825 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.561 ms/op
                 existUser·p0.9999: 14.955 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   3: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  7.440 ms/op
                 existUser·p0.9999: 22.602 ms/op
                 existUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337744
  mean =      2.843 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57507 
    [ 2.500,  5.000) = 279251 
    [ 5.000,  7.500) = 706 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.662 ms/op
     p(99.9900) =     15.752 ms/op
     p(99.9990) =     23.326 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.683 ms/op
                 getUser·p0.9999: 10.867 ms/op
                 getUser·p1.00:   11.059 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.527 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.692 ms/op
                 getUser·p0.9999: 12.863 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.258 ms/op
                 getUser·p0.9999: 15.159 ms/op
                 getUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325741
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2790 
    [ 1.250,  2.500) = 28033 
    [ 2.500,  3.750) = 281157 
    [ 3.750,  5.000) = 12573 
    [ 5.000,  6.250) = 749 
    [ 6.250,  7.500) = 198 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.586 ms/op
     p(99.9900) =     13.777 ms/op
     p(99.9990) =     15.524 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.009 ms/op
Iteration   1: 3.828 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  12.975 ms/op
                 listUser·p0.9999: 18.360 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   2: 3.871 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.694 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 19.185 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.460 ms/op
                 listUser·p0.999:  13.047 ms/op
                 listUser·p0.9999: 23.351 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250017
  mean =      3.837 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3474 
    [ 2.500,  5.000) = 229228 
    [ 5.000,  7.500) = 16132 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     21.790 ms/op
     p(99.9990) =     24.346 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.709 ± 1.606  ops/ms
ClientGrpc.existUser                       thrpt       3  11.394 ± 1.782  ops/ms
ClientGrpc.getUser                         thrpt       3  10.840 ± 0.534  ops/ms
ClientGrpc.listUser                        thrpt       3   8.316 ± 0.281  ops/ms
ClientGrpc.createUser                       avgt       3   2.937 ± 0.501   ms/op
ClientGrpc.existUser                        avgt       3   2.816 ± 0.605   ms/op
ClientGrpc.getUser                          avgt       3   2.932 ± 0.421   ms/op
ClientGrpc.listUser                         avgt       3   3.834 ± 0.020   ms/op
ClientGrpc.createUser                     sample  327361   2.932 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.637           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.929           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.314           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.294           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.509           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.297           ms/op
ClientGrpc.existUser                      sample  337744   2.843 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.826           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.662           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.752           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.429           ms/op
ClientGrpc.getUser                        sample  325741   2.946 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.527           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.586           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.777           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.630           ms/op
ClientGrpc.listUser                       sample  250017   3.837 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.694           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.795           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.790           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
