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
# Warmup Iteration   1: 3.618 ops/ms
# Warmup Iteration   2: 7.791 ops/ms
# Warmup Iteration   3: 9.231 ops/ms
Iteration   1: 9.402 ops/ms
Iteration   2: 10.127 ops/ms
Iteration   3: 9.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.809 ±(99.9%) 6.766 ops/ms [Average]
  (min, avg, max) = (9.402, 9.809, 10.127), stdev = 0.371
  CI (99.9%): [3.043, 16.575] (assumes normal distribution)


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
# Warmup Iteration   1: 6.967 ops/ms
# Warmup Iteration   2: 9.883 ops/ms
# Warmup Iteration   3: 10.335 ops/ms
Iteration   1: 10.554 ops/ms
Iteration   2: 10.419 ops/ms
Iteration   3: 10.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.417 ±(99.9%) 2.527 ops/ms [Average]
  (min, avg, max) = (10.277, 10.417, 10.554), stdev = 0.139
  CI (99.9%): [7.890, 12.944] (assumes normal distribution)


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
# Warmup Iteration   1: 6.689 ops/ms
# Warmup Iteration   2: 9.011 ops/ms
# Warmup Iteration   3: 9.607 ops/ms
Iteration   1: 9.827 ops/ms
Iteration   2: 9.850 ops/ms
Iteration   3: 9.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.804 ±(99.9%) 1.120 ops/ms [Average]
  (min, avg, max) = (9.734, 9.804, 9.850), stdev = 0.061
  CI (99.9%): [8.683, 10.924] (assumes normal distribution)


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
# Warmup Iteration   1: 5.500 ops/ms
# Warmup Iteration   2: 7.244 ops/ms
# Warmup Iteration   3: 7.729 ops/ms
Iteration   1: 7.690 ops/ms
Iteration   2: 7.696 ops/ms
Iteration   3: 8.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.823 ±(99.9%) 4.107 ops/ms [Average]
  (min, avg, max) = (7.690, 7.823, 8.083), stdev = 0.225
  CI (99.9%): [3.717, 11.930] (assumes normal distribution)


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
# Warmup Iteration   1: 4.795 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.003 ms/op
Iteration   1: 3.240 ±(99.9%) 0.002 ms/op
Iteration   2: 3.258 ±(99.9%) 0.002 ms/op
Iteration   3: 3.176 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.225 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.176, 3.225, 3.258), stdev = 0.043
  CI (99.9%): [2.438, 4.011] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.578 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.003 ms/op
Iteration   1: 3.017 ±(99.9%) 0.002 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.045 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.017, 3.045, 3.088), stdev = 0.038
  CI (99.9%): [2.358, 3.733] (assumes normal distribution)


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
# Warmup Iteration   1: 4.770 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.002 ms/op
Iteration   1: 3.198 ±(99.9%) 0.002 ms/op
Iteration   2: 3.210 ±(99.9%) 0.002 ms/op
Iteration   3: 3.168 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.192 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.168, 3.192, 3.210), stdev = 0.021
  CI (99.9%): [2.804, 3.580] (assumes normal distribution)


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
# Warmup Iteration   1: 5.721 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.017 ms/op
Iteration   1: 4.065 ±(99.9%) 0.013 ms/op
Iteration   2: 4.138 ±(99.9%) 0.015 ms/op
Iteration   3: 4.040 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.081 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (4.040, 4.081, 4.138), stdev = 0.051
  CI (99.9%): [3.151, 5.011] (assumes normal distribution)


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
# Warmup Iteration   1: 4.601 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
Iteration   1: 3.307 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  8.983 ms/op
                 createUser·p0.9999: 15.554 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   2: 3.182 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.429 ms/op
                 createUser·p0.999:  8.364 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   3: 3.281 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.598 ms/op
                 createUser·p0.999:  11.890 ms/op
                 createUser·p0.9999: 22.291 ms/op
                 createUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294798
  mean =      3.256 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8203 
    [ 2.500,  5.000) = 282276 
    [ 5.000,  7.500) = 3566 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     21.007 ms/op
     p(99.9990) =     22.382 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
Iteration   1: 3.129 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.377 ms/op
                 existUser·p0.999:  7.567 ms/op
                 existUser·p0.9999: 15.779 ms/op
                 existUser·p1.00:   16.138 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 20.508 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  9.628 ms/op
                 existUser·p0.9999: 18.341 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 306423
  mean =      3.133 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18562 
    [ 2.500,  5.000) = 283417 
    [ 5.000,  7.500) = 3824 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.487 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     18.493 ms/op
     p(99.9990) =     20.895 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  11.641 ms/op
                 getUser·p0.9999: 17.594 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  9.308 ms/op
                 getUser·p0.9999: 14.630 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  8.361 ms/op
                 getUser·p0.9999: 17.722 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302263
  mean =      3.175 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 474 
    [ 1.250,  2.500) = 14958 
    [ 2.500,  3.750) = 257185 
    [ 3.750,  5.000) = 24436 
    [ 5.000,  6.250) = 3151 
    [ 6.250,  7.500) = 1208 
    [ 7.500,  8.750) = 430 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 96 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     10.268 ms/op
     p(99.9900) =     17.458 ms/op
     p(99.9990) =     18.054 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 5.459 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.013 ms/op
Iteration   1: 4.143 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.660 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  13.972 ms/op
                 listUser·p0.9999: 16.645 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 4.193 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   3: 4.247 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   6.537 ms/op
                 listUser·p0.99:   8.686 ms/op
                 listUser·p0.999:  19.890 ms/op
                 listUser·p0.9999: 26.673 ms/op
                 listUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229118
  mean =      4.194 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2836 
    [ 2.500,  5.000) = 188902 
    [ 5.000,  7.500) = 33071 
    [ 7.500, 10.000) = 3122 
    [10.000, 12.500) = 613 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     25.988 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.809 ± 6.766  ops/ms
ClientGrpc.existUser                       thrpt       3  10.417 ± 2.527  ops/ms
ClientGrpc.getUser                         thrpt       3   9.804 ± 1.120  ops/ms
ClientGrpc.listUser                        thrpt       3   7.823 ± 4.107  ops/ms
ClientGrpc.createUser                       avgt       3   3.225 ± 0.786   ms/op
ClientGrpc.existUser                        avgt       3   3.045 ± 0.687   ms/op
ClientGrpc.getUser                          avgt       3   3.192 ± 0.388   ms/op
ClientGrpc.listUser                         avgt       3   4.081 ± 0.930   ms/op
ClientGrpc.createUser                     sample  294798   3.256 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.630           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.437           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.007           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  306423   3.133 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.560           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.064           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.487           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.060           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.493           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.398           ms/op
ClientGrpc.getUser                        sample  302263   3.175 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.121           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.268           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.458           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.186           ms/op
ClientGrpc.listUser                       sample  229118   4.194 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.660           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.398           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.843           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.988           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.296           ms/op
