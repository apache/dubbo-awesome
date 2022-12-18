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
# Warmup Iteration   1: 3.705 ops/ms
# Warmup Iteration   2: 8.546 ops/ms
# Warmup Iteration   3: 9.639 ops/ms
Iteration   1: 9.990 ops/ms
Iteration   2: 9.689 ops/ms
Iteration   3: 9.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.868 ±(99.9%) 2.886 ops/ms [Average]
  (min, avg, max) = (9.689, 9.868, 9.990), stdev = 0.158
  CI (99.9%): [6.982, 12.755] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.021 ops/ms
# Warmup Iteration   2: 10.078 ops/ms
# Warmup Iteration   3: 10.369 ops/ms
Iteration   1: 10.375 ops/ms
Iteration   2: 9.986 ops/ms
Iteration   3: 10.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.210 ±(99.9%) 3.668 ops/ms [Average]
  (min, avg, max) = (9.986, 10.210, 10.375), stdev = 0.201
  CI (99.9%): [6.543, 13.878] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.123 ops/ms
# Warmup Iteration   2: 9.748 ops/ms
# Warmup Iteration   3: 9.791 ops/ms
Iteration   1: 9.741 ops/ms
Iteration   2: 10.045 ops/ms
Iteration   3: 9.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.919 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (9.741, 9.919, 10.045), stdev = 0.159
  CI (99.9%): [7.023, 12.816] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.839 ops/ms
# Warmup Iteration   2: 7.351 ops/ms
# Warmup Iteration   3: 7.600 ops/ms
Iteration   1: 7.912 ops/ms
Iteration   2: 7.778 ops/ms
Iteration   3: 7.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.833 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (7.778, 7.833, 7.912), stdev = 0.070
  CI (99.9%): [6.554, 9.112] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.517 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.002 ms/op
Iteration   1: 3.214 ±(99.9%) 0.003 ms/op
Iteration   2: 3.238 ±(99.9%) 0.002 ms/op
Iteration   3: 3.208 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.220 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (3.208, 3.220, 3.238), stdev = 0.016
  CI (99.9%): [2.935, 3.505] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.002 ms/op
Iteration   1: 3.158 ±(99.9%) 0.003 ms/op
Iteration   2: 3.216 ±(99.9%) 0.001 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.128 ±(99.9%) 1.962 ms/op [Average]
  (min, avg, max) = (3.008, 3.128, 3.216), stdev = 0.108
  CI (99.9%): [1.165, 5.090] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.213 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.002 ms/op
Iteration   1: 3.232 ±(99.9%) 0.002 ms/op
Iteration   2: 3.247 ±(99.9%) 0.002 ms/op
Iteration   3: 3.238 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.239 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (3.232, 3.239, 3.247), stdev = 0.008
  CI (99.9%): [3.102, 3.376] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.810 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.012 ms/op
Iteration   1: 4.091 ±(99.9%) 0.007 ms/op
Iteration   2: 4.220 ±(99.9%) 0.014 ms/op
Iteration   3: 4.150 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.153 ±(99.9%) 1.179 ms/op [Average]
  (min, avg, max) = (4.091, 4.153, 4.220), stdev = 0.065
  CI (99.9%): [2.975, 5.332] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.676 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.006 ms/op
Iteration   1: 3.204 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  10.549 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  10.666 ms/op
                 createUser·p0.9999: 20.184 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   3: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  18.143 ms/op
                 createUser·p0.9999: 30.343 ms/op
                 createUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298250
  mean =      3.216 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14785 
    [ 2.500,  5.000) = 282088 
    [ 5.000,  7.500) = 858 
    [ 7.500, 10.000) = 176 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =     10.826 ms/op
     p(99.9900) =     28.984 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  7.478 ms/op
                 existUser·p0.9999: 13.217 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 17.882 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   3: 3.169 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  5.801 ms/op
                 existUser·p0.9999: 18.832 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 303425
  mean =      3.163 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27185 
    [ 2.500,  5.000) = 274988 
    [ 5.000,  7.500) = 958 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.427 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     20.693 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.359 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.006 ms/op
Iteration   1: 3.284 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  8.900 ms/op
                 getUser·p0.9999: 14.841 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   2: 3.241 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.075 ms/op
                 getUser·p0.9999: 17.600 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.343 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 295752
  mean =      3.247 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16471 
    [ 2.500,  5.000) = 277770 
    [ 5.000,  7.500) = 1082 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      8.225 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     19.732 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.275 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.012 ms/op
Iteration   1: 4.196 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  14.956 ms/op
                 listUser·p0.9999: 22.842 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 4.217 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  18.538 ms/op
                 listUser·p0.9999: 21.411 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 4.182 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  17.839 ms/op
                 listUser·p0.9999: 22.016 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228791
  mean =      4.198 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1835 
    [ 2.500,  5.000) = 193529 
    [ 5.000,  7.500) = 31293 
    [ 7.500, 10.000) = 1582 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     21.664 ms/op
     p(99.9990) =     23.705 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.868 ± 2.886  ops/ms
ClientGrpc.existUser                       thrpt       3  10.210 ± 3.668  ops/ms
ClientGrpc.getUser                         thrpt       3   9.919 ± 2.896  ops/ms
ClientGrpc.listUser                        thrpt       3   7.833 ± 1.279  ops/ms
ClientGrpc.createUser                       avgt       3   3.220 ± 0.285   ms/op
ClientGrpc.existUser                        avgt       3   3.128 ± 1.962   ms/op
ClientGrpc.getUser                          avgt       3   3.239 ± 0.137   ms/op
ClientGrpc.listUser                         avgt       3   4.153 ± 1.179   ms/op
ClientGrpc.createUser                     sample  298250   3.216 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.649           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.826           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.984           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.097           ms/op
ClientGrpc.existUser                      sample  303425   3.163 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.755           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.133           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.863           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.427           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.285           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.939           ms/op
ClientGrpc.getUser                        sample  295752   3.247 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.592           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.228           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.116           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.225           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.793           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.152           ms/op
ClientGrpc.listUser                       sample  228791   4.198 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.124           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.998           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.095           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.422           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.334           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.664           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.790           ms/op
