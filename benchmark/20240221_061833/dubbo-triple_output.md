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
# Warmup Iteration   1: 5.001 ops/ms
# Warmup Iteration   2: 12.034 ops/ms
# Warmup Iteration   3: 12.223 ops/ms
Iteration   1: 12.540 ops/ms
Iteration   2: 12.603 ops/ms
Iteration   3: 12.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.583 ±(99.9%) 0.686 ops/ms [Average]
  (min, avg, max) = (12.540, 12.583, 12.607), stdev = 0.038
  CI (99.9%): [11.898, 13.269] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.469 ops/ms
# Warmup Iteration   2: 13.022 ops/ms
# Warmup Iteration   3: 13.056 ops/ms
Iteration   1: 13.163 ops/ms
Iteration   2: 12.981 ops/ms
Iteration   3: 13.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.059 ±(99.9%) 1.708 ops/ms [Average]
  (min, avg, max) = (12.981, 13.059, 13.163), stdev = 0.094
  CI (99.9%): [11.351, 14.767] (assumes normal distribution)


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
# Warmup Iteration   1: 8.223 ops/ms
# Warmup Iteration   2: 12.531 ops/ms
# Warmup Iteration   3: 12.637 ops/ms
Iteration   1: 12.620 ops/ms
Iteration   2: 12.540 ops/ms
Iteration   3: 12.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.568 ±(99.9%) 0.827 ops/ms [Average]
  (min, avg, max) = (12.540, 12.568, 12.620), stdev = 0.045
  CI (99.9%): [11.741, 13.395] (assumes normal distribution)


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
# Warmup Iteration   1: 6.458 ops/ms
# Warmup Iteration   2: 10.142 ops/ms
# Warmup Iteration   3: 10.319 ops/ms
Iteration   1: 10.198 ops/ms
Iteration   2: 10.350 ops/ms
Iteration   3: 10.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.303 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (10.198, 10.303, 10.360), stdev = 0.091
  CI (99.9%): [8.647, 11.959] (assumes normal distribution)


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
# Warmup Iteration   1: 4.308 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.602 ±(99.9%) 0.005 ms/op
Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (2.530, 2.566, 2.602), stdev = 0.036
  CI (99.9%): [1.909, 3.222] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.004 ms/op
Iteration   1: 2.417 ±(99.9%) 0.003 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.403 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (2.403, 2.417, 2.431), stdev = 0.014
  CI (99.9%): [2.169, 2.665] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.003 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.476, 2.488, 2.508), stdev = 0.017
  CI (99.9%): [2.169, 2.807] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.671 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.005 ms/op
Iteration   1: 3.051 ±(99.9%) 0.004 ms/op
Iteration   2: 3.039 ±(99.9%) 0.007 ms/op
Iteration   3: 3.035 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.042 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (3.035, 3.042, 3.051), stdev = 0.008
  CI (99.9%): [2.895, 3.188] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.300 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  11.942 ms/op
                 createUser·p0.9999: 13.583 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.720 ms/op
                 createUser·p0.999:  9.356 ms/op
                 createUser·p0.9999: 14.647 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   4.030 ms/op
                 createUser·p0.999:  8.283 ms/op
                 createUser·p0.9999: 11.197 ms/op
                 createUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380019
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 183588 
    [ 2.500,  3.750) = 192274 
    [ 3.750,  5.000) = 3311 
    [ 5.000,  6.250) = 358 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.290 ms/op
     p(99.9900) =     13.943 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  6.178 ms/op
                 existUser·p0.9999: 13.470 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  8.012 ms/op
                 existUser·p0.9999: 12.812 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  6.257 ms/op
                 existUser·p0.9999: 11.597 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390570
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 194578 
    [ 2.500,  3.750) = 192605 
    [ 3.750,  5.000) = 2636 
    [ 5.000,  6.250) = 247 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      7.081 ms/op
     p(99.9900) =     13.084 ms/op
     p(99.9990) =     13.675 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  11.731 ms/op
                 getUser·p0.9999: 16.703 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   2: 2.596 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.630 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.404 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  9.727 ms/op
                 getUser·p0.9999: 16.744 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  8.676 ms/op
                 getUser·p0.9999: 11.655 ms/op
                 getUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374681
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 181393 
    [ 2.500,  3.750) = 185755 
    [ 3.750,  5.000) = 6147 
    [ 5.000,  6.250) = 832 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     16.352 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.078 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  8.511 ms/op
                 listUser·p0.9999: 10.398 ms/op
                 listUser·p1.00:   10.945 ms/op

Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.408 ms/op
                 listUser·p1.00:   10.682 ms/op

Iteration   3: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.441 ms/op
                 listUser·p0.9999: 11.878 ms/op
                 listUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311823
  mean =      3.076 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 81193 
    [ 2.500,  3.750) = 186279 
    [ 3.750,  5.000) = 35688 
    [ 5.000,  6.250) = 6902 
    [ 6.250,  7.500) = 947 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 326 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     10.715 ms/op
     p(99.9990) =     13.365 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.583 ± 0.686  ops/ms
ClientPb.existUser                       thrpt       3  13.059 ± 1.708  ops/ms
ClientPb.getUser                         thrpt       3  12.568 ± 0.827  ops/ms
ClientPb.listUser                        thrpt       3  10.303 ± 1.656  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.657   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.248   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.319   ms/op
ClientPb.listUser                         avgt       3   3.042 ± 0.146   ms/op
ClientPb.createUser                     sample  380019   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.887           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.290           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  390570   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.760           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.081           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.084           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.910           ms/op
ClientPb.getUser                        sample  374681   2.560 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.846           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.798           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.352           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.662           ms/op
ClientPb.listUser                       sample  311823   3.076 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.774           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.715           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.435           ms/op
