# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.519 ops/ms
# Warmup Iteration   2: 5.651 ops/ms
# Warmup Iteration   3: 9.143 ops/ms
Iteration   1: 10.006 ops/ms
Iteration   2: 9.428 ops/ms
Iteration   3: 10.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.880 ±(99.9%) 7.356 ops/ms [Average]
  (min, avg, max) = (9.428, 9.880, 10.205), stdev = 0.403
  CI (99.9%): [2.524, 17.236] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ops/ms
# Warmup Iteration   2: 9.231 ops/ms
# Warmup Iteration   3: 10.290 ops/ms
Iteration   1: 10.191 ops/ms
Iteration   2: 10.356 ops/ms
Iteration   3: 10.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.336 ±(99.9%) 2.472 ops/ms [Average]
  (min, avg, max) = (10.191, 10.336, 10.460), stdev = 0.135
  CI (99.9%): [7.864, 12.807] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.872 ops/ms
# Warmup Iteration   2: 8.404 ops/ms
# Warmup Iteration   3: 9.650 ops/ms
Iteration   1: 9.949 ops/ms
Iteration   2: 9.989 ops/ms
Iteration   3: 10.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.983 ±(99.9%) 0.579 ops/ms [Average]
  (min, avg, max) = (9.949, 9.983, 10.012), stdev = 0.032
  CI (99.9%): [9.404, 10.563] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.227 ops/ms
# Warmup Iteration   2: 7.665 ops/ms
# Warmup Iteration   3: 8.452 ops/ms
Iteration   1: 8.461 ops/ms
Iteration   2: 8.576 ops/ms
Iteration   3: 8.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.588 ±(99.9%) 2.423 ops/ms [Average]
  (min, avg, max) = (8.461, 8.588, 8.726), stdev = 0.133
  CI (99.9%): [6.165, 11.010] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.056 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.003 ms/op
Iteration   1: 3.263 ±(99.9%) 0.009 ms/op
Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
Iteration   3: 3.065 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.187 ±(99.9%) 1.951 ms/op [Average]
  (min, avg, max) = (3.065, 3.187, 3.263), stdev = 0.107
  CI (99.9%): [1.236, 5.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.663 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.004 ms/op
Iteration   1: 3.255 ±(99.9%) 0.006 ms/op
Iteration   2: 3.131 ±(99.9%) 0.003 ms/op
Iteration   3: 2.980 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.122 ±(99.9%) 2.514 ms/op [Average]
  (min, avg, max) = (2.980, 3.122, 3.255), stdev = 0.138
  CI (99.9%): [0.608, 5.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.300 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.004 ms/op
Iteration   1: 3.136 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.001 ms/op
Iteration   3: 3.137 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.117 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (3.077, 3.117, 3.137), stdev = 0.034
  CI (99.9%): [2.487, 3.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.117 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.005 ms/op
Iteration   1: 3.716 ±(99.9%) 0.007 ms/op
Iteration   2: 3.729 ±(99.9%) 0.005 ms/op
Iteration   3: 3.681 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.708 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (3.681, 3.708, 3.729), stdev = 0.025
  CI (99.9%): [3.253, 4.164] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.272 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.860 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
Iteration   1: 3.308 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  15.131 ms/op
                 createUser·p0.9999: 22.075 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  19.539 ms/op
                 createUser·p0.9999: 21.952 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  14.931 ms/op
                 createUser·p0.9999: 18.481 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296926
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25371 
    [ 2.500,  5.000) = 265669 
    [ 5.000,  7.500) = 4923 
    [ 7.500, 10.000) = 459 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     15.517 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.820 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.794 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
Iteration   1: 3.006 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.133 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  8.618 ms/op
                 existUser·p0.9999: 20.503 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  11.752 ms/op
                 existUser·p0.9999: 20.930 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 19.185 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314201
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18051 
    [ 2.500,  5.000) = 291443 
    [ 5.000,  7.500) = 4030 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     10.994 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.293 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.010 ms/op
Iteration   1: 3.176 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.577 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  12.227 ms/op
                 getUser·p0.9999: 19.792 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 23.298 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   3: 3.188 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  11.289 ms/op
                 getUser·p0.9999: 28.803 ms/op
                 getUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301836
  mean =      3.179 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16387 
    [ 2.500,  5.000) = 278604 
    [ 5.000,  7.500) = 5853 
    [ 7.500, 10.000) = 629 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     26.694 ms/op
     p(99.9990) =     30.170 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.764 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.012 ms/op
Iteration   1: 3.751 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  15.886 ms/op
                 listUser·p0.9999: 19.361 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 3.690 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.167 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.172 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 3.633 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.133 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259969
  mean =      3.691 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 252281 
    [ 5.000,  7.500) = 5692 
    [ 7.500, 10.000) = 1215 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     22.047 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.880 ± 7.356  ops/ms
ClientPb.existUser                       thrpt       3  10.336 ± 2.472  ops/ms
ClientPb.getUser                         thrpt       3   9.983 ± 0.579  ops/ms
ClientPb.listUser                        thrpt       3   8.588 ± 2.423  ops/ms
ClientPb.createUser                       avgt       3   3.187 ± 1.951   ms/op
ClientPb.existUser                        avgt       3   3.122 ± 2.514   ms/op
ClientPb.getUser                          avgt       3   3.117 ± 0.629   ms/op
ClientPb.listUser                         avgt       3   3.708 ± 0.456   ms/op
ClientPb.createUser                     sample  296926   3.231 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.551           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.517           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.791           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.298           ms/op
ClientPb.existUser                      sample  314201   3.053 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.934           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.994           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.480           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.692           ms/op
ClientPb.getUser                        sample  301836   3.179 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.307           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.289           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.694           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.376           ms/op
ClientPb.listUser                       sample  259969   3.691 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.514           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.610           ms/op
