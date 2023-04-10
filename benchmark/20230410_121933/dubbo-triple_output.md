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
# Warmup Iteration   1: 2.330 ops/ms
# Warmup Iteration   2: 6.625 ops/ms
# Warmup Iteration   3: 8.760 ops/ms
Iteration   1: 9.526 ops/ms
Iteration   2: 9.452 ops/ms
Iteration   3: 9.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.423 ±(99.9%) 2.207 ops/ms [Average]
  (min, avg, max) = (9.290, 9.423, 9.526), stdev = 0.121
  CI (99.9%): [7.215, 11.630] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.685 ops/ms
# Warmup Iteration   2: 8.882 ops/ms
# Warmup Iteration   3: 10.055 ops/ms
Iteration   1: 9.762 ops/ms
Iteration   2: 9.806 ops/ms
Iteration   3: 10.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.907 ±(99.9%) 3.905 ops/ms [Average]
  (min, avg, max) = (9.762, 9.907, 10.153), stdev = 0.214
  CI (99.9%): [6.002, 13.812] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.190 ops/ms
# Warmup Iteration   2: 8.504 ops/ms
# Warmup Iteration   3: 8.878 ops/ms
Iteration   1: 9.495 ops/ms
Iteration   2: 9.627 ops/ms
Iteration   3: 9.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.556 ±(99.9%) 1.210 ops/ms [Average]
  (min, avg, max) = (9.495, 9.556, 9.627), stdev = 0.066
  CI (99.9%): [8.346, 10.766] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.186 ops/ms
# Warmup Iteration   2: 7.496 ops/ms
# Warmup Iteration   3: 7.994 ops/ms
Iteration   1: 8.264 ops/ms
Iteration   2: 8.460 ops/ms
Iteration   3: 8.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.385 ±(99.9%) 1.930 ops/ms [Average]
  (min, avg, max) = (8.264, 8.385, 8.460), stdev = 0.106
  CI (99.9%): [6.455, 10.315] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.555 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.007 ms/op
Iteration   1: 3.199 ±(99.9%) 0.009 ms/op
Iteration   2: 3.351 ±(99.9%) 0.007 ms/op
Iteration   3: 3.397 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.316 ±(99.9%) 1.889 ms/op [Average]
  (min, avg, max) = (3.199, 3.316, 3.397), stdev = 0.104
  CI (99.9%): [1.427, 5.205] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.699 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.004 ms/op
Iteration   1: 3.210 ±(99.9%) 0.009 ms/op
Iteration   2: 3.341 ±(99.9%) 0.008 ms/op
Iteration   3: 3.233 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.261 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (3.210, 3.261, 3.341), stdev = 0.070
  CI (99.9%): [1.987, 4.535] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.783 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.002 ms/op
Iteration   1: 3.374 ±(99.9%) 0.005 ms/op
Iteration   2: 3.641 ±(99.9%) 0.007 ms/op
Iteration   3: 3.319 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.445 ±(99.9%) 3.148 ms/op [Average]
  (min, avg, max) = (3.319, 3.445, 3.641), stdev = 0.173
  CI (99.9%): [0.297, 6.592] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.489 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.006 ms/op
Iteration   1: 3.847 ±(99.9%) 0.011 ms/op
Iteration   2: 3.764 ±(99.9%) 0.011 ms/op
Iteration   3: 3.897 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.836 ±(99.9%) 1.219 ms/op [Average]
  (min, avg, max) = (3.764, 3.836, 3.897), stdev = 0.067
  CI (99.9%): [2.617, 5.055] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.957 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.009 ms/op
Iteration   1: 3.351 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  18.213 ms/op
                 createUser·p0.9999: 27.802 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   2: 3.290 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  22.970 ms/op
                 createUser·p0.9999: 28.723 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  16.916 ms/op
                 createUser·p0.9999: 30.263 ms/op
                 createUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287025
  mean =      3.341 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17643 
    [ 2.500,  5.000) = 263754 
    [ 5.000,  7.500) = 4567 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     28.823 ms/op
     p(99.9990) =     31.440 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 9.137 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.010 ms/op
Iteration   1: 3.309 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 24.358 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  17.069 ms/op
                 existUser·p0.9999: 23.996 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   3: 3.356 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.417 ms/op
                 existUser·p0.999:  18.505 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288841
  mean =      3.322 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14465 
    [ 2.500,  5.000) = 268755 
    [ 5.000,  7.500) = 4576 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     24.955 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 8.183 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.009 ms/op
Iteration   1: 3.432 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  20.630 ms/op
                 getUser·p0.9999: 24.205 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   2: 3.463 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  21.911 ms/op
                 getUser·p0.9999: 24.896 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.434 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  16.279 ms/op
                 getUser·p0.9999: 24.809 ms/op
                 getUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278662
  mean =      3.443 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11451 
    [ 2.500,  5.000) = 258030 
    [ 5.000,  7.500) = 8247 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     24.749 ms/op
     p(99.9990) =     25.369 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 9.826 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.012 ms/op
Iteration   1: 3.936 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 21.524 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.435 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.326 ms/op
                 listUser·p0.9999: 16.564 ms/op
                 listUser·p1.00:   16.630 ms/op

Iteration   3: 3.903 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243694
  mean =      3.940 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 235007 
    [ 5.000,  7.500) = 6419 
    [ 7.500, 10.000) = 1517 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     14.390 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     22.061 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.423 ± 2.207  ops/ms
ClientPb.existUser                       thrpt       3   9.907 ± 3.905  ops/ms
ClientPb.getUser                         thrpt       3   9.556 ± 1.210  ops/ms
ClientPb.listUser                        thrpt       3   8.385 ± 1.930  ops/ms
ClientPb.createUser                       avgt       3   3.316 ± 1.889   ms/op
ClientPb.existUser                        avgt       3   3.261 ± 1.274   ms/op
ClientPb.getUser                          avgt       3   3.445 ± 3.148   ms/op
ClientPb.listUser                         avgt       3   3.836 ± 1.219   ms/op
ClientPb.createUser                     sample  287025   3.341 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.085           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.907           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.823           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  288841   3.322 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.926           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.497           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.779           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.953           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.887           ms/op
ClientPb.getUser                        sample  278662   3.443 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.321           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.105           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.749           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.592           ms/op
ClientPb.listUser                       sample  243694   3.940 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.435           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.390           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.496           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.217           ms/op
