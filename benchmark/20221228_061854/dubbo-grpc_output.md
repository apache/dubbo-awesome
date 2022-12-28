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
# Warmup Iteration   1: 2.284 ops/ms
# Warmup Iteration   2: 5.512 ops/ms
# Warmup Iteration   3: 6.885 ops/ms
Iteration   1: 7.276 ops/ms
Iteration   2: 7.274 ops/ms
Iteration   3: 7.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.250 ±(99.9%) 0.794 ops/ms [Average]
  (min, avg, max) = (7.199, 7.250, 7.276), stdev = 0.044
  CI (99.9%): [6.455, 8.044] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.775 ops/ms
# Warmup Iteration   2: 7.162 ops/ms
# Warmup Iteration   3: 7.408 ops/ms
Iteration   1: 7.838 ops/ms
Iteration   2: 7.387 ops/ms
Iteration   3: 7.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.631 ±(99.9%) 4.151 ops/ms [Average]
  (min, avg, max) = (7.387, 7.631, 7.838), stdev = 0.228
  CI (99.9%): [3.480, 11.781] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ops/ms
# Warmup Iteration   2: 6.656 ops/ms
# Warmup Iteration   3: 6.980 ops/ms
Iteration   1: 7.318 ops/ms
Iteration   2: 7.334 ops/ms
Iteration   3: 7.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.427 ±(99.9%) 3.205 ops/ms [Average]
  (min, avg, max) = (7.318, 7.427, 7.630), stdev = 0.176
  CI (99.9%): [4.222, 10.632] (assumes normal distribution)


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
# Warmup Iteration   1: 3.786 ops/ms
# Warmup Iteration   2: 5.029 ops/ms
# Warmup Iteration   3: 5.559 ops/ms
Iteration   1: 5.520 ops/ms
Iteration   2: 5.699 ops/ms
Iteration   3: 5.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.645 ±(99.9%) 1.982 ops/ms [Average]
  (min, avg, max) = (5.520, 5.645, 5.717), stdev = 0.109
  CI (99.9%): [3.664, 7.627] (assumes normal distribution)


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
# Warmup Iteration   1: 6.655 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.673 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.433 ±(99.9%) 0.003 ms/op
Iteration   1: 4.404 ±(99.9%) 0.003 ms/op
Iteration   2: 4.650 ±(99.9%) 0.004 ms/op
Iteration   3: 4.538 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.531 ±(99.9%) 2.244 ms/op [Average]
  (min, avg, max) = (4.404, 4.531, 4.650), stdev = 0.123
  CI (99.9%): [2.286, 6.775] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.264 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.008 ms/op
Iteration   1: 4.338 ±(99.9%) 0.003 ms/op
Iteration   2: 4.282 ±(99.9%) 0.004 ms/op
Iteration   3: 4.119 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.247 ±(99.9%) 2.074 ms/op [Average]
  (min, avg, max) = (4.119, 4.247, 4.338), stdev = 0.114
  CI (99.9%): [2.173, 6.320] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.408 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.849 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.515 ±(99.9%) 0.004 ms/op
Iteration   1: 4.346 ±(99.9%) 0.007 ms/op
Iteration   2: 4.402 ±(99.9%) 0.004 ms/op
Iteration   3: 4.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.400 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (4.346, 4.400, 4.450), stdev = 0.052
  CI (99.9%): [3.452, 5.348] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.934 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 6.148 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.535 ±(99.9%) 0.026 ms/op
Iteration   1: 5.386 ±(99.9%) 0.011 ms/op
Iteration   2: 5.507 ±(99.9%) 0.006 ms/op
Iteration   3: 5.366 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.420 ±(99.9%) 1.386 ms/op [Average]
  (min, avg, max) = (5.366, 5.420, 5.507), stdev = 0.076
  CI (99.9%): [4.034, 6.806] (assumes normal distribution)


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
# Warmup Iteration   1: 6.894 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.710 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.562 ±(99.9%) 0.014 ms/op
Iteration   1: 4.449 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.612 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  12.845 ms/op
                 createUser·p0.9999: 21.732 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   2: 4.424 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.562 ms/op
                 createUser·p0.95:   5.882 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  14.369 ms/op
                 createUser·p0.9999: 21.514 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   3: 4.561 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   4.473 ms/op
                 createUser·p0.90:   5.802 ms/op
                 createUser·p0.95:   6.160 ms/op
                 createUser·p0.99:   7.683 ms/op
                 createUser·p0.999:  12.416 ms/op
                 createUser·p0.9999: 25.395 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214376
  mean =      4.477 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3036 
    [ 2.500,  5.000) = 154425 
    [ 5.000,  7.500) = 54901 
    [ 7.500, 10.000) = 1283 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.383 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     26.186 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 6.526 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.429 ±(99.9%) 0.013 ms/op
