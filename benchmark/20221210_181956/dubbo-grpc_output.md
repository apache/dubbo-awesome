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
# Warmup Iteration   1: 4.457 ops/ms
# Warmup Iteration   2: 9.332 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 10.388 ops/ms
Iteration   2: 10.672 ops/ms
Iteration   3: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.562 ±(99.9%) 2.782 ops/ms [Average]
  (min, avg, max) = (10.388, 10.562, 10.672), stdev = 0.152
  CI (99.9%): [7.781, 13.344] (assumes normal distribution)


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
# Warmup Iteration   1: 7.774 ops/ms
# Warmup Iteration   2: 10.402 ops/ms
# Warmup Iteration   3: 10.434 ops/ms
Iteration   1: 10.418 ops/ms
Iteration   2: 10.316 ops/ms
Iteration   3: 10.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.546 ±(99.9%) 5.734 ops/ms [Average]
  (min, avg, max) = (10.316, 10.546, 10.905), stdev = 0.314
  CI (99.9%): [4.812, 16.281] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.402 ops/ms
# Warmup Iteration   2: 10.364 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.472 ops/ms
Iteration   2: 10.553 ops/ms
Iteration   3: 10.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.500 ±(99.9%) 0.843 ops/ms [Average]
  (min, avg, max) = (10.472, 10.500, 10.553), stdev = 0.046
  CI (99.9%): [9.656, 11.343] (assumes normal distribution)


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
# Warmup Iteration   1: 6.534 ops/ms
# Warmup Iteration   2: 7.768 ops/ms
# Warmup Iteration   3: 7.977 ops/ms
Iteration   1: 8.192 ops/ms
Iteration   2: 7.919 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.048 ±(99.9%) 2.494 ops/ms [Average]
  (min, avg, max) = (7.919, 8.048, 8.192), stdev = 0.137
  CI (99.9%): [5.554, 10.542] (assumes normal distribution)


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.003 ms/op
Iteration   3: 3.070 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.063 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (3.026, 3.063, 3.093), stdev = 0.034
  CI (99.9%): [2.437, 3.689] (assumes normal distribution)


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.926 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.003 ms/op
Iteration   2: 2.900 ±(99.9%) 0.003 ms/op
Iteration   3: 2.931 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.940 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (2.900, 2.940, 2.988), stdev = 0.045
  CI (99.9%): [2.122, 3.758] (assumes normal distribution)


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.003 ms/op
Iteration   1: 3.096 ±(99.9%) 0.002 ms/op
Iteration   2: 3.222 ±(99.9%) 0.003 ms/op
Iteration   3: 3.184 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.167 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (3.096, 3.167, 3.222), stdev = 0.065
  CI (99.9%): [1.986, 4.349] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.018 ms/op
Iteration   1: 4.053 ±(99.9%) 0.026 ms/op
Iteration   2: 3.956 ±(99.9%) 0.023 ms/op
Iteration   3: 4.078 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.029 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (3.956, 4.029, 4.078), stdev = 0.064
  CI (99.9%): [2.860, 5.198] (assumes normal distribution)


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.411 ms/op
                 createUser·p0.999:  10.076 ms/op
                 createUser·p0.9999: 12.573 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   2: 3.164 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.054 ms/op
                 createUser·p0.9999: 12.366 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  10.472 ms/op
                 createUser·p0.9999: 25.229 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307669
  mean =      3.119 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25315 
    [ 2.500,  5.000) = 281381 
    [ 5.000,  7.500) = 602 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =     10.027 ms/op
     p(99.9900) =     24.059 ms/op
     p(99.9990) =     25.620 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.863 ±(99.9%) 0.007 ms/op
Iteration   1: 2.905 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  5.692 ms/op
                 existUser·p0.9999: 11.714 ms/op
                 existUser·p1.00:   11.977 ms/op

Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.423 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   3: 2.877 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.408 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327270
  mean =      2.934 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55438 
    [ 2.500,  5.000) = 271206 
    [ 5.000,  7.500) = 370 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.232 ms/op
     p(99.9900) =     20.704 ms/op
     p(99.9990) =     25.845 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
Iteration   1: 3.139 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.250 ms/op
                 getUser·p0.9999: 11.328 ms/op
                 getUser·p1.00:   11.665 ms/op

Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.619 ms/op
                 getUser·p0.9999: 13.533 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  5.728 ms/op
                 getUser·p0.9999: 15.270 ms/op
                 getUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312424
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2499 
    [ 1.250,  2.500) = 24541 
    [ 2.500,  3.750) = 256238 
    [ 3.750,  5.000) = 28443 
    [ 5.000,  6.250) = 380 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.296 ms/op
     p(99.9900) =     14.263 ms/op
     p(99.9990) =     15.426 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 5.261 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.010 ms/op
Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.506 ms/op
                 listUser·p0.9999: 22.631 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   2: 3.977 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  13.458 ms/op
                 listUser·p0.9999: 21.592 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 3.912 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.718 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  18.817 ms/op
                 listUser·p0.9999: 29.027 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243194
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4824 
    [ 2.500,  5.000) = 212426 
    [ 5.000,  7.500) = 24905 
    [ 7.500, 10.000) = 542 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     29.523 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.562 ± 2.782  ops/ms
ClientGrpc.existUser                       thrpt       3  10.546 ± 5.734  ops/ms
ClientGrpc.getUser                         thrpt       3  10.500 ± 0.843  ops/ms
ClientGrpc.listUser                        thrpt       3   8.048 ± 2.494  ops/ms
ClientGrpc.createUser                       avgt       3   3.063 ± 0.626   ms/op
ClientGrpc.existUser                        avgt       3   2.940 ± 0.818   ms/op
ClientGrpc.getUser                          avgt       3   3.167 ± 1.182   ms/op
ClientGrpc.listUser                         avgt       3   4.029 ± 1.169   ms/op
ClientGrpc.createUser                     sample  307669   3.119 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.688           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.965           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.027           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.059           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.542           ms/op
ClientGrpc.existUser                      sample  327270   2.934 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.605           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.232           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.704           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.985           ms/op
ClientGrpc.getUser                        sample  312424   3.072 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.679           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.296           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.263           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.532           ms/op
ClientGrpc.listUser                       sample  243194   3.947 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.718           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.499           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.100           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.655           ms/op
