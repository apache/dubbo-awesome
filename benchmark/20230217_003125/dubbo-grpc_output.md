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
# Warmup Iteration   1: 2.274 ops/ms
# Warmup Iteration   2: 5.448 ops/ms
# Warmup Iteration   3: 6.942 ops/ms
Iteration   1: 7.212 ops/ms
Iteration   2: 7.260 ops/ms
Iteration   3: 7.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.259 ±(99.9%) 0.836 ops/ms [Average]
  (min, avg, max) = (7.212, 7.259, 7.303), stdev = 0.046
  CI (99.9%): [6.422, 8.095] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.905 ops/ms
# Warmup Iteration   2: 6.846 ops/ms
# Warmup Iteration   3: 7.460 ops/ms
Iteration   1: 7.558 ops/ms
Iteration   2: 7.409 ops/ms
Iteration   3: 7.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.615 ±(99.9%) 4.363 ops/ms [Average]
  (min, avg, max) = (7.409, 7.615, 7.877), stdev = 0.239
  CI (99.9%): [3.251, 11.978] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.431 ops/ms
# Warmup Iteration   2: 6.794 ops/ms
# Warmup Iteration   3: 6.991 ops/ms
Iteration   1: 6.753 ops/ms
Iteration   2: 7.031 ops/ms
Iteration   3: 7.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.931 ±(99.9%) 2.820 ops/ms [Average]
  (min, avg, max) = (6.753, 6.931, 7.031), stdev = 0.155
  CI (99.9%): [4.111, 9.752] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ops/ms
# Warmup Iteration   2: 4.907 ops/ms
# Warmup Iteration   3: 5.458 ops/ms
Iteration   1: 5.479 ops/ms
Iteration   2: 5.607 ops/ms
Iteration   3: 5.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.573 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (5.479, 5.573, 5.633), stdev = 0.082
  CI (99.9%): [4.068, 7.078] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.601 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.722 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.453 ±(99.9%) 0.007 ms/op
Iteration   1: 4.602 ±(99.9%) 0.004 ms/op
Iteration   2: 4.348 ±(99.9%) 0.004 ms/op
Iteration   3: 4.537 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.496 ±(99.9%) 2.403 ms/op [Average]
  (min, avg, max) = (4.348, 4.496, 4.602), stdev = 0.132
  CI (99.9%): [2.093, 6.899] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.152 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.578 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.362 ±(99.9%) 0.003 ms/op
Iteration   1: 4.261 ±(99.9%) 0.004 ms/op
Iteration   2: 4.224 ±(99.9%) 0.005 ms/op
Iteration   3: 4.185 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.223 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (4.185, 4.223, 4.261), stdev = 0.038
  CI (99.9%): [3.528, 4.918] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.512 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.934 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.685 ±(99.9%) 0.003 ms/op
Iteration   1: 4.466 ±(99.9%) 0.005 ms/op
Iteration   2: 4.607 ±(99.9%) 0.008 ms/op
Iteration   3: 4.559 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.544 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (4.466, 4.544, 4.607), stdev = 0.072
  CI (99.9%): [3.229, 5.859] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.390 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.967 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.610 ±(99.9%) 0.016 ms/op
Iteration   1: 5.504 ±(99.9%) 0.020 ms/op
Iteration   2: 5.584 ±(99.9%) 0.029 ms/op
Iteration   3: 5.565 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.551 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (5.504, 5.551, 5.584), stdev = 0.042
  CI (99.9%): [4.791, 6.312] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.900 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.634 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.495 ±(99.9%) 0.014 ms/op
Iteration   1: 4.528 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.332 ms/op
                 createUser·p0.99:   8.307 ms/op
                 createUser·p0.999:  11.256 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   2: 4.522 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.775 ms/op
                 createUser·p0.95:   6.275 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  21.112 ms/op
                 createUser·p0.9999: 22.968 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   3: 4.430 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   8.372 ms/op
                 createUser·p0.999:  14.107 ms/op
                 createUser·p0.9999: 26.404 ms/op
                 createUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213714
  mean =      4.493 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4244 
    [ 2.500,  5.000) = 154248 
    [ 5.000,  7.500) = 51580 
    [ 7.500, 10.000) = 2808 
    [10.000, 12.500) = 528 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      8.379 ms/op
     p(99.9000) =     14.879 ms/op
     p(99.9900) =     25.809 ms/op
     p(99.9990) =     30.118 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.314 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.541 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.013 ms/op
