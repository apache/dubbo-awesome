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
# Warmup Iteration   1: 4.894 ops/ms
# Warmup Iteration   2: 9.241 ops/ms
# Warmup Iteration   3: 10.643 ops/ms
Iteration   1: 10.304 ops/ms
Iteration   2: 10.091 ops/ms
Iteration   3: 10.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.192 ±(99.9%) 1.955 ops/ms [Average]
  (min, avg, max) = (10.091, 10.192, 10.304), stdev = 0.107
  CI (99.9%): [8.238, 12.147] (assumes normal distribution)


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
# Warmup Iteration   1: 8.048 ops/ms
# Warmup Iteration   2: 10.749 ops/ms
# Warmup Iteration   3: 10.702 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.915 ops/ms
Iteration   3: 10.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.891 ±(99.9%) 2.120 ops/ms [Average]
  (min, avg, max) = (10.765, 10.891, 10.994), stdev = 0.116
  CI (99.9%): [8.772, 13.011] (assumes normal distribution)


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
# Warmup Iteration   1: 8.583 ops/ms
# Warmup Iteration   2: 10.470 ops/ms
# Warmup Iteration   3: 10.293 ops/ms
Iteration   1: 10.512 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.547 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (10.512, 10.547, 10.590), stdev = 0.040
  CI (99.9%): [9.820, 11.273] (assumes normal distribution)


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
# Warmup Iteration   1: 6.909 ops/ms
# Warmup Iteration   2: 7.722 ops/ms
# Warmup Iteration   3: 7.930 ops/ms
Iteration   1: 7.911 ops/ms
Iteration   2: 8.059 ops/ms
Iteration   3: 8.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.047 ±(99.9%) 2.389 ops/ms [Average]
  (min, avg, max) = (7.911, 8.047, 8.172), stdev = 0.131
  CI (99.9%): [5.658, 10.436] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.004 ms/op
Iteration   1: 3.042 ±(99.9%) 0.002 ms/op
Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.080 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (3.042, 3.080, 3.113), stdev = 0.036
  CI (99.9%): [2.425, 3.735] (assumes normal distribution)


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.003 ms/op
Iteration   1: 2.874 ±(99.9%) 0.003 ms/op
Iteration   2: 2.928 ±(99.9%) 0.002 ms/op
Iteration   3: 2.924 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.909 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (2.874, 2.909, 2.928), stdev = 0.030
  CI (99.9%): [2.355, 3.462] (assumes normal distribution)


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.002 ms/op
Iteration   1: 2.920 ±(99.9%) 0.003 ms/op
Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
Iteration   3: 2.933 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.976 ±(99.9%) 1.564 ms/op [Average]
  (min, avg, max) = (2.920, 2.976, 3.075), stdev = 0.086
  CI (99.9%): [1.412, 4.540] (assumes normal distribution)


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
# Warmup Iteration   1: 5.267 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.037 ms/op
Iteration   1: 3.922 ±(99.9%) 0.039 ms/op
Iteration   2: 3.922 ±(99.9%) 0.012 ms/op
Iteration   3: 3.896 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.913 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (3.896, 3.913, 3.922), stdev = 0.015
  CI (99.9%): [3.641, 4.185] (assumes normal distribution)


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.154 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 11.754 ms/op
                 createUser·p1.00:   12.091 ms/op

Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.642 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.731 ms/op
                 createUser·p0.9999: 12.845 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  10.813 ms/op
                 createUser·p0.9999: 16.449 ms/op
                 createUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306802
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 955 
    [ 1.250,  2.500) = 24671 
    [ 2.500,  3.750) = 244077 
    [ 3.750,  5.000) = 35897 
    [ 5.000,  6.250) = 429 
    [ 6.250,  7.500) = 300 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =     10.489 ms/op
     p(99.9900) =     14.265 ms/op
     p(99.9990) =     16.642 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
Iteration   1: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.414 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  10.757 ms/op
                 existUser·p0.9999: 13.570 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.320 ms/op
                 existUser·p0.9999: 13.162 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  11.059 ms/op
                 existUser·p0.9999: 14.855 ms/op
                 existUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322393
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2006 
    [ 1.250,  2.500) = 45840 
    [ 2.500,  3.750) = 253799 
    [ 3.750,  5.000) = 19520 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 199 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     10.336 ms/op
     p(99.9900) =     14.529 ms/op
     p(99.9990) =     15.037 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.505 ms/op
                 getUser·p0.9999: 12.703 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  8.353 ms/op
                 getUser·p0.9999: 16.024 ms/op
                 getUser·p1.00:   16.433 ms/op

Iteration   3: 3.017 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  5.161 ms/op
                 getUser·p0.9999: 14.758 ms/op
                 getUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318801
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1520 
    [ 1.250,  2.500) = 28443 
    [ 2.500,  3.750) = 272291 
    [ 3.750,  5.000) = 15741 
    [ 5.000,  6.250) = 349 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.953 ms/op
     p(99.9900) =     15.421 ms/op
     p(99.9990) =     16.323 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.012 ms/op
Iteration   1: 3.907 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  11.244 ms/op
                 listUser·p0.9999: 15.204 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.456 ms/op
                 listUser·p0.9999: 23.192 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 4.061 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  16.670 ms/op
                 listUser·p0.9999: 25.399 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243073
  mean =      3.949 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3208 
    [ 2.500,  5.000) = 212656 
    [ 5.000,  7.500) = 26155 
    [ 7.500, 10.000) = 618 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     14.153 ms/op
     p(99.9900) =     23.091 ms/op
     p(99.9990) =     26.168 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.192 ± 1.955  ops/ms
ClientGrpc.existUser                       thrpt       3  10.891 ± 2.120  ops/ms
ClientGrpc.getUser                         thrpt       3  10.547 ± 0.727  ops/ms
ClientGrpc.listUser                        thrpt       3   8.047 ± 2.389  ops/ms
ClientGrpc.createUser                       avgt       3   3.080 ± 0.655   ms/op
ClientGrpc.existUser                        avgt       3   2.909 ± 0.554   ms/op
ClientGrpc.getUser                          avgt       3   2.976 ± 1.564   ms/op
ClientGrpc.listUser                         avgt       3   3.913 ± 0.272   ms/op
ClientGrpc.createUser                     sample  306802   3.127 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.568           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.489           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.265           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.810           ms/op
ClientGrpc.existUser                      sample  322393   2.975 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.414           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.336           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.529           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.057           ms/op
ClientGrpc.getUser                        sample  318801   3.010 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.663           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.953           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.421           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.433           ms/op
ClientGrpc.listUser                       sample  243073   3.949 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.808           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.153           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.091           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
