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
# Warmup Iteration   1: 4.771 ops/ms
# Warmup Iteration   2: 12.181 ops/ms
# Warmup Iteration   3: 12.172 ops/ms
Iteration   1: 12.665 ops/ms
Iteration   2: 12.637 ops/ms
Iteration   3: 12.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.661 ±(99.9%) 0.406 ops/ms [Average]
  (min, avg, max) = (12.637, 12.661, 12.681), stdev = 0.022
  CI (99.9%): [12.255, 13.066] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.350 ops/ms
# Warmup Iteration   2: 13.183 ops/ms
# Warmup Iteration   3: 13.254 ops/ms
Iteration   1: 13.334 ops/ms
Iteration   2: 13.284 ops/ms
Iteration   3: 13.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.277 ±(99.9%) 1.102 ops/ms [Average]
  (min, avg, max) = (13.214, 13.277, 13.334), stdev = 0.060
  CI (99.9%): [12.176, 14.379] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.709 ops/ms
# Warmup Iteration   2: 12.581 ops/ms
# Warmup Iteration   3: 12.973 ops/ms
Iteration   1: 13.057 ops/ms
Iteration   2: 12.957 ops/ms
Iteration   3: 12.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.976 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (12.913, 12.976, 13.057), stdev = 0.074
  CI (99.9%): [11.625, 14.327] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.601 ops/ms
# Warmup Iteration   2: 10.746 ops/ms
# Warmup Iteration   3: 10.596 ops/ms
Iteration   1: 10.855 ops/ms
Iteration   2: 10.824 ops/ms
Iteration   3: 10.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.806 ±(99.9%) 1.098 ops/ms [Average]
  (min, avg, max) = (10.739, 10.806, 10.855), stdev = 0.060
  CI (99.9%): [9.707, 11.904] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.003 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.491, 2.516, 2.530), stdev = 0.021
  CI (99.9%): [2.130, 2.902] (assumes normal distribution)


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.003 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.451, 2.460, 2.470), stdev = 0.009
  CI (99.9%): [2.288, 2.633] (assumes normal distribution)


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.556 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.535 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (2.505, 2.535, 2.556), stdev = 0.027
  CI (99.9%): [2.051, 3.020] (assumes normal distribution)


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
Iteration   3: 2.952 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.976 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (2.952, 2.976, 2.994), stdev = 0.021
  CI (99.9%): [2.584, 3.368] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  11.893 ms/op
                 createUser·p0.9999: 13.932 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  10.074 ms/op
                 createUser·p0.9999: 12.376 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  8.716 ms/op
                 createUser·p0.9999: 10.486 ms/op
                 createUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381440
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 182761 
    [ 2.500,  3.750) = 194238 
    [ 3.750,  5.000) = 3557 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     13.463 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  6.380 ms/op
                 existUser·p0.9999: 13.750 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  5.194 ms/op
                 existUser·p0.9999: 13.350 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  8.855 ms/op
                 existUser·p0.9999: 11.112 ms/op
                 existUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389132
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 189957 
    [ 2.500,  3.750) = 195029 
    [ 3.750,  5.000) = 3212 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      6.474 ms/op
     p(99.9900) =     13.436 ms/op
     p(99.9990) =     14.452 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  12.387 ms/op
                 getUser·p0.9999: 15.847 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.953 ms/op
                 getUser·p0.9999: 13.524 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  8.697 ms/op
                 getUser·p0.9999: 11.979 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379986
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 186375 
    [ 2.500,  3.750) = 188028 
    [ 3.750,  5.000) = 4464 
    [ 5.000,  6.250) = 654 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     14.565 ms/op
     p(99.9990) =     16.289 ms/op
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
# Warmup Iteration   1: 5.097 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  8.671 ms/op
                 listUser·p0.9999: 10.469 ms/op
                 listUser·p1.00:   11.026 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.229 ms/op
                 listUser·p1.00:   10.781 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.230 ms/op
                 listUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317592
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 92646 
    [ 2.500,  3.750) = 185441 
    [ 3.750,  5.000) = 31593 
    [ 5.000,  6.250) = 6387 
    [ 6.250,  7.500) = 710 
    [ 7.500,  8.750) = 345 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     10.260 ms/op
     p(99.9990) =     10.972 ms/op
     p(99.9999) =     11.108 ms/op
    p(100.0000) =     11.108 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.661 ± 0.406  ops/ms
ClientPb.existUser                       thrpt       3  13.277 ± 1.102  ops/ms
ClientPb.getUser                         thrpt       3  12.976 ± 1.351  ops/ms
ClientPb.listUser                        thrpt       3  10.806 ± 1.098  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.386   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.173   ms/op
ClientPb.getUser                          avgt       3   2.535 ± 0.485   ms/op
ClientPb.listUser                         avgt       3   2.976 ± 0.392   ms/op
ClientPb.createUser                     sample  381440   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.870           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.463           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.500           ms/op
ClientPb.existUser                      sample  389132   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.741           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.474           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.436           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  379986   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.842           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.765           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.565           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.597           ms/op
ClientPb.listUser                       sample  317592   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.852           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.913           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.260           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.108           ms/op
