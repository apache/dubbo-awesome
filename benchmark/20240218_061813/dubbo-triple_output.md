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
# Warmup Iteration   1: 4.840 ops/ms
# Warmup Iteration   2: 11.958 ops/ms
# Warmup Iteration   3: 12.166 ops/ms
Iteration   1: 12.606 ops/ms
Iteration   2: 12.566 ops/ms
Iteration   3: 12.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.652 ±(99.9%) 2.115 ops/ms [Average]
  (min, avg, max) = (12.566, 12.652, 12.784), stdev = 0.116
  CI (99.9%): [10.537, 14.767] (assumes normal distribution)


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
# Warmup Iteration   1: 7.895 ops/ms
# Warmup Iteration   2: 12.913 ops/ms
# Warmup Iteration   3: 12.893 ops/ms
Iteration   1: 12.942 ops/ms
Iteration   2: 12.948 ops/ms
Iteration   3: 12.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.950 ±(99.9%) 0.158 ops/ms [Average]
  (min, avg, max) = (12.942, 12.950, 12.959), stdev = 0.009
  CI (99.9%): [12.791, 13.108] (assumes normal distribution)


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
# Warmup Iteration   1: 7.666 ops/ms
# Warmup Iteration   2: 12.741 ops/ms
# Warmup Iteration   3: 12.851 ops/ms
Iteration   1: 12.976 ops/ms
Iteration   2: 13.108 ops/ms
Iteration   3: 12.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.015 ±(99.9%) 1.477 ops/ms [Average]
  (min, avg, max) = (12.961, 13.015, 13.108), stdev = 0.081
  CI (99.9%): [11.538, 14.492] (assumes normal distribution)


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
# Warmup Iteration   1: 6.674 ops/ms
# Warmup Iteration   2: 10.743 ops/ms
# Warmup Iteration   3: 10.725 ops/ms
Iteration   1: 10.772 ops/ms
Iteration   2: 10.700 ops/ms
Iteration   3: 10.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.756 ±(99.9%) 0.920 ops/ms [Average]
  (min, avg, max) = (10.700, 10.756, 10.797), stdev = 0.050
  CI (99.9%): [9.836, 11.676] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.003 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.481 ±(99.9%) 0.049 ms/op [Average]
  (min, avg, max) = (2.479, 2.481, 2.484), stdev = 0.003
  CI (99.9%): [2.432, 2.529] (assumes normal distribution)


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.004 ms/op
Iteration   2: 2.413 ±(99.9%) 0.004 ms/op
Iteration   3: 2.402 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.415 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.402, 2.415, 2.428), stdev = 0.013
  CI (99.9%): [2.178, 2.651] (assumes normal distribution)


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.019 ms/op [Average]
  (min, avg, max) = (2.517, 2.518, 2.519), stdev = 0.001
  CI (99.9%): [2.499, 2.538] (assumes normal distribution)


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
# Warmup Iteration   1: 4.503 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
Iteration   1: 2.946 ±(99.9%) 0.004 ms/op
Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
Iteration   3: 2.952 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.948 ±(99.9%) 0.054 ms/op [Average]
  (min, avg, max) = (2.946, 2.948, 2.952), stdev = 0.003
  CI (99.9%): [2.894, 3.003] (assumes normal distribution)


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  6.132 ms/op
                 createUser·p0.9999: 13.424 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  10.305 ms/op
                 createUser·p0.9999: 12.324 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  8.141 ms/op
                 createUser·p0.9999: 9.334 ms/op
                 createUser·p1.00:   10.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384728
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 186511 
    [ 2.500,  3.750) = 194560 
    [ 3.750,  5.000) = 2844 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.459 ms/op
     p(99.9900) =     12.962 ms/op
     p(99.9990) =     13.783 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  6.906 ms/op
                 existUser·p0.9999: 13.549 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  7.764 ms/op
                 existUser·p0.9999: 11.993 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  8.651 ms/op
                 existUser·p0.9999: 11.125 ms/op
                 existUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390221
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 193835 
    [ 2.500,  3.750) = 193100 
    [ 3.750,  5.000) = 2420 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      7.938 ms/op
     p(99.9900) =     12.779 ms/op
     p(99.9990) =     13.913 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.490 ms/op
                 getUser·p0.999:  5.239 ms/op
                 getUser·p0.9999: 13.601 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.067 ms/op
                 getUser·p0.999:  9.095 ms/op
                 getUser·p0.9999: 13.260 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  8.023 ms/op
                 getUser·p0.9999: 11.095 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381215
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 187264 
    [ 2.500,  3.750) = 189916 
    [ 3.750,  5.000) = 2762 
    [ 5.000,  6.250) = 796 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      6.912 ms/op
     p(99.9900) =     13.302 ms/op
     p(99.9990) =     14.113 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
Iteration   1: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.749 ms/op
                 listUser·p0.9999: 11.145 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.245 ms/op
                 listUser·p0.9999: 10.870 ms/op
                 listUser·p1.00:   12.878 ms/op

Iteration   3: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.928 ms/op
                 listUser·p0.9999: 10.561 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322249
  mean =      2.976 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 98603 
    [ 2.500,  3.750) = 187200 
    [ 3.750,  5.000) = 29626 
    [ 5.000,  6.250) = 5479 
    [ 6.250,  7.500) = 528 
    [ 7.500,  8.750) = 311 
    [ 8.750, 10.000) = 239 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     11.006 ms/op
     p(99.9990) =     12.108 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.652 ± 2.115  ops/ms
ClientPb.existUser                       thrpt       3  12.950 ± 0.158  ops/ms
ClientPb.getUser                         thrpt       3  13.015 ± 1.477  ops/ms
ClientPb.listUser                        thrpt       3  10.756 ± 0.920  ops/ms
ClientPb.createUser                       avgt       3   2.481 ± 0.049   ms/op
ClientPb.existUser                        avgt       3   2.415 ± 0.237   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.019   ms/op
ClientPb.listUser                         avgt       3   2.948 ± 0.054   ms/op
ClientPb.createUser                     sample  384728   2.494 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.849           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.459           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.962           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.402           ms/op
ClientPb.existUser                      sample  390221   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.938           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.779           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.238           ms/op
ClientPb.getUser                        sample  381215   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.878           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.912           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.302           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  322249   2.976 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.929           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.006           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.878           ms/op
