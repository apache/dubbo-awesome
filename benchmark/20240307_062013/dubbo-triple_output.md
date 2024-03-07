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
# Warmup Iteration   1: 4.427 ops/ms
# Warmup Iteration   2: 12.088 ops/ms
# Warmup Iteration   3: 12.541 ops/ms
Iteration   1: 12.827 ops/ms
Iteration   2: 12.860 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.845 ±(99.9%) 0.302 ops/ms [Average]
  (min, avg, max) = (12.827, 12.845, 12.860), stdev = 0.017
  CI (99.9%): [12.543, 13.147] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.278 ops/ms
# Warmup Iteration   2: 13.214 ops/ms
# Warmup Iteration   3: 13.332 ops/ms
Iteration   1: 13.394 ops/ms
Iteration   2: 13.530 ops/ms
Iteration   3: 13.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.386 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (13.234, 13.386, 13.530), stdev = 0.148
  CI (99.9%): [10.682, 16.089] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.210 ops/ms
# Warmup Iteration   2: 12.596 ops/ms
# Warmup Iteration   3: 13.079 ops/ms
Iteration   1: 13.168 ops/ms
Iteration   2: 13.247 ops/ms
Iteration   3: 12.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.126 ±(99.9%) 2.683 ops/ms [Average]
  (min, avg, max) = (12.962, 13.126, 13.247), stdev = 0.147
  CI (99.9%): [10.443, 15.808] (assumes normal distribution)


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
# Warmup Iteration   1: 6.498 ops/ms
# Warmup Iteration   2: 10.647 ops/ms
# Warmup Iteration   3: 10.799 ops/ms
Iteration   1: 10.908 ops/ms
Iteration   2: 10.755 ops/ms
Iteration   3: 10.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.817 ±(99.9%) 1.466 ops/ms [Average]
  (min, avg, max) = (10.755, 10.817, 10.908), stdev = 0.080
  CI (99.9%): [9.351, 12.283] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.407 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.444 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (2.407, 2.444, 2.471), stdev = 0.033
  CI (99.9%): [1.838, 3.050] (assumes normal distribution)


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.370 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.390 ±(99.9%) 0.004 ms/op
Iteration   1: 2.372 ±(99.9%) 0.004 ms/op
Iteration   2: 2.356 ±(99.9%) 0.003 ms/op
Iteration   3: 2.396 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.374 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (2.356, 2.374, 2.396), stdev = 0.020
  CI (99.9%): [2.005, 2.743] (assumes normal distribution)


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.004 ms/op
Iteration   1: 2.420 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
Iteration   3: 2.453 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.438 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (2.420, 2.438, 2.453), stdev = 0.017
  CI (99.9%): [2.130, 2.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
Iteration   3: 2.973 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.976 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (2.953, 2.976, 3.001), stdev = 0.024
  CI (99.9%): [2.540, 3.412] (assumes normal distribution)


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 13.604 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  10.130 ms/op
                 createUser·p0.9999: 12.108 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 11.354 ms/op
                 createUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380988
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 183800 
    [ 2.500,  3.750) = 193005 
    [ 3.750,  5.000) = 3104 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.806 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.096 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.383 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.776 ms/op
                 existUser·p0.999:  7.430 ms/op
                 existUser·p0.9999: 14.513 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.410 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  8.373 ms/op
                 existUser·p0.9999: 14.385 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  8.961 ms/op
                 existUser·p0.9999: 12.385 ms/op
                 existUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394744
  mean =      2.429 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 201486 
    [ 2.500,  3.750) = 189544 
    [ 3.750,  5.000) = 2615 
    [ 5.000,  6.250) = 517 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      8.370 ms/op
     p(99.9900) =     14.312 ms/op
     p(99.9990) =     15.251 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.504 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  11.674 ms/op
                 getUser·p0.9999: 14.090 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.308 ms/op
                 getUser·p0.9999: 22.558 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  9.120 ms/op
                 getUser·p0.9999: 11.911 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381744
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189614 
    [ 2.500,  5.000) = 190863 
    [ 5.000,  7.500) = 878 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      9.310 ms/op
     p(99.9900) =     14.259 ms/op
     p(99.9990) =     23.638 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.009 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.576 ms/op
                 listUser·p0.999:  9.828 ms/op
                 listUser·p0.9999: 11.010 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   2: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.495 ms/op
                 listUser·p0.9999: 11.231 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   3: 2.948 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.856 ms/op
                 listUser·p0.9999: 11.509 ms/op
                 listUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323085
  mean =      2.969 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 97801 
    [ 2.500,  3.750) = 188440 
    [ 3.750,  5.000) = 29733 
    [ 5.000,  6.250) = 5719 
    [ 6.250,  7.500) = 569 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 259 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.355 ms/op
     p(99.9990) =     12.699 ms/op
     p(99.9999) =     12.796 ms/op
    p(100.0000) =     12.796 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.845 ± 0.302  ops/ms
ClientPb.existUser                       thrpt       3  13.386 ± 2.704  ops/ms
ClientPb.getUser                         thrpt       3  13.126 ± 2.683  ops/ms
ClientPb.listUser                        thrpt       3  10.817 ± 1.466  ops/ms
ClientPb.createUser                       avgt       3   2.444 ± 0.606   ms/op
ClientPb.existUser                        avgt       3   2.374 ± 0.369   ms/op
ClientPb.getUser                          avgt       3   2.438 ± 0.308   ms/op
ClientPb.listUser                         avgt       3   2.976 ± 0.436   ms/op
ClientPb.createUser                     sample  380988   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.888           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.806           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.470           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.353           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  394744   2.429 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.517           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.462           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.370           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.312           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.876           ms/op
ClientPb.getUser                        sample  381744   2.513 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.664           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.310           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.259           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.822           ms/op
ClientPb.listUser                       sample  323085   2.969 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.355           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.796           ms/op
