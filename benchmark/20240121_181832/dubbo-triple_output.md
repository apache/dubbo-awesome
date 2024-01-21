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
# Warmup Iteration   1: 4.497 ops/ms
# Warmup Iteration   2: 12.065 ops/ms
# Warmup Iteration   3: 12.366 ops/ms
Iteration   1: 12.463 ops/ms
Iteration   2: 12.589 ops/ms
Iteration   3: 12.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.534 ±(99.9%) 1.179 ops/ms [Average]
  (min, avg, max) = (12.463, 12.534, 12.589), stdev = 0.065
  CI (99.9%): [11.355, 13.714] (assumes normal distribution)


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
# Warmup Iteration   1: 8.014 ops/ms
# Warmup Iteration   2: 12.622 ops/ms
# Warmup Iteration   3: 12.815 ops/ms
Iteration   1: 12.867 ops/ms
Iteration   2: 12.879 ops/ms
Iteration   3: 12.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.834 ±(99.9%) 1.228 ops/ms [Average]
  (min, avg, max) = (12.757, 12.834, 12.879), stdev = 0.067
  CI (99.9%): [11.607, 14.062] (assumes normal distribution)


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
# Warmup Iteration   1: 7.793 ops/ms
# Warmup Iteration   2: 12.455 ops/ms
# Warmup Iteration   3: 12.836 ops/ms
Iteration   1: 12.882 ops/ms
Iteration   2: 12.810 ops/ms
Iteration   3: 12.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.824 ±(99.9%) 0.946 ops/ms [Average]
  (min, avg, max) = (12.782, 12.824, 12.882), stdev = 0.052
  CI (99.9%): [11.879, 13.770] (assumes normal distribution)


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
# Warmup Iteration   1: 6.900 ops/ms
# Warmup Iteration   2: 10.356 ops/ms
# Warmup Iteration   3: 10.562 ops/ms
Iteration   1: 10.594 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.572 ±(99.9%) 0.371 ops/ms [Average]
  (min, avg, max) = (10.554, 10.572, 10.594), stdev = 0.020
  CI (99.9%): [10.201, 10.944] (assumes normal distribution)


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
# Warmup Iteration   1: 4.290 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.005 ms/op
Iteration   1: 2.588 ±(99.9%) 0.004 ms/op
Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (2.519, 2.548, 2.588), stdev = 0.036
  CI (99.9%): [1.888, 3.208] (assumes normal distribution)


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.003 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.467, 2.477, 2.485), stdev = 0.009
  CI (99.9%): [2.311, 2.642] (assumes normal distribution)


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.003 ms/op
Iteration   3: 2.496 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.506 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (2.494, 2.506, 2.528), stdev = 0.019
  CI (99.9%): [2.157, 2.855] (assumes normal distribution)


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
Iteration   3: 3.042 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.030 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (3.020, 3.030, 3.042), stdev = 0.011
  CI (99.9%): [2.821, 3.239] (assumes normal distribution)


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.707 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  11.886 ms/op
                 createUser·p0.9999: 13.948 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  8.828 ms/op
                 createUser·p0.9999: 12.435 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 15.318 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375819
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 181317 
    [ 2.500,  3.750) = 190756 
    [ 3.750,  5.000) = 2970 
    [ 5.000,  6.250) = 220 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     14.032 ms/op
     p(99.9990) =     16.980 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  6.007 ms/op
                 existUser·p0.9999: 13.435 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  5.153 ms/op
                 existUser·p0.9999: 13.173 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 12.210 ms/op
                 existUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387599
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 189131 
    [ 2.500,  3.750) = 194517 
    [ 3.750,  5.000) = 2810 
    [ 5.000,  6.250) = 687 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 148 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      7.327 ms/op
     p(99.9900) =     13.181 ms/op
     p(99.9990) =     13.609 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  11.646 ms/op
                 getUser·p0.9999: 13.824 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.557 ms/op
                 getUser·p0.999:  9.880 ms/op
                 getUser·p0.9999: 14.310 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  9.070 ms/op
                 getUser·p0.9999: 22.577 ms/op
                 getUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378520
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185097 
    [ 2.500,  5.000) = 192575 
    [ 5.000,  7.500) = 463 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     14.469 ms/op
     p(99.9990) =     22.879 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 10.525 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 10.673 ms/op
                 listUser·p1.00:   10.961 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 13.894 ms/op
                 listUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318269
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 89337 
    [ 2.500,  3.750) = 190452 
    [ 3.750,  5.000) = 31875 
    [ 5.000,  6.250) = 5193 
    [ 6.250,  7.500) = 613 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 311 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.302 ms/op
     p(99.9900) =     12.815 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.534 ± 1.179  ops/ms
ClientPb.existUser                       thrpt       3  12.834 ± 1.228  ops/ms
ClientPb.getUser                         thrpt       3  12.824 ± 0.946  ops/ms
ClientPb.listUser                        thrpt       3  10.572 ± 0.371  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.660   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.166   ms/op
ClientPb.getUser                          avgt       3   2.506 ± 0.349   ms/op
ClientPb.listUser                         avgt       3   3.030 ± 0.209   ms/op
ClientPb.createUser                     sample  375819   2.552 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.967           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.322           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.032           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.022           ms/op
ClientPb.existUser                      sample  387599   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.916           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.327           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.181           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.565           ms/op
ClientPb.getUser                        sample  378520   2.534 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.768           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.191           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.469           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.003           ms/op
ClientPb.listUser                       sample  318269   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.780           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.302           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.815           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.287           ms/op