Iteration   1: 4.320 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   4.190 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   5.915 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  14.789 ms/op
                 existUser·p0.9999: 21.450 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 4.266 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   4.141 ms/op
                 existUser·p0.90:   5.464 ms/op
                 existUser·p0.95:   5.923 ms/op
                 existUser·p0.99:   7.700 ms/op
                 existUser·p0.999:  13.271 ms/op
                 existUser·p0.9999: 17.121 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 4.397 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   4.243 ms/op
                 existUser·p0.90:   5.603 ms/op
                 existUser·p0.95:   6.103 ms/op
                 existUser·p0.99:   8.102 ms/op
                 existUser·p0.999:  13.329 ms/op
                 existUser·p0.9999: 23.781 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 221853
  mean =      4.327 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4624 
    [ 2.500,  5.000) = 172635 
    [ 5.000,  7.500) = 41698 
    [ 7.500, 10.000) = 2080 
    [10.000, 12.500) = 484 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     23.253 ms/op
     p(99.9990) =     25.975 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 7.052 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.811 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.504 ±(99.9%) 0.013 ms/op
Iteration   1: 4.608 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.874 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  12.062 ms/op
                 getUser·p0.9999: 16.471 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 4.507 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.751 ms/op
                 getUser·p0.95:   6.308 ms/op
                 getUser·p0.99:   8.478 ms/op
                 getUser·p0.999:  13.629 ms/op
                 getUser·p0.9999: 16.905 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   3: 4.666 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   4.530 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   8.398 ms/op
                 getUser·p0.999:  15.988 ms/op
                 getUser·p0.9999: 23.298 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 208987
  mean =      4.593 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2721 
    [ 2.500,  5.000) = 143668 
    [ 5.000,  7.500) = 59165 
    [ 7.500, 10.000) = 2690 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     22.682 ms/op
     p(99.9990) =     23.393 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.740 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.269 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.919 ±(99.9%) 0.024 ms/op
Iteration   1: 5.916 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   8.233 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   11.436 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 6.236 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   8.749 ms/op
                 listUser·p0.95:   9.847 ms/op
                 listUser·p0.99:   12.547 ms/op
                 listUser·p0.999:  21.463 ms/op
                 listUser·p0.9999: 29.793 ms/op
                 listUser·p1.00:   30.671 ms/op

Iteration   3: 6.058 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.372 ms/op
                 listUser·p0.99:   12.222 ms/op
                 listUser·p0.999:  21.508 ms/op
                 listUser·p0.9999: 33.484 ms/op
                 listUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 158279
  mean =      6.067 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 141 
    [ 2.500,  5.000) = 47179 
    [ 5.000,  7.500) = 83041 
    [ 7.500, 10.000) = 22430 
    [10.000, 12.500) = 4182 
    [12.500, 15.000) = 683 
    [15.000, 17.500) = 311 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      5.620 ms/op
     p(90.0000) =      8.438 ms/op
     p(95.0000) =      9.486 ms/op
     p(99.0000) =     12.042 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     32.053 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.259 ± 0.836  ops/ms
ClientGrpc.existUser                       thrpt       3   7.615 ± 4.363  ops/ms
ClientGrpc.getUser                         thrpt       3   6.931 ± 2.820  ops/ms
ClientGrpc.listUser                        thrpt       3   5.573 ± 1.505  ops/ms
ClientGrpc.createUser                       avgt       3   4.496 ± 2.403   ms/op
ClientGrpc.existUser                        avgt       3   4.223 ± 0.695   ms/op
ClientGrpc.getUser                          avgt       3   4.544 ± 1.315   ms/op
ClientGrpc.listUser                         avgt       3   5.551 ± 0.760   ms/op
ClientGrpc.createUser                     sample  213714   4.493 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.632           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.693           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.218           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.379           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.879           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.809           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.326           ms/op
ClientGrpc.existUser                      sample  221853   4.327 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.675           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.980           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.897           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.599           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.253           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.051           ms/op
ClientGrpc.getUser                        sample  208987   4.593 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.534           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.865           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.357           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.307           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.008           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.682           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.396           ms/op
ClientGrpc.listUser                       sample  158279   6.067 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.720           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.438           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.486           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.042           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.857           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.053           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.817           ms/op
