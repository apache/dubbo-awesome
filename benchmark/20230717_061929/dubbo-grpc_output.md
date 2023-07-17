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
# Warmup Iteration   1: 4.502 ops/ms
# Warmup Iteration   2: 9.520 ops/ms
# Warmup Iteration   3: 10.115 ops/ms
Iteration   1: 10.529 ops/ms
Iteration   2: 10.623 ops/ms
Iteration   3: 10.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.547 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (10.490, 10.547, 10.623), stdev = 0.068
  CI (99.9%): [9.298, 11.797] (assumes normal distribution)


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
# Warmup Iteration   1: 7.767 ops/ms
# Warmup Iteration   2: 10.655 ops/ms
# Warmup Iteration   3: 10.902 ops/ms
Iteration   1: 10.797 ops/ms
Iteration   2: 10.951 ops/ms
Iteration   3: 11.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.949 ±(99.9%) 2.769 ops/ms [Average]
  (min, avg, max) = (10.797, 10.949, 11.100), stdev = 0.152
  CI (99.9%): [8.180, 13.718] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.680 ops/ms
# Warmup Iteration   2: 10.093 ops/ms
# Warmup Iteration   3: 10.191 ops/ms
Iteration   1: 10.465 ops/ms
Iteration   2: 10.564 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.535 ±(99.9%) 1.107 ops/ms [Average]
  (min, avg, max) = (10.465, 10.535, 10.575), stdev = 0.061
  CI (99.9%): [9.427, 11.642] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.453 ops/ms
# Warmup Iteration   2: 7.610 ops/ms
# Warmup Iteration   3: 7.810 ops/ms
Iteration   1: 7.568 ops/ms
Iteration   2: 7.788 ops/ms
Iteration   3: 8.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.850 ±(99.9%) 5.779 ops/ms [Average]
  (min, avg, max) = (7.568, 7.850, 8.193), stdev = 0.317
  CI (99.9%): [2.071, 13.629] (assumes normal distribution)


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
# Warmup Iteration   1: 4.174 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.009 ms/op
Iteration   1: 3.071 ±(99.9%) 0.003 ms/op
Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
Iteration   3: 3.072 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.064 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (3.050, 3.064, 3.072), stdev = 0.012
  CI (99.9%): [2.844, 3.284] (assumes normal distribution)


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.003 ms/op
Iteration   1: 2.985 ±(99.9%) 0.004 ms/op
Iteration   2: 2.975 ±(99.9%) 0.002 ms/op
Iteration   3: 2.950 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.970 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.950, 2.970, 2.985), stdev = 0.018
  CI (99.9%): [2.638, 3.302] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.321 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.004 ms/op
Iteration   1: 3.053 ±(99.9%) 0.004 ms/op
Iteration   2: 3.029 ±(99.9%) 0.004 ms/op
Iteration   3: 3.038 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.040 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (3.029, 3.040, 3.053), stdev = 0.012
  CI (99.9%): [2.825, 3.255] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.366 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.014 ms/op
Iteration   1: 3.936 ±(99.9%) 0.030 ms/op
Iteration   2: 3.916 ±(99.9%) 0.011 ms/op
Iteration   3: 3.927 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.926 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (3.916, 3.926, 3.936), stdev = 0.010
  CI (99.9%): [3.740, 4.112] (assumes normal distribution)


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  6.992 ms/op
                 createUser·p0.9999: 16.409 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.250 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  6.726 ms/op
                 createUser·p0.9999: 14.212 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.764 ms/op
                 createUser·p0.999:  12.277 ms/op
                 createUser·p0.9999: 20.547 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315117
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25010 
    [ 2.500,  5.000) = 288159 
    [ 5.000,  7.500) = 1547 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.250 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      8.532 ms/op
     p(99.9900) =     19.381 ms/op
     p(99.9990) =     20.868 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.370 ms/op
                 existUser·p0.9999: 12.567 ms/op
                 existUser·p1.00:   12.878 ms/op

Iteration   2: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.735 ms/op
                 existUser·p0.9999: 13.370 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.906 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  6.332 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329388
  mean =      2.913 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1219 
    [ 1.250,  2.500) = 32554 
    [ 2.500,  3.750) = 288139 
    [ 3.750,  5.000) = 6644 
    [ 5.000,  6.250) = 467 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      6.439 ms/op
     p(99.9900) =     16.679 ms/op
     p(99.9990) =     17.194 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.204 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.005 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.245 ms/op
                 getUser·p0.9999: 12.316 ms/op
                 getUser·p1.00:   12.583 ms/op

Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  7.498 ms/op
                 getUser·p0.9999: 16.767 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  7.543 ms/op
                 getUser·p0.9999: 17.498 ms/op
                 getUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316185
  mean =      3.038 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 884 
    [ 1.250,  2.500) = 20318 
    [ 2.500,  3.750) = 277836 
    [ 3.750,  5.000) = 14428 
    [ 5.000,  6.250) = 1948 
    [ 6.250,  7.500) = 465 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      7.396 ms/op
     p(99.9900) =     16.679 ms/op
     p(99.9990) =     18.875 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.965 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.011 ms/op
Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 19.363 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 4.085 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  16.208 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.036 ms/op
                 listUser·p0.999:  16.613 ms/op
                 listUser·p0.9999: 19.384 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238970
  mean =      4.019 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3021 
    [ 2.500,  5.000) = 209449 
    [ 5.000,  7.500) = 24962 
    [ 7.500, 10.000) = 1125 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     20.147 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.547 ± 1.249  ops/ms
ClientGrpc.existUser                       thrpt       3  10.949 ± 2.769  ops/ms
ClientGrpc.getUser                         thrpt       3  10.535 ± 1.107  ops/ms
ClientGrpc.listUser                        thrpt       3   7.850 ± 5.779  ops/ms
ClientGrpc.createUser                       avgt       3   3.064 ± 0.220   ms/op
ClientGrpc.existUser                        avgt       3   2.970 ± 0.332   ms/op
ClientGrpc.getUser                          avgt       3   3.040 ± 0.215   ms/op
ClientGrpc.listUser                         avgt       3   3.926 ± 0.186   ms/op
ClientGrpc.createUser                     sample  315117   3.044 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.250           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.532           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.381           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.972           ms/op
ClientGrpc.existUser                      sample  329388   2.913 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.439           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.679           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.334           ms/op
ClientGrpc.getUser                        sample  316185   3.038 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.720           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.396           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.679           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.940           ms/op
ClientGrpc.listUser                       sample  238970   4.019 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.854           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.268           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.758           ms/op
