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
# Warmup Iteration   1: 1.031 ops/ms
# Warmup Iteration   2: 2.378 ops/ms
# Warmup Iteration   3: 4.724 ops/ms
Iteration   1: 5.148 ops/ms
Iteration   2: 5.299 ops/ms
Iteration   3: 5.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.259 ±(99.9%) 1.768 ops/ms [Average]
  (min, avg, max) = (5.148, 5.259, 5.329), stdev = 0.097
  CI (99.9%): [3.491, 7.027] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.327 ops/ms
# Warmup Iteration   2: 3.800 ops/ms
# Warmup Iteration   3: 5.317 ops/ms
Iteration   1: 5.445 ops/ms
Iteration   2: 5.502 ops/ms
Iteration   3: 5.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.478 ±(99.9%) 0.534 ops/ms [Average]
  (min, avg, max) = (5.445, 5.478, 5.502), stdev = 0.029
  CI (99.9%): [4.944, 6.012] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.408 ops/ms
# Warmup Iteration   2: 4.164 ops/ms
# Warmup Iteration   3: 5.206 ops/ms
Iteration   1: 5.237 ops/ms
Iteration   2: 5.213 ops/ms
Iteration   3: 5.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.278 ±(99.9%) 1.694 ops/ms [Average]
  (min, avg, max) = (5.213, 5.278, 5.385), stdev = 0.093
  CI (99.9%): [3.585, 6.972] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.383 ops/ms
# Warmup Iteration   2: 3.504 ops/ms
# Warmup Iteration   3: 4.280 ops/ms
Iteration   1: 4.499 ops/ms
Iteration   2: 4.421 ops/ms
Iteration   3: 4.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.459 ±(99.9%) 0.713 ops/ms [Average]
  (min, avg, max) = (4.421, 4.459, 4.499), stdev = 0.039
  CI (99.9%): [3.746, 5.171] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 21.119 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 7.594 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.353 ±(99.9%) 0.015 ms/op
Iteration   1: 6.296 ±(99.9%) 0.009 ms/op
Iteration   2: 5.936 ±(99.9%) 0.015 ms/op
Iteration   3: 5.946 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.059 ±(99.9%) 3.739 ms/op [Average]
  (min, avg, max) = (5.936, 6.059, 6.296), stdev = 0.205
  CI (99.9%): [2.320, 9.799] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.630 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.760 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.868 ±(99.9%) 0.008 ms/op
Iteration   1: 5.906 ±(99.9%) 0.010 ms/op
Iteration   2: 5.653 ±(99.9%) 0.010 ms/op
Iteration   3: 5.931 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.830 ±(99.9%) 2.805 ms/op [Average]
  (min, avg, max) = (5.653, 5.830, 5.931), stdev = 0.154
  CI (99.9%): [3.025, 8.636] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 20.023 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 7.236 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.252 ±(99.9%) 0.010 ms/op
Iteration   1: 6.055 ±(99.9%) 0.013 ms/op
Iteration   2: 6.259 ±(99.9%) 0.013 ms/op
Iteration   3: 6.198 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.171 ±(99.9%) 1.914 ms/op [Average]
  (min, avg, max) = (6.055, 6.171, 6.259), stdev = 0.105
  CI (99.9%): [4.256, 8.085] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 22.608 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 9.018 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 7.068 ±(99.9%) 0.017 ms/op
Iteration   1: 7.266 ±(99.9%) 0.011 ms/op
Iteration   2: 6.923 ±(99.9%) 0.018 ms/op
Iteration   3: 7.081 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.090 ±(99.9%) 3.134 ms/op [Average]
  (min, avg, max) = (6.923, 7.090, 7.266), stdev = 0.172
  CI (99.9%): [3.956, 10.225] (assumes normal distribution)


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
# Warmup Iteration   1: 20.449 ±(99.9%) 0.373 ms/op
# Warmup Iteration   2: 8.138 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.480 ±(99.9%) 0.034 ms/op
Iteration   1: 5.931 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.874 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   7.643 ms/op
                 createUser·p0.95:   9.142 ms/op
                 createUser·p0.99:   12.468 ms/op
                 createUser·p0.999:  17.698 ms/op
                 createUser·p0.9999: 23.416 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 5.997 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.081 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   7.758 ms/op
                 createUser·p0.95:   9.077 ms/op
                 createUser·p0.99:   13.533 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 27.951 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 6.374 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.511 ms/op
                 createUser·p0.50:   5.947 ms/op
                 createUser·p0.90:   8.192 ms/op
                 createUser·p0.95:   9.470 ms/op
                 createUser·p0.99:   13.386 ms/op
                 createUser·p0.999:  25.912 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 157562
  mean =      6.095 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 28728 
    [ 5.000,  7.500) = 108609 
    [ 7.500, 10.000) = 14941 
    [10.000, 12.500) = 3330 
    [12.500, 15.000) = 1219 
    [15.000, 17.500) = 400 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      7.905 ms/op
     p(95.0000) =      9.241 ms/op
     p(99.0000) =     13.124 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     29.589 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 19.733 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 6.668 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.045 ±(99.9%) 0.030 ms/op
Iteration   1: 5.881 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   8.184 ms/op
                 existUser·p0.95:   9.355 ms/op
                 existUser·p0.99:   12.821 ms/op
                 existUser·p0.999:  17.203 ms/op
                 existUser·p0.9999: 27.276 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   2: 5.919 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.512 ms/op
                 existUser·p0.50:   5.349 ms/op
                 existUser·p0.90:   8.053 ms/op
                 existUser·p0.95:   9.421 ms/op
                 existUser·p0.99:   13.500 ms/op
                 existUser·p0.999:  28.409 ms/op
                 existUser·p0.9999: 34.524 ms/op
                 existUser·p1.00:   35.586 ms/op

