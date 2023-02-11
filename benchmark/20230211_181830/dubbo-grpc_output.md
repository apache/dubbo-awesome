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
# Warmup Iteration   1: 2.415 ops/ms
# Warmup Iteration   2: 5.315 ops/ms
# Warmup Iteration   3: 6.962 ops/ms
Iteration   1: 6.957 ops/ms
Iteration   2: 6.898 ops/ms
Iteration   3: 6.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.872 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (6.760, 6.872, 6.957), stdev = 0.101
  CI (99.9%): [5.030, 8.713] (assumes normal distribution)


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
# Warmup Iteration   1: 4.563 ops/ms
# Warmup Iteration   2: 7.080 ops/ms
# Warmup Iteration   3: 7.206 ops/ms
Iteration   1: 7.500 ops/ms
Iteration   2: 7.473 ops/ms
Iteration   3: 7.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.456 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (7.394, 7.456, 7.500), stdev = 0.055
  CI (99.9%): [6.456, 8.456] (assumes normal distribution)


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
# Warmup Iteration   1: 4.505 ops/ms
# Warmup Iteration   2: 6.862 ops/ms
# Warmup Iteration   3: 6.736 ops/ms
Iteration   1: 7.067 ops/ms
Iteration   2: 7.167 ops/ms
Iteration   3: 6.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.031 ±(99.9%) 2.868 ops/ms [Average]
  (min, avg, max) = (6.859, 7.031, 7.167), stdev = 0.157
  CI (99.9%): [4.163, 9.899] (assumes normal distribution)


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
# Warmup Iteration   1: 3.548 ops/ms
# Warmup Iteration   2: 5.154 ops/ms
# Warmup Iteration   3: 5.443 ops/ms
Iteration   1: 5.478 ops/ms
Iteration   2: 5.518 ops/ms
Iteration   3: 5.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.558 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (5.478, 5.558, 5.676), stdev = 0.104
  CI (99.9%): [3.653, 7.462] (assumes normal distribution)


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
# Warmup Iteration   1: 6.907 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.005 ms/op
Iteration   1: 4.598 ±(99.9%) 0.003 ms/op
Iteration   2: 4.472 ±(99.9%) 0.004 ms/op
Iteration   3: 4.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.514 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (4.472, 4.514, 4.598), stdev = 0.073
  CI (99.9%): [3.191, 5.837] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.616 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.004 ms/op
Iteration   1: 4.050 ±(99.9%) 0.008 ms/op
Iteration   2: 4.129 ±(99.9%) 0.004 ms/op
Iteration   3: 4.060 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.079 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (4.050, 4.079, 4.129), stdev = 0.043
  CI (99.9%): [3.296, 4.863] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.972 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.867 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.527 ±(99.9%) 0.008 ms/op
Iteration   1: 4.300 ±(99.9%) 0.006 ms/op
Iteration   2: 4.390 ±(99.9%) 0.004 ms/op
Iteration   3: 4.267 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.319 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (4.267, 4.319, 4.390), stdev = 0.064
  CI (99.9%): [3.160, 5.479] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.720 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 6.378 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.096 ±(99.9%) 0.029 ms/op
Iteration   1: 5.858 ±(99.9%) 0.022 ms/op
Iteration   2: 5.703 ±(99.9%) 0.018 ms/op
Iteration   3: 5.682 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.748 ±(99.9%) 1.753 ms/op [Average]
  (min, avg, max) = (5.682, 5.748, 5.858), stdev = 0.096
  CI (99.9%): [3.994, 7.501] (assumes normal distribution)


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
# Warmup Iteration   1: 6.511 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.664 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.527 ±(99.9%) 0.014 ms/op
Iteration   1: 4.470 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  14.934 ms/op
                 createUser·p0.9999: 19.351 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   2: 4.317 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   7.963 ms/op
                 createUser·p0.999:  13.301 ms/op
                 createUser·p0.9999: 17.798 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   3: 4.534 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.775 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.197 ms/op
                 createUser·p0.999:  12.808 ms/op
                 createUser·p0.9999: 20.149 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216213
  mean =      4.438 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5850 
    [ 2.500,  5.000) = 155413 
    [ 5.000,  7.500) = 51826 
    [ 7.500, 10.000) = 2366 
    [10.000, 12.500) = 444 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      8.224 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 6.029 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.460 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.486 ±(99.9%) 0.014 ms/op
