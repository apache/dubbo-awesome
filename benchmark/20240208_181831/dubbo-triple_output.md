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
# Warmup Iteration   1: 5.148 ops/ms
# Warmup Iteration   2: 12.258 ops/ms
# Warmup Iteration   3: 12.498 ops/ms
Iteration   1: 12.757 ops/ms
Iteration   2: 12.910 ops/ms
Iteration   3: 12.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.860 ±(99.9%) 1.638 ops/ms [Average]
  (min, avg, max) = (12.757, 12.860, 12.915), stdev = 0.090
  CI (99.9%): [11.222, 14.499] (assumes normal distribution)


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
# Warmup Iteration   1: 8.015 ops/ms
# Warmup Iteration   2: 13.342 ops/ms
# Warmup Iteration   3: 13.198 ops/ms
Iteration   1: 13.256 ops/ms
Iteration   2: 13.224 ops/ms
Iteration   3: 13.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.249 ±(99.9%) 0.422 ops/ms [Average]
  (min, avg, max) = (13.224, 13.249, 13.269), stdev = 0.023
  CI (99.9%): [12.828, 13.671] (assumes normal distribution)


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
# Warmup Iteration   1: 7.667 ops/ms
# Warmup Iteration   2: 12.544 ops/ms
# Warmup Iteration   3: 12.875 ops/ms
Iteration   1: 12.935 ops/ms
Iteration   2: 13.005 ops/ms
Iteration   3: 12.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.931 ±(99.9%) 1.380 ops/ms [Average]
  (min, avg, max) = (12.854, 12.931, 13.005), stdev = 0.076
  CI (99.9%): [11.551, 14.311] (assumes normal distribution)


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
# Warmup Iteration   1: 6.242 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 10.730 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.731 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.685 ±(99.9%) 1.377 ops/ms [Average]
  (min, avg, max) = (10.597, 10.685, 10.731), stdev = 0.076
  CI (99.9%): [9.307, 12.062] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.003 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.497 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (2.494, 2.497, 2.501), stdev = 0.004
  CI (99.9%): [2.429, 2.566] (assumes normal distribution)


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.456 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (2.446, 2.456, 2.476), stdev = 0.017
  CI (99.9%): [2.141, 2.771] (assumes normal distribution)


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.005 ms/op
Iteration   1: 2.541 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
Iteration   3: 2.527 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.533 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (2.527, 2.533, 2.541), stdev = 0.008
  CI (99.9%): [2.393, 2.672] (assumes normal distribution)


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
# Warmup Iteration   1: 4.963 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.005 ms/op
Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
Iteration   3: 3.033 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.025 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (3.019, 3.025, 3.033), stdev = 0.007
  CI (99.9%): [2.890, 3.161] (assumes normal distribution)


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.684 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  10.050 ms/op
                 createUser·p0.9999: 13.918 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  9.233 ms/op
                 createUser·p0.9999: 11.878 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  8.213 ms/op
                 createUser·p0.9999: 10.359 ms/op
                 createUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384167
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 187347 
    [ 2.500,  3.750) = 192781 
    [ 3.750,  5.000) = 3151 
    [ 5.000,  6.250) = 347 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.215 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.609 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.400 ms/op
                 existUser·p0.999:  5.715 ms/op
                 existUser·p0.9999: 13.499 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  5.342 ms/op
                 existUser·p0.9999: 13.957 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  9.609 ms/op
                 existUser·p0.9999: 11.959 ms/op
                 existUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393199
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 196142 
    [ 2.500,  3.750) = 194384 
    [ 3.750,  5.000) = 1888 
    [ 5.000,  6.250) = 310 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      8.264 ms/op
     p(99.9900) =     13.495 ms/op
     p(99.9990) =     14.616 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.006 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.522 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  5.743 ms/op
                 getUser·p0.9999: 13.846 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.334 ms/op
                 getUser·p0.9999: 13.051 ms/op
                 getUser·p1.00:   13.304 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  7.988 ms/op
                 getUser·p0.9999: 10.666 ms/op
                 getUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389853
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 196144 
    [ 2.500,  3.750) = 188712 
    [ 3.750,  5.000) = 3748 
    [ 5.000,  6.250) = 710 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      6.966 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     14.230 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.129 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   2: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 11.420 ms/op
                 listUser·p1.00:   12.222 ms/op

Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.728 ms/op
                 listUser·p0.9999: 11.813 ms/op
                 listUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320915
  mean =      2.989 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 96019 
    [ 2.500,  3.750) = 187764 
    [ 3.750,  5.000) = 30404 
    [ 5.000,  6.250) = 5301 
    [ 6.250,  7.500) = 607 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     11.664 ms/op
     p(99.9990) =     12.794 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.860 ± 1.638  ops/ms
ClientPb.existUser                       thrpt       3  13.249 ± 0.422  ops/ms
ClientPb.getUser                         thrpt       3  12.931 ± 1.380  ops/ms
ClientPb.listUser                        thrpt       3  10.685 ± 1.377  ops/ms
ClientPb.createUser                       avgt       3   2.497 ± 0.068   ms/op
ClientPb.existUser                        avgt       3   2.456 ± 0.315   ms/op
ClientPb.getUser                          avgt       3   2.533 ± 0.140   ms/op
ClientPb.listUser                         avgt       3   3.025 ± 0.136   ms/op
ClientPb.createUser                     sample  384167   2.497 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.676           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.215           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.042           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.942           ms/op
ClientPb.existUser                      sample  393199   2.440 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.264           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.495           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.664           ms/op
ClientPb.getUser                        sample  389853   2.460 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.522           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.966           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.352           ms/op
ClientPb.listUser                       sample  320915   2.989 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.902           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.664           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