Iteration   3: 5.796 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   7.774 ms/op
                 existUser·p0.95:   9.142 ms/op
                 existUser·p0.99:   12.583 ms/op
                 existUser·p0.999:  29.505 ms/op
                 existUser·p0.9999: 38.042 ms/op
                 existUser·p1.00:   39.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 163552
  mean =      5.865 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 52271 
    [ 5.000,  7.500) = 90865 
    [ 7.500, 10.000) = 14569 
    [10.000, 12.500) = 3874 
    [12.500, 15.000) = 1278 
    [15.000, 17.500) = 394 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 46 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.512 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      8.004 ms/op
     p(95.0000) =      9.306 ms/op
     p(99.0000) =     12.943 ms/op
     p(99.9000) =     23.517 ms/op
     p(99.9900) =     36.776 ms/op
     p(99.9990) =     39.507 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


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
# Warmup Iteration   1: 19.120 ±(99.9%) 0.365 ms/op
# Warmup Iteration   2: 7.654 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.148 ±(99.9%) 0.026 ms/op
Iteration   1: 6.051 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   5.538 ms/op
                 getUser·p0.90:   7.979 ms/op
                 getUser·p0.95:   9.388 ms/op
                 getUser·p0.99:   12.747 ms/op
                 getUser·p0.999:  25.333 ms/op
                 getUser·p0.9999: 34.996 ms/op
                 getUser·p1.00:   36.176 ms/op

Iteration   2: 5.967 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   9.191 ms/op
                 getUser·p0.99:   13.959 ms/op
                 getUser·p0.999:  27.209 ms/op
                 getUser·p0.9999: 30.787 ms/op
                 getUser·p1.00:   32.014 ms/op

Iteration   3: 5.977 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.498 ms/op
                 getUser·p0.50:   5.579 ms/op
                 getUser·p0.90:   7.520 ms/op
                 getUser·p0.95:   8.815 ms/op
                 getUser·p0.99:   12.009 ms/op
                 getUser·p0.999:  28.246 ms/op
                 getUser·p0.9999: 33.925 ms/op
                 getUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 160004
  mean =      5.998 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 35639 
    [ 5.000,  7.500) = 106220 
    [ 7.500, 10.000) = 12680 
    [10.000, 12.500) = 3560 
    [12.500, 15.000) = 1147 
    [15.000, 17.500) = 358 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     12.960 ms/op
     p(99.9000) =     27.263 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     36.137 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 22.624 ±(99.9%) 0.404 ms/op
# Warmup Iteration   2: 8.770 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 7.621 ±(99.9%) 0.036 ms/op
Iteration   1: 7.375 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   3.310 ms/op
                 listUser·p0.50:   6.717 ms/op
                 listUser·p0.90:   9.912 ms/op
                 listUser·p0.95:   11.445 ms/op
                 listUser·p0.99:   15.360 ms/op
                 listUser·p0.999:  29.590 ms/op
                 listUser·p0.9999: 33.532 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   2: 7.386 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   3.502 ms/op
                 listUser·p0.50:   6.660 ms/op
                 listUser·p0.90:   10.093 ms/op
                 listUser·p0.95:   11.731 ms/op
                 listUser·p0.99:   15.538 ms/op
                 listUser·p0.999:  28.041 ms/op
                 listUser·p0.9999: 31.512 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   3: 7.415 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   6.742 ms/op
                 listUser·p0.90:   10.060 ms/op
                 listUser·p0.95:   11.338 ms/op
                 listUser·p0.99:   14.848 ms/op
                 listUser·p0.999:  30.441 ms/op
                 listUser·p0.9999: 32.758 ms/op
                 listUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 129786
  mean =      7.392 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 1828 
    [ 5.000,  7.500) = 87361 
    [ 7.500, 10.000) = 27516 
    [10.000, 12.500) = 9068 
    [12.500, 15.000) = 2529 
    [15.000, 17.500) = 957 
    [17.500, 20.000) = 228 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 84 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      6.709 ms/op
     p(90.0000) =     10.027 ms/op
     p(95.0000) =     11.502 ms/op
     p(99.0000) =     15.272 ms/op
     p(99.9000) =     29.538 ms/op
     p(99.9900) =     32.769 ms/op
     p(99.9990) =     34.302 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.259 ± 1.768  ops/ms
ClientPb.existUser                       thrpt       3   5.478 ± 0.534  ops/ms
ClientPb.getUser                         thrpt       3   5.278 ± 1.694  ops/ms
ClientPb.listUser                        thrpt       3   4.459 ± 0.713  ops/ms
ClientPb.createUser                       avgt       3   6.059 ± 3.739   ms/op
ClientPb.existUser                        avgt       3   5.830 ± 2.805   ms/op
ClientPb.getUser                          avgt       3   6.171 ± 1.914   ms/op
ClientPb.listUser                         avgt       3   7.090 ± 3.134   ms/op
ClientPb.createUser                     sample  157562   6.095 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.511           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.905           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.241           ms/op
ClientPb.createUser:createUser·p0.99    sample          13.124           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.708           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.017           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.721           ms/op
ClientPb.existUser                      sample  163552   5.865 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.512           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.90      sample           8.004           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.306           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.943           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.776           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.715           ms/op
ClientPb.getUser                        sample  160004   5.998 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.498           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.521           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.717           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.110           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.960           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.263           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.341           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  129786   7.392 ± 0.020   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.963           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.90        sample          10.027           ms/op
ClientPb.listUser:listUser·p0.95        sample          11.502           ms/op
ClientPb.listUser:listUser·p0.99        sample          15.272           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.538           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.769           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.341           ms/op
