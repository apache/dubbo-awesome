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
# Warmup Iteration   1: 4.266 ops/ms
# Warmup Iteration   2: 11.682 ops/ms
# Warmup Iteration   3: 12.211 ops/ms
Iteration   1: 12.449 ops/ms
Iteration   2: 12.508 ops/ms
Iteration   3: 12.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.473 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (12.449, 12.473, 12.508), stdev = 0.031
  CI (99.9%): [11.912, 13.035] (assumes normal distribution)


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
# Warmup Iteration   1: 8.349 ops/ms
# Warmup Iteration   2: 12.878 ops/ms
# Warmup Iteration   3: 12.889 ops/ms
Iteration   1: 13.067 ops/ms
Iteration   2: 13.079 ops/ms
Iteration   3: 13.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.071 ±(99.9%) 0.128 ops/ms [Average]
  (min, avg, max) = (13.066, 13.071, 13.079), stdev = 0.007
  CI (99.9%): [12.943, 13.198] (assumes normal distribution)


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
# Warmup Iteration   1: 7.543 ops/ms
# Warmup Iteration   2: 12.394 ops/ms
# Warmup Iteration   3: 12.382 ops/ms
Iteration   1: 12.761 ops/ms
Iteration   2: 12.721 ops/ms
Iteration   3: 12.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.662 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (12.505, 12.662, 12.761), stdev = 0.138
  CI (99.9%): [10.149, 15.176] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.911 ops/ms
# Warmup Iteration   2: 10.490 ops/ms
# Warmup Iteration   3: 10.433 ops/ms
Iteration   1: 10.496 ops/ms
Iteration   2: 10.459 ops/ms
Iteration   3: 10.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.477 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (10.459, 10.477, 10.496), stdev = 0.019
  CI (99.9%): [10.137, 10.817] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (2.518, 2.548, 2.580), stdev = 0.031
  CI (99.9%): [1.980, 3.116] (assumes normal distribution)


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
Iteration   2: 2.450 ±(99.9%) 0.003 ms/op
Iteration   3: 2.454 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.466 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (2.450, 2.466, 2.495), stdev = 0.025
  CI (99.9%): [2.008, 2.925] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.003 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.520 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.515, 2.520, 2.525), stdev = 0.005
  CI (99.9%): [2.434, 2.606] (assumes normal distribution)


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
Iteration   3: 3.032 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (3.027, 3.036, 3.048), stdev = 0.011
  CI (99.9%): [2.839, 3.232] (assumes normal distribution)


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
# Warmup Iteration   1: 4.197 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.681 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.549 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.078 ms/op
                 createUser·p0.999:  11.665 ms/op
                 createUser·p0.9999: 14.205 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  9.799 ms/op
                 createUser·p0.9999: 12.567 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.121 ms/op
                 createUser·p0.999:  8.159 ms/op
                 createUser·p0.9999: 9.994 ms/op
                 createUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377310
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 178515 
    [ 2.500,  3.750) = 193117 
    [ 3.750,  5.000) = 4535 
    [ 5.000,  6.250) = 634 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      8.433 ms/op
     p(99.9900) =     13.456 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  8.054 ms/op
                 existUser·p0.9999: 14.077 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  6.224 ms/op
                 existUser·p0.9999: 12.342 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.966 ms/op
                 existUser·p0.999:  10.142 ms/op
                 existUser·p0.9999: 12.666 ms/op
                 existUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385816
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 187924 
    [ 2.500,  3.750) = 194098 
    [ 3.750,  5.000) = 2825 
    [ 5.000,  6.250) = 340 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      9.276 ms/op
     p(99.9900) =     13.720 ms/op
     p(99.9990) =     14.469 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  12.233 ms/op
                 getUser·p0.9999: 14.406 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  9.267 ms/op
                 getUser·p0.9999: 13.655 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   3: 2.573 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.916 ms/op
                 getUser·p0.9999: 10.619 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377007
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 184509 
    [ 2.500,  3.750) = 187022 
    [ 3.750,  5.000) = 4252 
    [ 5.000,  6.250) = 709 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      8.102 ms/op
     p(99.9900) =     14.062 ms/op
     p(99.9990) =     14.782 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 4.720 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.009 ms/op
Iteration   1: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.490 ms/op
                 listUser·p0.9999: 12.264 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   2: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.756 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.626 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   3: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 12.822 ms/op
                 listUser·p1.00:   13.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313317
  mean =      3.062 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 80679 
    [ 2.500,  3.750) = 189960 
    [ 3.750,  5.000) = 34776 
    [ 5.000,  6.250) = 6308 
    [ 6.250,  7.500) = 832 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 300 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     12.288 ms/op
     p(99.9990) =     13.123 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.473 ± 0.562  ops/ms
ClientPb.existUser                       thrpt       3  13.071 ± 0.128  ops/ms
ClientPb.getUser                         thrpt       3  12.662 ± 2.513  ops/ms
ClientPb.listUser                        thrpt       3  10.477 ± 0.340  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.568   ms/op
ClientPb.existUser                        avgt       3   2.466 ± 0.459   ms/op
ClientPb.getUser                          avgt       3   2.520 ± 0.086   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.196   ms/op
ClientPb.createUser                     sample  377310   2.542 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.848           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.433           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.456           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.385           ms/op
ClientPb.existUser                      sample  385816   2.487 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.886           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.276           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.720           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.204           ms/op
ClientPb.getUser                        sample  377007   2.544 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.834           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.102           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.062           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.057           ms/op
ClientPb.listUser                       sample  313317   3.062 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.756           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.288           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.582           ms/op
