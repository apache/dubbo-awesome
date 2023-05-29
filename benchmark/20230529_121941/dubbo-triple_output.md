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
# Warmup Iteration   1: 0.894 ops/ms
# Warmup Iteration   2: 1.916 ops/ms
# Warmup Iteration   3: 4.084 ops/ms
Iteration   1: 5.009 ops/ms
Iteration   2: 5.583 ops/ms
Iteration   3: 5.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.431 ±(99.9%) 6.743 ops/ms [Average]
  (min, avg, max) = (5.009, 5.431, 5.700), stdev = 0.370
  CI (99.9%): [≈ 0, 12.174] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:20
# Fork: 1 of 1
# Warmup Iteration   1: 1.498 ops/ms
# Warmup Iteration   2: 4.656 ops/ms
# Warmup Iteration   3: 5.865 ops/ms
Iteration   1: 6.068 ops/ms
Iteration   2: 6.072 ops/ms
Iteration   3: 6.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.087 ±(99.9%) 0.553 ops/ms [Average]
  (min, avg, max) = (6.068, 6.087, 6.122), stdev = 0.030
  CI (99.9%): [5.534, 6.640] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.387 ops/ms
# Warmup Iteration   2: 3.811 ops/ms
# Warmup Iteration   3: 5.366 ops/ms
Iteration   1: 5.728 ops/ms
Iteration   2: 5.746 ops/ms
Iteration   3: 5.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.703 ±(99.9%) 1.081 ops/ms [Average]
  (min, avg, max) = (5.635, 5.703, 5.746), stdev = 0.059
  CI (99.9%): [4.622, 6.784] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.385 ops/ms
# Warmup Iteration   2: 3.381 ops/ms
# Warmup Iteration   3: 4.673 ops/ms
Iteration   1: 4.756 ops/ms
Iteration   2: 4.582 ops/ms
Iteration   3: 4.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.707 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (4.582, 4.707, 4.783), stdev = 0.109
  CI (99.9%): [2.713, 6.701] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 20.334 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.326 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.905 ±(99.9%) 0.016 ms/op
Iteration   1: 5.706 ±(99.9%) 0.013 ms/op
Iteration   2: 5.875 ±(99.9%) 0.013 ms/op
Iteration   3: 6.284 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.955 ±(99.9%) 5.419 ms/op [Average]
  (min, avg, max) = (5.706, 5.955, 6.284), stdev = 0.297
  CI (99.9%): [0.536, 11.374] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 18.463 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.568 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.436 ±(99.9%) 0.008 ms/op
Iteration   1: 5.205 ±(99.9%) 0.014 ms/op
Iteration   2: 5.422 ±(99.9%) 0.009 ms/op
Iteration   3: 5.387 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.338 ±(99.9%) 2.122 ms/op [Average]
  (min, avg, max) = (5.205, 5.338, 5.422), stdev = 0.116
  CI (99.9%): [3.216, 7.460] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 18.798 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.919 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.780 ±(99.9%) 0.011 ms/op
Iteration   1: 6.012 ±(99.9%) 0.011 ms/op
Iteration   2: 5.659 ±(99.9%) 0.011 ms/op
Iteration   3: 5.588 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.753 ±(99.9%) 4.145 ms/op [Average]
  (min, avg, max) = (5.588, 5.753, 6.012), stdev = 0.227
  CI (99.9%): [1.607, 9.898] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 21.070 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 8.182 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.946 ±(99.9%) 0.014 ms/op
Iteration   1: 6.635 ±(99.9%) 0.017 ms/op
Iteration   2: 6.558 ±(99.9%) 0.016 ms/op
Iteration   3: 6.706 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.633 ±(99.9%) 1.349 ms/op [Average]
  (min, avg, max) = (6.558, 6.633, 6.706), stdev = 0.074
  CI (99.9%): [5.284, 7.983] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.069 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.923 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.674 ±(99.9%) 0.021 ms/op
Iteration   1: 5.508 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.298 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.660 ms/op
                 createUser·p0.95:   7.594 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  25.948 ms/op
                 createUser·p0.9999: 30.971 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 5.674 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.179 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   7.053 ms/op
                 createUser·p0.95:   7.684 ms/op
                 createUser·p0.99:   11.053 ms/op
                 createUser·p0.999:  27.810 ms/op
                 createUser·p0.9999: 31.342 ms/op
                 createUser·p1.00:   35.586 ms/op

Iteration   3: 5.819 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.095 ms/op
                 createUser·p0.50:   5.562 ms/op
                 createUser·p0.90:   7.143 ms/op
                 createUser·p0.95:   7.954 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  16.778 ms/op
                 createUser·p0.9999: 32.588 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169553
  mean =      5.664 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 51536 
    [ 5.000,  7.500) = 107506 
    [ 7.500, 10.000) = 8379 
    [10.000, 12.500) = 1395 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.095 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     19.452 ms/op
     p(99.9900) =     31.982 ms/op
     p(99.9990) =     34.355 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.319 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 6.635 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.481 ±(99.9%) 0.019 ms/op
