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
# Warmup Iteration   1: 4.841 ops/ms
# Warmup Iteration   2: 11.931 ops/ms
# Warmup Iteration   3: 12.143 ops/ms
Iteration   1: 12.419 ops/ms
Iteration   2: 12.352 ops/ms
Iteration   3: 12.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.400 ±(99.9%) 0.768 ops/ms [Average]
  (min, avg, max) = (12.352, 12.400, 12.430), stdev = 0.042
  CI (99.9%): [11.632, 13.168] (assumes normal distribution)


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
# Warmup Iteration   1: 8.166 ops/ms
# Warmup Iteration   2: 12.940 ops/ms
# Warmup Iteration   3: 12.956 ops/ms
Iteration   1: 12.919 ops/ms
Iteration   2: 12.867 ops/ms
Iteration   3: 12.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.860 ±(99.9%) 1.151 ops/ms [Average]
  (min, avg, max) = (12.793, 12.860, 12.919), stdev = 0.063
  CI (99.9%): [11.709, 14.010] (assumes normal distribution)


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
# Warmup Iteration   1: 6.827 ops/ms
# Warmup Iteration   2: 12.269 ops/ms
# Warmup Iteration   3: 12.486 ops/ms
Iteration   1: 12.503 ops/ms
Iteration   2: 12.330 ops/ms
Iteration   3: 12.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.394 ±(99.9%) 1.732 ops/ms [Average]
  (min, avg, max) = (12.330, 12.394, 12.503), stdev = 0.095
  CI (99.9%): [10.662, 14.126] (assumes normal distribution)


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
# Warmup Iteration   1: 6.040 ops/ms
# Warmup Iteration   2: 10.055 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.287 ops/ms
Iteration   2: 10.296 ops/ms
Iteration   3: 10.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.279 ±(99.9%) 0.400 ops/ms [Average]
  (min, avg, max) = (10.254, 10.279, 10.296), stdev = 0.022
  CI (99.9%): [9.879, 10.678] (assumes normal distribution)


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
# Warmup Iteration   1: 4.328 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.603 ±(99.9%) 0.005 ms/op
Iteration   1: 2.600 ±(99.9%) 0.004 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.592 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.590 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.580, 2.590, 2.600), stdev = 0.010
  CI (99.9%): [2.403, 2.777] (assumes normal distribution)


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.003 ms/op
Iteration   1: 2.541 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.527 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (2.520, 2.527, 2.541), stdev = 0.012
  CI (99.9%): [2.300, 2.754] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
Iteration   3: 2.586 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.565 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (2.542, 2.565, 2.586), stdev = 0.022
  CI (99.9%): [2.163, 2.966] (assumes normal distribution)


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
# Warmup Iteration   1: 4.863 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.067 ±(99.9%) 0.005 ms/op
Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
Iteration   3: 3.069 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.063 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (3.052, 3.063, 3.069), stdev = 0.009
  CI (99.9%): [2.893, 3.233] (assumes normal distribution)


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.707 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.574 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  11.122 ms/op
                 createUser·p0.9999: 13.559 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 14.377 ms/op
                 createUser·p1.00:   15.860 ms/op

Iteration   3: 2.587 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  8.138 ms/op
                 createUser·p0.9999: 10.037 ms/op
                 createUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372778
  mean =      2.573 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 177868 
    [ 2.500,  3.750) = 190824 
    [ 3.750,  5.000) = 3176 
    [ 5.000,  6.250) = 386 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.258 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     15.305 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.542 ms/op
                 existUser·p0.999:  7.249 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  7.737 ms/op
                 existUser·p0.9999: 12.632 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  6.052 ms/op
                 existUser·p0.9999: 11.928 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386957
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 190721 
    [ 2.500,  3.750) = 193321 
    [ 3.750,  5.000) = 2267 
    [ 5.000,  6.250) = 230 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      6.136 ms/op
     p(99.9900) =     13.505 ms/op
     p(99.9990) =     14.631 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  11.285 ms/op
                 getUser·p0.9999: 13.468 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 13.401 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  8.331 ms/op
                 getUser·p0.9999: 12.175 ms/op
                 getUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377249
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 184453 
    [ 2.500,  3.750) = 188497 
    [ 3.750,  5.000) = 3290 
    [ 5.000,  6.250) = 541 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     13.259 ms/op
     p(99.9990) =     14.172 ms/op
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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.009 ms/op
Iteration   1: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.096 ms/op
                 listUser·p0.9999: 11.592 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.784 ms/op
                 listUser·p0.9999: 13.613 ms/op
                 listUser·p1.00:   14.090 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.297 ms/op
                 listUser·p0.9999: 11.198 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316100
  mean =      3.034 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 87955 
    [ 2.500,  3.750) = 187096 
    [ 3.750,  5.000) = 33791 
    [ 5.000,  6.250) = 5804 
    [ 6.250,  7.500) = 734 
    [ 7.500,  8.750) = 274 
    [ 8.750, 10.000) = 165 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     11.649 ms/op
     p(99.9990) =     13.940 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.400 ± 0.768  ops/ms
ClientPb.existUser                       thrpt       3  12.860 ± 1.151  ops/ms
ClientPb.getUser                         thrpt       3  12.394 ± 1.732  ops/ms
ClientPb.listUser                        thrpt       3  10.279 ± 0.400  ops/ms
ClientPb.createUser                       avgt       3   2.590 ± 0.187   ms/op
ClientPb.existUser                        avgt       3   2.527 ± 0.227   ms/op
ClientPb.getUser                          avgt       3   2.565 ± 0.401   ms/op
ClientPb.listUser                         avgt       3   3.063 ± 0.170   ms/op
ClientPb.createUser                     sample  372778   2.573 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.758           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.258           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.860           ms/op
ClientPb.existUser                      sample  386957   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.607           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.136           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.505           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.778           ms/op
ClientPb.getUser                        sample  377249   2.542 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.016           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.438           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.259           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.352           ms/op
ClientPb.listUser                       sample  316100   3.034 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.908           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.126           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.649           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.090           ms/op
