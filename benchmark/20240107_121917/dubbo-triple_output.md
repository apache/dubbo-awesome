# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.011 ops/ms
# Warmup Iteration   2: 12.306 ops/ms
# Warmup Iteration   3: 12.369 ops/ms
Iteration   1: 12.757 ops/ms
Iteration   2: 12.896 ops/ms
Iteration   3: 12.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.824 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (12.757, 12.824, 12.896), stdev = 0.070
  CI (99.9%): [11.551, 14.097] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.217 ops/ms
# Warmup Iteration   2: 13.058 ops/ms
# Warmup Iteration   3: 13.111 ops/ms
Iteration   1: 13.074 ops/ms
Iteration   2: 13.201 ops/ms
Iteration   3: 13.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.141 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (13.074, 13.141, 13.201), stdev = 0.064
  CI (99.9%): [11.979, 14.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.118 ops/ms
# Warmup Iteration   2: 12.642 ops/ms
# Warmup Iteration   3: 12.911 ops/ms
Iteration   1: 12.933 ops/ms
Iteration   2: 12.973 ops/ms
Iteration   3: 12.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.888 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (12.757, 12.888, 12.973), stdev = 0.115
  CI (99.9%): [10.795, 14.981] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.291 ops/ms
# Warmup Iteration   2: 10.419 ops/ms
# Warmup Iteration   3: 10.462 ops/ms
Iteration   1: 10.466 ops/ms
Iteration   2: 10.430 ops/ms
Iteration   3: 10.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.487 ±(99.9%) 1.254 ops/ms [Average]
  (min, avg, max) = (10.430, 10.487, 10.563), stdev = 0.069
  CI (99.9%): [9.232, 11.741] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.064 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.003 ms/op
Iteration   1: 2.518 ±(99.9%) 0.003 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (2.501, 2.520, 2.540), stdev = 0.020
  CI (99.9%): [2.157, 2.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.004 ms/op
Iteration   1: 2.416 ±(99.9%) 0.005 ms/op
Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
Iteration   3: 2.414 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.414, 2.422, 2.436), stdev = 0.012
  CI (99.9%): [2.202, 2.642] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.478, 2.494, 2.510), stdev = 0.016
  CI (99.9%): [2.203, 2.785] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.631 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
Iteration   3: 2.992 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (2.980, 2.987, 2.992), stdev = 0.006
  CI (99.9%): [2.869, 3.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.550 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.992 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  10.437 ms/op
                 createUser·p0.9999: 13.311 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  9.535 ms/op
                 createUser·p0.9999: 11.977 ms/op
                 createUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376406
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 178142 
    [ 2.500,  3.750) = 193523 
    [ 3.750,  5.000) = 3754 
    [ 5.000,  6.250) = 493 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      9.604 ms/op
     p(99.9900) =     14.562 ms/op
     p(99.9990) =     17.670 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.577 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.330 ms/op
                 existUser·p0.999:  5.498 ms/op
                 existUser·p0.9999: 14.971 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  9.333 ms/op
                 existUser·p0.9999: 13.124 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  8.041 ms/op
                 existUser·p0.9999: 13.597 ms/op
                 existUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393948
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 195958 
    [ 2.500,  3.750) = 194752 
    [ 3.750,  5.000) = 2337 
    [ 5.000,  6.250) = 409 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      8.075 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     15.108 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  8.429 ms/op
                 getUser·p0.9999: 14.783 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  5.875 ms/op
                 getUser·p0.9999: 12.307 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.067 ms/op
                 getUser·p0.999:  6.866 ms/op
                 getUser·p0.9999: 15.191 ms/op
                 getUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386654
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 193800 
    [ 2.500,  3.750) = 187874 
    [ 3.750,  5.000) = 3969 
    [ 5.000,  6.250) = 506 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 80 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      7.331 ms/op
     p(99.9900) =     14.751 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.777 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.009 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.645 ms/op
                 listUser·p0.9999: 11.289 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.726 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.489 ms/op
                 listUser·p0.9999: 10.991 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  10.240 ms/op
                 listUser·p0.9999: 13.818 ms/op
                 listUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318582
  mean =      3.010 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 94060 
    [ 2.500,  3.750) = 184573 
    [ 3.750,  5.000) = 32459 
    [ 5.000,  6.250) = 5955 
    [ 6.250,  7.500) = 701 
    [ 7.500,  8.750) = 177 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 204 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     12.705 ms/op
     p(99.9990) =     14.013 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.824 ± 1.273  ops/ms
ClientPb.existUser                       thrpt       3  13.141 ± 1.163  ops/ms
ClientPb.getUser                         thrpt       3  12.888 ± 2.093  ops/ms
ClientPb.listUser                        thrpt       3  10.487 ± 1.254  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.363   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.220   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.291   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.118   ms/op
ClientPb.createUser                     sample  376406   2.548 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.946           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.604           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.562           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.121           ms/op
ClientPb.existUser                      sample  393948   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.771           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.075           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.877           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.532           ms/op
ClientPb.getUser                        sample  386654   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.861           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.331           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.751           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.597           ms/op
ClientPb.listUser                       sample  318582   3.010 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.765           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.705           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.189           ms/op
