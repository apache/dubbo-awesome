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
# Warmup Iteration   1: 4.831 ops/ms
# Warmup Iteration   2: 11.601 ops/ms
# Warmup Iteration   3: 11.993 ops/ms
Iteration   1: 12.495 ops/ms
Iteration   2: 12.558 ops/ms
Iteration   3: 12.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.569 ±(99.9%) 1.447 ops/ms [Average]
  (min, avg, max) = (12.495, 12.569, 12.653), stdev = 0.079
  CI (99.9%): [11.122, 14.015] (assumes normal distribution)


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
# Warmup Iteration   1: 7.729 ops/ms
# Warmup Iteration   2: 12.865 ops/ms
# Warmup Iteration   3: 12.648 ops/ms
Iteration   1: 12.734 ops/ms
Iteration   2: 13.121 ops/ms
Iteration   3: 12.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.890 ±(99.9%) 3.724 ops/ms [Average]
  (min, avg, max) = (12.734, 12.890, 13.121), stdev = 0.204
  CI (99.9%): [9.167, 16.614] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.368 ops/ms
# Warmup Iteration   2: 12.466 ops/ms
# Warmup Iteration   3: 12.836 ops/ms
Iteration   1: 12.585 ops/ms
Iteration   2: 12.854 ops/ms
Iteration   3: 12.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.734 ±(99.9%) 2.501 ops/ms [Average]
  (min, avg, max) = (12.585, 12.734, 12.854), stdev = 0.137
  CI (99.9%): [10.233, 15.234] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.843 ops/ms
# Warmup Iteration   2: 10.458 ops/ms
# Warmup Iteration   3: 10.622 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.661 ops/ms
Iteration   3: 10.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.691 ±(99.9%) 1.053 ops/ms [Average]
  (min, avg, max) = (10.655, 10.691, 10.758), stdev = 0.058
  CI (99.9%): [9.638, 11.745] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.217 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.003 ms/op
Iteration   1: 2.561 ±(99.9%) 0.004 ms/op
Iteration   2: 2.532 ±(99.9%) 0.003 ms/op
Iteration   3: 2.555 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.550 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (2.532, 2.550, 2.561), stdev = 0.015
  CI (99.9%): [2.276, 2.823] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.003 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.486 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (2.475, 2.486, 2.497), stdev = 0.011
  CI (99.9%): [2.286, 2.686] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.476 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.457, 2.476, 2.492), stdev = 0.018
  CI (99.9%): [2.156, 2.795] (assumes normal distribution)


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.004 ms/op
Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
Iteration   3: 3.020 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.028 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (3.020, 3.028, 3.041), stdev = 0.012
  CI (99.9%): [2.812, 3.243] (assumes normal distribution)


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  11.422 ms/op
                 createUser·p0.9999: 14.451 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  10.928 ms/op
                 createUser·p0.9999: 14.781 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  7.167 ms/op
                 createUser·p0.9999: 10.256 ms/op
                 createUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385942
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 187773 
    [ 2.500,  3.750) = 193276 
    [ 3.750,  5.000) = 3861 
    [ 5.000,  6.250) = 549 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.061 ms/op
     p(99.9900) =     14.300 ms/op
     p(99.9990) =     15.134 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  8.610 ms/op
                 existUser·p0.9999: 14.515 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.636 ms/op
                 existUser·p0.999:  7.723 ms/op
                 existUser·p0.9999: 14.372 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  5.983 ms/op
                 existUser·p0.9999: 12.256 ms/op
                 existUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388888
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 191388 
    [ 2.500,  3.750) = 194000 
    [ 3.750,  5.000) = 2556 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     13.994 ms/op
     p(99.9990) =     15.061 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 19.734 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  9.062 ms/op
                 getUser·p0.9999: 13.174 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  6.355 ms/op
                 getUser·p0.9999: 11.707 ms/op
                 getUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386195
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 192740 
    [ 2.500,  5.000) = 192437 
    [ 5.000,  7.500) = 614 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.172 ms/op
     p(99.9900) =     16.933 ms/op
     p(99.9990) =     20.943 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 4.732 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.009 ms/op
Iteration   1: 3.085 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.731 ms/op
                 listUser·p1.00:   12.894 ms/op

Iteration   2: 3.094 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  10.535 ms/op
                 listUser·p0.9999: 12.283 ms/op
                 listUser·p1.00:   14.238 ms/op

Iteration   3: 3.103 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.438 ms/op
                 listUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309978
  mean =      3.094 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 75122 
    [ 2.500,  3.750) = 189428 
    [ 3.750,  5.000) = 37661 
    [ 5.000,  6.250) = 6372 
    [ 6.250,  7.500) = 667 
    [ 7.500,  8.750) = 141 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 178 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     11.878 ms/op
     p(99.9990) =     13.645 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.569 ± 1.447  ops/ms
ClientPb.existUser                       thrpt       3  12.890 ± 3.724  ops/ms
ClientPb.getUser                         thrpt       3  12.734 ± 2.501  ops/ms
ClientPb.listUser                        thrpt       3  10.691 ± 1.053  ops/ms
ClientPb.createUser                       avgt       3   2.550 ± 0.273   ms/op
ClientPb.existUser                        avgt       3   2.486 ± 0.200   ms/op
ClientPb.getUser                          avgt       3   2.476 ± 0.319   ms/op
ClientPb.listUser                         avgt       3   3.028 ± 0.215   ms/op
ClientPb.createUser                     sample  385942   2.485 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.907           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.061           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.300           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.254           ms/op
ClientPb.existUser                      sample  388888   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.777           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.062           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.994           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.368           ms/op
ClientPb.getUser                        sample  386195   2.483 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.734           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.172           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.933           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.070           ms/op
ClientPb.listUser                       sample  309978   3.094 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.795           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.878           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.238           ms/op
