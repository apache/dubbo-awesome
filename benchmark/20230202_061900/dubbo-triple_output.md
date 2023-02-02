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
# Warmup Iteration   1: 1.086 ops/ms
# Warmup Iteration   2: 2.406 ops/ms
# Warmup Iteration   3: 5.074 ops/ms
Iteration   1: 5.668 ops/ms
Iteration   2: 5.694 ops/ms
Iteration   3: 5.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.701 ±(99.9%) 0.668 ops/ms [Average]
  (min, avg, max) = (5.668, 5.701, 5.740), stdev = 0.037
  CI (99.9%): [5.032, 6.369] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.620 ops/ms
# Warmup Iteration   2: 4.740 ops/ms
# Warmup Iteration   3: 5.803 ops/ms
Iteration   1: 5.955 ops/ms
Iteration   2: 6.035 ops/ms
Iteration   3: 5.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.969 ±(99.9%) 1.103 ops/ms [Average]
  (min, avg, max) = (5.917, 5.969, 6.035), stdev = 0.060
  CI (99.9%): [4.866, 7.073] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.527 ops/ms
# Warmup Iteration   2: 4.111 ops/ms
# Warmup Iteration   3: 5.531 ops/ms
Iteration   1: 5.255 ops/ms
Iteration   2: 5.475 ops/ms
Iteration   3: 5.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.466 ±(99.9%) 3.762 ops/ms [Average]
  (min, avg, max) = (5.255, 5.466, 5.667), stdev = 0.206
  CI (99.9%): [1.704, 9.228] (assumes normal distribution)


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
# Warmup Iteration   1: 1.473 ops/ms
# Warmup Iteration   2: 4.094 ops/ms
# Warmup Iteration   3: 4.921 ops/ms
Iteration   1: 4.886 ops/ms
Iteration   2: 4.940 ops/ms
Iteration   3: 5.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.967 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (4.886, 4.967, 5.075), stdev = 0.097
  CI (99.9%): [3.192, 6.742] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 20.430 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.803 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.882 ±(99.9%) 0.013 ms/op
Iteration   1: 5.719 ±(99.9%) 0.008 ms/op
Iteration   2: 5.461 ±(99.9%) 0.012 ms/op
Iteration   3: 5.507 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.562 ±(99.9%) 2.508 ms/op [Average]
  (min, avg, max) = (5.461, 5.562, 5.719), stdev = 0.137
  CI (99.9%): [3.055, 8.070] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 17.360 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.063 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.491 ±(99.9%) 0.009 ms/op
Iteration   1: 5.424 ±(99.9%) 0.010 ms/op
Iteration   2: 5.148 ±(99.9%) 0.014 ms/op
Iteration   3: 5.327 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.299 ±(99.9%) 2.552 ms/op [Average]
  (min, avg, max) = (5.148, 5.299, 5.424), stdev = 0.140
  CI (99.9%): [2.747, 7.852] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 19.033 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 7.560 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.681 ±(99.9%) 0.013 ms/op
Iteration   1: 5.793 ±(99.9%) 0.015 ms/op
Iteration   2: 5.521 ±(99.9%) 0.013 ms/op
Iteration   3: 5.660 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.658 ±(99.9%) 2.478 ms/op [Average]
  (min, avg, max) = (5.521, 5.658, 5.793), stdev = 0.136
  CI (99.9%): [3.180, 8.136] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.568 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 8.055 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.476 ±(99.9%) 0.015 ms/op
Iteration   1: 6.296 ±(99.9%) 0.017 ms/op
Iteration   2: 6.366 ±(99.9%) 0.011 ms/op
Iteration   3: 6.355 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.339 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (6.296, 6.339, 6.366), stdev = 0.037
  CI (99.9%): [5.659, 7.018] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.883 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 8.159 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 5.959 ±(99.9%) 0.025 ms/op
Iteration   1: 5.589 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.658 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   7.127 ms/op
                 createUser·p0.95:   8.143 ms/op
                 createUser·p0.99:   11.813 ms/op
                 createUser·p0.999:  22.332 ms/op
                 createUser·p0.9999: 25.848 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   2: 5.685 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.376 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   7.373 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.452 ms/op
                 createUser·p0.999:  27.778 ms/op
                 createUser·p0.9999: 37.118 ms/op
                 createUser·p1.00:   37.880 ms/op

Iteration   3: 5.919 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.482 ms/op
                 createUser·p0.50:   5.571 ms/op
                 createUser·p0.90:   7.709 ms/op
                 createUser·p0.95:   8.716 ms/op
                 createUser·p0.99:   12.173 ms/op
                 createUser·p0.999:  35.062 ms/op
                 createUser·p0.9999: 37.144 ms/op
                 createUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167586
  mean =      5.728 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 63392 
    [ 5.000,  7.500) = 88294 
    [ 7.500, 10.000) = 12221 
    [10.000, 12.500) = 2390 
    [12.500, 15.000) = 720 
    [15.000, 17.500) = 319 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     36.897 ms/op
     p(99.9990) =     38.360 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 18.998 ±(99.9%) 0.311 ms/op
