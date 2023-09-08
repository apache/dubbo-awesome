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
# Warmup Iteration   1: 2.247 ops/ms
# Warmup Iteration   2: 5.394 ops/ms
# Warmup Iteration   3: 6.845 ops/ms
Iteration   1: 7.206 ops/ms
Iteration   2: 7.315 ops/ms
Iteration   3: 7.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.276 ±(99.9%) 1.109 ops/ms [Average]
  (min, avg, max) = (7.206, 7.276, 7.315), stdev = 0.061
  CI (99.9%): [6.167, 8.384] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ops/ms
# Warmup Iteration   2: 6.882 ops/ms
# Warmup Iteration   3: 7.235 ops/ms
Iteration   1: 7.284 ops/ms
Iteration   2: 7.626 ops/ms
Iteration   3: 7.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.451 ±(99.9%) 3.127 ops/ms [Average]
  (min, avg, max) = (7.284, 7.451, 7.626), stdev = 0.171
  CI (99.9%): [4.325, 10.578] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.469 ops/ms
# Warmup Iteration   2: 6.264 ops/ms
# Warmup Iteration   3: 6.432 ops/ms
Iteration   1: 6.768 ops/ms
Iteration   2: 6.780 ops/ms
Iteration   3: 6.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.801 ±(99.9%) 0.833 ops/ms [Average]
  (min, avg, max) = (6.768, 6.801, 6.853), stdev = 0.046
  CI (99.9%): [5.968, 7.634] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.369 ops/ms
# Warmup Iteration   2: 4.872 ops/ms
# Warmup Iteration   3: 4.948 ops/ms
Iteration   1: 5.243 ops/ms
Iteration   2: 5.229 ops/ms
Iteration   3: 5.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.254 ±(99.9%) 0.579 ops/ms [Average]
  (min, avg, max) = (5.229, 5.254, 5.290), stdev = 0.032
  CI (99.9%): [4.676, 5.833] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.740 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.766 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.501 ±(99.9%) 0.004 ms/op
Iteration   1: 4.357 ±(99.9%) 0.005 ms/op
Iteration   2: 4.314 ±(99.9%) 0.003 ms/op
Iteration   3: 4.502 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.391 ±(99.9%) 1.797 ms/op [Average]
  (min, avg, max) = (4.314, 4.391, 4.502), stdev = 0.099
  CI (99.9%): [2.594, 6.189] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.275 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.266 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.003 ms/op
Iteration   1: 4.137 ±(99.9%) 0.003 ms/op
Iteration   2: 4.045 ±(99.9%) 0.004 ms/op
Iteration   3: 3.947 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.043 ±(99.9%) 1.732 ms/op [Average]
  (min, avg, max) = (3.947, 4.043, 4.137), stdev = 0.095
  CI (99.9%): [2.310, 5.775] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.515 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.418 ±(99.9%) 0.009 ms/op
Iteration   1: 4.305 ±(99.9%) 0.021 ms/op
Iteration   2: 4.343 ±(99.9%) 0.002 ms/op
Iteration   3: 4.266 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.305 ±(99.9%) 0.703 ms/op [Average]
  (min, avg, max) = (4.266, 4.305, 4.343), stdev = 0.039
  CI (99.9%): [3.602, 5.008] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 7.663 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 6.293 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.680 ±(99.9%) 0.029 ms/op
Iteration   1: 5.644 ±(99.9%) 0.016 ms/op
Iteration   2: 5.596 ±(99.9%) 0.018 ms/op
Iteration   3: 5.614 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.618 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (5.596, 5.618, 5.644), stdev = 0.024
  CI (99.9%): [5.176, 6.060] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.350 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.013 ms/op
Iteration   1: 4.337 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   4.190 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   8.110 ms/op
                 createUser·p0.999:  13.402 ms/op
                 createUser·p0.9999: 21.295 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   2: 4.246 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.166 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  14.151 ms/op
                 createUser·p0.9999: 24.163 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   3: 4.363 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  16.707 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222373
  mean =      4.315 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4979 
    [ 2.500,  5.000) = 175368 
    [ 5.000,  7.500) = 39745 
    [ 7.500, 10.000) = 1652 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     15.585 ms/op
     p(99.9900) =     27.993 ms/op
     p(99.9990) =     29.333 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.146 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.012 ms/op
Iteration   1: 4.026 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.085 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 22.581 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.980 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   7.225 ms/op
                 existUser·p0.999:  12.314 ms/op
                 existUser·p0.9999: 19.447 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  12.489 ms/op
                 existUser·p0.9999: 18.774 ms/op
                 existUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 240577
  mean =      3.990 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6350 
    [ 2.500,  5.000) = 211706 
    [ 5.000,  7.500) = 20813 
    [ 7.500, 10.000) = 1210 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     19.719 ms/op
     p(99.9990) =     22.884 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.665 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.618 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.321 ±(99.9%) 0.012 ms/op
Iteration   1: 4.510 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.418 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.339 ms/op
                 getUser·p0.999:  14.537 ms/op
                 getUser·p0.9999: 16.899 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   2: 4.787 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   4.563 ms/op
                 getUser·p0.90:   6.128 ms/op
                 getUser·p0.95:   6.849 ms/op
                 getUser·p0.99:   8.634 ms/op
                 getUser·p0.999:  14.848 ms/op
                 getUser·p0.9999: 21.244 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   3: 4.754 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   6.578 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  12.906 ms/op
                 getUser·p0.9999: 21.692 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 205133
  mean =      4.681 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1941 
    [ 2.500,  5.000) = 143363 
    [ 5.000,  7.500) = 55340 
    [ 7.500, 10.000) = 3677 
    [10.000, 12.500) = 448 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     13.941 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     22.148 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.945 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 6.714 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.247 ±(99.9%) 0.026 ms/op
Iteration   1: 5.820 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.848 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  17.011 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 5.893 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.043 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 22.805 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 6.139 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   8.044 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  23.560 ms/op
                 listUser·p0.9999: 29.648 ms/op
                 listUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161429
  mean =      5.948 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 39271 
    [ 5.000,  7.500) = 101373 
    [ 7.500, 10.000) = 16671 
    [10.000, 12.500) = 3090 
    [12.500, 15.000) = 605 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      5.620 ms/op
     p(90.0000) =      7.897 ms/op
     p(95.0000) =      8.929 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     19.122 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     31.566 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.276 ± 1.109  ops/ms
ClientGrpc.existUser                       thrpt       3   7.451 ± 3.127  ops/ms
ClientGrpc.getUser                         thrpt       3   6.801 ± 0.833  ops/ms
ClientGrpc.listUser                        thrpt       3   5.254 ± 0.579  ops/ms
ClientGrpc.createUser                       avgt       3   4.391 ± 1.797   ms/op
ClientGrpc.existUser                        avgt       3   4.043 ± 1.732   ms/op
ClientGrpc.getUser                          avgt       3   4.305 ± 0.703   ms/op
ClientGrpc.listUser                         avgt       3   5.618 ± 0.442   ms/op
ClientGrpc.createUser                     sample  222373   4.315 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.102           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.537           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.585           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.993           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.048           ms/op
ClientGrpc.existUser                      sample  240577   3.990 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.924           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.956           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.971           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.304           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.719           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.003           ms/op
ClientGrpc.getUser                        sample  205133   4.681 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.418           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.915           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.545           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.520           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.941           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.430           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.184           ms/op
ClientGrpc.listUser                       sample  161429   5.948 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.501           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.897           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.929           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.567           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.295           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.687           ms/op
