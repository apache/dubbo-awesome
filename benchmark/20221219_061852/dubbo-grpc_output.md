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
# Warmup Iteration   1: 2.385 ops/ms
# Warmup Iteration   2: 5.432 ops/ms
# Warmup Iteration   3: 7.299 ops/ms
Iteration   1: 7.367 ops/ms
Iteration   2: 7.503 ops/ms
Iteration   3: 7.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.486 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (7.367, 7.486, 7.588), stdev = 0.111
  CI (99.9%): [5.454, 9.519] (assumes normal distribution)


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
# Warmup Iteration   1: 4.526 ops/ms
# Warmup Iteration   2: 7.221 ops/ms
# Warmup Iteration   3: 7.712 ops/ms
Iteration   1: 7.778 ops/ms
Iteration   2: 7.788 ops/ms
Iteration   3: 7.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.831 ±(99.9%) 1.521 ops/ms [Average]
  (min, avg, max) = (7.778, 7.831, 7.927), stdev = 0.083
  CI (99.9%): [6.310, 9.352] (assumes normal distribution)


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
# Warmup Iteration   1: 4.760 ops/ms
# Warmup Iteration   2: 7.042 ops/ms
# Warmup Iteration   3: 7.622 ops/ms
Iteration   1: 7.354 ops/ms
Iteration   2: 7.275 ops/ms
Iteration   3: 7.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.352 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (7.275, 7.352, 7.427), stdev = 0.076
  CI (99.9%): [5.965, 8.739] (assumes normal distribution)


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
# Warmup Iteration   1: 3.752 ops/ms
# Warmup Iteration   2: 5.509 ops/ms
# Warmup Iteration   3: 5.673 ops/ms
Iteration   1: 5.918 ops/ms
Iteration   2: 5.890 ops/ms
Iteration   3: 5.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.921 ±(99.9%) 0.611 ops/ms [Average]
  (min, avg, max) = (5.890, 5.921, 5.957), stdev = 0.033
  CI (99.9%): [5.311, 6.532] (assumes normal distribution)


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
# Warmup Iteration   1: 6.957 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.006 ms/op
Iteration   1: 4.226 ±(99.9%) 0.004 ms/op
Iteration   2: 4.379 ±(99.9%) 0.003 ms/op
Iteration   3: 4.187 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.264 ±(99.9%) 1.852 ms/op [Average]
  (min, avg, max) = (4.187, 4.264, 4.379), stdev = 0.102
  CI (99.9%): [2.412, 6.116] (assumes normal distribution)


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
# Warmup Iteration   1: 5.720 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.003 ms/op
Iteration   1: 3.807 ±(99.9%) 0.004 ms/op
Iteration   2: 3.864 ±(99.9%) 0.003 ms/op
Iteration   3: 3.866 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.846 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.807, 3.846, 3.866), stdev = 0.034
  CI (99.9%): [3.230, 4.461] (assumes normal distribution)


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
# Warmup Iteration   1: 6.126 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.337 ±(99.9%) 0.003 ms/op
Iteration   1: 4.257 ±(99.9%) 0.005 ms/op
Iteration   2: 4.314 ±(99.9%) 0.004 ms/op
Iteration   3: 4.207 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.259 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (4.207, 4.259, 4.314), stdev = 0.054
  CI (99.9%): [3.280, 5.238] (assumes normal distribution)


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
# Warmup Iteration   1: 7.515 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 6.011 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.497 ±(99.9%) 0.026 ms/op
Iteration   1: 5.437 ±(99.9%) 0.018 ms/op
Iteration   2: 5.467 ±(99.9%) 0.025 ms/op
Iteration   3: 5.263 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.389 ±(99.9%) 2.007 ms/op [Average]
  (min, avg, max) = (5.263, 5.389, 5.467), stdev = 0.110
  CI (99.9%): [3.382, 7.396] (assumes normal distribution)


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
# Warmup Iteration   1: 6.013 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.014 ms/op
Iteration   1: 4.459 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   7.455 ms/op
                 createUser·p0.999:  11.389 ms/op
                 createUser·p0.9999: 34.788 ms/op
                 createUser·p1.00:   35.324 ms/op

