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
# Warmup Iteration   1: 4.552 ops/ms
# Warmup Iteration   2: 9.177 ops/ms
# Warmup Iteration   3: 10.105 ops/ms
Iteration   1: 10.405 ops/ms
Iteration   2: 10.422 ops/ms
Iteration   3: 10.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.344 ±(99.9%) 2.201 ops/ms [Average]
  (min, avg, max) = (10.205, 10.344, 10.422), stdev = 0.121
  CI (99.9%): [8.143, 12.545] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.775 ops/ms
# Warmup Iteration   2: 10.731 ops/ms
# Warmup Iteration   3: 10.656 ops/ms
Iteration   1: 10.639 ops/ms
Iteration   2: 10.550 ops/ms
Iteration   3: 10.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.648 ±(99.9%) 1.887 ops/ms [Average]
  (min, avg, max) = (10.550, 10.648, 10.756), stdev = 0.103
  CI (99.9%): [8.761, 12.535] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.263 ops/ms
# Warmup Iteration   2: 9.867 ops/ms
# Warmup Iteration   3: 10.173 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 10.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.372 ±(99.9%) 3.839 ops/ms [Average]
  (min, avg, max) = (10.186, 10.372, 10.600), stdev = 0.210
  CI (99.9%): [6.533, 14.210] (assumes normal distribution)


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
# Warmup Iteration   1: 6.040 ops/ms
# Warmup Iteration   2: 7.720 ops/ms
# Warmup Iteration   3: 7.750 ops/ms
Iteration   1: 7.890 ops/ms
Iteration   2: 8.226 ops/ms
Iteration   3: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.094 ±(99.9%) 3.266 ops/ms [Average]
  (min, avg, max) = (7.890, 8.094, 8.226), stdev = 0.179
  CI (99.9%): [4.828, 11.360] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.004 ms/op
Iteration   1: 3.006 ±(99.9%) 0.003 ms/op
Iteration   2: 2.987 ±(99.9%) 0.003 ms/op
Iteration   3: 3.174 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.055 ±(99.9%) 1.877 ms/op [Average]
  (min, avg, max) = (2.987, 3.055, 3.174), stdev = 0.103
  CI (99.9%): [1.178, 4.933] (assumes normal distribution)


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.005 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.965 ±(99.9%) 0.002 ms/op
Iteration   3: 2.913 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.940 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (2.913, 2.940, 2.965), stdev = 0.026
  CI (99.9%): [2.458, 3.422] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.003 ms/op
Iteration   1: 3.074 ±(99.9%) 0.002 ms/op
Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
Iteration   3: 3.101 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.089 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (3.074, 3.089, 3.101), stdev = 0.014
  CI (99.9%): [2.841, 3.336] (assumes normal distribution)


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
# Warmup Iteration   1: 4.753 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.020 ms/op
Iteration   1: 3.978 ±(99.9%) 0.049 ms/op
Iteration   2: 3.869 ±(99.9%) 0.007 ms/op
Iteration   3: 3.995 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.947 ±(99.9%) 1.250 ms/op [Average]
  (min, avg, max) = (3.869, 3.947, 3.995), stdev = 0.069
  CI (99.9%): [2.697, 5.197] (assumes normal distribution)


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.885 ms/op
                 createUser·p0.9999: 14.402 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.501 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  6.290 ms/op
                 createUser·p0.9999: 16.003 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.747 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313229
  mean =      3.063 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20222 
    [ 2.500,  5.000) = 292254 
    [ 5.000,  7.500) = 465 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.873 ms/op
     p(99.9900) =     20.666 ms/op
     p(99.9990) =     21.491 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
Iteration   1: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  6.332 ms/op
                 existUser·p0.9999: 17.433 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.806 ms/op
                 existUser·p0.9999: 13.062 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.415 ms/op
                 existUser·p0.9999: 14.107 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325286
  mean =      2.950 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1680 
    [ 1.250,  2.500) = 41789 
    [ 2.500,  3.750) = 268539 
    [ 3.750,  5.000) = 12309 
    [ 5.000,  6.250) = 409 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      9.056 ms/op
     p(99.9900) =     13.716 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.070 ms/op
                 getUser·p0.9999: 15.299 ms/op
                 getUser·p1.00:   15.729 ms/op

Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.029 ms/op
                 getUser·p0.9999: 15.944 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.351 ms/op
                 getUser·p0.9999: 34.865 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310724
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23703 
    [ 2.500,  5.000) = 286073 
    [ 5.000,  7.500) = 705 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.105 ms/op
     p(99.9900) =     34.101 ms/op
     p(99.9990) =     35.186 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.010 ms/op
Iteration   1: 3.980 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.325 ms/op
                 listUser·p0.9999: 15.580 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 4.033 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 3.961 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.764 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 26.212 ms/op
                 listUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240384
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3530 
    [ 2.500,  5.000) = 209550 
    [ 5.000,  7.500) = 25995 
    [ 7.500, 10.000) = 896 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.208 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     26.783 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.344 ± 2.201  ops/ms
ClientGrpc.existUser                       thrpt       3  10.648 ± 1.887  ops/ms
ClientGrpc.getUser                         thrpt       3  10.372 ± 3.839  ops/ms
ClientGrpc.listUser                        thrpt       3   8.094 ± 3.266  ops/ms
ClientGrpc.createUser                       avgt       3   3.055 ± 1.877   ms/op
ClientGrpc.existUser                        avgt       3   2.940 ± 0.482   ms/op
ClientGrpc.getUser                          avgt       3   3.089 ± 0.248   ms/op
ClientGrpc.listUser                         avgt       3   3.947 ± 1.250   ms/op
ClientGrpc.createUser                     sample  313229   3.063 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.501           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.873           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.666           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.692           ms/op
ClientGrpc.existUser                      sample  325286   2.950 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.504           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.056           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.716           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.498           ms/op
ClientGrpc.getUser                        sample  310724   3.088 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.633           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.105           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.101           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.258           ms/op
ClientGrpc.listUser                       sample  240384   3.991 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.000           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.208           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.642           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.754           ms/op
