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
# Warmup Iteration   1: 4.383 ops/ms
# Warmup Iteration   2: 12.117 ops/ms
# Warmup Iteration   3: 12.227 ops/ms
Iteration   1: 12.264 ops/ms
Iteration   2: 12.445 ops/ms
Iteration   3: 12.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.400 ±(99.9%) 2.196 ops/ms [Average]
  (min, avg, max) = (12.264, 12.400, 12.492), stdev = 0.120
  CI (99.9%): [10.205, 14.596] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.779 ops/ms
# Warmup Iteration   2: 13.105 ops/ms
# Warmup Iteration   3: 13.186 ops/ms
Iteration   1: 12.847 ops/ms
Iteration   2: 13.020 ops/ms
Iteration   3: 12.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.948 ±(99.9%) 1.643 ops/ms [Average]
  (min, avg, max) = (12.847, 12.948, 13.020), stdev = 0.090
  CI (99.9%): [11.305, 14.591] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.628 ops/ms
# Warmup Iteration   2: 12.269 ops/ms
# Warmup Iteration   3: 12.460 ops/ms
Iteration   1: 12.570 ops/ms
Iteration   2: 12.556 ops/ms
Iteration   3: 12.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.541 ±(99.9%) 0.700 ops/ms [Average]
  (min, avg, max) = (12.498, 12.541, 12.570), stdev = 0.038
  CI (99.9%): [11.841, 13.241] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.768 ops/ms
# Warmup Iteration   2: 10.562 ops/ms
# Warmup Iteration   3: 10.711 ops/ms
Iteration   1: 10.646 ops/ms
Iteration   2: 10.772 ops/ms
Iteration   3: 10.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.663 ±(99.9%) 1.855 ops/ms [Average]
  (min, avg, max) = (10.570, 10.663, 10.772), stdev = 0.102
  CI (99.9%): [8.808, 12.517] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.371 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.529 ±(99.9%) 0.004 ms/op
Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
Iteration   3: 2.550 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.529, 2.541, 2.550), stdev = 0.011
  CI (99.9%): [2.343, 2.738] (assumes normal distribution)


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.481 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (2.457, 2.481, 2.505), stdev = 0.024
  CI (99.9%): [2.041, 2.920] (assumes normal distribution)


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.516 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.499, 2.516, 2.526), stdev = 0.014
  CI (99.9%): [2.252, 2.780] (assumes normal distribution)


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
Iteration   3: 3.060 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (3.016, 3.036, 3.060), stdev = 0.022
  CI (99.9%): [2.633, 3.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.532 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.566 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.334 ms/op
                 createUser·p0.99:   4.166 ms/op
                 createUser·p0.999:  12.049 ms/op
                 createUser·p0.9999: 13.477 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  9.427 ms/op
                 createUser·p0.9999: 13.763 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   3: 2.569 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  8.860 ms/op
                 createUser·p0.9999: 12.243 ms/op
                 createUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374604
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 180037 
    [ 2.500,  3.750) = 188905 
    [ 3.750,  5.000) = 4564 
    [ 5.000,  6.250) = 529 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      9.132 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.324 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.774 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  8.320 ms/op
                 existUser·p0.9999: 14.796 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   2.634 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  9.098 ms/op
                 existUser·p0.9999: 14.230 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385799
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 186018 
    [ 2.500,  3.750) = 197051 
    [ 3.750,  5.000) = 2040 
    [ 5.000,  6.250) = 218 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      8.464 ms/op
     p(99.9900) =     14.212 ms/op
     p(99.9990) =     15.653 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  5.850 ms/op
                 getUser·p0.9999: 13.909 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  6.076 ms/op
                 getUser·p0.9999: 14.876 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.860 ms/op
                 getUser·p0.999:  7.145 ms/op
                 getUser·p0.9999: 11.412 ms/op
                 getUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390106
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 196509 
    [ 2.500,  3.750) = 189292 
    [ 3.750,  5.000) = 3449 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      7.069 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     15.216 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.009 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.589 ms/op
                 listUser·p0.9999: 11.328 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   2: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 12.641 ms/op
                 listUser·p1.00:   13.353 ms/op

Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.574 ms/op
                 listUser·p0.999:  9.831 ms/op
                 listUser·p0.9999: 13.473 ms/op
                 listUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317535
  mean =      3.021 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 92082 
    [ 2.500,  3.750) = 185150 
    [ 3.750,  5.000) = 33091 
    [ 5.000,  6.250) = 5860 
    [ 6.250,  7.500) = 551 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     12.620 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.400 ± 2.196  ops/ms
ClientPb.existUser                       thrpt       3  12.948 ± 1.643  ops/ms
ClientPb.getUser                         thrpt       3  12.541 ± 0.700  ops/ms
ClientPb.listUser                        thrpt       3  10.663 ± 1.855  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.197   ms/op
ClientPb.existUser                        avgt       3   2.481 ± 0.440   ms/op
ClientPb.getUser                          avgt       3   2.516 ± 0.264   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.403   ms/op
ClientPb.createUser                     sample  374604   2.560 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.699           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.132           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.369           ms/op
ClientPb.existUser                      sample  385799   2.485 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.969           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.593           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.464           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.212           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.908           ms/op
ClientPb.getUser                        sample  390106   2.458 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.840           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.069           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.910           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.417           ms/op
ClientPb.listUser                       sample  317535   3.021 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.859           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.620           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.483           ms/op
