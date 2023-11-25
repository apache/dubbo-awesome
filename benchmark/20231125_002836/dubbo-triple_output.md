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
# Warmup Iteration   1: 4.831 ops/ms
# Warmup Iteration   2: 11.733 ops/ms
# Warmup Iteration   3: 12.181 ops/ms
Iteration   1: 12.346 ops/ms
Iteration   2: 12.440 ops/ms
Iteration   3: 12.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.473 ±(99.9%) 2.654 ops/ms [Average]
  (min, avg, max) = (12.346, 12.473, 12.631), stdev = 0.145
  CI (99.9%): [9.819, 15.126] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.882 ops/ms
# Warmup Iteration   2: 12.762 ops/ms
# Warmup Iteration   3: 12.871 ops/ms
Iteration   1: 12.903 ops/ms
Iteration   2: 12.944 ops/ms
Iteration   3: 12.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.897 ±(99.9%) 0.906 ops/ms [Average]
  (min, avg, max) = (12.845, 12.897, 12.944), stdev = 0.050
  CI (99.9%): [11.991, 13.803] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.560 ops/ms
# Warmup Iteration   2: 12.221 ops/ms
# Warmup Iteration   3: 12.465 ops/ms
Iteration   1: 12.431 ops/ms
Iteration   2: 12.573 ops/ms
Iteration   3: 12.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.442 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (12.323, 12.442, 12.573), stdev = 0.125
  CI (99.9%): [10.158, 14.726] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.688 ops/ms
# Warmup Iteration   2: 10.468 ops/ms
# Warmup Iteration   3: 10.527 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.615 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.598 ±(99.9%) 0.296 ops/ms [Average]
  (min, avg, max) = (10.582, 10.598, 10.615), stdev = 0.016
  CI (99.9%): [10.302, 10.895] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.575 ±(99.9%) 0.005 ms/op
Iteration   1: 2.538 ±(99.9%) 0.004 ms/op
Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
Iteration   3: 2.565 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (2.538, 2.566, 2.596), stdev = 0.029
  CI (99.9%): [2.030, 3.103] (assumes normal distribution)


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.503 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (2.486, 2.503, 2.515), stdev = 0.015
  CI (99.9%): [2.224, 2.782] (assumes normal distribution)


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.005 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.555 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.540 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.530, 2.540, 2.555), stdev = 0.013
  CI (99.9%): [2.295, 2.785] (assumes normal distribution)


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.005 ms/op
Iteration   1: 2.971 ±(99.9%) 0.004 ms/op
Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
Iteration   3: 2.972 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (2.971, 2.982, 3.002), stdev = 0.018
  CI (99.9%): [2.662, 3.302] (assumes normal distribution)


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.692 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  11.406 ms/op
                 createUser·p0.9999: 13.697 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  9.391 ms/op
                 createUser·p0.9999: 12.148 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  8.617 ms/op
                 createUser·p0.9999: 11.092 ms/op
                 createUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381782
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 183625 
    [ 2.500,  3.750) = 193854 
    [ 3.750,  5.000) = 3323 
    [ 5.000,  6.250) = 496 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      8.622 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  6.816 ms/op
                 existUser·p0.9999: 14.681 ms/op
                 existUser·p1.00:   16.007 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 12.861 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 15.155 ms/op
                 existUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387077
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 189523 
    [ 2.500,  3.750) = 193486 
    [ 3.750,  5.000) = 3141 
    [ 5.000,  6.250) = 419 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 143 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      9.025 ms/op
     p(99.9900) =     14.919 ms/op
     p(99.9990) =     15.979 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  11.207 ms/op
                 getUser·p0.9999: 13.536 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  9.640 ms/op
                 getUser·p0.9999: 14.308 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  8.867 ms/op
                 getUser·p0.9999: 10.532 ms/op
                 getUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380711
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 186311 
    [ 2.500,  3.750) = 189164 
    [ 3.750,  5.000) = 4165 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.885 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     15.001 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.943 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.009 ms/op
Iteration   1: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 10.895 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.729 ms/op
                 listUser·p0.9999: 12.140 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   3: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.561 ms/op
                 listUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315097
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 85942 
    [ 2.500,  3.750) = 188235 
    [ 3.750,  5.000) = 33526 
    [ 5.000,  6.250) = 5871 
    [ 6.250,  7.500) = 742 
    [ 7.500,  8.750) = 175 
    [ 8.750, 10.000) = 295 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     11.542 ms/op
     p(99.9990) =     13.295 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.473 ± 2.654  ops/ms
ClientPb.existUser                       thrpt       3  12.897 ± 0.906  ops/ms
ClientPb.getUser                         thrpt       3  12.442 ± 2.284  ops/ms
ClientPb.listUser                        thrpt       3  10.598 ± 0.296  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.536   ms/op
ClientPb.existUser                        avgt       3   2.503 ± 0.279   ms/op
ClientPb.getUser                          avgt       3   2.540 ± 0.245   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.320   ms/op
ClientPb.createUser                     sample  381782   2.512 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.552           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.622           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.517           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  387077   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.971           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.025           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.919           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.138           ms/op
ClientPb.getUser                        sample  380711   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.903           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.885           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  315097   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.826           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.542           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
