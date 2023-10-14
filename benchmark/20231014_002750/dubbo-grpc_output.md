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
# Warmup Iteration   1: 3.653 ops/ms
# Warmup Iteration   2: 8.612 ops/ms
# Warmup Iteration   3: 9.759 ops/ms
Iteration   1: 9.853 ops/ms
Iteration   2: 10.248 ops/ms
Iteration   3: 10.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.116 ±(99.9%) 4.152 ops/ms [Average]
  (min, avg, max) = (9.853, 10.116, 10.248), stdev = 0.228
  CI (99.9%): [5.964, 14.267] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.337 ops/ms
# Warmup Iteration   2: 10.274 ops/ms
# Warmup Iteration   3: 10.576 ops/ms
Iteration   1: 10.866 ops/ms
Iteration   2: 10.906 ops/ms
Iteration   3: 10.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.792 ±(99.9%) 2.983 ops/ms [Average]
  (min, avg, max) = (10.605, 10.792, 10.906), stdev = 0.164
  CI (99.9%): [7.809, 13.776] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.912 ops/ms
# Warmup Iteration   2: 9.810 ops/ms
# Warmup Iteration   3: 9.910 ops/ms
Iteration   1: 10.166 ops/ms
Iteration   2: 10.156 ops/ms
Iteration   3: 10.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.151 ±(99.9%) 0.316 ops/ms [Average]
  (min, avg, max) = (10.132, 10.151, 10.166), stdev = 0.017
  CI (99.9%): [9.835, 10.468] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.468 ops/ms
# Warmup Iteration   2: 7.584 ops/ms
# Warmup Iteration   3: 7.856 ops/ms
Iteration   1: 7.846 ops/ms
Iteration   2: 7.897 ops/ms
Iteration   3: 7.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.884 ±(99.9%) 0.600 ops/ms [Average]
  (min, avg, max) = (7.846, 7.884, 7.907), stdev = 0.033
  CI (99.9%): [7.284, 8.483] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.494 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.002 ms/op
Iteration   1: 3.174 ±(99.9%) 0.002 ms/op
Iteration   2: 3.134 ±(99.9%) 0.003 ms/op
Iteration   3: 3.184 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.164 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (3.134, 3.164, 3.184), stdev = 0.026
  CI (99.9%): [2.684, 3.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.033 ±(99.9%) 0.003 ms/op
Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.022 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (3.010, 3.022, 3.033), stdev = 0.012
  CI (99.9%): [2.808, 3.235] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.267 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.002 ms/op
Iteration   1: 3.184 ±(99.9%) 0.006 ms/op
Iteration   2: 3.183 ±(99.9%) 0.003 ms/op
Iteration   3: 3.213 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.193 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (3.183, 3.193, 3.213), stdev = 0.017
  CI (99.9%): [2.880, 3.507] (assumes normal distribution)


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
# Warmup Iteration   1: 5.550 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.011 ms/op
Iteration   1: 4.049 ±(99.9%) 0.033 ms/op
Iteration   2: 3.881 ±(99.9%) 0.010 ms/op
Iteration   3: 3.986 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.972 ±(99.9%) 1.550 ms/op [Average]
  (min, avg, max) = (3.881, 3.972, 4.049), stdev = 0.085
  CI (99.9%): [2.421, 5.522] (assumes normal distribution)


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 19.543 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  13.832 ms/op
                 createUser·p0.9999: 21.559 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   3: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.973 ms/op
                 createUser·p0.999:  13.099 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304941
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12733 
    [ 2.500,  5.000) = 288760 
    [ 5.000,  7.500) = 2712 
    [ 7.500, 10.000) = 390 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     10.702 ms/op
     p(99.9900) =     21.578 ms/op
     p(99.9990) =     22.279 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.651 ms/op
                 existUser·p0.999:  12.075 ms/op
                 existUser·p0.9999: 17.510 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 16.553 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.886 ms/op
                 existUser·p0.9999: 19.932 ms/op
                 existUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316875
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23987 
    [ 2.500,  5.000) = 290791 
    [ 5.000,  7.500) = 1500 
    [ 7.500, 10.000) = 294 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.964 ms/op
     p(99.9900) =     17.902 ms/op
     p(99.9990) =     20.305 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.007 ms/op
Iteration   1: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  12.698 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.805 ms/op
                 getUser·p0.999:  8.617 ms/op
                 getUser·p0.9999: 23.776 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  11.138 ms/op
                 getUser·p0.9999: 21.128 ms/op
                 getUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302912
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12813 
    [ 2.500,  5.000) = 287182 
    [ 5.000,  7.500) = 2070 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     11.698 ms/op
     p(99.9900) =     21.486 ms/op
     p(99.9990) =     24.180 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 5.947 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.011 ms/op
Iteration   1: 4.008 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.206 ms/op
                 listUser·p0.9999: 16.188 ms/op
                 listUser·p1.00:   16.695 ms/op

Iteration   2: 3.939 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 17.228 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.956 ms/op
                 listUser·p0.9999: 23.785 ms/op
                 listUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242292
  mean =      3.962 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2078 
    [ 2.500,  5.000) = 223696 
    [ 5.000,  7.500) = 15120 
    [ 7.500, 10.000) = 896 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.752 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     24.071 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.116 ± 4.152  ops/ms
ClientGrpc.existUser                       thrpt       3  10.792 ± 2.983  ops/ms
ClientGrpc.getUser                         thrpt       3  10.151 ± 0.316  ops/ms
ClientGrpc.listUser                        thrpt       3   7.884 ± 0.600  ops/ms
ClientGrpc.createUser                       avgt       3   3.164 ± 0.480   ms/op
ClientGrpc.existUser                        avgt       3   3.022 ± 0.213   ms/op
ClientGrpc.getUser                          avgt       3   3.193 ± 0.313   ms/op
ClientGrpc.listUser                         avgt       3   3.972 ± 1.550   ms/op
ClientGrpc.createUser                     sample  304941   3.147 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.685           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.702           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.578           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.479           ms/op
ClientGrpc.existUser                      sample  316875   3.028 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.668           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.964           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.902           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.447           ms/op
ClientGrpc.getUser                        sample  302912   3.169 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.696           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.698           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.486           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.379           ms/op
ClientGrpc.listUser                       sample  242292   3.962 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.092           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.752           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.069           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.084           ms/op
