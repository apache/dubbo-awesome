# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.084 ops/ms
# Warmup Iteration   2: 5.412 ops/ms
# Warmup Iteration   3: 7.876 ops/ms
Iteration   1: 8.713 ops/ms
Iteration   2: 9.079 ops/ms
Iteration   3: 9.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.002 ±(99.9%) 4.743 ops/ms [Average]
  (min, avg, max) = (8.713, 9.002, 9.215), stdev = 0.260
  CI (99.9%): [4.260, 13.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.771 ops/ms
# Warmup Iteration   2: 8.479 ops/ms
# Warmup Iteration   3: 9.411 ops/ms
Iteration   1: 9.345 ops/ms
Iteration   2: 9.575 ops/ms
Iteration   3: 9.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.418 ±(99.9%) 2.487 ops/ms [Average]
  (min, avg, max) = (9.334, 9.418, 9.575), stdev = 0.136
  CI (99.9%): [6.931, 11.905] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ops/ms
# Warmup Iteration   2: 8.445 ops/ms
# Warmup Iteration   3: 8.816 ops/ms
Iteration   1: 9.250 ops/ms
Iteration   2: 9.298 ops/ms
Iteration   3: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.231 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (9.144, 9.231, 9.298), stdev = 0.079
  CI (99.9%): [7.789, 10.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.469 ops/ms
# Warmup Iteration   2: 7.021 ops/ms
# Warmup Iteration   3: 7.780 ops/ms
Iteration   1: 7.755 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 7.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.784 ±(99.9%) 3.163 ops/ms [Average]
  (min, avg, max) = (7.627, 7.784, 7.970), stdev = 0.173
  CI (99.9%): [4.621, 10.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.450 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.004 ms/op
Iteration   1: 3.496 ±(99.9%) 0.008 ms/op
Iteration   2: 3.607 ±(99.9%) 0.004 ms/op
Iteration   3: 3.589 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.564 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (3.496, 3.564, 3.607), stdev = 0.060
  CI (99.9%): [2.477, 4.651] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.232 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.004 ms/op
Iteration   1: 3.272 ±(99.9%) 0.004 ms/op
Iteration   2: 3.408 ±(99.9%) 0.006 ms/op
Iteration   3: 3.435 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.371 ±(99.9%) 1.594 ms/op [Average]
  (min, avg, max) = (3.272, 3.371, 3.435), stdev = 0.087
  CI (99.9%): [1.778, 4.965] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.096 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.005 ms/op
Iteration   1: 3.593 ±(99.9%) 0.004 ms/op
Iteration   2: 3.549 ±(99.9%) 0.006 ms/op
Iteration   3: 3.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.546 ±(99.9%) 0.881 ms/op [Average]
  (min, avg, max) = (3.496, 3.546, 3.593), stdev = 0.048
  CI (99.9%): [2.665, 4.427] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.815 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.735 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.008 ms/op
Iteration   1: 4.023 ±(99.9%) 0.009 ms/op
Iteration   2: 4.086 ±(99.9%) 0.009 ms/op
Iteration   3: 4.089 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.066 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (4.023, 4.066, 4.089), stdev = 0.037
  CI (99.9%): [3.386, 4.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.416 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.010 ms/op
Iteration   1: 3.564 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   7.059 ms/op
                 createUser·p0.999:  20.334 ms/op
                 createUser·p0.9999: 22.873 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   2: 3.531 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.466 ms/op
                 createUser·p0.999:  21.660 ms/op
                 createUser·p0.9999: 26.013 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   3: 3.437 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  21.922 ms/op
                 createUser·p0.9999: 27.486 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273200
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3869 
    [ 2.500,  5.000) = 260580 
    [ 5.000,  7.500) = 6925 
    [ 7.500, 10.000) = 1106 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.383 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
Iteration   1: 3.459 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  22.582 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   2: 3.578 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  10.151 ms/op
                 existUser·p0.9999: 26.133 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.424 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  25.186 ms/op
                 existUser·p0.9999: 31.741 ms/op
                 existUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275247
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5708 
    [ 2.500,  5.000) = 258860 
    [ 5.000,  7.500) = 8871 
    [ 7.500, 10.000) = 1187 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     11.887 ms/op
     p(99.9900) =     28.817 ms/op
     p(99.9990) =     32.128 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.810 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.012 ms/op
Iteration   1: 3.663 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  22.171 ms/op
                 getUser·p0.9999: 26.477 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   2: 3.548 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  24.543 ms/op
                 getUser·p0.9999: 28.868 ms/op
                 getUser·p1.00:   30.540 ms/op

Iteration   3: 3.591 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.353 ms/op
                 getUser·p0.999:  11.894 ms/op
                 getUser·p0.9999: 30.441 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266567
  mean =      3.600 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8875 
    [ 2.500,  5.000) = 244419 
    [ 5.000,  7.500) = 11166 
    [ 7.500, 10.000) = 1380 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     29.634 ms/op
     p(99.9990) =     31.031 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.023 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.244 ±(99.9%) 0.015 ms/op
Iteration   1: 4.214 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.557 ms/op
                 listUser·p0.999:  21.307 ms/op
                 listUser·p0.9999: 25.671 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   2: 4.117 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 18.587 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 4.203 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 27.951 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229543
  mean =      4.178 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 216118 
    [ 5.000,  7.500) = 10245 
    [ 7.500, 10.000) = 1863 
    [10.000, 12.500) = 634 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     17.448 ms/op
     p(99.9900) =     26.380 ms/op
     p(99.9990) =     30.262 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.002 ± 4.743  ops/ms
ClientPb.existUser                       thrpt       3   9.418 ± 2.487  ops/ms
ClientPb.getUser                         thrpt       3   9.231 ± 1.442  ops/ms
ClientPb.listUser                        thrpt       3   7.784 ± 3.163  ops/ms
ClientPb.createUser                       avgt       3   3.564 ± 1.087   ms/op
ClientPb.existUser                        avgt       3   3.371 ± 1.594   ms/op
ClientPb.getUser                          avgt       3   3.546 ± 0.881   ms/op
ClientPb.listUser                         avgt       3   4.066 ± 0.680   ms/op
ClientPb.createUser                     sample  273200   3.510 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.775           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.345           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.787           ms/op
ClientPb.existUser                      sample  275247   3.486 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.977           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.873           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.887           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.817           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.408           ms/op
ClientPb.getUser                        sample  266567   3.600 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.586           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.997           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.185           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.634           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.261           ms/op
ClientPb.listUser                       sample  229543   4.178 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.251           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.448           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.380           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.310           ms/op
