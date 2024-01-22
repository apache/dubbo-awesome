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
# Warmup Iteration   1: 5.051 ops/ms
# Warmup Iteration   2: 12.125 ops/ms
# Warmup Iteration   3: 12.422 ops/ms
Iteration   1: 12.575 ops/ms
Iteration   2: 12.530 ops/ms
Iteration   3: 12.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.572 ±(99.9%) 0.736 ops/ms [Average]
  (min, avg, max) = (12.530, 12.572, 12.611), stdev = 0.040
  CI (99.9%): [11.836, 13.308] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.096 ops/ms
# Warmup Iteration   2: 13.157 ops/ms
# Warmup Iteration   3: 13.126 ops/ms
Iteration   1: 13.083 ops/ms
Iteration   2: 12.764 ops/ms
Iteration   3: 13.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.961 ±(99.9%) 3.147 ops/ms [Average]
  (min, avg, max) = (12.764, 12.961, 13.083), stdev = 0.172
  CI (99.9%): [9.815, 16.108] (assumes normal distribution)


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
# Warmup Iteration   1: 7.930 ops/ms
# Warmup Iteration   2: 12.633 ops/ms
# Warmup Iteration   3: 12.894 ops/ms
Iteration   1: 12.910 ops/ms
Iteration   2: 12.971 ops/ms
Iteration   3: 13.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.967 ±(99.9%) 1.002 ops/ms [Average]
  (min, avg, max) = (12.910, 12.967, 13.020), stdev = 0.055
  CI (99.9%): [11.965, 13.970] (assumes normal distribution)


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
# Warmup Iteration   1: 6.784 ops/ms
# Warmup Iteration   2: 10.577 ops/ms
# Warmup Iteration   3: 10.732 ops/ms
Iteration   1: 10.843 ops/ms
Iteration   2: 10.715 ops/ms
Iteration   3: 10.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.750 ±(99.9%) 1.491 ops/ms [Average]
  (min, avg, max) = (10.691, 10.750, 10.843), stdev = 0.082
  CI (99.9%): [9.259, 12.241] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.004 ms/op
Iteration   1: 2.624 ±(99.9%) 0.005 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.577 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.594 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (2.577, 2.594, 2.624), stdev = 0.027
  CI (99.9%): [2.108, 3.079] (assumes normal distribution)


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.431, 2.442, 2.447), stdev = 0.009
  CI (99.9%): [2.280, 2.604] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
Iteration   2: 2.488 ±(99.9%) 0.003 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.511 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (2.488, 2.511, 2.538), stdev = 0.025
  CI (99.9%): [2.054, 2.968] (assumes normal distribution)


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
# Warmup Iteration   1: 4.873 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
Iteration   3: 3.030 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.022 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (3.015, 3.022, 3.030), stdev = 0.008
  CI (99.9%): [2.885, 3.159] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.568 ms/op
                 createUser·p0.999:  6.369 ms/op
                 createUser·p0.9999: 13.746 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.466 ms/op
                 createUser·p0.9999: 11.850 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  8.799 ms/op
                 createUser·p0.9999: 11.507 ms/op
                 createUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383585
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 187409 
    [ 2.500,  3.750) = 192453 
    [ 3.750,  5.000) = 2832 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.724 ms/op
     p(99.9000) =      8.779 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.371 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  6.314 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  6.101 ms/op
                 existUser·p0.9999: 11.960 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.177 ms/op
                 existUser·p0.9999: 12.159 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390157
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 192956 
    [ 2.500,  3.750) = 192947 
    [ 3.750,  5.000) = 3216 
    [ 5.000,  6.250) = 626 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.166 ms/op
     p(99.9900) =     13.172 ms/op
     p(99.9990) =     13.781 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  9.864 ms/op
                 getUser·p0.9999: 13.667 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  9.825 ms/op
                 getUser·p0.9999: 14.590 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.802 ms/op
                 getUser·p0.999:  7.915 ms/op
                 getUser·p0.9999: 10.407 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383479
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 190453 
    [ 2.500,  3.750) = 188268 
    [ 3.750,  5.000) = 3500 
    [ 5.000,  6.250) = 780 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      7.918 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     15.387 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   2: 3.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
Iteration   1: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 11.433 ms/op
                 listUser·p1.00:   13.976 ms/op

Iteration   2: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.608 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 11.527 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.311 ms/op
                 listUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319675
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 94123 
    [ 2.500,  3.750) = 187147 
    [ 3.750,  5.000) = 31230 
    [ 5.000,  6.250) = 5657 
    [ 6.250,  7.500) = 691 
    [ 7.500,  8.750) = 326 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     12.318 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.572 ± 0.736  ops/ms
ClientPb.existUser                       thrpt       3  12.961 ± 3.147  ops/ms
ClientPb.getUser                         thrpt       3  12.967 ± 1.002  ops/ms
ClientPb.listUser                        thrpt       3  10.750 ± 1.491  ops/ms
ClientPb.createUser                       avgt       3   2.594 ± 0.485   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.162   ms/op
ClientPb.getUser                          avgt       3   2.511 ± 0.457   ms/op
ClientPb.listUser                         avgt       3   3.022 ± 0.137   ms/op
ClientPb.createUser                     sample  383585   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.651           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.724           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.779           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.434           ms/op
ClientPb.existUser                      sample  390157   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.166           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.172           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.025           ms/op
ClientPb.getUser                        sample  383479   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.918           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.918           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.812           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.466           ms/op
ClientPb.listUser                       sample  319675   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.844           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.976           ms/op
