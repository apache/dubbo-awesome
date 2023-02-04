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
# Warmup Iteration   1: 1.931 ops/ms
# Warmup Iteration   2: 5.043 ops/ms
# Warmup Iteration   3: 6.712 ops/ms
Iteration   1: 6.861 ops/ms
Iteration   2: 7.001 ops/ms
Iteration   3: 7.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.020 ±(99.9%) 3.064 ops/ms [Average]
  (min, avg, max) = (6.861, 7.020, 7.196), stdev = 0.168
  CI (99.9%): [3.956, 10.083] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.696 ops/ms
# Warmup Iteration   2: 7.132 ops/ms
# Warmup Iteration   3: 6.962 ops/ms
Iteration   1: 7.438 ops/ms
Iteration   2: 7.510 ops/ms
Iteration   3: 7.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.451 ±(99.9%) 0.976 ops/ms [Average]
  (min, avg, max) = (7.406, 7.451, 7.510), stdev = 0.054
  CI (99.9%): [6.475, 8.427] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.880 ops/ms
# Warmup Iteration   2: 6.737 ops/ms
# Warmup Iteration   3: 6.876 ops/ms
Iteration   1: 6.947 ops/ms
Iteration   2: 6.939 ops/ms
Iteration   3: 7.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.977 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (6.939, 6.977, 7.046), stdev = 0.060
  CI (99.9%): [5.890, 8.065] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.840 ops/ms
# Warmup Iteration   2: 5.266 ops/ms
# Warmup Iteration   3: 5.849 ops/ms
Iteration   1: 5.733 ops/ms
Iteration   2: 6.092 ops/ms
Iteration   3: 5.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.871 ±(99.9%) 3.521 ops/ms [Average]
  (min, avg, max) = (5.733, 5.871, 6.092), stdev = 0.193
  CI (99.9%): [2.350, 9.392] (assumes normal distribution)


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
# Warmup Iteration   1: 7.241 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.856 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.673 ±(99.9%) 0.020 ms/op
Iteration   1: 4.966 ±(99.9%) 0.004 ms/op
Iteration   2: 4.771 ±(99.9%) 0.004 ms/op
Iteration   3: 4.800 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.846 ±(99.9%) 1.918 ms/op [Average]
  (min, avg, max) = (4.771, 4.846, 4.966), stdev = 0.105
  CI (99.9%): [2.927, 6.764] (assumes normal distribution)


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
# Warmup Iteration   1: 7.042 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.589 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.004 ms/op
Iteration   1: 4.210 ±(99.9%) 0.003 ms/op
Iteration   2: 4.299 ±(99.9%) 0.004 ms/op
Iteration   3: 4.320 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.276 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (4.210, 4.276, 4.320), stdev = 0.058
  CI (99.9%): [3.215, 5.338] (assumes normal distribution)


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
# Warmup Iteration   1: 6.666 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.867 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.592 ±(99.9%) 0.014 ms/op
Iteration   1: 4.448 ±(99.9%) 0.003 ms/op
Iteration   2: 4.411 ±(99.9%) 0.003 ms/op
Iteration   3: 4.618 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.492 ±(99.9%) 2.013 ms/op [Average]
  (min, avg, max) = (4.411, 4.492, 4.618), stdev = 0.110
  CI (99.9%): [2.479, 6.505] (assumes normal distribution)


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
# Warmup Iteration   1: 8.707 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.967 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.806 ±(99.9%) 0.024 ms/op
Iteration   1: 5.637 ±(99.9%) 0.014 ms/op
Iteration   2: 5.762 ±(99.9%) 0.011 ms/op
Iteration   3: 5.891 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.763 ±(99.9%) 2.318 ms/op [Average]
  (min, avg, max) = (5.637, 5.763, 5.891), stdev = 0.127
  CI (99.9%): [3.446, 8.081] (assumes normal distribution)


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
# Warmup Iteration   1: 7.593 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.955 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.595 ±(99.9%) 0.015 ms/op
Iteration   1: 4.449 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  12.897 ms/op
                 createUser·p0.9999: 16.381 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 4.518 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.070 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  12.513 ms/op
                 createUser·p0.9999: 29.753 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 4.376 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.890 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  11.152 ms/op
                 createUser·p0.9999: 25.231 ms/op
                 createUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215858
  mean =      4.447 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3467 
    [ 2.500,  5.000) = 162175 
    [ 5.000,  7.500) = 48608 
    [ 7.500, 10.000) = 1220 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     12.651 ms/op
     p(99.9900) =     29.251 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 6.190 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.740 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.418 ±(99.9%) 0.013 ms/op
