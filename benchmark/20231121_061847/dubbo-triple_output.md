# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.556 ops/ms
# Warmup Iteration   2: 11.906 ops/ms
# Warmup Iteration   3: 12.249 ops/ms
Iteration   1: 12.446 ops/ms
Iteration   2: 12.510 ops/ms
Iteration   3: 12.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.482 ±(99.9%) 0.598 ops/ms [Average]
  (min, avg, max) = (12.446, 12.482, 12.510), stdev = 0.033
  CI (99.9%): [11.883, 13.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.481 ops/ms
# Warmup Iteration   2: 13.155 ops/ms
# Warmup Iteration   3: 13.087 ops/ms
Iteration   1: 13.024 ops/ms
Iteration   2: 13.325 ops/ms
Iteration   3: 13.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.134 ±(99.9%) 3.039 ops/ms [Average]
  (min, avg, max) = (13.024, 13.134, 13.325), stdev = 0.167
  CI (99.9%): [10.095, 16.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.984 ops/ms
# Warmup Iteration   2: 12.223 ops/ms
# Warmup Iteration   3: 12.778 ops/ms
Iteration   1: 12.860 ops/ms
Iteration   2: 12.765 ops/ms
Iteration   3: 12.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.830 ±(99.9%) 1.022 ops/ms [Average]
  (min, avg, max) = (12.765, 12.830, 12.864), stdev = 0.056
  CI (99.9%): [11.808, 13.851] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.590 ops/ms
# Warmup Iteration   2: 10.309 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.751 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.647 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (10.590, 10.647, 10.751), stdev = 0.090
  CI (99.9%): [9.006, 12.288] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.217 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.003 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.496 ±(99.9%) 0.117 ms/op [Average]
  (min, avg, max) = (2.490, 2.496, 2.502), stdev = 0.006
  CI (99.9%): [2.379, 2.613] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.901 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.003 ms/op
Iteration   1: 2.456 ±(99.9%) 0.003 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.467 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (2.456, 2.467, 2.487), stdev = 0.017
  CI (99.9%): [2.158, 2.777] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.033 ms/op [Average]
  (min, avg, max) = (2.466, 2.468, 2.470), stdev = 0.002
  CI (99.9%): [2.435, 2.500] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.616 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.004 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
Iteration   3: 3.018 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.001 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (2.979, 3.001, 3.018), stdev = 0.020
  CI (99.9%): [2.645, 3.357] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.057 ms/op
                 createUser·p0.999:  11.456 ms/op
                 createUser·p0.9999: 13.425 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.751 ms/op
                 createUser·p0.999:  7.016 ms/op
                 createUser·p0.9999: 11.924 ms/op
                 createUser·p1.00:   12.435 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  7.824 ms/op
                 createUser·p0.9999: 16.122 ms/op
                 createUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383321
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 185063 
    [ 2.500,  3.750) = 194030 
    [ 3.750,  5.000) = 3272 
    [ 5.000,  6.250) = 516 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 145 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.264 ms/op
     p(99.9900) =     13.757 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.089 ms/op
                 existUser·p0.9999: 13.712 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  7.811 ms/op
                 existUser·p0.9999: 12.862 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.264 ms/op
                 existUser·p0.9999: 11.069 ms/op
                 existUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388074
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 191878 
    [ 2.500,  3.750) = 190800 
    [ 3.750,  5.000) = 4059 
    [ 5.000,  6.250) = 823 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      7.346 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  10.002 ms/op
                 getUser·p0.9999: 13.582 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  6.616 ms/op
                 getUser·p0.9999: 12.075 ms/op
                 getUser·p1.00:   12.632 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  5.751 ms/op
                 getUser·p0.9999: 12.738 ms/op
                 getUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387488
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 193581 
    [ 2.500,  3.750) = 188583 
    [ 3.750,  5.000) = 4229 
    [ 5.000,  6.250) = 618 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      6.337 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     13.980 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.752 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 10.699 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   2: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 11.223 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.616 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314347
  mean =      3.051 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 86407 
    [ 2.500,  3.750) = 186276 
    [ 3.750,  5.000) = 33821 
    [ 5.000,  6.250) = 6254 
    [ 6.250,  7.500) = 794 
    [ 7.500,  8.750) = 324 
    [ 8.750, 10.000) = 200 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     11.358 ms/op
     p(99.9990) =     12.243 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.482 ± 0.598  ops/ms
ClientPb.existUser                       thrpt       3  13.134 ± 3.039  ops/ms
ClientPb.getUser                         thrpt       3  12.830 ± 1.022  ops/ms
ClientPb.listUser                        thrpt       3  10.647 ± 1.641  ops/ms
ClientPb.createUser                       avgt       3   2.496 ± 0.117   ms/op
ClientPb.existUser                        avgt       3   2.467 ± 0.309   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.033   ms/op
ClientPb.listUser                         avgt       3   3.001 ± 0.356   ms/op
ClientPb.createUser                     sample  383321   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.608           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.264           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.757           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.368           ms/op
ClientPb.existUser                      sample  388074   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.671           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.346           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.074           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  387488   2.475 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.750           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.337           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.402           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  314347   3.051 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.358           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.354           ms/op
