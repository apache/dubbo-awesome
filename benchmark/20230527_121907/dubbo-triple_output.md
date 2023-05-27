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
# Warmup Iteration   1: 1.900 ops/ms
# Warmup Iteration   2: 5.700 ops/ms
# Warmup Iteration   3: 8.602 ops/ms
Iteration   1: 9.214 ops/ms
Iteration   2: 9.450 ops/ms
Iteration   3: 9.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.467 ±(99.9%) 4.765 ops/ms [Average]
  (min, avg, max) = (9.214, 9.467, 9.736), stdev = 0.261
  CI (99.9%): [4.701, 14.232] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.874 ops/ms
# Warmup Iteration   2: 8.658 ops/ms
# Warmup Iteration   3: 9.402 ops/ms
Iteration   1: 9.866 ops/ms
Iteration   2: 9.637 ops/ms
Iteration   3: 9.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.803 ±(99.9%) 2.642 ops/ms [Average]
  (min, avg, max) = (9.637, 9.803, 9.905), stdev = 0.145
  CI (99.9%): [7.161, 12.444] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.486 ops/ms
# Warmup Iteration   2: 7.270 ops/ms
# Warmup Iteration   3: 9.030 ops/ms
Iteration   1: 9.187 ops/ms
Iteration   2: 9.129 ops/ms
Iteration   3: 9.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.260 ±(99.9%) 3.249 ops/ms [Average]
  (min, avg, max) = (9.129, 9.260, 9.462), stdev = 0.178
  CI (99.9%): [6.010, 12.509] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.456 ops/ms
# Warmup Iteration   2: 6.954 ops/ms
# Warmup Iteration   3: 7.812 ops/ms
Iteration   1: 7.929 ops/ms
Iteration   2: 8.097 ops/ms
Iteration   3: 8.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.097 ±(99.9%) 3.071 ops/ms [Average]
  (min, avg, max) = (7.929, 8.097, 8.265), stdev = 0.168
  CI (99.9%): [5.026, 11.168] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.371 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.003 ms/op
Iteration   1: 3.366 ±(99.9%) 0.008 ms/op
Iteration   2: 3.502 ±(99.9%) 0.006 ms/op
Iteration   3: 3.536 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.468 ±(99.9%) 1.636 ms/op [Average]
  (min, avg, max) = (3.366, 3.468, 3.536), stdev = 0.090
  CI (99.9%): [1.832, 5.104] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.848 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.003 ms/op
Iteration   1: 3.517 ±(99.9%) 0.004 ms/op
Iteration   2: 3.286 ±(99.9%) 0.007 ms/op
Iteration   3: 3.334 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.379 ±(99.9%) 2.221 ms/op [Average]
  (min, avg, max) = (3.286, 3.379, 3.517), stdev = 0.122
  CI (99.9%): [1.158, 5.600] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.117 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.006 ms/op
Iteration   1: 3.502 ±(99.9%) 0.006 ms/op
Iteration   2: 3.429 ±(99.9%) 0.011 ms/op
Iteration   3: 3.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.468 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.429, 3.468, 3.502), stdev = 0.037
  CI (99.9%): [2.802, 4.134] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.413 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.006 ms/op
Iteration   1: 3.962 ±(99.9%) 0.013 ms/op
Iteration   2: 3.970 ±(99.9%) 0.013 ms/op
Iteration   3: 4.044 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.992 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.962, 3.992, 4.044), stdev = 0.046
  CI (99.9%): [3.161, 4.823] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.310 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.011 ms/op
Iteration   1: 3.789 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.806 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   7.987 ms/op
                 createUser·p0.999:  13.967 ms/op
                 createUser·p0.9999: 23.167 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.449 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  17.596 ms/op
                 createUser·p0.9999: 24.305 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   3: 3.324 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.022 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 25.297 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273295
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2420 
    [ 2.500,  5.000) = 261407 
    [ 5.000,  7.500) = 7187 
    [ 7.500, 10.000) = 1726 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     15.658 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     25.741 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 10.109 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
Iteration   1: 3.412 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  19.211 ms/op
                 existUser·p0.9999: 26.051 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   2: 3.305 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  16.178 ms/op
                 existUser·p0.9999: 26.323 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.262 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  11.272 ms/op
                 existUser·p0.9999: 24.943 ms/op
                 existUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288447
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1998 
    [ 2.500,  5.000) = 280790 
    [ 5.000,  7.500) = 4694 
    [ 7.500, 10.000) = 547 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     16.868 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.937 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.010 ms/op
Iteration   1: 3.563 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  17.498 ms/op
                 getUser·p0.9999: 28.803 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   2: 3.450 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  21.976 ms/op
                 getUser·p0.9999: 26.837 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 3.455 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.765 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   6.347 ms/op
                 getUser·p0.999:  21.150 ms/op
                 getUser·p0.9999: 27.681 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275073
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5105 
    [ 2.500,  5.000) = 261161 
    [ 5.000,  7.500) = 7476 
    [ 7.500, 10.000) = 922 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 119 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.539 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     27.803 ms/op
     p(99.9990) =     29.336 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.094 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.014 ms/op
Iteration   1: 4.008 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  21.234 ms/op
                 listUser·p0.9999: 26.056 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 3.996 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.556 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.825 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 3.931 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241302
  mean =      3.978 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 234005 
    [ 5.000,  7.500) = 5394 
    [ 7.500, 10.000) = 1165 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.759 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     16.723 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     26.993 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.467 ± 4.765  ops/ms
ClientPb.existUser                       thrpt       3   9.803 ± 2.642  ops/ms
ClientPb.getUser                         thrpt       3   9.260 ± 3.249  ops/ms
ClientPb.listUser                        thrpt       3   8.097 ± 3.071  ops/ms
ClientPb.createUser                       avgt       3   3.468 ± 1.636   ms/op
ClientPb.existUser                        avgt       3   3.379 ± 2.221   ms/op
ClientPb.getUser                          avgt       3   3.468 ± 0.666   ms/op
ClientPb.listUser                         avgt       3   3.992 ± 0.831   ms/op
ClientPb.createUser                     sample  273295   3.510 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.726           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.406           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.658           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.888           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.608           ms/op
ClientPb.existUser                      sample  288447   3.325 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.356           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.841           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.868           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.018           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.001           ms/op
ClientPb.getUser                        sample  275073   3.489 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.744           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.539           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.611           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.803           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  241302   3.978 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.759           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.723           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.969           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
