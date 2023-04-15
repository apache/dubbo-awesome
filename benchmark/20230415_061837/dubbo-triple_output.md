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
# Warmup Iteration   1: 2.528 ops/ms
# Warmup Iteration   2: 6.744 ops/ms
# Warmup Iteration   3: 9.671 ops/ms
Iteration   1: 10.054 ops/ms
Iteration   2: 9.910 ops/ms
Iteration   3: 10.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.044 ±(99.9%) 2.368 ops/ms [Average]
  (min, avg, max) = (9.910, 10.044, 10.169), stdev = 0.130
  CI (99.9%): [7.677, 12.412] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ops/ms
# Warmup Iteration   2: 9.394 ops/ms
# Warmup Iteration   3: 10.149 ops/ms
Iteration   1: 10.382 ops/ms
Iteration   2: 10.267 ops/ms
Iteration   3: 10.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.279 ±(99.9%) 1.788 ops/ms [Average]
  (min, avg, max) = (10.187, 10.279, 10.382), stdev = 0.098
  CI (99.9%): [8.491, 12.067] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.163 ops/ms
# Warmup Iteration   2: 8.847 ops/ms
# Warmup Iteration   3: 9.643 ops/ms
Iteration   1: 9.694 ops/ms
Iteration   2: 9.746 ops/ms
Iteration   3: 10.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.949 ±(99.9%) 7.250 ops/ms [Average]
  (min, avg, max) = (9.694, 9.949, 10.407), stdev = 0.397
  CI (99.9%): [2.699, 17.199] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.985 ops/ms
# Warmup Iteration   2: 7.463 ops/ms
# Warmup Iteration   3: 8.528 ops/ms
Iteration   1: 8.568 ops/ms
Iteration   2: 8.432 ops/ms
Iteration   3: 8.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.535 ±(99.9%) 1.666 ops/ms [Average]
  (min, avg, max) = (8.432, 8.535, 8.606), stdev = 0.091
  CI (99.9%): [6.870, 10.201] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.024 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
Iteration   1: 3.142 ±(99.9%) 0.006 ms/op
Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
Iteration   3: 3.095 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.097 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (3.054, 3.097, 3.142), stdev = 0.044
  CI (99.9%): [2.294, 3.900] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.389 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
Iteration   3: 3.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.079 ±(99.9%) 1.476 ms/op [Average]
  (min, avg, max) = (3.006, 3.079, 3.166), stdev = 0.081
  CI (99.9%): [1.602, 4.555] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.358 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.001 ms/op
Iteration   1: 3.289 ±(99.9%) 0.002 ms/op
Iteration   2: 3.234 ±(99.9%) 0.003 ms/op
Iteration   3: 3.221 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.248 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.221, 3.248, 3.289), stdev = 0.036
  CI (99.9%): [2.586, 3.910] (assumes normal distribution)


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
# Warmup Iteration   1: 9.757 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.235 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.010 ms/op
Iteration   1: 3.757 ±(99.9%) 0.009 ms/op
Iteration   2: 3.799 ±(99.9%) 0.008 ms/op
Iteration   3: 3.792 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.782 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.757, 3.782, 3.799), stdev = 0.022
  CI (99.9%): [3.373, 4.192] (assumes normal distribution)


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
# Warmup Iteration   1: 7.923 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
Iteration   1: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  9.432 ms/op
                 createUser·p0.9999: 19.160 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   2: 3.161 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 21.164 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.510 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  14.643 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306463
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25625 
    [ 2.500,  5.000) = 275001 
    [ 5.000,  7.500) = 4987 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 190 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     15.173 ms/op
     p(99.9900) =     20.623 ms/op
     p(99.9990) =     21.553 ms/op
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
# Warmup Iteration   1: 6.968 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 22.035 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   2: 3.175 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  19.732 ms/op
                 existUser·p0.9999: 25.914 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.882 ms/op
                 existUser·p0.999:  12.502 ms/op
                 existUser·p0.9999: 21.579 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310720
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12326 
    [ 2.500,  5.000) = 294665 
    [ 5.000,  7.500) = 3027 
    [ 7.500, 10.000) = 281 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     14.595 ms/op
     p(99.9900) =     25.290 ms/op
     p(99.9990) =     26.044 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 7.807 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  15.696 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.296 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  10.236 ms/op
                 getUser·p0.9999: 21.669 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  16.080 ms/op
                 getUser·p0.9999: 21.841 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292166
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16577 
    [ 2.500,  5.000) = 266499 
    [ 5.000,  7.500) = 8102 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     15.693 ms/op
     p(99.9900) =     21.456 ms/op
     p(99.9990) =     22.809 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 9.335 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.013 ms/op
Iteration   1: 3.812 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  17.074 ms/op
                 listUser·p0.9999: 21.471 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.054 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  14.137 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   3: 3.682 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   6.916 ms/op
                 listUser·p0.999:  12.863 ms/op
                 listUser·p0.9999: 13.959 ms/op
                 listUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255979
  mean =      3.749 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 247140 
    [ 5.000,  7.500) = 6758 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 320 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     22.362 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.044 ± 2.368  ops/ms
ClientPb.existUser                       thrpt       3  10.279 ± 1.788  ops/ms
ClientPb.getUser                         thrpt       3   9.949 ± 7.250  ops/ms
ClientPb.listUser                        thrpt       3   8.535 ± 1.666  ops/ms
ClientPb.createUser                       avgt       3   3.097 ± 0.803   ms/op
ClientPb.existUser                        avgt       3   3.079 ± 1.476   ms/op
ClientPb.getUser                          avgt       3   3.248 ± 0.662   ms/op
ClientPb.listUser                         avgt       3   3.782 ± 0.410   ms/op
ClientPb.createUser                     sample  306463   3.132 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.882           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.173           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.623           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.298           ms/op
ClientPb.existUser                      sample  310720   3.089 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.044           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.363           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.595           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.290           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.214           ms/op
ClientPb.getUser                        sample  292166   3.285 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.174           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.693           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.456           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.905           ms/op
ClientPb.listUser                       sample  255979   3.749 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.231           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.894           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.218           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.413           ms/op
