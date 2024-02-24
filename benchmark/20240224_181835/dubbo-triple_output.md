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
# Warmup Iteration   1: 4.912 ops/ms
# Warmup Iteration   2: 12.212 ops/ms
# Warmup Iteration   3: 12.473 ops/ms
Iteration   1: 12.664 ops/ms
Iteration   2: 12.614 ops/ms
Iteration   3: 12.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.671 ±(99.9%) 1.122 ops/ms [Average]
  (min, avg, max) = (12.614, 12.671, 12.736), stdev = 0.062
  CI (99.9%): [11.549, 13.793] (assumes normal distribution)


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
# Warmup Iteration   1: 8.254 ops/ms
# Warmup Iteration   2: 13.246 ops/ms
# Warmup Iteration   3: 13.299 ops/ms
Iteration   1: 13.277 ops/ms
Iteration   2: 13.234 ops/ms
Iteration   3: 13.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.211 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (13.122, 13.211, 13.277), stdev = 0.080
  CI (99.9%): [11.746, 14.675] (assumes normal distribution)


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
# Warmup Iteration   1: 7.939 ops/ms
# Warmup Iteration   2: 12.486 ops/ms
# Warmup Iteration   3: 12.569 ops/ms
Iteration   1: 12.473 ops/ms
Iteration   2: 12.431 ops/ms
Iteration   3: 12.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.461 ±(99.9%) 0.483 ops/ms [Average]
  (min, avg, max) = (12.431, 12.461, 12.479), stdev = 0.026
  CI (99.9%): [11.978, 12.944] (assumes normal distribution)


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
# Warmup Iteration   1: 6.512 ops/ms
# Warmup Iteration   2: 10.096 ops/ms
# Warmup Iteration   3: 10.582 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.592 ops/ms
Iteration   3: 10.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.465 ±(99.9%) 3.684 ops/ms [Average]
  (min, avg, max) = (10.232, 10.465, 10.592), stdev = 0.202
  CI (99.9%): [6.781, 14.150] (assumes normal distribution)


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.003 ms/op
Iteration   1: 2.503 ±(99.9%) 0.003 ms/op
Iteration   2: 2.474 ±(99.9%) 0.003 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.474, 2.506, 2.540), stdev = 0.033
  CI (99.9%): [1.902, 3.110] (assumes normal distribution)


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.004 ms/op
Iteration   1: 2.420 ±(99.9%) 0.004 ms/op
Iteration   2: 2.414 ±(99.9%) 0.004 ms/op
Iteration   3: 2.409 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.414 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.409, 2.414, 2.420), stdev = 0.005
  CI (99.9%): [2.316, 2.513] (assumes normal distribution)


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (2.481, 2.493, 2.516), stdev = 0.020
  CI (99.9%): [2.126, 2.859] (assumes normal distribution)


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.012 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (3.006, 3.012, 3.022), stdev = 0.009
  CI (99.9%): [2.848, 3.175] (assumes normal distribution)


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  11.911 ms/op
                 createUser·p0.9999: 13.571 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.932 ms/op
                 createUser·p0.9999: 12.489 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  8.167 ms/op
                 createUser·p0.9999: 9.863 ms/op
                 createUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382912
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 186032 
    [ 2.500,  3.750) = 193324 
    [ 3.750,  5.000) = 2812 
    [ 5.000,  6.250) = 234 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     13.245 ms/op
     p(99.9990) =     14.172 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.740 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  6.595 ms/op
                 existUser·p0.9999: 13.496 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  6.457 ms/op
                 existUser·p0.9999: 13.369 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 11.261 ms/op
                 existUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390009
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 194101 
    [ 2.500,  3.750) = 192025 
    [ 3.750,  5.000) = 2949 
    [ 5.000,  6.250) = 436 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      6.766 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  10.159 ms/op
                 getUser·p0.9999: 13.389 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  10.279 ms/op
                 getUser·p0.9999: 13.673 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.778 ms/op
                 getUser·p0.999:  7.701 ms/op
                 getUser·p0.9999: 14.371 ms/op
                 getUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383944
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 190156 
    [ 2.500,  3.750) = 189454 
    [ 3.750,  5.000) = 3479 
    [ 5.000,  6.250) = 378 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 139 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =     13.510 ms/op
     p(99.9990) =     14.573 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
Iteration   1: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 10.618 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 10.574 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.733 ms/op
                 listUser·p0.9999: 11.689 ms/op
                 listUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319422
  mean =      3.003 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 95410 
    [ 2.500,  3.750) = 184370 
    [ 3.750,  5.000) = 32452 
    [ 5.000,  6.250) = 5824 
    [ 6.250,  7.500) = 571 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     10.846 ms/op
     p(99.9990) =     12.259 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.671 ± 1.122  ops/ms
ClientPb.existUser                       thrpt       3  13.211 ± 1.465  ops/ms
ClientPb.getUser                         thrpt       3  12.461 ± 0.483  ops/ms
ClientPb.listUser                        thrpt       3  10.465 ± 3.684  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.604   ms/op
ClientPb.existUser                        avgt       3   2.414 ± 0.098   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.366   ms/op
ClientPb.listUser                         avgt       3   3.012 ± 0.164   ms/op
ClientPb.createUser                     sample  382912   2.504 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.807           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.913           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.245           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  390009   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.763           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.766           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.320           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.074           ms/op
ClientPb.getUser                        sample  383944   2.498 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.893           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.298           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.510           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.942           ms/op
ClientPb.listUser                       sample  319422   3.003 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.849           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.846           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
