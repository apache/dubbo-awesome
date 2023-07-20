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
# Warmup Iteration   1: 3.719 ops/ms
# Warmup Iteration   2: 8.790 ops/ms
# Warmup Iteration   3: 9.757 ops/ms
Iteration   1: 10.230 ops/ms
Iteration   2: 10.269 ops/ms
Iteration   3: 10.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.257 ±(99.9%) 0.426 ops/ms [Average]
  (min, avg, max) = (10.230, 10.257, 10.272), stdev = 0.023
  CI (99.9%): [9.831, 10.683] (assumes normal distribution)


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
# Warmup Iteration   1: 7.237 ops/ms
# Warmup Iteration   2: 10.485 ops/ms
# Warmup Iteration   3: 10.858 ops/ms
Iteration   1: 10.739 ops/ms
Iteration   2: 11.277 ops/ms
Iteration   3: 10.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.994 ±(99.9%) 4.936 ops/ms [Average]
  (min, avg, max) = (10.739, 10.994, 11.277), stdev = 0.271
  CI (99.9%): [6.058, 15.930] (assumes normal distribution)


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
# Warmup Iteration   1: 6.788 ops/ms
# Warmup Iteration   2: 9.556 ops/ms
# Warmup Iteration   3: 10.211 ops/ms
Iteration   1: 10.279 ops/ms
Iteration   2: 10.518 ops/ms
Iteration   3: 10.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.368 ±(99.9%) 2.377 ops/ms [Average]
  (min, avg, max) = (10.279, 10.368, 10.518), stdev = 0.130
  CI (99.9%): [7.992, 12.745] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.246 ops/ms
# Warmup Iteration   2: 7.444 ops/ms
# Warmup Iteration   3: 7.736 ops/ms
Iteration   1: 7.757 ops/ms
Iteration   2: 7.732 ops/ms
Iteration   3: 7.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.817 ±(99.9%) 2.312 ops/ms [Average]
  (min, avg, max) = (7.732, 7.817, 7.963), stdev = 0.127
  CI (99.9%): [5.505, 10.129] (assumes normal distribution)


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.293 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.003 ms/op
Iteration   1: 3.099 ±(99.9%) 0.003 ms/op
Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
Iteration   3: 3.067 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.074 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (3.057, 3.074, 3.099), stdev = 0.022
  CI (99.9%): [2.681, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.003 ms/op
Iteration   1: 2.989 ±(99.9%) 0.002 ms/op
Iteration   2: 2.904 ±(99.9%) 0.001 ms/op
Iteration   3: 2.992 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (2.904, 2.962, 2.992), stdev = 0.050
  CI (99.9%): [2.057, 3.866] (assumes normal distribution)


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.003 ms/op
Iteration   1: 3.056 ±(99.9%) 0.002 ms/op
Iteration   2: 3.095 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.056, 3.071, 3.095), stdev = 0.021
  CI (99.9%): [2.683, 3.459] (assumes normal distribution)


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
# Warmup Iteration   1: 5.057 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.018 ms/op
Iteration   1: 4.147 ±(99.9%) 0.019 ms/op
Iteration   2: 4.019 ±(99.9%) 0.009 ms/op
Iteration   3: 4.037 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.068 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (4.019, 4.068, 4.147), stdev = 0.069
  CI (99.9%): [2.801, 5.335] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.540 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
Iteration   1: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  10.068 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.799 ms/op
                 createUser·p0.9999: 18.817 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  10.779 ms/op
                 createUser·p0.9999: 22.746 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307332
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12818 
    [ 2.500,  5.000) = 292879 
    [ 5.000,  7.500) = 1154 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.429 ms/op
     p(99.9000) =      9.923 ms/op
     p(99.9900) =     21.186 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.005 ms/op
Iteration   1: 2.937 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  5.759 ms/op
                 existUser·p0.9999: 18.416 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  10.795 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  8.974 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325371
  mean =      2.950 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1570 
    [ 1.250,  2.500) = 28362 
    [ 2.500,  3.750) = 285298 
    [ 3.750,  5.000) = 9037 
    [ 5.000,  6.250) = 597 
    [ 6.250,  7.500) = 152 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.082 ms/op
     p(99.9900) =     18.267 ms/op
     p(99.9990) =     19.161 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.509 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 15.335 ms/op
                 getUser·p1.00:   15.729 ms/op

Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  6.835 ms/op
                 getUser·p0.9999: 15.648 ms/op
                 getUser·p1.00:   15.958 ms/op

Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.422 ms/op
                 getUser·p0.999:  7.012 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313290
  mean =      3.064 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 448 
    [ 1.250,  2.500) = 17474 
    [ 2.500,  3.750) = 279943 
    [ 3.750,  5.000) = 13638 
    [ 5.000,  6.250) = 1216 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.423 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 5.824 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.012 ms/op
Iteration   1: 4.100 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.164 ms/op
                 listUser·p0.999:  15.218 ms/op
                 listUser·p0.9999: 17.791 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 4.080 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.329 ms/op
                 listUser·p0.9999: 16.961 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 4.035 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  17.392 ms/op
                 listUser·p0.9999: 20.888 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235830
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1747 
    [ 2.500,  5.000) = 208226 
    [ 5.000,  7.500) = 24185 
    [ 7.500, 10.000) = 1242 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     19.650 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.257 ± 0.426  ops/ms
ClientGrpc.existUser                       thrpt       3  10.994 ± 4.936  ops/ms
ClientGrpc.getUser                         thrpt       3  10.368 ± 2.377  ops/ms
ClientGrpc.listUser                        thrpt       3   7.817 ± 2.312  ops/ms
ClientGrpc.createUser                       avgt       3   3.074 ± 0.394   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.905   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 0.388   ms/op
ClientGrpc.listUser                         avgt       3   4.068 ± 1.267   ms/op
ClientGrpc.createUser                     sample  307332   3.124 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.833           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.429           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.923           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.186           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  325371   2.950 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.082           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.267           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.202           ms/op
ClientGrpc.getUser                        sample  313290   3.064 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.509           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.005           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.595           ms/op
ClientGrpc.listUser                       sample  235830   4.071 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.959           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.548           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.650           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.463           ms/op
