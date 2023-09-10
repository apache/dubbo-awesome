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
# Warmup Iteration   1: 4.270 ops/ms
# Warmup Iteration   2: 8.415 ops/ms
# Warmup Iteration   3: 9.976 ops/ms
Iteration   1: 10.206 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 10.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.258 ±(99.9%) 1.051 ops/ms [Average]
  (min, avg, max) = (10.206, 10.258, 10.320), stdev = 0.058
  CI (99.9%): [9.207, 11.309] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.393 ops/ms
# Warmup Iteration   2: 10.558 ops/ms
# Warmup Iteration   3: 10.889 ops/ms
Iteration   1: 11.011 ops/ms
Iteration   2: 10.827 ops/ms
Iteration   3: 11.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.966 ±(99.9%) 2.238 ops/ms [Average]
  (min, avg, max) = (10.827, 10.966, 11.059), stdev = 0.123
  CI (99.9%): [8.727, 13.204] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.908 ops/ms
# Warmup Iteration   2: 9.923 ops/ms
# Warmup Iteration   3: 10.305 ops/ms
Iteration   1: 10.318 ops/ms
Iteration   2: 10.199 ops/ms
Iteration   3: 10.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.266 ±(99.9%) 1.105 ops/ms [Average]
  (min, avg, max) = (10.199, 10.266, 10.318), stdev = 0.061
  CI (99.9%): [9.161, 11.371] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.263 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 8.182 ops/ms
Iteration   1: 7.848 ops/ms
Iteration   2: 7.889 ops/ms
Iteration   3: 7.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.874 ±(99.9%) 0.411 ops/ms [Average]
  (min, avg, max) = (7.848, 7.874, 7.889), stdev = 0.023
  CI (99.9%): [7.462, 8.285] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.114 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.005 ms/op
Iteration   1: 3.077 ±(99.9%) 0.004 ms/op
Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
Iteration   3: 3.082 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (3.077, 3.086, 3.098), stdev = 0.011
  CI (99.9%): [2.883, 3.288] (assumes normal distribution)


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.004 ms/op
Iteration   1: 3.007 ±(99.9%) 0.002 ms/op
Iteration   2: 2.948 ±(99.9%) 0.004 ms/op
Iteration   3: 2.943 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.966 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (2.943, 2.966, 3.007), stdev = 0.035
  CI (99.9%): [2.320, 3.612] (assumes normal distribution)


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.003 ms/op
Iteration   1: 3.139 ±(99.9%) 0.003 ms/op
Iteration   2: 3.055 ±(99.9%) 0.003 ms/op
Iteration   3: 3.027 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.074 ±(99.9%) 1.065 ms/op [Average]
  (min, avg, max) = (3.027, 3.074, 3.139), stdev = 0.058
  CI (99.9%): [2.009, 4.139] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.025 ms/op
Iteration   1: 4.016 ±(99.9%) 0.038 ms/op
Iteration   2: 3.937 ±(99.9%) 0.009 ms/op
Iteration   3: 3.885 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.946 ±(99.9%) 1.206 ms/op [Average]
  (min, avg, max) = (3.885, 3.946, 4.016), stdev = 0.066
  CI (99.9%): [2.739, 5.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.510 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  11.067 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  7.897 ms/op
                 createUser·p0.9999: 14.385 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.875 ms/op
                 createUser·p0.9999: 14.951 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315402
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1770 
    [ 1.250,  2.500) = 23944 
    [ 2.500,  3.750) = 271243 
    [ 3.750,  5.000) = 16141 
    [ 5.000,  6.250) = 1162 
    [ 6.250,  7.500) = 595 
    [ 7.500,  8.750) = 244 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 88 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     17.478 ms/op
     p(99.9990) =     18.045 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.665 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  8.032 ms/op
                 existUser·p0.9999: 15.996 ms/op
                 existUser·p1.00:   16.777 ms/op

Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  7.674 ms/op
                 existUser·p0.9999: 12.589 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 2.988 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.469 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  8.003 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321500
  mean =      2.985 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32157 
    [ 2.500,  5.000) = 287302 
    [ 5.000,  7.500) = 1637 
    [ 7.500, 10.000) = 211 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      7.942 ms/op
     p(99.9900) =     19.893 ms/op
     p(99.9990) =     22.228 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  8.241 ms/op
                 getUser·p0.9999: 18.464 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.532 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.739 ms/op
                 getUser·p0.9999: 13.582 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  7.009 ms/op
                 getUser·p0.9999: 15.613 ms/op
                 getUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313771
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1393 
    [ 1.250,  2.500) = 22482 
    [ 2.500,  3.750) = 269300 
    [ 3.750,  5.000) = 18427 
    [ 5.000,  6.250) = 1205 
    [ 6.250,  7.500) = 594 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      7.684 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     18.636 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 5.534 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.012 ms/op
Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.287 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  12.422 ms/op
                 listUser·p0.9999: 14.396 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  17.891 ms/op
                 listUser·p0.9999: 24.609 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 4.066 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  17.247 ms/op
                 listUser·p0.9999: 25.306 ms/op
                 listUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239786
  mean =      4.002 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4342 
    [ 2.500,  5.000) = 210277 
    [ 5.000,  7.500) = 23417 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.287 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     16.060 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     25.480 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.258 ± 1.051  ops/ms
ClientGrpc.existUser                       thrpt       3  10.966 ± 2.238  ops/ms
ClientGrpc.getUser                         thrpt       3  10.266 ± 1.105  ops/ms
ClientGrpc.listUser                        thrpt       3   7.874 ± 0.411  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 0.202   ms/op
ClientGrpc.existUser                        avgt       3   2.966 ± 0.646   ms/op
ClientGrpc.getUser                          avgt       3   3.074 ± 1.065   ms/op
ClientGrpc.listUser                         avgt       3   3.946 ± 1.206   ms/op
ClientGrpc.createUser                     sample  315402   3.044 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.510           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.536           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.478           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.088           ms/op
ClientGrpc.existUser                      sample  321500   2.985 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.469           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.661           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.942           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.893           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.315           ms/op
ClientGrpc.getUser                        sample  313771   3.060 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.532           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.684           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.891           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.711           ms/op
ClientGrpc.listUser                       sample  239786   4.002 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.287           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.060           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.838           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.494           ms/op
