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
# Warmup Iteration   1: 4.741 ops/ms
# Warmup Iteration   2: 11.725 ops/ms
# Warmup Iteration   3: 11.939 ops/ms
Iteration   1: 12.244 ops/ms
Iteration   2: 12.148 ops/ms
Iteration   3: 12.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.231 ±(99.9%) 1.410 ops/ms [Average]
  (min, avg, max) = (12.148, 12.231, 12.301), stdev = 0.077
  CI (99.9%): [10.821, 13.641] (assumes normal distribution)


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
# Warmup Iteration   1: 7.909 ops/ms
# Warmup Iteration   2: 12.870 ops/ms
# Warmup Iteration   3: 12.922 ops/ms
Iteration   1: 12.849 ops/ms
Iteration   2: 12.779 ops/ms
Iteration   3: 13.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.886 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (12.779, 12.886, 13.029), stdev = 0.129
  CI (99.9%): [10.531, 15.240] (assumes normal distribution)


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
# Warmup Iteration   1: 7.579 ops/ms
# Warmup Iteration   2: 12.202 ops/ms
# Warmup Iteration   3: 12.519 ops/ms
Iteration   1: 12.466 ops/ms
Iteration   2: 12.504 ops/ms
Iteration   3: 12.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.461 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (12.414, 12.461, 12.504), stdev = 0.045
  CI (99.9%): [11.633, 13.289] (assumes normal distribution)


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
# Warmup Iteration   1: 6.435 ops/ms
# Warmup Iteration   2: 10.192 ops/ms
# Warmup Iteration   3: 10.430 ops/ms
Iteration   1: 10.382 ops/ms
Iteration   2: 10.454 ops/ms
Iteration   3: 10.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.424 ±(99.9%) 0.677 ops/ms [Average]
  (min, avg, max) = (10.382, 10.424, 10.454), stdev = 0.037
  CI (99.9%): [9.747, 11.101] (assumes normal distribution)


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.600 ±(99.9%) 0.004 ms/op
Iteration   1: 2.580 ±(99.9%) 0.005 ms/op
Iteration   2: 2.587 ±(99.9%) 0.004 ms/op
Iteration   3: 2.592 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.586 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (2.580, 2.586, 2.592), stdev = 0.006
  CI (99.9%): [2.481, 2.692] (assumes normal distribution)


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
# Warmup Iteration   1: 3.882 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.435, 2.442, 2.454), stdev = 0.010
  CI (99.9%): [2.251, 2.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.004 ms/op
Iteration   1: 2.539 ±(99.9%) 0.005 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.555 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.540 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (2.525, 2.540, 2.555), stdev = 0.015
  CI (99.9%): [2.266, 2.813] (assumes normal distribution)


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
# Warmup Iteration   1: 4.982 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
Iteration   3: 3.074 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.081 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (3.074, 3.081, 3.085), stdev = 0.006
  CI (99.9%): [2.964, 3.197] (assumes normal distribution)


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
# Warmup Iteration   1: 4.344 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.684 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  11.750 ms/op
                 createUser·p0.9999: 13.399 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  9.390 ms/op
                 createUser·p0.9999: 14.215 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  8.552 ms/op
                 createUser·p0.9999: 10.376 ms/op
                 createUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381648
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 184632 
    [ 2.500,  3.750) = 192796 
    [ 3.750,  5.000) = 3303 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     13.350 ms/op
     p(99.9990) =     14.557 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  11.506 ms/op
                 existUser·p0.9999: 13.947 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  6.148 ms/op
                 existUser·p0.9999: 13.107 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  9.387 ms/op
                 existUser·p0.9999: 12.068 ms/op
                 existUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382228
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 186856 
    [ 2.500,  3.750) = 191389 
    [ 3.750,  5.000) = 2846 
    [ 5.000,  6.250) = 692 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      6.332 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.320 ms/op
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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.006 ms/op
Iteration   1: 2.570 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  11.583 ms/op
                 getUser·p0.9999: 13.976 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.573 ms/op
                 getUser·p0.9999: 13.127 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   3.977 ms/op
                 getUser·p0.999:  6.102 ms/op
                 getUser·p0.9999: 11.632 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374340
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 181051 
    [ 2.500,  3.750) = 187379 
    [ 3.750,  5.000) = 4627 
    [ 5.000,  6.250) = 826 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      6.936 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 4.939 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.009 ms/op
Iteration   1: 3.124 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  9.219 ms/op
                 listUser·p0.9999: 10.285 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   2: 3.111 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.101 ms/op
                 listUser·p0.9999: 10.538 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   3: 3.127 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.627 ms/op
                 listUser·p0.9999: 13.746 ms/op
                 listUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 307288
  mean =      3.121 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 74198 
    [ 2.500,  3.750) = 185381 
    [ 3.750,  5.000) = 38862 
    [ 5.000,  6.250) = 7208 
    [ 6.250,  7.500) = 872 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 312 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.252 ms/op
     p(99.9900) =     12.206 ms/op
     p(99.9990) =     13.942 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.231 ± 1.410  ops/ms
ClientPb.existUser                       thrpt       3  12.886 ± 2.355  ops/ms
ClientPb.getUser                         thrpt       3  12.461 ± 0.828  ops/ms
ClientPb.listUser                        thrpt       3  10.424 ± 0.677  ops/ms
ClientPb.createUser                       avgt       3   2.586 ± 0.105   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.191   ms/op
ClientPb.getUser                          avgt       3   2.540 ± 0.274   ms/op
ClientPb.listUser                         avgt       3   3.081 ± 0.116   ms/op
ClientPb.createUser                     sample  381648   2.513 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.904           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.569           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.350           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.401           ms/op
ClientPb.existUser                      sample  382228   2.508 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.806           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.332           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.402           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.893           ms/op
ClientPb.getUser                        sample  374340   2.562 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.806           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.936           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.353           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.238           ms/op
ClientPb.listUser                       sample  307288   3.121 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.064           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.252           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.206           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.008           ms/op
