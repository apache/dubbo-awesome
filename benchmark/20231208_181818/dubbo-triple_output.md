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
# Warmup Iteration   1: 5.129 ops/ms
# Warmup Iteration   2: 11.979 ops/ms
# Warmup Iteration   3: 12.110 ops/ms
Iteration   1: 12.609 ops/ms
Iteration   2: 12.629 ops/ms
Iteration   3: 12.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.607 ±(99.9%) 0.428 ops/ms [Average]
  (min, avg, max) = (12.582, 12.607, 12.629), stdev = 0.023
  CI (99.9%): [12.179, 13.034] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.108 ops/ms
# Warmup Iteration   2: 12.344 ops/ms
# Warmup Iteration   3: 12.523 ops/ms
Iteration   1: 12.415 ops/ms
Iteration   2: 12.714 ops/ms
Iteration   3: 12.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.564 ±(99.9%) 2.726 ops/ms [Average]
  (min, avg, max) = (12.415, 12.564, 12.714), stdev = 0.149
  CI (99.9%): [9.838, 15.290] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.446 ops/ms
# Warmup Iteration   2: 12.232 ops/ms
# Warmup Iteration   3: 12.557 ops/ms
Iteration   1: 12.489 ops/ms
Iteration   2: 12.571 ops/ms
Iteration   3: 12.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.562 ±(99.9%) 1.259 ops/ms [Average]
  (min, avg, max) = (12.489, 12.562, 12.626), stdev = 0.069
  CI (99.9%): [11.303, 13.821] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.642 ops/ms
# Warmup Iteration   2: 10.384 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.384 ops/ms
Iteration   2: 10.410 ops/ms
Iteration   3: 10.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.402 ±(99.9%) 0.286 ops/ms [Average]
  (min, avg, max) = (10.384, 10.402, 10.412), stdev = 0.016
  CI (99.9%): [10.116, 10.688] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.384 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.602 ±(99.9%) 0.004 ms/op
Iteration   1: 2.624 ±(99.9%) 0.004 ms/op
Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
Iteration   3: 2.600 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.612 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.600, 2.612, 2.624), stdev = 0.012
  CI (99.9%): [2.391, 2.834] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
Iteration   3: 2.537 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.522 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (2.488, 2.522, 2.542), stdev = 0.030
  CI (99.9%): [1.979, 3.065] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.093 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.583 ±(99.9%) 0.004 ms/op
Iteration   1: 2.571 ±(99.9%) 0.004 ms/op
Iteration   2: 2.583 ±(99.9%) 0.005 ms/op
Iteration   3: 2.611 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.588 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.571, 2.588, 2.611), stdev = 0.020
  CI (99.9%): [2.215, 2.962] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.744 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.005 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
Iteration   2: 3.057 ±(99.9%) 0.004 ms/op
Iteration   3: 3.075 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.055 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.033, 3.055, 3.075), stdev = 0.021
  CI (99.9%): [2.670, 3.440] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.516 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.713 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  11.500 ms/op
                 createUser·p0.9999: 14.172 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  9.402 ms/op
                 createUser·p0.9999: 13.713 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 28.639 ms/op
                 createUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375333
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 178904 
    [ 2.500,  5.000) = 195739 
    [ 5.000,  7.500) = 271 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.809 ms/op
     p(99.9900) =     14.661 ms/op
     p(99.9990) =     28.811 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 3.846 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 14.076 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  5.698 ms/op
                 existUser·p0.9999: 13.261 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  9.162 ms/op
                 existUser·p0.9999: 12.785 ms/op
                 existUser·p1.00:   13.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379053
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 182874 
    [ 2.500,  3.750) = 192303 
    [ 3.750,  5.000) = 3045 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      6.479 ms/op
     p(99.9900) =     13.682 ms/op
     p(99.9990) =     14.602 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  11.646 ms/op
                 getUser·p0.9999: 14.318 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 2.555 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.355 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 14.418 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  8.895 ms/op
                 getUser·p0.9999: 12.453 ms/op
                 getUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377680
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 183198 
    [ 2.500,  3.750) = 187091 
    [ 3.750,  5.000) = 5328 
    [ 5.000,  6.250) = 1376 
    [ 6.250,  7.500) = 192 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      9.344 ms/op
     p(99.9900) =     14.192 ms/op
     p(99.9990) =     14.829 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.981 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.068 ms/op
                 listUser·p0.9999: 10.836 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.737 ms/op
                 listUser·p0.9999: 12.878 ms/op
                 listUser·p1.00:   13.746 ms/op

Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.586 ms/op
                 listUser·p0.9999: 11.780 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312131
  mean =      3.073 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 81645 
    [ 2.500,  3.750) = 187330 
    [ 3.750,  5.000) = 35707 
    [ 5.000,  6.250) = 6006 
    [ 6.250,  7.500) = 681 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     12.430 ms/op
     p(99.9990) =     13.698 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.607 ± 0.428  ops/ms
ClientPb.existUser                       thrpt       3  12.564 ± 2.726  ops/ms
ClientPb.getUser                         thrpt       3  12.562 ± 1.259  ops/ms
ClientPb.listUser                        thrpt       3  10.402 ± 0.286  ops/ms
ClientPb.createUser                       avgt       3   2.612 ± 0.221   ms/op
ClientPb.existUser                        avgt       3   2.522 ± 0.543   ms/op
ClientPb.getUser                          avgt       3   2.588 ± 0.374   ms/op
ClientPb.listUser                         avgt       3   3.055 ± 0.385   ms/op
ClientPb.createUser                     sample  375333   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.946           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.809           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.661           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.327           ms/op
ClientPb.existUser                      sample  379053   2.530 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.701           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.601           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.479           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.682           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.139           ms/op
ClientPb.getUser                        sample  377680   2.540 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.695           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.344           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.192           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.286           ms/op
ClientPb.listUser                       sample  312131   3.073 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.430           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.746           ms/op
