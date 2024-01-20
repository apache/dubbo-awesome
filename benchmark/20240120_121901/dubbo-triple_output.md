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
# Warmup Iteration   1: 4.466 ops/ms
# Warmup Iteration   2: 12.056 ops/ms
# Warmup Iteration   3: 12.211 ops/ms
Iteration   1: 12.498 ops/ms
Iteration   2: 12.571 ops/ms
Iteration   3: 12.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.549 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (12.498, 12.549, 12.578), stdev = 0.045
  CI (99.9%): [11.733, 13.365] (assumes normal distribution)


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
# Warmup Iteration   1: 7.811 ops/ms
# Warmup Iteration   2: 12.984 ops/ms
# Warmup Iteration   3: 12.924 ops/ms
Iteration   1: 13.034 ops/ms
Iteration   2: 13.141 ops/ms
Iteration   3: 12.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.013 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (12.863, 13.013, 13.141), stdev = 0.140
  CI (99.9%): [10.459, 15.566] (assumes normal distribution)


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
# Warmup Iteration   1: 7.590 ops/ms
# Warmup Iteration   2: 12.304 ops/ms
# Warmup Iteration   3: 12.805 ops/ms
Iteration   1: 12.793 ops/ms
Iteration   2: 12.553 ops/ms
Iteration   3: 12.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.662 ±(99.9%) 2.219 ops/ms [Average]
  (min, avg, max) = (12.553, 12.662, 12.793), stdev = 0.122
  CI (99.9%): [10.444, 14.881] (assumes normal distribution)


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
# Warmup Iteration   1: 6.240 ops/ms
# Warmup Iteration   2: 10.300 ops/ms
# Warmup Iteration   3: 10.396 ops/ms
Iteration   1: 10.402 ops/ms
Iteration   2: 10.453 ops/ms
Iteration   3: 10.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.439 ±(99.9%) 0.581 ops/ms [Average]
  (min, avg, max) = (10.402, 10.439, 10.460), stdev = 0.032
  CI (99.9%): [9.858, 11.019] (assumes normal distribution)


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
# Warmup Iteration   1: 4.258 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.691 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.591 ±(99.9%) 0.004 ms/op
Iteration   1: 2.596 ±(99.9%) 0.004 ms/op
Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
Iteration   3: 2.574 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.580 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.570, 2.580, 2.596), stdev = 0.014
  CI (99.9%): [2.324, 2.836] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.510 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.505, 2.510, 2.516), stdev = 0.006
  CI (99.9%): [2.403, 2.617] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.921 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.004 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.545 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.539 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.526, 2.539, 2.545), stdev = 0.011
  CI (99.9%): [2.335, 2.743] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.789 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.005 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
Iteration   3: 3.012 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.038 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.012, 3.038, 3.062), stdev = 0.025
  CI (99.9%): [2.584, 3.492] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.183 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.549 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.042 ms/op
                 createUser·p0.999:  11.462 ms/op
                 createUser·p0.9999: 15.663 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.155 ms/op
                 createUser·p0.9999: 14.749 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  8.617 ms/op
                 createUser·p0.9999: 10.524 ms/op
                 createUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379158
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 182429 
    [ 2.500,  3.750) = 192414 
    [ 3.750,  5.000) = 3385 
    [ 5.000,  6.250) = 459 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     15.516 ms/op
     p(99.9990) =     16.299 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  12.088 ms/op
                 existUser·p0.9999: 14.125 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.484 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.579 ms/op
                 existUser·p0.999:  5.893 ms/op
                 existUser·p0.9999: 22.524 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  8.733 ms/op
                 existUser·p0.9999: 13.143 ms/op
                 existUser·p1.00:   13.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385661
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189994 
    [ 2.500,  5.000) = 194883 
    [ 5.000,  7.500) = 418 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      7.157 ms/op
     p(99.9900) =     14.458 ms/op
     p(99.9990) =     23.251 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  11.860 ms/op
                 getUser·p0.9999: 13.899 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  9.664 ms/op
                 getUser·p0.9999: 16.302 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  5.756 ms/op
                 getUser·p0.9999: 11.132 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376260
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 183011 
    [ 2.500,  3.750) = 186690 
    [ 3.750,  5.000) = 4668 
    [ 5.000,  6.250) = 1302 
    [ 6.250,  7.500) = 132 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.860 ms/op
     p(99.9900) =     15.425 ms/op
     p(99.9990) =     16.372 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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
# Warmup Iteration   1: 4.866 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.009 ms/op
Iteration   1: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.646 ms/op
                 listUser·p0.9999: 11.632 ms/op
                 listUser·p1.00:   12.927 ms/op

Iteration   2: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.465 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316130
  mean =      3.034 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 86529 
    [ 2.500,  3.750) = 189060 
    [ 3.750,  5.000) = 33418 
    [ 5.000,  6.250) = 5607 
    [ 6.250,  7.500) = 684 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 201 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.648 ms/op
     p(99.9900) =     13.612 ms/op
     p(99.9990) =     19.295 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.549 ± 0.816  ops/ms
ClientPb.existUser                       thrpt       3  13.013 ± 2.554  ops/ms
ClientPb.getUser                         thrpt       3  12.662 ± 2.219  ops/ms
ClientPb.listUser                        thrpt       3  10.439 ± 0.581  ops/ms
ClientPb.createUser                       avgt       3   2.580 ± 0.256   ms/op
ClientPb.existUser                        avgt       3   2.510 ± 0.107   ms/op
ClientPb.getUser                          avgt       3   2.539 ± 0.204   ms/op
ClientPb.listUser                         avgt       3   3.038 ± 0.454   ms/op
ClientPb.createUser                     sample  379158   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.516           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.450           ms/op
ClientPb.existUser                      sample  385661   2.487 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.157           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.458           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.626           ms/op
ClientPb.getUser                        sample  376260   2.549 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.860           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.425           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.499           ms/op
ClientPb.listUser                       sample  316130   3.034 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.849           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.648           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.612           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.530           ms/op
