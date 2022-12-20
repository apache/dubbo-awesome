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
# Warmup Iteration   1: 2.367 ops/ms
# Warmup Iteration   2: 6.779 ops/ms
# Warmup Iteration   3: 9.416 ops/ms
Iteration   1: 9.904 ops/ms
Iteration   2: 9.879 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.012 ±(99.9%) 3.801 ops/ms [Average]
  (min, avg, max) = (9.879, 10.012, 10.252), stdev = 0.208
  CI (99.9%): [6.210, 13.813] (assumes normal distribution)


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
# Warmup Iteration   1: 3.554 ops/ms
# Warmup Iteration   2: 9.514 ops/ms
# Warmup Iteration   3: 10.482 ops/ms
Iteration   1: 10.336 ops/ms
Iteration   2: 10.174 ops/ms
Iteration   3: 10.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.308 ±(99.9%) 2.227 ops/ms [Average]
  (min, avg, max) = (10.174, 10.308, 10.413), stdev = 0.122
  CI (99.9%): [8.081, 12.535] (assumes normal distribution)


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
# Warmup Iteration   1: 3.619 ops/ms
# Warmup Iteration   2: 9.285 ops/ms
# Warmup Iteration   3: 9.602 ops/ms
Iteration   1: 10.340 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.333 ±(99.9%) 4.591 ops/ms [Average]
  (min, avg, max) = (10.078, 10.333, 10.581), stdev = 0.252
  CI (99.9%): [5.742, 14.924] (assumes normal distribution)


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
# Warmup Iteration   1: 3.470 ops/ms
# Warmup Iteration   2: 7.814 ops/ms
# Warmup Iteration   3: 8.463 ops/ms
Iteration   1: 8.522 ops/ms
Iteration   2: 8.410 ops/ms
Iteration   3: 8.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.420 ±(99.9%) 1.777 ops/ms [Average]
  (min, avg, max) = (8.328, 8.420, 8.522), stdev = 0.097
  CI (99.9%): [6.643, 10.197] (assumes normal distribution)


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
# Warmup Iteration   1: 9.164 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.003 ms/op
Iteration   1: 3.077 ±(99.9%) 0.006 ms/op
Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
Iteration   3: 3.068 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.086 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.068, 3.086, 3.114), stdev = 0.024
  CI (99.9%): [2.648, 3.525] (assumes normal distribution)


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
# Warmup Iteration   1: 7.491 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.004 ms/op
Iteration   1: 3.070 ±(99.9%) 0.008 ms/op
Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.042 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (2.971, 3.042, 3.085), stdev = 0.062
  CI (99.9%): [1.909, 4.175] (assumes normal distribution)


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
# Warmup Iteration   1: 7.882 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.004 ms/op
Iteration   1: 3.330 ±(99.9%) 0.006 ms/op
Iteration   2: 3.129 ±(99.9%) 0.003 ms/op
Iteration   3: 3.116 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 2.183 ms/op [Average]
  (min, avg, max) = (3.116, 3.192, 3.330), stdev = 0.120
  CI (99.9%): [1.009, 5.374] (assumes normal distribution)


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
# Warmup Iteration   1: 9.121 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.003 ms/op
Iteration   1: 3.684 ±(99.9%) 0.008 ms/op
Iteration   2: 3.721 ±(99.9%) 0.008 ms/op
Iteration   3: 3.616 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.674 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (3.616, 3.674, 3.721), stdev = 0.053
  CI (99.9%): [2.710, 4.638] (assumes normal distribution)


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
# Warmup Iteration   1: 8.354 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.008 ms/op
Iteration   1: 3.175 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  15.258 ms/op
                 createUser·p0.9999: 20.972 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.475 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  19.778 ms/op
                 createUser·p0.9999: 22.070 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  15.511 ms/op
                 createUser·p0.9999: 21.542 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293957
  mean =      3.266 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16410 
    [ 2.500,  5.000) = 269777 
    [ 5.000,  7.500) = 6822 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 164 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     16.486 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.514 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 7.469 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.120 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  9.682 ms/op
                 existUser·p0.9999: 24.600 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.318 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.782 ms/op
                 existUser·p0.9999: 22.103 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 19.946 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311429
  mean =      3.082 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15230 
    [ 2.500,  5.000) = 290658 
    [ 5.000,  7.500) = 4948 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =      9.496 ms/op
     p(99.9900) =     23.162 ms/op
     p(99.9990) =     25.486 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 7.560 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
Iteration   1: 3.248 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   2: 3.199 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.719 ms/op
                 getUser·p0.9999: 31.818 ms/op
                 getUser·p1.00:   33.161 ms/op

Iteration   3: 3.388 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  14.650 ms/op
                 getUser·p0.9999: 21.791 ms/op
                 getUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292866
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17871 
    [ 2.500,  5.000) = 265053 
    [ 5.000,  7.500) = 9119 
    [ 7.500, 10.000) = 458 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     12.367 ms/op
     p(99.9900) =     29.449 ms/op
     p(99.9990) =     33.161 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 9.725 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.013 ms/op
Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.972 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.333 ms/op
                 listUser·p0.999:  17.719 ms/op
                 listUser·p0.9999: 21.370 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 3.796 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.903 ms/op
                 listUser·p0.9999: 18.238 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 3.643 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   5.826 ms/op
                 listUser·p0.999:  13.058 ms/op
                 listUser·p0.9999: 14.795 ms/op
                 listUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253956
  mean =      3.774 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 246687 
    [ 5.000,  7.500) = 5354 
    [ 7.500, 10.000) = 1151 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 342 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.972 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     21.821 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.012 ± 3.801  ops/ms
ClientPb.existUser                       thrpt       3  10.308 ± 2.227  ops/ms
ClientPb.getUser                         thrpt       3  10.333 ± 4.591  ops/ms
ClientPb.listUser                        thrpt       3   8.420 ± 1.777  ops/ms
ClientPb.createUser                       avgt       3   3.086 ± 0.438   ms/op
ClientPb.existUser                        avgt       3   3.042 ± 1.133   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 2.183   ms/op
ClientPb.listUser                         avgt       3   3.674 ± 0.964   ms/op
ClientPb.createUser                     sample  293957   3.266 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.475           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.486           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.561           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.970           ms/op
ClientPb.existUser                      sample  311429   3.082 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.998           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.496           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.162           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.657           ms/op
ClientPb.getUser                        sample  292866   3.276 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.219           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.449           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.161           ms/op
ClientPb.listUser                       sample  253956   3.774 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.972           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.956           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.922           ms/op
