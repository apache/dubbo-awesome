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
# Warmup Iteration   1: 4.936 ops/ms
# Warmup Iteration   2: 12.028 ops/ms
# Warmup Iteration   3: 12.216 ops/ms
Iteration   1: 12.541 ops/ms
Iteration   2: 12.548 ops/ms
Iteration   3: 12.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.551 ±(99.9%) 0.205 ops/ms [Average]
  (min, avg, max) = (12.541, 12.551, 12.563), stdev = 0.011
  CI (99.9%): [12.346, 12.756] (assumes normal distribution)


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
# Warmup Iteration   1: 8.236 ops/ms
# Warmup Iteration   2: 12.907 ops/ms
# Warmup Iteration   3: 12.712 ops/ms
Iteration   1: 12.653 ops/ms
Iteration   2: 12.766 ops/ms
Iteration   3: 12.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.734 ±(99.9%) 1.291 ops/ms [Average]
  (min, avg, max) = (12.653, 12.734, 12.784), stdev = 0.071
  CI (99.9%): [11.444, 14.025] (assumes normal distribution)


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
# Warmup Iteration   1: 7.202 ops/ms
# Warmup Iteration   2: 12.146 ops/ms
# Warmup Iteration   3: 12.434 ops/ms
Iteration   1: 12.491 ops/ms
Iteration   2: 12.495 ops/ms
Iteration   3: 12.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.528 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (12.491, 12.528, 12.598), stdev = 0.061
  CI (99.9%): [11.422, 13.634] (assumes normal distribution)


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
# Warmup Iteration   1: 6.416 ops/ms
# Warmup Iteration   2: 10.298 ops/ms
# Warmup Iteration   3: 10.503 ops/ms
Iteration   1: 10.439 ops/ms
Iteration   2: 10.535 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.487 ±(99.9%) 0.870 ops/ms [Average]
  (min, avg, max) = (10.439, 10.487, 10.535), stdev = 0.048
  CI (99.9%): [9.617, 11.358] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.575 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.537, 2.545, 2.559), stdev = 0.012
  CI (99.9%): [2.319, 2.770] (assumes normal distribution)


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.433 ±(99.9%) 0.003 ms/op
Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.433, 2.451, 2.463), stdev = 0.016
  CI (99.9%): [2.165, 2.738] (assumes normal distribution)


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.537 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.527, 2.537, 2.553), stdev = 0.014
  CI (99.9%): [2.290, 2.784] (assumes normal distribution)


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.005 ms/op
Iteration   1: 3.033 ±(99.9%) 0.005 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.047 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (3.026, 3.036, 3.047), stdev = 0.011
  CI (99.9%): [2.838, 3.233] (assumes normal distribution)


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
# Warmup Iteration   1: 4.197 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.692 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.986 ms/op
                 createUser·p0.9999: 15.520 ms/op
                 createUser·p1.00:   16.531 ms/op

Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  10.074 ms/op
                 createUser·p0.9999: 14.200 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   3: 2.577 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  8.569 ms/op
                 createUser·p0.9999: 11.010 ms/op
                 createUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373703
  mean =      2.565 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 176509 
    [ 2.500,  3.750) = 192463 
    [ 3.750,  5.000) = 3917 
    [ 5.000,  6.250) = 269 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      8.677 ms/op
     p(99.9900) =     15.061 ms/op
     p(99.9990) =     16.165 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  11.634 ms/op
                 existUser·p0.9999: 19.733 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  5.127 ms/op
                 existUser·p0.9999: 12.507 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  6.372 ms/op
                 existUser·p0.9999: 11.257 ms/op
                 existUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387135
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 187401 
    [ 2.500,  5.000) = 198865 
    [ 5.000,  7.500) = 549 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      6.169 ms/op
     p(99.9900) =     14.444 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  5.224 ms/op
                 getUser·p0.9999: 14.569 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  9.130 ms/op
                 getUser·p0.9999: 14.142 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  8.756 ms/op
                 getUser·p0.9999: 11.638 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381356
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 187622 
    [ 2.500,  3.750) = 189794 
    [ 3.750,  5.000) = 3072 
    [ 5.000,  6.250) = 447 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      6.160 ms/op
     p(99.9900) =     13.891 ms/op
     p(99.9990) =     15.027 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 4.903 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.009 ms/op
Iteration   1: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.864 ms/op
                 listUser·p0.9999: 9.863 ms/op
                 listUser·p1.00:   10.666 ms/op

Iteration   2: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  10.237 ms/op
                 listUser·p0.9999: 12.997 ms/op
                 listUser·p1.00:   13.468 ms/op

Iteration   3: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.061 ms/op
                 listUser·p0.9999: 11.559 ms/op
                 listUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313405
  mean =      3.060 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 81760 
    [ 2.500,  3.750) = 189478 
    [ 3.750,  5.000) = 34964 
    [ 5.000,  6.250) = 5911 
    [ 6.250,  7.500) = 568 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 283 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     12.282 ms/op
     p(99.9990) =     14.594 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.551 ± 0.205  ops/ms
ClientPb.existUser                       thrpt       3  12.734 ± 1.291  ops/ms
ClientPb.getUser                         thrpt       3  12.528 ± 1.106  ops/ms
ClientPb.listUser                        thrpt       3  10.487 ± 0.870  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.225   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.286   ms/op
ClientPb.getUser                          avgt       3   2.537 ± 0.247   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.198   ms/op
ClientPb.createUser                     sample  373703   2.565 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.061           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.531           ms/op
ClientPb.existUser                      sample  387135   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.944           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.169           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.444           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.546           ms/op
ClientPb.getUser                        sample  381356   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.988           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.160           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.891           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.172           ms/op
ClientPb.listUser                       sample  313405   3.060 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.939           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.282           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.368           ms/op
