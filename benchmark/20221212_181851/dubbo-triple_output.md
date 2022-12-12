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
# Warmup Iteration   1: 2.382 ops/ms
# Warmup Iteration   2: 6.619 ops/ms
# Warmup Iteration   3: 9.262 ops/ms
Iteration   1: 9.948 ops/ms
Iteration   2: 10.120 ops/ms
Iteration   3: 10.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.033 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (9.948, 10.033, 10.120), stdev = 0.086
  CI (99.9%): [8.456, 11.609] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ops/ms
# Warmup Iteration   2: 9.479 ops/ms
# Warmup Iteration   3: 10.339 ops/ms
Iteration   1: 10.419 ops/ms
Iteration   2: 10.603 ops/ms
Iteration   3: 10.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.459 ±(99.9%) 2.341 ops/ms [Average]
  (min, avg, max) = (10.356, 10.459, 10.603), stdev = 0.128
  CI (99.9%): [8.118, 12.800] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.448 ops/ms
# Warmup Iteration   2: 9.101 ops/ms
# Warmup Iteration   3: 9.531 ops/ms
Iteration   1: 9.983 ops/ms
Iteration   2: 10.081 ops/ms
Iteration   3: 9.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.897 ±(99.9%) 4.358 ops/ms [Average]
  (min, avg, max) = (9.627, 9.897, 10.081), stdev = 0.239
  CI (99.9%): [5.539, 14.255] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.369 ops/ms
# Warmup Iteration   2: 7.830 ops/ms
# Warmup Iteration   3: 8.395 ops/ms
Iteration   1: 8.357 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.376 ±(99.9%) 2.073 ops/ms [Average]
  (min, avg, max) = (8.274, 8.376, 8.498), stdev = 0.114
  CI (99.9%): [6.304, 10.449] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.773 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.004 ms/op
Iteration   1: 3.255 ±(99.9%) 0.008 ms/op
Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
Iteration   3: 3.142 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.236 ±(99.9%) 1.578 ms/op [Average]
  (min, avg, max) = (3.142, 3.236, 3.312), stdev = 0.087
  CI (99.9%): [1.658, 4.815] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.631 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.004 ms/op
Iteration   1: 3.137 ±(99.9%) 0.009 ms/op
Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
Iteration   3: 2.959 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.070 ±(99.9%) 1.760 ms/op [Average]
  (min, avg, max) = (2.959, 3.070, 3.137), stdev = 0.096
  CI (99.9%): [1.309, 4.830] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.789 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.005 ms/op
Iteration   1: 3.281 ±(99.9%) 0.006 ms/op
Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
Iteration   3: 3.141 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.178 ±(99.9%) 1.644 ms/op [Average]
  (min, avg, max) = (3.113, 3.178, 3.281), stdev = 0.090
  CI (99.9%): [1.534, 4.822] (assumes normal distribution)


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
# Warmup Iteration   1: 9.027 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.007 ms/op
Iteration   1: 3.667 ±(99.9%) 0.012 ms/op
Iteration   2: 3.710 ±(99.9%) 0.008 ms/op
Iteration   3: 3.636 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.671 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.636, 3.671, 3.710), stdev = 0.037
  CI (99.9%): [2.993, 4.348] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.342 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
Iteration   1: 3.153 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  15.353 ms/op
                 createUser·p0.9999: 19.497 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  10.280 ms/op
                 createUser·p0.9999: 25.128 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  17.021 ms/op
                 createUser·p0.9999: 23.168 ms/op
                 createUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302665
  mean =      3.171 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12427 
    [ 2.500,  5.000) = 285529 
    [ 5.000,  7.500) = 3872 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     16.411 ms/op
     p(99.9900) =     23.224 ms/op
     p(99.9990) =     25.459 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 7.259 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.033 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.605 ms/op
                 existUser·p0.999:  10.380 ms/op
                 existUser·p0.9999: 25.985 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.671 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  13.463 ms/op
                 existUser·p0.9999: 23.156 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.336 ms/op
                 existUser·p0.9999: 20.342 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310791
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12258 
    [ 2.500,  5.000) = 294460 
    [ 5.000,  7.500) = 3357 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     24.235 ms/op
     p(99.9990) =     26.711 ms/op
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
# Warmup Iteration   1: 7.626 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.012 ms/op
Iteration   1: 3.186 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  10.675 ms/op
                 getUser·p0.9999: 22.704 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  9.464 ms/op
                 getUser·p0.9999: 23.187 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  15.532 ms/op
                 getUser·p0.9999: 21.515 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300172
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2813 
    [ 2.500,  5.000) = 291923 
    [ 5.000,  7.500) = 4444 
    [ 7.500, 10.000) = 651 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     15.272 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 8.813 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.011 ms/op
Iteration   1: 3.698 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 26.608 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 3.746 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.844 ms/op
                 listUser·p0.999:  12.550 ms/op
                 listUser·p0.9999: 16.695 ms/op
                 listUser·p1.00:   16.761 ms/op

Iteration   3: 3.792 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.623 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 16.187 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256298
  mean =      3.745 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 249452 
    [ 5.000,  7.500) = 4735 
    [ 7.500, 10.000) = 1365 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     27.036 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.033 ± 1.576  ops/ms
ClientPb.existUser                       thrpt       3  10.459 ± 2.341  ops/ms
ClientPb.getUser                         thrpt       3   9.897 ± 4.358  ops/ms
ClientPb.listUser                        thrpt       3   8.376 ± 2.073  ops/ms
ClientPb.createUser                       avgt       3   3.236 ± 1.578   ms/op
ClientPb.existUser                        avgt       3   3.070 ± 1.760   ms/op
ClientPb.getUser                          avgt       3   3.178 ± 1.644   ms/op
ClientPb.listUser                         avgt       3   3.671 ± 0.677   ms/op
ClientPb.createUser                     sample  302665   3.171 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.935           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.539           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.411           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.224           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.526           ms/op
ClientPb.existUser                      sample  310791   3.088 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.794           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.764           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.235           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.804           ms/op
ClientPb.getUser                        sample  300172   3.195 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.839           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.272           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.839           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.642           ms/op
ClientPb.listUser                       sample  256298   3.745 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.114           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.451           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.133           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.230           ms/op
