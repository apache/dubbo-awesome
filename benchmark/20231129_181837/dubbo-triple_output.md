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
# Warmup Iteration   1: 4.404 ops/ms
# Warmup Iteration   2: 11.794 ops/ms
# Warmup Iteration   3: 12.252 ops/ms
Iteration   1: 12.590 ops/ms
Iteration   2: 12.569 ops/ms
Iteration   3: 12.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.605 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (12.569, 12.605, 12.656), stdev = 0.045
  CI (99.9%): [11.777, 13.433] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 8.180 ops/ms
# Warmup Iteration   2: 12.900 ops/ms
# Warmup Iteration   3: 13.072 ops/ms
Iteration   1: 13.005 ops/ms
Iteration   2: 12.870 ops/ms
Iteration   3: 12.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.895 ±(99.9%) 1.824 ops/ms [Average]
  (min, avg, max) = (12.810, 12.895, 13.005), stdev = 0.100
  CI (99.9%): [11.071, 14.719] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.917 ops/ms
# Warmup Iteration   2: 12.576 ops/ms
# Warmup Iteration   3: 12.811 ops/ms
Iteration   1: 12.883 ops/ms
Iteration   2: 12.865 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.856 ±(99.9%) 0.599 ops/ms [Average]
  (min, avg, max) = (12.819, 12.856, 12.883), stdev = 0.033
  CI (99.9%): [12.257, 13.455] (assumes normal distribution)


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
# Warmup Iteration   1: 6.712 ops/ms
# Warmup Iteration   2: 10.464 ops/ms
# Warmup Iteration   3: 10.601 ops/ms
Iteration   1: 10.408 ops/ms
Iteration   2: 10.481 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.523 ±(99.9%) 2.580 ops/ms [Average]
  (min, avg, max) = (10.408, 10.523, 10.681), stdev = 0.141
  CI (99.9%): [7.943, 13.104] (assumes normal distribution)


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.575 ±(99.9%) 0.003 ms/op
Iteration   1: 2.617 ±(99.9%) 0.004 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.580 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.592 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.580, 2.592, 2.617), stdev = 0.021
  CI (99.9%): [2.204, 2.981] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.520 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.501 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (2.471, 2.501, 2.520), stdev = 0.027
  CI (99.9%): [2.013, 2.989] (assumes normal distribution)


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.521, 2.529, 2.538), stdev = 0.009
  CI (99.9%): [2.371, 2.687] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.625 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.004 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
Iteration   3: 2.976 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (2.976, 2.987, 2.998), stdev = 0.011
  CI (99.9%): [2.787, 3.188] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.704 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  11.269 ms/op
                 createUser·p0.9999: 14.176 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 11.951 ms/op
                 createUser·p1.00:   12.255 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  8.265 ms/op
                 createUser·p0.9999: 12.324 ms/op
                 createUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379640
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 182581 
    [ 2.500,  3.750) = 192589 
    [ 3.750,  5.000) = 3494 
    [ 5.000,  6.250) = 469 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.571 ms/op
     p(99.9900) =     13.452 ms/op
     p(99.9990) =     14.867 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  9.393 ms/op
                 existUser·p0.9999: 13.668 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  7.637 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 11.998 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386627
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 194173 
    [ 2.500,  3.750) = 189405 
    [ 3.750,  5.000) = 2216 
    [ 5.000,  6.250) = 285 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      8.395 ms/op
     p(99.9900) =     13.217 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  6.712 ms/op
                 getUser·p0.9999: 14.337 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.318 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 14.342 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  7.821 ms/op
                 getUser·p0.9999: 11.809 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384519
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 190399 
    [ 2.500,  3.750) = 187567 
    [ 3.750,  5.000) = 5037 
    [ 5.000,  6.250) = 935 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.165 ms/op
     p(99.9000) =      8.528 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     15.146 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.009 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 10.881 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   2: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.365 ms/op
                 listUser·p0.9999: 11.076 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.721 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.900 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318943
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 94186 
    [ 2.500,  3.750) = 184964 
    [ 3.750,  5.000) = 32595 
    [ 5.000,  6.250) = 5700 
    [ 6.250,  7.500) = 686 
    [ 7.500,  8.750) = 297 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     10.977 ms/op
     p(99.9990) =     11.381 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.605 ± 0.828  ops/ms
ClientPb.existUser                       thrpt       3  12.895 ± 1.824  ops/ms
ClientPb.getUser                         thrpt       3  12.856 ± 0.599  ops/ms
ClientPb.listUser                        thrpt       3  10.523 ± 2.580  ops/ms
ClientPb.createUser                       avgt       3   2.592 ± 0.389   ms/op
ClientPb.existUser                        avgt       3   2.501 ± 0.488   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.158   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.200   ms/op
ClientPb.createUser                     sample  379640   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.954           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.571           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.452           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.893           ms/op
ClientPb.existUser                      sample  386627   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.904           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.395           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.217           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  384519   2.494 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.670           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.165           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.528           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.172           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.712           ms/op
ClientPb.listUser                       sample  318943   3.007 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.721           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.518           ms/op
