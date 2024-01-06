# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.573 ops/ms
# Warmup Iteration   2: 11.927 ops/ms
# Warmup Iteration   3: 12.177 ops/ms
Iteration   1: 12.630 ops/ms
Iteration   2: 12.560 ops/ms
Iteration   3: 12.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.629 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (12.560, 12.629, 12.697), stdev = 0.068
  CI (99.9%): [11.386, 13.872] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.238 ops/ms
# Warmup Iteration   2: 12.995 ops/ms
# Warmup Iteration   3: 12.977 ops/ms
Iteration   1: 13.151 ops/ms
Iteration   2: 13.031 ops/ms
Iteration   3: 13.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.121 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (13.031, 13.121, 13.181), stdev = 0.079
  CI (99.9%): [11.677, 14.565] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.564 ops/ms
# Warmup Iteration   2: 12.467 ops/ms
# Warmup Iteration   3: 12.715 ops/ms
Iteration   1: 12.611 ops/ms
Iteration   2: 12.755 ops/ms
Iteration   3: 12.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.691 ±(99.9%) 1.334 ops/ms [Average]
  (min, avg, max) = (12.611, 12.691, 12.755), stdev = 0.073
  CI (99.9%): [11.357, 14.025] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.518 ops/ms
# Warmup Iteration   2: 10.310 ops/ms
# Warmup Iteration   3: 10.576 ops/ms
Iteration   1: 10.668 ops/ms
Iteration   2: 10.602 ops/ms
Iteration   3: 10.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.617 ±(99.9%) 0.823 ops/ms [Average]
  (min, avg, max) = (10.582, 10.617, 10.668), stdev = 0.045
  CI (99.9%): [9.794, 11.441] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.003 ms/op
Iteration   1: 2.511 ±(99.9%) 0.003 ms/op
Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
Iteration   3: 2.524 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (2.511, 2.529, 2.553), stdev = 0.022
  CI (99.9%): [2.133, 2.925] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.594 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.003 ms/op
Iteration   1: 2.436 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.430 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.420, 2.430, 2.436), stdev = 0.009
  CI (99.9%): [2.258, 2.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.485, 2.492, 2.503), stdev = 0.009
  CI (99.9%): [2.320, 2.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.694 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.005 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
Iteration   3: 2.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.993, 3.006, 3.016), stdev = 0.012
  CI (99.9%): [2.793, 3.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.400 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.665 ms/op
                 createUser·p0.999:  11.566 ms/op
                 createUser·p0.9999: 13.566 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  9.535 ms/op
                 createUser·p0.9999: 12.573 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.767 ms/op
                 createUser·p0.999:  8.357 ms/op
                 createUser·p0.9999: 10.352 ms/op
                 createUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380977
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 185160 
    [ 2.500,  3.750) = 191595 
    [ 3.750,  5.000) = 3361 
    [ 5.000,  6.250) = 388 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     13.351 ms/op
     p(99.9990) =     14.011 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.511 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.425 ms/op
                 existUser·p0.999:  6.042 ms/op
                 existUser·p0.9999: 14.842 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  7.205 ms/op
                 existUser·p0.9999: 13.107 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.169 ms/op
                 existUser·p0.9999: 11.272 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391625
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 194888 
    [ 2.500,  3.750) = 193510 
    [ 3.750,  5.000) = 2305 
    [ 5.000,  6.250) = 430 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      7.253 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.980 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.963 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  11.749 ms/op
                 getUser·p0.9999: 13.286 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  9.714 ms/op
                 getUser·p0.9999: 14.893 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  8.729 ms/op
                 getUser·p0.9999: 10.834 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381517
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 187726 
    [ 2.500,  3.750) = 189250 
    [ 3.750,  5.000) = 3700 
    [ 5.000,  6.250) = 349 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     15.601 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.673 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
Iteration   1: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.329 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.370 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 10.385 ms/op
                 listUser·p1.00:   11.862 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.392 ms/op
                 listUser·p0.9999: 11.967 ms/op
                 listUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317253
  mean =      3.023 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 90299 
    [ 2.500,  3.750) = 187620 
    [ 3.750,  5.000) = 31922 
    [ 5.000,  6.250) = 5839 
    [ 6.250,  7.500) = 721 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 312 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.572 ms/op
     p(99.9990) =     12.673 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.629 ± 1.243  ops/ms
ClientPb.existUser                       thrpt       3  13.121 ± 1.444  ops/ms
ClientPb.getUser                         thrpt       3  12.691 ± 1.334  ops/ms
ClientPb.listUser                        thrpt       3  10.617 ± 0.823  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.396   ms/op
ClientPb.existUser                        avgt       3   2.430 ± 0.172   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.172   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.213   ms/op
ClientPb.createUser                     sample  380977   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.746           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.389           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.351           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.221           ms/op
ClientPb.existUser                      sample  391625   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.737           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.253           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.188           ms/op
ClientPb.getUser                        sample  381517   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.709           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.322           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.074           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.827           ms/op
ClientPb.listUser                       sample  317253   3.023 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.813           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.572           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
