# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.051 ops/ms
# Warmup Iteration   2: 5.683 ops/ms
# Warmup Iteration   3: 8.723 ops/ms
Iteration   1: 8.901 ops/ms
Iteration   2: 9.248 ops/ms
Iteration   3: 9.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.134 ±(99.9%) 3.674 ops/ms [Average]
  (min, avg, max) = (8.901, 9.134, 9.252), stdev = 0.201
  CI (99.9%): [5.460, 12.807] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ops/ms
# Warmup Iteration   2: 9.027 ops/ms
# Warmup Iteration   3: 9.574 ops/ms
Iteration   1: 9.469 ops/ms
Iteration   2: 9.541 ops/ms
Iteration   3: 9.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.545 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (9.469, 9.545, 9.627), stdev = 0.079
  CI (99.9%): [8.104, 10.987] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.517 ops/ms
# Warmup Iteration   2: 8.805 ops/ms
# Warmup Iteration   3: 8.957 ops/ms
Iteration   1: 9.236 ops/ms
Iteration   2: 9.282 ops/ms
Iteration   3: 9.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.174 ±(99.9%) 2.718 ops/ms [Average]
  (min, avg, max) = (9.004, 9.174, 9.282), stdev = 0.149
  CI (99.9%): [6.456, 11.892] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.854 ops/ms
# Warmup Iteration   2: 7.216 ops/ms
# Warmup Iteration   3: 7.552 ops/ms
Iteration   1: 7.718 ops/ms
Iteration   2: 7.445 ops/ms
Iteration   3: 7.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.580 ±(99.9%) 2.496 ops/ms [Average]
  (min, avg, max) = (7.445, 7.580, 7.718), stdev = 0.137
  CI (99.9%): [5.084, 10.076] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.126 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.006 ms/op
Iteration   1: 3.507 ±(99.9%) 0.004 ms/op
Iteration   2: 3.518 ±(99.9%) 0.005 ms/op
Iteration   3: 3.440 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.488 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (3.440, 3.488, 3.518), stdev = 0.042
  CI (99.9%): [2.717, 4.260] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.549 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.002 ms/op
Iteration   1: 3.287 ±(99.9%) 0.005 ms/op
Iteration   2: 3.362 ±(99.9%) 0.005 ms/op
Iteration   3: 3.311 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.320 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (3.287, 3.320, 3.362), stdev = 0.038
  CI (99.9%): [2.624, 4.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.566 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.003 ms/op
Iteration   1: 3.512 ±(99.9%) 0.004 ms/op
Iteration   2: 3.466 ±(99.9%) 0.003 ms/op
Iteration   3: 3.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.482 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.466, 3.482, 3.512), stdev = 0.026
  CI (99.9%): [3.010, 3.954] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.542 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.005 ms/op
Iteration   1: 4.200 ±(99.9%) 0.006 ms/op
Iteration   2: 4.131 ±(99.9%) 0.006 ms/op
Iteration   3: 4.216 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.182 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (4.131, 4.182, 4.216), stdev = 0.045
  CI (99.9%): [3.358, 5.006] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.252 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.010 ms/op
Iteration   1: 3.421 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  19.349 ms/op
                 createUser·p0.9999: 21.550 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 26.018 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   3: 3.512 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  17.564 ms/op
                 createUser·p0.9999: 26.794 ms/op
                 createUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278388
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4900 
    [ 2.500,  5.000) = 266535 
    [ 5.000,  7.500) = 5742 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     18.698 ms/op
     p(99.9900) =     26.351 ms/op
     p(99.9990) =     27.612 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.161 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.007 ms/op
Iteration   1: 3.483 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.333 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  11.013 ms/op
                 existUser·p0.9999: 21.293 ms/op
                 existUser·p1.00:   21.823 ms/op

Iteration   2: 3.397 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  20.868 ms/op
                 existUser·p0.9999: 23.101 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   3: 3.358 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.354 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  18.408 ms/op
                 existUser·p0.9999: 26.177 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281190
  mean =      3.412 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8376 
    [ 2.500,  5.000) = 266476 
    [ 5.000,  7.500) = 5508 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     11.793 ms/op
     p(99.9900) =     25.555 ms/op
     p(99.9990) =     27.255 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.155 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.013 ms/op
Iteration   1: 3.520 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  8.751 ms/op
                 getUser·p0.9999: 28.079 ms/op
                 getUser·p1.00:   31.850 ms/op

Iteration   2: 3.548 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.951 ms/op
                 getUser·p0.999:  22.217 ms/op
                 getUser·p0.9999: 26.968 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   3: 3.609 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 26.125 ms/op
                 getUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269528
  mean =      3.559 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3298 
    [ 2.500,  5.000) = 259103 
    [ 5.000,  7.500) = 5645 
    [ 7.500, 10.000) = 945 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     16.225 ms/op
     p(99.9900) =     27.463 ms/op
     p(99.9990) =     30.187 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.974 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.317 ±(99.9%) 0.014 ms/op
Iteration   1: 4.174 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  21.561 ms/op
                 listUser·p0.9999: 25.307 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   2: 4.249 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   4.170 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.887 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  16.046 ms/op
                 listUser·p0.9999: 18.606 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 4.263 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   4.153 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.938 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227066
  mean =      4.228 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 216447 
    [ 5.000,  7.500) = 8380 
    [ 7.500, 10.000) = 1390 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 244 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.134 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     16.185 ms/op
     p(99.9900) =     24.146 ms/op
     p(99.9990) =     26.697 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.134 ± 3.674  ops/ms
ClientPb.existUser                       thrpt       3   9.545 ± 1.442  ops/ms
ClientPb.getUser                         thrpt       3   9.174 ± 2.718  ops/ms
ClientPb.listUser                        thrpt       3   7.580 ± 2.496  ops/ms
ClientPb.createUser                       avgt       3   3.488 ± 0.772   ms/op
ClientPb.existUser                        avgt       3   3.320 ± 0.696   ms/op
ClientPb.getUser                          avgt       3   3.482 ± 0.472   ms/op
ClientPb.listUser                         avgt       3   4.182 ± 0.824   ms/op
ClientPb.createUser                     sample  278388   3.447 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.895           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.619           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.698           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.351           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.984           ms/op
ClientPb.existUser                      sample  281190   3.412 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.333           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.915           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.793           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.555           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.525           ms/op
ClientPb.getUser                        sample  269528   3.559 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.447           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.225           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.463           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.850           ms/op
ClientPb.listUser                       sample  227066   4.228 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.134           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.964           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.430           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.185           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.146           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.870           ms/op
