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
# Warmup Iteration   1: 4.780 ops/ms
# Warmup Iteration   2: 11.748 ops/ms
# Warmup Iteration   3: 12.229 ops/ms
Iteration   1: 12.501 ops/ms
Iteration   2: 12.305 ops/ms
Iteration   3: 12.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.451 ±(99.9%) 2.349 ops/ms [Average]
  (min, avg, max) = (12.305, 12.451, 12.548), stdev = 0.129
  CI (99.9%): [10.103, 14.800] (assumes normal distribution)


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
# Warmup Iteration   1: 8.149 ops/ms
# Warmup Iteration   2: 13.050 ops/ms
# Warmup Iteration   3: 12.998 ops/ms
Iteration   1: 13.054 ops/ms
Iteration   2: 13.101 ops/ms
Iteration   3: 12.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.051 ±(99.9%) 0.935 ops/ms [Average]
  (min, avg, max) = (12.998, 13.051, 13.101), stdev = 0.051
  CI (99.9%): [12.116, 13.986] (assumes normal distribution)


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
# Warmup Iteration   1: 8.094 ops/ms
# Warmup Iteration   2: 12.350 ops/ms
# Warmup Iteration   3: 12.504 ops/ms
Iteration   1: 12.636 ops/ms
Iteration   2: 12.763 ops/ms
Iteration   3: 12.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.683 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (12.636, 12.683, 12.763), stdev = 0.069
  CI (99.9%): [11.419, 13.946] (assumes normal distribution)


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
# Warmup Iteration   1: 6.623 ops/ms
# Warmup Iteration   2: 10.265 ops/ms
# Warmup Iteration   3: 10.478 ops/ms
Iteration   1: 10.651 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.600 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (10.528, 10.600, 10.651), stdev = 0.064
  CI (99.9%): [9.425, 11.775] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.231 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.549 ±(99.9%) 0.005 ms/op
Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (2.482, 2.513, 2.549), stdev = 0.034
  CI (99.9%): [1.900, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.437 ±(99.9%) 0.003 ms/op
Iteration   3: 2.456 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.437, 2.451, 2.459), stdev = 0.012
  CI (99.9%): [2.234, 2.668] (assumes normal distribution)


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.483 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.467, 2.483, 2.506), stdev = 0.020
  CI (99.9%): [2.111, 2.855] (assumes normal distribution)


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.005 ms/op
Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
Iteration   3: 2.990 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.990, 3.010, 3.034), stdev = 0.023
  CI (99.9%): [2.598, 3.421] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
Iteration   1: 2.572 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  11.483 ms/op
                 createUser·p0.9999: 13.674 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  9.197 ms/op
                 createUser·p0.9999: 11.937 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  7.830 ms/op
                 createUser·p0.9999: 10.918 ms/op
                 createUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377241
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 179533 
    [ 2.500,  3.750) = 194009 
    [ 3.750,  5.000) = 2946 
    [ 5.000,  6.250) = 215 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =     13.305 ms/op
     p(99.9990) =     13.969 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  5.710 ms/op
                 existUser·p0.9999: 13.452 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  8.192 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  8.323 ms/op
                 existUser·p0.9999: 12.291 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388282
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 192044 
    [ 2.500,  3.750) = 193192 
    [ 3.750,  5.000) = 2209 
    [ 5.000,  6.250) = 351 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      7.875 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.180 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  10.940 ms/op
                 getUser·p0.9999: 14.164 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   4.447 ms/op
                 getUser·p0.999:  9.129 ms/op
                 getUser·p0.9999: 13.073 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  8.380 ms/op
                 getUser·p0.9999: 14.016 ms/op
                 getUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381454
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 188596 
    [ 2.500,  3.750) = 187337 
    [ 3.750,  5.000) = 4023 
    [ 5.000,  6.250) = 946 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     13.891 ms/op
     p(99.9990) =     14.336 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.699 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.008 ms/op
Iteration   1: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.523 ms/op
                 listUser·p0.999:  9.188 ms/op
                 listUser·p0.9999: 10.969 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.211 ms/op
                 listUser·p0.9999: 11.265 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   3: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  10.109 ms/op
                 listUser·p0.9999: 11.289 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314853
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 84109 
    [ 2.500,  3.750) = 189958 
    [ 3.750,  5.000) = 33569 
    [ 5.000,  6.250) = 5777 
    [ 6.250,  7.500) = 630 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 263 
    [10.000, 11.250) = 189 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.256 ms/op
     p(99.9990) =     12.694 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.451 ± 2.349  ops/ms
ClientPb.existUser                       thrpt       3  13.051 ± 0.935  ops/ms
ClientPb.getUser                         thrpt       3  12.683 ± 1.264  ops/ms
ClientPb.listUser                        thrpt       3  10.600 ± 1.175  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.613   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.217   ms/op
ClientPb.getUser                          avgt       3   2.483 ± 0.372   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.411   ms/op
ClientPb.createUser                     sample  377241   2.543 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.783           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.305           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.926           ms/op
ClientPb.existUser                      sample  388282   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.841           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.875           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.386           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.320           ms/op
ClientPb.getUser                        sample  381454   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.822           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.389           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.891           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.139           ms/op
ClientPb.listUser                       sample  314853   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.961           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.256           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
