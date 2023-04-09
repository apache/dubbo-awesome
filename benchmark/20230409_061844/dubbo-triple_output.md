# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.980 ops/ms
# Warmup Iteration   2: 4.835 ops/ms
# Warmup Iteration   3: 8.487 ops/ms
Iteration   1: 8.710 ops/ms
Iteration   2: 9.170 ops/ms
Iteration   3: 9.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.061 ±(99.9%) 5.681 ops/ms [Average]
  (min, avg, max) = (8.710, 9.061, 9.303), stdev = 0.311
  CI (99.9%): [3.380, 14.742] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.322 ops/ms
# Warmup Iteration   2: 8.724 ops/ms
# Warmup Iteration   3: 9.823 ops/ms
Iteration   1: 9.705 ops/ms
Iteration   2: 9.678 ops/ms
Iteration   3: 9.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.761 ±(99.9%) 2.222 ops/ms [Average]
  (min, avg, max) = (9.678, 9.761, 9.901), stdev = 0.122
  CI (99.9%): [7.540, 11.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.336 ops/ms
# Warmup Iteration   2: 8.935 ops/ms
# Warmup Iteration   3: 9.034 ops/ms
Iteration   1: 9.478 ops/ms
Iteration   2: 9.057 ops/ms
Iteration   3: 9.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.280 ±(99.9%) 3.863 ops/ms [Average]
  (min, avg, max) = (9.057, 9.280, 9.478), stdev = 0.212
  CI (99.9%): [5.417, 13.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.575 ops/ms
# Warmup Iteration   2: 6.698 ops/ms
# Warmup Iteration   3: 7.730 ops/ms
Iteration   1: 7.898 ops/ms
Iteration   2: 8.066 ops/ms
Iteration   3: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.992 ±(99.9%) 1.567 ops/ms [Average]
  (min, avg, max) = (7.898, 7.992, 8.066), stdev = 0.086
  CI (99.9%): [6.425, 9.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.043 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.004 ms/op
Iteration   1: 3.430 ±(99.9%) 0.011 ms/op
Iteration   2: 3.379 ±(99.9%) 0.011 ms/op
Iteration   3: 3.443 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.417 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (3.379, 3.417, 3.443), stdev = 0.034
  CI (99.9%): [2.799, 4.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.759 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.009 ms/op
Iteration   1: 3.354 ±(99.9%) 0.006 ms/op
Iteration   2: 3.361 ±(99.9%) 0.004 ms/op
Iteration   3: 3.260 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.325 ±(99.9%) 1.036 ms/op [Average]
  (min, avg, max) = (3.260, 3.325, 3.361), stdev = 0.057
  CI (99.9%): [2.289, 4.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.857 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.007 ms/op
Iteration   1: 3.491 ±(99.9%) 0.004 ms/op
Iteration   2: 3.387 ±(99.9%) 0.005 ms/op
Iteration   3: 3.384 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.421 ±(99.9%) 1.110 ms/op [Average]
  (min, avg, max) = (3.384, 3.421, 3.491), stdev = 0.061
  CI (99.9%): [2.311, 4.531] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.546 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.007 ms/op
Iteration   1: 4.227 ±(99.9%) 0.011 ms/op
Iteration   2: 3.951 ±(99.9%) 0.016 ms/op
Iteration   3: 4.098 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.092 ±(99.9%) 2.517 ms/op [Average]
  (min, avg, max) = (3.951, 4.092, 4.227), stdev = 0.138
  CI (99.9%): [1.574, 6.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.226 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.014 ms/op
Iteration   1: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  19.834 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.625 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  10.957 ms/op
                 createUser·p0.9999: 26.581 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   3: 3.616 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  24.052 ms/op
                 createUser·p0.9999: 33.686 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269478
  mean =      3.563 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8970 
    [ 2.500,  5.000) = 248293 
    [ 5.000,  7.500) = 11241 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     11.068 ms/op
     p(99.9900) =     31.461 ms/op
     p(99.9990) =     34.754 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.747 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.009 ms/op
Iteration   1: 3.386 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.707 ms/op
                 existUser·p0.999:  20.433 ms/op
                 existUser·p0.9999: 23.513 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  12.772 ms/op
                 existUser·p0.9999: 24.609 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.868 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  11.428 ms/op
                 existUser·p0.9999: 27.273 ms/op
                 existUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288704
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16351 
    [ 2.500,  5.000) = 267722 
    [ 5.000,  7.500) = 3790 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.681 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.988 ms/op
     p(99.9900) =     25.633 ms/op
     p(99.9990) =     27.723 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.356 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.010 ms/op
Iteration   1: 3.475 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  18.711 ms/op
                 getUser·p0.9999: 20.513 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  19.600 ms/op
                 getUser·p0.9999: 22.282 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.550 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.372 ms/op
                 getUser·p0.999:  17.655 ms/op
                 getUser·p0.9999: 26.703 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276850
  mean =      3.469 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12831 
    [ 2.500,  5.000) = 255660 
    [ 5.000,  7.500) = 7231 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     18.458 ms/op
     p(99.9900) =     24.859 ms/op
     p(99.9990) =     28.297 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.496 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.611 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.013 ms/op
Iteration   1: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.919 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.678 ms/op
                 listUser·p0.999:  20.363 ms/op
                 listUser·p0.9999: 23.627 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 4.080 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.875 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 18.863 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   3: 3.978 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.401 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238469
  mean =      4.026 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 231335 
    [ 5.000,  7.500) = 4669 
    [ 7.500, 10.000) = 1452 
    [10.000, 12.500) = 399 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 234 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.555 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     22.342 ms/op
     p(99.9990) =     24.579 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.061 ± 5.681  ops/ms
ClientPb.existUser                       thrpt       3   9.761 ± 2.222  ops/ms
ClientPb.getUser                         thrpt       3   9.280 ± 3.863  ops/ms
ClientPb.listUser                        thrpt       3   7.992 ± 1.567  ops/ms
ClientPb.createUser                       avgt       3   3.417 ± 0.618   ms/op
ClientPb.existUser                        avgt       3   3.325 ± 1.036   ms/op
ClientPb.getUser                          avgt       3   3.421 ± 1.110   ms/op
ClientPb.listUser                         avgt       3   4.092 ± 2.517   ms/op
ClientPb.createUser                     sample  269478   3.563 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.785           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.891           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.068           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.461           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.931           ms/op
ClientPb.existUser                      sample  288704   3.323 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.026           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.681           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.988           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.633           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.475           ms/op
ClientPb.getUser                        sample  276850   3.469 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.296           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.458           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.859           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.574           ms/op
ClientPb.listUser                       sample  238469   4.026 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.608           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.555           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.187           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.342           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.740           ms/op
