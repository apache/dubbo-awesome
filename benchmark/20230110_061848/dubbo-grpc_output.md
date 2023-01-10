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
# Warmup Iteration   1: 2.201 ops/ms
# Warmup Iteration   2: 5.641 ops/ms
# Warmup Iteration   3: 7.061 ops/ms
Iteration   1: 7.218 ops/ms
Iteration   2: 7.013 ops/ms
Iteration   3: 7.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.195 ±(99.9%) 3.123 ops/ms [Average]
  (min, avg, max) = (7.013, 7.195, 7.353), stdev = 0.171
  CI (99.9%): [4.072, 10.317] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.504 ops/ms
# Warmup Iteration   2: 6.978 ops/ms
# Warmup Iteration   3: 7.398 ops/ms
Iteration   1: 7.557 ops/ms
Iteration   2: 7.516 ops/ms
Iteration   3: 7.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.543 ±(99.9%) 0.417 ops/ms [Average]
  (min, avg, max) = (7.516, 7.543, 7.557), stdev = 0.023
  CI (99.9%): [7.125, 7.960] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.267 ops/ms
# Warmup Iteration   2: 6.396 ops/ms
# Warmup Iteration   3: 7.131 ops/ms
Iteration   1: 7.184 ops/ms
Iteration   2: 7.267 ops/ms
Iteration   3: 7.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.158 ±(99.9%) 2.272 ops/ms [Average]
  (min, avg, max) = (7.022, 7.158, 7.267), stdev = 0.125
  CI (99.9%): [4.886, 9.430] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.476 ops/ms
# Warmup Iteration   2: 5.230 ops/ms
# Warmup Iteration   3: 5.658 ops/ms
Iteration   1: 5.694 ops/ms
Iteration   2: 5.904 ops/ms
Iteration   3: 5.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.733 ±(99.9%) 2.826 ops/ms [Average]
  (min, avg, max) = (5.602, 5.733, 5.904), stdev = 0.155
  CI (99.9%): [2.907, 8.559] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.101 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.547 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.480 ±(99.9%) 0.009 ms/op
Iteration   1: 4.472 ±(99.9%) 0.002 ms/op
Iteration   2: 4.465 ±(99.9%) 0.004 ms/op
Iteration   3: 4.512 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.483 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (4.465, 4.483, 4.512), stdev = 0.025
  CI (99.9%): [4.026, 4.940] (assumes normal distribution)


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
# Warmup Iteration   1: 6.173 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.436 ±(99.9%) 0.007 ms/op
Iteration   1: 4.475 ±(99.9%) 0.008 ms/op
Iteration   2: 4.378 ±(99.9%) 0.005 ms/op
Iteration   3: 4.297 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.383 ±(99.9%) 1.628 ms/op [Average]
  (min, avg, max) = (4.297, 4.383, 4.475), stdev = 0.089
  CI (99.9%): [2.756, 6.011] (assumes normal distribution)


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
# Warmup Iteration   1: 7.059 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.783 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.854 ±(99.9%) 0.006 ms/op
Iteration   1: 4.652 ±(99.9%) 0.003 ms/op
Iteration   2: 4.625 ±(99.9%) 0.004 ms/op
Iteration   3: 4.649 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.642 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (4.625, 4.642, 4.652), stdev = 0.015
  CI (99.9%): [4.366, 4.918] (assumes normal distribution)


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
# Warmup Iteration   1: 8.055 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 6.008 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.458 ±(99.9%) 0.015 ms/op
Iteration   1: 5.273 ±(99.9%) 0.013 ms/op
Iteration   2: 5.469 ±(99.9%) 0.018 ms/op
Iteration   3: 5.413 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.385 ±(99.9%) 1.837 ms/op [Average]
  (min, avg, max) = (5.273, 5.385, 5.469), stdev = 0.101
  CI (99.9%): [3.548, 7.222] (assumes normal distribution)


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
# Warmup Iteration   1: 7.077 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.538 ±(99.9%) 0.014 ms/op
Iteration   1: 4.300 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   4.174 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  13.673 ms/op
                 createUser·p0.9999: 31.756 ms/op
                 createUser·p1.00:   32.408 ms/op

