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
# Warmup Iteration   1: 5.085 ops/ms
# Warmup Iteration   2: 12.399 ops/ms
# Warmup Iteration   3: 12.716 ops/ms
Iteration   1: 12.842 ops/ms
Iteration   2: 13.080 ops/ms
Iteration   3: 13.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.986 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (12.842, 12.986, 13.080), stdev = 0.126
  CI (99.9%): [10.680, 15.292] (assumes normal distribution)


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
# Warmup Iteration   1: 8.229 ops/ms
# Warmup Iteration   2: 13.307 ops/ms
# Warmup Iteration   3: 13.433 ops/ms
Iteration   1: 13.480 ops/ms
Iteration   2: 13.455 ops/ms
Iteration   3: 13.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.375 ±(99.9%) 2.935 ops/ms [Average]
  (min, avg, max) = (13.189, 13.375, 13.480), stdev = 0.161
  CI (99.9%): [10.440, 16.310] (assumes normal distribution)


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
# Warmup Iteration   1: 7.833 ops/ms
# Warmup Iteration   2: 12.912 ops/ms
# Warmup Iteration   3: 12.885 ops/ms
Iteration   1: 13.056 ops/ms
Iteration   2: 13.170 ops/ms
Iteration   3: 13.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.158 ±(99.9%) 1.767 ops/ms [Average]
  (min, avg, max) = (13.056, 13.158, 13.248), stdev = 0.097
  CI (99.9%): [11.392, 14.925] (assumes normal distribution)


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
# Warmup Iteration   1: 6.566 ops/ms
# Warmup Iteration   2: 10.599 ops/ms
# Warmup Iteration   3: 10.846 ops/ms
Iteration   1: 10.890 ops/ms
Iteration   2: 10.797 ops/ms
Iteration   3: 10.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.840 ±(99.9%) 0.856 ops/ms [Average]
  (min, avg, max) = (10.797, 10.840, 10.890), stdev = 0.047
  CI (99.9%): [9.984, 11.696] (assumes normal distribution)


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.501, 2.513, 2.523), stdev = 0.011
  CI (99.9%): [2.304, 2.722] (assumes normal distribution)


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.419 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.403 ±(99.9%) 0.004 ms/op
Iteration   1: 2.404 ±(99.9%) 0.003 ms/op
Iteration   2: 2.411 ±(99.9%) 0.004 ms/op
Iteration   3: 2.404 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.406 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (2.404, 2.406, 2.411), stdev = 0.004
  CI (99.9%): [2.329, 2.484] (assumes normal distribution)


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.464, 2.486, 2.503), stdev = 0.020
  CI (99.9%): [2.122, 2.850] (assumes normal distribution)


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.007 ms/op
Iteration   2: 2.990 ±(99.9%) 0.007 ms/op
Iteration   3: 2.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.977 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (2.951, 2.977, 2.990), stdev = 0.022
  CI (99.9%): [2.568, 3.385] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  11.972 ms/op
                 createUser·p0.9999: 14.385 ms/op
                 createUser·p1.00:   16.433 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  10.699 ms/op
                 createUser·p0.9999: 13.633 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   4.039 ms/op
                 createUser·p0.999:  8.594 ms/op
                 createUser·p0.9999: 10.306 ms/op
                 createUser·p1.00:   10.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386649
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 191914 
    [ 2.500,  3.750) = 189988 
    [ 3.750,  5.000) = 3547 
    [ 5.000,  6.250) = 628 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     13.844 ms/op
     p(99.9990) =     14.819 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 3.623 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.412 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.006 ms/op
Iteration   1: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  4.915 ms/op
                 existUser·p0.9999: 13.074 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.591 ms/op
                 existUser·p0.999:  7.263 ms/op
                 existUser·p0.9999: 13.907 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   3: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  8.460 ms/op
                 existUser·p0.9999: 10.558 ms/op
                 existUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398282
  mean =      2.408 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 201180 
    [ 2.500,  3.750) = 194631 
    [ 3.750,  5.000) = 1817 
    [ 5.000,  6.250) = 204 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      6.812 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     14.746 ms/op
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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.006 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.588 ms/op
                 getUser·p0.999:  10.608 ms/op
                 getUser·p0.9999: 14.367 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   2.480 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  8.526 ms/op
                 getUser·p0.9999: 12.127 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  6.115 ms/op
                 getUser·p0.9999: 10.566 ms/op
                 getUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391877
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 198845 
    [ 2.500,  3.750) = 188836 
    [ 3.750,  5.000) = 3126 
    [ 5.000,  6.250) = 513 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.440 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.519 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.890 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.009 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 10.348 ms/op
                 listUser·p1.00:   11.239 ms/op

Iteration   2: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.085 ms/op
                 listUser·p0.9999: 11.556 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.101 ms/op
                 listUser·p0.9999: 10.886 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315555
  mean =      3.039 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 86662 
    [ 2.500,  3.750) = 186818 
    [ 3.750,  5.000) = 34262 
    [ 5.000,  6.250) = 6304 
    [ 6.250,  7.500) = 756 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 213 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     11.272 ms/op
     p(99.9990) =     12.098 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.986 ± 2.306  ops/ms
ClientPb.existUser                       thrpt       3  13.375 ± 2.935  ops/ms
ClientPb.getUser                         thrpt       3  13.158 ± 1.767  ops/ms
ClientPb.listUser                        thrpt       3  10.840 ± 0.856  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.209   ms/op
ClientPb.existUser                        avgt       3   2.406 ± 0.078   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.364   ms/op
ClientPb.listUser                         avgt       3   2.977 ± 0.408   ms/op
ClientPb.createUser                     sample  386649   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.810           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.601           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.844           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.433           ms/op
ClientPb.existUser                      sample  398282   2.408 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.005           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.812           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.124           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.778           ms/op
ClientPb.getUser                        sample  391877   2.448 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.675           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.440           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.271           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  315555   3.039 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.781           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.011           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.272           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.419           ms/op
