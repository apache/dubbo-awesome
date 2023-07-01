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
# Warmup Iteration   1: 4.088 ops/ms
# Warmup Iteration   2: 9.327 ops/ms
# Warmup Iteration   3: 10.136 ops/ms
Iteration   1: 10.533 ops/ms
Iteration   2: 10.540 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.483 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (10.378, 10.483, 10.540), stdev = 0.092
  CI (99.9%): [8.812, 12.154] (assumes normal distribution)


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
# Warmup Iteration   1: 7.359 ops/ms
# Warmup Iteration   2: 10.625 ops/ms
# Warmup Iteration   3: 10.807 ops/ms
Iteration   1: 10.805 ops/ms
Iteration   2: 10.820 ops/ms
Iteration   3: 11.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.924 ±(99.9%) 3.499 ops/ms [Average]
  (min, avg, max) = (10.805, 10.924, 11.145), stdev = 0.192
  CI (99.9%): [7.425, 14.422] (assumes normal distribution)


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
# Warmup Iteration   1: 7.079 ops/ms
# Warmup Iteration   2: 9.903 ops/ms
# Warmup Iteration   3: 10.379 ops/ms
Iteration   1: 10.341 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.374 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (10.328, 10.374, 10.454), stdev = 0.069
  CI (99.9%): [9.111, 11.638] (assumes normal distribution)


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
# Warmup Iteration   1: 5.157 ops/ms
# Warmup Iteration   2: 7.632 ops/ms
# Warmup Iteration   3: 7.805 ops/ms
Iteration   1: 7.863 ops/ms
Iteration   2: 7.862 ops/ms
Iteration   3: 7.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.857 ±(99.9%) 0.176 ops/ms [Average]
  (min, avg, max) = (7.846, 7.857, 7.863), stdev = 0.010
  CI (99.9%): [7.681, 8.033] (assumes normal distribution)


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
# Warmup Iteration   1: 4.154 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
Iteration   2: 3.052 ±(99.9%) 0.002 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (3.027, 3.037, 3.052), stdev = 0.014
  CI (99.9%): [2.786, 3.287] (assumes normal distribution)


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.002 ms/op
Iteration   2: 2.922 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.948 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (2.922, 2.948, 2.962), stdev = 0.023
  CI (99.9%): [2.530, 3.366] (assumes normal distribution)


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.011 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
Iteration   3: 3.081 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (3.041, 3.058, 3.081), stdev = 0.021
  CI (99.9%): [2.679, 3.437] (assumes normal distribution)


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
# Warmup Iteration   1: 5.524 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.031 ms/op
Iteration   1: 4.019 ±(99.9%) 0.010 ms/op
Iteration   2: 3.990 ±(99.9%) 0.014 ms/op
Iteration   3: 4.047 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.019 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (3.990, 4.019, 4.047), stdev = 0.028
  CI (99.9%): [3.501, 4.536] (assumes normal distribution)


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
# Warmup Iteration   1: 4.761 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  11.557 ms/op
                 createUser·p0.9999: 16.752 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.307 ms/op
                 createUser·p0.999:  7.615 ms/op
                 createUser·p0.9999: 20.070 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  9.636 ms/op
                 createUser·p0.9999: 21.975 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313940
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19286 
    [ 2.500,  5.000) = 293062 
    [ 5.000,  7.500) = 1190 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.339 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.948 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.595 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   2: 2.941 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   3.947 ms/op
                 existUser·p0.999:  5.857 ms/op
                 existUser·p0.9999: 15.729 ms/op
                 existUser·p1.00:   16.073 ms/op

Iteration   3: 2.941 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  6.687 ms/op
                 existUser·p0.9999: 16.921 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325352
  mean =      2.948 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 473 
    [ 1.250,  2.500) = 30802 
    [ 2.500,  3.750) = 284351 
    [ 3.750,  5.000) = 8518 
    [ 5.000,  6.250) = 734 
    [ 6.250,  7.500) = 239 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.977 ms/op
     p(99.9900) =     16.269 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.008 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.648 ms/op
                 getUser·p0.9999: 17.681 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  6.996 ms/op
                 getUser·p0.9999: 29.703 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.349 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  10.753 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311553
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18764 
    [ 2.500,  5.000) = 290891 
    [ 5.000,  7.500) = 1556 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      8.012 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 5.770 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.011 ms/op
Iteration   1: 4.078 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.966 ms/op
                 listUser·p0.9999: 16.478 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.354 ms/op
                 listUser·p0.9999: 25.791 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   3: 4.044 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  20.629 ms/op
                 listUser·p0.9999: 31.758 ms/op
                 listUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237287
  mean =      4.046 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1985 
    [ 2.500,  5.000) = 213001 
    [ 5.000,  7.500) = 20469 
    [ 7.500, 10.000) = 1322 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     15.808 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     32.207 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.483 ± 1.671  ops/ms
ClientGrpc.existUser                       thrpt       3  10.924 ± 3.499  ops/ms
ClientGrpc.getUser                         thrpt       3  10.374 ± 1.263  ops/ms
ClientGrpc.listUser                        thrpt       3   7.857 ± 0.176  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.251   ms/op
ClientGrpc.existUser                        avgt       3   2.948 ± 0.418   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.379   ms/op
ClientGrpc.listUser                         avgt       3   4.019 ± 0.518   ms/op
ClientGrpc.createUser                     sample  313940   3.056 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.306           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.627           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.708           ms/op
ClientGrpc.existUser                      sample  325352   2.948 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.499           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.977           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.269           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.334           ms/op
ClientGrpc.getUser                        sample  311553   3.080 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.349           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.012           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.017           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.048           ms/op
ClientGrpc.listUser                       sample  237287   4.046 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.102           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.808           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.900           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.227           ms/op
