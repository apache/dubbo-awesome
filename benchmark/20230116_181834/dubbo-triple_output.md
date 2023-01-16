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
# Warmup Iteration   1: 2.737 ops/ms
# Warmup Iteration   2: 6.203 ops/ms
# Warmup Iteration   3: 8.778 ops/ms
Iteration   1: 9.739 ops/ms
Iteration   2: 10.198 ops/ms
Iteration   3: 10.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.047 ±(99.9%) 4.864 ops/ms [Average]
  (min, avg, max) = (9.739, 10.047, 10.203), stdev = 0.267
  CI (99.9%): [5.183, 14.911] (assumes normal distribution)


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
# Warmup Iteration   1: 3.383 ops/ms
# Warmup Iteration   2: 9.124 ops/ms
# Warmup Iteration   3: 10.272 ops/ms
Iteration   1: 10.077 ops/ms
Iteration   2: 10.313 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.341 ±(99.9%) 5.077 ops/ms [Average]
  (min, avg, max) = (10.077, 10.341, 10.632), stdev = 0.278
  CI (99.9%): [5.264, 15.418] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ops/ms
# Warmup Iteration   2: 9.391 ops/ms
# Warmup Iteration   3: 9.714 ops/ms
Iteration   1: 9.853 ops/ms
Iteration   2: 10.318 ops/ms
Iteration   3: 10.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.111 ±(99.9%) 4.321 ops/ms [Average]
  (min, avg, max) = (9.853, 10.111, 10.318), stdev = 0.237
  CI (99.9%): [5.790, 14.432] (assumes normal distribution)


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
# Warmup Iteration   1: 3.309 ops/ms
# Warmup Iteration   2: 7.608 ops/ms
# Warmup Iteration   3: 8.277 ops/ms
Iteration   1: 8.371 ops/ms
Iteration   2: 8.504 ops/ms
Iteration   3: 8.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.399 ±(99.9%) 1.701 ops/ms [Average]
  (min, avg, max) = (8.324, 8.399, 8.504), stdev = 0.093
  CI (99.9%): [6.699, 10.100] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.894 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.002 ms/op
Iteration   1: 3.301 ±(99.9%) 0.005 ms/op
Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
Iteration   3: 3.094 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.178 ±(99.9%) 1.986 ms/op [Average]
  (min, avg, max) = (3.094, 3.178, 3.301), stdev = 0.109
  CI (99.9%): [1.192, 5.164] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.114 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.003 ms/op
Iteration   2: 3.065 ±(99.9%) 0.004 ms/op
Iteration   3: 2.984 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.026 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (2.984, 3.026, 3.065), stdev = 0.041
  CI (99.9%): [2.280, 3.772] (assumes normal distribution)


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
# Warmup Iteration   1: 7.000 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.004 ms/op
Iteration   1: 3.132 ±(99.9%) 0.002 ms/op
Iteration   2: 3.238 ±(99.9%) 0.003 ms/op
Iteration   3: 3.105 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.159 ±(99.9%) 1.283 ms/op [Average]
  (min, avg, max) = (3.105, 3.159, 3.238), stdev = 0.070
  CI (99.9%): [1.876, 4.441] (assumes normal distribution)


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
# Warmup Iteration   1: 8.940 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.009 ms/op
Iteration   1: 3.713 ±(99.9%) 0.006 ms/op
Iteration   2: 3.694 ±(99.9%) 0.003 ms/op
Iteration   3: 3.698 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.701 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (3.694, 3.701, 3.713), stdev = 0.010
  CI (99.9%): [3.520, 3.883] (assumes normal distribution)


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
# Warmup Iteration   1: 8.124 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.010 ms/op
Iteration   1: 3.297 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  16.908 ms/op
                 createUser·p0.9999: 26.748 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 3.147 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  19.309 ms/op
                 createUser·p0.9999: 28.017 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  14.641 ms/op
                 createUser·p0.9999: 17.625 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300059
  mean =      3.199 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14174 
    [ 2.500,  5.000) = 280107 
    [ 5.000,  7.500) = 4758 
    [ 7.500, 10.000) = 474 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     16.481 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 7.035 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 3.047 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 19.448 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.126 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 21.651 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.546 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  8.360 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310967
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13896 
    [ 2.500,  5.000) = 292414 
    [ 5.000,  7.500) = 4012 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     11.687 ms/op
     p(99.9900) =     23.551 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 7.401 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.010 ms/op
Iteration   1: 3.151 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  14.746 ms/op
                 getUser·p0.9999: 22.535 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.494 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.795 ms/op
                 getUser·p0.9999: 24.478 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 22.987 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 308424
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4532 
    [ 2.500,  5.000) = 299368 
    [ 5.000,  7.500) = 3834 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     23.893 ms/op
     p(99.9990) =     25.253 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 9.091 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.011 ms/op
Iteration   1: 3.738 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 22.853 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 3.618 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.510 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   6.309 ms/op
                 listUser·p0.999:  13.451 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   3: 3.612 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.731 ms/op
                 listUser·p0.95:   3.928 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  11.682 ms/op
                 listUser·p0.9999: 15.542 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 262453
  mean =      3.655 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 256621 
    [ 5.000,  7.500) = 4227 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     23.130 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.047 ± 4.864  ops/ms
ClientPb.existUser                       thrpt       3  10.341 ± 5.077  ops/ms
ClientPb.getUser                         thrpt       3  10.111 ± 4.321  ops/ms
ClientPb.listUser                        thrpt       3   8.399 ± 1.701  ops/ms
ClientPb.createUser                       avgt       3   3.178 ± 1.986   ms/op
ClientPb.existUser                        avgt       3   3.026 ± 0.746   ms/op
ClientPb.getUser                          avgt       3   3.159 ± 1.283   ms/op
ClientPb.listUser                         avgt       3   3.701 ± 0.181   ms/op
ClientPb.createUser                     sample  300059   3.199 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.916           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.685           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.481           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.099           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.032           ms/op
ClientPb.existUser                      sample  310967   3.085 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.096           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.687           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.551           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.576           ms/op
ClientPb.getUser                        sample  308424   3.109 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.069           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.448           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.680           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.893           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.690           ms/op
ClientPb.listUser                       sample  262453   3.655 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.339           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.564           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.451           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.168           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.298           ms/op
