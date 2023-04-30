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
# Warmup Iteration   1: 4.960 ops/ms
# Warmup Iteration   2: 9.328 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.975 ops/ms
Iteration   2: 10.966 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.903 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (10.767, 10.903, 10.975), stdev = 0.117
  CI (99.9%): [8.763, 13.043] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.425 ops/ms
# Warmup Iteration   2: 11.218 ops/ms
# Warmup Iteration   3: 11.575 ops/ms
Iteration   1: 11.522 ops/ms
Iteration   2: 11.419 ops/ms
Iteration   3: 11.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.523 ±(99.9%) 1.901 ops/ms [Average]
  (min, avg, max) = (11.419, 11.523, 11.627), stdev = 0.104
  CI (99.9%): [9.622, 13.424] (assumes normal distribution)


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
# Warmup Iteration   2: 10.527 ops/ms
# Warmup Iteration   3: 10.966 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 11.016 ops/ms
Iteration   3: 10.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.893 ±(99.9%) 2.454 ops/ms [Average]
  (min, avg, max) = (10.749, 10.893, 11.016), stdev = 0.135
  CI (99.9%): [8.439, 13.347] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.277 ops/ms
# Warmup Iteration   2: 8.259 ops/ms
# Warmup Iteration   3: 8.602 ops/ms
Iteration   1: 8.454 ops/ms
Iteration   2: 8.382 ops/ms
Iteration   3: 8.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.430 ±(99.9%) 0.763 ops/ms [Average]
  (min, avg, max) = (8.382, 8.430, 8.455), stdev = 0.042
  CI (99.9%): [7.667, 9.194] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.548 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.002 ms/op
Iteration   1: 2.960 ±(99.9%) 0.002 ms/op
Iteration   2: 2.905 ±(99.9%) 0.003 ms/op
Iteration   3: 2.872 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.912 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (2.872, 2.912, 2.960), stdev = 0.045
  CI (99.9%): [2.095, 3.730] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.896 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.802 ±(99.9%) 0.003 ms/op
Iteration   1: 2.824 ±(99.9%) 0.004 ms/op
Iteration   2: 2.816 ±(99.9%) 0.002 ms/op
Iteration   3: 2.698 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.779 ±(99.9%) 1.283 ms/op [Average]
  (min, avg, max) = (2.698, 2.779, 2.824), stdev = 0.070
  CI (99.9%): [1.497, 4.062] (assumes normal distribution)


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.003 ms/op
Iteration   1: 2.890 ±(99.9%) 0.003 ms/op
Iteration   2: 2.967 ±(99.9%) 0.003 ms/op
Iteration   3: 2.885 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.914 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (2.885, 2.914, 2.967), stdev = 0.046
  CI (99.9%): [2.077, 3.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.010 ms/op
Iteration   1: 3.736 ±(99.9%) 0.008 ms/op
Iteration   2: 3.717 ±(99.9%) 0.016 ms/op
Iteration   3: 3.746 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.733 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (3.717, 3.733, 3.746), stdev = 0.015
  CI (99.9%): [3.465, 4.001] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 2.948 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.389 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.354 ms/op
                 createUser·p0.999:  7.682 ms/op
                 createUser·p0.9999: 11.897 ms/op
                 createUser·p1.00:   12.157 ms/op

Iteration   2: 2.904 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.635 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   3: 2.950 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.544 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  13.517 ms/op
                 createUser·p0.9999: 22.189 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 327070
  mean =      2.934 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34379 
    [ 2.500,  5.000) = 291443 
    [ 5.000,  7.500) = 828 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     20.924 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.826 ±(99.9%) 0.005 ms/op
Iteration   1: 2.805 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.319 ms/op
                 existUser·p0.999:  4.956 ms/op
                 existUser·p0.9999: 17.778 ms/op
                 existUser·p1.00:   18.416 ms/op

Iteration   2: 2.795 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.200 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  6.147 ms/op
                 existUser·p0.9999: 24.112 ms/op
                 existUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340152
  mean =      2.822 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63426 
    [ 2.500,  5.000) = 276075 
    [ 5.000,  7.500) = 462 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      5.956 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     24.366 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.006 ms/op
Iteration   1: 2.938 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.579 ms/op
                 getUser·p0.9999: 18.091 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   2: 2.902 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.499 ms/op
                 getUser·p0.50:   2.900 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.937 ms/op
                 getUser·p0.9999: 17.889 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   3: 2.927 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.248 ms/op
                 getUser·p0.9999: 20.583 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 328426
  mean =      2.922 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39160 
    [ 2.500,  5.000) = 287985 
    [ 5.000,  7.500) = 1018 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.632 ms/op
     p(99.9900) =     20.256 ms/op
     p(99.9990) =     20.766 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 4.997 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.775 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.009 ms/op
Iteration   1: 3.763 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  11.534 ms/op
                 listUser·p0.9999: 12.984 ms/op
                 listUser·p1.00:   13.206 ms/op

Iteration   2: 3.760 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  12.549 ms/op
                 listUser·p0.9999: 18.399 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.717 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   6.259 ms/op
                 listUser·p0.999:  14.630 ms/op
                 listUser·p0.9999: 18.691 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 256202
  mean =      3.747 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 6600 
    [ 2.500,  3.750) = 152787 
    [ 3.750,  5.000) = 80192 
    [ 5.000,  6.250) = 13416 
    [ 6.250,  7.500) = 2236 
    [ 7.500,  8.750) = 383 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 69 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     12.301 ms/op
     p(99.9900) =     18.461 ms/op
     p(99.9990) =     18.856 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.903 ± 2.140  ops/ms
ClientGrpc.existUser                       thrpt       3  11.523 ± 1.901  ops/ms
ClientGrpc.getUser                         thrpt       3  10.893 ± 2.454  ops/ms
ClientGrpc.listUser                        thrpt       3   8.430 ± 0.763  ops/ms
ClientGrpc.createUser                       avgt       3   2.912 ± 0.817   ms/op
ClientGrpc.existUser                        avgt       3   2.779 ± 1.283   ms/op
ClientGrpc.getUser                          avgt       3   2.914 ± 0.837   ms/op
ClientGrpc.listUser                         avgt       3   3.733 ± 0.268   ms/op
ClientGrpc.createUser                     sample  327070   2.934 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.389           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.916           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.405           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.924           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.381           ms/op
ClientGrpc.existUser                      sample  340152   2.822 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.557           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.818           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.956           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.350           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.445           ms/op
ClientGrpc.getUser                        sample  328426   2.922 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.499           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.916           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.428           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.632           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.256           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  256202   3.747 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.927           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.613           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.431           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.301           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.461           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.907           ms/op
