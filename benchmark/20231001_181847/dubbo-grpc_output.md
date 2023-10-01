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
# Warmup Iteration   1: 3.681 ops/ms
# Warmup Iteration   2: 8.288 ops/ms
# Warmup Iteration   3: 9.601 ops/ms
Iteration   1: 10.114 ops/ms
Iteration   2: 10.133 ops/ms
Iteration   3: 9.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.076 ±(99.9%) 1.499 ops/ms [Average]
  (min, avg, max) = (9.982, 10.076, 10.133), stdev = 0.082
  CI (99.9%): [8.578, 11.575] (assumes normal distribution)


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
# Warmup Iteration   1: 7.372 ops/ms
# Warmup Iteration   2: 10.069 ops/ms
# Warmup Iteration   3: 10.326 ops/ms
Iteration   1: 10.553 ops/ms
Iteration   2: 10.451 ops/ms
Iteration   3: 10.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.484 ±(99.9%) 1.095 ops/ms [Average]
  (min, avg, max) = (10.448, 10.484, 10.553), stdev = 0.060
  CI (99.9%): [9.389, 11.579] (assumes normal distribution)


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
# Warmup Iteration   1: 6.728 ops/ms
# Warmup Iteration   2: 9.764 ops/ms
# Warmup Iteration   3: 10.225 ops/ms
Iteration   1: 10.120 ops/ms
Iteration   2: 10.150 ops/ms
Iteration   3: 10.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.123 ±(99.9%) 0.467 ops/ms [Average]
  (min, avg, max) = (10.100, 10.123, 10.150), stdev = 0.026
  CI (99.9%): [9.656, 10.590] (assumes normal distribution)


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
# Warmup Iteration   1: 4.998 ops/ms
# Warmup Iteration   2: 6.904 ops/ms
# Warmup Iteration   3: 7.555 ops/ms
Iteration   1: 7.780 ops/ms
Iteration   2: 7.781 ops/ms
Iteration   3: 7.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.753 ±(99.9%) 0.878 ops/ms [Average]
  (min, avg, max) = (7.697, 7.753, 7.781), stdev = 0.048
  CI (99.9%): [6.875, 8.631] (assumes normal distribution)


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
# Warmup Iteration   1: 4.482 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.003 ms/op
Iteration   1: 3.167 ±(99.9%) 0.003 ms/op
Iteration   2: 3.177 ±(99.9%) 0.002 ms/op
Iteration   3: 3.156 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.167 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.156, 3.167, 3.177), stdev = 0.011
  CI (99.9%): [2.975, 3.359] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 2.958 ±(99.9%) 0.003 ms/op
Iteration   2: 3.000 ±(99.9%) 0.002 ms/op
Iteration   3: 2.982 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.958, 2.980, 3.000), stdev = 0.021
  CI (99.9%): [2.594, 3.366] (assumes normal distribution)


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.003 ms/op
Iteration   1: 3.190 ±(99.9%) 0.004 ms/op
Iteration   2: 3.166 ±(99.9%) 0.003 ms/op
Iteration   3: 3.197 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.184 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (3.166, 3.184, 3.197), stdev = 0.016
  CI (99.9%): [2.884, 3.485] (assumes normal distribution)


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
# Warmup Iteration   1: 5.291 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.017 ms/op
Iteration   1: 3.996 ±(99.9%) 0.005 ms/op
Iteration   2: 4.020 ±(99.9%) 0.016 ms/op
Iteration   3: 3.939 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.985 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (3.939, 3.985, 4.020), stdev = 0.042
  CI (99.9%): [3.227, 4.743] (assumes normal distribution)


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.008 ms/op
Iteration   1: 3.283 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.046 ms/op
                 createUser·p0.999:  9.431 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   2: 3.289 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  7.930 ms/op
                 createUser·p0.9999: 19.047 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  11.347 ms/op
                 createUser·p0.9999: 22.417 ms/op
                 createUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 293433
  mean =      3.269 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9321 
    [ 2.500,  5.000) = 281231 
    [ 5.000,  7.500) = 2207 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      4.981 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     21.583 ms/op
     p(99.9990) =     22.481 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.503 ms/op
                 existUser·p0.9999: 16.678 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  10.284 ms/op
                 existUser·p0.9999: 18.592 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.296 ms/op
                 existUser·p0.9999: 20.583 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315756
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23415 
    [ 2.500,  5.000) = 290289 
    [ 5.000,  7.500) = 1641 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.093 ms/op
     p(99.9900) =     19.085 ms/op
     p(99.9990) =     20.994 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.007 ms/op
Iteration   1: 3.212 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  10.197 ms/op
                 getUser·p0.9999: 15.141 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 3.160 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.453 ms/op
                 getUser·p0.9999: 14.613 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  8.069 ms/op
                 getUser·p0.9999: 17.361 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301688
  mean =      3.180 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 5528 
    [ 2.500,  3.750) = 266956 
    [ 3.750,  5.000) = 27530 
    [ 5.000,  6.250) = 646 
    [ 6.250,  7.500) = 524 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.367 ms/op
     p(99.9000) =      7.979 ms/op
     p(99.9900) =     15.483 ms/op
     p(99.9990) =     17.530 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 5.822 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.009 ms/op
Iteration   1: 4.063 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.421 ms/op
                 listUser·p0.9999: 14.860 ms/op
                 listUser·p1.00:   15.204 ms/op

Iteration   2: 3.933 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.986 ms/op
                 listUser·p0.9999: 15.415 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 3.855 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.125 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243204
  mean =      3.948 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1676 
    [ 2.500,  3.750) = 94088 
    [ 3.750,  5.000) = 133899 
    [ 5.000,  6.250) = 8157 
    [ 6.250,  7.500) = 4205 
    [ 7.500,  8.750) = 583 
    [ 8.750, 10.000) = 135 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 167 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 61 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.972 ms/op
     p(99.9900) =     17.094 ms/op
     p(99.9990) =     17.947 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.076 ± 1.499  ops/ms
ClientGrpc.existUser                       thrpt       3  10.484 ± 1.095  ops/ms
ClientGrpc.getUser                         thrpt       3  10.123 ± 0.467  ops/ms
ClientGrpc.listUser                        thrpt       3   7.753 ± 0.878  ops/ms
ClientGrpc.createUser                       avgt       3   3.167 ± 0.192   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 0.386   ms/op
ClientGrpc.getUser                          avgt       3   3.184 ± 0.300   ms/op
ClientGrpc.listUser                         avgt       3   3.985 ± 0.758   ms/op
ClientGrpc.createUser                     sample  293433   3.269 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.703           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.203           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.162           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.981           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.583           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.577           ms/op
ClientGrpc.existUser                      sample  315756   3.040 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.737           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.093           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.085           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.103           ms/op
ClientGrpc.getUser                        sample  301688   3.180 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.910           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.367           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.979           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.483           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.629           ms/op
ClientGrpc.listUser                       sample  243204   3.948 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.912           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.972           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.094           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.088           ms/op
