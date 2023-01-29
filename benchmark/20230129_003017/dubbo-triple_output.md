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
# Warmup Iteration   1: 2.637 ops/ms
# Warmup Iteration   2: 5.990 ops/ms
# Warmup Iteration   3: 9.713 ops/ms
Iteration   1: 10.250 ops/ms
Iteration   2: 9.833 ops/ms
Iteration   3: 9.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.981 ±(99.9%) 4.247 ops/ms [Average]
  (min, avg, max) = (9.833, 9.981, 10.250), stdev = 0.233
  CI (99.9%): [5.734, 14.229] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ops/ms
# Warmup Iteration   2: 9.294 ops/ms
# Warmup Iteration   3: 10.433 ops/ms
Iteration   1: 10.550 ops/ms
Iteration   2: 10.410 ops/ms
Iteration   3: 10.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.561 ±(99.9%) 2.857 ops/ms [Average]
  (min, avg, max) = (10.410, 10.561, 10.722), stdev = 0.157
  CI (99.9%): [7.704, 13.418] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.141 ops/ms
# Warmup Iteration   2: 9.435 ops/ms
# Warmup Iteration   3: 10.059 ops/ms
Iteration   1: 10.334 ops/ms
Iteration   2: 10.508 ops/ms
Iteration   3: 10.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.432 ±(99.9%) 1.620 ops/ms [Average]
  (min, avg, max) = (10.334, 10.432, 10.508), stdev = 0.089
  CI (99.9%): [8.812, 12.052] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ops/ms
# Warmup Iteration   2: 7.866 ops/ms
# Warmup Iteration   3: 8.515 ops/ms
Iteration   1: 8.556 ops/ms
Iteration   2: 8.745 ops/ms
Iteration   3: 8.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.685 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (8.556, 8.685, 8.753), stdev = 0.111
  CI (99.9%): [6.651, 10.718] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.060 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.005 ms/op
Iteration   1: 3.179 ±(99.9%) 0.007 ms/op
Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
Iteration   3: 3.065 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.094 ±(99.9%) 1.370 ms/op [Average]
  (min, avg, max) = (3.037, 3.094, 3.179), stdev = 0.075
  CI (99.9%): [1.723, 4.464] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.109 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.004 ms/op
Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
Iteration   3: 3.104 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.043 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (2.983, 3.043, 3.104), stdev = 0.061
  CI (99.9%): [1.936, 4.150] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 7.092 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.003 ms/op
Iteration   1: 3.244 ±(99.9%) 0.005 ms/op
Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
Iteration   3: 3.131 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.175 ±(99.9%) 1.110 ms/op [Average]
  (min, avg, max) = (3.131, 3.175, 3.244), stdev = 0.061
  CI (99.9%): [2.065, 4.285] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 8.646 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.003 ms/op
Iteration   1: 3.618 ±(99.9%) 0.009 ms/op
Iteration   2: 3.671 ±(99.9%) 0.006 ms/op
Iteration   3: 3.735 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.675 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.618, 3.675, 3.735), stdev = 0.059
  CI (99.9%): [2.601, 4.748] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.183 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.009 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  12.157 ms/op
                 createUser·p0.9999: 19.648 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.046 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  19.305 ms/op
                 createUser·p0.9999: 23.213 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.240 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  16.290 ms/op
                 createUser·p0.9999: 27.034 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300712
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16811 
    [ 2.500,  5.000) = 278180 
    [ 5.000,  7.500) = 5031 
    [ 7.500, 10.000) = 274 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     28.899 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.766 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 19.825 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  9.643 ms/op
                 existUser·p0.9999: 21.389 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.113 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  13.435 ms/op
                 existUser·p0.9999: 20.304 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314570
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21947 
    [ 2.500,  5.000) = 288167 
    [ 5.000,  7.500) = 3607 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.248 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     12.925 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     21.772 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.073 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.010 ms/op
Iteration   1: 3.170 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.501 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 19.714 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  9.394 ms/op
                 getUser·p0.9999: 23.935 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   3: 3.250 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.022 ms/op
                 getUser·p0.999:  13.127 ms/op
                 getUser·p0.9999: 19.732 ms/op
                 getUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302539
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20210 
    [ 2.500,  5.000) = 274894 
    [ 5.000,  7.500) = 6680 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 188 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     12.106 ms/op
     p(99.9900) =     21.918 ms/op
     p(99.9990) =     24.313 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 8.550 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.012 ms/op
Iteration   1: 3.732 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  15.439 ms/op
                 listUser·p0.9999: 20.396 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 3.667 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.125 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.239 ms/op
                 listUser·p0.9999: 14.668 ms/op
                 listUser·p1.00:   14.778 ms/op

Iteration   3: 3.688 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.017 ms/op
                 listUser·p0.9999: 14.899 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259476
  mean =      3.696 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 251303 
    [ 5.000,  7.500) = 6358 
    [ 7.500, 10.000) = 1126 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     12.919 ms/op
     p(99.9900) =     18.912 ms/op
     p(99.9990) =     20.795 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.981 ± 4.247  ops/ms
ClientPb.existUser                       thrpt       3  10.561 ± 2.857  ops/ms
ClientPb.getUser                         thrpt       3  10.432 ± 1.620  ops/ms
ClientPb.listUser                        thrpt       3   8.685 ± 2.033  ops/ms
ClientPb.createUser                       avgt       3   3.094 ± 1.370   ms/op
ClientPb.existUser                        avgt       3   3.043 ± 1.107   ms/op
ClientPb.getUser                          avgt       3   3.175 ± 1.110   ms/op
ClientPb.listUser                         avgt       3   3.675 ± 1.074   ms/op
ClientPb.createUser                     sample  300712   3.192 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.943           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.843           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.018           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.131           ms/op
ClientPb.existUser                      sample  314570   3.052 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.051           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.925           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.644           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.986           ms/op
ClientPb.getUser                        sample  302539   3.172 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.646           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.106           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.918           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.740           ms/op
ClientPb.listUser                       sample  259476   3.696 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.919           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.594           ms/op
