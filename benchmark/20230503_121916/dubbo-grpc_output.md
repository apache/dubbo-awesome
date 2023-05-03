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
# Warmup Iteration   1: 4.337 ops/ms
# Warmup Iteration   2: 9.188 ops/ms
# Warmup Iteration   3: 10.528 ops/ms
Iteration   1: 10.660 ops/ms
Iteration   2: 10.663 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.537 ±(99.9%) 3.937 ops/ms [Average]
  (min, avg, max) = (10.288, 10.537, 10.663), stdev = 0.216
  CI (99.9%): [6.600, 14.474] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.570 ops/ms
# Warmup Iteration   2: 10.849 ops/ms
# Warmup Iteration   3: 11.141 ops/ms
Iteration   1: 11.170 ops/ms
Iteration   2: 11.269 ops/ms
Iteration   3: 10.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.974 ±(99.9%) 7.814 ops/ms [Average]
  (min, avg, max) = (10.483, 10.974, 11.269), stdev = 0.428
  CI (99.9%): [3.160, 18.788] (assumes normal distribution)


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
# Warmup Iteration   1: 7.964 ops/ms
# Warmup Iteration   2: 10.252 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.597 ops/ms
Iteration   2: 10.387 ops/ms
Iteration   3: 10.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.603 ±(99.9%) 4.000 ops/ms [Average]
  (min, avg, max) = (10.387, 10.603, 10.826), stdev = 0.219
  CI (99.9%): [6.603, 14.603] (assumes normal distribution)


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
# Warmup Iteration   1: 5.555 ops/ms
# Warmup Iteration   2: 7.856 ops/ms
# Warmup Iteration   3: 8.110 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 8.204 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.179 ±(99.9%) 0.402 ops/ms [Average]
  (min, avg, max) = (8.163, 8.179, 8.204), stdev = 0.022
  CI (99.9%): [7.777, 8.581] (assumes normal distribution)


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.003 ms/op
Iteration   1: 2.985 ±(99.9%) 0.003 ms/op
Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.985, 2.997, 3.003), stdev = 0.010
  CI (99.9%): [2.813, 3.181] (assumes normal distribution)


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
# Warmup Iteration   1: 3.669 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.004 ms/op
Iteration   1: 2.939 ±(99.9%) 0.003 ms/op
Iteration   2: 2.851 ±(99.9%) 0.004 ms/op
Iteration   3: 2.784 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.858 ±(99.9%) 1.415 ms/op [Average]
  (min, avg, max) = (2.784, 2.858, 2.939), stdev = 0.078
  CI (99.9%): [1.443, 4.273] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.002 ms/op
Iteration   1: 2.956 ±(99.9%) 0.003 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 2.993 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.983 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (2.956, 2.983, 2.999), stdev = 0.023
  CI (99.9%): [2.561, 3.405] (assumes normal distribution)


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
# Warmup Iteration   1: 4.870 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.031 ms/op
Iteration   1: 3.899 ±(99.9%) 0.008 ms/op
Iteration   2: 3.780 ±(99.9%) 0.007 ms/op
Iteration   3: 3.882 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.854 ±(99.9%) 1.176 ms/op [Average]
  (min, avg, max) = (3.780, 3.854, 3.899), stdev = 0.064
  CI (99.9%): [2.678, 5.030] (assumes normal distribution)


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
# Warmup Iteration   1: 4.174 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  6.758 ms/op
                 createUser·p0.9999: 11.584 ms/op
                 createUser·p1.00:   12.141 ms/op

Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.782 ms/op
                 createUser·p0.9999: 12.517 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.233 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  8.286 ms/op
                 createUser·p0.9999: 23.672 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317637
  mean =      3.023 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22173 
    [ 2.500,  5.000) = 293827 
    [ 5.000,  7.500) = 1295 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.233 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.684 ms/op
     p(99.9900) =     22.830 ms/op
     p(99.9990) =     23.975 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 3.514 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
Iteration   1: 2.900 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.538 ms/op
                 existUser·p0.9999: 12.107 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   2: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.104 ms/op
                 existUser·p0.9999: 14.033 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.913 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.348 ms/op
                 existUser·p0.9999: 21.211 ms/op
                 existUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328695
  mean =      2.918 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44337 
    [ 2.500,  5.000) = 282996 
    [ 5.000,  7.500) = 1108 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.220 ms/op
     p(99.9900) =     16.058 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.554 ms/op
                 getUser·p0.999:  9.024 ms/op
                 getUser·p0.9999: 15.799 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.248 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.687 ms/op
                 getUser·p0.9999: 18.585 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.528 ms/op
                 getUser·p0.999:  6.537 ms/op
                 getUser·p0.9999: 18.578 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320714
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2137 
    [ 1.250,  2.500) = 24701 
    [ 2.500,  3.750) = 278456 
    [ 3.750,  5.000) = 13960 
    [ 5.000,  6.250) = 887 
    [ 6.250,  7.500) = 228 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.248 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.818 ms/op
     p(99.9900) =     18.348 ms/op
     p(99.9990) =     19.031 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 5.250 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.010 ms/op
Iteration   1: 3.928 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  11.764 ms/op
                 listUser·p0.9999: 13.570 ms/op
                 listUser·p1.00:   14.664 ms/op

Iteration   2: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.891 ms/op
                 listUser·p0.9999: 17.327 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 3.938 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.737 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  16.602 ms/op
                 listUser·p0.9999: 20.115 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243896
  mean =      3.936 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5139 
    [ 2.500,  5.000) = 217966 
    [ 5.000,  7.500) = 19693 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.387 ms/op
     p(99.9900) =     19.189 ms/op
     p(99.9990) =     20.451 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.537 ± 3.937  ops/ms
ClientGrpc.existUser                       thrpt       3  10.974 ± 7.814  ops/ms
ClientGrpc.getUser                         thrpt       3  10.603 ± 4.000  ops/ms
ClientGrpc.listUser                        thrpt       3   8.179 ± 0.402  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.184   ms/op
ClientGrpc.existUser                        avgt       3   2.858 ± 1.415   ms/op
ClientGrpc.getUser                          avgt       3   2.983 ± 0.422   ms/op
ClientGrpc.listUser                         avgt       3   3.854 ± 1.176   ms/op
ClientGrpc.createUser                     sample  317637   3.023 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.233           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.684           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.830           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  328695   2.918 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.517           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.220           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.058           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.970           ms/op
ClientGrpc.getUser                        sample  320714   2.992 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.248           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.818           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.348           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.235           ms/op
ClientGrpc.listUser                       sample  243896   3.936 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.737           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.387           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.189           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.578           ms/op