Iteration   1: 4.316 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.505 ms/op
                 existUser·p0.95:   5.882 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  15.052 ms/op
                 existUser·p0.9999: 17.072 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   2: 4.178 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   6.877 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 19.410 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   3: 4.140 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.095 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  11.867 ms/op
                 existUser·p0.9999: 21.327 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227792
  mean =      4.210 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5444 
    [ 2.500,  5.000) = 185585 
    [ 5.000,  7.500) = 35350 
    [ 7.500, 10.000) = 875 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.130 ms/op
     p(99.9900) =     20.534 ms/op
     p(99.9990) =     21.763 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 6.687 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.001 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.602 ±(99.9%) 0.013 ms/op
Iteration   1: 4.550 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   7.955 ms/op
                 getUser·p0.999:  16.352 ms/op
                 getUser·p0.9999: 21.986 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 4.433 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  14.577 ms/op
                 getUser·p0.9999: 23.074 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   3: 4.713 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   6.005 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   8.602 ms/op
                 getUser·p0.999:  13.533 ms/op
                 getUser·p0.9999: 22.867 ms/op
                 getUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210228
  mean =      4.563 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2826 
    [ 2.500,  5.000) = 149029 
    [ 5.000,  7.500) = 55346 
    [ 7.500, 10.000) = 2313 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     22.346 ms/op
     p(99.9990) =     25.015 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 8.246 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.822 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.613 ±(99.9%) 0.020 ms/op
Iteration   1: 5.557 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.110 ms/op
                 listUser·p0.99:   10.109 ms/op
                 listUser·p0.999:  16.318 ms/op
                 listUser·p0.9999: 18.955 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 5.574 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  18.259 ms/op
                 listUser·p0.9999: 21.237 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 5.287 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   5.071 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   7.741 ms/op
                 listUser·p0.99:   9.930 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 26.862 ms/op
                 listUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175537
  mean =      5.470 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 70769 
    [ 5.000,  7.500) = 90989 
    [ 7.500, 10.000) = 11535 
    [10.000, 12.500) = 1525 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      7.168 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     17.906 ms/op
     p(99.9900) =     25.770 ms/op
     p(99.9990) =     27.516 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.020 ± 3.064  ops/ms
ClientGrpc.existUser                       thrpt       3   7.451 ± 0.976  ops/ms
ClientGrpc.getUser                         thrpt       3   6.977 ± 1.088  ops/ms
ClientGrpc.listUser                        thrpt       3   5.871 ± 3.521  ops/ms
ClientGrpc.createUser                       avgt       3   4.846 ± 1.918   ms/op
ClientGrpc.existUser                        avgt       3   4.276 ± 1.062   ms/op
ClientGrpc.getUser                          avgt       3   4.492 ± 2.013   ms/op
ClientGrpc.listUser                         avgt       3   5.763 ± 2.318   ms/op
ClientGrpc.createUser                     sample  215858   4.447 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.504           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.988           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.143           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.251           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.179           ms/op
ClientGrpc.existUser                      sample  227792   4.210 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.980           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.702           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.840           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.130           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.534           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  210228   4.563 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.090           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.226           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.045           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.926           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.346           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.166           ms/op
ClientGrpc.listUser                       sample  175537   5.470 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.640           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.045           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.338           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.906           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.770           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.591           ms/op
