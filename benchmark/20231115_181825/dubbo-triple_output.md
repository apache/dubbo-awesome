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
# Warmup Iteration   1: 5.257 ops/ms
# Warmup Iteration   2: 12.193 ops/ms
# Warmup Iteration   3: 12.418 ops/ms
Iteration   1: 12.696 ops/ms
Iteration   2: 12.810 ops/ms
Iteration   3: 12.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.762 ±(99.9%) 1.077 ops/ms [Average]
  (min, avg, max) = (12.696, 12.762, 12.810), stdev = 0.059
  CI (99.9%): [11.684, 13.839] (assumes normal distribution)


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
# Warmup Iteration   1: 8.142 ops/ms
# Warmup Iteration   2: 13.150 ops/ms
# Warmup Iteration   3: 13.094 ops/ms
Iteration   1: 13.256 ops/ms
Iteration   2: 12.972 ops/ms
Iteration   3: 13.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.101 ±(99.9%) 2.629 ops/ms [Average]
  (min, avg, max) = (12.972, 13.101, 13.256), stdev = 0.144
  CI (99.9%): [10.471, 15.730] (assumes normal distribution)


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
# Warmup Iteration   1: 7.640 ops/ms
# Warmup Iteration   2: 12.555 ops/ms
# Warmup Iteration   3: 12.748 ops/ms
Iteration   1: 12.786 ops/ms
Iteration   2: 12.861 ops/ms
Iteration   3: 12.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.820 ±(99.9%) 0.691 ops/ms [Average]
  (min, avg, max) = (12.786, 12.820, 12.861), stdev = 0.038
  CI (99.9%): [12.130, 13.511] (assumes normal distribution)


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
# Warmup Iteration   1: 6.832 ops/ms
# Warmup Iteration   2: 10.607 ops/ms
# Warmup Iteration   3: 10.687 ops/ms
Iteration   1: 10.693 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.639 ±(99.9%) 2.510 ops/ms [Average]
  (min, avg, max) = (10.483, 10.639, 10.742), stdev = 0.138
  CI (99.9%): [8.130, 13.149] (assumes normal distribution)


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.003 ms/op
Iteration   1: 2.550 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.003 ms/op
Iteration   3: 2.516 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.516, 2.529, 2.550), stdev = 0.018
  CI (99.9%): [2.196, 2.861] (assumes normal distribution)


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.003 ms/op
Iteration   2: 2.420 ±(99.9%) 0.003 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.420, 2.434, 2.448), stdev = 0.014
  CI (99.9%): [2.177, 2.691] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.003 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.507 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.498, 2.507, 2.516), stdev = 0.009
  CI (99.9%): [2.341, 2.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.548 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.003 ±(99.9%) 0.005 ms/op
Iteration   2: 2.973 ±(99.9%) 0.004 ms/op
Iteration   3: 3.000 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.973, 2.992, 3.003), stdev = 0.016
  CI (99.9%): [2.693, 3.291] (assumes normal distribution)


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  12.366 ms/op
                 createUser·p0.9999: 13.976 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 14.799 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  8.167 ms/op
                 createUser·p0.9999: 9.982 ms/op
                 createUser·p1.00:   10.519 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381277
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 181669 
    [ 2.500,  3.750) = 195558 
    [ 3.750,  5.000) = 3234 
    [ 5.000,  6.250) = 311 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.679 ms/op
     p(99.9900) =     13.971 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.996 ms/op
                 existUser·p0.9999: 15.172 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  6.070 ms/op
                 existUser·p0.9999: 12.812 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 11.158 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385675
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 187773 
    [ 2.500,  3.750) = 193678 
    [ 3.750,  5.000) = 3349 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      7.454 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     15.403 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  12.160 ms/op
                 getUser·p0.9999: 13.968 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  7.877 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.574 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  7.531 ms/op
                 getUser·p0.9999: 10.627 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385926
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 191150 
    [ 2.500,  3.750) = 189913 
    [ 3.750,  5.000) = 3493 
    [ 5.000,  6.250) = 805 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     13.687 ms/op
     p(99.9990) =     14.390 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 4.856 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.009 ms/op
Iteration   1: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.994 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   2: 3.073 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.174 ms/op
                 listUser·p1.00:   10.322 ms/op

Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.469 ms/op
                 listUser·p0.9999: 12.542 ms/op
                 listUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314078
  mean =      3.054 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 84398 
    [ 2.500,  3.750) = 187994 
    [ 3.750,  5.000) = 33939 
    [ 5.000,  6.250) = 6243 
    [ 6.250,  7.500) = 737 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 288 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.141 ms/op
     p(99.9900) =     11.324 ms/op
     p(99.9990) =     13.234 ms/op
     p(99.9999) =     13.402 ms/op
    p(100.0000) =     13.402 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.762 ± 1.077  ops/ms
ClientPb.existUser                       thrpt       3  13.101 ± 2.629  ops/ms
ClientPb.getUser                         thrpt       3  12.820 ± 0.691  ops/ms
ClientPb.listUser                        thrpt       3  10.639 ± 2.510  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.333   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.257   ms/op
ClientPb.getUser                          avgt       3   2.507 ± 0.166   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.299   ms/op
ClientPb.createUser                     sample  381277   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.902           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.679           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.971           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  385675   2.486 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.951           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.454           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.550           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.434           ms/op
ClientPb.getUser                        sample  385926   2.485 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.574           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.602           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.687           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.451           ms/op
ClientPb.listUser                       sample  314078   3.054 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.850           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.141           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.324           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.402           ms/op
