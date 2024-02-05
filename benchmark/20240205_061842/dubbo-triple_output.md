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
# Warmup Iteration   1: 3.939 ops/ms
# Warmup Iteration   2: 11.474 ops/ms
# Warmup Iteration   3: 11.534 ops/ms
Iteration   1: 12.101 ops/ms
Iteration   2: 12.276 ops/ms
Iteration   3: 12.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.207 ±(99.9%) 1.702 ops/ms [Average]
  (min, avg, max) = (12.101, 12.207, 12.276), stdev = 0.093
  CI (99.9%): [10.505, 13.909] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.801 ops/ms
# Warmup Iteration   2: 13.028 ops/ms
# Warmup Iteration   3: 12.894 ops/ms
Iteration   1: 12.788 ops/ms
Iteration   2: 12.839 ops/ms
Iteration   3: 12.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.776 ±(99.9%) 1.287 ops/ms [Average]
  (min, avg, max) = (12.700, 12.776, 12.839), stdev = 0.071
  CI (99.9%): [11.489, 14.063] (assumes normal distribution)


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
# Warmup Iteration   1: 6.923 ops/ms
# Warmup Iteration   2: 12.050 ops/ms
# Warmup Iteration   3: 12.402 ops/ms
Iteration   1: 12.567 ops/ms
Iteration   2: 12.362 ops/ms
Iteration   3: 12.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.535 ±(99.9%) 2.906 ops/ms [Average]
  (min, avg, max) = (12.362, 12.535, 12.676), stdev = 0.159
  CI (99.9%): [9.630, 15.441] (assumes normal distribution)


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
# Warmup Iteration   1: 6.689 ops/ms
# Warmup Iteration   2: 10.631 ops/ms
# Warmup Iteration   3: 10.610 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.495 ops/ms
Iteration   3: 10.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.475 ±(99.9%) 0.325 ops/ms [Average]
  (min, avg, max) = (10.461, 10.475, 10.495), stdev = 0.018
  CI (99.9%): [10.150, 10.800] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.319 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.003 ms/op
Iteration   1: 2.557 ±(99.9%) 0.004 ms/op
Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
Iteration   3: 2.553 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (2.547, 2.552, 2.557), stdev = 0.005
  CI (99.9%): [2.459, 2.646] (assumes normal distribution)


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.517 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.506, 2.517, 2.531), stdev = 0.013
  CI (99.9%): [2.287, 2.746] (assumes normal distribution)


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.503, 2.513, 2.528), stdev = 0.013
  CI (99.9%): [2.277, 2.748] (assumes normal distribution)


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
# Warmup Iteration   1: 5.055 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.005 ms/op
Iteration   1: 3.102 ±(99.9%) 0.005 ms/op
Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
Iteration   3: 3.082 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.093 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (3.082, 3.093, 3.102), stdev = 0.010
  CI (99.9%): [2.909, 3.277] (assumes normal distribution)


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
# Warmup Iteration   1: 4.805 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 2.773 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.006 ms/op
Iteration   1: 2.562 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  11.161 ms/op
                 createUser·p0.9999: 14.238 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.634 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.699 ms/op
                 createUser·p0.90:   3.199 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  10.050 ms/op
                 createUser·p0.9999: 14.790 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   3: 2.580 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 11.321 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369893
  mean =      2.592 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 175456 
    [ 2.500,  3.750) = 189385 
    [ 3.750,  5.000) = 3969 
    [ 5.000,  6.250) = 584 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     15.283 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 3.777 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  6.975 ms/op
                 existUser·p0.9999: 13.518 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.404 ms/op
                 existUser·p0.999:  8.751 ms/op
                 existUser·p0.9999: 12.636 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  6.051 ms/op
                 existUser·p0.9999: 11.815 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388008
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 191075 
    [ 2.500,  3.750) = 194010 
    [ 3.750,  5.000) = 2211 
    [ 5.000,  6.250) = 249 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      6.668 ms/op
     p(99.9900) =     13.078 ms/op
     p(99.9990) =     15.048 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.698 ms/op
                 getUser·p0.999:  11.506 ms/op
                 getUser·p0.9999: 13.522 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 2.554 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.762 ms/op
                 getUser·p0.9999: 15.860 ms/op
                 getUser·p1.00:   16.728 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  8.359 ms/op
                 getUser·p0.9999: 10.345 ms/op
                 getUser·p1.00:   10.699 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377605
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 183995 
    [ 2.500,  3.750) = 188348 
    [ 3.750,  5.000) = 3813 
    [ 5.000,  6.250) = 864 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      8.559 ms/op
     p(99.9900) =     14.491 ms/op
     p(99.9990) =     16.553 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.009 ms/op
Iteration   1: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.653 ms/op
                 listUser·p0.9999: 11.043 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   2: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.722 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.621 ms/op
                 listUser·p0.999:  9.554 ms/op
                 listUser·p0.9999: 12.059 ms/op
                 listUser·p1.00:   15.254 ms/op

Iteration   3: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.494 ms/op
                 listUser·p0.9999: 11.936 ms/op
                 listUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313750
  mean =      3.057 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 83673 
    [ 2.500,  3.750) = 188347 
    [ 3.750,  5.000) = 34206 
    [ 5.000,  6.250) = 6124 
    [ 6.250,  7.500) = 662 
    [ 7.500,  8.750) = 191 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.911 ms/op
     p(99.9990) =     12.646 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.207 ± 1.702  ops/ms
ClientPb.existUser                       thrpt       3  12.776 ± 1.287  ops/ms
ClientPb.getUser                         thrpt       3  12.535 ± 2.906  ops/ms
ClientPb.listUser                        thrpt       3  10.475 ± 0.325  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.094   ms/op
ClientPb.existUser                        avgt       3   2.517 ± 0.229   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.235   ms/op
ClientPb.listUser                         avgt       3   3.093 ± 0.184   ms/op
ClientPb.createUser                     sample  369893   2.592 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.952           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.683           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.254           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.596           ms/op
ClientPb.existUser                      sample  388008   2.472 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.668           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.078           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.221           ms/op
ClientPb.getUser                        sample  377605   2.540 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.982           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.559           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.491           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.728           ms/op
ClientPb.listUser                       sample  313750   3.057 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.722           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.911           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.254           ms/op
