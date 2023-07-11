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
# Warmup Iteration   1: 3.930 ops/ms
# Warmup Iteration   2: 9.086 ops/ms
# Warmup Iteration   3: 9.852 ops/ms
Iteration   1: 10.305 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.416 ±(99.9%) 2.709 ops/ms [Average]
  (min, avg, max) = (10.305, 10.416, 10.585), stdev = 0.149
  CI (99.9%): [7.706, 13.125] (assumes normal distribution)


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
# Warmup Iteration   1: 7.175 ops/ms
# Warmup Iteration   2: 10.250 ops/ms
# Warmup Iteration   3: 10.831 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.778 ops/ms
Iteration   3: 11.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.813 ±(99.9%) 3.379 ops/ms [Average]
  (min, avg, max) = (10.647, 10.813, 11.013), stdev = 0.185
  CI (99.9%): [7.434, 14.192] (assumes normal distribution)


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
# Warmup Iteration   1: 6.584 ops/ms
# Warmup Iteration   2: 10.050 ops/ms
# Warmup Iteration   3: 10.314 ops/ms
Iteration   1: 10.436 ops/ms
Iteration   2: 10.385 ops/ms
Iteration   3: 10.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.404 ±(99.9%) 0.510 ops/ms [Average]
  (min, avg, max) = (10.385, 10.404, 10.436), stdev = 0.028
  CI (99.9%): [9.893, 10.914] (assumes normal distribution)


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
# Warmup Iteration   1: 5.954 ops/ms
# Warmup Iteration   2: 7.269 ops/ms
# Warmup Iteration   3: 7.595 ops/ms
Iteration   1: 7.802 ops/ms
Iteration   2: 7.854 ops/ms
Iteration   3: 7.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.829 ±(99.9%) 0.476 ops/ms [Average]
  (min, avg, max) = (7.802, 7.829, 7.854), stdev = 0.026
  CI (99.9%): [7.353, 8.305] (assumes normal distribution)


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.003 ms/op
Iteration   1: 3.101 ±(99.9%) 0.002 ms/op
Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
Iteration   3: 3.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.067 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.024, 3.067, 3.101), stdev = 0.040
  CI (99.9%): [2.344, 3.789] (assumes normal distribution)


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.002 ms/op
Iteration   1: 2.942 ±(99.9%) 0.002 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 2.813 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.913 ±(99.9%) 1.628 ms/op [Average]
  (min, avg, max) = (2.813, 2.913, 2.984), stdev = 0.089
  CI (99.9%): [1.285, 4.542] (assumes normal distribution)


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
# Warmup Iteration   1: 4.344 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.004 ms/op
Iteration   1: 3.089 ±(99.9%) 0.003 ms/op
Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.097 ±(99.9%) 0.357 ms/op [Average]
  (min, avg, max) = (3.083, 3.097, 3.120), stdev = 0.020
  CI (99.9%): [2.740, 3.454] (assumes normal distribution)


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
# Warmup Iteration   1: 6.014 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
Iteration   1: 4.107 ±(99.9%) 0.013 ms/op
Iteration   2: 4.071 ±(99.9%) 0.021 ms/op
Iteration   3: 4.097 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.092 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (4.071, 4.092, 4.107), stdev = 0.019
  CI (99.9%): [3.752, 4.431] (assumes normal distribution)


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
# Warmup Iteration   1: 4.608 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  7.762 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  10.857 ms/op
                 createUser·p0.9999: 15.157 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 18.996 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312145
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13815 
    [ 2.500,  5.000) = 296927 
    [ 5.000,  7.500) = 944 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.662 ms/op
     p(99.9900) =     19.705 ms/op
     p(99.9990) =     20.312 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.953 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   3.973 ms/op
                 existUser·p0.999:  5.470 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 2.976 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 14.008 ms/op
                 existUser·p1.00:   15.794 ms/op

Iteration   3: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.741 ms/op
                 existUser·p0.9999: 18.334 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324953
  mean =      2.953 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 383 
    [ 1.250,  2.500) = 22702 
    [ 2.500,  3.750) = 294075 
    [ 3.750,  5.000) = 6937 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 208 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     16.646 ms/op
     p(99.9990) =     18.932 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.008 ms/op
Iteration   1: 3.142 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.902 ms/op
                 getUser·p0.999:  7.930 ms/op
                 getUser·p0.9999: 17.689 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  8.684 ms/op
                 getUser·p0.9999: 30.453 ms/op
                 getUser·p1.00:   31.326 ms/op

Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  6.503 ms/op
                 getUser·p0.9999: 22.272 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308186
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14139 
    [ 2.500,  5.000) = 291845 
    [ 5.000,  7.500) = 1870 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      7.750 ms/op
     p(99.9900) =     29.411 ms/op
     p(99.9990) =     31.223 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 5.797 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.011 ms/op
Iteration   1: 4.136 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.863 ms/op
                 listUser·p0.9999: 22.987 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 4.114 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.466 ms/op
                 listUser·p0.9999: 19.880 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 4.061 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.475 ms/op
                 listUser·p0.9999: 26.247 ms/op
                 listUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233910
  mean =      4.104 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1841 
    [ 2.500,  5.000) = 208739 
    [ 5.000,  7.500) = 21726 
    [ 7.500, 10.000) = 1147 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     25.972 ms/op
     p(99.9990) =     26.595 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.416 ± 2.709  ops/ms
ClientGrpc.existUser                       thrpt       3  10.813 ± 3.379  ops/ms
ClientGrpc.getUser                         thrpt       3  10.404 ± 0.510  ops/ms
ClientGrpc.listUser                        thrpt       3   7.829 ± 0.476  ops/ms
ClientGrpc.createUser                       avgt       3   3.067 ± 0.723   ms/op
ClientGrpc.existUser                        avgt       3   2.913 ± 1.628   ms/op
ClientGrpc.getUser                          avgt       3   3.097 ± 0.357   ms/op
ClientGrpc.listUser                         avgt       3   4.092 ± 0.340   ms/op
ClientGrpc.createUser                     sample  312145   3.075 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.675           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.662           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.705           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.382           ms/op
ClientGrpc.existUser                      sample  324953   2.953 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.646           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.940           ms/op
ClientGrpc.getUser                        sample  308186   3.113 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.726           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.750           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.411           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.326           ms/op
ClientGrpc.listUser                       sample  233910   4.104 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.190           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.237           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.972           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.460           ms/op
