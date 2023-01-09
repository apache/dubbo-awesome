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
# Warmup Iteration   1: 1.589 ops/ms
# Warmup Iteration   2: 4.684 ops/ms
# Warmup Iteration   3: 8.074 ops/ms
Iteration   1: 8.793 ops/ms
Iteration   2: 8.337 ops/ms
Iteration   3: 8.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.708 ±(99.9%) 6.131 ops/ms [Average]
  (min, avg, max) = (8.337, 8.708, 8.993), stdev = 0.336
  CI (99.9%): [2.577, 14.839] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.158 ops/ms
# Warmup Iteration   2: 9.046 ops/ms
# Warmup Iteration   3: 8.645 ops/ms
Iteration   1: 9.147 ops/ms
Iteration   2: 9.286 ops/ms
Iteration   3: 9.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.239 ±(99.9%) 1.460 ops/ms [Average]
  (min, avg, max) = (9.147, 9.239, 9.286), stdev = 0.080
  CI (99.9%): [7.779, 10.700] (assumes normal distribution)


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
# Warmup Iteration   1: 2.803 ops/ms
# Warmup Iteration   2: 8.100 ops/ms
# Warmup Iteration   3: 9.103 ops/ms
Iteration   1: 9.608 ops/ms
Iteration   2: 8.965 ops/ms
Iteration   3: 8.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.891 ±(99.9%) 13.793 ops/ms [Average]
  (min, avg, max) = (8.101, 8.891, 9.608), stdev = 0.756
  CI (99.9%): [≈ 0, 22.684] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.209 ops/ms
# Warmup Iteration   2: 6.481 ops/ms
# Warmup Iteration   3: 7.151 ops/ms
Iteration   1: 6.994 ops/ms
Iteration   2: 7.151 ops/ms
Iteration   3: 7.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.061 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (6.994, 7.061, 7.151), stdev = 0.081
  CI (99.9%): [5.589, 8.533] (assumes normal distribution)


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
# Warmup Iteration   1: 15.062 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.004 ms/op
Iteration   1: 3.634 ±(99.9%) 0.011 ms/op
Iteration   2: 3.630 ±(99.9%) 0.008 ms/op
Iteration   3: 3.557 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.607 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.557, 3.607, 3.634), stdev = 0.043
  CI (99.9%): [2.821, 4.393] (assumes normal distribution)


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
# Warmup Iteration   1: 10.258 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.005 ms/op
Iteration   1: 3.527 ±(99.9%) 0.007 ms/op
Iteration   2: 3.788 ±(99.9%) 0.008 ms/op
Iteration   3: 3.758 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.691 ±(99.9%) 2.608 ms/op [Average]
  (min, avg, max) = (3.527, 3.691, 3.788), stdev = 0.143
  CI (99.9%): [1.083, 6.299] (assumes normal distribution)


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
# Warmup Iteration   1: 12.834 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.885 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.003 ms/op
Iteration   1: 3.761 ±(99.9%) 0.005 ms/op
Iteration   2: 4.064 ±(99.9%) 0.004 ms/op
Iteration   3: 3.860 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.895 ±(99.9%) 2.819 ms/op [Average]
  (min, avg, max) = (3.761, 3.895, 4.064), stdev = 0.155
  CI (99.9%): [1.076, 6.715] (assumes normal distribution)


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
# Warmup Iteration   1: 13.480 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.816 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.430 ±(99.9%) 0.007 ms/op
Iteration   1: 4.484 ±(99.9%) 0.008 ms/op
Iteration   2: 4.498 ±(99.9%) 0.010 ms/op
Iteration   3: 4.470 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.484 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (4.470, 4.484, 4.498), stdev = 0.014
  CI (99.9%): [4.232, 4.736] (assumes normal distribution)


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
# Warmup Iteration   1: 14.394 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.622 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.363 ±(99.9%) 0.022 ms/op
Iteration   1: 3.691 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  25.548 ms/op
                 createUser·p0.9999: 28.650 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   2: 3.575 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.957 ms/op
                 createUser·p0.999:  27.390 ms/op
                 createUser·p0.9999: 35.791 ms/op
                 createUser·p1.00:   36.372 ms/op

