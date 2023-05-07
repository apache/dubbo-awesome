# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.600 ops/ms
# Warmup Iteration   2: 6.421 ops/ms
# Warmup Iteration   3: 9.101 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.882 ops/ms
Iteration   3: 9.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.840 ±(99.9%) 1.721 ops/ms [Average]
  (min, avg, max) = (9.733, 9.840, 9.907), stdev = 0.094
  CI (99.9%): [8.120, 11.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.490 ops/ms
# Warmup Iteration   2: 9.609 ops/ms
# Warmup Iteration   3: 10.357 ops/ms
Iteration   1: 10.377 ops/ms
Iteration   2: 10.096 ops/ms
Iteration   3: 10.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.331 ±(99.9%) 3.930 ops/ms [Average]
  (min, avg, max) = (10.096, 10.331, 10.520), stdev = 0.215
  CI (99.9%): [6.401, 14.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ops/ms
# Warmup Iteration   2: 9.331 ops/ms
# Warmup Iteration   3: 10.004 ops/ms
Iteration   1: 10.113 ops/ms
Iteration   2: 10.420 ops/ms
Iteration   3: 10.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.193 ±(99.9%) 3.637 ops/ms [Average]
  (min, avg, max) = (10.047, 10.193, 10.420), stdev = 0.199
  CI (99.9%): [6.556, 13.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.509 ops/ms
# Warmup Iteration   2: 7.773 ops/ms
# Warmup Iteration   3: 8.134 ops/ms
Iteration   1: 8.417 ops/ms
Iteration   2: 8.671 ops/ms
Iteration   3: 8.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.497 ±(99.9%) 2.755 ops/ms [Average]
  (min, avg, max) = (8.403, 8.497, 8.671), stdev = 0.151
  CI (99.9%): [5.742, 11.252] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.256 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.006 ms/op
Iteration   1: 3.176 ±(99.9%) 0.006 ms/op
Iteration   2: 3.355 ±(99.9%) 0.003 ms/op
Iteration   3: 3.127 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.219 ±(99.9%) 2.189 ms/op [Average]
  (min, avg, max) = (3.127, 3.219, 3.355), stdev = 0.120
  CI (99.9%): [1.030, 5.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.006 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.004 ms/op
Iteration   1: 3.097 ±(99.9%) 0.005 ms/op
Iteration   2: 2.998 ±(99.9%) 0.004 ms/op
Iteration   3: 3.136 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.077 ±(99.9%) 1.298 ms/op [Average]
  (min, avg, max) = (2.998, 3.077, 3.136), stdev = 0.071
  CI (99.9%): [1.779, 4.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.777 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.005 ms/op
Iteration   1: 3.384 ±(99.9%) 0.006 ms/op
Iteration   2: 3.136 ±(99.9%) 0.002 ms/op
Iteration   3: 3.136 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.219 ±(99.9%) 2.607 ms/op [Average]
  (min, avg, max) = (3.136, 3.219, 3.384), stdev = 0.143
  CI (99.9%): [0.612, 5.825] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.659 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.008 ms/op
Iteration   1: 3.776 ±(99.9%) 0.008 ms/op
Iteration   2: 3.701 ±(99.9%) 0.006 ms/op
Iteration   3: 3.734 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.737 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (3.701, 3.737, 3.776), stdev = 0.038
  CI (99.9%): [3.051, 4.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.679 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.009 ms/op
Iteration   1: 3.162 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   4.093 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 19.820 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 22.826 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 17.424 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304718
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17827 
    [ 2.500,  5.000) = 281367 
    [ 5.000,  7.500) = 4739 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     14.124 ms/op
     p(99.9900) =     22.037 ms/op
     p(99.9990) =     23.428 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.717 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.316 ms/op
                 existUser·p0.999:  13.674 ms/op
                 existUser·p0.9999: 19.051 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  9.535 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  13.024 ms/op
                 existUser·p0.9999: 22.829 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313138
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23046 
    [ 2.500,  5.000) = 285822 
    [ 5.000,  7.500) = 3417 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     24.631 ms/op
     p(99.9990) =     26.459 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.961 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.010 ms/op
Iteration   1: 3.208 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  12.927 ms/op
                 getUser·p0.9999: 18.614 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  18.711 ms/op
                 getUser·p0.9999: 20.380 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   3: 3.191 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  9.878 ms/op
                 getUser·p0.9999: 20.414 ms/op
                 getUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300093
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9874 
    [ 2.500,  5.000) = 282906 
    [ 5.000,  7.500) = 6368 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 185 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     20.971 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.712 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.012 ms/op
Iteration   1: 3.728 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 19.590 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 3.798 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  12.255 ms/op
                 listUser·p0.9999: 15.794 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.722 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 14.778 ms/op
                 listUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255857
  mean =      3.749 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 247955 
    [ 5.000,  7.500) = 6240 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     18.757 ms/op
     p(99.9990) =     20.097 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.840 ± 1.721  ops/ms
ClientPb.existUser                       thrpt       3  10.331 ± 3.930  ops/ms
ClientPb.getUser                         thrpt       3  10.193 ± 3.637  ops/ms
ClientPb.listUser                        thrpt       3   8.497 ± 2.755  ops/ms
ClientPb.createUser                       avgt       3   3.219 ± 2.189   ms/op
ClientPb.existUser                        avgt       3   3.077 ± 1.298   ms/op
ClientPb.getUser                          avgt       3   3.219 ± 2.607   ms/op
ClientPb.listUser                         avgt       3   3.737 ± 0.686   ms/op
ClientPb.createUser                     sample  304718   3.150 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.955           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.124           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.037           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.921           ms/op
ClientPb.existUser                      sample  313138   3.066 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.982           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.632           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.631           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  300093   3.197 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.067           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.531           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.251           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.234           ms/op
ClientPb.listUser                       sample  255857   3.749 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.571           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.632           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.757           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.283           ms/op