# Warmup Iteration   2: 6.468 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.664 ±(99.9%) 0.024 ms/op
Iteration   1: 5.298 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.717 ms/op
                 existUser·p0.95:   8.176 ms/op
                 existUser·p0.99:   11.239 ms/op
                 existUser·p0.999:  16.630 ms/op
                 existUser·p0.9999: 28.569 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   2: 5.410 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.919 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.865 ms/op
                 existUser·p0.95:   7.766 ms/op
                 existUser·p0.99:   10.863 ms/op
                 existUser·p0.999:  26.135 ms/op
                 existUser·p0.9999: 30.291 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   3: 5.321 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.302 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.496 ms/op
                 existUser·p0.99:   10.481 ms/op
                 existUser·p0.999:  29.186 ms/op
                 existUser·p0.9999: 39.124 ms/op
                 existUser·p1.00:   40.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179680
  mean =      5.343 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 95797 
    [ 5.000, 10.000) = 81030 
    [10.000, 15.000) = 2440 
    [15.000, 20.000) = 212 
    [20.000, 25.000) = 41 
    [25.000, 30.000) = 96 
    [30.000, 35.000) = 53 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.717 ms/op
     p(95.0000) =      7.807 ms/op
     p(99.0000) =     10.912 ms/op
     p(99.9000) =     21.572 ms/op
     p(99.9900) =     33.227 ms/op
     p(99.9990) =     40.476 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.603 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.695 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.712 ±(99.9%) 0.022 ms/op
Iteration   1: 5.972 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.798 ms/op
                 getUser·p0.50:   5.497 ms/op
                 getUser·p0.90:   7.856 ms/op
                 getUser·p0.95:   8.978 ms/op
                 getUser·p0.99:   13.238 ms/op
                 getUser·p0.999:  31.195 ms/op
                 getUser·p0.9999: 44.030 ms/op
                 getUser·p1.00:   48.497 ms/op

Iteration   2: 5.591 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.499 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.168 ms/op
                 getUser·p0.95:   8.110 ms/op
                 getUser·p0.99:   10.650 ms/op
                 getUser·p0.999:  24.526 ms/op
                 getUser·p0.9999: 31.392 ms/op
                 getUser·p1.00:   32.375 ms/op

Iteration   3: 5.880 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.646 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.700 ms/op
                 getUser·p0.95:   8.847 ms/op
                 getUser·p0.99:   11.796 ms/op
                 getUser·p0.999:  26.313 ms/op
                 getUser·p0.9999: 32.871 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165146
  mean =      5.810 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 53918 
    [ 5.000, 10.000) = 107605 
    [10.000, 15.000) = 3069 
    [15.000, 20.000) = 281 
    [20.000, 25.000) = 58 
    [25.000, 30.000) = 113 
    [30.000, 35.000) = 71 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.499 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.528 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     11.911 ms/op
     p(99.9000) =     26.477 ms/op
     p(99.9900) =     41.055 ms/op
     p(99.9990) =     47.899 ms/op
     p(99.9999) =     48.497 ms/op
    p(100.0000) =     48.497 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.443 ±(99.9%) 0.363 ms/op
# Warmup Iteration   2: 7.732 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.591 ±(99.9%) 0.028 ms/op
Iteration   1: 6.768 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   6.267 ms/op
                 listUser·p0.90:   8.995 ms/op
                 listUser·p0.95:   10.109 ms/op
                 listUser·p0.99:   13.468 ms/op
                 listUser·p0.999:  27.197 ms/op
                 listUser·p0.9999: 31.395 ms/op
                 listUser·p1.00:   31.785 ms/op

Iteration   2: 6.410 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.117 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   7.954 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  28.348 ms/op
                 listUser·p0.9999: 31.196 ms/op
                 listUser·p1.00:   31.556 ms/op

Iteration   3: 6.579 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.060 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  25.615 ms/op
                 listUser·p0.9999: 30.942 ms/op
                 listUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145790
  mean =      6.583 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 6923 
    [ 5.000,  7.500) = 113217 
    [ 7.500, 10.000) = 20250 
    [10.000, 12.500) = 3820 
    [12.500, 15.000) = 843 
    [15.000, 17.500) = 326 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 99 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.462 ms/op
     p(50.0000) =      6.160 ms/op
     p(90.0000) =      8.421 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     12.681 ms/op
     p(99.9000) =     27.303 ms/op
     p(99.9900) =     31.111 ms/op
     p(99.9990) =     31.725 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.701 ± 0.668  ops/ms
ClientPb.existUser                       thrpt       3   5.969 ± 1.103  ops/ms
ClientPb.getUser                         thrpt       3   5.466 ± 3.762  ops/ms
ClientPb.listUser                        thrpt       3   4.967 ± 1.775  ops/ms
ClientPb.createUser                       avgt       3   5.562 ± 2.508   ms/op
ClientPb.existUser                        avgt       3   5.299 ± 2.552   ms/op
ClientPb.getUser                          avgt       3   5.658 ± 2.478   ms/op
ClientPb.listUser                         avgt       3   6.339 ± 0.680   ms/op
ClientPb.createUser                     sample  167586   5.728 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.482           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.414           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.438           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.928           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.495           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.897           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.404           ms/op
ClientPb.existUser                      sample  179680   5.343 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.924           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.717           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.807           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.912           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.572           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.227           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.632           ms/op
ClientPb.getUser                        sample  165146   5.810 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.439           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.618           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.911           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.477           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.055           ms/op
ClientPb.getUser:getUser·p1.00          sample          48.497           ms/op
ClientPb.listUser                       sample  145790   6.583 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.462           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.535           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.681           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.111           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.785           ms/op
