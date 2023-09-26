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
# Warmup Iteration   1: 3.506 ops/ms
# Warmup Iteration   2: 7.059 ops/ms
# Warmup Iteration   3: 8.597 ops/ms
Iteration   1: 8.848 ops/ms
Iteration   2: 9.084 ops/ms
Iteration   3: 8.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.976 ±(99.9%) 2.168 ops/ms [Average]
  (min, avg, max) = (8.848, 8.976, 9.084), stdev = 0.119
  CI (99.9%): [6.807, 11.144] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.398 ops/ms
# Warmup Iteration   2: 9.052 ops/ms
# Warmup Iteration   3: 9.591 ops/ms
Iteration   1: 9.706 ops/ms
Iteration   2: 9.819 ops/ms
Iteration   3: 9.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.574 ±(99.9%) 6.037 ops/ms [Average]
  (min, avg, max) = (9.197, 9.574, 9.819), stdev = 0.331
  CI (99.9%): [3.537, 15.610] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.203 ops/ms
# Warmup Iteration   2: 8.660 ops/ms
# Warmup Iteration   3: 8.838 ops/ms
Iteration   1: 9.072 ops/ms
Iteration   2: 8.893 ops/ms
Iteration   3: 8.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.964 ±(99.9%) 1.733 ops/ms [Average]
  (min, avg, max) = (8.893, 8.964, 9.072), stdev = 0.095
  CI (99.9%): [7.231, 10.697] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.668 ops/ms
# Warmup Iteration   2: 6.716 ops/ms
# Warmup Iteration   3: 6.869 ops/ms
Iteration   1: 6.860 ops/ms
Iteration   2: 7.059 ops/ms
Iteration   3: 7.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.998 ±(99.9%) 2.187 ops/ms [Average]
  (min, avg, max) = (6.860, 6.998, 7.075), stdev = 0.120
  CI (99.9%): [4.811, 9.185] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.092 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.009 ms/op
Iteration   1: 3.538 ±(99.9%) 0.010 ms/op
Iteration   2: 3.477 ±(99.9%) 0.003 ms/op
Iteration   3: 3.616 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.544 ±(99.9%) 1.264 ms/op [Average]
  (min, avg, max) = (3.477, 3.544, 3.616), stdev = 0.069
  CI (99.9%): [2.280, 4.807] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.859 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.002 ms/op
Iteration   1: 3.301 ±(99.9%) 0.003 ms/op
Iteration   2: 3.357 ±(99.9%) 0.002 ms/op
Iteration   3: 3.390 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.350 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (3.301, 3.350, 3.390), stdev = 0.045
  CI (99.9%): [2.531, 4.168] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.862 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.006 ms/op
Iteration   1: 3.583 ±(99.9%) 0.003 ms/op
Iteration   2: 3.627 ±(99.9%) 0.003 ms/op
Iteration   3: 3.498 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.570 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (3.498, 3.570, 3.627), stdev = 0.066
  CI (99.9%): [2.370, 4.769] (assumes normal distribution)


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
# Warmup Iteration   1: 6.678 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.841 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.658 ±(99.9%) 0.018 ms/op
Iteration   1: 4.639 ±(99.9%) 0.014 ms/op
Iteration   2: 4.542 ±(99.9%) 0.012 ms/op
Iteration   3: 4.386 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.522 ±(99.9%) 2.331 ms/op [Average]
  (min, avg, max) = (4.386, 4.522, 4.639), stdev = 0.128
  CI (99.9%): [2.191, 6.854] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.059 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.010 ms/op
Iteration   1: 3.650 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  11.656 ms/op
                 createUser·p0.9999: 14.553 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   2: 3.425 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.253 ms/op
                 createUser·p0.999:  8.770 ms/op
                 createUser·p0.9999: 14.745 ms/op
                 createUser·p1.00:   16.269 ms/op

Iteration   3: 3.438 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  12.024 ms/op
                 createUser·p0.9999: 18.153 ms/op
                 createUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 273977
  mean =      3.501 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 467 
    [ 1.250,  2.500) = 12141 
    [ 2.500,  3.750) = 182437 
    [ 3.750,  5.000) = 73405 
    [ 5.000,  6.250) = 3529 
    [ 6.250,  7.500) = 998 
    [ 7.500,  8.750) = 419 
    [ 8.750, 10.000) = 208 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.400 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.008 ms/op
Iteration   1: 3.422 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  8.482 ms/op
                 existUser·p0.9999: 22.411 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 3.560 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 15.958 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   3: 3.581 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  13.128 ms/op
                 existUser·p0.9999: 23.757 ms/op
                 existUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272805
  mean =      3.520 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6658 
    [ 2.500,  5.000) = 260520 
    [ 5.000,  7.500) = 4506 
    [ 7.500, 10.000) = 660 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     11.780 ms/op
     p(99.9900) =     23.229 ms/op
     p(99.9990) =     24.093 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 4.919 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.008 ms/op
Iteration   1: 3.620 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  11.234 ms/op
                 getUser·p0.9999: 16.166 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   2: 3.510 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  8.198 ms/op
                 getUser·p0.9999: 17.162 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   3: 3.524 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  13.292 ms/op
                 getUser·p0.9999: 19.951 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 270281
  mean =      3.551 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8159 
    [ 2.500,  5.000) = 257118 
    [ 5.000,  7.500) = 4254 
    [ 7.500, 10.000) = 500 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.498 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     20.401 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 5.905 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.778 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.571 ±(99.9%) 0.013 ms/op
Iteration   1: 4.449 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   6.250 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  14.993 ms/op
                 listUser·p0.9999: 17.239 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 4.582 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  14.513 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 4.672 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   8.426 ms/op
                 listUser·p0.999:  18.331 ms/op
                 listUser·p0.9999: 21.795 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 210286
  mean =      4.566 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 429 
    [ 2.500,  5.000) = 174087 
    [ 5.000,  7.500) = 32111 
    [ 7.500, 10.000) = 3025 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     21.100 ms/op
     p(99.9990) =     22.007 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.976 ± 2.168  ops/ms
ClientGrpc.existUser                       thrpt       3   9.574 ± 6.037  ops/ms
ClientGrpc.getUser                         thrpt       3   8.964 ± 1.733  ops/ms
ClientGrpc.listUser                        thrpt       3   6.998 ± 2.187  ops/ms
ClientGrpc.createUser                       avgt       3   3.544 ± 1.264   ms/op
ClientGrpc.existUser                        avgt       3   3.350 ± 0.818   ms/op
ClientGrpc.getUser                          avgt       3   3.570 ± 1.200   ms/op
ClientGrpc.listUser                         avgt       3   4.522 ± 2.331   ms/op
ClientGrpc.createUser                     sample  273977   3.501 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.833           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.043           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.055           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.481           ms/op
ClientGrpc.existUser                      sample  272805   3.520 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.749           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.661           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.780           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.229           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.183           ms/op
ClientGrpc.getUser                        sample  270281   3.551 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.807           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.636           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.498           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.366           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.513           ms/op
ClientGrpc.listUser                       sample  210286   4.566 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.270           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.100           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.479           ms/op
