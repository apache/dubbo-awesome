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
# Warmup Iteration   1: 2.270 ops/ms
# Warmup Iteration   2: 5.344 ops/ms
# Warmup Iteration   3: 6.806 ops/ms
Iteration   1: 6.901 ops/ms
Iteration   2: 6.987 ops/ms
Iteration   3: 7.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.006 ±(99.9%) 2.114 ops/ms [Average]
  (min, avg, max) = (6.901, 7.006, 7.131), stdev = 0.116
  CI (99.9%): [4.892, 9.121] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.499 ops/ms
# Warmup Iteration   2: 7.117 ops/ms
# Warmup Iteration   3: 7.430 ops/ms
Iteration   1: 7.706 ops/ms
Iteration   2: 7.479 ops/ms
Iteration   3: 7.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.645 ±(99.9%) 2.656 ops/ms [Average]
  (min, avg, max) = (7.479, 7.645, 7.749), stdev = 0.146
  CI (99.9%): [4.989, 10.301] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ops/ms
# Warmup Iteration   2: 6.688 ops/ms
# Warmup Iteration   3: 7.005 ops/ms
Iteration   1: 7.205 ops/ms
Iteration   2: 7.478 ops/ms
Iteration   3: 7.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.292 ±(99.9%) 2.949 ops/ms [Average]
  (min, avg, max) = (7.192, 7.292, 7.478), stdev = 0.162
  CI (99.9%): [4.343, 10.240] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.404 ops/ms
# Warmup Iteration   2: 5.138 ops/ms
# Warmup Iteration   3: 5.576 ops/ms
Iteration   1: 5.558 ops/ms
Iteration   2: 5.804 ops/ms
Iteration   3: 5.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.614 ±(99.9%) 3.095 ops/ms [Average]
  (min, avg, max) = (5.479, 5.614, 5.804), stdev = 0.170
  CI (99.9%): [2.519, 8.709] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.809 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.805 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.560 ±(99.9%) 0.004 ms/op
Iteration   1: 4.519 ±(99.9%) 0.002 ms/op
Iteration   2: 4.627 ±(99.9%) 0.003 ms/op
Iteration   3: 4.449 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.532 ±(99.9%) 1.635 ms/op [Average]
  (min, avg, max) = (4.449, 4.532, 4.627), stdev = 0.090
  CI (99.9%): [2.896, 6.167] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.344 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.004 ms/op
Iteration   1: 4.155 ±(99.9%) 0.003 ms/op
Iteration   2: 4.323 ±(99.9%) 0.004 ms/op
Iteration   3: 4.174 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.218 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (4.155, 4.218, 4.323), stdev = 0.092
  CI (99.9%): [2.538, 5.898] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.953 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.770 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.520 ±(99.9%) 0.012 ms/op
Iteration   1: 4.457 ±(99.9%) 0.004 ms/op
Iteration   2: 4.479 ±(99.9%) 0.004 ms/op
Iteration   3: 4.548 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.495 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (4.457, 4.495, 4.548), stdev = 0.048
  CI (99.9%): [3.625, 5.364] (assumes normal distribution)


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
# Warmup Iteration   1: 8.963 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.371 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.758 ±(99.9%) 0.025 ms/op
Iteration   1: 5.723 ±(99.9%) 0.022 ms/op
Iteration   2: 5.498 ±(99.9%) 0.013 ms/op
Iteration   3: 5.679 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.633 ±(99.9%) 2.179 ms/op [Average]
  (min, avg, max) = (5.498, 5.633, 5.723), stdev = 0.119
  CI (99.9%): [3.455, 7.812] (assumes normal distribution)


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
# Warmup Iteration   1: 6.653 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.924 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.614 ±(99.9%) 0.015 ms/op
Iteration   1: 4.459 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   8.314 ms/op
                 createUser·p0.999:  10.919 ms/op
                 createUser·p0.9999: 29.808 ms/op
                 createUser·p1.00:   33.260 ms/op

