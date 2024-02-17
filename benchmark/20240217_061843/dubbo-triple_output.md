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
# Warmup Iteration   1: 4.485 ops/ms
# Warmup Iteration   2: 11.871 ops/ms
# Warmup Iteration   3: 12.211 ops/ms
Iteration   1: 12.510 ops/ms
Iteration   2: 12.528 ops/ms
Iteration   3: 12.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.505 ±(99.9%) 0.482 ops/ms [Average]
  (min, avg, max) = (12.476, 12.505, 12.528), stdev = 0.026
  CI (99.9%): [12.023, 12.987] (assumes normal distribution)


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
# Warmup Iteration   1: 8.136 ops/ms
# Warmup Iteration   2: 13.044 ops/ms
# Warmup Iteration   3: 13.016 ops/ms
Iteration   1: 12.987 ops/ms
Iteration   2: 13.041 ops/ms
Iteration   3: 12.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.974 ±(99.9%) 1.347 ops/ms [Average]
  (min, avg, max) = (12.895, 12.974, 13.041), stdev = 0.074
  CI (99.9%): [11.627, 14.321] (assumes normal distribution)


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
# Warmup Iteration   1: 7.546 ops/ms
# Warmup Iteration   2: 12.318 ops/ms
# Warmup Iteration   3: 12.491 ops/ms
Iteration   1: 12.573 ops/ms
Iteration   2: 12.576 ops/ms
Iteration   3: 12.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.543 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (12.479, 12.543, 12.576), stdev = 0.055
  CI (99.9%): [11.543, 13.542] (assumes normal distribution)


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
# Warmup Iteration   1: 6.388 ops/ms
# Warmup Iteration   2: 10.450 ops/ms
# Warmup Iteration   3: 10.457 ops/ms
Iteration   1: 10.394 ops/ms
Iteration   2: 10.517 ops/ms
Iteration   3: 10.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.443 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (10.394, 10.443, 10.517), stdev = 0.065
  CI (99.9%): [9.252, 11.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.004 ms/op
Iteration   1: 2.606 ±(99.9%) 0.005 ms/op
Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
Iteration   3: 2.574 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.572 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (2.537, 2.572, 2.606), stdev = 0.034
  CI (99.9%): [1.946, 3.198] (assumes normal distribution)


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.440 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (2.440, 2.449, 2.467), stdev = 0.015
  CI (99.9%): [2.171, 2.728] (assumes normal distribution)


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.003 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.481, 2.492, 2.498), stdev = 0.009
  CI (99.9%): [2.320, 2.665] (assumes normal distribution)


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.004 ms/op
Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
Iteration   3: 3.030 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (2.982, 3.016, 3.037), stdev = 0.030
  CI (99.9%): [2.471, 3.562] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 13.009 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  9.333 ms/op
                 createUser·p0.9999: 11.540 ms/op
                 createUser·p1.00:   12.337 ms/op

Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  9.472 ms/op
                 createUser·p0.9999: 11.616 ms/op
                 createUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378372
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 182459 
    [ 2.500,  3.750) = 191571 
    [ 3.750,  5.000) = 3283 
    [ 5.000,  6.250) = 473 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      9.480 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     13.845 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  6.115 ms/op
                 existUser·p0.9999: 13.517 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  5.857 ms/op
                 existUser·p0.9999: 11.927 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  8.094 ms/op
                 existUser·p0.9999: 11.806 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388577
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 191549 
    [ 2.500,  3.750) = 193888 
    [ 3.750,  5.000) = 2303 
    [ 5.000,  6.250) = 362 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      7.396 ms/op
     p(99.9900) =     12.763 ms/op
     p(99.9990) =     14.059 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  7.568 ms/op
                 getUser·p0.9999: 13.746 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  9.315 ms/op
                 getUser·p0.9999: 14.739 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  9.233 ms/op
                 getUser·p0.9999: 11.649 ms/op
                 getUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382969
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 189372 
    [ 2.500,  3.750) = 188968 
    [ 3.750,  5.000) = 3398 
    [ 5.000,  6.250) = 716 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     14.151 ms/op
     p(99.9990) =     14.912 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 4.847 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.200 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.998 ms/op
                 listUser·p0.9999: 12.023 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   3: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.721 ms/op
                 listUser·p0.9999: 12.767 ms/op
                 listUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311768
  mean =      3.076 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 78801 
    [ 2.500,  3.750) = 189559 
    [ 3.750,  5.000) = 35675 
    [ 5.000,  6.250) = 6426 
    [ 6.250,  7.500) = 575 
    [ 7.500,  8.750) = 179 
    [ 8.750, 10.000) = 181 
    [10.000, 11.250) = 204 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     11.791 ms/op
     p(99.9990) =     12.909 ms/op
     p(99.9999) =     13.058 ms/op
    p(100.0000) =     13.058 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.505 ± 0.482  ops/ms
ClientPb.existUser                       thrpt       3  12.974 ± 1.347  ops/ms
ClientPb.getUser                         thrpt       3  12.543 ± 1.000  ops/ms
ClientPb.listUser                        thrpt       3  10.443 ± 1.191  ops/ms
ClientPb.createUser                       avgt       3   2.572 ± 0.626   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.278   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.172   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.546   ms/op
ClientPb.createUser                     sample  378372   2.535 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.784           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.480           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.714           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.384           ms/op
ClientPb.existUser                      sample  388577   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.857           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.396           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  382969   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.953           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.257           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.151           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.434           ms/op
ClientPb.listUser                       sample  311768   3.076 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.828           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.791           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.058           ms/op
