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
# Warmup Iteration   1: 1.069 ops/ms
# Warmup Iteration   2: 2.726 ops/ms
# Warmup Iteration   3: 5.597 ops/ms
Iteration   1: 5.579 ops/ms
Iteration   2: 5.611 ops/ms
Iteration   3: 5.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.682 ±(99.9%) 2.761 ops/ms [Average]
  (min, avg, max) = (5.579, 5.682, 5.855), stdev = 0.151
  CI (99.9%): [2.920, 8.443] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.750 ops/ms
# Warmup Iteration   2: 5.016 ops/ms
# Warmup Iteration   3: 6.416 ops/ms
Iteration   1: 6.363 ops/ms
Iteration   2: 6.626 ops/ms
Iteration   3: 6.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.440 ±(99.9%) 2.966 ops/ms [Average]
  (min, avg, max) = (6.330, 6.440, 6.626), stdev = 0.163
  CI (99.9%): [3.474, 9.405] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.539 ops/ms
# Warmup Iteration   2: 4.932 ops/ms
# Warmup Iteration   3: 5.973 ops/ms
Iteration   1: 6.032 ops/ms
Iteration   2: 6.085 ops/ms
Iteration   3: 5.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.926 ±(99.9%) 4.215 ops/ms [Average]
  (min, avg, max) = (5.661, 5.926, 6.085), stdev = 0.231
  CI (99.9%): [1.711, 10.141] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 4.100 ops/ms
# Warmup Iteration   3: 5.216 ops/ms
Iteration   1: 5.491 ops/ms
Iteration   2: 5.193 ops/ms
Iteration   3: 4.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.217 ±(99.9%) 4.798 ops/ms [Average]
  (min, avg, max) = (4.966, 5.217, 5.491), stdev = 0.263
  CI (99.9%): [0.419, 10.015] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.930 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.381 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.612 ±(99.9%) 0.012 ms/op
Iteration   1: 5.253 ±(99.9%) 0.017 ms/op
Iteration   2: 5.390 ±(99.9%) 0.016 ms/op
Iteration   3: 5.305 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.316 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (5.253, 5.316, 5.390), stdev = 0.069
  CI (99.9%): [4.050, 6.582] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.809 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.548 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.109 ±(99.9%) 0.015 ms/op
Iteration   1: 5.164 ±(99.9%) 0.011 ms/op
Iteration   2: 5.479 ±(99.9%) 0.014 ms/op
Iteration   3: 5.128 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.257 ±(99.9%) 3.526 ms/op [Average]
  (min, avg, max) = (5.128, 5.257, 5.479), stdev = 0.193
  CI (99.9%): [1.731, 8.783] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.092 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.741 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.355 ±(99.9%) 0.015 ms/op
Iteration   1: 5.336 ±(99.9%) 0.012 ms/op
Iteration   2: 5.387 ±(99.9%) 0.010 ms/op
Iteration   3: 5.136 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.286 ±(99.9%) 2.423 ms/op [Average]
  (min, avg, max) = (5.136, 5.286, 5.387), stdev = 0.133
  CI (99.9%): [2.863, 7.710] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.740 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 8.412 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.749 ±(99.9%) 0.013 ms/op
Iteration   1: 6.572 ±(99.9%) 0.012 ms/op
Iteration   2: 6.254 ±(99.9%) 0.016 ms/op
Iteration   3: 6.299 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.375 ±(99.9%) 3.141 ms/op [Average]
  (min, avg, max) = (6.254, 6.375, 6.572), stdev = 0.172
  CI (99.9%): [3.234, 9.517] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.119 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.629 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.092 ±(99.9%) 0.033 ms/op
Iteration   1: 5.585 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.265 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   7.274 ms/op
                 createUser·p0.95:   8.380 ms/op
                 createUser·p0.99:   12.468 ms/op
                 createUser·p0.999:  24.936 ms/op
                 createUser·p0.9999: 28.428 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   2: 5.395 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.474 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   7.823 ms/op
                 createUser·p0.99:   10.617 ms/op
                 createUser·p0.999:  25.212 ms/op
                 createUser·p0.9999: 29.138 ms/op
                 createUser·p1.00:   30.409 ms/op

Iteration   3: 5.565 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.482 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   10.420 ms/op
                 createUser·p0.999:  29.590 ms/op
                 createUser·p0.9999: 36.226 ms/op
                 createUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174047
  mean =      5.514 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 78537 
    [ 5.000,  7.500) = 82016 
    [ 7.500, 10.000) = 10691 
    [10.000, 12.500) = 1690 
    [12.500, 15.000) = 644 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.265 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.086 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     25.131 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     37.045 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.844 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 6.588 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.389 ±(99.9%) 0.023 ms/op
