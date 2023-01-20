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
# Warmup Iteration   1: 4.477 ops/ms
# Warmup Iteration   2: 8.825 ops/ms
# Warmup Iteration   3: 9.862 ops/ms
Iteration   1: 10.139 ops/ms
Iteration   2: 10.172 ops/ms
Iteration   3: 10.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.143 ±(99.9%) 0.489 ops/ms [Average]
  (min, avg, max) = (10.118, 10.143, 10.172), stdev = 0.027
  CI (99.9%): [9.654, 10.632] (assumes normal distribution)


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
# Warmup Iteration   1: 8.134 ops/ms
# Warmup Iteration   2: 10.338 ops/ms
# Warmup Iteration   3: 10.737 ops/ms
Iteration   1: 10.496 ops/ms
Iteration   2: 10.401 ops/ms
Iteration   3: 10.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.518 ±(99.9%) 2.376 ops/ms [Average]
  (min, avg, max) = (10.401, 10.518, 10.658), stdev = 0.130
  CI (99.9%): [8.143, 12.894] (assumes normal distribution)


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
# Warmup Iteration   1: 7.335 ops/ms
# Warmup Iteration   2: 9.678 ops/ms
# Warmup Iteration   3: 10.004 ops/ms
Iteration   1: 9.801 ops/ms
Iteration   2: 9.890 ops/ms
Iteration   3: 10.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.978 ±(99.9%) 4.258 ops/ms [Average]
  (min, avg, max) = (9.801, 9.978, 10.243), stdev = 0.233
  CI (99.9%): [5.720, 14.236] (assumes normal distribution)


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
# Warmup Iteration   1: 6.094 ops/ms
# Warmup Iteration   2: 7.287 ops/ms
# Warmup Iteration   3: 7.866 ops/ms
Iteration   1: 7.921 ops/ms
Iteration   2: 7.841 ops/ms
Iteration   3: 7.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.914 ±(99.9%) 1.275 ops/ms [Average]
  (min, avg, max) = (7.841, 7.914, 7.980), stdev = 0.070
  CI (99.9%): [6.639, 9.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.003 ms/op
Iteration   1: 3.147 ±(99.9%) 0.003 ms/op
Iteration   2: 3.275 ±(99.9%) 0.001 ms/op
Iteration   3: 3.248 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.223 ±(99.9%) 1.231 ms/op [Average]
  (min, avg, max) = (3.147, 3.223, 3.275), stdev = 0.067
  CI (99.9%): [1.992, 4.454] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
Iteration   1: 3.034 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 3.094 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.045 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (3.008, 3.045, 3.094), stdev = 0.044
  CI (99.9%): [2.239, 3.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.003 ms/op
Iteration   1: 3.148 ±(99.9%) 0.003 ms/op
Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
Iteration   3: 3.142 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.149 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (3.142, 3.149, 3.156), stdev = 0.007
  CI (99.9%): [3.022, 3.276] (assumes normal distribution)


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
# Warmup Iteration   1: 4.567 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.018 ms/op
Iteration   1: 3.913 ±(99.9%) 0.006 ms/op
Iteration   2: 3.986 ±(99.9%) 0.007 ms/op
Iteration   3: 4.009 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (3.913, 3.969, 4.009), stdev = 0.050
  CI (99.9%): [3.058, 4.880] (assumes normal distribution)


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.006 ms/op
Iteration   1: 3.242 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.596 ms/op
                 createUser·p0.9999: 14.123 ms/op
                 createUser·p1.00:   14.467 ms/op

Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.208 ms/op
                 createUser·p0.9999: 14.123 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  12.632 ms/op
                 createUser·p0.9999: 18.762 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305047
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 572 
    [ 1.250,  2.500) = 23479 
    [ 2.500,  3.750) = 245500 
    [ 3.750,  5.000) = 34196 
    [ 5.000,  6.250) = 733 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.420 ms/op
     p(99.9900) =     18.235 ms/op
     p(99.9990) =     18.938 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  8.086 ms/op
                 existUser·p0.9999: 13.181 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 2.925 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.299 ms/op
                 existUser·p0.9999: 23.825 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  8.211 ms/op
                 existUser·p0.9999: 17.160 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316162
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42000 
    [ 2.500,  5.000) = 273184 
    [ 5.000,  7.500) = 613 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.043 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 4.292 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
Iteration   1: 3.210 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.436 ms/op
                 getUser·p0.999:  6.827 ms/op
                 getUser·p0.9999: 16.122 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 17.891 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.200 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   4.450 ms/op
                 getUser·p0.999:  8.134 ms/op
                 getUser·p0.9999: 23.035 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300945
  mean =      3.191 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17440 
    [ 2.500,  5.000) = 282467 
    [ 5.000,  7.500) = 786 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.070 ms/op
     p(99.9900) =     21.897 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 5.840 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.011 ms/op
Iteration   1: 4.049 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.992 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.932 ms/op
                 listUser·p0.999:  14.789 ms/op
                 listUser·p0.9999: 19.665 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 4.089 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   6.886 ms/op
                 listUser·p0.999:  14.068 ms/op
                 listUser·p0.9999: 31.151 ms/op
                 listUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236091
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2216 
    [ 2.500,  5.000) = 206166 
    [ 5.000,  7.500) = 26456 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.775 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     31.979 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.143 ± 0.489  ops/ms
ClientGrpc.existUser                       thrpt       3  10.518 ± 2.376  ops/ms
ClientGrpc.getUser                         thrpt       3   9.978 ± 4.258  ops/ms
ClientGrpc.listUser                        thrpt       3   7.914 ± 1.275  ops/ms
ClientGrpc.createUser                       avgt       3   3.223 ± 1.231   ms/op
ClientGrpc.existUser                        avgt       3   3.045 ± 0.806   ms/op
ClientGrpc.getUser                          avgt       3   3.149 ± 0.127   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 0.911   ms/op
ClientGrpc.createUser                     sample  305047   3.147 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.716           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.420           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.235           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  316162   3.033 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.557           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.043           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.610           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.478           ms/op
ClientGrpc.getUser                        sample  300945   3.191 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.624           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.154           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.076           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.070           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.897           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  236091   4.068 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.030           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.775           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.474           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.113           ms/op
