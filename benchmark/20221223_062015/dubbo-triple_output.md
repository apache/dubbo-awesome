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
# Warmup Iteration   1: 2.700 ops/ms
# Warmup Iteration   2: 6.839 ops/ms
# Warmup Iteration   3: 9.364 ops/ms
Iteration   1: 10.021 ops/ms
Iteration   2: 9.959 ops/ms
Iteration   3: 10.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.995 ±(99.9%) 0.587 ops/ms [Average]
  (min, avg, max) = (9.959, 9.995, 10.021), stdev = 0.032
  CI (99.9%): [9.408, 10.582] (assumes normal distribution)


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
# Warmup Iteration   1: 3.760 ops/ms
# Warmup Iteration   2: 9.574 ops/ms
# Warmup Iteration   3: 10.264 ops/ms
Iteration   1: 10.735 ops/ms
Iteration   2: 10.755 ops/ms
Iteration   3: 10.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.640 ±(99.9%) 3.309 ops/ms [Average]
  (min, avg, max) = (10.431, 10.640, 10.755), stdev = 0.181
  CI (99.9%): [7.331, 13.950] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ops/ms
# Warmup Iteration   2: 9.407 ops/ms
# Warmup Iteration   3: 9.964 ops/ms
Iteration   1: 10.388 ops/ms
Iteration   2: 10.212 ops/ms
Iteration   3: 10.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.401 ±(99.9%) 3.573 ops/ms [Average]
  (min, avg, max) = (10.212, 10.401, 10.603), stdev = 0.196
  CI (99.9%): [6.828, 13.974] (assumes normal distribution)


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
# Warmup Iteration   1: 3.461 ops/ms
# Warmup Iteration   2: 8.076 ops/ms
# Warmup Iteration   3: 8.597 ops/ms
Iteration   1: 8.109 ops/ms
Iteration   2: 8.585 ops/ms
Iteration   3: 8.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.398 ±(99.9%) 4.636 ops/ms [Average]
  (min, avg, max) = (8.109, 8.398, 8.585), stdev = 0.254
  CI (99.9%): [3.762, 13.034] (assumes normal distribution)


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
# Warmup Iteration   1: 7.638 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.005 ms/op
Iteration   1: 3.260 ±(99.9%) 0.007 ms/op
Iteration   2: 3.325 ±(99.9%) 0.004 ms/op
Iteration   3: 3.232 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.273 ±(99.9%) 0.868 ms/op [Average]
  (min, avg, max) = (3.232, 3.273, 3.325), stdev = 0.048
  CI (99.9%): [2.405, 4.140] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.832 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.004 ms/op
Iteration   1: 3.242 ±(99.9%) 0.005 ms/op
Iteration   2: 3.200 ±(99.9%) 0.006 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.145 ±(99.9%) 2.442 ms/op [Average]
  (min, avg, max) = (2.992, 3.145, 3.242), stdev = 0.134
  CI (99.9%): [0.703, 5.587] (assumes normal distribution)


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
# Warmup Iteration   1: 7.563 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.005 ms/op
Iteration   1: 3.131 ±(99.9%) 0.008 ms/op
Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
Iteration   3: 3.213 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.172 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.131, 3.172, 3.213), stdev = 0.041
  CI (99.9%): [2.428, 3.917] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.510 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.003 ms/op
Iteration   1: 3.777 ±(99.9%) 0.003 ms/op
Iteration   2: 3.701 ±(99.9%) 0.009 ms/op
Iteration   3: 3.647 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.708 ±(99.9%) 1.192 ms/op [Average]
  (min, avg, max) = (3.647, 3.708, 3.777), stdev = 0.065
  CI (99.9%): [2.517, 4.900] (assumes normal distribution)


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
# Warmup Iteration   1: 7.537 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.008 ms/op
Iteration   1: 3.171 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  19.169 ms/op
                 createUser·p0.9999: 23.557 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 21.325 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  14.947 ms/op
                 createUser·p0.9999: 20.117 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304911
  mean =      3.145 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20937 
    [ 2.500,  5.000) = 278213 
    [ 5.000,  7.500) = 4894 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     22.987 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 7.137 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.008 ms/op
Iteration   1: 3.085 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  10.306 ms/op
                 existUser·p0.9999: 26.235 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  8.871 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.412 ms/op
                 existUser·p0.9999: 27.117 ms/op
                 existUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312992
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28024 
    [ 2.500,  5.000) = 280249 
    [ 5.000,  7.500) = 4152 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     26.270 ms/op
     p(99.9990) =     27.709 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 7.229 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
Iteration   1: 3.084 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  17.547 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  19.137 ms/op
                 getUser·p0.9999: 23.370 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  13.477 ms/op
                 getUser·p0.9999: 19.530 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300975
  mean =      3.191 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18893 
    [ 2.500,  5.000) = 275843 
    [ 5.000,  7.500) = 5612 
    [ 7.500, 10.000) = 235 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     17.172 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 9.768 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.011 ms/op
Iteration   1: 3.639 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   3.744 ms/op
                 listUser·p0.95:   3.899 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  13.353 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 3.693 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.450 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 19.574 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 3.707 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.059 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260849
  mean =      3.679 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 255359 
    [ 5.000,  7.500) = 3772 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     20.455 ms/op
     p(99.9990) =     22.446 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.995 ± 0.587  ops/ms
ClientPb.existUser                       thrpt       3  10.640 ± 3.309  ops/ms
ClientPb.getUser                         thrpt       3  10.401 ± 3.573  ops/ms
ClientPb.listUser                        thrpt       3   8.398 ± 4.636  ops/ms
ClientPb.createUser                       avgt       3   3.273 ± 0.868   ms/op
ClientPb.existUser                        avgt       3   3.145 ± 2.442   ms/op
ClientPb.getUser                          avgt       3   3.172 ± 0.744   ms/op
ClientPb.listUser                         avgt       3   3.708 ± 1.192   ms/op
ClientPb.createUser                     sample  304911   3.145 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.188           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.987           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.953           ms/op
ClientPb.existUser                      sample  312992   3.063 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.933           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.207           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.270           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.984           ms/op
ClientPb.getUser                        sample  300975   3.191 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.172           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.872           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.756           ms/op
ClientPb.listUser                       sample  260849   3.679 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.120           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.586           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.455           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.675           ms/op
