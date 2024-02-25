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
# Warmup Iteration   1: 5.372 ops/ms
# Warmup Iteration   2: 12.262 ops/ms
# Warmup Iteration   3: 12.534 ops/ms
Iteration   1: 12.690 ops/ms
Iteration   2: 12.833 ops/ms
Iteration   3: 12.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.807 ±(99.9%) 1.934 ops/ms [Average]
  (min, avg, max) = (12.690, 12.807, 12.897), stdev = 0.106
  CI (99.9%): [10.872, 14.741] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.620 ops/ms
# Warmup Iteration   2: 13.105 ops/ms
# Warmup Iteration   3: 13.329 ops/ms
Iteration   1: 13.296 ops/ms
Iteration   2: 13.337 ops/ms
Iteration   3: 13.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.311 ±(99.9%) 0.407 ops/ms [Average]
  (min, avg, max) = (13.296, 13.311, 13.337), stdev = 0.022
  CI (99.9%): [12.905, 13.718] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.402 ops/ms
# Warmup Iteration   2: 12.616 ops/ms
# Warmup Iteration   3: 12.847 ops/ms
Iteration   1: 12.762 ops/ms
Iteration   2: 12.984 ops/ms
Iteration   3: 12.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.893 ±(99.9%) 2.118 ops/ms [Average]
  (min, avg, max) = (12.762, 12.893, 12.984), stdev = 0.116
  CI (99.9%): [10.775, 15.012] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.771 ops/ms
# Warmup Iteration   2: 10.625 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.619 ops/ms
Iteration   2: 10.749 ops/ms
Iteration   3: 10.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.681 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (10.619, 10.681, 10.749), stdev = 0.065
  CI (99.9%): [9.489, 11.873] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.003 ms/op
Iteration   2: 2.526 ±(99.9%) 0.003 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.500 ±(99.9%) 0.558 ms/op [Average]
  (min, avg, max) = (2.466, 2.500, 2.526), stdev = 0.031
  CI (99.9%): [1.942, 3.058] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.003 ms/op
Iteration   1: 2.438 ±(99.9%) 0.004 ms/op
Iteration   2: 2.425 ±(99.9%) 0.003 ms/op
Iteration   3: 2.417 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.417, 2.426, 2.438), stdev = 0.011
  CI (99.9%): [2.234, 2.619] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
Iteration   2: 2.484 ±(99.9%) 0.003 ms/op
Iteration   3: 2.474 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.476 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (2.469, 2.476, 2.484), stdev = 0.007
  CI (99.9%): [2.342, 2.609] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.005 ms/op
Iteration   1: 2.976 ±(99.9%) 0.005 ms/op
Iteration   2: 2.942 ±(99.9%) 0.005 ms/op
Iteration   3: 2.967 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.961 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (2.942, 2.961, 2.976), stdev = 0.018
  CI (99.9%): [2.642, 3.281] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.086 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  7.953 ms/op
                 createUser·p0.9999: 13.484 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.391 ms/op
                 createUser·p0.999:  6.877 ms/op
                 createUser·p0.9999: 12.027 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  7.416 ms/op
                 createUser·p0.9999: 10.191 ms/op
                 createUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387770
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 189489 
    [ 2.500,  3.750) = 194759 
    [ 3.750,  5.000) = 2802 
    [ 5.000,  6.250) = 221 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      7.542 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     13.750 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.640 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.407 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.005 ms/op
Iteration   1: 2.398 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  5.315 ms/op
                 existUser·p0.9999: 13.348 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  6.363 ms/op
                 existUser·p0.9999: 12.691 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 10.760 ms/op
                 existUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397218
  mean =      2.414 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 203766 
    [ 2.500,  3.750) = 190555 
    [ 3.750,  5.000) = 2107 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 158 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.550 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.731 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  6.537 ms/op
                 getUser·p0.9999: 13.012 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  7.751 ms/op
                 getUser·p0.9999: 12.831 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  6.873 ms/op
                 getUser·p0.9999: 10.553 ms/op
                 getUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385670
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 191626 
    [ 2.500,  3.750) = 189721 
    [ 3.750,  5.000) = 3297 
    [ 5.000,  6.250) = 538 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      6.564 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     13.767 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.717 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 13.025 ms/op
                 listUser·p1.00:   13.615 ms/op

Iteration   2: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.210 ms/op
                 listUser·p0.9999: 11.826 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.408 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 11.557 ms/op
                 listUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320840
  mean =      2.989 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 98041 
    [ 2.500,  3.750) = 184563 
    [ 3.750,  5.000) = 30952 
    [ 5.000,  6.250) = 5790 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 310 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     12.041 ms/op
     p(99.9990) =     13.444 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.807 ± 1.934  ops/ms
ClientPb.existUser                       thrpt       3  13.311 ± 0.407  ops/ms
ClientPb.getUser                         thrpt       3  12.893 ± 2.118  ops/ms
ClientPb.listUser                        thrpt       3  10.681 ± 1.192  ops/ms
ClientPb.createUser                       avgt       3   2.500 ± 0.558   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.192   ms/op
ClientPb.getUser                          avgt       3   2.476 ± 0.133   ms/op
ClientPb.listUser                         avgt       3   2.961 ± 0.320   ms/op
ClientPb.createUser                     sample  387770   2.473 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.865           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.542           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.894           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  397218   2.414 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.735           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.449           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.550           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.405           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.943           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.041           ms/op
ClientPb.getUser                        sample  385670   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.821           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.564           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.829           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.959           ms/op
ClientPb.listUser                       sample  320840   2.989 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.847           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.041           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.615           ms/op
