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
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 5.784 ops/ms
# Warmup Iteration   3: 9.261 ops/ms
Iteration   1: 10.064 ops/ms
Iteration   2: 10.222 ops/ms
Iteration   3: 9.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.075 ±(99.9%) 2.576 ops/ms [Average]
  (min, avg, max) = (9.940, 10.075, 10.222), stdev = 0.141
  CI (99.9%): [7.499, 12.651] (assumes normal distribution)


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
# Warmup Iteration   1: 3.606 ops/ms
# Warmup Iteration   2: 9.591 ops/ms
# Warmup Iteration   3: 9.735 ops/ms
Iteration   1: 10.668 ops/ms
Iteration   2: 10.199 ops/ms
Iteration   3: 10.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.374 ±(99.9%) 4.674 ops/ms [Average]
  (min, avg, max) = (10.199, 10.374, 10.668), stdev = 0.256
  CI (99.9%): [5.700, 15.048] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.607 ops/ms
# Warmup Iteration   2: 9.287 ops/ms
# Warmup Iteration   3: 9.761 ops/ms
Iteration   1: 10.168 ops/ms
Iteration   2: 10.242 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.299 ±(99.9%) 3.045 ops/ms [Average]
  (min, avg, max) = (10.168, 10.299, 10.487), stdev = 0.167
  CI (99.9%): [7.254, 13.344] (assumes normal distribution)


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
# Warmup Iteration   1: 3.147 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.253 ops/ms
Iteration   1: 8.797 ops/ms
Iteration   2: 8.689 ops/ms
Iteration   3: 8.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.761 ±(99.9%) 1.151 ops/ms [Average]
  (min, avg, max) = (8.689, 8.761, 8.798), stdev = 0.063
  CI (99.9%): [7.611, 9.912] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.651 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.003 ms/op
Iteration   1: 3.249 ±(99.9%) 0.004 ms/op
Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
Iteration   3: 3.105 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.162 ±(99.9%) 1.392 ms/op [Average]
  (min, avg, max) = (3.105, 3.162, 3.249), stdev = 0.076
  CI (99.9%): [1.770, 4.555] (assumes normal distribution)


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
# Warmup Iteration   1: 6.773 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.129 ±(99.9%) 0.003 ms/op
Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
Iteration   3: 3.109 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.103 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (3.072, 3.103, 3.129), stdev = 0.029
  CI (99.9%): [2.578, 3.629] (assumes normal distribution)


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
# Warmup Iteration   1: 7.995 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.005 ms/op
Iteration   2: 3.367 ±(99.9%) 0.006 ms/op
Iteration   3: 3.072 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 2.874 ms/op [Average]
  (min, avg, max) = (3.072, 3.188, 3.367), stdev = 0.158
  CI (99.9%): [0.314, 6.062] (assumes normal distribution)


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
# Warmup Iteration   1: 9.366 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.005 ms/op
Iteration   1: 3.738 ±(99.9%) 0.006 ms/op
Iteration   2: 3.682 ±(99.9%) 0.006 ms/op
Iteration   3: 3.601 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.674 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (3.601, 3.674, 3.738), stdev = 0.069
  CI (99.9%): [2.413, 4.934] (assumes normal distribution)


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
# Warmup Iteration   1: 8.605 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.009 ms/op
Iteration   1: 3.257 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  18.928 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  13.311 ms/op
                 createUser·p0.9999: 23.167 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.143 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.432 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  15.224 ms/op
                 createUser·p0.9999: 20.108 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302254
  mean =      3.174 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21975 
    [ 2.500,  5.000) = 274103 
    [ 5.000,  7.500) = 5102 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     15.704 ms/op
     p(99.9900) =     22.799 ms/op
     p(99.9990) =     23.461 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 7.087 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.009 ms/op
