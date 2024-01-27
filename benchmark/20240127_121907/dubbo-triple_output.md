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
# Warmup Iteration   1: 4.648 ops/ms
# Warmup Iteration   2: 12.104 ops/ms
# Warmup Iteration   3: 12.413 ops/ms
Iteration   1: 12.665 ops/ms
Iteration   2: 12.615 ops/ms
Iteration   3: 12.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.712 ±(99.9%) 2.298 ops/ms [Average]
  (min, avg, max) = (12.615, 12.712, 12.854), stdev = 0.126
  CI (99.9%): [10.414, 15.010] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.276 ops/ms
# Warmup Iteration   2: 13.350 ops/ms
# Warmup Iteration   3: 13.239 ops/ms
Iteration   1: 13.414 ops/ms
Iteration   2: 13.199 ops/ms
Iteration   3: 13.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.276 ±(99.9%) 2.189 ops/ms [Average]
  (min, avg, max) = (13.199, 13.276, 13.414), stdev = 0.120
  CI (99.9%): [11.087, 15.465] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.459 ops/ms
# Warmup Iteration   2: 12.753 ops/ms
# Warmup Iteration   3: 12.821 ops/ms
Iteration   1: 12.706 ops/ms
Iteration   2: 13.010 ops/ms
Iteration   3: 12.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.869 ±(99.9%) 2.798 ops/ms [Average]
  (min, avg, max) = (12.706, 12.869, 13.010), stdev = 0.153
  CI (99.9%): [10.072, 15.667] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.659 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.651 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.636 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (10.590, 10.636, 10.696), stdev = 0.054
  CI (99.9%): [9.648, 11.625] (assumes normal distribution)


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.499 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.482, 2.499, 2.508), stdev = 0.014
  CI (99.9%): [2.234, 2.763] (assumes normal distribution)


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
# Warmup Iteration   1: 3.621 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.417 ±(99.9%) 0.003 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.417, 2.432, 2.445), stdev = 0.014
  CI (99.9%): [2.176, 2.689] (assumes normal distribution)


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (2.470, 2.492, 2.522), stdev = 0.027
  CI (99.9%): [2.008, 2.977] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.006 ms/op
Iteration   2: 2.994 ±(99.9%) 0.005 ms/op
Iteration   3: 2.964 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.976 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.964, 2.976, 2.994), stdev = 0.017
  CI (99.9%): [2.674, 3.277] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.007 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  8.570 ms/op
                 createUser·p0.9999: 13.915 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  8.268 ms/op
                 createUser·p0.9999: 11.898 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  8.364 ms/op
                 createUser·p0.9999: 10.633 ms/op
                 createUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384360
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 189111 
    [ 2.500,  3.750) = 190934 
    [ 3.750,  5.000) = 3490 
    [ 5.000,  6.250) = 360 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.355 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     14.180 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  8.501 ms/op
                 existUser·p0.9999: 13.068 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  6.784 ms/op
                 existUser·p0.9999: 13.647 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  5.980 ms/op
                 existUser·p0.9999: 11.384 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392261
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 196499 
    [ 2.500,  3.750) = 192739 
    [ 3.750,  5.000) = 2263 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      6.132 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     13.836 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  7.469 ms/op
                 getUser·p0.9999: 14.238 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  9.596 ms/op
                 getUser·p0.9999: 21.214 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  7.325 ms/op
                 getUser·p0.9999: 10.117 ms/op
                 getUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382677
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189997 
    [ 2.500,  5.000) = 191077 
    [ 5.000,  7.500) = 1219 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      8.094 ms/op
     p(99.9900) =     14.348 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.663 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.651 ms/op
                 listUser·p0.9999: 10.650 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  10.033 ms/op
                 listUser·p0.9999: 11.411 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.777 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.543 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 10.845 ms/op
                 listUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320835
  mean =      2.990 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 97240 
    [ 2.500,  3.750) = 185965 
    [ 3.750,  5.000) = 30788 
    [ 5.000,  6.250) = 5475 
    [ 6.250,  7.500) = 584 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 182 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     11.205 ms/op
     p(99.9990) =     11.865 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.712 ± 2.298  ops/ms
ClientPb.existUser                       thrpt       3  13.276 ± 2.189  ops/ms
ClientPb.getUser                         thrpt       3  12.869 ± 2.798  ops/ms
ClientPb.listUser                        thrpt       3  10.636 ± 0.988  ops/ms
ClientPb.createUser                       avgt       3   2.499 ± 0.265   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.256   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.484   ms/op
ClientPb.listUser                         avgt       3   2.976 ± 0.301   ms/op
ClientPb.createUser                     sample  384360   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.872           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.355           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.058           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.270           ms/op
ClientPb.existUser                      sample  392261   2.445 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.834           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.132           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.845           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.156           ms/op
ClientPb.getUser                        sample  382677   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.814           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.094           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.348           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.791           ms/op
ClientPb.listUser                       sample  320835   2.990 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.777           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.205           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.075           ms/op
