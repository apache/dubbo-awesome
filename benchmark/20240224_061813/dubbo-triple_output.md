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
# Warmup Iteration   1: 4.140 ops/ms
# Warmup Iteration   2: 12.085 ops/ms
# Warmup Iteration   3: 12.583 ops/ms
Iteration   1: 12.606 ops/ms
Iteration   2: 12.645 ops/ms
Iteration   3: 12.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.692 ±(99.9%) 2.113 ops/ms [Average]
  (min, avg, max) = (12.606, 12.692, 12.823), stdev = 0.116
  CI (99.9%): [10.578, 14.805] (assumes normal distribution)


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
# Warmup Iteration   1: 8.505 ops/ms
# Warmup Iteration   2: 13.086 ops/ms
# Warmup Iteration   3: 13.198 ops/ms
Iteration   1: 13.260 ops/ms
Iteration   2: 13.256 ops/ms
Iteration   3: 13.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.251 ±(99.9%) 0.237 ops/ms [Average]
  (min, avg, max) = (13.236, 13.251, 13.260), stdev = 0.013
  CI (99.9%): [13.013, 13.488] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.123 ops/ms
# Warmup Iteration   2: 12.909 ops/ms
# Warmup Iteration   3: 12.840 ops/ms
Iteration   1: 12.873 ops/ms
Iteration   2: 12.890 ops/ms
Iteration   3: 12.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.873 ±(99.9%) 0.319 ops/ms [Average]
  (min, avg, max) = (12.855, 12.873, 12.890), stdev = 0.017
  CI (99.9%): [12.554, 13.191] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.632 ops/ms
# Warmup Iteration   2: 10.327 ops/ms
# Warmup Iteration   3: 10.430 ops/ms
Iteration   1: 10.457 ops/ms
Iteration   2: 10.487 ops/ms
Iteration   3: 10.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.511 ±(99.9%) 1.256 ops/ms [Average]
  (min, avg, max) = (10.457, 10.511, 10.588), stdev = 0.069
  CI (99.9%): [9.254, 11.767] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.543 ±(99.9%) 0.003 ms/op
Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.538, 2.545, 2.555), stdev = 0.009
  CI (99.9%): [2.382, 2.709] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.004 ms/op
Iteration   1: 2.411 ±(99.9%) 0.004 ms/op
Iteration   2: 2.434 ±(99.9%) 0.003 ms/op
Iteration   3: 2.426 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.424 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.411, 2.424, 2.434), stdev = 0.012
  CI (99.9%): [2.213, 2.635] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.860 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.447, 2.461, 2.472), stdev = 0.013
  CI (99.9%): [2.231, 2.692] (assumes normal distribution)


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.007 ms/op
Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
Iteration   3: 3.023 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (3.023, 3.033, 3.045), stdev = 0.011
  CI (99.9%): [2.837, 3.229] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.676 ms/op
                 createUser·p0.9999: 13.935 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.529 ms/op
                 createUser·p0.9999: 12.380 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 11.301 ms/op
                 createUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374267
  mean =      2.563 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 179011 
    [ 2.500,  3.750) = 190991 
    [ 3.750,  5.000) = 3422 
    [ 5.000,  6.250) = 363 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.650 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     15.430 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  5.888 ms/op
                 existUser·p0.9999: 14.106 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  6.806 ms/op
                 existUser·p0.9999: 13.647 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  5.911 ms/op
                 existUser·p0.9999: 11.928 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390097
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 190970 
    [ 2.500,  3.750) = 196463 
    [ 3.750,  5.000) = 2078 
    [ 5.000,  6.250) = 166 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =      5.996 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.864 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  11.368 ms/op
                 getUser·p0.9999: 14.050 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  9.472 ms/op
                 getUser·p0.9999: 13.285 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 11.408 ms/op
                 getUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381013
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 187289 
    [ 2.500,  3.750) = 189145 
    [ 3.750,  5.000) = 3636 
    [ 5.000,  6.250) = 430 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     13.759 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.009 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.710 ms/op
                 listUser·p0.9999: 10.619 ms/op
                 listUser·p1.00:   14.025 ms/op

Iteration   2: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 12.213 ms/op
                 listUser·p1.00:   13.140 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  10.059 ms/op
                 listUser·p0.9999: 12.491 ms/op
                 listUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317730
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 91150 
    [ 2.500,  3.750) = 186272 
    [ 3.750,  5.000) = 32682 
    [ 5.000,  6.250) = 6180 
    [ 6.250,  7.500) = 670 
    [ 7.500,  8.750) = 218 
    [ 8.750, 10.000) = 227 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     12.144 ms/op
     p(99.9990) =     13.137 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.692 ± 2.113  ops/ms
ClientPb.existUser                       thrpt       3  13.251 ± 0.237  ops/ms
ClientPb.getUser                         thrpt       3  12.873 ± 0.319  ops/ms
ClientPb.listUser                        thrpt       3  10.511 ± 1.256  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.164   ms/op
ClientPb.existUser                        avgt       3   2.424 ± 0.211   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.231   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.196   ms/op
ClientPb.createUser                     sample  374267   2.563 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.650           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.566           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.333           ms/op
ClientPb.existUser                      sample  390097   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.953           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.996           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.959           ms/op
ClientPb.getUser                        sample  381013   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.470           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.759           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.418           ms/op
ClientPb.listUser                       sample  317730   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.863           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.144           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.025           ms/op
