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
# Warmup Iteration   1: 2.334 ops/ms
# Warmup Iteration   2: 6.332 ops/ms
# Warmup Iteration   3: 8.546 ops/ms
Iteration   1: 9.450 ops/ms
Iteration   2: 9.466 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.451 ±(99.9%) 0.281 ops/ms [Average]
  (min, avg, max) = (9.436, 9.451, 9.466), stdev = 0.015
  CI (99.9%): [9.170, 9.732] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 9.407 ops/ms
# Warmup Iteration   3: 9.766 ops/ms
Iteration   1: 10.091 ops/ms
Iteration   2: 10.058 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.948 ±(99.9%) 3.997 ops/ms [Average]
  (min, avg, max) = (9.696, 9.948, 10.091), stdev = 0.219
  CI (99.9%): [5.951, 13.945] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 8.531 ops/ms
# Warmup Iteration   3: 8.992 ops/ms
Iteration   1: 9.386 ops/ms
Iteration   2: 9.285 ops/ms
Iteration   3: 8.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.206 ±(99.9%) 4.206 ops/ms [Average]
  (min, avg, max) = (8.946, 9.206, 9.386), stdev = 0.231
  CI (99.9%): [5.000, 13.412] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.274 ops/ms
# Warmup Iteration   2: 7.290 ops/ms
# Warmup Iteration   3: 7.719 ops/ms
Iteration   1: 8.185 ops/ms
Iteration   2: 8.078 ops/ms
Iteration   3: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.135 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (8.078, 8.135, 8.185), stdev = 0.054
  CI (99.9%): [7.147, 9.124] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.238 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.012 ms/op
Iteration   1: 3.291 ±(99.9%) 0.009 ms/op
Iteration   2: 3.217 ±(99.9%) 0.014 ms/op
Iteration   3: 3.340 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.283 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (3.217, 3.283, 3.340), stdev = 0.062
  CI (99.9%): [2.146, 4.419] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.715 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.003 ms/op
Iteration   1: 3.206 ±(99.9%) 0.010 ms/op
Iteration   2: 3.151 ±(99.9%) 0.012 ms/op
Iteration   3: 3.240 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.199 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (3.151, 3.199, 3.240), stdev = 0.045
  CI (99.9%): [2.376, 4.022] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.879 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.005 ms/op
Iteration   1: 3.306 ±(99.9%) 0.006 ms/op
Iteration   2: 3.336 ±(99.9%) 0.012 ms/op
Iteration   3: 3.300 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.314 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (3.300, 3.314, 3.336), stdev = 0.019
  CI (99.9%): [2.965, 3.663] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.762 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.010 ms/op
Iteration   1: 3.895 ±(99.9%) 0.010 ms/op
Iteration   2: 3.960 ±(99.9%) 0.006 ms/op
Iteration   3: 4.126 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.994 ±(99.9%) 2.177 ms/op [Average]
  (min, avg, max) = (3.895, 3.994, 4.126), stdev = 0.119
  CI (99.9%): [1.817, 6.171] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.610 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
Iteration   1: 3.465 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  19.220 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  21.548 ms/op
                 createUser·p0.9999: 27.377 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   3: 3.483 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.464 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  19.334 ms/op
                 createUser·p0.9999: 24.471 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279578
  mean =      3.434 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11882 
    [ 2.500,  5.000) = 260859 
    [ 5.000,  7.500) = 5920 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     19.281 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     27.644 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.418 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  9.601 ms/op
                 existUser·p0.9999: 21.962 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.610 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  9.695 ms/op
                 existUser·p0.9999: 23.435 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   3: 3.379 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.343 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  16.778 ms/op
                 existUser·p0.9999: 24.611 ms/op
                 existUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293456
  mean =      3.270 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14116 
    [ 2.500,  5.000) = 274011 
    [ 5.000,  7.500) = 4639 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 172 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      4.031 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     10.864 ms/op
     p(99.9900) =     23.669 ms/op
     p(99.9990) =     25.111 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 10.015 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
Iteration   1: 3.552 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.763 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  18.607 ms/op
                 getUser·p0.9999: 27.361 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 3.349 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.574 ms/op
                 getUser·p0.999:  19.231 ms/op
                 getUser·p0.9999: 22.166 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   3: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  17.023 ms/op
                 getUser·p0.9999: 26.882 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276968
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8911 
    [ 2.500,  5.000) = 259217 
    [ 5.000,  7.500) = 7755 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     18.154 ms/op
     p(99.9900) =     27.076 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 9.956 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.362 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.012 ms/op
Iteration   1: 4.091 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  17.359 ms/op
                 listUser·p0.9999: 22.392 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 4.108 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 22.139 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 3.984 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  15.921 ms/op
                 listUser·p0.9999: 20.084 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236333
  mean =      4.060 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 227323 
    [ 5.000,  7.500) = 6109 
    [ 7.500, 10.000) = 1921 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.960 ms/op
     p(99.9000) =     16.029 ms/op
     p(99.9900) =     21.794 ms/op
     p(99.9990) =     22.815 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.451 ± 0.281  ops/ms
ClientPb.existUser                       thrpt       3   9.948 ± 3.997  ops/ms
ClientPb.getUser                         thrpt       3   9.206 ± 4.206  ops/ms
ClientPb.listUser                        thrpt       3   8.135 ± 0.988  ops/ms
ClientPb.createUser                       avgt       3   3.283 ± 1.137   ms/op
ClientPb.existUser                        avgt       3   3.199 ± 0.823   ms/op
ClientPb.getUser                          avgt       3   3.314 ± 0.349   ms/op
ClientPb.listUser                         avgt       3   3.994 ± 2.177   ms/op
ClientPb.createUser                     sample  279578   3.434 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.249           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.281           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.313           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.541           ms/op
ClientPb.existUser                      sample  293456   3.270 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.343           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.031           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.864           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.669           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.362           ms/op
ClientPb.getUser                        sample  276968   3.468 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.137           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.154           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.076           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  236333   4.060 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.960           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.029           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.794           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.938           ms/op
