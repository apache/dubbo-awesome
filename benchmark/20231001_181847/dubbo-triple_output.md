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
# Warmup Iteration   1: 2.065 ops/ms
# Warmup Iteration   2: 5.124 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.578 ops/ms
Iteration   2: 9.311 ops/ms
Iteration   3: 9.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.994 ±(99.9%) 6.874 ops/ms [Average]
  (min, avg, max) = (8.578, 8.994, 9.311), stdev = 0.377
  CI (99.9%): [2.120, 15.869] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.023 ops/ms
# Warmup Iteration   2: 8.897 ops/ms
# Warmup Iteration   3: 9.287 ops/ms
Iteration   1: 9.569 ops/ms
Iteration   2: 9.478 ops/ms
Iteration   3: 9.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.443 ±(99.9%) 2.668 ops/ms [Average]
  (min, avg, max) = (9.283, 9.443, 9.569), stdev = 0.146
  CI (99.9%): [6.776, 12.111] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.727 ops/ms
# Warmup Iteration   2: 8.003 ops/ms
# Warmup Iteration   3: 9.077 ops/ms
Iteration   1: 8.824 ops/ms
Iteration   2: 9.212 ops/ms
Iteration   3: 9.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.070 ±(99.9%) 3.902 ops/ms [Average]
  (min, avg, max) = (8.824, 9.070, 9.212), stdev = 0.214
  CI (99.9%): [5.168, 12.972] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.753 ops/ms
# Warmup Iteration   2: 7.125 ops/ms
# Warmup Iteration   3: 7.607 ops/ms
Iteration   1: 7.826 ops/ms
Iteration   2: 7.731 ops/ms
Iteration   3: 7.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.803 ±(99.9%) 1.154 ops/ms [Average]
  (min, avg, max) = (7.731, 7.803, 7.851), stdev = 0.063
  CI (99.9%): [6.649, 8.957] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.303 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.007 ms/op
Iteration   1: 3.541 ±(99.9%) 0.005 ms/op
Iteration   2: 3.551 ±(99.9%) 0.005 ms/op
Iteration   3: 3.501 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.531 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (3.501, 3.531, 3.551), stdev = 0.026
  CI (99.9%): [3.049, 4.013] (assumes normal distribution)


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
# Warmup Iteration   1: 8.370 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.005 ms/op
Iteration   1: 3.290 ±(99.9%) 0.005 ms/op
Iteration   2: 3.333 ±(99.9%) 0.003 ms/op
Iteration   3: 3.337 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.320 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.290, 3.320, 3.337), stdev = 0.026
  CI (99.9%): [2.844, 3.795] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.857 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.004 ms/op
Iteration   1: 3.462 ±(99.9%) 0.003 ms/op
Iteration   2: 3.529 ±(99.9%) 0.004 ms/op
Iteration   3: 3.518 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.503 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (3.462, 3.503, 3.529), stdev = 0.036
  CI (99.9%): [2.845, 4.161] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.524 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.252 ±(99.9%) 0.007 ms/op
Iteration   1: 4.236 ±(99.9%) 0.005 ms/op
Iteration   2: 4.191 ±(99.9%) 0.007 ms/op
Iteration   3: 4.179 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.202 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (4.179, 4.202, 4.236), stdev = 0.030
  CI (99.9%): [3.649, 4.755] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.435 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.015 ms/op
Iteration   1: 3.469 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  22.141 ms/op
                 createUser·p0.9999: 24.831 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   2: 3.546 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   7.234 ms/op
                 createUser·p0.999:  23.429 ms/op
                 createUser·p0.9999: 30.474 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   3: 3.537 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  20.981 ms/op
                 createUser·p0.9999: 27.294 ms/op
                 createUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272817
  mean =      3.517 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3231 
    [ 2.500,  5.000) = 260242 
    [ 5.000,  7.500) = 7407 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 161 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     22.321 ms/op
     p(99.9900) =     27.432 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.920 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.011 ms/op
Iteration   1: 3.405 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  13.369 ms/op
                 existUser·p0.9999: 21.201 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.313 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  16.604 ms/op
                 existUser·p0.9999: 23.779 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.395 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.000 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  22.079 ms/op
                 existUser·p0.9999: 29.086 ms/op
                 existUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284678
  mean =      3.370 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9714 
    [ 2.500,  5.000) = 267972 
    [ 5.000,  7.500) = 5489 
    [ 7.500, 10.000) = 863 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.588 ms/op
     p(99.9000) =     15.215 ms/op
     p(99.9900) =     27.837 ms/op
     p(99.9990) =     29.398 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.247 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.012 ms/op
Iteration   1: 3.627 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  21.758 ms/op
                 getUser·p0.9999: 23.790 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.443 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  24.609 ms/op
                 getUser·p0.9999: 29.056 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   3: 3.589 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   7.257 ms/op
                 getUser·p0.999:  22.901 ms/op
                 getUser·p0.9999: 29.756 ms/op
                 getUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270221
  mean =      3.551 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4610 
    [ 2.500,  5.000) = 256122 
    [ 5.000,  7.500) = 7486 
    [ 7.500, 10.000) = 1085 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     22.479 ms/op
     p(99.9900) =     29.097 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.442 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.014 ms/op
Iteration   1: 4.101 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.901 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  20.875 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 4.255 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  18.443 ms/op
                 listUser·p0.9999: 21.183 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.186 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  16.051 ms/op
                 listUser·p0.9999: 32.300 ms/op
                 listUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229495
  mean =      4.179 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 217372 
    [ 5.000,  7.500) = 8402 
    [ 7.500, 10.000) = 2470 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 317 
    [15.000, 17.500) = 285 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     17.678 ms/op
     p(99.9900) =     23.796 ms/op
     p(99.9990) =     33.161 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.994 ± 6.874  ops/ms
ClientPb.existUser                       thrpt       3   9.443 ± 2.668  ops/ms
ClientPb.getUser                         thrpt       3   9.070 ± 3.902  ops/ms
ClientPb.listUser                        thrpt       3   7.803 ± 1.154  ops/ms
ClientPb.createUser                       avgt       3   3.531 ± 0.482   ms/op
ClientPb.existUser                        avgt       3   3.320 ± 0.476   ms/op
ClientPb.getUser                          avgt       3   3.503 ± 0.658   ms/op
ClientPb.listUser                         avgt       3   4.202 ± 0.553   ms/op
ClientPb.createUser                     sample  272817   3.517 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.372           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.176           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.321           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.432           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.162           ms/op
ClientPb.existUser                      sample  284678   3.370 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.588           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.215           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.837           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.179           ms/op
ClientPb.getUser                        sample  270221   3.551 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.122           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.053           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.479           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.097           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.556           ms/op
ClientPb.listUser                       sample  229495   4.179 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.360           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.678           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.796           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.227           ms/op
