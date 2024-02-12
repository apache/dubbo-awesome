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
# Warmup Iteration   1: 4.834 ops/ms
# Warmup Iteration   2: 11.866 ops/ms
# Warmup Iteration   3: 12.495 ops/ms
Iteration   1: 12.530 ops/ms
Iteration   2: 12.591 ops/ms
Iteration   3: 12.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.494 ±(99.9%) 2.181 ops/ms [Average]
  (min, avg, max) = (12.360, 12.494, 12.591), stdev = 0.120
  CI (99.9%): [10.313, 14.675] (assumes normal distribution)


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
# Warmup Iteration   1: 7.738 ops/ms
# Warmup Iteration   2: 13.045 ops/ms
# Warmup Iteration   3: 13.256 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 13.320 ops/ms
Iteration   3: 13.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.149 ±(99.9%) 2.711 ops/ms [Average]
  (min, avg, max) = (13.060, 13.149, 13.320), stdev = 0.149
  CI (99.9%): [10.438, 15.860] (assumes normal distribution)


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
# Warmup Iteration   1: 7.168 ops/ms
# Warmup Iteration   2: 12.303 ops/ms
# Warmup Iteration   3: 12.320 ops/ms
Iteration   1: 12.468 ops/ms
Iteration   2: 12.539 ops/ms
Iteration   3: 12.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.475 ±(99.9%) 1.093 ops/ms [Average]
  (min, avg, max) = (12.419, 12.475, 12.539), stdev = 0.060
  CI (99.9%): [11.383, 13.568] (assumes normal distribution)


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
# Warmup Iteration   1: 6.515 ops/ms
# Warmup Iteration   2: 10.259 ops/ms
# Warmup Iteration   3: 10.408 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 10.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.514 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (10.423, 10.514, 10.614), stdev = 0.096
  CI (99.9%): [8.766, 12.263] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.003 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.515 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.507, 2.515, 2.530), stdev = 0.013
  CI (99.9%): [2.286, 2.744] (assumes normal distribution)


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.003 ms/op
Iteration   2: 2.467 ±(99.9%) 0.003 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.467, 2.472, 2.480), stdev = 0.007
  CI (99.9%): [2.345, 2.600] (assumes normal distribution)


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.529 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.493, 2.513, 2.529), stdev = 0.018
  CI (99.9%): [2.178, 2.848] (assumes normal distribution)


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.004 ms/op
Iteration   1: 3.049 ±(99.9%) 0.008 ms/op
Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
Iteration   3: 2.992 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.013 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (2.992, 3.013, 3.049), stdev = 0.031
  CI (99.9%): [2.444, 3.582] (assumes normal distribution)


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
# Warmup Iteration   1: 4.385 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.700 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.005 ms/op
Iteration   1: 2.601 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.385 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.026 ms/op
                 createUser·p0.999:  11.945 ms/op
                 createUser·p0.9999: 19.005 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  9.895 ms/op
                 createUser·p0.9999: 13.844 ms/op
                 createUser·p1.00:   14.467 ms/op

Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 12.009 ms/op
                 createUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371838
  mean =      2.579 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 175716 
    [ 2.500,  5.000) = 195212 
    [ 5.000,  7.500) = 494 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      9.284 ms/op
     p(99.9900) =     14.352 ms/op
     p(99.9990) =     19.766 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.201 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  5.890 ms/op
                 existUser·p0.9999: 15.106 ms/op
                 existUser·p1.00:   15.925 ms/op

Iteration   2: 2.482 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 16.767 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  8.245 ms/op
                 existUser·p0.9999: 12.075 ms/op
                 existUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383634
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 193211 
    [ 2.500,  3.750) = 185957 
    [ 3.750,  5.000) = 3563 
    [ 5.000,  6.250) = 335 
    [ 6.250,  7.500) = 118 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      7.029 ms/op
     p(99.9900) =     15.182 ms/op
     p(99.9990) =     16.990 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.596 ±(99.9%) 0.006 ms/op
Iteration   1: 2.594 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  11.903 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   2: 2.621 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.370 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.252 ms/op
                 getUser·p0.95:   3.482 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  10.143 ms/op
                 getUser·p0.9999: 14.140 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   3: 2.571 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.370 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.203 ms/op
                 getUser·p0.95:   3.449 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.447 ms/op
                 getUser·p0.9999: 11.387 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 369561
  mean =      2.595 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 178632 
    [ 2.500,  3.750) = 181598 
    [ 3.750,  5.000) = 7443 
    [ 5.000,  6.250) = 918 
    [ 6.250,  7.500) = 341 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.207 ms/op
     p(95.0000) =      3.416 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.679 ms/op
     p(99.9900) =     15.385 ms/op
     p(99.9990) =     17.487 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 5.354 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.010 ms/op
Iteration   1: 3.100 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.470 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.915 ms/op
                 listUser·p0.999:  10.369 ms/op
                 listUser·p0.9999: 12.037 ms/op
                 listUser·p1.00:   12.927 ms/op

Iteration   2: 2.983 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  10.089 ms/op
                 listUser·p0.9999: 11.850 ms/op
                 listUser·p1.00:   14.696 ms/op

Iteration   3: 2.987 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  10.828 ms/op
                 listUser·p0.9999: 15.787 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317357
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 414 
    [ 1.250,  2.500) = 104073 
    [ 2.500,  3.750) = 163446 
    [ 3.750,  5.000) = 41058 
    [ 5.000,  6.250) = 6435 
    [ 6.250,  7.500) = 1053 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 268 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     10.365 ms/op
     p(99.9900) =     12.718 ms/op
     p(99.9990) =     18.099 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.494 ± 2.181  ops/ms
ClientPb.existUser                       thrpt       3  13.149 ± 2.711  ops/ms
ClientPb.getUser                         thrpt       3  12.475 ± 1.093  ops/ms
ClientPb.listUser                        thrpt       3  10.514 ± 1.748  ops/ms
ClientPb.createUser                       avgt       3   2.515 ± 0.229   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.128   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.335   ms/op
ClientPb.listUser                         avgt       3   3.013 ± 0.569   ms/op
ClientPb.createUser                     sample  371838   2.579 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.385           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.284           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.352           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.037           ms/op
ClientPb.existUser                      sample  383634   2.500 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.613           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.029           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.826           ms/op
ClientPb.getUser                        sample  369561   2.595 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.370           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.679           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.385           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.826           ms/op
ClientPb.listUser                       sample  317357   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.470           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.365           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.718           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.874           ms/op
