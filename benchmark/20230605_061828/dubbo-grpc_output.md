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
# Warmup Iteration   1: 4.486 ops/ms
# Warmup Iteration   2: 9.107 ops/ms
# Warmup Iteration   3: 10.077 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 10.526 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.530 ±(99.9%) 0.071 ops/ms [Average]
  (min, avg, max) = (10.526, 10.530, 10.533), stdev = 0.004
  CI (99.9%): [10.459, 10.602] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.432 ops/ms
# Warmup Iteration   2: 10.601 ops/ms
# Warmup Iteration   3: 11.210 ops/ms
Iteration   1: 11.213 ops/ms
Iteration   2: 10.904 ops/ms
Iteration   3: 11.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.050 ±(99.9%) 2.833 ops/ms [Average]
  (min, avg, max) = (10.904, 11.050, 11.213), stdev = 0.155
  CI (99.9%): [8.217, 13.883] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.187 ops/ms
# Warmup Iteration   2: 10.289 ops/ms
# Warmup Iteration   3: 10.575 ops/ms
Iteration   1: 10.551 ops/ms
Iteration   2: 10.640 ops/ms
Iteration   3: 10.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.653 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (10.551, 10.653, 10.769), stdev = 0.110
  CI (99.9%): [8.654, 12.652] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.225 ops/ms
# Warmup Iteration   2: 7.816 ops/ms
# Warmup Iteration   3: 8.127 ops/ms
Iteration   1: 8.208 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.206 ±(99.9%) 0.212 ops/ms [Average]
  (min, avg, max) = (8.194, 8.206, 8.217), stdev = 0.012
  CI (99.9%): [7.994, 8.418] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.205 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.003 ms/op
Iteration   1: 3.080 ±(99.9%) 0.003 ms/op
Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
Iteration   3: 3.022 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.050 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.022, 3.050, 3.080), stdev = 0.029
  CI (99.9%): [2.519, 3.582] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.003 ms/op
Iteration   1: 2.882 ±(99.9%) 0.003 ms/op
Iteration   2: 2.865 ±(99.9%) 0.002 ms/op
Iteration   3: 2.915 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.887 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (2.865, 2.887, 2.915), stdev = 0.025
  CI (99.9%): [2.428, 3.347] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.004 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.016, 3.043, 3.077), stdev = 0.031
  CI (99.9%): [2.472, 3.614] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.220 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.028 ms/op
Iteration   1: 3.862 ±(99.9%) 0.032 ms/op
Iteration   2: 3.899 ±(99.9%) 0.009 ms/op
Iteration   3: 3.830 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.864 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.830, 3.864, 3.899), stdev = 0.034
  CI (99.9%): [3.238, 4.489] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.260 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  7.753 ms/op
                 createUser·p0.9999: 15.876 ms/op
                 createUser·p1.00:   16.302 ms/op

Iteration   2: 3.076 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.257 ms/op
                 createUser·p0.9999: 14.935 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  12.534 ms/op
                 createUser·p0.9999: 17.171 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312354
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 591 
    [ 1.250,  2.500) = 25530 
    [ 2.500,  3.750) = 263143 
    [ 3.750,  5.000) = 21398 
    [ 5.000,  6.250) = 942 
    [ 6.250,  7.500) = 336 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     10.660 ms/op
     p(99.9900) =     16.176 ms/op
     p(99.9990) =     17.527 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.921 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.406 ms/op
                 existUser·p0.9999: 13.382 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  9.894 ms/op
                 existUser·p0.9999: 16.073 ms/op
                 existUser·p1.00:   18.776 ms/op

Iteration   3: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.377 ms/op
                 existUser·p0.999:  7.082 ms/op
                 existUser·p0.9999: 16.437 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329717
  mean =      2.912 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1121 
    [ 1.250,  2.500) = 36286 
    [ 2.500,  3.750) = 284210 
    [ 3.750,  5.000) = 6968 
    [ 5.000,  6.250) = 639 
    [ 6.250,  7.500) = 186 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.200 ms/op
     p(99.9900) =     15.795 ms/op
     p(99.9990) =     17.323 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.203 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
Iteration   1: 3.026 ±(99.9%) 0.004 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.449 ms/op
                 getUser·p0.9999: 12.229 ms/op
                 getUser·p1.00:   12.452 ms/op

Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  11.037 ms/op
                 getUser·p0.9999: 22.692 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  7.792 ms/op
                 getUser·p0.9999: 14.873 ms/op
                 getUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316764
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23427 
    [ 2.500,  5.000) = 291534 
    [ 5.000,  7.500) = 1457 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      7.717 ms/op
     p(99.9900) =     21.998 ms/op
     p(99.9990) =     23.058 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.078 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.010 ms/op
Iteration   1: 3.961 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 16.493 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   2: 3.885 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.725 ms/op
                 listUser·p0.9999: 16.295 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  18.957 ms/op
                 listUser·p0.9999: 21.327 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244608
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3042 
    [ 2.500,  5.000) = 220578 
    [ 5.000,  7.500) = 19950 
    [ 7.500, 10.000) = 603 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.326 ms/op
     p(99.9900) =     20.697 ms/op
     p(99.9990) =     21.808 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.530 ± 0.071  ops/ms
ClientGrpc.existUser                       thrpt       3  11.050 ± 2.833  ops/ms
ClientGrpc.getUser                         thrpt       3  10.653 ± 1.999  ops/ms
ClientGrpc.listUser                        thrpt       3   8.206 ± 0.212  ops/ms
ClientGrpc.createUser                       avgt       3   3.050 ± 0.532   ms/op
ClientGrpc.existUser                        avgt       3   2.887 ± 0.459   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.571   ms/op
ClientGrpc.listUser                         avgt       3   3.864 ± 0.625   ms/op
ClientGrpc.createUser                     sample  312354   3.074 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.483           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.660           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.176           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.662           ms/op
ClientGrpc.existUser                      sample  329717   2.912 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.589           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.200           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.795           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.776           ms/op
ClientGrpc.getUser                        sample  316764   3.030 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.717           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.998           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.233           ms/op
ClientGrpc.listUser                       sample  244608   3.924 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.922           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.326           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.697           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.003           ms/op
