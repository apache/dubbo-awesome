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
# Warmup Iteration   1: 1.958 ops/ms
# Warmup Iteration   2: 5.460 ops/ms
# Warmup Iteration   3: 8.520 ops/ms
Iteration   1: 9.579 ops/ms
Iteration   2: 9.539 ops/ms
Iteration   3: 9.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.554 ±(99.9%) 0.389 ops/ms [Average]
  (min, avg, max) = (9.539, 9.554, 9.579), stdev = 0.021
  CI (99.9%): [9.165, 9.944] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 8.753 ops/ms
# Warmup Iteration   3: 9.311 ops/ms
Iteration   1: 9.952 ops/ms
Iteration   2: 9.819 ops/ms
Iteration   3: 9.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.829 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (9.717, 9.829, 9.952), stdev = 0.118
  CI (99.9%): [7.676, 11.983] (assumes normal distribution)


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
# Warmup Iteration   1: 2.972 ops/ms
# Warmup Iteration   2: 8.700 ops/ms
# Warmup Iteration   3: 8.696 ops/ms
Iteration   1: 9.051 ops/ms
Iteration   2: 9.241 ops/ms
Iteration   3: 9.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.114 ±(99.9%) 2.005 ops/ms [Average]
  (min, avg, max) = (9.050, 9.114, 9.241), stdev = 0.110
  CI (99.9%): [7.109, 11.120] (assumes normal distribution)


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
# Warmup Iteration   1: 2.941 ops/ms
# Warmup Iteration   2: 7.333 ops/ms
# Warmup Iteration   3: 7.978 ops/ms
Iteration   1: 7.822 ops/ms
Iteration   2: 7.918 ops/ms
Iteration   3: 8.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.032 ±(99.9%) 5.193 ops/ms [Average]
  (min, avg, max) = (7.822, 8.032, 8.356), stdev = 0.285
  CI (99.9%): [2.839, 13.224] (assumes normal distribution)


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
# Warmup Iteration   1: 9.729 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.005 ms/op
Iteration   1: 3.366 ±(99.9%) 0.008 ms/op
Iteration   2: 3.327 ±(99.9%) 0.006 ms/op
Iteration   3: 3.388 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.360 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.327, 3.360, 3.388), stdev = 0.031
  CI (99.9%): [2.791, 3.929] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.171 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.004 ms/op
Iteration   1: 3.220 ±(99.9%) 0.007 ms/op
Iteration   2: 3.294 ±(99.9%) 0.004 ms/op
Iteration   3: 3.289 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.268 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.220, 3.268, 3.294), stdev = 0.041
  CI (99.9%): [2.518, 4.017] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.043 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.002 ms/op
Iteration   1: 3.379 ±(99.9%) 0.003 ms/op
Iteration   2: 3.406 ±(99.9%) 0.008 ms/op
Iteration   3: 3.442 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.409 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (3.379, 3.409, 3.442), stdev = 0.032
  CI (99.9%): [2.828, 3.989] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.028 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.009 ms/op
Iteration   1: 4.233 ±(99.9%) 0.006 ms/op
Iteration   2: 4.489 ±(99.9%) 0.013 ms/op
Iteration   3: 4.027 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.250 ±(99.9%) 4.217 ms/op [Average]
  (min, avg, max) = (4.027, 4.250, 4.489), stdev = 0.231
  CI (99.9%): [0.033, 8.467] (assumes normal distribution)


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
# Warmup Iteration   1: 9.092 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.010 ms/op
Iteration   1: 3.539 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  19.224 ms/op
                 createUser·p0.9999: 25.390 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   2: 3.484 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  21.642 ms/op
                 createUser·p0.9999: 24.945 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.515 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.861 ms/op
                 createUser·p0.999:  17.494 ms/op
                 createUser·p0.9999: 27.161 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273216
  mean =      3.512 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3509 
    [ 2.500,  5.000) = 262889 
    [ 5.000,  7.500) = 5765 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     25.931 ms/op
     p(99.9990) =     27.593 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 7.540 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.009 ms/op
Iteration   1: 3.425 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  20.283 ms/op
                 existUser·p0.9999: 31.249 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   2: 3.286 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.714 ms/op
                 existUser·p0.999:  14.107 ms/op
                 existUser·p0.9999: 25.217 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   3: 3.331 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  17.863 ms/op
                 existUser·p0.9999: 25.794 ms/op
                 existUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286745
  mean =      3.347 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17902 
    [ 2.500,  5.000) = 263550 
    [ 5.000,  7.500) = 4274 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     18.155 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     31.392 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 8.377 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.012 ms/op
Iteration   1: 3.554 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.894 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  20.381 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   2: 3.408 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  22.454 ms/op
                 getUser·p0.9999: 28.069 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 3.528 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  19.071 ms/op
                 getUser·p0.9999: 27.228 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274546
  mean =      3.495 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8320 
    [ 2.500,  5.000) = 255137 
    [ 5.000,  7.500) = 9618 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     19.348 ms/op
     p(99.9900) =     27.248 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 8.812 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
Iteration   1: 3.985 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.869 ms/op
                 listUser·p0.999:  17.180 ms/op
                 listUser·p0.9999: 22.478 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 4.073 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.068 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.157 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 19.731 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  14.258 ms/op
                 listUser·p0.9999: 15.532 ms/op
                 listUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238650
  mean =      4.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 231758 
    [ 5.000,  7.500) = 5063 
    [ 7.500, 10.000) = 1082 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     21.992 ms/op
     p(99.9990) =     22.532 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.554 ± 0.389  ops/ms
ClientPb.existUser                       thrpt       3   9.829 ± 2.153  ops/ms
ClientPb.getUser                         thrpt       3   9.114 ± 2.005  ops/ms
ClientPb.listUser                        thrpt       3   8.032 ± 5.193  ops/ms
ClientPb.createUser                       avgt       3   3.360 ± 0.569   ms/op
ClientPb.existUser                        avgt       3   3.268 ± 0.750   ms/op
ClientPb.getUser                          avgt       3   3.409 ± 0.580   ms/op
ClientPb.listUser                         avgt       3   4.250 ± 4.217   ms/op
ClientPb.createUser                     sample  273216   3.512 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.511           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.350           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.754           ms/op
ClientPb.existUser                      sample  286745   3.347 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.085           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.155           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.409           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  274546   3.495 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.740           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.348           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.248           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.803           ms/op
ClientPb.listUser                       sample  238650   4.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.031           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.565           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.992           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.675           ms/op
