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
# Warmup Iteration   1: 2.184 ops/ms
# Warmup Iteration   2: 5.199 ops/ms
# Warmup Iteration   3: 8.520 ops/ms
Iteration   1: 9.106 ops/ms
Iteration   2: 9.101 ops/ms
Iteration   3: 9.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.182 ±(99.9%) 2.473 ops/ms [Average]
  (min, avg, max) = (9.101, 9.182, 9.338), stdev = 0.136
  CI (99.9%): [6.709, 11.655] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.189 ops/ms
# Warmup Iteration   2: 8.763 ops/ms
# Warmup Iteration   3: 9.534 ops/ms
Iteration   1: 9.596 ops/ms
Iteration   2: 9.907 ops/ms
Iteration   3: 9.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.667 ±(99.9%) 3.909 ops/ms [Average]
  (min, avg, max) = (9.497, 9.667, 9.907), stdev = 0.214
  CI (99.9%): [5.758, 13.575] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.170 ops/ms
# Warmup Iteration   2: 8.330 ops/ms
# Warmup Iteration   3: 8.542 ops/ms
Iteration   1: 9.081 ops/ms
Iteration   2: 9.037 ops/ms
Iteration   3: 9.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.128 ±(99.9%) 2.210 ops/ms [Average]
  (min, avg, max) = (9.037, 9.128, 9.265), stdev = 0.121
  CI (99.9%): [6.917, 11.338] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.956 ops/ms
# Warmup Iteration   2: 7.076 ops/ms
# Warmup Iteration   3: 7.566 ops/ms
Iteration   1: 7.731 ops/ms
Iteration   2: 7.852 ops/ms
Iteration   3: 7.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.777 ±(99.9%) 1.196 ops/ms [Average]
  (min, avg, max) = (7.731, 7.777, 7.852), stdev = 0.066
  CI (99.9%): [6.581, 8.973] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.134 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.006 ms/op
Iteration   1: 3.566 ±(99.9%) 0.006 ms/op
Iteration   2: 3.500 ±(99.9%) 0.007 ms/op
Iteration   3: 3.438 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.501 ±(99.9%) 1.170 ms/op [Average]
  (min, avg, max) = (3.438, 3.501, 3.566), stdev = 0.064
  CI (99.9%): [2.332, 4.671] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.180 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.004 ms/op
Iteration   1: 3.187 ±(99.9%) 0.008 ms/op
Iteration   2: 3.298 ±(99.9%) 0.009 ms/op
Iteration   3: 3.247 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.244 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (3.187, 3.244, 3.298), stdev = 0.056
  CI (99.9%): [2.230, 4.258] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.174 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.005 ms/op
Iteration   1: 3.426 ±(99.9%) 0.002 ms/op
Iteration   2: 3.472 ±(99.9%) 0.004 ms/op
Iteration   3: 3.333 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.410 ±(99.9%) 1.297 ms/op [Average]
  (min, avg, max) = (3.333, 3.410, 3.472), stdev = 0.071
  CI (99.9%): [2.114, 4.707] (assumes normal distribution)


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
# Warmup Iteration   1: 10.427 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.008 ms/op
Iteration   1: 4.098 ±(99.9%) 0.009 ms/op
Iteration   2: 3.915 ±(99.9%) 0.014 ms/op
Iteration   3: 4.112 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.042 ±(99.9%) 2.010 ms/op [Average]
  (min, avg, max) = (3.915, 4.042, 4.112), stdev = 0.110
  CI (99.9%): [2.032, 6.052] (assumes normal distribution)


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
# Warmup Iteration   1: 9.666 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.010 ms/op
Iteration   1: 3.496 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  16.523 ms/op
                 createUser·p0.9999: 19.685 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.401 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  17.239 ms/op
                 createUser·p0.9999: 23.023 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.362 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  15.825 ms/op
                 createUser·p0.9999: 25.656 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280508
  mean =      3.419 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5604 
    [ 2.500,  5.000) = 268397 
    [ 5.000,  7.500) = 5452 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     26.096 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 8.313 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.008 ms/op
Iteration   1: 3.315 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.729 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  15.488 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   2: 3.391 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  22.008 ms/op
                 existUser·p0.9999: 35.324 ms/op
                 existUser·p1.00:   36.504 ms/op

Iteration   3: 3.340 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  17.015 ms/op
                 existUser·p0.9999: 28.040 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286568
  mean =      3.348 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9920 
    [ 2.500,  5.000) = 270770 
    [ 5.000,  7.500) = 4966 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.794 ms/op
     p(99.9000) =     17.053 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     35.595 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 8.800 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
Iteration   1: 3.403 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  18.937 ms/op
                 getUser·p0.9999: 22.072 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.639 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  21.433 ms/op
                 getUser·p0.9999: 29.721 ms/op
                 getUser·p1.00:   31.293 ms/op

Iteration   3: 3.389 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  19.817 ms/op
                 getUser·p0.9999: 25.610 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276491
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7872 
    [ 2.500,  5.000) = 259298 
    [ 5.000,  7.500) = 8130 
    [ 7.500, 10.000) = 788 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     28.433 ms/op
     p(99.9990) =     30.285 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 9.755 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.013 ms/op
Iteration   1: 4.070 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  18.162 ms/op
                 listUser·p0.9999: 23.799 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   2: 4.140 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.285 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 4.050 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.220 ms/op
                 listUser·p0.999:  14.484 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234786
  mean =      4.086 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 222640 
    [ 5.000,  7.500) = 10131 
    [ 7.500, 10.000) = 1225 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     15.454 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.486 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.182 ± 2.473  ops/ms
ClientPb.existUser                       thrpt       3   9.667 ± 3.909  ops/ms
ClientPb.getUser                         thrpt       3   9.128 ± 2.210  ops/ms
ClientPb.listUser                        thrpt       3   7.777 ± 1.196  ops/ms
ClientPb.createUser                       avgt       3   3.501 ± 1.170   ms/op
ClientPb.existUser                        avgt       3   3.244 ± 1.014   ms/op
ClientPb.getUser                          avgt       3   3.410 ± 1.297   ms/op
ClientPb.listUser                         avgt       3   4.042 ± 2.010   ms/op
ClientPb.createUser                     sample  280508   3.419 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.335           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.626           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.182           ms/op
ClientPb.existUser                      sample  286568   3.348 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.794           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.053           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.948           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.504           ms/op
ClientPb.getUser                        sample  276491   3.473 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.059           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.366           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.433           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.293           ms/op
ClientPb.listUser                       sample  234786   4.086 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.667           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.610           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.133           ms/op
