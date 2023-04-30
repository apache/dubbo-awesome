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
# Warmup Iteration   1: 4.306 ops/ms
# Warmup Iteration   2: 8.914 ops/ms
# Warmup Iteration   3: 10.133 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.809 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.737 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (10.671, 10.737, 10.809), stdev = 0.069
  CI (99.9%): [9.473, 12.001] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.829 ops/ms
# Warmup Iteration   2: 10.943 ops/ms
# Warmup Iteration   3: 11.251 ops/ms
Iteration   1: 11.513 ops/ms
Iteration   2: 11.457 ops/ms
Iteration   3: 11.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.460 ±(99.9%) 0.942 ops/ms [Average]
  (min, avg, max) = (11.410, 11.460, 11.513), stdev = 0.052
  CI (99.9%): [10.517, 12.402] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.692 ops/ms
# Warmup Iteration   2: 10.639 ops/ms
# Warmup Iteration   3: 10.950 ops/ms
Iteration   1: 10.801 ops/ms
Iteration   2: 10.854 ops/ms
Iteration   3: 10.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.790 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (10.714, 10.790, 10.854), stdev = 0.071
  CI (99.9%): [9.503, 12.076] (assumes normal distribution)


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
# Warmup Iteration   1: 7.703 ops/ms
# Warmup Iteration   2: 7.825 ops/ms
# Warmup Iteration   3: 8.556 ops/ms
Iteration   1: 8.275 ops/ms
Iteration   2: 8.395 ops/ms
Iteration   3: 8.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.392 ±(99.9%) 2.091 ops/ms [Average]
  (min, avg, max) = (8.275, 8.392, 8.504), stdev = 0.115
  CI (99.9%): [6.300, 10.483] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
Iteration   1: 3.016 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.989 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (2.955, 2.989, 3.016), stdev = 0.031
  CI (99.9%): [2.423, 3.554] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.915 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.861 ±(99.9%) 0.004 ms/op
Iteration   1: 2.818 ±(99.9%) 0.002 ms/op
Iteration   2: 2.850 ±(99.9%) 0.004 ms/op
Iteration   3: 2.842 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.837 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.818, 2.837, 2.850), stdev = 0.016
  CI (99.9%): [2.541, 3.132] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.003 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.927 ±(99.9%) 0.002 ms/op
Iteration   3: 2.912 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.925 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (2.912, 2.925, 2.937), stdev = 0.013
  CI (99.9%): [2.693, 3.157] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.197 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.029 ms/op
Iteration   1: 3.762 ±(99.9%) 0.012 ms/op
Iteration   2: 3.733 ±(99.9%) 0.005 ms/op
Iteration   3: 3.866 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.787 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (3.733, 3.787, 3.866), stdev = 0.070
  CI (99.9%): [2.513, 5.061] (assumes normal distribution)


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  11.078 ms/op
                 createUser·p0.9999: 14.431 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  10.120 ms/op
                 createUser·p0.9999: 26.951 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  7.635 ms/op
                 createUser·p0.9999: 18.061 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319441
  mean =      3.003 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22322 
    [ 2.500,  5.000) = 295663 
    [ 5.000,  7.500) = 870 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     27.217 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.005 ms/op
Iteration   1: 2.869 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  5.948 ms/op
                 existUser·p0.9999: 15.268 ms/op
                 existUser·p1.00:   15.663 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  9.729 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  8.142 ms/op
                 existUser·p0.9999: 23.760 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329732
  mean =      2.909 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37564 
    [ 2.500,  5.000) = 290971 
    [ 5.000,  7.500) = 747 
    [ 7.500, 10.000) = 265 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.143 ms/op
     p(99.9900) =     19.544 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  10.219 ms/op
                 getUser·p0.9999: 12.272 ms/op
                 getUser·p1.00:   12.468 ms/op

Iteration   2: 2.976 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  7.295 ms/op
                 getUser·p0.9999: 13.111 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.519 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  6.119 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321606
  mean =      2.984 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21926 
    [ 2.500,  5.000) = 298396 
    [ 5.000,  7.500) = 900 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     19.737 ms/op
     p(99.9990) =     22.006 ms/op
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
# Warmup Iteration   1: 5.264 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.012 ms/op
Iteration   1: 3.998 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.469 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  13.554 ms/op
                 listUser·p0.9999: 17.988 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.763 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  14.408 ms/op
                 listUser·p0.9999: 17.166 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.978 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.334 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.946 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.984 ms/op
                 listUser·p0.9999: 17.890 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239159
  mean =      4.017 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 2186 
    [ 2.500,  3.750) = 103818 
    [ 3.750,  5.000) = 104996 
    [ 5.000,  6.250) = 20496 
    [ 6.250,  7.500) = 5768 
    [ 7.500,  8.750) = 1092 
    [ 8.750, 10.000) = 312 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 116 
    [15.000, 16.250) = 101 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     18.488 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.737 ± 1.264  ops/ms
ClientGrpc.existUser                       thrpt       3  11.460 ± 0.942  ops/ms
ClientGrpc.getUser                         thrpt       3  10.790 ± 1.286  ops/ms
ClientGrpc.listUser                        thrpt       3   8.392 ± 2.091  ops/ms
ClientGrpc.createUser                       avgt       3   2.989 ± 0.566   ms/op
ClientGrpc.existUser                        avgt       3   2.837 ± 0.296   ms/op
ClientGrpc.getUser                          avgt       3   2.925 ± 0.232   ms/op
ClientGrpc.listUser                         avgt       3   3.787 ± 1.274   ms/op
ClientGrpc.createUser                     sample  319441   3.003 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.597           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.174           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.280           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.263           ms/op
ClientGrpc.existUser                      sample  329732   2.909 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.504           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.143           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.544           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.986           ms/op
ClientGrpc.getUser                        sample  321606   2.984 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.519           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.249           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.737           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.053           ms/op
ClientGrpc.listUser                       sample  239159   4.017 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.334           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.793           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.809           ms/op
