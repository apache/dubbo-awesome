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
# Warmup Iteration   1: 4.048 ops/ms
# Warmup Iteration   2: 9.093 ops/ms
# Warmup Iteration   3: 10.056 ops/ms
Iteration   1: 10.377 ops/ms
Iteration   2: 10.386 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.448 ±(99.9%) 2.127 ops/ms [Average]
  (min, avg, max) = (10.377, 10.448, 10.583), stdev = 0.117
  CI (99.9%): [8.321, 12.576] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.702 ops/ms
# Warmup Iteration   2: 10.274 ops/ms
# Warmup Iteration   3: 10.757 ops/ms
Iteration   1: 10.907 ops/ms
Iteration   2: 10.847 ops/ms
Iteration   3: 10.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.872 ±(99.9%) 0.570 ops/ms [Average]
  (min, avg, max) = (10.847, 10.872, 10.907), stdev = 0.031
  CI (99.9%): [10.302, 11.442] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.663 ops/ms
# Warmup Iteration   2: 9.958 ops/ms
# Warmup Iteration   3: 10.507 ops/ms
Iteration   1: 10.350 ops/ms
Iteration   2: 10.323 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.371 ±(99.9%) 1.128 ops/ms [Average]
  (min, avg, max) = (10.323, 10.371, 10.441), stdev = 0.062
  CI (99.9%): [9.243, 11.499] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.079 ops/ms
# Warmup Iteration   2: 7.561 ops/ms
# Warmup Iteration   3: 7.744 ops/ms
Iteration   1: 7.799 ops/ms
Iteration   2: 7.858 ops/ms
Iteration   3: 7.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.825 ±(99.9%) 0.547 ops/ms [Average]
  (min, avg, max) = (7.799, 7.825, 7.858), stdev = 0.030
  CI (99.9%): [7.278, 8.371] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.185 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.002 ms/op
Iteration   1: 2.994 ±(99.9%) 0.001 ms/op
Iteration   2: 3.067 ±(99.9%) 0.001 ms/op
Iteration   3: 3.057 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.039 ±(99.9%) 0.719 ms/op [Average]
  (min, avg, max) = (2.994, 3.039, 3.067), stdev = 0.039
  CI (99.9%): [2.321, 3.758] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 2.924 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.945 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.924, 2.945, 2.968), stdev = 0.023
  CI (99.9%): [2.534, 3.356] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.003 ms/op
Iteration   1: 3.065 ±(99.9%) 0.004 ms/op
Iteration   2: 3.051 ±(99.9%) 0.004 ms/op
Iteration   3: 3.046 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.054 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (3.046, 3.054, 3.065), stdev = 0.010
  CI (99.9%): [2.879, 3.229] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.727 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.019 ms/op
Iteration   1: 4.012 ±(99.9%) 0.020 ms/op
Iteration   2: 3.968 ±(99.9%) 0.024 ms/op
Iteration   3: 3.885 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.955 ±(99.9%) 1.180 ms/op [Average]
  (min, avg, max) = (3.885, 3.955, 4.012), stdev = 0.065
  CI (99.9%): [2.775, 5.135] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.429 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.036 ms/op
                 createUser·p0.9999: 13.487 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  6.786 ms/op
                 createUser·p0.9999: 15.916 ms/op
                 createUser·p1.00:   16.499 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.442 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  13.768 ms/op
                 createUser·p0.9999: 16.049 ms/op
                 createUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311939
  mean =      3.078 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 323 
    [ 1.250,  2.500) = 17390 
    [ 2.500,  3.750) = 277722 
    [ 3.750,  5.000) = 15231 
    [ 5.000,  6.250) = 711 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 67 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.966 ms/op
     p(99.9900) =     15.794 ms/op
     p(99.9990) =     16.446 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.005 ms/op
Iteration   1: 2.886 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  7.234 ms/op
                 existUser·p0.9999: 13.746 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  6.193 ms/op
                 existUser·p0.9999: 17.700 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   3: 2.971 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  5.388 ms/op
                 existUser·p0.9999: 15.949 ms/op
                 existUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326951
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25374 
    [ 2.500,  5.000) = 300786 
    [ 5.000,  7.500) = 601 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     16.678 ms/op
     p(99.9990) =     18.011 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.269 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.932 ms/op
                 getUser·p0.9999: 21.595 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.417 ms/op
                 getUser·p0.9999: 17.618 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   3: 3.045 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  5.931 ms/op
                 getUser·p0.9999: 19.023 ms/op
                 getUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313466
  mean =      3.062 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15507 
    [ 2.500,  5.000) = 296432 
    [ 5.000,  7.500) = 1299 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.624 ms/op
     p(99.9900) =     20.053 ms/op
     p(99.9990) =     21.913 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 4.740 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.330 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.012 ms/op
Iteration   1: 3.989 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.966 ms/op
                 listUser·p0.9999: 21.331 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 4.065 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.294 ms/op
                 listUser·p0.9999: 18.813 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 4.061 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  16.639 ms/op
                 listUser·p0.9999: 24.805 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237762
  mean =      4.038 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2431 
    [ 2.500,  5.000) = 211090 
    [ 5.000,  7.500) = 22894 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     16.355 ms/op
     p(99.9900) =     23.961 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.448 ± 2.127  ops/ms
ClientGrpc.existUser                       thrpt       3  10.872 ± 0.570  ops/ms
ClientGrpc.getUser                         thrpt       3  10.371 ± 1.128  ops/ms
ClientGrpc.listUser                        thrpt       3   7.825 ± 0.547  ops/ms
ClientGrpc.createUser                       avgt       3   3.039 ± 0.719   ms/op
ClientGrpc.existUser                        avgt       3   2.945 ± 0.411   ms/op
ClientGrpc.getUser                          avgt       3   3.054 ± 0.175   ms/op
ClientGrpc.listUser                         avgt       3   3.955 ± 1.180   ms/op
ClientGrpc.createUser                     sample  311939   3.078 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.442           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.966           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.794           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.499           ms/op
ClientGrpc.existUser                      sample  326951   2.935 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.663           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.521           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.678           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.513           ms/op
ClientGrpc.getUser                        sample  313466   3.062 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.792           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.624           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.053           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.053           ms/op
ClientGrpc.listUser                       sample  237762   4.038 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.873           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.355           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.961           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.133           ms/op
