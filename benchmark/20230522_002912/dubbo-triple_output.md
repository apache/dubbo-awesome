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
# Warmup Iteration   1: 2.520 ops/ms
# Warmup Iteration   2: 6.301 ops/ms
# Warmup Iteration   3: 9.409 ops/ms
Iteration   1: 9.545 ops/ms
Iteration   2: 10.175 ops/ms
Iteration   3: 10.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.959 ±(99.9%) 6.546 ops/ms [Average]
  (min, avg, max) = (9.545, 9.959, 10.175), stdev = 0.359
  CI (99.9%): [3.413, 16.505] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.511 ops/ms
# Warmup Iteration   2: 9.463 ops/ms
# Warmup Iteration   3: 10.157 ops/ms
Iteration   1: 10.369 ops/ms
Iteration   2: 10.361 ops/ms
Iteration   3: 10.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.371 ±(99.9%) 0.202 ops/ms [Average]
  (min, avg, max) = (10.361, 10.371, 10.383), stdev = 0.011
  CI (99.9%): [10.169, 10.573] (assumes normal distribution)


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
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 9.142 ops/ms
# Warmup Iteration   3: 10.001 ops/ms
Iteration   1: 10.021 ops/ms
Iteration   2: 10.206 ops/ms
Iteration   3: 9.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.854 ±(99.9%) 8.389 ops/ms [Average]
  (min, avg, max) = (9.334, 9.854, 10.206), stdev = 0.460
  CI (99.9%): [1.465, 18.242] (assumes normal distribution)


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
# Warmup Iteration   1: 3.020 ops/ms
# Warmup Iteration   2: 7.572 ops/ms
# Warmup Iteration   3: 8.459 ops/ms
Iteration   1: 8.573 ops/ms
Iteration   2: 8.268 ops/ms
Iteration   3: 8.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.441 ±(99.9%) 2.847 ops/ms [Average]
  (min, avg, max) = (8.268, 8.441, 8.573), stdev = 0.156
  CI (99.9%): [5.594, 11.288] (assumes normal distribution)


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
# Warmup Iteration   1: 9.032 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.820 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.006 ms/op
Iteration   1: 3.211 ±(99.9%) 0.008 ms/op
Iteration   2: 3.245 ±(99.9%) 0.006 ms/op
Iteration   3: 3.130 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.195 ±(99.9%) 1.070 ms/op [Average]
  (min, avg, max) = (3.130, 3.195, 3.245), stdev = 0.059
  CI (99.9%): [2.125, 4.265] (assumes normal distribution)


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
# Warmup Iteration   1: 7.821 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.005 ms/op
Iteration   1: 3.145 ±(99.9%) 0.004 ms/op
Iteration   2: 3.044 ±(99.9%) 0.004 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.100 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (3.044, 3.100, 3.145), stdev = 0.051
  CI (99.9%): [2.161, 4.038] (assumes normal distribution)


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
# Warmup Iteration   1: 8.736 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.005 ms/op
Iteration   1: 3.249 ±(99.9%) 0.009 ms/op
Iteration   2: 3.220 ±(99.9%) 0.006 ms/op
Iteration   3: 3.127 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.199 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (3.127, 3.199, 3.249), stdev = 0.063
  CI (99.9%): [2.042, 4.356] (assumes normal distribution)


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
# Warmup Iteration   1: 10.157 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.006 ms/op
Iteration   1: 3.787 ±(99.9%) 0.006 ms/op
Iteration   2: 3.753 ±(99.9%) 0.010 ms/op
Iteration   3: 3.773 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.771 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.753, 3.771, 3.787), stdev = 0.017
  CI (99.9%): [3.456, 4.086] (assumes normal distribution)


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
# Warmup Iteration   1: 7.749 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
Iteration   1: 3.142 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  8.802 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  12.845 ms/op
                 createUser·p0.9999: 19.923 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  8.485 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301880
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24153 
    [ 2.500,  5.000) = 273475 
    [ 5.000,  7.500) = 3530 
    [ 7.500, 10.000) = 305 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     12.568 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 7.037 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  15.070 ms/op
                 existUser·p0.9999: 20.642 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  14.811 ms/op
                 existUser·p0.9999: 22.298 ms/op
                 existUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313075
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16506 
    [ 2.500,  5.000) = 291527 
    [ 5.000,  7.500) = 4275 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     14.744 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 7.601 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.011 ms/op
Iteration   1: 3.334 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.715 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  18.430 ms/op
                 getUser·p0.9999: 28.180 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   2: 3.354 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  21.521 ms/op
                 getUser·p0.9999: 24.603 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  10.360 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290577
  mean =      3.302 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16142 
    [ 2.500,  5.000) = 266219 
    [ 5.000,  7.500) = 7111 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     26.573 ms/op
     p(99.9990) =     28.492 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 9.242 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.011 ms/op
Iteration   1: 3.883 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   2: 3.826 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  16.749 ms/op
                 listUser·p0.9999: 20.271 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 14.233 ms/op
                 listUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249117
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 239799 
    [ 5.000,  7.500) = 7648 
    [ 7.500, 10.000) = 941 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.959 ± 6.546  ops/ms
ClientPb.existUser                       thrpt       3  10.371 ± 0.202  ops/ms
ClientPb.getUser                         thrpt       3   9.854 ± 8.389  ops/ms
ClientPb.listUser                        thrpt       3   8.441 ± 2.847  ops/ms
ClientPb.createUser                       avgt       3   3.195 ± 1.070   ms/op
ClientPb.existUser                        avgt       3   3.100 ± 0.938   ms/op
ClientPb.getUser                          avgt       3   3.199 ± 1.157   ms/op
ClientPb.listUser                         avgt       3   3.771 ± 0.315   ms/op
ClientPb.createUser                     sample  301880   3.181 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.360           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.568           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.923           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.480           ms/op
ClientPb.existUser                      sample  313075   3.065 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.174           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.744           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.429           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.559           ms/op
ClientPb.getUser                        sample  290577   3.302 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.860           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.573           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  249117   3.857 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.313           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.283           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.133           ms/op
