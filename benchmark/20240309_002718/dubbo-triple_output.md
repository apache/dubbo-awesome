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
# Warmup Iteration   1: 4.724 ops/ms
# Warmup Iteration   2: 12.478 ops/ms
# Warmup Iteration   3: 12.719 ops/ms
Iteration   1: 12.866 ops/ms
Iteration   2: 13.151 ops/ms
Iteration   3: 13.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.032 ±(99.9%) 2.705 ops/ms [Average]
  (min, avg, max) = (12.866, 13.032, 13.151), stdev = 0.148
  CI (99.9%): [10.327, 15.738] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.097 ops/ms
# Warmup Iteration   2: 13.227 ops/ms
# Warmup Iteration   3: 13.331 ops/ms
Iteration   1: 13.414 ops/ms
Iteration   2: 13.360 ops/ms
Iteration   3: 13.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.385 ±(99.9%) 0.499 ops/ms [Average]
  (min, avg, max) = (13.360, 13.385, 13.414), stdev = 0.027
  CI (99.9%): [12.886, 13.884] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.616 ops/ms
# Warmup Iteration   2: 12.844 ops/ms
# Warmup Iteration   3: 12.836 ops/ms
Iteration   1: 13.041 ops/ms
Iteration   2: 13.034 ops/ms
Iteration   3: 13.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.042 ±(99.9%) 0.170 ops/ms [Average]
  (min, avg, max) = (13.034, 13.042, 13.052), stdev = 0.009
  CI (99.9%): [12.872, 13.213] (assumes normal distribution)


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
# Warmup Iteration   1: 6.745 ops/ms
# Warmup Iteration   2: 10.686 ops/ms
# Warmup Iteration   3: 10.729 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.600 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.660 ±(99.9%) 0.990 ops/ms [Average]
  (min, avg, max) = (10.600, 10.660, 10.706), stdev = 0.054
  CI (99.9%): [9.670, 11.650] (assumes normal distribution)


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
Iteration   3: 2.490 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.483 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (2.462, 2.483, 2.495), stdev = 0.018
  CI (99.9%): [2.156, 2.809] (assumes normal distribution)


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.004 ms/op
Iteration   1: 2.404 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
Iteration   3: 2.417 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.416 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.404, 2.416, 2.426), stdev = 0.011
  CI (99.9%): [2.210, 2.622] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.467, 2.477, 2.487), stdev = 0.010
  CI (99.9%): [2.288, 2.666] (assumes normal distribution)


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
# Warmup Iteration   1: 4.667 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.004 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
Iteration   2: 3.018 ±(99.9%) 0.004 ms/op
Iteration   3: 3.052 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.038 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (3.018, 3.038, 3.052), stdev = 0.018
  CI (99.9%): [2.715, 3.362] (assumes normal distribution)


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
# Warmup Iteration   1: 4.334 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  12.386 ms/op
                 createUser·p0.9999: 14.373 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  9.437 ms/op
                 createUser·p0.9999: 12.031 ms/op
                 createUser·p1.00:   12.354 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  8.797 ms/op
                 createUser·p0.9999: 12.112 ms/op
                 createUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377634
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 181153 
    [ 2.500,  3.750) = 192450 
    [ 3.750,  5.000) = 3197 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      9.591 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  7.070 ms/op
                 existUser·p0.9999: 14.072 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.679 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.706 ms/op
                 existUser·p0.999:  9.131 ms/op
                 existUser·p0.9999: 12.226 ms/op
                 existUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387212
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 192873 
    [ 2.500,  3.750) = 191114 
    [ 3.750,  5.000) = 2422 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      7.353 ms/op
     p(99.9900) =     13.844 ms/op
     p(99.9990) =     14.666 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  11.822 ms/op
                 getUser·p0.9999: 14.157 ms/op
                 getUser·p1.00:   15.909 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  10.158 ms/op
                 getUser·p0.9999: 14.061 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.730 ms/op
                 getUser·p0.9999: 12.224 ms/op
                 getUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384674
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 190756 
    [ 2.500,  3.750) = 189462 
    [ 3.750,  5.000) = 3534 
    [ 5.000,  6.250) = 435 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      7.344 ms/op
     p(99.9900) =     13.846 ms/op
     p(99.9990) =     15.659 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 4.859 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
Iteration   1: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.676 ms/op
                 listUser·p0.9999: 12.091 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.769 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.997 ms/op
                 listUser·p0.9999: 11.670 ms/op
                 listUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319851
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 94857 
    [ 2.500,  3.750) = 186529 
    [ 3.750,  5.000) = 31302 
    [ 5.000,  6.250) = 5674 
    [ 6.250,  7.500) = 674 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 205 
    [10.000, 11.250) = 204 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     11.829 ms/op
     p(99.9990) =     12.557 ms/op
     p(99.9999) =     12.796 ms/op
    p(100.0000) =     12.796 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.032 ± 2.705  ops/ms
ClientPb.existUser                       thrpt       3  13.385 ± 0.499  ops/ms
ClientPb.getUser                         thrpt       3  13.042 ± 0.170  ops/ms
ClientPb.listUser                        thrpt       3  10.660 ± 0.990  ops/ms
ClientPb.createUser                       avgt       3   2.483 ± 0.327   ms/op
ClientPb.existUser                        avgt       3   2.416 ± 0.206   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.189   ms/op
ClientPb.listUser                         avgt       3   3.038 ± 0.324   ms/op
ClientPb.createUser                     sample  377634   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.935           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.591           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.828           ms/op
ClientPb.existUser                      sample  387212   2.477 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.853           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.353           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.844           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.909           ms/op
ClientPb.getUser                        sample  384674   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.649           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.344           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.846           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.909           ms/op
ClientPb.listUser                       sample  319851   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.829           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.796           ms/op
