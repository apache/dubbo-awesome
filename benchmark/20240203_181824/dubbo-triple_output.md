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
# Warmup Iteration   1: 4.476 ops/ms
# Warmup Iteration   2: 11.848 ops/ms
# Warmup Iteration   3: 12.313 ops/ms
Iteration   1: 12.552 ops/ms
Iteration   2: 12.616 ops/ms
Iteration   3: 12.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.594 ±(99.9%) 0.654 ops/ms [Average]
  (min, avg, max) = (12.552, 12.594, 12.616), stdev = 0.036
  CI (99.9%): [11.940, 13.247] (assumes normal distribution)


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
# Warmup Iteration   1: 8.075 ops/ms
# Warmup Iteration   2: 12.939 ops/ms
# Warmup Iteration   3: 12.994 ops/ms
Iteration   1: 13.164 ops/ms
Iteration   2: 13.155 ops/ms
Iteration   3: 12.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.097 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (12.971, 13.097, 13.164), stdev = 0.109
  CI (99.9%): [11.112, 15.082] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.738 ops/ms
# Warmup Iteration   2: 12.784 ops/ms
# Warmup Iteration   3: 12.588 ops/ms
Iteration   1: 12.817 ops/ms
Iteration   2: 12.798 ops/ms
Iteration   3: 12.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.764 ±(99.9%) 1.414 ops/ms [Average]
  (min, avg, max) = (12.675, 12.764, 12.817), stdev = 0.078
  CI (99.9%): [11.350, 14.178] (assumes normal distribution)


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
# Warmup Iteration   1: 6.910 ops/ms
# Warmup Iteration   2: 10.515 ops/ms
# Warmup Iteration   3: 10.712 ops/ms
Iteration   1: 10.771 ops/ms
Iteration   2: 10.629 ops/ms
Iteration   3: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.676 ±(99.9%) 1.502 ops/ms [Average]
  (min, avg, max) = (10.627, 10.676, 10.771), stdev = 0.082
  CI (99.9%): [9.174, 12.178] (assumes normal distribution)


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.533 ±(99.9%) 0.005 ms/op
Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.533, 2.549, 2.566), stdev = 0.017
  CI (99.9%): [2.244, 2.854] (assumes normal distribution)


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
Iteration   2: 2.486 ±(99.9%) 0.003 ms/op
Iteration   3: 2.503 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.497 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.486, 2.497, 2.504), stdev = 0.010
  CI (99.9%): [2.310, 2.685] (assumes normal distribution)


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.513 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (2.487, 2.500, 2.513), stdev = 0.013
  CI (99.9%): [2.264, 2.736] (assumes normal distribution)


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.005 ms/op
Iteration   1: 3.042 ±(99.9%) 0.005 ms/op
Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
Iteration   3: 3.017 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.017, 3.035, 3.046), stdev = 0.016
  CI (99.9%): [2.742, 3.329] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  11.168 ms/op
                 createUser·p0.9999: 13.880 ms/op
                 createUser·p1.00:   14.467 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.523 ms/op
                 createUser·p0.999:  9.143 ms/op
                 createUser·p0.9999: 12.603 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.893 ms/op
                 createUser·p0.999:  8.786 ms/op
                 createUser·p0.9999: 10.928 ms/op
                 createUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382101
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 184111 
    [ 2.500,  3.750) = 194334 
    [ 3.750,  5.000) = 2745 
    [ 5.000,  6.250) = 374 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.857 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.404 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 3.617 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  5.775 ms/op
                 existUser·p0.9999: 13.173 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.991 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  5.688 ms/op
                 existUser·p0.9999: 12.233 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 12.814 ms/op
                 existUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389173
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 190155 
    [ 2.500,  3.750) = 196133 
    [ 3.750,  5.000) = 2159 
    [ 5.000,  6.250) = 312 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      6.160 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     13.863 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  6.674 ms/op
                 getUser·p0.9999: 16.877 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  9.514 ms/op
                 getUser·p0.9999: 12.819 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.679 ms/op
                 getUser·p0.999:  6.657 ms/op
                 getUser·p0.9999: 10.176 ms/op
                 getUser·p1.00:   10.650 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386532
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 192169 
    [ 2.500,  3.750) = 190358 
    [ 3.750,  5.000) = 2978 
    [ 5.000,  6.250) = 553 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      7.994 ms/op
     p(99.9900) =     13.948 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.849 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
Iteration   1: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.287 ms/op
                 listUser·p0.9999: 11.172 ms/op
                 listUser·p1.00:   12.108 ms/op

Iteration   2: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.487 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 10.850 ms/op
                 listUser·p1.00:   11.452 ms/op

Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.100 ms/op
                 listUser·p0.9999: 12.469 ms/op
                 listUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321295
  mean =      2.985 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 97098 
    [ 2.500,  3.750) = 187021 
    [ 3.750,  5.000) = 30082 
    [ 5.000,  6.250) = 5622 
    [ 6.250,  7.500) = 663 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.800 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.594 ± 0.654  ops/ms
ClientPb.existUser                       thrpt       3  13.097 ± 1.985  ops/ms
ClientPb.getUser                         thrpt       3  12.764 ± 1.414  ops/ms
ClientPb.listUser                        thrpt       3  10.676 ± 1.502  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.305   ms/op
ClientPb.existUser                        avgt       3   2.497 ± 0.188   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.236   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.293   ms/op
ClientPb.createUser                     sample  382101   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.813           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.857           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.204           ms/op
ClientPb.existUser                      sample  389173   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.808           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.160           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.894           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.943           ms/op
ClientPb.getUser                        sample  386532   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.699           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.994           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.948           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.629           ms/op
ClientPb.listUser                       sample  321295   2.985 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.943           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.800           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.173           ms/op
