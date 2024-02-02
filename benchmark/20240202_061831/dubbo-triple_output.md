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
# Warmup Iteration   1: 4.884 ops/ms
# Warmup Iteration   2: 12.252 ops/ms
# Warmup Iteration   3: 12.360 ops/ms
Iteration   1: 12.666 ops/ms
Iteration   2: 12.820 ops/ms
Iteration   3: 13.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.932 ±(99.9%) 6.131 ops/ms [Average]
  (min, avg, max) = (12.666, 12.932, 13.309), stdev = 0.336
  CI (99.9%): [6.801, 19.063] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.313 ops/ms
# Warmup Iteration   2: 13.004 ops/ms
# Warmup Iteration   3: 13.123 ops/ms
Iteration   1: 13.479 ops/ms
Iteration   2: 13.315 ops/ms
Iteration   3: 13.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.431 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (13.315, 13.431, 13.501), stdev = 0.102
  CI (99.9%): [11.578, 15.285] (assumes normal distribution)


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
# Warmup Iteration   1: 7.974 ops/ms
# Warmup Iteration   2: 12.384 ops/ms
# Warmup Iteration   3: 12.811 ops/ms
Iteration   1: 12.775 ops/ms
Iteration   2: 12.749 ops/ms
Iteration   3: 12.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.740 ±(99.9%) 0.736 ops/ms [Average]
  (min, avg, max) = (12.696, 12.740, 12.775), stdev = 0.040
  CI (99.9%): [12.004, 13.476] (assumes normal distribution)


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
# Warmup Iteration   1: 6.790 ops/ms
# Warmup Iteration   2: 10.698 ops/ms
# Warmup Iteration   3: 10.754 ops/ms
Iteration   1: 10.719 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.716 ±(99.9%) 1.696 ops/ms [Average]
  (min, avg, max) = (10.621, 10.716, 10.807), stdev = 0.093
  CI (99.9%): [9.020, 12.411] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.003 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.521, 2.530, 2.535), stdev = 0.008
  CI (99.9%): [2.382, 2.679] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.609 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.408 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.409 ±(99.9%) 0.004 ms/op
Iteration   1: 2.406 ±(99.9%) 0.003 ms/op
Iteration   2: 2.398 ±(99.9%) 0.003 ms/op
Iteration   3: 2.394 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.399 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (2.394, 2.399, 2.406), stdev = 0.006
  CI (99.9%): [2.285, 2.513] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.003 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.494, 2.500, 2.511), stdev = 0.009
  CI (99.9%): [2.329, 2.672] (assumes normal distribution)


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
# Warmup Iteration   1: 4.893 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
Iteration   3: 2.983 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.977, 2.982, 2.986), stdev = 0.004
  CI (99.9%): [2.901, 3.063] (assumes normal distribution)


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.385 ms/op
                 createUser·p0.9999: 13.029 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  8.746 ms/op
                 createUser·p0.9999: 11.702 ms/op
                 createUser·p1.00:   12.141 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  8.571 ms/op
                 createUser·p0.9999: 10.764 ms/op
                 createUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385439
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 186132 
    [ 2.500,  3.750) = 195491 
    [ 3.750,  5.000) = 2873 
    [ 5.000,  6.250) = 398 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.578 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     13.366 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  7.984 ms/op
                 existUser·p0.9999: 14.082 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.338 ms/op
                 existUser·p0.999:  7.076 ms/op
                 existUser·p0.9999: 12.353 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.208 ms/op
                 existUser·p0.9999: 10.961 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389194
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 189939 
    [ 2.500,  3.750) = 196551 
    [ 3.750,  5.000) = 1950 
    [ 5.000,  6.250) = 233 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.449 ms/op
                 getUser·p0.999:  6.055 ms/op
                 getUser·p0.9999: 14.631 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  9.376 ms/op
                 getUser·p0.9999: 12.625 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  6.270 ms/op
                 getUser·p0.9999: 11.143 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386119
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 191809 
    [ 2.500,  3.750) = 189804 
    [ 3.750,  5.000) = 3650 
    [ 5.000,  6.250) = 331 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      7.912 ms/op
     p(99.9900) =     13.391 ms/op
     p(99.9990) =     14.944 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
Iteration   1: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.678 ms/op
                 listUser·p0.9999: 11.289 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.801 ms/op
                 listUser·p0.9999: 11.725 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.650 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.764 ms/op
                 listUser·p0.9999: 11.131 ms/op
                 listUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319038
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 92574 
    [ 2.500,  3.750) = 187539 
    [ 3.750,  5.000) = 31686 
    [ 5.000,  6.250) = 5803 
    [ 6.250,  7.500) = 653 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 197 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.338 ms/op
     p(99.9900) =     11.354 ms/op
     p(99.9990) =     12.138 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.932 ± 6.131  ops/ms
ClientPb.existUser                       thrpt       3  13.431 ± 1.853  ops/ms
ClientPb.getUser                         thrpt       3  12.740 ± 0.736  ops/ms
ClientPb.listUser                        thrpt       3  10.716 ± 1.696  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.148   ms/op
ClientPb.existUser                        avgt       3   2.399 ± 0.114   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.172   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.081   ms/op
ClientPb.createUser                     sample  385439   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.864           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.578           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.665           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.779           ms/op
ClientPb.existUser                      sample  389194   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.571           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.200           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.991           ms/op
ClientPb.getUser                        sample  386119   2.484 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.924           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.912           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.391           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.401           ms/op
ClientPb.listUser                       sample  319038   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.650           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.338           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.354           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.452           ms/op
