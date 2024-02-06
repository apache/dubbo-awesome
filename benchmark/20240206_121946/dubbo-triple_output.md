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
# Warmup Iteration   1: 4.785 ops/ms
# Warmup Iteration   2: 11.997 ops/ms
# Warmup Iteration   3: 12.374 ops/ms
Iteration   1: 12.551 ops/ms
Iteration   2: 12.705 ops/ms
Iteration   3: 12.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.636 ±(99.9%) 1.424 ops/ms [Average]
  (min, avg, max) = (12.551, 12.636, 12.705), stdev = 0.078
  CI (99.9%): [11.211, 14.060] (assumes normal distribution)


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
# Warmup Iteration   1: 8.316 ops/ms
# Warmup Iteration   2: 12.873 ops/ms
# Warmup Iteration   3: 13.029 ops/ms
Iteration   1: 13.057 ops/ms
Iteration   2: 13.094 ops/ms
Iteration   3: 13.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.054 ±(99.9%) 0.745 ops/ms [Average]
  (min, avg, max) = (13.013, 13.054, 13.094), stdev = 0.041
  CI (99.9%): [12.310, 13.799] (assumes normal distribution)


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
# Warmup Iteration   1: 7.165 ops/ms
# Warmup Iteration   2: 12.448 ops/ms
# Warmup Iteration   3: 12.467 ops/ms
Iteration   1: 12.507 ops/ms
Iteration   2: 12.739 ops/ms
Iteration   3: 12.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.660 ±(99.9%) 2.411 ops/ms [Average]
  (min, avg, max) = (12.507, 12.660, 12.739), stdev = 0.132
  CI (99.9%): [10.249, 15.071] (assumes normal distribution)


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
# Warmup Iteration   1: 6.658 ops/ms
# Warmup Iteration   2: 10.291 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.456 ops/ms
Iteration   2: 10.525 ops/ms
Iteration   3: 10.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.495 ±(99.9%) 0.647 ops/ms [Average]
  (min, avg, max) = (10.456, 10.495, 10.525), stdev = 0.035
  CI (99.9%): [9.848, 11.141] (assumes normal distribution)


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.004 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.522, 2.532, 2.544), stdev = 0.011
  CI (99.9%): [2.324, 2.739] (assumes normal distribution)


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
# Warmup Iteration   1: 3.556 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.003 ms/op
Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
Iteration   3: 2.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.446, 2.459, 2.474), stdev = 0.014
  CI (99.9%): [2.208, 2.709] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.003 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.512 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.506, 2.512, 2.516), stdev = 0.006
  CI (99.9%): [2.411, 2.614] (assumes normal distribution)


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.005 ms/op
Iteration   1: 3.015 ±(99.9%) 0.007 ms/op
Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
Iteration   3: 3.037 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.015, 3.034, 3.049), stdev = 0.017
  CI (99.9%): [2.718, 3.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.256 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.714 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   2.474 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.941 ms/op
                 createUser·p0.999:  11.815 ms/op
                 createUser·p0.9999: 13.986 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  9.801 ms/op
                 createUser·p0.9999: 13.177 ms/op
                 createUser·p1.00:   13.828 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.063 ms/op
                 createUser·p0.999:  9.035 ms/op
                 createUser·p0.9999: 12.212 ms/op
                 createUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380316
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 185970 
    [ 2.500,  3.750) = 189350 
    [ 3.750,  5.000) = 3900 
    [ 5.000,  6.250) = 548 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  8.771 ms/op
                 existUser·p0.9999: 13.091 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  7.568 ms/op
                 existUser·p0.9999: 14.399 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  5.800 ms/op
                 existUser·p0.9999: 12.009 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388991
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 191454 
    [ 2.500,  3.750) = 194378 
    [ 3.750,  5.000) = 2386 
    [ 5.000,  6.250) = 319 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     13.158 ms/op
     p(99.9990) =     14.864 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  11.244 ms/op
                 getUser·p0.9999: 13.357 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 14.737 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  7.267 ms/op
                 getUser·p0.9999: 12.274 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381482
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 187320 
    [ 2.500,  3.750) = 189576 
    [ 3.750,  5.000) = 3607 
    [ 5.000,  6.250) = 429 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      8.152 ms/op
     p(99.9900) =     13.610 ms/op
     p(99.9990) =     14.896 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.009 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 10.984 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.694 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 11.557 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.926 ms/op
                 listUser·p0.9999: 11.125 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316278
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 89468 
    [ 2.500,  3.750) = 186473 
    [ 3.750,  5.000) = 32833 
    [ 5.000,  6.250) = 5910 
    [ 6.250,  7.500) = 789 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 259 
    [10.000, 11.250) = 181 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.219 ms/op
     p(99.9990) =     11.821 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.636 ± 1.424  ops/ms
ClientPb.existUser                       thrpt       3  13.054 ± 0.745  ops/ms
ClientPb.getUser                         thrpt       3  12.660 ± 2.411  ops/ms
ClientPb.listUser                        thrpt       3  10.495 ± 0.647  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.207   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 0.251   ms/op
ClientPb.getUser                          avgt       3   2.512 ± 0.102   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.316   ms/op
ClientPb.createUser                     sample  380316   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.572           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.044           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.451           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.516           ms/op
ClientPb.existUser                      sample  388991   2.465 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.854           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.595           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.158           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.942           ms/op
ClientPb.getUser                        sample  381482   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.775           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.152           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.610           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.366           ms/op
ClientPb.listUser                       sample  316278   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.694           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.219           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.878           ms/op
