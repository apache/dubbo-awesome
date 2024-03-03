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
# Warmup Iteration   1: 4.389 ops/ms
# Warmup Iteration   2: 12.158 ops/ms
# Warmup Iteration   3: 12.334 ops/ms
Iteration   1: 12.367 ops/ms
Iteration   2: 12.437 ops/ms
Iteration   3: 12.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.469 ±(99.9%) 2.210 ops/ms [Average]
  (min, avg, max) = (12.367, 12.469, 12.603), stdev = 0.121
  CI (99.9%): [10.259, 14.679] (assumes normal distribution)


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
# Warmup Iteration   1: 7.606 ops/ms
# Warmup Iteration   2: 12.734 ops/ms
# Warmup Iteration   3: 12.732 ops/ms
Iteration   1: 12.776 ops/ms
Iteration   2: 12.829 ops/ms
Iteration   3: 12.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.796 ±(99.9%) 0.525 ops/ms [Average]
  (min, avg, max) = (12.776, 12.796, 12.829), stdev = 0.029
  CI (99.9%): [12.271, 13.321] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.035 ops/ms
# Warmup Iteration   2: 12.558 ops/ms
# Warmup Iteration   3: 12.710 ops/ms
Iteration   1: 12.875 ops/ms
Iteration   2: 13.079 ops/ms
Iteration   3: 12.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.980 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (12.875, 12.980, 13.079), stdev = 0.102
  CI (99.9%): [11.115, 14.845] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.744 ops/ms
# Warmup Iteration   2: 10.535 ops/ms
# Warmup Iteration   3: 10.547 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 10.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.646 ±(99.9%) 0.785 ops/ms [Average]
  (min, avg, max) = (10.598, 10.646, 10.682), stdev = 0.043
  CI (99.9%): [9.861, 11.431] (assumes normal distribution)


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.003 ms/op
Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.498, 2.513, 2.527), stdev = 0.015
  CI (99.9%): [2.248, 2.778] (assumes normal distribution)


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
# Warmup Iteration   1: 3.725 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.405 ±(99.9%) 0.004 ms/op
Iteration   1: 2.427 ±(99.9%) 0.004 ms/op
Iteration   2: 2.409 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.409, 2.418, 2.427), stdev = 0.009
  CI (99.9%): [2.253, 2.583] (assumes normal distribution)


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.003 ms/op
Iteration   3: 2.494 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.479, 2.490, 2.497), stdev = 0.010
  CI (99.9%): [2.310, 2.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
Iteration   2: 2.980 ±(99.9%) 0.004 ms/op
Iteration   3: 2.964 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.984 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (2.964, 2.984, 3.007), stdev = 0.022
  CI (99.9%): [2.582, 3.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  10.932 ms/op
                 createUser·p0.9999: 14.212 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  6.794 ms/op
                 createUser·p0.9999: 12.405 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 12.354 ms/op
                 createUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386550
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 187993 
    [ 2.500,  3.750) = 195313 
    [ 3.750,  5.000) = 2576 
    [ 5.000,  6.250) = 176 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      8.609 ms/op
     p(99.9900) =     13.463 ms/op
     p(99.9990) =     15.110 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.005 ms/op
Iteration   1: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  6.200 ms/op
                 existUser·p0.9999: 13.776 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  6.353 ms/op
                 existUser·p0.9999: 12.709 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.973 ms/op
                 existUser·p0.999:  6.458 ms/op
                 existUser·p0.9999: 11.875 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396913
  mean =      2.416 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 202631 
    [ 2.500,  3.750) = 190489 
    [ 3.750,  5.000) = 2854 
    [ 5.000,  6.250) = 471 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      6.374 ms/op
     p(99.9900) =     13.538 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.006 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  6.168 ms/op
                 getUser·p0.9999: 14.953 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.488 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.151 ms/op
                 getUser·p0.999:  7.853 ms/op
                 getUser·p0.9999: 19.628 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  6.349 ms/op
                 getUser·p0.9999: 11.682 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389270
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196023 
    [ 2.500,  5.000) = 192197 
    [ 5.000,  7.500) = 632 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     15.025 ms/op
     p(99.9990) =     21.080 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 4.768 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
Iteration   1: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.151 ms/op
                 listUser·p0.9999: 10.998 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.682 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 14.582 ms/op
                 listUser·p1.00:   14.729 ms/op

Iteration   3: 2.942 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.338 ms/op
                 listUser·p0.9999: 11.915 ms/op
                 listUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323608
  mean =      2.964 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 99397 
    [ 2.500,  3.750) = 187544 
    [ 3.750,  5.000) = 29451 
    [ 5.000,  6.250) = 5799 
    [ 6.250,  7.500) = 584 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 278 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     12.790 ms/op
     p(99.9990) =     14.676 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.469 ± 2.210  ops/ms
ClientPb.existUser                       thrpt       3  12.796 ± 0.525  ops/ms
ClientPb.getUser                         thrpt       3  12.980 ± 1.865  ops/ms
ClientPb.listUser                        thrpt       3  10.646 ± 0.785  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.265   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.165   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.180   ms/op
ClientPb.listUser                         avgt       3   2.984 ± 0.402   ms/op
ClientPb.createUser                     sample  386550   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.609           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.463           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.303           ms/op
ClientPb.existUser                      sample  396913   2.416 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.855           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.374           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.538           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  389270   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.818           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.758           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.025           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.594           ms/op
ClientPb.listUser                       sample  323608   2.964 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.682           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.790           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.729           ms/op
