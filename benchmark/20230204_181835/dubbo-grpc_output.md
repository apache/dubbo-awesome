# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.052 ops/ms
# Warmup Iteration   2: 8.781 ops/ms
# Warmup Iteration   3: 9.573 ops/ms
Iteration   1: 9.371 ops/ms
Iteration   2: 9.699 ops/ms
Iteration   3: 9.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.496 ±(99.9%) 3.236 ops/ms [Average]
  (min, avg, max) = (9.371, 9.496, 9.699), stdev = 0.177
  CI (99.9%): [6.259, 12.732] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.252 ops/ms
# Warmup Iteration   2: 10.078 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 9.924 ops/ms
Iteration   2: 10.079 ops/ms
Iteration   3: 9.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.999 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (9.924, 9.999, 10.079), stdev = 0.078
  CI (99.9%): [8.581, 11.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.613 ops/ms
# Warmup Iteration   2: 9.372 ops/ms
# Warmup Iteration   3: 9.627 ops/ms
Iteration   1: 9.832 ops/ms
Iteration   2: 9.572 ops/ms
Iteration   3: 9.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.757 ±(99.9%) 2.942 ops/ms [Average]
  (min, avg, max) = (9.572, 9.757, 9.867), stdev = 0.161
  CI (99.9%): [6.814, 12.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.357 ops/ms
# Warmup Iteration   2: 7.247 ops/ms
# Warmup Iteration   3: 7.529 ops/ms
Iteration   1: 7.608 ops/ms
Iteration   2: 7.492 ops/ms
Iteration   3: 7.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.527 ±(99.9%) 1.292 ops/ms [Average]
  (min, avg, max) = (7.480, 7.527, 7.608), stdev = 0.071
  CI (99.9%): [6.234, 8.819] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.540 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.002 ms/op
Iteration   1: 3.341 ±(99.9%) 0.001 ms/op
Iteration   2: 3.394 ±(99.9%) 0.001 ms/op
Iteration   3: 3.353 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.363 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.341, 3.363, 3.394), stdev = 0.028
  CI (99.9%): [2.853, 3.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.314 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.003 ms/op
Iteration   1: 3.197 ±(99.9%) 0.003 ms/op
Iteration   2: 3.264 ±(99.9%) 0.003 ms/op
Iteration   3: 3.258 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.240 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (3.197, 3.240, 3.264), stdev = 0.037
  CI (99.9%): [2.564, 3.916] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.591 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.003 ms/op
Iteration   1: 3.322 ±(99.9%) 0.005 ms/op
Iteration   2: 3.279 ±(99.9%) 0.003 ms/op
Iteration   3: 3.357 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.319 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (3.279, 3.319, 3.357), stdev = 0.039
  CI (99.9%): [2.607, 4.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.733 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.465 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.334 ±(99.9%) 0.007 ms/op
Iteration   1: 4.279 ±(99.9%) 0.018 ms/op
Iteration   2: 4.169 ±(99.9%) 0.011 ms/op
Iteration   3: 4.222 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.223 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (4.169, 4.223, 4.279), stdev = 0.055
  CI (99.9%): [3.219, 5.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.674 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.345 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.328 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  8.375 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   17.760 ms/op

Iteration   2: 3.390 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  6.832 ms/op
                 createUser·p0.9999: 18.991 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  7.856 ms/op
                 createUser·p0.9999: 22.111 ms/op
                 createUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 287580
  mean =      3.338 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18266 
    [ 2.500,  5.000) = 267421 
    [ 5.000,  7.500) = 1587 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     24.588 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.219 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.006 ms/op
Iteration   1: 3.091 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  6.877 ms/op
                 existUser·p0.9999: 15.199 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   2: 3.175 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  5.938 ms/op
                 existUser·p0.9999: 22.409 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   3: 3.197 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  6.619 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 304218
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40734 
    [ 2.500,  5.000) = 262419 
    [ 5.000,  7.500) = 833 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     20.130 ms/op
     p(99.9990) =     22.805 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.720 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
Iteration   1: 3.368 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  6.586 ms/op
                 getUser·p0.9999: 18.924 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   2: 3.300 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  7.856 ms/op
                 getUser·p0.9999: 18.917 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   3: 3.300 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  7.169 ms/op
                 getUser·p0.9999: 21.188 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 288809
  mean =      3.322 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19668 
    [ 2.500,  5.000) = 267845 
    [ 5.000,  7.500) = 1031 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      7.360 ms/op
     p(99.9900) =     20.619 ms/op
     p(99.9990) =     21.474 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.631 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.012 ms/op
Iteration   1: 4.210 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 22.538 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   2: 4.274 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   7.374 ms/op
                 listUser·p0.999:  14.566 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 4.338 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   4.178 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  18.064 ms/op
                 listUser·p0.9999: 32.318 ms/op
                 listUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 224713
  mean =      4.273 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1799 
    [ 2.500,  5.000) = 192639 
    [ 5.000,  7.500) = 28233 
    [ 7.500, 10.000) = 1557 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     16.569 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     32.719 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.496 ± 3.236  ops/ms
ClientGrpc.existUser                       thrpt       3   9.999 ± 1.418  ops/ms
ClientGrpc.getUser                         thrpt       3   9.757 ± 2.942  ops/ms
ClientGrpc.listUser                        thrpt       3   7.527 ± 1.292  ops/ms
ClientGrpc.createUser                       avgt       3   3.363 ± 0.510   ms/op
ClientGrpc.existUser                        avgt       3   3.240 ± 0.676   ms/op
ClientGrpc.getUser                          avgt       3   3.319 ± 0.712   ms/op
ClientGrpc.listUser                         avgt       3   4.223 ± 1.004   ms/op
ClientGrpc.createUser                     sample  287580   3.338 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.697           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.310           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.635           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.168           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.674           ms/op
ClientGrpc.existUser                      sample  304218   3.154 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.554           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.158           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.734           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.130           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.905           ms/op
ClientGrpc.getUser                        sample  288809   3.322 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.084           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.360           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.619           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  224713   4.273 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.858           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.112           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.317           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.569           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.179           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.834           ms/op
