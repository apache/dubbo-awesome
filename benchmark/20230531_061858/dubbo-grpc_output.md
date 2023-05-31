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
# Warmup Iteration   1: 3.253 ops/ms
# Warmup Iteration   2: 7.046 ops/ms
# Warmup Iteration   3: 8.196 ops/ms
Iteration   1: 8.689 ops/ms
Iteration   2: 8.867 ops/ms
Iteration   3: 9.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.913 ±(99.9%) 4.568 ops/ms [Average]
  (min, avg, max) = (8.689, 8.913, 9.183), stdev = 0.250
  CI (99.9%): [4.345, 13.480] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.963 ops/ms
# Warmup Iteration   2: 8.549 ops/ms
# Warmup Iteration   3: 9.186 ops/ms
Iteration   1: 9.209 ops/ms
Iteration   2: 9.342 ops/ms
Iteration   3: 9.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.367 ±(99.9%) 3.147 ops/ms [Average]
  (min, avg, max) = (9.209, 9.367, 9.551), stdev = 0.172
  CI (99.9%): [6.221, 12.514] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.507 ops/ms
# Warmup Iteration   2: 8.284 ops/ms
# Warmup Iteration   3: 8.561 ops/ms
Iteration   1: 8.612 ops/ms
Iteration   2: 8.569 ops/ms
Iteration   3: 8.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.514 ±(99.9%) 2.455 ops/ms [Average]
  (min, avg, max) = (8.360, 8.514, 8.612), stdev = 0.135
  CI (99.9%): [6.059, 10.969] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.573 ops/ms
# Warmup Iteration   2: 6.350 ops/ms
# Warmup Iteration   3: 6.678 ops/ms
Iteration   1: 6.485 ops/ms
Iteration   2: 6.402 ops/ms
Iteration   3: 6.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.483 ±(99.9%) 1.456 ops/ms [Average]
  (min, avg, max) = (6.402, 6.483, 6.562), stdev = 0.080
  CI (99.9%): [5.027, 7.939] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.521 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.005 ms/op
Iteration   1: 3.658 ±(99.9%) 0.004 ms/op
Iteration   2: 3.689 ±(99.9%) 0.003 ms/op
Iteration   3: 3.709 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.685 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.658, 3.685, 3.709), stdev = 0.026
  CI (99.9%): [3.216, 4.155] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.003 ms/op
Iteration   1: 3.273 ±(99.9%) 0.002 ms/op
Iteration   2: 3.369 ±(99.9%) 0.002 ms/op
Iteration   3: 3.415 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.352 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (3.273, 3.352, 3.415), stdev = 0.072
  CI (99.9%): [2.032, 4.673] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.101 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.004 ms/op
Iteration   1: 3.701 ±(99.9%) 0.003 ms/op
Iteration   2: 3.560 ±(99.9%) 0.005 ms/op
Iteration   3: 3.544 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.602 ±(99.9%) 1.577 ms/op [Average]
  (min, avg, max) = (3.544, 3.602, 3.701), stdev = 0.086
  CI (99.9%): [2.025, 5.179] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.839 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.944 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.720 ±(99.9%) 0.012 ms/op
Iteration   1: 4.774 ±(99.9%) 0.015 ms/op
Iteration   2: 4.613 ±(99.9%) 0.007 ms/op
Iteration   3: 4.675 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.687 ±(99.9%) 1.484 ms/op [Average]
  (min, avg, max) = (4.613, 4.687, 4.774), stdev = 0.081
  CI (99.9%): [3.203, 6.171] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.095 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.009 ms/op
Iteration   1: 3.818 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  10.011 ms/op
                 createUser·p0.9999: 14.711 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   2: 3.674 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  11.893 ms/op
                 createUser·p0.9999: 15.563 ms/op
                 createUser·p1.00:   16.122 ms/op

Iteration   3: 3.665 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  13.813 ms/op
                 createUser·p0.9999: 30.048 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258193
  mean =      3.718 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8949 
    [ 2.500,  5.000) = 237962 
    [ 5.000,  7.500) = 10072 
    [ 7.500, 10.000) = 886 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     11.525 ms/op
     p(99.9900) =     28.561 ms/op
     p(99.9990) =     30.483 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.830 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.008 ms/op
Iteration   1: 3.449 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 15.338 ms/op
                 existUser·p1.00:   15.811 ms/op

Iteration   2: 3.556 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  9.504 ms/op
                 existUser·p0.9999: 18.121 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   3: 3.539 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 29.819 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273241
  mean =      3.514 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10360 
    [ 2.500,  5.000) = 255131 
    [ 5.000,  7.500) = 6630 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     11.494 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     31.405 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.343 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.009 ms/op
Iteration   1: 3.568 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  12.703 ms/op
                 getUser·p0.9999: 24.020 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   2: 3.561 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  9.175 ms/op
                 getUser·p0.9999: 17.466 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 3.613 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  10.950 ms/op
                 getUser·p0.9999: 19.023 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268287
  mean =      3.580 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6562 
    [ 2.500,  5.000) = 254567 
    [ 5.000,  7.500) = 6229 
    [ 7.500, 10.000) = 602 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     11.115 ms/op
     p(99.9900) =     23.435 ms/op
     p(99.9990) =     24.259 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 6.264 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.653 ±(99.9%) 0.014 ms/op
Iteration   1: 4.769 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  15.859 ms/op
                 listUser·p0.9999: 23.308 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 4.850 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  16.912 ms/op
                 listUser·p0.9999: 22.145 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.849 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.587 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   9.216 ms/op
                 listUser·p0.999:  19.626 ms/op
                 listUser·p0.9999: 33.260 ms/op
                 listUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198993
  mean =      4.822 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 419 
    [ 2.500,  5.000) = 145649 
    [ 5.000,  7.500) = 46266 
    [ 7.500, 10.000) = 5526 
    [10.000, 12.500) = 688 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     31.588 ms/op
     p(99.9990) =     33.292 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.913 ± 4.568  ops/ms
ClientGrpc.existUser                       thrpt       3   9.367 ± 3.147  ops/ms
ClientGrpc.getUser                         thrpt       3   8.514 ± 2.455  ops/ms
ClientGrpc.listUser                        thrpt       3   6.483 ± 1.456  ops/ms
ClientGrpc.createUser                       avgt       3   3.685 ± 0.470   ms/op
ClientGrpc.existUser                        avgt       3   3.352 ± 1.321   ms/op
ClientGrpc.getUser                          avgt       3   3.602 ± 1.577   ms/op
ClientGrpc.listUser                         avgt       3   4.687 ± 1.484   ms/op
ClientGrpc.createUser                     sample  258193   3.718 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.908           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.357           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.525           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.561           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.573           ms/op
ClientGrpc.existUser                      sample  273241   3.514 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.770           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.939           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.494           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.327           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.719           ms/op
ClientGrpc.getUser                        sample  268287   3.580 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.813           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.115           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.435           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.314           ms/op
ClientGrpc.listUser                       sample  198993   4.822 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.587           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.160           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.093           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.588           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.292           ms/op
