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
# Warmup Iteration   1: 2.551 ops/ms
# Warmup Iteration   2: 6.277 ops/ms
# Warmup Iteration   3: 9.647 ops/ms
Iteration   1: 10.211 ops/ms
Iteration   2: 10.106 ops/ms
Iteration   3: 9.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.935 ±(99.9%) 7.139 ops/ms [Average]
  (min, avg, max) = (9.487, 9.935, 10.211), stdev = 0.391
  CI (99.9%): [2.796, 17.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ops/ms
# Warmup Iteration   2: 9.194 ops/ms
# Warmup Iteration   3: 10.283 ops/ms
Iteration   1: 9.804 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.258 ±(99.9%) 7.217 ops/ms [Average]
  (min, avg, max) = (9.804, 10.258, 10.528), stdev = 0.396
  CI (99.9%): [3.042, 17.475] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ops/ms
# Warmup Iteration   2: 9.218 ops/ms
# Warmup Iteration   3: 9.671 ops/ms
Iteration   1: 10.070 ops/ms
Iteration   2: 9.734 ops/ms
Iteration   3: 9.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.893 ±(99.9%) 3.074 ops/ms [Average]
  (min, avg, max) = (9.734, 9.893, 10.070), stdev = 0.168
  CI (99.9%): [6.819, 12.967] (assumes normal distribution)


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
# Warmup Iteration   1: 3.073 ops/ms
# Warmup Iteration   2: 7.521 ops/ms
# Warmup Iteration   3: 8.478 ops/ms
Iteration   1: 8.513 ops/ms
Iteration   2: 8.467 ops/ms
Iteration   3: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.456 ±(99.9%) 1.142 ops/ms [Average]
  (min, avg, max) = (8.389, 8.456, 8.513), stdev = 0.063
  CI (99.9%): [7.314, 9.599] (assumes normal distribution)


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
# Warmup Iteration   1: 9.176 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.003 ms/op
Iteration   1: 3.159 ±(99.9%) 0.004 ms/op
Iteration   2: 3.273 ±(99.9%) 0.006 ms/op
Iteration   3: 3.113 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.182 ±(99.9%) 1.503 ms/op [Average]
  (min, avg, max) = (3.113, 3.182, 3.273), stdev = 0.082
  CI (99.9%): [1.678, 4.685] (assumes normal distribution)


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
# Warmup Iteration   1: 7.287 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.180 ±(99.9%) 0.004 ms/op
Iteration   2: 3.135 ±(99.9%) 0.004 ms/op
Iteration   3: 2.947 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.087 ±(99.9%) 2.262 ms/op [Average]
  (min, avg, max) = (2.947, 3.087, 3.180), stdev = 0.124
  CI (99.9%): [0.825, 5.350] (assumes normal distribution)


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
# Warmup Iteration   1: 7.728 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.003 ms/op
Iteration   1: 3.202 ±(99.9%) 0.002 ms/op
Iteration   2: 3.159 ±(99.9%) 0.009 ms/op
Iteration   3: 3.221 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.194 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.159, 3.194, 3.221), stdev = 0.031
  CI (99.9%): [2.623, 3.765] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.833 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.005 ms/op
Iteration   1: 3.756 ±(99.9%) 0.007 ms/op
Iteration   2: 3.662 ±(99.9%) 0.011 ms/op
Iteration   3: 3.833 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.750 ±(99.9%) 1.561 ms/op [Average]
  (min, avg, max) = (3.662, 3.750, 3.833), stdev = 0.086
  CI (99.9%): [2.189, 5.311] (assumes normal distribution)


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
# Warmup Iteration   1: 8.627 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.011 ms/op
Iteration   1: 3.224 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  16.643 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  19.608 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  15.517 ms/op
                 createUser·p0.9999: 25.550 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304812
  mean =      3.147 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26026 
    [ 2.500,  5.000) = 275273 
    [ 5.000,  7.500) = 2776 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     24.479 ms/op
     p(99.9990) =     25.754 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 6.771 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
Iteration   1: 3.115 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  16.089 ms/op
                 existUser·p0.9999: 24.804 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.557 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  13.177 ms/op
                 existUser·p0.9999: 23.662 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 20.349 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314957
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15149 
    [ 2.500,  5.000) = 295328 
    [ 5.000,  7.500) = 3631 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     23.937 ms/op
     p(99.9990) =     25.249 ms/op
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
# Warmup Iteration   1: 7.018 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.009 ms/op
Iteration   1: 3.252 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  11.407 ms/op
                 getUser·p0.9999: 19.338 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.831 ms/op
                 getUser·p0.999:  12.953 ms/op
                 getUser·p0.9999: 22.476 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.273 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  14.801 ms/op
                 getUser·p0.9999: 23.895 ms/op
                 getUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296693
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15742 
    [ 2.500,  5.000) = 273451 
    [ 5.000,  7.500) = 6563 
    [ 7.500, 10.000) = 467 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     14.641 ms/op
     p(99.9900) =     22.588 ms/op
     p(99.9990) =     24.186 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 8.750 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.010 ms/op
Iteration   1: 3.725 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.488 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 3.776 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  13.730 ms/op
                 listUser·p0.9999: 16.007 ms/op
                 listUser·p1.00:   16.433 ms/op

Iteration   3: 3.812 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.424 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254251
  mean =      3.771 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 244874 
    [ 5.000,  7.500) = 7048 
    [ 7.500, 10.000) = 1425 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 397 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     21.777 ms/op
     p(99.9990) =     24.755 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.935 ± 7.139  ops/ms
ClientPb.existUser                       thrpt       3  10.258 ± 7.217  ops/ms
ClientPb.getUser                         thrpt       3   9.893 ± 3.074  ops/ms
ClientPb.listUser                        thrpt       3   8.456 ± 1.142  ops/ms
ClientPb.createUser                       avgt       3   3.182 ± 1.503   ms/op
ClientPb.existUser                        avgt       3   3.087 ± 2.262   ms/op
ClientPb.getUser                          avgt       3   3.194 ± 0.571   ms/op
ClientPb.listUser                         avgt       3   3.750 ± 1.561   ms/op
ClientPb.createUser                     sample  304812   3.147 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.987           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.744           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.479           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.968           ms/op
ClientPb.existUser                      sample  314957   3.046 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.855           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.582           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.937           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.657           ms/op
ClientPb.getUser                        sample  296693   3.235 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.083           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.641           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.588           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.445           ms/op
ClientPb.listUser                       sample  254251   3.771 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.041           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.777           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.838           ms/op
