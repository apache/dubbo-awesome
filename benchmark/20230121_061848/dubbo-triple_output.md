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
# Warmup Iteration   1: 1.768 ops/ms
# Warmup Iteration   2: 5.549 ops/ms
# Warmup Iteration   3: 8.065 ops/ms
Iteration   1: 8.955 ops/ms
Iteration   2: 9.539 ops/ms
Iteration   3: 9.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.294 ±(99.9%) 5.533 ops/ms [Average]
  (min, avg, max) = (8.955, 9.294, 9.539), stdev = 0.303
  CI (99.9%): [3.761, 14.827] (assumes normal distribution)


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
# Warmup Iteration   1: 2.667 ops/ms
# Warmup Iteration   2: 7.947 ops/ms
# Warmup Iteration   3: 9.703 ops/ms
Iteration   1: 9.954 ops/ms
Iteration   2: 9.660 ops/ms
Iteration   3: 9.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.801 ±(99.9%) 2.687 ops/ms [Average]
  (min, avg, max) = (9.660, 9.801, 9.954), stdev = 0.147
  CI (99.9%): [7.114, 12.488] (assumes normal distribution)


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
# Warmup Iteration   1: 3.179 ops/ms
# Warmup Iteration   2: 8.234 ops/ms
# Warmup Iteration   3: 8.498 ops/ms
Iteration   1: 9.343 ops/ms
Iteration   2: 8.981 ops/ms
Iteration   3: 9.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.180 ±(99.9%) 3.354 ops/ms [Average]
  (min, avg, max) = (8.981, 9.180, 9.343), stdev = 0.184
  CI (99.9%): [5.826, 12.535] (assumes normal distribution)


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
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 7.047 ops/ms
# Warmup Iteration   3: 7.977 ops/ms
Iteration   1: 7.912 ops/ms
Iteration   2: 7.894 ops/ms
Iteration   3: 8.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.958 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (7.894, 7.958, 8.069), stdev = 0.097
  CI (99.9%): [6.195, 9.722] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.282 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.006 ms/op
Iteration   1: 3.366 ±(99.9%) 0.010 ms/op
Iteration   2: 3.444 ±(99.9%) 0.005 ms/op
Iteration   3: 3.555 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.455 ±(99.9%) 1.733 ms/op [Average]
  (min, avg, max) = (3.366, 3.455, 3.555), stdev = 0.095
  CI (99.9%): [1.723, 5.188] (assumes normal distribution)


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
# Warmup Iteration   1: 8.407 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.005 ms/op
Iteration   1: 3.274 ±(99.9%) 0.006 ms/op
Iteration   2: 3.307 ±(99.9%) 0.008 ms/op
Iteration   3: 3.333 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.305 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.274, 3.305, 3.333), stdev = 0.030
  CI (99.9%): [2.766, 3.844] (assumes normal distribution)


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
# Warmup Iteration   1: 10.468 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.004 ms/op
Iteration   1: 3.378 ±(99.9%) 0.009 ms/op
Iteration   2: 3.298 ±(99.9%) 0.006 ms/op
Iteration   3: 3.474 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.383 ±(99.9%) 1.614 ms/op [Average]
  (min, avg, max) = (3.298, 3.383, 3.474), stdev = 0.088
  CI (99.9%): [1.770, 4.997] (assumes normal distribution)


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
# Warmup Iteration   1: 9.941 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.012 ms/op
Iteration   1: 4.120 ±(99.9%) 0.008 ms/op
Iteration   2: 4.005 ±(99.9%) 0.010 ms/op
Iteration   3: 4.134 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.086 ±(99.9%) 1.295 ms/op [Average]
  (min, avg, max) = (4.005, 4.086, 4.134), stdev = 0.071
  CI (99.9%): [2.791, 5.381] (assumes normal distribution)


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
# Warmup Iteration   1: 10.087 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.011 ms/op
Iteration   1: 3.514 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  20.087 ms/op
                 createUser·p0.9999: 23.059 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 3.396 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  23.308 ms/op
                 createUser·p0.9999: 27.361 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   3: 3.554 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  22.676 ms/op
                 createUser·p0.9999: 31.294 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275121
  mean =      3.487 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5662 
    [ 2.500,  5.000) = 262258 
    [ 5.000,  7.500) = 6348 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     20.616 ms/op
     p(99.9900) =     27.639 ms/op
     p(99.9990) =     31.818 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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
# Warmup Iteration   1: 9.527 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.009 ms/op
Iteration   1: 3.418 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  21.264 ms/op
                 existUser·p0.9999: 27.742 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   2: 3.351 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  23.221 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.459 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  9.290 ms/op
                 existUser·p0.9999: 27.418 ms/op
                 existUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281597
  mean =      3.409 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8822 
    [ 2.500,  5.000) = 266849 
    [ 5.000,  7.500) = 4803 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 118 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     12.013 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     28.765 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 8.398 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.011 ms/op
Iteration   1: 3.526 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  21.084 ms/op
                 getUser·p0.9999: 25.970 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   2: 3.344 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  20.360 ms/op
                 getUser·p0.9999: 23.509 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.490 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  21.987 ms/op
                 getUser·p0.9999: 28.508 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278121
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1983 
    [ 2.500,  5.000) = 268633 
    [ 5.000,  7.500) = 6279 
    [ 7.500, 10.000) = 758 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     21.033 ms/op
     p(99.9900) =     27.427 ms/op
     p(99.9990) =     29.302 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 10.989 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.015 ms/op
Iteration   1: 4.119 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   8.383 ms/op
                 listUser·p0.999:  22.589 ms/op
                 listUser·p0.9999: 26.704 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 4.016 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 18.646 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 3.994 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237437
  mean =      4.042 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 228430 
    [ 5.000,  7.500) = 6420 
    [ 7.500, 10.000) = 1589 
    [10.000, 12.500) = 435 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     24.357 ms/op
     p(99.9990) =     27.521 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.294 ± 5.533  ops/ms
ClientPb.existUser                       thrpt       3   9.801 ± 2.687  ops/ms
ClientPb.getUser                         thrpt       3   9.180 ± 3.354  ops/ms
ClientPb.listUser                        thrpt       3   7.958 ± 1.763  ops/ms
ClientPb.createUser                       avgt       3   3.455 ± 1.733   ms/op
ClientPb.existUser                        avgt       3   3.305 ± 0.539   ms/op
ClientPb.getUser                          avgt       3   3.383 ± 1.614   ms/op
ClientPb.listUser                         avgt       3   4.086 ± 1.295   ms/op
ClientPb.createUser                     sample  275121   3.487 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.397           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.616           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.604           ms/op
ClientPb.existUser                      sample  281597   3.409 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.013           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.394           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  278121   3.452 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.264           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.033           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.427           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.721           ms/op
ClientPb.listUser                       sample  237437   4.042 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.470           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.619           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.040           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.357           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
