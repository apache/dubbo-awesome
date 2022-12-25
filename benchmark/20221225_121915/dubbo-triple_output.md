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
# Warmup Iteration   1: 2.589 ops/ms
# Warmup Iteration   2: 6.430 ops/ms
# Warmup Iteration   3: 9.186 ops/ms
Iteration   1: 9.892 ops/ms
Iteration   2: 10.049 ops/ms
Iteration   3: 9.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.926 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (9.839, 9.926, 10.049), stdev = 0.109
  CI (99.9%): [7.932, 11.920] (assumes normal distribution)


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
# Warmup Iteration   1: 3.649 ops/ms
# Warmup Iteration   2: 9.712 ops/ms
# Warmup Iteration   3: 9.926 ops/ms
Iteration   1: 10.715 ops/ms
Iteration   2: 10.126 ops/ms
Iteration   3: 10.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.439 ±(99.9%) 5.406 ops/ms [Average]
  (min, avg, max) = (10.126, 10.439, 10.715), stdev = 0.296
  CI (99.9%): [5.033, 15.845] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.128 ops/ms
# Warmup Iteration   2: 8.702 ops/ms
# Warmup Iteration   3: 10.112 ops/ms
Iteration   1: 10.286 ops/ms
Iteration   2: 10.131 ops/ms
Iteration   3: 10.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.181 ±(99.9%) 1.672 ops/ms [Average]
  (min, avg, max) = (10.125, 10.181, 10.286), stdev = 0.092
  CI (99.9%): [8.509, 11.853] (assumes normal distribution)


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
# Warmup Iteration   1: 3.551 ops/ms
# Warmup Iteration   2: 7.846 ops/ms
# Warmup Iteration   3: 8.449 ops/ms
Iteration   1: 8.421 ops/ms
Iteration   2: 8.673 ops/ms
Iteration   3: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.494 ±(99.9%) 2.842 ops/ms [Average]
  (min, avg, max) = (8.389, 8.494, 8.673), stdev = 0.156
  CI (99.9%): [5.653, 11.336] (assumes normal distribution)


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
# Warmup Iteration   1: 7.328 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.005 ms/op
Iteration   1: 3.234 ±(99.9%) 0.003 ms/op
Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
Iteration   3: 3.182 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.200 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.182, 3.200, 3.234), stdev = 0.030
  CI (99.9%): [2.655, 3.745] (assumes normal distribution)


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
# Warmup Iteration   1: 7.823 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.004 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
Iteration   3: 3.011 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.010 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (3.008, 3.010, 3.012), stdev = 0.002
  CI (99.9%): [2.969, 3.051] (assumes normal distribution)


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
# Warmup Iteration   1: 7.052 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.005 ms/op
Iteration   1: 3.179 ±(99.9%) 0.005 ms/op
Iteration   2: 3.327 ±(99.9%) 0.008 ms/op
Iteration   3: 3.159 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.222 ±(99.9%) 1.674 ms/op [Average]
  (min, avg, max) = (3.159, 3.222, 3.327), stdev = 0.092
  CI (99.9%): [1.547, 4.896] (assumes normal distribution)


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
# Warmup Iteration   1: 9.004 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.006 ms/op
Iteration   1: 3.953 ±(99.9%) 0.008 ms/op
Iteration   2: 3.668 ±(99.9%) 0.006 ms/op
Iteration   3: 3.666 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.762 ±(99.9%) 3.012 ms/op [Average]
  (min, avg, max) = (3.666, 3.762, 3.953), stdev = 0.165
  CI (99.9%): [0.750, 6.775] (assumes normal distribution)


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
# Warmup Iteration   1: 8.284 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.010 ms/op
Iteration   1: 3.153 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  19.628 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.084 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.211 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 23.593 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.219 ms/op
                 createUser·p0.95:   3.363 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  11.767 ms/op
                 createUser·p0.9999: 17.996 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 308612
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24170 
    [ 2.500,  5.000) = 280213 
    [ 5.000,  7.500) = 3379 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 7.982 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.010 ms/op
Iteration   1: 3.145 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  12.901 ms/op
                 existUser·p0.9999: 20.082 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  13.320 ms/op
                 existUser·p0.9999: 21.414 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  11.081 ms/op
                 existUser·p0.9999: 22.872 ms/op
                 existUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309134
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23846 
    [ 2.500,  5.000) = 280658 
    [ 5.000,  7.500) = 3864 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     21.466 ms/op
     p(99.9990) =     23.861 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 8.177 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.010 ms/op
Iteration   1: 3.292 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  16.581 ms/op
                 getUser·p0.9999: 20.424 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.239 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  20.444 ms/op
                 getUser·p0.9999: 25.662 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  10.612 ms/op
                 getUser·p0.9999: 24.110 ms/op
                 getUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297969
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17387 
    [ 2.500,  5.000) = 271826 
    [ 5.000,  7.500) = 7712 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     26.772 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 8.882 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.012 ms/op
Iteration   1: 3.684 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.823 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  13.823 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 3.774 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.309 ms/op
                 listUser·p0.9999: 16.131 ms/op
                 listUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256823
  mean =      3.733 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 249301 
    [ 5.000,  7.500) = 5742 
    [ 7.500, 10.000) = 1119 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.823 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.585 ms/op
     p(99.9900) =     18.623 ms/op
     p(99.9990) =     19.849 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.926 ± 1.994  ops/ms
ClientPb.existUser                       thrpt       3  10.439 ± 5.406  ops/ms
ClientPb.getUser                         thrpt       3  10.181 ± 1.672  ops/ms
ClientPb.listUser                        thrpt       3   8.494 ± 2.842  ops/ms
ClientPb.createUser                       avgt       3   3.200 ± 0.545   ms/op
ClientPb.existUser                        avgt       3   3.010 ± 0.041   ms/op
ClientPb.getUser                          avgt       3   3.222 ± 1.674   ms/op
ClientPb.listUser                         avgt       3   3.762 ± 3.012   ms/op
ClientPb.createUser                     sample  308612   3.106 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.483           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.069           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.724           ms/op
ClientPb.existUser                      sample  309134   3.103 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.602           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.074           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.466           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.297           ms/op
ClientPb.getUser                        sample  297969   3.218 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.145           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.400           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.674           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.001           ms/op
ClientPb.listUser                       sample  256823   3.733 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.823           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.585           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.623           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.677           ms/op
