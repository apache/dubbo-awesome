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
# Warmup Iteration   1: 4.147 ops/ms
# Warmup Iteration   2: 8.546 ops/ms
# Warmup Iteration   3: 9.802 ops/ms
Iteration   1: 10.132 ops/ms
Iteration   2: 9.908 ops/ms
Iteration   3: 10.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.016 ±(99.9%) 2.051 ops/ms [Average]
  (min, avg, max) = (9.908, 10.016, 10.132), stdev = 0.112
  CI (99.9%): [7.965, 12.067] (assumes normal distribution)


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
# Warmup Iteration   1: 7.413 ops/ms
# Warmup Iteration   2: 10.176 ops/ms
# Warmup Iteration   3: 10.470 ops/ms
Iteration   1: 10.403 ops/ms
Iteration   2: 10.416 ops/ms
Iteration   3: 10.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.442 ±(99.9%) 1.052 ops/ms [Average]
  (min, avg, max) = (10.403, 10.442, 10.508), stdev = 0.058
  CI (99.9%): [9.391, 11.494] (assumes normal distribution)


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
# Warmup Iteration   1: 6.718 ops/ms
# Warmup Iteration   2: 9.808 ops/ms
# Warmup Iteration   3: 9.994 ops/ms
Iteration   1: 9.776 ops/ms
Iteration   2: 9.880 ops/ms
Iteration   3: 9.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.813 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (9.776, 9.813, 9.880), stdev = 0.058
  CI (99.9%): [8.764, 10.863] (assumes normal distribution)


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
# Warmup Iteration   1: 5.271 ops/ms
# Warmup Iteration   2: 7.500 ops/ms
# Warmup Iteration   3: 7.705 ops/ms
Iteration   1: 7.822 ops/ms
Iteration   2: 7.952 ops/ms
Iteration   3: 7.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.884 ±(99.9%) 1.186 ops/ms [Average]
  (min, avg, max) = (7.822, 7.884, 7.952), stdev = 0.065
  CI (99.9%): [6.698, 9.070] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.003 ms/op
Iteration   1: 3.232 ±(99.9%) 0.007 ms/op
Iteration   2: 3.202 ±(99.9%) 0.002 ms/op
Iteration   3: 3.217 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.217 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.202, 3.217, 3.232), stdev = 0.015
  CI (99.9%): [2.941, 3.494] (assumes normal distribution)


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.002 ms/op
Iteration   1: 3.045 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
Iteration   3: 3.044 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.053 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (3.044, 3.053, 3.070), stdev = 0.015
  CI (99.9%): [2.785, 3.321] (assumes normal distribution)


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.002 ms/op
Iteration   1: 3.196 ±(99.9%) 0.002 ms/op
Iteration   2: 3.235 ±(99.9%) 0.001 ms/op
Iteration   3: 3.266 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.232 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.196, 3.232, 3.266), stdev = 0.035
  CI (99.9%): [2.591, 3.873] (assumes normal distribution)


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
# Warmup Iteration   1: 5.568 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.030 ms/op
Iteration   1: 4.003 ±(99.9%) 0.018 ms/op
Iteration   2: 4.040 ±(99.9%) 0.006 ms/op
Iteration   3: 3.924 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.989 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (3.924, 3.989, 4.040), stdev = 0.059
  CI (99.9%): [2.908, 5.070] (assumes normal distribution)


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.007 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.918 ms/op
                 createUser·p0.9999: 19.028 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.160 ms/op
                 createUser·p0.9999: 17.751 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   3: 3.233 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  10.326 ms/op
                 createUser·p0.9999: 16.948 ms/op
                 createUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301876
  mean =      3.180 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20241 
    [ 2.500,  5.000) = 280443 
    [ 5.000,  7.500) = 865 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.877 ms/op
     p(99.9900) =     18.278 ms/op
     p(99.9990) =     19.397 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.006 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.795 ms/op
                 existUser·p0.9999: 12.518 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.379 ms/op
                 existUser·p0.9999: 13.593 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.387 ms/op
                 existUser·p0.9999: 17.258 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312825
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1262 
    [ 1.250,  2.500) = 34302 
    [ 2.500,  3.750) = 244935 
    [ 3.750,  5.000) = 31489 
    [ 5.000,  6.250) = 411 
    [ 6.250,  7.500) = 199 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.906 ms/op
     p(99.9900) =     15.375 ms/op
     p(99.9990) =     17.494 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.007 ms/op
Iteration   1: 3.157 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.644 ms/op
                 getUser·p0.9999: 13.435 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  9.083 ms/op
                 getUser·p0.9999: 14.565 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  9.038 ms/op
                 getUser·p0.9999: 18.779 ms/op
                 getUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300162
  mean =      3.198 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 841 
    [ 1.250,  2.500) = 15238 
    [ 2.500,  3.750) = 242315 
    [ 3.750,  5.000) = 40510 
    [ 5.000,  6.250) = 617 
    [ 6.250,  7.500) = 251 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.419 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 5.493 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.011 ms/op
Iteration   1: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.382 ms/op
                 listUser·p0.9999: 14.516 ms/op
                 listUser·p1.00:   14.942 ms/op

Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 15.404 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.803 ms/op
                 listUser·p0.9999: 18.388 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237951
  mean =      4.031 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 2802 
    [ 2.500,  3.750) = 89794 
    [ 3.750,  5.000) = 119058 
    [ 5.000,  6.250) = 19763 
    [ 6.250,  7.500) = 5261 
    [ 7.500,  8.750) = 717 
    [ 8.750, 10.000) = 123 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 141 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     16.744 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.016 ± 2.051  ops/ms
ClientGrpc.existUser                       thrpt       3  10.442 ± 1.052  ops/ms
ClientGrpc.getUser                         thrpt       3   9.813 ± 1.050  ops/ms
ClientGrpc.listUser                        thrpt       3   7.884 ± 1.186  ops/ms
ClientGrpc.createUser                       avgt       3   3.217 ± 0.276   ms/op
ClientGrpc.existUser                        avgt       3   3.053 ± 0.268   ms/op
ClientGrpc.getUser                          avgt       3   3.232 ± 0.641   ms/op
ClientGrpc.listUser                         avgt       3   3.989 ± 1.081   ms/op
ClientGrpc.createUser                     sample  301876   3.180 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.573           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.158           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.877           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.278           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.021           ms/op
ClientGrpc.existUser                      sample  312825   3.069 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.684           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.052           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.906           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.375           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.826           ms/op
ClientGrpc.getUser                        sample  300162   3.198 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.596           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.419           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.022           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.071           ms/op
ClientGrpc.listUser                       sample  237951   4.031 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.022           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.681           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.744           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.071           ms/op
