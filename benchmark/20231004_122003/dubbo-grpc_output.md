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
# Warmup Iteration   1: 4.091 ops/ms
# Warmup Iteration   2: 8.923 ops/ms
# Warmup Iteration   3: 9.858 ops/ms
Iteration   1: 10.212 ops/ms
Iteration   2: 10.272 ops/ms
Iteration   3: 10.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.206 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (10.134, 10.206, 10.272), stdev = 0.070
  CI (99.9%): [8.938, 11.474] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.127 ops/ms
# Warmup Iteration   2: 10.290 ops/ms
# Warmup Iteration   3: 10.605 ops/ms
Iteration   1: 10.739 ops/ms
Iteration   2: 10.794 ops/ms
Iteration   3: 10.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.707 ±(99.9%) 1.930 ops/ms [Average]
  (min, avg, max) = (10.589, 10.707, 10.794), stdev = 0.106
  CI (99.9%): [8.777, 12.638] (assumes normal distribution)


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
# Warmup Iteration   1: 6.931 ops/ms
# Warmup Iteration   2: 9.836 ops/ms
# Warmup Iteration   3: 10.005 ops/ms
Iteration   1: 10.250 ops/ms
Iteration   2: 10.318 ops/ms
Iteration   3: 10.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.199 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (10.030, 10.199, 10.318), stdev = 0.151
  CI (99.9%): [7.449, 12.950] (assumes normal distribution)


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
# Warmup Iteration   1: 5.448 ops/ms
# Warmup Iteration   2: 7.934 ops/ms
# Warmup Iteration   3: 8.142 ops/ms
Iteration   1: 8.206 ops/ms
Iteration   2: 8.240 ops/ms
Iteration   3: 8.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.186 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (8.111, 8.186, 8.240), stdev = 0.067
  CI (99.9%): [6.970, 9.401] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.372 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
Iteration   3: 3.074 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.097 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (3.063, 3.097, 3.155), stdev = 0.051
  CI (99.9%): [2.174, 4.021] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.214 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.003 ms/op
Iteration   3: 2.959 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.991 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (2.959, 2.991, 3.026), stdev = 0.034
  CI (99.9%): [2.378, 3.603] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.372 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.005 ms/op
Iteration   1: 3.105 ±(99.9%) 0.003 ms/op
Iteration   2: 3.080 ±(99.9%) 0.004 ms/op
Iteration   3: 3.087 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.080, 3.091, 3.105), stdev = 0.013
  CI (99.9%): [2.856, 3.325] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.062 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.021 ms/op
Iteration   1: 3.882 ±(99.9%) 0.016 ms/op
Iteration   2: 3.841 ±(99.9%) 0.029 ms/op
Iteration   3: 3.880 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.867 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (3.841, 3.867, 3.882), stdev = 0.023
  CI (99.9%): [3.451, 4.283] (assumes normal distribution)


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
Iteration   1: 3.215 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  8.087 ms/op
                 createUser·p0.9999: 22.120 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.415 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  11.236 ms/op
                 createUser·p0.9999: 21.147 ms/op
                 createUser·p1.00:   21.627 ms/op

Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  15.026 ms/op
                 createUser·p0.9999: 28.075 ms/op
                 createUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304918
  mean =      3.151 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12288 
    [ 2.500,  5.000) = 290210 
    [ 5.000,  7.500) = 1855 
    [ 7.500, 10.000) = 254 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =     10.225 ms/op
     p(99.9900) =     26.100 ms/op
     p(99.9990) =     28.244 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 16.008 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 17.458 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   3: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.963 ms/op
                 existUser·p0.9999: 20.906 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321243
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25677 
    [ 2.500,  5.000) = 293978 
    [ 5.000,  7.500) = 1148 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     21.063 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.538 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
Iteration   1: 3.140 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  13.124 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.394 ms/op
                 getUser·p0.9999: 23.940 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.166 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  12.124 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307209
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10152 
    [ 2.500,  5.000) = 295039 
    [ 5.000,  7.500) = 1311 
    [ 7.500, 10.000) = 248 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     12.317 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     25.849 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 4.972 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.815 ms/op
                 listUser·p0.9999: 16.314 ms/op
                 listUser·p1.00:   16.728 ms/op

Iteration   2: 3.866 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 21.631 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 3.932 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 28.200 ms/op
                 listUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247047
  mean =      3.886 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3045 
    [ 2.500,  5.000) = 228821 
    [ 5.000,  7.500) = 13983 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     22.851 ms/op
     p(99.9990) =     28.676 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.206 ± 1.268  ops/ms
ClientGrpc.existUser                       thrpt       3  10.707 ± 1.930  ops/ms
ClientGrpc.getUser                         thrpt       3  10.199 ± 2.750  ops/ms
ClientGrpc.listUser                        thrpt       3   8.186 ± 1.216  ops/ms
ClientGrpc.createUser                       avgt       3   3.097 ± 0.923   ms/op
ClientGrpc.existUser                        avgt       3   2.991 ± 0.613   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.235   ms/op
ClientGrpc.listUser                         avgt       3   3.867 ± 0.416   ms/op
ClientGrpc.createUser                     sample  304918   3.151 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.415           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.225           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.100           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.344           ms/op
ClientGrpc.existUser                      sample  321243   2.986 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.658           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.733           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.776           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.070           ms/op
ClientGrpc.getUser                        sample  307209   3.125 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.760           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.317           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.936           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.116           ms/op
ClientGrpc.listUser                       sample  247047   3.886 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.931           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.565           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.851           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.967           ms/op
