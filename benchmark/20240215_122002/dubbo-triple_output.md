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
# Warmup Iteration   1: 4.597 ops/ms
# Warmup Iteration   2: 11.881 ops/ms
# Warmup Iteration   3: 11.930 ops/ms
Iteration   1: 12.268 ops/ms
Iteration   2: 12.435 ops/ms
Iteration   3: 12.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.388 ±(99.9%) 1.909 ops/ms [Average]
  (min, avg, max) = (12.268, 12.388, 12.460), stdev = 0.105
  CI (99.9%): [10.479, 14.297] (assumes normal distribution)


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
# Warmup Iteration   1: 8.261 ops/ms
# Warmup Iteration   2: 12.880 ops/ms
# Warmup Iteration   3: 12.900 ops/ms
Iteration   1: 13.021 ops/ms
Iteration   2: 12.956 ops/ms
Iteration   3: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.950 ±(99.9%) 1.375 ops/ms [Average]
  (min, avg, max) = (12.871, 12.950, 13.021), stdev = 0.075
  CI (99.9%): [11.575, 14.325] (assumes normal distribution)


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
# Warmup Iteration   1: 7.683 ops/ms
# Warmup Iteration   2: 12.436 ops/ms
# Warmup Iteration   3: 12.870 ops/ms
Iteration   1: 12.778 ops/ms
Iteration   2: 12.426 ops/ms
Iteration   3: 12.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.683 ±(99.9%) 4.109 ops/ms [Average]
  (min, avg, max) = (12.426, 12.683, 12.846), stdev = 0.225
  CI (99.9%): [8.575, 16.792] (assumes normal distribution)


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
# Warmup Iteration   1: 6.604 ops/ms
# Warmup Iteration   2: 10.339 ops/ms
# Warmup Iteration   3: 10.529 ops/ms
Iteration   1: 10.419 ops/ms
Iteration   2: 10.508 ops/ms
Iteration   3: 10.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.484 ±(99.9%) 1.030 ops/ms [Average]
  (min, avg, max) = (10.419, 10.484, 10.524), stdev = 0.056
  CI (99.9%): [9.454, 11.514] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.136 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.004 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.601 ±(99.9%) 0.004 ms/op
Iteration   3: 2.573 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.573 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (2.546, 2.573, 2.601), stdev = 0.028
  CI (99.9%): [2.068, 3.078] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.004 ms/op
Iteration   1: 2.435 ±(99.9%) 0.004 ms/op
Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
Iteration   3: 2.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.054 ms/op [Average]
  (min, avg, max) = (2.430, 2.432, 2.435), stdev = 0.003
  CI (99.9%): [2.378, 2.485] (assumes normal distribution)


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.508 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.503, 2.508, 2.518), stdev = 0.009
  CI (99.9%): [2.349, 2.666] (assumes normal distribution)


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
# Warmup Iteration   1: 4.955 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
Iteration   3: 3.061 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (3.021, 3.039, 3.061), stdev = 0.020
  CI (99.9%): [2.667, 3.410] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
Iteration   1: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  11.024 ms/op
                 createUser·p0.9999: 13.205 ms/op
                 createUser·p1.00:   13.517 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 12.277 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  8.542 ms/op
                 createUser·p0.9999: 13.948 ms/op
                 createUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379227
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 182791 
    [ 2.500,  3.750) = 192249 
    [ 3.750,  5.000) = 3154 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     13.257 ms/op
     p(99.9990) =     14.565 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  5.604 ms/op
                 existUser·p0.9999: 14.042 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 12.328 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.646 ms/op
                 existUser·p0.999:  7.791 ms/op
                 existUser·p0.9999: 11.829 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385771
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 186870 
    [ 2.500,  3.750) = 195685 
    [ 3.750,  5.000) = 2374 
    [ 5.000,  6.250) = 364 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      7.878 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     14.633 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.519 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  10.614 ms/op
                 getUser·p0.9999: 13.824 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.697 ms/op
                 getUser·p0.999:  6.177 ms/op
                 getUser·p0.9999: 12.497 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.263 ms/op
                 getUser·p0.9999: 11.866 ms/op
                 getUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381682
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 187621 
    [ 2.500,  3.750) = 188972 
    [ 3.750,  5.000) = 3827 
    [ 5.000,  6.250) = 652 
    [ 6.250,  7.500) = 154 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      7.484 ms/op
     p(99.9900) =     13.088 ms/op
     p(99.9990) =     14.011 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.834 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.387 ms/op
                 listUser·p1.00:   12.648 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  8.803 ms/op
                 listUser·p0.9999: 12.244 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 12.071 ms/op
                 listUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317858
  mean =      3.017 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 91976 
    [ 2.500,  3.750) = 186152 
    [ 3.750,  5.000) = 32077 
    [ 5.000,  6.250) = 6296 
    [ 6.250,  7.500) = 530 
    [ 7.500,  8.750) = 313 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.902 ms/op
     p(99.9990) =     12.798 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.388 ± 1.909  ops/ms
ClientPb.existUser                       thrpt       3  12.950 ± 1.375  ops/ms
ClientPb.getUser                         thrpt       3  12.683 ± 4.109  ops/ms
ClientPb.listUser                        thrpt       3  10.484 ± 1.030  ops/ms
ClientPb.createUser                       avgt       3   2.573 ± 0.505   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.054   ms/op
ClientPb.getUser                          avgt       3   2.508 ± 0.158   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.372   ms/op
ClientPb.createUser                     sample  379227   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.911           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.552           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.257           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.746           ms/op
ClientPb.existUser                      sample  385771   2.485 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.878           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.877           ms/op
ClientPb.getUser                        sample  381682   2.513 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.519           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.484           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.088           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  317858   3.017 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.882           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.902           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.156           ms/op
