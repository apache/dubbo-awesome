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
# Warmup Iteration   1: 3.851 ops/ms
# Warmup Iteration   2: 8.712 ops/ms
# Warmup Iteration   3: 9.733 ops/ms
Iteration   1: 9.826 ops/ms
Iteration   2: 10.083 ops/ms
Iteration   3: 9.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.907 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (9.812, 9.907, 10.083), stdev = 0.152
  CI (99.9%): [7.130, 12.684] (assumes normal distribution)


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
# Warmup Iteration   1: 7.523 ops/ms
# Warmup Iteration   2: 9.810 ops/ms
# Warmup Iteration   3: 9.968 ops/ms
Iteration   1: 10.056 ops/ms
Iteration   2: 10.198 ops/ms
Iteration   3: 10.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.119 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (10.056, 10.119, 10.198), stdev = 0.072
  CI (99.9%): [8.799, 11.440] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.126 ops/ms
# Warmup Iteration   2: 9.622 ops/ms
# Warmup Iteration   3: 9.935 ops/ms
Iteration   1: 9.853 ops/ms
Iteration   2: 9.751 ops/ms
Iteration   3: 9.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.781 ±(99.9%) 1.142 ops/ms [Average]
  (min, avg, max) = (9.739, 9.781, 9.853), stdev = 0.063
  CI (99.9%): [8.639, 10.923] (assumes normal distribution)


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
# Warmup Iteration   1: 5.397 ops/ms
# Warmup Iteration   2: 7.264 ops/ms
# Warmup Iteration   3: 7.390 ops/ms
Iteration   1: 7.638 ops/ms
Iteration   2: 7.577 ops/ms
Iteration   3: 7.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.627 ±(99.9%) 0.820 ops/ms [Average]
  (min, avg, max) = (7.577, 7.627, 7.664), stdev = 0.045
  CI (99.9%): [6.807, 8.446] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.002 ms/op
Iteration   1: 3.307 ±(99.9%) 0.002 ms/op
Iteration   2: 3.302 ±(99.9%) 0.005 ms/op
Iteration   3: 3.261 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.290 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.261, 3.290, 3.307), stdev = 0.025
  CI (99.9%): [2.836, 3.744] (assumes normal distribution)


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.002 ms/op
Iteration   1: 3.003 ±(99.9%) 0.003 ms/op
Iteration   2: 3.151 ±(99.9%) 0.001 ms/op
Iteration   3: 3.106 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.087 ±(99.9%) 1.388 ms/op [Average]
  (min, avg, max) = (3.003, 3.087, 3.151), stdev = 0.076
  CI (99.9%): [1.699, 4.474] (assumes normal distribution)


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
# Warmup Iteration   1: 4.666 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.003 ms/op
Iteration   1: 3.245 ±(99.9%) 0.002 ms/op
Iteration   2: 3.236 ±(99.9%) 0.001 ms/op
Iteration   3: 3.263 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.248 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (3.236, 3.248, 3.263), stdev = 0.014
  CI (99.9%): [2.994, 3.502] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.007 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.022 ms/op
Iteration   1: 4.164 ±(99.9%) 0.007 ms/op
Iteration   2: 4.106 ±(99.9%) 0.014 ms/op
Iteration   3: 4.169 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.146 ±(99.9%) 0.642 ms/op [Average]
  (min, avg, max) = (4.106, 4.146, 4.169), stdev = 0.035
  CI (99.9%): [3.504, 4.789] (assumes normal distribution)


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
# Warmup Iteration   1: 4.491 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
Iteration   1: 3.309 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.023 ms/op
                 createUser·p0.9999: 17.149 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  11.662 ms/op
                 createUser·p0.9999: 32.047 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   3: 3.319 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.804 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 292618
  mean =      3.280 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11579 
    [ 2.500,  5.000) = 280034 
    [ 5.000,  7.500) = 611 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.224 ms/op
     p(99.9900) =     30.704 ms/op
     p(99.9990) =     34.280 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
Iteration   1: 3.138 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.266 ms/op
                 existUser·p0.9999: 15.187 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.296 ms/op
                 existUser·p0.9999: 15.548 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   3: 3.139 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  8.489 ms/op
                 existUser·p0.9999: 28.305 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307342
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29653 
    [ 2.500,  5.000) = 276650 
    [ 5.000,  7.500) = 677 
    [ 7.500, 10.000) = 190 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.796 ms/op
     p(99.9900) =     27.477 ms/op
     p(99.9990) =     30.011 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
Iteration   1: 3.276 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.166 ms/op
                 getUser·p0.9999: 13.568 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 3.256 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.442 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.939 ms/op
                 getUser·p0.9999: 15.046 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 3.264 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.819 ms/op
                 getUser·p0.9999: 18.586 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 294080
  mean =      3.265 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 364 
    [ 1.250,  2.500) = 14597 
    [ 2.500,  3.750) = 223932 
    [ 3.750,  5.000) = 54183 
    [ 5.000,  6.250) = 447 
    [ 6.250,  7.500) = 223 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.740 ms/op
     p(99.9900) =     18.075 ms/op
     p(99.9990) =     19.208 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.744 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.011 ms/op
Iteration   1: 4.172 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.424 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 4.253 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  15.947 ms/op
                 listUser·p0.9999: 19.802 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.082 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  16.093 ms/op
                 listUser·p0.9999: 25.499 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230340
  mean =      4.168 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1999 
    [ 2.500,  5.000) = 195604 
    [ 5.000,  7.500) = 31031 
    [ 7.500, 10.000) = 1245 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     23.920 ms/op
     p(99.9990) =     25.824 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.907 ± 2.777  ops/ms
ClientGrpc.existUser                       thrpt       3  10.119 ± 1.321  ops/ms
ClientGrpc.getUser                         thrpt       3   9.781 ± 1.142  ops/ms
ClientGrpc.listUser                        thrpt       3   7.627 ± 0.820  ops/ms
ClientGrpc.createUser                       avgt       3   3.290 ± 0.454   ms/op
ClientGrpc.existUser                        avgt       3   3.087 ± 1.388   ms/op
ClientGrpc.getUser                          avgt       3   3.248 ± 0.254   ms/op
ClientGrpc.listUser                         avgt       3   4.146 ± 0.642   ms/op
ClientGrpc.createUser                     sample  292618   3.280 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.256           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.224           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.704           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.406           ms/op
ClientGrpc.existUser                      sample  307342   3.123 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.097           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.796           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.477           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.114           ms/op
ClientGrpc.getUser                        sample  294080   3.265 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.442           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.240           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.740           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.075           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.530           ms/op
ClientGrpc.listUser                       sample  230340   4.168 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.807           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.234           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.920           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.952           ms/op
