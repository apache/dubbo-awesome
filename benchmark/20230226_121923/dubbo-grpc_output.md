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
# Warmup Iteration   1: 4.872 ops/ms
# Warmup Iteration   2: 8.976 ops/ms
# Warmup Iteration   3: 10.248 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.002 ops/ms
Iteration   3: 10.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.304 ±(99.9%) 5.088 ops/ms [Average]
  (min, avg, max) = (10.002, 10.304, 10.552), stdev = 0.279
  CI (99.9%): [5.216, 15.392] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.873 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 10.833 ops/ms
Iteration   1: 10.740 ops/ms
Iteration   2: 10.508 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.556 ±(99.9%) 3.005 ops/ms [Average]
  (min, avg, max) = (10.421, 10.556, 10.740), stdev = 0.165
  CI (99.9%): [7.551, 13.561] (assumes normal distribution)


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
# Warmup Iteration   1: 7.433 ops/ms
# Warmup Iteration   2: 10.329 ops/ms
# Warmup Iteration   3: 10.142 ops/ms
Iteration   1: 10.386 ops/ms
Iteration   2: 10.169 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.338 ±(99.9%) 2.746 ops/ms [Average]
  (min, avg, max) = (10.169, 10.338, 10.458), stdev = 0.151
  CI (99.9%): [7.591, 13.084] (assumes normal distribution)


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
# Warmup Iteration   1: 6.200 ops/ms
# Warmup Iteration   2: 7.811 ops/ms
# Warmup Iteration   3: 8.099 ops/ms
Iteration   1: 8.127 ops/ms
Iteration   2: 7.891 ops/ms
Iteration   3: 8.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.096 ±(99.9%) 3.488 ops/ms [Average]
  (min, avg, max) = (7.891, 8.096, 8.270), stdev = 0.191
  CI (99.9%): [4.608, 11.584] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.002 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.141 ±(99.9%) 0.001 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.121 ±(99.9%) 1.161 ms/op [Average]
  (min, avg, max) = (3.049, 3.121, 3.171), stdev = 0.064
  CI (99.9%): [1.959, 4.282] (assumes normal distribution)


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
# Warmup Iteration   1: 3.409 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
Iteration   3: 2.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.992 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (2.952, 2.992, 3.032), stdev = 0.040
  CI (99.9%): [2.254, 3.730] (assumes normal distribution)


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.002 ms/op
Iteration   1: 3.215 ±(99.9%) 0.002 ms/op
Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
Iteration   3: 3.197 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.172 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.105, 3.172, 3.215), stdev = 0.059
  CI (99.9%): [2.099, 4.246] (assumes normal distribution)


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
# Warmup Iteration   1: 5.025 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.025 ms/op
Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
Iteration   2: 3.767 ±(99.9%) 0.027 ms/op
Iteration   3: 3.882 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.870 ±(99.9%) 1.764 ms/op [Average]
  (min, avg, max) = (3.767, 3.870, 3.959), stdev = 0.097
  CI (99.9%): [2.106, 5.633] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.007 ms/op
Iteration   1: 3.153 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  9.247 ms/op
                 createUser·p0.9999: 15.527 ms/op
                 createUser·p1.00:   16.040 ms/op

Iteration   2: 3.013 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  11.398 ms/op
                 createUser·p0.9999: 22.053 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.384 ms/op
                 createUser·p0.9999: 20.236 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311351
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23918 
    [ 2.500,  5.000) = 286649 
    [ 5.000,  7.500) = 406 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     21.487 ms/op
     p(99.9990) =     22.238 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.497 ms/op
                 existUser·p0.9999: 11.903 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.447 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.349 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  8.076 ms/op
                 existUser·p0.9999: 16.241 ms/op
                 existUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320667
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1767 
    [ 1.250,  2.500) = 40915 
    [ 2.500,  3.750) = 257032 
    [ 3.750,  5.000) = 20086 
    [ 5.000,  6.250) = 414 
    [ 6.250,  7.500) = 172 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     17.998 ms/op
     p(99.9990) =     19.313 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.493 ms/op
                 getUser·p0.9999: 11.623 ms/op
                 getUser·p1.00:   11.960 ms/op

Iteration   2: 3.127 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.277 ms/op
                 getUser·p0.999:  5.880 ms/op
                 getUser·p0.9999: 12.814 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.528 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.717 ms/op
                 getUser·p0.9999: 23.679 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311498
  mean =      3.079 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21764 
    [ 2.500,  5.000) = 288943 
    [ 5.000,  7.500) = 557 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     22.802 ms/op
     p(99.9990) =     24.081 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
Iteration   1: 4.025 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  12.920 ms/op
                 listUser·p0.9999: 13.783 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.569 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.687 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 18.567 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.717 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  13.829 ms/op
                 listUser·p0.9999: 22.073 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244414
  mean =      3.928 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3902 
    [ 2.500,  5.000) = 213003 
    [ 5.000,  7.500) = 26540 
    [ 7.500, 10.000) = 574 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.510 ms/op
     p(99.9900) =     21.532 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.304 ± 5.088  ops/ms
ClientGrpc.existUser                       thrpt       3  10.556 ± 3.005  ops/ms
ClientGrpc.getUser                         thrpt       3  10.338 ± 2.746  ops/ms
ClientGrpc.listUser                        thrpt       3   8.096 ± 3.488  ops/ms
ClientGrpc.createUser                       avgt       3   3.121 ± 1.161   ms/op
ClientGrpc.existUser                        avgt       3   2.992 ± 0.738   ms/op
ClientGrpc.getUser                          avgt       3   3.172 ± 1.074   ms/op
ClientGrpc.listUser                         avgt       3   3.870 ± 1.764   ms/op
ClientGrpc.createUser                     sample  311351   3.083 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.617           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.961           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.487           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  320667   2.994 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.349           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.881           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.998           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  311498   3.079 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.528           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.750           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.802           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.216           ms/op
ClientGrpc.listUser                       sample  244414   3.928 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.569           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.510           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.532           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.462           ms/op
