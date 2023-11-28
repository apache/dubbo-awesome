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
# Warmup Iteration   1: 4.569 ops/ms
# Warmup Iteration   2: 11.786 ops/ms
# Warmup Iteration   3: 11.958 ops/ms
Iteration   1: 12.361 ops/ms
Iteration   2: 12.326 ops/ms
Iteration   3: 12.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.380 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (12.326, 12.380, 12.452), stdev = 0.065
  CI (99.9%): [11.193, 13.567] (assumes normal distribution)


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
# Warmup Iteration   1: 7.856 ops/ms
# Warmup Iteration   2: 12.755 ops/ms
# Warmup Iteration   3: 12.722 ops/ms
Iteration   1: 12.902 ops/ms
Iteration   2: 13.022 ops/ms
Iteration   3: 13.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.975 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (12.902, 12.975, 13.022), stdev = 0.064
  CI (99.9%): [11.812, 14.138] (assumes normal distribution)


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
# Warmup Iteration   1: 7.881 ops/ms
# Warmup Iteration   2: 12.814 ops/ms
# Warmup Iteration   3: 12.933 ops/ms
Iteration   1: 12.982 ops/ms
Iteration   2: 12.811 ops/ms
Iteration   3: 12.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.875 ±(99.9%) 1.712 ops/ms [Average]
  (min, avg, max) = (12.811, 12.875, 12.982), stdev = 0.094
  CI (99.9%): [11.162, 14.587] (assumes normal distribution)


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
# Warmup Iteration   1: 6.588 ops/ms
# Warmup Iteration   2: 10.272 ops/ms
# Warmup Iteration   3: 10.562 ops/ms
Iteration   1: 10.485 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.559 ±(99.9%) 1.353 ops/ms [Average]
  (min, avg, max) = (10.485, 10.559, 10.634), stdev = 0.074
  CI (99.9%): [9.205, 11.912] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
Iteration   1: 2.578 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
Iteration   3: 2.543 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (2.543, 2.557, 2.578), stdev = 0.019
  CI (99.9%): [2.212, 2.901] (assumes normal distribution)


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.503 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.484, 2.503, 2.519), stdev = 0.017
  CI (99.9%): [2.184, 2.821] (assumes normal distribution)


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.003 ms/op
Iteration   3: 2.527 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.506 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (2.475, 2.506, 2.527), stdev = 0.028
  CI (99.9%): [1.998, 3.014] (assumes normal distribution)


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
# Warmup Iteration   1: 4.810 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.005 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
Iteration   2: 3.029 ±(99.9%) 0.004 ms/op
Iteration   3: 2.992 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.032 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (2.992, 3.032, 3.074), stdev = 0.041
  CI (99.9%): [2.277, 3.787] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.686 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  12.191 ms/op
                 createUser·p0.9999: 14.489 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.432 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  9.797 ms/op
                 createUser·p0.9999: 11.812 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 12.313 ms/op
                 createUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377693
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 180520 
    [ 2.500,  3.750) = 191109 
    [ 3.750,  5.000) = 3998 
    [ 5.000,  6.250) = 1355 
    [ 6.250,  7.500) = 206 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      8.721 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     14.675 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.763 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  6.195 ms/op
                 existUser·p0.9999: 13.926 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  6.297 ms/op
                 existUser·p0.9999: 13.973 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.005 ms/op
                 existUser·p0.9999: 10.765 ms/op
                 existUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389872
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 195854 
    [ 2.500,  3.750) = 188904 
    [ 3.750,  5.000) = 3905 
    [ 5.000,  6.250) = 795 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      6.006 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 13.976 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.496 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.436 ms/op
                 getUser·p0.9999: 14.119 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   2.488 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  5.696 ms/op
                 getUser·p0.9999: 11.518 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384161
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 190148 
    [ 2.500,  3.750) = 189007 
    [ 3.750,  5.000) = 3796 
    [ 5.000,  6.250) = 694 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     13.936 ms/op
     p(99.9990) =     14.930 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.009 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.403 ms/op
                 listUser·p1.00:   12.648 ms/op

Iteration   2: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.790 ms/op
                 listUser·p0.9999: 11.903 ms/op
                 listUser·p1.00:   12.993 ms/op

Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.720 ms/op
                 listUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321892
  mean =      2.979 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 99917 
    [ 2.500,  3.750) = 184008 
    [ 3.750,  5.000) = 30641 
    [ 5.000,  6.250) = 5760 
    [ 6.250,  7.500) = 752 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.253 ms/op
     p(99.9990) =     12.903 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.380 ± 1.187  ops/ms
ClientPb.existUser                       thrpt       3  12.975 ± 1.163  ops/ms
ClientPb.getUser                         thrpt       3  12.875 ± 1.712  ops/ms
ClientPb.listUser                        thrpt       3  10.559 ± 1.353  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.345   ms/op
ClientPb.existUser                        avgt       3   2.503 ± 0.319   ms/op
ClientPb.getUser                          avgt       3   2.506 ± 0.508   ms/op
ClientPb.listUser                         avgt       3   3.032 ± 0.755   ms/op
ClientPb.createUser                     sample  377693   2.539 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.432           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.721           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.877           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  389872   2.460 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.786           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.006           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.681           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.729           ms/op
ClientPb.getUser                        sample  384161   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.496           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.487           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.204           ms/op
ClientPb.listUser                       sample  321892   2.979 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.912           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.253           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.993           ms/op
