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
# Warmup Iteration   1: 4.169 ops/ms
# Warmup Iteration   2: 11.724 ops/ms
# Warmup Iteration   3: 12.031 ops/ms
Iteration   1: 12.164 ops/ms
Iteration   2: 12.315 ops/ms
Iteration   3: 12.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.267 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (12.164, 12.267, 12.323), stdev = 0.090
  CI (99.9%): [10.626, 13.908] (assumes normal distribution)


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
# Warmup Iteration   1: 8.246 ops/ms
# Warmup Iteration   2: 12.769 ops/ms
# Warmup Iteration   3: 12.750 ops/ms
Iteration   1: 12.835 ops/ms
Iteration   2: 12.639 ops/ms
Iteration   3: 12.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.779 ±(99.9%) 2.225 ops/ms [Average]
  (min, avg, max) = (12.639, 12.779, 12.863), stdev = 0.122
  CI (99.9%): [10.554, 15.004] (assumes normal distribution)


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
# Warmup Iteration   1: 7.800 ops/ms
# Warmup Iteration   2: 12.452 ops/ms
# Warmup Iteration   3: 12.476 ops/ms
Iteration   1: 12.544 ops/ms
Iteration   2: 12.614 ops/ms
Iteration   3: 12.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.534 ±(99.9%) 1.558 ops/ms [Average]
  (min, avg, max) = (12.444, 12.534, 12.614), stdev = 0.085
  CI (99.9%): [10.976, 14.092] (assumes normal distribution)


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
# Warmup Iteration   1: 6.490 ops/ms
# Warmup Iteration   2: 10.346 ops/ms
# Warmup Iteration   3: 10.457 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.525 ops/ms
Iteration   3: 10.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.520 ±(99.9%) 0.243 ops/ms [Average]
  (min, avg, max) = (10.505, 10.520, 10.530), stdev = 0.013
  CI (99.9%): [10.277, 10.763] (assumes normal distribution)


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
Iteration   1: 2.596 ±(99.9%) 0.005 ms/op
Iteration   2: 2.602 ±(99.9%) 0.004 ms/op
Iteration   3: 2.598 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.598 ±(99.9%) 0.054 ms/op [Average]
  (min, avg, max) = (2.596, 2.598, 2.602), stdev = 0.003
  CI (99.9%): [2.544, 2.653] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.503 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.493, 2.503, 2.513), stdev = 0.010
  CI (99.9%): [2.316, 2.689] (assumes normal distribution)


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.004 ms/op
Iteration   1: 2.540 ±(99.9%) 0.005 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.527 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.516, 2.527, 2.540), stdev = 0.012
  CI (99.9%): [2.311, 2.743] (assumes normal distribution)


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.005 ms/op
Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
Iteration   3: 3.074 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.060 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (3.046, 3.060, 3.074), stdev = 0.014
  CI (99.9%): [2.805, 3.315] (assumes normal distribution)


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
Iteration   1: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  10.868 ms/op
                 createUser·p0.9999: 13.409 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  9.579 ms/op
                 createUser·p0.9999: 12.262 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 2.597 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 11.017 ms/op
                 createUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374043
  mean =      2.563 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 176909 
    [ 2.500,  3.750) = 191588 
    [ 3.750,  5.000) = 4545 
    [ 5.000,  6.250) = 512 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     13.767 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.521 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 13.697 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.119 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  8.908 ms/op
                 existUser·p0.9999: 13.162 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  6.398 ms/op
                 existUser·p0.9999: 11.425 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382344
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 184054 
    [ 2.500,  3.750) = 194911 
    [ 3.750,  5.000) = 2559 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      7.246 ms/op
     p(99.9900) =     13.595 ms/op
     p(99.9990) =     14.061 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  6.279 ms/op
                 getUser·p0.9999: 14.130 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 2.565 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 13.607 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.865 ms/op
                 getUser·p0.999:  9.180 ms/op
                 getUser·p0.9999: 11.769 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377023
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 183314 
    [ 2.500,  3.750) = 187644 
    [ 3.750,  5.000) = 4776 
    [ 5.000,  6.250) = 695 
    [ 6.250,  7.500) = 178 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.039 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.446 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.910 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.085 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.817 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   2: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.800 ms/op
                 listUser·p0.9999: 10.905 ms/op
                 listUser·p1.00:   11.502 ms/op

Iteration   3: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 13.854 ms/op
                 listUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311417
  mean =      3.080 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 77534 
    [ 2.500,  3.750) = 190929 
    [ 3.750,  5.000) = 35352 
    [ 5.000,  6.250) = 6308 
    [ 6.250,  7.500) = 542 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 217 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.725 ms/op
     p(99.9900) =     12.386 ms/op
     p(99.9990) =     15.135 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.267 ± 1.641  ops/ms
ClientPb.existUser                       thrpt       3  12.779 ± 2.225  ops/ms
ClientPb.getUser                         thrpt       3  12.534 ± 1.558  ops/ms
ClientPb.listUser                        thrpt       3  10.520 ± 0.243  ops/ms
ClientPb.createUser                       avgt       3   2.598 ± 0.054   ms/op
ClientPb.existUser                        avgt       3   2.503 ± 0.186   ms/op
ClientPb.getUser                          avgt       3   2.527 ± 0.216   ms/op
ClientPb.listUser                         avgt       3   3.060 ± 0.255   ms/op
ClientPb.createUser                     sample  374043   2.563 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.844           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.142           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.057           ms/op
ClientPb.existUser                      sample  382344   2.508 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.933           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.605           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.246           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.595           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  377023   2.544 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.768           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.963           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.615           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.549           ms/op
ClientPb.listUser                       sample  311417   3.080 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.838           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.725           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.386           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.237           ms/op
