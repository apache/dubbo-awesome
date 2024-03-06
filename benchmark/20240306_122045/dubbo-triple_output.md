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
# Warmup Iteration   1: 5.015 ops/ms
# Warmup Iteration   2: 12.387 ops/ms
# Warmup Iteration   3: 12.638 ops/ms
Iteration   1: 12.808 ops/ms
Iteration   2: 13.031 ops/ms
Iteration   3: 12.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.873 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (12.781, 12.873, 13.031), stdev = 0.137
  CI (99.9%): [10.367, 15.380] (assumes normal distribution)


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
# Warmup Iteration   1: 8.415 ops/ms
# Warmup Iteration   2: 13.040 ops/ms
# Warmup Iteration   3: 13.051 ops/ms
Iteration   1: 13.279 ops/ms
Iteration   2: 13.009 ops/ms
Iteration   3: 13.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.111 ±(99.9%) 2.668 ops/ms [Average]
  (min, avg, max) = (13.009, 13.111, 13.279), stdev = 0.146
  CI (99.9%): [10.443, 15.779] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.237 ops/ms
# Warmup Iteration   2: 13.008 ops/ms
# Warmup Iteration   3: 13.252 ops/ms
Iteration   1: 13.345 ops/ms
Iteration   2: 13.240 ops/ms
Iteration   3: 13.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.294 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (13.240, 13.294, 13.345), stdev = 0.052
  CI (99.9%): [12.342, 14.246] (assumes normal distribution)


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
# Warmup Iteration   1: 7.135 ops/ms
# Warmup Iteration   2: 10.747 ops/ms
# Warmup Iteration   3: 10.886 ops/ms
Iteration   1: 10.965 ops/ms
Iteration   2: 10.848 ops/ms
Iteration   3: 10.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.914 ±(99.9%) 1.091 ops/ms [Average]
  (min, avg, max) = (10.848, 10.914, 10.965), stdev = 0.060
  CI (99.9%): [9.823, 12.005] (assumes normal distribution)


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.004 ms/op
Iteration   1: 2.413 ±(99.9%) 0.003 ms/op
Iteration   2: 2.408 ±(99.9%) 0.003 ms/op
Iteration   3: 2.431 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.417 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.408, 2.417, 2.431), stdev = 0.012
  CI (99.9%): [2.195, 2.639] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.471 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.376 ±(99.9%) 0.004 ms/op
Iteration   1: 2.377 ±(99.9%) 0.004 ms/op
Iteration   2: 2.361 ±(99.9%) 0.004 ms/op
Iteration   3: 2.381 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.373 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.361, 2.373, 2.381), stdev = 0.011
  CI (99.9%): [2.175, 2.572] (assumes normal distribution)


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.003 ms/op
Iteration   1: 2.427 ±(99.9%) 0.004 ms/op
Iteration   2: 2.414 ±(99.9%) 0.003 ms/op
Iteration   3: 2.438 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.426 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.414, 2.426, 2.438), stdev = 0.012
  CI (99.9%): [2.216, 2.637] (assumes normal distribution)


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
# Warmup Iteration   1: 4.840 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
Iteration   3: 3.018 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.985, 3.006, 3.018), stdev = 0.018
  CI (99.9%): [2.672, 3.340] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.143 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  5.862 ms/op
                 createUser·p0.9999: 13.845 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  8.225 ms/op
                 createUser·p0.9999: 12.403 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.674 ms/op
                 createUser·p0.9999: 11.043 ms/op
                 createUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386807
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 189375 
    [ 2.500,  3.750) = 192125 
    [ 3.750,  5.000) = 4273 
    [ 5.000,  6.250) = 521 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.556 ms/op
     p(99.9900) =     13.538 ms/op
     p(99.9990) =     14.120 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.383 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.394 ±(99.9%) 0.005 ms/op
Iteration   1: 2.370 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.875 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  4.915 ms/op
                 existUser·p0.9999: 13.648 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  7.545 ms/op
                 existUser·p0.9999: 13.806 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   3: 2.348 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.847 ms/op
                 existUser·p0.95:   2.957 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  6.135 ms/op
                 existUser·p0.9999: 11.370 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 404507
  mean =      2.370 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 211340 
    [ 2.500,  3.750) = 189900 
    [ 3.750,  5.000) = 2410 
    [ 5.000,  6.250) = 390 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      6.169 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.006 ms/op
Iteration   1: 2.383 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   2.413 ms/op
                 getUser·p0.90:   2.900 ms/op
                 getUser·p0.95:   3.019 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  5.328 ms/op
                 getUser·p0.9999: 16.728 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   2: 2.408 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   2.920 ms/op
                 getUser·p0.95:   3.035 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  7.263 ms/op
                 getUser·p0.9999: 13.320 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   3: 2.403 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   2.933 ms/op
                 getUser·p0.95:   3.043 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  6.092 ms/op
                 getUser·p0.9999: 10.846 ms/op
                 getUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 399962
  mean =      2.398 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 207806 
    [ 2.500,  3.750) = 188612 
    [ 3.750,  5.000) = 2656 
    [ 5.000,  6.250) = 322 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      6.833 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.008 ms/op
Iteration   1: 2.924 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 10.076 ms/op
                 listUser·p1.00:   10.289 ms/op

Iteration   2: 2.883 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   2.822 ms/op
                 listUser·p0.90:   3.719 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.680 ms/op
                 listUser·p1.00:   12.386 ms/op

Iteration   3: 2.899 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.862 ms/op
                 listUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 330500
  mean =      2.902 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 112804 
    [ 2.500,  3.750) = 183271 
    [ 3.750,  5.000) = 28012 
    [ 5.000,  6.250) = 5071 
    [ 6.250,  7.500) = 467 
    [ 7.500,  8.750) = 274 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.026 ms/op
     p(99.9990) =     12.302 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.873 ± 2.506  ops/ms
ClientPb.existUser                       thrpt       3  13.111 ± 2.668  ops/ms
ClientPb.getUser                         thrpt       3  13.294 ± 0.952  ops/ms
ClientPb.listUser                        thrpt       3  10.914 ± 1.091  ops/ms
ClientPb.createUser                       avgt       3   2.417 ± 0.222   ms/op
ClientPb.existUser                        avgt       3   2.373 ± 0.199   ms/op
ClientPb.getUser                          avgt       3   2.426 ± 0.211   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.334   ms/op
ClientPb.createUser                     sample  386807   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.936           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.556           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.538           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.696           ms/op
ClientPb.existUser                      sample  404507   2.370 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.891           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.437           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.875           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.169           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.991           ms/op
ClientPb.getUser                        sample  399962   2.398 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.691           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.421           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.833           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.367           ms/op
ClientPb.listUser                       sample  330500   2.902 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.879           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.415           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.026           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.386           ms/op
