# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.402 ops/ms
# Warmup Iteration   2: 6.012 ops/ms
# Warmup Iteration   3: 9.294 ops/ms
Iteration   1: 9.990 ops/ms
Iteration   2: 10.094 ops/ms
Iteration   3: 9.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.974 ±(99.9%) 2.340 ops/ms [Average]
  (min, avg, max) = (9.839, 9.974, 10.094), stdev = 0.128
  CI (99.9%): [7.634, 12.315] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.615 ops/ms
# Warmup Iteration   2: 9.407 ops/ms
# Warmup Iteration   3: 10.002 ops/ms
Iteration   1: 10.285 ops/ms
Iteration   2: 10.351 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.394 ±(99.9%) 2.489 ops/ms [Average]
  (min, avg, max) = (10.285, 10.394, 10.547), stdev = 0.136
  CI (99.9%): [7.905, 12.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.267 ops/ms
# Warmup Iteration   2: 8.869 ops/ms
# Warmup Iteration   3: 10.029 ops/ms
Iteration   1: 9.773 ops/ms
Iteration   2: 9.873 ops/ms
Iteration   3: 10.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.000 ±(99.9%) 5.644 ops/ms [Average]
  (min, avg, max) = (9.773, 10.000, 10.352), stdev = 0.309
  CI (99.9%): [4.356, 15.644] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.380 ops/ms
# Warmup Iteration   2: 7.844 ops/ms
# Warmup Iteration   3: 8.407 ops/ms
Iteration   1: 8.687 ops/ms
Iteration   2: 8.617 ops/ms
Iteration   3: 8.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.646 ±(99.9%) 0.660 ops/ms [Average]
  (min, avg, max) = (8.617, 8.646, 8.687), stdev = 0.036
  CI (99.9%): [7.986, 9.306] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.074 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.003 ms/op
Iteration   1: 3.256 ±(99.9%) 0.008 ms/op
Iteration   2: 3.187 ±(99.9%) 0.010 ms/op
Iteration   3: 3.186 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.210 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (3.186, 3.210, 3.256), stdev = 0.040
  CI (99.9%): [2.480, 3.940] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.651 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.004 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
Iteration   2: 3.084 ±(99.9%) 0.002 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.049 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.010, 3.049, 3.084), stdev = 0.037
  CI (99.9%): [2.370, 3.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.116 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.002 ms/op
Iteration   1: 3.130 ±(99.9%) 0.004 ms/op
Iteration   2: 3.133 ±(99.9%) 0.004 ms/op
Iteration   3: 3.129 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.131 ±(99.9%) 0.042 ms/op [Average]
  (min, avg, max) = (3.129, 3.131, 3.133), stdev = 0.002
  CI (99.9%): [3.089, 3.172] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.687 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.005 ms/op
Iteration   1: 3.582 ±(99.9%) 0.010 ms/op
Iteration   2: 3.562 ±(99.9%) 0.010 ms/op
Iteration   3: 3.675 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.606 ±(99.9%) 1.104 ms/op [Average]
  (min, avg, max) = (3.562, 3.606, 3.675), stdev = 0.061
  CI (99.9%): [2.502, 4.710] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.138 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
Iteration   1: 3.185 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  11.780 ms/op
                 createUser·p0.9999: 18.152 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.453 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  10.240 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.434 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  14.811 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307599
  mean =      3.120 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21311 
    [ 2.500,  5.000) = 281839 
    [ 5.000,  7.500) = 3665 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     19.636 ms/op
     p(99.9990) =     20.856 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.699 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  8.635 ms/op
                 existUser·p0.9999: 19.169 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   2: 3.020 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  9.096 ms/op
                 existUser·p0.9999: 23.508 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   3: 3.089 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  12.861 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316387
  mean =      3.032 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12689 
    [ 2.500,  5.000) = 299659 
    [ 5.000,  7.500) = 3374 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 176 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =     12.200 ms/op
     p(99.9900) =     22.175 ms/op
     p(99.9990) =     23.850 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.725 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.009 ms/op
Iteration   1: 3.188 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.011 ms/op
                 getUser·p0.999:  20.578 ms/op
                 getUser·p0.9999: 27.065 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   2: 3.307 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  12.676 ms/op
                 getUser·p0.9999: 23.036 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  10.174 ms/op
                 getUser·p0.9999: 18.081 ms/op
                 getUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299217
  mean =      3.205 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18563 
    [ 2.500,  5.000) = 274045 
    [ 5.000,  7.500) = 5621 
    [ 7.500, 10.000) = 519 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     16.593 ms/op
     p(99.9900) =     24.579 ms/op
     p(99.9990) =     27.362 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.311 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.013 ms/op
Iteration   1: 3.688 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 21.449 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 3.567 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.051 ms/op
                 listUser·p0.99:   6.365 ms/op
                 listUser·p0.999:  12.845 ms/op
                 listUser·p0.9999: 14.320 ms/op
                 listUser·p1.00:   14.811 ms/op

Iteration   3: 3.595 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.039 ms/op
                 listUser·p0.99:   6.250 ms/op
                 listUser·p0.999:  12.747 ms/op
                 listUser·p0.9999: 15.483 ms/op
                 listUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 265583
  mean =      3.616 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 260559 
    [ 5.000,  7.500) = 3357 
    [ 7.500, 10.000) = 902 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     19.794 ms/op
     p(99.9990) =     22.176 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.974 ± 2.340  ops/ms
ClientPb.existUser                       thrpt       3  10.394 ± 2.489  ops/ms
ClientPb.getUser                         thrpt       3  10.000 ± 5.644  ops/ms
ClientPb.listUser                        thrpt       3   8.646 ± 0.660  ops/ms
ClientPb.createUser                       avgt       3   3.210 ± 0.730   ms/op
ClientPb.existUser                        avgt       3   3.049 ± 0.679   ms/op
ClientPb.getUser                          avgt       3   3.131 ± 0.042   ms/op
ClientPb.listUser                         avgt       3   3.606 ± 1.104   ms/op
ClientPb.createUser                     sample  307599   3.120 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.128           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.107           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.636           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.070           ms/op
ClientPb.existUser                      sample  316387   3.032 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.982           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.200           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.175           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.412           ms/op
ClientPb.getUser                        sample  299217   3.205 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.593           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.579           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.787           ms/op
ClientPb.listUser                       sample  265583   3.616 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.626           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.498           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.463           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.976           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.794           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.610           ms/op
