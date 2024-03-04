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
# Warmup Iteration   1: 4.922 ops/ms
# Warmup Iteration   2: 12.272 ops/ms
# Warmup Iteration   3: 12.510 ops/ms
Iteration   1: 12.787 ops/ms
Iteration   2: 12.751 ops/ms
Iteration   3: 12.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.733 ±(99.9%) 1.190 ops/ms [Average]
  (min, avg, max) = (12.660, 12.733, 12.787), stdev = 0.065
  CI (99.9%): [11.543, 13.922] (assumes normal distribution)


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
# Warmup Iteration   1: 8.297 ops/ms
# Warmup Iteration   2: 13.130 ops/ms
# Warmup Iteration   3: 13.252 ops/ms
Iteration   1: 13.328 ops/ms
Iteration   2: 13.241 ops/ms
Iteration   3: 13.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.278 ±(99.9%) 0.827 ops/ms [Average]
  (min, avg, max) = (13.241, 13.278, 13.328), stdev = 0.045
  CI (99.9%): [12.451, 14.104] (assumes normal distribution)


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
# Warmup Iteration   1: 7.468 ops/ms
# Warmup Iteration   2: 12.545 ops/ms
# Warmup Iteration   3: 12.696 ops/ms
Iteration   1: 12.677 ops/ms
Iteration   2: 12.760 ops/ms
Iteration   3: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.739 ±(99.9%) 0.991 ops/ms [Average]
  (min, avg, max) = (12.677, 12.739, 12.779), stdev = 0.054
  CI (99.9%): [11.748, 13.731] (assumes normal distribution)


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
# Warmup Iteration   1: 6.922 ops/ms
# Warmup Iteration   2: 10.337 ops/ms
# Warmup Iteration   3: 10.563 ops/ms
Iteration   1: 10.623 ops/ms
Iteration   2: 10.704 ops/ms
Iteration   3: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.635 ±(99.9%) 1.170 ops/ms [Average]
  (min, avg, max) = (10.578, 10.635, 10.704), stdev = 0.064
  CI (99.9%): [9.465, 11.805] (assumes normal distribution)


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.003 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.503, 2.516, 2.536), stdev = 0.018
  CI (99.9%): [2.193, 2.840] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.598 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.442, 2.449, 2.460), stdev = 0.010
  CI (99.9%): [2.265, 2.633] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.003 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (2.486, 2.490, 2.496), stdev = 0.006
  CI (99.9%): [2.387, 2.593] (assumes normal distribution)


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.005 ms/op
Iteration   1: 2.946 ±(99.9%) 0.006 ms/op
Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
Iteration   3: 2.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.960 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.946, 2.960, 2.977), stdev = 0.016
  CI (99.9%): [2.673, 3.247] (assumes normal distribution)


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.732 ms/op
                 createUser·p0.999:  10.797 ms/op
                 createUser·p0.9999: 13.494 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.936 ms/op
                 createUser·p0.999:  9.334 ms/op
                 createUser·p0.9999: 11.789 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.859 ms/op
                 createUser·p0.999:  7.665 ms/op
                 createUser·p0.9999: 10.531 ms/op
                 createUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380366
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 181026 
    [ 2.500,  3.750) = 194750 
    [ 3.750,  5.000) = 3666 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      7.747 ms/op
     p(99.9900) =     13.254 ms/op
     p(99.9990) =     13.831 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.636 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.335 ms/op
                 existUser·p0.999:  4.824 ms/op
                 existUser·p0.9999: 13.067 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  8.035 ms/op
                 existUser·p0.9999: 12.431 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  6.574 ms/op
                 existUser·p0.9999: 12.419 ms/op
                 existUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395517
  mean =      2.425 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 198754 
    [ 2.500,  3.750) = 194510 
    [ 3.750,  5.000) = 1638 
    [ 5.000,  6.250) = 180 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 143 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      6.140 ms/op
     p(99.9900) =     12.639 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.874 ms/op
                 getUser·p0.999:  11.256 ms/op
                 getUser·p0.9999: 13.451 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  9.462 ms/op
                 getUser·p0.9999: 12.878 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.855 ms/op
                 getUser·p0.999:  7.534 ms/op
                 getUser·p0.9999: 11.813 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382764
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 188709 
    [ 2.500,  3.750) = 189802 
    [ 3.750,  5.000) = 3301 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     13.065 ms/op
     p(99.9990) =     13.779 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 4.835 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.082 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.689 ms/op
                 listUser·p0.999:  9.277 ms/op
                 listUser·p0.9999: 10.443 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  8.687 ms/op
                 listUser·p0.9999: 10.232 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  8.690 ms/op
                 listUser·p0.9999: 12.878 ms/op
                 listUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313344
  mean =      3.061 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 82507 
    [ 2.500,  3.750) = 186970 
    [ 3.750,  5.000) = 35726 
    [ 5.000,  6.250) = 6554 
    [ 6.250,  7.500) = 859 
    [ 7.500,  8.750) = 296 
    [ 8.750, 10.000) = 243 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     11.567 ms/op
     p(99.9990) =     13.166 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.733 ± 1.190  ops/ms
ClientPb.existUser                       thrpt       3  13.278 ± 0.827  ops/ms
ClientPb.getUser                         thrpt       3  12.739 ± 0.991  ops/ms
ClientPb.listUser                        thrpt       3  10.635 ± 1.170  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.324   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.184   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.103   ms/op
ClientPb.listUser                         avgt       3   2.960 ± 0.287   ms/op
ClientPb.createUser                     sample  380366   2.521 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.774           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.747           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.254           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  395517   2.425 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.922           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.140           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.639           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.533           ms/op
ClientPb.getUser                        sample  382764   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.935           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.922           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.065           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.894           ms/op
ClientPb.listUser                       sample  313344   3.061 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.567           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.550           ms/op
