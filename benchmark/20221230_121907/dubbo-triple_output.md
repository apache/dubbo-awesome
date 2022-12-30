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
# Warmup Iteration   1: 1.796 ops/ms
# Warmup Iteration   2: 4.478 ops/ms
# Warmup Iteration   3: 8.266 ops/ms
Iteration   1: 8.896 ops/ms
Iteration   2: 9.200 ops/ms
Iteration   3: 9.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.088 ±(99.9%) 3.046 ops/ms [Average]
  (min, avg, max) = (8.896, 9.088, 9.200), stdev = 0.167
  CI (99.9%): [6.042, 12.134] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.482 ops/ms
# Warmup Iteration   2: 7.767 ops/ms
# Warmup Iteration   3: 9.451 ops/ms
Iteration   1: 9.593 ops/ms
Iteration   2: 9.276 ops/ms
Iteration   3: 9.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.496 ±(99.9%) 3.490 ops/ms [Average]
  (min, avg, max) = (9.276, 9.496, 9.619), stdev = 0.191
  CI (99.9%): [6.006, 12.986] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.651 ops/ms
# Warmup Iteration   2: 8.138 ops/ms
# Warmup Iteration   3: 9.324 ops/ms
Iteration   1: 8.824 ops/ms
Iteration   2: 9.485 ops/ms
Iteration   3: 9.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.212 ±(99.9%) 6.306 ops/ms [Average]
  (min, avg, max) = (8.824, 9.212, 9.485), stdev = 0.346
  CI (99.9%): [2.906, 15.519] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.644 ops/ms
# Warmup Iteration   2: 6.745 ops/ms
# Warmup Iteration   3: 7.778 ops/ms
Iteration   1: 7.657 ops/ms
Iteration   2: 7.937 ops/ms
Iteration   3: 7.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.794 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (7.657, 7.794, 7.937), stdev = 0.140
  CI (99.9%): [5.241, 10.348] (assumes normal distribution)


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
# Warmup Iteration   1: 12.811 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.007 ms/op
Iteration   1: 3.427 ±(99.9%) 0.013 ms/op
Iteration   2: 3.511 ±(99.9%) 0.007 ms/op
Iteration   3: 3.410 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 0.986 ms/op [Average]
  (min, avg, max) = (3.410, 3.450, 3.511), stdev = 0.054
  CI (99.9%): [2.464, 4.435] (assumes normal distribution)


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
# Warmup Iteration   1: 10.274 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.004 ms/op
Iteration   1: 3.434 ±(99.9%) 0.005 ms/op
Iteration   2: 3.307 ±(99.9%) 0.006 ms/op
Iteration   3: 3.294 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.345 ±(99.9%) 1.409 ms/op [Average]
  (min, avg, max) = (3.294, 3.345, 3.434), stdev = 0.077
  CI (99.9%): [1.936, 4.754] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.138 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.008 ms/op
Iteration   1: 3.504 ±(99.9%) 0.006 ms/op
Iteration   2: 3.400 ±(99.9%) 0.011 ms/op
Iteration   3: 3.513 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.473 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.400, 3.473, 3.513), stdev = 0.063
  CI (99.9%): [2.323, 4.622] (assumes normal distribution)


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
# Warmup Iteration   1: 11.188 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.767 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.012 ms/op
Iteration   1: 4.098 ±(99.9%) 0.009 ms/op
Iteration   2: 4.125 ±(99.9%) 0.013 ms/op
Iteration   3: 4.053 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.092 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (4.053, 4.092, 4.125), stdev = 0.036
  CI (99.9%): [3.435, 4.749] (assumes normal distribution)


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
# Warmup Iteration   1: 11.482 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.015 ms/op
Iteration   1: 3.273 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 23.550 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.443 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  23.076 ms/op
                 createUser·p0.9999: 26.500 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   3: 3.594 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.786 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  21.660 ms/op
                 createUser·p0.9999: 28.186 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279658
  mean =      3.432 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8959 
    [ 2.500,  5.000) = 263466 
    [ 5.000,  7.500) = 6265 
    [ 7.500, 10.000) = 491 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     21.365 ms/op
     p(99.9900) =     27.690 ms/op
     p(99.9990) =     29.072 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 9.916 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.009 ms/op
Iteration   1: 3.201 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 24.249 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.303 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  13.318 ms/op
                 existUser·p0.9999: 26.793 ms/op
                 existUser·p1.00:   29.688 ms/op

Iteration   3: 3.370 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  18.833 ms/op
                 existUser·p0.9999: 25.396 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291476
  mean =      3.290 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10940 
    [ 2.500,  5.000) = 275794 
    [ 5.000,  7.500) = 3685 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     26.177 ms/op
     p(99.9990) =     29.177 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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
# Warmup Iteration   1: 9.989 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.009 ms/op
Iteration   1: 3.644 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  22.151 ms/op
                 getUser·p0.9999: 23.994 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.774 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  23.858 ms/op
                 getUser·p0.9999: 26.326 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.396 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  19.984 ms/op
                 getUser·p0.9999: 26.928 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274763
  mean =      3.490 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9638 
    [ 2.500,  5.000) = 257933 
    [ 5.000,  7.500) = 5814 
    [ 7.500, 10.000) = 791 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 147 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     20.954 ms/op
     p(99.9900) =     26.166 ms/op
     p(99.9990) =     28.239 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 14.182 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.742 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.015 ms/op
Iteration   1: 4.120 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.960 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  21.507 ms/op
                 listUser·p0.9999: 26.933 ms/op
                 listUser·p1.00:   27.951 ms/op

Iteration   2: 4.044 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  15.860 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236580
  mean =      4.058 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 228107 
    [ 5.000,  7.500) = 5848 
    [ 7.500, 10.000) = 1573 
    [10.000, 12.500) = 444 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.960 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     26.127 ms/op
     p(99.9990) =     27.843 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.088 ± 3.046  ops/ms
ClientPb.existUser                       thrpt       3   9.496 ± 3.490  ops/ms
ClientPb.getUser                         thrpt       3   9.212 ± 6.306  ops/ms
ClientPb.listUser                        thrpt       3   7.794 ± 2.554  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 0.986   ms/op
ClientPb.existUser                        avgt       3   3.345 ± 1.409   ms/op
ClientPb.getUser                          avgt       3   3.473 ± 1.149   ms/op
ClientPb.listUser                         avgt       3   4.092 ± 0.657   ms/op
ClientPb.createUser                     sample  279658   3.432 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.423           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.365           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.690           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  291476   3.290 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.233           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.942           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.177           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.688           ms/op
ClientPb.getUser                        sample  274763   3.490 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.356           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.954           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.166           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.705           ms/op
ClientPb.listUser                       sample  236580   4.058 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.960           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.127           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.951           ms/op
