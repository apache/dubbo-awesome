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
# Warmup Iteration   1: 3.113 ops/ms
# Warmup Iteration   2: 6.712 ops/ms
# Warmup Iteration   3: 8.357 ops/ms
Iteration   1: 8.705 ops/ms
Iteration   2: 8.890 ops/ms
Iteration   3: 8.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.855 ±(99.9%) 2.495 ops/ms [Average]
  (min, avg, max) = (8.705, 8.855, 8.972), stdev = 0.137
  CI (99.9%): [6.361, 11.350] (assumes normal distribution)


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
# Warmup Iteration   1: 6.015 ops/ms
# Warmup Iteration   2: 8.551 ops/ms
# Warmup Iteration   3: 9.180 ops/ms
Iteration   1: 9.428 ops/ms
Iteration   2: 9.384 ops/ms
Iteration   3: 9.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.410 ±(99.9%) 0.418 ops/ms [Average]
  (min, avg, max) = (9.384, 9.410, 9.428), stdev = 0.023
  CI (99.9%): [8.992, 9.827] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.760 ops/ms
# Warmup Iteration   2: 8.522 ops/ms
# Warmup Iteration   3: 8.809 ops/ms
Iteration   1: 8.601 ops/ms
Iteration   2: 8.871 ops/ms
Iteration   3: 8.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.784 ±(99.9%) 2.888 ops/ms [Average]
  (min, avg, max) = (8.601, 8.784, 8.880), stdev = 0.158
  CI (99.9%): [5.896, 11.672] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.616 ops/ms
# Warmup Iteration   2: 6.363 ops/ms
# Warmup Iteration   3: 6.636 ops/ms
Iteration   1: 6.697 ops/ms
Iteration   2: 6.819 ops/ms
Iteration   3: 6.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.793 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (6.697, 6.793, 6.864), stdev = 0.087
  CI (99.9%): [5.210, 8.377] (assumes normal distribution)


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
# Warmup Iteration   1: 5.320 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.029 ms/op
Iteration   1: 3.687 ±(99.9%) 0.003 ms/op
Iteration   2: 3.605 ±(99.9%) 0.002 ms/op
Iteration   3: 3.616 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.636 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (3.605, 3.636, 3.687), stdev = 0.044
  CI (99.9%): [2.828, 4.444] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.740 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.008 ms/op
Iteration   1: 3.439 ±(99.9%) 0.005 ms/op
Iteration   2: 3.483 ±(99.9%) 0.002 ms/op
Iteration   3: 3.390 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.438 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (3.390, 3.438, 3.483), stdev = 0.046
  CI (99.9%): [2.590, 4.286] (assumes normal distribution)


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
# Warmup Iteration   1: 5.325 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.004 ms/op
Iteration   1: 3.573 ±(99.9%) 0.003 ms/op
Iteration   2: 3.584 ±(99.9%) 0.004 ms/op
Iteration   3: 3.634 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.597 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.573, 3.597, 3.634), stdev = 0.032
  CI (99.9%): [3.009, 4.185] (assumes normal distribution)


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
# Warmup Iteration   1: 7.217 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.909 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.788 ±(99.9%) 0.008 ms/op
Iteration   1: 4.688 ±(99.9%) 0.011 ms/op
Iteration   2: 4.674 ±(99.9%) 0.020 ms/op
Iteration   3: 4.632 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.665 ±(99.9%) 0.530 ms/op [Average]
  (min, avg, max) = (4.632, 4.665, 4.688), stdev = 0.029
  CI (99.9%): [4.135, 5.195] (assumes normal distribution)


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
# Warmup Iteration   1: 5.264 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.011 ms/op
Iteration   1: 3.662 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  13.169 ms/op
                 createUser·p0.9999: 19.973 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.620 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.460 ms/op
                 createUser·p0.999:  11.315 ms/op
                 createUser·p0.9999: 20.272 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   3: 3.616 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  11.780 ms/op
                 createUser·p0.9999: 26.717 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264087
  mean =      3.633 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7750 
    [ 2.500,  5.000) = 250414 
    [ 5.000,  7.500) = 4933 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     11.780 ms/op
     p(99.9900) =     23.121 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 5.125 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.007 ms/op
Iteration   1: 3.461 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  11.148 ms/op
                 existUser·p0.9999: 15.286 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   2: 3.465 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  10.819 ms/op
                 existUser·p0.9999: 15.770 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   3: 3.411 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  7.741 ms/op
                 existUser·p0.9999: 17.998 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278594
  mean =      3.445 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 300 
    [ 1.250,  2.500) = 10189 
    [ 2.500,  3.750) = 215220 
    [ 3.750,  5.000) = 48720 
    [ 5.000,  6.250) = 2844 
    [ 6.250,  7.500) = 696 
    [ 7.500,  8.750) = 366 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     16.026 ms/op
     p(99.9990) =     18.495 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 5.330 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.009 ms/op
Iteration   1: 3.639 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  11.669 ms/op
                 getUser·p0.9999: 15.379 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   2: 3.581 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.392 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  11.265 ms/op
                 getUser·p0.9999: 15.846 ms/op
                 getUser·p1.00:   16.269 ms/op

Iteration   3: 3.630 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  12.108 ms/op
                 getUser·p0.9999: 18.454 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265458
  mean =      3.616 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 8649 
    [ 2.500,  3.750) = 164800 
    [ 3.750,  5.000) = 85431 
    [ 5.000,  6.250) = 4692 
    [ 6.250,  7.500) = 795 
    [ 7.500,  8.750) = 362 
    [ 8.750, 10.000) = 195 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     18.070 ms/op
     p(99.9990) =     18.558 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 6.792 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.980 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.822 ±(99.9%) 0.014 ms/op
Iteration   1: 4.741 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  14.983 ms/op
                 listUser·p0.9999: 16.105 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 4.867 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.226 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 18.621 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 4.750 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  19.159 ms/op
                 listUser·p0.9999: 33.262 ms/op
                 listUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200563
  mean =      4.785 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 415 
    [ 2.500,  5.000) = 151095 
    [ 5.000,  7.500) = 43412 
    [ 7.500, 10.000) = 4773 
    [10.000, 12.500) = 458 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     15.982 ms/op
     p(99.9900) =     31.881 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.855 ± 2.495  ops/ms
ClientGrpc.existUser                       thrpt       3   9.410 ± 0.418  ops/ms
ClientGrpc.getUser                         thrpt       3   8.784 ± 2.888  ops/ms
ClientGrpc.listUser                        thrpt       3   6.793 ± 1.584  ops/ms
ClientGrpc.createUser                       avgt       3   3.636 ± 0.808   ms/op
ClientGrpc.existUser                        avgt       3   3.438 ± 0.848   ms/op
ClientGrpc.getUser                          avgt       3   3.597 ± 0.588   ms/op
ClientGrpc.listUser                         avgt       3   4.665 ± 0.530   ms/op
ClientGrpc.createUser                     sample  264087   3.633 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.939           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.780           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.121           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.492           ms/op
ClientGrpc.existUser                      sample  278594   3.445 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.889           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.602           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.026           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.612           ms/op
ClientGrpc.getUser                        sample  265458   3.616 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.392           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.070           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.579           ms/op
ClientGrpc.listUser                       sample  200563   4.785 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.942           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.982           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.881           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.751           ms/op
