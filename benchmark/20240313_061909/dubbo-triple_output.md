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
# Warmup Iteration   1: 4.549 ops/ms
# Warmup Iteration   2: 12.352 ops/ms
# Warmup Iteration   3: 12.615 ops/ms
Iteration   1: 12.936 ops/ms
Iteration   2: 12.846 ops/ms
Iteration   3: 12.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.906 ±(99.9%) 0.949 ops/ms [Average]
  (min, avg, max) = (12.846, 12.906, 12.937), stdev = 0.052
  CI (99.9%): [11.957, 13.856] (assumes normal distribution)


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
# Warmup Iteration   1: 8.063 ops/ms
# Warmup Iteration   2: 13.369 ops/ms
# Warmup Iteration   3: 13.410 ops/ms
Iteration   1: 13.441 ops/ms
Iteration   2: 13.457 ops/ms
Iteration   3: 13.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.449 ±(99.9%) 0.146 ops/ms [Average]
  (min, avg, max) = (13.441, 13.449, 13.457), stdev = 0.008
  CI (99.9%): [13.303, 13.595] (assumes normal distribution)


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
# Warmup Iteration   1: 7.650 ops/ms
# Warmup Iteration   2: 12.803 ops/ms
# Warmup Iteration   3: 13.058 ops/ms
Iteration   1: 13.012 ops/ms
Iteration   2: 13.123 ops/ms
Iteration   3: 13.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.057 ±(99.9%) 1.067 ops/ms [Average]
  (min, avg, max) = (13.012, 13.057, 13.123), stdev = 0.059
  CI (99.9%): [11.990, 14.125] (assumes normal distribution)


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
# Warmup Iteration   1: 6.913 ops/ms
# Warmup Iteration   2: 10.707 ops/ms
# Warmup Iteration   3: 10.780 ops/ms
Iteration   1: 10.781 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.769 ±(99.9%) 0.526 ops/ms [Average]
  (min, avg, max) = (10.736, 10.769, 10.789), stdev = 0.029
  CI (99.9%): [10.243, 11.295] (assumes normal distribution)


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.003 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.479 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.469, 2.479, 2.497), stdev = 0.016
  CI (99.9%): [2.191, 2.767] (assumes normal distribution)


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
# Warmup Iteration   1: 3.562 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.368 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.336 ±(99.9%) 0.004 ms/op
Iteration   1: 2.366 ±(99.9%) 0.004 ms/op
Iteration   2: 2.350 ±(99.9%) 0.003 ms/op
Iteration   3: 2.368 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.361 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.350, 2.361, 2.368), stdev = 0.010
  CI (99.9%): [2.179, 2.543] (assumes normal distribution)


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
# Warmup Iteration   1: 3.678 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.002 ms/op
Iteration   2: 2.420 ±(99.9%) 0.003 ms/op
Iteration   3: 2.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.426 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.420, 2.426, 2.437), stdev = 0.010
  CI (99.9%): [2.252, 2.600] (assumes normal distribution)


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
# Warmup Iteration   1: 4.588 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
Iteration   2: 2.968 ±(99.9%) 0.005 ms/op
Iteration   3: 2.960 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.967 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.960, 2.967, 2.971), stdev = 0.006
  CI (99.9%): [2.861, 3.072] (assumes normal distribution)


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.949 ms/op
                 createUser·p0.95:   3.043 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  6.431 ms/op
                 createUser·p0.9999: 13.479 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   3.449 ms/op
                 createUser·p0.999:  6.775 ms/op
                 createUser·p0.9999: 12.186 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  8.736 ms/op
                 createUser·p0.9999: 10.338 ms/op
                 createUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 392387
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 192801 
    [ 2.500,  3.750) = 196876 
    [ 3.750,  5.000) = 1995 
    [ 5.000,  6.250) = 227 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =      7.770 ms/op
     p(99.9900) =     12.907 ms/op
     p(99.9990) =     14.442 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.407 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.391 ±(99.9%) 0.005 ms/op
Iteration   1: 2.351 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.843 ms/op
                 existUser·p0.95:   2.937 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  5.554 ms/op
                 existUser·p0.9999: 13.212 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   2: 2.380 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  5.695 ms/op
                 existUser·p0.9999: 13.142 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.361 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.855 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  7.048 ms/op
                 existUser·p0.9999: 11.887 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 405626
  mean =      2.364 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 208777 
    [ 2.500,  3.750) = 194537 
    [ 3.750,  5.000) = 1697 
    [ 5.000,  6.250) = 129 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 159 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      3.420 ms/op
     p(99.9000) =      6.884 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  12.157 ms/op
                 getUser·p0.9999: 14.795 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  6.211 ms/op
                 getUser·p0.9999: 11.607 ms/op
                 getUser·p1.00:   12.059 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  5.584 ms/op
                 getUser·p0.9999: 12.466 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392468
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 198285 
    [ 2.500,  3.750) = 190517 
    [ 3.750,  5.000) = 2839 
    [ 5.000,  6.250) = 322 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      6.911 ms/op
     p(99.9900) =     13.849 ms/op
     p(99.9990) =     15.245 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.008 ms/op
Iteration   1: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.022 ms/op
                 listUser·p0.9999: 12.060 ms/op
                 listUser·p1.00:   13.468 ms/op

Iteration   2: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.445 ms/op
                 listUser·p0.9999: 11.300 ms/op
                 listUser·p1.00:   13.058 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324051
  mean =      2.960 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 101466 
    [ 2.500,  3.750) = 185728 
    [ 3.750,  5.000) = 29989 
    [ 5.000,  6.250) = 5473 
    [ 6.250,  7.500) = 588 
    [ 7.500,  8.750) = 179 
    [ 8.750, 10.000) = 287 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.318 ms/op
     p(99.9990) =     13.282 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.906 ± 0.949  ops/ms
ClientPb.existUser                       thrpt       3  13.449 ± 0.146  ops/ms
ClientPb.getUser                         thrpt       3  13.057 ± 1.067  ops/ms
ClientPb.listUser                        thrpt       3  10.769 ± 0.526  ops/ms
ClientPb.createUser                       avgt       3   2.479 ± 0.288   ms/op
ClientPb.existUser                        avgt       3   2.361 ± 0.182   ms/op
ClientPb.getUser                          avgt       3   2.426 ± 0.174   ms/op
ClientPb.listUser                         avgt       3   2.967 ± 0.106   ms/op
ClientPb.createUser                     sample  392387   2.445 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.651           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.770           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.907           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.778           ms/op
ClientPb.existUser                      sample  405626   2.364 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.912           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.863           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.884           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.878           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.779           ms/op
ClientPb.getUser                        sample  392468   2.444 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.530           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.978           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.911           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.849           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.401           ms/op
ClientPb.listUser                       sample  324051   2.960 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.318           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
