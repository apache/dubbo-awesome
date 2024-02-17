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
# Warmup Iteration   1: 4.958 ops/ms
# Warmup Iteration   2: 12.315 ops/ms
# Warmup Iteration   3: 12.378 ops/ms
Iteration   1: 12.630 ops/ms
Iteration   2: 12.634 ops/ms
Iteration   3: 12.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.641 ±(99.9%) 0.276 ops/ms [Average]
  (min, avg, max) = (12.630, 12.641, 12.658), stdev = 0.015
  CI (99.9%): [12.364, 12.917] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.302 ops/ms
# Warmup Iteration   2: 12.997 ops/ms
# Warmup Iteration   3: 13.090 ops/ms
Iteration   1: 13.112 ops/ms
Iteration   2: 13.108 ops/ms
Iteration   3: 13.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.083 ±(99.9%) 0.851 ops/ms [Average]
  (min, avg, max) = (13.029, 13.083, 13.112), stdev = 0.047
  CI (99.9%): [12.232, 13.934] (assumes normal distribution)


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
# Warmup Iteration   1: 7.573 ops/ms
# Warmup Iteration   2: 12.756 ops/ms
# Warmup Iteration   3: 12.993 ops/ms
Iteration   1: 12.969 ops/ms
Iteration   2: 13.013 ops/ms
Iteration   3: 12.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.957 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (12.889, 12.957, 13.013), stdev = 0.063
  CI (99.9%): [11.812, 14.103] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.839 ops/ms
# Warmup Iteration   2: 10.542 ops/ms
# Warmup Iteration   3: 10.772 ops/ms
Iteration   1: 10.825 ops/ms
Iteration   2: 10.759 ops/ms
Iteration   3: 10.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.742 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (10.642, 10.742, 10.825), stdev = 0.093
  CI (99.9%): [9.054, 12.431] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.003 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.497 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.489, 2.497, 2.510), stdev = 0.011
  CI (99.9%): [2.293, 2.702] (assumes normal distribution)


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.397 ±(99.9%) 0.003 ms/op
Iteration   1: 2.433 ±(99.9%) 0.003 ms/op
Iteration   2: 2.419 ±(99.9%) 0.004 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.419, 2.426, 2.433), stdev = 0.007
  CI (99.9%): [2.301, 2.552] (assumes normal distribution)


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.482 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.469, 2.482, 2.506), stdev = 0.021
  CI (99.9%): [2.096, 2.868] (assumes normal distribution)


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.005 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
Iteration   3: 2.990 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.000 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.990, 3.000, 3.015), stdev = 0.013
  CI (99.9%): [2.759, 3.241] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  10.273 ms/op
                 createUser·p0.9999: 13.400 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  10.600 ms/op
                 createUser·p0.9999: 12.124 ms/op
                 createUser·p1.00:   12.517 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.126 ms/op
                 createUser·p0.9999: 9.999 ms/op
                 createUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385701
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 185424 
    [ 2.500,  3.750) = 196744 
    [ 3.750,  5.000) = 2550 
    [ 5.000,  6.250) = 401 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     12.803 ms/op
     p(99.9990) =     14.987 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.602 ms/op
                 existUser·p0.999:  11.486 ms/op
                 existUser·p0.9999: 13.942 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  7.029 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  6.431 ms/op
                 existUser·p0.9999: 12.484 ms/op
                 existUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391383
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 193828 
    [ 2.500,  3.750) = 194575 
    [ 3.750,  5.000) = 2034 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      7.286 ms/op
     p(99.9900) =     13.383 ms/op
     p(99.9990) =     14.305 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  8.444 ms/op
                 getUser·p0.9999: 17.798 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  8.682 ms/op
                 getUser·p0.9999: 10.703 ms/op
                 getUser·p1.00:   11.469 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.795 ms/op
                 getUser·p0.999:  8.086 ms/op
                 getUser·p0.9999: 11.611 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384021
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 189990 
    [ 2.500,  3.750) = 189882 
    [ 3.750,  5.000) = 2823 
    [ 5.000,  6.250) = 812 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     12.757 ms/op
     p(99.9990) =     18.355 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.604 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.293 ms/op
                 listUser·p0.9999: 10.919 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   2: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.702 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 10.759 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.765 ms/op
                 listUser·p0.9999: 10.165 ms/op
                 listUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318749
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 95473 
    [ 2.500,  3.750) = 183136 
    [ 3.750,  5.000) = 32191 
    [ 5.000,  6.250) = 6486 
    [ 6.250,  7.500) = 750 
    [ 7.500,  8.750) = 260 
    [ 8.750, 10.000) = 222 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      8.987 ms/op
     p(99.9900) =     10.748 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.641 ± 0.276  ops/ms
ClientPb.existUser                       thrpt       3  13.083 ± 0.851  ops/ms
ClientPb.getUser                         thrpt       3  12.957 ± 1.145  ops/ms
ClientPb.listUser                        thrpt       3  10.742 ± 1.688  ops/ms
ClientPb.createUser                       avgt       3   2.497 ± 0.204   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.126   ms/op
ClientPb.getUser                          avgt       3   2.482 ± 0.386   ms/op
ClientPb.listUser                         avgt       3   3.000 ± 0.241   ms/op
ClientPb.createUser                     sample  385701   2.487 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.931           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.864           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.433           ms/op
ClientPb.existUser                      sample  391383   2.451 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.622           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.286           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.383           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.336           ms/op
ClientPb.getUser                        sample  384021   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.969           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.389           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.757           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.481           ms/op
ClientPb.listUser                       sample  318749   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.702           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.987           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.748           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.681           ms/op
