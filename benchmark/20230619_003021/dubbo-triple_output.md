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
# Warmup Iteration   1: 1.133 ops/ms
# Warmup Iteration   2: 2.532 ops/ms
# Warmup Iteration   3: 6.391 ops/ms
Iteration   1: 7.147 ops/ms
Iteration   2: 7.214 ops/ms
Iteration   3: 7.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.139 ±(99.9%) 1.469 ops/ms [Average]
  (min, avg, max) = (7.054, 7.139, 7.214), stdev = 0.080
  CI (99.9%): [5.670, 8.607] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.919 ops/ms
# Warmup Iteration   2: 5.915 ops/ms
# Warmup Iteration   3: 7.285 ops/ms
Iteration   1: 7.546 ops/ms
Iteration   2: 7.664 ops/ms
Iteration   3: 7.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.715 ±(99.9%) 3.634 ops/ms [Average]
  (min, avg, max) = (7.546, 7.715, 7.935), stdev = 0.199
  CI (99.9%): [4.081, 11.349] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 5.685 ops/ms
# Warmup Iteration   3: 7.172 ops/ms
Iteration   1: 7.372 ops/ms
Iteration   2: 7.363 ops/ms
Iteration   3: 7.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.432 ±(99.9%) 2.028 ops/ms [Average]
  (min, avg, max) = (7.363, 7.432, 7.560), stdev = 0.111
  CI (99.9%): [5.404, 9.460] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.792 ops/ms
# Warmup Iteration   2: 5.143 ops/ms
# Warmup Iteration   3: 6.284 ops/ms
Iteration   1: 5.972 ops/ms
Iteration   2: 5.751 ops/ms
Iteration   3: 6.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.089 ±(99.9%) 7.464 ops/ms [Average]
  (min, avg, max) = (5.751, 6.089, 6.544), stdev = 0.409
  CI (99.9%): [≈ 0, 13.553] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.831 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.591 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.909 ±(99.9%) 0.009 ms/op
Iteration   1: 4.288 ±(99.9%) 0.008 ms/op
Iteration   2: 4.262 ±(99.9%) 0.005 ms/op
Iteration   3: 4.319 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.290 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (4.262, 4.290, 4.319), stdev = 0.028
  CI (99.9%): [3.772, 4.808] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.991 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.010 ms/op
Iteration   1: 4.158 ±(99.9%) 0.008 ms/op
Iteration   2: 4.089 ±(99.9%) 0.004 ms/op
Iteration   3: 4.111 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.119 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (4.089, 4.119, 4.158), stdev = 0.036
  CI (99.9%): [3.469, 4.769] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.838 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.534 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.005 ms/op
Iteration   1: 4.610 ±(99.9%) 0.008 ms/op
Iteration   2: 4.356 ±(99.9%) 0.007 ms/op
Iteration   3: 4.380 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.449 ±(99.9%) 2.554 ms/op [Average]
  (min, avg, max) = (4.356, 4.449, 4.610), stdev = 0.140
  CI (99.9%): [1.894, 7.003] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.715 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.639 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.345 ±(99.9%) 0.011 ms/op
Iteration   1: 4.914 ±(99.9%) 0.011 ms/op
Iteration   2: 3.976 ±(99.9%) 0.004 ms/op
Iteration   3: 3.891 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.261 ±(99.9%) 10.358 ms/op [Average]
  (min, avg, max) = (3.891, 4.261, 4.914), stdev = 0.568
  CI (99.9%): [≈ 0, 14.619] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.291 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.008 ms/op
Iteration   1: 3.158 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  18.252 ms/op
                 createUser·p0.9999: 20.247 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 3.249 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  13.264 ms/op
                 createUser·p0.9999: 21.206 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   3: 3.265 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  11.435 ms/op
                 createUser·p0.9999: 19.497 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297756
  mean =      3.223 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25431 
    [ 2.500,  5.000) = 265084 
    [ 5.000,  7.500) = 6547 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 188 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     20.422 ms/op
     p(99.9990) =     21.465 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.661 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
Iteration   1: 3.103 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 21.584 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  9.802 ms/op
                 existUser·p0.9999: 22.118 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.507 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.164 ms/op
                 existUser·p0.999:  13.156 ms/op
                 existUser·p0.9999: 28.541 ms/op
                 existUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311063
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24701 
    [ 2.500,  5.000) = 282066 
    [ 5.000,  7.500) = 3624 
    [ 7.500, 10.000) = 268 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     12.220 ms/op
     p(99.9900) =     27.121 ms/op
     p(99.9990) =     29.258 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.469 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.009 ms/op
Iteration   1: 3.087 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.314 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  18.940 ms/op
                 getUser·p0.9999: 21.375 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.127 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 22.446 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.510 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 18.404 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 309111
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11083 
    [ 2.500,  5.000) = 293363 
    [ 5.000,  7.500) = 3871 
    [ 7.500, 10.000) = 386 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 182 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.283 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.353 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.012 ms/op
Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.426 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 23.974 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.740 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.935 ms/op
                 listUser·p0.9999: 16.146 ms/op
                 listUser·p1.00:   16.187 ms/op

Iteration   3: 3.767 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.013 ms/op
                 listUser·p0.9999: 20.857 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254092
  mean =      3.775 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 246055 
    [ 5.000,  7.500) = 6150 
    [ 7.500, 10.000) = 1195 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     23.285 ms/op
     p(99.9990) =     24.192 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.139 ±  1.469  ops/ms
ClientPb.existUser                       thrpt       3   7.715 ±  3.634  ops/ms
ClientPb.getUser                         thrpt       3   7.432 ±  2.028  ops/ms
ClientPb.listUser                        thrpt       3   6.089 ±  7.464  ops/ms
ClientPb.createUser                       avgt       3   4.290 ±  0.518   ms/op
ClientPb.existUser                        avgt       3   4.119 ±  0.650   ms/op
ClientPb.getUser                          avgt       3   4.449 ±  2.554   ms/op
ClientPb.listUser                         avgt       3   4.261 ± 10.358   ms/op
ClientPb.createUser                     sample  297756   3.223 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.102            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.456            ms/op
ClientPb.createUser:createUser·p0.999   sample          15.565            ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.422            ms/op
ClientPb.createUser:createUser·p1.00    sample          21.856            ms/op
ClientPb.existUser                      sample  311063   3.084 ±  0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.325            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.318            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.625            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.210            ms/op
ClientPb.existUser:existUser·p0.999     sample          12.220            ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.121            ms/op
ClientPb.existUser:existUser·p1.00      sample          29.753            ms/op
ClientPb.getUser                        sample  309111   3.101 ±  0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.002            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.379            ms/op
ClientPb.getUser:getUser·p0.95          sample           3.580            ms/op
ClientPb.getUser:getUser·p0.99          sample           5.415            ms/op
ClientPb.getUser:getUser·p0.999         sample          15.352            ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.086            ms/op
ClientPb.getUser:getUser·p1.00          sample          23.822            ms/op
ClientPb.listUser                       sample  254092   3.775 ±  0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.702            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094            ms/op
ClientPb.listUser:listUser·p0.999       sample          14.451            ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.285            ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379            ms/op
