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
# Warmup Iteration   1: 0.907 ops/ms
# Warmup Iteration   2: 2.372 ops/ms
# Warmup Iteration   3: 5.209 ops/ms
Iteration   1: 5.510 ops/ms
Iteration   2: 5.735 ops/ms
Iteration   3: 5.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.721 ±(99.9%) 3.730 ops/ms [Average]
  (min, avg, max) = (5.510, 5.721, 5.918), stdev = 0.204
  CI (99.9%): [1.991, 9.451] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.605 ops/ms
# Warmup Iteration   2: 4.635 ops/ms
# Warmup Iteration   3: 5.817 ops/ms
Iteration   1: 5.749 ops/ms
Iteration   2: 5.984 ops/ms
Iteration   3: 5.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.884 ±(99.9%) 2.205 ops/ms [Average]
  (min, avg, max) = (5.749, 5.884, 5.984), stdev = 0.121
  CI (99.9%): [3.679, 8.089] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.743 ops/ms
# Warmup Iteration   2: 4.973 ops/ms
# Warmup Iteration   3: 5.820 ops/ms
Iteration   1: 5.728 ops/ms
Iteration   2: 5.870 ops/ms
Iteration   3: 5.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.788 ±(99.9%) 1.345 ops/ms [Average]
  (min, avg, max) = (5.728, 5.788, 5.870), stdev = 0.074
  CI (99.9%): [4.443, 7.133] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.443 ops/ms
# Warmup Iteration   2: 3.438 ops/ms
# Warmup Iteration   3: 4.731 ops/ms
Iteration   1: 5.082 ops/ms
Iteration   2: 5.076 ops/ms
Iteration   3: 4.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.044 ±(99.9%) 1.104 ops/ms [Average]
  (min, avg, max) = (4.974, 5.044, 5.082), stdev = 0.061
  CI (99.9%): [3.940, 6.148] (assumes normal distribution)


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
# Warmup Iteration   1: 16.945 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.091 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.527 ±(99.9%) 0.015 ms/op
Iteration   1: 5.215 ±(99.9%) 0.014 ms/op
Iteration   2: 5.277 ±(99.9%) 0.014 ms/op
Iteration   3: 5.468 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.320 ±(99.9%) 2.411 ms/op [Average]
  (min, avg, max) = (5.215, 5.320, 5.468), stdev = 0.132
  CI (99.9%): [2.908, 7.731] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.308 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.215 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.539 ±(99.9%) 0.006 ms/op
Iteration   1: 6.233 ±(99.9%) 0.013 ms/op
Iteration   2: 5.264 ±(99.9%) 0.010 ms/op
Iteration   3: 4.938 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.479 ±(99.9%) 12.288 ms/op [Average]
  (min, avg, max) = (4.938, 5.479, 6.233), stdev = 0.674
  CI (99.9%): [≈ 0, 17.767] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.195 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.624 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.758 ±(99.9%) 0.007 ms/op
Iteration   1: 5.829 ±(99.9%) 0.013 ms/op
Iteration   2: 5.578 ±(99.9%) 0.010 ms/op
Iteration   3: 5.315 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.574 ±(99.9%) 4.691 ms/op [Average]
  (min, avg, max) = (5.315, 5.574, 5.829), stdev = 0.257
  CI (99.9%): [0.883, 10.265] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.334 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.761 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.237 ±(99.9%) 0.027 ms/op
Iteration   1: 6.362 ±(99.9%) 0.013 ms/op
Iteration   2: 6.294 ±(99.9%) 0.015 ms/op
Iteration   3: 6.414 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.357 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (6.294, 6.357, 6.414), stdev = 0.060
  CI (99.9%): [5.258, 7.456] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.718 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 6.622 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.614 ±(99.9%) 0.024 ms/op
Iteration   1: 5.760 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.234 ms/op
                 createUser·p0.95:   8.364 ms/op
                 createUser·p0.99:   11.157 ms/op
                 createUser·p0.999:  25.690 ms/op
                 createUser·p0.9999: 29.506 ms/op
                 createUser·p1.00:   31.654 ms/op

Iteration   2: 5.714 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.650 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.698 ms/op
                 createUser·p0.999:  30.082 ms/op
                 createUser·p0.9999: 37.133 ms/op
                 createUser·p1.00:   38.404 ms/op

Iteration   3: 5.697 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   6.898 ms/op
                 createUser·p0.95:   7.913 ms/op
                 createUser·p0.99:   11.092 ms/op
                 createUser·p0.999:  30.644 ms/op
                 createUser·p0.9999: 34.155 ms/op
                 createUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167605
  mean =      5.723 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 49744 
    [ 5.000,  7.500) = 104671 
    [ 7.500, 10.000) = 9932 
    [10.000, 12.500) = 2227 
    [12.500, 15.000) = 595 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 45 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.339 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     26.575 ms/op
     p(99.9900) =     35.536 ms/op
     p(99.9990) =     38.315 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.706 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.259 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.352 ±(99.9%) 0.020 ms/op
Iteration   1: 5.184 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.218 ms/op
                 existUser·p0.95:   6.906 ms/op
                 existUser·p0.99:   9.208 ms/op
                 existUser·p0.999:  23.810 ms/op
                 existUser·p0.9999: 34.493 ms/op
                 existUser·p1.00:   35.783 ms/op

