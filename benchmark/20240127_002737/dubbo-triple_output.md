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
# Warmup Iteration   1: 5.019 ops/ms
# Warmup Iteration   2: 11.849 ops/ms
# Warmup Iteration   3: 12.198 ops/ms
Iteration   1: 12.476 ops/ms
Iteration   2: 12.510 ops/ms
Iteration   3: 12.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.497 ±(99.9%) 0.335 ops/ms [Average]
  (min, avg, max) = (12.476, 12.497, 12.510), stdev = 0.018
  CI (99.9%): [12.161, 12.832] (assumes normal distribution)


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
# Warmup Iteration   1: 8.392 ops/ms
# Warmup Iteration   2: 13.135 ops/ms
# Warmup Iteration   3: 13.084 ops/ms
Iteration   1: 13.068 ops/ms
Iteration   2: 13.158 ops/ms
Iteration   3: 13.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.163 ±(99.9%) 1.761 ops/ms [Average]
  (min, avg, max) = (13.068, 13.163, 13.261), stdev = 0.097
  CI (99.9%): [11.402, 14.923] (assumes normal distribution)


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
# Warmup Iteration   1: 7.767 ops/ms
# Warmup Iteration   2: 12.248 ops/ms
# Warmup Iteration   3: 12.690 ops/ms
Iteration   1: 12.705 ops/ms
Iteration   2: 12.856 ops/ms
Iteration   3: 12.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.810 ±(99.9%) 1.668 ops/ms [Average]
  (min, avg, max) = (12.705, 12.810, 12.869), stdev = 0.091
  CI (99.9%): [11.142, 14.478] (assumes normal distribution)


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
# Warmup Iteration   1: 6.700 ops/ms
# Warmup Iteration   2: 10.427 ops/ms
# Warmup Iteration   3: 10.483 ops/ms
Iteration   1: 10.623 ops/ms
Iteration   2: 10.687 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.631 ±(99.9%) 0.957 ops/ms [Average]
  (min, avg, max) = (10.583, 10.631, 10.687), stdev = 0.052
  CI (99.9%): [9.674, 11.589] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.609 ±(99.9%) 0.004 ms/op
Iteration   2: 2.584 ±(99.9%) 0.004 ms/op
Iteration   3: 2.566 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.587 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.566, 2.587, 2.609), stdev = 0.022
  CI (99.9%): [2.189, 2.984] (assumes normal distribution)


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.004 ms/op
Iteration   1: 2.523 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.523 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (2.513, 2.523, 2.535), stdev = 0.011
  CI (99.9%): [2.321, 2.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
Iteration   1: 2.529 ±(99.9%) 0.004 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.542 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (2.529, 2.542, 2.560), stdev = 0.016
  CI (99.9%): [2.249, 2.835] (assumes normal distribution)


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.005 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
Iteration   2: 3.067 ±(99.9%) 0.004 ms/op
Iteration   3: 3.035 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.478 ms/op [Average]
  (min, avg, max) = (3.016, 3.039, 3.067), stdev = 0.026
  CI (99.9%): [2.562, 3.517] (assumes normal distribution)


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.717 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 13.165 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.506 ms/op
                 createUser·p0.999:  10.339 ms/op
                 createUser·p0.9999: 11.993 ms/op
                 createUser·p1.00:   12.698 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.968 ms/op
                 createUser·p0.999:  8.531 ms/op
                 createUser·p0.9999: 10.908 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376181
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 179118 
    [ 2.500,  3.750) = 193545 
    [ 3.750,  5.000) = 2682 
    [ 5.000,  6.250) = 354 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.628 ms/op
     p(99.9900) =     12.933 ms/op
     p(99.9990) =     16.415 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
Iteration   1: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.750 ms/op
                 existUser·p0.9999: 14.008 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  8.630 ms/op
                 existUser·p0.9999: 13.728 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  7.053 ms/op
                 existUser·p0.9999: 12.141 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394586
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 197301 
    [ 2.500,  3.750) = 194300 
    [ 3.750,  5.000) = 2337 
    [ 5.000,  6.250) = 197 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      7.857 ms/op
     p(99.9900) =     13.673 ms/op
     p(99.9990) =     14.658 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  11.048 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.513 ms/op
                 getUser·p0.9999: 13.289 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.072 ms/op
                 getUser·p0.999:  9.257 ms/op
                 getUser·p0.9999: 11.600 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375377
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 182616 
    [ 2.500,  3.750) = 186992 
    [ 3.750,  5.000) = 4439 
    [ 5.000,  6.250) = 819 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      7.820 ms/op
     p(99.9900) =     13.410 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 4.625 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.009 ms/op
Iteration   1: 3.081 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 12.128 ms/op
                 listUser·p1.00:   12.485 ms/op

Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 11.096 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   3: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 11.200 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311448
  mean =      3.080 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 80201 
    [ 2.500,  3.750) = 187795 
    [ 3.750,  5.000) = 35317 
    [ 5.000,  6.250) = 6486 
    [ 6.250,  7.500) = 849 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 196 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     11.775 ms/op
     p(99.9990) =     12.466 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.497 ± 0.335  ops/ms
ClientPb.existUser                       thrpt       3  13.163 ± 1.761  ops/ms
ClientPb.getUser                         thrpt       3  12.810 ± 1.668  ops/ms
ClientPb.listUser                        thrpt       3  10.631 ± 0.957  ops/ms
ClientPb.createUser                       avgt       3   2.587 ± 0.398   ms/op
ClientPb.existUser                        avgt       3   2.523 ± 0.202   ms/op
ClientPb.getUser                          avgt       3   2.542 ± 0.293   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.478   ms/op
ClientPb.createUser                     sample  376181   2.549 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.877           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.628           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.933           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.776           ms/op
ClientPb.existUser                      sample  394586   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.589           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.857           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.673           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.024           ms/op
ClientPb.getUser                        sample  375377   2.555 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.690           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.820           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.410           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.893           ms/op
ClientPb.listUser                       sample  311448   3.080 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.954           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.748           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.775           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.763           ms/op
