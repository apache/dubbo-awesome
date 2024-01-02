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
# Warmup Iteration   1: 4.975 ops/ms
# Warmup Iteration   2: 11.895 ops/ms
# Warmup Iteration   3: 12.306 ops/ms
Iteration   1: 12.463 ops/ms
Iteration   2: 12.416 ops/ms
Iteration   3: 12.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.431 ±(99.9%) 0.501 ops/ms [Average]
  (min, avg, max) = (12.414, 12.431, 12.463), stdev = 0.027
  CI (99.9%): [11.930, 12.932] (assumes normal distribution)


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
# Warmup Iteration   1: 8.419 ops/ms
# Warmup Iteration   2: 13.056 ops/ms
# Warmup Iteration   3: 13.024 ops/ms
Iteration   1: 12.975 ops/ms
Iteration   2: 12.944 ops/ms
Iteration   3: 13.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.973 ±(99.9%) 0.510 ops/ms [Average]
  (min, avg, max) = (12.944, 12.973, 13.000), stdev = 0.028
  CI (99.9%): [12.463, 13.483] (assumes normal distribution)


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
# Warmup Iteration   1: 7.733 ops/ms
# Warmup Iteration   2: 12.665 ops/ms
# Warmup Iteration   3: 12.718 ops/ms
Iteration   1: 12.597 ops/ms
Iteration   2: 12.784 ops/ms
Iteration   3: 12.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.689 ±(99.9%) 1.707 ops/ms [Average]
  (min, avg, max) = (12.597, 12.689, 12.784), stdev = 0.094
  CI (99.9%): [10.982, 14.396] (assumes normal distribution)


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
# Warmup Iteration   1: 6.832 ops/ms
# Warmup Iteration   2: 10.468 ops/ms
# Warmup Iteration   3: 10.458 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.562 ±(99.9%) 0.638 ops/ms [Average]
  (min, avg, max) = (10.536, 10.562, 10.602), stdev = 0.035
  CI (99.9%): [9.925, 11.200] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.004 ms/op
Iteration   1: 2.585 ±(99.9%) 0.004 ms/op
Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
Iteration   3: 2.600 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.584 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.567, 2.584, 2.600), stdev = 0.016
  CI (99.9%): [2.288, 2.879] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.543 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.523 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.509, 2.523, 2.543), stdev = 0.018
  CI (99.9%): [2.199, 2.846] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.588 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
Iteration   3: 2.535 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.554 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (2.535, 2.554, 2.592), stdev = 0.032
  CI (99.9%): [1.964, 3.145] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.897 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
Iteration   3: 3.022 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.001, 3.021, 3.042), stdev = 0.021
  CI (99.9%): [2.647, 3.396] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.417 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.676 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 14.435 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  9.762 ms/op
                 createUser·p0.9999: 13.537 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  8.701 ms/op
                 createUser·p0.9999: 10.395 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375798
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 180355 
    [ 2.500,  3.750) = 191897 
    [ 3.750,  5.000) = 2864 
    [ 5.000,  6.250) = 203 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.916 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.684 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.583 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  9.594 ms/op
                 existUser·p0.9999: 14.451 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  6.557 ms/op
                 existUser·p0.9999: 13.675 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  8.372 ms/op
                 existUser·p0.9999: 12.127 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384199
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 190225 
    [ 2.500,  3.750) = 190036 
    [ 3.750,  5.000) = 3023 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      7.461 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.516 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.558 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  10.912 ms/op
                 getUser·p0.9999: 13.359 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 12.026 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.030 ms/op
                 getUser·p0.999:  7.435 ms/op
                 getUser·p0.9999: 10.256 ms/op
                 getUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377816
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 184120 
    [ 2.500,  3.750) = 189215 
    [ 3.750,  5.000) = 3486 
    [ 5.000,  6.250) = 534 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     12.812 ms/op
     p(99.9990) =     13.712 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.010 ms/op
Iteration   1: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.080 ms/op
                 listUser·p0.9999: 11.347 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.521 ms/op
                 listUser·p0.9999: 10.850 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  10.314 ms/op
                 listUser·p0.9999: 11.868 ms/op
                 listUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312010
  mean =      3.074 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 81561 
    [ 2.500,  3.750) = 186568 
    [ 3.750,  5.000) = 35807 
    [ 5.000,  6.250) = 6404 
    [ 6.250,  7.500) = 794 
    [ 7.500,  8.750) = 285 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 178 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.449 ms/op
     p(99.9990) =     12.266 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.431 ± 0.501  ops/ms
ClientPb.existUser                       thrpt       3  12.973 ± 0.510  ops/ms
ClientPb.getUser                         thrpt       3  12.689 ± 1.707  ops/ms
ClientPb.listUser                        thrpt       3  10.562 ± 0.638  ops/ms
ClientPb.createUser                       avgt       3   2.584 ± 0.295   ms/op
ClientPb.existUser                        avgt       3   2.523 ± 0.323   ms/op
ClientPb.getUser                          avgt       3   2.554 ± 0.591   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.374   ms/op
ClientPb.createUser                     sample  375798   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.714           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.916           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.302           ms/op
ClientPb.existUser                      sample  384199   2.497 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.461           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.615           ms/op
ClientPb.getUser                        sample  377816   2.539 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.686           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.987           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.812           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.959           ms/op
ClientPb.listUser                       sample  312010   3.074 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.449           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.354           ms/op
