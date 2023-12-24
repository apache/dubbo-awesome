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
# Warmup Iteration   1: 4.666 ops/ms
# Warmup Iteration   2: 12.026 ops/ms
# Warmup Iteration   3: 12.293 ops/ms
Iteration   1: 12.530 ops/ms
Iteration   2: 12.650 ops/ms
Iteration   3: 12.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.605 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (12.530, 12.605, 12.650), stdev = 0.066
  CI (99.9%): [11.407, 13.802] (assumes normal distribution)


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
# Warmup Iteration   1: 8.331 ops/ms
# Warmup Iteration   2: 13.186 ops/ms
# Warmup Iteration   3: 13.087 ops/ms
Iteration   1: 13.176 ops/ms
Iteration   2: 13.081 ops/ms
Iteration   3: 13.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.110 ±(99.9%) 1.044 ops/ms [Average]
  (min, avg, max) = (13.073, 13.110, 13.176), stdev = 0.057
  CI (99.9%): [12.066, 14.154] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.981 ops/ms
# Warmup Iteration   2: 12.587 ops/ms
# Warmup Iteration   3: 12.733 ops/ms
Iteration   1: 12.947 ops/ms
Iteration   2: 12.771 ops/ms
Iteration   3: 12.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.790 ±(99.9%) 2.712 ops/ms [Average]
  (min, avg, max) = (12.652, 12.790, 12.947), stdev = 0.149
  CI (99.9%): [10.078, 15.502] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.467 ops/ms
# Warmup Iteration   2: 10.523 ops/ms
# Warmup Iteration   3: 10.736 ops/ms
Iteration   1: 10.687 ops/ms
Iteration   2: 10.727 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.684 ±(99.9%) 0.800 ops/ms [Average]
  (min, avg, max) = (10.639, 10.684, 10.727), stdev = 0.044
  CI (99.9%): [9.884, 11.484] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.116 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.003 ms/op
Iteration   2: 2.577 ±(99.9%) 0.006 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (2.494, 2.539, 2.577), stdev = 0.042
  CI (99.9%): [1.767, 3.311] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.643 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.443 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.104 ms/op [Average]
  (min, avg, max) = (2.440, 2.445, 2.451), stdev = 0.006
  CI (99.9%): [2.341, 2.549] (assumes normal distribution)


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (2.482, 2.501, 2.511), stdev = 0.016
  CI (99.9%): [2.208, 2.794] (assumes normal distribution)


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
Iteration   3: 3.006 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (3.006, 3.016, 3.024), stdev = 0.009
  CI (99.9%): [2.852, 3.180] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.993 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  11.695 ms/op
                 createUser·p0.9999: 14.109 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  8.928 ms/op
                 createUser·p0.9999: 14.549 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  7.727 ms/op
                 createUser·p0.9999: 11.343 ms/op
                 createUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381266
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 184425 
    [ 2.500,  3.750) = 192438 
    [ 3.750,  5.000) = 3574 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.092 ms/op
     p(99.9900) =     13.973 ms/op
     p(99.9990) =     14.927 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.613 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.011 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.199 ms/op
                 existUser·p0.9999: 13.272 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  7.809 ms/op
                 existUser·p0.9999: 11.977 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388476
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 196553 
    [ 2.500,  3.750) = 188372 
    [ 3.750,  5.000) = 2704 
    [ 5.000,  6.250) = 375 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 150 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      7.599 ms/op
     p(99.9900) =     13.241 ms/op
     p(99.9990) =     14.080 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  10.024 ms/op
                 getUser·p0.9999: 13.304 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.404 ms/op
                 getUser·p0.999:  6.070 ms/op
                 getUser·p0.9999: 13.648 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  7.608 ms/op
                 getUser·p0.9999: 11.424 ms/op
                 getUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385600
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 191743 
    [ 2.500,  3.750) = 189527 
    [ 3.750,  5.000) = 3401 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      7.286 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     14.226 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.694 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.706 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.243 ms/op
                 listUser·p0.9999: 12.162 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   2: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.870 ms/op
                 listUser·p0.9999: 11.698 ms/op
                 listUser·p1.00:   12.206 ms/op

Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.941 ms/op
                 listUser·p0.9999: 12.559 ms/op
                 listUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320707
  mean =      2.991 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 96332 
    [ 2.500,  3.750) = 186345 
    [ 3.750,  5.000) = 30843 
    [ 5.000,  6.250) = 5573 
    [ 6.250,  7.500) = 770 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.508 ms/op
     p(99.9900) =     12.074 ms/op
     p(99.9990) =     12.723 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.605 ± 1.197  ops/ms
ClientPb.existUser                       thrpt       3  13.110 ± 1.044  ops/ms
ClientPb.getUser                         thrpt       3  12.790 ± 2.712  ops/ms
ClientPb.listUser                        thrpt       3  10.684 ± 0.800  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.772   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.104   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.293   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.164   ms/op
ClientPb.createUser                     sample  381266   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.777           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.092           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.973           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.122           ms/op
ClientPb.existUser                      sample  388476   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.944           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.241           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  385600   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.792           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.286           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.287           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.369           ms/op
ClientPb.listUser                       sample  320707   2.991 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.508           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.074           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.091           ms/op
