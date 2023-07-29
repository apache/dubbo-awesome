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
# Warmup Iteration   1: 4.647 ops/ms
# Warmup Iteration   2: 9.187 ops/ms
# Warmup Iteration   3: 10.365 ops/ms
Iteration   1: 10.818 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.753 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (10.621, 10.753, 10.820), stdev = 0.115
  CI (99.9%): [8.663, 12.843] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.058 ops/ms
# Warmup Iteration   2: 10.892 ops/ms
# Warmup Iteration   3: 11.485 ops/ms
Iteration   1: 11.088 ops/ms
Iteration   2: 11.372 ops/ms
Iteration   3: 11.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.253 ±(99.9%) 2.692 ops/ms [Average]
  (min, avg, max) = (11.088, 11.253, 11.372), stdev = 0.148
  CI (99.9%): [8.561, 13.946] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.121 ops/ms
# Warmup Iteration   2: 10.226 ops/ms
# Warmup Iteration   3: 10.775 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.684 ±(99.9%) 1.253 ops/ms [Average]
  (min, avg, max) = (10.634, 10.684, 10.763), stdev = 0.069
  CI (99.9%): [9.432, 11.937] (assumes normal distribution)


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
# Warmup Iteration   1: 6.860 ops/ms
# Warmup Iteration   2: 7.806 ops/ms
# Warmup Iteration   3: 8.273 ops/ms
Iteration   1: 8.348 ops/ms
Iteration   2: 8.400 ops/ms
Iteration   3: 8.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.374 ±(99.9%) 0.477 ops/ms [Average]
  (min, avg, max) = (8.348, 8.374, 8.400), stdev = 0.026
  CI (99.9%): [7.897, 8.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.003 ms/op
Iteration   1: 3.005 ±(99.9%) 0.002 ms/op
Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
Iteration   3: 3.003 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (3.003, 3.010, 3.021), stdev = 0.010
  CI (99.9%): [2.827, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.003 ms/op
Iteration   1: 2.849 ±(99.9%) 0.003 ms/op
Iteration   2: 2.854 ±(99.9%) 0.004 ms/op
Iteration   3: 2.838 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.847 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (2.838, 2.847, 2.854), stdev = 0.008
  CI (99.9%): [2.700, 2.994] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.003 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.978 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.965, 2.978, 2.997), stdev = 0.017
  CI (99.9%): [2.668, 3.287] (assumes normal distribution)


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
# Warmup Iteration   1: 5.073 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.015 ms/op
Iteration   1: 3.747 ±(99.9%) 0.022 ms/op
Iteration   2: 3.687 ±(99.9%) 0.005 ms/op
Iteration   3: 3.720 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.718 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.687, 3.718, 3.747), stdev = 0.030
  CI (99.9%): [3.166, 4.270] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.836 ms/op
                 createUser·p0.9999: 15.489 ms/op
                 createUser·p1.00:   16.318 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.288 ms/op
                 createUser·p0.999:  9.177 ms/op
                 createUser·p0.9999: 22.135 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  6.461 ms/op
                 createUser·p0.9999: 19.968 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319345
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24062 
    [ 2.500,  5.000) = 294053 
    [ 5.000,  7.500) = 849 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.927 ms/op
     p(99.9900) =     20.089 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
Iteration   1: 2.883 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.067 ms/op
                 existUser·p0.9999: 16.901 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   2: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  9.692 ms/op
                 existUser·p0.9999: 13.530 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 2.868 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  8.094 ms/op
                 existUser·p0.9999: 14.123 ms/op
                 existUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333470
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2320 
    [ 1.250,  2.500) = 40148 
    [ 2.500,  3.750) = 280537 
    [ 3.750,  5.000) = 9259 
    [ 5.000,  6.250) = 646 
    [ 6.250,  7.500) = 167 
    [ 7.500,  8.750) = 126 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.094 ms/op
     p(99.9900) =     14.455 ms/op
     p(99.9990) =     17.225 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.620 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  10.768 ms/op
                 getUser·p0.9999: 18.448 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  6.382 ms/op
                 getUser·p0.9999: 13.765 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.385 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.290 ms/op
                 getUser·p0.9999: 17.763 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325405
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2729 
    [ 1.250,  2.500) = 29062 
    [ 2.500,  3.750) = 281882 
    [ 3.750,  5.000) = 10644 
    [ 5.000,  6.250) = 602 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 66 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      8.369 ms/op
     p(99.9900) =     18.085 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
Iteration   1: 3.835 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  11.951 ms/op
                 listUser·p0.9999: 16.073 ms/op
                 listUser·p1.00:   16.466 ms/op

Iteration   2: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.494 ms/op
                 listUser·p0.9999: 16.750 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.680 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  14.309 ms/op
                 listUser·p0.9999: 22.668 ms/op
                 listUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249127
  mean =      3.853 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3772 
    [ 2.500,  5.000) = 228139 
    [ 5.000,  7.500) = 16267 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.365 ms/op
     p(99.9900) =     21.564 ms/op
     p(99.9990) =     23.971 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.753 ± 2.090  ops/ms
ClientGrpc.existUser                       thrpt       3  11.253 ± 2.692  ops/ms
ClientGrpc.getUser                         thrpt       3  10.684 ± 1.253  ops/ms
ClientGrpc.listUser                        thrpt       3   8.374 ± 0.477  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.183   ms/op
ClientGrpc.existUser                        avgt       3   2.847 ± 0.147   ms/op
ClientGrpc.getUser                          avgt       3   2.978 ± 0.310   ms/op
ClientGrpc.listUser                         avgt       3   3.718 ± 0.552   ms/op
ClientGrpc.createUser                     sample  319345   3.005 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.588           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.927           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.089           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.413           ms/op
ClientGrpc.existUser                      sample  333470   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.604           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.455           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.433           ms/op
ClientGrpc.getUser                        sample  325405   2.951 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.385           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.369           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.085           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.825           ms/op
ClientGrpc.listUser                       sample  249127   3.853 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.680           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.365           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.564           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.084           ms/op
