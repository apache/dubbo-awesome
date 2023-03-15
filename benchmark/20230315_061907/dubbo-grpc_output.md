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
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 5.354 ops/ms
# Warmup Iteration   3: 7.147 ops/ms
Iteration   1: 7.238 ops/ms
Iteration   2: 7.358 ops/ms
Iteration   3: 7.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.430 ±(99.9%) 4.304 ops/ms [Average]
  (min, avg, max) = (7.238, 7.430, 7.693), stdev = 0.236
  CI (99.9%): [3.126, 11.734] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.487 ops/ms
# Warmup Iteration   2: 7.065 ops/ms
# Warmup Iteration   3: 7.758 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 8.032 ops/ms
Iteration   3: 7.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.891 ±(99.9%) 2.225 ops/ms [Average]
  (min, avg, max) = (7.818, 7.891, 8.032), stdev = 0.122
  CI (99.9%): [5.666, 10.116] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.274 ops/ms
# Warmup Iteration   2: 6.580 ops/ms
# Warmup Iteration   3: 7.311 ops/ms
Iteration   1: 7.349 ops/ms
Iteration   2: 7.367 ops/ms
Iteration   3: 7.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.283 ±(99.9%) 2.366 ops/ms [Average]
  (min, avg, max) = (7.134, 7.283, 7.367), stdev = 0.130
  CI (99.9%): [4.917, 9.649] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.556 ops/ms
# Warmup Iteration   2: 5.095 ops/ms
# Warmup Iteration   3: 5.606 ops/ms
Iteration   1: 5.802 ops/ms
Iteration   2: 5.806 ops/ms
Iteration   3: 5.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.837 ±(99.9%) 1.045 ops/ms [Average]
  (min, avg, max) = (5.802, 5.837, 5.903), stdev = 0.057
  CI (99.9%): [4.792, 6.882] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.857 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.073 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.635 ±(99.9%) 0.011 ms/op
Iteration   1: 4.508 ±(99.9%) 0.004 ms/op
Iteration   2: 4.590 ±(99.9%) 0.003 ms/op
Iteration   3: 4.554 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.551 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (4.508, 4.551, 4.590), stdev = 0.041
  CI (99.9%): [3.797, 5.304] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.443 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.005 ms/op
Iteration   1: 4.172 ±(99.9%) 0.002 ms/op
Iteration   2: 4.097 ±(99.9%) 0.003 ms/op
Iteration   3: 3.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.085 ±(99.9%) 1.689 ms/op [Average]
  (min, avg, max) = (3.988, 4.085, 4.172), stdev = 0.093
  CI (99.9%): [2.396, 5.775] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.715 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.583 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.425 ±(99.9%) 0.003 ms/op
Iteration   1: 4.369 ±(99.9%) 0.004 ms/op
Iteration   2: 4.300 ±(99.9%) 0.004 ms/op
Iteration   3: 4.291 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.320 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (4.291, 4.320, 4.369), stdev = 0.043
  CI (99.9%): [3.539, 5.101] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.090 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.971 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.529 ±(99.9%) 0.010 ms/op
Iteration   1: 5.428 ±(99.9%) 0.019 ms/op
Iteration   2: 5.418 ±(99.9%) 0.013 ms/op
Iteration   3: 5.443 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.430 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (5.418, 5.430, 5.443), stdev = 0.013
  CI (99.9%): [5.198, 5.662] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.855 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.780 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.011 ms/op
Iteration   1: 4.374 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.776 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 4.381 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.132 ms/op
                 createUser·p0.999:  11.582 ms/op
                 createUser·p0.9999: 17.577 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   3: 4.329 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   6.901 ms/op
                 createUser·p0.999:  14.945 ms/op
                 createUser·p0.9999: 19.603 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220071
  mean =      4.361 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2751 
    [ 2.500,  5.000) = 179997 
    [ 5.000,  7.500) = 35702 
    [ 7.500, 10.000) = 1037 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.054 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     20.132 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.381 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.405 ±(99.9%) 0.013 ms/op
Iteration   1: 4.162 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.620 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  10.338 ms/op
                 existUser·p0.9999: 16.995 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   2: 4.067 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.994 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   7.091 ms/op
                 existUser·p0.999:  13.015 ms/op
                 existUser·p0.9999: 18.092 ms/op
                 existUser·p1.00:   18.350 ms/op

Iteration   3: 4.192 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  9.240 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231829
  mean =      4.140 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6611 
    [ 2.500,  5.000) = 197426 
    [ 5.000,  7.500) = 26186 
    [ 7.500, 10.000) = 1280 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     11.370 ms/op
     p(99.9900) =     20.495 ms/op
     p(99.9990) =     23.040 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.323 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.649 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.012 ms/op
Iteration   1: 4.296 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.702 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  9.421 ms/op
                 getUser·p0.9999: 15.779 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   2: 4.341 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  14.975 ms/op
                 getUser·p0.9999: 17.617 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   3: 4.214 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  12.231 ms/op
                 getUser·p0.9999: 19.701 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 224117
  mean =      4.283 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2326 
    [ 2.500,  5.000) = 190673 
    [ 5.000,  7.500) = 29742 
    [ 7.500, 10.000) = 1007 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      4.186 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     20.285 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.831 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 5.890 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.376 ±(99.9%) 0.017 ms/op
Iteration   1: 5.410 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.643 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  22.173 ms/op
                 listUser·p0.9999: 25.827 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 5.400 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   6.758 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   9.961 ms/op
                 listUser·p0.999:  16.645 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 5.473 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   5.259 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.791 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  19.988 ms/op
                 listUser·p0.9999: 31.687 ms/op
                 listUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176850
  mean =      5.427 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 68601 
    [ 5.000,  7.500) = 97515 
    [ 7.500, 10.000) = 9155 
    [10.000, 12.500) = 1069 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     30.221 ms/op
     p(99.9990) =     31.719 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.430 ± 4.304  ops/ms
ClientGrpc.existUser                       thrpt       3   7.891 ± 2.225  ops/ms
ClientGrpc.getUser                         thrpt       3   7.283 ± 2.366  ops/ms
ClientGrpc.listUser                        thrpt       3   5.837 ± 1.045  ops/ms
ClientGrpc.createUser                       avgt       3   4.551 ± 0.754   ms/op
ClientGrpc.existUser                        avgt       3   4.085 ± 1.689   ms/op
ClientGrpc.getUser                          avgt       3   4.320 ± 0.781   ms/op
ClientGrpc.listUser                         avgt       3   5.430 ± 0.232   ms/op
ClientGrpc.createUser                     sample  220071   4.361 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.689           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.300           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.980           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.054           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.842           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.677           ms/op
ClientGrpc.existUser                      sample  231829   4.140 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.976           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.051           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.554           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.980           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.370           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.495           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.462           ms/op
ClientGrpc.getUser                        sample  224117   4.283 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.046           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.186           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.587           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.816           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.550           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.596           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.382           ms/op
ClientGrpc.listUser                       sample  176850   5.427 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.370           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.733           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.748           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.202           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.221           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.719           ms/op
