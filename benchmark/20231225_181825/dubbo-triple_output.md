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
# Warmup Iteration   1: 4.994 ops/ms
# Warmup Iteration   2: 11.731 ops/ms
# Warmup Iteration   3: 12.094 ops/ms
Iteration   1: 12.317 ops/ms
Iteration   2: 12.520 ops/ms
Iteration   3: 12.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.463 ±(99.9%) 2.330 ops/ms [Average]
  (min, avg, max) = (12.317, 12.463, 12.553), stdev = 0.128
  CI (99.9%): [10.133, 14.793] (assumes normal distribution)


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
# Warmup Iteration   1: 8.458 ops/ms
# Warmup Iteration   2: 13.019 ops/ms
# Warmup Iteration   3: 13.002 ops/ms
Iteration   1: 13.030 ops/ms
Iteration   2: 12.919 ops/ms
Iteration   3: 13.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.027 ±(99.9%) 1.952 ops/ms [Average]
  (min, avg, max) = (12.919, 13.027, 13.133), stdev = 0.107
  CI (99.9%): [11.075, 14.979] (assumes normal distribution)


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
# Warmup Iteration   1: 7.845 ops/ms
# Warmup Iteration   2: 12.377 ops/ms
# Warmup Iteration   3: 12.828 ops/ms
Iteration   1: 12.887 ops/ms
Iteration   2: 12.947 ops/ms
Iteration   3: 12.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.891 ±(99.9%) 0.982 ops/ms [Average]
  (min, avg, max) = (12.840, 12.891, 12.947), stdev = 0.054
  CI (99.9%): [11.910, 13.873] (assumes normal distribution)


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
# Warmup Iteration   1: 6.394 ops/ms
# Warmup Iteration   2: 10.298 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.474 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.514 ±(99.9%) 0.724 ops/ms [Average]
  (min, avg, max) = (10.474, 10.514, 10.553), stdev = 0.040
  CI (99.9%): [9.790, 11.238] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.004 ms/op
Iteration   1: 2.575 ±(99.9%) 0.004 ms/op
Iteration   2: 2.586 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.569 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.547, 2.569, 2.586), stdev = 0.020
  CI (99.9%): [2.197, 2.941] (assumes normal distribution)


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.432 ±(99.9%) 0.003 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.432, 2.443, 2.457), stdev = 0.013
  CI (99.9%): [2.215, 2.672] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.515 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.489, 2.503, 2.515), stdev = 0.013
  CI (99.9%): [2.260, 2.746] (assumes normal distribution)


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
# Warmup Iteration   1: 4.650 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.005 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
Iteration   3: 2.998 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.012 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.998, 3.012, 3.036), stdev = 0.021
  CI (99.9%): [2.627, 3.397] (assumes normal distribution)


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.719 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.575 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.531 ms/op
                 createUser·p0.999:  11.062 ms/op
                 createUser·p0.9999: 16.591 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 12.303 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 11.566 ms/op
                 createUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377646
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 180526 
    [ 2.500,  3.750) = 193443 
    [ 3.750,  5.000) = 2877 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     13.982 ms/op
     p(99.9990) =     17.112 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 3.667 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  5.796 ms/op
                 existUser·p0.9999: 13.598 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  6.717 ms/op
                 existUser·p0.9999: 12.549 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  7.635 ms/op
                 existUser·p0.9999: 11.992 ms/op
                 existUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391720
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 193930 
    [ 2.500,  3.750) = 195129 
    [ 3.750,  5.000) = 2043 
    [ 5.000,  6.250) = 165 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =      6.986 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     13.880 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.458 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  9.519 ms/op
                 getUser·p0.9999: 13.571 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.865 ms/op
                 getUser·p0.9999: 12.370 ms/op
                 getUser·p1.00:   12.517 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  9.094 ms/op
                 getUser·p0.9999: 11.933 ms/op
                 getUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381240
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 185419 
    [ 2.500,  3.750) = 189869 
    [ 3.750,  5.000) = 4309 
    [ 5.000,  6.250) = 1002 
    [ 6.250,  7.500) = 173 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 138 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      7.903 ms/op
     p(99.9900) =     13.072 ms/op
     p(99.9990) =     13.991 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.871 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.009 ms/op
Iteration   1: 3.098 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 12.179 ms/op
                 listUser·p1.00:   14.369 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.238 ms/op
                 listUser·p0.9999: 10.428 ms/op
                 listUser·p1.00:   11.108 ms/op

Iteration   3: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.905 ms/op
                 listUser·p0.9999: 11.782 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312737
  mean =      3.067 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 81246 
    [ 2.500,  3.750) = 188170 
    [ 3.750,  5.000) = 35693 
    [ 5.000,  6.250) = 6119 
    [ 6.250,  7.500) = 754 
    [ 7.500,  8.750) = 269 
    [ 8.750, 10.000) = 249 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.633 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.734 ms/op
     p(99.9990) =     13.605 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.463 ± 2.330  ops/ms
ClientPb.existUser                       thrpt       3  13.027 ± 1.952  ops/ms
ClientPb.getUser                         thrpt       3  12.891 ± 0.982  ops/ms
ClientPb.listUser                        thrpt       3  10.514 ± 0.724  ops/ms
ClientPb.createUser                       avgt       3   2.569 ± 0.372   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.229   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.243   ms/op
ClientPb.listUser                         avgt       3   3.012 ± 0.385   ms/op
ClientPb.createUser                     sample  377646   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.766           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.535           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.982           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.203           ms/op
ClientPb.existUser                      sample  391720   2.448 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.795           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.986           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.074           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.976           ms/op
ClientPb.getUser                        sample  381240   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.458           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.903           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.072           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  312737   3.067 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.927           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.633           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.734           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.369           ms/op
