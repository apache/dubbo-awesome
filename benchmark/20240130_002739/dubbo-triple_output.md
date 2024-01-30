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
# Warmup Iteration   1: 4.543 ops/ms
# Warmup Iteration   2: 11.959 ops/ms
# Warmup Iteration   3: 12.309 ops/ms
Iteration   1: 12.594 ops/ms
Iteration   2: 12.649 ops/ms
Iteration   3: 12.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.669 ±(99.9%) 1.596 ops/ms [Average]
  (min, avg, max) = (12.594, 12.669, 12.765), stdev = 0.087
  CI (99.9%): [11.073, 14.266] (assumes normal distribution)


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
# Warmup Iteration   1: 8.134 ops/ms
# Warmup Iteration   2: 12.807 ops/ms
# Warmup Iteration   3: 12.856 ops/ms
Iteration   1: 12.868 ops/ms
Iteration   2: 13.023 ops/ms
Iteration   3: 12.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.931 ±(99.9%) 1.476 ops/ms [Average]
  (min, avg, max) = (12.868, 12.931, 13.023), stdev = 0.081
  CI (99.9%): [11.456, 14.407] (assumes normal distribution)


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
# Warmup Iteration   1: 7.642 ops/ms
# Warmup Iteration   2: 12.490 ops/ms
# Warmup Iteration   3: 12.665 ops/ms
Iteration   1: 12.667 ops/ms
Iteration   2: 12.697 ops/ms
Iteration   3: 12.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.708 ±(99.9%) 0.866 ops/ms [Average]
  (min, avg, max) = (12.667, 12.708, 12.760), stdev = 0.047
  CI (99.9%): [11.842, 13.574] (assumes normal distribution)


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
# Warmup Iteration   1: 6.387 ops/ms
# Warmup Iteration   2: 10.264 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.636 ops/ms
Iteration   2: 10.553 ops/ms
Iteration   3: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.616 ±(99.9%) 1.026 ops/ms [Average]
  (min, avg, max) = (10.553, 10.616, 10.660), stdev = 0.056
  CI (99.9%): [9.590, 11.642] (assumes normal distribution)


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.599 ±(99.9%) 0.004 ms/op
Iteration   1: 2.602 ±(99.9%) 0.004 ms/op
Iteration   2: 2.606 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.585 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (2.546, 2.585, 2.606), stdev = 0.033
  CI (99.9%): [1.976, 3.194] (assumes normal distribution)


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.527 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.524, 2.527, 2.529), stdev = 0.003
  CI (99.9%): [2.471, 2.583] (assumes normal distribution)


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
Iteration   3: 2.544 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.534 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.521, 2.534, 2.544), stdev = 0.012
  CI (99.9%): [2.316, 2.751] (assumes normal distribution)


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
# Warmup Iteration   1: 4.809 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.005 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
Iteration   3: 3.004 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (3.004, 3.016, 3.032), stdev = 0.014
  CI (99.9%): [2.762, 3.270] (assumes normal distribution)


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.765 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.587 ±(99.9%) 0.006 ms/op
Iteration   1: 2.577 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  11.977 ms/op
                 createUser·p0.9999: 13.851 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 2.612 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  9.857 ms/op
                 createUser·p0.9999: 13.727 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   3: 2.601 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 10.984 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369346
  mean =      2.596 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 173952 
    [ 2.500,  3.750) = 190431 
    [ 3.750,  5.000) = 3957 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.293 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.156 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  5.964 ms/op
                 existUser·p0.9999: 14.189 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  7.591 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 12.369 ms/op
                 existUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390261
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 195093 
    [ 2.500,  3.750) = 191458 
    [ 3.750,  5.000) = 2752 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.337 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     14.563 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  12.485 ms/op
                 getUser·p0.9999: 14.343 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.579 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.371 ms/op
                 getUser·p0.99:   4.395 ms/op
                 getUser·p0.999:  10.028 ms/op
                 getUser·p0.9999: 16.410 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 11.833 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377698
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 184078 
    [ 2.500,  3.750) = 187861 
    [ 3.750,  5.000) = 4710 
    [ 5.000,  6.250) = 613 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =      8.901 ms/op
     p(99.9900) =     14.717 ms/op
     p(99.9990) =     16.748 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.764 ms/op
                 listUser·p0.9999: 13.037 ms/op
                 listUser·p1.00:   13.631 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 11.540 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  10.462 ms/op
                 listUser·p0.9999: 12.131 ms/op
                 listUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318488
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 89949 
    [ 2.500,  3.750) = 189831 
    [ 3.750,  5.000) = 31970 
    [ 5.000,  6.250) = 5438 
    [ 6.250,  7.500) = 517 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 257 
    [10.000, 11.250) = 221 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     12.110 ms/op
     p(99.9990) =     13.351 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.669 ± 1.596  ops/ms
ClientPb.existUser                       thrpt       3  12.931 ± 1.476  ops/ms
ClientPb.getUser                         thrpt       3  12.708 ± 0.866  ops/ms
ClientPb.listUser                        thrpt       3  10.616 ± 1.026  ops/ms
ClientPb.createUser                       avgt       3   2.585 ± 0.609   ms/op
ClientPb.existUser                        avgt       3   2.527 ± 0.056   ms/op
ClientPb.getUser                          avgt       3   2.534 ± 0.217   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.254   ms/op
ClientPb.createUser                     sample  369346   2.596 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.792           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.648           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  390261   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.861           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.991           ms/op
ClientPb.getUser                        sample  377698   2.539 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.830           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.901           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.717           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.170           ms/op
ClientPb.listUser                       sample  318488   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.945           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.110           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.631           ms/op
