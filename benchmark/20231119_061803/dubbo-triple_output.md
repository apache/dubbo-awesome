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
# Warmup Iteration   1: 4.888 ops/ms
# Warmup Iteration   2: 11.819 ops/ms
# Warmup Iteration   3: 12.212 ops/ms
Iteration   1: 12.460 ops/ms
Iteration   2: 12.420 ops/ms
Iteration   3: 12.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.495 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (12.420, 12.495, 12.605), stdev = 0.097
  CI (99.9%): [10.721, 14.269] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.771 ops/ms
# Warmup Iteration   2: 12.577 ops/ms
# Warmup Iteration   3: 12.758 ops/ms
Iteration   1: 12.779 ops/ms
Iteration   2: 12.755 ops/ms
Iteration   3: 12.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.732 ±(99.9%) 1.129 ops/ms [Average]
  (min, avg, max) = (12.662, 12.732, 12.779), stdev = 0.062
  CI (99.9%): [11.603, 13.861] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.606 ops/ms
# Warmup Iteration   2: 12.560 ops/ms
# Warmup Iteration   3: 12.623 ops/ms
Iteration   1: 12.565 ops/ms
Iteration   2: 12.833 ops/ms
Iteration   3: 12.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.715 ±(99.9%) 2.495 ops/ms [Average]
  (min, avg, max) = (12.565, 12.715, 12.833), stdev = 0.137
  CI (99.9%): [10.220, 15.210] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.561 ops/ms
# Warmup Iteration   2: 10.345 ops/ms
# Warmup Iteration   3: 10.537 ops/ms
Iteration   1: 10.520 ops/ms
Iteration   2: 10.629 ops/ms
Iteration   3: 10.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.624 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (10.520, 10.624, 10.724), stdev = 0.102
  CI (99.9%): [8.759, 12.489] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
Iteration   3: 2.600 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.570 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (2.536, 2.570, 2.600), stdev = 0.032
  CI (99.9%): [1.989, 3.150] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
Iteration   3: 2.496 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.493 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (2.483, 2.493, 2.500), stdev = 0.009
  CI (99.9%): [2.337, 2.650] (assumes normal distribution)


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.047 ms/op [Average]
  (min, avg, max) = (2.489, 2.492, 2.494), stdev = 0.003
  CI (99.9%): [2.445, 2.539] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.005 ms/op
Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
Iteration   3: 3.021 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (2.996, 3.009, 3.021), stdev = 0.012
  CI (99.9%): [2.781, 3.236] (assumes normal distribution)


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  11.337 ms/op
                 createUser·p0.9999: 14.991 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  9.199 ms/op
                 createUser·p0.9999: 13.358 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  8.840 ms/op
                 createUser·p0.9999: 12.960 ms/op
                 createUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379775
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 182723 
    [ 2.500,  3.750) = 192688 
    [ 3.750,  5.000) = 3378 
    [ 5.000,  6.250) = 453 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     15.185 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  6.227 ms/op
                 existUser·p0.9999: 13.844 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  7.263 ms/op
                 existUser·p0.9999: 14.088 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  8.782 ms/op
                 existUser·p0.9999: 12.406 ms/op
                 existUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390452
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 193846 
    [ 2.500,  3.750) = 192405 
    [ 3.750,  5.000) = 3037 
    [ 5.000,  6.250) = 606 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      7.988 ms/op
     p(99.9900) =     13.841 ms/op
     p(99.9990) =     14.370 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  8.129 ms/op
                 getUser·p0.9999: 14.320 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.003 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 15.270 ms/op
                 getUser·p1.00:   16.269 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 11.342 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382903
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 189099 
    [ 2.500,  3.750) = 188435 
    [ 3.750,  5.000) = 4259 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      8.538 ms/op
     p(99.9900) =     14.549 ms/op
     p(99.9990) =     16.090 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 4.695 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.009 ms/op
Iteration   1: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  8.733 ms/op
                 listUser·p0.9999: 11.076 ms/op
                 listUser·p1.00:   11.387 ms/op

Iteration   2: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.274 ms/op
                 listUser·p0.9999: 11.466 ms/op
                 listUser·p1.00:   13.697 ms/op

Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.658 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.857 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323619
  mean =      2.963 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 101564 
    [ 2.500,  3.750) = 186010 
    [ 3.750,  5.000) = 28962 
    [ 5.000,  6.250) = 5669 
    [ 6.250,  7.500) = 609 
    [ 7.500,  8.750) = 265 
    [ 8.750, 10.000) = 239 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     11.146 ms/op
     p(99.9990) =     13.396 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.495 ± 1.774  ops/ms
ClientPb.existUser                       thrpt       3  12.732 ± 1.129  ops/ms
ClientPb.getUser                         thrpt       3  12.715 ± 2.495  ops/ms
ClientPb.listUser                        thrpt       3  10.624 ± 1.865  ops/ms
ClientPb.createUser                       avgt       3   2.570 ± 0.580   ms/op
ClientPb.existUser                        avgt       3   2.493 ± 0.157   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.047   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.227   ms/op
ClientPb.createUser                     sample  379775   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.830           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.864           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.172           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.352           ms/op
ClientPb.existUser                      sample  390452   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.796           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.988           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.841           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  382903   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.735           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.538           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.549           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.269           ms/op
ClientPb.listUser                       sample  323619   2.963 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.658           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.093           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.146           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
