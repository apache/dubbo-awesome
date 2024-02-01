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
# Warmup Iteration   1: 4.209 ops/ms
# Warmup Iteration   2: 12.287 ops/ms
# Warmup Iteration   3: 12.492 ops/ms
Iteration   1: 12.447 ops/ms
Iteration   2: 12.582 ops/ms
Iteration   3: 12.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.602 ±(99.9%) 3.032 ops/ms [Average]
  (min, avg, max) = (12.447, 12.602, 12.778), stdev = 0.166
  CI (99.9%): [9.570, 15.634] (assumes normal distribution)


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
# Warmup Iteration   1: 8.052 ops/ms
# Warmup Iteration   2: 13.217 ops/ms
# Warmup Iteration   3: 13.126 ops/ms
Iteration   1: 13.078 ops/ms
Iteration   2: 13.060 ops/ms
Iteration   3: 13.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.116 ±(99.9%) 1.497 ops/ms [Average]
  (min, avg, max) = (13.060, 13.116, 13.210), stdev = 0.082
  CI (99.9%): [11.620, 14.613] (assumes normal distribution)


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
# Warmup Iteration   1: 7.623 ops/ms
# Warmup Iteration   2: 12.544 ops/ms
# Warmup Iteration   3: 12.920 ops/ms
Iteration   1: 12.849 ops/ms
Iteration   2: 12.696 ops/ms
Iteration   3: 12.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.831 ±(99.9%) 2.305 ops/ms [Average]
  (min, avg, max) = (12.696, 12.831, 12.947), stdev = 0.126
  CI (99.9%): [10.526, 15.135] (assumes normal distribution)


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
# Warmup Iteration   1: 6.871 ops/ms
# Warmup Iteration   2: 10.618 ops/ms
# Warmup Iteration   3: 10.709 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.767 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.703 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (10.600, 10.703, 10.767), stdev = 0.090
  CI (99.9%): [9.062, 12.343] (assumes normal distribution)


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.003 ms/op
Iteration   1: 2.538 ±(99.9%) 0.004 ms/op
Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.530, 2.540, 2.554), stdev = 0.012
  CI (99.9%): [2.321, 2.759] (assumes normal distribution)


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.053 ms/op [Average]
  (min, avg, max) = (2.462, 2.465, 2.468), stdev = 0.003
  CI (99.9%): [2.412, 2.519] (assumes normal distribution)


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (2.465, 2.469, 2.474), stdev = 0.005
  CI (99.9%): [2.385, 2.552] (assumes normal distribution)


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
Iteration   3: 2.990 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.050 ms/op [Average]
  (min, avg, max) = (2.989, 2.991, 2.995), stdev = 0.003
  CI (99.9%): [2.942, 3.041] (assumes normal distribution)


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.696 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  11.381 ms/op
                 createUser·p0.9999: 13.944 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  9.781 ms/op
                 createUser·p0.9999: 12.573 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  8.524 ms/op
                 createUser·p0.9999: 12.134 ms/op
                 createUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379235
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 183092 
    [ 2.500,  3.750) = 192734 
    [ 3.750,  5.000) = 2681 
    [ 5.000,  6.250) = 227 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      8.598 ms/op
     p(99.9900) =     13.633 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  9.726 ms/op
                 existUser·p0.9999: 13.970 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.156 ms/op
                 existUser·p0.9999: 13.091 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.305 ms/op
                 existUser·p0.9999: 13.060 ms/op
                 existUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387632
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 193193 
    [ 2.500,  3.750) = 191636 
    [ 3.750,  5.000) = 2124 
    [ 5.000,  6.250) = 178 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 150 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      7.802 ms/op
     p(99.9900) =     13.606 ms/op
     p(99.9990) =     14.111 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.939 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  11.526 ms/op
                 getUser·p0.9999: 14.077 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  8.706 ms/op
                 getUser·p0.9999: 11.822 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.195 ms/op
                 getUser·p0.9999: 10.890 ms/op
                 getUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381448
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 187931 
    [ 2.500,  3.750) = 186618 
    [ 3.750,  5.000) = 5019 
    [ 5.000,  6.250) = 1344 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.246 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     14.397 ms/op
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
# Warmup Iteration   1: 4.682 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.570 ms/op
                 listUser·p0.9999: 10.538 ms/op
                 listUser·p1.00:   10.961 ms/op

Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.834 ms/op
                 listUser·p0.9999: 11.541 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.459 ms/op
                 listUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320863
  mean =      2.989 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 94628 
    [ 2.500,  3.750) = 188494 
    [ 3.750,  5.000) = 30651 
    [ 5.000,  6.250) = 5514 
    [ 6.250,  7.500) = 757 
    [ 7.500,  8.750) = 256 
    [ 8.750, 10.000) = 238 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.190 ms/op
     p(99.9990) =     11.897 ms/op
     p(99.9999) =     12.861 ms/op
    p(100.0000) =     12.861 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.602 ± 3.032  ops/ms
ClientPb.existUser                       thrpt       3  13.116 ± 1.497  ops/ms
ClientPb.getUser                         thrpt       3  12.831 ± 2.305  ops/ms
ClientPb.listUser                        thrpt       3  10.703 ± 1.641  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.219   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.053   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.083   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.050   ms/op
ClientPb.createUser                     sample  379235   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.809           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.598           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.633           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.663           ms/op
ClientPb.existUser                      sample  387632   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.757           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.802           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.606           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  381448   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.797           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.246           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.796           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  320863   2.989 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.838           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.190           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.861           ms/op