Iteration   1: 3.073 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  11.862 ms/op
                 existUser·p0.9999: 19.779 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 3.099 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  13.670 ms/op
                 existUser·p0.9999: 22.042 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.079 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.231 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  17.400 ms/op
                 existUser·p0.9999: 118.489 ms/op
                 existUser·p1.00:   119.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311239
  mean =      3.084 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 310830 
    [ 12.500,  25.000) = 370 
    [ 25.000,  37.500) = 4 
    [ 37.500,  50.000) = 3 
    [ 50.000,  62.500) = 2 
    [ 62.500,  75.000) = 3 
    [ 75.000,  87.500) = 4 
    [ 87.500, 100.000) = 3 
    [100.000, 112.500) = 3 
    [112.500, 125.000) = 17 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.231 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.248 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     16.773 ms/op
     p(99.9900) =     61.172 ms/op
     p(99.9990) =    118.999 ms/op
     p(99.9999) =    119.669 ms/op
    p(100.0000) =    119.669 ms/op


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
# Warmup Iteration   1: 7.444 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.009 ms/op
Iteration   1: 3.215 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  18.317 ms/op
                 getUser·p0.9999: 21.137 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   2: 3.133 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  19.656 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 3.377 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  14.176 ms/op
                 getUser·p0.9999: 21.972 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296234
  mean =      3.239 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21032 
    [ 2.500,  5.000) = 267681 
    [ 5.000,  7.500) = 6565 
    [ 7.500, 10.000) = 442 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 9.010 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.011 ms/op
Iteration   1: 3.768 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.984 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 3.687 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  12.124 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   3: 3.671 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  14.023 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258632
  mean =      3.708 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 251250 
    [ 5.000,  7.500) = 5458 
    [ 7.500, 10.000) = 1272 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     19.239 ms/op
     p(99.9990) =     19.865 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt    Score   Error   Units
ClientPb.createUser                      thrpt       3   10.075 ± 2.576  ops/ms
ClientPb.existUser                       thrpt       3   10.374 ± 4.674  ops/ms
ClientPb.getUser                         thrpt       3   10.299 ± 3.045  ops/ms
ClientPb.listUser                        thrpt       3    8.761 ± 1.151  ops/ms
ClientPb.createUser                       avgt       3    3.162 ± 1.392   ms/op
ClientPb.existUser                        avgt       3    3.103 ± 0.525   ms/op
ClientPb.getUser                          avgt       3    3.188 ± 2.874   ms/op
ClientPb.listUser                         avgt       3    3.674 ± 1.261   ms/op
ClientPb.createUser                     sample  302254    3.174 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample            1.174           ms/op
ClientPb.createUser:createUser·p0.50    sample            3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample            3.478           ms/op
ClientPb.createUser:createUser·p0.95    sample            3.879           ms/op
ClientPb.createUser:createUser·p0.99    sample            5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample           15.704           ms/op
ClientPb.createUser:createUser·p0.9999  sample           22.799           ms/op
ClientPb.createUser:createUser·p1.00    sample           23.888           ms/op
ClientPb.existUser                      sample  311239    3.084 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample            0.231           ms/op
ClientPb.existUser:existUser·p0.50      sample            3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample            3.248           ms/op
ClientPb.existUser:existUser·p0.95      sample            3.510           ms/op
ClientPb.existUser:existUser·p0.99      sample            5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample           16.773           ms/op
ClientPb.existUser:existUser·p0.9999    sample           61.172           ms/op
ClientPb.existUser:existUser·p1.00      sample          119.669           ms/op
ClientPb.getUser                        sample  296234    3.239 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample            0.551           ms/op
ClientPb.getUser:getUser·p0.50          sample            3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample            3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample            4.141           ms/op
ClientPb.getUser:getUser·p0.99          sample            5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample           16.269           ms/op
ClientPb.getUser:getUser·p0.9999        sample           25.166           ms/op
ClientPb.getUser:getUser·p1.00          sample           27.329           ms/op
ClientPb.listUser                       sample  258632    3.708 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample            1.321           ms/op
ClientPb.listUser:listUser·p0.50        sample            3.568           ms/op
ClientPb.listUser:listUser·p0.90        sample            4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample            4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample            6.898           ms/op
ClientPb.listUser:listUser·p0.999       sample           13.681           ms/op
ClientPb.listUser:listUser·p0.9999      sample           19.239           ms/op
ClientPb.listUser:listUser·p1.00        sample           20.447           ms/op
