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
# Warmup Iteration   1: 5.020 ops/ms
# Warmup Iteration   2: 11.838 ops/ms
# Warmup Iteration   3: 12.280 ops/ms
Iteration   1: 12.503 ops/ms
Iteration   2: 12.402 ops/ms
Iteration   3: 12.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.469 ±(99.9%) 1.073 ops/ms [Average]
  (min, avg, max) = (12.402, 12.469, 12.504), stdev = 0.059
  CI (99.9%): [11.396, 13.543] (assumes normal distribution)


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
# Warmup Iteration   1: 8.249 ops/ms
# Warmup Iteration   2: 13.014 ops/ms
# Warmup Iteration   3: 13.070 ops/ms
Iteration   1: 12.938 ops/ms
Iteration   2: 13.063 ops/ms
Iteration   3: 13.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.006 ±(99.9%) 1.158 ops/ms [Average]
  (min, avg, max) = (12.938, 13.006, 13.063), stdev = 0.063
  CI (99.9%): [11.848, 14.164] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.472 ops/ms
# Warmup Iteration   2: 12.432 ops/ms
# Warmup Iteration   3: 12.643 ops/ms
Iteration   1: 12.675 ops/ms
Iteration   2: 12.748 ops/ms
Iteration   3: 12.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.784 ±(99.9%) 2.383 ops/ms [Average]
  (min, avg, max) = (12.675, 12.784, 12.929), stdev = 0.131
  CI (99.9%): [10.401, 15.167] (assumes normal distribution)


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
# Warmup Iteration   1: 6.277 ops/ms
# Warmup Iteration   2: 10.239 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.489 ops/ms
Iteration   2: 10.499 ops/ms
Iteration   3: 10.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.459 ±(99.9%) 1.102 ops/ms [Average]
  (min, avg, max) = (10.390, 10.459, 10.499), stdev = 0.060
  CI (99.9%): [9.357, 11.562] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.554 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (2.520, 2.538, 2.554), stdev = 0.017
  CI (99.9%): [2.226, 2.851] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.003 ms/op
Iteration   1: 2.447 ±(99.9%) 0.003 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.441 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (2.428, 2.441, 2.449), stdev = 0.011
  CI (99.9%): [2.237, 2.646] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.565 ±(99.9%) 0.003 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.525 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (2.495, 2.525, 2.565), stdev = 0.036
  CI (99.9%): [1.862, 3.188] (assumes normal distribution)


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
# Warmup Iteration   1: 4.864 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.005 ms/op
Iteration   1: 3.110 ±(99.9%) 0.007 ms/op
Iteration   2: 3.085 ±(99.9%) 0.004 ms/op
Iteration   3: 3.058 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.084 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.058, 3.084, 3.110), stdev = 0.026
  CI (99.9%): [2.608, 3.561] (assumes normal distribution)


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.947 ms/op
                 createUser·p0.999:  11.764 ms/op
                 createUser·p0.9999: 14.458 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  9.523 ms/op
                 createUser·p0.9999: 12.681 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   4.103 ms/op
                 createUser·p0.999:  9.353 ms/op
                 createUser·p0.9999: 18.645 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374936
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 178881 
    [ 2.500,  3.750) = 190949 
    [ 3.750,  5.000) = 3967 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     15.090 ms/op
     p(99.9990) =     18.858 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.485 ms/op
                 existUser·p0.999:  6.355 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  8.505 ms/op
                 existUser·p0.9999: 12.739 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  6.490 ms/op
                 existUser·p0.9999: 12.472 ms/op
                 existUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384059
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 185877 
    [ 2.500,  3.750) = 195339 
    [ 3.750,  5.000) = 2165 
    [ 5.000,  6.250) = 227 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      7.395 ms/op
     p(99.9900) =     13.346 ms/op
     p(99.9990) =     14.246 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
Iteration   1: 2.577 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   3.906 ms/op
                 getUser·p0.999:  11.812 ms/op
                 getUser·p0.9999: 15.771 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   2: 2.605 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.638 ms/op
                 getUser·p0.90:   3.174 ms/op
                 getUser·p0.95:   3.391 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.919 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  9.043 ms/op
                 getUser·p0.9999: 11.944 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 371865
  mean =      2.580 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 178338 
    [ 2.500,  3.750) = 186626 
    [ 3.750,  5.000) = 5586 
    [ 5.000,  6.250) = 725 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      9.390 ms/op
     p(99.9900) =     14.565 ms/op
     p(99.9990) =     15.951 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.031 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.009 ms/op
Iteration   1: 3.109 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.049 ms/op
                 listUser·p0.9999: 10.938 ms/op
                 listUser·p1.00:   11.174 ms/op

Iteration   2: 3.090 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.738 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 12.271 ms/op
                 listUser·p1.00:   13.369 ms/op

Iteration   3: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.606 ms/op
                 listUser·p0.9999: 11.154 ms/op
                 listUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309993
  mean =      3.094 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 77851 
    [ 2.500,  3.750) = 187276 
    [ 3.750,  5.000) = 36375 
    [ 5.000,  6.250) = 6861 
    [ 6.250,  7.500) = 827 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 187 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.338 ms/op
     p(99.9990) =     13.238 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.469 ± 1.073  ops/ms
ClientPb.existUser                       thrpt       3  13.006 ± 1.158  ops/ms
ClientPb.getUser                         thrpt       3  12.784 ± 2.383  ops/ms
ClientPb.listUser                        thrpt       3  10.459 ± 1.102  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.313   ms/op
ClientPb.existUser                        avgt       3   2.441 ± 0.205   ms/op
ClientPb.getUser                          avgt       3   2.525 ± 0.663   ms/op
ClientPb.listUser                         avgt       3   3.084 ± 0.477   ms/op
ClientPb.createUser                     sample  374936   2.558 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.722           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.470           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.090           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.940           ms/op
ClientPb.existUser                      sample  384059   2.497 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.951           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.395           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.346           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.402           ms/op
ClientPb.getUser                        sample  371865   2.580 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.792           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.609           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.390           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.565           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.040           ms/op
ClientPb.listUser                       sample  309993   3.094 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.338           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.369           ms/op
