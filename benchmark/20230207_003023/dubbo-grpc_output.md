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
# Warmup Iteration   1: 4.923 ops/ms
# Warmup Iteration   2: 8.861 ops/ms
# Warmup Iteration   3: 10.772 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.095 ops/ms
Iteration   3: 10.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.397 ±(99.9%) 4.896 ops/ms [Average]
  (min, avg, max) = (10.095, 10.397, 10.608), stdev = 0.268
  CI (99.9%): [5.502, 15.293] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.087 ops/ms
# Warmup Iteration   2: 10.589 ops/ms
# Warmup Iteration   3: 10.968 ops/ms
Iteration   1: 11.046 ops/ms
Iteration   2: 10.842 ops/ms
Iteration   3: 10.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.885 ±(99.9%) 2.636 ops/ms [Average]
  (min, avg, max) = (10.766, 10.885, 11.046), stdev = 0.144
  CI (99.9%): [8.249, 13.521] (assumes normal distribution)


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
# Warmup Iteration   1: 8.187 ops/ms
# Warmup Iteration   2: 10.216 ops/ms
# Warmup Iteration   3: 10.690 ops/ms
Iteration   1: 10.457 ops/ms
Iteration   2: 10.525 ops/ms
Iteration   3: 10.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.568 ±(99.9%) 2.507 ops/ms [Average]
  (min, avg, max) = (10.457, 10.568, 10.722), stdev = 0.137
  CI (99.9%): [8.061, 13.075] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.024 ops/ms
# Warmup Iteration   2: 7.985 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.160 ops/ms
Iteration   2: 7.960 ops/ms
Iteration   3: 8.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.128 ±(99.9%) 2.801 ops/ms [Average]
  (min, avg, max) = (7.960, 8.128, 8.262), stdev = 0.154
  CI (99.9%): [5.327, 10.929] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.001 ms/op
Iteration   2: 3.136 ±(99.9%) 0.001 ms/op
Iteration   3: 3.041 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.092 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (3.041, 3.092, 3.136), stdev = 0.048
  CI (99.9%): [2.217, 3.967] (assumes normal distribution)


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.921 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.003 ms/op
Iteration   1: 2.928 ±(99.9%) 0.002 ms/op
Iteration   2: 2.892 ±(99.9%) 0.003 ms/op
Iteration   3: 2.944 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (2.892, 2.921, 2.944), stdev = 0.027
  CI (99.9%): [2.438, 3.405] (assumes normal distribution)


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.002 ms/op
Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
Iteration   3: 3.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.036 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (3.026, 3.036, 3.045), stdev = 0.010
  CI (99.9%): [2.862, 3.210] (assumes normal distribution)


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.016 ms/op
Iteration   1: 4.016 ±(99.9%) 0.030 ms/op
Iteration   2: 3.938 ±(99.9%) 0.037 ms/op
Iteration   3: 3.933 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.962 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.933, 3.962, 4.016), stdev = 0.047
  CI (99.9%): [3.110, 4.815] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.126 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  8.166 ms/op
                 createUser·p0.9999: 11.769 ms/op
                 createUser·p1.00:   12.190 ms/op

Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.327 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.506 ms/op
                 createUser·p0.9999: 13.746 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.725 ms/op
                 createUser·p0.9999: 16.888 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307408
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24221 
    [ 2.500,  5.000) = 282260 
    [ 5.000,  7.500) = 568 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.913 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     17.657 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.406 ms/op
                 existUser·p0.9999: 11.587 ms/op
                 existUser·p1.00:   11.846 ms/op

Iteration   2: 2.841 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.452 ms/op
                 existUser·p0.9999: 12.665 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.672 ms/op
                 existUser·p0.9999: 14.039 ms/op
                 existUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331776
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2474 
    [ 1.250,  2.500) = 55159 
    [ 2.500,  3.750) = 261245 
    [ 3.750,  5.000) = 12138 
    [ 5.000,  6.250) = 441 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.683 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.169 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.599 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.007 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.288 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.556 ms/op
                 getUser·p0.9999: 15.172 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.498 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.215 ms/op
                 getUser·p0.9999: 14.769 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.498 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.277 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323520
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3470 
    [ 1.250,  2.500) = 27672 
    [ 2.500,  3.750) = 279441 
    [ 3.750,  5.000) = 12112 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 93 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.644 ms/op
     p(99.9900) =     17.224 ms/op
     p(99.9990) =     19.065 ms/op
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
# Warmup Iteration   1: 4.895 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.011 ms/op
Iteration   1: 3.963 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  12.515 ms/op
                 listUser·p0.9999: 18.148 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   2: 3.919 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.788 ms/op
                 listUser·p0.9999: 15.294 ms/op
                 listUser·p1.00:   15.598 ms/op

Iteration   3: 3.793 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 21.318 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246898
  mean =      3.890 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4763 
    [ 2.500,  5.000) = 220309 
    [ 5.000,  7.500) = 20860 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     20.523 ms/op
     p(99.9990) =     21.535 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.397 ± 4.896  ops/ms
ClientGrpc.existUser                       thrpt       3  10.885 ± 2.636  ops/ms
ClientGrpc.getUser                         thrpt       3  10.568 ± 2.507  ops/ms
ClientGrpc.listUser                        thrpt       3   8.128 ± 2.801  ops/ms
ClientGrpc.createUser                       avgt       3   3.092 ± 0.875   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.484   ms/op
ClientGrpc.getUser                          avgt       3   3.036 ± 0.174   ms/op
ClientGrpc.listUser                         avgt       3   3.962 ± 0.853   ms/op
ClientGrpc.createUser                     sample  307408   3.121 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.327           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.965           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.913           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.942           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.087           ms/op
ClientGrpc.existUser                      sample  331776   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.600           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.683           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.169           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.566           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.713           ms/op
ClientGrpc.getUser                        sample  323520   2.967 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.288           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.644           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.224           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.104           ms/op
ClientGrpc.listUser                       sample  246898   3.890 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.919           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.523           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.774           ms/op
