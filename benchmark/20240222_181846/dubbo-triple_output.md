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
# Warmup Iteration   1: 4.751 ops/ms
# Warmup Iteration   2: 11.865 ops/ms
# Warmup Iteration   3: 12.260 ops/ms
Iteration   1: 12.472 ops/ms
Iteration   2: 12.372 ops/ms
Iteration   3: 12.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.416 ±(99.9%) 0.924 ops/ms [Average]
  (min, avg, max) = (12.372, 12.416, 12.472), stdev = 0.051
  CI (99.9%): [11.492, 13.341] (assumes normal distribution)


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
# Warmup Iteration   1: 8.236 ops/ms
# Warmup Iteration   2: 12.893 ops/ms
# Warmup Iteration   3: 12.832 ops/ms
Iteration   1: 13.043 ops/ms
Iteration   2: 12.932 ops/ms
Iteration   3: 13.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.012 ±(99.9%) 1.261 ops/ms [Average]
  (min, avg, max) = (12.932, 13.012, 13.059), stdev = 0.069
  CI (99.9%): [11.750, 14.273] (assumes normal distribution)


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
# Warmup Iteration   1: 7.996 ops/ms
# Warmup Iteration   2: 12.507 ops/ms
# Warmup Iteration   3: 12.713 ops/ms
Iteration   1: 12.795 ops/ms
Iteration   2: 12.725 ops/ms
Iteration   3: 12.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.808 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (12.725, 12.808, 12.903), stdev = 0.090
  CI (99.9%): [11.174, 14.442] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.710 ops/ms
# Warmup Iteration   2: 10.489 ops/ms
# Warmup Iteration   3: 10.691 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.694 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.656 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (10.576, 10.656, 10.698), stdev = 0.070
  CI (99.9%): [9.384, 11.928] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.003 ms/op
Iteration   1: 2.545 ±(99.9%) 0.003 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.518, 2.530, 2.545), stdev = 0.014
  CI (99.9%): [2.279, 2.781] (assumes normal distribution)


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.490 ±(99.9%) 0.067 ms/op [Average]
  (min, avg, max) = (2.486, 2.490, 2.492), stdev = 0.004
  CI (99.9%): [2.423, 2.557] (assumes normal distribution)


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
# Warmup Iteration   1: 4.154 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.004 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.519, 2.524, 2.529), stdev = 0.005
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.787 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.004 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
Iteration   3: 3.058 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.035, 3.044, 3.058), stdev = 0.012
  CI (99.9%): [2.828, 3.261] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.278 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.851 ms/op
                 createUser·p0.9999: 13.883 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  10.022 ms/op
                 createUser·p0.9999: 12.599 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 12.544 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377481
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 179928 
    [ 2.500,  3.750) = 193699 
    [ 3.750,  5.000) = 3003 
    [ 5.000,  6.250) = 358 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      9.167 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     16.182 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  5.175 ms/op
                 existUser·p0.9999: 14.109 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.643 ms/op
                 existUser·p0.999:  7.992 ms/op
                 existUser·p0.9999: 13.043 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  8.110 ms/op
                 existUser·p0.9999: 11.944 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388684
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 194248 
    [ 2.500,  3.750) = 191125 
    [ 3.750,  5.000) = 2548 
    [ 5.000,  6.250) = 308 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      6.900 ms/op
     p(99.9900) =     13.814 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 3.837 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  11.616 ms/op
                 getUser·p0.9999: 13.800 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  9.945 ms/op
                 getUser·p0.9999: 12.958 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  8.813 ms/op
                 getUser·p0.9999: 12.530 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378689
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 184805 
    [ 2.500,  3.750) = 187942 
    [ 3.750,  5.000) = 4661 
    [ 5.000,  6.250) = 796 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      8.956 ms/op
     p(99.9900) =     13.388 ms/op
     p(99.9990) =     14.126 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.883 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
Iteration   1: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.626 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 15.671 ms/op
                 listUser·p1.00:   16.384 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  10.020 ms/op
                 listUser·p0.9999: 11.312 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   3: 3.068 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.685 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.688 ms/op
                 listUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314545
  mean =      3.049 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 86108 
    [ 2.500,  3.750) = 186404 
    [ 3.750,  5.000) = 34217 
    [ 5.000,  6.250) = 6288 
    [ 6.250,  7.500) = 758 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 230 
    [10.000, 11.250) = 146 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     15.017 ms/op
     p(99.9990) =     15.986 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.416 ± 0.924  ops/ms
ClientPb.existUser                       thrpt       3  13.012 ± 1.261  ops/ms
ClientPb.getUser                         thrpt       3  12.808 ± 1.634  ops/ms
ClientPb.listUser                        thrpt       3  10.656 ± 1.272  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.251   ms/op
ClientPb.existUser                        avgt       3   2.490 ± 0.067   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.092   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.217   ms/op
ClientPb.createUser                     sample  377481   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.973           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.167           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.533           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.138           ms/op
ClientPb.existUser                      sample  388684   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.949           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.900           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.814           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.828           ms/op
ClientPb.getUser                        sample  378689   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.723           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.956           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.388           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.057           ms/op
ClientPb.listUser                       sample  314545   3.049 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.626           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.017           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.384           ms/op
