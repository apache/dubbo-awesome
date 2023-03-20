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
# Warmup Iteration   1: 4.157 ops/ms
# Warmup Iteration   2: 8.839 ops/ms
# Warmup Iteration   3: 9.921 ops/ms
Iteration   1: 10.422 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 10.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.548 ±(99.9%) 2.610 ops/ms [Average]
  (min, avg, max) = (10.422, 10.548, 10.703), stdev = 0.143
  CI (99.9%): [7.938, 13.158] (assumes normal distribution)


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
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 10.607 ops/ms
# Warmup Iteration   3: 10.965 ops/ms
Iteration   1: 10.971 ops/ms
Iteration   2: 11.285 ops/ms
Iteration   3: 11.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.100 ±(99.9%) 3.004 ops/ms [Average]
  (min, avg, max) = (10.971, 11.100, 11.285), stdev = 0.165
  CI (99.9%): [8.095, 14.104] (assumes normal distribution)


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
# Warmup Iteration   1: 6.854 ops/ms
# Warmup Iteration   2: 10.041 ops/ms
# Warmup Iteration   3: 10.357 ops/ms
Iteration   1: 10.384 ops/ms
Iteration   2: 10.429 ops/ms
Iteration   3: 10.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.378 ±(99.9%) 1.010 ops/ms [Average]
  (min, avg, max) = (10.319, 10.378, 10.429), stdev = 0.055
  CI (99.9%): [9.367, 11.388] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.162 ops/ms
# Warmup Iteration   2: 7.854 ops/ms
# Warmup Iteration   3: 7.980 ops/ms
Iteration   1: 7.971 ops/ms
Iteration   2: 8.063 ops/ms
Iteration   3: 7.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.996 ±(99.9%) 1.062 ops/ms [Average]
  (min, avg, max) = (7.955, 7.996, 8.063), stdev = 0.058
  CI (99.9%): [6.934, 9.059] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.002 ms/op
Iteration   1: 3.018 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 2.972 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.018 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (2.972, 3.018, 3.064), stdev = 0.046
  CI (99.9%): [2.185, 3.852] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.113 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.002 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.908 ±(99.9%) 0.001 ms/op
Iteration   3: 2.921 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.913 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.908, 2.913, 2.921), stdev = 0.007
  CI (99.9%): [2.782, 3.043] (assumes normal distribution)


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.003 ms/op
Iteration   1: 3.053 ±(99.9%) 0.002 ms/op
Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
Iteration   3: 3.018 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.038 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (3.018, 3.038, 3.053), stdev = 0.018
  CI (99.9%): [2.702, 3.375] (assumes normal distribution)


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
# Warmup Iteration   1: 5.126 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.024 ms/op
Iteration   1: 4.029 ±(99.9%) 0.027 ms/op
Iteration   2: 3.950 ±(99.9%) 0.013 ms/op
Iteration   3: 4.069 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.016 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (3.950, 4.016, 4.069), stdev = 0.061
  CI (99.9%): [2.909, 5.123] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.445 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
Iteration   1: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.448 ms/op
                 createUser·p0.9999: 13.823 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.698 ms/op
                 createUser·p0.9999: 15.456 ms/op
                 createUser·p1.00:   15.909 ms/op

Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  9.506 ms/op
                 createUser·p0.9999: 18.767 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308890
  mean =      3.106 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 338 
    [ 1.250,  2.500) = 18516 
    [ 2.500,  3.750) = 267529 
    [ 3.750,  5.000) = 20831 
    [ 5.000,  6.250) = 1096 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     16.622 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.006 ms/op
Iteration   1: 2.799 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  6.879 ms/op
                 existUser·p0.9999: 13.152 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   2: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  5.840 ms/op
                 existUser·p0.9999: 14.309 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  11.600 ms/op
                 existUser·p0.9999: 16.556 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334704
  mean =      2.867 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1898 
    [ 1.250,  2.500) = 47222 
    [ 2.500,  3.750) = 279070 
    [ 3.750,  5.000) = 5434 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 247 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      7.252 ms/op
     p(99.9900) =     15.967 ms/op
     p(99.9990) =     17.572 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
Iteration   1: 3.068 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.181 ms/op
                 getUser·p0.9999: 13.338 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.507 ms/op
                 getUser·p0.999:  7.856 ms/op
                 getUser·p0.9999: 14.754 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.308 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.996 ms/op
                 getUser·p0.9999: 17.793 ms/op
                 getUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314356
  mean =      3.054 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 544 
    [ 1.250,  2.500) = 18822 
    [ 2.500,  3.750) = 275450 
    [ 3.750,  5.000) = 17829 
    [ 5.000,  6.250) = 970 
    [ 6.250,  7.500) = 345 
    [ 7.500,  8.750) = 135 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.134 ms/op
     p(99.9900) =     16.796 ms/op
     p(99.9990) =     18.706 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 5.849 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.011 ms/op
Iteration   1: 4.167 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  14.256 ms/op
                 listUser·p0.9999: 16.798 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   2: 4.037 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.968 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   3: 4.125 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.718 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 20.037 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233629
  mean =      4.109 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1720 
    [ 2.500,  5.000) = 199361 
    [ 5.000,  7.500) = 30538 
    [ 7.500, 10.000) = 1419 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.878 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     25.994 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.548 ± 2.610  ops/ms
ClientGrpc.existUser                       thrpt       3  11.100 ± 3.004  ops/ms
ClientGrpc.getUser                         thrpt       3  10.378 ± 1.010  ops/ms
ClientGrpc.listUser                        thrpt       3   7.996 ± 1.062  ops/ms
ClientGrpc.createUser                       avgt       3   3.018 ± 0.833   ms/op
ClientGrpc.existUser                        avgt       3   2.913 ± 0.131   ms/op
ClientGrpc.getUser                          avgt       3   3.038 ± 0.337   ms/op
ClientGrpc.listUser                         avgt       3   4.016 ± 1.107   ms/op
ClientGrpc.createUser                     sample  308890   3.106 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.799           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.585           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.622           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.842           ms/op
ClientGrpc.existUser                      sample  334704   2.867 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.697           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.252           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.967           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.662           ms/op
ClientGrpc.getUser                        sample  314356   3.054 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.308           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.134           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.796           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.776           ms/op
ClientGrpc.listUser                       sample  233629   4.109 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.718           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.878           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.332           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.303           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.994           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
