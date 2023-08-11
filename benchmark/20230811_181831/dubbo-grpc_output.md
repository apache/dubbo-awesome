# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ops/ms
# Warmup Iteration   2: 8.933 ops/ms
# Warmup Iteration   3: 10.106 ops/ms
Iteration   1: 10.415 ops/ms
Iteration   2: 10.426 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.504 ±(99.9%) 2.638 ops/ms [Average]
  (min, avg, max) = (10.415, 10.504, 10.671), stdev = 0.145
  CI (99.9%): [7.866, 13.142] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.517 ops/ms
# Warmup Iteration   2: 10.505 ops/ms
# Warmup Iteration   3: 11.315 ops/ms
Iteration   1: 11.215 ops/ms
Iteration   2: 11.237 ops/ms
Iteration   3: 11.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.164 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (11.040, 11.164, 11.237), stdev = 0.108
  CI (99.9%): [9.191, 13.137] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.274 ops/ms
# Warmup Iteration   2: 10.129 ops/ms
# Warmup Iteration   3: 10.834 ops/ms
Iteration   1: 10.813 ops/ms
Iteration   2: 10.904 ops/ms
Iteration   3: 10.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.844 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (10.813, 10.844, 10.904), stdev = 0.052
  CI (99.9%): [9.892, 11.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.846 ops/ms
# Warmup Iteration   2: 8.078 ops/ms
# Warmup Iteration   3: 8.112 ops/ms
Iteration   1: 8.445 ops/ms
Iteration   2: 8.283 ops/ms
Iteration   3: 8.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.332 ±(99.9%) 1.790 ops/ms [Average]
  (min, avg, max) = (8.268, 8.332, 8.445), stdev = 0.098
  CI (99.9%): [6.542, 10.122] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.020 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.002 ms/op
Iteration   1: 3.077 ±(99.9%) 0.002 ms/op
Iteration   2: 3.010 ±(99.9%) 0.009 ms/op
Iteration   3: 3.105 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.064 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (3.010, 3.064, 3.105), stdev = 0.049
  CI (99.9%): [2.169, 3.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.818 ±(99.9%) 0.003 ms/op
Iteration   1: 2.871 ±(99.9%) 0.004 ms/op
Iteration   2: 2.870 ±(99.9%) 0.003 ms/op
Iteration   3: 2.867 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.869 ±(99.9%) 0.044 ms/op [Average]
  (min, avg, max) = (2.867, 2.869, 2.871), stdev = 0.002
  CI (99.9%): [2.826, 2.913] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.002 ms/op
Iteration   1: 2.912 ±(99.9%) 0.004 ms/op
Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
Iteration   3: 3.015 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.000 ±(99.9%) 1.502 ms/op [Average]
  (min, avg, max) = (2.912, 3.000, 3.075), stdev = 0.082
  CI (99.9%): [1.499, 4.502] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.154 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.012 ms/op
Iteration   1: 3.876 ±(99.9%) 0.010 ms/op
Iteration   2: 3.919 ±(99.9%) 0.011 ms/op
Iteration   3: 3.854 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.883 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.854, 3.883, 3.919), stdev = 0.033
  CI (99.9%): [3.277, 4.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.086 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  8.894 ms/op
                 createUser·p0.9999: 11.796 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  11.979 ms/op
                 createUser·p0.9999: 22.722 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  10.534 ms/op
                 createUser·p0.9999: 18.295 ms/op
                 createUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317690
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19357 
    [ 2.500,  5.000) = 296582 
    [ 5.000,  7.500) = 1170 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     10.026 ms/op
     p(99.9900) =     21.995 ms/op
     p(99.9990) =     22.965 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  7.963 ms/op
                 existUser·p0.9999: 11.567 ms/op
                 existUser·p1.00:   11.747 ms/op

Iteration   2: 2.935 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  7.609 ms/op
                 existUser·p0.9999: 22.842 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  7.766 ms/op
                 existUser·p0.9999: 16.739 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329200
  mean =      2.919 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47985 
    [ 2.500,  5.000) = 279500 
    [ 5.000,  7.500) = 1267 
    [ 7.500, 10.000) = 256 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.805 ms/op
     p(99.9900) =     17.262 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.052 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.399 ms/op
                 getUser·p0.9999: 17.934 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.483 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  9.198 ms/op
                 getUser·p0.9999: 23.377 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.375 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.805 ms/op
                 getUser·p0.9999: 16.582 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318912
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27218 
    [ 2.500,  5.000) = 290075 
    [ 5.000,  7.500) = 1211 
    [ 7.500, 10.000) = 175 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     24.406 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.806 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.011 ms/op
Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.705 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.491 ms/op
                 listUser·p0.99:   6.867 ms/op
                 listUser·p0.999:  14.178 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.878 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.799 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.437 ms/op
                 listUser·p0.9999: 18.374 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 3.903 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 26.011 ms/op
                 listUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247279
  mean =      3.885 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4234 
    [ 2.500,  5.000) = 221469 
    [ 5.000,  7.500) = 20250 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     16.347 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     26.264 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.504 ± 2.638  ops/ms
ClientGrpc.existUser                       thrpt       3  11.164 ± 1.973  ops/ms
ClientGrpc.getUser                         thrpt       3  10.844 ± 0.952  ops/ms
ClientGrpc.listUser                        thrpt       3   8.332 ± 1.790  ops/ms
ClientGrpc.createUser                       avgt       3   3.064 ± 0.894   ms/op
ClientGrpc.existUser                        avgt       3   2.869 ± 0.044   ms/op
ClientGrpc.getUser                          avgt       3   3.000 ± 1.502   ms/op
ClientGrpc.listUser                         avgt       3   3.883 ± 0.606   ms/op
ClientGrpc.createUser                     sample  317690   3.021 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.642           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.026           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.995           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.036           ms/op
ClientGrpc.existUser                      sample  329200   2.919 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.536           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.805           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.262           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.298           ms/op
ClientGrpc.getUser                        sample  318912   3.008 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.375           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.897           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.512           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.510           ms/op
ClientGrpc.listUser                       sample  247279   3.885 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.705           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.347           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.216           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.378           ms/op