Iteration   1: 5.111 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.183 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.610 ms/op
                 existUser·p0.99:   10.797 ms/op
                 existUser·p0.999:  22.196 ms/op
                 existUser·p0.9999: 27.448 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   2: 5.244 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.832 ms/op
                 existUser·p0.95:   7.832 ms/op
                 existUser·p0.99:   10.650 ms/op
                 existUser·p0.999:  24.778 ms/op
                 existUser·p0.9999: 27.296 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 5.600 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   7.717 ms/op
                 existUser·p0.95:   8.815 ms/op
                 existUser·p0.99:   11.518 ms/op
                 existUser·p0.999:  18.810 ms/op
                 existUser·p0.9999: 33.582 ms/op
                 existUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180750
  mean =      5.310 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 106476 
    [ 5.000,  7.500) = 60533 
    [ 7.500, 10.000) = 10557 
    [10.000, 12.500) = 2357 
    [12.500, 15.000) = 458 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      8.143 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     20.316 ms/op
     p(99.9900) =     32.698 ms/op
     p(99.9990) =     35.122 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.696 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.475 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.649 ±(99.9%) 0.023 ms/op
Iteration   1: 5.424 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.400 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.930 ms/op
                 getUser·p0.95:   8.249 ms/op
                 getUser·p0.99:   11.272 ms/op
                 getUser·p0.999:  23.624 ms/op
                 getUser·p0.9999: 27.341 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   2: 5.290 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.540 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.726 ms/op
                 getUser·p0.95:   7.651 ms/op
                 getUser·p0.99:   10.607 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 31.701 ms/op
                 getUser·p1.00:   32.211 ms/op

Iteration   3: 5.111 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.946 ms/op
                 getUser·p0.50:   4.743 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.668 ms/op
                 getUser·p0.99:   10.217 ms/op
                 getUser·p0.999:  26.393 ms/op
                 getUser·p0.9999: 36.552 ms/op
                 getUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182062
  mean =      5.272 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 102348 
    [ 5.000,  7.500) = 68611 
    [ 7.500, 10.000) = 8456 
    [10.000, 12.500) = 1867 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      7.832 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     36.176 ms/op
     p(99.9990) =     37.251 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.477 ±(99.9%) 0.326 ms/op
# Warmup Iteration   2: 7.172 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.043 ±(99.9%) 0.024 ms/op
Iteration   1: 6.100 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   5.710 ms/op
                 listUser·p0.90:   7.597 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   12.287 ms/op
                 listUser·p0.999:  24.943 ms/op
                 listUser·p0.9999: 28.238 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 6.073 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.695 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   12.321 ms/op
                 listUser·p0.999:  25.243 ms/op
                 listUser·p0.9999: 34.586 ms/op
                 listUser·p1.00:   35.062 ms/op

Iteration   3: 5.895 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.851 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   11.518 ms/op
                 listUser·p0.999:  21.627 ms/op
                 listUser·p0.9999: 27.923 ms/op
                 listUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159286
  mean =      6.021 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 23679 
    [ 5.000,  7.500) = 120328 
    [ 7.500, 10.000) = 11572 
    [10.000, 12.500) = 2301 
    [12.500, 15.000) = 695 
    [15.000, 17.500) = 285 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     12.042 ms/op
     p(99.9000) =     24.707 ms/op
     p(99.9900) =     33.756 ms/op
     p(99.9990) =     34.984 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.682 ± 2.761  ops/ms
ClientPb.existUser                       thrpt       3   6.440 ± 2.966  ops/ms
ClientPb.getUser                         thrpt       3   5.926 ± 4.215  ops/ms
ClientPb.listUser                        thrpt       3   5.217 ± 4.798  ops/ms
ClientPb.createUser                       avgt       3   5.316 ± 1.266   ms/op
ClientPb.existUser                        avgt       3   5.257 ± 3.526   ms/op
ClientPb.getUser                          avgt       3   5.286 ± 2.423   ms/op
ClientPb.listUser                         avgt       3   6.375 ± 3.141   ms/op
ClientPb.createUser                     sample  174047   5.514 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.265           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.111           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.086           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.076           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.131           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.093           ms/op
ClientPb.existUser                      sample  180750   5.310 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.500           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.070           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.143           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.076           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.316           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.698           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.652           ms/op
ClientPb.getUser                        sample  182062   5.272 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.946           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.709           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.832           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.682           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.594           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.176           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.273           ms/op
ClientPb.listUser                       sample  159286   6.021 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.163           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.430           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.042           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.707           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.756           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.062           ms/op
