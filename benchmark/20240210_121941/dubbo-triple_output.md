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
# Warmup Iteration   1: 4.804 ops/ms
# Warmup Iteration   2: 11.766 ops/ms
# Warmup Iteration   3: 12.170 ops/ms
Iteration   1: 12.411 ops/ms
Iteration   2: 12.517 ops/ms
Iteration   3: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.475 ±(99.9%) 1.026 ops/ms [Average]
  (min, avg, max) = (12.411, 12.475, 12.517), stdev = 0.056
  CI (99.9%): [11.450, 13.501] (assumes normal distribution)


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
# Warmup Iteration   1: 8.141 ops/ms
# Warmup Iteration   2: 13.084 ops/ms
# Warmup Iteration   3: 13.046 ops/ms
Iteration   1: 12.986 ops/ms
Iteration   2: 13.157 ops/ms
Iteration   3: 13.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.095 ±(99.9%) 1.722 ops/ms [Average]
  (min, avg, max) = (12.986, 13.095, 13.157), stdev = 0.094
  CI (99.9%): [11.373, 14.817] (assumes normal distribution)


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
# Warmup Iteration   1: 7.956 ops/ms
# Warmup Iteration   2: 12.513 ops/ms
# Warmup Iteration   3: 12.687 ops/ms
Iteration   1: 12.662 ops/ms
Iteration   2: 12.536 ops/ms
Iteration   3: 12.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.594 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (12.536, 12.594, 12.662), stdev = 0.064
  CI (99.9%): [11.431, 13.758] (assumes normal distribution)


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
# Warmup Iteration   1: 6.630 ops/ms
# Warmup Iteration   2: 10.230 ops/ms
# Warmup Iteration   3: 10.688 ops/ms
Iteration   1: 10.620 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.643 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (10.613, 10.643, 10.697), stdev = 0.047
  CI (99.9%): [9.794, 11.493] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.577 ±(99.9%) 0.004 ms/op
Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.556 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.546, 2.556, 2.577), stdev = 0.018
  CI (99.9%): [2.224, 2.888] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.003 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.464 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.460, 2.464, 2.468), stdev = 0.004
  CI (99.9%): [2.390, 2.538] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.003 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.473, 2.494, 2.507), stdev = 0.019
  CI (99.9%): [2.156, 2.832] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.803 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.005 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
Iteration   3: 3.052 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.053 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (3.048, 3.053, 3.060), stdev = 0.006
  CI (99.9%): [2.936, 3.171] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  12.255 ms/op
                 createUser·p0.9999: 13.928 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.970 ms/op
                 createUser·p0.9999: 14.230 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 10.846 ms/op
                 createUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374038
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 178280 
    [ 2.500,  3.750) = 191137 
    [ 3.750,  5.000) = 3675 
    [ 5.000,  6.250) = 440 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.527 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.246 ms/op
                 existUser·p0.9999: 13.827 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  6.024 ms/op
                 existUser·p0.9999: 13.679 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.703 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391994
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 197088 
    [ 2.500,  3.750) = 191618 
    [ 3.750,  5.000) = 2498 
    [ 5.000,  6.250) = 350 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 137 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      6.111 ms/op
     p(99.9900) =     13.694 ms/op
     p(99.9990) =     14.392 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.923 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  6.597 ms/op
                 getUser·p0.9999: 13.610 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  9.218 ms/op
                 getUser·p0.9999: 13.998 ms/op
                 getUser·p1.00:   15.548 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  7.776 ms/op
                 getUser·p0.9999: 11.420 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379935
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 187399 
    [ 2.500,  3.750) = 187649 
    [ 3.750,  5.000) = 3725 
    [ 5.000,  6.250) = 657 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     15.345 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.674 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 10.748 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  10.128 ms/op
                 listUser·p0.9999: 13.095 ms/op
                 listUser·p1.00:   13.681 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.796 ms/op
                 listUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317758
  mean =      3.018 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 88927 
    [ 2.500,  3.750) = 189857 
    [ 3.750,  5.000) = 31857 
    [ 5.000,  6.250) = 5674 
    [ 6.250,  7.500) = 658 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 194 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     12.046 ms/op
     p(99.9990) =     13.489 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.475 ± 1.026  ops/ms
ClientPb.existUser                       thrpt       3  13.095 ± 1.722  ops/ms
ClientPb.getUser                         thrpt       3  12.594 ± 1.163  ops/ms
ClientPb.listUser                        thrpt       3  10.643 ± 0.850  ops/ms
ClientPb.createUser                       avgt       3   2.556 ± 0.332   ms/op
ClientPb.existUser                        avgt       3   2.464 ± 0.074   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.338   ms/op
ClientPb.listUser                         avgt       3   3.053 ± 0.118   ms/op
ClientPb.createUser                     sample  374038   2.564 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.965           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.664           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  391994   2.446 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.990           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.111           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.694           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  379935   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.807           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.636           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.548           ms/op
ClientPb.listUser                       sample  317758   3.018 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.788           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.046           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.681           ms/op
