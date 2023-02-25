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
# Warmup Iteration   1: 5.107 ops/ms
# Warmup Iteration   2: 9.682 ops/ms
# Warmup Iteration   3: 10.230 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.508 ±(99.9%) 2.229 ops/ms [Average]
  (min, avg, max) = (10.390, 10.508, 10.634), stdev = 0.122
  CI (99.9%): [8.279, 12.736] (assumes normal distribution)


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
# Warmup Iteration   1: 8.088 ops/ms
# Warmup Iteration   2: 10.765 ops/ms
# Warmup Iteration   3: 10.602 ops/ms
Iteration   1: 10.815 ops/ms
Iteration   2: 10.642 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.757 ±(99.9%) 1.819 ops/ms [Average]
  (min, avg, max) = (10.642, 10.757, 10.815), stdev = 0.100
  CI (99.9%): [8.938, 12.575] (assumes normal distribution)


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
# Warmup Iteration   1: 7.367 ops/ms
# Warmup Iteration   2: 10.566 ops/ms
# Warmup Iteration   3: 10.579 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.617 ±(99.9%) 3.792 ops/ms [Average]
  (min, avg, max) = (10.413, 10.617, 10.829), stdev = 0.208
  CI (99.9%): [6.826, 14.409] (assumes normal distribution)


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
# Warmup Iteration   1: 7.341 ops/ms
# Warmup Iteration   2: 7.775 ops/ms
# Warmup Iteration   3: 7.836 ops/ms
Iteration   1: 8.120 ops/ms
Iteration   2: 8.386 ops/ms
Iteration   3: 8.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.236 ±(99.9%) 2.487 ops/ms [Average]
  (min, avg, max) = (8.120, 8.236, 8.386), stdev = 0.136
  CI (99.9%): [5.749, 10.722] (assumes normal distribution)


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.003 ms/op
Iteration   1: 3.080 ±(99.9%) 0.011 ms/op
Iteration   2: 3.118 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.101 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (3.080, 3.101, 3.118), stdev = 0.019
  CI (99.9%): [2.753, 3.448] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 2.952 ±(99.9%) 0.009 ms/op
Iteration   2: 2.894 ±(99.9%) 0.002 ms/op
Iteration   3: 2.919 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.922 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (2.894, 2.922, 2.952), stdev = 0.029
  CI (99.9%): [2.390, 3.453] (assumes normal distribution)


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.002 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
Iteration   3: 3.093 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (3.049, 3.091, 3.130), stdev = 0.041
  CI (99.9%): [2.350, 3.832] (assumes normal distribution)


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
# Warmup Iteration   1: 5.043 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.015 ms/op
Iteration   1: 3.908 ±(99.9%) 0.032 ms/op
Iteration   2: 4.148 ±(99.9%) 0.006 ms/op
Iteration   3: 3.923 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.993 ±(99.9%) 2.444 ms/op [Average]
  (min, avg, max) = (3.908, 3.993, 4.148), stdev = 0.134
  CI (99.9%): [1.549, 6.437] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.006 ms/op
Iteration   1: 3.147 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  9.502 ms/op
                 createUser·p0.9999: 13.645 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.531 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 12.943 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  10.036 ms/op
                 createUser·p0.9999: 18.499 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309949
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1308 
    [ 1.250,  2.500) = 27896 
    [ 2.500,  3.750) = 247598 
    [ 3.750,  5.000) = 31779 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 195 
    [ 7.500,  8.750) = 182 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 163 
    [12.500, 13.750) = 134 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     17.761 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.006 ms/op
Iteration   1: 2.831 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.313 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.087 ms/op
                 existUser·p0.9999: 10.668 ms/op
                 existUser·p1.00:   11.993 ms/op

Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  9.592 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  7.631 ms/op
                 existUser·p0.9999: 13.926 ms/op
                 existUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328251
  mean =      2.924 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3650 
    [ 1.250,  2.500) = 50159 
    [ 2.500,  3.750) = 255141 
    [ 3.750,  5.000) = 18323 
    [ 5.000,  6.250) = 407 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.313 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      7.600 ms/op
     p(99.9900) =     13.473 ms/op
     p(99.9990) =     15.999 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.848 ms/op
                 getUser·p0.9999: 11.411 ms/op
                 getUser·p1.00:   11.813 ms/op

Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.774 ms/op
                 getUser·p0.9999: 13.569 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.339 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.288 ms/op
                 getUser·p0.9999: 18.210 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309282
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1373 
    [ 1.250,  2.500) = 30342 
    [ 2.500,  3.750) = 242114 
    [ 3.750,  5.000) = 34377 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 379 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.339 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.184 ms/op
     p(99.9900) =     16.270 ms/op
     p(99.9990) =     18.511 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 4.601 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.012 ms/op
Iteration   1: 3.913 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 15.381 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 3.915 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.639 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 23.014 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.308 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 21.857 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243131
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4892 
    [ 2.500,  5.000) = 212309 
    [ 5.000,  7.500) = 24714 
    [ 7.500, 10.000) = 794 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     22.436 ms/op
     p(99.9990) =     23.237 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.508 ± 2.229  ops/ms
ClientGrpc.existUser                       thrpt       3  10.757 ± 1.819  ops/ms
ClientGrpc.getUser                         thrpt       3  10.617 ± 3.792  ops/ms
ClientGrpc.listUser                        thrpt       3   8.236 ± 2.487  ops/ms
ClientGrpc.createUser                       avgt       3   3.101 ± 0.348   ms/op
ClientGrpc.existUser                        avgt       3   2.922 ± 0.531   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.741   ms/op
ClientGrpc.listUser                         avgt       3   3.993 ± 2.444   ms/op
ClientGrpc.createUser                     sample  309949   3.097 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.674           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.715           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.761           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.678           ms/op
ClientGrpc.existUser                      sample  328251   2.924 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.313           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.600           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.473           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.237           ms/op
ClientGrpc.getUser                        sample  309282   3.101 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.339           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.184           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.270           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.579           ms/op
ClientGrpc.listUser                       sample  243131   3.946 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.308           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.436           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
