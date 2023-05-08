# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.150 ops/ms
# Warmup Iteration   2: 6.770 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 8.426 ops/ms
Iteration   2: 8.795 ops/ms
Iteration   3: 8.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.688 ±(99.9%) 4.151 ops/ms [Average]
  (min, avg, max) = (8.426, 8.688, 8.842), stdev = 0.228
  CI (99.9%): [4.537, 12.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 6.058 ops/ms
# Warmup Iteration   2: 8.556 ops/ms
# Warmup Iteration   3: 9.013 ops/ms
Iteration   1: 9.221 ops/ms
Iteration   2: 9.122 ops/ms
Iteration   3: 9.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.209 ±(99.9%) 1.493 ops/ms [Average]
  (min, avg, max) = (9.122, 9.209, 9.285), stdev = 0.082
  CI (99.9%): [7.717, 10.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.180 ops/ms
# Warmup Iteration   2: 7.930 ops/ms
# Warmup Iteration   3: 8.514 ops/ms
Iteration   1: 8.741 ops/ms
Iteration   2: 8.720 ops/ms
Iteration   3: 8.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.739 ±(99.9%) 0.347 ops/ms [Average]
  (min, avg, max) = (8.720, 8.739, 8.758), stdev = 0.019
  CI (99.9%): [8.393, 9.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ops/ms
# Warmup Iteration   2: 6.283 ops/ms
# Warmup Iteration   3: 6.712 ops/ms
Iteration   1: 6.659 ops/ms
Iteration   2: 6.795 ops/ms
Iteration   3: 6.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.761 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (6.659, 6.761, 6.828), stdev = 0.090
  CI (99.9%): [5.128, 8.394] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.181 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.025 ms/op
Iteration   1: 3.760 ±(99.9%) 0.003 ms/op
Iteration   2: 3.744 ±(99.9%) 0.003 ms/op
Iteration   3: 3.758 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.754 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (3.744, 3.754, 3.760), stdev = 0.009
  CI (99.9%): [3.592, 3.917] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.529 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.003 ms/op
Iteration   1: 3.452 ±(99.9%) 0.004 ms/op
Iteration   2: 3.492 ±(99.9%) 0.004 ms/op
Iteration   3: 3.514 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.486 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.452, 3.486, 3.514), stdev = 0.031
  CI (99.9%): [2.917, 4.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.010 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.003 ms/op
Iteration   1: 3.687 ±(99.9%) 0.004 ms/op
Iteration   2: 3.586 ±(99.9%) 0.004 ms/op
Iteration   3: 3.624 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.632 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.586, 3.632, 3.687), stdev = 0.051
  CI (99.9%): [2.705, 4.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.579 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 5.333 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.792 ±(99.9%) 0.012 ms/op
Iteration   1: 4.618 ±(99.9%) 0.008 ms/op
Iteration   2: 4.760 ±(99.9%) 0.018 ms/op
Iteration   3: 4.744 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.707 ±(99.9%) 1.422 ms/op [Average]
  (min, avg, max) = (4.618, 4.707, 4.760), stdev = 0.078
  CI (99.9%): [3.285, 6.129] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.335 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.011 ms/op
Iteration   1: 3.700 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  12.233 ms/op
                 createUser·p0.9999: 24.391 ms/op
                 createUser·p1.00:   44.958 ms/op

Iteration   2: 3.612 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.527 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 16.705 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   3: 3.664 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  17.039 ms/op
                 createUser·p0.9999: 34.669 ms/op
                 createUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262382
  mean =      3.658 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 252600 
    [ 5.000, 10.000) = 9299 
    [10.000, 15.000) = 276 
    [15.000, 20.000) = 129 
    [20.000, 25.000) = 40 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     34.063 ms/op
     p(99.9990) =     40.247 ms/op
     p(99.9999) =     44.958 ms/op
    p(100.0000) =     44.958 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.906 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.008 ms/op
Iteration   1: 3.464 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.852 ms/op
                 existUser·p0.999:  8.864 ms/op
                 existUser·p0.9999: 19.759 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   2: 3.480 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.427 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  10.373 ms/op
                 existUser·p0.9999: 14.674 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 3.547 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  12.236 ms/op
                 existUser·p0.9999: 18.743 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274552
  mean =      3.497 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 432 
    [ 1.250,  2.500) = 8314 
    [ 2.500,  3.750) = 200117 
    [ 3.750,  5.000) = 60326 
    [ 5.000,  6.250) = 3238 
    [ 6.250,  7.500) = 1125 
    [ 7.500,  8.750) = 545 
    [ 8.750, 10.000) = 177 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.098 ms/op
     p(99.9900) =     19.417 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.993 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.009 ms/op
Iteration   1: 3.672 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   5.982 ms/op
                 getUser·p0.999:  10.206 ms/op
                 getUser·p0.9999: 16.583 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   2: 3.711 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.410 ms/op
                 getUser·p0.999:  11.190 ms/op
                 getUser·p0.9999: 21.955 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.665 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.143 ms/op
                 getUser·p0.999:  13.244 ms/op
                 getUser·p0.9999: 28.845 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260546
  mean =      3.683 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8844 
    [ 2.500,  5.000) = 243676 
    [ 5.000,  7.500) = 6741 
    [ 7.500, 10.000) = 893 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     12.073 ms/op
     p(99.9900) =     28.015 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.203 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.030 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.017 ms/op
Iteration   1: 4.802 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.681 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  20.032 ms/op
                 listUser·p0.9999: 23.407 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   2: 4.741 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 24.747 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   3: 4.656 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  20.408 ms/op
                 listUser·p0.9999: 32.936 ms/op
                 listUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202833
  mean =      4.732 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 694 
    [ 2.500,  5.000) = 150103 
    [ 5.000,  7.500) = 46172 
    [ 7.500, 10.000) = 4840 
    [10.000, 12.500) = 499 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      6.955 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     32.600 ms/op
     p(99.9990) =     32.997 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.688 ± 4.151  ops/ms
ClientGrpc.existUser                       thrpt       3   9.209 ± 1.493  ops/ms
ClientGrpc.getUser                         thrpt       3   8.739 ± 0.347  ops/ms
ClientGrpc.listUser                        thrpt       3   6.761 ± 1.633  ops/ms
ClientGrpc.createUser                       avgt       3   3.754 ± 0.162   ms/op
ClientGrpc.existUser                        avgt       3   3.486 ± 0.569   ms/op
ClientGrpc.getUser                          avgt       3   3.632 ± 0.927   ms/op
ClientGrpc.listUser                         avgt       3   4.707 ± 1.422   ms/op
ClientGrpc.createUser                     sample  262382   3.658 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.750           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.496           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.059           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.063           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          44.958           ms/op
ClientGrpc.existUser                      sample  274552   3.497 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.831           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.098           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.417           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.890           ms/op
ClientGrpc.getUser                        sample  260546   3.683 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.839           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.177           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.073           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.015           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.590           ms/op
ClientGrpc.listUser                       sample  202833   4.732 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.681           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.473           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.111           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.513           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.600           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.128           ms/op
