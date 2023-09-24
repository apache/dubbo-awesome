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
# Warmup Iteration   1: 4.287 ops/ms
# Warmup Iteration   2: 8.644 ops/ms
# Warmup Iteration   3: 10.032 ops/ms
Iteration   1: 10.130 ops/ms
Iteration   2: 10.258 ops/ms
Iteration   3: 10.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.182 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (10.130, 10.182, 10.258), stdev = 0.068
  CI (99.9%): [8.947, 11.416] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.435 ops/ms
# Warmup Iteration   2: 10.381 ops/ms
# Warmup Iteration   3: 11.000 ops/ms
Iteration   1: 10.939 ops/ms
Iteration   2: 10.843 ops/ms
Iteration   3: 10.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.897 ±(99.9%) 0.905 ops/ms [Average]
  (min, avg, max) = (10.843, 10.897, 10.939), stdev = 0.050
  CI (99.9%): [9.993, 11.802] (assumes normal distribution)


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
# Warmup Iteration   1: 7.892 ops/ms
# Warmup Iteration   2: 10.032 ops/ms
# Warmup Iteration   3: 10.225 ops/ms
Iteration   1: 10.186 ops/ms
Iteration   2: 10.367 ops/ms
Iteration   3: 10.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.206 ±(99.9%) 2.781 ops/ms [Average]
  (min, avg, max) = (10.064, 10.206, 10.367), stdev = 0.152
  CI (99.9%): [7.425, 12.987] (assumes normal distribution)


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
# Warmup Iteration   1: 6.527 ops/ms
# Warmup Iteration   2: 7.907 ops/ms
# Warmup Iteration   3: 8.414 ops/ms
Iteration   1: 8.202 ops/ms
Iteration   2: 8.351 ops/ms
Iteration   3: 8.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.293 ±(99.9%) 1.462 ops/ms [Average]
  (min, avg, max) = (8.202, 8.293, 8.351), stdev = 0.080
  CI (99.9%): [6.831, 9.755] (assumes normal distribution)


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.055 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.072 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (3.055, 3.072, 3.085), stdev = 0.016
  CI (99.9%): [2.784, 3.360] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.003 ms/op
Iteration   1: 2.916 ±(99.9%) 0.002 ms/op
Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
Iteration   3: 2.960 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.953 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (2.916, 2.953, 2.983), stdev = 0.034
  CI (99.9%): [2.335, 3.571] (assumes normal distribution)


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.002 ms/op
Iteration   1: 3.078 ±(99.9%) 0.002 ms/op
Iteration   2: 3.190 ±(99.9%) 0.001 ms/op
Iteration   3: 3.108 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.125 ±(99.9%) 1.056 ms/op [Average]
  (min, avg, max) = (3.078, 3.125, 3.190), stdev = 0.058
  CI (99.9%): [2.070, 4.181] (assumes normal distribution)


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.017 ms/op
Iteration   1: 3.850 ±(99.9%) 0.023 ms/op
Iteration   2: 3.899 ±(99.9%) 0.015 ms/op
Iteration   3: 3.760 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.836 ±(99.9%) 1.290 ms/op [Average]
  (min, avg, max) = (3.760, 3.836, 3.899), stdev = 0.071
  CI (99.9%): [2.547, 5.126] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  6.969 ms/op
                 createUser·p0.9999: 13.885 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  9.595 ms/op
                 createUser·p0.9999: 24.077 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  11.319 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308753
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9183 
    [ 2.500,  5.000) = 298025 
    [ 5.000,  7.500) = 1132 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.384 ms/op
     p(99.9900) =     23.568 ms/op
     p(99.9990) =     24.344 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.005 ms/op
Iteration   1: 2.976 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.111 ms/op
                 existUser·p0.9999: 10.936 ms/op
                 existUser·p1.00:   11.747 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  7.574 ms/op
                 existUser·p0.9999: 18.925 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.995 ms/op
                 existUser·p0.9999: 15.487 ms/op
                 existUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322562
  mean =      2.977 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1225 
    [ 1.250,  2.500) = 23605 
    [ 2.500,  3.750) = 287094 
    [ 3.750,  5.000) = 9070 
    [ 5.000,  6.250) = 918 
    [ 6.250,  7.500) = 337 
    [ 7.500,  8.750) = 149 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.450 ms/op
     p(99.9900) =     17.597 ms/op
     p(99.9990) =     19.286 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
Iteration   1: 3.176 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  8.131 ms/op
                 getUser·p0.9999: 14.629 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   2: 2.973 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.533 ms/op
                 getUser·p0.9999: 17.619 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 3.031 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.501 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  6.631 ms/op
                 getUser·p0.9999: 21.642 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313938
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20432 
    [ 2.500,  5.000) = 291458 
    [ 5.000,  7.500) = 1734 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.513 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.917 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 4.613 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.009 ms/op
Iteration   1: 3.849 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  12.026 ms/op
                 listUser·p0.9999: 14.544 ms/op
                 listUser·p1.00:   14.959 ms/op

Iteration   2: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.713 ms/op
                 listUser·p0.9999: 18.134 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 3.854 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 18.419 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249111
  mean =      3.852 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 4697 
    [ 2.500,  3.750) = 119569 
    [ 3.750,  5.000) = 108710 
    [ 5.000,  6.250) = 10859 
    [ 6.250,  7.500) = 4220 
    [ 7.500,  8.750) = 373 
    [ 8.750, 10.000) = 170 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 82 
    [15.000, 16.250) = 73 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.548 ms/op
     p(99.9900) =     18.025 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.182 ± 1.234  ops/ms
ClientGrpc.existUser                       thrpt       3  10.897 ± 0.905  ops/ms
ClientGrpc.getUser                         thrpt       3  10.206 ± 2.781  ops/ms
ClientGrpc.listUser                        thrpt       3   8.293 ± 1.462  ops/ms
ClientGrpc.createUser                       avgt       3   3.072 ± 0.288   ms/op
ClientGrpc.existUser                        avgt       3   2.953 ± 0.618   ms/op
ClientGrpc.getUser                          avgt       3   3.125 ± 1.056   ms/op
ClientGrpc.listUser                         avgt       3   3.836 ± 1.290   ms/op
ClientGrpc.createUser                     sample  308753   3.109 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.697           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.384           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.568           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.412           ms/op
ClientGrpc.existUser                      sample  322562   2.977 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.664           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.450           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.597           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.366           ms/op
ClientGrpc.getUser                        sample  313938   3.058 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.501           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.513           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.234           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.955           ms/op
ClientGrpc.listUser                       sample  249111   3.852 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.059           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.317           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.548           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.025           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.874           ms/op
