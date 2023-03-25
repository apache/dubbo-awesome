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
# Warmup Iteration   1: 2.173 ops/ms
# Warmup Iteration   2: 5.904 ops/ms
# Warmup Iteration   3: 8.415 ops/ms
Iteration   1: 9.634 ops/ms
Iteration   2: 9.470 ops/ms
Iteration   3: 9.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.419 ±(99.9%) 4.438 ops/ms [Average]
  (min, avg, max) = (9.155, 9.419, 9.634), stdev = 0.243
  CI (99.9%): [4.981, 13.858] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 8.904 ops/ms
# Warmup Iteration   3: 9.787 ops/ms
Iteration   1: 10.007 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 9.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.887 ±(99.9%) 2.072 ops/ms [Average]
  (min, avg, max) = (9.782, 9.887, 10.007), stdev = 0.114
  CI (99.9%): [7.814, 11.959] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ops/ms
# Warmup Iteration   2: 8.851 ops/ms
# Warmup Iteration   3: 9.299 ops/ms
Iteration   1: 9.344 ops/ms
Iteration   2: 9.784 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.524 ±(99.9%) 4.205 ops/ms [Average]
  (min, avg, max) = (9.344, 9.524, 9.784), stdev = 0.230
  CI (99.9%): [5.319, 13.729] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.815 ops/ms
# Warmup Iteration   2: 7.143 ops/ms
# Warmup Iteration   3: 7.936 ops/ms
Iteration   1: 8.061 ops/ms
Iteration   2: 7.938 ops/ms
Iteration   3: 8.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.020 ±(99.9%) 1.309 ops/ms [Average]
  (min, avg, max) = (7.938, 8.020, 8.063), stdev = 0.072
  CI (99.9%): [6.711, 9.329] (assumes normal distribution)


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
# Warmup Iteration   1: 9.732 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.008 ms/op
Iteration   1: 3.400 ±(99.9%) 0.012 ms/op
Iteration   2: 3.391 ±(99.9%) 0.006 ms/op
Iteration   3: 3.367 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.386 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (3.367, 3.386, 3.400), stdev = 0.017
  CI (99.9%): [3.074, 3.698] (assumes normal distribution)


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
# Warmup Iteration   1: 7.468 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.480 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.003 ms/op
Iteration   1: 3.126 ±(99.9%) 0.007 ms/op
Iteration   2: 3.212 ±(99.9%) 0.006 ms/op
Iteration   3: 3.216 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.185 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.126, 3.185, 3.216), stdev = 0.051
  CI (99.9%): [2.260, 4.110] (assumes normal distribution)


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
# Warmup Iteration   1: 8.261 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.003 ms/op
Iteration   1: 3.339 ±(99.9%) 0.008 ms/op
Iteration   2: 3.360 ±(99.9%) 0.007 ms/op
Iteration   3: 3.310 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.336 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.310, 3.336, 3.360), stdev = 0.025
  CI (99.9%): [2.881, 3.791] (assumes normal distribution)


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
# Warmup Iteration   1: 9.255 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.006 ms/op
Iteration   1: 3.935 ±(99.9%) 0.009 ms/op
Iteration   2: 3.927 ±(99.9%) 0.012 ms/op
Iteration   3: 4.092 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.984 ±(99.9%) 1.695 ms/op [Average]
  (min, avg, max) = (3.927, 3.984, 4.092), stdev = 0.093
  CI (99.9%): [2.289, 5.680] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.108 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.010 ms/op
Iteration   1: 3.350 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.812 ms/op
                 createUser·p0.999:  20.135 ms/op
                 createUser·p0.9999: 28.293 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 3.756 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   6.980 ms/op
                 createUser·p0.99:   9.142 ms/op
                 createUser·p0.999:  21.254 ms/op
                 createUser·p0.9999: 43.086 ms/op
                 createUser·p1.00:   43.975 ms/op

Iteration   3: 3.336 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.502 ms/op
                 createUser·p0.999:  18.131 ms/op
                 createUser·p0.9999: 25.253 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276612
  mean =      3.470 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 265611 
    [ 5.000, 10.000) = 10098 
    [10.000, 15.000) = 480 
    [15.000, 20.000) = 165 
    [20.000, 25.000) = 149 
    [25.000, 30.000) = 77 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     18.703 ms/op
     p(99.9900) =     39.016 ms/op
     p(99.9990) =     43.728 ms/op
     p(99.9999) =     43.975 ms/op
    p(100.0000) =     43.975 ms/op


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
# Warmup Iteration   1: 8.815 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.009 ms/op
Iteration   1: 3.255 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.327 ms/op
                 existUser·p0.999:  10.267 ms/op
                 existUser·p0.9999: 23.069 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  22.151 ms/op
                 existUser·p0.9999: 26.702 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  10.802 ms/op
                 existUser·p0.9999: 26.910 ms/op
                 existUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291222
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10510 
    [ 2.500,  5.000) = 275878 
    [ 5.000,  7.500) = 3920 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     14.578 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 8.389 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.011 ms/op
Iteration   1: 3.293 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  14.308 ms/op
                 getUser·p0.9999: 24.773 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  14.705 ms/op
                 getUser·p0.9999: 24.609 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  15.192 ms/op
                 getUser·p0.9999: 24.197 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289285
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9299 
    [ 2.500,  5.000) = 273150 
    [ 5.000,  7.500) = 5627 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 147 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     14.219 ms/op
     p(99.9900) =     24.546 ms/op
     p(99.9990) =     25.147 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 10.637 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.462 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.011 ms/op
Iteration   1: 4.031 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.749 ms/op
                 listUser·p0.999:  19.123 ms/op
                 listUser·p0.9999: 22.321 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 4.047 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 18.064 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.013 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.884 ms/op
                 listUser·p0.999:  15.030 ms/op
                 listUser·p0.9999: 17.567 ms/op
                 listUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238086
  mean =      4.031 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 228445 
    [ 5.000,  7.500) = 7242 
    [ 7.500, 10.000) = 1535 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 245 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     16.219 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     23.158 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.419 ± 4.438  ops/ms
ClientPb.existUser                       thrpt       3   9.887 ± 2.072  ops/ms
ClientPb.getUser                         thrpt       3   9.524 ± 4.205  ops/ms
ClientPb.listUser                        thrpt       3   8.020 ± 1.309  ops/ms
ClientPb.createUser                       avgt       3   3.386 ± 0.312   ms/op
ClientPb.existUser                        avgt       3   3.185 ± 0.925   ms/op
ClientPb.getUser                          avgt       3   3.336 ± 0.455   ms/op
ClientPb.listUser                         avgt       3   3.984 ± 1.695   ms/op
ClientPb.createUser                     sample  276612   3.470 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.427           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.578           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.703           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.016           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.975           ms/op
ClientPb.existUser                      sample  291222   3.296 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.415           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.623           ms/op
ClientPb.getUser                        sample  289285   3.316 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.219           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.546           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.428           ms/op
ClientPb.listUser                       sample  238086   4.031 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.602           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.219           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.692           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.265           ms/op
