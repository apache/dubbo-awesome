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
# Warmup Iteration   1: 5.072 ops/ms
# Warmup Iteration   2: 12.041 ops/ms
# Warmup Iteration   3: 12.139 ops/ms
Iteration   1: 12.158 ops/ms
Iteration   2: 12.235 ops/ms
Iteration   3: 12.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.273 ±(99.9%) 2.509 ops/ms [Average]
  (min, avg, max) = (12.158, 12.273, 12.425), stdev = 0.138
  CI (99.9%): [9.764, 14.781] (assumes normal distribution)


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
# Warmup Iteration   1: 7.920 ops/ms
# Warmup Iteration   2: 12.608 ops/ms
# Warmup Iteration   3: 12.646 ops/ms
Iteration   1: 12.885 ops/ms
Iteration   2: 12.660 ops/ms
Iteration   3: 12.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.755 ±(99.9%) 2.132 ops/ms [Average]
  (min, avg, max) = (12.660, 12.755, 12.885), stdev = 0.117
  CI (99.9%): [10.623, 14.887] (assumes normal distribution)


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
# Warmup Iteration   1: 7.459 ops/ms
# Warmup Iteration   2: 12.247 ops/ms
# Warmup Iteration   3: 12.434 ops/ms
Iteration   1: 12.457 ops/ms
Iteration   2: 12.590 ops/ms
Iteration   3: 12.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.484 ±(99.9%) 1.733 ops/ms [Average]
  (min, avg, max) = (12.406, 12.484, 12.590), stdev = 0.095
  CI (99.9%): [10.752, 14.217] (assumes normal distribution)


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
# Warmup Iteration   1: 6.569 ops/ms
# Warmup Iteration   2: 10.267 ops/ms
# Warmup Iteration   3: 10.230 ops/ms
Iteration   1: 10.556 ops/ms
Iteration   2: 10.462 ops/ms
Iteration   3: 10.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.488 ±(99.9%) 1.078 ops/ms [Average]
  (min, avg, max) = (10.447, 10.488, 10.556), stdev = 0.059
  CI (99.9%): [9.410, 11.566] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.080 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.003 ms/op
Iteration   1: 2.590 ±(99.9%) 0.004 ms/op
Iteration   2: 2.613 ±(99.9%) 0.003 ms/op
Iteration   3: 2.581 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.594 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (2.581, 2.594, 2.613), stdev = 0.017
  CI (99.9%): [2.292, 2.897] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.003 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.501 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.489, 2.501, 2.508), stdev = 0.011
  CI (99.9%): [2.307, 2.695] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.523 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (2.504, 2.523, 2.540), stdev = 0.018
  CI (99.9%): [2.193, 2.853] (assumes normal distribution)


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
# Warmup Iteration   1: 4.814 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.004 ms/op
Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
Iteration   3: 3.064 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.011, 3.035, 3.064), stdev = 0.027
  CI (99.9%): [2.548, 3.523] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.670 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.618 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   4.096 ms/op
                 createUser·p0.999:  11.928 ms/op
                 createUser·p0.9999: 14.748 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   2: 2.613 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  9.364 ms/op
                 createUser·p0.9999: 12.284 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.658 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.720 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.408 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  6.911 ms/op
                 createUser·p0.9999: 12.090 ms/op
                 createUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 364660
  mean =      2.630 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 168963 
    [ 2.500,  3.750) = 188225 
    [ 3.750,  5.000) = 5782 
    [ 5.000,  6.250) = 1082 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.675 ms/op
     p(90.0000) =      3.195 ms/op
     p(95.0000) =      3.346 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      9.508 ms/op
     p(99.9900) =     13.606 ms/op
     p(99.9990) =     15.271 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  11.802 ms/op
                 existUser·p0.9999: 14.323 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  6.152 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 12.308 ms/op
                 existUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385706
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 188540 
    [ 2.500,  3.750) = 193531 
    [ 3.750,  5.000) = 2720 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     14.434 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.549 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  11.577 ms/op
                 getUser·p0.9999: 15.155 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  10.124 ms/op
                 getUser·p0.9999: 13.018 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 10.505 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376641
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 182354 
    [ 2.500,  3.750) = 188463 
    [ 3.750,  5.000) = 4263 
    [ 5.000,  6.250) = 980 
    [ 6.250,  7.500) = 129 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      8.493 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     15.297 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 4.972 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.009 ms/op
Iteration   1: 3.087 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 10.873 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   2: 3.091 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 10.999 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   3: 3.078 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.662 ms/op
                 listUser·p0.999:  9.947 ms/op
                 listUser·p0.9999: 12.206 ms/op
                 listUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310876
  mean =      3.085 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 79303 
    [ 2.500,  3.750) = 187679 
    [ 3.750,  5.000) = 35184 
    [ 5.000,  6.250) = 6986 
    [ 6.250,  7.500) = 951 
    [ 7.500,  8.750) = 179 
    [ 8.750, 10.000) = 298 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     11.502 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.273 ± 2.509  ops/ms
ClientPb.existUser                       thrpt       3  12.755 ± 2.132  ops/ms
ClientPb.getUser                         thrpt       3  12.484 ± 1.733  ops/ms
ClientPb.listUser                        thrpt       3  10.488 ± 1.078  ops/ms
ClientPb.createUser                       avgt       3   2.594 ± 0.302   ms/op
ClientPb.existUser                        avgt       3   2.501 ± 0.194   ms/op
ClientPb.getUser                          avgt       3   2.523 ± 0.330   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.487   ms/op
ClientPb.createUser                     sample  364660   2.630 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.951           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.675           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.508           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.606           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.319           ms/op
ClientPb.existUser                      sample  385706   2.486 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.803           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.791           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.025           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.451           ms/op
ClientPb.getUser                        sample  376641   2.546 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.774           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.493           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.369           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.385           ms/op
ClientPb.listUser                       sample  310876   3.085 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.822           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.502           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
