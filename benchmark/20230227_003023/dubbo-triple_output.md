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
# Warmup Iteration   1: 2.004 ops/ms
# Warmup Iteration   2: 4.913 ops/ms
# Warmup Iteration   3: 8.118 ops/ms
Iteration   1: 8.572 ops/ms
Iteration   2: 8.940 ops/ms
Iteration   3: 8.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.796 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (8.572, 8.796, 8.940), stdev = 0.196
  CI (99.9%): [5.216, 12.375] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.378 ops/ms
# Warmup Iteration   2: 7.497 ops/ms
# Warmup Iteration   3: 9.121 ops/ms
Iteration   1: 9.568 ops/ms
Iteration   2: 9.410 ops/ms
Iteration   3: 9.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.373 ±(99.9%) 3.943 ops/ms [Average]
  (min, avg, max) = (9.141, 9.373, 9.568), stdev = 0.216
  CI (99.9%): [5.430, 13.316] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.535 ops/ms
# Warmup Iteration   2: 7.224 ops/ms
# Warmup Iteration   3: 8.393 ops/ms
Iteration   1: 8.816 ops/ms
Iteration   2: 8.601 ops/ms
Iteration   3: 8.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.673 ±(99.9%) 2.255 ops/ms [Average]
  (min, avg, max) = (8.601, 8.673, 8.816), stdev = 0.124
  CI (99.9%): [6.418, 10.928] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.370 ops/ms
# Warmup Iteration   2: 6.418 ops/ms
# Warmup Iteration   3: 7.658 ops/ms
Iteration   1: 7.516 ops/ms
Iteration   2: 7.610 ops/ms
Iteration   3: 7.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.673 ±(99.9%) 3.587 ops/ms [Average]
  (min, avg, max) = (7.516, 7.673, 7.894), stdev = 0.197
  CI (99.9%): [4.086, 11.261] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.049 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.011 ms/op
Iteration   1: 3.702 ±(99.9%) 0.008 ms/op
Iteration   2: 3.528 ±(99.9%) 0.014 ms/op
Iteration   3: 3.421 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.550 ±(99.9%) 2.583 ms/op [Average]
  (min, avg, max) = (3.421, 3.550, 3.702), stdev = 0.142
  CI (99.9%): [0.967, 6.134] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.623 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.009 ms/op
Iteration   1: 3.428 ±(99.9%) 0.005 ms/op
Iteration   2: 3.427 ±(99.9%) 0.007 ms/op
Iteration   3: 3.441 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.432 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (3.427, 3.432, 3.441), stdev = 0.008
  CI (99.9%): [3.290, 3.574] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.953 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.009 ms/op
Iteration   1: 3.799 ±(99.9%) 0.006 ms/op
Iteration   2: 3.844 ±(99.9%) 0.005 ms/op
Iteration   3: 3.644 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.762 ±(99.9%) 1.916 ms/op [Average]
  (min, avg, max) = (3.644, 3.762, 3.844), stdev = 0.105
  CI (99.9%): [1.847, 5.678] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.650 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.889 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.404 ±(99.9%) 0.008 ms/op
Iteration   1: 4.142 ±(99.9%) 0.013 ms/op
Iteration   2: 4.217 ±(99.9%) 0.010 ms/op
Iteration   3: 4.382 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.247 ±(99.9%) 2.236 ms/op [Average]
  (min, avg, max) = (4.142, 4.247, 4.382), stdev = 0.123
  CI (99.9%): [2.011, 6.483] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.003 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.016 ms/op
Iteration   1: 3.544 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.338 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  22.976 ms/op
                 createUser·p0.9999: 24.707 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 3.556 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  24.159 ms/op
                 createUser·p0.9999: 28.444 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   3: 3.746 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  26.356 ms/op
                 createUser·p0.9999: 40.698 ms/op
                 createUser·p1.00:   42.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265944
  mean =      3.613 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 257580 
    [ 5.000, 10.000) = 7777 
    [10.000, 15.000) = 218 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 126 
    [25.000, 30.000) = 138 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 45 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.338 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     23.921 ms/op
     p(99.9900) =     39.152 ms/op
     p(99.9990) =     41.009 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.628 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.011 ms/op
Iteration   1: 3.325 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  18.616 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   2: 3.476 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  23.004 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.450 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.404 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  9.567 ms/op
                 existUser·p0.9999: 29.786 ms/op
                 existUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280940
  mean =      3.416 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11915 
    [ 2.500,  5.000) = 263204 
    [ 5.000,  7.500) = 4840 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     13.977 ms/op
     p(99.9900) =     27.751 ms/op
     p(99.9990) =     29.956 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.197 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.013 ms/op
Iteration   1: 3.672 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   7.333 ms/op
                 getUser·p0.999:  19.169 ms/op
                 getUser·p0.9999: 21.768 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   2: 3.701 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  21.268 ms/op
                 getUser·p0.9999: 24.425 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.695 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  11.765 ms/op
                 getUser·p0.9999: 30.933 ms/op
                 getUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 260028
  mean =      3.689 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3446 
    [ 2.500,  5.000) = 247543 
    [ 5.000,  7.500) = 7267 
    [ 7.500, 10.000) = 1150 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.789 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     31.903 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 12.531 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.510 ±(99.9%) 0.016 ms/op
Iteration   1: 4.443 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  24.052 ms/op
                 listUser·p0.9999: 26.804 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 4.242 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 21.019 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 4.199 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 26.030 ms/op
                 listUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223508
  mean =      4.292 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 206989 
    [ 5.000,  7.500) = 12928 
    [ 7.500, 10.000) = 2632 
    [10.000, 12.500) = 371 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     17.350 ms/op
     p(99.9900) =     26.596 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.796 ± 3.580  ops/ms
ClientPb.existUser                       thrpt       3   9.373 ± 3.943  ops/ms
ClientPb.getUser                         thrpt       3   8.673 ± 2.255  ops/ms
ClientPb.listUser                        thrpt       3   7.673 ± 3.587  ops/ms
ClientPb.createUser                       avgt       3   3.550 ± 2.583   ms/op
ClientPb.existUser                        avgt       3   3.432 ± 0.142   ms/op
ClientPb.getUser                          avgt       3   3.762 ± 1.916   ms/op
ClientPb.listUser                         avgt       3   4.247 ± 2.236   ms/op
ClientPb.createUser                     sample  265944   3.613 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.338           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.332           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.921           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.152           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.140           ms/op
ClientPb.existUser                      sample  280940   3.416 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.404           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.977           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.751           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.983           ms/op
ClientPb.getUser                        sample  260028   3.689 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.212           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.789           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.696           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.967           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342           ms/op
ClientPb.listUser                       sample  223508   4.292 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.176           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.350           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.596           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.132           ms/op
