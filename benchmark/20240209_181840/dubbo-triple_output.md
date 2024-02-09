# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.713 ops/ms
# Warmup Iteration   2: 12.013 ops/ms
# Warmup Iteration   3: 12.421 ops/ms
Iteration   1: 12.606 ops/ms
Iteration   2: 12.824 ops/ms
Iteration   3: 12.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.749 ±(99.9%) 2.269 ops/ms [Average]
  (min, avg, max) = (12.606, 12.749, 12.824), stdev = 0.124
  CI (99.9%): [10.481, 15.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.283 ops/ms
# Warmup Iteration   2: 13.493 ops/ms
# Warmup Iteration   3: 13.213 ops/ms
Iteration   1: 13.425 ops/ms
Iteration   2: 13.491 ops/ms
Iteration   3: 13.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.450 ±(99.9%) 0.655 ops/ms [Average]
  (min, avg, max) = (13.425, 13.450, 13.491), stdev = 0.036
  CI (99.9%): [12.795, 14.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 12.822 ops/ms
# Warmup Iteration   3: 12.990 ops/ms
Iteration   1: 13.168 ops/ms
Iteration   2: 13.000 ops/ms
Iteration   3: 12.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.046 ±(99.9%) 1.961 ops/ms [Average]
  (min, avg, max) = (12.969, 13.046, 13.168), stdev = 0.107
  CI (99.9%): [11.085, 15.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.488 ops/ms
# Warmup Iteration   2: 10.585 ops/ms
# Warmup Iteration   3: 10.594 ops/ms
Iteration   1: 10.705 ops/ms
Iteration   2: 10.739 ops/ms
Iteration   3: 10.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.689 ±(99.9%) 1.074 ops/ms [Average]
  (min, avg, max) = (10.625, 10.689, 10.739), stdev = 0.059
  CI (99.9%): [9.615, 11.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.003 ms/op
Iteration   1: 2.573 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
Iteration   3: 2.523 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (2.523, 2.548, 2.573), stdev = 0.025
  CI (99.9%): [2.095, 3.001] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.004 ms/op
Iteration   1: 2.391 ±(99.9%) 0.004 ms/op
Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
Iteration   3: 2.398 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.407 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (2.391, 2.407, 2.432), stdev = 0.022
  CI (99.9%): [2.011, 2.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.781 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.452 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.452 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.438, 2.452, 2.466), stdev = 0.014
  CI (99.9%): [2.200, 2.704] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.536 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
Iteration   3: 2.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.969 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.963, 2.969, 2.977), stdev = 0.007
  CI (99.9%): [2.840, 3.099] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  10.479 ms/op
                 createUser·p0.9999: 14.385 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  7.737 ms/op
                 createUser·p0.9999: 19.762 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  8.176 ms/op
                 createUser·p0.9999: 9.673 ms/op
                 createUser·p1.00:   10.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386382
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188036 
    [ 2.500,  5.000) = 197138 
    [ 5.000,  7.500) = 758 
    [ 7.500, 10.000) = 200 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     14.446 ms/op
     p(99.9990) =     20.484 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.757 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
Iteration   1: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  5.664 ms/op
                 existUser·p0.9999: 17.816 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   2: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.049 ms/op
                 existUser·p0.9999: 13.398 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   3: 2.390 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.759 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399439
  mean =      2.401 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 203042 
    [ 2.500,  3.750) = 193677 
    [ 3.750,  5.000) = 2117 
    [ 5.000,  6.250) = 142 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =      5.759 ms/op
     p(99.9900) =     14.484 ms/op
     p(99.9990) =     18.023 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  9.806 ms/op
                 getUser·p0.9999: 13.410 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  7.333 ms/op
                 getUser·p0.9999: 13.060 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.502 ms/op
                 getUser·p0.999:  5.819 ms/op
                 getUser·p0.9999: 10.988 ms/op
                 getUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388440
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 194305 
    [ 2.500,  3.750) = 189594 
    [ 3.750,  5.000) = 3671 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      7.144 ms/op
     p(99.9900) =     13.093 ms/op
     p(99.9990) =     13.635 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.765 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
Iteration   1: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.797 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.611 ms/op
                 listUser·p0.9999: 10.572 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   2: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.446 ms/op
                 listUser·p0.999:  9.845 ms/op
                 listUser·p0.9999: 14.287 ms/op
                 listUser·p1.00:   14.860 ms/op

Iteration   3: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  10.616 ms/op
                 listUser·p0.9999: 12.963 ms/op
                 listUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323506
  mean =      2.965 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 100884 
    [ 2.500,  3.750) = 186944 
    [ 3.750,  5.000) = 29284 
    [ 5.000,  6.250) = 4968 
    [ 6.250,  7.500) = 616 
    [ 7.500,  8.750) = 165 
    [ 8.750, 10.000) = 230 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     13.495 ms/op
     p(99.9990) =     14.509 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.749 ± 2.269  ops/ms
ClientPb.existUser                       thrpt       3  13.450 ± 0.655  ops/ms
ClientPb.getUser                         thrpt       3  13.046 ± 1.961  ops/ms
ClientPb.listUser                        thrpt       3  10.689 ± 1.074  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.453   ms/op
ClientPb.existUser                        avgt       3   2.407 ± 0.396   ms/op
ClientPb.getUser                          avgt       3   2.452 ± 0.252   ms/op
ClientPb.listUser                         avgt       3   2.969 ± 0.130   ms/op
ClientPb.createUser                     sample  386382   2.482 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.785           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.389           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.446           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.808           ms/op
ClientPb.existUser                      sample  399439   2.401 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.813           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.912           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.759           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.874           ms/op
ClientPb.getUser                        sample  388440   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.808           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.144           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.093           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.139           ms/op
ClientPb.listUser                       sample  323506   2.965 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.797           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.495           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.860           ms/op
