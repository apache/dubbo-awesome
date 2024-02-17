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
# Warmup Iteration   1: 4.202 ops/ms
# Warmup Iteration   2: 11.911 ops/ms
# Warmup Iteration   3: 12.132 ops/ms
Iteration   1: 12.562 ops/ms
Iteration   2: 12.492 ops/ms
Iteration   3: 12.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.534 ±(99.9%) 0.681 ops/ms [Average]
  (min, avg, max) = (12.492, 12.534, 12.562), stdev = 0.037
  CI (99.9%): [11.853, 13.215] (assumes normal distribution)


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
# Warmup Iteration   1: 8.142 ops/ms
# Warmup Iteration   2: 12.895 ops/ms
# Warmup Iteration   3: 12.979 ops/ms
Iteration   1: 12.990 ops/ms
Iteration   2: 13.120 ops/ms
Iteration   3: 12.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.995 ±(99.9%) 2.251 ops/ms [Average]
  (min, avg, max) = (12.873, 12.995, 13.120), stdev = 0.123
  CI (99.9%): [10.743, 15.246] (assumes normal distribution)


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
# Warmup Iteration   1: 7.812 ops/ms
# Warmup Iteration   2: 12.631 ops/ms
# Warmup Iteration   3: 12.940 ops/ms
Iteration   1: 12.865 ops/ms
Iteration   2: 12.720 ops/ms
Iteration   3: 12.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.646 ±(99.9%) 4.828 ops/ms [Average]
  (min, avg, max) = (12.352, 12.646, 12.865), stdev = 0.265
  CI (99.9%): [7.817, 17.474] (assumes normal distribution)


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
# Warmup Iteration   1: 6.342 ops/ms
# Warmup Iteration   2: 10.558 ops/ms
# Warmup Iteration   3: 10.688 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.647 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (10.566, 10.647, 10.695), stdev = 0.070
  CI (99.9%): [9.361, 11.933] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.518, 2.524, 2.527), stdev = 0.005
  CI (99.9%): [2.432, 2.616] (assumes normal distribution)


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.003 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.476 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.466, 2.476, 2.494), stdev = 0.016
  CI (99.9%): [2.191, 2.761] (assumes normal distribution)


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.004 ms/op
Iteration   1: 2.531 ±(99.9%) 0.005 ms/op
Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
Iteration   3: 2.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.499, 2.518, 2.531), stdev = 0.017
  CI (99.9%): [2.212, 2.825] (assumes normal distribution)


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
# Warmup Iteration   1: 5.015 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.005 ms/op
Iteration   1: 3.043 ±(99.9%) 0.006 ms/op
Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
Iteration   3: 3.035 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (3.023, 3.034, 3.043), stdev = 0.010
  CI (99.9%): [2.849, 3.219] (assumes normal distribution)


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.531 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.804 ms/op
                 createUser·p0.999:  11.742 ms/op
                 createUser·p0.9999: 15.132 ms/op
                 createUser·p1.00:   15.892 ms/op

Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 11.261 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 10.422 ms/op
                 createUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380482
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 182045 
    [ 2.500,  3.750) = 193453 
    [ 3.750,  5.000) = 3852 
    [ 5.000,  6.250) = 530 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 159 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     13.532 ms/op
     p(99.9990) =     15.729 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  5.274 ms/op
                 existUser·p0.9999: 14.184 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  6.591 ms/op
                 existUser·p0.9999: 12.956 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  8.211 ms/op
                 existUser·p0.9999: 12.689 ms/op
                 existUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394457
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 195019 
    [ 2.500,  3.750) = 196157 
    [ 3.750,  5.000) = 2515 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      6.493 ms/op
     p(99.9900) =     13.699 ms/op
     p(99.9990) =     14.467 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.082 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.047 ms/op
                 getUser·p0.999:  8.180 ms/op
                 getUser·p0.9999: 14.256 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  6.944 ms/op
                 getUser·p0.9999: 12.173 ms/op
                 getUser·p1.00:   12.386 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.255 ms/op
                 getUser·p0.9999: 12.141 ms/op
                 getUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386949
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 191532 
    [ 2.500,  3.750) = 189895 
    [ 3.750,  5.000) = 4031 
    [ 5.000,  6.250) = 973 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      4.119 ms/op
     p(99.9000) =      7.950 ms/op
     p(99.9900) =     13.145 ms/op
     p(99.9990) =     14.879 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.009 ms/op
Iteration   1: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.710 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.235 ms/op
                 listUser·p0.9999: 10.997 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.434 ms/op
                 listUser·p0.9999: 15.928 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.517 ms/op
                 listUser·p0.9999: 11.179 ms/op
                 listUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319614
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 95182 
    [ 2.500,  3.750) = 184179 
    [ 3.750,  5.000) = 32176 
    [ 5.000,  6.250) = 6586 
    [ 6.250,  7.500) = 749 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 252 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     12.552 ms/op
     p(99.9990) =     16.715 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.534 ± 0.681  ops/ms
ClientPb.existUser                       thrpt       3  12.995 ± 2.251  ops/ms
ClientPb.getUser                         thrpt       3  12.646 ± 4.828  ops/ms
ClientPb.listUser                        thrpt       3  10.647 ± 1.286  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.092   ms/op
ClientPb.existUser                        avgt       3   2.476 ± 0.285   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.307   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.185   ms/op
ClientPb.createUser                     sample  380482   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.558           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.716           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.532           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.892           ms/op
ClientPb.existUser                      sample  394457   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.691           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.493           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.699           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  386949   2.479 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.824           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.119           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.950           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.145           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.008           ms/op
ClientPb.listUser                       sample  319614   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.710           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.552           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.170           ms/op
