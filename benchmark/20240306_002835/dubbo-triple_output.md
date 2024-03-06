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
# Warmup Iteration   1: 5.437 ops/ms
# Warmup Iteration   2: 12.609 ops/ms
# Warmup Iteration   3: 12.730 ops/ms
Iteration   1: 13.031 ops/ms
Iteration   2: 13.013 ops/ms
Iteration   3: 12.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.988 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (12.919, 12.988, 13.031), stdev = 0.060
  CI (99.9%): [11.894, 14.082] (assumes normal distribution)


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
# Warmup Iteration   1: 8.328 ops/ms
# Warmup Iteration   2: 13.130 ops/ms
# Warmup Iteration   3: 13.489 ops/ms
Iteration   1: 13.452 ops/ms
Iteration   2: 13.398 ops/ms
Iteration   3: 13.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.373 ±(99.9%) 1.737 ops/ms [Average]
  (min, avg, max) = (13.267, 13.373, 13.452), stdev = 0.095
  CI (99.9%): [11.636, 15.109] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.142 ops/ms
# Warmup Iteration   2: 12.972 ops/ms
# Warmup Iteration   3: 13.068 ops/ms
Iteration   1: 13.249 ops/ms
Iteration   2: 12.991 ops/ms
Iteration   3: 12.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.062 ±(99.9%) 2.983 ops/ms [Average]
  (min, avg, max) = (12.946, 13.062, 13.249), stdev = 0.163
  CI (99.9%): [10.079, 16.045] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 6.565 ops/ms
# Warmup Iteration   2: 10.641 ops/ms
# Warmup Iteration   3: 10.737 ops/ms
Iteration   1: 10.727 ops/ms
Iteration   2: 10.718 ops/ms
Iteration   3: 10.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.755 ±(99.9%) 1.012 ops/ms [Average]
  (min, avg, max) = (10.718, 10.755, 10.818), stdev = 0.055
  CI (99.9%): [9.742, 11.767] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.454 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (2.435, 2.454, 2.486), stdev = 0.028
  CI (99.9%): [1.945, 2.963] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.593 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.004 ms/op
Iteration   1: 2.408 ±(99.9%) 0.005 ms/op
Iteration   2: 2.395 ±(99.9%) 0.004 ms/op
Iteration   3: 2.391 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.398 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.391, 2.398, 2.408), stdev = 0.009
  CI (99.9%): [2.237, 2.560] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.573 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.003 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.402 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.416 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.402, 2.416, 2.424), stdev = 0.013
  CI (99.9%): [2.188, 2.645] (assumes normal distribution)


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
# Warmup Iteration   1: 4.522 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.005 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
Iteration   3: 2.956 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.952 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (2.938, 2.952, 2.960), stdev = 0.012
  CI (99.9%): [2.739, 3.164] (assumes normal distribution)


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  8.764 ms/op
                 createUser·p0.9999: 12.995 ms/op
                 createUser·p1.00:   13.517 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  9.535 ms/op
                 createUser·p0.9999: 13.107 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  9.134 ms/op
                 createUser·p0.9999: 11.784 ms/op
                 createUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382670
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 184460 
    [ 2.500,  3.750) = 194404 
    [ 3.750,  5.000) = 3012 
    [ 5.000,  6.250) = 267 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     12.873 ms/op
     p(99.9990) =     13.438 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


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
# Warmup Iteration   1: 3.475 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.005 ms/op
Iteration   1: 2.402 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  6.413 ms/op
                 existUser·p0.9999: 13.451 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.521 ms/op
                 existUser·p0.999:  6.633 ms/op
                 existUser·p0.9999: 12.698 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  9.657 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399051
  mean =      2.403 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 206336 
    [ 2.500,  5.000) = 191711 
    [ 5.000,  7.500) = 588 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.386 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.006 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.493 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  5.806 ms/op
                 getUser·p0.9999: 12.991 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.166 ms/op
                 getUser·p0.9999: 11.977 ms/op
                 getUser·p1.00:   12.321 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.400 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  7.264 ms/op
                 getUser·p0.9999: 11.403 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391035
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 199477 
    [ 2.500,  3.750) = 186142 
    [ 3.750,  5.000) = 4492 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 139 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      6.198 ms/op
     p(99.9900) =     12.542 ms/op
     p(99.9990) =     13.830 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.614 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.009 ms/op
Iteration   1: 3.014 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  8.994 ms/op
                 listUser·p0.9999: 11.570 ms/op
                 listUser·p1.00:   13.140 ms/op

Iteration   2: 3.027 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.778 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  10.732 ms/op
                 listUser·p0.9999: 12.230 ms/op
                 listUser·p1.00:   14.057 ms/op

Iteration   3: 3.058 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.561 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  11.050 ms/op
                 listUser·p0.9999: 12.403 ms/op
                 listUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316241
  mean =      3.033 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 400 
    [ 1.250,  2.500) = 102030 
    [ 2.500,  3.750) = 163126 
    [ 3.750,  5.000) = 40518 
    [ 5.000,  6.250) = 7168 
    [ 6.250,  7.500) = 1494 
    [ 7.500,  8.750) = 702 
    [ 8.750, 10.000) = 369 
    [10.000, 11.250) = 273 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     10.515 ms/op
     p(99.9900) =     12.311 ms/op
     p(99.9990) =     13.589 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.988 ± 1.094  ops/ms
ClientPb.existUser                       thrpt       3  13.373 ± 1.737  ops/ms
ClientPb.getUser                         thrpt       3  13.062 ± 2.983  ops/ms
ClientPb.listUser                        thrpt       3  10.755 ± 1.012  ops/ms
ClientPb.createUser                       avgt       3   2.454 ± 0.509   ms/op
ClientPb.existUser                        avgt       3   2.398 ± 0.161   ms/op
ClientPb.getUser                          avgt       3   2.416 ± 0.228   ms/op
ClientPb.listUser                         avgt       3   2.952 ± 0.212   ms/op
ClientPb.createUser                     sample  382670   2.506 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.795           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.142           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.873           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.517           ms/op
ClientPb.existUser                      sample  399051   2.403 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.903           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.441           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.322           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.402           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  391035   2.453 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.400           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.198           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.542           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.894           ms/op
ClientPb.listUser                       sample  316241   3.033 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.561           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.177           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.515           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.311           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.516           ms/op
