# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.830 ops/ms
# Warmup Iteration   2: 12.778 ops/ms
# Warmup Iteration   3: 13.003 ops/ms
Iteration   1: 13.096 ops/ms
Iteration   2: 13.285 ops/ms
Iteration   3: 13.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.216 ±(99.9%) 1.904 ops/ms [Average]
  (min, avg, max) = (13.096, 13.216, 13.285), stdev = 0.104
  CI (99.9%): [11.312, 15.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.761 ops/ms
# Warmup Iteration   2: 13.595 ops/ms
# Warmup Iteration   3: 13.551 ops/ms
Iteration   1: 13.674 ops/ms
Iteration   2: 13.632 ops/ms
Iteration   3: 13.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.651 ±(99.9%) 0.388 ops/ms [Average]
  (min, avg, max) = (13.632, 13.651, 13.674), stdev = 0.021
  CI (99.9%): [13.263, 14.039] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.313 ops/ms
# Warmup Iteration   2: 13.349 ops/ms
# Warmup Iteration   3: 13.368 ops/ms
Iteration   1: 13.373 ops/ms
Iteration   2: 13.306 ops/ms
Iteration   3: 13.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.383 ±(99.9%) 1.498 ops/ms [Average]
  (min, avg, max) = (13.306, 13.383, 13.470), stdev = 0.082
  CI (99.9%): [11.885, 14.881] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.350 ops/ms
# Warmup Iteration   2: 10.929 ops/ms
# Warmup Iteration   3: 11.161 ops/ms
Iteration   1: 11.088 ops/ms
Iteration   2: 11.085 ops/ms
Iteration   3: 11.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.126 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (11.085, 11.126, 11.205), stdev = 0.068
  CI (99.9%): [9.877, 12.376] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.405 ±(99.9%) 0.004 ms/op
Iteration   3: 2.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.423 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (2.405, 2.423, 2.443), stdev = 0.019
  CI (99.9%): [2.079, 2.767] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.479 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.329 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.342 ±(99.9%) 0.003 ms/op
Iteration   1: 2.377 ±(99.9%) 0.004 ms/op
Iteration   2: 2.340 ±(99.9%) 0.004 ms/op
Iteration   3: 2.368 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.362 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (2.340, 2.362, 2.377), stdev = 0.019
  CI (99.9%): [2.007, 2.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.602 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.004 ms/op
Iteration   2: 2.414 ±(99.9%) 0.004 ms/op
Iteration   3: 2.383 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.413 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (2.383, 2.413, 2.442), stdev = 0.030
  CI (99.9%): [1.874, 2.952] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.903 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.842 ±(99.9%) 0.005 ms/op
Iteration   1: 2.831 ±(99.9%) 0.005 ms/op
Iteration   2: 2.860 ±(99.9%) 0.006 ms/op
Iteration   3: 2.839 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.843 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (2.831, 2.843, 2.860), stdev = 0.015
  CI (99.9%): [2.569, 3.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.411 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.458 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  10.388 ms/op
                 createUser·p0.9999: 12.485 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 2.403 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   2.466 ms/op
                 createUser·p0.90:   2.941 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   3.527 ms/op
                 createUser·p0.999:  7.000 ms/op
                 createUser·p0.9999: 11.365 ms/op
                 createUser·p1.00:   11.911 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.466 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  6.443 ms/op
                 createUser·p0.9999: 9.860 ms/op
                 createUser·p1.00:   10.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 396279
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 203644 
    [ 2.500,  3.750) = 189297 
    [ 3.750,  5.000) = 2600 
    [ 5.000,  6.250) = 240 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     12.130 ms/op
     p(99.9990) =     12.966 ms/op
     p(99.9999) =     13.402 ms/op
    p(100.0000) =     13.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.408 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.373 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.327 ±(99.9%) 0.005 ms/op
Iteration   1: 2.314 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.355 ms/op
                 existUser·p0.90:   2.839 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  5.218 ms/op
                 existUser·p0.9999: 14.664 ms/op
                 existUser·p1.00:   15.516 ms/op

Iteration   2: 2.332 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.355 ms/op
                 existUser·p0.90:   2.863 ms/op
                 existUser·p0.95:   2.974 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  6.889 ms/op
                 existUser·p0.9999: 11.947 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   3: 2.322 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.363 ms/op
                 existUser·p0.90:   2.851 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  8.094 ms/op
                 existUser·p0.9999: 10.211 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 412871
  mean =      2.323 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 235220 
    [ 2.500,  3.750) = 174916 
    [ 3.750,  5.000) = 1949 
    [ 5.000,  6.250) = 200 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.359 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      3.457 ms/op
     p(99.9000) =      7.883 ms/op
     p(99.9900) =     13.540 ms/op
     p(99.9990) =     15.390 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.597 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.394 ±(99.9%) 0.005 ms/op
Iteration   1: 2.398 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   2.392 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.689 ms/op
                 getUser·p0.999:  6.130 ms/op
                 getUser·p0.9999: 16.734 ms/op
                 getUser·p1.00:   17.400 ms/op

Iteration   2: 2.457 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.673 ms/op
                 getUser·p0.9999: 13.222 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   3: 2.385 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.372 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  5.668 ms/op
                 getUser·p0.9999: 10.463 ms/op
                 getUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 397479
  mean =      2.413 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 213407 
    [ 2.500,  3.750) = 179139 
    [ 3.750,  5.000) = 3714 
    [ 5.000,  6.250) = 633 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.396 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      7.208 ms/op
     p(99.9900) =     14.279 ms/op
     p(99.9990) =     17.008 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.317 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.944 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.008 ms/op
Iteration   1: 2.893 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   3.723 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   5.267 ms/op
                 listUser·p0.999:  8.552 ms/op
                 listUser·p0.9999: 10.582 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   2: 2.886 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   3.715 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   5.251 ms/op
                 listUser·p0.999:  8.572 ms/op
                 listUser·p0.9999: 11.615 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   3: 2.905 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   2.834 ms/op
                 listUser·p0.90:   3.744 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   5.341 ms/op
                 listUser·p0.999:  8.879 ms/op
                 listUser·p0.9999: 11.254 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 331407
  mean =      2.894 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 110735 
    [ 2.500,  3.750) = 188504 
    [ 3.750,  5.000) = 26980 
    [ 5.000,  6.250) = 3955 
    [ 6.250,  7.500) = 519 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 170 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     11.338 ms/op
     p(99.9990) =     12.313 ms/op
     p(99.9999) =     12.861 ms/op
    p(100.0000) =     12.861 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.216 ± 1.904  ops/ms
ClientPb.existUser                       thrpt       3  13.651 ± 0.388  ops/ms
ClientPb.getUser                         thrpt       3  13.383 ± 1.498  ops/ms
ClientPb.listUser                        thrpt       3  11.126 ± 1.249  ops/ms
ClientPb.createUser                       avgt       3   2.423 ± 0.344   ms/op
ClientPb.existUser                        avgt       3   2.362 ± 0.355   ms/op
ClientPb.getUser                          avgt       3   2.413 ± 0.539   ms/op
ClientPb.listUser                         avgt       3   2.843 ± 0.274   ms/op
ClientPb.createUser                     sample  396279   2.420 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.765           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.462           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.970           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.438           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.130           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.402           ms/op
ClientPb.existUser                      sample  412871   2.323 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.834           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.359           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.851           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.883           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.540           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.516           ms/op
ClientPb.getUser                        sample  397479   2.413 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.837           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.966           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.208           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.279           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.400           ms/op
ClientPb.listUser                       sample  331407   2.894 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.936           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.292           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.651           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.338           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.861           ms/op
