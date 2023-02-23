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
# Warmup Iteration   1: 3.635 ops/ms
# Warmup Iteration   2: 8.521 ops/ms
# Warmup Iteration   3: 9.745 ops/ms
Iteration   1: 10.194 ops/ms
Iteration   2: 10.016 ops/ms
Iteration   3: 9.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.953 ±(99.9%) 5.071 ops/ms [Average]
  (min, avg, max) = (9.649, 9.953, 10.194), stdev = 0.278
  CI (99.9%): [4.881, 15.024] (assumes normal distribution)


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
# Warmup Iteration   1: 6.932 ops/ms
# Warmup Iteration   2: 9.928 ops/ms
# Warmup Iteration   3: 10.220 ops/ms
Iteration   1: 10.514 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.662 ±(99.9%) 2.696 ops/ms [Average]
  (min, avg, max) = (10.514, 10.662, 10.810), stdev = 0.148
  CI (99.9%): [7.966, 13.357] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.336 ops/ms
# Warmup Iteration   2: 9.798 ops/ms
# Warmup Iteration   3: 10.004 ops/ms
Iteration   1: 10.043 ops/ms
Iteration   2: 10.046 ops/ms
Iteration   3: 10.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.030 ±(99.9%) 0.471 ops/ms [Average]
  (min, avg, max) = (10.000, 10.030, 10.046), stdev = 0.026
  CI (99.9%): [9.558, 10.501] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.034 ops/ms
# Warmup Iteration   2: 7.298 ops/ms
# Warmup Iteration   3: 7.752 ops/ms
Iteration   1: 7.624 ops/ms
Iteration   2: 7.696 ops/ms
Iteration   3: 7.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.679 ±(99.9%) 0.891 ops/ms [Average]
  (min, avg, max) = (7.624, 7.679, 7.718), stdev = 0.049
  CI (99.9%): [6.789, 8.570] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.008 ms/op
Iteration   1: 3.236 ±(99.9%) 0.002 ms/op
Iteration   2: 3.297 ±(99.9%) 0.002 ms/op
Iteration   3: 3.172 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.235 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (3.172, 3.235, 3.297), stdev = 0.063
  CI (99.9%): [2.092, 4.378] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.003 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.086 ±(99.9%) 0.002 ms/op
Iteration   3: 3.021 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.069 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (3.021, 3.069, 3.100), stdev = 0.042
  CI (99.9%): [2.300, 3.838] (assumes normal distribution)


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.002 ms/op
Iteration   1: 3.218 ±(99.9%) 0.002 ms/op
Iteration   2: 3.261 ±(99.9%) 0.002 ms/op
Iteration   3: 3.171 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.217 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (3.171, 3.217, 3.261), stdev = 0.045
  CI (99.9%): [2.399, 4.034] (assumes normal distribution)


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
# Warmup Iteration   1: 5.867 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.009 ms/op
Iteration   1: 4.184 ±(99.9%) 0.009 ms/op
Iteration   2: 4.079 ±(99.9%) 0.017 ms/op
Iteration   3: 4.082 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.115 ±(99.9%) 1.084 ms/op [Average]
  (min, avg, max) = (4.079, 4.115, 4.184), stdev = 0.059
  CI (99.9%): [3.031, 5.199] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.573 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.007 ms/op
Iteration   1: 3.270 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  11.062 ms/op
                 createUser·p0.9999: 18.849 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.622 ms/op
                 createUser·p0.9999: 19.790 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.487 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  11.496 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300371
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19711 
    [ 2.500,  5.000) = 279204 
    [ 5.000,  7.500) = 1002 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =     10.863 ms/op
     p(99.9900) =     21.101 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.365 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.136 ms/op
                 existUser·p0.9999: 16.717 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 3.146 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.950 ms/op
                 existUser·p0.9999: 16.004 ms/op
                 existUser·p1.00:   16.613 ms/op

Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.300 ms/op
                 existUser·p0.9999: 17.010 ms/op
                 existUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 310220
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1758 
    [ 1.250,  2.500) = 35846 
    [ 2.500,  3.750) = 233070 
    [ 3.750,  5.000) = 38748 
    [ 5.000,  6.250) = 312 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.356 ms/op
     p(99.9900) =     16.597 ms/op
     p(99.9990) =     19.061 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.007 ms/op
Iteration   1: 3.302 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.046 ms/op
                 getUser·p0.9999: 14.794 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 3.258 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.354 ms/op
                 getUser·p0.9999: 15.863 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 3.261 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  10.386 ms/op
                 getUser·p0.9999: 20.525 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 293162
  mean =      3.273 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16673 
    [ 2.500,  5.000) = 275203 
    [ 5.000,  7.500) = 887 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.192 ms/op
     p(99.9900) =     19.519 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 6.183 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.482 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.013 ms/op
Iteration   1: 4.170 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  22.217 ms/op
                 listUser·p0.9999: 26.160 ms/op
                 listUser·p1.00:   30.966 ms/op

Iteration   2: 4.078 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  15.100 ms/op
                 listUser·p0.9999: 19.922 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.157 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.370 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 19.502 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232003
  mean =      4.135 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2843 
    [ 2.500,  5.000) = 197318 
    [ 5.000,  7.500) = 29935 
    [ 7.500, 10.000) = 1425 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     25.670 ms/op
     p(99.9990) =     29.161 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.953 ± 5.071  ops/ms
ClientGrpc.existUser                       thrpt       3  10.662 ± 2.696  ops/ms
ClientGrpc.getUser                         thrpt       3  10.030 ± 0.471  ops/ms
ClientGrpc.listUser                        thrpt       3   7.679 ± 0.891  ops/ms
ClientGrpc.createUser                       avgt       3   3.235 ± 1.143   ms/op
ClientGrpc.existUser                        avgt       3   3.069 ± 0.769   ms/op
ClientGrpc.getUser                          avgt       3   3.217 ± 0.817   ms/op
ClientGrpc.listUser                         avgt       3   4.115 ± 1.084   ms/op
ClientGrpc.createUser                     sample  300371   3.196 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.487           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.158           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.863           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.101           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.184           ms/op
ClientGrpc.existUser                      sample  310220   3.093 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.733           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.088           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.356           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.597           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.169           ms/op
ClientGrpc.getUser                        sample  293162   3.273 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.723           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.256           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.182           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.192           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.519           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.709           ms/op
ClientGrpc.listUser                       sample  232003   4.135 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.868           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.891           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.670           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.966           ms/op
