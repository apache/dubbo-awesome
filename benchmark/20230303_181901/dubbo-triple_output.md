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
# Warmup Iteration   1: 1.210 ops/ms
# Warmup Iteration   2: 2.811 ops/ms
# Warmup Iteration   3: 5.314 ops/ms
Iteration   1: 5.603 ops/ms
Iteration   2: 5.776 ops/ms
Iteration   3: 5.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.720 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (5.603, 5.720, 5.780), stdev = 0.101
  CI (99.9%): [3.879, 7.561] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.753 ops/ms
# Warmup Iteration   2: 4.896 ops/ms
# Warmup Iteration   3: 5.886 ops/ms
Iteration   1: 6.128 ops/ms
Iteration   2: 5.930 ops/ms
Iteration   3: 6.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.104 ±(99.9%) 2.984 ops/ms [Average]
  (min, avg, max) = (5.930, 6.104, 6.255), stdev = 0.164
  CI (99.9%): [3.120, 9.089] (assumes normal distribution)


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
# Warmup Iteration   1: 1.599 ops/ms
# Warmup Iteration   2: 5.015 ops/ms
# Warmup Iteration   3: 5.775 ops/ms
Iteration   1: 5.953 ops/ms
Iteration   2: 5.814 ops/ms
Iteration   3: 6.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.934 ±(99.9%) 2.040 ops/ms [Average]
  (min, avg, max) = (5.814, 5.934, 6.035), stdev = 0.112
  CI (99.9%): [3.894, 7.974] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.434 ops/ms
# Warmup Iteration   2: 3.802 ops/ms
# Warmup Iteration   3: 5.104 ops/ms
Iteration   1: 5.133 ops/ms
Iteration   2: 5.068 ops/ms
Iteration   3: 5.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.157 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (5.068, 5.157, 5.270), stdev = 0.103
  CI (99.9%): [3.272, 7.042] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.826 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.372 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.687 ±(99.9%) 0.013 ms/op
Iteration   1: 5.527 ±(99.9%) 0.014 ms/op
Iteration   2: 5.288 ±(99.9%) 0.013 ms/op
Iteration   3: 5.504 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.440 ±(99.9%) 2.402 ms/op [Average]
  (min, avg, max) = (5.288, 5.440, 5.527), stdev = 0.132
  CI (99.9%): [3.038, 7.841] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 15.916 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.213 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.294 ±(99.9%) 0.013 ms/op
Iteration   1: 5.348 ±(99.9%) 0.007 ms/op
Iteration   2: 5.246 ±(99.9%) 0.013 ms/op
Iteration   3: 5.237 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.277 ±(99.9%) 1.131 ms/op [Average]
  (min, avg, max) = (5.237, 5.277, 5.348), stdev = 0.062
  CI (99.9%): [4.146, 6.408] (assumes normal distribution)


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
# Warmup Iteration   1: 15.799 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.136 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.802 ±(99.9%) 0.011 ms/op
Iteration   1: 5.699 ±(99.9%) 0.010 ms/op
Iteration   2: 5.686 ±(99.9%) 0.010 ms/op
Iteration   3: 5.496 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.627 ±(99.9%) 2.070 ms/op [Average]
  (min, avg, max) = (5.496, 5.627, 5.699), stdev = 0.113
  CI (99.9%): [3.557, 7.697] (assumes normal distribution)


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
# Warmup Iteration   1: 19.583 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.760 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.543 ±(99.9%) 0.014 ms/op
Iteration   1: 6.499 ±(99.9%) 0.019 ms/op
Iteration   2: 6.496 ±(99.9%) 0.016 ms/op
Iteration   3: 6.513 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.503 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (6.496, 6.503, 6.513), stdev = 0.009
  CI (99.9%): [6.333, 6.673] (assumes normal distribution)


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
# Warmup Iteration   1: 17.998 ±(99.9%) 0.330 ms/op
# Warmup Iteration   2: 7.162 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.232 ±(99.9%) 0.030 ms/op
Iteration   1: 5.882 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.818 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.651 ms/op
                 createUser·p0.99:   12.482 ms/op
                 createUser·p0.999:  23.978 ms/op
                 createUser·p0.9999: 31.523 ms/op
                 createUser·p1.00:   32.539 ms/op

Iteration   2: 5.836 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   5.546 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.503 ms/op
                 createUser·p0.99:   11.731 ms/op
                 createUser·p0.999:  27.695 ms/op
                 createUser·p0.9999: 32.476 ms/op
                 createUser·p1.00:   33.063 ms/op

Iteration   3: 5.703 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.490 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   6.881 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   11.059 ms/op
                 createUser·p0.999:  27.846 ms/op
                 createUser·p0.9999: 31.293 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 165281
  mean =      5.806 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 36434 
    [ 5.000,  7.500) = 115719 
    [ 7.500, 10.000) = 9662 
    [10.000, 12.500) = 2238 
    [12.500, 15.000) = 755 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 82 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      5.489 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      8.348 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     25.854 ms/op
     p(99.9900) =     31.783 ms/op
     p(99.9990) =     32.785 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 16.272 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.442 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.498 ±(99.9%) 0.020 ms/op
