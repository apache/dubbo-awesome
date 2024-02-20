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
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 11.953 ops/ms
# Warmup Iteration   3: 12.293 ops/ms
Iteration   1: 12.545 ops/ms
Iteration   2: 12.483 ops/ms
Iteration   3: 12.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.576 ±(99.9%) 2.046 ops/ms [Average]
  (min, avg, max) = (12.483, 12.576, 12.701), stdev = 0.112
  CI (99.9%): [10.531, 14.622] (assumes normal distribution)


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
# Warmup Iteration   1: 8.186 ops/ms
# Warmup Iteration   2: 12.993 ops/ms
# Warmup Iteration   3: 12.920 ops/ms
Iteration   1: 13.091 ops/ms
Iteration   2: 13.125 ops/ms
Iteration   3: 12.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.047 ±(99.9%) 1.957 ops/ms [Average]
  (min, avg, max) = (12.924, 13.047, 13.125), stdev = 0.107
  CI (99.9%): [11.089, 15.004] (assumes normal distribution)


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
# Warmup Iteration   1: 7.610 ops/ms
# Warmup Iteration   2: 12.520 ops/ms
# Warmup Iteration   3: 12.715 ops/ms
Iteration   1: 12.981 ops/ms
Iteration   2: 12.895 ops/ms
Iteration   3: 12.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.900 ±(99.9%) 1.450 ops/ms [Average]
  (min, avg, max) = (12.822, 12.900, 12.981), stdev = 0.079
  CI (99.9%): [11.449, 14.350] (assumes normal distribution)


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
# Warmup Iteration   1: 6.828 ops/ms
# Warmup Iteration   2: 10.557 ops/ms
# Warmup Iteration   3: 10.575 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.701 ops/ms
Iteration   3: 10.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.667 ±(99.9%) 0.539 ops/ms [Average]
  (min, avg, max) = (10.647, 10.667, 10.701), stdev = 0.030
  CI (99.9%): [10.128, 11.206] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (2.527, 2.538, 2.551), stdev = 0.012
  CI (99.9%): [2.314, 2.762] (assumes normal distribution)


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.440, 2.465, 2.485), stdev = 0.023
  CI (99.9%): [2.053, 2.877] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.005 ms/op
Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.539 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.521, 2.539, 2.558), stdev = 0.019
  CI (99.9%): [2.198, 2.879] (assumes normal distribution)


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
# Warmup Iteration   1: 4.932 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.004 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
Iteration   2: 2.970 ±(99.9%) 0.005 ms/op
Iteration   3: 2.975 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.045 ms/op [Average]
  (min, avg, max) = (2.970, 2.973, 2.975), stdev = 0.002
  CI (99.9%): [2.928, 3.019] (assumes normal distribution)


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  11.586 ms/op
                 createUser·p0.9999: 14.221 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  6.820 ms/op
                 createUser·p0.9999: 12.028 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  9.634 ms/op
                 createUser·p0.9999: 15.942 ms/op
                 createUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385622
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 189381 
    [ 2.500,  3.750) = 191885 
    [ 3.750,  5.000) = 3062 
    [ 5.000,  6.250) = 705 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     14.130 ms/op
     p(99.9990) =     16.450 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.006 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  5.612 ms/op
                 existUser·p0.9999: 14.184 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 13.359 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.582 ms/op
                 existUser·p0.999:  8.417 ms/op
                 existUser·p0.9999: 12.883 ms/op
                 existUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396356
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 201806 
    [ 2.500,  3.750) = 191499 
    [ 3.750,  5.000) = 2382 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.582 ms/op
     p(99.9000) =      5.805 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  7.940 ms/op
                 getUser·p0.9999: 13.798 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.292 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  5.819 ms/op
                 getUser·p0.9999: 10.162 ms/op
                 getUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385839
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 191268 
    [ 2.500,  3.750) = 190108 
    [ 3.750,  5.000) = 3431 
    [ 5.000,  6.250) = 554 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      7.573 ms/op
     p(99.9900) =     13.458 ms/op
     p(99.9990) =     14.245 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.845 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.362 ms/op
                 listUser·p0.9999: 11.858 ms/op
                 listUser·p1.00:   12.927 ms/op

Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.935 ms/op
                 listUser·p0.9999: 11.556 ms/op
                 listUser·p1.00:   12.583 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.731 ms/op
                 listUser·p0.9999: 11.229 ms/op
                 listUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318226
  mean =      3.014 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 92125 
    [ 2.500,  3.750) = 186479 
    [ 3.750,  5.000) = 32558 
    [ 5.000,  6.250) = 5642 
    [ 6.250,  7.500) = 608 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 238 
    [10.000, 11.250) = 192 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     11.537 ms/op
     p(99.9990) =     12.797 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.576 ± 2.046  ops/ms
ClientPb.existUser                       thrpt       3  13.047 ± 1.957  ops/ms
ClientPb.getUser                         thrpt       3  12.900 ± 1.450  ops/ms
ClientPb.listUser                        thrpt       3  10.667 ± 0.539  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.224   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.412   ms/op
ClientPb.getUser                          avgt       3   2.539 ± 0.340   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.045   ms/op
ClientPb.createUser                     sample  385622   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.936           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.130           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.646           ms/op
ClientPb.existUser                      sample  396356   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.828           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.582           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.805           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  385839   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.660           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.573           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.458           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  318226   3.014 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.683           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.537           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.927           ms/op
