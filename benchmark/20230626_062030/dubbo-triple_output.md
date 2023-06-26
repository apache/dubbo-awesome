# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.308 ops/ms
# Warmup Iteration   2: 6.038 ops/ms
# Warmup Iteration   3: 8.994 ops/ms
Iteration   1: 9.795 ops/ms
Iteration   2: 9.707 ops/ms
Iteration   3: 9.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.751 ±(99.9%) 0.805 ops/ms [Average]
  (min, avg, max) = (9.707, 9.751, 9.795), stdev = 0.044
  CI (99.9%): [8.946, 10.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.562 ops/ms
# Warmup Iteration   2: 9.726 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.275 ops/ms
Iteration   2: 10.470 ops/ms
Iteration   3: 10.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.437 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (10.275, 10.437, 10.565), stdev = 0.148
  CI (99.9%): [7.733, 13.140] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.567 ops/ms
# Warmup Iteration   2: 9.230 ops/ms
# Warmup Iteration   3: 9.792 ops/ms
Iteration   1: 10.048 ops/ms
Iteration   2: 9.915 ops/ms
Iteration   3: 10.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.069 ±(99.9%) 3.022 ops/ms [Average]
  (min, avg, max) = (9.915, 10.069, 10.244), stdev = 0.166
  CI (99.9%): [7.047, 13.092] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.542 ops/ms
# Warmup Iteration   2: 7.622 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.239 ops/ms
Iteration   2: 8.483 ops/ms
Iteration   3: 8.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.468 ±(99.9%) 4.043 ops/ms [Average]
  (min, avg, max) = (8.239, 8.468, 8.682), stdev = 0.222
  CI (99.9%): [4.425, 12.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.740 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.007 ms/op
Iteration   1: 3.343 ±(99.9%) 0.004 ms/op
Iteration   2: 3.310 ±(99.9%) 0.007 ms/op
Iteration   3: 3.116 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.256 ±(99.9%) 2.236 ms/op [Average]
  (min, avg, max) = (3.116, 3.256, 3.343), stdev = 0.123
  CI (99.9%): [1.020, 5.492] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.692 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
Iteration   1: 3.195 ±(99.9%) 0.006 ms/op
Iteration   2: 3.034 ±(99.9%) 0.003 ms/op
Iteration   3: 3.082 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.104 ±(99.9%) 1.511 ms/op [Average]
  (min, avg, max) = (3.034, 3.104, 3.195), stdev = 0.083
  CI (99.9%): [1.593, 4.615] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.853 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.003 ms/op
Iteration   1: 3.153 ±(99.9%) 0.002 ms/op
Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
Iteration   3: 3.127 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.129 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (3.107, 3.129, 3.153), stdev = 0.023
  CI (99.9%): [2.716, 3.542] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.912 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.003 ms/op
Iteration   1: 3.714 ±(99.9%) 0.010 ms/op
Iteration   2: 3.730 ±(99.9%) 0.006 ms/op
Iteration   3: 3.767 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.737 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.714, 3.737, 3.767), stdev = 0.028
  CI (99.9%): [3.235, 4.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.744 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.010 ms/op
Iteration   1: 3.196 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  10.142 ms/op
                 createUser·p0.9999: 27.001 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   2: 3.129 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  20.873 ms/op
                 createUser·p0.9999: 23.750 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   3: 3.166 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.983 ms/op
                 createUser·p0.999:  15.663 ms/op
                 createUser·p0.9999: 24.114 ms/op
                 createUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302968
  mean =      3.164 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12974 
    [ 2.500,  5.000) = 284724 
    [ 5.000,  7.500) = 4239 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     17.794 ms/op
     p(99.9900) =     26.106 ms/op
     p(99.9990) =     27.977 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.070 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.008 ms/op
Iteration   1: 3.125 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   6.403 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 33.064 ms/op
                 existUser·p1.00:   34.079 ms/op

Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  11.118 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  8.249 ms/op
                 existUser·p0.9999: 22.237 ms/op
                 existUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311472
  mean =      3.080 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15554 
    [ 2.500,  5.000) = 289770 
    [ 5.000,  7.500) = 5287 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     11.654 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     33.940 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.961 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.010 ms/op
Iteration   1: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  17.062 ms/op
                 getUser·p0.9999: 21.137 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  10.263 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  15.424 ms/op
                 getUser·p0.9999: 20.344 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302824
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6200 
    [ 2.500,  5.000) = 291101 
    [ 5.000,  7.500) = 4641 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     15.598 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     22.636 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.143 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.014 ms/op
Iteration   1: 3.768 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.449 ms/op
                 listUser·p0.999:  16.605 ms/op
                 listUser·p0.9999: 20.858 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 3.706 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.129 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 20.259 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 3.812 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 15.499 ms/op
                 listUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254931
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 248596 
    [ 5.000,  7.500) = 4208 
    [ 7.500, 10.000) = 1500 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.878 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      7.124 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     20.235 ms/op
     p(99.9990) =     22.395 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.751 ± 0.805  ops/ms
ClientPb.existUser                       thrpt       3  10.437 ± 2.704  ops/ms
ClientPb.getUser                         thrpt       3  10.069 ± 3.022  ops/ms
ClientPb.listUser                        thrpt       3   8.468 ± 4.043  ops/ms
ClientPb.createUser                       avgt       3   3.256 ± 2.236   ms/op
ClientPb.existUser                        avgt       3   3.104 ± 1.511   ms/op
ClientPb.getUser                          avgt       3   3.129 ± 0.413   ms/op
ClientPb.listUser                         avgt       3   3.737 ± 0.502   ms/op
ClientPb.createUser                     sample  302968   3.164 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.937           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.510           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.794           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.106           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.443           ms/op
ClientPb.existUser                      sample  311472   3.080 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.231           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.654           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.621           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.079           ms/op
ClientPb.getUser                        sample  302824   3.166 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.212           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.587           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.598           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.758           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.101           ms/op
ClientPb.listUser                       sample  254931   3.761 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.124           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.221           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.544           ms/op
