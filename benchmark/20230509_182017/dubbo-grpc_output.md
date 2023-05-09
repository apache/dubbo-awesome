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
# Warmup Iteration   1: 3.485 ops/ms
# Warmup Iteration   2: 8.232 ops/ms
# Warmup Iteration   3: 9.129 ops/ms
Iteration   1: 9.463 ops/ms
Iteration   2: 9.246 ops/ms
Iteration   3: 9.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.367 ±(99.9%) 2.017 ops/ms [Average]
  (min, avg, max) = (9.246, 9.367, 9.463), stdev = 0.111
  CI (99.9%): [7.350, 11.383] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.309 ops/ms
# Warmup Iteration   2: 9.572 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.815 ops/ms
Iteration   2: 10.302 ops/ms
Iteration   3: 10.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.439 ±(99.9%) 6.006 ops/ms [Average]
  (min, avg, max) = (10.201, 10.439, 10.815), stdev = 0.329
  CI (99.9%): [4.433, 16.446] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 5.302 ops/ms
# Warmup Iteration   2: 8.011 ops/ms
# Warmup Iteration   3: 8.458 ops/ms
Iteration   1: 8.836 ops/ms
Iteration   2: 8.802 ops/ms
Iteration   3: 8.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.791 ±(99.9%) 0.935 ops/ms [Average]
  (min, avg, max) = (8.735, 8.791, 8.836), stdev = 0.051
  CI (99.9%): [7.856, 9.727] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.630 ops/ms
# Warmup Iteration   2: 6.061 ops/ms
# Warmup Iteration   3: 6.602 ops/ms
Iteration   1: 6.584 ops/ms
Iteration   2: 6.443 ops/ms
Iteration   3: 6.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.553 ±(99.9%) 1.777 ops/ms [Average]
  (min, avg, max) = (6.443, 6.553, 6.630), stdev = 0.097
  CI (99.9%): [4.776, 8.329] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.108 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.003 ms/op
Iteration   1: 3.448 ±(99.9%) 0.002 ms/op
Iteration   2: 3.425 ±(99.9%) 0.002 ms/op
Iteration   3: 3.475 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.449 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.425, 3.449, 3.475), stdev = 0.025
  CI (99.9%): [2.989, 3.910] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.002 ms/op
Iteration   1: 3.272 ±(99.9%) 0.002 ms/op
Iteration   2: 3.203 ±(99.9%) 0.002 ms/op
Iteration   3: 3.174 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.216 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (3.174, 3.216, 3.272), stdev = 0.050
  CI (99.9%): [2.304, 4.129] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.790 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.002 ms/op
Iteration   1: 3.379 ±(99.9%) 0.003 ms/op
Iteration   2: 3.306 ±(99.9%) 0.002 ms/op
Iteration   3: 3.323 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.336 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (3.306, 3.336, 3.379), stdev = 0.038
  CI (99.9%): [2.639, 4.033] (assumes normal distribution)


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
# Warmup Iteration   1: 6.571 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.592 ±(99.9%) 0.016 ms/op
Iteration   1: 4.456 ±(99.9%) 0.012 ms/op
Iteration   2: 4.442 ±(99.9%) 0.014 ms/op
Iteration   3: 4.480 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.459 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (4.442, 4.459, 4.480), stdev = 0.019
  CI (99.9%): [4.106, 4.813] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.219 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.009 ms/op
Iteration   1: 3.496 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  8.549 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   2: 3.573 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 26.855 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  9.269 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 276740
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14107 
    [ 2.500,  5.000) = 254021 
    [ 5.000,  7.500) = 7832 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     26.487 ms/op
     p(99.9990) =     27.631 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.683 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.008 ms/op
Iteration   1: 3.114 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  7.231 ms/op
                 existUser·p0.9999: 14.336 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  8.197 ms/op
                 existUser·p0.9999: 13.596 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 3.102 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  10.810 ms/op
                 existUser·p0.9999: 29.514 ms/op
                 existUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307378
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28724 
    [ 2.500,  5.000) = 275504 
    [ 5.000,  7.500) = 2737 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =      8.071 ms/op
     p(99.9900) =     29.074 ms/op
     p(99.9990) =     29.716 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.010 ms/op
Iteration   1: 3.415 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  8.525 ms/op
                 getUser·p0.9999: 23.667 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.412 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  11.958 ms/op
                 getUser·p0.9999: 26.112 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.369 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  7.439 ms/op
                 getUser·p0.9999: 23.938 ms/op
                 getUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 282284
  mean =      3.398 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12151 
    [ 2.500,  5.000) = 264259 
    [ 5.000,  7.500) = 5443 
    [ 7.500, 10.000) = 239 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      8.247 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 5.850 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.527 ±(99.9%) 0.015 ms/op
Iteration   1: 4.454 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  12.965 ms/op
                 listUser·p0.9999: 17.813 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   2: 4.498 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 27.875 ms/op
                 listUser·p1.00:   28.279 ms/op

Iteration   3: 4.515 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.562 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 28.603 ms/op
                 listUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213987
  mean =      4.489 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1096 
    [ 2.500,  5.000) = 167448 
    [ 5.000,  7.500) = 41677 
    [ 7.500, 10.000) = 3044 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.012 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.751 ms/op
     p(95.0000) =      6.488 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     27.925 ms/op
     p(99.9990) =     28.859 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.367 ± 2.017  ops/ms
ClientGrpc.existUser                       thrpt       3  10.439 ± 6.006  ops/ms
ClientGrpc.getUser                         thrpt       3   8.791 ± 0.935  ops/ms
ClientGrpc.listUser                        thrpt       3   6.553 ± 1.777  ops/ms
ClientGrpc.createUser                       avgt       3   3.449 ± 0.460   ms/op
ClientGrpc.existUser                        avgt       3   3.216 ± 0.913   ms/op
ClientGrpc.getUser                          avgt       3   3.336 ± 0.697   ms/op
ClientGrpc.listUser                         avgt       3   4.459 ± 0.354   ms/op
ClientGrpc.createUser                     sample  276740   3.468 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.815           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.371           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.487           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.754           ms/op
ClientGrpc.existUser                      sample  307378   3.123 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.589           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.052           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.014           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.071           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.074           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.753           ms/op
ClientGrpc.getUser                        sample  282284   3.398 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.897           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.310           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.247           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.921           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.313           ms/op
ClientGrpc.listUser                       sample  213987   4.489 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.012           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.284           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.488           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.941           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.925           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.967           ms/op
