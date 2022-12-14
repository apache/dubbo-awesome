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
# Warmup Iteration   1: 2.651 ops/ms
# Warmup Iteration   2: 6.144 ops/ms
# Warmup Iteration   3: 9.745 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 9.938 ops/ms
Iteration   3: 10.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.992 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (9.938, 9.992, 10.043), stdev = 0.053
  CI (99.9%): [9.035, 10.950] (assumes normal distribution)


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
# Warmup Iteration   1: 3.530 ops/ms
# Warmup Iteration   2: 9.455 ops/ms
# Warmup Iteration   3: 10.334 ops/ms
Iteration   1: 10.189 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.435 ±(99.9%) 4.279 ops/ms [Average]
  (min, avg, max) = (10.189, 10.435, 10.656), stdev = 0.235
  CI (99.9%): [6.156, 14.714] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.290 ops/ms
# Warmup Iteration   2: 9.131 ops/ms
# Warmup Iteration   3: 9.797 ops/ms
Iteration   1: 10.157 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.369 ±(99.9%) 3.612 ops/ms [Average]
  (min, avg, max) = (10.157, 10.369, 10.549), stdev = 0.198
  CI (99.9%): [6.757, 13.980] (assumes normal distribution)


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
# Warmup Iteration   1: 3.632 ops/ms
# Warmup Iteration   2: 8.114 ops/ms
# Warmup Iteration   3: 8.358 ops/ms
Iteration   1: 8.418 ops/ms
Iteration   2: 8.556 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.509 ±(99.9%) 1.447 ops/ms [Average]
  (min, avg, max) = (8.418, 8.509, 8.556), stdev = 0.079
  CI (99.9%): [7.062, 9.956] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.149 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.005 ms/op
Iteration   1: 3.215 ±(99.9%) 0.004 ms/op
Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
Iteration   3: 3.220 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.183 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.115, 3.183, 3.220), stdev = 0.059
  CI (99.9%): [2.103, 4.263] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.621 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.002 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
Iteration   3: 3.107 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.113 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (3.107, 3.113, 3.121), stdev = 0.007
  CI (99.9%): [2.986, 3.240] (assumes normal distribution)


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
# Warmup Iteration   1: 7.280 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.003 ms/op
Iteration   1: 3.247 ±(99.9%) 0.003 ms/op
Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
Iteration   3: 3.249 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.252 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (3.247, 3.252, 3.259), stdev = 0.006
  CI (99.9%): [3.137, 3.366] (assumes normal distribution)


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
# Warmup Iteration   1: 9.019 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.007 ms/op
Iteration   1: 3.685 ±(99.9%) 0.004 ms/op
Iteration   2: 3.572 ±(99.9%) 0.010 ms/op
Iteration   3: 3.635 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.631 ±(99.9%) 1.032 ms/op [Average]
  (min, avg, max) = (3.572, 3.631, 3.685), stdev = 0.057
  CI (99.9%): [2.599, 4.662] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.074 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.011 ms/op
Iteration   1: 3.219 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  8.413 ms/op
                 createUser·p0.9999: 20.917 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   2: 3.101 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  14.478 ms/op
                 createUser·p0.9999: 23.769 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  15.691 ms/op
                 createUser·p0.9999: 18.706 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303941
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23458 
    [ 2.500,  5.000) = 275859 
    [ 5.000,  7.500) = 3955 
    [ 7.500, 10.000) = 281 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     15.353 ms/op
     p(99.9900) =     22.493 ms/op
     p(99.9990) =     24.210 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 6.800 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.008 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.265 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 17.976 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.546 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 20.749 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  9.743 ms/op
                 existUser·p0.9999: 26.804 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316107
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27700 
    [ 2.500,  5.000) = 284764 
    [ 5.000,  7.500) = 3018 
    [ 7.500, 10.000) = 302 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.191 ms/op
     p(95.0000) =      3.342 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     10.763 ms/op
     p(99.9900) =     22.406 ms/op
     p(99.9990) =     27.651 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 7.246 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.010 ms/op
Iteration   1: 3.270 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  10.732 ms/op
                 getUser·p0.9999: 20.756 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   5.514 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 23.036 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303319
  mean =      3.166 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16589 
    [ 2.500,  5.000) = 279316 
    [ 5.000,  7.500) = 6629 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     23.360 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.384 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.010 ms/op
Iteration   1: 3.777 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.993 ms/op
                 listUser·p0.999:  15.567 ms/op
                 listUser·p0.9999: 21.136 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   2: 3.758 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.964 ms/op
                 listUser·p0.999:  14.105 ms/op
                 listUser·p0.9999: 15.942 ms/op
                 listUser·p1.00:   15.942 ms/op

Iteration   3: 3.701 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  12.283 ms/op
                 listUser·p0.9999: 13.861 ms/op
                 listUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256310
  mean =      3.745 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 110 
    [ 2.500,  5.000) = 248355 
    [ 5.000,  7.500) = 6379 
    [ 7.500, 10.000) = 904 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     19.837 ms/op
     p(99.9990) =     21.524 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.992 ± 0.958  ops/ms
ClientPb.existUser                       thrpt       3  10.435 ± 4.279  ops/ms
ClientPb.getUser                         thrpt       3  10.369 ± 3.612  ops/ms
ClientPb.listUser                        thrpt       3   8.509 ± 1.447  ops/ms
ClientPb.createUser                       avgt       3   3.183 ± 1.080   ms/op
ClientPb.existUser                        avgt       3   3.113 ± 0.127   ms/op
ClientPb.getUser                          avgt       3   3.252 ± 0.115   ms/op
ClientPb.listUser                         avgt       3   3.631 ± 1.032   ms/op
ClientPb.createUser                     sample  303941   3.158 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.358           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.469           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.353           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.493           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  316107   3.036 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.763           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.406           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.918           ms/op
ClientPb.getUser                        sample  303319   3.166 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.961           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.256           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.249           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.117           ms/op
ClientPb.listUser                       sample  256310   3.745 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.032           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.681           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.837           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.725           ms/op
