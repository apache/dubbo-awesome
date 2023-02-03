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
# Warmup Iteration   1: 4.391 ops/ms
# Warmup Iteration   2: 9.304 ops/ms
# Warmup Iteration   3: 10.234 ops/ms
Iteration   1: 10.343 ops/ms
Iteration   2: 10.297 ops/ms
Iteration   3: 10.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.414 ±(99.9%) 2.995 ops/ms [Average]
  (min, avg, max) = (10.297, 10.414, 10.601), stdev = 0.164
  CI (99.9%): [7.418, 13.409] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.729 ops/ms
# Warmup Iteration   2: 10.412 ops/ms
# Warmup Iteration   3: 10.353 ops/ms
Iteration   1: 10.422 ops/ms
Iteration   2: 10.827 ops/ms
Iteration   3: 10.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.625 ±(99.9%) 3.688 ops/ms [Average]
  (min, avg, max) = (10.422, 10.625, 10.827), stdev = 0.202
  CI (99.9%): [6.937, 14.312] (assumes normal distribution)


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
# Warmup Iteration   1: 7.027 ops/ms
# Warmup Iteration   2: 10.062 ops/ms
# Warmup Iteration   3: 10.302 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 10.270 ops/ms
Iteration   3: 10.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.172 ±(99.9%) 2.289 ops/ms [Average]
  (min, avg, max) = (10.031, 10.172, 10.270), stdev = 0.125
  CI (99.9%): [7.884, 12.461] (assumes normal distribution)


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
# Warmup Iteration   1: 6.297 ops/ms
# Warmup Iteration   2: 7.349 ops/ms
# Warmup Iteration   3: 7.813 ops/ms
Iteration   1: 7.901 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 7.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.950 ±(99.9%) 2.543 ops/ms [Average]
  (min, avg, max) = (7.842, 7.950, 8.107), stdev = 0.139
  CI (99.9%): [5.407, 10.492] (assumes normal distribution)


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.004 ms/op
Iteration   1: 3.125 ±(99.9%) 0.003 ms/op
Iteration   2: 3.167 ±(99.9%) 0.002 ms/op
Iteration   3: 3.127 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.139 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.125, 3.139, 3.167), stdev = 0.024
  CI (99.9%): [2.708, 3.571] (assumes normal distribution)


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.002 ms/op
Iteration   1: 2.973 ±(99.9%) 0.003 ms/op
Iteration   2: 2.974 ±(99.9%) 0.003 ms/op
Iteration   3: 2.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.966 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (2.949, 2.966, 2.974), stdev = 0.014
  CI (99.9%): [2.705, 3.226] (assumes normal distribution)


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.002 ms/op
Iteration   1: 3.081 ±(99.9%) 0.003 ms/op
Iteration   2: 3.152 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.131 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (3.081, 3.131, 3.161), stdev = 0.044
  CI (99.9%): [2.337, 3.925] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.359 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.017 ms/op
Iteration   1: 3.977 ±(99.9%) 0.018 ms/op
Iteration   2: 4.109 ±(99.9%) 0.009 ms/op
Iteration   3: 4.014 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.033 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (3.977, 4.033, 4.109), stdev = 0.068
  CI (99.9%): [2.792, 5.275] (assumes normal distribution)


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
Iteration   1: 3.226 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  7.503 ms/op
                 createUser·p0.9999: 17.923 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.168 ms/op
                 createUser·p0.9999: 15.609 ms/op
                 createUser·p1.00:   16.237 ms/op

Iteration   3: 3.227 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 15.389 ms/op
                 createUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301158
  mean =      3.185 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 916 
    [ 1.250,  2.500) = 20827 
    [ 2.500,  3.750) = 235706 
    [ 3.750,  5.000) = 42436 
    [ 5.000,  6.250) = 503 
    [ 6.250,  7.500) = 385 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.856 ms/op
     p(99.9900) =     17.294 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.254 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 12.145 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  6.668 ms/op
                 existUser·p0.9999: 16.950 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.946 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322200
  mean =      2.978 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1760 
    [ 1.250,  2.500) = 36030 
    [ 2.500,  3.750) = 268208 
    [ 3.750,  5.000) = 15154 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.536 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.130 ms/op
                 getUser·p0.999:  8.784 ms/op
                 getUser·p0.9999: 16.129 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.674 ms/op
                 getUser·p0.9999: 18.046 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   3: 3.183 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.483 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.943 ms/op
                 getUser·p0.9999: 17.955 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306071
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 856 
    [ 1.250,  2.500) = 17252 
    [ 2.500,  3.750) = 257410 
    [ 3.750,  5.000) = 29453 
    [ 5.000,  6.250) = 508 
    [ 6.250,  7.500) = 289 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.462 ms/op
     p(99.9900) =     17.740 ms/op
     p(99.9990) =     18.414 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.953 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.010 ms/op
Iteration   1: 4.193 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  12.958 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.520 ms/op
                 listUser·p0.9999: 16.488 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   6.861 ms/op
                 listUser·p0.999:  15.380 ms/op
                 listUser·p0.9999: 19.465 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234717
  mean =      4.089 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4104 
    [ 2.500,  5.000) = 189526 
    [ 5.000,  7.500) = 39546 
    [ 7.500, 10.000) = 1075 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.160 ms/op
     p(99.9900) =     18.662 ms/op
     p(99.9990) =     20.010 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.414 ± 2.995  ops/ms
ClientGrpc.existUser                       thrpt       3  10.625 ± 3.688  ops/ms
ClientGrpc.getUser                         thrpt       3  10.172 ± 2.289  ops/ms
ClientGrpc.listUser                        thrpt       3   7.950 ± 2.543  ops/ms
ClientGrpc.createUser                       avgt       3   3.139 ± 0.431   ms/op
ClientGrpc.existUser                        avgt       3   2.966 ± 0.261   ms/op
ClientGrpc.getUser                          avgt       3   3.131 ± 0.794   ms/op
ClientGrpc.listUser                         avgt       3   4.033 ± 1.241   ms/op
ClientGrpc.createUser                     sample  301158   3.185 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.599           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.166           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.856           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.294           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.711           ms/op
ClientGrpc.existUser                      sample  322200   2.978 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.254           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.929           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.941           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.629           ms/op
ClientGrpc.getUser                        sample  306071   3.136 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.483           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.462           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.740           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.481           ms/op
ClientGrpc.listUser                       sample  234717   4.089 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.864           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.160           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.662           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.087           ms/op
