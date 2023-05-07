# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ops/ms
# Warmup Iteration   2: 9.010 ops/ms
# Warmup Iteration   3: 9.964 ops/ms
Iteration   1: 10.337 ops/ms
Iteration   2: 10.553 ops/ms
Iteration   3: 10.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.420 ±(99.9%) 2.129 ops/ms [Average]
  (min, avg, max) = (10.337, 10.420, 10.553), stdev = 0.117
  CI (99.9%): [8.291, 12.548] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.070 ops/ms
# Warmup Iteration   2: 10.495 ops/ms
# Warmup Iteration   3: 10.971 ops/ms
Iteration   1: 10.983 ops/ms
Iteration   2: 11.138 ops/ms
Iteration   3: 11.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.085 ±(99.9%) 1.608 ops/ms [Average]
  (min, avg, max) = (10.983, 11.085, 11.138), stdev = 0.088
  CI (99.9%): [9.476, 12.693] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.420 ops/ms
# Warmup Iteration   2: 9.980 ops/ms
# Warmup Iteration   3: 10.474 ops/ms
Iteration   1: 10.437 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.512 ±(99.9%) 1.185 ops/ms [Average]
  (min, avg, max) = (10.437, 10.512, 10.554), stdev = 0.065
  CI (99.9%): [9.327, 11.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.053 ops/ms
# Warmup Iteration   2: 7.429 ops/ms
# Warmup Iteration   3: 7.880 ops/ms
Iteration   1: 7.952 ops/ms
Iteration   2: 7.988 ops/ms
Iteration   3: 7.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.970 ±(99.9%) 0.329 ops/ms [Average]
  (min, avg, max) = (7.952, 7.970, 7.988), stdev = 0.018
  CI (99.9%): [7.641, 8.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.454 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.004 ms/op
Iteration   1: 3.043 ±(99.9%) 0.004 ms/op
Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (3.009, 3.051, 3.100), stdev = 0.046
  CI (99.9%): [2.208, 3.893] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.003 ms/op
Iteration   1: 2.931 ±(99.9%) 0.002 ms/op
Iteration   2: 2.912 ±(99.9%) 0.002 ms/op
Iteration   3: 2.803 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.882 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (2.803, 2.882, 2.931), stdev = 0.069
  CI (99.9%): [1.617, 4.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.429 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.005 ms/op
Iteration   1: 3.036 ±(99.9%) 0.002 ms/op
Iteration   2: 3.067 ±(99.9%) 0.004 ms/op
Iteration   3: 2.999 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.034 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (2.999, 3.034, 3.067), stdev = 0.034
  CI (99.9%): [2.411, 3.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.257 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.024 ms/op
Iteration   1: 4.032 ±(99.9%) 0.060 ms/op
Iteration   2: 3.984 ±(99.9%) 0.006 ms/op
Iteration   3: 3.878 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 1.440 ms/op [Average]
  (min, avg, max) = (3.878, 3.965, 4.032), stdev = 0.079
  CI (99.9%): [2.525, 5.404] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  11.980 ms/op
                 createUser·p0.9999: 15.466 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  10.461 ms/op
                 createUser·p0.9999: 17.202 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  9.599 ms/op
                 createUser·p0.9999: 17.930 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313740
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 582 
    [ 1.250,  2.500) = 17285 
    [ 2.500,  3.750) = 278956 
    [ 3.750,  5.000) = 15616 
    [ 5.000,  6.250) = 622 
    [ 6.250,  7.500) = 134 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =     10.244 ms/op
     p(99.9900) =     17.584 ms/op
     p(99.9990) =     19.259 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.024 ms/op
                 existUser·p0.9999: 21.168 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  7.266 ms/op
                 existUser·p0.9999: 14.713 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  7.381 ms/op
                 existUser·p0.9999: 19.019 ms/op
                 existUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318971
  mean =      3.008 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22958 
    [ 2.500,  5.000) = 294765 
    [ 5.000,  7.500) = 1034 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      7.021 ms/op
     p(99.9900) =     20.549 ms/op
     p(99.9990) =     21.647 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.414 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.380 ms/op
                 getUser·p0.9999: 13.543 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.398 ms/op
                 getUser·p0.9999: 15.221 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.723 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313350
  mean =      3.064 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1238 
    [ 1.250,  2.500) = 16065 
    [ 2.500,  3.750) = 278977 
    [ 3.750,  5.000) = 15651 
    [ 5.000,  6.250) = 917 
    [ 6.250,  7.500) = 231 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.209 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.854 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.179 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
Iteration   1: 4.024 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 21.664 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 21.583 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 4.041 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.331 ms/op
                 listUser·p0.9999: 20.389 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239021
  mean =      4.017 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2303 
    [ 2.500,  5.000) = 214550 
    [ 5.000,  7.500) = 20603 
    [ 7.500, 10.000) = 1057 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     21.007 ms/op
     p(99.9990) =     22.710 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.420 ± 2.129  ops/ms
ClientGrpc.existUser                       thrpt       3  11.085 ± 1.608  ops/ms
ClientGrpc.getUser                         thrpt       3  10.512 ± 1.185  ops/ms
ClientGrpc.listUser                        thrpt       3   7.970 ± 0.329  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 0.843   ms/op
ClientGrpc.existUser                        avgt       3   2.882 ± 1.265   ms/op
ClientGrpc.getUser                          avgt       3   3.034 ± 0.623   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 1.440   ms/op
ClientGrpc.createUser                     sample  313740   3.058 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.616           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.244           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.584           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.366           ms/op
ClientGrpc.existUser                      sample  318971   3.008 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.775           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.021           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.549           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.791           ms/op
ClientGrpc.getUser                        sample  313350   3.064 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.585           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.209           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.302           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.891           ms/op
ClientGrpc.listUser                       sample  239021   4.017 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.819           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.170           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.007           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
