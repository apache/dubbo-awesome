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
# Warmup Iteration   1: 4.659 ops/ms
# Warmup Iteration   2: 12.151 ops/ms
# Warmup Iteration   3: 12.335 ops/ms
Iteration   1: 12.721 ops/ms
Iteration   2: 12.477 ops/ms
Iteration   3: 12.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.636 ±(99.9%) 2.522 ops/ms [Average]
  (min, avg, max) = (12.477, 12.636, 12.721), stdev = 0.138
  CI (99.9%): [10.114, 15.158] (assumes normal distribution)


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
# Warmup Iteration   1: 8.380 ops/ms
# Warmup Iteration   2: 13.137 ops/ms
# Warmup Iteration   3: 13.131 ops/ms
Iteration   1: 13.169 ops/ms
Iteration   2: 13.217 ops/ms
Iteration   3: 13.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.143 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (13.044, 13.143, 13.217), stdev = 0.089
  CI (99.9%): [11.515, 14.771] (assumes normal distribution)


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
# Warmup Iteration   1: 7.580 ops/ms
# Warmup Iteration   2: 12.710 ops/ms
# Warmup Iteration   3: 12.951 ops/ms
Iteration   1: 12.728 ops/ms
Iteration   2: 12.739 ops/ms
Iteration   3: 12.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.742 ±(99.9%) 0.278 ops/ms [Average]
  (min, avg, max) = (12.728, 12.742, 12.758), stdev = 0.015
  CI (99.9%): [12.463, 13.020] (assumes normal distribution)


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
# Warmup Iteration   1: 6.838 ops/ms
# Warmup Iteration   2: 10.504 ops/ms
# Warmup Iteration   3: 10.572 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.564 ops/ms
Iteration   3: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.589 ±(99.9%) 0.791 ops/ms [Average]
  (min, avg, max) = (10.564, 10.589, 10.640), stdev = 0.043
  CI (99.9%): [9.798, 11.381] (assumes normal distribution)


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.486 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (2.479, 2.486, 2.494), stdev = 0.008
  CI (99.9%): [2.344, 2.629] (assumes normal distribution)


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
# Warmup Iteration   1: 3.603 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.004 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
Iteration   2: 2.437 ±(99.9%) 0.003 ms/op
Iteration   3: 2.440 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (2.432, 2.436, 2.440), stdev = 0.004
  CI (99.9%): [2.370, 2.502] (assumes normal distribution)


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.452 ±(99.9%) 0.003 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.454 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.449, 2.454, 2.462), stdev = 0.007
  CI (99.9%): [2.327, 2.581] (assumes normal distribution)


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
# Warmup Iteration   1: 4.655 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.005 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
Iteration   2: 3.018 ±(99.9%) 0.004 ms/op
Iteration   3: 3.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.994, 3.006, 3.018), stdev = 0.012
  CI (99.9%): [2.790, 3.222] (assumes normal distribution)


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
Iteration   1: 2.550 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  11.960 ms/op
                 createUser·p0.9999: 14.352 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   2: 2.573 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  9.634 ms/op
                 createUser·p0.9999: 14.580 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.510 ms/op
                 createUser·p0.999:  8.260 ms/op
                 createUser·p0.9999: 11.829 ms/op
                 createUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376933
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 180537 
    [ 2.500,  3.750) = 192891 
    [ 3.750,  5.000) = 2641 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.472 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     15.330 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  5.862 ms/op
                 existUser·p0.9999: 18.154 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.878 ms/op
                 existUser·p0.999:  7.208 ms/op
                 existUser·p0.9999: 11.830 ms/op
                 existUser·p1.00:   12.763 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  6.529 ms/op
                 existUser·p0.9999: 11.140 ms/op
                 existUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389992
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 191174 
    [ 2.500,  3.750) = 195658 
    [ 3.750,  5.000) = 2277 
    [ 5.000,  6.250) = 409 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      6.767 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     18.386 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  11.765 ms/op
                 getUser·p0.9999: 13.451 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  8.618 ms/op
                 getUser·p0.9999: 12.979 ms/op
                 getUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381384
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 188406 
    [ 2.500,  3.750) = 189082 
    [ 3.750,  5.000) = 3125 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 133 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.661 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.093 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 4.552 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.104 ms/op
                 listUser·p0.9999: 10.279 ms/op
                 listUser·p1.00:   10.879 ms/op

Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.488 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.438 ms/op
                 listUser·p0.9999: 10.904 ms/op
                 listUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319422
  mean =      3.003 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 93496 
    [ 2.500,  3.750) = 187701 
    [ 3.750,  5.000) = 30867 
    [ 5.000,  6.250) = 5853 
    [ 6.250,  7.500) = 755 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      8.972 ms/op
     p(99.9900) =     10.929 ms/op
     p(99.9990) =     12.488 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.636 ± 2.522  ops/ms
ClientPb.existUser                       thrpt       3  13.143 ± 1.628  ops/ms
ClientPb.getUser                         thrpt       3  12.742 ± 0.278  ops/ms
ClientPb.listUser                        thrpt       3  10.589 ± 0.791  ops/ms
ClientPb.createUser                       avgt       3   2.486 ± 0.142   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.066   ms/op
ClientPb.getUser                          avgt       3   2.454 ± 0.127   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.216   ms/op
ClientPb.createUser                     sample  376933   2.544 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.683           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.472           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.434           ms/op
ClientPb.existUser                      sample  389992   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.934           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.767           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.448           ms/op
ClientPb.getUser                        sample  381384   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.884           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.661           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.566           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.205           ms/op
ClientPb.listUser                       sample  319422   3.003 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.972           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.929           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.156           ms/op
