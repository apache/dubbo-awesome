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
# Warmup Iteration   1: 3.801 ops/ms
# Warmup Iteration   2: 8.657 ops/ms
# Warmup Iteration   3: 9.614 ops/ms
Iteration   1: 10.169 ops/ms
Iteration   2: 10.285 ops/ms
Iteration   3: 10.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.207 ±(99.9%) 1.244 ops/ms [Average]
  (min, avg, max) = (10.165, 10.207, 10.285), stdev = 0.068
  CI (99.9%): [8.962, 11.451] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.127 ops/ms
# Warmup Iteration   2: 10.130 ops/ms
# Warmup Iteration   3: 10.798 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.916 ops/ms
Iteration   3: 10.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.812 ±(99.9%) 1.654 ops/ms [Average]
  (min, avg, max) = (10.754, 10.812, 10.916), stdev = 0.091
  CI (99.9%): [9.158, 12.466] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.394 ops/ms
# Warmup Iteration   2: 9.919 ops/ms
# Warmup Iteration   3: 10.588 ops/ms
Iteration   1: 10.633 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.656 ±(99.9%) 0.418 ops/ms [Average]
  (min, avg, max) = (10.633, 10.656, 10.679), stdev = 0.023
  CI (99.9%): [10.238, 11.074] (assumes normal distribution)


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
# Warmup Iteration   1: 5.202 ops/ms
# Warmup Iteration   2: 7.668 ops/ms
# Warmup Iteration   3: 7.933 ops/ms
Iteration   1: 7.759 ops/ms
Iteration   2: 7.974 ops/ms
Iteration   3: 7.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.864 ±(99.9%) 1.963 ops/ms [Average]
  (min, avg, max) = (7.759, 7.864, 7.974), stdev = 0.108
  CI (99.9%): [5.901, 9.827] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.352 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.002 ms/op
Iteration   1: 3.026 ±(99.9%) 0.003 ms/op
Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (3.026, 3.051, 3.067), stdev = 0.022
  CI (99.9%): [2.644, 3.459] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.003 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
Iteration   3: 2.960 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.441 ms/op [Average]
  (min, avg, max) = (2.939, 2.962, 2.987), stdev = 0.024
  CI (99.9%): [2.521, 3.403] (assumes normal distribution)


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.004 ms/op
Iteration   1: 3.056 ±(99.9%) 0.003 ms/op
Iteration   2: 3.074 ±(99.9%) 0.005 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (3.056, 3.071, 3.082), stdev = 0.014
  CI (99.9%): [2.824, 3.318] (assumes normal distribution)


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
# Warmup Iteration   1: 5.512 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.024 ms/op
Iteration   1: 4.040 ±(99.9%) 0.019 ms/op
Iteration   2: 3.934 ±(99.9%) 0.024 ms/op
Iteration   3: 3.993 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.989 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.934, 3.989, 4.040), stdev = 0.053
  CI (99.9%): [3.021, 4.957] (assumes normal distribution)


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  9.711 ms/op
                 createUser·p0.9999: 21.153 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.284 ms/op
                 createUser·p0.9999: 16.079 ms/op
                 createUser·p1.00:   16.515 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.716 ms/op
                 createUser·p0.9999: 17.987 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315942
  mean =      3.039 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24683 
    [ 2.500,  5.000) = 289786 
    [ 5.000,  7.500) = 1126 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.145 ms/op
     p(99.9900) =     20.089 ms/op
     p(99.9990) =     21.453 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.005 ms/op
Iteration   1: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.607 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 12.517 ms/op
                 existUser·p1.00:   12.878 ms/op

Iteration   2: 2.921 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  5.128 ms/op
                 existUser·p0.9999: 14.468 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.286 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  8.128 ms/op
                 existUser·p0.9999: 16.815 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327456
  mean =      2.932 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1359 
    [ 1.250,  2.500) = 39299 
    [ 2.500,  3.750) = 275917 
    [ 3.750,  5.000) = 9851 
    [ 5.000,  6.250) = 526 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.286 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.464 ms/op
     p(99.9900) =     15.450 ms/op
     p(99.9990) =     17.054 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.228 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.225 ms/op
                 getUser·p0.9999: 14.796 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   3: 3.058 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.456 ms/op
                 getUser·p0.9999: 18.824 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313681
  mean =      3.061 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13317 
    [ 2.500,  5.000) = 299180 
    [ 5.000,  7.500) = 908 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.291 ms/op
     p(99.9900) =     18.510 ms/op
     p(99.9990) =     19.624 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 5.427 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.012 ms/op
Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  16.106 ms/op
                 listUser·p0.9999: 21.106 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.993 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 16.581 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 3.994 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.048 ms/op
                 listUser·p0.999:  15.952 ms/op
                 listUser·p0.9999: 31.064 ms/op
                 listUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239118
  mean =      4.016 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2170 
    [ 2.500,  5.000) = 213214 
    [ 5.000,  7.500) = 22241 
    [ 7.500, 10.000) = 1001 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.432 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     31.215 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.207 ± 1.244  ops/ms
ClientGrpc.existUser                       thrpt       3  10.812 ± 1.654  ops/ms
ClientGrpc.getUser                         thrpt       3  10.656 ± 0.418  ops/ms
ClientGrpc.listUser                        thrpt       3   7.864 ± 1.963  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 0.407   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.441   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 0.247   ms/op
ClientGrpc.listUser                         avgt       3   3.989 ± 0.968   ms/op
ClientGrpc.createUser                     sample  315942   3.039 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.799           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.145           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.089           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.529           ms/op
ClientGrpc.existUser                      sample  327456   2.932 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.286           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.464           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.450           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  313681   3.061 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.811           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.291           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.510           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.185           ms/op
ClientGrpc.listUser                       sample  239118   4.016 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.874           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.432           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.212           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.228           ms/op