Iteration   1: 5.508 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.327 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   8.266 ms/op
                 existUser·p0.99:   11.682 ms/op
                 existUser·p0.999:  21.810 ms/op
                 existUser·p0.9999: 27.970 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   2: 5.339 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.478 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.398 ms/op
                 existUser·p0.95:   6.930 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  15.502 ms/op
                 existUser·p0.9999: 28.738 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   3: 5.704 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   7.475 ms/op
                 existUser·p0.95:   8.307 ms/op
                 existUser·p0.99:   10.917 ms/op
                 existUser·p0.999:  25.231 ms/op
                 existUser·p0.9999: 34.378 ms/op
                 existUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174096
  mean =      5.513 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 69298 
    [ 5.000,  7.500) = 93317 
    [ 7.500, 10.000) = 9038 
    [10.000, 12.500) = 1511 
    [12.500, 15.000) = 482 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      7.881 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     22.115 ms/op
     p(99.9900) =     31.870 ms/op
     p(99.9990) =     35.523 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.983 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 6.670 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.670 ±(99.9%) 0.020 ms/op
Iteration   1: 5.643 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.621 ms/op
                 getUser·p0.50:   5.349 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   8.004 ms/op
                 getUser·p0.99:   11.076 ms/op
                 getUser·p0.999:  24.561 ms/op
                 getUser·p0.9999: 29.404 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   2: 5.707 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.605 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.184 ms/op
                 getUser·p0.95:   9.273 ms/op
                 getUser·p0.99:   12.419 ms/op
                 getUser·p0.999:  18.809 ms/op
                 getUser·p0.9999: 33.583 ms/op
                 getUser·p1.00:   35.324 ms/op

Iteration   3: 5.770 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.834 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   7.258 ms/op
                 getUser·p0.95:   8.462 ms/op
                 getUser·p0.99:   12.141 ms/op
                 getUser·p0.999:  29.027 ms/op
                 getUser·p0.9999: 34.668 ms/op
                 getUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168050
  mean =      5.706 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 51779 
    [ 5.000,  7.500) = 103154 
    [ 7.500, 10.000) = 8954 
    [10.000, 12.500) = 2897 
    [12.500, 15.000) = 726 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.605 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.037 ms/op
     p(95.0000) =      8.634 ms/op
     p(99.0000) =     11.977 ms/op
     p(99.9000) =     23.721 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     35.387 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.647 ±(99.9%) 0.378 ms/op
# Warmup Iteration   2: 9.030 ±(99.9%) 0.077 ms/op
# Warmup Iteration   3: 7.247 ±(99.9%) 0.036 ms/op
Iteration   1: 6.917 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.293 ms/op
                 listUser·p0.50:   6.357 ms/op
                 listUser·p0.90:   9.011 ms/op
                 listUser·p0.95:   10.238 ms/op
                 listUser·p0.99:   14.008 ms/op
                 listUser·p0.999:  30.147 ms/op
                 listUser·p0.9999: 33.395 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   2: 6.885 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.244 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   13.844 ms/op
                 listUser·p0.999:  31.097 ms/op
                 listUser·p0.9999: 37.552 ms/op
                 listUser·p1.00:   37.749 ms/op

Iteration   3: 7.065 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   3.572 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   9.141 ms/op
                 listUser·p0.95:   10.715 ms/op
                 listUser·p0.99:   13.420 ms/op
                 listUser·p0.999:  31.677 ms/op
                 listUser·p0.9999: 35.995 ms/op
                 listUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138031
  mean =      6.955 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2625 
    [ 5.000,  7.500) = 107565 
    [ 7.500, 10.000) = 19465 
    [10.000, 12.500) = 5879 
    [12.500, 15.000) = 1681 
    [15.000, 17.500) = 344 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 85 
    [32.500, 35.000) = 58 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      3.244 ms/op
     p(50.0000) =      6.447 ms/op
     p(90.0000) =      8.897 ms/op
     p(95.0000) =     10.338 ms/op
     p(99.0000) =     13.779 ms/op
     p(99.9000) =     30.834 ms/op
     p(99.9900) =     36.333 ms/op
     p(99.9990) =     37.749 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.431 ± 6.743  ops/ms
ClientPb.existUser                       thrpt       3   6.087 ± 0.553  ops/ms
ClientPb.getUser                         thrpt       3   5.703 ± 1.081  ops/ms
ClientPb.listUser                        thrpt       3   4.707 ± 1.994  ops/ms
ClientPb.createUser                       avgt       3   5.955 ± 5.419   ms/op
ClientPb.existUser                        avgt       3   5.338 ± 2.122   ms/op
ClientPb.getUser                          avgt       3   5.753 ± 4.145   ms/op
ClientPb.listUser                         avgt       3   6.633 ± 1.349   ms/op
ClientPb.createUser                     sample  169553   5.664 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.095           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.980           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.741           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.437           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.452           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.982           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.586           ms/op
ClientPb.existUser                      sample  174096   5.513 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.294           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.930           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.881           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.115           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.870           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.717           ms/op
ClientPb.getUser                        sample  168050   5.706 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.605           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.037           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.634           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.977           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.721           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.882           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.521           ms/op
ClientPb.listUser                       sample  138031   6.955 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.244           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.447           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.338           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.779           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.834           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.333           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.749           ms/op
