# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.563 ops/ms
# Warmup Iteration   2: 6.111 ops/ms
# Warmup Iteration   3: 9.484 ops/ms
Iteration   1: 9.852 ops/ms
Iteration   2: 9.932 ops/ms
Iteration   3: 10.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.984 ±(99.9%) 2.990 ops/ms [Average]
  (min, avg, max) = (9.852, 9.984, 10.167), stdev = 0.164
  CI (99.9%): [6.994, 12.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ops/ms
# Warmup Iteration   2: 9.705 ops/ms
# Warmup Iteration   3: 10.356 ops/ms
Iteration   1: 10.277 ops/ms
Iteration   2: 10.739 ops/ms
Iteration   3: 10.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.484 ±(99.9%) 4.277 ops/ms [Average]
  (min, avg, max) = (10.277, 10.484, 10.739), stdev = 0.234
  CI (99.9%): [6.207, 14.761] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ops/ms
# Warmup Iteration   2: 9.246 ops/ms
# Warmup Iteration   3: 9.745 ops/ms
Iteration   1: 9.834 ops/ms
Iteration   2: 10.096 ops/ms
Iteration   3: 10.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.114 ±(99.9%) 5.267 ops/ms [Average]
  (min, avg, max) = (9.834, 10.114, 10.411), stdev = 0.289
  CI (99.9%): [4.846, 15.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.520 ops/ms
# Warmup Iteration   2: 7.676 ops/ms
# Warmup Iteration   3: 8.352 ops/ms
Iteration   1: 8.611 ops/ms
Iteration   2: 8.456 ops/ms
Iteration   3: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.511 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (8.456, 8.511, 8.611), stdev = 0.086
  CI (99.9%): [6.936, 10.087] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.538 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.004 ms/op
Iteration   1: 3.230 ±(99.9%) 0.002 ms/op
Iteration   2: 3.165 ±(99.9%) 0.004 ms/op
Iteration   3: 3.228 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.207 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (3.165, 3.207, 3.230), stdev = 0.037
  CI (99.9%): [2.529, 3.886] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.996 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.003 ms/op
Iteration   1: 2.975 ±(99.9%) 0.003 ms/op
Iteration   2: 3.336 ±(99.9%) 0.005 ms/op
Iteration   3: 2.981 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 3.773 ms/op [Average]
  (min, avg, max) = (2.975, 3.097, 3.336), stdev = 0.207
  CI (99.9%): [≈ 0, 6.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.086 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.003 ms/op
Iteration   1: 3.194 ±(99.9%) 0.005 ms/op
Iteration   2: 3.341 ±(99.9%) 0.005 ms/op
Iteration   3: 3.213 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.249 ±(99.9%) 1.455 ms/op [Average]
  (min, avg, max) = (3.194, 3.249, 3.341), stdev = 0.080
  CI (99.9%): [1.794, 4.704] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.213 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.006 ms/op
Iteration   1: 3.633 ±(99.9%) 0.010 ms/op
Iteration   2: 3.708 ±(99.9%) 0.008 ms/op
Iteration   3: 3.778 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.706 ±(99.9%) 1.326 ms/op [Average]
  (min, avg, max) = (3.633, 3.706, 3.778), stdev = 0.073
  CI (99.9%): [2.381, 5.032] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.489 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
Iteration   1: 3.256 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.963 ms/op
                 createUser·p0.999:  18.245 ms/op
                 createUser·p0.9999: 26.518 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 21.525 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.374 ms/op
                 createUser·p0.999:  15.942 ms/op
                 createUser·p0.9999: 21.914 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296666
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22149 
    [ 2.500,  5.000) = 266045 
    [ 5.000,  7.500) = 7301 
    [ 7.500, 10.000) = 598 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     27.362 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.699 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 21.652 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  14.156 ms/op
                 existUser·p0.9999: 21.115 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  10.027 ms/op
                 existUser·p0.9999: 21.332 ms/op
                 existUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310094
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17167 
    [ 2.500,  5.000) = 288694 
    [ 5.000,  7.500) = 3428 
    [ 7.500, 10.000) = 379 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.561 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.360 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.010 ms/op
Iteration   1: 3.242 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  19.164 ms/op
                 getUser·p0.9999: 26.972 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  9.613 ms/op
                 getUser·p0.9999: 25.846 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.642 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  12.360 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304652
  mean =      3.150 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15844 
    [ 2.500,  5.000) = 283102 
    [ 5.000,  7.500) = 4858 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     15.822 ms/op
     p(99.9900) =     25.887 ms/op
     p(99.9990) =     27.976 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.493 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.011 ms/op
Iteration   1: 3.706 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 22.942 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 3.906 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.313 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 3.743 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  11.928 ms/op
                 listUser·p0.9999: 13.386 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253614
  mean =      3.783 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 100 
    [ 2.500,  5.000) = 244810 
    [ 5.000,  7.500) = 6318 
    [ 7.500, 10.000) = 1570 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.313 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     21.386 ms/op
     p(99.9990) =     23.215 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.984 ± 2.990  ops/ms
ClientPb.existUser                       thrpt       3  10.484 ± 4.277  ops/ms
ClientPb.getUser                         thrpt       3  10.114 ± 5.267  ops/ms
ClientPb.listUser                        thrpt       3   8.511 ± 1.576  ops/ms
ClientPb.createUser                       avgt       3   3.207 ± 0.678   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 3.773   ms/op
ClientPb.getUser                          avgt       3   3.249 ± 1.455   ms/op
ClientPb.listUser                         avgt       3   3.706 ± 1.326   ms/op
ClientPb.createUser                     sample  296666   3.235 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.026           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.728           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.330           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  310094   3.093 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.997           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.332           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.741           ms/op
ClientPb.getUser                        sample  304652   3.150 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.031           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.822           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.887           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  253614   3.783 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.313           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.386           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.298           ms/op
