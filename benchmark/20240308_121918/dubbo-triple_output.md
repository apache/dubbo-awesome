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
# Warmup Iteration   1: 5.085 ops/ms
# Warmup Iteration   2: 12.202 ops/ms
# Warmup Iteration   3: 12.599 ops/ms
Iteration   1: 12.539 ops/ms
Iteration   2: 12.877 ops/ms
Iteration   3: 12.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.729 ±(99.9%) 3.158 ops/ms [Average]
  (min, avg, max) = (12.539, 12.729, 12.877), stdev = 0.173
  CI (99.9%): [9.571, 15.887] (assumes normal distribution)


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
# Warmup Iteration   1: 8.086 ops/ms
# Warmup Iteration   2: 13.301 ops/ms
# Warmup Iteration   3: 13.409 ops/ms
Iteration   1: 13.387 ops/ms
Iteration   2: 13.383 ops/ms
Iteration   3: 13.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.412 ±(99.9%) 0.861 ops/ms [Average]
  (min, avg, max) = (13.383, 13.412, 13.466), stdev = 0.047
  CI (99.9%): [12.551, 14.272] (assumes normal distribution)


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
# Warmup Iteration   1: 7.737 ops/ms
# Warmup Iteration   2: 13.109 ops/ms
# Warmup Iteration   3: 13.081 ops/ms
Iteration   1: 13.070 ops/ms
Iteration   2: 13.023 ops/ms
Iteration   3: 13.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.082 ±(99.9%) 1.193 ops/ms [Average]
  (min, avg, max) = (13.023, 13.082, 13.152), stdev = 0.065
  CI (99.9%): [11.889, 14.275] (assumes normal distribution)


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
# Warmup Iteration   1: 6.922 ops/ms
# Warmup Iteration   2: 10.753 ops/ms
# Warmup Iteration   3: 10.777 ops/ms
Iteration   1: 10.909 ops/ms
Iteration   2: 10.886 ops/ms
Iteration   3: 10.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.910 ±(99.9%) 0.468 ops/ms [Average]
  (min, avg, max) = (10.886, 10.910, 10.937), stdev = 0.026
  CI (99.9%): [10.442, 11.379] (assumes normal distribution)


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
# Warmup Iteration   1: 3.907 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
Iteration   2: 2.471 ±(99.9%) 0.003 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.471 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.450, 2.471, 2.491), stdev = 0.020
  CI (99.9%): [2.100, 2.841] (assumes normal distribution)


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
# Warmup Iteration   1: 3.646 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.403 ±(99.9%) 0.003 ms/op
Iteration   1: 2.416 ±(99.9%) 0.003 ms/op
Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.419 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.412, 2.419, 2.429), stdev = 0.009
  CI (99.9%): [2.260, 2.579] (assumes normal distribution)


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.454 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.443, 2.454, 2.475), stdev = 0.018
  CI (99.9%): [2.125, 2.783] (assumes normal distribution)


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
# Warmup Iteration   1: 4.548 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.005 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
Iteration   3: 2.960 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (2.960, 2.979, 3.009), stdev = 0.026
  CI (99.9%): [2.498, 3.460] (assumes normal distribution)


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  6.509 ms/op
                 createUser·p0.9999: 13.367 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  10.338 ms/op
                 createUser·p0.9999: 12.657 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.466 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  8.644 ms/op
                 createUser·p0.9999: 10.693 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391053
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 196496 
    [ 2.500,  3.750) = 190181 
    [ 3.750,  5.000) = 3400 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.878 ms/op
     p(99.9900) =     12.991 ms/op
     p(99.9990) =     14.191 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.403 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.385 ±(99.9%) 0.005 ms/op
Iteration   1: 2.373 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.974 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  6.431 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.388 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.413 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  5.038 ms/op
                 existUser·p0.9999: 10.788 ms/op
                 existUser·p1.00:   11.403 ms/op

Iteration   3: 2.396 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  6.889 ms/op
                 existUser·p0.9999: 12.403 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402094
  mean =      2.385 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 208355 
    [ 2.500,  3.750) = 191259 
    [ 3.750,  5.000) = 1819 
    [ 5.000,  6.250) = 181 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.473 ms/op
     p(99.9000) =      5.780 ms/op
     p(99.9900) =     12.550 ms/op
     p(99.9990) =     14.139 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.006 ms/op
Iteration   1: 2.426 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  6.315 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.575 ms/op
                 getUser·p0.9999: 11.565 ms/op
                 getUser·p1.00:   12.485 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   3.564 ms/op
                 getUser·p0.999:  6.115 ms/op
                 getUser·p0.9999: 10.598 ms/op
                 getUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 394143
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 201084 
    [ 2.500,  3.750) = 188979 
    [ 3.750,  5.000) = 3110 
    [ 5.000,  6.250) = 481 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      6.681 ms/op
     p(99.9900) =     12.834 ms/op
     p(99.9990) =     13.895 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 4.778 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.009 ms/op
Iteration   1: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.889 ms/op
                 listUser·p0.9999: 12.616 ms/op
                 listUser·p1.00:   14.565 ms/op

Iteration   2: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 12.020 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  10.247 ms/op
                 listUser·p0.9999: 13.246 ms/op
                 listUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321808
  mean =      2.980 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 99337 
    [ 2.500,  3.750) = 184443 
    [ 3.750,  5.000) = 30309 
    [ 5.000,  6.250) = 6163 
    [ 6.250,  7.500) = 770 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 245 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     12.561 ms/op
     p(99.9990) =     14.154 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.729 ± 3.158  ops/ms
ClientPb.existUser                       thrpt       3  13.412 ± 0.861  ops/ms
ClientPb.getUser                         thrpt       3  13.082 ± 1.193  ops/ms
ClientPb.listUser                        thrpt       3  10.910 ± 0.468  ops/ms
ClientPb.createUser                       avgt       3   2.471 ± 0.370   ms/op
ClientPb.existUser                        avgt       3   2.419 ± 0.160   ms/op
ClientPb.getUser                          avgt       3   2.454 ± 0.329   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.481   ms/op
ClientPb.createUser                     sample  391053   2.452 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.882           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.490           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.982           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.878           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.991           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.433           ms/op
ClientPb.existUser                      sample  402094   2.385 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.852           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.433           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.780           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.550           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  394143   2.433 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.667           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.454           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.961           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.681           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.834           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.943           ms/op
ClientPb.listUser                       sample  321808   2.980 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.565           ms/op
