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
# Warmup Iteration   1: 4.755 ops/ms
# Warmup Iteration   2: 12.030 ops/ms
# Warmup Iteration   3: 12.119 ops/ms
Iteration   1: 12.433 ops/ms
Iteration   2: 12.527 ops/ms
Iteration   3: 12.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.524 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (12.433, 12.524, 12.611), stdev = 0.089
  CI (99.9%): [10.902, 14.145] (assumes normal distribution)


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
# Warmup Iteration   1: 8.375 ops/ms
# Warmup Iteration   2: 13.019 ops/ms
# Warmup Iteration   3: 13.171 ops/ms
Iteration   1: 13.143 ops/ms
Iteration   2: 13.070 ops/ms
Iteration   3: 12.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.029 ±(99.9%) 2.529 ops/ms [Average]
  (min, avg, max) = (12.875, 13.029, 13.143), stdev = 0.139
  CI (99.9%): [10.501, 15.558] (assumes normal distribution)


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
# Warmup Iteration   1: 7.796 ops/ms
# Warmup Iteration   2: 12.643 ops/ms
# Warmup Iteration   3: 12.692 ops/ms
Iteration   1: 12.865 ops/ms
Iteration   2: 12.696 ops/ms
Iteration   3: 12.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.783 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (12.696, 12.783, 12.865), stdev = 0.085
  CI (99.9%): [11.233, 14.334] (assumes normal distribution)


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
# Warmup Iteration   1: 6.554 ops/ms
# Warmup Iteration   2: 10.367 ops/ms
# Warmup Iteration   3: 10.525 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.520 ops/ms
Iteration   3: 10.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.536 ±(99.9%) 1.213 ops/ms [Average]
  (min, avg, max) = (10.479, 10.536, 10.609), stdev = 0.067
  CI (99.9%): [9.322, 11.749] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.003 ms/op
Iteration   1: 2.568 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.003 ms/op
Iteration   3: 2.525 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (2.493, 2.529, 2.568), stdev = 0.038
  CI (99.9%): [1.843, 3.215] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (2.450, 2.458, 2.466), stdev = 0.008
  CI (99.9%): [2.318, 2.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.487, 2.492, 2.497), stdev = 0.005
  CI (99.9%): [2.396, 2.589] (assumes normal distribution)


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
Iteration   2: 2.995 ±(99.9%) 0.004 ms/op
Iteration   3: 2.988 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (2.988, 2.997, 3.008), stdev = 0.010
  CI (99.9%): [2.817, 3.176] (assumes normal distribution)


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  6.684 ms/op
                 createUser·p0.9999: 14.226 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  6.973 ms/op
                 createUser·p0.9999: 12.911 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  8.377 ms/op
                 createUser·p0.9999: 11.276 ms/op
                 createUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387784
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 189797 
    [ 2.500,  3.750) = 194708 
    [ 3.750,  5.000) = 2607 
    [ 5.000,  6.250) = 226 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      8.294 ms/op
     p(99.9900) =     13.488 ms/op
     p(99.9990) =     14.567 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  6.418 ms/op
                 existUser·p0.9999: 14.088 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.794 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.653 ms/op
                 existUser·p0.999:  8.466 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389851
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 193226 
    [ 2.500,  3.750) = 193768 
    [ 3.750,  5.000) = 2075 
    [ 5.000,  6.250) = 335 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      6.571 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     14.439 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  8.799 ms/op
                 getUser·p0.9999: 12.768 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  9.120 ms/op
                 getUser·p0.9999: 12.423 ms/op
                 getUser·p1.00:   12.829 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  7.410 ms/op
                 getUser·p0.9999: 10.489 ms/op
                 getUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384073
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 191729 
    [ 2.500,  3.750) = 188019 
    [ 3.750,  5.000) = 3531 
    [ 5.000,  6.250) = 310 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      7.459 ms/op
     p(99.9900) =     12.583 ms/op
     p(99.9990) =     13.327 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.008 ms/op
Iteration   1: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 10.984 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   2: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.776 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.483 ms/op
                 listUser·p0.9999: 11.000 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.467 ms/op
                 listUser·p0.9999: 11.518 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323580
  mean =      2.964 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 102247 
    [ 2.500,  3.750) = 185364 
    [ 3.750,  5.000) = 28908 
    [ 5.000,  6.250) = 5519 
    [ 6.250,  7.500) = 738 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 287 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.113 ms/op
     p(99.9990) =     11.711 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.524 ± 1.622  ops/ms
ClientPb.existUser                       thrpt       3  13.029 ± 2.529  ops/ms
ClientPb.getUser                         thrpt       3  12.783 ± 1.550  ops/ms
ClientPb.listUser                        thrpt       3  10.536 ± 1.213  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.686   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.140   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.097   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.179   ms/op
ClientPb.createUser                     sample  387784   2.473 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.968           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.294           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.488           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.680           ms/op
ClientPb.existUser                      sample  389851   2.460 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.933           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.571           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.681           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.729           ms/op
ClientPb.getUser                        sample  384073   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.889           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.459           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.583           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.730           ms/op
ClientPb.listUser                       sample  323580   2.964 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.776           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.113           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.222           ms/op
