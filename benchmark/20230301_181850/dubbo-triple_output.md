# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.335 ops/ms
# Warmup Iteration   2: 5.532 ops/ms
# Warmup Iteration   3: 8.750 ops/ms
Iteration   1: 9.284 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.338 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (9.284, 9.338, 9.418), stdev = 0.070
  CI (99.9%): [8.060, 10.617] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.954 ops/ms
# Warmup Iteration   2: 8.707 ops/ms
# Warmup Iteration   3: 9.830 ops/ms
Iteration   1: 9.918 ops/ms
Iteration   2: 9.716 ops/ms
Iteration   3: 9.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.765 ±(99.9%) 2.474 ops/ms [Average]
  (min, avg, max) = (9.660, 9.765, 9.918), stdev = 0.136
  CI (99.9%): [7.291, 12.239] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.949 ops/ms
# Warmup Iteration   2: 8.790 ops/ms
# Warmup Iteration   3: 9.561 ops/ms
Iteration   1: 9.387 ops/ms
Iteration   2: 9.317 ops/ms
Iteration   3: 9.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.351 ±(99.9%) 0.642 ops/ms [Average]
  (min, avg, max) = (9.317, 9.351, 9.387), stdev = 0.035
  CI (99.9%): [8.709, 9.992] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.133 ops/ms
# Warmup Iteration   2: 7.531 ops/ms
# Warmup Iteration   3: 8.110 ops/ms
Iteration   1: 7.854 ops/ms
Iteration   2: 7.965 ops/ms
Iteration   3: 8.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.111 ±(99.9%) 6.456 ops/ms [Average]
  (min, avg, max) = (7.854, 8.111, 8.515), stdev = 0.354
  CI (99.9%): [1.655, 14.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.525 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.005 ms/op
Iteration   1: 3.494 ±(99.9%) 0.009 ms/op
Iteration   2: 3.381 ±(99.9%) 0.008 ms/op
Iteration   3: 3.418 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.431 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.381, 3.431, 3.494), stdev = 0.058
  CI (99.9%): [2.377, 4.485] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.946 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.003 ms/op
Iteration   1: 3.280 ±(99.9%) 0.008 ms/op
Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
Iteration   3: 3.344 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.279 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (3.213, 3.279, 3.344), stdev = 0.066
  CI (99.9%): [2.081, 4.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.497 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.003 ms/op
Iteration   1: 3.453 ±(99.9%) 0.005 ms/op
Iteration   2: 3.348 ±(99.9%) 0.006 ms/op
Iteration   3: 3.326 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.376 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (3.326, 3.376, 3.453), stdev = 0.068
  CI (99.9%): [2.137, 4.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.724 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.008 ms/op
Iteration   1: 3.923 ±(99.9%) 0.010 ms/op
Iteration   2: 4.052 ±(99.9%) 0.008 ms/op
Iteration   3: 3.905 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.960 ±(99.9%) 1.465 ms/op [Average]
  (min, avg, max) = (3.905, 3.960, 4.052), stdev = 0.080
  CI (99.9%): [2.494, 5.425] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.574 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.010 ms/op
Iteration   1: 3.314 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  16.992 ms/op
                 createUser·p0.9999: 23.178 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.429 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 24.139 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  18.121 ms/op
                 createUser·p0.9999: 24.824 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281227
  mean =      3.411 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9093 
    [ 2.500,  5.000) = 266106 
    [ 5.000,  7.500) = 4998 
    [ 7.500, 10.000) = 583 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     24.310 ms/op
     p(99.9990) =     25.211 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.452 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  8.879 ms/op
                 existUser·p0.9999: 22.287 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   2: 3.341 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  21.245 ms/op
                 existUser·p0.9999: 24.473 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   3: 3.379 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   5.789 ms/op
                 existUser·p0.999:  12.632 ms/op
                 existUser·p0.9999: 24.785 ms/op
                 existUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288974
  mean =      3.319 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19650 
    [ 2.500,  5.000) = 262769 
    [ 5.000,  7.500) = 5460 
    [ 7.500, 10.000) = 647 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     12.600 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     26.480 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.783 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.011 ms/op
Iteration   1: 3.441 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.084 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 29.744 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   2: 3.568 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.159 ms/op
                 getUser·p0.999:  21.436 ms/op
                 getUser·p0.9999: 29.786 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 3.564 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.389 ms/op
                 getUser·p0.999:  18.916 ms/op
                 getUser·p0.9999: 24.970 ms/op
                 getUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272406
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1999 
    [ 2.500,  5.000) = 257747 
    [ 5.000,  7.500) = 10768 
    [ 7.500, 10.000) = 1336 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     19.287 ms/op
     p(99.9900) =     29.557 ms/op
     p(99.9990) =     30.338 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.711 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.012 ms/op
Iteration   1: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 4.098 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 19.968 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 3.970 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 16.661 ms/op
                 listUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239040
  mean =      4.016 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 227599 
    [ 5.000,  7.500) = 8632 
    [ 7.500, 10.000) = 1978 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.075 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     22.616 ms/op
     p(99.9990) =     24.236 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.338 ± 1.279  ops/ms
ClientPb.existUser                       thrpt       3   9.765 ± 2.474  ops/ms
ClientPb.getUser                         thrpt       3   9.351 ± 0.642  ops/ms
ClientPb.listUser                        thrpt       3   8.111 ± 6.456  ops/ms
ClientPb.createUser                       avgt       3   3.431 ± 1.054   ms/op
ClientPb.existUser                        avgt       3   3.279 ± 1.198   ms/op
ClientPb.getUser                          avgt       3   3.376 ± 1.239   ms/op
ClientPb.listUser                         avgt       3   3.960 ± 1.465   ms/op
ClientPb.createUser                     sample  281227   3.411 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.466           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.252           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.310           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.264           ms/op
ClientPb.existUser                      sample  288974   3.319 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.438           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.600           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.183           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.329           ms/op
ClientPb.getUser                        sample  272406   3.523 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.143           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.135           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.287           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.557           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  239040   4.016 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.075           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.964           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.499           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.616           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.281           ms/op
