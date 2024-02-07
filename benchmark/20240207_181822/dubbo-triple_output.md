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
# Warmup Iteration   1: 4.704 ops/ms
# Warmup Iteration   2: 11.989 ops/ms
# Warmup Iteration   3: 12.173 ops/ms
Iteration   1: 12.291 ops/ms
Iteration   2: 12.460 ops/ms
Iteration   3: 12.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.477 ±(99.9%) 3.570 ops/ms [Average]
  (min, avg, max) = (12.291, 12.477, 12.681), stdev = 0.196
  CI (99.9%): [8.907, 16.048] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.074 ops/ms
# Warmup Iteration   2: 12.941 ops/ms
# Warmup Iteration   3: 13.067 ops/ms
Iteration   1: 13.113 ops/ms
Iteration   2: 13.067 ops/ms
Iteration   3: 13.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.088 ±(99.9%) 0.426 ops/ms [Average]
  (min, avg, max) = (13.067, 13.088, 13.113), stdev = 0.023
  CI (99.9%): [12.662, 13.514] (assumes normal distribution)


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
# Warmup Iteration   1: 7.937 ops/ms
# Warmup Iteration   2: 12.464 ops/ms
# Warmup Iteration   3: 12.706 ops/ms
Iteration   1: 12.848 ops/ms
Iteration   2: 12.668 ops/ms
Iteration   3: 12.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.751 ±(99.9%) 1.655 ops/ms [Average]
  (min, avg, max) = (12.668, 12.751, 12.848), stdev = 0.091
  CI (99.9%): [11.096, 14.406] (assumes normal distribution)


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
# Warmup Iteration   1: 6.660 ops/ms
# Warmup Iteration   2: 10.402 ops/ms
# Warmup Iteration   3: 10.549 ops/ms
Iteration   1: 10.597 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.524 ±(99.9%) 1.686 ops/ms [Average]
  (min, avg, max) = (10.420, 10.524, 10.597), stdev = 0.092
  CI (99.9%): [8.838, 12.210] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.672 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.004 ms/op
Iteration   1: 2.597 ±(99.9%) 0.005 ms/op
Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
Iteration   3: 2.571 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.578 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.568, 2.578, 2.597), stdev = 0.016
  CI (99.9%): [2.283, 2.874] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.934 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.481 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.475, 2.481, 2.484), stdev = 0.005
  CI (99.9%): [2.385, 2.577] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.026 ms/op [Average]
  (min, avg, max) = (2.482, 2.484, 2.485), stdev = 0.001
  CI (99.9%): [2.458, 2.510] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.648 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.004 ms/op
Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
Iteration   3: 2.992 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.983 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (2.968, 2.983, 2.992), stdev = 0.013
  CI (99.9%): [2.750, 3.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  11.794 ms/op
                 createUser·p0.9999: 14.251 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  9.780 ms/op
                 createUser·p0.9999: 11.996 ms/op
                 createUser·p1.00:   12.255 ms/op

Iteration   3: 2.582 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  7.055 ms/op
                 createUser·p0.9999: 10.764 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375976
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 179965 
    [ 2.500,  3.750) = 191178 
    [ 3.750,  5.000) = 3888 
    [ 5.000,  6.250) = 394 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      7.881 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     16.547 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  5.273 ms/op
                 existUser·p0.9999: 15.155 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  8.221 ms/op
                 existUser·p0.9999: 13.093 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  9.452 ms/op
                 existUser·p0.9999: 11.452 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389113
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 193481 
    [ 2.500,  3.750) = 192027 
    [ 3.750,  5.000) = 2768 
    [ 5.000,  6.250) = 332 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      7.660 ms/op
     p(99.9900) =     14.270 ms/op
     p(99.9990) =     15.223 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  7.023 ms/op
                 getUser·p0.9999: 14.190 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  9.349 ms/op
                 getUser·p0.9999: 14.125 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  9.781 ms/op
                 getUser·p0.9999: 11.572 ms/op
                 getUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381780
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 188732 
    [ 2.500,  3.750) = 187188 
    [ 3.750,  5.000) = 4506 
    [ 5.000,  6.250) = 885 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =      9.360 ms/op
     p(99.9900) =     13.907 ms/op
     p(99.9990) =     14.683 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 4.867 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.009 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.471 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.019 ms/op
                 listUser·p0.9999: 10.541 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   2: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.733 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.474 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 10.664 ms/op
                 listUser·p1.00:   12.993 ms/op

Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.479 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319924
  mean =      2.997 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 94036 
    [ 2.500,  3.750) = 187139 
    [ 3.750,  5.000) = 31712 
    [ 5.000,  6.250) = 5564 
    [ 6.250,  7.500) = 665 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 307 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.340 ms/op
     p(99.9900) =     10.912 ms/op
     p(99.9990) =     11.938 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.477 ± 3.570  ops/ms
ClientPb.existUser                       thrpt       3  13.088 ± 0.426  ops/ms
ClientPb.getUser                         thrpt       3  12.751 ± 1.655  ops/ms
ClientPb.listUser                        thrpt       3  10.524 ± 1.686  ops/ms
ClientPb.createUser                       avgt       3   2.578 ± 0.295   ms/op
ClientPb.existUser                        avgt       3   2.481 ± 0.096   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.026   ms/op
ClientPb.listUser                         avgt       3   2.983 ± 0.233   ms/op
ClientPb.createUser                     sample  375976   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.990           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.881           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.582           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.597           ms/op
ClientPb.existUser                      sample  389113   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.942           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.660           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.270           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.319           ms/op
ClientPb.getUser                        sample  381780   2.512 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.858           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.360           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.907           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.811           ms/op
ClientPb.listUser                       sample  319924   2.997 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.471           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.340           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
