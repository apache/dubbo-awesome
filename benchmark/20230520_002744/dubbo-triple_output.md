# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.263 ops/ms
# Warmup Iteration   2: 2.817 ops/ms
# Warmup Iteration   3: 5.442 ops/ms
Iteration   1: 5.621 ops/ms
Iteration   2: 5.503 ops/ms
Iteration   3: 5.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.666 ±(99.9%) 3.452 ops/ms [Average]
  (min, avg, max) = (5.503, 5.666, 5.873), stdev = 0.189
  CI (99.9%): [2.214, 9.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.859 ops/ms
# Warmup Iteration   2: 5.249 ops/ms
# Warmup Iteration   3: 6.092 ops/ms
Iteration   1: 6.172 ops/ms
Iteration   2: 6.157 ops/ms
Iteration   3: 6.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.218 ±(99.9%) 1.678 ops/ms [Average]
  (min, avg, max) = (6.157, 6.218, 6.323), stdev = 0.092
  CI (99.9%): [4.540, 7.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.773 ops/ms
# Warmup Iteration   2: 4.883 ops/ms
# Warmup Iteration   3: 5.639 ops/ms
Iteration   1: 5.704 ops/ms
Iteration   2: 5.706 ops/ms
Iteration   3: 6.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.819 ±(99.9%) 3.598 ops/ms [Average]
  (min, avg, max) = (5.704, 5.819, 6.046), stdev = 0.197
  CI (99.9%): [2.220, 9.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.525 ops/ms
# Warmup Iteration   2: 4.363 ops/ms
# Warmup Iteration   3: 5.194 ops/ms
Iteration   1: 5.337 ops/ms
Iteration   2: 5.327 ops/ms
Iteration   3: 5.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.303 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (5.244, 5.303, 5.337), stdev = 0.051
  CI (99.9%): [4.364, 6.242] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.527 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 6.680 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.528 ±(99.9%) 0.016 ms/op
Iteration   1: 5.452 ±(99.9%) 0.012 ms/op
Iteration   2: 5.459 ±(99.9%) 0.012 ms/op
Iteration   3: 5.454 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.455 ±(99.9%) 0.067 ms/op [Average]
  (min, avg, max) = (5.452, 5.455, 5.459), stdev = 0.004
  CI (99.9%): [5.389, 5.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.856 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.393 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.191 ±(99.9%) 0.009 ms/op
Iteration   1: 5.279 ±(99.9%) 0.007 ms/op
Iteration   2: 5.107 ±(99.9%) 0.014 ms/op
Iteration   3: 5.095 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.160 ±(99.9%) 1.879 ms/op [Average]
  (min, avg, max) = (5.095, 5.160, 5.279), stdev = 0.103
  CI (99.9%): [3.281, 7.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.855 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.300 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.480 ±(99.9%) 0.008 ms/op
Iteration   1: 5.548 ±(99.9%) 0.013 ms/op
Iteration   2: 5.631 ±(99.9%) 0.007 ms/op
Iteration   3: 5.421 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.533 ±(99.9%) 1.933 ms/op [Average]
  (min, avg, max) = (5.421, 5.533, 5.631), stdev = 0.106
  CI (99.9%): [3.601, 7.466] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.701 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 7.429 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.503 ±(99.9%) 0.011 ms/op
Iteration   1: 6.405 ±(99.9%) 0.015 ms/op
Iteration   2: 5.985 ±(99.9%) 0.011 ms/op
Iteration   3: 5.928 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.106 ±(99.9%) 4.750 ms/op [Average]
  (min, avg, max) = (5.928, 6.106, 6.405), stdev = 0.260
  CI (99.9%): [1.356, 10.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.618 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 6.151 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.391 ±(99.9%) 0.024 ms/op
Iteration   1: 5.201 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.042 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.463 ms/op
                 createUser·p0.95:   7.250 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  23.345 ms/op
                 createUser·p0.9999: 36.222 ms/op
                 createUser·p1.00:   36.897 ms/op

Iteration   2: 5.478 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.808 ms/op
                 createUser·p0.95:   7.578 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  23.645 ms/op
                 createUser·p0.9999: 27.940 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 5.414 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.980 ms/op
                 createUser·p0.95:   7.660 ms/op
                 createUser·p0.99:   9.880 ms/op
                 createUser·p0.999:  21.970 ms/op
                 createUser·p0.9999: 31.264 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178994
  mean =      5.361 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 83056 
    [ 5.000,  7.500) = 86859 
    [ 7.500, 10.000) = 7207 
    [10.000, 12.500) = 1165 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      7.512 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     36.845 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.087 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.374 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.248 ±(99.9%) 0.020 ms/op
Iteration   1: 4.939 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.044 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.307 ms/op
                 existUser·p0.99:   9.503 ms/op
                 existUser·p0.999:  18.747 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 4.929 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   6.357 ms/op
                 existUser·p0.95:   7.070 ms/op
                 existUser·p0.99:   9.355 ms/op
                 existUser·p0.999:  19.419 ms/op
                 existUser·p0.9999: 28.739 ms/op
                 existUser·p1.00:   30.671 ms/op

Iteration   3: 4.990 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.094 ms/op
                 existUser·p0.99:   9.617 ms/op
                 existUser·p0.999:  24.695 ms/op
                 existUser·p0.9999: 29.923 ms/op
                 existUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193795
  mean =      4.953 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 118859 
    [ 5.000,  7.500) = 67662 
    [ 7.500, 10.000) = 5721 
    [10.000, 12.500) = 907 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     22.289 ms/op
     p(99.9900) =     29.532 ms/op
     p(99.9990) =     30.673 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.772 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.787 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.450 ±(99.9%) 0.023 ms/op
Iteration   1: 5.385 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.163 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   7.905 ms/op
                 getUser·p0.99:   10.043 ms/op
                 getUser·p0.999:  23.428 ms/op
                 getUser·p0.9999: 27.759 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   2: 5.539 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.716 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   7.190 ms/op
                 getUser·p0.95:   7.873 ms/op
                 getUser·p0.99:   10.043 ms/op
                 getUser·p0.999:  26.640 ms/op
                 getUser·p0.9999: 33.509 ms/op
                 getUser·p1.00:   33.948 ms/op

Iteration   3: 5.186 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.478 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.693 ms/op
                 getUser·p0.95:   7.758 ms/op
                 getUser·p0.99:   10.487 ms/op
                 getUser·p0.999:  27.591 ms/op
                 getUser·p0.9999: 33.128 ms/op
                 getUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178741
  mean =      5.366 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 86533 
    [ 5.000,  7.500) = 80200 
    [ 7.500, 10.000) = 9910 
    [10.000, 12.500) = 1491 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      7.004 ms/op
     p(95.0000) =      7.848 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     24.700 ms/op
     p(99.9900) =     32.018 ms/op
     p(99.9990) =     33.976 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.610 ±(99.9%) 0.320 ms/op
# Warmup Iteration   2: 7.332 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.379 ±(99.9%) 0.026 ms/op
Iteration   1: 6.037 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  24.603 ms/op
                 listUser·p0.9999: 27.551 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   2: 5.952 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.740 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  27.132 ms/op
                 listUser·p0.9999: 31.752 ms/op
                 listUser·p1.00:   33.128 ms/op

Iteration   3: 5.948 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  19.798 ms/op
                 listUser·p0.9999: 26.794 ms/op
                 listUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160605
  mean =      5.979 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 37390 
    [ 5.000,  7.500) = 106997 
    [ 7.500, 10.000) = 13520 
    [10.000, 12.500) = 1826 
    [12.500, 15.000) = 432 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      5.734 ms/op
     p(90.0000) =      7.512 ms/op
     p(95.0000) =      8.364 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     24.360 ms/op
     p(99.9900) =     29.188 ms/op
     p(99.9990) =     32.771 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.666 ± 3.452  ops/ms
ClientPb.existUser                       thrpt       3   6.218 ± 1.678  ops/ms
ClientPb.getUser                         thrpt       3   5.819 ± 3.598  ops/ms
ClientPb.listUser                        thrpt       3   5.303 ± 0.939  ops/ms
ClientPb.createUser                       avgt       3   5.455 ± 0.067   ms/op
ClientPb.existUser                        avgt       3   5.160 ± 1.879   ms/op
ClientPb.getUser                          avgt       3   5.533 ± 1.933   ms/op
ClientPb.listUser                         avgt       3   6.106 ± 4.750   ms/op
ClientPb.createUser                     sample  178994   5.361 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.489           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.079           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.783           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.512           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.011           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.610           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.261           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.897           ms/op
ClientPb.existUser                      sample  193795   4.953 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.528           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.143           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.470           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.289           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.532           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.704           ms/op
ClientPb.getUser                        sample  178741   5.366 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.163           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.004           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.848           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.240           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.700           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.018           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  160605   5.979 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.364           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.797           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.360           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.188           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.128           ms/op
