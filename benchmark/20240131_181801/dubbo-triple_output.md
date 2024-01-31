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
# Warmup Iteration   1: 4.944 ops/ms
# Warmup Iteration   2: 12.216 ops/ms
# Warmup Iteration   3: 12.445 ops/ms
Iteration   1: 12.739 ops/ms
Iteration   2: 12.776 ops/ms
Iteration   3: 12.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.821 ±(99.9%) 2.025 ops/ms [Average]
  (min, avg, max) = (12.739, 12.821, 12.947), stdev = 0.111
  CI (99.9%): [10.796, 14.846] (assumes normal distribution)


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
# Warmup Iteration   1: 8.155 ops/ms
# Warmup Iteration   2: 12.898 ops/ms
# Warmup Iteration   3: 13.077 ops/ms
Iteration   1: 13.206 ops/ms
Iteration   2: 13.204 ops/ms
Iteration   3: 13.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.179 ±(99.9%) 0.825 ops/ms [Average]
  (min, avg, max) = (13.127, 13.179, 13.206), stdev = 0.045
  CI (99.9%): [12.354, 14.004] (assumes normal distribution)


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
# Warmup Iteration   1: 6.824 ops/ms
# Warmup Iteration   2: 12.434 ops/ms
# Warmup Iteration   3: 12.896 ops/ms
Iteration   1: 12.861 ops/ms
Iteration   2: 12.883 ops/ms
Iteration   3: 12.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.836 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (12.765, 12.836, 12.883), stdev = 0.062
  CI (99.9%): [11.698, 13.975] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.371 ops/ms
# Warmup Iteration   2: 10.401 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.523 ±(99.9%) 2.732 ops/ms [Average]
  (min, avg, max) = (10.357, 10.523, 10.647), stdev = 0.150
  CI (99.9%): [7.791, 13.255] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.564 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.003 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.526 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (2.500, 2.526, 2.564), stdev = 0.033
  CI (99.9%): [1.917, 3.134] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.464 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (2.448, 2.464, 2.477), stdev = 0.015
  CI (99.9%): [2.191, 2.736] (assumes normal distribution)


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.017 ms/op [Average]
  (min, avg, max) = (2.499, 2.500, 2.501), stdev = 0.001
  CI (99.9%): [2.482, 2.517] (assumes normal distribution)


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
# Warmup Iteration   1: 4.681 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.005 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
Iteration   3: 2.968 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.986 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.968, 2.986, 2.997), stdev = 0.016
  CI (99.9%): [2.700, 3.271] (assumes normal distribution)


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  11.205 ms/op
                 createUser·p0.9999: 13.851 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.568 ms/op
                 createUser·p0.999:  10.143 ms/op
                 createUser·p0.9999: 15.694 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  8.607 ms/op
                 createUser·p0.9999: 11.183 ms/op
                 createUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375887
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 181512 
    [ 2.500,  3.750) = 190697 
    [ 3.750,  5.000) = 2923 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.755 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     16.371 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.006 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.433 ms/op
                 existUser·p0.999:  4.973 ms/op
                 existUser·p0.9999: 14.565 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  7.353 ms/op
                 existUser·p0.9999: 13.189 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.845 ms/op
                 existUser·p0.999:  8.311 ms/op
                 existUser·p0.9999: 12.747 ms/op
                 existUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390316
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 196053 
    [ 2.500,  3.750) = 191204 
    [ 3.750,  5.000) = 2388 
    [ 5.000,  6.250) = 235 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      6.027 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     15.209 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  11.694 ms/op
                 getUser·p0.9999: 14.242 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  9.666 ms/op
                 getUser·p0.9999: 16.433 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.915 ms/op
                 getUser·p0.999:  8.509 ms/op
                 getUser·p0.9999: 12.858 ms/op
                 getUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378567
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 185987 
    [ 2.500,  3.750) = 187006 
    [ 3.750,  5.000) = 4152 
    [ 5.000,  6.250) = 816 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =      8.674 ms/op
     p(99.9900) =     14.341 ms/op
     p(99.9990) =     17.177 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.009 ms/op
Iteration   1: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.555 ms/op
                 listUser·p0.9999: 11.723 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.663 ms/op
                 listUser·p0.999:  10.273 ms/op
                 listUser·p0.9999: 13.992 ms/op
                 listUser·p1.00:   14.778 ms/op

Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.667 ms/op
                 listUser·p0.9999: 13.091 ms/op
                 listUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317109
  mean =      3.025 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 90936 
    [ 2.500,  3.750) = 185599 
    [ 3.750,  5.000) = 32723 
    [ 5.000,  6.250) = 6221 
    [ 6.250,  7.500) = 840 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     13.096 ms/op
     p(99.9990) =     14.551 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.821 ± 2.025  ops/ms
ClientPb.existUser                       thrpt       3  13.179 ± 0.825  ops/ms
ClientPb.getUser                         thrpt       3  12.836 ± 1.139  ops/ms
ClientPb.listUser                        thrpt       3  10.523 ± 2.732  ops/ms
ClientPb.createUser                       avgt       3   2.526 ± 0.609   ms/op
ClientPb.existUser                        avgt       3   2.464 ± 0.273   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.017   ms/op
ClientPb.listUser                         avgt       3   2.986 ± 0.285   ms/op
ClientPb.createUser                     sample  375887   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.940           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.755           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.008           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.663           ms/op
ClientPb.existUser                      sample  390316   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.910           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.027           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.303           ms/op
ClientPb.getUser                        sample  378567   2.534 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.823           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.674           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.341           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.302           ms/op
ClientPb.listUser                       sample  317109   3.025 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.823           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.096           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.778           ms/op
