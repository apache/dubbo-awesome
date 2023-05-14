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
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 5.189 ops/ms
# Warmup Iteration   3: 7.137 ops/ms
Iteration   1: 7.450 ops/ms
Iteration   2: 7.329 ops/ms
Iteration   3: 7.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.399 ±(99.9%) 1.148 ops/ms [Average]
  (min, avg, max) = (7.329, 7.399, 7.450), stdev = 0.063
  CI (99.9%): [6.251, 8.547] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.544 ops/ms
# Warmup Iteration   2: 7.230 ops/ms
# Warmup Iteration   3: 7.931 ops/ms
Iteration   1: 7.823 ops/ms
Iteration   2: 7.912 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.887 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (7.823, 7.887, 7.925), stdev = 0.056
  CI (99.9%): [6.873, 8.900] (assumes normal distribution)


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
# Warmup Iteration   1: 4.348 ops/ms
# Warmup Iteration   2: 6.923 ops/ms
# Warmup Iteration   3: 7.509 ops/ms
Iteration   1: 7.578 ops/ms
Iteration   2: 7.714 ops/ms
Iteration   3: 7.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.705 ±(99.9%) 2.248 ops/ms [Average]
  (min, avg, max) = (7.578, 7.705, 7.824), stdev = 0.123
  CI (99.9%): [5.457, 9.953] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.380 ops/ms
# Warmup Iteration   2: 4.919 ops/ms
# Warmup Iteration   3: 5.372 ops/ms
Iteration   1: 5.685 ops/ms
Iteration   2: 5.971 ops/ms
Iteration   3: 6.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.939 ±(99.9%) 4.378 ops/ms [Average]
  (min, avg, max) = (5.685, 5.939, 6.161), stdev = 0.240
  CI (99.9%): [1.561, 10.317] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.003 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.580 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.382 ±(99.9%) 0.009 ms/op
Iteration   1: 4.297 ±(99.9%) 0.002 ms/op
Iteration   2: 4.355 ±(99.9%) 0.003 ms/op
Iteration   3: 4.402 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.351 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (4.297, 4.351, 4.402), stdev = 0.052
  CI (99.9%): [3.395, 5.308] (assumes normal distribution)


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
# Warmup Iteration   1: 6.117 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.004 ms/op
Iteration   1: 4.263 ±(99.9%) 0.002 ms/op
Iteration   2: 3.992 ±(99.9%) 0.005 ms/op
Iteration   3: 4.109 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.121 ±(99.9%) 2.475 ms/op [Average]
  (min, avg, max) = (3.992, 4.121, 4.263), stdev = 0.136
  CI (99.9%): [1.646, 6.597] (assumes normal distribution)


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
# Warmup Iteration   1: 7.306 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.597 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.003 ms/op
Iteration   1: 4.151 ±(99.9%) 0.003 ms/op
Iteration   2: 4.376 ±(99.9%) 0.002 ms/op
Iteration   3: 4.273 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.267 ±(99.9%) 2.054 ms/op [Average]
  (min, avg, max) = (4.151, 4.267, 4.376), stdev = 0.113
  CI (99.9%): [2.213, 6.320] (assumes normal distribution)


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
# Warmup Iteration   1: 7.910 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 6.175 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.613 ±(99.9%) 0.021 ms/op
Iteration   1: 5.362 ±(99.9%) 0.014 ms/op
Iteration   2: 5.339 ±(99.9%) 0.017 ms/op
Iteration   3: 5.446 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.382 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (5.339, 5.382, 5.446), stdev = 0.056
  CI (99.9%): [4.356, 6.409] (assumes normal distribution)


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
# Warmup Iteration   1: 7.418 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.565 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.430 ±(99.9%) 0.013 ms/op
Iteration   1: 4.393 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  14.858 ms/op
                 createUser·p0.9999: 27.310 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   2: 4.282 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   4.182 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  12.687 ms/op
                 createUser·p0.9999: 24.871 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 4.270 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  17.277 ms/op
                 createUser·p0.9999: 27.869 ms/op
                 createUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222337
  mean =      4.314 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3035 
    [ 2.500,  5.000) = 183966 
    [ 5.000,  7.500) = 33590 
    [ 7.500, 10.000) = 1125 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     14.855 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     28.257 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 6.348 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.307 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.010 ms/op
Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.337 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  12.649 ms/op
                 existUser·p0.9999: 15.945 ms/op
                 existUser·p1.00:   16.220 ms/op

Iteration   2: 4.020 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  10.541 ms/op
                 existUser·p0.9999: 17.204 ms/op
                 existUser·p1.00:   18.842 ms/op

Iteration   3: 4.088 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.413 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   5.693 ms/op
                 existUser·p0.99:   7.594 ms/op
                 existUser·p0.999:  10.547 ms/op
                 existUser·p0.9999: 26.018 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 235896
  mean =      4.069 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6988 
    [ 2.500,  5.000) = 204114 
    [ 5.000,  7.500) = 22866 
    [ 7.500, 10.000) = 1517 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     11.439 ms/op
     p(99.9900) =     23.739 ms/op
     p(99.9990) =     26.942 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 6.836 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.341 ±(99.9%) 0.012 ms/op
Iteration   1: 4.300 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  9.595 ms/op
                 getUser·p0.9999: 16.807 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   2: 4.245 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   4.162 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  9.347 ms/op
                 getUser·p0.9999: 17.639 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   3: 4.249 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   4.153 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  10.535 ms/op
                 getUser·p0.9999: 20.934 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225009
  mean =      4.265 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1816 
    [ 2.500,  5.000) = 192012 
    [ 5.000,  7.500) = 29982 
    [ 7.500, 10.000) = 1008 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.178 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 7.305 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.925 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.458 ±(99.9%) 0.020 ms/op
Iteration   1: 5.472 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.840 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  17.058 ms/op
                 listUser·p0.9999: 20.242 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 5.374 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   5.153 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  18.151 ms/op
                 listUser·p0.9999: 23.991 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   3: 5.494 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  29.964 ms/op
                 listUser·p0.9999: 34.025 ms/op
                 listUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176132
  mean =      5.446 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 66670 
    [ 5.000,  7.500) = 98506 
    [ 7.500, 10.000) = 9209 
    [10.000, 12.500) = 1163 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.791 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     33.010 ms/op
     p(99.9990) =     35.708 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.399 ± 1.148  ops/ms
ClientGrpc.existUser                       thrpt       3   7.887 ± 1.014  ops/ms
ClientGrpc.getUser                         thrpt       3   7.705 ± 2.248  ops/ms
ClientGrpc.listUser                        thrpt       3   5.939 ± 4.378  ops/ms
ClientGrpc.createUser                       avgt       3   4.351 ± 0.957   ms/op
ClientGrpc.existUser                        avgt       3   4.121 ± 2.475   ms/op
ClientGrpc.getUser                          avgt       3   4.267 ± 2.054   ms/op
ClientGrpc.listUser                         avgt       3   5.382 ± 1.026   ms/op
ClientGrpc.createUser                     sample  222337   4.314 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.726           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.284           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.078           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.855           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.394           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.410           ms/op
ClientGrpc.existUser                      sample  235896   4.069 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.413           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.480           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.217           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.439           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.739           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.066           ms/op
ClientGrpc.getUser                        sample  225009   4.265 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.053           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.178           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.169           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.709           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.667           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.907           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  176132   5.446 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.122           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.791           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.896           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.481           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.010           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.307           ms/op
