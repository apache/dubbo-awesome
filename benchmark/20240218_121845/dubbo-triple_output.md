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
# Warmup Iteration   1: 5.257 ops/ms
# Warmup Iteration   2: 12.073 ops/ms
# Warmup Iteration   3: 12.263 ops/ms
Iteration   1: 12.568 ops/ms
Iteration   2: 12.637 ops/ms
Iteration   3: 12.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.599 ±(99.9%) 0.646 ops/ms [Average]
  (min, avg, max) = (12.568, 12.599, 12.637), stdev = 0.035
  CI (99.9%): [11.952, 13.245] (assumes normal distribution)


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
# Warmup Iteration   1: 7.957 ops/ms
# Warmup Iteration   2: 13.161 ops/ms
# Warmup Iteration   3: 13.238 ops/ms
Iteration   1: 13.386 ops/ms
Iteration   2: 13.298 ops/ms
Iteration   3: 13.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.322 ±(99.9%) 1.033 ops/ms [Average]
  (min, avg, max) = (13.281, 13.322, 13.386), stdev = 0.057
  CI (99.9%): [12.288, 14.355] (assumes normal distribution)


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
# Warmup Iteration   1: 7.417 ops/ms
# Warmup Iteration   2: 12.371 ops/ms
# Warmup Iteration   3: 12.525 ops/ms
Iteration   1: 12.660 ops/ms
Iteration   2: 12.303 ops/ms
Iteration   3: 12.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.503 ±(99.9%) 3.324 ops/ms [Average]
  (min, avg, max) = (12.303, 12.503, 12.660), stdev = 0.182
  CI (99.9%): [9.179, 15.827] (assumes normal distribution)


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
# Warmup Iteration   1: 6.433 ops/ms
# Warmup Iteration   2: 10.174 ops/ms
# Warmup Iteration   3: 10.282 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.644 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.598 ±(99.9%) 0.868 ops/ms [Average]
  (min, avg, max) = (10.549, 10.598, 10.644), stdev = 0.048
  CI (99.9%): [9.730, 11.466] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.004 ms/op
Iteration   1: 2.567 ±(99.9%) 0.004 ms/op
Iteration   2: 2.608 ±(99.9%) 0.003 ms/op
Iteration   3: 2.559 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.578 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (2.559, 2.578, 2.608), stdev = 0.026
  CI (99.9%): [2.098, 3.058] (assumes normal distribution)


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.003 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.490 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.475, 2.490, 2.503), stdev = 0.014
  CI (99.9%): [2.233, 2.747] (assumes normal distribution)


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.563 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.538 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.518, 2.538, 2.563), stdev = 0.023
  CI (99.9%): [2.127, 2.950] (assumes normal distribution)


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
# Warmup Iteration   1: 5.142 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.005 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
Iteration   3: 3.001 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.002 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (2.975, 3.002, 3.029), stdev = 0.027
  CI (99.9%): [2.510, 3.493] (assumes normal distribution)


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
# Warmup Iteration   1: 4.229 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.682 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  11.511 ms/op
                 createUser·p0.9999: 14.285 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  9.869 ms/op
                 createUser·p0.9999: 12.494 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   3: 2.582 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  8.740 ms/op
                 createUser·p0.9999: 10.824 ms/op
                 createUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373639
  mean =      2.567 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 176198 
    [ 2.500,  3.750) = 192000 
    [ 3.750,  5.000) = 4241 
    [ 5.000,  6.250) = 675 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      8.886 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  5.358 ms/op
                 existUser·p0.9999: 13.483 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  7.313 ms/op
                 existUser·p0.9999: 12.862 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.933 ms/op
                 existUser·p0.9999: 11.828 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390938
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 195221 
    [ 2.500,  3.750) = 192462 
    [ 3.750,  5.000) = 2257 
    [ 5.000,  6.250) = 567 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      6.154 ms/op
     p(99.9900) =     13.368 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  11.071 ms/op
                 getUser·p0.9999: 14.647 ms/op
                 getUser·p1.00:   16.122 ms/op

Iteration   2: 2.572 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 14.018 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  8.673 ms/op
                 getUser·p0.9999: 10.997 ms/op
                 getUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379598
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 186361 
    [ 2.500,  3.750) = 188343 
    [ 3.750,  5.000) = 3620 
    [ 5.000,  6.250) = 679 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     15.487 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 4.816 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.755 ms/op
                 listUser·p0.9999: 11.130 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 10.853 ms/op
                 listUser·p1.00:   13.009 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 10.984 ms/op
                 listUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317672
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 89629 
    [ 2.500,  3.750) = 187756 
    [ 3.750,  5.000) = 32623 
    [ 5.000,  6.250) = 6243 
    [ 6.250,  7.500) = 605 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 257 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.230 ms/op
     p(99.9900) =     11.001 ms/op
     p(99.9990) =     12.877 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.599 ± 0.646  ops/ms
ClientPb.existUser                       thrpt       3  13.322 ± 1.033  ops/ms
ClientPb.getUser                         thrpt       3  12.503 ± 3.324  ops/ms
ClientPb.listUser                        thrpt       3  10.598 ± 0.868  ops/ms
ClientPb.createUser                       avgt       3   2.578 ± 0.480   ms/op
ClientPb.existUser                        avgt       3   2.490 ± 0.257   ms/op
ClientPb.getUser                          avgt       3   2.538 ± 0.412   ms/op
ClientPb.listUser                         avgt       3   3.002 ± 0.492   ms/op
ClientPb.createUser                     sample  373639   2.567 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.837           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.886           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.828           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.204           ms/op
ClientPb.existUser                      sample  390938   2.453 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.908           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.154           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.368           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.336           ms/op
ClientPb.getUser                        sample  379598   2.527 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.834           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.831           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.122           ms/op
ClientPb.listUser                       sample  317672   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.942           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.230           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.001           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.009           ms/op
