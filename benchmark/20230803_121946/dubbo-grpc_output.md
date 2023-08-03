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
# Warmup Iteration   1: 3.661 ops/ms
# Warmup Iteration   2: 8.336 ops/ms
# Warmup Iteration   3: 9.920 ops/ms
Iteration   1: 10.122 ops/ms
Iteration   2: 10.313 ops/ms
Iteration   3: 10.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.203 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (10.122, 10.203, 10.313), stdev = 0.099
  CI (99.9%): [8.403, 12.002] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.603 ops/ms
# Warmup Iteration   2: 10.312 ops/ms
# Warmup Iteration   3: 10.895 ops/ms
Iteration   1: 10.977 ops/ms
Iteration   2: 10.814 ops/ms
Iteration   3: 11.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.000 ±(99.9%) 3.608 ops/ms [Average]
  (min, avg, max) = (10.814, 11.000, 11.208), stdev = 0.198
  CI (99.9%): [7.392, 14.608] (assumes normal distribution)


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
# Warmup Iteration   1: 6.826 ops/ms
# Warmup Iteration   2: 10.151 ops/ms
# Warmup Iteration   3: 10.437 ops/ms
Iteration   1: 10.581 ops/ms
Iteration   2: 10.588 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.603 ±(99.9%) 0.583 ops/ms [Average]
  (min, avg, max) = (10.581, 10.603, 10.639), stdev = 0.032
  CI (99.9%): [10.020, 11.185] (assumes normal distribution)


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
# Warmup Iteration   1: 5.433 ops/ms
# Warmup Iteration   2: 7.618 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 7.780 ops/ms
Iteration   2: 8.047 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.935 ±(99.9%) 2.523 ops/ms [Average]
  (min, avg, max) = (7.780, 7.935, 8.047), stdev = 0.138
  CI (99.9%): [5.412, 10.458] (assumes normal distribution)


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.002 ms/op
Iteration   1: 3.089 ±(99.9%) 0.003 ms/op
Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
Iteration   3: 3.070 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.083 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (3.070, 3.083, 3.091), stdev = 0.012
  CI (99.9%): [2.873, 3.293] (assumes normal distribution)


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 2.912 ±(99.9%) 0.002 ms/op
Iteration   2: 2.893 ±(99.9%) 0.002 ms/op
Iteration   3: 2.971 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.925 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (2.893, 2.925, 2.971), stdev = 0.040
  CI (99.9%): [2.187, 3.663] (assumes normal distribution)


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.002 ms/op
Iteration   1: 3.096 ±(99.9%) 0.003 ms/op
Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
Iteration   3: 3.065 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.090 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (3.065, 3.090, 3.108), stdev = 0.022
  CI (99.9%): [2.684, 3.496] (assumes normal distribution)


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
# Warmup Iteration   1: 5.455 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.017 ms/op
Iteration   1: 4.002 ±(99.9%) 0.010 ms/op
Iteration   2: 4.000 ±(99.9%) 0.010 ms/op
Iteration   3: 4.021 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.008 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (4.000, 4.008, 4.021), stdev = 0.012
  CI (99.9%): [3.794, 4.221] (assumes normal distribution)


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
# Warmup Iteration   1: 4.340 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 15.112 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 15.383 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.302 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  9.423 ms/op
                 createUser·p0.9999: 17.616 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314123
  mean =      3.055 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 707 
    [ 1.250,  2.500) = 15062 
    [ 2.500,  3.750) = 283486 
    [ 3.750,  5.000) = 13125 
    [ 5.000,  6.250) = 730 
    [ 6.250,  7.500) = 416 
    [ 7.500,  8.750) = 237 
    [ 8.750, 10.000) = 129 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.302 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     16.507 ms/op
     p(99.9990) =     17.915 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.006 ms/op
Iteration   1: 2.927 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  8.549 ms/op
                 existUser·p0.9999: 13.829 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   2: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 14.289 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  8.745 ms/op
                 existUser·p0.9999: 15.915 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327052
  mean =      2.936 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 700 
    [ 1.250,  2.500) = 33617 
    [ 2.500,  3.750) = 284029 
    [ 3.750,  5.000) = 7322 
    [ 5.000,  6.250) = 562 
    [ 6.250,  7.500) = 267 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.617 ms/op
     p(99.9900) =     15.455 ms/op
     p(99.9990) =     16.980 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.849 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.184 ms/op
                 getUser·p0.9999: 13.435 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.655 ms/op
                 getUser·p0.9999: 21.579 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  7.919 ms/op
                 getUser·p0.9999: 28.279 ms/op
                 getUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312914
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19426 
    [ 2.500,  5.000) = 291229 
    [ 5.000,  7.500) = 1857 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      8.063 ms/op
     p(99.9900) =     26.336 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 5.829 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.012 ms/op
Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  13.925 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   2: 3.995 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.883 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  17.332 ms/op
                 listUser·p0.9999: 28.573 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   3: 4.016 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  17.030 ms/op
                 listUser·p0.9999: 30.015 ms/op
                 listUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239769
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2325 
    [ 2.500,  5.000) = 211985 
    [ 5.000,  7.500) = 23502 
    [ 7.500, 10.000) = 1436 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     16.715 ms/op
     p(99.9900) =     28.740 ms/op
     p(99.9990) =     30.304 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.203 ± 1.799  ops/ms
ClientGrpc.existUser                       thrpt       3  11.000 ± 3.608  ops/ms
ClientGrpc.getUser                         thrpt       3  10.603 ± 0.583  ops/ms
ClientGrpc.listUser                        thrpt       3   7.935 ± 2.523  ops/ms
ClientGrpc.createUser                       avgt       3   3.083 ± 0.210   ms/op
ClientGrpc.existUser                        avgt       3   2.925 ± 0.738   ms/op
ClientGrpc.getUser                          avgt       3   3.090 ± 0.406   ms/op
ClientGrpc.listUser                         avgt       3   4.008 ± 0.214   ms/op
ClientGrpc.createUser                     sample  314123   3.055 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.302           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.060           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.507           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.055           ms/op
ClientGrpc.existUser                      sample  327052   2.936 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.751           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.617           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.455           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.203           ms/op
ClientGrpc.getUser                        sample  312914   3.067 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.611           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.063           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.336           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.475           ms/op
ClientGrpc.listUser                       sample  239769   4.004 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.862           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.715           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.740           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.409           ms/op
