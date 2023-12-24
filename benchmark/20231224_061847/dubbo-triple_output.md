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
# Warmup Iteration   1: 4.811 ops/ms
# Warmup Iteration   2: 11.996 ops/ms
# Warmup Iteration   3: 12.157 ops/ms
Iteration   1: 12.168 ops/ms
Iteration   2: 12.256 ops/ms
Iteration   3: 12.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.230 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (12.168, 12.230, 12.265), stdev = 0.053
  CI (99.9%): [11.259, 13.200] (assumes normal distribution)


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
# Warmup Iteration   1: 8.054 ops/ms
# Warmup Iteration   2: 12.739 ops/ms
# Warmup Iteration   3: 12.718 ops/ms
Iteration   1: 12.615 ops/ms
Iteration   2: 12.708 ops/ms
Iteration   3: 12.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.688 ±(99.9%) 1.178 ops/ms [Average]
  (min, avg, max) = (12.615, 12.688, 12.740), stdev = 0.065
  CI (99.9%): [11.510, 13.865] (assumes normal distribution)


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
# Warmup Iteration   1: 7.764 ops/ms
# Warmup Iteration   2: 12.110 ops/ms
# Warmup Iteration   3: 12.630 ops/ms
Iteration   1: 12.613 ops/ms
Iteration   2: 12.501 ops/ms
Iteration   3: 12.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.535 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (12.490, 12.535, 12.613), stdev = 0.068
  CI (99.9%): [11.292, 13.777] (assumes normal distribution)


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
# Warmup Iteration   1: 6.246 ops/ms
# Warmup Iteration   2: 10.126 ops/ms
# Warmup Iteration   3: 10.240 ops/ms
Iteration   1: 10.205 ops/ms
Iteration   2: 10.319 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.271 ±(99.9%) 1.074 ops/ms [Average]
  (min, avg, max) = (10.205, 10.271, 10.319), stdev = 0.059
  CI (99.9%): [9.197, 11.345] (assumes normal distribution)


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.572 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.521 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (2.485, 2.521, 2.572), stdev = 0.045
  CI (99.9%): [1.698, 3.345] (assumes normal distribution)


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.525 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.525 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (2.522, 2.525, 2.529), stdev = 0.004
  CI (99.9%): [2.460, 2.591] (assumes normal distribution)


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
Iteration   3: 2.553 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.553 ±(99.9%) 0.043 ms/op [Average]
  (min, avg, max) = (2.551, 2.553, 2.555), stdev = 0.002
  CI (99.9%): [2.510, 2.596] (assumes normal distribution)


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
# Warmup Iteration   1: 4.878 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.005 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
Iteration   3: 3.083 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.089 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (3.072, 3.089, 3.112), stdev = 0.020
  CI (99.9%): [2.719, 3.459] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  11.602 ms/op
                 createUser·p0.9999: 14.091 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  9.511 ms/op
                 createUser·p0.9999: 13.587 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 12.403 ms/op
                 createUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376040
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 180067 
    [ 2.500,  3.750) = 191584 
    [ 3.750,  5.000) = 3429 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      9.256 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.605 ms/op
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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.117 ms/op
                 existUser·p0.95:   3.240 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  5.538 ms/op
                 existUser·p0.9999: 14.615 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   3.125 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  9.652 ms/op
                 existUser·p0.9999: 16.482 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.451 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  8.130 ms/op
                 existUser·p0.9999: 13.110 ms/op
                 existUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 380844
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 196137 
    [ 2.500,  3.750) = 179370 
    [ 3.750,  5.000) = 4167 
    [ 5.000,  6.250) = 655 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      6.660 ms/op
     p(99.9900) =     15.449 ms/op
     p(99.9990) =     17.183 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.006 ms/op
Iteration   1: 2.588 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.032 ms/op
                 getUser·p0.999:  11.862 ms/op
                 getUser·p0.9999: 16.301 ms/op
                 getUser·p1.00:   16.810 ms/op

Iteration   2: 2.584 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  9.695 ms/op
                 getUser·p0.9999: 13.435 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  8.945 ms/op
                 getUser·p0.9999: 11.403 ms/op
                 getUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 372326
  mean =      2.576 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 179799 
    [ 2.500,  3.750) = 187412 
    [ 3.750,  5.000) = 4038 
    [ 5.000,  6.250) = 607 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      9.132 ms/op
     p(99.9900) =     14.246 ms/op
     p(99.9990) =     16.519 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 5.086 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.009 ms/op
Iteration   1: 3.086 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  8.854 ms/op
                 listUser·p0.9999: 11.878 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.291 ms/op
                 listUser·p0.9999: 11.610 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   3: 3.106 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  9.720 ms/op
                 listUser·p0.9999: 13.079 ms/op
                 listUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310469
  mean =      3.089 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 76383 
    [ 2.500,  3.750) = 190711 
    [ 3.750,  5.000) = 35204 
    [ 5.000,  6.250) = 6421 
    [ 6.250,  7.500) = 1022 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 208 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      9.315 ms/op
     p(99.9900) =     11.829 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.230 ± 0.971  ops/ms
ClientPb.existUser                       thrpt       3  12.688 ± 1.178  ops/ms
ClientPb.getUser                         thrpt       3  12.535 ± 1.243  ops/ms
ClientPb.listUser                        thrpt       3  10.271 ± 1.074  ops/ms
ClientPb.createUser                       avgt       3   2.521 ± 0.824   ms/op
ClientPb.existUser                        avgt       3   2.525 ± 0.065   ms/op
ClientPb.getUser                          avgt       3   2.553 ± 0.043   ms/op
ClientPb.listUser                         avgt       3   3.089 ± 0.370   ms/op
ClientPb.createUser                     sample  376040   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.604           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.256           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.763           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.352           ms/op
ClientPb.existUser                      sample  380844   2.518 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.451           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.660           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.449           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.302           ms/op
ClientPb.getUser                        sample  372326   2.576 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.934           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.132           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.246           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.810           ms/op
ClientPb.listUser                       sample  310469   3.089 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.849           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.315           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.829           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.550           ms/op
