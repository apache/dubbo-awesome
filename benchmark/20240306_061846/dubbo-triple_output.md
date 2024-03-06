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
# Warmup Iteration   1: 5.230 ops/ms
# Warmup Iteration   2: 12.455 ops/ms
# Warmup Iteration   3: 12.971 ops/ms
Iteration   1: 12.784 ops/ms
Iteration   2: 13.226 ops/ms
Iteration   3: 13.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.049 ±(99.9%) 4.265 ops/ms [Average]
  (min, avg, max) = (12.784, 13.049, 13.226), stdev = 0.234
  CI (99.9%): [8.784, 17.314] (assumes normal distribution)


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
# Warmup Iteration   1: 8.697 ops/ms
# Warmup Iteration   2: 13.611 ops/ms
# Warmup Iteration   3: 13.469 ops/ms
Iteration   1: 13.474 ops/ms
Iteration   2: 13.669 ops/ms
Iteration   3: 13.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.575 ±(99.9%) 1.780 ops/ms [Average]
  (min, avg, max) = (13.474, 13.575, 13.669), stdev = 0.098
  CI (99.9%): [11.795, 15.355] (assumes normal distribution)


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
# Warmup Iteration   1: 8.316 ops/ms
# Warmup Iteration   2: 12.692 ops/ms
# Warmup Iteration   3: 13.106 ops/ms
Iteration   1: 13.109 ops/ms
Iteration   2: 13.049 ops/ms
Iteration   3: 13.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.083 ±(99.9%) 0.560 ops/ms [Average]
  (min, avg, max) = (13.049, 13.083, 13.109), stdev = 0.031
  CI (99.9%): [12.523, 13.642] (assumes normal distribution)


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
# Warmup Iteration   1: 7.114 ops/ms
# Warmup Iteration   2: 10.748 ops/ms
# Warmup Iteration   3: 10.649 ops/ms
Iteration   1: 10.965 ops/ms
Iteration   2: 10.888 ops/ms
Iteration   3: 10.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.928 ±(99.9%) 0.709 ops/ms [Average]
  (min, avg, max) = (10.888, 10.928, 10.965), stdev = 0.039
  CI (99.9%): [10.219, 11.637] (assumes normal distribution)


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.003 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.515 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.511, 2.515, 2.518), stdev = 0.004
  CI (99.9%): [2.441, 2.590] (assumes normal distribution)


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
# Warmup Iteration   1: 3.512 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.399 ±(99.9%) 0.004 ms/op
Iteration   1: 2.366 ±(99.9%) 0.003 ms/op
Iteration   2: 2.391 ±(99.9%) 0.004 ms/op
Iteration   3: 2.385 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.380 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.366, 2.380, 2.391), stdev = 0.013
  CI (99.9%): [2.142, 2.619] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.786 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.003 ms/op
Iteration   1: 2.425 ±(99.9%) 0.003 ms/op
Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.429 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (2.425, 2.429, 2.432), stdev = 0.004
  CI (99.9%): [2.361, 2.497] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.478 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.005 ms/op
Iteration   1: 2.923 ±(99.9%) 0.005 ms/op
Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
Iteration   3: 2.950 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.942 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.923, 2.942, 2.952), stdev = 0.016
  CI (99.9%): [2.641, 3.243] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.006 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.474 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  10.414 ms/op
                 createUser·p0.9999: 13.314 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.474 ms/op
                 createUser·p0.90:   2.945 ms/op
                 createUser·p0.95:   3.056 ms/op
                 createUser·p0.99:   3.502 ms/op
                 createUser·p0.999:  7.118 ms/op
                 createUser·p0.9999: 12.281 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  7.974 ms/op
                 createUser·p0.9999: 10.542 ms/op
                 createUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 394458
  mean =      2.432 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 198372 
    [ 2.500,  3.750) = 192897 
    [ 3.750,  5.000) = 2319 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     12.599 ms/op
     p(99.9990) =     13.830 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.581 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.409 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.407 ±(99.9%) 0.005 ms/op
Iteration   1: 2.373 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.871 ms/op
                 existUser·p0.95:   2.957 ms/op
                 existUser·p0.99:   3.248 ms/op
                 existUser·p0.999:  4.651 ms/op
                 existUser·p0.9999: 14.001 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.599 ms/op
                 existUser·p0.999:  8.060 ms/op
                 existUser·p0.9999: 15.516 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   3: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  6.447 ms/op
                 existUser·p0.9999: 11.710 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 400927
  mean =      2.392 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 205473 
    [ 2.500,  3.750) = 192585 
    [ 3.750,  5.000) = 2011 
    [ 5.000,  6.250) = 377 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =      6.556 ms/op
     p(99.9900) =     13.956 ms/op
     p(99.9990) =     15.778 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   3.502 ms/op
                 getUser·p0.999:  5.422 ms/op
                 getUser·p0.9999: 13.481 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.065 ms/op
                 getUser·p0.9999: 13.091 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  5.808 ms/op
                 getUser·p0.9999: 12.481 ms/op
                 getUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392866
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 200169 
    [ 2.500,  3.750) = 187635 
    [ 3.750,  5.000) = 3810 
    [ 5.000,  6.250) = 743 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      6.490 ms/op
     p(99.9900) =     13.184 ms/op
     p(99.9990) =     13.653 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.580 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
Iteration   1: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.659 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.358 ms/op
                 listUser·p1.00:   11.256 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.703 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.303 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   3: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  8.680 ms/op
                 listUser·p0.9999: 10.427 ms/op
                 listUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323439
  mean =      2.965 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 100450 
    [ 2.500,  3.750) = 185510 
    [ 3.750,  5.000) = 30350 
    [ 5.000,  6.250) = 5688 
    [ 6.250,  7.500) = 687 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.053 ms/op
     p(99.9900) =     10.709 ms/op
     p(99.9990) =     11.248 ms/op
     p(99.9999) =     11.436 ms/op
    p(100.0000) =     11.436 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.049 ± 4.265  ops/ms
ClientPb.existUser                       thrpt       3  13.575 ± 1.780  ops/ms
ClientPb.getUser                         thrpt       3  13.083 ± 0.560  ops/ms
ClientPb.listUser                        thrpt       3  10.928 ± 0.709  ops/ms
ClientPb.createUser                       avgt       3   2.515 ± 0.074   ms/op
ClientPb.existUser                        avgt       3   2.380 ± 0.238   ms/op
ClientPb.getUser                          avgt       3   2.429 ± 0.068   ms/op
ClientPb.listUser                         avgt       3   2.942 ± 0.301   ms/op
ClientPb.createUser                     sample  394458   2.432 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.490           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.962           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.599           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.483           ms/op
ClientPb.existUser                      sample  400927   2.392 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.912           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.556           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.956           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.876           ms/op
ClientPb.getUser                        sample  392866   2.442 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.746           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.974           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.490           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.184           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.779           ms/op
ClientPb.listUser                       sample  323439   2.965 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.659           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.053           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.709           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.436           ms/op
