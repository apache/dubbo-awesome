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
# Warmup Iteration   1: 2.502 ops/ms
# Warmup Iteration   2: 4.961 ops/ms
# Warmup Iteration   3: 9.028 ops/ms
Iteration   1: 10.143 ops/ms
Iteration   2: 10.232 ops/ms
Iteration   3: 9.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.063 ±(99.9%) 4.015 ops/ms [Average]
  (min, avg, max) = (9.814, 10.063, 10.232), stdev = 0.220
  CI (99.9%): [6.048, 14.078] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ops/ms
# Warmup Iteration   2: 9.789 ops/ms
# Warmup Iteration   3: 10.623 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 11.003 ops/ms
Iteration   3: 9.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.600 ±(99.9%) 9.733 ops/ms [Average]
  (min, avg, max) = (9.995, 10.600, 11.003), stdev = 0.533
  CI (99.9%): [0.867, 20.333] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.508 ops/ms
# Warmup Iteration   2: 9.640 ops/ms
# Warmup Iteration   3: 9.566 ops/ms
Iteration   1: 10.334 ops/ms
Iteration   2: 10.036 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.220 ±(99.9%) 2.926 ops/ms [Average]
  (min, avg, max) = (10.036, 10.220, 10.334), stdev = 0.160
  CI (99.9%): [7.294, 13.146] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ops/ms
# Warmup Iteration   2: 8.205 ops/ms
# Warmup Iteration   3: 8.348 ops/ms
Iteration   1: 8.542 ops/ms
Iteration   2: 8.715 ops/ms
Iteration   3: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.631 ±(99.9%) 1.573 ops/ms [Average]
  (min, avg, max) = (8.542, 8.631, 8.715), stdev = 0.086
  CI (99.9%): [7.059, 10.204] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.217 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.005 ms/op
Iteration   1: 3.276 ±(99.9%) 0.008 ms/op
Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
Iteration   3: 3.048 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.156 ±(99.9%) 2.089 ms/op [Average]
  (min, avg, max) = (3.048, 3.156, 3.276), stdev = 0.115
  CI (99.9%): [1.067, 5.245] (assumes normal distribution)


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
# Warmup Iteration   1: 7.895 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.104 ±(99.9%) 0.009 ms/op
Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
Iteration   3: 2.969 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.066 ±(99.9%) 1.540 ms/op [Average]
  (min, avg, max) = (2.969, 3.066, 3.125), stdev = 0.084
  CI (99.9%): [1.526, 4.606] (assumes normal distribution)


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
# Warmup Iteration   1: 6.996 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.004 ms/op
Iteration   1: 3.241 ±(99.9%) 0.005 ms/op
Iteration   2: 3.172 ±(99.9%) 0.006 ms/op
Iteration   3: 3.226 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.213 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.172, 3.213, 3.241), stdev = 0.037
  CI (99.9%): [2.546, 3.880] (assumes normal distribution)


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
# Warmup Iteration   1: 8.148 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.007 ms/op
Iteration   1: 3.819 ±(99.9%) 0.005 ms/op
Iteration   2: 3.750 ±(99.9%) 0.008 ms/op
Iteration   3: 3.726 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.765 ±(99.9%) 0.881 ms/op [Average]
  (min, avg, max) = (3.726, 3.765, 3.819), stdev = 0.048
  CI (99.9%): [2.885, 4.646] (assumes normal distribution)


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
# Warmup Iteration   1: 7.276 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.008 ms/op
Iteration   1: 3.144 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.400 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  8.313 ms/op
                 createUser·p0.9999: 22.751 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.173 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  13.337 ms/op
                 createUser·p0.9999: 21.919 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   3: 3.056 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.236 ms/op
                 createUser·p0.95:   3.404 ms/op
                 createUser·p0.99:   4.116 ms/op
                 createUser·p0.999:  9.112 ms/op
                 createUser·p0.9999: 16.483 ms/op
                 createUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307199
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34077 
    [ 2.500,  5.000) = 267952 
    [ 5.000,  7.500) = 4445 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.441 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     21.964 ms/op
     p(99.9990) =     23.361 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 6.952 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
Iteration   1: 2.978 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  8.266 ms/op
                 existUser·p0.9999: 25.068 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  9.929 ms/op
                 existUser·p0.9999: 21.878 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  9.650 ms/op
                 existUser·p0.9999: 19.888 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 317031
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18581 
    [ 2.500,  5.000) = 293823 
    [ 5.000,  7.500) = 4104 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      9.627 ms/op
     p(99.9900) =     23.382 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 7.387 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.010 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 20.049 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  9.664 ms/op
                 getUser·p0.9999: 22.243 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.130 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  13.812 ms/op
                 getUser·p0.9999: 25.742 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304842
  mean =      3.147 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12069 
    [ 2.500,  5.000) = 286072 
    [ 5.000,  7.500) = 5796 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     15.124 ms/op
     p(99.9900) =     23.922 ms/op
     p(99.9990) =     26.433 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 8.729 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.011 ms/op
Iteration   1: 3.749 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  18.699 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 3.694 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  14.086 ms/op
                 listUser·p0.9999: 18.318 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 3.707 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.929 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.921 ms/op
                 listUser·p0.9999: 21.737 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258328
  mean =      3.716 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 249679 
    [ 5.000,  7.500) = 6322 
    [ 7.500, 10.000) = 1534 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     24.227 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.063 ± 4.015  ops/ms
ClientPb.existUser                       thrpt       3  10.600 ± 9.733  ops/ms
ClientPb.getUser                         thrpt       3  10.220 ± 2.926  ops/ms
ClientPb.listUser                        thrpt       3   8.631 ± 1.573  ops/ms
ClientPb.createUser                       avgt       3   3.156 ± 2.089   ms/op
ClientPb.existUser                        avgt       3   3.066 ± 1.540   ms/op
ClientPb.getUser                          avgt       3   3.213 ± 0.667   ms/op
ClientPb.listUser                         avgt       3   3.765 ± 0.881   ms/op
ClientPb.createUser                     sample  307199   3.123 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.013           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.993           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.964           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.527           ms/op
ClientPb.existUser                      sample  317031   3.025 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.948           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.627           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.382           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.887           ms/op
ClientPb.getUser                        sample  304842   3.147 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.987           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.482           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.124           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.922           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.673           ms/op
ClientPb.listUser                       sample  258328   3.716 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.812           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.839           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.838           ms/op
