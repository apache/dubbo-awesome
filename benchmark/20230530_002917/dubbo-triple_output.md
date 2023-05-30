# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.208 ops/ms
# Warmup Iteration   2: 4.991 ops/ms
# Warmup Iteration   3: 8.755 ops/ms
Iteration   1: 9.667 ops/ms
Iteration   2: 9.258 ops/ms
Iteration   3: 9.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.378 ±(99.9%) 4.580 ops/ms [Average]
  (min, avg, max) = (9.210, 9.378, 9.667), stdev = 0.251
  CI (99.9%): [4.798, 13.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 8.417 ops/ms
# Warmup Iteration   3: 9.182 ops/ms
Iteration   1: 9.755 ops/ms
Iteration   2: 9.918 ops/ms
Iteration   3: 9.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.837 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (9.755, 9.837, 9.918), stdev = 0.082
  CI (99.9%): [8.348, 11.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.005 ops/ms
# Warmup Iteration   2: 8.743 ops/ms
# Warmup Iteration   3: 8.727 ops/ms
Iteration   1: 9.124 ops/ms
Iteration   2: 9.248 ops/ms
Iteration   3: 9.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.212 ±(99.9%) 1.397 ops/ms [Average]
  (min, avg, max) = (9.124, 9.212, 9.264), stdev = 0.077
  CI (99.9%): [7.815, 10.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.733 ops/ms
# Warmup Iteration   2: 7.228 ops/ms
# Warmup Iteration   3: 7.814 ops/ms
Iteration   1: 8.090 ops/ms
Iteration   2: 8.318 ops/ms
Iteration   3: 7.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.126 ±(99.9%) 3.217 ops/ms [Average]
  (min, avg, max) = (7.971, 8.126, 8.318), stdev = 0.176
  CI (99.9%): [4.909, 11.344] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.944 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.005 ms/op
Iteration   1: 3.391 ±(99.9%) 0.009 ms/op
Iteration   2: 3.275 ±(99.9%) 0.011 ms/op
Iteration   3: 3.397 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.354 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (3.275, 3.354, 3.397), stdev = 0.069
  CI (99.9%): [2.096, 4.612] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.068 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.004 ms/op
Iteration   1: 3.279 ±(99.9%) 0.006 ms/op
Iteration   2: 3.276 ±(99.9%) 0.008 ms/op
Iteration   3: 3.368 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.308 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (3.276, 3.308, 3.368), stdev = 0.052
  CI (99.9%): [2.359, 4.257] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.447 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.004 ms/op
Iteration   1: 3.412 ±(99.9%) 0.002 ms/op
Iteration   2: 3.500 ±(99.9%) 0.004 ms/op
Iteration   3: 3.325 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.412 ±(99.9%) 1.599 ms/op [Average]
  (min, avg, max) = (3.325, 3.412, 3.500), stdev = 0.088
  CI (99.9%): [1.813, 5.012] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.539 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.009 ms/op
Iteration   1: 3.860 ±(99.9%) 0.015 ms/op
Iteration   2: 4.190 ±(99.9%) 0.006 ms/op
Iteration   3: 4.075 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.042 ±(99.9%) 3.054 ms/op [Average]
  (min, avg, max) = (3.860, 4.042, 4.190), stdev = 0.167
  CI (99.9%): [0.987, 7.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.869 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.008 ms/op
Iteration   1: 3.460 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.863 ms/op
                 createUser·p0.999:  19.254 ms/op
                 createUser·p0.9999: 27.345 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   2: 3.355 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  20.945 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 3.429 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  17.833 ms/op
                 createUser·p0.9999: 26.420 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281178
  mean =      3.414 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6830 
    [ 2.500,  5.000) = 268535 
    [ 5.000,  7.500) = 4749 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     18.082 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.832 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.171 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.009 ms/op
Iteration   1: 3.329 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.507 ms/op
                 existUser·p0.999:  12.075 ms/op
                 existUser·p0.9999: 25.182 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   2: 3.289 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.919 ms/op
                 existUser·p0.999:  19.818 ms/op
                 existUser·p0.9999: 24.969 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.422 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  18.934 ms/op
                 existUser·p0.9999: 25.765 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286936
  mean =      3.346 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13066 
    [ 2.500,  5.000) = 266952 
    [ 5.000,  7.500) = 5887 
    [ 7.500, 10.000) = 391 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     14.329 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     26.719 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.238 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.010 ms/op
Iteration   1: 3.486 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  19.988 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.549 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  21.856 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  20.510 ms/op
                 getUser·p0.9999: 26.791 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274106
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6976 
    [ 2.500,  5.000) = 255965 
    [ 5.000,  7.500) = 10002 
    [ 7.500, 10.000) = 675 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     26.168 ms/op
     p(99.9990) =     27.403 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.908 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.014 ms/op
Iteration   1: 4.110 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   7.363 ms/op
                 listUser·p0.999:  21.633 ms/op
                 listUser·p0.9999: 29.393 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 17.558 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.926 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.810 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 16.237 ms/op
                 listUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238470
  mean =      4.024 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 227579 
    [ 5.000,  7.500) = 8418 
    [ 7.500, 10.000) = 1355 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     16.147 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     29.446 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.378 ± 4.580  ops/ms
ClientPb.existUser                       thrpt       3   9.837 ± 1.490  ops/ms
ClientPb.getUser                         thrpt       3   9.212 ± 1.397  ops/ms
ClientPb.listUser                        thrpt       3   8.126 ± 3.217  ops/ms
ClientPb.createUser                       avgt       3   3.354 ± 1.258   ms/op
ClientPb.existUser                        avgt       3   3.308 ± 0.949   ms/op
ClientPb.getUser                          avgt       3   3.412 ± 1.599   ms/op
ClientPb.listUser                         avgt       3   4.042 ± 3.054   ms/op
ClientPb.createUser                     sample  281178   3.414 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.466           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.082           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.542           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.984           ms/op
ClientPb.existUser                      sample  286936   3.346 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.198           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.964           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.329           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.166           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.672           ms/op
ClientPb.getUser                        sample  274106   3.502 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.214           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.168           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.623           ms/op
ClientPb.listUser                       sample  238470   4.024 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.511           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.528           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.147           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.065           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.278           ms/op
