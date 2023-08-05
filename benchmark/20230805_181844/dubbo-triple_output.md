# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.937 ops/ms
# Warmup Iteration   2: 4.581 ops/ms
# Warmup Iteration   3: 8.584 ops/ms
Iteration   1: 8.727 ops/ms
Iteration   2: 9.151 ops/ms
Iteration   3: 9.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.110 ±(99.9%) 6.658 ops/ms [Average]
  (min, avg, max) = (8.727, 9.110, 9.453), stdev = 0.365
  CI (99.9%): [2.452, 15.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ops/ms
# Warmup Iteration   2: 8.740 ops/ms
# Warmup Iteration   3: 9.707 ops/ms
Iteration   1: 9.391 ops/ms
Iteration   2: 9.897 ops/ms
Iteration   3: 9.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.720 ±(99.9%) 5.194 ops/ms [Average]
  (min, avg, max) = (9.391, 9.720, 9.897), stdev = 0.285
  CI (99.9%): [4.526, 14.914] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.078 ops/ms
# Warmup Iteration   2: 7.158 ops/ms
# Warmup Iteration   3: 8.982 ops/ms
Iteration   1: 9.191 ops/ms
Iteration   2: 8.501 ops/ms
Iteration   3: 9.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.900 ±(99.9%) 6.514 ops/ms [Average]
  (min, avg, max) = (8.501, 8.900, 9.191), stdev = 0.357
  CI (99.9%): [2.386, 15.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.304 ops/ms
# Warmup Iteration   2: 6.699 ops/ms
# Warmup Iteration   3: 7.662 ops/ms
Iteration   1: 7.908 ops/ms
Iteration   2: 7.778 ops/ms
Iteration   3: 7.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.795 ±(99.9%) 1.911 ops/ms [Average]
  (min, avg, max) = (7.700, 7.795, 7.908), stdev = 0.105
  CI (99.9%): [5.885, 9.706] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.195 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.008 ms/op
Iteration   1: 3.429 ±(99.9%) 0.011 ms/op
Iteration   2: 3.395 ±(99.9%) 0.005 ms/op
Iteration   3: 3.444 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.423 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.395, 3.423, 3.444), stdev = 0.025
  CI (99.9%): [2.972, 3.874] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.638 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.004 ms/op
Iteration   1: 3.400 ±(99.9%) 0.005 ms/op
Iteration   2: 3.383 ±(99.9%) 0.004 ms/op
Iteration   3: 3.379 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.387 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (3.379, 3.387, 3.400), stdev = 0.011
  CI (99.9%): [3.185, 3.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.545 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.005 ms/op
Iteration   1: 3.634 ±(99.9%) 0.006 ms/op
Iteration   2: 3.629 ±(99.9%) 0.002 ms/op
Iteration   3: 3.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.591 ±(99.9%) 1.269 ms/op [Average]
  (min, avg, max) = (3.511, 3.591, 3.634), stdev = 0.070
  CI (99.9%): [2.322, 4.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.859 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.005 ms/op
Iteration   1: 4.065 ±(99.9%) 0.011 ms/op
Iteration   2: 4.045 ±(99.9%) 0.009 ms/op
Iteration   3: 4.104 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.071 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (4.045, 4.071, 4.104), stdev = 0.030
  CI (99.9%): [3.521, 4.621] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.654 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.011 ms/op
Iteration   1: 3.503 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.855 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  20.829 ms/op
                 createUser·p0.9999: 23.261 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.541 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  22.750 ms/op
                 createUser·p0.9999: 29.654 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   3: 3.607 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 26.940 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270416
  mean =      3.550 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4642 
    [ 2.500,  5.000) = 257814 
    [ 5.000,  7.500) = 6441 
    [ 7.500, 10.000) = 1084 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     20.092 ms/op
     p(99.9900) =     28.930 ms/op
     p(99.9990) =     29.927 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.146 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
Iteration   1: 3.475 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  20.689 ms/op
                 existUser·p0.9999: 22.957 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  19.147 ms/op
                 existUser·p0.9999: 25.559 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 27.417 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281272
  mean =      3.417 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13702 
    [ 2.500,  5.000) = 259338 
    [ 5.000,  7.500) = 6753 
    [ 7.500, 10.000) = 1031 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     11.759 ms/op
     p(99.9900) =     26.112 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.700 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.012 ms/op
Iteration   1: 3.624 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.718 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.496 ms/op
                 getUser·p0.999:  21.299 ms/op
                 getUser·p0.9999: 30.087 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   2: 3.514 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  22.348 ms/op
                 getUser·p0.9999: 24.248 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 3.560 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  18.596 ms/op
                 getUser·p0.9999: 26.939 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268996
  mean =      3.566 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6992 
    [ 2.500,  5.000) = 252131 
    [ 5.000,  7.500) = 7655 
    [ 7.500, 10.000) = 1485 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     28.118 ms/op
     p(99.9990) =     30.419 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.704 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.013 ms/op
Iteration   1: 4.054 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  21.574 ms/op
                 listUser·p0.9999: 35.979 ms/op
                 listUser·p1.00:   36.766 ms/op

Iteration   2: 4.100 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 17.970 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 4.207 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  14.517 ms/op
                 listUser·p0.9999: 16.243 ms/op
                 listUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232810
  mean =      4.119 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 221761 
    [ 5.000,  7.500) = 7545 
    [ 7.500, 10.000) = 2407 
    [10.000, 12.500) = 573 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     34.650 ms/op
     p(99.9990) =     36.242 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.110 ± 6.658  ops/ms
ClientPb.existUser                       thrpt       3   9.720 ± 5.194  ops/ms
ClientPb.getUser                         thrpt       3   8.900 ± 6.514  ops/ms
ClientPb.listUser                        thrpt       3   7.795 ± 1.911  ops/ms
ClientPb.createUser                       avgt       3   3.423 ± 0.451   ms/op
ClientPb.existUser                        avgt       3   3.387 ± 0.203   ms/op
ClientPb.getUser                          avgt       3   3.591 ± 1.269   ms/op
ClientPb.listUser                         avgt       3   4.071 ± 0.550   ms/op
ClientPb.createUser                     sample  270416   3.550 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.290           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.461           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.092           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.930           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.015           ms/op
ClientPb.existUser                      sample  281272   3.417 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.145           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.357           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.759           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.112           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  268996   3.566 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.592           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.135           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.578           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.118           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  232810   4.119 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.503           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.339           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.385           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.650           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.766           ms/op
