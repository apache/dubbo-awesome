# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.574 ops/ms
# Warmup Iteration   2: 6.632 ops/ms
# Warmup Iteration   3: 9.213 ops/ms
Iteration   1: 9.715 ops/ms
Iteration   2: 9.976 ops/ms
Iteration   3: 10.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.926 ±(99.9%) 3.490 ops/ms [Average]
  (min, avg, max) = (9.715, 9.926, 10.088), stdev = 0.191
  CI (99.9%): [6.436, 13.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ops/ms
# Warmup Iteration   2: 9.868 ops/ms
# Warmup Iteration   3: 10.140 ops/ms
Iteration   1: 10.253 ops/ms
Iteration   2: 10.049 ops/ms
Iteration   3: 10.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.145 ±(99.9%) 1.864 ops/ms [Average]
  (min, avg, max) = (10.049, 10.145, 10.253), stdev = 0.102
  CI (99.9%): [8.282, 12.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ops/ms
# Warmup Iteration   2: 9.523 ops/ms
# Warmup Iteration   3: 9.779 ops/ms
Iteration   1: 10.429 ops/ms
Iteration   2: 10.478 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.397 ±(99.9%) 1.839 ops/ms [Average]
  (min, avg, max) = (10.284, 10.397, 10.478), stdev = 0.101
  CI (99.9%): [8.558, 12.236] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.306 ops/ms
# Warmup Iteration   2: 7.581 ops/ms
# Warmup Iteration   3: 8.569 ops/ms
Iteration   1: 8.547 ops/ms
Iteration   2: 8.496 ops/ms
Iteration   3: 8.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.460 ±(99.9%) 2.006 ops/ms [Average]
  (min, avg, max) = (8.336, 8.460, 8.547), stdev = 0.110
  CI (99.9%): [6.454, 10.466] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.288 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.005 ms/op
Iteration   1: 3.166 ±(99.9%) 0.005 ms/op
Iteration   2: 3.117 ±(99.9%) 0.010 ms/op
Iteration   3: 3.112 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.132 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.112, 3.132, 3.166), stdev = 0.030
  CI (99.9%): [2.586, 3.678] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.521 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.004 ms/op
Iteration   1: 2.958 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.989 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (2.958, 2.989, 3.014), stdev = 0.028
  CI (99.9%): [2.477, 3.501] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.387 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.285 ±(99.9%) 0.006 ms/op
Iteration   2: 3.283 ±(99.9%) 0.005 ms/op
Iteration   3: 3.092 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.220 ±(99.9%) 2.026 ms/op [Average]
  (min, avg, max) = (3.092, 3.220, 3.285), stdev = 0.111
  CI (99.9%): [1.193, 5.246] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.129 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.008 ms/op
Iteration   1: 3.696 ±(99.9%) 0.007 ms/op
Iteration   2: 3.641 ±(99.9%) 0.010 ms/op
Iteration   3: 3.644 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.660 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.641, 3.660, 3.696), stdev = 0.031
  CI (99.9%): [3.090, 4.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.422 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
Iteration   1: 3.114 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  17.408 ms/op
                 createUser·p0.9999: 19.595 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   2: 3.139 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  16.318 ms/op
                 createUser·p0.9999: 20.357 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  12.697 ms/op
                 createUser·p0.9999: 19.753 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306651
  mean =      3.130 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14443 
    [ 2.500,  5.000) = 286912 
    [ 5.000,  7.500) = 4420 
    [ 7.500, 10.000) = 368 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 237 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     20.797 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.777 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.009 ms/op
Iteration   1: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.976 ms/op
                 existUser·p0.9999: 20.483 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  10.027 ms/op
                 existUser·p0.9999: 28.944 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 22.151 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314405
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13639 
    [ 2.500,  5.000) = 295380 
    [ 5.000,  7.500) = 4813 
    [ 7.500, 10.000) = 267 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     29.964 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.888 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.009 ms/op
Iteration   1: 3.136 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   6.049 ms/op
                 getUser·p0.999:  15.550 ms/op
                 getUser·p0.9999: 23.915 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 3.240 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  9.670 ms/op
                 getUser·p0.9999: 22.647 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  10.182 ms/op
                 getUser·p0.9999: 19.754 ms/op
                 getUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302214
  mean =      3.174 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18651 
    [ 2.500,  5.000) = 276153 
    [ 5.000,  7.500) = 6609 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     23.040 ms/op
     p(99.9990) =     24.703 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.784 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.011 ms/op
Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 21.365 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 3.702 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 19.202 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 3.677 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.116 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.190 ms/op
                 listUser·p0.9999: 13.199 ms/op
                 listUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257402
  mean =      3.724 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 249681 
    [ 5.000,  7.500) = 5797 
    [ 7.500, 10.000) = 1249 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.798 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     19.669 ms/op
     p(99.9990) =     22.600 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.926 ± 3.490  ops/ms
ClientPb.existUser                       thrpt       3  10.145 ± 1.864  ops/ms
ClientPb.getUser                         thrpt       3  10.397 ± 1.839  ops/ms
ClientPb.listUser                        thrpt       3   8.460 ± 2.006  ops/ms
ClientPb.createUser                       avgt       3   3.132 ± 0.546   ms/op
ClientPb.existUser                        avgt       3   2.989 ± 0.512   ms/op
ClientPb.getUser                          avgt       3   3.220 ± 2.026   ms/op
ClientPb.listUser                         avgt       3   3.660 ± 0.571   ms/op
ClientPb.createUser                     sample  306651   3.130 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.294           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.857           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.840           ms/op
ClientPb.existUser                      sample  314405   3.051 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.863           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.978           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.329           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.015           ms/op
ClientPb.getUser                        sample  302214   3.174 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.065           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.942           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.040           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.002           ms/op
ClientPb.listUser                       sample  257402   3.724 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.669           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.708           ms/op
