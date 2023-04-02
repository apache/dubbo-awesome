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
# Warmup Iteration   1: 2.928 ops/ms
# Warmup Iteration   2: 7.616 ops/ms
# Warmup Iteration   3: 7.898 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 8.300 ops/ms
Iteration   3: 8.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.365 ±(99.9%) 3.673 ops/ms [Average]
  (min, avg, max) = (8.204, 8.365, 8.591), stdev = 0.201
  CI (99.9%): [4.692, 12.037] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.590 ops/ms
# Warmup Iteration   2: 8.872 ops/ms
# Warmup Iteration   3: 9.637 ops/ms
Iteration   1: 9.367 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.417 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (9.367, 9.417, 9.467), stdev = 0.050
  CI (99.9%): [8.501, 10.334] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.323 ops/ms
# Warmup Iteration   2: 8.674 ops/ms
# Warmup Iteration   3: 8.839 ops/ms
Iteration   1: 8.877 ops/ms
Iteration   2: 8.618 ops/ms
Iteration   3: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.887 ±(99.9%) 5.004 ops/ms [Average]
  (min, avg, max) = (8.618, 8.887, 9.166), stdev = 0.274
  CI (99.9%): [3.884, 13.891] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.676 ops/ms
# Warmup Iteration   2: 6.235 ops/ms
# Warmup Iteration   3: 6.289 ops/ms
Iteration   1: 6.144 ops/ms
Iteration   2: 6.412 ops/ms
Iteration   3: 6.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.327 ±(99.9%) 2.898 ops/ms [Average]
  (min, avg, max) = (6.144, 6.327, 6.425), stdev = 0.159
  CI (99.9%): [3.429, 9.225] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.621 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.007 ms/op
Iteration   1: 3.571 ±(99.9%) 0.004 ms/op
Iteration   2: 3.544 ±(99.9%) 0.003 ms/op
Iteration   3: 3.568 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.561 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (3.544, 3.561, 3.571), stdev = 0.015
  CI (99.9%): [3.288, 3.834] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.994 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.002 ms/op
Iteration   1: 3.297 ±(99.9%) 0.002 ms/op
Iteration   2: 3.356 ±(99.9%) 0.002 ms/op
Iteration   3: 3.381 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.345 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.297, 3.345, 3.381), stdev = 0.043
  CI (99.9%): [2.563, 4.127] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.486 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.003 ms/op
Iteration   1: 3.865 ±(99.9%) 0.005 ms/op
Iteration   2: 3.720 ±(99.9%) 0.004 ms/op
Iteration   3: 3.636 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.740 ±(99.9%) 2.118 ms/op [Average]
  (min, avg, max) = (3.636, 3.740, 3.865), stdev = 0.116
  CI (99.9%): [1.622, 5.858] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.848 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.027 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.978 ±(99.9%) 0.029 ms/op
Iteration   1: 4.953 ±(99.9%) 0.018 ms/op
Iteration   2: 5.160 ±(99.9%) 0.026 ms/op
Iteration   3: 5.008 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.040 ±(99.9%) 1.955 ms/op [Average]
  (min, avg, max) = (4.953, 5.040, 5.160), stdev = 0.107
  CI (99.9%): [3.085, 6.995] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.071 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.009 ms/op
Iteration   1: 3.497 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  12.199 ms/op
                 createUser·p0.9999: 18.182 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   2: 3.489 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  12.517 ms/op
                 createUser·p0.9999: 37.017 ms/op
                 createUser·p1.00:   37.749 ms/op

Iteration   3: 3.606 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  13.553 ms/op
                 createUser·p0.9999: 24.482 ms/op
                 createUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271924
  mean =      3.530 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7376 
    [ 2.500,  5.000) = 258477 
    [ 5.000,  7.500) = 5073 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     35.881 ms/op
     p(99.9990) =     37.476 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.585 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.007 ms/op
Iteration   1: 3.377 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  10.856 ms/op
                 existUser·p0.9999: 18.105 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   2: 3.358 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  10.073 ms/op
                 existUser·p0.9999: 16.441 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 3.307 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  12.616 ms/op
                 existUser·p0.9999: 19.104 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 286637
  mean =      3.347 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 321 
    [ 1.250,  2.500) = 7786 
    [ 2.500,  3.750) = 225781 
    [ 3.750,  5.000) = 48014 
    [ 5.000,  6.250) = 2875 
    [ 6.250,  7.500) = 812 
    [ 7.500,  8.750) = 503 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 180 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     18.667 ms/op
     p(99.9990) =     19.375 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.039 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.010 ms/op
Iteration   1: 3.759 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  11.600 ms/op
                 getUser·p0.9999: 28.622 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   2: 3.631 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.873 ms/op
                 getUser·p0.999:  14.515 ms/op
                 getUser·p0.9999: 22.786 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   3: 3.606 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  12.261 ms/op
                 getUser·p0.9999: 22.418 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262027
  mean =      3.664 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5679 
    [ 2.500,  5.000) = 245583 
    [ 5.000,  7.500) = 9618 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     22.826 ms/op
     p(99.9990) =     29.090 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 8.038 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.451 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.091 ±(99.9%) 0.020 ms/op
Iteration   1: 4.826 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.439 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  16.695 ms/op
                 listUser·p0.9999: 21.365 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 4.799 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 28.541 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   3: 4.601 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   6.029 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  19.215 ms/op
                 listUser·p0.9999: 23.265 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202527
  mean =      4.740 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 419 
    [ 2.500,  5.000) = 147243 
    [ 5.000,  7.500) = 46680 
    [ 7.500, 10.000) = 6611 
    [10.000, 12.500) = 916 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     27.091 ms/op
     p(99.9990) =     28.704 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.365 ± 3.673  ops/ms
ClientGrpc.existUser                       thrpt       3   9.417 ± 0.916  ops/ms
ClientGrpc.getUser                         thrpt       3   8.887 ± 5.004  ops/ms
ClientGrpc.listUser                        thrpt       3   6.327 ± 2.898  ops/ms
ClientGrpc.createUser                       avgt       3   3.561 ± 0.273   ms/op
ClientGrpc.existUser                        avgt       3   3.345 ± 0.782   ms/op
ClientGrpc.getUser                          avgt       3   3.740 ± 2.118   ms/op
ClientGrpc.listUser                         avgt       3   5.040 ± 1.955   ms/op
ClientGrpc.createUser                     sample  271924   3.530 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.942           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.714           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.881           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          37.749           ms/op
ClientGrpc.existUser                      sample  286637   3.347 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.653           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.092           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.667           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.530           ms/op
ClientGrpc.getUser                        sample  262027   3.664 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.818           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.226           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.370           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.826           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.196           ms/op
ClientGrpc.listUser                       sample  202527   4.740 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.210           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.373           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.486           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.186           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.091           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.803           ms/op
