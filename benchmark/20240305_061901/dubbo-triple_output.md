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
# Warmup Iteration   1: 4.359 ops/ms
# Warmup Iteration   2: 12.161 ops/ms
# Warmup Iteration   3: 12.555 ops/ms
Iteration   1: 12.573 ops/ms
Iteration   2: 12.963 ops/ms
Iteration   3: 12.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.800 ±(99.9%) 3.699 ops/ms [Average]
  (min, avg, max) = (12.573, 12.800, 12.963), stdev = 0.203
  CI (99.9%): [9.101, 16.499] (assumes normal distribution)


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
# Warmup Iteration   1: 7.947 ops/ms
# Warmup Iteration   2: 13.151 ops/ms
# Warmup Iteration   3: 13.044 ops/ms
Iteration   1: 13.128 ops/ms
Iteration   2: 12.979 ops/ms
Iteration   3: 13.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.091 ±(99.9%) 1.802 ops/ms [Average]
  (min, avg, max) = (12.979, 13.091, 13.166), stdev = 0.099
  CI (99.9%): [11.290, 14.893] (assumes normal distribution)


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
# Warmup Iteration   1: 7.517 ops/ms
# Warmup Iteration   2: 12.698 ops/ms
# Warmup Iteration   3: 12.737 ops/ms
Iteration   1: 12.931 ops/ms
Iteration   2: 12.813 ops/ms
Iteration   3: 12.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.880 ±(99.9%) 1.102 ops/ms [Average]
  (min, avg, max) = (12.813, 12.880, 12.931), stdev = 0.060
  CI (99.9%): [11.778, 13.981] (assumes normal distribution)


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
# Warmup Iteration   1: 6.110 ops/ms
# Warmup Iteration   2: 10.225 ops/ms
# Warmup Iteration   3: 10.332 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.508 ops/ms
Iteration   3: 10.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.442 ±(99.9%) 1.849 ops/ms [Average]
  (min, avg, max) = (10.325, 10.442, 10.508), stdev = 0.101
  CI (99.9%): [8.593, 12.291] (assumes normal distribution)


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
Iteration   3: 2.500 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.471, 2.495, 2.515), stdev = 0.022
  CI (99.9%): [2.091, 2.899] (assumes normal distribution)


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
# Warmup Iteration   1: 3.786 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.405 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.417 ±(99.9%) 0.003 ms/op
Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
Iteration   3: 2.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (2.417, 2.442, 2.457), stdev = 0.022
  CI (99.9%): [2.041, 2.843] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.519 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.504, 2.519, 2.536), stdev = 0.016
  CI (99.9%): [2.219, 2.818] (assumes normal distribution)


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
# Warmup Iteration   1: 5.121 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
Iteration   3: 3.046 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.038 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.005, 3.038, 3.062), stdev = 0.029
  CI (99.9%): [2.506, 3.569] (assumes normal distribution)


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   3.183 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  12.688 ms/op
                 createUser·p0.9999: 15.407 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   2: 2.477 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.437 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.510 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  10.185 ms/op
                 createUser·p0.9999: 13.453 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 2.465 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   2.413 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.445 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.173 ms/op
                 createUser·p0.9999: 12.026 ms/op
                 createUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385419
  mean =      2.488 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 418 
    [ 1.250,  2.500) = 201213 
    [ 2.500,  3.750) = 172002 
    [ 3.750,  5.000) = 10275 
    [ 5.000,  6.250) = 942 
    [ 6.250,  7.500) = 128 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.591 ms/op
     p(99.9900) =     14.753 ms/op
     p(99.9990) =     15.851 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.390 ±(99.9%) 0.006 ms/op
Iteration   1: 2.402 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.363 ms/op
                 existUser·p0.90:   3.101 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.382 ms/op
                 existUser·p0.9999: 15.466 ms/op
                 existUser·p1.00:   16.138 ms/op

Iteration   2: 2.384 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.322 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  9.530 ms/op
                 existUser·p0.9999: 15.778 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   3: 2.381 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.351 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.363 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  8.141 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401540
  mean =      2.389 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 534 
    [ 1.250,  2.500) = 236536 
    [ 2.500,  3.750) = 153605 
    [ 3.750,  5.000) = 9346 
    [ 5.000,  6.250) = 993 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 143 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.347 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.412 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     14.637 ms/op
     p(99.9990) =     16.400 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   3.277 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  11.338 ms/op
                 getUser·p0.9999: 17.039 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 2.547 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.505 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.207 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  11.010 ms/op
                 getUser·p0.9999: 16.178 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.333 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   3.207 ms/op
                 getUser·p0.95:   3.523 ms/op
                 getUser·p0.99:   4.553 ms/op
                 getUser·p0.999:  10.770 ms/op
                 getUser·p0.9999: 15.657 ms/op
                 getUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377796
  mean =      2.538 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196666 
    [ 2.500,  5.000) = 178858 
    [ 5.000,  7.500) = 1769 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     11.030 ms/op
     p(99.9900) =     16.318 ms/op
     p(99.9990) =     17.545 ms/op
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
# Warmup Iteration   1: 5.161 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.010 ms/op
Iteration   1: 3.069 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.931 ms/op
                 listUser·p0.999:  10.060 ms/op
                 listUser·p0.9999: 16.150 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   2: 3.050 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.456 ms/op
                 listUser·p0.9999: 27.890 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   3: 3.034 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  10.486 ms/op
                 listUser·p0.9999: 13.435 ms/op
                 listUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314419
  mean =      3.051 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97992 
    [ 2.500,  5.000) = 207749 
    [ 5.000,  7.500) = 7557 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.397 ms/op
     p(99.9900) =     25.610 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.800 ± 3.699  ops/ms
ClientPb.existUser                       thrpt       3  13.091 ± 1.802  ops/ms
ClientPb.getUser                         thrpt       3  12.880 ± 1.102  ops/ms
ClientPb.listUser                        thrpt       3  10.442 ± 1.849  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.404   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.401   ms/op
ClientPb.getUser                          avgt       3   2.519 ± 0.300   ms/op
ClientPb.listUser                         avgt       3   3.038 ± 0.532   ms/op
ClientPb.createUser                     sample  385419   2.488 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.595           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.454           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.482           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.591           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.753           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.253           ms/op
ClientPb.existUser                      sample  401540   2.389 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.679           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.347           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.077           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.637           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.334           ms/op
ClientPb.getUser                        sample  377796   2.538 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.030           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.318           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.791           ms/op
ClientPb.listUser                       sample  314419   3.051 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.397           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.610           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.557           ms/op
