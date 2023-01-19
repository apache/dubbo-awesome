# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.823 ops/ms
# Warmup Iteration   2: 9.490 ops/ms
# Warmup Iteration   3: 10.490 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.611 ops/ms
Iteration   3: 10.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.436 ±(99.9%) 4.825 ops/ms [Average]
  (min, avg, max) = (10.132, 10.436, 10.611), stdev = 0.264
  CI (99.9%): [5.611, 15.260] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.461 ops/ms
# Warmup Iteration   2: 10.568 ops/ms
# Warmup Iteration   3: 11.168 ops/ms
Iteration   1: 11.306 ops/ms
Iteration   2: 11.160 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.115 ±(99.9%) 3.964 ops/ms [Average]
  (min, avg, max) = (10.878, 11.115, 11.306), stdev = 0.217
  CI (99.9%): [7.151, 15.078] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.674 ops/ms
# Warmup Iteration   2: 10.305 ops/ms
# Warmup Iteration   3: 10.517 ops/ms
Iteration   1: 10.453 ops/ms
Iteration   2: 10.646 ops/ms
Iteration   3: 10.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.464 ±(99.9%) 3.223 ops/ms [Average]
  (min, avg, max) = (10.293, 10.464, 10.646), stdev = 0.177
  CI (99.9%): [7.241, 13.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.321 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.103 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 8.162 ops/ms
Iteration   3: 7.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.058 ±(99.9%) 2.938 ops/ms [Average]
  (min, avg, max) = (7.873, 8.058, 8.162), stdev = 0.161
  CI (99.9%): [5.121, 10.996] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.055 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.111 ±(99.9%) 0.002 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.115 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (3.111, 3.115, 3.124), stdev = 0.007
  CI (99.9%): [2.986, 3.245] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.550 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.905 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.003 ms/op
Iteration   1: 2.941 ±(99.9%) 0.002 ms/op
Iteration   2: 2.932 ±(99.9%) 0.004 ms/op
Iteration   3: 2.788 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.887 ±(99.9%) 1.563 ms/op [Average]
  (min, avg, max) = (2.788, 2.887, 2.941), stdev = 0.086
  CI (99.9%): [1.324, 4.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.110 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 3.006 ±(99.9%) 0.002 ms/op
Iteration   3: 3.030 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.036 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.006, 3.036, 3.070), stdev = 0.032
  CI (99.9%): [2.447, 3.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.197 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.024 ms/op
Iteration   1: 4.050 ±(99.9%) 0.011 ms/op
Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
Iteration   3: 3.825 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 2.051 ms/op [Average]
  (min, avg, max) = (3.825, 3.938, 4.050), stdev = 0.112
  CI (99.9%): [1.887, 5.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.123 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.102 ms/op
                 createUser·p0.9999: 12.883 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.583 ms/op
                 createUser·p0.9999: 12.721 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.219 ms/op
                 createUser·p0.9999: 19.202 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306942
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1319 
    [ 1.250,  2.500) = 26774 
    [ 2.500,  3.750) = 238603 
    [ 3.750,  5.000) = 39321 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 173 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =     17.770 ms/op
     p(99.9990) =     19.361 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.565 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  4.866 ms/op
                 existUser·p0.9999: 18.201 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   2: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.397 ms/op
                 existUser·p0.9999: 15.225 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  8.657 ms/op
                 existUser·p0.9999: 15.510 ms/op
                 existUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323992
  mean =      2.962 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2128 
    [ 1.250,  2.500) = 44991 
    [ 2.500,  3.750) = 259759 
    [ 3.750,  5.000) = 16358 
    [ 5.000,  6.250) = 354 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      6.504 ms/op
     p(99.9900) =     16.752 ms/op
     p(99.9990) =     18.604 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.406 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.808 ms/op
                 getUser·p0.9999: 11.321 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.549 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.243 ms/op
                 getUser·p0.9999: 12.765 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.472 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.941 ms/op
                 getUser·p0.9999: 16.024 ms/op
                 getUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315997
  mean =      3.037 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1701 
    [ 1.250,  2.500) = 25894 
    [ 2.500,  3.750) = 265345 
    [ 3.750,  5.000) = 22011 
    [ 5.000,  6.250) = 508 
    [ 6.250,  7.500) = 285 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.988 ms/op
     p(99.9900) =     14.248 ms/op
     p(99.9990) =     16.259 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.132 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.011 ms/op
Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.431 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  11.692 ms/op
                 listUser·p0.9999: 20.254 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 3.853 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.754 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 22.151 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244750
  mean =      3.920 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4841 
    [ 2.500,  5.000) = 216649 
    [ 5.000,  7.500) = 22489 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     22.070 ms/op
     p(99.9990) =     25.118 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.436 ± 4.825  ops/ms
ClientGrpc.existUser                       thrpt       3  11.115 ± 3.964  ops/ms
ClientGrpc.getUser                         thrpt       3  10.464 ± 3.223  ops/ms
ClientGrpc.listUser                        thrpt       3   8.058 ± 2.938  ops/ms
ClientGrpc.createUser                       avgt       3   3.115 ± 0.129   ms/op
ClientGrpc.existUser                        avgt       3   2.887 ± 1.563   ms/op
ClientGrpc.getUser                          avgt       3   3.036 ± 0.588   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 2.051   ms/op
ClientGrpc.createUser                     sample  306942   3.126 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.745           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.791           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.770           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.562           ms/op
ClientGrpc.existUser                      sample  323992   2.962 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.478           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.504           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.752           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  315997   3.037 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.406           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.988           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.248           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.433           ms/op
ClientGrpc.listUser                       sample  244750   3.920 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.431           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.681           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.070           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.166           ms/op
