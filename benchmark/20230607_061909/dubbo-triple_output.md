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
# Warmup Iteration   1: 2.498 ops/ms
# Warmup Iteration   2: 6.396 ops/ms
# Warmup Iteration   3: 9.333 ops/ms
Iteration   1: 9.833 ops/ms
Iteration   2: 9.912 ops/ms
Iteration   3: 9.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.854 ±(99.9%) 0.941 ops/ms [Average]
  (min, avg, max) = (9.816, 9.854, 9.912), stdev = 0.052
  CI (99.9%): [8.913, 10.794] (assumes normal distribution)


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
# Warmup Iteration   1: 3.471 ops/ms
# Warmup Iteration   2: 9.044 ops/ms
# Warmup Iteration   3: 10.556 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.401 ops/ms
Iteration   3: 10.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.349 ±(99.9%) 2.855 ops/ms [Average]
  (min, avg, max) = (10.173, 10.349, 10.473), stdev = 0.156
  CI (99.9%): [7.494, 13.204] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.416 ops/ms
# Warmup Iteration   2: 9.244 ops/ms
# Warmup Iteration   3: 9.557 ops/ms
Iteration   1: 10.107 ops/ms
Iteration   2: 9.889 ops/ms
Iteration   3: 10.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.041 ±(99.9%) 2.412 ops/ms [Average]
  (min, avg, max) = (9.889, 10.041, 10.127), stdev = 0.132
  CI (99.9%): [7.628, 12.453] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.192 ops/ms
# Warmup Iteration   2: 7.564 ops/ms
# Warmup Iteration   3: 8.191 ops/ms
Iteration   1: 8.253 ops/ms
Iteration   2: 8.367 ops/ms
Iteration   3: 8.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.405 ±(99.9%) 3.193 ops/ms [Average]
  (min, avg, max) = (8.253, 8.405, 8.596), stdev = 0.175
  CI (99.9%): [5.213, 11.598] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.733 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.004 ms/op
Iteration   1: 3.329 ±(99.9%) 0.007 ms/op
Iteration   2: 3.272 ±(99.9%) 0.004 ms/op
Iteration   3: 3.269 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.290 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.269, 3.290, 3.329), stdev = 0.034
  CI (99.9%): [2.668, 3.912] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.790 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.209 ±(99.9%) 0.003 ms/op
Iteration   2: 3.088 ±(99.9%) 0.005 ms/op
Iteration   3: 3.074 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.123 ±(99.9%) 1.351 ms/op [Average]
  (min, avg, max) = (3.074, 3.123, 3.209), stdev = 0.074
  CI (99.9%): [1.772, 4.475] (assumes normal distribution)


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
# Warmup Iteration   1: 7.273 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.002 ms/op
Iteration   1: 3.296 ±(99.9%) 0.003 ms/op
Iteration   2: 3.313 ±(99.9%) 0.005 ms/op
Iteration   3: 3.166 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.258 ±(99.9%) 1.466 ms/op [Average]
  (min, avg, max) = (3.166, 3.258, 3.313), stdev = 0.080
  CI (99.9%): [1.793, 4.724] (assumes normal distribution)


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
# Warmup Iteration   1: 8.549 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.006 ms/op
Iteration   1: 3.836 ±(99.9%) 0.005 ms/op
Iteration   2: 3.763 ±(99.9%) 0.009 ms/op
Iteration   3: 3.704 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.768 ±(99.9%) 1.206 ms/op [Average]
  (min, avg, max) = (3.704, 3.768, 3.836), stdev = 0.066
  CI (99.9%): [2.561, 4.974] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.189 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.010 ms/op
Iteration   1: 3.221 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  10.392 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  19.971 ms/op
                 createUser·p0.9999: 21.885 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 3.328 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  14.877 ms/op
                 createUser·p0.9999: 21.836 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296212
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19659 
    [ 2.500,  5.000) = 270257 
    [ 5.000,  7.500) = 5369 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     16.577 ms/op
     p(99.9900) =     21.574 ms/op
     p(99.9990) =     22.188 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 7.492 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  11.485 ms/op
                 existUser·p0.9999: 20.480 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.082 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.392 ms/op
                 existUser·p0.999:  11.243 ms/op
                 existUser·p0.9999: 23.253 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  11.518 ms/op
                 existUser·p0.9999: 26.280 ms/op
                 existUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307494
  mean =      3.120 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23175 
    [ 2.500,  5.000) = 280316 
    [ 5.000,  7.500) = 3300 
    [ 7.500, 10.000) = 273 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     25.477 ms/op
     p(99.9990) =     27.218 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 7.881 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
Iteration   1: 3.282 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  18.828 ms/op
                 getUser·p0.9999: 24.356 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.537 ms/op
                 getUser·p0.9999: 24.216 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  9.273 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302633
  mean =      3.171 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8318 
    [ 2.500,  5.000) = 288432 
    [ 5.000,  7.500) = 4989 
    [ 7.500, 10.000) = 467 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     17.936 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     25.064 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 8.705 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.012 ms/op
Iteration   1: 3.813 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 18.665 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 3.859 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 15.024 ms/op
                 listUser·p1.00:   15.172 ms/op

Iteration   3: 3.728 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 14.277 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252693
  mean =      3.799 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 104 
    [ 2.500,  3.750) = 157907 
    [ 3.750,  5.000) = 85992 
    [ 5.000,  6.250) = 3014 
    [ 6.250,  7.500) = 3359 
    [ 7.500,  8.750) = 1124 
    [ 8.750, 10.000) = 393 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 155 
    [12.500, 13.750) = 383 
    [13.750, 15.000) = 125 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     13.489 ms/op
     p(99.9900) =     18.079 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.854 ± 0.941  ops/ms
ClientPb.existUser                       thrpt       3  10.349 ± 2.855  ops/ms
ClientPb.getUser                         thrpt       3  10.041 ± 2.412  ops/ms
ClientPb.listUser                        thrpt       3   8.405 ± 3.193  ops/ms
ClientPb.createUser                       avgt       3   3.290 ± 0.622   ms/op
ClientPb.existUser                        avgt       3   3.123 ± 1.351   ms/op
ClientPb.getUser                          avgt       3   3.258 ± 1.466   ms/op
ClientPb.listUser                         avgt       3   3.768 ± 1.206   ms/op
ClientPb.createUser                     sample  296212   3.242 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.892           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.577           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.574           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.381           ms/op
ClientPb.existUser                      sample  307494   3.120 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.827           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.518           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.477           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.427           ms/op
ClientPb.getUser                        sample  302633   3.171 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.998           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.936           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.724           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.985           ms/op
ClientPb.listUser                       sample  252693   3.799 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.114           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.373           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.489           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.079           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.530           ms/op
