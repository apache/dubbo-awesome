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
# Warmup Iteration   1: 3.066 ops/ms
# Warmup Iteration   2: 6.267 ops/ms
# Warmup Iteration   3: 7.536 ops/ms
Iteration   1: 7.517 ops/ms
Iteration   2: 7.877 ops/ms
Iteration   3: 7.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.673 ±(99.9%) 3.379 ops/ms [Average]
  (min, avg, max) = (7.517, 7.673, 7.877), stdev = 0.185
  CI (99.9%): [4.293, 11.052] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 6.178 ops/ms
# Warmup Iteration   2: 7.765 ops/ms
# Warmup Iteration   3: 8.120 ops/ms
Iteration   1: 8.355 ops/ms
Iteration   2: 8.167 ops/ms
Iteration   3: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.178 ±(99.9%) 3.130 ops/ms [Average]
  (min, avg, max) = (8.012, 8.178, 8.355), stdev = 0.172
  CI (99.9%): [5.048, 11.308] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.602 ops/ms
# Warmup Iteration   2: 7.518 ops/ms
# Warmup Iteration   3: 7.894 ops/ms
Iteration   1: 7.933 ops/ms
Iteration   2: 7.942 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.889 ±(99.9%) 1.533 ops/ms [Average]
  (min, avg, max) = (7.792, 7.889, 7.942), stdev = 0.084
  CI (99.9%): [6.356, 9.422] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.542 ops/ms
# Warmup Iteration   2: 5.309 ops/ms
# Warmup Iteration   3: 6.196 ops/ms
Iteration   1: 6.220 ops/ms
Iteration   2: 6.391 ops/ms
Iteration   3: 6.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.317 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (6.220, 6.317, 6.391), stdev = 0.088
  CI (99.9%): [4.716, 7.919] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.814 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.003 ms/op
Iteration   1: 4.017 ±(99.9%) 0.004 ms/op
Iteration   2: 4.120 ±(99.9%) 0.003 ms/op
Iteration   3: 4.091 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.076 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (4.017, 4.076, 4.120), stdev = 0.053
  CI (99.9%): [3.110, 5.043] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.003 ms/op
Iteration   1: 3.968 ±(99.9%) 0.003 ms/op
Iteration   2: 3.827 ±(99.9%) 0.003 ms/op
Iteration   3: 3.929 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.908 ±(99.9%) 1.330 ms/op [Average]
  (min, avg, max) = (3.827, 3.908, 3.968), stdev = 0.073
  CI (99.9%): [2.578, 5.238] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.966 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
Iteration   1: 4.057 ±(99.9%) 0.004 ms/op
Iteration   2: 4.141 ±(99.9%) 0.004 ms/op
Iteration   3: 4.150 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.116 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (4.057, 4.116, 4.150), stdev = 0.051
  CI (99.9%): [3.187, 5.044] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.099 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.294 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.035 ±(99.9%) 0.012 ms/op
Iteration   1: 5.163 ±(99.9%) 0.016 ms/op
Iteration   2: 5.066 ±(99.9%) 0.014 ms/op
Iteration   3: 4.915 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.048 ±(99.9%) 2.287 ms/op [Average]
  (min, avg, max) = (4.915, 5.048, 5.163), stdev = 0.125
  CI (99.9%): [2.761, 7.335] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.056 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.011 ms/op
Iteration   1: 3.995 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   5.382 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  11.943 ms/op
                 createUser·p0.9999: 16.874 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 4.057 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   5.014 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  15.321 ms/op
                 createUser·p0.9999: 17.469 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   3: 4.188 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   4.088 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  12.166 ms/op
                 createUser·p0.9999: 35.609 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235548
  mean =      4.078 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6186 
    [ 2.500,  5.000) = 203790 
    [ 5.000,  7.500) = 24125 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     33.074 ms/op
     p(99.9990) =     35.998 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.424 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
Iteration   1: 3.878 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 22.463 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.932 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  12.135 ms/op
                 existUser·p0.9999: 21.749 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 3.986 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  9.780 ms/op
                 existUser·p0.9999: 20.576 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244172
  mean =      3.931 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10899 
    [ 2.500,  5.000) = 215188 
    [ 5.000,  7.500) = 16764 
    [ 7.500, 10.000) = 866 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     23.204 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.000 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.011 ms/op
Iteration   1: 4.036 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  10.370 ms/op
                 getUser·p0.9999: 15.422 ms/op
                 getUser·p1.00:   15.761 ms/op

Iteration   2: 4.097 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   4.088 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  10.484 ms/op
                 getUser·p0.9999: 19.175 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   3: 4.080 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   4.014 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  12.503 ms/op
                 getUser·p0.9999: 28.234 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235829
  mean =      4.071 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7222 
    [ 2.500,  5.000) = 203369 
    [ 5.000,  7.500) = 24103 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     10.570 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     28.646 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.448 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.669 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.270 ±(99.9%) 0.017 ms/op
Iteration   1: 5.118 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.627 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  16.615 ms/op
                 listUser·p0.9999: 18.367 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   2: 5.171 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   6.750 ms/op
                 listUser·p0.95:   7.673 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 24.209 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 5.141 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  26.879 ms/op
                 listUser·p0.9999: 35.914 ms/op
                 listUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186519
  mean =      5.143 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 238 
    [ 2.500,  5.000) = 105027 
    [ 5.000,  7.500) = 71801 
    [ 7.500, 10.000) = 8331 
    [10.000, 12.500) = 723 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.512 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     35.347 ms/op
     p(99.9990) =     36.071 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.673 ± 3.379  ops/ms
ClientGrpc.existUser                       thrpt       3   8.178 ± 3.130  ops/ms
ClientGrpc.getUser                         thrpt       3   7.889 ± 1.533  ops/ms
ClientGrpc.listUser                        thrpt       3   6.317 ± 1.601  ops/ms
ClientGrpc.createUser                       avgt       3   4.076 ± 0.966   ms/op
ClientGrpc.existUser                        avgt       3   3.908 ± 1.330   ms/op
ClientGrpc.getUser                          avgt       3   4.116 ± 0.928   ms/op
ClientGrpc.listUser                         avgt       3   5.048 ± 2.287   ms/op
ClientGrpc.createUser                     sample  235548   4.078 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.032           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.734           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.861           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.074           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.110           ms/op
ClientGrpc.existUser                      sample  244172   3.931 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.881           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.858           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.194           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.562           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.272           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.889           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.298           ms/op
ClientGrpc.getUser                        sample  235829   4.071 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.051           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.038           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.358           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.488           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.570           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.739           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.770           ms/op
ClientGrpc.listUser                       sample  186519   5.143 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.167           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.512           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.339           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.793           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.347           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.241           ms/op
