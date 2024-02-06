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
# Warmup Iteration   1: 5.027 ops/ms
# Warmup Iteration   2: 12.093 ops/ms
# Warmup Iteration   3: 12.178 ops/ms
Iteration   1: 12.535 ops/ms
Iteration   2: 12.644 ops/ms
Iteration   3: 12.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.614 ±(99.9%) 1.274 ops/ms [Average]
  (min, avg, max) = (12.535, 12.614, 12.665), stdev = 0.070
  CI (99.9%): [11.341, 13.888] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.460 ops/ms
# Warmup Iteration   2: 13.011 ops/ms
# Warmup Iteration   3: 13.259 ops/ms
Iteration   1: 13.065 ops/ms
Iteration   2: 13.237 ops/ms
Iteration   3: 13.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.161 ±(99.9%) 1.594 ops/ms [Average]
  (min, avg, max) = (13.065, 13.161, 13.237), stdev = 0.087
  CI (99.9%): [11.567, 14.754] (assumes normal distribution)


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
# Warmup Iteration   1: 7.920 ops/ms
# Warmup Iteration   2: 12.445 ops/ms
# Warmup Iteration   3: 12.860 ops/ms
Iteration   1: 12.691 ops/ms
Iteration   2: 12.829 ops/ms
Iteration   3: 12.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.746 ±(99.9%) 1.330 ops/ms [Average]
  (min, avg, max) = (12.691, 12.746, 12.829), stdev = 0.073
  CI (99.9%): [11.416, 14.076] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.401 ops/ms
# Warmup Iteration   2: 10.430 ops/ms
# Warmup Iteration   3: 10.471 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.559 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.545 ±(99.9%) 0.337 ops/ms [Average]
  (min, avg, max) = (10.524, 10.545, 10.559), stdev = 0.018
  CI (99.9%): [10.208, 10.882] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.878 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.004 ms/op
Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
Iteration   3: 2.532 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (2.532, 2.545, 2.562), stdev = 0.016
  CI (99.9%): [2.255, 2.834] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.003 ms/op
Iteration   1: 2.421 ±(99.9%) 0.002 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.440 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.437 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.421, 2.437, 2.448), stdev = 0.014
  CI (99.9%): [2.179, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.003 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.477, 2.487, 2.500), stdev = 0.012
  CI (99.9%): [2.272, 2.702] (assumes normal distribution)


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
Iteration   2: 2.990 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (2.990, 3.010, 3.038), stdev = 0.025
  CI (99.9%): [2.553, 3.467] (assumes normal distribution)


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  11.354 ms/op
                 createUser·p0.9999: 13.710 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  9.663 ms/op
                 createUser·p0.9999: 12.723 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  8.647 ms/op
                 createUser·p0.9999: 11.831 ms/op
                 createUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379724
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 182256 
    [ 2.500,  3.750) = 193511 
    [ 3.750,  5.000) = 3071 
    [ 5.000,  6.250) = 356 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.688 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     14.097 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  7.045 ms/op
                 existUser·p0.9999: 13.708 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  6.335 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.878 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.185 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394862
  mean =      2.429 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 198194 
    [ 2.500,  3.750) = 193903 
    [ 3.750,  5.000) = 2062 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =      6.214 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     13.996 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  9.888 ms/op
                 getUser·p0.9999: 13.287 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   5.054 ms/op
                 getUser·p0.999:  9.111 ms/op
                 getUser·p0.9999: 12.548 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  8.335 ms/op
                 getUser·p0.9999: 10.938 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383299
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 190044 
    [ 2.500,  3.750) = 186890 
    [ 3.750,  5.000) = 4261 
    [ 5.000,  6.250) = 1547 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     12.823 ms/op
     p(99.9990) =     13.552 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.009 ms/op
Iteration   1: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  8.844 ms/op
                 listUser·p0.9999: 11.583 ms/op
                 listUser·p1.00:   13.222 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.876 ms/op
                 listUser·p0.9999: 10.720 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.567 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 11.561 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320134
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 183 
    [ 1.250,  2.500) = 95437 
    [ 2.500,  3.750) = 186191 
    [ 3.750,  5.000) = 30578 
    [ 5.000,  6.250) = 6537 
    [ 6.250,  7.500) = 574 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 199 
    [10.000, 11.250) = 180 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     13.005 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.614 ± 1.274  ops/ms
ClientPb.existUser                       thrpt       3  13.161 ± 1.594  ops/ms
ClientPb.getUser                         thrpt       3  12.746 ± 1.330  ops/ms
ClientPb.listUser                        thrpt       3  10.545 ± 0.337  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.289   ms/op
ClientPb.existUser                        avgt       3   2.437 ± 0.257   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.215   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.457   ms/op
ClientPb.createUser                     sample  379724   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.933           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.688           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.287           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  394862   2.429 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.214           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.139           ms/op
ClientPb.getUser                        sample  383299   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.405           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.823           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.615           ms/op
ClientPb.listUser                       sample  320134   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.771           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.222           ms/op
