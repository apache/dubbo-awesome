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
# Warmup Iteration   1: 4.948 ops/ms
# Warmup Iteration   2: 12.172 ops/ms
# Warmup Iteration   3: 12.241 ops/ms
Iteration   1: 12.604 ops/ms
Iteration   2: 12.579 ops/ms
Iteration   3: 12.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.612 ±(99.9%) 0.688 ops/ms [Average]
  (min, avg, max) = (12.579, 12.612, 12.653), stdev = 0.038
  CI (99.9%): [11.924, 13.300] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.117 ops/ms
# Warmup Iteration   2: 13.136 ops/ms
# Warmup Iteration   3: 13.204 ops/ms
Iteration   1: 13.214 ops/ms
Iteration   2: 13.214 ops/ms
Iteration   3: 13.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.200 ±(99.9%) 0.424 ops/ms [Average]
  (min, avg, max) = (13.174, 13.200, 13.214), stdev = 0.023
  CI (99.9%): [12.777, 13.624] (assumes normal distribution)


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
# Warmup Iteration   1: 8.003 ops/ms
# Warmup Iteration   2: 12.494 ops/ms
# Warmup Iteration   3: 13.070 ops/ms
Iteration   1: 12.912 ops/ms
Iteration   2: 13.110 ops/ms
Iteration   3: 13.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.042 ±(99.9%) 2.064 ops/ms [Average]
  (min, avg, max) = (12.912, 13.042, 13.110), stdev = 0.113
  CI (99.9%): [10.979, 15.106] (assumes normal distribution)


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
# Warmup Iteration   1: 6.981 ops/ms
# Warmup Iteration   2: 10.584 ops/ms
# Warmup Iteration   3: 10.805 ops/ms
Iteration   1: 10.660 ops/ms
Iteration   2: 10.748 ops/ms
Iteration   3: 10.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.680 ±(99.9%) 1.091 ops/ms [Average]
  (min, avg, max) = (10.634, 10.680, 10.748), stdev = 0.060
  CI (99.9%): [9.590, 11.771] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.558 ±(99.9%) 0.004 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.535 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.516, 2.535, 2.558), stdev = 0.021
  CI (99.9%): [2.151, 2.920] (assumes normal distribution)


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.410 ±(99.9%) 0.004 ms/op
Iteration   3: 2.398 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.411 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.398, 2.411, 2.424), stdev = 0.013
  CI (99.9%): [2.171, 2.650] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.473 ±(99.9%) 0.003 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.453, 2.467, 2.475), stdev = 0.012
  CI (99.9%): [2.247, 2.687] (assumes normal distribution)


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
# Warmup Iteration   1: 4.682 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.005 ms/op
Iteration   1: 3.007 ±(99.9%) 0.005 ms/op
Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
Iteration   3: 2.964 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (2.964, 2.982, 3.007), stdev = 0.022
  CI (99.9%): [2.574, 3.390] (assumes normal distribution)


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  9.335 ms/op
                 createUser·p0.9999: 14.326 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  7.164 ms/op
                 createUser·p0.9999: 13.157 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  8.052 ms/op
                 createUser·p0.9999: 10.649 ms/op
                 createUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388187
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 189970 
    [ 2.500,  3.750) = 194944 
    [ 3.750,  5.000) = 2444 
    [ 5.000,  6.250) = 324 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      8.041 ms/op
     p(99.9900) =     13.618 ms/op
     p(99.9990) =     14.766 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  5.394 ms/op
                 existUser·p0.9999: 13.470 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  7.373 ms/op
                 existUser·p0.9999: 12.919 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.106 ms/op
                 existUser·p0.9999: 11.697 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393254
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 196070 
    [ 2.500,  3.750) = 193741 
    [ 3.750,  5.000) = 2618 
    [ 5.000,  6.250) = 375 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      6.330 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     13.740 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  7.603 ms/op
                 getUser·p0.9999: 15.041 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  7.473 ms/op
                 getUser·p0.9999: 13.766 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.821 ms/op
                 getUser·p0.9999: 10.813 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387764
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 194290 
    [ 2.500,  3.750) = 189258 
    [ 3.750,  5.000) = 3188 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      7.234 ms/op
     p(99.9900) =     14.159 ms/op
     p(99.9990) =     15.864 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.575 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.008 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.940 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.789 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 10.908 ms/op
                 listUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322859
  mean =      2.971 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 100911 
    [ 2.500,  3.750) = 184944 
    [ 3.750,  5.000) = 29940 
    [ 5.000,  6.250) = 5603 
    [ 6.250,  7.500) = 627 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 205 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     10.977 ms/op
     p(99.9990) =     11.696 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.612 ± 0.688  ops/ms
ClientPb.existUser                       thrpt       3  13.200 ± 0.424  ops/ms
ClientPb.getUser                         thrpt       3  13.042 ± 2.064  ops/ms
ClientPb.listUser                        thrpt       3  10.680 ± 1.091  ops/ms
ClientPb.createUser                       avgt       3   2.535 ± 0.384   ms/op
ClientPb.existUser                        avgt       3   2.411 ± 0.240   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.220   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.408   ms/op
ClientPb.createUser                     sample  388187   2.471 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.748           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.041           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.618           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.155           ms/op
ClientPb.existUser                      sample  393254   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.961           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.330           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.861           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.992           ms/op
ClientPb.getUser                        sample  387764   2.474 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.703           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.234           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.159           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.974           ms/op
ClientPb.listUser                       sample  322859   2.971 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.890           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.190           ms/op
