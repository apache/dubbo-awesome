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
# Warmup Iteration   1: 4.169 ops/ms
# Warmup Iteration   2: 8.959 ops/ms
# Warmup Iteration   3: 10.019 ops/ms
Iteration   1: 10.112 ops/ms
Iteration   2: 10.036 ops/ms
Iteration   3: 10.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.141 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (10.036, 10.141, 10.276), stdev = 0.122
  CI (99.9%): [7.908, 12.375] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.481 ops/ms
# Warmup Iteration   2: 10.342 ops/ms
# Warmup Iteration   3: 10.397 ops/ms
Iteration   1: 10.657 ops/ms
Iteration   2: 10.501 ops/ms
Iteration   3: 10.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.523 ±(99.9%) 2.255 ops/ms [Average]
  (min, avg, max) = (10.413, 10.523, 10.657), stdev = 0.124
  CI (99.9%): [8.268, 12.778] (assumes normal distribution)


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
# Warmup Iteration   1: 6.947 ops/ms
# Warmup Iteration   2: 9.733 ops/ms
# Warmup Iteration   3: 9.960 ops/ms
Iteration   1: 9.913 ops/ms
Iteration   2: 10.218 ops/ms
Iteration   3: 9.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.021 ±(99.9%) 3.120 ops/ms [Average]
  (min, avg, max) = (9.913, 10.021, 10.218), stdev = 0.171
  CI (99.9%): [6.901, 13.141] (assumes normal distribution)


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
# Warmup Iteration   1: 5.390 ops/ms
# Warmup Iteration   2: 7.557 ops/ms
# Warmup Iteration   3: 7.817 ops/ms
Iteration   1: 8.208 ops/ms
Iteration   2: 7.839 ops/ms
Iteration   3: 8.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.022 ±(99.9%) 3.365 ops/ms [Average]
  (min, avg, max) = (7.839, 8.022, 8.208), stdev = 0.184
  CI (99.9%): [4.657, 11.387] (assumes normal distribution)


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.004 ms/op
Iteration   1: 3.236 ±(99.9%) 0.002 ms/op
Iteration   2: 3.168 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.176 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.124, 3.176, 3.236), stdev = 0.056
  CI (99.9%): [2.150, 4.201] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.052 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (2.981, 3.052, 3.100), stdev = 0.063
  CI (99.9%): [1.909, 4.196] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.002 ms/op
Iteration   1: 3.079 ±(99.9%) 0.003 ms/op
Iteration   2: 3.196 ±(99.9%) 0.002 ms/op
Iteration   3: 3.170 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.149 ±(99.9%) 1.121 ms/op [Average]
  (min, avg, max) = (3.079, 3.149, 3.196), stdev = 0.061
  CI (99.9%): [2.028, 4.269] (assumes normal distribution)


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
# Warmup Iteration   1: 5.608 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.026 ms/op
Iteration   1: 3.980 ±(99.9%) 0.008 ms/op
Iteration   2: 3.962 ±(99.9%) 0.009 ms/op
Iteration   3: 3.865 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.936 ±(99.9%) 1.126 ms/op [Average]
  (min, avg, max) = (3.865, 3.936, 3.980), stdev = 0.062
  CI (99.9%): [2.810, 5.062] (assumes normal distribution)


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.008 ms/op
Iteration   1: 3.205 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.168 ms/op
                 createUser·p0.9999: 13.124 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  10.054 ms/op
                 createUser·p0.9999: 20.707 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  13.498 ms/op
                 createUser·p0.9999: 19.209 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298477
  mean =      3.214 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20404 
    [ 2.500,  5.000) = 276490 
    [ 5.000,  7.500) = 1077 
    [ 7.500, 10.000) = 189 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =     10.216 ms/op
     p(99.9900) =     19.802 ms/op
     p(99.9990) =     21.005 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.792 ms/op
                 existUser·p0.9999: 14.367 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.537 ms/op
                 existUser·p0.9999: 14.755 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314747
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36286 
    [ 2.500,  5.000) = 277620 
    [ 5.000,  7.500) = 597 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     28.012 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.007 ms/op
Iteration   1: 3.201 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  10.669 ms/op
                 getUser·p0.9999: 16.204 ms/op
                 getUser·p1.00:   16.548 ms/op

Iteration   2: 3.204 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.823 ms/op
                 getUser·p0.9999: 14.844 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.713 ms/op
                 getUser·p0.9999: 20.239 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300623
  mean =      3.190 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19946 
    [ 2.500,  5.000) = 279627 
    [ 5.000,  7.500) = 716 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.768 ms/op
     p(99.9900) =     17.201 ms/op
     p(99.9990) =     20.938 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 5.207 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.012 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.008 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 16.403 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   2: 4.161 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  18.529 ms/op
                 listUser·p0.9999: 28.377 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   3: 4.054 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  18.243 ms/op
                 listUser·p0.9999: 29.295 ms/op
                 listUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235113
  mean =      4.081 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1902 
    [ 2.500,  5.000) = 202671 
    [ 5.000,  7.500) = 28960 
    [ 7.500, 10.000) = 1115 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.956 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.719 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.141 ± 2.233  ops/ms
ClientGrpc.existUser                       thrpt       3  10.523 ± 2.255  ops/ms
ClientGrpc.getUser                         thrpt       3  10.021 ± 3.120  ops/ms
ClientGrpc.listUser                        thrpt       3   8.022 ± 3.365  ops/ms
ClientGrpc.createUser                       avgt       3   3.176 ± 1.025   ms/op
ClientGrpc.existUser                        avgt       3   3.052 ± 1.143   ms/op
ClientGrpc.getUser                          avgt       3   3.149 ± 1.121   ms/op
ClientGrpc.listUser                         avgt       3   3.936 ± 1.126   ms/op
ClientGrpc.createUser                     sample  298477   3.214 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.216           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.802           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.168           ms/op
ClientGrpc.existUser                      sample  314747   3.050 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.755           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.019           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.903           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.078           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.575           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.098           ms/op
ClientGrpc.getUser                        sample  300623   3.190 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.773           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.768           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.201           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  235113   4.081 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.936           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.956           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.246           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.852           ms/op