Iteration   3: 3.596 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.428 ms/op
                 createUser·p0.999:  30.540 ms/op
                 createUser·p0.9999: 35.402 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265075
  mean =      3.620 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4539 
    [ 2.500,  5.000) = 251945 
    [ 5.000,  7.500) = 6915 
    [ 7.500, 10.000) = 983 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 61 
    [35.000, 37.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     35.356 ms/op
     p(99.9990) =     36.156 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 11.557 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.013 ms/op
Iteration   1: 3.577 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.850 ms/op
                 existUser·p0.999:  10.889 ms/op
                 existUser·p0.9999: 36.381 ms/op
                 existUser·p1.00:   38.011 ms/op

Iteration   2: 3.617 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.665 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   7.610 ms/op
                 existUser·p0.999:  26.860 ms/op
                 existUser·p0.9999: 29.737 ms/op
                 existUser·p1.00:   30.507 ms/op

Iteration   3: 3.426 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.501 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  27.905 ms/op
                 existUser·p0.9999: 36.548 ms/op
                 existUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 270916
  mean =      3.538 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2666 
    [ 2.500,  5.000) = 259754 
    [ 5.000,  7.500) = 6227 
    [ 7.500, 10.000) = 1487 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 106 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     21.933 ms/op
     p(99.9900) =     36.301 ms/op
     p(99.9990) =     38.011 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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
# Warmup Iteration   1: 11.732 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.569 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.014 ms/op
Iteration   1: 3.729 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   5.464 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  24.482 ms/op
                 getUser·p0.9999: 35.979 ms/op
                 getUser·p1.00:   38.011 ms/op

Iteration   2: 3.615 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.256 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  24.218 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   3: 3.756 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  28.681 ms/op
                 getUser·p0.9999: 31.712 ms/op
                 getUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 259597
  mean =      3.699 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2321 
    [ 2.500,  5.000) = 247507 
    [ 5.000,  7.500) = 7679 
    [ 7.500, 10.000) = 1299 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     24.622 ms/op
     p(99.9900) =     31.569 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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
# Warmup Iteration   1: 14.743 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.493 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.717 ±(99.9%) 0.021 ms/op
Iteration   1: 4.238 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   8.098 ms/op
                 listUser·p0.999:  27.106 ms/op
                 listUser·p0.9999: 30.763 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   2: 4.384 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   8.229 ms/op
                 listUser·p0.999:  21.922 ms/op
                 listUser·p0.9999: 24.403 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 4.437 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  18.382 ms/op
                 listUser·p0.9999: 21.352 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 220385
  mean =      4.351 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 203090 
    [ 5.000,  7.500) = 12863 
    [ 7.500, 10.000) = 3292 
    [10.000, 12.500) = 518 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     21.450 ms/op
     p(99.9900) =     29.983 ms/op
     p(99.9990) =     32.572 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.708 ±  6.131  ops/ms
ClientPb.existUser                       thrpt       3   9.239 ±  1.460  ops/ms
ClientPb.getUser                         thrpt       3   8.891 ± 13.793  ops/ms
ClientPb.listUser                        thrpt       3   7.061 ±  1.472  ops/ms
ClientPb.createUser                       avgt       3   3.607 ±  0.786   ms/op
ClientPb.existUser                        avgt       3   3.691 ±  2.608   ms/op
ClientPb.getUser                          avgt       3   3.895 ±  2.819   ms/op
ClientPb.listUser                         avgt       3   4.484 ±  0.252   ms/op
ClientPb.createUser                     sample  265075   3.620 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.487            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.473            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.129            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.538            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.775            ms/op
ClientPb.createUser:createUser·p0.999   sample          26.083            ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.356            ms/op
ClientPb.createUser:createUser·p1.00    sample          36.372            ms/op
ClientPb.existUser                      sample  270916   3.538 ±  0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.501            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.379            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.924            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.358            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.062            ms/op
ClientPb.existUser:existUser·p0.999     sample          21.933            ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.301            ms/op
ClientPb.existUser:existUser·p1.00      sample          38.011            ms/op
ClientPb.getUser                        sample  259597   3.699 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.581            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.551            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.182            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.628            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.102            ms/op
ClientPb.getUser:getUser·p0.999         sample          24.622            ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.569            ms/op
ClientPb.getUser:getUser·p1.00          sample          38.011            ms/op
ClientPb.listUser                       sample  220385   4.351 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.104            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.145            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.850            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.505            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.503            ms/op
ClientPb.listUser:listUser·p0.999       sample          21.450            ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.983            ms/op
ClientPb.listUser:listUser·p1.00        sample          32.899            ms/op
