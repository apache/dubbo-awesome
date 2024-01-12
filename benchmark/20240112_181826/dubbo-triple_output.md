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
# Warmup Iteration   1: 4.637 ops/ms
# Warmup Iteration   2: 12.065 ops/ms
# Warmup Iteration   3: 12.004 ops/ms
Iteration   1: 12.413 ops/ms
Iteration   2: 12.459 ops/ms
Iteration   3: 12.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.490 ±(99.9%) 1.761 ops/ms [Average]
  (min, avg, max) = (12.413, 12.490, 12.598), stdev = 0.097
  CI (99.9%): [10.729, 14.251] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.666 ops/ms
# Warmup Iteration   2: 12.463 ops/ms
# Warmup Iteration   3: 12.752 ops/ms
Iteration   1: 12.757 ops/ms
Iteration   2: 12.979 ops/ms
Iteration   3: 13.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.947 ±(99.9%) 3.209 ops/ms [Average]
  (min, avg, max) = (12.757, 12.947, 13.104), stdev = 0.176
  CI (99.9%): [9.737, 16.156] (assumes normal distribution)


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
# Warmup Iteration   1: 7.583 ops/ms
# Warmup Iteration   2: 12.342 ops/ms
# Warmup Iteration   3: 12.677 ops/ms
Iteration   1: 12.323 ops/ms
Iteration   2: 12.761 ops/ms
Iteration   3: 12.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.619 ±(99.9%) 4.674 ops/ms [Average]
  (min, avg, max) = (12.323, 12.619, 12.773), stdev = 0.256
  CI (99.9%): [7.945, 17.293] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.429 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.380 ops/ms
Iteration   1: 10.464 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.404 ±(99.9%) 1.640 ops/ms [Average]
  (min, avg, max) = (10.300, 10.404, 10.464), stdev = 0.090
  CI (99.9%): [8.764, 12.044] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.080 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.620 ±(99.9%) 0.005 ms/op
Iteration   1: 2.616 ±(99.9%) 0.004 ms/op
Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
Iteration   3: 2.580 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.588 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (2.567, 2.588, 2.616), stdev = 0.025
  CI (99.9%): [2.129, 3.047] (assumes normal distribution)


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.505 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.487, 2.505, 2.515), stdev = 0.015
  CI (99.9%): [2.224, 2.785] (assumes normal distribution)


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.005 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.556 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.545, 2.556, 2.564), stdev = 0.010
  CI (99.9%): [2.370, 2.743] (assumes normal distribution)


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
# Warmup Iteration   1: 4.916 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
Iteration   3: 3.013 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.057 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.013, 3.057, 3.084), stdev = 0.038
  CI (99.9%): [2.365, 3.748] (assumes normal distribution)


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.717 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.909 ms/op
                 createUser·p0.999:  11.918 ms/op
                 createUser·p0.9999: 14.689 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 2.589 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  11.199 ms/op
                 createUser·p0.9999: 12.861 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   3: 2.599 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.103 ms/op
                 createUser·p0.9999: 11.279 ms/op
                 createUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370973
  mean =      2.585 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 176664 
    [ 2.500,  3.750) = 188466 
    [ 3.750,  5.000) = 4570 
    [ 5.000,  6.250) = 709 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     14.251 ms/op
     p(99.9990) =     15.542 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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
# Warmup Iteration   1: 3.688 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.513 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.585 ms/op
                 existUser·p0.999:  11.798 ms/op
                 existUser·p0.9999: 14.870 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.620 ms/op
                 existUser·p0.999:  7.103 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.565 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.105 ms/op
                 existUser·p0.95:   3.248 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  8.263 ms/op
                 existUser·p0.9999: 26.330 ms/op
                 existUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379132
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183984 
    [ 2.500,  5.000) = 193945 
    [ 5.000,  7.500) = 820 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      7.704 ms/op
     p(99.9900) =     15.050 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.653 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.626 ±(99.9%) 0.006 ms/op
Iteration   1: 2.598 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.166 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 15.902 ms/op
                 getUser·p1.00:   16.564 ms/op

Iteration   2: 2.587 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   2.621 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  9.929 ms/op
                 getUser·p0.9999: 14.555 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   3: 2.598 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.360 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  8.995 ms/op
                 getUser·p0.9999: 11.431 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 369693
  mean =      2.594 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 178159 
    [ 2.500,  3.750) = 187102 
    [ 3.750,  5.000) = 3606 
    [ 5.000,  6.250) = 348 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     15.172 ms/op
     p(99.9990) =     16.394 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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
# Warmup Iteration   1: 5.108 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.009 ms/op
Iteration   1: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   2: 3.078 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.522 ms/op
                 listUser·p0.9999: 11.471 ms/op
                 listUser·p1.00:   13.615 ms/op

Iteration   3: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  10.133 ms/op
                 listUser·p0.9999: 12.890 ms/op
                 listUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312484
  mean =      3.069 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 82332 
    [ 2.500,  3.750) = 187075 
    [ 3.750,  5.000) = 34583 
    [ 5.000,  6.250) = 6870 
    [ 6.250,  7.500) = 807 
    [ 7.500,  8.750) = 177 
    [ 8.750, 10.000) = 271 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.659 ms/op
     p(99.9900) =     12.477 ms/op
     p(99.9990) =     13.255 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.490 ± 1.761  ops/ms
ClientPb.existUser                       thrpt       3  12.947 ± 3.209  ops/ms
ClientPb.getUser                         thrpt       3  12.619 ± 4.674  ops/ms
ClientPb.listUser                        thrpt       3  10.404 ± 1.640  ops/ms
ClientPb.createUser                       avgt       3   2.588 ± 0.459   ms/op
ClientPb.existUser                        avgt       3   2.505 ± 0.281   ms/op
ClientPb.getUser                          avgt       3   2.556 ± 0.187   ms/op
ClientPb.listUser                         avgt       3   3.057 ± 0.691   ms/op
ClientPb.createUser                     sample  370973   2.585 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.591           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.421           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.251           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.647           ms/op
ClientPb.existUser                      sample  379132   2.530 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.794           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.704           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.050           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.870           ms/op
ClientPb.getUser                        sample  369693   2.594 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.613           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.191           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.172           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.564           ms/op
ClientPb.listUser                       sample  312484   3.069 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.888           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.659           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.477           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.615           ms/op