Iteration   2: 5.272 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.463 ms/op
                 existUser·p0.95:   7.504 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  15.725 ms/op
                 existUser·p0.9999: 33.016 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 5.233 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.150 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   10.292 ms/op
                 existUser·p0.999:  26.939 ms/op
                 existUser·p0.9999: 30.766 ms/op
                 existUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183375
  mean =      5.230 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 94161 
    [ 5.000,  7.500) = 81744 
    [ 7.500, 10.000) = 5644 
    [10.000, 12.500) = 1176 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      9.961 ms/op
     p(99.9000) =     18.117 ms/op
     p(99.9900) =     33.194 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.898 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 6.856 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.710 ±(99.9%) 0.022 ms/op
Iteration   1: 5.701 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.900 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   7.012 ms/op
                 getUser·p0.95:   8.487 ms/op
                 getUser·p0.99:   11.715 ms/op
                 getUser·p0.999:  25.362 ms/op
                 getUser·p0.9999: 36.070 ms/op
                 getUser·p1.00:   36.700 ms/op

Iteration   2: 5.557 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.626 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.651 ms/op
                 getUser·p0.99:   10.453 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 31.400 ms/op
                 getUser·p1.00:   32.604 ms/op

Iteration   3: 5.363 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.954 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.283 ms/op
                 getUser·p0.99:   9.552 ms/op
                 getUser·p0.999:  29.712 ms/op
                 getUser·p0.9999: 32.409 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173292
  mean =      5.537 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 59684 
    [ 5.000,  7.500) = 103609 
    [ 7.500, 10.000) = 7415 
    [10.000, 12.500) = 1733 
    [12.500, 15.000) = 513 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     34.057 ms/op
     p(99.9990) =     36.652 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 15.871 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 7.356 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.359 ±(99.9%) 0.024 ms/op
Iteration   1: 6.717 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.945 ms/op
                 listUser·p0.99:   13.769 ms/op
                 listUser·p0.999:  31.850 ms/op
                 listUser·p0.9999: 35.944 ms/op
                 listUser·p1.00:   36.504 ms/op

Iteration   2: 6.935 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   10.519 ms/op
                 listUser·p0.99:   13.697 ms/op
                 listUser·p0.999:  37.093 ms/op
                 listUser·p0.9999: 40.889 ms/op
                 listUser·p1.00:   42.533 ms/op

Iteration   3: 6.774 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   6.316 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   9.880 ms/op
                 listUser·p0.99:   13.451 ms/op
                 listUser·p0.999:  25.452 ms/op
                 listUser·p0.9999: 36.194 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141071
  mean =      6.807 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3050 
    [ 5.000, 10.000) = 130610 
    [10.000, 15.000) = 6560 
    [15.000, 20.000) = 537 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 69 
    [30.000, 35.000) = 101 
    [35.000, 40.000) = 67 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      6.324 ms/op
     p(90.0000) =      8.503 ms/op
     p(95.0000) =     10.125 ms/op
     p(99.0000) =     13.664 ms/op
     p(99.9000) =     31.619 ms/op
     p(99.9900) =     39.715 ms/op
     p(99.9990) =     41.995 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   5.721 ±  3.730  ops/ms
ClientPb.existUser                       thrpt       3   5.884 ±  2.205  ops/ms
ClientPb.getUser                         thrpt       3   5.788 ±  1.345  ops/ms
ClientPb.listUser                        thrpt       3   5.044 ±  1.104  ops/ms
ClientPb.createUser                       avgt       3   5.320 ±  2.411   ms/op
ClientPb.existUser                        avgt       3   5.479 ± 12.288   ms/op
ClientPb.getUser                          avgt       3   5.574 ±  4.691   ms/op
ClientPb.listUser                         avgt       3   6.357 ±  1.099   ms/op
ClientPb.createUser                     sample  167605   5.723 ±  0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.339            ms/op
ClientPb.createUser:createUser·p0.50    sample           5.366            ms/op
ClientPb.createUser:createUser·p0.90    sample           7.152            ms/op
ClientPb.createUser:createUser·p0.95    sample           8.249            ms/op
ClientPb.createUser:createUser·p0.99    sample          11.338            ms/op
ClientPb.createUser:createUser·p0.999   sample          26.575            ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.536            ms/op
ClientPb.createUser:createUser·p1.00    sample          38.404            ms/op
ClientPb.existUser                      sample  183375   5.230 ±  0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.430            ms/op
ClientPb.existUser:existUser·p0.50      sample           4.981            ms/op
ClientPb.existUser:existUser·p0.90      sample           6.332            ms/op
ClientPb.existUser:existUser·p0.95      sample           7.143            ms/op
ClientPb.existUser:existUser·p0.99      sample           9.961            ms/op
ClientPb.existUser:existUser·p0.999     sample          18.117            ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.194            ms/op
ClientPb.existUser:existUser·p1.00      sample          35.783            ms/op
ClientPb.getUser                        sample  173292   5.537 ±  0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.954            ms/op
ClientPb.getUser:getUser·p0.50          sample           5.259            ms/op
ClientPb.getUser:getUser·p0.90          sample           6.652            ms/op
ClientPb.getUser:getUser·p0.95          sample           7.741            ms/op
ClientPb.getUser:getUser·p0.99          sample          10.732            ms/op
ClientPb.getUser:getUser·p0.999         sample          20.873            ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.057            ms/op
ClientPb.getUser:getUser·p1.00          sample          36.700            ms/op
ClientPb.listUser                       sample  141071   6.807 ±  0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.114            ms/op
ClientPb.listUser:listUser·p0.50        sample           6.324            ms/op
ClientPb.listUser:listUser·p0.90        sample           8.503            ms/op
ClientPb.listUser:listUser·p0.95        sample          10.125            ms/op
ClientPb.listUser:listUser·p0.99        sample          13.664            ms/op
ClientPb.listUser:listUser·p0.999       sample          31.619            ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.715            ms/op
ClientPb.listUser:listUser·p1.00        sample          42.533            ms/op
