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
# Warmup Iteration   1: 2.171 ops/ms
# Warmup Iteration   2: 6.229 ops/ms
# Warmup Iteration   3: 8.207 ops/ms
Iteration   1: 8.942 ops/ms
Iteration   2: 9.215 ops/ms
Iteration   3: 8.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.046 ±(99.9%) 2.698 ops/ms [Average]
  (min, avg, max) = (8.942, 9.046, 9.215), stdev = 0.148
  CI (99.9%): [6.348, 11.744] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.963 ops/ms
# Warmup Iteration   2: 8.588 ops/ms
# Warmup Iteration   3: 9.148 ops/ms
Iteration   1: 9.745 ops/ms
Iteration   2: 9.791 ops/ms
Iteration   3: 9.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.807 ±(99.9%) 1.318 ops/ms [Average]
  (min, avg, max) = (9.745, 9.807, 9.886), stdev = 0.072
  CI (99.9%): [8.489, 11.125] (assumes normal distribution)


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
# Warmup Iteration   1: 3.428 ops/ms
# Warmup Iteration   2: 8.610 ops/ms
# Warmup Iteration   3: 9.019 ops/ms
Iteration   1: 9.199 ops/ms
Iteration   2: 9.408 ops/ms
Iteration   3: 9.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.442 ±(99.9%) 4.770 ops/ms [Average]
  (min, avg, max) = (9.199, 9.442, 9.718), stdev = 0.261
  CI (99.9%): [4.672, 14.212] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.928 ops/ms
# Warmup Iteration   2: 7.379 ops/ms
# Warmup Iteration   3: 7.859 ops/ms
Iteration   1: 7.617 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 8.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.921 ±(99.9%) 5.493 ops/ms [Average]
  (min, avg, max) = (7.617, 7.921, 8.219), stdev = 0.301
  CI (99.9%): [2.428, 13.414] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.747 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.011 ms/op
Iteration   1: 3.409 ±(99.9%) 0.008 ms/op
Iteration   2: 3.303 ±(99.9%) 0.012 ms/op
Iteration   3: 3.372 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.362 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.303, 3.362, 3.409), stdev = 0.054
  CI (99.9%): [2.378, 4.345] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.824 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.005 ms/op
Iteration   1: 3.254 ±(99.9%) 0.010 ms/op
Iteration   2: 3.190 ±(99.9%) 0.011 ms/op
Iteration   3: 3.282 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.242 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (3.190, 3.242, 3.282), stdev = 0.047
  CI (99.9%): [2.388, 4.096] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.403 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.006 ms/op
Iteration   1: 3.513 ±(99.9%) 0.006 ms/op
Iteration   2: 3.297 ±(99.9%) 0.006 ms/op
Iteration   3: 3.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.418 ±(99.9%) 2.014 ms/op [Average]
  (min, avg, max) = (3.297, 3.418, 3.513), stdev = 0.110
  CI (99.9%): [1.404, 5.432] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.123 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.009 ms/op
Iteration   1: 3.974 ±(99.9%) 0.011 ms/op
Iteration   2: 3.859 ±(99.9%) 0.014 ms/op
Iteration   3: 3.936 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.923 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (3.859, 3.923, 3.974), stdev = 0.059
  CI (99.9%): [2.855, 4.991] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.810 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.009 ms/op
Iteration   1: 3.437 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.788 ms/op
                 createUser·p0.999:  20.608 ms/op
                 createUser·p0.9999: 26.860 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 3.404 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  22.086 ms/op
                 createUser·p0.9999: 25.035 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   3: 3.413 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.098 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  17.470 ms/op
                 createUser·p0.9999: 29.322 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280958
  mean =      3.418 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10700 
    [ 2.500,  5.000) = 263414 
    [ 5.000,  7.500) = 5849 
    [ 7.500, 10.000) = 451 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     18.581 ms/op
     p(99.9900) =     28.243 ms/op
     p(99.9990) =     30.125 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.966 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.009 ms/op
Iteration   1: 3.291 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.423 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  10.306 ms/op
                 existUser·p0.9999: 20.283 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.318 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  15.888 ms/op
                 existUser·p0.9999: 25.124 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  12.587 ms/op
                 existUser·p0.9999: 25.625 ms/op
                 existUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290469
  mean =      3.303 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13528 
    [ 2.500,  5.000) = 271920 
    [ 5.000,  7.500) = 4277 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     24.638 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 9.603 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.012 ms/op
Iteration   1: 3.520 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  21.770 ms/op
                 getUser·p0.9999: 24.277 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   2: 3.360 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.642 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  23.082 ms/op
                 getUser·p0.9999: 29.376 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   3: 3.386 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.831 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.929 ms/op
                 getUser·p0.999:  24.496 ms/op
                 getUser·p0.9999: 30.530 ms/op
                 getUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280361
  mean =      3.421 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14807 
    [ 2.500,  5.000) = 258215 
    [ 5.000,  7.500) = 6249 
    [ 7.500, 10.000) = 640 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     21.812 ms/op
     p(99.9900) =     29.621 ms/op
     p(99.9990) =     32.079 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 11.064 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.931 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.254 ±(99.9%) 0.015 ms/op
Iteration   1: 3.896 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.706 ms/op
                 listUser·p0.999:  22.315 ms/op
                 listUser·p0.9999: 25.257 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   2: 4.022 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.797 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 16.091 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 3.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.234 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 16.940 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241993
  mean =      3.966 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 235776 
    [ 5.000,  7.500) = 4208 
    [ 7.500, 10.000) = 1309 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     24.701 ms/op
     p(99.9990) =     26.798 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.046 ± 2.698  ops/ms
ClientPb.existUser                       thrpt       3   9.807 ± 1.318  ops/ms
ClientPb.getUser                         thrpt       3   9.442 ± 4.770  ops/ms
ClientPb.listUser                        thrpt       3   7.921 ± 5.493  ops/ms
ClientPb.createUser                       avgt       3   3.362 ± 0.984   ms/op
ClientPb.existUser                        avgt       3   3.242 ± 0.854   ms/op
ClientPb.getUser                          avgt       3   3.418 ± 2.014   ms/op
ClientPb.listUser                         avgt       3   3.923 ± 1.068   ms/op
ClientPb.createUser                     sample  280958   3.418 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.440           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.581           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.243           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.605           ms/op
ClientPb.existUser                      sample  290469   3.303 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.198           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.051           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.485           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.638           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.723           ms/op
ClientPb.getUser                        sample  280361   3.421 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.491           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.812           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.621           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276           ms/op
ClientPb.listUser                       sample  241993   3.966 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.032           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.024           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.701           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.099           ms/op