Iteration   2: 4.339 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.489 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.971 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 23.445 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 4.358 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  20.925 ms/op
                 createUser·p0.9999: 41.986 ms/op
                 createUser·p1.00:   42.402 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219000
  mean =      4.385 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 170094 
    [ 5.000, 10.000) = 48397 
    [10.000, 15.000) = 362 
    [15.000, 20.000) = 18 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     41.229 ms/op
     p(99.9990) =     42.311 ms/op
     p(99.9999) =     42.402 ms/op
    p(100.0000) =     42.402 ms/op


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
# Warmup Iteration   1: 6.048 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.482 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.012 ms/op
Iteration   1: 4.117 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.381 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.685 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  11.517 ms/op
                 existUser·p0.9999: 16.027 ms/op
                 existUser·p1.00:   16.433 ms/op

Iteration   2: 4.145 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  10.434 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   3: 4.031 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  10.380 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 234279
  mean =      4.097 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 180 
    [ 1.250,  2.500) = 9862 
    [ 2.500,  3.750) = 75624 
    [ 3.750,  5.000) = 113642 
    [ 5.000,  6.250) = 31405 
    [ 6.250,  7.500) = 2319 
    [ 7.500,  8.750) = 643 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 158 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     18.959 ms/op
     p(99.9990) =     19.474 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 6.317 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.362 ±(99.9%) 0.012 ms/op
Iteration   1: 4.398 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   7.873 ms/op
                 getUser·p0.999:  16.716 ms/op
                 getUser·p0.9999: 19.994 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 4.291 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   4.162 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  12.444 ms/op
                 getUser·p0.9999: 30.623 ms/op
                 getUser·p1.00:   31.326 ms/op

Iteration   3: 4.231 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   4.100 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   6.827 ms/op
                 getUser·p0.999:  9.664 ms/op
                 getUser·p0.9999: 23.982 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 222812
  mean =      4.306 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2690 
    [ 2.500,  5.000) = 176946 
    [ 5.000,  7.500) = 41174 
    [ 7.500, 10.000) = 1432 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      4.170 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.323 ms/op
     p(99.9000) =     13.507 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     31.165 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 7.563 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.686 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.218 ±(99.9%) 0.018 ms/op
Iteration   1: 5.444 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.166 ms/op
                 listUser·p0.99:   10.479 ms/op
                 listUser·p0.999:  16.311 ms/op
                 listUser·p0.9999: 19.178 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 5.254 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   6.742 ms/op
                 listUser·p0.95:   7.610 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 21.618 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 5.177 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.463 ms/op
                 listUser·p0.99:   10.174 ms/op
                 listUser·p0.999:  20.883 ms/op
                 listUser·p0.9999: 25.330 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181448
  mean =      5.290 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 216 
    [ 2.500,  5.000) = 89142 
    [ 5.000,  7.500) = 80883 
    [ 7.500, 10.000) = 9241 
    [10.000, 12.500) = 1362 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     24.571 ms/op
     p(99.9990) =     25.900 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.486 ± 2.033  ops/ms
ClientGrpc.existUser                       thrpt       3   7.831 ± 1.521  ops/ms
ClientGrpc.getUser                         thrpt       3   7.352 ± 1.387  ops/ms
ClientGrpc.listUser                        thrpt       3   5.921 ± 0.611  ops/ms
ClientGrpc.createUser                       avgt       3   4.264 ± 1.852   ms/op
ClientGrpc.existUser                        avgt       3   3.846 ± 0.616   ms/op
ClientGrpc.getUser                          avgt       3   4.259 ± 0.979   ms/op
ClientGrpc.listUser                         avgt       3   5.389 ± 2.007   ms/op
ClientGrpc.createUser                     sample  219000   4.385 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.098           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.939           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.528           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.763           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          41.229           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          42.402           ms/op
ClientGrpc.existUser                      sample  234279   4.097 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.381           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.030           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.612           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.627           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.748           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.959           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  222812   4.306 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.892           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.323           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.507           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.886           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.326           ms/op
ClientGrpc.listUser                       sample  181448   5.290 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.184           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.774           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.125           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.571           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.968           ms/op
