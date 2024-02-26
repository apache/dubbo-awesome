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
# Warmup Iteration   1: 5.039 ops/ms
# Warmup Iteration   2: 11.773 ops/ms
# Warmup Iteration   3: 12.123 ops/ms
Iteration   1: 12.507 ops/ms
Iteration   2: 12.451 ops/ms
Iteration   3: 12.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.487 ±(99.9%) 0.573 ops/ms [Average]
  (min, avg, max) = (12.451, 12.487, 12.507), stdev = 0.031
  CI (99.9%): [11.914, 13.060] (assumes normal distribution)


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
# Warmup Iteration   1: 8.336 ops/ms
# Warmup Iteration   2: 13.162 ops/ms
# Warmup Iteration   3: 13.119 ops/ms
Iteration   1: 13.277 ops/ms
Iteration   2: 13.063 ops/ms
Iteration   3: 13.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.172 ±(99.9%) 1.959 ops/ms [Average]
  (min, avg, max) = (13.063, 13.172, 13.277), stdev = 0.107
  CI (99.9%): [11.212, 15.131] (assumes normal distribution)


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
# Warmup Iteration   1: 7.792 ops/ms
# Warmup Iteration   2: 12.534 ops/ms
# Warmup Iteration   3: 12.680 ops/ms
Iteration   1: 12.536 ops/ms
Iteration   2: 12.567 ops/ms
Iteration   3: 12.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.600 ±(99.9%) 1.555 ops/ms [Average]
  (min, avg, max) = (12.536, 12.600, 12.697), stdev = 0.085
  CI (99.9%): [11.045, 14.155] (assumes normal distribution)


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
# Warmup Iteration   1: 6.669 ops/ms
# Warmup Iteration   2: 10.393 ops/ms
# Warmup Iteration   3: 10.539 ops/ms
Iteration   1: 10.433 ops/ms
Iteration   2: 10.511 ops/ms
Iteration   3: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.507 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (10.433, 10.507, 10.578), stdev = 0.073
  CI (99.9%): [9.180, 11.834] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.004 ms/op
Iteration   1: 2.578 ±(99.9%) 0.004 ms/op
Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
Iteration   3: 2.563 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.567 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.560, 2.567, 2.578), stdev = 0.009
  CI (99.9%): [2.394, 2.740] (assumes normal distribution)


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.518 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (2.511, 2.518, 2.526), stdev = 0.008
  CI (99.9%): [2.380, 2.655] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (2.497, 2.521, 2.538), stdev = 0.022
  CI (99.9%): [2.127, 2.916] (assumes normal distribution)


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
# Warmup Iteration   1: 4.824 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.005 ms/op
Iteration   1: 3.052 ±(99.9%) 0.005 ms/op
Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
Iteration   3: 3.042 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.043 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (3.035, 3.043, 3.052), stdev = 0.008
  CI (99.9%): [2.891, 3.196] (assumes normal distribution)


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.701 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 13.795 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.734 ms/op
                 createUser·p0.9999: 11.884 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  8.029 ms/op
                 createUser·p0.9999: 9.994 ms/op
                 createUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379545
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 181739 
    [ 2.500,  3.750) = 193338 
    [ 3.750,  5.000) = 3590 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.060 ms/op
     p(99.9900) =     12.895 ms/op
     p(99.9990) =     13.989 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.006 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.507 ms/op
                 existUser·p0.999:  6.429 ms/op
                 existUser·p0.9999: 14.301 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  7.936 ms/op
                 existUser·p0.9999: 12.402 ms/op
                 existUser·p1.00:   13.058 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  8.905 ms/op
                 existUser·p0.9999: 11.993 ms/op
                 existUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390705
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 192506 
    [ 2.500,  3.750) = 194570 
    [ 3.750,  5.000) = 2583 
    [ 5.000,  6.250) = 513 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     14.780 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  11.663 ms/op
                 getUser·p0.9999: 14.057 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  8.964 ms/op
                 getUser·p0.9999: 14.031 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.420 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  8.655 ms/op
                 getUser·p0.9999: 10.916 ms/op
                 getUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380548
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 187222 
    [ 2.500,  3.750) = 189345 
    [ 3.750,  5.000) = 3156 
    [ 5.000,  6.250) = 338 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 135 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.691 ms/op
     p(99.9900) =     13.891 ms/op
     p(99.9990) =     14.712 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.728 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.009 ms/op
Iteration   1: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  8.964 ms/op
                 listUser·p0.9999: 15.333 ms/op
                 listUser·p1.00:   16.400 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.092 ms/op
                 listUser·p0.9999: 11.125 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   3: 3.112 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.208 ms/op
                 listUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311662
  mean =      3.078 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 82445 
    [ 2.500,  3.750) = 184688 
    [ 3.750,  5.000) = 35826 
    [ 5.000,  6.250) = 7057 
    [ 6.250,  7.500) = 924 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.197 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     16.131 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.487 ± 0.573  ops/ms
ClientPb.existUser                       thrpt       3  13.172 ± 1.959  ops/ms
ClientPb.getUser                         thrpt       3  12.600 ± 1.555  ops/ms
ClientPb.listUser                        thrpt       3  10.507 ± 1.327  ops/ms
ClientPb.createUser                       avgt       3   2.567 ± 0.173   ms/op
ClientPb.existUser                        avgt       3   2.518 ± 0.138   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.395   ms/op
ClientPb.listUser                         avgt       3   3.043 ± 0.153   ms/op
ClientPb.createUser                     sample  379545   2.527 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.694           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.060           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.895           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.303           ms/op
ClientPb.existUser                      sample  390705   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.909           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.765           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.124           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.893           ms/op
ClientPb.getUser                        sample  380548   2.521 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.420           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.691           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.891           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.877           ms/op
ClientPb.listUser                       sample  311662   3.078 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.932           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.197           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.550           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.400           ms/op
