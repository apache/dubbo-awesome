# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.720 ops/ms
# Warmup Iteration   2: 6.519 ops/ms
# Warmup Iteration   3: 9.364 ops/ms
Iteration   1: 9.766 ops/ms
Iteration   2: 9.844 ops/ms
Iteration   3: 10.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.913 ±(99.9%) 3.485 ops/ms [Average]
  (min, avg, max) = (9.766, 9.913, 10.129), stdev = 0.191
  CI (99.9%): [6.428, 13.398] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.711 ops/ms
# Warmup Iteration   2: 9.225 ops/ms
# Warmup Iteration   3: 10.496 ops/ms
Iteration   1: 10.430 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.561 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (10.430, 10.561, 10.733), stdev = 0.156
  CI (99.9%): [7.724, 13.398] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.401 ops/ms
# Warmup Iteration   2: 8.609 ops/ms
# Warmup Iteration   3: 9.597 ops/ms
Iteration   1: 10.101 ops/ms
Iteration   2: 10.383 ops/ms
Iteration   3: 9.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.138 ±(99.9%) 4.155 ops/ms [Average]
  (min, avg, max) = (9.932, 10.138, 10.383), stdev = 0.228
  CI (99.9%): [5.984, 14.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 7.886 ops/ms
# Warmup Iteration   3: 8.288 ops/ms
Iteration   1: 8.400 ops/ms
Iteration   2: 8.437 ops/ms
Iteration   3: 8.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.428 ±(99.9%) 0.453 ops/ms [Average]
  (min, avg, max) = (8.400, 8.428, 8.447), stdev = 0.025
  CI (99.9%): [7.975, 8.881] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.210 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.002 ms/op
Iteration   1: 3.292 ±(99.9%) 0.003 ms/op
Iteration   2: 3.242 ±(99.9%) 0.004 ms/op
Iteration   3: 3.123 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.219 ±(99.9%) 1.580 ms/op [Average]
  (min, avg, max) = (3.123, 3.219, 3.292), stdev = 0.087
  CI (99.9%): [1.639, 4.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.790 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.004 ms/op
Iteration   2: 3.201 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.090 ±(99.9%) 1.812 ms/op [Average]
  (min, avg, max) = (3.008, 3.090, 3.201), stdev = 0.099
  CI (99.9%): [1.279, 4.902] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.830 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.002 ms/op
Iteration   1: 3.167 ±(99.9%) 0.003 ms/op
Iteration   2: 3.121 ±(99.9%) 0.005 ms/op
Iteration   3: 3.165 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.151 ±(99.9%) 0.466 ms/op [Average]
  (min, avg, max) = (3.121, 3.151, 3.167), stdev = 0.026
  CI (99.9%): [2.685, 3.617] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.218 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.005 ms/op
Iteration   1: 4.052 ±(99.9%) 0.009 ms/op
Iteration   2: 3.736 ±(99.9%) 0.010 ms/op
Iteration   3: 3.786 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.858 ±(99.9%) 3.105 ms/op [Average]
  (min, avg, max) = (3.736, 3.858, 4.052), stdev = 0.170
  CI (99.9%): [0.753, 6.963] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.155 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
Iteration   1: 3.136 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 20.591 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.310 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  14.368 ms/op
                 createUser·p0.9999: 34.472 ms/op
                 createUser·p1.00:   36.241 ms/op

Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  13.746 ms/op
                 createUser·p0.9999: 29.709 ms/op
                 createUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296393
  mean =      3.237 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18749 
    [ 2.500,  5.000) = 272797 
    [ 5.000,  7.500) = 3898 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     32.988 ms/op
     p(99.9990) =     35.017 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.001 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.071 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.314 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 21.777 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   2: 3.139 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  14.151 ms/op
                 existUser·p0.9999: 24.499 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.277 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  11.373 ms/op
                 existUser·p0.9999: 26.659 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310068
  mean =      3.092 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22534 
    [ 2.500,  5.000) = 282267 
    [ 5.000,  7.500) = 4206 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     13.106 ms/op
     p(99.9900) =     25.296 ms/op
     p(99.9990) =     27.122 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.531 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.010 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  17.174 ms/op
                 getUser·p0.9999: 26.170 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   2: 3.286 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  11.415 ms/op
                 getUser·p0.9999: 23.471 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.854 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 22.177 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292812
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13986 
    [ 2.500,  5.000) = 272574 
    [ 5.000,  7.500) = 5447 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     14.760 ms/op
     p(99.9900) =     24.394 ms/op
     p(99.9990) =     26.874 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.167 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.012 ms/op
Iteration   1: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.451 ms/op
                 listUser·p0.9999: 22.544 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 3.689 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 16.482 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.761 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.239 ms/op
                 listUser·p0.9999: 15.729 ms/op
                 listUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257505
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 249711 
    [ 5.000,  7.500) = 6026 
    [ 7.500, 10.000) = 1053 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     14.115 ms/op
     p(99.9900) =     20.947 ms/op
     p(99.9990) =     23.162 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.913 ± 3.485  ops/ms
ClientPb.existUser                       thrpt       3  10.561 ± 2.837  ops/ms
ClientPb.getUser                         thrpt       3  10.138 ± 4.155  ops/ms
ClientPb.listUser                        thrpt       3   8.428 ± 0.453  ops/ms
ClientPb.createUser                       avgt       3   3.219 ± 1.580   ms/op
ClientPb.existUser                        avgt       3   3.090 ± 1.812   ms/op
ClientPb.getUser                          avgt       3   3.151 ± 0.466   ms/op
ClientPb.listUser                         avgt       3   3.858 ± 3.105   ms/op
ClientPb.createUser                     sample  296393   3.237 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.227           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.155           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.988           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.241           ms/op
ClientPb.existUser                      sample  310068   3.092 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.106           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.296           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  292812   3.276 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.145           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.760           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.394           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.361           ms/op
ClientPb.listUser                       sample  257505   3.725 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.495           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.115           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.947           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.265           ms/op
