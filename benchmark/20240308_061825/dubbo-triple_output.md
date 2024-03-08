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
# Warmup Iteration   1: 5.113 ops/ms
# Warmup Iteration   2: 12.356 ops/ms
# Warmup Iteration   3: 12.616 ops/ms
Iteration   1: 12.587 ops/ms
Iteration   2: 13.099 ops/ms
Iteration   3: 13.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.946 ±(99.9%) 5.691 ops/ms [Average]
  (min, avg, max) = (12.587, 12.946, 13.152), stdev = 0.312
  CI (99.9%): [7.255, 18.637] (assumes normal distribution)


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
# Warmup Iteration   1: 8.537 ops/ms
# Warmup Iteration   2: 13.453 ops/ms
# Warmup Iteration   3: 13.527 ops/ms
Iteration   1: 13.489 ops/ms
Iteration   2: 13.579 ops/ms
Iteration   3: 13.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.543 ±(99.9%) 0.865 ops/ms [Average]
  (min, avg, max) = (13.489, 13.543, 13.579), stdev = 0.047
  CI (99.9%): [12.678, 14.408] (assumes normal distribution)


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
# Warmup Iteration   1: 8.210 ops/ms
# Warmup Iteration   2: 13.101 ops/ms
# Warmup Iteration   3: 13.080 ops/ms
Iteration   1: 13.272 ops/ms
Iteration   2: 13.355 ops/ms
Iteration   3: 13.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.327 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (13.272, 13.327, 13.355), stdev = 0.048
  CI (99.9%): [12.454, 14.200] (assumes normal distribution)


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
# Warmup Iteration   1: 6.644 ops/ms
# Warmup Iteration   2: 10.609 ops/ms
# Warmup Iteration   3: 10.657 ops/ms
Iteration   1: 10.741 ops/ms
Iteration   2: 10.592 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.707 ±(99.9%) 1.882 ops/ms [Average]
  (min, avg, max) = (10.592, 10.707, 10.789), stdev = 0.103
  CI (99.9%): [8.825, 12.590] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.429 ±(99.9%) 0.003 ms/op
Iteration   2: 2.451 ±(99.9%) 0.002 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.448 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.429, 2.448, 2.463), stdev = 0.017
  CI (99.9%): [2.132, 2.764] (assumes normal distribution)


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
# Warmup Iteration   1: 3.490 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.356 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.337 ±(99.9%) 0.003 ms/op
Iteration   1: 2.356 ±(99.9%) 0.004 ms/op
Iteration   2: 2.346 ±(99.9%) 0.003 ms/op
Iteration   3: 2.366 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.356 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.346, 2.356, 2.366), stdev = 0.010
  CI (99.9%): [2.169, 2.542] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.139 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.466 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.445, 2.466, 2.486), stdev = 0.020
  CI (99.9%): [2.094, 2.838] (assumes normal distribution)


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
# Warmup Iteration   1: 4.606 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.006 ms/op
Iteration   1: 2.928 ±(99.9%) 0.004 ms/op
Iteration   2: 2.932 ±(99.9%) 0.004 ms/op
Iteration   3: 2.925 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.928 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (2.925, 2.928, 2.932), stdev = 0.004
  CI (99.9%): [2.862, 2.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.006 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.482 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  6.288 ms/op
                 createUser·p0.9999: 13.962 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  10.224 ms/op
                 createUser·p0.9999: 12.599 ms/op
                 createUser·p1.00:   12.796 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  7.977 ms/op
                 createUser·p0.9999: 9.995 ms/op
                 createUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391312
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 194465 
    [ 2.500,  3.750) = 192809 
    [ 3.750,  5.000) = 3112 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.826 ms/op
     p(99.9900) =     12.730 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.605 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.395 ±(99.9%) 0.005 ms/op
Iteration   1: 2.371 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.871 ms/op
                 existUser·p0.95:   2.966 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  5.714 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.363 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   2.867 ms/op
                 existUser·p0.95:   2.970 ms/op
                 existUser·p0.99:   3.357 ms/op
                 existUser·p0.999:  5.598 ms/op
                 existUser·p0.9999: 14.606 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   3: 2.388 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  7.996 ms/op
                 existUser·p0.9999: 12.324 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 404087
  mean =      2.374 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 210109 
    [ 2.500,  3.750) = 191325 
    [ 3.750,  5.000) = 1857 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      6.962 ms/op
     p(99.9900) =     13.716 ms/op
     p(99.9990) =     14.679 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
Iteration   1: 2.411 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   2.941 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  5.510 ms/op
                 getUser·p0.9999: 14.454 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.879 ms/op
                 getUser·p0.9999: 12.514 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.933 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  6.362 ms/op
                 getUser·p0.9999: 12.955 ms/op
                 getUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 396503
  mean =      2.419 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 204738 
    [ 2.500,  3.750) = 186922 
    [ 3.750,  5.000) = 3893 
    [ 5.000,  6.250) = 393 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     15.204 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.008 ms/op
Iteration   1: 2.938 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.033 ms/op
                 listUser·p0.9999: 12.142 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   2: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  10.476 ms/op
                 listUser·p0.9999: 12.797 ms/op
                 listUser·p1.00:   13.320 ms/op

Iteration   3: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 11.668 ms/op
                 listUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324696
  mean =      2.954 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 197 
    [ 1.250,  2.500) = 103148 
    [ 2.500,  3.750) = 183996 
    [ 3.750,  5.000) = 30372 
    [ 5.000,  6.250) = 5689 
    [ 6.250,  7.500) = 584 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 188 
    [10.000, 11.250) = 190 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.803 ms/op
     p(99.9900) =     12.420 ms/op
     p(99.9990) =     13.136 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.946 ± 5.691  ops/ms
ClientPb.existUser                       thrpt       3  13.543 ± 0.865  ops/ms
ClientPb.getUser                         thrpt       3  13.327 ± 0.873  ops/ms
ClientPb.listUser                        thrpt       3  10.707 ± 1.882  ops/ms
ClientPb.createUser                       avgt       3   2.448 ± 0.316   ms/op
ClientPb.existUser                        avgt       3   2.356 ± 0.186   ms/op
ClientPb.getUser                          avgt       3   2.466 ± 0.372   ms/op
ClientPb.listUser                         avgt       3   2.928 ± 0.066   ms/op
ClientPb.createUser                     sample  391312   2.451 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.511           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.982           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.826           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.860           ms/op
ClientPb.existUser                      sample  404087   2.374 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.593           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.437           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.962           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.716           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.352           ms/op
ClientPb.getUser                        sample  396503   2.419 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.890           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.437           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.945           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.697           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.303           ms/op
ClientPb.listUser                       sample  324696   2.954 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.809           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.803           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.420           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.320           ms/op
