# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.856 ops/ms
# Warmup Iteration   2: 9.127 ops/ms
# Warmup Iteration   3: 10.041 ops/ms
Iteration   1: 9.994 ops/ms
Iteration   2: 9.865 ops/ms
Iteration   3: 10.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.973 ±(99.9%) 1.810 ops/ms [Average]
  (min, avg, max) = (9.865, 9.973, 10.060), stdev = 0.099
  CI (99.9%): [8.163, 11.783] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.800 ops/ms
# Warmup Iteration   2: 10.153 ops/ms
# Warmup Iteration   3: 10.846 ops/ms
Iteration   1: 11.034 ops/ms
Iteration   2: 10.305 ops/ms
Iteration   3: 10.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.574 ±(99.9%) 7.314 ops/ms [Average]
  (min, avg, max) = (10.305, 10.574, 11.034), stdev = 0.401
  CI (99.9%): [3.259, 17.888] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.946 ops/ms
# Warmup Iteration   2: 9.877 ops/ms
# Warmup Iteration   3: 10.018 ops/ms
Iteration   1: 10.265 ops/ms
Iteration   2: 10.123 ops/ms
Iteration   3: 10.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.156 ±(99.9%) 1.756 ops/ms [Average]
  (min, avg, max) = (10.081, 10.156, 10.265), stdev = 0.096
  CI (99.9%): [8.400, 11.913] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.636 ops/ms
# Warmup Iteration   2: 7.588 ops/ms
# Warmup Iteration   3: 7.825 ops/ms
Iteration   1: 8.005 ops/ms
Iteration   2: 8.023 ops/ms
Iteration   3: 8.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.012 ±(99.9%) 0.170 ops/ms [Average]
  (min, avg, max) = (8.005, 8.012, 8.023), stdev = 0.009
  CI (99.9%): [7.842, 8.182] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.409 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.003 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.219 ±(99.9%) 0.001 ms/op
Iteration   3: 3.196 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.195 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (3.171, 3.195, 3.219), stdev = 0.024
  CI (99.9%): [2.755, 3.635] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.546 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 2.984 ±(99.9%) 0.002 ms/op
Iteration   3: 2.918 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.965 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (2.918, 2.965, 2.992), stdev = 0.040
  CI (99.9%): [2.231, 3.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.161 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.002 ms/op
Iteration   1: 3.091 ±(99.9%) 0.003 ms/op
Iteration   2: 3.136 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.129 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.091, 3.129, 3.161), stdev = 0.036
  CI (99.9%): [2.476, 3.783] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.373 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.008 ms/op
Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
Iteration   2: 3.958 ±(99.9%) 0.008 ms/op
Iteration   3: 3.987 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (3.950, 3.965, 3.987), stdev = 0.019
  CI (99.9%): [3.614, 4.316] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.262 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.322 ms/op
                 createUser·p0.9999: 15.797 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.436 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  12.464 ms/op
                 createUser·p0.9999: 23.167 ms/op
                 createUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300219
  mean =      3.197 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22152 
    [ 2.500,  5.000) = 276676 
    [ 5.000,  7.500) = 926 
    [ 7.500, 10.000) = 198 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     22.707 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.858 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
Iteration   1: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  8.760 ms/op
                 existUser·p0.9999: 16.266 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  9.817 ms/op
                 existUser·p0.9999: 14.811 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 19.792 ms/op
                 existUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315761
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1323 
    [ 1.250,  2.500) = 41294 
    [ 2.500,  3.750) = 242542 
    [ 3.750,  5.000) = 29381 
    [ 5.000,  6.250) = 574 
    [ 6.250,  7.500) = 251 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.474 ms/op
     p(99.9900) =     17.043 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.201 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.135 ms/op
                 getUser·p0.9999: 16.551 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.139 ms/op
                 getUser·p0.9999: 29.883 ms/op
                 getUser·p1.00:   30.343 ms/op

Iteration   3: 3.040 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.952 ms/op
                 getUser·p0.9999: 23.329 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309482
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29158 
    [ 2.500,  5.000) = 279102 
    [ 5.000,  7.500) = 857 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.336 ms/op
     p(99.9900) =     28.906 ms/op
     p(99.9990) =     30.242 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.293 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.012 ms/op
Iteration   1: 4.012 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  12.739 ms/op
                 listUser·p0.9999: 16.318 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   2: 4.051 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  16.811 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 3.897 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  16.102 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240760
  mean =      3.986 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2057 
    [ 2.500,  5.000) = 213243 
    [ 5.000,  7.500) = 24395 
    [ 7.500, 10.000) = 663 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.933 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.973 ± 1.810  ops/ms
ClientGrpc.existUser                       thrpt       3  10.574 ± 7.314  ops/ms
ClientGrpc.getUser                         thrpt       3  10.156 ± 1.756  ops/ms
ClientGrpc.listUser                        thrpt       3   8.012 ± 0.170  ops/ms
ClientGrpc.createUser                       avgt       3   3.195 ± 0.440   ms/op
ClientGrpc.existUser                        avgt       3   2.965 ± 0.734   ms/op
ClientGrpc.getUser                          avgt       3   3.129 ± 0.654   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 0.351   ms/op
ClientGrpc.createUser                     sample  300219   3.197 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.096           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.699           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.707           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.280           ms/op
ClientGrpc.existUser                      sample  315761   3.040 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.536           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.936           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.474           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.043           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.923           ms/op
ClientGrpc.getUser                        sample  309482   3.103 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.605           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.336           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.906           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.343           ms/op
ClientGrpc.listUser                       sample  240760   3.986 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.942           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.933           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.725           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.658           ms/op
