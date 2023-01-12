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
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 5.222 ops/ms
# Warmup Iteration   3: 8.587 ops/ms
Iteration   1: 9.282 ops/ms
Iteration   2: 9.608 ops/ms
Iteration   3: 9.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.511 ±(99.9%) 3.623 ops/ms [Average]
  (min, avg, max) = (9.282, 9.511, 9.642), stdev = 0.199
  CI (99.9%): [5.887, 13.134] (assumes normal distribution)


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
# Warmup Iteration   1: 2.880 ops/ms
# Warmup Iteration   2: 8.368 ops/ms
# Warmup Iteration   3: 9.398 ops/ms
Iteration   1: 9.683 ops/ms
Iteration   2: 9.707 ops/ms
Iteration   3: 9.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.707 ±(99.9%) 0.430 ops/ms [Average]
  (min, avg, max) = (9.683, 9.707, 9.730), stdev = 0.024
  CI (99.9%): [9.277, 10.137] (assumes normal distribution)


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
# Warmup Iteration   1: 3.553 ops/ms
# Warmup Iteration   2: 8.781 ops/ms
# Warmup Iteration   3: 9.081 ops/ms
Iteration   1: 9.447 ops/ms
Iteration   2: 9.371 ops/ms
Iteration   3: 9.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.331 ±(99.9%) 2.551 ops/ms [Average]
  (min, avg, max) = (9.176, 9.331, 9.447), stdev = 0.140
  CI (99.9%): [6.781, 11.882] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 6.959 ops/ms
# Warmup Iteration   3: 7.553 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 7.894 ops/ms
Iteration   3: 7.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.909 ±(99.9%) 2.338 ops/ms [Average]
  (min, avg, max) = (7.788, 7.909, 8.044), stdev = 0.128
  CI (99.9%): [5.570, 10.247] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.381 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.008 ms/op
Iteration   1: 3.573 ±(99.9%) 0.004 ms/op
Iteration   2: 3.342 ±(99.9%) 0.006 ms/op
Iteration   3: 3.527 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.480 ±(99.9%) 2.233 ms/op [Average]
  (min, avg, max) = (3.342, 3.480, 3.573), stdev = 0.122
  CI (99.9%): [1.247, 5.714] (assumes normal distribution)


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
# Warmup Iteration   1: 7.943 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.005 ms/op
Iteration   1: 3.252 ±(99.9%) 0.010 ms/op
Iteration   2: 3.366 ±(99.9%) 0.003 ms/op
Iteration   3: 3.241 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.286 ±(99.9%) 1.264 ms/op [Average]
  (min, avg, max) = (3.241, 3.286, 3.366), stdev = 0.069
  CI (99.9%): [2.022, 4.550] (assumes normal distribution)


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
# Warmup Iteration   1: 9.253 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.003 ms/op
Iteration   1: 3.390 ±(99.9%) 0.006 ms/op
Iteration   2: 3.506 ±(99.9%) 0.005 ms/op
Iteration   3: 3.372 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.423 ±(99.9%) 1.331 ms/op [Average]
  (min, avg, max) = (3.372, 3.423, 3.506), stdev = 0.073
  CI (99.9%): [2.091, 4.754] (assumes normal distribution)


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
# Warmup Iteration   1: 10.901 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.365 ±(99.9%) 0.005 ms/op
Iteration   1: 4.323 ±(99.9%) 0.007 ms/op
Iteration   2: 4.097 ±(99.9%) 0.010 ms/op
Iteration   3: 4.168 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.196 ±(99.9%) 2.109 ms/op [Average]
  (min, avg, max) = (4.097, 4.196, 4.323), stdev = 0.116
  CI (99.9%): [2.087, 6.304] (assumes normal distribution)


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
# Warmup Iteration   1: 10.460 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.014 ms/op
Iteration   1: 3.428 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  20.045 ms/op
                 createUser·p0.9999: 24.238 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   2: 3.520 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  22.544 ms/op
                 createUser·p0.9999: 25.362 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  18.055 ms/op
                 createUser·p0.9999: 27.636 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277159
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6056 
    [ 2.500,  5.000) = 265140 
    [ 5.000,  7.500) = 4837 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     18.607 ms/op
     p(99.9900) =     26.149 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 8.746 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.009 ms/op
Iteration   1: 3.358 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  10.158 ms/op
                 existUser·p0.9999: 25.068 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   2: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  15.177 ms/op
                 existUser·p0.9999: 26.430 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   3: 3.260 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.772 ms/op
                 existUser·p0.999:  13.465 ms/op
                 existUser·p0.9999: 26.352 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290311
  mean =      3.307 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8295 
    [ 2.500,  5.000) = 276144 
    [ 5.000,  7.500) = 4934 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     12.403 ms/op
     p(99.9900) =     25.755 ms/op
     p(99.9990) =     27.233 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 8.759 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.011 ms/op
Iteration   1: 3.520 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  20.882 ms/op
                 getUser·p0.9999: 28.738 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   2: 3.457 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.910 ms/op
                 getUser·p0.999:  12.190 ms/op
                 getUser·p0.9999: 34.289 ms/op
                 getUser·p1.00:   34.406 ms/op

Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 28.194 ms/op
                 getUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277473
  mean =      3.459 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5445 
    [ 2.500,  5.000) = 264027 
    [ 5.000,  7.500) = 6861 
    [ 7.500, 10.000) = 633 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     32.276 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 11.085 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.622 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.014 ms/op
Iteration   1: 4.196 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  20.766 ms/op
                 listUser·p0.9999: 22.491 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 4.246 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  16.648 ms/op
                 listUser·p0.9999: 21.675 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 4.067 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  15.520 ms/op
                 listUser·p0.9999: 20.517 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230299
  mean =      4.168 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 219172 
    [ 5.000,  7.500) = 8664 
    [ 7.500, 10.000) = 1583 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.062 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.511 ± 3.623  ops/ms
ClientPb.existUser                       thrpt       3   9.707 ± 0.430  ops/ms
ClientPb.getUser                         thrpt       3   9.331 ± 2.551  ops/ms
ClientPb.listUser                        thrpt       3   7.909 ± 2.338  ops/ms
ClientPb.createUser                       avgt       3   3.480 ± 2.233   ms/op
ClientPb.existUser                        avgt       3   3.286 ± 1.264   ms/op
ClientPb.getUser                          avgt       3   3.423 ± 1.331   ms/op
ClientPb.listUser                         avgt       3   4.196 ± 2.109   ms/op
ClientPb.createUser                     sample  277159   3.463 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.567           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.607           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.149           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.886           ms/op
ClientPb.existUser                      sample  290311   3.307 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.206           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.403           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.755           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  277473   3.459 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.384           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.399           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.276           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  230299   4.168 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.126           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.561           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.121           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.086           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.298           ms/op
