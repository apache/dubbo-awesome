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
# Warmup Iteration   1: 3.811 ops/ms
# Warmup Iteration   2: 11.842 ops/ms
# Warmup Iteration   3: 12.003 ops/ms
Iteration   1: 12.441 ops/ms
Iteration   2: 12.417 ops/ms
Iteration   3: 12.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.465 ±(99.9%) 1.157 ops/ms [Average]
  (min, avg, max) = (12.417, 12.465, 12.537), stdev = 0.063
  CI (99.9%): [11.308, 13.621] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.641 ops/ms
# Warmup Iteration   2: 12.701 ops/ms
# Warmup Iteration   3: 12.907 ops/ms
Iteration   1: 12.906 ops/ms
Iteration   2: 12.889 ops/ms
Iteration   3: 12.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.903 ±(99.9%) 0.237 ops/ms [Average]
  (min, avg, max) = (12.889, 12.903, 12.914), stdev = 0.013
  CI (99.9%): [12.666, 13.140] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.964 ops/ms
# Warmup Iteration   2: 12.260 ops/ms
# Warmup Iteration   3: 12.583 ops/ms
Iteration   1: 12.572 ops/ms
Iteration   2: 12.488 ops/ms
Iteration   3: 12.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.587 ±(99.9%) 1.947 ops/ms [Average]
  (min, avg, max) = (12.488, 12.587, 12.700), stdev = 0.107
  CI (99.9%): [10.639, 14.534] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.324 ops/ms
# Warmup Iteration   2: 10.183 ops/ms
# Warmup Iteration   3: 10.404 ops/ms
Iteration   1: 10.367 ops/ms
Iteration   2: 10.305 ops/ms
Iteration   3: 10.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.365 ±(99.9%) 1.068 ops/ms [Average]
  (min, avg, max) = (10.305, 10.365, 10.422), stdev = 0.059
  CI (99.9%): [9.297, 11.433] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.550 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.697 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.628 ±(99.9%) 0.005 ms/op
Iteration   1: 2.594 ±(99.9%) 0.004 ms/op
Iteration   2: 2.589 ±(99.9%) 0.004 ms/op
Iteration   3: 2.597 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.593 ±(99.9%) 0.070 ms/op [Average]
  (min, avg, max) = (2.589, 2.593, 2.597), stdev = 0.004
  CI (99.9%): [2.523, 2.663] (assumes normal distribution)


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.524 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.505, 2.524, 2.545), stdev = 0.020
  CI (99.9%): [2.163, 2.885] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.555 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.544 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.537, 2.544, 2.555), stdev = 0.010
  CI (99.9%): [2.368, 2.720] (assumes normal distribution)


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.005 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
Iteration   3: 3.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.054 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.044, 3.054, 3.074), stdev = 0.017
  CI (99.9%): [2.749, 3.360] (assumes normal distribution)


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.705 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.561 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  11.247 ms/op
                 createUser·p0.9999: 13.435 ms/op
                 createUser·p1.00:   14.467 ms/op

Iteration   2: 2.588 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 12.479 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.578 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 11.102 ms/op
                 createUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372288
  mean =      2.576 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 175760 
    [ 2.500,  3.750) = 191854 
    [ 3.750,  5.000) = 3712 
    [ 5.000,  6.250) = 489 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     12.809 ms/op
     p(99.9990) =     13.673 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  5.489 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  7.371 ms/op
                 existUser·p0.9999: 13.238 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  8.779 ms/op
                 existUser·p0.9999: 12.243 ms/op
                 existUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388456
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 188939 
    [ 2.500,  3.750) = 196136 
    [ 3.750,  5.000) = 2728 
    [ 5.000,  6.250) = 195 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.883 ms/op
     p(99.9900) =     13.241 ms/op
     p(99.9990) =     14.160 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  11.991 ms/op
                 getUser·p0.9999: 14.716 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.189 ms/op
                 getUser·p0.999:  9.745 ms/op
                 getUser·p0.9999: 13.703 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  8.337 ms/op
                 getUser·p0.9999: 14.784 ms/op
                 getUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380653
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 185404 
    [ 2.500,  3.750) = 189153 
    [ 3.750,  5.000) = 4995 
    [ 5.000,  6.250) = 605 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      8.547 ms/op
     p(99.9900) =     14.546 ms/op
     p(99.9990) =     15.181 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 4.898 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.009 ms/op
Iteration   1: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  8.997 ms/op
                 listUser·p0.9999: 11.538 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 12.561 ms/op
                 listUser·p1.00:   14.778 ms/op

Iteration   3: 3.081 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.867 ms/op
                 listUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311313
  mean =      3.081 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 81046 
    [ 2.500,  3.750) = 185350 
    [ 3.750,  5.000) = 36020 
    [ 5.000,  6.250) = 7123 
    [ 6.250,  7.500) = 1038 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.860 ms/op
     p(99.9990) =     14.010 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.465 ± 1.157  ops/ms
ClientPb.existUser                       thrpt       3  12.903 ± 0.237  ops/ms
ClientPb.getUser                         thrpt       3  12.587 ± 1.947  ops/ms
ClientPb.listUser                        thrpt       3  10.365 ± 1.068  ops/ms
ClientPb.createUser                       avgt       3   2.593 ± 0.070   ms/op
ClientPb.existUser                        avgt       3   2.524 ± 0.361   ms/op
ClientPb.getUser                          avgt       3   2.544 ± 0.176   ms/op
ClientPb.listUser                         avgt       3   3.054 ± 0.306   ms/op
ClientPb.createUser                     sample  372288   2.576 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.807           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.617           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.809           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.467           ms/op
ClientPb.existUser                      sample  388456   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.936           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.883           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.241           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  380653   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.948           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.547           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.546           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.368           ms/op
ClientPb.listUser                       sample  311313   3.081 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.816           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.860           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.778           ms/op
