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
# Warmup Iteration   1: 3.908 ops/ms
# Warmup Iteration   2: 8.724 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 9.922 ops/ms
Iteration   2: 9.567 ops/ms
Iteration   3: 9.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.757 ±(99.9%) 3.265 ops/ms [Average]
  (min, avg, max) = (9.567, 9.757, 9.922), stdev = 0.179
  CI (99.9%): [6.492, 13.022] (assumes normal distribution)


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
# Warmup Iteration   1: 7.370 ops/ms
# Warmup Iteration   2: 9.779 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.032 ops/ms
Iteration   2: 10.285 ops/ms
Iteration   3: 10.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.204 ±(99.9%) 2.722 ops/ms [Average]
  (min, avg, max) = (10.032, 10.204, 10.295), stdev = 0.149
  CI (99.9%): [7.482, 12.926] (assumes normal distribution)


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
# Warmup Iteration   1: 6.651 ops/ms
# Warmup Iteration   2: 9.746 ops/ms
# Warmup Iteration   3: 9.833 ops/ms
Iteration   1: 9.868 ops/ms
Iteration   2: 10.044 ops/ms
Iteration   3: 9.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.926 ±(99.9%) 1.858 ops/ms [Average]
  (min, avg, max) = (9.866, 9.926, 10.044), stdev = 0.102
  CI (99.9%): [8.068, 11.784] (assumes normal distribution)


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
# Warmup Iteration   1: 4.923 ops/ms
# Warmup Iteration   2: 7.210 ops/ms
# Warmup Iteration   3: 7.584 ops/ms
Iteration   1: 7.817 ops/ms
Iteration   2: 7.786 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.798 ±(99.9%) 0.307 ops/ms [Average]
  (min, avg, max) = (7.786, 7.798, 7.817), stdev = 0.017
  CI (99.9%): [7.491, 8.105] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.621 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.002 ms/op
Iteration   1: 3.241 ±(99.9%) 0.002 ms/op
Iteration   2: 3.213 ±(99.9%) 0.004 ms/op
Iteration   3: 3.202 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.219 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (3.202, 3.219, 3.241), stdev = 0.020
  CI (99.9%): [2.847, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.003 ms/op
Iteration   1: 3.084 ±(99.9%) 0.003 ms/op
Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
Iteration   3: 3.050 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.051 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.017, 3.051, 3.084), stdev = 0.034
  CI (99.9%): [2.436, 3.665] (assumes normal distribution)


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
# Warmup Iteration   1: 4.575 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.002 ms/op
Iteration   1: 3.167 ±(99.9%) 0.003 ms/op
Iteration   2: 3.222 ±(99.9%) 0.002 ms/op
Iteration   3: 3.263 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.217 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (3.167, 3.217, 3.263), stdev = 0.048
  CI (99.9%): [2.339, 4.096] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.127 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.027 ms/op
Iteration   1: 4.070 ±(99.9%) 0.037 ms/op
Iteration   2: 4.164 ±(99.9%) 0.019 ms/op
Iteration   3: 3.995 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.076 ±(99.9%) 1.544 ms/op [Average]
  (min, avg, max) = (3.995, 4.076, 4.164), stdev = 0.085
  CI (99.9%): [2.532, 5.621] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.667 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
Iteration   1: 3.203 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  8.072 ms/op
                 createUser·p0.9999: 18.580 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  7.436 ms/op
                 createUser·p0.9999: 26.474 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   3: 3.251 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  11.843 ms/op
                 createUser·p0.9999: 21.703 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298904
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23515 
    [ 2.500,  5.000) = 272219 
    [ 5.000,  7.500) = 2770 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.095 ms/op
     p(99.9000) =      8.022 ms/op
     p(99.9900) =     25.956 ms/op
     p(99.9990) =     27.563 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  7.854 ms/op
                 existUser·p0.9999: 14.014 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 3.104 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  11.943 ms/op
                 existUser·p0.9999: 30.094 ms/op
                 existUser·p1.00:   30.573 ms/op

Iteration   3: 3.105 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  7.922 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 309295
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35573 
    [ 2.500,  5.000) = 270784 
    [ 5.000,  7.500) = 2387 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.948 ms/op
     p(99.9000) =      9.154 ms/op
     p(99.9900) =     29.138 ms/op
     p(99.9990) =     30.435 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.008 ms/op
Iteration   1: 3.192 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  10.034 ms/op
                 getUser·p0.9999: 14.860 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  8.334 ms/op
                 getUser·p0.9999: 16.634 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 3.233 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  8.125 ms/op
                 getUser·p0.9999: 18.320 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297929
  mean =      3.222 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 556 
    [ 1.250,  2.500) = 22295 
    [ 2.500,  3.750) = 228080 
    [ 3.750,  5.000) = 43679 
    [ 5.000,  6.250) = 2018 
    [ 6.250,  7.500) = 729 
    [ 7.500,  8.750) = 295 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =      8.439 ms/op
     p(99.9900) =     17.479 ms/op
     p(99.9990) =     18.699 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 6.138 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.013 ms/op
Iteration   1: 4.155 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  16.719 ms/op
                 listUser·p0.9999: 21.931 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 4.220 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  20.526 ms/op
                 listUser·p0.9999: 27.060 ms/op
                 listUser·p1.00:   27.427 ms/op

Iteration   3: 4.216 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  23.104 ms/op
                 listUser·p0.9999: 31.445 ms/op
                 listUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228976
  mean =      4.197 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2367 
    [ 2.500,  5.000) = 189591 
    [ 5.000,  7.500) = 34277 
    [ 7.500, 10.000) = 2053 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     30.248 ms/op
     p(99.9990) =     31.644 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.757 ± 3.265  ops/ms
ClientGrpc.existUser                       thrpt       3  10.204 ± 2.722  ops/ms
ClientGrpc.getUser                         thrpt       3   9.926 ± 1.858  ops/ms
ClientGrpc.listUser                        thrpt       3   7.798 ± 0.307  ops/ms
ClientGrpc.createUser                       avgt       3   3.219 ± 0.372   ms/op
ClientGrpc.existUser                        avgt       3   3.051 ± 0.614   ms/op
ClientGrpc.getUser                          avgt       3   3.217 ± 0.879   ms/op
ClientGrpc.listUser                         avgt       3   4.076 ± 1.544   ms/op
ClientGrpc.createUser                     sample  298904   3.212 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.752           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.116           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.095           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.022           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.956           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.770           ms/op
ClientGrpc.existUser                      sample  309295   3.103 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.554           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.948           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.154           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.138           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.573           ms/op
ClientGrpc.getUser                        sample  297929   3.222 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.636           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.187           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.439           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.479           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.825           ms/op
ClientGrpc.listUser                       sample  228976   4.197 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.933           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.953           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.684           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.366           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.248           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.752           ms/op
