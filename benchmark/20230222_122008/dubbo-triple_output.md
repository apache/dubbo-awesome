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
# Warmup Iteration   1: 1.992 ops/ms
# Warmup Iteration   2: 4.014 ops/ms
# Warmup Iteration   3: 8.585 ops/ms
Iteration   1: 8.946 ops/ms
Iteration   2: 9.126 ops/ms
Iteration   3: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.182 ±(99.9%) 4.876 ops/ms [Average]
  (min, avg, max) = (8.946, 9.182, 9.472), stdev = 0.267
  CI (99.9%): [4.306, 14.058] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.826 ops/ms
# Warmup Iteration   2: 8.969 ops/ms
# Warmup Iteration   3: 9.440 ops/ms
Iteration   1: 9.696 ops/ms
Iteration   2: 9.963 ops/ms
Iteration   3: 9.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.819 ±(99.9%) 2.455 ops/ms [Average]
  (min, avg, max) = (9.696, 9.819, 9.963), stdev = 0.135
  CI (99.9%): [7.363, 12.274] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.581 ops/ms
# Warmup Iteration   2: 8.215 ops/ms
# Warmup Iteration   3: 8.992 ops/ms
Iteration   1: 9.382 ops/ms
Iteration   2: 9.521 ops/ms
Iteration   3: 9.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.410 ±(99.9%) 1.829 ops/ms [Average]
  (min, avg, max) = (9.326, 9.410, 9.521), stdev = 0.100
  CI (99.9%): [7.581, 11.239] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.619 ops/ms
# Warmup Iteration   2: 6.924 ops/ms
# Warmup Iteration   3: 7.589 ops/ms
Iteration   1: 7.526 ops/ms
Iteration   2: 7.828 ops/ms
Iteration   3: 7.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.700 ±(99.9%) 2.847 ops/ms [Average]
  (min, avg, max) = (7.526, 7.700, 7.828), stdev = 0.156
  CI (99.9%): [4.853, 10.547] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.425 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.006 ms/op
Iteration   1: 3.336 ±(99.9%) 0.014 ms/op
Iteration   2: 3.455 ±(99.9%) 0.007 ms/op
Iteration   3: 3.428 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.406 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.336, 3.406, 3.455), stdev = 0.062
  CI (99.9%): [2.271, 4.541] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.528 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.004 ms/op
Iteration   1: 3.245 ±(99.9%) 0.009 ms/op
Iteration   2: 3.521 ±(99.9%) 0.003 ms/op
Iteration   3: 3.367 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.377 ±(99.9%) 2.517 ms/op [Average]
  (min, avg, max) = (3.245, 3.377, 3.521), stdev = 0.138
  CI (99.9%): [0.860, 5.895] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 11.401 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.007 ms/op
Iteration   1: 3.462 ±(99.9%) 0.004 ms/op
Iteration   2: 3.560 ±(99.9%) 0.005 ms/op
Iteration   3: 3.553 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.525 ±(99.9%) 0.998 ms/op [Average]
  (min, avg, max) = (3.462, 3.525, 3.560), stdev = 0.055
  CI (99.9%): [2.527, 4.522] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 12.100 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.007 ms/op
Iteration   1: 4.184 ±(99.9%) 0.007 ms/op
Iteration   2: 4.038 ±(99.9%) 0.009 ms/op
Iteration   3: 3.972 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.064 ±(99.9%) 1.977 ms/op [Average]
  (min, avg, max) = (3.972, 4.064, 4.184), stdev = 0.108
  CI (99.9%): [2.087, 6.042] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.733 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.010 ms/op
Iteration   1: 3.337 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  21.076 ms/op
                 createUser·p0.9999: 26.274 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   2: 3.336 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.483 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  23.744 ms/op
                 createUser·p0.9999: 29.124 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   3: 3.435 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.494 ms/op
                 createUser·p0.999:  20.955 ms/op
                 createUser·p0.9999: 39.367 ms/op
                 createUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285090
  mean =      3.369 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 278618 
    [ 5.000, 10.000) = 5860 
    [10.000, 15.000) = 291 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 142 
    [25.000, 30.000) = 113 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     20.960 ms/op
     p(99.9900) =     38.404 ms/op
     p(99.9990) =     39.875 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.400 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
Iteration   1: 3.314 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.761 ms/op
                 existUser·p0.999:  15.798 ms/op
                 existUser·p0.9999: 25.243 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   2: 3.441 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  24.379 ms/op
                 existUser·p0.9999: 27.754 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.442 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  14.399 ms/op
                 existUser·p0.9999: 29.342 ms/op
                 existUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282328
  mean =      3.398 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12305 
    [ 2.500,  5.000) = 262241 
    [ 5.000,  7.500) = 6530 
    [ 7.500, 10.000) = 764 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.101 ms/op
     p(99.9000) =     17.323 ms/op
     p(99.9900) =     28.591 ms/op
     p(99.9990) =     30.916 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 10.389 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.014 ms/op
Iteration   1: 4.323 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.778 ms/op
                 getUser·p0.999:  13.861 ms/op
                 getUser·p0.9999: 37.749 ms/op
                 getUser·p1.00:   38.470 ms/op

Iteration   2: 3.386 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  21.459 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  24.150 ms/op
                 getUser·p0.9999: 28.590 ms/op
                 getUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 260946
  mean =      3.677 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2963 
    [ 2.500,  5.000) = 234293 
    [ 5.000,  7.500) = 21566 
    [ 7.500, 10.000) = 1409 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     14.648 ms/op
     p(99.9900) =     35.711 ms/op
     p(99.9990) =     38.062 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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
# Warmup Iteration   1: 10.679 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.015 ms/op
Iteration   1: 4.145 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   8.062 ms/op
                 listUser·p0.999:  18.888 ms/op
                 listUser·p0.9999: 31.785 ms/op
                 listUser·p1.00:   32.834 ms/op

Iteration   2: 3.992 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  16.645 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 4.086 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  15.511 ms/op
                 listUser·p0.9999: 21.010 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235535
  mean =      4.074 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 225756 
    [ 5.000,  7.500) = 7046 
    [ 7.500, 10.000) = 1698 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 234 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     16.858 ms/op
     p(99.9900) =     26.819 ms/op
     p(99.9990) =     32.469 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.182 ± 4.876  ops/ms
ClientPb.existUser                       thrpt       3   9.819 ± 2.455  ops/ms
ClientPb.getUser                         thrpt       3   9.410 ± 1.829  ops/ms
ClientPb.listUser                        thrpt       3   7.700 ± 2.847  ops/ms
ClientPb.createUser                       avgt       3   3.406 ± 1.135   ms/op
ClientPb.existUser                        avgt       3   3.377 ± 2.517   ms/op
ClientPb.getUser                          avgt       3   3.525 ± 0.998   ms/op
ClientPb.listUser                         avgt       3   4.064 ± 1.977   ms/op
ClientPb.createUser                     sample  285090   3.369 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.483           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.980           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.960           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.404           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.501           ms/op
ClientPb.existUser                      sample  282328   3.398 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.257           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.101           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.323           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.591           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.490           ms/op
ClientPb.getUser                        sample  260946   3.677 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.964           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.439           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.168           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.648           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.711           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.470           ms/op
ClientPb.listUser                       sample  235535   4.074 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.632           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.858           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.819           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.834           ms/op
