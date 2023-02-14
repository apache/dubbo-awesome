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
# Warmup Iteration   1: 3.592 ops/ms
# Warmup Iteration   2: 8.279 ops/ms
# Warmup Iteration   3: 9.687 ops/ms
Iteration   1: 9.752 ops/ms
Iteration   2: 9.898 ops/ms
Iteration   3: 9.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.882 ±(99.9%) 2.236 ops/ms [Average]
  (min, avg, max) = (9.752, 9.882, 9.995), stdev = 0.123
  CI (99.9%): [7.645, 12.118] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.016 ops/ms
# Warmup Iteration   2: 10.083 ops/ms
# Warmup Iteration   3: 10.076 ops/ms
Iteration   1: 10.238 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 10.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.251 ±(99.9%) 0.790 ops/ms [Average]
  (min, avg, max) = (10.215, 10.251, 10.299), stdev = 0.043
  CI (99.9%): [9.460, 11.041] (assumes normal distribution)


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
# Warmup Iteration   1: 6.632 ops/ms
# Warmup Iteration   2: 9.593 ops/ms
# Warmup Iteration   3: 9.723 ops/ms
Iteration   1: 9.817 ops/ms
Iteration   2: 10.025 ops/ms
Iteration   3: 9.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.919 ±(99.9%) 1.902 ops/ms [Average]
  (min, avg, max) = (9.817, 9.919, 10.025), stdev = 0.104
  CI (99.9%): [8.017, 11.821] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.155 ops/ms
# Warmup Iteration   2: 7.177 ops/ms
# Warmup Iteration   3: 7.354 ops/ms
Iteration   1: 7.496 ops/ms
Iteration   2: 7.527 ops/ms
Iteration   3: 7.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.654 ±(99.9%) 4.530 ops/ms [Average]
  (min, avg, max) = (7.496, 7.654, 7.940), stdev = 0.248
  CI (99.9%): [3.125, 12.184] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.759 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.421 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.003 ms/op
Iteration   1: 3.254 ±(99.9%) 0.005 ms/op
Iteration   2: 3.299 ±(99.9%) 0.001 ms/op
Iteration   3: 3.312 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.288 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (3.254, 3.288, 3.312), stdev = 0.030
  CI (99.9%): [2.738, 3.838] (assumes normal distribution)


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
# Warmup Iteration   1: 4.022 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.001 ms/op
Iteration   1: 3.110 ±(99.9%) 0.002 ms/op
Iteration   2: 3.036 ±(99.9%) 0.002 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.086 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (3.036, 3.086, 3.112), stdev = 0.043
  CI (99.9%): [2.301, 3.871] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.002 ms/op
Iteration   1: 3.281 ±(99.9%) 0.002 ms/op
Iteration   2: 3.297 ±(99.9%) 0.001 ms/op
Iteration   3: 3.268 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.282 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (3.268, 3.282, 3.297), stdev = 0.015
  CI (99.9%): [3.016, 3.548] (assumes normal distribution)


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
# Warmup Iteration   1: 6.239 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.013 ms/op
Iteration   1: 4.133 ±(99.9%) 0.009 ms/op
Iteration   2: 4.228 ±(99.9%) 0.039 ms/op
Iteration   3: 4.156 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.172 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (4.133, 4.172, 4.228), stdev = 0.050
  CI (99.9%): [3.260, 5.085] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.537 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.008 ms/op
Iteration   1: 3.239 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   4.765 ms/op
                 createUser·p0.999:  8.315 ms/op
                 createUser·p0.9999: 17.314 ms/op
                 createUser·p1.00:   18.874 ms/op

Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  10.756 ms/op
                 createUser·p0.9999: 25.664 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.466 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296033
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19139 
    [ 2.500,  5.000) = 274728 
    [ 5.000,  7.500) = 1429 
    [ 7.500, 10.000) = 401 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     10.305 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     26.412 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
Iteration   1: 3.105 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  11.091 ms/op
                 existUser·p0.9999: 15.637 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.095 ms/op
                 existUser·p0.9999: 20.305 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  7.969 ms/op
                 existUser·p0.9999: 20.775 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 309696
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40441 
    [ 2.500,  5.000) = 267726 
    [ 5.000,  7.500) = 1099 
    [ 7.500, 10.000) = 205 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.156 ms/op
     p(99.9900) =     20.383 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 4.751 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.007 ms/op
Iteration   1: 3.260 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  8.503 ms/op
                 getUser·p0.9999: 15.506 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   2: 3.255 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.437 ms/op
                 getUser·p0.9999: 17.870 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 20.523 ms/op
                 getUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 293334
  mean =      3.272 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15504 
    [ 2.500,  5.000) = 275936 
    [ 5.000,  7.500) = 1454 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.361 ms/op
     p(99.9900) =     18.798 ms/op
     p(99.9990) =     20.843 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 5.450 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.360 ±(99.9%) 0.014 ms/op
Iteration   1: 4.279 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.201 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  15.585 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 4.236 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 23.695 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   3: 4.213 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 226264
  mean =      4.243 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1740 
    [ 2.500,  5.000) = 191151 
    [ 5.000,  7.500) = 30804 
    [ 7.500, 10.000) = 1837 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     26.266 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.882 ± 2.236  ops/ms
ClientGrpc.existUser                       thrpt       3  10.251 ± 0.790  ops/ms
ClientGrpc.getUser                         thrpt       3   9.919 ± 1.902  ops/ms
ClientGrpc.listUser                        thrpt       3   7.654 ± 4.530  ops/ms
ClientGrpc.createUser                       avgt       3   3.288 ± 0.550   ms/op
ClientGrpc.existUser                        avgt       3   3.086 ± 0.785   ms/op
ClientGrpc.getUser                          avgt       3   3.282 ± 0.266   ms/op
ClientGrpc.listUser                         avgt       3   4.172 ± 0.913   ms/op
ClientGrpc.createUser                     sample  296033   3.241 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.736           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.199           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.305           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.002           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.444           ms/op
ClientGrpc.existUser                      sample  309696   3.099 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.706           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.105           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.850           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.156           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.383           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.856           ms/op
ClientGrpc.getUser                        sample  293334   3.272 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.763           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.236           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.361           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.798           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.906           ms/op
ClientGrpc.listUser                       sample  226264   4.243 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.849           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.035           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.111           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.055           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.347           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.542           ms/op
