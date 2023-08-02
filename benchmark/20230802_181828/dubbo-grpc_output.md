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
# Warmup Iteration   1: 3.824 ops/ms
# Warmup Iteration   2: 8.616 ops/ms
# Warmup Iteration   3: 9.750 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.423 ±(99.9%) 3.745 ops/ms [Average]
  (min, avg, max) = (10.196, 10.423, 10.596), stdev = 0.205
  CI (99.9%): [6.678, 14.168] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.258 ops/ms
# Warmup Iteration   2: 10.281 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.770 ops/ms
Iteration   2: 10.889 ops/ms
Iteration   3: 11.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.922 ±(99.9%) 3.122 ops/ms [Average]
  (min, avg, max) = (10.770, 10.922, 11.107), stdev = 0.171
  CI (99.9%): [7.800, 14.044] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.589 ops/ms
# Warmup Iteration   2: 10.073 ops/ms
# Warmup Iteration   3: 10.478 ops/ms
Iteration   1: 10.333 ops/ms
Iteration   2: 10.514 ops/ms
Iteration   3: 10.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.473 ±(99.9%) 2.267 ops/ms [Average]
  (min, avg, max) = (10.333, 10.473, 10.572), stdev = 0.124
  CI (99.9%): [8.206, 12.740] (assumes normal distribution)


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
# Warmup Iteration   1: 5.285 ops/ms
# Warmup Iteration   2: 7.420 ops/ms
# Warmup Iteration   3: 7.592 ops/ms
Iteration   1: 7.754 ops/ms
Iteration   2: 7.808 ops/ms
Iteration   3: 7.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.801 ±(99.9%) 0.797 ops/ms [Average]
  (min, avg, max) = (7.754, 7.801, 7.841), stdev = 0.044
  CI (99.9%): [7.004, 8.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.003 ms/op
Iteration   1: 3.105 ±(99.9%) 0.002 ms/op
Iteration   2: 3.094 ±(99.9%) 0.002 ms/op
Iteration   3: 3.097 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.098 ±(99.9%) 0.104 ms/op [Average]
  (min, avg, max) = (3.094, 3.098, 3.105), stdev = 0.006
  CI (99.9%): [2.994, 3.202] (assumes normal distribution)


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.003 ms/op
Iteration   1: 2.979 ±(99.9%) 0.002 ms/op
Iteration   2: 2.909 ±(99.9%) 0.002 ms/op
Iteration   3: 3.004 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.964 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (2.909, 2.964, 3.004), stdev = 0.049
  CI (99.9%): [2.069, 3.860] (assumes normal distribution)


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.003 ms/op
Iteration   1: 3.083 ±(99.9%) 0.003 ms/op
Iteration   2: 3.128 ±(99.9%) 0.006 ms/op
Iteration   3: 3.061 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (3.061, 3.091, 3.128), stdev = 0.034
  CI (99.9%): [2.470, 3.711] (assumes normal distribution)


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
# Warmup Iteration   1: 5.994 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.021 ms/op
Iteration   1: 4.109 ±(99.9%) 0.021 ms/op
Iteration   2: 4.168 ±(99.9%) 0.024 ms/op
Iteration   3: 4.162 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.146 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (4.109, 4.146, 4.168), stdev = 0.032
  CI (99.9%): [3.555, 4.738] (assumes normal distribution)


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
# Warmup Iteration   1: 4.675 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.471 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 13.291 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   2: 3.071 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  8.469 ms/op
                 createUser·p0.9999: 13.789 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   3: 3.086 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  11.410 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310523
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22795 
    [ 2.500,  5.000) = 284601 
    [ 5.000,  7.500) = 2282 
    [ 7.500, 10.000) = 563 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     24.967 ms/op
     p(99.9990) =     26.113 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.280 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  8.018 ms/op
                 existUser·p0.9999: 13.455 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.649 ms/op
                 existUser·p0.999:  8.086 ms/op
                 existUser·p0.9999: 14.159 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  11.502 ms/op
                 existUser·p0.9999: 17.839 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321320
  mean =      2.988 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 914 
    [ 1.250,  2.500) = 25442 
    [ 2.500,  3.750) = 282225 
    [ 3.750,  5.000) = 10362 
    [ 5.000,  6.250) = 1137 
    [ 6.250,  7.500) = 589 
    [ 7.500,  8.750) = 264 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.651 ms/op
     p(99.9000) =      9.858 ms/op
     p(99.9900) =     17.106 ms/op
     p(99.9990) =     17.950 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.520 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
Iteration   1: 3.140 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  8.069 ms/op
                 getUser·p0.9999: 13.723 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.177 ms/op
                 getUser·p0.999:  9.990 ms/op
                 getUser·p0.9999: 15.660 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.012 ms/op
                 getUser·p0.999:  9.742 ms/op
                 getUser·p0.9999: 21.672 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305866
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17057 
    [ 2.500,  5.000) = 285686 
    [ 5.000,  7.500) = 2464 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =      9.276 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     22.180 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 5.692 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.013 ms/op
Iteration   1: 4.226 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  14.980 ms/op
                 listUser·p0.9999: 17.742 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.259 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  15.326 ms/op
                 listUser·p0.9999: 20.201 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 4.048 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  17.282 ms/op
                 listUser·p0.9999: 20.679 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229936
  mean =      4.176 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1948 
    [ 2.500,  5.000) = 198640 
    [ 5.000,  7.500) = 26556 
    [ 7.500, 10.000) = 2169 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     15.599 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     23.849 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.423 ± 3.745  ops/ms
ClientGrpc.existUser                       thrpt       3  10.922 ± 3.122  ops/ms
ClientGrpc.getUser                         thrpt       3  10.473 ± 2.267  ops/ms
ClientGrpc.listUser                        thrpt       3   7.801 ± 0.797  ops/ms
ClientGrpc.createUser                       avgt       3   3.098 ± 0.104   ms/op
ClientGrpc.existUser                        avgt       3   2.964 ± 0.896   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.621   ms/op
ClientGrpc.listUser                         avgt       3   4.146 ± 0.591   ms/op
ClientGrpc.createUser                     sample  310523   3.093 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.471           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.601           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.967           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.673           ms/op
ClientGrpc.existUser                      sample  321320   2.988 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.651           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.858           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.106           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.055           ms/op
ClientGrpc.getUser                        sample  305866   3.138 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.022           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.276           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.054           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.315           ms/op
ClientGrpc.listUser                       sample  229936   4.176 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.925           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.985           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.119           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.709           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.599           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.578           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