Iteration   1: 4.560 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.431 ms/op
                 existUser·p0.99:   8.911 ms/op
                 existUser·p0.999:  13.857 ms/op
                 existUser·p0.9999: 18.349 ms/op
                 existUser·p1.00:   18.645 ms/op

Iteration   2: 4.435 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   4.301 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.038 ms/op
                 existUser·p0.99:   8.119 ms/op
                 existUser·p0.999:  14.529 ms/op
                 existUser·p0.9999: 20.347 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   3: 4.304 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   5.718 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  14.921 ms/op
                 existUser·p0.9999: 63.241 ms/op
                 existUser·p1.00:   65.208 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 216595
  mean =      4.430 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 162880 
    [ 5.000, 10.000) = 52695 
    [10.000, 15.000) = 858 
    [15.000, 20.000) = 114 
    [20.000, 25.000) = 16 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     60.686 ms/op
     p(99.9990) =     65.208 ms/op
     p(99.9999) =     65.208 ms/op
    p(100.0000) =     65.208 ms/op


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
# Warmup Iteration   1: 6.480 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.809 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.556 ±(99.9%) 0.014 ms/op
Iteration   1: 4.471 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.249 ms/op
                 getUser·p0.999:  11.591 ms/op
                 getUser·p0.9999: 22.605 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 4.565 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   4.481 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  13.839 ms/op
                 getUser·p0.9999: 25.166 ms/op
                 getUser·p1.00:   27.066 ms/op

Iteration   3: 4.439 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  12.773 ms/op
                 getUser·p0.9999: 27.912 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213682
  mean =      4.491 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4173 
    [ 2.500,  5.000) = 151206 
    [ 5.000,  7.500) = 56037 
    [ 7.500, 10.000) = 1708 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     12.457 ms/op
     p(99.9900) =     27.354 ms/op
     p(99.9990) =     30.534 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.136 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.932 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.565 ±(99.9%) 0.018 ms/op
Iteration   1: 5.234 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   6.504 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 17.855 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   2: 5.498 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.160 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 19.461 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 5.436 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  20.322 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178085
  mean =      5.387 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 156 
    [ 2.500,  5.000) = 74331 
    [ 5.000,  7.500) = 92324 
    [ 7.500, 10.000) = 9590 
    [10.000, 12.500) = 1107 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.898 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     22.301 ms/op
     p(99.9990) =     23.043 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.250 ± 0.794  ops/ms
ClientGrpc.existUser                       thrpt       3   7.631 ± 4.151  ops/ms
ClientGrpc.getUser                         thrpt       3   7.427 ± 3.205  ops/ms
ClientGrpc.listUser                        thrpt       3   5.645 ± 1.982  ops/ms
ClientGrpc.createUser                       avgt       3   4.531 ± 2.244   ms/op
ClientGrpc.existUser                        avgt       3   4.247 ± 2.074   ms/op
ClientGrpc.getUser                          avgt       3   4.400 ± 0.948   ms/op
ClientGrpc.listUser                         avgt       3   5.420 ± 1.386   ms/op
ClientGrpc.createUser                     sample  214376   4.477 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.051           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.029           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.074           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.773           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.411           ms/op
ClientGrpc.existUser                      sample  216595   4.430 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.955           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.644           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.062           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.143           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.402           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          60.686           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          65.208           ms/op
ClientGrpc.getUser                        sample  213682   4.491 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.641           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.685           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.062           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.619           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.457           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.354           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.704           ms/op
ClientGrpc.listUser                       sample  178085   5.387 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.135           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.774           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.912           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.301           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.069           ms/op
