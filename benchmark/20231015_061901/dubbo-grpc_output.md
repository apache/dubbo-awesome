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
# Warmup Iteration   1: 3.350 ops/ms
# Warmup Iteration   2: 8.268 ops/ms
# Warmup Iteration   3: 9.390 ops/ms
Iteration   1: 9.575 ops/ms
Iteration   2: 9.687 ops/ms
Iteration   3: 9.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.727 ±(99.9%) 3.207 ops/ms [Average]
  (min, avg, max) = (9.575, 9.727, 9.919), stdev = 0.176
  CI (99.9%): [6.520, 12.934] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.559 ops/ms
# Warmup Iteration   2: 9.862 ops/ms
# Warmup Iteration   3: 10.191 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.467 ops/ms
Iteration   3: 10.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.471 ±(99.9%) 0.593 ops/ms [Average]
  (min, avg, max) = (10.440, 10.471, 10.505), stdev = 0.033
  CI (99.9%): [9.878, 11.063] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.237 ops/ms
# Warmup Iteration   2: 9.693 ops/ms
# Warmup Iteration   3: 9.663 ops/ms
Iteration   1: 9.841 ops/ms
Iteration   2: 10.095 ops/ms
Iteration   3: 9.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.968 ±(99.9%) 2.319 ops/ms [Average]
  (min, avg, max) = (9.841, 9.968, 10.095), stdev = 0.127
  CI (99.9%): [7.648, 12.287] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.328 ops/ms
# Warmup Iteration   2: 7.434 ops/ms
# Warmup Iteration   3: 7.867 ops/ms
Iteration   1: 7.659 ops/ms
Iteration   2: 7.834 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.802 ±(99.9%) 2.368 ops/ms [Average]
  (min, avg, max) = (7.659, 7.802, 7.913), stdev = 0.130
  CI (99.9%): [5.434, 10.170] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.682 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.003 ms/op
Iteration   1: 3.268 ±(99.9%) 0.005 ms/op
Iteration   2: 3.217 ±(99.9%) 0.004 ms/op
Iteration   3: 3.294 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.260 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.217, 3.260, 3.294), stdev = 0.040
  CI (99.9%): [2.537, 3.982] (assumes normal distribution)


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
# Warmup Iteration   1: 4.433 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.004 ms/op
Iteration   1: 3.018 ±(99.9%) 0.002 ms/op
Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.046 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.018, 3.046, 3.087), stdev = 0.037
  CI (99.9%): [2.378, 3.713] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.371 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.004 ms/op
Iteration   1: 3.179 ±(99.9%) 0.004 ms/op
Iteration   2: 3.177 ±(99.9%) 0.003 ms/op
Iteration   3: 3.255 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.203 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.177, 3.203, 3.255), stdev = 0.044
  CI (99.9%): [2.394, 4.013] (assumes normal distribution)


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
# Warmup Iteration   1: 5.994 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.013 ms/op
Iteration   1: 4.032 ±(99.9%) 0.013 ms/op
Iteration   2: 4.123 ±(99.9%) 0.009 ms/op
Iteration   3: 4.110 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.088 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (4.032, 4.088, 4.123), stdev = 0.049
  CI (99.9%): [3.193, 4.984] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.079 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.008 ms/op
Iteration   1: 3.206 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  10.109 ms/op
                 createUser·p0.9999: 14.894 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  10.625 ms/op
                 createUser·p0.9999: 15.759 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  15.647 ms/op
                 createUser·p0.9999: 21.574 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302009
  mean =      3.177 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16214 
    [ 2.500,  5.000) = 282287 
    [ 5.000,  7.500) = 2721 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     10.404 ms/op
     p(99.9900) =     20.676 ms/op
     p(99.9990) =     21.822 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 4.703 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  11.886 ms/op
                 existUser·p0.9999: 17.426 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  10.584 ms/op
                 existUser·p0.9999: 16.106 ms/op
                 existUser·p1.00:   16.974 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  12.777 ms/op
                 existUser·p0.9999: 19.480 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311076
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1007 
    [ 1.250,  2.500) = 16956 
    [ 2.500,  3.750) = 269146 
    [ 3.750,  5.000) = 21233 
    [ 5.000,  6.250) = 1449 
    [ 6.250,  7.500) = 577 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 100 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     19.592 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 4.835 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.061 ms/op
                 getUser·p0.999:  9.124 ms/op
                 getUser·p0.9999: 18.350 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   2: 3.236 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 33.304 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   3: 3.202 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  11.780 ms/op
                 getUser·p0.9999: 40.370 ms/op
                 getUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300922
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 297902 
    [ 5.000, 10.000) = 2722 
    [10.000, 15.000) = 133 
    [15.000, 20.000) = 66 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      9.932 ms/op
     p(99.9900) =     38.732 ms/op
     p(99.9990) =     40.632 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


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
# Warmup Iteration   1: 5.246 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.333 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.012 ms/op
Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  13.998 ms/op
                 listUser·p0.9999: 15.838 ms/op
                 listUser·p1.00:   16.646 ms/op

Iteration   2: 4.145 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  16.393 ms/op
                 listUser·p0.9999: 19.572 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 4.083 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  16.355 ms/op
                 listUser·p0.9999: 19.109 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238051
  mean =      4.031 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1584 
    [ 2.500,  5.000) = 214714 
    [ 5.000,  7.500) = 19427 
    [ 7.500, 10.000) = 1662 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     18.985 ms/op
     p(99.9990) =     23.092 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.727 ± 3.207  ops/ms
ClientGrpc.existUser                       thrpt       3  10.471 ± 0.593  ops/ms
ClientGrpc.getUser                         thrpt       3   9.968 ± 2.319  ops/ms
ClientGrpc.listUser                        thrpt       3   7.802 ± 2.368  ops/ms
ClientGrpc.createUser                       avgt       3   3.260 ± 0.723   ms/op
ClientGrpc.existUser                        avgt       3   3.046 ± 0.667   ms/op
ClientGrpc.getUser                          avgt       3   3.203 ± 0.809   ms/op
ClientGrpc.listUser                         avgt       3   4.088 ± 0.896   ms/op
ClientGrpc.createUser                     sample  302009   3.177 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.541           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.128           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.404           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.676           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.264           ms/op
ClientGrpc.existUser                      sample  311076   3.086 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.605           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.936           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.960           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.169           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  300922   3.190 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.733           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.932           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          38.732           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          40.698           ms/op
ClientGrpc.listUser                       sample  238051   4.031 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.463           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.532           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.985           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.233           ms/op
