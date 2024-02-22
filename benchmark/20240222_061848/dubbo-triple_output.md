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
# Warmup Iteration   1: 4.773 ops/ms
# Warmup Iteration   2: 12.236 ops/ms
# Warmup Iteration   3: 12.330 ops/ms
Iteration   1: 12.665 ops/ms
Iteration   2: 12.542 ops/ms
Iteration   3: 12.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.630 ±(99.9%) 1.388 ops/ms [Average]
  (min, avg, max) = (12.542, 12.630, 12.682), stdev = 0.076
  CI (99.9%): [11.241, 14.018] (assumes normal distribution)


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
# Warmup Iteration   1: 7.812 ops/ms
# Warmup Iteration   2: 12.847 ops/ms
# Warmup Iteration   3: 12.930 ops/ms
Iteration   1: 12.981 ops/ms
Iteration   2: 12.858 ops/ms
Iteration   3: 12.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.902 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (12.858, 12.902, 12.981), stdev = 0.068
  CI (99.9%): [11.658, 14.147] (assumes normal distribution)


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
# Warmup Iteration   1: 7.875 ops/ms
# Warmup Iteration   2: 12.676 ops/ms
# Warmup Iteration   3: 12.825 ops/ms
Iteration   1: 12.974 ops/ms
Iteration   2: 12.845 ops/ms
Iteration   3: 12.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.902 ±(99.9%) 1.195 ops/ms [Average]
  (min, avg, max) = (12.845, 12.902, 12.974), stdev = 0.065
  CI (99.9%): [11.707, 14.096] (assumes normal distribution)


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
# Warmup Iteration   1: 6.598 ops/ms
# Warmup Iteration   2: 10.337 ops/ms
# Warmup Iteration   3: 10.266 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.367 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (10.280, 10.367, 10.492), stdev = 0.111
  CI (99.9%): [8.347, 12.387] (assumes normal distribution)


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.496 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.481, 2.496, 2.509), stdev = 0.014
  CI (99.9%): [2.233, 2.760] (assumes normal distribution)


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.431 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.420, 2.427, 2.431), stdev = 0.006
  CI (99.9%): [2.321, 2.532] (assumes normal distribution)


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (2.482, 2.490, 2.496), stdev = 0.007
  CI (99.9%): [2.365, 2.614] (assumes normal distribution)


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.005 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
Iteration   3: 2.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.984, 2.987, 2.992), stdev = 0.004
  CI (99.9%): [2.906, 3.068] (assumes normal distribution)


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.676 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  11.174 ms/op
                 createUser·p0.9999: 13.357 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.457 ms/op
                 createUser·p0.999:  7.546 ms/op
                 createUser·p0.9999: 12.108 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  7.890 ms/op
                 createUser·p0.9999: 10.948 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385496
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 187030 
    [ 2.500,  3.750) = 194504 
    [ 3.750,  5.000) = 2932 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 106 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      7.803 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     13.494 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  5.860 ms/op
                 existUser·p0.9999: 13.827 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  8.551 ms/op
                 existUser·p0.9999: 13.091 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  5.787 ms/op
                 existUser·p0.9999: 11.125 ms/op
                 existUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390563
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 193904 
    [ 2.500,  3.750) = 193575 
    [ 3.750,  5.000) = 2228 
    [ 5.000,  6.250) = 446 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      6.135 ms/op
     p(99.9900) =     13.204 ms/op
     p(99.9990) =     13.961 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  5.930 ms/op
                 getUser·p0.9999: 13.486 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 2.527 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  10.461 ms/op
                 getUser·p0.9999: 13.446 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.625 ms/op
                 getUser·p0.999:  7.082 ms/op
                 getUser·p0.9999: 12.764 ms/op
                 getUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385747
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 191684 
    [ 2.500,  3.750) = 189431 
    [ 3.750,  5.000) = 3612 
    [ 5.000,  6.250) = 565 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      7.202 ms/op
     p(99.9900) =     13.245 ms/op
     p(99.9990) =     14.577 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.769 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.533 ms/op
                 listUser·p0.999:  9.127 ms/op
                 listUser·p0.9999: 10.974 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.468 ms/op
                 listUser·p0.999:  9.726 ms/op
                 listUser·p0.9999: 11.721 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.365 ms/op
                 listUser·p0.9999: 10.531 ms/op
                 listUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318501
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 91545 
    [ 2.500,  3.750) = 187625 
    [ 3.750,  5.000) = 32557 
    [ 5.000,  6.250) = 5414 
    [ 6.250,  7.500) = 578 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 161 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.174 ms/op
     p(99.9990) =     12.158 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.630 ± 1.388  ops/ms
ClientPb.existUser                       thrpt       3  12.902 ± 1.245  ops/ms
ClientPb.getUser                         thrpt       3  12.902 ± 1.195  ops/ms
ClientPb.listUser                        thrpt       3  10.367 ± 2.020  ops/ms
ClientPb.createUser                       avgt       3   2.496 ± 0.264   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.106   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.124   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.081   ms/op
ClientPb.createUser                     sample  385496   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.803           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.747           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.582           ms/op
ClientPb.existUser                      sample  390563   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.799           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.135           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.204           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.008           ms/op
ClientPb.getUser                        sample  385747   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.905           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.202           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.245           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.926           ms/op
ClientPb.listUser                       sample  318501   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.885           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.370           ms/op