Iteration   1: 5.193 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.380 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.101 ms/op
                 existUser·p0.95:   6.824 ms/op
                 existUser·p0.99:   9.941 ms/op
                 existUser·p0.999:  22.940 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 5.357 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.327 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   7.283 ms/op
                 existUser·p0.99:   10.153 ms/op
                 existUser·p0.999:  15.443 ms/op
                 existUser·p0.9999: 29.597 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   3: 5.425 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   6.668 ms/op
                 existUser·p0.95:   7.438 ms/op
                 existUser·p0.99:   10.387 ms/op
                 existUser·p0.999:  26.874 ms/op
                 existUser·p0.9999: 28.836 ms/op
                 existUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180206
  mean =      5.324 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 82929 
    [ 5.000,  7.500) = 89831 
    [ 7.500, 10.000) = 5510 
    [10.000, 12.500) = 1096 
    [12.500, 15.000) = 446 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      7.201 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     23.324 ms/op
     p(99.9900) =     28.703 ms/op
     p(99.9990) =     30.735 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 17.671 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 7.064 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.693 ±(99.9%) 0.022 ms/op
Iteration   1: 5.714 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.458 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   7.258 ms/op
                 getUser·p0.95:   8.929 ms/op
                 getUser·p0.99:   11.780 ms/op
                 getUser·p0.999:  24.119 ms/op
                 getUser·p0.9999: 27.361 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   2: 5.294 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.291 ms/op
                 getUser·p0.95:   7.217 ms/op
                 getUser·p0.99:   9.830 ms/op
                 getUser·p0.999:  27.246 ms/op
                 getUser·p0.9999: 34.144 ms/op
                 getUser·p1.00:   34.210 ms/op

Iteration   3: 5.482 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   7.667 ms/op
                 getUser·p0.99:   9.699 ms/op
                 getUser·p0.999:  13.124 ms/op
                 getUser·p0.9999: 32.812 ms/op
                 getUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174822
  mean =      5.491 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 69375 
    [ 5.000,  7.500) = 94508 
    [ 7.500, 10.000) = 8161 
    [10.000, 12.500) = 2051 
    [12.500, 15.000) = 379 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     24.483 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     35.291 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 19.484 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 7.772 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.772 ±(99.9%) 0.029 ms/op
Iteration   1: 6.390 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.802 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   12.435 ms/op
                 listUser·p0.999:  29.622 ms/op
                 listUser·p0.9999: 33.292 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   2: 6.566 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.675 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   12.812 ms/op
                 listUser·p0.999:  34.488 ms/op
                 listUser·p0.9999: 37.183 ms/op
                 listUser·p1.00:   40.239 ms/op

Iteration   3: 6.480 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   7.799 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  26.247 ms/op
                 listUser·p0.9999: 30.455 ms/op
                 listUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148178
  mean =      6.478 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6022 
    [ 5.000, 10.000) = 137180 
    [10.000, 15.000) = 4445 
    [15.000, 20.000) = 239 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 125 
    [30.000, 35.000) = 94 
    [35.000, 40.000) = 40 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.675 ms/op
     p(50.0000) =      6.111 ms/op
     p(90.0000) =      7.856 ms/op
     p(95.0000) =      9.175 ms/op
     p(99.0000) =     12.304 ms/op
     p(99.9000) =     29.622 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     39.387 ms/op
     p(99.9999) =     40.239 ms/op
    p(100.0000) =     40.239 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.720 ± 1.841  ops/ms
ClientPb.existUser                       thrpt       3   6.104 ± 2.984  ops/ms
ClientPb.getUser                         thrpt       3   5.934 ± 2.040  ops/ms
ClientPb.listUser                        thrpt       3   5.157 ± 1.885  ops/ms
ClientPb.createUser                       avgt       3   5.440 ± 2.402   ms/op
ClientPb.existUser                        avgt       3   5.277 ± 1.131   ms/op
ClientPb.getUser                          avgt       3   5.627 ± 2.070   ms/op
ClientPb.listUser                         avgt       3   6.503 ± 0.170   ms/op
ClientPb.createUser                     sample  165281   5.806 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.356           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.160           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.348           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.878           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.854           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.783           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.063           ms/op
ClientPb.existUser                      sample  180206   5.324 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.389           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.063           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.431           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.201           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.191           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.324           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.703           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.130           ms/op
ClientPb.getUser                        sample  174822   5.491 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.571           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.954           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.715           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.483           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.013           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  148178   6.478 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.675           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.111           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.856           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.304           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.622           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.372           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.239           ms/op
