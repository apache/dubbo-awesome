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
# Warmup Iteration   1: 4.652 ops/ms
# Warmup Iteration   2: 12.192 ops/ms
# Warmup Iteration   3: 12.373 ops/ms
Iteration   1: 12.631 ops/ms
Iteration   2: 12.763 ops/ms
Iteration   3: 12.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.681 ±(99.9%) 1.297 ops/ms [Average]
  (min, avg, max) = (12.631, 12.681, 12.763), stdev = 0.071
  CI (99.9%): [11.384, 13.978] (assumes normal distribution)


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
# Warmup Iteration   1: 8.793 ops/ms
# Warmup Iteration   2: 13.177 ops/ms
# Warmup Iteration   3: 13.271 ops/ms
Iteration   1: 13.291 ops/ms
Iteration   2: 13.408 ops/ms
Iteration   3: 13.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.304 ±(99.9%) 1.802 ops/ms [Average]
  (min, avg, max) = (13.212, 13.304, 13.408), stdev = 0.099
  CI (99.9%): [11.501, 15.106] (assumes normal distribution)


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
# Warmup Iteration   1: 7.549 ops/ms
# Warmup Iteration   2: 12.469 ops/ms
# Warmup Iteration   3: 12.645 ops/ms
Iteration   1: 12.747 ops/ms
Iteration   2: 12.823 ops/ms
Iteration   3: 12.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.745 ±(99.9%) 1.433 ops/ms [Average]
  (min, avg, max) = (12.666, 12.745, 12.823), stdev = 0.079
  CI (99.9%): [11.312, 14.178] (assumes normal distribution)


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
# Warmup Iteration   1: 7.005 ops/ms
# Warmup Iteration   2: 10.652 ops/ms
# Warmup Iteration   3: 10.719 ops/ms
Iteration   1: 10.704 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.703 ±(99.9%) 0.383 ops/ms [Average]
  (min, avg, max) = (10.681, 10.703, 10.723), stdev = 0.021
  CI (99.9%): [10.320, 11.085] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.557 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (2.495, 2.520, 2.557), stdev = 0.033
  CI (99.9%): [1.922, 3.119] (assumes normal distribution)


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.004 ms/op
Iteration   1: 2.427 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
Iteration   3: 2.411 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.411, 2.426, 2.440), stdev = 0.014
  CI (99.9%): [2.163, 2.689] (assumes normal distribution)


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.489 ±(99.9%) 0.064 ms/op [Average]
  (min, avg, max) = (2.487, 2.489, 2.493), stdev = 0.004
  CI (99.9%): [2.425, 2.553] (assumes normal distribution)


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
# Warmup Iteration   1: 4.663 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.005 ms/op
Iteration   1: 3.026 ±(99.9%) 0.005 ms/op
Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.002, 3.015, 3.026), stdev = 0.012
  CI (99.9%): [2.797, 3.232] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  6.904 ms/op
                 createUser·p0.9999: 14.128 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  7.346 ms/op
                 createUser·p0.9999: 14.139 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.063 ms/op
                 createUser·p0.9999: 9.803 ms/op
                 createUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386405
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 189048 
    [ 2.500,  3.750) = 193495 
    [ 3.750,  5.000) = 3154 
    [ 5.000,  6.250) = 228 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      7.589 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
Iteration   1: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  6.503 ms/op
                 existUser·p0.9999: 13.375 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  5.618 ms/op
                 existUser·p0.9999: 12.583 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  7.971 ms/op
                 existUser·p0.9999: 11.615 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392519
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 194974 
    [ 2.500,  3.750) = 194501 
    [ 3.750,  5.000) = 2324 
    [ 5.000,  6.250) = 246 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      6.340 ms/op
     p(99.9900) =     13.021 ms/op
     p(99.9990) =     13.911 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.006 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  5.897 ms/op
                 getUser·p0.9999: 13.140 ms/op
                 getUser·p1.00:   13.533 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  6.588 ms/op
                 getUser·p0.9999: 11.878 ms/op
                 getUser·p1.00:   12.534 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.052 ms/op
                 getUser·p0.999:  7.579 ms/op
                 getUser·p0.9999: 11.485 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391410
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 197221 
    [ 2.500,  3.750) = 189755 
    [ 3.750,  5.000) = 3561 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      6.588 ms/op
     p(99.9900) =     12.630 ms/op
     p(99.9990) =     13.371 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
Iteration   1: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.656 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  10.189 ms/op
                 listUser·p0.9999: 11.835 ms/op
                 listUser·p1.00:   13.287 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 10.813 ms/op
                 listUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318363
  mean =      3.012 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 88610 
    [ 2.500,  3.750) = 190982 
    [ 3.750,  5.000) = 31831 
    [ 5.000,  6.250) = 5556 
    [ 6.250,  7.500) = 623 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.583 ms/op
     p(99.9900) =     11.605 ms/op
     p(99.9990) =     12.699 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.681 ± 1.297  ops/ms
ClientPb.existUser                       thrpt       3  13.304 ± 1.802  ops/ms
ClientPb.getUser                         thrpt       3  12.745 ± 1.433  ops/ms
ClientPb.listUser                        thrpt       3  10.703 ± 0.383  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.599   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.263   ms/op
ClientPb.getUser                          avgt       3   2.489 ± 0.064   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.217   ms/op
ClientPb.createUser                     sample  386405   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.852           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.589           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.041           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  392519   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.671           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.340           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.021           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.041           ms/op
ClientPb.getUser                        sample  391410   2.450 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.714           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.588           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.630           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.533           ms/op
ClientPb.listUser                       sample  318363   3.012 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.768           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.583           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.605           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.287           ms/op
