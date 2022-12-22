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
# Warmup Iteration   1: 4.799 ops/ms
# Warmup Iteration   2: 9.514 ops/ms
# Warmup Iteration   3: 10.459 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.671 ±(99.9%) 2.540 ops/ms [Average]
  (min, avg, max) = (10.563, 10.671, 10.828), stdev = 0.139
  CI (99.9%): [8.130, 13.211] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.148 ops/ms
# Warmup Iteration   2: 10.704 ops/ms
# Warmup Iteration   3: 10.988 ops/ms
Iteration   1: 11.000 ops/ms
Iteration   2: 10.924 ops/ms
Iteration   3: 10.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.895 ±(99.9%) 2.229 ops/ms [Average]
  (min, avg, max) = (10.761, 10.895, 11.000), stdev = 0.122
  CI (99.9%): [8.666, 13.124] (assumes normal distribution)


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
# Warmup Iteration   1: 7.672 ops/ms
# Warmup Iteration   2: 10.403 ops/ms
# Warmup Iteration   3: 10.414 ops/ms
Iteration   1: 10.772 ops/ms
Iteration   2: 10.336 ops/ms
Iteration   3: 10.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.520 ±(99.9%) 4.123 ops/ms [Average]
  (min, avg, max) = (10.336, 10.520, 10.772), stdev = 0.226
  CI (99.9%): [6.396, 14.643] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.539 ops/ms
# Warmup Iteration   2: 7.899 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.004 ops/ms
Iteration   2: 8.126 ops/ms
Iteration   3: 7.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.024 ±(99.9%) 1.697 ops/ms [Average]
  (min, avg, max) = (7.943, 8.024, 8.126), stdev = 0.093
  CI (99.9%): [6.327, 9.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 3.013 ±(99.9%) 0.002 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.029 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.006, 3.029, 3.068), stdev = 0.034
  CI (99.9%): [2.404, 3.654] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.621 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.003 ms/op
Iteration   1: 2.922 ±(99.9%) 0.002 ms/op
Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
Iteration   3: 2.870 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.910 ±(99.9%) 0.659 ms/op [Average]
  (min, avg, max) = (2.870, 2.910, 2.939), stdev = 0.036
  CI (99.9%): [2.251, 3.569] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.024 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 3.074 ±(99.9%) 0.003 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.059 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.044, 3.059, 3.074), stdev = 0.015
  CI (99.9%): [2.783, 3.334] (assumes normal distribution)


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.020 ms/op
Iteration   1: 3.962 ±(99.9%) 0.010 ms/op
Iteration   2: 3.861 ±(99.9%) 0.023 ms/op
Iteration   3: 3.888 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.904 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.861, 3.904, 3.962), stdev = 0.052
  CI (99.9%): [2.946, 4.861] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.832 ms/op
                 createUser·p0.9999: 11.876 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  6.596 ms/op
                 createUser·p0.9999: 12.705 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.720 ms/op
                 createUser·p0.9999: 15.605 ms/op
                 createUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313530
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1296 
    [ 1.250,  2.500) = 34439 
    [ 2.500,  3.750) = 245199 
    [ 3.750,  5.000) = 31588 
    [ 5.000,  6.250) = 485 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.753 ms/op
     p(99.9900) =     14.226 ms/op
     p(99.9990) =     16.099 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


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
# Warmup Iteration   1: 3.598 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.007 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.638 ms/op
                 existUser·p0.9999: 21.468 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.406 ms/op
                 existUser·p0.9999: 13.057 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  5.534 ms/op
                 existUser·p0.9999: 21.266 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328341
  mean =      2.921 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53073 
    [ 2.500,  5.000) = 274609 
    [ 5.000,  7.500) = 402 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      6.067 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.923 ms/op
                 getUser·p0.9999: 11.633 ms/op
                 getUser·p1.00:   12.075 ms/op

Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  5.933 ms/op
                 getUser·p0.9999: 19.099 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.119 ms/op
                 getUser·p0.9999: 16.439 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317333
  mean =      3.025 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1736 
    [ 1.250,  2.500) = 28389 
    [ 2.500,  3.750) = 269728 
    [ 3.750,  5.000) = 16729 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      6.248 ms/op
     p(99.9900) =     18.236 ms/op
     p(99.9990) =     19.420 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.012 ms/op
Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.685 ms/op
                 listUser·p0.9999: 18.878 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 4.134 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 22.618 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 3.845 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  12.623 ms/op
                 listUser·p0.9999: 18.341 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241943
  mean =      3.966 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5436 
    [ 2.500,  5.000) = 206403 
    [ 5.000,  7.500) = 29003 
    [ 7.500, 10.000) = 710 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.304 ms/op
     p(99.9900) =     22.368 ms/op
     p(99.9990) =     26.937 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.671 ± 2.540  ops/ms
ClientGrpc.existUser                       thrpt       3  10.895 ± 2.229  ops/ms
ClientGrpc.getUser                         thrpt       3  10.520 ± 4.123  ops/ms
ClientGrpc.listUser                        thrpt       3   8.024 ± 1.697  ops/ms
ClientGrpc.createUser                       avgt       3   3.029 ± 0.625   ms/op
ClientGrpc.existUser                        avgt       3   2.910 ± 0.659   ms/op
ClientGrpc.getUser                          avgt       3   3.059 ± 0.276   ms/op
ClientGrpc.listUser                         avgt       3   3.904 ± 0.958   ms/op
ClientGrpc.createUser                     sample  313530   3.065 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.605           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.753           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.226           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.548           ms/op
ClientGrpc.existUser                      sample  328341   2.921 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.549           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.067           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.234           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.791           ms/op
ClientGrpc.getUser                        sample  317333   3.025 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.248           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.236           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.530           ms/op
ClientGrpc.listUser                       sample  241943   3.966 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.814           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.304           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.368           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
