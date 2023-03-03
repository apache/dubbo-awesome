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
# Warmup Iteration   1: 4.087 ops/ms
# Warmup Iteration   2: 8.954 ops/ms
# Warmup Iteration   3: 9.938 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 10.017 ops/ms
Iteration   3: 9.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.984 ±(99.9%) 0.514 ops/ms [Average]
  (min, avg, max) = (9.965, 9.984, 10.017), stdev = 0.028
  CI (99.9%): [9.470, 10.499] (assumes normal distribution)


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
# Warmup Iteration   1: 7.238 ops/ms
# Warmup Iteration   2: 10.064 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.232 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.373 ±(99.9%) 2.245 ops/ms [Average]
  (min, avg, max) = (10.232, 10.373, 10.458), stdev = 0.123
  CI (99.9%): [8.128, 12.617] (assumes normal distribution)


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
# Warmup Iteration   1: 6.720 ops/ms
# Warmup Iteration   2: 9.849 ops/ms
# Warmup Iteration   3: 9.863 ops/ms
Iteration   1: 10.001 ops/ms
Iteration   2: 10.180 ops/ms
Iteration   3: 10.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.078 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (10.001, 10.078, 10.180), stdev = 0.093
  CI (99.9%): [8.390, 11.766] (assumes normal distribution)


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
# Warmup Iteration   1: 5.906 ops/ms
# Warmup Iteration   2: 7.522 ops/ms
# Warmup Iteration   3: 7.699 ops/ms
Iteration   1: 7.873 ops/ms
Iteration   2: 7.719 ops/ms
Iteration   3: 7.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.826 ±(99.9%) 1.709 ops/ms [Average]
  (min, avg, max) = (7.719, 7.826, 7.888), stdev = 0.094
  CI (99.9%): [6.117, 9.536] (assumes normal distribution)


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
# Warmup Iteration   1: 4.389 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.002 ms/op
Iteration   1: 3.305 ±(99.9%) 0.011 ms/op
Iteration   2: 3.198 ±(99.9%) 0.003 ms/op
Iteration   3: 3.226 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.243 ±(99.9%) 1.013 ms/op [Average]
  (min, avg, max) = (3.198, 3.243, 3.305), stdev = 0.056
  CI (99.9%): [2.230, 4.256] (assumes normal distribution)


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.002 ms/op
Iteration   1: 3.130 ±(99.9%) 0.003 ms/op
Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
Iteration   3: 3.155 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.130 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (3.105, 3.130, 3.155), stdev = 0.025
  CI (99.9%): [2.681, 3.579] (assumes normal distribution)


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.001 ms/op
Iteration   1: 3.215 ±(99.9%) 0.002 ms/op
Iteration   2: 3.193 ±(99.9%) 0.003 ms/op
Iteration   3: 3.160 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.189 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.160, 3.189, 3.215), stdev = 0.028
  CI (99.9%): [2.687, 3.692] (assumes normal distribution)


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
# Warmup Iteration   1: 5.340 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.008 ms/op
Iteration   1: 4.071 ±(99.9%) 0.008 ms/op
Iteration   2: 4.065 ±(99.9%) 0.004 ms/op
Iteration   3: 4.004 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.046 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (4.004, 4.046, 4.071), stdev = 0.037
  CI (99.9%): [3.369, 4.724] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.006 ms/op
Iteration   1: 3.221 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.807 ms/op
                 createUser·p0.9999: 13.732 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 3.256 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  9.904 ms/op
                 createUser·p0.9999: 13.965 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 3.239 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.201 ms/op
                 createUser·p0.9999: 18.099 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296638
  mean =      3.239 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 493 
    [ 1.250,  2.500) = 17102 
    [ 2.500,  3.750) = 228231 
    [ 3.750,  5.000) = 49880 
    [ 5.000,  6.250) = 290 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 110 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     16.521 ms/op
     p(99.9990) =     18.451 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.129 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.142 ms/op
                 existUser·p0.9999: 21.973 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.726 ms/op
                 existUser·p0.9999: 23.285 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 310909
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30178 
    [ 2.500,  5.000) = 279756 
    [ 5.000,  7.500) = 644 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.718 ms/op
     p(99.9900) =     22.497 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.007 ms/op
Iteration   1: 3.206 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.363 ms/op
                 getUser·p0.9999: 13.108 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   2: 3.237 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.391 ms/op
                 getUser·p0.9999: 14.535 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   3: 3.282 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.041 ms/op
                 getUser·p0.9999: 19.964 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 296000
  mean =      3.241 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16229 
    [ 2.500,  5.000) = 278398 
    [ 5.000,  7.500) = 1095 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.365 ms/op
     p(99.9900) =     17.315 ms/op
     p(99.9990) =     20.352 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 5.759 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.010 ms/op
Iteration   1: 3.999 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  12.740 ms/op
                 listUser·p0.9999: 14.762 ms/op
                 listUser·p1.00:   15.221 ms/op

Iteration   2: 4.057 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.280 ms/op
                 listUser·p0.9999: 21.773 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   3: 4.133 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.088 ms/op
                 listUser·p0.999:  17.326 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236323
  mean =      4.062 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2244 
    [ 2.500,  5.000) = 204294 
    [ 5.000,  7.500) = 28365 
    [ 7.500, 10.000) = 1022 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.473 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     23.578 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.984 ± 0.514  ops/ms
ClientGrpc.existUser                       thrpt       3  10.373 ± 2.245  ops/ms
ClientGrpc.getUser                         thrpt       3  10.078 ± 1.688  ops/ms
ClientGrpc.listUser                        thrpt       3   7.826 ± 1.709  ops/ms
ClientGrpc.createUser                       avgt       3   3.243 ± 1.013   ms/op
ClientGrpc.existUser                        avgt       3   3.130 ± 0.449   ms/op
ClientGrpc.getUser                          avgt       3   3.189 ± 0.503   ms/op
ClientGrpc.listUser                         avgt       3   4.046 ± 0.678   ms/op
ClientGrpc.createUser                     sample  296638   3.239 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.651           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.228           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.076           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.617           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.521           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.579           ms/op
ClientGrpc.existUser                      sample  310909   3.088 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.626           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.072           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.718           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.497           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.691           ms/op
ClientGrpc.getUser                        sample  296000   3.241 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.664           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.224           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.116           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.365           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.315           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.513           ms/op
ClientGrpc.listUser                       sample  236323   4.062 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.935           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.473           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.430           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.347           ms/op
