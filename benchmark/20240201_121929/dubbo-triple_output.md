# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.017 ops/ms
# Warmup Iteration   2: 11.932 ops/ms
# Warmup Iteration   3: 12.151 ops/ms
Iteration   1: 12.359 ops/ms
Iteration   2: 12.511 ops/ms
Iteration   3: 12.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.496 ±(99.9%) 2.357 ops/ms [Average]
  (min, avg, max) = (12.359, 12.496, 12.616), stdev = 0.129
  CI (99.9%): [10.138, 14.853] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.142 ops/ms
# Warmup Iteration   2: 12.889 ops/ms
# Warmup Iteration   3: 12.825 ops/ms
Iteration   1: 12.594 ops/ms
Iteration   2: 12.875 ops/ms
Iteration   3: 12.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.756 ±(99.9%) 2.655 ops/ms [Average]
  (min, avg, max) = (12.594, 12.756, 12.875), stdev = 0.146
  CI (99.9%): [10.101, 15.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.540 ops/ms
# Warmup Iteration   2: 12.607 ops/ms
# Warmup Iteration   3: 12.783 ops/ms
Iteration   1: 12.727 ops/ms
Iteration   2: 12.728 ops/ms
Iteration   3: 12.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.655 ±(99.9%) 2.303 ops/ms [Average]
  (min, avg, max) = (12.509, 12.655, 12.728), stdev = 0.126
  CI (99.9%): [10.352, 14.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.417 ops/ms
# Warmup Iteration   2: 10.463 ops/ms
# Warmup Iteration   3: 10.467 ops/ms
Iteration   1: 10.620 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.598 ±(99.9%) 0.431 ops/ms [Average]
  (min, avg, max) = (10.573, 10.598, 10.620), stdev = 0.024
  CI (99.9%): [10.167, 11.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.003 ms/op
Iteration   1: 2.562 ±(99.9%) 0.004 ms/op
Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
Iteration   3: 2.599 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.584 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.562, 2.584, 2.599), stdev = 0.019
  CI (99.9%): [2.233, 2.934] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.003 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.464 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.454, 2.464, 2.472), stdev = 0.009
  CI (99.9%): [2.296, 2.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.003 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.510 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.506, 2.510, 2.516), stdev = 0.005
  CI (99.9%): [2.410, 2.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.005 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
Iteration   3: 3.047 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.025, 3.036, 3.047), stdev = 0.011
  CI (99.9%): [2.838, 3.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.430 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  11.357 ms/op
                 createUser·p0.9999: 13.817 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.506 ms/op
                 createUser·p0.999:  8.953 ms/op
                 createUser·p0.9999: 13.553 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 11.272 ms/op
                 createUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381506
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 183857 
    [ 2.500,  3.750) = 193924 
    [ 3.750,  5.000) = 2941 
    [ 5.000,  6.250) = 256 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     13.463 ms/op
     p(99.9990) =     14.480 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.685 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  6.540 ms/op
                 existUser·p0.9999: 13.942 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.732 ms/op
                 existUser·p0.9999: 12.747 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  8.098 ms/op
                 existUser·p0.9999: 16.597 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388569
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 191437 
    [ 2.500,  3.750) = 193966 
    [ 3.750,  5.000) = 2309 
    [ 5.000,  6.250) = 435 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      6.094 ms/op
     p(99.9900) =     14.006 ms/op
     p(99.9990) =     17.109 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.923 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  6.136 ms/op
                 getUser·p0.9999: 14.157 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.557 ms/op
                 getUser·p0.999:  8.646 ms/op
                 getUser·p0.9999: 13.564 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.184 ms/op
                 getUser·p0.999:  8.024 ms/op
                 getUser·p0.9999: 11.387 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385920
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 192135 
    [ 2.500,  3.750) = 187788 
    [ 3.750,  5.000) = 4399 
    [ 5.000,  6.250) = 1054 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      7.728 ms/op
     p(99.9900) =     13.736 ms/op
     p(99.9990) =     14.242 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.009 ms/op
Iteration   1: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.160 ms/op
                 listUser·p1.00:   12.796 ms/op

Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 12.345 ms/op
                 listUser·p1.00:   13.418 ms/op

Iteration   3: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.573 ms/op
                 listUser·p0.9999: 11.829 ms/op
                 listUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313629
  mean =      3.059 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 85641 
    [ 2.500,  3.750) = 185068 
    [ 3.750,  5.000) = 35070 
    [ 5.000,  6.250) = 6419 
    [ 6.250,  7.500) = 650 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.427 ms/op
     p(99.9900) =     11.829 ms/op
     p(99.9990) =     13.344 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.496 ± 2.357  ops/ms
ClientPb.existUser                       thrpt       3  12.756 ± 2.655  ops/ms
ClientPb.getUser                         thrpt       3  12.655 ± 2.303  ops/ms
ClientPb.listUser                        thrpt       3  10.598 ± 0.431  ops/ms
ClientPb.createUser                       avgt       3   2.584 ± 0.351   ms/op
ClientPb.existUser                        avgt       3   2.464 ± 0.168   ms/op
ClientPb.getUser                          avgt       3   2.510 ± 0.099   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.199   ms/op
ClientPb.createUser                     sample  381506   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.958           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.093           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.463           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.926           ms/op
ClientPb.existUser                      sample  388569   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.856           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.094           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.006           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.170           ms/op
ClientPb.getUser                        sample  385920   2.485 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.782           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.728           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.736           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  313629   3.059 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.427           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.829           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.418           ms/op
