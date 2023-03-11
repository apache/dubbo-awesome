# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.590 ops/ms
# Warmup Iteration   2: 6.371 ops/ms
# Warmup Iteration   3: 9.111 ops/ms
Iteration   1: 9.810 ops/ms
Iteration   2: 10.297 ops/ms
Iteration   3: 10.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.157 ±(99.9%) 5.515 ops/ms [Average]
  (min, avg, max) = (9.810, 10.157, 10.365), stdev = 0.302
  CI (99.9%): [4.642, 15.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.566 ops/ms
# Warmup Iteration   2: 9.296 ops/ms
# Warmup Iteration   3: 10.453 ops/ms
Iteration   1: 10.275 ops/ms
Iteration   2: 10.824 ops/ms
Iteration   3: 10.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.527 ±(99.9%) 5.055 ops/ms [Average]
  (min, avg, max) = (10.275, 10.527, 10.824), stdev = 0.277
  CI (99.9%): [5.472, 15.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 9.432 ops/ms
# Warmup Iteration   3: 10.216 ops/ms
Iteration   1: 9.862 ops/ms
Iteration   2: 9.838 ops/ms
Iteration   3: 10.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.975 ±(99.9%) 3.958 ops/ms [Average]
  (min, avg, max) = (9.838, 9.975, 10.225), stdev = 0.217
  CI (99.9%): [6.017, 13.933] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.562 ops/ms
# Warmup Iteration   2: 8.116 ops/ms
# Warmup Iteration   3: 8.422 ops/ms
Iteration   1: 8.781 ops/ms
Iteration   2: 8.853 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.729 ±(99.9%) 2.853 ops/ms [Average]
  (min, avg, max) = (8.554, 8.729, 8.853), stdev = 0.156
  CI (99.9%): [5.877, 11.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.621 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.003 ms/op
Iteration   1: 3.118 ±(99.9%) 0.006 ms/op
Iteration   2: 3.068 ±(99.9%) 0.009 ms/op
Iteration   3: 3.036 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.074 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.036, 3.074, 3.118), stdev = 0.041
  CI (99.9%): [2.320, 3.829] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.680 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.004 ms/op
Iteration   1: 3.133 ±(99.9%) 0.003 ms/op
Iteration   2: 3.083 ±(99.9%) 0.005 ms/op
Iteration   3: 3.019 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.078 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (3.019, 3.078, 3.133), stdev = 0.057
  CI (99.9%): [2.034, 4.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.028 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.004 ms/op
Iteration   1: 3.117 ±(99.9%) 0.002 ms/op
Iteration   2: 3.081 ±(99.9%) 0.003 ms/op
Iteration   3: 3.155 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.117 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (3.081, 3.117, 3.155), stdev = 0.037
  CI (99.9%): [2.450, 3.785] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.103 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.009 ms/op
Iteration   1: 3.579 ±(99.9%) 0.011 ms/op
Iteration   2: 3.565 ±(99.9%) 0.009 ms/op
Iteration   3: 3.733 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.626 ±(99.9%) 1.697 ms/op [Average]
  (min, avg, max) = (3.565, 3.626, 3.733), stdev = 0.093
  CI (99.9%): [1.929, 5.323] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.095 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.009 ms/op
Iteration   1: 3.210 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  11.367 ms/op
                 createUser·p0.9999: 19.367 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  11.487 ms/op
                 createUser·p0.9999: 22.873 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  15.375 ms/op
                 createUser·p0.9999: 17.749 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302734
  mean =      3.167 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14646 
    [ 2.500,  5.000) = 282041 
    [ 5.000,  7.500) = 5049 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.998 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
Iteration   1: 3.189 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 21.529 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  12.593 ms/op
                 existUser·p0.9999: 20.540 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.290 ms/op
                 existUser·p0.999:  8.514 ms/op
                 existUser·p0.9999: 20.261 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310753
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17105 
    [ 2.500,  5.000) = 287851 
    [ 5.000,  7.500) = 5071 
    [ 7.500, 10.000) = 284 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     20.936 ms/op
     p(99.9990) =     22.446 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.236 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.010 ms/op
Iteration   1: 3.192 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  18.598 ms/op
                 getUser·p0.9999: 39.715 ms/op
                 getUser·p1.00:   41.419 ms/op

Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.269 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  8.503 ms/op
                 getUser·p0.9999: 21.838 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  9.996 ms/op
                 getUser·p0.9999: 22.351 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304905
  mean =      3.148 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 300022 
    [ 5.000, 10.000) = 4497 
    [10.000, 15.000) = 55 
    [15.000, 20.000) = 103 
    [20.000, 25.000) = 172 
    [25.000, 30.000) = 27 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     29.983 ms/op
     p(99.9990) =     39.974 ms/op
     p(99.9999) =     41.419 ms/op
    p(100.0000) =     41.419 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.649 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.012 ms/op
Iteration   1: 3.635 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.092 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  16.909 ms/op
                 listUser·p0.9999: 20.126 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   2: 3.682 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 15.286 ms/op
                 listUser·p1.00:   15.942 ms/op

Iteration   3: 3.793 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 15.148 ms/op
                 listUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259040
  mean =      3.702 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 250972 
    [ 5.000,  7.500) = 6494 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     19.402 ms/op
     p(99.9990) =     21.553 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.157 ± 5.515  ops/ms
ClientPb.existUser                       thrpt       3  10.527 ± 5.055  ops/ms
ClientPb.getUser                         thrpt       3   9.975 ± 3.958  ops/ms
ClientPb.listUser                        thrpt       3   8.729 ± 2.853  ops/ms
ClientPb.createUser                       avgt       3   3.074 ± 0.754   ms/op
ClientPb.existUser                        avgt       3   3.078 ± 1.045   ms/op
ClientPb.getUser                          avgt       3   3.117 ± 0.668   ms/op
ClientPb.listUser                         avgt       3   3.626 ± 1.697   ms/op
ClientPb.createUser                     sample  302734   3.167 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.902           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.172           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.692           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  310753   3.087 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.936           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.936           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.643           ms/op
ClientPb.getUser                        sample  304905   3.148 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.531           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.407           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.153           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.983           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.419           ms/op
ClientPb.listUser                       sample  259040   3.702 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.325           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.562           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.516           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.402           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.019           ms/op
