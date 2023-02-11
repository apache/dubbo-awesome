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
# Warmup Iteration   1: 4.212 ops/ms
# Warmup Iteration   2: 8.837 ops/ms
# Warmup Iteration   3: 9.701 ops/ms
Iteration   1: 9.555 ops/ms
Iteration   2: 9.894 ops/ms
Iteration   3: 9.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.658 ±(99.9%) 3.736 ops/ms [Average]
  (min, avg, max) = (9.526, 9.658, 9.894), stdev = 0.205
  CI (99.9%): [5.923, 13.394] (assumes normal distribution)


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
# Warmup Iteration   1: 7.571 ops/ms
# Warmup Iteration   2: 10.084 ops/ms
# Warmup Iteration   3: 10.611 ops/ms
Iteration   1: 10.605 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 9.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.342 ±(99.9%) 5.683 ops/ms [Average]
  (min, avg, max) = (9.998, 10.342, 10.605), stdev = 0.311
  CI (99.9%): [4.659, 16.025] (assumes normal distribution)


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
# Warmup Iteration   1: 6.429 ops/ms
# Warmup Iteration   2: 9.703 ops/ms
# Warmup Iteration   3: 9.870 ops/ms
Iteration   1: 9.788 ops/ms
Iteration   2: 10.081 ops/ms
Iteration   3: 9.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.920 ±(99.9%) 2.711 ops/ms [Average]
  (min, avg, max) = (9.788, 9.920, 10.081), stdev = 0.149
  CI (99.9%): [7.209, 12.632] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.442 ops/ms
# Warmup Iteration   2: 7.574 ops/ms
# Warmup Iteration   3: 7.737 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 7.862 ops/ms
Iteration   3: 7.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.903 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (7.862, 7.903, 7.963), stdev = 0.053
  CI (99.9%): [6.929, 8.877] (assumes normal distribution)


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.002 ms/op
Iteration   1: 3.284 ±(99.9%) 0.001 ms/op
Iteration   2: 3.224 ±(99.9%) 0.001 ms/op
Iteration   3: 3.180 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.229 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (3.180, 3.229, 3.284), stdev = 0.052
  CI (99.9%): [2.281, 4.177] (assumes normal distribution)


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.002 ms/op
Iteration   2: 3.109 ±(99.9%) 0.003 ms/op
Iteration   3: 3.086 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.105 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.086, 3.105, 3.119), stdev = 0.017
  CI (99.9%): [2.796, 3.413] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.417 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.005 ms/op
Iteration   1: 3.216 ±(99.9%) 0.003 ms/op
Iteration   2: 3.259 ±(99.9%) 0.003 ms/op
Iteration   3: 3.236 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.237 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.216, 3.237, 3.259), stdev = 0.022
  CI (99.9%): [2.843, 3.630] (assumes normal distribution)


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.009 ms/op
Iteration   1: 4.140 ±(99.9%) 0.012 ms/op
Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
Iteration   3: 4.050 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.072 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (4.026, 4.072, 4.140), stdev = 0.060
  CI (99.9%): [2.973, 5.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.007 ms/op
Iteration   1: 3.274 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  7.153 ms/op
                 createUser·p0.9999: 12.849 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   2: 3.202 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.987 ms/op
                 createUser·p0.9999: 14.467 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   3: 3.121 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.210 ms/op
                 createUser·p0.9999: 16.507 ms/op
                 createUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300121
  mean =      3.198 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 378 
    [ 1.250,  2.500) = 18396 
    [ 2.500,  3.750) = 240411 
    [ 3.750,  5.000) = 39663 
    [ 5.000,  6.250) = 769 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     15.006 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
Iteration   1: 3.201 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  6.910 ms/op
                 existUser·p0.9999: 15.893 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.316 ms/op
                 existUser·p0.9999: 16.538 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   3: 3.118 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.079 ms/op
                 existUser·p0.9999: 16.265 ms/op
                 existUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 303928
  mean =      3.157 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 512 
    [ 1.250,  2.500) = 28101 
    [ 2.500,  3.750) = 230783 
    [ 3.750,  5.000) = 43327 
    [ 5.000,  6.250) = 654 
    [ 6.250,  7.500) = 190 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.889 ms/op
     p(99.9900) =     16.204 ms/op
     p(99.9990) =     17.628 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.007 ms/op
Iteration   1: 3.172 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.616 ms/op
                 getUser·p0.999:  8.929 ms/op
                 getUser·p0.9999: 16.414 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  10.558 ms/op
                 getUser·p0.9999: 29.488 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 3.248 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.492 ms/op
                 getUser·p0.9999: 20.546 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300231
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17404 
    [ 2.500,  5.000) = 281348 
    [ 5.000,  7.500) = 1006 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     28.867 ms/op
     p(99.9990) =     29.786 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 4.805 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.669 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.010 ms/op
Iteration   1: 4.077 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  13.814 ms/op
                 listUser·p0.9999: 16.979 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   2: 4.032 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  17.455 ms/op
                 listUser·p0.9999: 19.698 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 4.092 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.739 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 23.910 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236045
  mean =      4.067 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2285 
    [ 2.500,  5.000) = 208621 
    [ 5.000,  7.500) = 23738 
    [ 7.500, 10.000) = 972 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     23.337 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.658 ± 3.736  ops/ms
ClientGrpc.existUser                       thrpt       3  10.342 ± 5.683  ops/ms
ClientGrpc.getUser                         thrpt       3   9.920 ± 2.711  ops/ms
ClientGrpc.listUser                        thrpt       3   7.903 ± 0.974  ops/ms
ClientGrpc.createUser                       avgt       3   3.229 ± 0.948   ms/op
ClientGrpc.existUser                        avgt       3   3.105 ± 0.309   ms/op
ClientGrpc.getUser                          avgt       3   3.237 ± 0.393   ms/op
ClientGrpc.listUser                         avgt       3   4.072 ± 1.099   ms/op
ClientGrpc.createUser                     sample  300121   3.198 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.786           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.121           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.062           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.006           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.941           ms/op
ClientGrpc.existUser                      sample  303928   3.157 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.138           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.863           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.035           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.889           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.204           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  300231   3.196 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.150           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.044           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.867           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.917           ms/op
ClientGrpc.listUser                       sample  236045   4.067 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.739           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.204           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.337           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
