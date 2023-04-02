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
# Warmup Iteration   1: 4.191 ops/ms
# Warmup Iteration   2: 8.928 ops/ms
# Warmup Iteration   3: 10.285 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.570 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.583 ±(99.9%) 0.284 ops/ms [Average]
  (min, avg, max) = (10.570, 10.583, 10.600), stdev = 0.016
  CI (99.9%): [10.299, 10.866] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.906 ops/ms
# Warmup Iteration   2: 10.581 ops/ms
# Warmup Iteration   3: 11.215 ops/ms
Iteration   1: 11.212 ops/ms
Iteration   2: 11.166 ops/ms
Iteration   3: 10.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.098 ±(99.9%) 2.911 ops/ms [Average]
  (min, avg, max) = (10.915, 11.098, 11.212), stdev = 0.160
  CI (99.9%): [8.187, 14.009] (assumes normal distribution)


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
# Warmup Iteration   1: 6.574 ops/ms
# Warmup Iteration   2: 9.873 ops/ms
# Warmup Iteration   3: 10.358 ops/ms
Iteration   1: 10.649 ops/ms
Iteration   2: 10.596 ops/ms
Iteration   3: 10.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.638 ±(99.9%) 0.698 ops/ms [Average]
  (min, avg, max) = (10.596, 10.638, 10.670), stdev = 0.038
  CI (99.9%): [9.941, 11.336] (assumes normal distribution)


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
# Warmup Iteration   1: 5.448 ops/ms
# Warmup Iteration   2: 7.839 ops/ms
# Warmup Iteration   3: 8.038 ops/ms
Iteration   1: 7.902 ops/ms
Iteration   2: 8.183 ops/ms
Iteration   3: 7.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.026 ±(99.9%) 2.616 ops/ms [Average]
  (min, avg, max) = (7.902, 8.026, 8.183), stdev = 0.143
  CI (99.9%): [5.410, 10.642] (assumes normal distribution)


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.004 ms/op
Iteration   1: 3.032 ±(99.9%) 0.004 ms/op
Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.022 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (3.013, 3.022, 3.032), stdev = 0.009
  CI (99.9%): [2.850, 3.193] (assumes normal distribution)


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.002 ms/op
Iteration   1: 2.916 ±(99.9%) 0.002 ms/op
Iteration   2: 2.909 ±(99.9%) 0.002 ms/op
Iteration   3: 2.833 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (2.833, 2.886, 2.916), stdev = 0.046
  CI (99.9%): [2.047, 3.725] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.003 ms/op
Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
Iteration   3: 3.038 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.032 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (3.013, 3.032, 3.044), stdev = 0.017
  CI (99.9%): [2.728, 3.336] (assumes normal distribution)


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
# Warmup Iteration   1: 5.659 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.008 ms/op
Iteration   1: 3.938 ±(99.9%) 0.015 ms/op
Iteration   2: 3.974 ±(99.9%) 0.014 ms/op
Iteration   3: 3.992 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.968 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.938, 3.968, 3.992), stdev = 0.027
  CI (99.9%): [3.472, 4.464] (assumes normal distribution)


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.498 ms/op
                 createUser·p0.999:  8.046 ms/op
                 createUser·p0.9999: 19.333 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 16.179 ms/op
                 createUser·p1.00:   16.613 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  11.742 ms/op
                 createUser·p0.9999: 17.105 ms/op
                 createUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317877
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 408 
    [ 1.250,  2.500) = 23151 
    [ 2.500,  3.750) = 281515 
    [ 3.750,  5.000) = 11154 
    [ 5.000,  6.250) = 869 
    [ 6.250,  7.500) = 316 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.638 ms/op
     p(99.9900) =     18.652 ms/op
     p(99.9990) =     19.557 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.890 ±(99.9%) 0.005 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  6.807 ms/op
                 existUser·p0.9999: 12.240 ms/op
                 existUser·p1.00:   12.419 ms/op

Iteration   2: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  6.695 ms/op
                 existUser·p0.9999: 19.333 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.603 ms/op
                 existUser·p0.9999: 19.281 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326350
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34787 
    [ 2.500,  5.000) = 290682 
    [ 5.000,  7.500) = 602 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      7.029 ms/op
     p(99.9900) =     18.952 ms/op
     p(99.9990) =     20.582 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   4.288 ms/op
                 getUser·p0.999:  6.589 ms/op
                 getUser·p0.9999: 13.210 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.582 ms/op
                 getUser·p0.9999: 15.008 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.648 ms/op
                 getUser·p0.9999: 26.853 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318250
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20361 
    [ 2.500,  5.000) = 296294 
    [ 5.000,  7.500) = 1307 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.270 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 5.563 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
Iteration   1: 3.998 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.989 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.407 ms/op
                 listUser·p0.9999: 18.597 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 4.000 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.474 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.886 ms/op
                 listUser·p0.9999: 26.640 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240426
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3693 
    [ 2.500,  5.000) = 211827 
    [ 5.000,  7.500) = 23463 
    [ 7.500, 10.000) = 975 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     24.804 ms/op
     p(99.9990) =     27.040 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.583 ± 0.284  ops/ms
ClientGrpc.existUser                       thrpt       3  11.098 ± 2.911  ops/ms
ClientGrpc.getUser                         thrpt       3  10.638 ± 0.698  ops/ms
ClientGrpc.listUser                        thrpt       3   8.026 ± 2.616  ops/ms
ClientGrpc.createUser                       avgt       3   3.022 ± 0.171   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 0.839   ms/op
ClientGrpc.getUser                          avgt       3   3.032 ± 0.304   ms/op
ClientGrpc.listUser                         avgt       3   3.968 ± 0.496   ms/op
ClientGrpc.createUser                     sample  317877   3.018 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.741           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.638           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.652           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.661           ms/op
ClientGrpc.existUser                      sample  326350   2.940 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.029           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.952           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  318250   3.018 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.739           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.270           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.247           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.492           ms/op
ClientGrpc.listUser                       sample  240426   3.995 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.474           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.024           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.804           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.132           ms/op
