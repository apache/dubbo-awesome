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
# Warmup Iteration   1: 5.223 ops/ms
# Warmup Iteration   2: 12.034 ops/ms
# Warmup Iteration   3: 12.434 ops/ms
Iteration   1: 12.504 ops/ms
Iteration   2: 12.405 ops/ms
Iteration   3: 12.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.525 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (12.405, 12.525, 12.666), stdev = 0.132
  CI (99.9%): [10.124, 14.926] (assumes normal distribution)


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
# Warmup Iteration   1: 8.608 ops/ms
# Warmup Iteration   2: 12.988 ops/ms
# Warmup Iteration   3: 13.314 ops/ms
Iteration   1: 13.259 ops/ms
Iteration   2: 13.291 ops/ms
Iteration   3: 13.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.287 ±(99.9%) 0.484 ops/ms [Average]
  (min, avg, max) = (13.259, 13.287, 13.311), stdev = 0.027
  CI (99.9%): [12.803, 13.771] (assumes normal distribution)


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
# Warmup Iteration   1: 7.848 ops/ms
# Warmup Iteration   2: 12.670 ops/ms
# Warmup Iteration   3: 12.974 ops/ms
Iteration   1: 12.806 ops/ms
Iteration   2: 12.943 ops/ms
Iteration   3: 13.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.919 ±(99.9%) 1.887 ops/ms [Average]
  (min, avg, max) = (12.806, 12.919, 13.009), stdev = 0.103
  CI (99.9%): [11.033, 14.806] (assumes normal distribution)


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
# Warmup Iteration   1: 6.745 ops/ms
# Warmup Iteration   2: 10.480 ops/ms
# Warmup Iteration   3: 10.584 ops/ms
Iteration   1: 10.724 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.685 ±(99.9%) 1.354 ops/ms [Average]
  (min, avg, max) = (10.599, 10.685, 10.732), stdev = 0.074
  CI (99.9%): [9.331, 12.039] (assumes normal distribution)


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.480 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (2.459, 2.480, 2.512), stdev = 0.028
  CI (99.9%): [1.972, 2.988] (assumes normal distribution)


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
# Warmup Iteration   1: 3.632 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.404 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.397 ±(99.9%) 0.004 ms/op
Iteration   1: 2.421 ±(99.9%) 0.003 ms/op
Iteration   2: 2.392 ±(99.9%) 0.003 ms/op
Iteration   3: 2.406 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.406 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.392, 2.406, 2.421), stdev = 0.015
  CI (99.9%): [2.139, 2.674] (assumes normal distribution)


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.003 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (2.465, 2.484, 2.501), stdev = 0.019
  CI (99.9%): [2.145, 2.823] (assumes normal distribution)


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.005 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 3.016 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.993, 3.008, 3.016), stdev = 0.013
  CI (99.9%): [2.771, 3.245] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  8.155 ms/op
                 createUser·p0.9999: 13.550 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  5.583 ms/op
                 createUser·p0.9999: 11.513 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.721 ms/op
                 createUser·p0.9999: 10.715 ms/op
                 createUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389199
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 190977 
    [ 2.500,  3.750) = 194320 
    [ 3.750,  5.000) = 2817 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      8.231 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     13.788 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.384 ±(99.9%) 0.005 ms/op
Iteration   1: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  4.847 ms/op
                 existUser·p0.9999: 13.806 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 13.135 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   3: 2.390 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.409 ms/op
                 existUser·p0.9999: 10.398 ms/op
                 existUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399881
  mean =      2.398 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 204314 
    [ 2.500,  3.750) = 191915 
    [ 3.750,  5.000) = 2560 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      7.786 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.006 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  5.955 ms/op
                 getUser·p0.9999: 13.730 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  7.777 ms/op
                 getUser·p0.9999: 12.325 ms/op
                 getUser·p1.00:   13.091 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  6.723 ms/op
                 getUser·p0.9999: 14.169 ms/op
                 getUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387518
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 193155 
    [ 2.500,  3.750) = 189931 
    [ 3.750,  5.000) = 3513 
    [ 5.000,  6.250) = 448 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.447 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.708 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
Iteration   1: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 11.888 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.392 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.600 ms/op
                 listUser·p1.00:   11.567 ms/op

Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.132 ms/op
                 listUser·p0.9999: 10.964 ms/op
                 listUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322932
  mean =      2.970 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 98948 
    [ 2.500,  3.750) = 186402 
    [ 3.750,  5.000) = 30486 
    [ 5.000,  6.250) = 5590 
    [ 6.250,  7.500) = 694 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 230 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.174 ms/op
     p(99.9990) =     12.268 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.525 ± 2.401  ops/ms
ClientPb.existUser                       thrpt       3  13.287 ± 0.484  ops/ms
ClientPb.getUser                         thrpt       3  12.919 ± 1.887  ops/ms
ClientPb.listUser                        thrpt       3  10.685 ± 1.354  ops/ms
ClientPb.createUser                       avgt       3   2.480 ± 0.508   ms/op
ClientPb.existUser                        avgt       3   2.406 ± 0.268   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.339   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.237   ms/op
ClientPb.createUser                     sample  389199   2.464 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.502           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.231           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.959           ms/op
ClientPb.existUser                      sample  399881   2.398 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.974           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.908           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.786           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.222           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.631           ms/op
ClientPb.getUser                        sample  387518   2.475 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.970           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.963           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.648           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  322932   2.970 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.864           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.403           ms/op
