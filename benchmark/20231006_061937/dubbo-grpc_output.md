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
# Warmup Iteration   1: 4.078 ops/ms
# Warmup Iteration   2: 8.571 ops/ms
# Warmup Iteration   3: 9.672 ops/ms
Iteration   1: 10.358 ops/ms
Iteration   2: 10.113 ops/ms
Iteration   3: 10.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.240 ±(99.9%) 2.238 ops/ms [Average]
  (min, avg, max) = (10.113, 10.240, 10.358), stdev = 0.123
  CI (99.9%): [8.002, 12.479] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.991 ops/ms
# Warmup Iteration   2: 10.204 ops/ms
# Warmup Iteration   3: 10.749 ops/ms
Iteration   1: 10.635 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.669 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (10.585, 10.669, 10.788), stdev = 0.106
  CI (99.9%): [8.741, 12.597] (assumes normal distribution)


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
# Warmup Iteration   1: 7.339 ops/ms
# Warmup Iteration   2: 9.920 ops/ms
# Warmup Iteration   3: 10.063 ops/ms
Iteration   1: 10.502 ops/ms
Iteration   2: 10.318 ops/ms
Iteration   3: 10.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.335 ±(99.9%) 2.901 ops/ms [Average]
  (min, avg, max) = (10.186, 10.335, 10.502), stdev = 0.159
  CI (99.9%): [7.435, 13.236] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.420 ops/ms
# Warmup Iteration   2: 7.635 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 8.143 ops/ms
Iteration   2: 8.335 ops/ms
Iteration   3: 8.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.185 ±(99.9%) 2.442 ops/ms [Average]
  (min, avg, max) = (8.078, 8.185, 8.335), stdev = 0.134
  CI (99.9%): [5.744, 10.627] (assumes normal distribution)


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.006 ms/op
Iteration   1: 3.130 ±(99.9%) 0.002 ms/op
Iteration   2: 3.126 ±(99.9%) 0.004 ms/op
Iteration   3: 3.138 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.131 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (3.126, 3.131, 3.138), stdev = 0.006
  CI (99.9%): [3.024, 3.238] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.002 ms/op
Iteration   1: 2.987 ±(99.9%) 0.003 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 2.978 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.009 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (2.978, 3.009, 3.061), stdev = 0.046
  CI (99.9%): [2.177, 3.841] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.004 ms/op
Iteration   1: 3.182 ±(99.9%) 0.003 ms/op
Iteration   2: 3.147 ±(99.9%) 0.004 ms/op
Iteration   3: 3.153 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.161 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.147, 3.161, 3.182), stdev = 0.019
  CI (99.9%): [2.821, 3.500] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.900 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.045 ms/op
Iteration   1: 3.909 ±(99.9%) 0.016 ms/op
Iteration   2: 3.930 ±(99.9%) 0.033 ms/op
Iteration   3: 3.992 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.944 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.909, 3.944, 3.992), stdev = 0.043
  CI (99.9%): [3.155, 4.733] (assumes normal distribution)


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.008 ms/op
Iteration   1: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  11.923 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.896 ms/op
                 createUser·p0.9999: 22.115 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   3: 3.117 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.430 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  16.974 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305885
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13725 
    [ 2.500,  5.000) = 290280 
    [ 5.000,  7.500) = 1398 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 17.508 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.413 ms/op
                 existUser·p0.9999: 14.772 ms/op
                 existUser·p1.00:   19.300 ms/op

Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  11.809 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320281
  mean =      2.999 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25487 
    [ 2.500,  5.000) = 292947 
    [ 5.000,  7.500) = 1307 
    [ 7.500, 10.000) = 256 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     18.612 ms/op
     p(99.9990) =     21.384 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.409 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  12.640 ms/op
                 getUser·p0.9999: 17.203 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.516 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  15.359 ms/op
                 getUser·p0.9999: 22.905 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.746 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306205
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10842 
    [ 2.500,  5.000) = 293340 
    [ 5.000,  7.500) = 1557 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     21.869 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 5.800 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.011 ms/op
Iteration   1: 4.026 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.148 ms/op
                 listUser·p0.9999: 23.336 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 3.941 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.661 ms/op
                 listUser·p0.9999: 16.020 ms/op
                 listUser·p1.00:   16.630 ms/op

Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  19.349 ms/op
                 listUser·p0.9999: 26.963 ms/op
                 listUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241128
  mean =      3.980 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2786 
    [ 2.500,  5.000) = 221028 
    [ 5.000,  7.500) = 16005 
    [ 7.500, 10.000) = 726 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.879 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     23.673 ms/op
     p(99.9990) =     27.517 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.240 ± 2.238  ops/ms
ClientGrpc.existUser                       thrpt       3  10.669 ± 1.928  ops/ms
ClientGrpc.getUser                         thrpt       3  10.335 ± 2.901  ops/ms
ClientGrpc.listUser                        thrpt       3   8.185 ± 2.442  ops/ms
ClientGrpc.createUser                       avgt       3   3.131 ± 0.107   ms/op
ClientGrpc.existUser                        avgt       3   3.009 ± 0.832   ms/op
ClientGrpc.getUser                          avgt       3   3.161 ± 0.340   ms/op
ClientGrpc.listUser                         avgt       3   3.944 ± 0.789   ms/op
ClientGrpc.createUser                     sample  305885   3.142 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.430           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.159           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.233           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.888           ms/op
ClientGrpc.existUser                      sample  320281   2.999 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.764           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.306           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.612           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.529           ms/op
ClientGrpc.getUser                        sample  306205   3.136 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.516           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.764           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.869           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.953           ms/op
ClientGrpc.listUser                       sample  241128   3.980 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.868           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.879           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.893           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.673           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.656           ms/op