Iteration   2: 4.548 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.702 ms/op
                 createUser·p0.95:   6.169 ms/op
                 createUser·p0.99:   7.873 ms/op
                 createUser·p0.999:  12.158 ms/op
                 createUser·p0.9999: 22.313 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 4.341 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.210 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   7.152 ms/op
                 createUser·p0.999:  10.853 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215825
  mean =      4.448 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3640 
    [ 2.500,  5.000) = 169271 
    [ 5.000,  7.500) = 40416 
    [ 7.500, 10.000) = 1934 
    [10.000, 12.500) = 381 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     29.054 ms/op
     p(99.9990) =     31.691 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 6.204 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.012 ms/op
Iteration   1: 4.255 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   4.141 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  10.743 ms/op
                 existUser·p0.9999: 17.841 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 4.232 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   4.125 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 18.837 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   3: 4.216 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   4.137 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 19.543 ms/op
                 existUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 226654
  mean =      4.235 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 3810 
    [ 2.500,  3.750) = 57573 
    [ 3.750,  5.000) = 133402 
    [ 5.000,  6.250) = 27716 
    [ 6.250,  7.500) = 2721 
    [ 7.500,  8.750) = 822 
    [ 8.750, 10.000) = 293 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     10.590 ms/op
     p(99.9900) =     18.896 ms/op
     p(99.9990) =     19.912 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 7.146 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.905 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.605 ±(99.9%) 0.013 ms/op
Iteration   1: 4.366 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  11.432 ms/op
                 getUser·p0.9999: 14.408 ms/op
                 getUser·p1.00:   16.318 ms/op

Iteration   2: 4.329 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  12.474 ms/op
                 getUser·p0.9999: 16.283 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 4.600 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  9.779 ms/op
                 getUser·p0.9999: 21.959 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216694
  mean =      4.428 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5190 
    [ 2.500,  5.000) = 166348 
    [ 5.000,  7.500) = 43186 
    [ 7.500, 10.000) = 1593 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     11.217 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     22.211 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 8.646 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.887 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.691 ±(99.9%) 0.020 ms/op
Iteration   1: 5.682 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  16.563 ms/op
                 listUser·p0.9999: 20.262 ms/op
                 listUser·p1.00:   28.934 ms/op

Iteration   2: 5.752 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.732 ms/op
                 listUser·p0.999:  20.558 ms/op
                 listUser·p0.9999: 25.555 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   3: 5.768 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  26.200 ms/op
                 listUser·p0.9999: 30.814 ms/op
                 listUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167335
  mean =      5.734 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 106 
    [ 2.500,  5.000) = 45197 
    [ 5.000,  7.500) = 107713 
    [ 7.500, 10.000) = 11836 
    [10.000, 12.500) = 1898 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      5.480 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     29.059 ms/op
     p(99.9990) =     31.118 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.006 ± 2.114  ops/ms
ClientGrpc.existUser                       thrpt       3   7.645 ± 2.656  ops/ms
ClientGrpc.getUser                         thrpt       3   7.292 ± 2.949  ops/ms
ClientGrpc.listUser                        thrpt       3   5.614 ± 3.095  ops/ms
ClientGrpc.createUser                       avgt       3   4.532 ± 1.635   ms/op
ClientGrpc.existUser                        avgt       3   4.218 ± 1.680   ms/op
ClientGrpc.getUser                          avgt       3   4.495 ± 0.869   ms/op
ClientGrpc.listUser                         avgt       3   5.633 ± 2.179   ms/op
ClientGrpc.createUser                     sample  215825   4.448 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.159           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.489           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.741           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.895           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.054           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.260           ms/op
ClientGrpc.existUser                      sample  226654   4.235 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.891           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.808           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.590           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.896           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.988           ms/op
ClientGrpc.getUser                        sample  216694   4.428 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.965           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.480           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.915           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.373           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.217           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.350           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.217           ms/op
ClientGrpc.listUser                       sample  167335   5.734 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.298           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.551           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.661           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.059           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.162           ms/op
