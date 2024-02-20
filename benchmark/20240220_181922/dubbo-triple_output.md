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
# Warmup Iteration   1: 5.150 ops/ms
# Warmup Iteration   2: 12.353 ops/ms
# Warmup Iteration   3: 12.587 ops/ms
Iteration   1: 12.814 ops/ms
Iteration   2: 12.913 ops/ms
Iteration   3: 12.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.879 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (12.814, 12.879, 12.913), stdev = 0.056
  CI (99.9%): [11.853, 13.906] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.126 ops/ms
# Warmup Iteration   2: 13.375 ops/ms
# Warmup Iteration   3: 13.516 ops/ms
Iteration   1: 13.251 ops/ms
Iteration   2: 13.219 ops/ms
Iteration   3: 13.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.260 ±(99.9%) 0.855 ops/ms [Average]
  (min, avg, max) = (13.219, 13.260, 13.311), stdev = 0.047
  CI (99.9%): [12.405, 14.116] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.157 ops/ms
# Warmup Iteration   2: 13.023 ops/ms
# Warmup Iteration   3: 13.098 ops/ms
Iteration   1: 13.134 ops/ms
Iteration   2: 13.212 ops/ms
Iteration   3: 13.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.202 ±(99.9%) 1.142 ops/ms [Average]
  (min, avg, max) = (13.134, 13.202, 13.258), stdev = 0.063
  CI (99.9%): [12.060, 14.344] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.024 ops/ms
# Warmup Iteration   2: 10.683 ops/ms
# Warmup Iteration   3: 10.853 ops/ms
Iteration   1: 10.891 ops/ms
Iteration   2: 10.901 ops/ms
Iteration   3: 10.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.882 ±(99.9%) 0.460 ops/ms [Average]
  (min, avg, max) = (10.854, 10.882, 10.901), stdev = 0.025
  CI (99.9%): [10.423, 11.342] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.818 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.003 ms/op
Iteration   3: 2.466 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.470 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.464, 2.470, 2.481), stdev = 0.009
  CI (99.9%): [2.301, 2.640] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.765 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.405 ±(99.9%) 0.003 ms/op
Iteration   1: 2.421 ±(99.9%) 0.004 ms/op
Iteration   2: 2.419 ±(99.9%) 0.003 ms/op
Iteration   3: 2.422 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.421 ±(99.9%) 0.026 ms/op [Average]
  (min, avg, max) = (2.419, 2.421, 2.422), stdev = 0.001
  CI (99.9%): [2.395, 2.446] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.451 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (2.442, 2.451, 2.463), stdev = 0.011
  CI (99.9%): [2.258, 2.644] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.775 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
Iteration   2: 2.970 ±(99.9%) 0.004 ms/op
Iteration   3: 2.981 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.978 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (2.970, 2.978, 2.983), stdev = 0.007
  CI (99.9%): [2.849, 3.107] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.086 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.423 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  8.334 ms/op
                 createUser·p0.9999: 14.295 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  9.682 ms/op
                 createUser·p0.9999: 12.009 ms/op
                 createUser·p1.00:   13.238 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.186 ms/op
                 createUser·p0.9999: 10.065 ms/op
                 createUser·p1.00:   10.650 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383591
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 186205 
    [ 2.500,  3.750) = 192328 
    [ 3.750,  5.000) = 3819 
    [ 5.000,  6.250) = 690 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 143 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     13.331 ms/op
     p(99.9990) =     14.786 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.818 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.005 ms/op
Iteration   1: 2.373 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.408 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  5.588 ms/op
                 existUser·p0.9999: 14.468 ms/op
                 existUser·p1.00:   16.007 ms/op

Iteration   2: 2.377 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.974 ms/op
                 existUser·p0.99:   3.369 ms/op
                 existUser·p0.999:  7.324 ms/op
                 existUser·p0.9999: 13.766 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  9.270 ms/op
                 existUser·p0.9999: 15.598 ms/op
                 existUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401725
  mean =      2.387 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 207847 
    [ 2.500,  3.750) = 191204 
    [ 3.750,  5.000) = 1908 
    [ 5.000,  6.250) = 252 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.506 ms/op
     p(99.9000) =      8.557 ms/op
     p(99.9900) =     14.478 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.006 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.006 ms/op
Iteration   1: 2.429 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  5.476 ms/op
                 getUser·p0.9999: 13.956 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  7.490 ms/op
                 getUser·p0.9999: 12.927 ms/op
                 getUser·p1.00:   13.435 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.429 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  5.814 ms/op
                 getUser·p0.9999: 11.610 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393702
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 200365 
    [ 2.500,  3.750) = 189826 
    [ 3.750,  5.000) = 2622 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      6.555 ms/op
     p(99.9900) =     13.175 ms/op
     p(99.9990) =     14.255 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.628 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
Iteration   1: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.547 ms/op
                 listUser·p0.9999: 12.222 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   2: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.711 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.565 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   3: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.742 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 12.947 ms/op
                 listUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324103
  mean =      2.959 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 102485 
    [ 2.500,  3.750) = 184757 
    [ 3.750,  5.000) = 29582 
    [ 5.000,  6.250) = 5791 
    [ 6.250,  7.500) = 615 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 301 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     12.222 ms/op
     p(99.9990) =     13.419 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.879 ± 1.027  ops/ms
ClientPb.existUser                       thrpt       3  13.260 ± 0.855  ops/ms
ClientPb.getUser                         thrpt       3  13.202 ± 1.142  ops/ms
ClientPb.listUser                        thrpt       3  10.882 ± 0.460  ops/ms
ClientPb.createUser                       avgt       3   2.470 ± 0.170   ms/op
ClientPb.existUser                        avgt       3   2.421 ± 0.026   ms/op
ClientPb.getUser                          avgt       3   2.451 ± 0.193   ms/op
ClientPb.listUser                         avgt       3   2.978 ± 0.129   ms/op
ClientPb.createUser                     sample  383591   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.423           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.331           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.877           ms/op
ClientPb.existUser                      sample  401725   2.387 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.801           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.433           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.557           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.478           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.613           ms/op
ClientPb.getUser                        sample  393702   2.436 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.887           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.458           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.966           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.678           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.555           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.175           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.287           ms/op
ClientPb.listUser                       sample  324103   2.959 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.711           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.222           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.090           ms/op
