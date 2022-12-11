# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.935 ops/ms
# Warmup Iteration   2: 4.813 ops/ms
# Warmup Iteration   3: 8.442 ops/ms
Iteration   1: 9.274 ops/ms
Iteration   2: 9.294 ops/ms
Iteration   3: 9.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.237 ±(99.9%) 1.491 ops/ms [Average]
  (min, avg, max) = (9.143, 9.237, 9.294), stdev = 0.082
  CI (99.9%): [7.746, 10.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.638 ops/ms
# Warmup Iteration   2: 8.387 ops/ms
# Warmup Iteration   3: 9.129 ops/ms
Iteration   1: 9.565 ops/ms
Iteration   2: 9.831 ops/ms
Iteration   3: 9.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.642 ±(99.9%) 2.994 ops/ms [Average]
  (min, avg, max) = (9.531, 9.642, 9.831), stdev = 0.164
  CI (99.9%): [6.648, 12.636] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.604 ops/ms
# Warmup Iteration   2: 7.902 ops/ms
# Warmup Iteration   3: 9.253 ops/ms
Iteration   1: 9.347 ops/ms
Iteration   2: 9.146 ops/ms
Iteration   3: 9.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.215 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (9.146, 9.215, 9.347), stdev = 0.115
  CI (99.9%): [7.118, 11.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.587 ops/ms
# Warmup Iteration   2: 7.095 ops/ms
# Warmup Iteration   3: 7.702 ops/ms
Iteration   1: 7.994 ops/ms
Iteration   2: 7.750 ops/ms
Iteration   3: 7.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.816 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (7.705, 7.816, 7.994), stdev = 0.156
  CI (99.9%): [4.979, 10.653] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.614 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.004 ms/op
Iteration   1: 3.353 ±(99.9%) 0.012 ms/op
Iteration   2: 3.449 ±(99.9%) 0.007 ms/op
Iteration   3: 3.452 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.418 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.353, 3.418, 3.452), stdev = 0.056
  CI (99.9%): [2.392, 4.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.721 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.005 ms/op
Iteration   1: 3.313 ±(99.9%) 0.007 ms/op
Iteration   2: 3.295 ±(99.9%) 0.007 ms/op
Iteration   3: 3.378 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.328 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (3.295, 3.328, 3.378), stdev = 0.044
  CI (99.9%): [2.533, 4.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.368 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.005 ms/op
Iteration   1: 3.566 ±(99.9%) 0.006 ms/op
Iteration   2: 3.471 ±(99.9%) 0.007 ms/op
Iteration   3: 3.393 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.477 ±(99.9%) 1.580 ms/op [Average]
  (min, avg, max) = (3.393, 3.477, 3.566), stdev = 0.087
  CI (99.9%): [1.896, 5.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.770 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.755 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.343 ±(99.9%) 0.006 ms/op
Iteration   1: 4.180 ±(99.9%) 0.009 ms/op
Iteration   2: 4.119 ±(99.9%) 0.012 ms/op
Iteration   3: 3.921 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.074 ±(99.9%) 2.470 ms/op [Average]
  (min, avg, max) = (3.921, 4.074, 4.180), stdev = 0.135
  CI (99.9%): [1.603, 6.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.987 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.015 ms/op
Iteration   1: 3.434 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  20.437 ms/op
                 createUser·p0.9999: 22.972 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.566 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  23.560 ms/op
                 createUser·p0.9999: 32.866 ms/op
                 createUser·p1.00:   33.522 ms/op

Iteration   3: 3.400 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  21.168 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276979
  mean =      3.465 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9339 
    [ 2.500,  5.000) = 262091 
    [ 5.000,  7.500) = 4374 
    [ 7.500, 10.000) = 704 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     30.625 ms/op
     p(99.9990) =     33.257 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.911 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
Iteration   1: 3.411 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  10.833 ms/op
                 existUser·p0.9999: 22.847 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.321 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.375 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  16.629 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  21.535 ms/op
                 existUser·p0.9999: 26.059 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286138
  mean =      3.357 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21487 
    [ 2.500,  5.000) = 258710 
    [ 5.000,  7.500) = 5117 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     25.310 ms/op
     p(99.9990) =     26.588 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.964 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.009 ms/op
Iteration   1: 3.484 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.823 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  18.728 ms/op
                 getUser·p0.9999: 21.561 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.450 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  19.366 ms/op
                 getUser·p0.9999: 25.762 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   3: 3.538 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  13.018 ms/op
                 getUser·p0.9999: 24.899 ms/op
                 getUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274990
  mean =      3.490 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2075 
    [ 2.500,  5.000) = 267137 
    [ 5.000,  7.500) = 4612 
    [ 7.500, 10.000) = 675 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     17.466 ms/op
     p(99.9900) =     25.117 ms/op
     p(99.9990) =     27.140 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.443 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.623 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.013 ms/op
Iteration   1: 3.943 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  21.165 ms/op
                 listUser·p0.9999: 25.978 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 3.900 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.119 ms/op
                 listUser·p0.9999: 18.513 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 4.114 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240853
  mean =      3.984 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 233708 
    [ 5.000,  7.500) = 5048 
    [ 7.500, 10.000) = 1256 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     25.062 ms/op
     p(99.9990) =     26.521 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.237 ± 1.491  ops/ms
ClientPb.existUser                       thrpt       3   9.642 ± 2.994  ops/ms
ClientPb.getUser                         thrpt       3   9.215 ± 2.096  ops/ms
ClientPb.listUser                        thrpt       3   7.816 ± 2.837  ops/ms
ClientPb.createUser                       avgt       3   3.418 ± 1.026   ms/op
ClientPb.existUser                        avgt       3   3.328 ± 0.795   ms/op
ClientPb.getUser                          avgt       3   3.477 ± 1.580   ms/op
ClientPb.listUser                         avgt       3   4.074 ± 2.470   ms/op
ClientPb.createUser                     sample  276979   3.465 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.112           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.980           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.808           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.625           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.522           ms/op
ClientPb.existUser                      sample  286138   3.357 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.375           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.310           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.804           ms/op
ClientPb.getUser                        sample  274990   3.490 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.298           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.466           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.117           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.296           ms/op
ClientPb.listUser                       sample  240853   3.984 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.311           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.040           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.062           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
