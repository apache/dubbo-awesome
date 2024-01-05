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
# Warmup Iteration   1: 4.379 ops/ms
# Warmup Iteration   2: 12.012 ops/ms
# Warmup Iteration   3: 12.284 ops/ms
Iteration   1: 12.493 ops/ms
Iteration   2: 12.462 ops/ms
Iteration   3: 12.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.482 ±(99.9%) 0.318 ops/ms [Average]
  (min, avg, max) = (12.462, 12.482, 12.493), stdev = 0.017
  CI (99.9%): [12.164, 12.800] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.304 ops/ms
# Warmup Iteration   2: 13.046 ops/ms
# Warmup Iteration   3: 13.054 ops/ms
Iteration   1: 13.151 ops/ms
Iteration   2: 13.218 ops/ms
Iteration   3: 13.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.210 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (13.151, 13.210, 13.259), stdev = 0.055
  CI (99.9%): [12.215, 14.204] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.909 ops/ms
# Warmup Iteration   2: 12.351 ops/ms
# Warmup Iteration   3: 12.768 ops/ms
Iteration   1: 12.761 ops/ms
Iteration   2: 12.710 ops/ms
Iteration   3: 12.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.809 ±(99.9%) 2.374 ops/ms [Average]
  (min, avg, max) = (12.710, 12.809, 12.957), stdev = 0.130
  CI (99.9%): [10.435, 15.183] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.906 ops/ms
# Warmup Iteration   2: 10.535 ops/ms
# Warmup Iteration   3: 10.731 ops/ms
Iteration   1: 10.707 ops/ms
Iteration   2: 10.690 ops/ms
Iteration   3: 10.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.709 ±(99.9%) 0.358 ops/ms [Average]
  (min, avg, max) = (10.690, 10.709, 10.729), stdev = 0.020
  CI (99.9%): [10.350, 11.067] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.003 ms/op
Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (2.519, 2.542, 2.565), stdev = 0.023
  CI (99.9%): [2.121, 2.962] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (2.422, 2.428, 2.432), stdev = 0.005
  CI (99.9%): [2.334, 2.521] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.805 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.506 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.497, 2.506, 2.514), stdev = 0.009
  CI (99.9%): [2.346, 2.666] (assumes normal distribution)


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
# Warmup Iteration   1: 4.551 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.978 ±(99.9%) 0.005 ms/op
Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
Iteration   3: 2.967 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.975 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (2.967, 2.975, 2.981), stdev = 0.008
  CI (99.9%): [2.837, 3.113] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  11.388 ms/op
                 createUser·p0.9999: 14.008 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.568 ms/op
                 createUser·p0.999:  9.690 ms/op
                 createUser·p0.9999: 12.803 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.407 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  8.955 ms/op
                 createUser·p0.9999: 11.616 ms/op
                 createUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382191
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 184160 
    [ 2.500,  3.750) = 193996 
    [ 3.750,  5.000) = 3124 
    [ 5.000,  6.250) = 380 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      9.018 ms/op
     p(99.9900) =     13.051 ms/op
     p(99.9990) =     14.634 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.639 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.436 ms/op
                 existUser·p0.999:  5.877 ms/op
                 existUser·p0.9999: 14.022 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.404 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  5.562 ms/op
                 existUser·p0.9999: 16.522 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  8.814 ms/op
                 existUser·p0.9999: 12.316 ms/op
                 existUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395401
  mean =      2.426 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 201276 
    [ 2.500,  3.750) = 191660 
    [ 3.750,  5.000) = 1811 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      6.596 ms/op
     p(99.9900) =     14.107 ms/op
     p(99.9990) =     16.783 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.810 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.437 ms/op
                 getUser·p0.999:  4.891 ms/op
                 getUser·p0.9999: 14.075 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  5.726 ms/op
                 getUser·p0.9999: 12.095 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  7.516 ms/op
                 getUser·p0.9999: 12.059 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386653
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 192184 
    [ 2.500,  3.750) = 191392 
    [ 3.750,  5.000) = 2431 
    [ 5.000,  6.250) = 215 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      5.669 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     14.406 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.146 ms/op
                 listUser·p0.9999: 11.190 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 10.966 ms/op
                 listUser·p1.00:   11.108 ms/op

Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.668 ms/op
                 listUser·p0.9999: 11.194 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320726
  mean =      2.991 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 96478 
    [ 2.500,  3.750) = 186438 
    [ 3.750,  5.000) = 30488 
    [ 5.000,  6.250) = 5905 
    [ 6.250,  7.500) = 599 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 303 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     11.107 ms/op
     p(99.9990) =     12.644 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.482 ± 0.318  ops/ms
ClientPb.existUser                       thrpt       3  13.210 ± 0.995  ops/ms
ClientPb.getUser                         thrpt       3  12.809 ± 2.374  ops/ms
ClientPb.listUser                        thrpt       3  10.709 ± 0.358  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.420   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.094   ms/op
ClientPb.getUser                          avgt       3   2.506 ± 0.160   ms/op
ClientPb.listUser                         avgt       3   2.975 ± 0.138   ms/op
ClientPb.createUser                     sample  382191   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.407           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.018           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.051           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.778           ms/op
ClientPb.existUser                      sample  395401   2.426 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.825           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.596           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.107           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.564           ms/op
ClientPb.getUser                        sample  386653   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.898           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.669           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.255           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.516           ms/op
ClientPb.listUser                       sample  320726   2.991 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.107           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.714           ms/op
