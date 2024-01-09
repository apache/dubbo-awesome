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
# Warmup Iteration   1: 4.539 ops/ms
# Warmup Iteration   2: 12.274 ops/ms
# Warmup Iteration   3: 12.520 ops/ms
Iteration   1: 12.792 ops/ms
Iteration   2: 12.826 ops/ms
Iteration   3: 12.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.844 ±(99.9%) 1.166 ops/ms [Average]
  (min, avg, max) = (12.792, 12.844, 12.915), stdev = 0.064
  CI (99.9%): [11.678, 14.010] (assumes normal distribution)


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
# Warmup Iteration   1: 8.222 ops/ms
# Warmup Iteration   2: 13.288 ops/ms
# Warmup Iteration   3: 13.190 ops/ms
Iteration   1: 13.255 ops/ms
Iteration   2: 13.344 ops/ms
Iteration   3: 13.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.282 ±(99.9%) 0.977 ops/ms [Average]
  (min, avg, max) = (13.247, 13.282, 13.344), stdev = 0.054
  CI (99.9%): [12.305, 14.259] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.867 ops/ms
# Warmup Iteration   2: 12.748 ops/ms
# Warmup Iteration   3: 12.816 ops/ms
Iteration   1: 12.678 ops/ms
Iteration   2: 13.060 ops/ms
Iteration   3: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.870 ±(99.9%) 3.481 ops/ms [Average]
  (min, avg, max) = (12.678, 12.870, 13.060), stdev = 0.191
  CI (99.9%): [9.389, 16.351] (assumes normal distribution)


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
# Warmup Iteration   1: 6.725 ops/ms
# Warmup Iteration   2: 10.438 ops/ms
# Warmup Iteration   3: 10.627 ops/ms
Iteration   1: 10.738 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.713 ±(99.9%) 1.403 ops/ms [Average]
  (min, avg, max) = (10.627, 10.713, 10.775), stdev = 0.077
  CI (99.9%): [9.311, 12.116] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.003 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.491 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (2.464, 2.491, 2.531), stdev = 0.035
  CI (99.9%): [1.845, 3.137] (assumes normal distribution)


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.004 ms/op
Iteration   1: 2.428 ±(99.9%) 0.004 ms/op
Iteration   2: 2.408 ±(99.9%) 0.003 ms/op
Iteration   3: 2.417 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.408, 2.418, 2.428), stdev = 0.010
  CI (99.9%): [2.236, 2.599] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.003 ms/op
Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
Iteration   3: 2.450 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.450, 2.461, 2.476), stdev = 0.013
  CI (99.9%): [2.220, 2.703] (assumes normal distribution)


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
# Warmup Iteration   1: 4.907 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.004 ms/op
Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.013 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (3.002, 3.013, 3.025), stdev = 0.012
  CI (99.9%): [2.799, 3.227] (assumes normal distribution)


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 13.652 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  8.789 ms/op
                 createUser·p0.9999: 18.448 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  6.750 ms/op
                 createUser·p0.9999: 10.224 ms/op
                 createUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386054
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 187727 
    [ 2.500,  3.750) = 194394 
    [ 3.750,  5.000) = 3071 
    [ 5.000,  6.250) = 398 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      7.658 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     18.523 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  6.304 ms/op
                 existUser·p0.9999: 13.825 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.418 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  7.281 ms/op
                 existUser·p0.9999: 13.124 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   3: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  8.320 ms/op
                 existUser·p0.9999: 11.551 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396684
  mean =      2.417 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 200358 
    [ 2.500,  3.750) = 193221 
    [ 3.750,  5.000) = 2277 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      7.654 ms/op
     p(99.9900) =     13.211 ms/op
     p(99.9990) =     14.191 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.006 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  7.850 ms/op
                 getUser·p0.9999: 13.566 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  7.160 ms/op
                 getUser·p0.9999: 12.780 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  6.033 ms/op
                 getUser·p0.9999: 11.600 ms/op
                 getUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390646
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 195228 
    [ 2.500,  3.750) = 191527 
    [ 3.750,  5.000) = 3154 
    [ 5.000,  6.250) = 268 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      7.203 ms/op
     p(99.9900) =     12.975 ms/op
     p(99.9990) =     13.904 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 4.655 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 3.040 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   6.373 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 10.755 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   2: 3.061 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  10.020 ms/op
                 listUser·p0.9999: 13.739 ms/op
                 listUser·p1.00:   14.402 ms/op

Iteration   3: 2.929 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.648 ms/op
                 listUser·p0.9999: 13.929 ms/op
                 listUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318783
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 209 
    [ 1.250,  2.500) = 101930 
    [ 2.500,  3.750) = 173897 
    [ 3.750,  5.000) = 32821 
    [ 5.000,  6.250) = 6910 
    [ 6.250,  7.500) = 1671 
    [ 7.500,  8.750) = 695 
    [ 8.750, 10.000) = 404 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =      9.654 ms/op
     p(99.9900) =     12.935 ms/op
     p(99.9990) =     14.557 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.844 ± 1.166  ops/ms
ClientPb.existUser                       thrpt       3  13.282 ± 0.977  ops/ms
ClientPb.getUser                         thrpt       3  12.870 ± 3.481  ops/ms
ClientPb.listUser                        thrpt       3  10.713 ± 1.403  ops/ms
ClientPb.createUser                       avgt       3   2.491 ± 0.646   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.181   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.241   ms/op
ClientPb.listUser                         avgt       3   3.013 ± 0.214   ms/op
ClientPb.createUser                     sample  386054   2.484 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.734           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.658           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.612           ms/op
ClientPb.existUser                      sample  396684   2.417 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.965           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.654           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.211           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  390646   2.456 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.686           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.982           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.203           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.975           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.041           ms/op
ClientPb.listUser                       sample  318783   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.885           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.177           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.654           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.935           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.877           ms/op
