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
# Warmup Iteration   1: 4.548 ops/ms
# Warmup Iteration   2: 12.060 ops/ms
# Warmup Iteration   3: 12.387 ops/ms
Iteration   1: 12.581 ops/ms
Iteration   2: 12.630 ops/ms
Iteration   3: 12.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.664 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (12.581, 12.664, 12.781), stdev = 0.104
  CI (99.9%): [10.768, 14.560] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.923 ops/ms
# Warmup Iteration   2: 12.990 ops/ms
# Warmup Iteration   3: 13.054 ops/ms
Iteration   1: 13.190 ops/ms
Iteration   2: 13.137 ops/ms
Iteration   3: 13.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.128 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (13.057, 13.128, 13.190), stdev = 0.067
  CI (99.9%): [11.901, 14.355] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.607 ops/ms
# Warmup Iteration   2: 12.083 ops/ms
# Warmup Iteration   3: 12.670 ops/ms
Iteration   1: 12.767 ops/ms
Iteration   2: 12.847 ops/ms
Iteration   3: 12.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.715 ±(99.9%) 3.021 ops/ms [Average]
  (min, avg, max) = (12.529, 12.715, 12.847), stdev = 0.166
  CI (99.9%): [9.694, 15.736] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.714 ops/ms
# Warmup Iteration   2: 10.670 ops/ms
# Warmup Iteration   3: 10.744 ops/ms
Iteration   1: 10.759 ops/ms
Iteration   2: 10.724 ops/ms
Iteration   3: 10.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.761 ±(99.9%) 0.708 ops/ms [Average]
  (min, avg, max) = (10.724, 10.761, 10.801), stdev = 0.039
  CI (99.9%): [10.053, 11.469] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.003 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.533, 2.541, 2.556), stdev = 0.013
  CI (99.9%): [2.304, 2.778] (assumes normal distribution)


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.435 ±(99.9%) 0.003 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.452 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.438, 2.452, 2.459), stdev = 0.011
  CI (99.9%): [2.245, 2.658] (assumes normal distribution)


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.454 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.442, 2.454, 2.461), stdev = 0.010
  CI (99.9%): [2.273, 2.635] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.559 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.005 ms/op
Iteration   1: 2.917 ±(99.9%) 0.005 ms/op
Iteration   2: 2.925 ±(99.9%) 0.006 ms/op
Iteration   3: 2.912 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.918 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (2.912, 2.918, 2.925), stdev = 0.007
  CI (99.9%): [2.799, 3.037] (assumes normal distribution)


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  7.014 ms/op
                 createUser·p0.9999: 16.302 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  9.848 ms/op
                 createUser·p0.9999: 13.371 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.749 ms/op
                 createUser·p0.999:  7.437 ms/op
                 createUser·p0.9999: 10.535 ms/op
                 createUser·p1.00:   10.830 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388888
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 189560 
    [ 2.500,  3.750) = 195893 
    [ 3.750,  5.000) = 2532 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     13.571 ms/op
     p(99.9990) =     16.846 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.617 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.068 ms/op
                 existUser·p0.9999: 13.449 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  6.389 ms/op
                 existUser·p0.9999: 14.809 ms/op
                 existUser·p1.00:   15.466 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  8.733 ms/op
                 existUser·p0.9999: 11.254 ms/op
                 existUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393899
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 196848 
    [ 2.500,  3.750) = 194333 
    [ 3.750,  5.000) = 1954 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =      8.521 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     15.320 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.471 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.877 ms/op
                 getUser·p0.999:  5.694 ms/op
                 getUser·p0.9999: 15.417 ms/op
                 getUser·p1.00:   15.974 ms/op

Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.623 ms/op
                 getUser·p0.9999: 12.585 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.044 ms/op
                 getUser·p0.999:  8.885 ms/op
                 getUser·p0.9999: 11.076 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385647
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 193571 
    [ 2.500,  3.750) = 186253 
    [ 3.750,  5.000) = 3947 
    [ 5.000,  6.250) = 1329 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      4.069 ms/op
     p(99.9000) =      7.827 ms/op
     p(99.9900) =     14.434 ms/op
     p(99.9990) =     15.944 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 4.556 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.009 ms/op
Iteration   1: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 11.368 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 12.373 ms/op
                 listUser·p1.00:   13.156 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.328 ms/op
                 listUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319586
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 94052 
    [ 2.500,  3.750) = 187368 
    [ 3.750,  5.000) = 31377 
    [ 5.000,  6.250) = 5370 
    [ 6.250,  7.500) = 593 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 299 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.444 ms/op
     p(99.9900) =     11.454 ms/op
     p(99.9990) =     12.652 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.664 ± 1.896  ops/ms
ClientPb.existUser                       thrpt       3  13.128 ± 1.227  ops/ms
ClientPb.getUser                         thrpt       3  12.715 ± 3.021  ops/ms
ClientPb.listUser                        thrpt       3  10.761 ± 0.708  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.237   ms/op
ClientPb.existUser                        avgt       3   2.452 ± 0.207   ms/op
ClientPb.getUser                          avgt       3   2.454 ± 0.181   ms/op
ClientPb.listUser                         avgt       3   2.918 ± 0.119   ms/op
ClientPb.createUser                     sample  388888   2.467 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.840           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.257           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.571           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.908           ms/op
ClientPb.existUser                      sample  393899   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.521           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.517           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.466           ms/op
ClientPb.getUser                        sample  385647   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.471           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.069           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.827           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.434           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.974           ms/op
ClientPb.listUser                       sample  319586   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.444           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.454           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.156           ms/op
