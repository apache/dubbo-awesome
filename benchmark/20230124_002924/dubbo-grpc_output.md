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
# Warmup Iteration   1: 4.241 ops/ms
# Warmup Iteration   2: 9.064 ops/ms
# Warmup Iteration   3: 10.096 ops/ms
Iteration   1: 10.214 ops/ms
Iteration   2: 9.956 ops/ms
Iteration   3: 10.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.107 ±(99.9%) 2.456 ops/ms [Average]
  (min, avg, max) = (9.956, 10.107, 10.214), stdev = 0.135
  CI (99.9%): [7.651, 12.563] (assumes normal distribution)


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
# Warmup Iteration   1: 7.716 ops/ms
# Warmup Iteration   2: 10.195 ops/ms
# Warmup Iteration   3: 10.397 ops/ms
Iteration   1: 10.455 ops/ms
Iteration   2: 10.641 ops/ms
Iteration   3: 10.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.477 ±(99.9%) 2.815 ops/ms [Average]
  (min, avg, max) = (10.335, 10.477, 10.641), stdev = 0.154
  CI (99.9%): [7.661, 13.292] (assumes normal distribution)


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
# Warmup Iteration   1: 7.256 ops/ms
# Warmup Iteration   2: 9.843 ops/ms
# Warmup Iteration   3: 9.973 ops/ms
Iteration   1: 9.999 ops/ms
Iteration   2: 9.971 ops/ms
Iteration   3: 9.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.907 ±(99.9%) 2.476 ops/ms [Average]
  (min, avg, max) = (9.751, 9.907, 9.999), stdev = 0.136
  CI (99.9%): [7.430, 12.383] (assumes normal distribution)


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
# Warmup Iteration   1: 5.444 ops/ms
# Warmup Iteration   2: 7.534 ops/ms
# Warmup Iteration   3: 7.739 ops/ms
Iteration   1: 7.913 ops/ms
Iteration   2: 8.594 ops/ms
Iteration   3: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.202 ±(99.9%) 6.419 ops/ms [Average]
  (min, avg, max) = (7.913, 8.202, 8.594), stdev = 0.352
  CI (99.9%): [1.783, 14.621] (assumes normal distribution)


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
# Warmup Iteration   1: 4.204 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.005 ms/op
Iteration   1: 3.273 ±(99.9%) 0.002 ms/op
Iteration   2: 3.226 ±(99.9%) 0.002 ms/op
Iteration   3: 3.218 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.239 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.218, 3.239, 3.273), stdev = 0.029
  CI (99.9%): [2.702, 3.776] (assumes normal distribution)


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.002 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 2.998 ±(99.9%) 0.002 ms/op
Iteration   3: 2.999 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.009 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (2.998, 3.009, 3.031), stdev = 0.019
  CI (99.9%): [2.670, 3.349] (assumes normal distribution)


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.002 ms/op
Iteration   1: 3.223 ±(99.9%) 0.002 ms/op
Iteration   2: 3.209 ±(99.9%) 0.003 ms/op
Iteration   3: 3.185 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.206 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (3.185, 3.206, 3.223), stdev = 0.019
  CI (99.9%): [2.858, 3.553] (assumes normal distribution)


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
# Warmup Iteration   1: 5.344 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.016 ms/op
Iteration   1: 3.940 ±(99.9%) 0.007 ms/op
Iteration   2: 3.899 ±(99.9%) 0.005 ms/op
Iteration   3: 3.945 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (3.899, 3.928, 3.945), stdev = 0.025
  CI (99.9%): [3.469, 4.388] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.006 ms/op
Iteration   1: 3.327 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 13.310 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   2: 3.235 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.256 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.597 ms/op
                 createUser·p0.9999: 15.093 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   3: 3.197 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  10.240 ms/op
                 createUser·p0.9999: 18.153 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295267
  mean =      3.252 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 253 
    [ 1.250,  2.500) = 17506 
    [ 2.500,  3.750) = 222733 
    [ 3.750,  5.000) = 53304 
    [ 5.000,  6.250) = 667 
    [ 6.250,  7.500) = 347 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.256 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      9.531 ms/op
     p(99.9900) =     17.331 ms/op
     p(99.9990) =     18.386 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.376 ms/op
                 existUser·p0.9999: 13.183 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  11.634 ms/op
                 existUser·p0.9999: 15.483 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.469 ms/op
                 existUser·p0.9999: 14.974 ms/op
                 existUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313853
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1106 
    [ 1.250,  2.500) = 39770 
    [ 2.500,  3.750) = 238888 
    [ 3.750,  5.000) = 33086 
    [ 5.000,  6.250) = 476 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.473 ms/op
     p(99.9900) =     15.122 ms/op
     p(99.9990) =     16.227 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.441 ms/op
                 getUser·p0.9999: 12.860 ms/op
                 getUser·p1.00:   13.124 ms/op

Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  9.130 ms/op
                 getUser·p0.9999: 13.940 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 3.154 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.697 ms/op
                 getUser·p0.9999: 19.106 ms/op
                 getUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304348
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20413 
    [ 2.500,  5.000) = 282512 
    [ 5.000,  7.500) = 1027 
    [ 7.500, 10.000) = 233 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.285 ms/op
     p(99.9900) =     14.362 ms/op
     p(99.9990) =     20.345 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 5.705 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.011 ms/op
Iteration   1: 3.969 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 18.674 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 3.913 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.346 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 4.060 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  19.323 ms/op
                 listUser·p0.9999: 23.560 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241039
  mean =      3.980 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2980 
    [ 2.500,  5.000) = 212106 
    [ 5.000,  7.500) = 24438 
    [ 7.500, 10.000) = 997 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     23.678 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.107 ± 2.456  ops/ms
ClientGrpc.existUser                       thrpt       3  10.477 ± 2.815  ops/ms
ClientGrpc.getUser                         thrpt       3   9.907 ± 2.476  ops/ms
ClientGrpc.listUser                        thrpt       3   8.202 ± 6.419  ops/ms
ClientGrpc.createUser                       avgt       3   3.239 ± 0.537   ms/op
ClientGrpc.existUser                        avgt       3   3.009 ± 0.339   ms/op
ClientGrpc.getUser                          avgt       3   3.206 ± 0.348   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 0.459   ms/op
ClientGrpc.createUser                     sample  295267   3.252 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.256           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.203           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.990           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.178           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.531           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.331           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.547           ms/op
ClientGrpc.existUser                      sample  313853   3.059 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.693           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.473           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.122           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.302           ms/op
ClientGrpc.getUser                        sample  304348   3.154 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.602           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.285           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.362           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.480           ms/op
ClientGrpc.listUser                       sample  241039   3.980 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.926           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.286           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.970           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.790           ms/op
