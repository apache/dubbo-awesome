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
# Warmup Iteration   1: 3.966 ops/ms
# Warmup Iteration   2: 9.385 ops/ms
# Warmup Iteration   3: 10.327 ops/ms
Iteration   1: 10.753 ops/ms
Iteration   2: 10.662 ops/ms
Iteration   3: 10.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.723 ±(99.9%) 0.965 ops/ms [Average]
  (min, avg, max) = (10.662, 10.723, 10.754), stdev = 0.053
  CI (99.9%): [9.757, 11.688] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.201 ops/ms
# Warmup Iteration   2: 10.387 ops/ms
# Warmup Iteration   3: 10.772 ops/ms
Iteration   1: 11.191 ops/ms
Iteration   2: 11.191 ops/ms
Iteration   3: 11.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.252 ±(99.9%) 1.925 ops/ms [Average]
  (min, avg, max) = (11.191, 11.252, 11.374), stdev = 0.106
  CI (99.9%): [9.327, 13.177] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.950 ops/ms
# Warmup Iteration   2: 10.239 ops/ms
# Warmup Iteration   3: 10.797 ops/ms
Iteration   1: 10.728 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.692 ±(99.9%) 1.603 ops/ms [Average]
  (min, avg, max) = (10.591, 10.692, 10.755), stdev = 0.088
  CI (99.9%): [9.089, 12.294] (assumes normal distribution)


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
# Warmup Iteration   1: 5.273 ops/ms
# Warmup Iteration   2: 7.829 ops/ms
# Warmup Iteration   3: 8.208 ops/ms
Iteration   1: 8.330 ops/ms
Iteration   2: 8.129 ops/ms
Iteration   3: 8.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.250 ±(99.9%) 1.940 ops/ms [Average]
  (min, avg, max) = (8.129, 8.250, 8.330), stdev = 0.106
  CI (99.9%): [6.310, 10.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.002 ms/op
Iteration   1: 2.965 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.002 ms/op
Iteration   3: 3.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.006 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (2.965, 3.006, 3.036), stdev = 0.037
  CI (99.9%): [2.330, 3.682] (assumes normal distribution)


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.003 ms/op
Iteration   1: 2.916 ±(99.9%) 0.003 ms/op
Iteration   2: 2.870 ±(99.9%) 0.002 ms/op
Iteration   3: 2.968 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.918 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (2.870, 2.918, 2.968), stdev = 0.049
  CI (99.9%): [2.026, 3.810] (assumes normal distribution)


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.003 ms/op
Iteration   1: 2.985 ±(99.9%) 0.004 ms/op
Iteration   2: 3.006 ±(99.9%) 0.004 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.998 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (2.985, 2.998, 3.006), stdev = 0.011
  CI (99.9%): [2.803, 3.193] (assumes normal distribution)


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
# Warmup Iteration   1: 5.508 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.022 ms/op
Iteration   1: 3.861 ±(99.9%) 0.028 ms/op
Iteration   2: 3.878 ±(99.9%) 0.015 ms/op
Iteration   3: 3.852 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.863 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (3.852, 3.863, 3.878), stdev = 0.013
  CI (99.9%): [3.624, 4.103] (assumes normal distribution)


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.372 ms/op
                 createUser·p0.9999: 17.695 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.478 ms/op
                 createUser·p0.999:  9.282 ms/op
                 createUser·p0.9999: 14.682 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  6.868 ms/op
                 createUser·p0.9999: 16.253 ms/op
                 createUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318936
  mean =      3.009 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 518 
    [ 1.250,  2.500) = 27426 
    [ 2.500,  3.750) = 277638 
    [ 3.750,  5.000) = 12059 
    [ 5.000,  6.250) = 643 
    [ 6.250,  7.500) = 241 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 88 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     17.177 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
Iteration   1: 2.904 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  7.240 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   11.911 ms/op

Iteration   2: 2.902 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  6.233 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  7.294 ms/op
                 existUser·p0.9999: 16.498 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330880
  mean =      2.899 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 654 
    [ 1.250,  2.500) = 37441 
    [ 2.500,  3.750) = 285708 
    [ 3.750,  5.000) = 6149 
    [ 5.000,  6.250) = 490 
    [ 6.250,  7.500) = 203 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      6.882 ms/op
     p(99.9900) =     15.743 ms/op
     p(99.9990) =     16.823 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.353 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.987 ms/op
                 getUser·p0.9999: 17.808 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.447 ms/op
                 getUser·p0.9999: 18.113 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.580 ms/op
                 getUser·p0.9999: 19.869 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318133
  mean =      3.016 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20071 
    [ 2.500,  5.000) = 296521 
    [ 5.000,  7.500) = 1217 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.536 ms/op
     p(99.9900) =     19.372 ms/op
     p(99.9990) =     20.140 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 4.918 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.010 ms/op
Iteration   1: 3.858 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 20.864 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.546 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  15.886 ms/op
                 listUser·p0.9999: 18.910 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 3.865 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.657 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 23.116 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248701
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2571 
    [ 2.500,  5.000) = 228707 
    [ 5.000,  7.500) = 16333 
    [ 7.500, 10.000) = 641 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     16.984 ms/op
     p(99.9900) =     22.418 ms/op
     p(99.9990) =     23.266 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.723 ± 0.965  ops/ms
ClientGrpc.existUser                       thrpt       3  11.252 ± 1.925  ops/ms
ClientGrpc.getUser                         thrpt       3  10.692 ± 1.603  ops/ms
ClientGrpc.listUser                        thrpt       3   8.250 ± 1.940  ops/ms
ClientGrpc.createUser                       avgt       3   3.006 ± 0.676   ms/op
ClientGrpc.existUser                        avgt       3   2.918 ± 0.892   ms/op
ClientGrpc.getUser                          avgt       3   2.998 ± 0.195   ms/op
ClientGrpc.listUser                         avgt       3   3.863 ± 0.240   ms/op
ClientGrpc.createUser                     sample  318936   3.009 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.728           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.241           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.177           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.924           ms/op
ClientGrpc.existUser                      sample  330880   2.899 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.494           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.882           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.743           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.039           ms/op
ClientGrpc.getUser                        sample  318133   3.016 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.852           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.536           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.372           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  248701   3.857 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.546           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.984           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.418           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.429           ms/op
