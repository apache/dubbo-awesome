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
# Warmup Iteration   1: 3.989 ops/ms
# Warmup Iteration   2: 9.046 ops/ms
# Warmup Iteration   3: 10.124 ops/ms
Iteration   1: 10.486 ops/ms
Iteration   2: 10.717 ops/ms
Iteration   3: 10.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.591 ±(99.9%) 2.127 ops/ms [Average]
  (min, avg, max) = (10.486, 10.591, 10.717), stdev = 0.117
  CI (99.9%): [8.465, 12.718] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.435 ops/ms
# Warmup Iteration   2: 10.626 ops/ms
# Warmup Iteration   3: 10.904 ops/ms
Iteration   1: 11.013 ops/ms
Iteration   2: 10.929 ops/ms
Iteration   3: 11.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.190 ±(99.9%) 6.951 ops/ms [Average]
  (min, avg, max) = (10.929, 11.190, 11.627), stdev = 0.381
  CI (99.9%): [4.238, 18.141] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.874 ops/ms
# Warmup Iteration   2: 9.942 ops/ms
# Warmup Iteration   3: 10.329 ops/ms
Iteration   1: 10.596 ops/ms
Iteration   2: 10.516 ops/ms
Iteration   3: 10.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.614 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (10.516, 10.614, 10.731), stdev = 0.109
  CI (99.9%): [8.631, 12.598] (assumes normal distribution)


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
# Warmup Iteration   1: 5.693 ops/ms
# Warmup Iteration   2: 7.780 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 8.193 ops/ms
Iteration   2: 8.276 ops/ms
Iteration   3: 8.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.216 ±(99.9%) 0.941 ops/ms [Average]
  (min, avg, max) = (8.181, 8.216, 8.276), stdev = 0.052
  CI (99.9%): [7.275, 9.157] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.002 ms/op
Iteration   1: 3.060 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
Iteration   3: 3.066 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.070 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (3.060, 3.070, 3.082), stdev = 0.011
  CI (99.9%): [2.861, 3.279] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.004 ms/op
Iteration   1: 2.881 ±(99.9%) 0.002 ms/op
Iteration   2: 2.885 ±(99.9%) 0.002 ms/op
Iteration   3: 2.865 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.877 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.865, 2.877, 2.885), stdev = 0.010
  CI (99.9%): [2.689, 3.065] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.300 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 2.999 ±(99.9%) 0.004 ms/op
Iteration   3: 3.071 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (2.999, 3.043, 3.071), stdev = 0.039
  CI (99.9%): [2.335, 3.751] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.376 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
Iteration   1: 3.954 ±(99.9%) 0.014 ms/op
Iteration   2: 3.878 ±(99.9%) 0.021 ms/op
Iteration   3: 3.893 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.908 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (3.878, 3.908, 3.954), stdev = 0.040
  CI (99.9%): [3.175, 4.642] (assumes normal distribution)


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.842 ms/op
                 createUser·p0.9999: 19.850 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  11.486 ms/op
                 createUser·p0.9999: 20.238 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   3: 3.074 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  16.630 ms/op
                 createUser·p0.9999: 20.073 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314269
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20356 
    [ 2.500,  5.000) = 292267 
    [ 5.000,  7.500) = 1140 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     11.640 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     21.393 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.854 ms/op
                 existUser·p0.9999: 13.341 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   2: 2.912 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.673 ms/op
                 existUser·p0.9999: 22.447 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  8.283 ms/op
                 existUser·p0.9999: 16.515 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327763
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33079 
    [ 2.500,  5.000) = 293600 
    [ 5.000,  7.500) = 793 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.936 ms/op
     p(99.9900) =     19.739 ms/op
     p(99.9990) =     22.765 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 2.988 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.357 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.273 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.528 ms/op
                 getUser·p0.9999: 15.691 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.386 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.980 ms/op
                 getUser·p0.9999: 18.403 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320347
  mean =      2.996 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28641 
    [ 2.500,  5.000) = 290018 
    [ 5.000,  7.500) = 1294 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.020 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     20.827 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 5.663 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.012 ms/op
Iteration   1: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.942 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 20.763 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 3.911 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  16.486 ms/op
                 listUser·p0.9999: 20.867 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.342 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.835 ms/op
                 listUser·p0.999:  15.957 ms/op
                 listUser·p0.9999: 37.224 ms/op
                 listUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244084
  mean =      3.932 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4234 
    [ 2.500,  5.000) = 218430 
    [ 5.000,  7.500) = 20081 
    [ 7.500, 10.000) = 886 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     32.151 ms/op
     p(99.9990) =     37.327 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.591 ± 2.127  ops/ms
ClientGrpc.existUser                       thrpt       3  11.190 ± 6.951  ops/ms
ClientGrpc.getUser                         thrpt       3  10.614 ± 1.984  ops/ms
ClientGrpc.listUser                        thrpt       3   8.216 ± 0.941  ops/ms
ClientGrpc.createUser                       avgt       3   3.070 ± 0.209   ms/op
ClientGrpc.existUser                        avgt       3   2.877 ± 0.188   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.708   ms/op
ClientGrpc.listUser                         avgt       3   3.908 ± 0.733   ms/op
ClientGrpc.createUser                     sample  314269   3.053 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.639           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.640           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.054           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.020           ms/op
ClientGrpc.existUser                      sample  327763   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.440           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.936           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.739           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.839           ms/op
ClientGrpc.getUser                        sample  320347   2.996 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.357           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.020           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.988           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.873           ms/op
ClientGrpc.listUser                       sample  244084   3.932 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.342           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.532           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.151           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.683           ms/op
