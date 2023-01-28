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
# Warmup Iteration   1: 2.049 ops/ms
# Warmup Iteration   2: 5.762 ops/ms
# Warmup Iteration   3: 8.691 ops/ms
Iteration   1: 9.357 ops/ms
Iteration   2: 9.417 ops/ms
Iteration   3: 9.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.456 ±(99.9%) 2.246 ops/ms [Average]
  (min, avg, max) = (9.357, 9.456, 9.594), stdev = 0.123
  CI (99.9%): [7.210, 11.702] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.249 ops/ms
# Warmup Iteration   2: 9.090 ops/ms
# Warmup Iteration   3: 9.158 ops/ms
Iteration   1: 9.878 ops/ms
Iteration   2: 9.589 ops/ms
Iteration   3: 9.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.756 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (9.589, 9.756, 9.878), stdev = 0.149
  CI (99.9%): [7.035, 12.476] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.493 ops/ms
# Warmup Iteration   2: 8.775 ops/ms
# Warmup Iteration   3: 9.460 ops/ms
Iteration   1: 9.583 ops/ms
Iteration   2: 9.159 ops/ms
Iteration   3: 9.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.456 ±(99.9%) 4.708 ops/ms [Average]
  (min, avg, max) = (9.159, 9.456, 9.626), stdev = 0.258
  CI (99.9%): [4.749, 14.164] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.232 ops/ms
# Warmup Iteration   2: 7.011 ops/ms
# Warmup Iteration   3: 7.613 ops/ms
Iteration   1: 7.496 ops/ms
Iteration   2: 8.108 ops/ms
Iteration   3: 7.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.865 ±(99.9%) 5.927 ops/ms [Average]
  (min, avg, max) = (7.496, 7.865, 8.108), stdev = 0.325
  CI (99.9%): [1.938, 13.792] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.898 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.008 ms/op
Iteration   1: 3.429 ±(99.9%) 0.006 ms/op
Iteration   2: 3.433 ±(99.9%) 0.005 ms/op
Iteration   3: 3.417 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.426 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (3.417, 3.426, 3.433), stdev = 0.008
  CI (99.9%): [3.274, 3.578] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.386 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.003 ms/op
Iteration   1: 3.277 ±(99.9%) 0.008 ms/op
Iteration   2: 3.370 ±(99.9%) 0.006 ms/op
Iteration   3: 3.251 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.299 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (3.251, 3.299, 3.370), stdev = 0.062
  CI (99.9%): [2.163, 4.436] (assumes normal distribution)


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
# Warmup Iteration   1: 9.833 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.006 ms/op
Iteration   1: 3.425 ±(99.9%) 0.004 ms/op
Iteration   2: 3.538 ±(99.9%) 0.005 ms/op
Iteration   3: 3.402 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.455 ±(99.9%) 1.330 ms/op [Average]
  (min, avg, max) = (3.402, 3.455, 3.538), stdev = 0.073
  CI (99.9%): [2.125, 4.785] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.290 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.008 ms/op
Iteration   1: 3.962 ±(99.9%) 0.012 ms/op
Iteration   2: 3.978 ±(99.9%) 0.009 ms/op
Iteration   3: 4.031 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.990 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.962, 3.990, 4.031), stdev = 0.036
  CI (99.9%): [3.333, 4.648] (assumes normal distribution)


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
# Warmup Iteration   1: 8.409 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.009 ms/op
Iteration   1: 3.509 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  19.034 ms/op
                 createUser·p0.9999: 21.430 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   2: 3.449 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.171 ms/op
                 createUser·p0.999:  21.244 ms/op
                 createUser·p0.9999: 23.575 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.562 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  20.027 ms/op
                 createUser·p0.9999: 35.979 ms/op
                 createUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273630
  mean =      3.506 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3588 
    [ 2.500,  5.000) = 260652 
    [ 5.000,  7.500) = 7903 
    [ 7.500, 10.000) = 964 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     19.357 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 9.119 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
Iteration   1: 3.319 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  19.694 ms/op
                 existUser·p0.9999: 26.739 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 3.419 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  21.462 ms/op
                 existUser·p0.9999: 25.405 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.332 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  17.358 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284866
  mean =      3.367 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6893 
    [ 2.500,  5.000) = 271878 
    [ 5.000,  7.500) = 5176 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 8.513 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.011 ms/op
Iteration   1: 3.412 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  20.522 ms/op
                 getUser·p0.9999: 23.217 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.435 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  9.960 ms/op
                 getUser·p0.9999: 24.992 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.433 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.351 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  19.719 ms/op
                 getUser·p0.9999: 27.089 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280055
  mean =      3.427 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7524 
    [ 2.500,  5.000) = 264394 
    [ 5.000,  7.500) = 7141 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     12.990 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     27.335 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 11.961 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.296 ±(99.9%) 0.015 ms/op
Iteration   1: 4.157 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  21.270 ms/op
                 listUser·p0.9999: 25.204 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 4.029 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  15.951 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   3: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  16.544 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235556
  mean =      4.073 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 225469 
    [ 5.000,  7.500) = 7199 
    [ 7.500, 10.000) = 1881 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     16.806 ms/op
     p(99.9900) =     23.851 ms/op
     p(99.9990) =     25.742 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.456 ± 2.246  ops/ms
ClientPb.existUser                       thrpt       3   9.756 ± 2.720  ops/ms
ClientPb.getUser                         thrpt       3   9.456 ± 4.708  ops/ms
ClientPb.listUser                        thrpt       3   7.865 ± 5.927  ops/ms
ClientPb.createUser                       avgt       3   3.426 ± 0.152   ms/op
ClientPb.existUser                        avgt       3   3.299 ± 1.137   ms/op
ClientPb.getUser                          avgt       3   3.455 ± 1.330   ms/op
ClientPb.listUser                         avgt       3   3.990 ± 0.657   ms/op
ClientPb.createUser                     sample  273630   3.506 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.734           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.481           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.357           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.948           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.045           ms/op
ClientPb.existUser                      sample  284866   3.367 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.503           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.743           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.498           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.558           ms/op
ClientPb.getUser                        sample  280055   3.427 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.351           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.990           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.264           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.394           ms/op
ClientPb.listUser                       sample  235556   4.073 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.104           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.806           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.851           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
