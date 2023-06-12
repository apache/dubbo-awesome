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
# Warmup Iteration   1: 2.165 ops/ms
# Warmup Iteration   2: 5.238 ops/ms
# Warmup Iteration   3: 6.765 ops/ms
Iteration   1: 7.096 ops/ms
Iteration   2: 7.183 ops/ms
Iteration   3: 7.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.224 ±(99.9%) 2.784 ops/ms [Average]
  (min, avg, max) = (7.096, 7.224, 7.393), stdev = 0.153
  CI (99.9%): [4.440, 10.008] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.707 ops/ms
# Warmup Iteration   2: 7.339 ops/ms
# Warmup Iteration   3: 7.829 ops/ms
Iteration   1: 7.760 ops/ms
Iteration   2: 8.020 ops/ms
Iteration   3: 7.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.846 ±(99.9%) 2.752 ops/ms [Average]
  (min, avg, max) = (7.757, 7.846, 8.020), stdev = 0.151
  CI (99.9%): [5.094, 10.598] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ops/ms
# Warmup Iteration   2: 6.737 ops/ms
# Warmup Iteration   3: 7.488 ops/ms
Iteration   1: 7.642 ops/ms
Iteration   2: 7.503 ops/ms
Iteration   3: 7.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.609 ±(99.9%) 1.720 ops/ms [Average]
  (min, avg, max) = (7.503, 7.609, 7.683), stdev = 0.094
  CI (99.9%): [5.890, 9.329] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ops/ms
# Warmup Iteration   2: 5.271 ops/ms
# Warmup Iteration   3: 5.800 ops/ms
Iteration   1: 5.875 ops/ms
Iteration   2: 5.823 ops/ms
Iteration   3: 5.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.883 ±(99.9%) 1.169 ops/ms [Average]
  (min, avg, max) = (5.823, 5.883, 5.950), stdev = 0.064
  CI (99.9%): [4.714, 7.051] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.272 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.007 ms/op
Iteration   1: 4.489 ±(99.9%) 0.002 ms/op
Iteration   2: 4.274 ±(99.9%) 0.003 ms/op
Iteration   3: 4.364 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.376 ±(99.9%) 1.967 ms/op [Average]
  (min, avg, max) = (4.274, 4.376, 4.489), stdev = 0.108
  CI (99.9%): [2.409, 6.342] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.258 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.004 ms/op
Iteration   1: 4.262 ±(99.9%) 0.004 ms/op
Iteration   2: 4.064 ±(99.9%) 0.005 ms/op
Iteration   3: 4.083 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.136 ±(99.9%) 1.994 ms/op [Average]
  (min, avg, max) = (4.064, 4.136, 4.262), stdev = 0.109
  CI (99.9%): [2.143, 6.130] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.428 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.520 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.010 ms/op
Iteration   1: 4.338 ±(99.9%) 0.005 ms/op
Iteration   2: 4.440 ±(99.9%) 0.003 ms/op
Iteration   3: 4.389 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.389 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (4.338, 4.389, 4.440), stdev = 0.051
  CI (99.9%): [3.457, 5.321] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.880 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 6.174 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.611 ±(99.9%) 0.019 ms/op
Iteration   1: 5.797 ±(99.9%) 0.027 ms/op
Iteration   2: 5.721 ±(99.9%) 0.015 ms/op
Iteration   3: 5.622 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.713 ±(99.9%) 1.596 ms/op [Average]
  (min, avg, max) = (5.622, 5.713, 5.797), stdev = 0.087
  CI (99.9%): [4.117, 7.309] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.864 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.891 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.442 ±(99.9%) 0.013 ms/op
Iteration   1: 4.493 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   8.236 ms/op
                 createUser·p0.999:  15.335 ms/op
                 createUser·p0.9999: 17.556 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   2: 4.337 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.471 ms/op
                 createUser·p0.999:  13.541 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 4.308 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   7.192 ms/op
                 createUser·p0.999:  14.101 ms/op
                 createUser·p0.9999: 20.714 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219228
  mean =      4.378 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3655 
    [ 2.500,  5.000) = 176388 
    [ 5.000,  7.500) = 36838 
    [ 7.500, 10.000) = 1599 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     14.807 ms/op
     p(99.9900) =     20.286 ms/op
     p(99.9990) =     21.110 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 6.426 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.583 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.011 ms/op
Iteration   1: 4.166 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.128 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   6.873 ms/op
                 existUser·p0.999:  11.234 ms/op
                 existUser·p0.9999: 23.123 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   2: 3.974 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  13.652 ms/op
                 existUser·p0.9999: 18.642 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   3: 4.154 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   7.432 ms/op
                 existUser·p0.999:  11.683 ms/op
                 existUser·p0.9999: 19.540 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 234225
  mean =      4.096 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6614 
    [ 2.500,  5.000) = 202672 
    [ 5.000,  7.500) = 23093 
    [ 7.500, 10.000) = 1362 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     22.268 ms/op
     p(99.9990) =     23.395 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.530 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.433 ±(99.9%) 0.013 ms/op
Iteration   1: 4.351 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  10.912 ms/op
                 getUser·p0.9999: 18.928 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   2: 4.389 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  11.359 ms/op
                 getUser·p0.9999: 35.324 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   3: 4.345 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.284 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  14.822 ms/op
                 getUser·p0.9999: 28.255 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219994
  mean =      4.362 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3037 
    [ 2.500,  5.000) = 182340 
    [ 5.000,  7.500) = 32973 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     12.043 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     35.324 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.845 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 5.981 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.718 ±(99.9%) 0.020 ms/op
Iteration   1: 5.737 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  18.817 ms/op
                 listUser·p0.9999: 23.405 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 5.808 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  20.529 ms/op
                 listUser·p0.9999: 22.643 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 5.545 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.192 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  21.114 ms/op
                 listUser·p0.9999: 27.165 ms/op
                 listUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168568
  mean =      5.694 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 52917 
    [ 5.000,  7.500) = 99198 
    [ 7.500, 10.000) = 13901 
    [10.000, 12.500) = 1870 
    [12.500, 15.000) = 272 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.455 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     23.336 ms/op
     p(99.9990) =     28.120 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.224 ± 2.784  ops/ms
ClientGrpc.existUser                       thrpt       3   7.846 ± 2.752  ops/ms
ClientGrpc.getUser                         thrpt       3   7.609 ± 1.720  ops/ms
ClientGrpc.listUser                        thrpt       3   5.883 ± 1.169  ops/ms
ClientGrpc.createUser                       avgt       3   4.376 ± 1.967   ms/op
ClientGrpc.existUser                        avgt       3   4.136 ± 1.994   ms/op
ClientGrpc.getUser                          avgt       3   4.389 ± 0.932   ms/op
ClientGrpc.listUser                         avgt       3   5.713 ± 1.596   ms/op
ClientGrpc.createUser                     sample  219228   4.378 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.750           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.627           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.807           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.286           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.430           ms/op
ClientGrpc.existUser                      sample  234225   4.096 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.966           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.038           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.045           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.960           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.268           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.724           ms/op
ClientGrpc.getUser                        sample  219994   4.362 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.773           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.243           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.652           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.094           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.043           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.013           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.389           ms/op
ClientGrpc.listUser                       sample  168568   5.694 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.624           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.455           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.438           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.551           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.578           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.336           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.344           ms/op
