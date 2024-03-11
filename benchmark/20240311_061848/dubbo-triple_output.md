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
# Warmup Iteration   1: 5.168 ops/ms
# Warmup Iteration   2: 12.407 ops/ms
# Warmup Iteration   3: 12.644 ops/ms
Iteration   1: 12.917 ops/ms
Iteration   2: 13.045 ops/ms
Iteration   3: 13.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.996 ±(99.9%) 1.250 ops/ms [Average]
  (min, avg, max) = (12.917, 12.996, 13.045), stdev = 0.068
  CI (99.9%): [11.746, 14.245] (assumes normal distribution)


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
# Warmup Iteration   1: 8.431 ops/ms
# Warmup Iteration   2: 13.487 ops/ms
# Warmup Iteration   3: 13.440 ops/ms
Iteration   1: 13.448 ops/ms
Iteration   2: 13.481 ops/ms
Iteration   3: 13.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.465 ±(99.9%) 0.299 ops/ms [Average]
  (min, avg, max) = (13.448, 13.465, 13.481), stdev = 0.016
  CI (99.9%): [13.166, 13.763] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.819 ops/ms
# Warmup Iteration   2: 12.966 ops/ms
# Warmup Iteration   3: 12.724 ops/ms
Iteration   1: 13.141 ops/ms
Iteration   2: 13.080 ops/ms
Iteration   3: 12.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.045 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (12.913, 13.045, 13.141), stdev = 0.118
  CI (99.9%): [10.892, 15.198] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.664 ops/ms
# Warmup Iteration   2: 10.851 ops/ms
# Warmup Iteration   3: 10.658 ops/ms
Iteration   1: 10.924 ops/ms
Iteration   2: 10.838 ops/ms
Iteration   3: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.862 ±(99.9%) 0.990 ops/ms [Average]
  (min, avg, max) = (10.825, 10.862, 10.924), stdev = 0.054
  CI (99.9%): [9.873, 11.852] (assumes normal distribution)


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.452 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.441, 2.452, 2.472), stdev = 0.017
  CI (99.9%): [2.142, 2.762] (assumes normal distribution)


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.405 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.390 ±(99.9%) 0.005 ms/op
Iteration   1: 2.359 ±(99.9%) 0.004 ms/op
Iteration   2: 2.387 ±(99.9%) 0.004 ms/op
Iteration   3: 2.371 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.372 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (2.359, 2.372, 2.387), stdev = 0.014
  CI (99.9%): [2.123, 2.622] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.003 ms/op
Iteration   1: 2.472 ±(99.9%) 0.004 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.446 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.456 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (2.446, 2.456, 2.472), stdev = 0.014
  CI (99.9%): [2.195, 2.716] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.530 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.004 ms/op
Iteration   1: 2.961 ±(99.9%) 0.004 ms/op
Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
Iteration   3: 2.957 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.957 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (2.955, 2.957, 2.961), stdev = 0.003
  CI (99.9%): [2.905, 3.010] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.666 ms/op
                 createUser·p0.999:  10.517 ms/op
                 createUser·p0.9999: 13.943 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  8.693 ms/op
                 createUser·p0.9999: 12.111 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  7.591 ms/op
                 createUser·p0.9999: 11.651 ms/op
                 createUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383563
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 185339 
    [ 2.500,  3.750) = 194783 
    [ 3.750,  5.000) = 2678 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      7.609 ms/op
     p(99.9900) =     13.538 ms/op
     p(99.9990) =     14.817 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.463 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.396 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.407 ±(99.9%) 0.005 ms/op
Iteration   1: 2.376 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.400 ms/op
                 existUser·p0.999:  5.116 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.365 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   2.413 ms/op
                 existUser·p0.90:   2.871 ms/op
                 existUser·p0.95:   2.974 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  8.208 ms/op
                 existUser·p0.9999: 13.541 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   3: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  8.107 ms/op
                 existUser·p0.9999: 12.414 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402906
  mean =      2.380 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 210802 
    [ 2.500,  3.750) = 189338 
    [ 3.750,  5.000) = 2030 
    [ 5.000,  6.250) = 220 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.429 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =      7.709 ms/op
     p(99.9900) =     13.416 ms/op
     p(99.9990) =     14.237 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.084 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  5.933 ms/op
                 getUser·p0.9999: 14.041 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  9.914 ms/op
                 getUser·p0.9999: 17.564 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  7.539 ms/op
                 getUser·p0.9999: 11.166 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385593
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 193323 
    [ 2.500,  3.750) = 186645 
    [ 3.750,  5.000) = 4563 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      7.822 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     17.831 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.008 ms/op
Iteration   1: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.735 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  8.651 ms/op
                 listUser·p0.9999: 10.125 ms/op
                 listUser·p1.00:   10.666 ms/op

Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.686 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 11.026 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   3: 2.939 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.067 ms/op
                 listUser·p0.9999: 10.717 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324993
  mean =      2.951 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 103449 
    [ 2.500,  3.750) = 184969 
    [ 3.750,  5.000) = 29151 
    [ 5.000,  6.250) = 5946 
    [ 6.250,  7.500) = 626 
    [ 7.500,  8.750) = 293 
    [ 8.750, 10.000) = 279 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     10.772 ms/op
     p(99.9990) =     11.473 ms/op
     p(99.9999) =     11.731 ms/op
    p(100.0000) =     11.731 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.996 ± 1.250  ops/ms
ClientPb.existUser                       thrpt       3  13.465 ± 0.299  ops/ms
ClientPb.getUser                         thrpt       3  13.045 ± 2.153  ops/ms
ClientPb.listUser                        thrpt       3  10.862 ± 0.990  ops/ms
ClientPb.createUser                       avgt       3   2.452 ± 0.310   ms/op
ClientPb.existUser                        avgt       3   2.372 ± 0.250   ms/op
ClientPb.getUser                          avgt       3   2.456 ± 0.261   ms/op
ClientPb.listUser                         avgt       3   2.957 ± 0.052   ms/op
ClientPb.createUser                     sample  383563   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.565           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.609           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.538           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.794           ms/op
ClientPb.existUser                      sample  402906   2.380 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.873           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.429           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.896           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.709           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.416           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  385593   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.641           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.822           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.121           ms/op
ClientPb.listUser                       sample  324993   2.951 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.686           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.884           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.946           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.772           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.731           ms/op
