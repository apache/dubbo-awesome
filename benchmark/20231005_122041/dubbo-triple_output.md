# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.428 ops/ms
# Warmup Iteration   2: 5.369 ops/ms
# Warmup Iteration   3: 8.701 ops/ms
Iteration   1: 9.374 ops/ms
Iteration   2: 9.465 ops/ms
Iteration   3: 9.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.442 ±(99.9%) 1.097 ops/ms [Average]
  (min, avg, max) = (9.374, 9.442, 9.488), stdev = 0.060
  CI (99.9%): [8.345, 10.539] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ops/ms
# Warmup Iteration   2: 9.213 ops/ms
# Warmup Iteration   3: 9.619 ops/ms
Iteration   1: 9.890 ops/ms
Iteration   2: 9.973 ops/ms
Iteration   3: 9.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.850 ±(99.9%) 2.675 ops/ms [Average]
  (min, avg, max) = (9.688, 9.850, 9.973), stdev = 0.147
  CI (99.9%): [7.176, 12.525] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 8.822 ops/ms
# Warmup Iteration   3: 9.331 ops/ms
Iteration   1: 9.777 ops/ms
Iteration   2: 9.773 ops/ms
Iteration   3: 9.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.740 ±(99.9%) 1.119 ops/ms [Average]
  (min, avg, max) = (9.669, 9.740, 9.777), stdev = 0.061
  CI (99.9%): [8.621, 10.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.284 ops/ms
# Warmup Iteration   2: 7.640 ops/ms
# Warmup Iteration   3: 7.996 ops/ms
Iteration   1: 8.350 ops/ms
Iteration   2: 8.285 ops/ms
Iteration   3: 7.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.208 ±(99.9%) 3.498 ops/ms [Average]
  (min, avg, max) = (7.990, 8.208, 8.350), stdev = 0.192
  CI (99.9%): [4.710, 11.706] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.062 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.004 ms/op
Iteration   1: 3.500 ±(99.9%) 0.002 ms/op
Iteration   2: 3.583 ±(99.9%) 0.005 ms/op
Iteration   3: 3.471 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.518 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (3.471, 3.518, 3.583), stdev = 0.058
  CI (99.9%): [2.461, 4.575] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.193 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.005 ms/op
Iteration   1: 3.324 ±(99.9%) 0.004 ms/op
Iteration   2: 3.329 ±(99.9%) 0.005 ms/op
Iteration   3: 3.348 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.334 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.324, 3.334, 3.348), stdev = 0.012
  CI (99.9%): [3.109, 3.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.017 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.002 ms/op
Iteration   1: 3.495 ±(99.9%) 0.003 ms/op
Iteration   2: 3.406 ±(99.9%) 0.003 ms/op
Iteration   3: 3.643 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.514 ±(99.9%) 2.188 ms/op [Average]
  (min, avg, max) = (3.406, 3.514, 3.643), stdev = 0.120
  CI (99.9%): [1.326, 5.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.532 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.004 ms/op
Iteration   1: 3.893 ±(99.9%) 0.005 ms/op
Iteration   2: 3.940 ±(99.9%) 0.005 ms/op
Iteration   3: 3.982 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.939 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.893, 3.939, 3.982), stdev = 0.044
  CI (99.9%): [3.127, 4.750] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.883 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
Iteration   1: 3.313 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  18.264 ms/op
                 createUser·p0.9999: 23.309 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.351 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  20.102 ms/op
                 createUser·p0.9999: 22.493 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.384 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.836 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  16.951 ms/op
                 createUser·p0.9999: 23.101 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286844
  mean =      3.349 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16246 
    [ 2.500,  5.000) = 262319 
    [ 5.000,  7.500) = 7037 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     17.607 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     23.827 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.544 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.008 ms/op
Iteration   1: 3.296 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  18.084 ms/op
                 existUser·p0.9999: 22.292 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   6.094 ms/op
                 existUser·p0.999:  13.582 ms/op
                 existUser·p0.9999: 21.273 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  16.468 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292231
  mean =      3.282 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12491 
    [ 2.500,  5.000) = 271836 
    [ 5.000,  7.500) = 6638 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     14.398 ms/op
     p(99.9900) =     23.258 ms/op
     p(99.9990) =     25.577 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.145 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.010 ms/op
Iteration   1: 3.431 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  19.323 ms/op
                 getUser·p0.9999: 30.136 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   2: 3.267 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  12.574 ms/op
                 getUser·p0.9999: 22.361 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.350 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.664 ms/op
                 getUser·p0.999:  19.009 ms/op
                 getUser·p0.9999: 29.390 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286668
  mean =      3.348 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9235 
    [ 2.500,  5.000) = 267984 
    [ 5.000,  7.500) = 8211 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     19.016 ms/op
     p(99.9900) =     29.338 ms/op
     p(99.9990) =     30.806 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.153 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.012 ms/op
Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  16.967 ms/op
                 listUser·p0.9999: 25.672 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   2: 3.941 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 17.003 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.852 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.214 ms/op
                 listUser·p0.999:  12.726 ms/op
                 listUser·p0.9999: 32.999 ms/op
                 listUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246969
  mean =      3.887 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91 
    [ 2.500,  5.000) = 238266 
    [ 5.000,  7.500) = 6530 
    [ 7.500, 10.000) = 1213 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 324 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     25.743 ms/op
     p(99.9990) =     35.328 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.442 ± 1.097  ops/ms
ClientPb.existUser                       thrpt       3   9.850 ± 2.675  ops/ms
ClientPb.getUser                         thrpt       3   9.740 ± 1.119  ops/ms
ClientPb.listUser                        thrpt       3   8.208 ± 3.498  ops/ms
ClientPb.createUser                       avgt       3   3.518 ± 1.057   ms/op
ClientPb.existUser                        avgt       3   3.334 ± 0.225   ms/op
ClientPb.getUser                          avgt       3   3.514 ± 2.188   ms/op
ClientPb.listUser                         avgt       3   3.939 ± 0.811   ms/op
ClientPb.createUser                     sample  286844   3.349 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.811           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.157           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.607           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.938           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.953           ms/op
ClientPb.existUser                      sample  292231   3.282 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.612           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.291           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.398           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.258           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.821           ms/op
ClientPb.getUser                        sample  286668   3.348 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.016           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.338           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.687           ms/op
ClientPb.listUser                       sample  246969   3.887 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.247           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.743           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.652           ms/op
