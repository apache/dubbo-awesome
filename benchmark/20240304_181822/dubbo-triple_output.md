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
# Warmup Iteration   1: 5.306 ops/ms
# Warmup Iteration   2: 12.718 ops/ms
# Warmup Iteration   3: 12.733 ops/ms
Iteration   1: 12.906 ops/ms
Iteration   2: 13.107 ops/ms
Iteration   3: 12.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.996 ±(99.9%) 1.868 ops/ms [Average]
  (min, avg, max) = (12.906, 12.996, 13.107), stdev = 0.102
  CI (99.9%): [11.128, 14.864] (assumes normal distribution)


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
# Warmup Iteration   1: 8.009 ops/ms
# Warmup Iteration   2: 13.193 ops/ms
# Warmup Iteration   3: 13.221 ops/ms
Iteration   1: 13.155 ops/ms
Iteration   2: 13.292 ops/ms
Iteration   3: 13.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.265 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (13.155, 13.265, 13.346), stdev = 0.098
  CI (99.9%): [11.468, 15.061] (assumes normal distribution)


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
# Warmup Iteration   1: 7.901 ops/ms
# Warmup Iteration   2: 12.781 ops/ms
# Warmup Iteration   3: 12.851 ops/ms
Iteration   1: 13.112 ops/ms
Iteration   2: 13.042 ops/ms
Iteration   3: 12.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.029 ±(99.9%) 1.647 ops/ms [Average]
  (min, avg, max) = (12.933, 13.029, 13.112), stdev = 0.090
  CI (99.9%): [11.382, 14.676] (assumes normal distribution)


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
# Warmup Iteration   1: 6.959 ops/ms
# Warmup Iteration   2: 10.701 ops/ms
# Warmup Iteration   3: 10.708 ops/ms
Iteration   1: 10.813 ops/ms
Iteration   2: 10.851 ops/ms
Iteration   3: 10.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.764 ±(99.9%) 2.163 ops/ms [Average]
  (min, avg, max) = (10.629, 10.764, 10.851), stdev = 0.119
  CI (99.9%): [8.601, 12.928] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
Iteration   1: 2.393 ±(99.9%) 0.006 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.404 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.417 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (2.393, 2.417, 2.455), stdev = 0.033
  CI (99.9%): [1.816, 3.018] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.660 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.388 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.390 ±(99.9%) 0.004 ms/op
Iteration   1: 2.393 ±(99.9%) 0.003 ms/op
Iteration   2: 2.409 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (2.393, 2.418, 2.450), stdev = 0.029
  CI (99.9%): [1.885, 2.950] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.473 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.461, 2.473, 2.479), stdev = 0.010
  CI (99.9%): [2.286, 2.661] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.587 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
Iteration   3: 2.974 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.970 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (2.966, 2.970, 2.974), stdev = 0.004
  CI (99.9%): [2.895, 3.046] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  11.596 ms/op
                 createUser·p0.9999: 14.041 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   4.063 ms/op
                 createUser·p0.999:  10.158 ms/op
                 createUser·p0.9999: 12.534 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.842 ms/op
                 createUser·p0.9999: 10.933 ms/op
                 createUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382744
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 187374 
    [ 2.500,  3.750) = 188879 
    [ 3.750,  5.000) = 4848 
    [ 5.000,  6.250) = 996 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      9.622 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.332 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  5.564 ms/op
                 existUser·p0.9999: 14.483 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  6.388 ms/op
                 existUser·p0.9999: 13.838 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 11.488 ms/op
                 existUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388364
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 192774 
    [ 2.500,  3.750) = 191810 
    [ 3.750,  5.000) = 2963 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      7.033 ms/op
     p(99.9900) =     13.798 ms/op
     p(99.9990) =     15.261 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.093 ms/op
                 getUser·p0.999:  8.028 ms/op
                 getUser·p0.9999: 14.587 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.320 ms/op
                 getUser·p0.999:  6.013 ms/op
                 getUser·p0.9999: 13.457 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 12.703 ms/op
                 getUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382333
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 190039 
    [ 2.500,  3.750) = 186390 
    [ 3.750,  5.000) = 4609 
    [ 5.000,  6.250) = 717 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =      7.356 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     15.060 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.009 ms/op
Iteration   1: 2.961 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  10.461 ms/op
                 listUser·p0.9999: 13.858 ms/op
                 listUser·p1.00:   14.828 ms/op

Iteration   2: 2.933 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.839 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.357 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 2.857 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   2.781 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.360 ms/op
                 listUser·p0.9999: 12.960 ms/op
                 listUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 328857
  mean =      2.916 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 369 
    [ 1.250,  2.500) = 118467 
    [ 2.500,  3.750) = 168564 
    [ 3.750,  5.000) = 34343 
    [ 5.000,  6.250) = 5478 
    [ 6.250,  7.500) = 822 
    [ 7.500,  8.750) = 290 
    [ 8.750, 10.000) = 214 
    [10.000, 11.250) = 181 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.882 ms/op
     p(99.9900) =     13.127 ms/op
     p(99.9990) =     14.198 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.996 ± 1.868  ops/ms
ClientPb.existUser                       thrpt       3  13.265 ± 1.797  ops/ms
ClientPb.getUser                         thrpt       3  13.029 ± 1.647  ops/ms
ClientPb.listUser                        thrpt       3  10.764 ± 2.163  ops/ms
ClientPb.createUser                       avgt       3   2.417 ± 0.601   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.533   ms/op
ClientPb.getUser                          avgt       3   2.473 ± 0.188   ms/op
ClientPb.listUser                         avgt       3   2.970 ± 0.076   ms/op
ClientPb.createUser                     sample  382744   2.506 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.794           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.622           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.648           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.500           ms/op
ClientPb.existUser                      sample  388364   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.933           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.033           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.798           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.565           ms/op
ClientPb.getUser                        sample  382333   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.715           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.356           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.582           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.122           ms/op
ClientPb.listUser                       sample  328857   2.916 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.817           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.882           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.127           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.828           ms/op
