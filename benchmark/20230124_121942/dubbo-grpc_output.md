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
# Warmup Iteration   1: 4.022 ops/ms
# Warmup Iteration   2: 8.293 ops/ms
# Warmup Iteration   3: 9.798 ops/ms
Iteration   1: 10.174 ops/ms
Iteration   2: 10.072 ops/ms
Iteration   3: 10.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.117 ±(99.9%) 0.944 ops/ms [Average]
  (min, avg, max) = (10.072, 10.117, 10.174), stdev = 0.052
  CI (99.9%): [9.173, 11.061] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.433 ops/ms
# Warmup Iteration   2: 10.050 ops/ms
# Warmup Iteration   3: 10.489 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.451 ±(99.9%) 2.042 ops/ms [Average]
  (min, avg, max) = (10.324, 10.451, 10.536), stdev = 0.112
  CI (99.9%): [8.409, 12.493] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.585 ops/ms
# Warmup Iteration   2: 9.489 ops/ms
# Warmup Iteration   3: 10.196 ops/ms
Iteration   1: 9.925 ops/ms
Iteration   2: 9.952 ops/ms
Iteration   3: 10.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.978 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (9.925, 9.978, 10.057), stdev = 0.070
  CI (99.9%): [8.706, 11.250] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.187 ops/ms
# Warmup Iteration   2: 7.517 ops/ms
# Warmup Iteration   3: 7.797 ops/ms
Iteration   1: 7.881 ops/ms
Iteration   2: 7.847 ops/ms
Iteration   3: 7.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.861 ±(99.9%) 0.321 ops/ms [Average]
  (min, avg, max) = (7.847, 7.861, 7.881), stdev = 0.018
  CI (99.9%): [7.540, 8.182] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.738 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
Iteration   1: 3.196 ±(99.9%) 0.001 ms/op
Iteration   2: 3.270 ±(99.9%) 0.002 ms/op
Iteration   3: 3.268 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.245 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (3.196, 3.245, 3.270), stdev = 0.042
  CI (99.9%): [2.478, 4.012] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.292 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.133 ±(99.9%) 0.002 ms/op
Iteration   2: 3.158 ±(99.9%) 0.002 ms/op
Iteration   3: 3.155 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.149 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (3.133, 3.149, 3.158), stdev = 0.014
  CI (99.9%): [2.897, 3.400] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.331 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.002 ms/op
Iteration   1: 3.166 ±(99.9%) 0.003 ms/op
Iteration   2: 3.239 ±(99.9%) 0.003 ms/op
Iteration   3: 3.266 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.223 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.166, 3.223, 3.266), stdev = 0.051
  CI (99.9%): [2.285, 4.162] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.886 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.014 ms/op
Iteration   1: 4.073 ±(99.9%) 0.016 ms/op
Iteration   2: 4.019 ±(99.9%) 0.012 ms/op
Iteration   3: 4.049 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.047 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (4.019, 4.047, 4.073), stdev = 0.027
  CI (99.9%): [3.552, 4.542] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.006 ms/op
Iteration   1: 3.172 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  11.101 ms/op
                 createUser·p0.9999: 13.660 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.368 ms/op
                 createUser·p0.999:  7.813 ms/op
                 createUser·p0.9999: 21.151 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.210 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.868 ms/op
                 createUser·p0.9999: 17.761 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303028
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19275 
    [ 2.500,  5.000) = 282516 
    [ 5.000,  7.500) = 825 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     19.651 ms/op
     p(99.9990) =     21.495 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.073 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 2.989 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.718 ms/op
                 existUser·p0.9999: 13.592 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  8.541 ms/op
                 existUser·p0.9999: 17.322 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.415 ms/op
                 existUser·p0.9999: 18.593 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313828
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43747 
    [ 2.500,  5.000) = 269383 
    [ 5.000,  7.500) = 480 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.857 ms/op
     p(99.9900) =     17.944 ms/op
     p(99.9990) =     20.574 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.329 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
Iteration   1: 3.196 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.947 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  10.730 ms/op
                 getUser·p0.9999: 17.432 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   2: 3.253 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.555 ms/op
                 getUser·p0.9999: 15.961 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.668 ms/op
                 getUser·p0.9999: 18.075 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300394
  mean =      3.193 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16234 
    [ 2.500,  5.000) = 283173 
    [ 5.000,  7.500) = 576 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     17.661 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 5.375 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.011 ms/op
Iteration   1: 4.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.651 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.254 ms/op
                 listUser·p0.9999: 16.368 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   3: 4.080 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.529 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.902 ms/op
                 listUser·p0.9999: 19.706 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238317
  mean =      4.029 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1671 
    [ 2.500,  5.000) = 210768 
    [ 5.000,  7.500) = 24437 
    [ 7.500, 10.000) = 951 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     19.710 ms/op
     p(99.9990) =     20.377 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.117 ± 0.944  ops/ms
ClientGrpc.existUser                       thrpt       3  10.451 ± 2.042  ops/ms
ClientGrpc.getUser                         thrpt       3   9.978 ± 1.272  ops/ms
ClientGrpc.listUser                        thrpt       3   7.861 ± 0.321  ops/ms
ClientGrpc.createUser                       avgt       3   3.245 ± 0.767   ms/op
ClientGrpc.existUser                        avgt       3   3.149 ± 0.251   ms/op
ClientGrpc.getUser                          avgt       3   3.223 ± 0.939   ms/op
ClientGrpc.listUser                         avgt       3   4.047 ± 0.495   ms/op
ClientGrpc.createUser                     sample  303028   3.167 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.682           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.018           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.569           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.651           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.594           ms/op
ClientGrpc.existUser                      sample  313828   3.058 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.772           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.060           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.857           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.944           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.742           ms/op
ClientGrpc.getUser                        sample  300394   3.193 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.617           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.257           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.661           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.021           ms/op
ClientGrpc.listUser                       sample  238317   4.029 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.529           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.549           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.710           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.644           ms/op
