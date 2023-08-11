# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.150 ops/ms
# Warmup Iteration   2: 5.608 ops/ms
# Warmup Iteration   3: 7.681 ops/ms
Iteration   1: 8.638 ops/ms
Iteration   2: 9.080 ops/ms
Iteration   3: 9.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.072 ±(99.9%) 7.832 ops/ms [Average]
  (min, avg, max) = (8.638, 9.072, 9.497), stdev = 0.429
  CI (99.9%): [1.239, 16.904] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.905 ops/ms
# Warmup Iteration   2: 8.222 ops/ms
# Warmup Iteration   3: 9.610 ops/ms
Iteration   1: 9.444 ops/ms
Iteration   2: 9.477 ops/ms
Iteration   3: 9.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.443 ±(99.9%) 0.637 ops/ms [Average]
  (min, avg, max) = (9.407, 9.443, 9.477), stdev = 0.035
  CI (99.9%): [8.805, 10.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.582 ops/ms
# Warmup Iteration   2: 8.121 ops/ms
# Warmup Iteration   3: 8.994 ops/ms
Iteration   1: 9.315 ops/ms
Iteration   2: 9.559 ops/ms
Iteration   3: 9.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.402 ±(99.9%) 2.485 ops/ms [Average]
  (min, avg, max) = (9.315, 9.402, 9.559), stdev = 0.136
  CI (99.9%): [6.917, 11.887] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.850 ops/ms
# Warmup Iteration   2: 7.182 ops/ms
# Warmup Iteration   3: 7.490 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 7.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.828 ±(99.9%) 0.938 ops/ms [Average]
  (min, avg, max) = (7.783, 7.828, 7.884), stdev = 0.051
  CI (99.9%): [6.890, 8.766] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.963 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.011 ms/op
Iteration   1: 3.595 ±(99.9%) 0.007 ms/op
Iteration   2: 3.518 ±(99.9%) 0.008 ms/op
Iteration   3: 3.442 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.518 ±(99.9%) 1.399 ms/op [Average]
  (min, avg, max) = (3.442, 3.518, 3.595), stdev = 0.077
  CI (99.9%): [2.119, 4.917] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.588 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.006 ms/op
Iteration   1: 3.272 ±(99.9%) 0.009 ms/op
Iteration   2: 3.284 ±(99.9%) 0.007 ms/op
Iteration   3: 3.303 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.286 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.272, 3.286, 3.303), stdev = 0.015
  CI (99.9%): [3.010, 3.563] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.352 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.008 ms/op
Iteration   1: 3.364 ±(99.9%) 0.010 ms/op
Iteration   2: 3.432 ±(99.9%) 0.002 ms/op
Iteration   3: 3.397 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.398 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.364, 3.398, 3.432), stdev = 0.034
  CI (99.9%): [2.777, 4.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.161 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.669 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.006 ms/op
Iteration   1: 4.089 ±(99.9%) 0.007 ms/op
Iteration   2: 4.056 ±(99.9%) 0.006 ms/op
Iteration   3: 4.084 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.076 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (4.056, 4.076, 4.089), stdev = 0.018
  CI (99.9%): [3.749, 4.404] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.822 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.010 ms/op
Iteration   1: 3.484 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  21.143 ms/op
                 createUser·p0.9999: 27.427 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   2: 3.360 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  22.746 ms/op
                 createUser·p0.9999: 24.657 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.555 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.376 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276981
  mean =      3.465 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10001 
    [ 2.500,  5.000) = 258948 
    [ 5.000,  7.500) = 6623 
    [ 7.500, 10.000) = 997 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 155 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     17.728 ms/op
     p(99.9900) =     26.224 ms/op
     p(99.9990) =     28.042 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.930 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.009 ms/op
Iteration   1: 3.357 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 19.808 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.411 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.252 ms/op
                 existUser·p0.999:  19.865 ms/op
                 existUser·p0.9999: 27.009 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   3: 3.416 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  20.919 ms/op
                 existUser·p0.9999: 39.059 ms/op
                 existUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282591
  mean =      3.394 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 273453 
    [ 5.000, 10.000) = 8521 
    [10.000, 15.000) = 344 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 112 
    [25.000, 30.000) = 47 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     40.436 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.881 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.014 ms/op
Iteration   1: 3.485 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  18.913 ms/op
                 getUser·p0.9999: 24.801 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.543 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  21.192 ms/op
                 getUser·p0.9999: 25.198 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.462 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  18.733 ms/op
                 getUser·p0.9999: 30.598 ms/op
                 getUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274496
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 766 
    [ 2.500,  5.000) = 266126 
    [ 5.000,  7.500) = 5642 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     18.956 ms/op
     p(99.9900) =     29.611 ms/op
     p(99.9990) =     30.958 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.934 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.013 ms/op
Iteration   1: 4.133 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 23.242 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 4.111 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   8.013 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.229 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230855
  mean =      4.157 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 219437 
    [ 5.000,  7.500) = 8222 
    [ 7.500, 10.000) = 2012 
    [10.000, 12.500) = 649 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      8.359 ms/op
     p(99.9000) =     15.682 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     24.026 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.072 ± 7.832  ops/ms
ClientPb.existUser                       thrpt       3   9.443 ± 0.637  ops/ms
ClientPb.getUser                         thrpt       3   9.402 ± 2.485  ops/ms
ClientPb.listUser                        thrpt       3   7.828 ± 0.938  ops/ms
ClientPb.createUser                       avgt       3   3.518 ± 1.399   ms/op
ClientPb.existUser                        avgt       3   3.286 ± 0.277   ms/op
ClientPb.getUser                          avgt       3   3.398 ± 0.620   ms/op
ClientPb.listUser                         avgt       3   4.076 ± 0.327   ms/op
ClientPb.createUser                     sample  276981   3.465 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.103           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.728           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.224           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.901           ms/op
ClientPb.existUser                      sample  282591   3.394 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.676           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.814           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.501           ms/op
ClientPb.getUser                        sample  274496   3.496 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.956           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.611           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.785           ms/op
ClientPb.listUser                       sample  230855   4.157 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.085           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.989           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.359           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.682           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.315           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.347           ms/op
