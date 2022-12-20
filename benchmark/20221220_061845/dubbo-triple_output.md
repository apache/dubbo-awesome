# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.118 ops/ms
# Warmup Iteration   2: 5.668 ops/ms
# Warmup Iteration   3: 8.731 ops/ms
Iteration   1: 8.809 ops/ms
Iteration   2: 9.309 ops/ms
Iteration   3: 9.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.164 ±(99.9%) 5.648 ops/ms [Average]
  (min, avg, max) = (8.809, 9.164, 9.375), stdev = 0.310
  CI (99.9%): [3.516, 14.813] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.277 ops/ms
# Warmup Iteration   2: 8.850 ops/ms
# Warmup Iteration   3: 9.424 ops/ms
Iteration   1: 9.748 ops/ms
Iteration   2: 9.730 ops/ms
Iteration   3: 9.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.747 ±(99.9%) 0.320 ops/ms [Average]
  (min, avg, max) = (9.730, 9.747, 9.765), stdev = 0.018
  CI (99.9%): [9.427, 10.068] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.056 ops/ms
# Warmup Iteration   2: 8.393 ops/ms
# Warmup Iteration   3: 8.997 ops/ms
Iteration   1: 9.420 ops/ms
Iteration   2: 9.750 ops/ms
Iteration   3: 9.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.476 ±(99.9%) 4.574 ops/ms [Average]
  (min, avg, max) = (9.258, 9.476, 9.750), stdev = 0.251
  CI (99.9%): [4.902, 14.050] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.928 ops/ms
# Warmup Iteration   2: 7.314 ops/ms
# Warmup Iteration   3: 7.670 ops/ms
Iteration   1: 7.878 ops/ms
Iteration   2: 8.033 ops/ms
Iteration   3: 8.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.003 ±(99.9%) 2.069 ops/ms [Average]
  (min, avg, max) = (7.878, 8.003, 8.099), stdev = 0.113
  CI (99.9%): [5.935, 10.072] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 11.303 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.004 ms/op
Iteration   1: 3.554 ±(99.9%) 0.007 ms/op
Iteration   2: 3.492 ±(99.9%) 0.009 ms/op
Iteration   3: 3.464 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.503 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (3.464, 3.503, 3.554), stdev = 0.046
  CI (99.9%): [2.662, 4.344] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.708 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.008 ms/op
Iteration   1: 3.347 ±(99.9%) 0.006 ms/op
Iteration   2: 3.264 ±(99.9%) 0.005 ms/op
Iteration   3: 3.277 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.296 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (3.264, 3.296, 3.347), stdev = 0.045
  CI (99.9%): [2.482, 4.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.155 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.009 ms/op
Iteration   1: 3.359 ±(99.9%) 0.007 ms/op
Iteration   2: 3.481 ±(99.9%) 0.007 ms/op
Iteration   3: 3.460 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.433 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (3.359, 3.433, 3.481), stdev = 0.065
  CI (99.9%): [2.249, 4.617] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.451 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.007 ms/op
Iteration   1: 3.976 ±(99.9%) 0.012 ms/op
Iteration   2: 4.114 ±(99.9%) 0.008 ms/op
Iteration   3: 4.106 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.066 ±(99.9%) 1.412 ms/op [Average]
  (min, avg, max) = (3.976, 4.066, 4.114), stdev = 0.077
  CI (99.9%): [2.654, 5.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.075 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.009 ms/op
Iteration   1: 3.461 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  21.809 ms/op
                 createUser·p0.9999: 30.081 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   2: 3.493 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  23.197 ms/op
                 createUser·p0.9999: 29.584 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   3: 3.452 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  19.149 ms/op
                 createUser·p0.9999: 27.663 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276586
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6255 
    [ 2.500,  5.000) = 263013 
    [ 5.000,  7.500) = 6408 
    [ 7.500, 10.000) = 508 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     29.514 ms/op
     p(99.9990) =     30.391 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.077 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.010 ms/op
Iteration   1: 3.449 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  20.677 ms/op
                 existUser·p0.9999: 25.452 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.364 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  22.084 ms/op
                 existUser·p0.9999: 26.410 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   3: 3.317 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  10.479 ms/op
                 existUser·p0.9999: 28.374 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284213
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9402 
    [ 2.500,  5.000) = 267449 
    [ 5.000,  7.500) = 6447 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 80 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     10.813 ms/op
     p(99.9900) =     27.418 ms/op
     p(99.9990) =     28.889 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.693 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
Iteration   1: 3.523 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.729 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  21.014 ms/op
                 getUser·p0.9999: 23.343 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.095 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  22.151 ms/op
                 getUser·p0.9999: 25.517 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  20.543 ms/op
                 getUser·p0.9999: 28.198 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278322
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13561 
    [ 2.500,  5.000) = 257434 
    [ 5.000,  7.500) = 6251 
    [ 7.500, 10.000) = 652 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     20.797 ms/op
     p(99.9900) =     27.334 ms/op
     p(99.9990) =     28.897 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.295 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.014 ms/op
Iteration   1: 4.131 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  19.841 ms/op
                 listUser·p0.9999: 28.844 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   2: 4.085 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  16.036 ms/op
                 listUser·p0.9999: 21.567 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.911 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  16.509 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237411
  mean =      4.040 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 229174 
    [ 5.000,  7.500) = 5854 
    [ 7.500, 10.000) = 1634 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.495 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     27.337 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.164 ± 5.648  ops/ms
ClientPb.existUser                       thrpt       3   9.747 ± 0.320  ops/ms
ClientPb.getUser                         thrpt       3   9.476 ± 4.574  ops/ms
ClientPb.listUser                        thrpt       3   8.003 ± 2.069  ops/ms
ClientPb.createUser                       avgt       3   3.503 ± 0.841   ms/op
ClientPb.existUser                        avgt       3   3.296 ± 0.813   ms/op
ClientPb.getUser                          avgt       3   3.433 ± 1.184   ms/op
ClientPb.listUser                         avgt       3   4.066 ± 1.412   ms/op
ClientPb.createUser                     sample  276586   3.468 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.986           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.661           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.514           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.293           ms/op
ClientPb.existUser                      sample  284213   3.376 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.294           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.813           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.418           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.229           ms/op
ClientPb.getUser                        sample  278322   3.447 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.797           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.334           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.065           ms/op
ClientPb.listUser                       sample  237411   4.040 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.126           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.495           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.072           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.337           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.852           ms/op
