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
# Warmup Iteration   1: 4.907 ops/ms
# Warmup Iteration   2: 12.123 ops/ms
# Warmup Iteration   3: 12.356 ops/ms
Iteration   1: 12.427 ops/ms
Iteration   2: 12.547 ops/ms
Iteration   3: 12.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.496 ±(99.9%) 1.129 ops/ms [Average]
  (min, avg, max) = (12.427, 12.496, 12.547), stdev = 0.062
  CI (99.9%): [11.367, 13.625] (assumes normal distribution)


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
# Warmup Iteration   1: 8.328 ops/ms
# Warmup Iteration   2: 13.208 ops/ms
# Warmup Iteration   3: 13.208 ops/ms
Iteration   1: 13.272 ops/ms
Iteration   2: 13.243 ops/ms
Iteration   3: 13.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.274 ±(99.9%) 0.594 ops/ms [Average]
  (min, avg, max) = (13.243, 13.274, 13.308), stdev = 0.033
  CI (99.9%): [12.681, 13.868] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.434 ops/ms
# Warmup Iteration   2: 12.712 ops/ms
# Warmup Iteration   3: 12.949 ops/ms
Iteration   1: 12.881 ops/ms
Iteration   2: 12.911 ops/ms
Iteration   3: 12.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.809 ±(99.9%) 2.772 ops/ms [Average]
  (min, avg, max) = (12.634, 12.809, 12.911), stdev = 0.152
  CI (99.9%): [10.037, 15.581] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.413 ops/ms
# Warmup Iteration   2: 10.600 ops/ms
# Warmup Iteration   3: 10.615 ops/ms
Iteration   1: 10.855 ops/ms
Iteration   2: 10.811 ops/ms
Iteration   3: 10.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.812 ±(99.9%) 0.778 ops/ms [Average]
  (min, avg, max) = (10.770, 10.812, 10.855), stdev = 0.043
  CI (99.9%): [10.034, 11.590] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.003 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.501 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.483, 2.501, 2.519), stdev = 0.018
  CI (99.9%): [2.173, 2.829] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.004 ms/op
Iteration   1: 2.412 ±(99.9%) 0.004 ms/op
Iteration   2: 2.432 ±(99.9%) 0.003 ms/op
Iteration   3: 2.412 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.419 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.412, 2.419, 2.432), stdev = 0.011
  CI (99.9%): [2.210, 2.628] (assumes normal distribution)


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.003 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.511 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (2.480, 2.511, 2.529), stdev = 0.027
  CI (99.9%): [2.019, 3.003] (assumes normal distribution)


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
# Warmup Iteration   1: 4.850 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.005 ms/op
Iteration   1: 2.996 ±(99.9%) 0.005 ms/op
Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
Iteration   3: 2.960 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (2.960, 2.973, 2.996), stdev = 0.021
  CI (99.9%): [2.597, 3.349] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  9.033 ms/op
                 createUser·p0.9999: 13.451 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  8.413 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  8.597 ms/op
                 createUser·p0.9999: 11.423 ms/op
                 createUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387510
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 189287 
    [ 2.500,  3.750) = 194687 
    [ 3.750,  5.000) = 2730 
    [ 5.000,  6.250) = 287 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     19.632 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.684 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.260 ms/op
                 existUser·p0.999:  6.645 ms/op
                 existUser·p0.9999: 13.333 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  7.926 ms/op
                 existUser·p0.9999: 12.459 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  7.823 ms/op
                 existUser·p0.9999: 11.679 ms/op
                 existUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396427
  mean =      2.419 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 197367 
    [ 2.500,  3.750) = 196618 
    [ 3.750,  5.000) = 1693 
    [ 5.000,  6.250) = 234 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.445 ms/op
     p(99.9000) =      7.812 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     13.633 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  6.636 ms/op
                 getUser·p0.9999: 13.287 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  4.983 ms/op
                 getUser·p0.9999: 10.603 ms/op
                 getUser·p1.00:   11.043 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  6.600 ms/op
                 getUser·p0.9999: 11.372 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386764
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 193119 
    [ 2.500,  3.750) = 190638 
    [ 3.750,  5.000) = 2434 
    [ 5.000,  6.250) = 143 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      5.464 ms/op
     p(99.9900) =     13.025 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 4.669 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.505 ms/op
                 listUser·p0.9999: 11.430 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.281 ms/op
                 listUser·p0.9999: 10.486 ms/op
                 listUser·p1.00:   10.928 ms/op

Iteration   3: 2.964 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.333 ms/op
                 listUser·p0.999:  8.765 ms/op
                 listUser·p0.9999: 10.289 ms/op
                 listUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321298
  mean =      2.985 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 95452 
    [ 2.500,  3.750) = 188213 
    [ 3.750,  5.000) = 31157 
    [ 5.000,  6.250) = 5183 
    [ 6.250,  7.500) = 564 
    [ 7.500,  8.750) = 267 
    [ 8.750, 10.000) = 205 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      8.777 ms/op
     p(99.9900) =     10.615 ms/op
     p(99.9990) =     12.149 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.496 ± 1.129  ops/ms
ClientPb.existUser                       thrpt       3  13.274 ± 0.594  ops/ms
ClientPb.getUser                         thrpt       3  12.809 ± 2.772  ops/ms
ClientPb.listUser                        thrpt       3  10.812 ± 0.778  ops/ms
ClientPb.createUser                       avgt       3   2.501 ± 0.328   ms/op
ClientPb.existUser                        avgt       3   2.419 ± 0.209   ms/op
ClientPb.getUser                          avgt       3   2.511 ± 0.492   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.376   ms/op
ClientPb.createUser                     sample  387510   2.474 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.800           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.602           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.599           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.759           ms/op
ClientPb.existUser                      sample  396427   2.419 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.843           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.812           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.894           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.991           ms/op
ClientPb.getUser                        sample  386764   2.480 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.767           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.464           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.025           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.238           ms/op
ClientPb.listUser                       sample  321298   2.985 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.777           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.615           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.255           ms/op
