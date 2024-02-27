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
# Warmup Iteration   1: 5.213 ops/ms
# Warmup Iteration   2: 12.110 ops/ms
# Warmup Iteration   3: 12.440 ops/ms
Iteration   1: 12.597 ops/ms
Iteration   2: 12.742 ops/ms
Iteration   3: 12.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.673 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (12.597, 12.673, 12.742), stdev = 0.072
  CI (99.9%): [11.350, 13.995] (assumes normal distribution)


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
# Warmup Iteration   1: 8.370 ops/ms
# Warmup Iteration   2: 13.109 ops/ms
# Warmup Iteration   3: 13.119 ops/ms
Iteration   1: 13.031 ops/ms
Iteration   2: 13.145 ops/ms
Iteration   3: 13.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.109 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (13.031, 13.109, 13.152), stdev = 0.068
  CI (99.9%): [11.873, 14.345] (assumes normal distribution)


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
# Warmup Iteration   1: 7.885 ops/ms
# Warmup Iteration   2: 12.911 ops/ms
# Warmup Iteration   3: 12.972 ops/ms
Iteration   1: 13.025 ops/ms
Iteration   2: 13.157 ops/ms
Iteration   3: 13.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.111 ±(99.9%) 1.367 ops/ms [Average]
  (min, avg, max) = (13.025, 13.111, 13.157), stdev = 0.075
  CI (99.9%): [11.744, 14.478] (assumes normal distribution)


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
# Warmup Iteration   1: 7.096 ops/ms
# Warmup Iteration   2: 10.748 ops/ms
# Warmup Iteration   3: 10.881 ops/ms
Iteration   1: 10.842 ops/ms
Iteration   2: 10.846 ops/ms
Iteration   3: 10.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.817 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (10.764, 10.817, 10.846), stdev = 0.046
  CI (99.9%): [9.978, 11.657] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.003 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.489, 2.502, 2.512), stdev = 0.012
  CI (99.9%): [2.292, 2.712] (assumes normal distribution)


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.004 ms/op
Iteration   1: 2.395 ±(99.9%) 0.003 ms/op
Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
Iteration   3: 2.402 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.409 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.395, 2.409, 2.430), stdev = 0.019
  CI (99.9%): [2.071, 2.747] (assumes normal distribution)


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.483 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.483, 2.496, 2.503), stdev = 0.011
  CI (99.9%): [2.298, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.005 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
Iteration   3: 2.995 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.000 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.995, 3.000, 3.007), stdev = 0.006
  CI (99.9%): [2.890, 3.109] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  11.813 ms/op
                 createUser·p0.9999: 14.008 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 11.898 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  8.991 ms/op
                 createUser·p0.9999: 11.637 ms/op
                 createUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381206
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 181732 
    [ 2.500,  3.750) = 195045 
    [ 3.750,  5.000) = 3534 
    [ 5.000,  6.250) = 351 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.208 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.293 ms/op
                 existUser·p0.999:  7.133 ms/op
                 existUser·p0.9999: 13.566 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  7.609 ms/op
                 existUser·p0.9999: 12.302 ms/op
                 existUser·p1.00:   12.829 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.648 ms/op
                 existUser·p0.999:  7.645 ms/op
                 existUser·p0.9999: 11.615 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392442
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 195625 
    [ 2.500,  3.750) = 194077 
    [ 3.750,  5.000) = 2016 
    [ 5.000,  6.250) = 253 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.498 ms/op
     p(99.9000) =      7.468 ms/op
     p(99.9900) =     12.792 ms/op
     p(99.9990) =     14.288 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  6.802 ms/op
                 getUser·p0.9999: 13.697 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.403 ms/op
                 getUser·p0.9999: 12.337 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.547 ms/op
                 getUser·p0.999:  7.538 ms/op
                 getUser·p0.9999: 10.405 ms/op
                 getUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388132
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 194605 
    [ 2.500,  3.750) = 188977 
    [ 3.750,  5.000) = 3495 
    [ 5.000,  6.250) = 565 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
Iteration   1: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.618 ms/op
                 listUser·p0.9999: 10.210 ms/op
                 listUser·p1.00:   11.338 ms/op

Iteration   2: 2.941 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 11.115 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   3: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.048 ms/op
                 listUser·p0.9999: 10.684 ms/op
                 listUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324065
  mean =      2.960 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 103741 
    [ 2.500,  3.750) = 184163 
    [ 3.750,  5.000) = 29624 
    [ 5.000,  6.250) = 5130 
    [ 6.250,  7.500) = 600 
    [ 7.500,  8.750) = 297 
    [ 8.750, 10.000) = 297 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     10.836 ms/op
     p(99.9990) =     11.592 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.673 ± 1.322  ops/ms
ClientPb.existUser                       thrpt       3  13.109 ± 1.236  ops/ms
ClientPb.getUser                         thrpt       3  13.111 ± 1.367  ops/ms
ClientPb.listUser                        thrpt       3  10.817 ± 0.840  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.210   ms/op
ClientPb.existUser                        avgt       3   2.409 ± 0.338   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.198   ms/op
ClientPb.listUser                         avgt       3   3.000 ± 0.110   ms/op
ClientPb.createUser                     sample  381206   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.808           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.451           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.713           ms/op
ClientPb.existUser                      sample  392442   2.444 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.904           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.468           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.792           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.336           ms/op
ClientPb.getUser                        sample  388132   2.471 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.827           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.062           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.993           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  324065   2.960 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.811           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.913           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.836           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.255           ms/op
