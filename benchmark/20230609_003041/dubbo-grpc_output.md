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
# Warmup Iteration   1: 2.234 ops/ms
# Warmup Iteration   2: 4.962 ops/ms
# Warmup Iteration   3: 6.886 ops/ms
Iteration   1: 7.119 ops/ms
Iteration   2: 7.188 ops/ms
Iteration   3: 7.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.121 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (7.055, 7.121, 7.188), stdev = 0.067
  CI (99.9%): [5.906, 8.336] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.584 ops/ms
# Warmup Iteration   2: 6.984 ops/ms
# Warmup Iteration   3: 7.851 ops/ms
Iteration   1: 7.902 ops/ms
Iteration   2: 7.796 ops/ms
Iteration   3: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.948 ±(99.9%) 3.278 ops/ms [Average]
  (min, avg, max) = (7.796, 7.948, 8.146), stdev = 0.180
  CI (99.9%): [4.670, 11.226] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.447 ops/ms
# Warmup Iteration   2: 6.528 ops/ms
# Warmup Iteration   3: 6.959 ops/ms
Iteration   1: 7.090 ops/ms
Iteration   2: 7.107 ops/ms
Iteration   3: 7.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.164 ±(99.9%) 2.066 ops/ms [Average]
  (min, avg, max) = (7.090, 7.164, 7.294), stdev = 0.113
  CI (99.9%): [5.098, 9.230] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 4.955 ops/ms
# Warmup Iteration   3: 5.535 ops/ms
Iteration   1: 5.625 ops/ms
Iteration   2: 5.540 ops/ms
Iteration   3: 5.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.595 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (5.540, 5.595, 5.625), stdev = 0.048
  CI (99.9%): [4.722, 6.468] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.953 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.541 ±(99.9%) 0.004 ms/op
Iteration   1: 4.488 ±(99.9%) 0.006 ms/op
Iteration   2: 4.327 ±(99.9%) 0.004 ms/op
Iteration   3: 4.387 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.400 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (4.327, 4.400, 4.488), stdev = 0.081
  CI (99.9%): [2.919, 5.882] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.398 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.565 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.367 ±(99.9%) 0.003 ms/op
Iteration   1: 4.078 ±(99.9%) 0.003 ms/op
Iteration   2: 4.172 ±(99.9%) 0.002 ms/op
Iteration   3: 4.266 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.172 ±(99.9%) 1.714 ms/op [Average]
  (min, avg, max) = (4.078, 4.172, 4.266), stdev = 0.094
  CI (99.9%): [2.458, 5.886] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.739 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.540 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.003 ms/op
Iteration   1: 4.369 ±(99.9%) 0.005 ms/op
Iteration   2: 4.399 ±(99.9%) 0.003 ms/op
Iteration   3: 4.375 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.381 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (4.369, 4.381, 4.399), stdev = 0.016
  CI (99.9%): [4.085, 4.676] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.694 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 6.162 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.721 ±(99.9%) 0.021 ms/op
Iteration   1: 5.628 ±(99.9%) 0.016 ms/op
Iteration   2: 5.735 ±(99.9%) 0.010 ms/op
Iteration   3: 5.733 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.699 ±(99.9%) 1.111 ms/op [Average]
  (min, avg, max) = (5.628, 5.699, 5.735), stdev = 0.061
  CI (99.9%): [4.588, 6.809] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.768 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.819 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.535 ±(99.9%) 0.013 ms/op
Iteration   1: 4.450 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.455 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  11.641 ms/op
                 createUser·p0.9999: 22.708 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 4.465 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.434 ms/op
                 createUser·p0.999:  13.550 ms/op
                 createUser·p0.9999: 28.945 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 4.490 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.275 ms/op
                 createUser·p0.999:  14.647 ms/op
                 createUser·p0.9999: 26.861 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214817
  mean =      4.468 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1917 
    [ 2.500,  5.000) = 165618 
    [ 5.000,  7.500) = 45354 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     14.293 ms/op
     p(99.9900) =     27.444 ms/op
     p(99.9990) =     29.116 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.288 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.011 ms/op
Iteration   1: 4.215 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   4.125 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  13.140 ms/op
                 existUser·p0.9999: 18.265 ms/op
                 existUser·p1.00:   18.809 ms/op

Iteration   2: 4.145 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   4.055 ms/op
                 existUser·p0.90:   4.989 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  12.129 ms/op
                 existUser·p0.9999: 19.664 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 4.073 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   4.915 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  8.797 ms/op
                 existUser·p0.9999: 21.107 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231620
  mean =      4.144 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4447 
    [ 2.500,  5.000) = 201732 
    [ 5.000,  7.500) = 24100 
    [ 7.500, 10.000) = 1064 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     11.459 ms/op
     p(99.9900) =     20.540 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.859 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.012 ms/op
Iteration   1: 4.385 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 16.866 ms/op
                 getUser·p1.00:   17.400 ms/op

Iteration   2: 4.414 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  13.202 ms/op
                 getUser·p0.9999: 18.932 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 4.331 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   6.846 ms/op
                 getUser·p0.999:  15.000 ms/op
                 getUser·p0.9999: 22.900 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219266
  mean =      4.376 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2028 
    [ 2.500,  5.000) = 179103 
    [ 5.000,  7.500) = 36321 
    [ 7.500, 10.000) = 1385 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     13.070 ms/op
     p(99.9900) =     22.222 ms/op
     p(99.9990) =     23.740 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.793 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.601 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.713 ±(99.9%) 0.022 ms/op
Iteration   1: 5.611 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  25.887 ms/op
                 listUser·p0.9999: 29.400 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   2: 5.571 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  30.245 ms/op
                 listUser·p0.9999: 32.572 ms/op
                 listUser·p1.00:   34.537 ms/op

Iteration   3: 5.787 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.356 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  29.884 ms/op
                 listUser·p0.9999: 36.731 ms/op
                 listUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169714
  mean =      5.655 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 125 
    [ 2.500,  5.000) = 55061 
    [ 5.000,  7.500) = 100118 
    [ 7.500, 10.000) = 12089 
    [10.000, 12.500) = 1645 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.225 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     27.502 ms/op
     p(99.9900) =     35.916 ms/op
     p(99.9990) =     37.258 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.121 ± 1.215  ops/ms
ClientGrpc.existUser                       thrpt       3   7.948 ± 3.278  ops/ms
ClientGrpc.getUser                         thrpt       3   7.164 ± 2.066  ops/ms
ClientGrpc.listUser                        thrpt       3   5.595 ± 0.873  ops/ms
ClientGrpc.createUser                       avgt       3   4.400 ± 1.482   ms/op
ClientGrpc.existUser                        avgt       3   4.172 ± 1.714   ms/op
ClientGrpc.getUser                          avgt       3   4.381 ± 0.296   ms/op
ClientGrpc.listUser                         avgt       3   5.699 ± 1.111   ms/op
ClientGrpc.createUser                     sample  214817   4.468 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.912           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.505           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.906           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.348           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.293           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.444           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.327           ms/op
ClientGrpc.existUser                      sample  231620   4.144 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.946           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.054           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.685           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.459           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.540           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.398           ms/op
ClientGrpc.getUser                        sample  219266   4.376 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.920           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.816           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.274           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.070           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.222           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.019           ms/op
ClientGrpc.listUser                       sample  169714   5.655 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.227           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.225           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.453           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          27.502           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.916           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.487           ms/op
