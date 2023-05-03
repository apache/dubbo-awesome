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
# Warmup Iteration   1: 2.245 ops/ms
# Warmup Iteration   2: 5.333 ops/ms
# Warmup Iteration   3: 8.262 ops/ms
Iteration   1: 9.085 ops/ms
Iteration   2: 8.991 ops/ms
Iteration   3: 9.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.140 ±(99.9%) 3.334 ops/ms [Average]
  (min, avg, max) = (8.991, 9.140, 9.344), stdev = 0.183
  CI (99.9%): [5.806, 12.474] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ops/ms
# Warmup Iteration   2: 8.916 ops/ms
# Warmup Iteration   3: 9.428 ops/ms
Iteration   1: 9.778 ops/ms
Iteration   2: 9.811 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.777 ±(99.9%) 0.622 ops/ms [Average]
  (min, avg, max) = (9.743, 9.777, 9.811), stdev = 0.034
  CI (99.9%): [9.156, 10.399] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.199 ops/ms
# Warmup Iteration   2: 7.867 ops/ms
# Warmup Iteration   3: 9.022 ops/ms
Iteration   1: 8.691 ops/ms
Iteration   2: 9.259 ops/ms
Iteration   3: 9.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.999 ±(99.9%) 5.244 ops/ms [Average]
  (min, avg, max) = (8.691, 8.999, 9.259), stdev = 0.287
  CI (99.9%): [3.755, 14.243] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.849 ops/ms
# Warmup Iteration   2: 7.176 ops/ms
# Warmup Iteration   3: 7.797 ops/ms
Iteration   1: 7.893 ops/ms
Iteration   2: 8.016 ops/ms
Iteration   3: 7.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.957 ±(99.9%) 1.118 ops/ms [Average]
  (min, avg, max) = (7.893, 7.957, 8.016), stdev = 0.061
  CI (99.9%): [6.839, 9.075] (assumes normal distribution)


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
# Warmup Iteration   1: 9.932 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.006 ms/op
Iteration   1: 3.438 ±(99.9%) 0.005 ms/op
Iteration   2: 3.430 ±(99.9%) 0.010 ms/op
Iteration   3: 3.429 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.432 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (3.429, 3.432, 3.438), stdev = 0.005
  CI (99.9%): [3.338, 3.527] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.641 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.007 ms/op
Iteration   1: 3.474 ±(99.9%) 0.004 ms/op
Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
Iteration   3: 3.346 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 2.819 ms/op [Average]
  (min, avg, max) = (3.167, 3.329, 3.474), stdev = 0.155
  CI (99.9%): [0.510, 6.148] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.146 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.003 ms/op
Iteration   1: 3.294 ±(99.9%) 0.010 ms/op
Iteration   2: 3.377 ±(99.9%) 0.009 ms/op
Iteration   3: 3.318 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.329 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (3.294, 3.329, 3.377), stdev = 0.043
  CI (99.9%): [2.551, 4.108] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.618 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.008 ms/op
Iteration   1: 3.982 ±(99.9%) 0.004 ms/op
Iteration   2: 3.858 ±(99.9%) 0.009 ms/op
Iteration   3: 3.872 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.904 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (3.858, 3.904, 3.982), stdev = 0.068
  CI (99.9%): [2.663, 5.145] (assumes normal distribution)


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
# Warmup Iteration   1: 8.976 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.011 ms/op
Iteration   1: 3.336 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  19.215 ms/op
                 createUser·p0.9999: 34.695 ms/op
                 createUser·p1.00:   36.307 ms/op

Iteration   2: 3.360 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  19.623 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.373 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  18.127 ms/op
                 createUser·p0.9999: 24.056 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285854
  mean =      3.356 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8258 
    [ 2.500,  5.000) = 272306 
    [ 5.000,  7.500) = 4120 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     35.117 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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
# Warmup Iteration   1: 7.420 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.009 ms/op
Iteration   1: 3.195 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.782 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  9.568 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 23.562 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   3: 3.261 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  16.893 ms/op
                 existUser·p0.9999: 24.871 ms/op
                 existUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297438
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15869 
    [ 2.500,  5.000) = 277592 
    [ 5.000,  7.500) = 3146 
    [ 7.500, 10.000) = 436 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     23.634 ms/op
     p(99.9990) =     25.102 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 8.391 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.012 ms/op
Iteration   1: 3.428 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   6.354 ms/op
                 getUser·p0.999:  17.979 ms/op
                 getUser·p0.9999: 22.107 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.374 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.647 ms/op
                 getUser·p0.999:  21.172 ms/op
                 getUser·p0.9999: 45.613 ms/op
                 getUser·p1.00:   47.645 ms/op

Iteration   3: 3.501 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  16.172 ms/op
                 getUser·p0.9999: 25.428 ms/op
                 getUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279673
  mean =      3.434 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 272817 
    [ 5.000, 10.000) = 6446 
    [10.000, 15.000) = 112 
    [15.000, 20.000) = 106 
    [20.000, 25.000) = 143 
    [25.000, 30.000) = 23 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     16.853 ms/op
     p(99.9900) =     29.951 ms/op
     p(99.9990) =     47.083 ms/op
     p(99.9999) =     47.645 ms/op
    p(100.0000) =     47.645 ms/op


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
# Warmup Iteration   1: 10.109 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.464 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
Iteration   1: 3.902 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.817 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  18.422 ms/op
                 listUser·p0.9999: 34.341 ms/op
                 listUser·p1.00:   34.537 ms/op

Iteration   3: 3.815 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  15.954 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247558
  mean =      3.875 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 241210 
    [ 5.000,  7.500) = 4476 
    [ 7.500, 10.000) = 1083 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 162 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.817 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     17.218 ms/op
     p(99.9900) =     23.107 ms/op
     p(99.9990) =     34.475 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.140 ± 3.334  ops/ms
ClientPb.existUser                       thrpt       3   9.777 ± 0.622  ops/ms
ClientPb.getUser                         thrpt       3   8.999 ± 5.244  ops/ms
ClientPb.listUser                        thrpt       3   7.957 ± 1.118  ops/ms
ClientPb.createUser                       avgt       3   3.432 ± 0.094   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 2.819   ms/op
ClientPb.getUser                          avgt       3   3.329 ± 0.778   ms/op
ClientPb.listUser                         avgt       3   3.904 ± 1.241   ms/op
ClientPb.createUser                     sample  285854   3.356 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.977           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.153           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.013           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.307           ms/op
ClientPb.existUser                      sample  297438   3.226 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.346           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.042           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.634           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.330           ms/op
ClientPb.getUser                        sample  279673   3.434 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.805           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.853           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.951           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.645           ms/op
ClientPb.listUser                       sample  247558   3.875 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.817           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.218           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.107           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.537           ms/op
