# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.239 ops/ms
# Warmup Iteration   2: 6.849 ops/ms
# Warmup Iteration   3: 8.276 ops/ms
Iteration   1: 8.569 ops/ms
Iteration   2: 8.864 ops/ms
Iteration   3: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.719 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (8.569, 8.719, 8.864), stdev = 0.147
  CI (99.9%): [6.031, 11.407] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.973 ops/ms
# Warmup Iteration   2: 8.391 ops/ms
# Warmup Iteration   3: 9.164 ops/ms
Iteration   1: 9.040 ops/ms
Iteration   2: 9.132 ops/ms
Iteration   3: 9.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.196 ±(99.9%) 3.563 ops/ms [Average]
  (min, avg, max) = (9.040, 9.196, 9.415), stdev = 0.195
  CI (99.9%): [5.632, 12.759] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.792 ops/ms
# Warmup Iteration   2: 8.698 ops/ms
# Warmup Iteration   3: 8.929 ops/ms
Iteration   1: 9.096 ops/ms
Iteration   2: 9.102 ops/ms
Iteration   3: 8.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.020 ±(99.9%) 2.504 ops/ms [Average]
  (min, avg, max) = (8.861, 9.020, 9.102), stdev = 0.137
  CI (99.9%): [6.516, 11.523] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.452 ops/ms
# Warmup Iteration   2: 6.541 ops/ms
# Warmup Iteration   3: 6.781 ops/ms
Iteration   1: 6.957 ops/ms
Iteration   2: 6.943 ops/ms
Iteration   3: 6.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.965 ±(99.9%) 0.494 ops/ms [Average]
  (min, avg, max) = (6.943, 6.965, 6.995), stdev = 0.027
  CI (99.9%): [6.472, 7.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.072 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.004 ms/op
Iteration   1: 3.639 ±(99.9%) 0.005 ms/op
Iteration   2: 3.642 ±(99.9%) 0.006 ms/op
Iteration   3: 3.573 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.618 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (3.573, 3.618, 3.642), stdev = 0.039
  CI (99.9%): [2.902, 4.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.116 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.004 ms/op
Iteration   1: 3.396 ±(99.9%) 0.005 ms/op
Iteration   2: 3.421 ±(99.9%) 0.004 ms/op
Iteration   3: 3.426 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.415 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (3.396, 3.415, 3.426), stdev = 0.016
  CI (99.9%): [3.123, 3.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.035 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.003 ms/op
Iteration   1: 3.577 ±(99.9%) 0.003 ms/op
Iteration   2: 3.600 ±(99.9%) 0.004 ms/op
Iteration   3: 3.548 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.575 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.548, 3.575, 3.600), stdev = 0.026
  CI (99.9%): [3.104, 4.047] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.753 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.696 ±(99.9%) 0.016 ms/op
Iteration   1: 4.641 ±(99.9%) 0.022 ms/op
Iteration   2: 4.590 ±(99.9%) 0.033 ms/op
Iteration   3: 4.635 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.622 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (4.590, 4.622, 4.641), stdev = 0.028
  CI (99.9%): [4.114, 5.130] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.276 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.009 ms/op
Iteration   1: 3.479 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.354 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  11.254 ms/op
                 createUser·p0.9999: 15.201 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   2: 3.524 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  7.178 ms/op
                 createUser·p0.9999: 15.154 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   3: 3.575 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  11.108 ms/op
                 createUser·p0.9999: 20.875 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 272275
  mean =      3.526 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11166 
    [ 2.500,  5.000) = 256213 
    [ 5.000,  7.500) = 4262 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     10.596 ms/op
     p(99.9900) =     19.049 ms/op
     p(99.9990) =     21.154 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.008 ms/op
Iteration   1: 3.358 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  10.944 ms/op
                 existUser·p0.9999: 21.511 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   2: 3.365 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  7.143 ms/op
                 existUser·p0.9999: 21.119 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   3: 3.302 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  12.143 ms/op
                 existUser·p0.9999: 21.201 ms/op
                 existUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 287105
  mean =      3.341 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16280 
    [ 2.500,  5.000) = 266898 
    [ 5.000,  7.500) = 3461 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      8.977 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.204 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.009 ms/op
Iteration   1: 3.549 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  9.040 ms/op
                 getUser·p0.9999: 14.483 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   2: 3.543 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  10.191 ms/op
                 getUser·p0.9999: 16.104 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   3: 3.556 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  10.060 ms/op
                 getUser·p0.9999: 19.661 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 270343
  mean =      3.550 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8021 
    [ 2.500,  5.000) = 257023 
    [ 5.000,  7.500) = 4560 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.485 ms/op
     p(99.9000) =      9.579 ms/op
     p(99.9900) =     19.036 ms/op
     p(99.9990) =     19.965 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.408 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.915 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.630 ±(99.9%) 0.013 ms/op
Iteration   1: 4.631 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.572 ms/op
                 listUser·p0.99:   8.327 ms/op
                 listUser·p0.999:  16.334 ms/op
                 listUser·p0.9999: 22.318 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 4.609 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  16.441 ms/op
                 listUser·p0.9999: 19.269 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.653 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   6.619 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  20.438 ms/op
                 listUser·p0.9999: 23.997 ms/op
                 listUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207430
  mean =      4.631 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 377 
    [ 2.500,  5.000) = 172916 
    [ 5.000,  7.500) = 30418 
    [ 7.500, 10.000) = 2986 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     22.430 ms/op
     p(99.9990) =     24.861 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.719 ± 2.688  ops/ms
ClientGrpc.existUser                       thrpt       3   9.196 ± 3.563  ops/ms
ClientGrpc.getUser                         thrpt       3   9.020 ± 2.504  ops/ms
ClientGrpc.listUser                        thrpt       3   6.965 ± 0.494  ops/ms
ClientGrpc.createUser                       avgt       3   3.618 ± 0.716   ms/op
ClientGrpc.existUser                        avgt       3   3.415 ± 0.292   ms/op
ClientGrpc.getUser                          avgt       3   3.575 ± 0.471   ms/op
ClientGrpc.listUser                         avgt       3   4.622 ± 0.508   ms/op
ClientGrpc.createUser                     sample  272275   3.526 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.354           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.513           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.596           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.049           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.299           ms/op
ClientGrpc.existUser                      sample  287105   3.341 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.657           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.341           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.977           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.234           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.053           ms/op
ClientGrpc.getUser                        sample  270343   3.550 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.767           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.485           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.579           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.036           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.021           ms/op
ClientGrpc.listUser                       sample  207430   4.631 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.036           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.110           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.974           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.430           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.936           ms/op