Iteration   2: 4.309 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   4.170 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   7.536 ms/op
                 createUser·p0.999:  14.842 ms/op
                 createUser·p0.9999: 21.157 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 4.349 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.867 ms/op
                 createUser·p0.999:  16.641 ms/op
                 createUser·p0.9999: 25.875 ms/op
                 createUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222238
  mean =      4.319 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5387 
    [ 2.500,  5.000) = 173711 
    [ 5.000,  7.500) = 40659 
    [ 7.500, 10.000) = 1736 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     15.233 ms/op
     p(99.9900) =     28.836 ms/op
     p(99.9990) =     32.083 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 6.408 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.012 ms/op
Iteration   1: 4.278 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   4.174 ms/op
                 existUser·p0.90:   5.480 ms/op
                 existUser·p0.95:   5.865 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  11.021 ms/op
                 existUser·p0.9999: 17.420 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 4.294 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   4.182 ms/op
                 existUser·p0.90:   5.489 ms/op
                 existUser·p0.95:   5.898 ms/op
                 existUser·p0.99:   7.299 ms/op
                 existUser·p0.999:  11.306 ms/op
                 existUser·p0.9999: 19.256 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   3: 4.100 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   4.088 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.620 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  9.601 ms/op
                 existUser·p0.9999: 21.804 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227248
  mean =      4.222 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8376 
    [ 2.500,  5.000) = 174924 
    [ 5.000,  7.500) = 42309 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      4.149 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     10.813 ms/op
     p(99.9900) =     19.155 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.567 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.432 ±(99.9%) 0.014 ms/op
Iteration   1: 4.318 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 14.903 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   2: 4.313 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.415 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   7.150 ms/op
                 getUser·p0.999:  11.495 ms/op
                 getUser·p0.9999: 17.012 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   3: 4.528 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.816 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.118 ms/op
                 getUser·p0.999:  14.363 ms/op
                 getUser·p0.9999: 21.758 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218886
  mean =      4.384 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4003 
    [ 2.500,  5.000) = 164234 
    [ 5.000,  7.500) = 48484 
    [ 7.500, 10.000) = 1700 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     20.655 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 8.346 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.999 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.648 ±(99.9%) 0.023 ms/op
Iteration   1: 5.584 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 23.900 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 5.293 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  17.169 ms/op
                 listUser·p0.9999: 29.883 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   3: 5.412 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  20.054 ms/op
                 listUser·p0.9999: 22.066 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176702
  mean =      5.427 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 125 
    [ 2.500,  5.000) = 78164 
    [ 5.000,  7.500) = 84164 
    [ 7.500, 10.000) = 12092 
    [10.000, 12.500) = 1515 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.102 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     30.152 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.195 ± 3.123  ops/ms
ClientGrpc.existUser                       thrpt       3   7.543 ± 0.417  ops/ms
ClientGrpc.getUser                         thrpt       3   7.158 ± 2.272  ops/ms
ClientGrpc.listUser                        thrpt       3   5.733 ± 2.826  ops/ms
ClientGrpc.createUser                       avgt       3   4.483 ± 0.457   ms/op
ClientGrpc.existUser                        avgt       3   4.383 ± 1.628   ms/op
ClientGrpc.getUser                          avgt       3   4.642 ± 0.276   ms/op
ClientGrpc.listUser                         avgt       3   5.385 ± 1.837   ms/op
ClientGrpc.createUser                     sample  222238   4.319 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.882           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.676           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.233           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.836           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.408           ms/op
ClientGrpc.existUser                      sample  227248   4.222 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.854           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.415           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.808           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.111           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.813           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.155           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.315           ms/op
ClientGrpc.getUser                        sample  218886   4.384 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.415           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.595           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.021           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.487           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.960           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.655           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.889           ms/op
ClientGrpc.listUser                       sample  176702   5.427 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.102           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.306           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.202           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.967           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.278           ms/op
