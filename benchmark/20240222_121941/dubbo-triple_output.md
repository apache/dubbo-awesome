# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.820 ops/ms
# Warmup Iteration   2: 12.161 ops/ms
# Warmup Iteration   3: 12.313 ops/ms
Iteration   1: 12.713 ops/ms
Iteration   2: 12.697 ops/ms
Iteration   3: 12.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.647 ±(99.9%) 1.838 ops/ms [Average]
  (min, avg, max) = (12.531, 12.647, 12.713), stdev = 0.101
  CI (99.9%): [10.809, 14.485] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.900 ops/ms
# Warmup Iteration   2: 13.050 ops/ms
# Warmup Iteration   3: 13.006 ops/ms
Iteration   1: 13.139 ops/ms
Iteration   2: 13.009 ops/ms
Iteration   3: 12.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.936 ±(99.9%) 4.528 ops/ms [Average]
  (min, avg, max) = (12.659, 12.936, 13.139), stdev = 0.248
  CI (99.9%): [8.407, 17.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.825 ops/ms
# Warmup Iteration   2: 13.094 ops/ms
# Warmup Iteration   3: 13.110 ops/ms
Iteration   1: 13.164 ops/ms
Iteration   2: 12.935 ops/ms
Iteration   3: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.958 ±(99.9%) 3.558 ops/ms [Average]
  (min, avg, max) = (12.776, 12.958, 13.164), stdev = 0.195
  CI (99.9%): [9.400, 16.516] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.903 ops/ms
# Warmup Iteration   2: 10.600 ops/ms
# Warmup Iteration   3: 10.730 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.610 ops/ms
Iteration   3: 10.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.628 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (10.582, 10.628, 10.693), stdev = 0.058
  CI (99.9%): [9.579, 11.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (2.477, 2.498, 2.527), stdev = 0.026
  CI (99.9%): [2.028, 2.968] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.004 ms/op
Iteration   1: 2.427 ±(99.9%) 0.003 ms/op
Iteration   2: 2.384 ±(99.9%) 0.003 ms/op
Iteration   3: 2.379 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.397 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (2.379, 2.397, 2.427), stdev = 0.026
  CI (99.9%): [1.920, 2.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.080 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.480 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.467, 2.480, 2.501), stdev = 0.019
  CI (99.9%): [2.140, 2.820] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.825 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.005 ms/op
Iteration   1: 3.010 ±(99.9%) 0.004 ms/op
Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
Iteration   3: 2.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.980, 2.991, 3.010), stdev = 0.017
  CI (99.9%): [2.681, 3.301] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  9.390 ms/op
                 createUser·p0.9999: 13.055 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  9.313 ms/op
                 createUser·p0.9999: 12.323 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  8.757 ms/op
                 createUser·p0.9999: 11.731 ms/op
                 createUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382184
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 185305 
    [ 2.500,  3.750) = 193365 
    [ 3.750,  5.000) = 2824 
    [ 5.000,  6.250) = 234 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     12.814 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.592 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.991 ms/op
                 existUser·p0.9999: 13.287 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  9.396 ms/op
                 existUser·p0.9999: 13.599 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  7.394 ms/op
                 existUser·p0.9999: 12.041 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391605
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 199109 
    [ 2.500,  3.750) = 189171 
    [ 3.750,  5.000) = 2460 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      7.610 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.165 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   4.067 ms/op
                 getUser·p0.999:  10.903 ms/op
                 getUser·p0.9999: 13.261 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  5.979 ms/op
                 getUser·p0.9999: 11.880 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  5.926 ms/op
                 getUser·p0.9999: 10.912 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388448
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 194487 
    [ 2.500,  3.750) = 189888 
    [ 3.750,  5.000) = 2881 
    [ 5.000,  6.250) = 567 
    [ 6.250,  7.500) = 164 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      7.316 ms/op
     p(99.9900) =     12.848 ms/op
     p(99.9990) =     13.541 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.009 ms/op
Iteration   1: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  10.240 ms/op
                 listUser·p0.9999: 11.731 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.700 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 14.664 ms/op
                 listUser·p1.00:   15.122 ms/op

Iteration   3: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.262 ms/op
                 listUser·p0.9999: 11.043 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314524
  mean =      3.049 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 88183 
    [ 2.500,  3.750) = 183080 
    [ 3.750,  5.000) = 34611 
    [ 5.000,  6.250) = 6935 
    [ 6.250,  7.500) = 889 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 195 
    [10.000, 11.250) = 193 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.863 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     15.071 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.647 ± 1.838  ops/ms
ClientPb.existUser                       thrpt       3  12.936 ± 4.528  ops/ms
ClientPb.getUser                         thrpt       3  12.958 ± 3.558  ops/ms
ClientPb.listUser                        thrpt       3  10.628 ± 1.049  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.470   ms/op
ClientPb.existUser                        avgt       3   2.397 ± 0.477   ms/op
ClientPb.getUser                          avgt       3   2.480 ± 0.340   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.310   ms/op
ClientPb.createUser                     sample  382184   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.955           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.765           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.814           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.582           ms/op
ClientPb.existUser                      sample  391605   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.805           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.610           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.418           ms/op
ClientPb.getUser                        sample  388448   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.584           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.316           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.848           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.664           ms/op
ClientPb.listUser                       sample  314524   3.049 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.700           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.863           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.122           ms/op
