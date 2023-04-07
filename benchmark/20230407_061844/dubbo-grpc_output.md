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
# Warmup Iteration   1: 3.912 ops/ms
# Warmup Iteration   2: 8.901 ops/ms
# Warmup Iteration   3: 9.866 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.312 ops/ms
Iteration   3: 10.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.512 ±(99.9%) 4.008 ops/ms [Average]
  (min, avg, max) = (10.312, 10.512, 10.747), stdev = 0.220
  CI (99.9%): [6.504, 14.521] (assumes normal distribution)


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
# Warmup Iteration   1: 7.068 ops/ms
# Warmup Iteration   2: 10.512 ops/ms
# Warmup Iteration   3: 10.810 ops/ms
Iteration   1: 10.795 ops/ms
Iteration   2: 11.103 ops/ms
Iteration   3: 10.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.952 ±(99.9%) 2.803 ops/ms [Average]
  (min, avg, max) = (10.795, 10.952, 11.103), stdev = 0.154
  CI (99.9%): [8.149, 13.756] (assumes normal distribution)


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
# Warmup Iteration   1: 7.106 ops/ms
# Warmup Iteration   2: 10.079 ops/ms
# Warmup Iteration   3: 10.382 ops/ms
Iteration   1: 10.410 ops/ms
Iteration   2: 10.387 ops/ms
Iteration   3: 10.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.450 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (10.387, 10.450, 10.552), stdev = 0.090
  CI (99.9%): [8.816, 12.083] (assumes normal distribution)


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
# Warmup Iteration   1: 6.185 ops/ms
# Warmup Iteration   2: 7.444 ops/ms
# Warmup Iteration   3: 8.009 ops/ms
Iteration   1: 7.984 ops/ms
Iteration   2: 8.171 ops/ms
Iteration   3: 8.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.139 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (7.984, 8.139, 8.261), stdev = 0.142
  CI (99.9%): [5.556, 10.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.005 ms/op
Iteration   2: 3.037 ±(99.9%) 0.003 ms/op
Iteration   3: 3.038 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.025 ms/op [Average]
  (min, avg, max) = (3.036, 3.037, 3.038), stdev = 0.001
  CI (99.9%): [3.012, 3.062] (assumes normal distribution)


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.003 ms/op
Iteration   2: 2.857 ±(99.9%) 0.004 ms/op
Iteration   3: 2.967 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (2.857, 2.931, 2.969), stdev = 0.064
  CI (99.9%): [1.765, 4.097] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.003 ms/op
Iteration   1: 3.018 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
Iteration   3: 3.065 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.051 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.018, 3.051, 3.070), stdev = 0.029
  CI (99.9%): [2.530, 3.573] (assumes normal distribution)


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
# Warmup Iteration   1: 6.014 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.051 ms/op
Iteration   1: 3.972 ±(99.9%) 0.005 ms/op
Iteration   2: 4.036 ±(99.9%) 0.013 ms/op
Iteration   3: 3.989 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.999 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (3.972, 3.999, 4.036), stdev = 0.033
  CI (99.9%): [3.396, 4.602] (assumes normal distribution)


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  7.006 ms/op
                 createUser·p0.9999: 19.550 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  7.945 ms/op
                 createUser·p0.9999: 15.299 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  9.880 ms/op
                 createUser·p0.9999: 27.394 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309425
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13190 
    [ 2.500,  5.000) = 294299 
    [ 5.000,  7.500) = 1544 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.306 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     27.519 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.005 ms/op
Iteration   1: 3.000 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.655 ms/op
                 existUser·p0.9999: 11.972 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.666 ms/op
                 existUser·p0.9999: 21.446 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.336 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 16.289 ms/op
                 existUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320032
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25430 
    [ 2.500,  5.000) = 293484 
    [ 5.000,  7.500) = 864 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.954 ms/op
     p(99.9900) =     19.882 ms/op
     p(99.9990) =     21.837 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 4.918 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.108 ms/op
                 getUser·p0.9999: 18.862 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  6.586 ms/op
                 getUser·p0.9999: 14.110 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   3: 3.009 ±(99.9%) 0.004 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  6.582 ms/op
                 getUser·p0.9999: 16.089 ms/op
                 getUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314746
  mean =      3.048 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 480 
    [ 1.250,  2.500) = 15041 
    [ 2.500,  3.750) = 281206 
    [ 3.750,  5.000) = 16534 
    [ 5.000,  6.250) = 1046 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     18.402 ms/op
     p(99.9990) =     19.033 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 5.664 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.010 ms/op
Iteration   1: 3.939 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  13.383 ms/op
                 listUser·p0.9999: 16.071 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   2: 3.968 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.717 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.805 ms/op
                 listUser·p0.999:  14.324 ms/op
                 listUser·p0.9999: 17.327 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.190 ms/op
                 listUser·p0.9999: 29.188 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242758
  mean =      3.957 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2808 
    [ 2.500,  5.000) = 218496 
    [ 5.000,  7.500) = 20061 
    [ 7.500, 10.000) = 865 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     27.811 ms/op
     p(99.9990) =     29.594 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.512 ± 4.008  ops/ms
ClientGrpc.existUser                       thrpt       3  10.952 ± 2.803  ops/ms
ClientGrpc.getUser                         thrpt       3  10.450 ± 1.633  ops/ms
ClientGrpc.listUser                        thrpt       3   8.139 ± 2.582  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.025   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 1.166   ms/op
ClientGrpc.getUser                          avgt       3   3.051 ± 0.521   ms/op
ClientGrpc.listUser                         avgt       3   3.999 ± 0.603   ms/op
ClientGrpc.createUser                     sample  309425   3.102 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.721           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.306           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.870           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.623           ms/op
ClientGrpc.existUser                      sample  320032   2.999 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.579           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.954           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.882           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.053           ms/op
ClientGrpc.getUser                        sample  314746   3.048 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.694           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.750           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.402           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.104           ms/op
ClientGrpc.listUser                       sample  242758   3.957 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.717           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.107           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.811           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.688           ms/op