Iteration   1: 4.353 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.587 ms/op
                 existUser·p0.95:   6.046 ms/op
                 existUser·p0.99:   8.749 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 20.147 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 4.425 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   4.301 ms/op
                 existUser·p0.90:   5.603 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   8.405 ms/op
                 existUser·p0.999:  14.713 ms/op
                 existUser·p0.9999: 20.112 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   3: 4.411 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   8.070 ms/op
                 existUser·p0.999:  12.387 ms/op
                 existUser·p0.9999: 22.831 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 218190
  mean =      4.396 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5981 
    [ 2.500,  5.000) = 159936 
    [ 5.000,  7.500) = 48969 
    [ 7.500, 10.000) = 2317 
    [10.000, 12.500) = 707 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     13.248 ms/op
     p(99.9900) =     21.841 ms/op
     p(99.9990) =     22.920 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 6.894 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.846 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.660 ±(99.9%) 0.015 ms/op
Iteration   1: 4.584 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.849 ms/op
                 getUser·p0.95:   6.365 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  12.566 ms/op
                 getUser·p0.9999: 15.811 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   2: 4.404 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.372 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.644 ms/op
                 getUser·p0.95:   6.136 ms/op
                 getUser·p0.99:   8.075 ms/op
                 getUser·p0.999:  12.067 ms/op
                 getUser·p0.9999: 27.232 ms/op
                 getUser·p1.00:   30.540 ms/op

Iteration   3: 4.509 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   7.294 ms/op
                 getUser·p0.999:  12.750 ms/op
                 getUser·p0.9999: 22.129 ms/op
                 getUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213335
  mean =      4.498 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4626 
    [ 2.500,  5.000) = 151911 
    [ 5.000,  7.500) = 53817 
    [ 7.500, 10.000) = 2214 
    [10.000, 12.500) = 553 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     23.571 ms/op
     p(99.9990) =     29.367 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 8.647 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.914 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.918 ±(99.9%) 0.022 ms/op
Iteration   1: 5.559 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.160 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  17.678 ms/op
                 listUser·p0.9999: 25.338 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 5.598 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.249 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  16.570 ms/op
                 listUser·p0.9999: 22.006 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 5.852 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   7.741 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   12.042 ms/op
                 listUser·p0.999:  21.474 ms/op
                 listUser·p0.9999: 27.514 ms/op
                 listUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169420
  mean =      5.667 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 136 
    [ 2.500,  5.000) = 57692 
    [ 5.000,  7.500) = 95778 
    [ 7.500, 10.000) = 12712 
    [10.000, 12.500) = 2225 
    [12.500, 15.000) = 494 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.389 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     18.893 ms/op
     p(99.9900) =     24.940 ms/op
     p(99.9990) =     28.447 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.872 ± 1.842  ops/ms
ClientGrpc.existUser                       thrpt       3   7.456 ± 1.000  ops/ms
ClientGrpc.getUser                         thrpt       3   7.031 ± 2.868  ops/ms
ClientGrpc.listUser                        thrpt       3   5.558 ± 1.905  ops/ms
ClientGrpc.createUser                       avgt       3   4.514 ± 1.323   ms/op
ClientGrpc.existUser                        avgt       3   4.079 ± 0.783   ms/op
ClientGrpc.getUser                          avgt       3   4.319 ± 1.160   ms/op
ClientGrpc.listUser                         avgt       3   5.748 ± 1.753   ms/op
ClientGrpc.createUser                     sample  216213   4.438 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.973           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.669           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.119           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.224           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.123           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.857           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.677           ms/op
ClientGrpc.existUser                      sample  218190   4.396 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.017           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.620           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.054           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.405           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.248           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.841           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.003           ms/op
ClientGrpc.getUser                        sample  213335   4.498 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.372           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.143           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.501           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.571           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.540           ms/op
ClientGrpc.listUser                       sample  169420   5.667 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.333           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.389           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.421           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.141           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.893           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.940           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.606           ms/op
