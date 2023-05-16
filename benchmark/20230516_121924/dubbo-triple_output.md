# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.110 ops/ms
# Warmup Iteration   2: 4.778 ops/ms
# Warmup Iteration   3: 8.650 ops/ms
Iteration   1: 9.037 ops/ms
Iteration   2: 9.455 ops/ms
Iteration   3: 9.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.326 ±(99.9%) 4.571 ops/ms [Average]
  (min, avg, max) = (9.037, 9.326, 9.486), stdev = 0.251
  CI (99.9%): [4.755, 13.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.925 ops/ms
# Warmup Iteration   2: 8.905 ops/ms
# Warmup Iteration   3: 9.435 ops/ms
Iteration   1: 10.188 ops/ms
Iteration   2: 9.817 ops/ms
Iteration   3: 9.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.915 ±(99.9%) 4.364 ops/ms [Average]
  (min, avg, max) = (9.741, 9.915, 10.188), stdev = 0.239
  CI (99.9%): [5.552, 14.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.709 ops/ms
# Warmup Iteration   2: 8.037 ops/ms
# Warmup Iteration   3: 9.313 ops/ms
Iteration   1: 9.346 ops/ms
Iteration   2: 9.782 ops/ms
Iteration   3: 9.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.561 ±(99.9%) 3.985 ops/ms [Average]
  (min, avg, max) = (9.346, 9.561, 9.782), stdev = 0.218
  CI (99.9%): [5.576, 13.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.980 ops/ms
# Warmup Iteration   2: 7.302 ops/ms
# Warmup Iteration   3: 7.794 ops/ms
Iteration   1: 8.047 ops/ms
Iteration   2: 7.928 ops/ms
Iteration   3: 8.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.133 ±(99.9%) 4.712 ops/ms [Average]
  (min, avg, max) = (7.928, 8.133, 8.423), stdev = 0.258
  CI (99.9%): [3.420, 12.845] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.156 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.006 ms/op
Iteration   1: 3.326 ±(99.9%) 0.006 ms/op
Iteration   2: 3.394 ±(99.9%) 0.011 ms/op
Iteration   3: 3.348 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.356 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (3.326, 3.356, 3.394), stdev = 0.035
  CI (99.9%): [2.726, 3.987] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.389 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.002 ms/op
Iteration   1: 3.472 ±(99.9%) 0.005 ms/op
Iteration   2: 3.194 ±(99.9%) 0.009 ms/op
Iteration   3: 3.322 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 2.538 ms/op [Average]
  (min, avg, max) = (3.194, 3.329, 3.472), stdev = 0.139
  CI (99.9%): [0.791, 5.868] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.945 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.004 ms/op
Iteration   1: 3.366 ±(99.9%) 0.006 ms/op
Iteration   2: 3.299 ±(99.9%) 0.005 ms/op
Iteration   3: 3.529 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.398 ±(99.9%) 2.157 ms/op [Average]
  (min, avg, max) = (3.299, 3.398, 3.529), stdev = 0.118
  CI (99.9%): [1.241, 5.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.081 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.010 ms/op
Iteration   1: 4.169 ±(99.9%) 0.004 ms/op
Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
Iteration   3: 3.881 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.991 ±(99.9%) 2.837 ms/op [Average]
  (min, avg, max) = (3.881, 3.991, 4.169), stdev = 0.155
  CI (99.9%): [1.154, 6.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.012 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.009 ms/op
Iteration   1: 3.598 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  19.038 ms/op
                 createUser·p0.9999: 23.953 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   2: 3.472 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  20.050 ms/op
                 createUser·p0.9999: 25.100 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.423 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  18.928 ms/op
                 createUser·p0.9999: 26.629 ms/op
                 createUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274485
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10369 
    [ 2.500,  5.000) = 256050 
    [ 5.000,  7.500) = 7098 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     25.151 ms/op
     p(99.9990) =     26.952 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.389 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
Iteration   1: 3.247 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  13.734 ms/op
                 existUser·p0.9999: 20.789 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 22.489 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 26.284 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294634
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16824 
    [ 2.500,  5.000) = 272220 
    [ 5.000,  7.500) = 4905 
    [ 7.500, 10.000) = 366 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     24.790 ms/op
     p(99.9990) =     26.642 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.349 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.012 ms/op
Iteration   1: 3.425 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  20.188 ms/op
                 getUser·p0.9999: 24.281 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   2: 3.372 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  20.680 ms/op
                 getUser·p0.9999: 25.903 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.645 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  18.581 ms/op
                 getUser·p0.9999: 24.103 ms/op
                 getUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282598
  mean =      3.396 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5800 
    [ 2.500,  5.000) = 270315 
    [ 5.000,  7.500) = 5382 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     19.641 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     26.127 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.639 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.362 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.015 ms/op
Iteration   1: 3.977 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  19.905 ms/op
                 listUser·p0.9999: 31.455 ms/op
                 listUser·p1.00:   32.571 ms/op

Iteration   2: 3.990 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   3: 3.838 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.063 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  14.049 ms/op
                 listUser·p0.9999: 15.357 ms/op
                 listUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243795
  mean =      3.934 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 234981 
    [ 5.000,  7.500) = 7035 
    [ 7.500, 10.000) = 978 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.898 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     29.532 ms/op
     p(99.9990) =     31.709 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.326 ± 4.571  ops/ms
ClientPb.existUser                       thrpt       3   9.915 ± 4.364  ops/ms
ClientPb.getUser                         thrpt       3   9.561 ± 3.985  ops/ms
ClientPb.listUser                        thrpt       3   8.133 ± 4.712  ops/ms
ClientPb.createUser                       avgt       3   3.356 ± 0.631   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 2.538   ms/op
ClientPb.getUser                          avgt       3   3.398 ± 2.157   ms/op
ClientPb.listUser                         avgt       3   3.991 ± 2.837   ms/op
ClientPb.createUser                     sample  274485   3.496 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.760           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.137           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.151           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.329           ms/op
ClientPb.existUser                      sample  294634   3.258 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.151           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.453           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.790           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.001           ms/op
ClientPb.getUser                        sample  282598   3.396 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.681           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.641           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.281           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.771           ms/op
ClientPb.listUser                       sample  243795   3.934 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.898           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.811           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.532           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.571           ms/op
