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
# Warmup Iteration   1: 4.962 ops/ms
# Warmup Iteration   2: 12.009 ops/ms
# Warmup Iteration   3: 12.238 ops/ms
Iteration   1: 12.555 ops/ms
Iteration   2: 12.553 ops/ms
Iteration   3: 12.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.604 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (12.553, 12.604, 12.702), stdev = 0.085
  CI (99.9%): [11.047, 14.160] (assumes normal distribution)


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
# Warmup Iteration   1: 7.960 ops/ms
# Warmup Iteration   2: 12.891 ops/ms
# Warmup Iteration   3: 12.994 ops/ms
Iteration   1: 12.920 ops/ms
Iteration   2: 12.997 ops/ms
Iteration   3: 13.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.987 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (12.920, 12.987, 13.044), stdev = 0.063
  CI (99.9%): [11.843, 14.132] (assumes normal distribution)


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
# Warmup Iteration   1: 7.863 ops/ms
# Warmup Iteration   2: 12.504 ops/ms
# Warmup Iteration   3: 12.769 ops/ms
Iteration   1: 12.840 ops/ms
Iteration   2: 12.742 ops/ms
Iteration   3: 12.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.809 ±(99.9%) 1.047 ops/ms [Average]
  (min, avg, max) = (12.742, 12.809, 12.843), stdev = 0.057
  CI (99.9%): [11.761, 13.856] (assumes normal distribution)


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
# Warmup Iteration   1: 6.746 ops/ms
# Warmup Iteration   2: 10.654 ops/ms
# Warmup Iteration   3: 10.649 ops/ms
Iteration   1: 10.747 ops/ms
Iteration   2: 10.715 ops/ms
Iteration   3: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.670 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (10.548, 10.670, 10.747), stdev = 0.107
  CI (99.9%): [8.726, 12.614] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.003 ms/op
Iteration   1: 2.522 ±(99.9%) 0.003 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.551 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.522, 2.538, 2.551), stdev = 0.015
  CI (99.9%): [2.273, 2.802] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.696 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.003 ms/op
Iteration   1: 2.464 ±(99.9%) 0.003 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (2.455, 2.462, 2.467), stdev = 0.006
  CI (99.9%): [2.344, 2.581] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.476, 2.486, 2.499), stdev = 0.012
  CI (99.9%): [2.273, 2.699] (assumes normal distribution)


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
# Warmup Iteration   1: 4.656 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.005 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
Iteration   3: 3.064 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.038 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (3.025, 3.038, 3.064), stdev = 0.023
  CI (99.9%): [2.627, 3.450] (assumes normal distribution)


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
Iteration   1: 2.508 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  11.773 ms/op
                 createUser·p0.9999: 13.517 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  10.426 ms/op
                 createUser·p0.9999: 12.591 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  8.614 ms/op
                 createUser·p0.9999: 10.403 ms/op
                 createUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382742
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 186223 
    [ 2.500,  3.750) = 192135 
    [ 3.750,  5.000) = 3520 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     13.782 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.692 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.456 ms/op
                 existUser·p0.9999: 14.141 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 12.698 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  9.880 ms/op
                 existUser·p0.9999: 12.337 ms/op
                 existUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388567
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 192335 
    [ 2.500,  3.750) = 193163 
    [ 3.750,  5.000) = 2255 
    [ 5.000,  6.250) = 356 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 134 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      7.482 ms/op
     p(99.9900) =     13.175 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  5.536 ms/op
                 getUser·p0.9999: 13.620 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 2.550 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  10.322 ms/op
                 getUser·p0.9999: 23.739 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  7.983 ms/op
                 getUser·p0.9999: 11.681 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380210
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186880 
    [ 2.500,  5.000) = 191861 
    [ 5.000,  7.500) = 1117 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      6.544 ms/op
     p(99.9900) =     14.250 ms/op
     p(99.9990) =     24.025 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 4.775 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.009 ms/op
Iteration   1: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.909 ms/op
                 listUser·p0.9999: 10.726 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 10.884 ms/op
                 listUser·p1.00:   12.026 ms/op

Iteration   3: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.746 ms/op
                 listUser·p0.9999: 14.603 ms/op
                 listUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321253
  mean =      2.985 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 95996 
    [ 2.500,  3.750) = 188033 
    [ 3.750,  5.000) = 30319 
    [ 5.000,  6.250) = 5457 
    [ 6.250,  7.500) = 632 
    [ 7.500,  8.750) = 207 
    [ 8.750, 10.000) = 327 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     13.117 ms/op
     p(99.9990) =     15.495 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.604 ± 1.556  ops/ms
ClientPb.existUser                       thrpt       3  12.987 ± 1.145  ops/ms
ClientPb.getUser                         thrpt       3  12.809 ± 1.047  ops/ms
ClientPb.listUser                        thrpt       3  10.670 ± 1.944  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.265   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.118   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.213   ms/op
ClientPb.listUser                         avgt       3   3.038 ± 0.412   ms/op
ClientPb.createUser                     sample  382742   2.506 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.844           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.651           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.943           ms/op
ClientPb.existUser                      sample  388567   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.881           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.482           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.175           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.762           ms/op
ClientPb.getUser                        sample  380210   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.544           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.250           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.642           ms/op
ClientPb.listUser                       sample  321253   2.985 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.886           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.117           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.942           ms/op
