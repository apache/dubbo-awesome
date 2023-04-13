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
# Warmup Iteration   1: 3.006 ops/ms
# Warmup Iteration   2: 6.827 ops/ms
# Warmup Iteration   3: 8.091 ops/ms
Iteration   1: 8.670 ops/ms
Iteration   2: 8.473 ops/ms
Iteration   3: 8.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.576 ±(99.9%) 1.805 ops/ms [Average]
  (min, avg, max) = (8.473, 8.576, 8.670), stdev = 0.099
  CI (99.9%): [6.770, 10.381] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.545 ops/ms
# Warmup Iteration   2: 8.364 ops/ms
# Warmup Iteration   3: 8.756 ops/ms
Iteration   1: 8.932 ops/ms
Iteration   2: 9.011 ops/ms
Iteration   3: 8.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.959 ±(99.9%) 0.833 ops/ms [Average]
  (min, avg, max) = (8.932, 8.959, 9.011), stdev = 0.046
  CI (99.9%): [8.125, 9.792] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.381 ops/ms
# Warmup Iteration   2: 7.887 ops/ms
# Warmup Iteration   3: 8.427 ops/ms
Iteration   1: 8.459 ops/ms
Iteration   2: 8.600 ops/ms
Iteration   3: 8.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.488 ±(99.9%) 1.826 ops/ms [Average]
  (min, avg, max) = (8.406, 8.488, 8.600), stdev = 0.100
  CI (99.9%): [6.662, 10.314] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.651 ops/ms
# Warmup Iteration   2: 6.451 ops/ms
# Warmup Iteration   3: 6.559 ops/ms
Iteration   1: 6.609 ops/ms
Iteration   2: 6.656 ops/ms
Iteration   3: 6.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.670 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (6.609, 6.670, 6.745), stdev = 0.069
  CI (99.9%): [5.406, 7.934] (assumes normal distribution)


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
# Warmup Iteration   1: 5.326 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.007 ms/op
Iteration   1: 3.786 ±(99.9%) 0.003 ms/op
Iteration   2: 3.716 ±(99.9%) 0.003 ms/op
Iteration   3: 3.740 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.747 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.716, 3.747, 3.786), stdev = 0.036
  CI (99.9%): [3.097, 4.397] (assumes normal distribution)


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
# Warmup Iteration   1: 5.070 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.004 ms/op
Iteration   1: 3.648 ±(99.9%) 0.003 ms/op
Iteration   2: 3.532 ±(99.9%) 0.003 ms/op
Iteration   3: 3.570 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.584 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (3.532, 3.584, 3.648), stdev = 0.059
  CI (99.9%): [2.502, 4.665] (assumes normal distribution)


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
# Warmup Iteration   1: 5.425 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.004 ms/op
Iteration   1: 3.844 ±(99.9%) 0.003 ms/op
Iteration   2: 3.767 ±(99.9%) 0.003 ms/op
Iteration   3: 3.745 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.785 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.745, 3.785, 3.844), stdev = 0.052
  CI (99.9%): [2.839, 4.731] (assumes normal distribution)


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
# Warmup Iteration   1: 7.018 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.838 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.752 ±(99.9%) 0.010 ms/op
Iteration   1: 4.715 ±(99.9%) 0.012 ms/op
Iteration   2: 4.715 ±(99.9%) 0.016 ms/op
Iteration   3: 4.678 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.703 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (4.678, 4.703, 4.715), stdev = 0.021
  CI (99.9%): [4.316, 5.089] (assumes normal distribution)


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
# Warmup Iteration   1: 5.437 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.009 ms/op
Iteration   1: 3.772 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  10.699 ms/op
                 createUser·p0.9999: 13.550 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 3.708 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.380 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  13.025 ms/op
                 createUser·p0.9999: 15.702 ms/op
                 createUser·p1.00:   16.171 ms/op

Iteration   3: 3.803 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  11.687 ms/op
                 createUser·p0.9999: 20.878 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255564
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4441 
    [ 2.500,  5.000) = 245239 
    [ 5.000,  7.500) = 5224 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.380 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     11.181 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     21.310 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 5.113 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.008 ms/op
Iteration   1: 3.581 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  10.325 ms/op
                 existUser·p0.9999: 15.027 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 3.557 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  7.331 ms/op
                 existUser·p0.9999: 16.531 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 3.640 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  7.758 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267429
  mean =      3.592 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7565 
    [ 2.500,  5.000) = 255280 
    [ 5.000,  7.500) = 4190 
    [ 7.500, 10.000) = 207 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =      8.221 ms/op
     p(99.9900) =     19.973 ms/op
     p(99.9990) =     22.161 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 5.626 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.009 ms/op
Iteration   1: 3.745 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  8.251 ms/op
                 getUser·p0.9999: 14.819 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 3.701 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  7.819 ms/op
                 getUser·p0.9999: 15.216 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.730 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  8.307 ms/op
                 getUser·p0.9999: 18.509 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257652
  mean =      3.725 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3929 
    [ 2.500,  5.000) = 248698 
    [ 5.000,  7.500) = 4554 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =      8.195 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     19.286 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 6.817 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.027 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.897 ±(99.9%) 0.015 ms/op
Iteration   1: 4.861 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.712 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.821 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  15.173 ms/op
                 listUser·p0.9999: 17.938 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 4.684 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.496 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 19.802 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 5.015 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.627 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 20.337 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198023
  mean =      4.849 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 164 
    [ 2.500,  5.000) = 145762 
    [ 5.000,  7.500) = 46011 
    [ 7.500, 10.000) = 5321 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     20.028 ms/op
     p(99.9990) =     20.718 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.576 ± 1.805  ops/ms
ClientGrpc.existUser                       thrpt       3   8.959 ± 0.833  ops/ms
ClientGrpc.getUser                         thrpt       3   8.488 ± 1.826  ops/ms
ClientGrpc.listUser                        thrpt       3   6.670 ± 1.264  ops/ms
ClientGrpc.createUser                       avgt       3   3.747 ± 0.650   ms/op
ClientGrpc.existUser                        avgt       3   3.584 ± 1.082   ms/op
ClientGrpc.getUser                          avgt       3   3.785 ± 0.946   ms/op
ClientGrpc.listUser                         avgt       3   4.703 ± 0.387   ms/op
ClientGrpc.createUser                     sample  255564   3.761 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.380           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.181           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.988           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.463           ms/op
ClientGrpc.existUser                      sample  267429   3.592 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.873           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.221           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.973           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.381           ms/op
ClientGrpc.getUser                        sample  257652   3.725 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.010           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.195           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.055           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.152           ms/op
ClientGrpc.listUser                       sample  198023   4.849 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.728           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.028           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.135           ms/op
