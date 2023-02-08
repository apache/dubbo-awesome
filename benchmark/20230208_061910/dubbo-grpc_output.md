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
# Warmup Iteration   1: 3.746 ops/ms
# Warmup Iteration   2: 8.419 ops/ms
# Warmup Iteration   3: 9.431 ops/ms
Iteration   1: 9.606 ops/ms
Iteration   2: 9.787 ops/ms
Iteration   3: 9.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.791 ±(99.9%) 3.423 ops/ms [Average]
  (min, avg, max) = (9.606, 9.791, 9.981), stdev = 0.188
  CI (99.9%): [6.368, 13.214] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.344 ops/ms
# Warmup Iteration   2: 9.849 ops/ms
# Warmup Iteration   3: 9.936 ops/ms
Iteration   1: 10.065 ops/ms
Iteration   2: 10.060 ops/ms
Iteration   3: 9.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.990 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (9.847, 9.990, 10.065), stdev = 0.125
  CI (99.9%): [7.717, 12.263] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.673 ops/ms
# Warmup Iteration   2: 9.409 ops/ms
# Warmup Iteration   3: 10.157 ops/ms
Iteration   1: 9.857 ops/ms
Iteration   2: 9.775 ops/ms
Iteration   3: 9.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.804 ±(99.9%) 0.844 ops/ms [Average]
  (min, avg, max) = (9.775, 9.804, 9.857), stdev = 0.046
  CI (99.9%): [8.960, 10.648] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.245 ops/ms
# Warmup Iteration   2: 7.211 ops/ms
# Warmup Iteration   3: 7.570 ops/ms
Iteration   1: 7.542 ops/ms
Iteration   2: 7.601 ops/ms
Iteration   3: 7.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.585 ±(99.9%) 0.686 ops/ms [Average]
  (min, avg, max) = (7.542, 7.585, 7.612), stdev = 0.038
  CI (99.9%): [6.900, 8.271] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.201 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.002 ms/op
Iteration   1: 3.231 ±(99.9%) 0.002 ms/op
Iteration   2: 3.272 ±(99.9%) 0.002 ms/op
Iteration   3: 3.232 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.245 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.231, 3.245, 3.272), stdev = 0.024
  CI (99.9%): [2.813, 3.676] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
Iteration   3: 3.070 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.137 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.070, 3.137, 3.192), stdev = 0.062
  CI (99.9%): [2.005, 4.268] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.002 ms/op
Iteration   1: 3.224 ±(99.9%) 0.003 ms/op
Iteration   2: 3.225 ±(99.9%) 0.002 ms/op
Iteration   3: 3.315 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.255 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (3.224, 3.255, 3.315), stdev = 0.052
  CI (99.9%): [2.302, 4.207] (assumes normal distribution)


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
# Warmup Iteration   1: 4.876 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.530 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.015 ms/op
Iteration   1: 4.414 ±(99.9%) 0.010 ms/op
Iteration   2: 4.274 ±(99.9%) 0.007 ms/op
Iteration   3: 4.225 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.304 ±(99.9%) 1.794 ms/op [Average]
  (min, avg, max) = (4.225, 4.304, 4.414), stdev = 0.098
  CI (99.9%): [2.511, 6.098] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.313 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
Iteration   1: 3.338 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  8.471 ms/op
                 createUser·p0.9999: 23.574 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   2: 3.378 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.353 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  11.344 ms/op
                 createUser·p0.9999: 18.859 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.367 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   4.866 ms/op
                 createUser·p0.999:  13.320 ms/op
                 createUser·p0.9999: 20.250 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 285616
  mean =      3.361 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12099 
    [ 2.500,  5.000) = 271867 
    [ 5.000,  7.500) = 1217 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     22.489 ms/op
     p(99.9990) =     23.898 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.392 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
Iteration   1: 3.251 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  6.111 ms/op
                 existUser·p0.9999: 12.162 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.389 ms/op
                 existUser·p0.9999: 23.429 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.163 ms/op
                 existUser·p0.9999: 15.339 ms/op
                 existUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 296685
  mean =      3.234 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15512 
    [ 2.500,  5.000) = 280156 
    [ 5.000,  7.500) = 737 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.397 ms/op
     p(99.9900) =     20.032 ms/op
     p(99.9990) =     23.627 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.007 ms/op
Iteration   1: 3.246 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.639 ms/op
                 getUser·p0.9999: 11.998 ms/op
                 getUser·p1.00:   12.485 ms/op

Iteration   2: 3.250 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.340 ms/op
                 getUser·p0.9999: 13.533 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   3: 3.276 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  9.765 ms/op
                 getUser·p0.9999: 15.978 ms/op
                 getUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 294518
  mean =      3.257 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 619 
    [ 1.250,  2.500) = 13235 
    [ 2.500,  3.750) = 237612 
    [ 3.750,  5.000) = 41353 
    [ 5.000,  6.250) = 923 
    [ 6.250,  7.500) = 455 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.786 ms/op
     p(99.9900) =     14.993 ms/op
     p(99.9990) =     16.321 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 5.108 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.011 ms/op
Iteration   1: 4.154 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.279 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 18.851 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 4.345 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.346 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.801 ms/op
                 listUser·p0.999:  15.543 ms/op
                 listUser·p0.9999: 18.535 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.951 ms/op
                 listUser·p0.9999: 30.263 ms/op
                 listUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229443
  mean =      4.181 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2467 
    [ 2.500,  5.000) = 191153 
    [ 5.000,  7.500) = 33760 
    [ 7.500, 10.000) = 1445 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.279 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     14.460 ms/op
     p(99.9900) =     28.772 ms/op
     p(99.9990) =     31.284 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.791 ± 3.423  ops/ms
ClientGrpc.existUser                       thrpt       3   9.990 ± 2.273  ops/ms
ClientGrpc.getUser                         thrpt       3   9.804 ± 0.844  ops/ms
ClientGrpc.listUser                        thrpt       3   7.585 ± 0.686  ops/ms
ClientGrpc.createUser                       avgt       3   3.245 ± 0.431   ms/op
ClientGrpc.existUser                        avgt       3   3.137 ± 1.132   ms/op
ClientGrpc.getUser                          avgt       3   3.255 ± 0.953   ms/op
ClientGrpc.listUser                         avgt       3   4.304 ± 1.794   ms/op
ClientGrpc.createUser                     sample  285616   3.361 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.613           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.334           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.404           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.489           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.216           ms/op
ClientGrpc.existUser                      sample  296685   3.234 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.455           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.215           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.397           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.032           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.691           ms/op
ClientGrpc.getUser                        sample  294518   3.257 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.793           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.236           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.112           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.786           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.993           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.450           ms/op
ClientGrpc.listUser                       sample  229443   4.181 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.279           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.002           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.460           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.772           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.293           ms/op
