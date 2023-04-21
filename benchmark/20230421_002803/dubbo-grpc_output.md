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
# Warmup Iteration   1: 3.807 ops/ms
# Warmup Iteration   2: 8.042 ops/ms
# Warmup Iteration   3: 9.653 ops/ms
Iteration   1: 10.055 ops/ms
Iteration   2: 10.332 ops/ms
Iteration   3: 10.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.246 ±(99.9%) 3.025 ops/ms [Average]
  (min, avg, max) = (10.055, 10.246, 10.352), stdev = 0.166
  CI (99.9%): [7.221, 13.271] (assumes normal distribution)


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
# Warmup Iteration   1: 6.666 ops/ms
# Warmup Iteration   2: 10.372 ops/ms
# Warmup Iteration   3: 10.793 ops/ms
Iteration   1: 10.775 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.728 ±(99.9%) 1.726 ops/ms [Average]
  (min, avg, max) = (10.619, 10.728, 10.789), stdev = 0.095
  CI (99.9%): [9.002, 12.453] (assumes normal distribution)


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
# Warmup Iteration   1: 6.144 ops/ms
# Warmup Iteration   2: 9.844 ops/ms
# Warmup Iteration   3: 10.258 ops/ms
Iteration   1: 10.331 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 10.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.322 ±(99.9%) 0.152 ops/ms [Average]
  (min, avg, max) = (10.315, 10.322, 10.331), stdev = 0.008
  CI (99.9%): [10.171, 10.474] (assumes normal distribution)


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
# Warmup Iteration   1: 5.014 ops/ms
# Warmup Iteration   2: 7.566 ops/ms
# Warmup Iteration   3: 7.924 ops/ms
Iteration   1: 7.807 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 7.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.981 ±(99.9%) 5.035 ops/ms [Average]
  (min, avg, max) = (7.807, 7.981, 8.299), stdev = 0.276
  CI (99.9%): [2.946, 13.016] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.241 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.031 ms/op
Iteration   1: 3.118 ±(99.9%) 0.010 ms/op
Iteration   2: 3.134 ±(99.9%) 0.003 ms/op
Iteration   3: 3.106 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.119 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (3.106, 3.119, 3.134), stdev = 0.014
  CI (99.9%): [2.863, 3.375] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.003 ms/op
Iteration   1: 2.999 ±(99.9%) 0.002 ms/op
Iteration   2: 2.977 ±(99.9%) 0.002 ms/op
Iteration   3: 2.931 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.969 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (2.931, 2.969, 2.999), stdev = 0.035
  CI (99.9%): [2.334, 3.604] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.752 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.002 ms/op
Iteration   1: 3.147 ±(99.9%) 0.003 ms/op
Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.104 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.067, 3.104, 3.147), stdev = 0.040
  CI (99.9%): [2.366, 3.843] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.605 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.268 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.008 ms/op
Iteration   1: 4.092 ±(99.9%) 0.009 ms/op
Iteration   2: 4.058 ±(99.9%) 0.006 ms/op
Iteration   3: 4.044 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.065 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (4.044, 4.065, 4.092), stdev = 0.025
  CI (99.9%): [3.612, 4.517] (assumes normal distribution)


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
# Warmup Iteration   1: 4.814 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.529 ms/op
                 createUser·p0.999:  8.355 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   18.874 ms/op

Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  11.859 ms/op
                 createUser·p0.9999: 22.858 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  13.079 ms/op
                 createUser·p0.9999: 24.707 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305754
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16569 
    [ 2.500,  5.000) = 287639 
    [ 5.000,  7.500) = 1033 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =     11.080 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     24.834 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.005 ms/op
Iteration   1: 2.961 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.528 ms/op
                 existUser·p0.9999: 14.012 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.895 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  9.348 ms/op
                 existUser·p0.9999: 14.106 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.733 ms/op
                 existUser·p0.9999: 20.742 ms/op
                 existUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325299
  mean =      2.949 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28692 
    [ 2.500,  5.000) = 295230 
    [ 5.000,  7.500) = 983 
    [ 7.500, 10.000) = 167 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.895 ms/op
     p(99.9900) =     18.410 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
Iteration   1: 3.110 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.461 ms/op
                 getUser·p0.999:  7.744 ms/op
                 getUser·p0.9999: 20.082 ms/op
                 getUser·p1.00:   21.922 ms/op

Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.277 ms/op
                 getUser·p0.9999: 21.418 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  8.145 ms/op
                 getUser·p0.9999: 22.733 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308826
  mean =      3.108 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10070 
    [ 2.500,  5.000) = 297117 
    [ 5.000,  7.500) = 1140 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.963 ms/op
     p(99.9900) =     22.057 ms/op
     p(99.9990) =     23.000 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 5.848 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.012 ms/op
Iteration   1: 4.100 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.563 ms/op
                 listUser·p0.9999: 23.173 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 4.075 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  16.483 ms/op
                 listUser·p0.9999: 21.072 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 4.122 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  18.454 ms/op
                 listUser·p0.9999: 23.699 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234107
  mean =      4.099 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1744 
    [ 2.500,  5.000) = 205393 
    [ 5.000,  7.500) = 25083 
    [ 7.500, 10.000) = 1401 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     23.186 ms/op
     p(99.9990) =     23.833 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.246 ± 3.025  ops/ms
ClientGrpc.existUser                       thrpt       3  10.728 ± 1.726  ops/ms
ClientGrpc.getUser                         thrpt       3  10.322 ± 0.152  ops/ms
ClientGrpc.listUser                        thrpt       3   7.981 ± 5.035  ops/ms
ClientGrpc.createUser                       avgt       3   3.119 ± 0.256   ms/op
ClientGrpc.existUser                        avgt       3   2.969 ± 0.635   ms/op
ClientGrpc.getUser                          avgt       3   3.104 ± 0.738   ms/op
ClientGrpc.listUser                         avgt       3   4.065 ± 0.453   ms/op
ClientGrpc.createUser                     sample  305754   3.137 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.610           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.080           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.543           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.904           ms/op
ClientGrpc.existUser                      sample  325299   2.949 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.551           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.895           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.410           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.365           ms/op
ClientGrpc.getUser                        sample  308826   3.108 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.760           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.963           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.057           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.101           ms/op
ClientGrpc.listUser                       sample  234107   4.099 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.988           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.203           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.186           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.314           ms/op
