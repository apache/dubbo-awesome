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
# Warmup Iteration   1: 5.079 ops/ms
# Warmup Iteration   2: 12.047 ops/ms
# Warmup Iteration   3: 12.058 ops/ms
Iteration   1: 12.414 ops/ms
Iteration   2: 12.422 ops/ms
Iteration   3: 12.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.408 ±(99.9%) 0.347 ops/ms [Average]
  (min, avg, max) = (12.386, 12.408, 12.422), stdev = 0.019
  CI (99.9%): [12.060, 12.755] (assumes normal distribution)


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
# Warmup Iteration   1: 8.148 ops/ms
# Warmup Iteration   2: 12.791 ops/ms
# Warmup Iteration   3: 13.025 ops/ms
Iteration   1: 12.979 ops/ms
Iteration   2: 13.021 ops/ms
Iteration   3: 12.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.984 ±(99.9%) 0.628 ops/ms [Average]
  (min, avg, max) = (12.953, 12.984, 13.021), stdev = 0.034
  CI (99.9%): [12.356, 13.613] (assumes normal distribution)


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
# Warmup Iteration   1: 7.816 ops/ms
# Warmup Iteration   2: 12.437 ops/ms
# Warmup Iteration   3: 12.613 ops/ms
Iteration   1: 12.599 ops/ms
Iteration   2: 12.494 ops/ms
Iteration   3: 12.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.589 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (12.494, 12.589, 12.673), stdev = 0.090
  CI (99.9%): [10.948, 14.230] (assumes normal distribution)


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
# Warmup Iteration   1: 6.780 ops/ms
# Warmup Iteration   2: 10.344 ops/ms
# Warmup Iteration   3: 10.525 ops/ms
Iteration   1: 10.566 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 10.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.480 ±(99.9%) 1.496 ops/ms [Average]
  (min, avg, max) = (10.403, 10.480, 10.566), stdev = 0.082
  CI (99.9%): [8.984, 11.977] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.544 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.003 ms/op
Iteration   3: 2.550 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.544 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (2.538, 2.544, 2.550), stdev = 0.006
  CI (99.9%): [2.440, 2.649] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.421 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.405 ±(99.9%) 0.003 ms/op
Iteration   1: 2.417 ±(99.9%) 0.004 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.442 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.417, 2.428, 2.442), stdev = 0.013
  CI (99.9%): [2.191, 2.665] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.129 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.003 ms/op
Iteration   2: 2.498 ±(99.9%) 0.003 ms/op
Iteration   3: 2.524 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.511 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.498, 2.511, 2.524), stdev = 0.013
  CI (99.9%): [2.274, 2.748] (assumes normal distribution)


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
# Warmup Iteration   1: 4.680 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.005 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
Iteration   3: 3.038 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.054 ms/op [Average]
  (min, avg, max) = (3.032, 3.035, 3.038), stdev = 0.003
  CI (99.9%): [2.981, 3.090] (assumes normal distribution)


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.689 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.574 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  11.905 ms/op
                 createUser·p0.9999: 14.516 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.584 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  10.309 ms/op
                 createUser·p0.9999: 12.069 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  8.312 ms/op
                 createUser·p0.9999: 11.114 ms/op
                 createUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373287
  mean =      2.569 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 175514 
    [ 2.500,  3.750) = 192138 
    [ 3.750,  5.000) = 4386 
    [ 5.000,  6.250) = 599 
    [ 6.250,  7.500) = 189 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      8.499 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.665 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  5.546 ms/op
                 existUser·p0.9999: 13.597 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.466 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 13.467 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  7.256 ms/op
                 existUser·p0.9999: 11.846 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391567
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 192073 
    [ 2.500,  3.750) = 196623 
    [ 3.750,  5.000) = 2213 
    [ 5.000,  6.250) = 217 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      6.144 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.101 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 13.540 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  9.175 ms/op
                 getUser·p0.9999: 12.864 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   3: 2.555 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  8.525 ms/op
                 getUser·p0.9999: 11.526 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375334
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 181791 
    [ 2.500,  3.750) = 186529 
    [ 3.750,  5.000) = 5445 
    [ 5.000,  6.250) = 1045 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      4.331 ms/op
     p(99.9000) =      8.656 ms/op
     p(99.9900) =     13.155 ms/op
     p(99.9990) =     13.799 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 4.705 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.381 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 10.131 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 12.337 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 10.131 ms/op
                 listUser·p1.00:   10.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319936
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 92982 
    [ 2.500,  3.750) = 189204 
    [ 3.750,  5.000) = 31406 
    [ 5.000,  6.250) = 5055 
    [ 6.250,  7.500) = 512 
    [ 7.500,  8.750) = 255 
    [ 8.750, 10.000) = 268 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     11.567 ms/op
     p(99.9990) =     12.596 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.408 ± 0.347  ops/ms
ClientPb.existUser                       thrpt       3  12.984 ± 0.628  ops/ms
ClientPb.getUser                         thrpt       3  12.589 ± 1.641  ops/ms
ClientPb.listUser                        thrpt       3  10.480 ± 1.496  ops/ms
ClientPb.createUser                       avgt       3   2.544 ± 0.105   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.237   ms/op
ClientPb.getUser                          avgt       3   2.511 ± 0.237   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.054   ms/op
ClientPb.createUser                     sample  373287   2.569 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.910           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.499           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.615           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.762           ms/op
ClientPb.existUser                      sample  391567   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.466           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.144           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  375334   2.556 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.891           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.331           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.656           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.155           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.041           ms/op
ClientPb.listUser                       sample  319936   2.998 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.809           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.962           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.567           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
