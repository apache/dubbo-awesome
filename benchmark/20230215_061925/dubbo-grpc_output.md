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
# Warmup Iteration   1: 3.988 ops/ms
# Warmup Iteration   2: 8.849 ops/ms
# Warmup Iteration   3: 9.813 ops/ms
Iteration   1: 9.876 ops/ms
Iteration   2: 9.904 ops/ms
Iteration   3: 9.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.850 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (9.771, 9.850, 9.904), stdev = 0.070
  CI (99.9%): [8.570, 11.131] (assumes normal distribution)


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
# Warmup Iteration   1: 7.083 ops/ms
# Warmup Iteration   2: 10.076 ops/ms
# Warmup Iteration   3: 10.118 ops/ms
Iteration   1: 10.525 ops/ms
Iteration   2: 10.323 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.425 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (10.323, 10.425, 10.525), stdev = 0.101
  CI (99.9%): [8.584, 12.266] (assumes normal distribution)


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
# Warmup Iteration   1: 6.435 ops/ms
# Warmup Iteration   2: 9.719 ops/ms
# Warmup Iteration   3: 9.882 ops/ms
Iteration   1: 10.083 ops/ms
Iteration   2: 9.939 ops/ms
Iteration   3: 10.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.049 ±(99.9%) 1.765 ops/ms [Average]
  (min, avg, max) = (9.939, 10.049, 10.123), stdev = 0.097
  CI (99.9%): [8.284, 11.813] (assumes normal distribution)


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
# Warmup Iteration   1: 4.973 ops/ms
# Warmup Iteration   2: 7.530 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 7.733 ops/ms
Iteration   2: 7.831 ops/ms
Iteration   3: 7.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.832 ±(99.9%) 1.830 ops/ms [Average]
  (min, avg, max) = (7.733, 7.832, 7.933), stdev = 0.100
  CI (99.9%): [6.002, 9.662] (assumes normal distribution)


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
# Warmup Iteration   1: 4.801 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.003 ms/op
Iteration   1: 3.210 ±(99.9%) 0.003 ms/op
Iteration   2: 3.256 ±(99.9%) 0.001 ms/op
Iteration   3: 3.293 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.253 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.210, 3.253, 3.293), stdev = 0.042
  CI (99.9%): [2.491, 4.015] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.002 ms/op
Iteration   1: 3.089 ±(99.9%) 0.002 ms/op
Iteration   2: 3.116 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.114 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (3.089, 3.114, 3.137), stdev = 0.024
  CI (99.9%): [2.675, 3.553] (assumes normal distribution)


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.224 ±(99.9%) 0.002 ms/op
Iteration   2: 3.268 ±(99.9%) 0.003 ms/op
Iteration   3: 3.229 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.240 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (3.224, 3.240, 3.268), stdev = 0.024
  CI (99.9%): [2.802, 3.679] (assumes normal distribution)


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
# Warmup Iteration   1: 5.653 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.018 ms/op
Iteration   1: 4.073 ±(99.9%) 0.006 ms/op
Iteration   2: 4.029 ±(99.9%) 0.006 ms/op
Iteration   3: 3.986 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.029 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.986, 4.029, 4.073), stdev = 0.044
  CI (99.9%): [3.231, 4.828] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.007 ms/op
Iteration   1: 3.148 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.442 ms/op
                 createUser·p0.9999: 25.330 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   2: 3.264 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 19.051 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 3.276 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 23.986 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297507
  mean =      3.228 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12077 
    [ 2.500,  5.000) = 284296 
    [ 5.000,  7.500) = 705 
    [ 7.500, 10.000) = 162 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      9.118 ms/op
     p(99.9900) =     24.560 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 3.111 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.234 ms/op
                 existUser·p0.9999: 12.847 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  11.858 ms/op
                 existUser·p0.9999: 18.485 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  5.415 ms/op
                 existUser·p0.9999: 17.666 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316260
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1298 
    [ 1.250,  2.500) = 37519 
    [ 2.500,  3.750) = 251518 
    [ 3.750,  5.000) = 24850 
    [ 5.000,  6.250) = 502 
    [ 6.250,  7.500) = 317 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.201 ms/op
     p(99.9900) =     17.576 ms/op
     p(99.9990) =     18.711 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.590 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.007 ms/op
Iteration   1: 3.165 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.926 ms/op
                 getUser·p0.9999: 17.134 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.406 ms/op
                 getUser·p0.9999: 19.194 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 3.189 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.825 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302673
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19755 
    [ 2.500,  5.000) = 281574 
    [ 5.000,  7.500) = 991 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.720 ms/op
     p(99.9900) =     20.135 ms/op
     p(99.9990) =     21.364 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 5.944 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.011 ms/op
Iteration   1: 4.122 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  13.889 ms/op
                 listUser·p0.9999: 18.225 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   2: 4.138 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.330 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.322 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.542 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  16.850 ms/op
                 listUser·p0.9999: 21.583 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232679
  mean =      4.124 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2257 
    [ 2.500,  5.000) = 201573 
    [ 5.000,  7.500) = 27276 
    [ 7.500, 10.000) = 1107 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.330 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     22.637 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.850 ± 1.281  ops/ms
ClientGrpc.existUser                       thrpt       3  10.425 ± 1.841  ops/ms
ClientGrpc.getUser                         thrpt       3  10.049 ± 1.765  ops/ms
ClientGrpc.listUser                        thrpt       3   7.832 ± 1.830  ops/ms
ClientGrpc.createUser                       avgt       3   3.253 ± 0.762   ms/op
ClientGrpc.existUser                        avgt       3   3.114 ± 0.439   ms/op
ClientGrpc.getUser                          avgt       3   3.240 ± 0.439   ms/op
ClientGrpc.listUser                         avgt       3   4.029 ± 0.798   ms/op
ClientGrpc.createUser                     sample  297507   3.228 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.657           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.183           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.108           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.118           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.560           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.526           ms/op
ClientGrpc.existUser                      sample  316260   3.037 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.776           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.201           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.576           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  302673   3.171 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.772           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.146           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.030           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.720           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.135           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.496           ms/op
ClientGrpc.listUser                       sample  232679   4.124 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.330           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.944           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.926           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.430           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.265           ms/op
