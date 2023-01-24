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
# Warmup Iteration   1: 4.034 ops/ms
# Warmup Iteration   2: 8.177 ops/ms
# Warmup Iteration   3: 9.174 ops/ms
Iteration   1: 9.498 ops/ms
Iteration   2: 9.248 ops/ms
Iteration   3: 9.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.255 ±(99.9%) 4.376 ops/ms [Average]
  (min, avg, max) = (9.019, 9.255, 9.498), stdev = 0.240
  CI (99.9%): [4.879, 13.630] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.449 ops/ms
# Warmup Iteration   2: 9.077 ops/ms
# Warmup Iteration   3: 9.721 ops/ms
Iteration   1: 9.567 ops/ms
Iteration   2: 9.715 ops/ms
Iteration   3: 9.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.604 ±(99.9%) 1.791 ops/ms [Average]
  (min, avg, max) = (9.530, 9.604, 9.715), stdev = 0.098
  CI (99.9%): [7.813, 11.395] (assumes normal distribution)


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
# Warmup Iteration   1: 6.206 ops/ms
# Warmup Iteration   2: 9.230 ops/ms
# Warmup Iteration   3: 9.448 ops/ms
Iteration   1: 9.420 ops/ms
Iteration   2: 9.543 ops/ms
Iteration   3: 9.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.511 ±(99.9%) 1.463 ops/ms [Average]
  (min, avg, max) = (9.420, 9.511, 9.571), stdev = 0.080
  CI (99.9%): [8.049, 10.974] (assumes normal distribution)


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
# Warmup Iteration   1: 4.950 ops/ms
# Warmup Iteration   2: 7.007 ops/ms
# Warmup Iteration   3: 7.397 ops/ms
Iteration   1: 7.528 ops/ms
Iteration   2: 7.658 ops/ms
Iteration   3: 7.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.535 ±(99.9%) 2.178 ops/ms [Average]
  (min, avg, max) = (7.419, 7.535, 7.658), stdev = 0.119
  CI (99.9%): [5.357, 9.713] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.010 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.003 ms/op
Iteration   1: 3.440 ±(99.9%) 0.003 ms/op
Iteration   2: 3.558 ±(99.9%) 0.003 ms/op
Iteration   3: 3.398 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.465 ±(99.9%) 1.514 ms/op [Average]
  (min, avg, max) = (3.398, 3.465, 3.558), stdev = 0.083
  CI (99.9%): [1.952, 4.979] (assumes normal distribution)


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.002 ms/op
Iteration   1: 3.286 ±(99.9%) 0.002 ms/op
Iteration   2: 3.298 ±(99.9%) 0.003 ms/op
Iteration   3: 3.364 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.316 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (3.286, 3.316, 3.364), stdev = 0.042
  CI (99.9%): [2.544, 4.088] (assumes normal distribution)


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.002 ms/op
Iteration   1: 3.338 ±(99.9%) 0.003 ms/op
Iteration   2: 3.493 ±(99.9%) 0.002 ms/op
Iteration   3: 3.354 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.395 ±(99.9%) 1.552 ms/op [Average]
  (min, avg, max) = (3.338, 3.395, 3.493), stdev = 0.085
  CI (99.9%): [1.843, 4.947] (assumes normal distribution)


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
# Warmup Iteration   1: 5.780 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.776 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.409 ±(99.9%) 0.009 ms/op
Iteration   1: 4.345 ±(99.9%) 0.007 ms/op
Iteration   2: 4.315 ±(99.9%) 0.009 ms/op
Iteration   3: 4.279 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.313 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (4.279, 4.313, 4.345), stdev = 0.033
  CI (99.9%): [3.711, 4.915] (assumes normal distribution)


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
# Warmup Iteration   1: 4.932 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.009 ms/op
Iteration   1: 3.420 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  8.647 ms/op
                 createUser·p0.9999: 13.188 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   2: 3.436 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  8.723 ms/op
                 createUser·p0.9999: 18.798 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   3: 3.377 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  11.179 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 281513
  mean =      3.411 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 300 
    [ 1.250,  2.500) = 15589 
    [ 2.500,  3.750) = 188041 
    [ 3.750,  5.000) = 75524 
    [ 5.000,  6.250) = 1230 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 159 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =     10.027 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     19.110 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.007 ms/op
Iteration   1: 3.195 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.216 ms/op
                 existUser·p0.99:   4.702 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 17.202 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  8.266 ms/op
                 existUser·p0.9999: 18.604 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   3: 3.272 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  6.142 ms/op
                 existUser·p0.9999: 21.798 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 298391
  mean =      3.217 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31068 
    [ 2.500,  5.000) = 266087 
    [ 5.000,  7.500) = 1019 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     19.175 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.941 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.008 ms/op
Iteration   1: 3.387 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  7.221 ms/op
                 getUser·p0.9999: 14.887 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 3.433 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  11.861 ms/op
                 getUser·p0.9999: 16.423 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   3: 3.337 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.635 ms/op
                 getUser·p0.9999: 25.913 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 283485
  mean =      3.385 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15234 
    [ 2.500,  5.000) = 266246 
    [ 5.000,  7.500) = 1675 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      7.836 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     26.061 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 5.783 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.011 ms/op
Iteration   1: 4.334 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  13.441 ms/op
                 listUser·p0.9999: 16.693 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   2: 4.335 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   4.186 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  14.881 ms/op
                 listUser·p0.9999: 16.892 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 4.286 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   4.149 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  19.870 ms/op
                 listUser·p0.9999: 25.625 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 222175
  mean =      4.318 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1358 
    [ 2.500,  5.000) = 190395 
    [ 5.000,  7.500) = 28462 
    [ 7.500, 10.000) = 1576 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      4.178 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     14.712 ms/op
     p(99.9900) =     24.169 ms/op
     p(99.9990) =     25.872 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.255 ± 4.376  ops/ms
ClientGrpc.existUser                       thrpt       3   9.604 ± 1.791  ops/ms
ClientGrpc.getUser                         thrpt       3   9.511 ± 1.463  ops/ms
ClientGrpc.listUser                        thrpt       3   7.535 ± 2.178  ops/ms
ClientGrpc.createUser                       avgt       3   3.465 ± 1.514   ms/op
ClientGrpc.existUser                        avgt       3   3.316 ± 0.772   ms/op
ClientGrpc.getUser                          avgt       3   3.395 ± 1.552   ms/op
ClientGrpc.listUser                         avgt       3   4.313 ± 0.602   ms/op
ClientGrpc.createUser                     sample  281513   3.411 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.541           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.387           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.166           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.027           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.743           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.169           ms/op
ClientGrpc.existUser                      sample  298391   3.217 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.663           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.215           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.990           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.996           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.175           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  283485   3.385 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.781           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.367           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.092           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.836           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.526           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.182           ms/op
ClientGrpc.listUser                       sample  222175   4.318 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.847           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.178           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.712           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.169           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919           ms/op
