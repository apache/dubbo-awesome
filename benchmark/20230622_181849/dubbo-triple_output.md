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
# Warmup Iteration   1: 2.574 ops/ms
# Warmup Iteration   2: 4.807 ops/ms
# Warmup Iteration   3: 9.280 ops/ms
Iteration   1: 9.780 ops/ms
Iteration   2: 10.288 ops/ms
Iteration   3: 9.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.970 ±(99.9%) 5.057 ops/ms [Average]
  (min, avg, max) = (9.780, 9.970, 10.288), stdev = 0.277
  CI (99.9%): [4.913, 15.028] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.619 ops/ms
# Warmup Iteration   2: 9.410 ops/ms
# Warmup Iteration   3: 9.763 ops/ms
Iteration   1: 10.415 ops/ms
Iteration   2: 10.272 ops/ms
Iteration   3: 10.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.354 ±(99.9%) 1.346 ops/ms [Average]
  (min, avg, max) = (10.272, 10.354, 10.415), stdev = 0.074
  CI (99.9%): [9.008, 11.700] (assumes normal distribution)


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
# Warmup Iteration   1: 3.567 ops/ms
# Warmup Iteration   2: 9.154 ops/ms
# Warmup Iteration   3: 9.704 ops/ms
Iteration   1: 9.647 ops/ms
Iteration   2: 10.029 ops/ms
Iteration   3: 9.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.712 ±(99.9%) 5.290 ops/ms [Average]
  (min, avg, max) = (9.460, 9.712, 10.029), stdev = 0.290
  CI (99.9%): [4.423, 15.002] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.026 ops/ms
# Warmup Iteration   2: 7.390 ops/ms
# Warmup Iteration   3: 8.309 ops/ms
Iteration   1: 8.450 ops/ms
Iteration   2: 8.465 ops/ms
Iteration   3: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.454 ±(99.9%) 0.170 ops/ms [Average]
  (min, avg, max) = (8.448, 8.454, 8.465), stdev = 0.009
  CI (99.9%): [8.284, 8.623] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.625 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.005 ms/op
Iteration   1: 3.152 ±(99.9%) 0.003 ms/op
Iteration   2: 3.128 ±(99.9%) 0.005 ms/op
Iteration   3: 3.140 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.140 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (3.128, 3.140, 3.152), stdev = 0.012
  CI (99.9%): [2.928, 3.352] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.848 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.003 ms/op
Iteration   1: 3.151 ±(99.9%) 0.004 ms/op
Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
Iteration   3: 3.186 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.164 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.151, 3.164, 3.186), stdev = 0.020
  CI (99.9%): [2.805, 3.523] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.964 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.005 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
Iteration   2: 3.302 ±(99.9%) 0.003 ms/op
Iteration   3: 3.196 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.223 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (3.171, 3.223, 3.302), stdev = 0.070
  CI (99.9%): [1.948, 4.498] (assumes normal distribution)


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
# Warmup Iteration   1: 9.613 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.009 ms/op
Iteration   1: 3.728 ±(99.9%) 0.006 ms/op
Iteration   2: 3.630 ±(99.9%) 0.011 ms/op
Iteration   3: 3.666 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.675 ±(99.9%) 0.912 ms/op [Average]
  (min, avg, max) = (3.630, 3.675, 3.728), stdev = 0.050
  CI (99.9%): [2.762, 4.587] (assumes normal distribution)


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
# Warmup Iteration   1: 7.446 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.010 ms/op
Iteration   1: 3.186 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  10.626 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 21.833 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  15.078 ms/op
                 createUser·p0.9999: 28.179 ms/op
                 createUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294188
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21737 
    [ 2.500,  5.000) = 265759 
    [ 5.000,  7.500) = 5963 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     26.861 ms/op
     p(99.9990) =     29.333 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 8.028 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.293 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
Iteration   1: 3.025 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 20.228 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 3.102 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  15.707 ms/op
                 existUser·p0.9999: 22.675 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  12.269 ms/op
                 existUser·p0.9999: 20.200 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313895
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20172 
    [ 2.500,  5.000) = 288680 
    [ 5.000,  7.500) = 4071 
    [ 7.500, 10.000) = 382 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.486 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     12.732 ms/op
     p(99.9900) =     21.995 ms/op
     p(99.9990) =     23.046 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 8.503 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.010 ms/op
Iteration   1: 3.262 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   6.320 ms/op
                 getUser·p0.999:  17.924 ms/op
                 getUser·p0.9999: 20.892 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.599 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.314 ms/op
                 getUser·p0.95:   3.498 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  14.449 ms/op
                 getUser·p0.9999: 22.446 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.205 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   6.002 ms/op
                 getUser·p0.999:  11.226 ms/op
                 getUser·p0.9999: 38.732 ms/op
                 getUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302094
  mean =      3.177 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12805 
    [ 2.500,  5.000) = 282985 
    [ 5.000,  7.500) = 5149 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     14.874 ms/op
     p(99.9900) =     36.293 ms/op
     p(99.9990) =     38.990 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


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
# Warmup Iteration   1: 8.923 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.013 ms/op
Iteration   1: 3.790 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  15.214 ms/op
                 listUser·p0.9999: 21.499 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 3.619 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 14.587 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   3: 3.828 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 21.222 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256362
  mean =      3.744 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 248925 
    [ 5.000,  7.500) = 5295 
    [ 7.500, 10.000) = 1305 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      7.114 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.690 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.970 ± 5.057  ops/ms
ClientPb.existUser                       thrpt       3  10.354 ± 1.346  ops/ms
ClientPb.getUser                         thrpt       3   9.712 ± 5.290  ops/ms
ClientPb.listUser                        thrpt       3   8.454 ± 0.170  ops/ms
ClientPb.createUser                       avgt       3   3.140 ± 0.212   ms/op
ClientPb.existUser                        avgt       3   3.164 ± 0.359   ms/op
ClientPb.getUser                          avgt       3   3.223 ± 1.275   ms/op
ClientPb.listUser                         avgt       3   3.675 ± 0.912   ms/op
ClientPb.createUser                     sample  294188   3.260 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.916           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.352           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.458           ms/op
ClientPb.existUser                      sample  313895   3.056 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.860           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.732           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.995           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.953           ms/op
ClientPb.getUser                        sample  302094   3.177 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.227           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.874           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.293           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.387           ms/op
ClientPb.listUser                       sample  256362   3.744 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.221           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.114           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.386           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.070           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.741           ms/op
