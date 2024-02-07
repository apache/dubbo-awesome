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
# Warmup Iteration   1: 4.948 ops/ms
# Warmup Iteration   2: 12.090 ops/ms
# Warmup Iteration   3: 12.278 ops/ms
Iteration   1: 12.618 ops/ms
Iteration   2: 12.710 ops/ms
Iteration   3: 12.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.714 ±(99.9%) 1.794 ops/ms [Average]
  (min, avg, max) = (12.618, 12.714, 12.815), stdev = 0.098
  CI (99.9%): [10.920, 14.508] (assumes normal distribution)


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
# Warmup Iteration   1: 8.634 ops/ms
# Warmup Iteration   2: 13.259 ops/ms
# Warmup Iteration   3: 13.179 ops/ms
Iteration   1: 13.228 ops/ms
Iteration   2: 13.091 ops/ms
Iteration   3: 12.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.103 ±(99.9%) 2.183 ops/ms [Average]
  (min, avg, max) = (12.989, 13.103, 13.228), stdev = 0.120
  CI (99.9%): [10.920, 15.286] (assumes normal distribution)


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
# Warmup Iteration   1: 7.978 ops/ms
# Warmup Iteration   2: 12.770 ops/ms
# Warmup Iteration   3: 13.138 ops/ms
Iteration   1: 13.145 ops/ms
Iteration   2: 13.020 ops/ms
Iteration   3: 13.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.097 ±(99.9%) 1.223 ops/ms [Average]
  (min, avg, max) = (13.020, 13.097, 13.145), stdev = 0.067
  CI (99.9%): [11.874, 14.320] (assumes normal distribution)


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
# Warmup Iteration   1: 7.000 ops/ms
# Warmup Iteration   2: 10.398 ops/ms
# Warmup Iteration   3: 10.565 ops/ms
Iteration   1: 10.604 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.639 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (10.604, 10.639, 10.691), stdev = 0.045
  CI (99.9%): [9.811, 11.468] (assumes normal distribution)


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.003 ms/op
Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.498, 2.504, 2.514), stdev = 0.008
  CI (99.9%): [2.353, 2.656] (assumes normal distribution)


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
# Warmup Iteration   1: 3.598 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.054 ms/op [Average]
  (min, avg, max) = (2.470, 2.473, 2.475), stdev = 0.003
  CI (99.9%): [2.419, 2.527] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.429 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.440 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.439 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (2.429, 2.439, 2.447), stdev = 0.009
  CI (99.9%): [2.271, 2.606] (assumes normal distribution)


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.004 ms/op
Iteration   1: 3.034 ±(99.9%) 0.005 ms/op
Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
Iteration   3: 2.996 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.003 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (2.979, 3.003, 3.034), stdev = 0.028
  CI (99.9%): [2.490, 3.516] (assumes normal distribution)


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
# Warmup Iteration   1: 4.131 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  5.839 ms/op
                 createUser·p0.9999: 13.617 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  7.032 ms/op
                 createUser·p0.9999: 11.846 ms/op
                 createUser·p1.00:   12.026 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  9.224 ms/op
                 createUser·p0.9999: 10.387 ms/op
                 createUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385701
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 185502 
    [ 2.500,  3.750) = 195780 
    [ 3.750,  5.000) = 3546 
    [ 5.000,  6.250) = 407 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 129 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     12.934 ms/op
     p(99.9990) =     13.716 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  7.075 ms/op
                 existUser·p0.9999: 13.769 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   2: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.366 ms/op
                 existUser·p0.999:  7.165 ms/op
                 existUser·p0.9999: 13.935 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.393 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  5.942 ms/op
                 existUser·p0.9999: 11.239 ms/op
                 existUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397390
  mean =      2.413 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 198211 
    [ 2.500,  3.750) = 196464 
    [ 3.750,  5.000) = 1953 
    [ 5.000,  6.250) = 299 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =      6.762 ms/op
     p(99.9900) =     13.509 ms/op
     p(99.9990) =     14.206 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.746 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  6.020 ms/op
                 getUser·p0.9999: 13.040 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.073 ms/op
                 getUser·p0.9999: 12.420 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  6.257 ms/op
                 getUser·p0.9999: 10.371 ms/op
                 getUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391669
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 197465 
    [ 2.500,  3.750) = 189751 
    [ 3.750,  5.000) = 3449 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.815 ms/op
     p(99.9000) =      6.406 ms/op
     p(99.9900) =     12.758 ms/op
     p(99.9990) =     13.619 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
Iteration   1: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 10.812 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.409 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.446 ms/op
                 listUser·p0.999:  8.794 ms/op
                 listUser·p0.9999: 10.843 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320103
  mean =      2.996 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 93104 
    [ 2.500,  3.750) = 189703 
    [ 3.750,  5.000) = 30793 
    [ 5.000,  6.250) = 5191 
    [ 6.250,  7.500) = 494 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     10.977 ms/op
     p(99.9990) =     11.780 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.714 ± 1.794  ops/ms
ClientPb.existUser                       thrpt       3  13.103 ± 2.183  ops/ms
ClientPb.getUser                         thrpt       3  13.097 ± 1.223  ops/ms
ClientPb.listUser                        thrpt       3  10.639 ± 0.828  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.152   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.054   ms/op
ClientPb.getUser                          avgt       3   2.439 ± 0.167   ms/op
ClientPb.listUser                         avgt       3   3.003 ± 0.513   ms/op
ClientPb.createUser                     sample  385701   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.853           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.208           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.934           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.992           ms/op
ClientPb.existUser                      sample  397390   2.413 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.863           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.762           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.509           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.336           ms/op
ClientPb.getUser                        sample  391669   2.449 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.866           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.982           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.815           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.406           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.758           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.894           ms/op
ClientPb.listUser                       sample  320103   2.996 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.840           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.009           ms/op
