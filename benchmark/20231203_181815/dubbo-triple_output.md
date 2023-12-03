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
# Warmup Iteration   1: 5.280 ops/ms
# Warmup Iteration   2: 11.841 ops/ms
# Warmup Iteration   3: 12.177 ops/ms
Iteration   1: 12.341 ops/ms
Iteration   2: 12.366 ops/ms
Iteration   3: 12.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.349 ±(99.9%) 0.269 ops/ms [Average]
  (min, avg, max) = (12.340, 12.349, 12.366), stdev = 0.015
  CI (99.9%): [12.080, 12.618] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.972 ops/ms
# Warmup Iteration   2: 12.834 ops/ms
# Warmup Iteration   3: 12.858 ops/ms
Iteration   1: 13.032 ops/ms
Iteration   2: 13.021 ops/ms
Iteration   3: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.975 ±(99.9%) 1.646 ops/ms [Average]
  (min, avg, max) = (12.871, 12.975, 13.032), stdev = 0.090
  CI (99.9%): [11.329, 14.621] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.530 ops/ms
# Warmup Iteration   2: 12.171 ops/ms
# Warmup Iteration   3: 12.537 ops/ms
Iteration   1: 12.357 ops/ms
Iteration   2: 12.196 ops/ms
Iteration   3: 12.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.370 ±(99.9%) 3.298 ops/ms [Average]
  (min, avg, max) = (12.196, 12.370, 12.557), stdev = 0.181
  CI (99.9%): [9.072, 15.668] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.491 ops/ms
# Warmup Iteration   2: 10.414 ops/ms
# Warmup Iteration   3: 10.578 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.651 ±(99.9%) 0.644 ops/ms [Average]
  (min, avg, max) = (10.612, 10.651, 10.681), stdev = 0.035
  CI (99.9%): [10.006, 11.295] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.051 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.593 ±(99.9%) 0.004 ms/op
Iteration   1: 2.618 ±(99.9%) 0.005 ms/op
Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.577 ±(99.9%) 0.659 ms/op [Average]
  (min, avg, max) = (2.552, 2.577, 2.618), stdev = 0.036
  CI (99.9%): [1.918, 3.236] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.003 ms/op
Iteration   2: 2.477 ±(99.9%) 0.003 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.474 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (2.467, 2.474, 2.478), stdev = 0.006
  CI (99.9%): [2.359, 2.589] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.507 ±(99.9%) 0.003 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.510 ±(99.9%) 0.053 ms/op [Average]
  (min, avg, max) = (2.507, 2.510, 2.513), stdev = 0.003
  CI (99.9%): [2.457, 2.563] (assumes normal distribution)


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.005 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
Iteration   3: 3.000 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (2.993, 2.997, 3.000), stdev = 0.004
  CI (99.9%): [2.930, 3.065] (assumes normal distribution)


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.719 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  11.487 ms/op
                 createUser·p0.9999: 13.976 ms/op
                 createUser·p1.00:   14.533 ms/op

Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  10.538 ms/op
                 createUser·p0.9999: 12.243 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 11.993 ms/op
                 createUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374341
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 176702 
    [ 2.500,  3.750) = 192533 
    [ 3.750,  5.000) = 3983 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 147 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.934 ms/op
     p(99.9900) =     13.170 ms/op
     p(99.9990) =     14.443 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.379 ms/op
                 existUser·p0.999:  5.888 ms/op
                 existUser·p0.9999: 14.261 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  5.589 ms/op
                 existUser·p0.9999: 12.958 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.920 ms/op
                 existUser·p0.999:  7.925 ms/op
                 existUser·p0.9999: 15.843 ms/op
                 existUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386445
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 190860 
    [ 2.500,  3.750) = 192009 
    [ 3.750,  5.000) = 2642 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.230 ms/op
     p(99.9900) =     15.024 ms/op
     p(99.9990) =     16.599 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.007 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  11.803 ms/op
                 getUser·p0.9999: 14.533 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  9.542 ms/op
                 getUser·p0.9999: 14.880 ms/op
                 getUser·p1.00:   16.122 ms/op

Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.504 ms/op
                 getUser·p0.9999: 11.059 ms/op
                 getUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380420
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 186382 
    [ 2.500,  3.750) = 188777 
    [ 3.750,  5.000) = 4046 
    [ 5.000,  6.250) = 715 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     14.514 ms/op
     p(99.9990) =     15.932 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
Iteration   1: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 10.881 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  10.519 ms/op
                 listUser·p0.9999: 12.521 ms/op
                 listUser·p1.00:   14.041 ms/op

Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.516 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314422
  mean =      3.050 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 86782 
    [ 2.500,  3.750) = 185020 
    [ 3.750,  5.000) = 34626 
    [ 5.000,  6.250) = 6399 
    [ 6.250,  7.500) = 809 
    [ 7.500,  8.750) = 218 
    [ 8.750, 10.000) = 212 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     12.028 ms/op
     p(99.9990) =     13.535 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.349 ± 0.269  ops/ms
ClientPb.existUser                       thrpt       3  12.975 ± 1.646  ops/ms
ClientPb.getUser                         thrpt       3  12.370 ± 3.298  ops/ms
ClientPb.listUser                        thrpt       3  10.651 ± 0.644  ops/ms
ClientPb.createUser                       avgt       3   2.577 ± 0.659   ms/op
ClientPb.existUser                        avgt       3   2.474 ± 0.115   ms/op
ClientPb.getUser                          avgt       3   2.510 ± 0.053   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.068   ms/op
ClientPb.createUser                     sample  374341   2.562 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.670           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.934           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.170           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.533           ms/op
ClientPb.existUser                      sample  386445   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.716           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.230           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.024           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.695           ms/op
ClientPb.getUser                        sample  380420   2.521 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.840           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.536           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.514           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.122           ms/op
ClientPb.listUser                       sample  314422   3.050 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.716           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.028           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.041           ms/op
