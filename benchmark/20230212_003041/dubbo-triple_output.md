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
# Warmup Iteration   1: 1.817 ops/ms
# Warmup Iteration   2: 4.458 ops/ms
# Warmup Iteration   3: 8.504 ops/ms
Iteration   1: 8.964 ops/ms
Iteration   2: 9.264 ops/ms
Iteration   3: 9.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.205 ±(99.9%) 3.984 ops/ms [Average]
  (min, avg, max) = (8.964, 9.205, 9.389), stdev = 0.218
  CI (99.9%): [5.221, 13.189] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.796 ops/ms
# Warmup Iteration   2: 8.228 ops/ms
# Warmup Iteration   3: 9.489 ops/ms
Iteration   1: 9.628 ops/ms
Iteration   2: 9.641 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.571 ±(99.9%) 2.000 ops/ms [Average]
  (min, avg, max) = (9.445, 9.571, 9.641), stdev = 0.110
  CI (99.9%): [7.571, 11.571] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.703 ops/ms
# Warmup Iteration   2: 8.317 ops/ms
# Warmup Iteration   3: 9.226 ops/ms
Iteration   1: 9.512 ops/ms
Iteration   2: 9.245 ops/ms
Iteration   3: 9.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.400 ±(99.9%) 2.526 ops/ms [Average]
  (min, avg, max) = (9.245, 9.400, 9.512), stdev = 0.138
  CI (99.9%): [6.874, 11.926] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.937 ops/ms
# Warmup Iteration   2: 7.261 ops/ms
# Warmup Iteration   3: 7.624 ops/ms
Iteration   1: 7.573 ops/ms
Iteration   2: 7.365 ops/ms
Iteration   3: 8.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.665 ±(99.9%) 6.484 ops/ms [Average]
  (min, avg, max) = (7.365, 7.665, 8.058), stdev = 0.355
  CI (99.9%): [1.182, 14.149] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 11.224 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.006 ms/op
Iteration   1: 3.600 ±(99.9%) 0.003 ms/op
Iteration   2: 3.593 ±(99.9%) 0.008 ms/op
Iteration   3: 3.604 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.599 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (3.593, 3.599, 3.604), stdev = 0.006
  CI (99.9%): [3.498, 3.700] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.529 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.005 ms/op
Iteration   1: 3.340 ±(99.9%) 0.005 ms/op
Iteration   2: 3.314 ±(99.9%) 0.005 ms/op
Iteration   3: 3.286 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.313 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (3.286, 3.313, 3.340), stdev = 0.027
  CI (99.9%): [2.823, 3.803] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.955 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.009 ms/op
Iteration   1: 3.361 ±(99.9%) 0.010 ms/op
Iteration   2: 3.480 ±(99.9%) 0.007 ms/op
Iteration   3: 3.607 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.483 ±(99.9%) 2.239 ms/op [Average]
  (min, avg, max) = (3.361, 3.483, 3.607), stdev = 0.123
  CI (99.9%): [1.243, 5.722] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.957 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.008 ms/op
Iteration   1: 4.093 ±(99.9%) 0.009 ms/op
Iteration   2: 4.065 ±(99.9%) 0.010 ms/op
Iteration   3: 4.184 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.114 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (4.065, 4.114, 4.184), stdev = 0.062
  CI (99.9%): [2.981, 5.247] (assumes normal distribution)


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
# Warmup Iteration   1: 10.011 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.012 ms/op
Iteration   1: 3.942 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   6.930 ms/op
                 createUser·p0.99:   8.239 ms/op
                 createUser·p0.999:  11.762 ms/op
                 createUser·p0.9999: 32.801 ms/op
                 createUser·p1.00:   33.325 ms/op

Iteration   2: 3.382 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  24.525 ms/op
                 createUser·p0.9999: 28.362 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 3.538 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  26.820 ms/op
                 createUser·p0.9999: 29.687 ms/op
                 createUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265934
  mean =      3.606 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4972 
    [ 2.500,  5.000) = 245189 
    [ 5.000,  7.500) = 12971 
    [ 7.500, 10.000) = 2129 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 136 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     30.252 ms/op
     p(99.9990) =     33.238 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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
# Warmup Iteration   1: 8.377 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.009 ms/op
Iteration   1: 3.409 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.622 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  20.699 ms/op
                 existUser·p0.9999: 26.644 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   2: 3.541 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  24.248 ms/op
                 existUser·p0.9999: 26.208 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.585 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  13.809 ms/op
                 existUser·p0.9999: 43.212 ms/op
                 existUser·p1.00:   43.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 273271
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 265417 
    [ 5.000, 10.000) = 7399 
    [10.000, 15.000) = 192 
    [15.000, 20.000) = 6 
    [20.000, 25.000) = 140 
    [25.000, 30.000) = 85 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     14.086 ms/op
     p(99.9900) =     41.135 ms/op
     p(99.9990) =     43.581 ms/op
     p(99.9999) =     43.778 ms/op
    p(100.0000) =     43.778 ms/op


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
# Warmup Iteration   1: 11.033 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.010 ms/op
Iteration   1: 3.490 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  22.460 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 3.521 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.666 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  23.407 ms/op
                 getUser·p0.9999: 32.235 ms/op
                 getUser·p1.00:   33.522 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  20.297 ms/op
                 getUser·p0.9999: 28.896 ms/op
                 getUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274046
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5956 
    [ 2.500,  5.000) = 258818 
    [ 5.000,  7.500) = 7962 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     21.920 ms/op
     p(99.9900) =     30.421 ms/op
     p(99.9990) =     32.859 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 11.843 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.013 ms/op
Iteration   1: 4.249 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   8.378 ms/op
                 listUser·p0.999:  23.691 ms/op
                 listUser·p0.9999: 27.620 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   2: 4.158 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 4.096 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.055 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230188
  mean =      4.167 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 216477 
    [ 5.000,  7.500) = 10895 
    [ 7.500, 10.000) = 1856 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.729 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     16.433 ms/op
     p(99.9900) =     26.409 ms/op
     p(99.9990) =     28.623 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.205 ± 3.984  ops/ms
ClientPb.existUser                       thrpt       3   9.571 ± 2.000  ops/ms
ClientPb.getUser                         thrpt       3   9.400 ± 2.526  ops/ms
ClientPb.listUser                        thrpt       3   7.665 ± 6.484  ops/ms
ClientPb.createUser                       avgt       3   3.599 ± 0.101   ms/op
ClientPb.existUser                        avgt       3   3.313 ± 0.490   ms/op
ClientPb.getUser                          avgt       3   3.483 ± 2.239   ms/op
ClientPb.listUser                         avgt       3   4.114 ± 1.133   ms/op
ClientPb.createUser                     sample  265934   3.606 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.604           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.553           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.694           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.252           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.325           ms/op
ClientPb.existUser                      sample  273271   3.510 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.085           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.371           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.086           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.135           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.778           ms/op
ClientPb.getUser                        sample  274046   3.502 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.892           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.920           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.421           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.522           ms/op
ClientPb.listUser                       sample  230188   4.167 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.729           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.112           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.433           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.409           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.065           ms/op
